#### Test 50650278dbf8a2a_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 172867444917; DSPS: 5804952; Offset : -4298618388
,D/AndroidRuntime( 6126): 
D/AndroidRuntime( 6126): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6126): CheckJNI is OFF
D/AndroidRuntime( 6126): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1031): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1940): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1031): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1031): setTaskToReturnTo : TaskRecord{10891cc4 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1031): setTaskToReturnTo : TaskRecord{10891cc4 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1031): AppWindowTokenEx init.. 
E/GBMv2   (  350): DFP En is all cleared set to be enabled
I/ActivityManager( 1031): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6145 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6126): Shutting down VM
V/ActivityManager( 1031): Display changed displayId=0
D/DSDPConnection( 1850): Display #0 changed.
D/SplitWindowPolicy( 1940): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1940): topRunningActivity=ActivityInfo{1492eb53 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1940): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1940): topRunningActivity=ActivityInfo{1b73ac90 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 6145): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 6145): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
I/LibraryLoader( 6145): Loading: webviewchromium
I/LibraryLoader( 6145): Time to load native libraries: 3 ms (timestamps 8087-8090)
I/LibraryLoader( 6145): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6145): Binding Chromium to main looper Looper (main, tid 1) {14e9a06c}
I/LibraryLoader( 6145): Expected native library version number "",actual native library version number ""
I/chromium( 6145): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6145): Initializing chromium process, renderers=0
W/art     ( 6145): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6145): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
V/AudioPolicyService(  335): registerClient() client 0xb1530240, uid 10311
W/chromium( 6145): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6145): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 6145): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
D/BluetoothManagerService( 1031): Message: 20
D/BluetoothManagerService( 1031): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@34b2b32e:true
D/BluetoothAdapter( 6145): 367158837: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 6145): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6145): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6145): Build Date: 12/12/14 금
I/Adreno-EGL( 6145): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6145): Remote Branch: 
I/Adreno-EGL( 6145): Local Patches: 
I/Adreno-EGL( 6145): Reconstruct Branch: 
W/chromium( 6145): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 6145): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 6145): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6145): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6145): CordovaWebView is running on device made by: LGE
W/art     ( 6145): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6145): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 6145): Render dirty regions requested: true
I/OpenGLRenderer( 6145): Initialized EGL, version 1.4
D/OpenGLRenderer( 6145): Enabling debug mode 0
W/ActivityManager( 1031): Activity pause timeout for ActivityRecord{14bd27ad u0 com.test.thalitest/.MainActivity t4}
D/Atlas   ( 6145): Validating map...
D/SplitWindow( 1031): check instance of lgWin Window{2c419178 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/LgDataFeature( 6145): LgDataFeature() Constructor: none
D/LgDataFeature( 6145): LgDataFeature() Constructor Done, null
I/SystemUI[Framework]( 1031): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
D/PhoneStatusBar( 1444): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1444): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1444):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1444): , Keyguard show=false, IME shown=false, Panel expanded=false
W/PhoneWindowManagerEx( 1031): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1031): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1031): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1031): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3d091175,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1031): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/ActivityManager( 1031): Displayed com.test.thalitest/.MainActivity: +722ms (total +820ms)
I/Timeline( 6145): Timeline: Activity_idle id: android.os.BinderProxy@267a46a5 time:178635
I/Timeline( 1031): Timeline: Activity_windows_visible id: ActivityRecord{14bd27ad u0 com.test.thalitest/.MainActivity t4} time:178636
I/chromium( 6145): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6145): 
D/JsMessageQueue( 6145): Set native->JS mode to OnlineEventsBridgeMode
I/chromium( 6145): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 6145): 
E/GBMv2   (  350): DFP En is all cleared set to be enabled
E/GBMv2   (  350): Set value is all cleared set the max
I/GBMv2   (  350): DFP Enabled. Ignore VFP set
D/jxcore_app_log( 6145): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1434887552
,D/JX-Cordova( 6145): jxcore cordova android initializing
W/jxcore-log( 6145): Initializing JXcore engine
W/jxcore-log( 6145): JXcore engine is ready
,W/jxcore-log( 6145): Starting JXcore engine
W/.test.thalitest( 6145): type=1400 audit(0.0:146): avc: denied { ioctl } for path="socket:[8349]" dev="sockfs" ino=8349 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/.test.thalitest( 6145): type=1400 audit(0.0:147): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 6145): type=1400 audit(0.0:148): avc: denied { ioctl } for path="socket:[9434]" dev="sockfs" ino=9434 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 6145): type=1400 audit(0.0:149): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/.test.thalitest( 6145): type=1400 audit(0.0:150): avc: denied { ioctl } for path="socket:[30214]" dev="sockfs" ino=30214 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
I/art     ( 6145): Background sticky concurrent mark sweep GC freed 123793(12MB) AllocSpace objects, 23(7MB) LOS objects, 28% free, 39MB/55MB, paused 1.601ms total 119.633ms
,W/jxcore-log( 6145): Platform android
W/jxcore-log( 6145): 
W/jxcore-log( 6145): Process ARCH arm
W/jxcore-log( 6145): 
,I/jxcore-log( 6145): JXcore Cordova bridge is ready!
I/jxcore-log( 6145): 
W/jxcore-log( 6145): JXcore engine is started
,I/jxcore-log( 6145): Toggling radios to true
I/jxcore-log( 6145): 
,D/BluetoothManagerService( 1031): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1031): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService( 1031): Message: 1
D/BluetoothManagerService( 1031): MESSAGE_ENABLE: mBluetooth = null
D/LocationManagerService( 1031): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1031): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1031): JNI:system_update. Event-4
D/WifiService( 1031): New client listening to asynchronous messages
I/ActivityManager( 1031): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=6234 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,D/WifiServiceImplEx( 1031): setWifiEnabled: true pid=6145, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1031): setWifiEnabled: true pid=6145, uid=10311
E/WifiService( 1031): Invoking mWifiStateMachine.setWifiEnabled
,D/WifiServiceImplEx( 1031): disconnect pid=6145, uid=10311, packageName=com.test.thalitest
E/WifiStateMachine( 1031):  InitialState CMD_START_SUPPLICANT 0 0
I/LGFTMITEM( 1031): [GET_FTM][id=6], offset=12288
D/WifiServiceImplEx( 1031): reconnect pid=6145, uid=10311, packageName=com.test.thalitest
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
I/jxcore-log( 6145): Radios toggled
I/jxcore-log( 6145): 
I/WifiUtil( 1031): gEnableBmps=1
D/BluetoothManagerService( 1031): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 6145): Got Device Bluetooth address: 58:3F:54:73:64:C0
I/jxcore-log( 6145): 
I/jxcore-log( 6145): Perf Test app loaded loaded
I/jxcore-log( 6145): 
,W/ResourcesManager( 6234): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager( 6234): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 6234): Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 6234): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/jxcore-log( 6145): check test folder
I/jxcore-log( 6145): 
,I/jxcore-log( 6145): found test : ./testFindPeers.js
I/jxcore-log( 6145): 
D/BluetoothAdapterApp( 6234): Loading JNI Library
,I/jxcore-log( 6145): found test : ./testSendData.js
I/jxcore-log( 6145): 
D/BluetoothAdapterApp( 6234): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@3418c040 Instance Count = 1
,D/SoftapController(  331): Softap fwReload - Ok
,D/Tethering( 1031): sendTetherStateChangedBroadcast 1, 0, 0
D/CommandListener(  331): Setting iface cfg
D/CommandListener(  331): Trying to bring down wlan0
,D/CommandListener(  331): Clearing all IP addresses on wlan0
D/libc-netbsd(  331): default dns: query_ipv6=0, query_ipv4=0
I/ActivityManager( 1031): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=6260 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/Tethering( 1031): InitialState.processMessage what=4
,D/Tethering( 1031): sendTetherStateChangedBroadcast 0, 0, 0
D/BluetoothAdapterApp( 6234): onCreate
D/DSQN    ( 1031): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,E/WifiHW  ( 1031): Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
E/WifiStateMachine( 1031): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1031): useWiFiOffloading() : false
E/WifiStateMachine( 1031): CONFIG_LGE_WLAN_PATH : true
I/WifiServerServiceExt( 1031): WIFI_STATE_CHANGED_ACTION [2]
V/WfdStateTracker( 1940): WfdStateTracker handleDirectStateChangedEvent: 1
D/WifiMonitor( 1031): startMonitoring(wlan0) with mConnected = false
D/WifiMonitor( 1031): connecting to supplicant
E/WifiHW  ( 1031): Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
W/wpa_supplicant( 6270): type=1400 audit(0.0:151): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/wpa_supplicant( 6270): type=1400 audit(0.0:152): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,D/ProfileConfigQcom( 6234): [BTUI] HeadsetService is supported
D/ProfileConfigQcom( 6234): Adding HeadsetService
D/ProfileConfigQcom( 6234): [BTUI] A2dpService is supported
D/ProfileConfigQcom( 6234): Adding A2dpService
D/ProfileConfigQcom( 6234): [BTUI] HidService is supported
D/ProfileConfigQcom( 6234): Adding HidService
D/ProfileConfigQcom( 6234): [BTUI] HealthService is supported
D/ProfileConfigQcom( 6234): Adding HealthService
D/LGBluetoothFeatureConfig( 6234): isSupportPan() :  mTargetOp=OPEN
D/ProfileConfigQcom( 6234): [BTUI] PanService is supported
D/ProfileConfigQcom( 6234): Adding PanService
D/ProfileConfigQcom( 6234): [BTUI] GattService is supported
D/ProfileConfigQcom( 6234): Adding GattService
D/ProfileConfigQcom( 6234): [BTUI] BluetoothMapService is supported
D/ProfileConfigQcom( 6234): Adding BluetoothMapService
D/ProfileConfigQcom( 6234): [BTUI] HeadsetClientService is NOT supported
I/Choreographer( 6145): Skipped 79 frames!  The application may be doing too much work on its main thread.
I/wpa_supplicant( 6270): Successfully initialized wpa_supplicant
I/chromium( 6145): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/BluetoothManagerService( 1031): Message: 20
D/BluetoothManagerService( 1031): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@358688cb:true
D/BluetoothAdapterState( 6234): make
I/LGFMServiceAdapter( 6234): [FM] LGFMServiceAdapter : create
I/bluedroid-qcom( 6234): init
I/BluetoothAdapterState( 6234): Entering OffState
I/bte_conf( 6234): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
I/wpa_supplicant( 6270): rfkill: Cannot open RFKILL control device
I/bte_conf( 6234): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 6234): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 6234): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
D/BTIF_CORE( 6234): [BTUI] lge_load_bluetooth_address
I/wpa_supplicant( 6270): [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,I/bluedroid-qcom( 6234): get_profile_interface socket
I/bluedroid-qcom( 6234): get_profile_interface map_client
W/bdaddr_loader( 6292): type=1400 audit(0.0:153): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/bdaddr_loader( 6292): type=1400 audit(0.0:154): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/chromium( 6145): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/GKI_LINUX( 6234): gki_task_entry task_id=1 [BTIF] starting
D/lge_bdaddr_loader( 6292): [BTUI] bdaddr_loader ::: START
D/lge_bdaddr_loader( 6292): [BTUI] bluetooth_load_bdaddress
I/LGFTMITEM( 6292): [GET_FTM][id=8], offset=16384
D/BluetoothManagerService( 1031): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService( 1031): Message: 40
D/BluetoothManagerService( 1031): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
W/ResourcesManager( 6260): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6260): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6260): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6260): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
D/BluetoothAdapterProperties( 6234): Address is:58:3F:54:73:64:C0
I/bluedroid-qcom( 6234): config_hci_snoop_log
W/ResourcesManager( 6260): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6260): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/BluetoothManagerService( 1031): Bluetooth Adapter name changed to G3-1
D/lge_bdaddr_loader( 6292): [BTUI] bdaddr to set in property : 58:3F:54:73:64:C0
D/BluetoothManagerService( 1031): Stored Bluetooth name: G3-1
D/BluetoothManagerService( 1031): Calling onBluetoothServiceUp callbacks
,D/BluetoothManagerService( 1031): Broadcasting onBluetoothServiceUp() to 7 receivers.
D/BluetoothAdapterProperties( 6234): Name is: G3-1
V/LGMDMManagerInternal( 6234): Create singleton instance
E/lge_bdaddr_loader( 6292): [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:64:C0
D/lge_bdaddr_loader( 6292): [BTUI] bdaddr_loader ::: END
,D/BluetoothAdapterState( 6234): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 6234): Setting state to 11
I/BluetoothAdapterState( 6234): Bluetooth adapter state changed: 10-> 11
,D/BluetoothManagerService( 1031): Message: 60
D/BluetoothManagerService( 1031): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService( 1031): Bluetooth State Change Intent: 10 -> 11
I/LGBluetoothServiceJni( 6234): classInitNative: succeeds
D/LGBluetoothAPIService( 1940): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
I/[SystemUI]BluetoothHandler( 1444): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
I/wpa_supplicant( 6270): rfkill: Cannot open RFKILL control device
,D/UsbSettingsReceiver( 6260): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6260): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6260): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6260): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/BluetoothBondStateMachine( 6234): make
D/UsbSettingsReceiver( 6260): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/BluetoothAdapterService( 6234): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16bde43b
I/BluetoothBondStateMachine( 6234): StableState(): Entering Off State
D/LGBluetoothServiceAdapter( 6234): [BTUI] check adapter is available - false.
,D/BluetoothAdapterService( 6234): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16bde43b
D/LGBluetoothServiceAdapter( 6234): [BTUI] check adapter is available - true : set adapter available.
D/LGBluetoothSettingsDBObserver( 6234): [BTUI] register observer for LG device name DB
D/UsbSettingsControl( 6260): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6260): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6260): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6260): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6260): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6260): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 6260): [AUTORUN] setTetherStatus() : status=false
I/ActivityManager( 1031): Killing 5854:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,E/BluetoothAdapterService( 6234): File transfer profiles supported!!
I/wpa_supplicant( 6270): [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,I/wpa_supplicant( 6270): p2p0: CTRL-EVENT-AVOID-FREQ ranges=
I/wpa_supplicant( 6270): wlan0: CTRL-EVENT-SCAN-STARTED 
V/BluetoothPbapReceiver( 6234): PbapReceiver onReceive 
,V/BluetoothPbapReceiver( 6234): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6234): ***********state = 11
W/libprocessgroup( 1031): failed to open /acct/uid_10008/pid_5854/cgroup.procs: No such file or directory
E/BluetoothAdapterService( 6234): File transfer profiles supported!!
,D/BluetoothHeadset( 1850): Proxy object connected
D/BluetoothHeadset( 1031): Proxy object connected
D/UsbSettingsReceiver( 6260): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6260): [AUTORUN] sys.usb.config = ptp_only,adb
D/BluetoothHeadset( 1850): Proxy object connected
D/UsbSettingsReceiver( 6260): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6260): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/BluetoothHeadset( 1850): Proxy object connected
D/HeadsetService( 6234): Received start request. Starting profile...
D/UsbSettingsReceiver( 6260): [AUTORUN] onReceive() : app userid = 0, current userid = 0
I/LGBluetoothHeadsetServiceJni( 6234): classInitNative: succeeds
D/LGBluetoothHfpAdapter( 6234): Version 1.6
,D/LGBluetoothFeatureConfig( 6234): isPrivacyLogsEnabled : true
I/BluetoothHeadsetServiceJni( 6234): classInitNative: succeeds
,D/HeadsetStateMachine( 6234): make
I/ActivityManager( 1031): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6299 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,D/UsbSettingsControl( 6260): [AUTORUN] getUsbConnected() : connected=true
,D/UsbSettingsReceiver( 6260): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 6260): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6260): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6260): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 6260): [AUTORUN] setTetherStatus() : status=false
E/BluetoothAdapterService( 6234): File transfer profiles supported!!
D/LgDataFeature( 6234): LgDataFeature() Constructor: none
D/LgDataFeature( 6234): LgDataFeature() Constructor Done, null
I/ActivityManager( 1031): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6316 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,D/HeadsetStateMachine( 6234): max_hf_connections = 1
I/bluedroid-qcom( 6234): get_profile_interface handsfree
E/BluetoothAdapterService( 6234): File transfer profiles supported!!
V/ToneGenerator( 6234): ToneGenerator constructor: streamType=8, volume=1.000000
V/AudioPolicyService(  335): registerClient() client 0xb1004ce0, uid 1002
,V/AudioPolicyManager(  335): getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  335): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  335): getOutput() returns output 2
V/AudioSystem( 6234): getOutputSamplingRate() no output descriptor for output 2 in gOutputs
V/AudioFlinger(  335): registerClient() client 0xb123eb20, pid 6234
V/AudioSystem(  335): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  335): ioConfigChanged() opening already existing output! 2
V/ToneGenerator( 6234): Create Track: 0xb4928a80
V/AudioSystem( 1031): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1031): ioConfigChanged() opening already existing output! 2
V/AudioTrack( 6234): set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
V/AudioTrack( 6234): set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
V/AudioSystem( 1444): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1444): ioConfigChanged() opening already existing output! 2
V/AudioPolicyManager(  335): getOutputForAttr() usage=3, content=4, tag= flags=00000000
V/AudioPolicyManager(  335): getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  335): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  335): getOutput() returns output 2
V/AudioSystem( 1850): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1850): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 3226): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 3226): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 6234): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 6234): ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
V/AudioSystem(  335): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem(  335): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1444): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1444): ioConfigChanged() opening already existing output! 4
I/AudioFlinger(  335): isAudioPlaybackHookOn() false
V/AudioSystem( 1031): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1031): ioConfigChanged() opening already existing output! 4
V/AudioPolicyManager(  335): getOutputForAttr() usage=3, content=4, tag= flags=00000000
V/AudioPolicyManager(  335): getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
V/AudioPolicyManagerEx(  335): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  335): getOutput() returns output 2
V/AudioSystem( 6234): getLatency() output 2, latency 50
V/AudioSystem( 6234): getFrameCount() output 2, frameCount 960
V/AudioTrack( 6234): createTrack_l() output 2 afLatency 50
V/AudioSystem( 6234): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 6234): ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
V/AudioFlinger(  335): [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
V/AudioFlinger(  335): [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
V/AudioSystem( 3226): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 3226): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1850): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1850): ioConfigChanged() opening already existing output! 4
V/AudioFlinger(  335): [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
V/AudioFlinger(  335): [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
V/AudioFlinger(  335): createTrack() lSessionId: 16
V/AudioTrack( 6234): AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
V/AudioFlinger(  335): acquiring 16 from 6234, for 6234
V/AudioFlinger(  335):  added new entry for 16
V/ToneGenerator( 6234): ToneGenerator INIT OK, time: 182676
D/BluetoothAdapterService( 6234): getAdapterService() - returning com.android.bluetooth.btse,rvice.AdapterService@16bde43b
D/BluetoothAdapterService( 6234): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16bde43b
D/BluetoothA2dp( 1031): Proxy object connected
D/A2dpService( 6234): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 6234): classInitNative: succeeds
V/Avrcp   ( 6234): make
D/Avrcp   ( 6234): [BTUI] Use Native AVRCP : init jni
I/bluedroid-qcom( 6234): get_profile_interface avrcp
E/BluetoothAdapterService( 6234): File transfer profiles supported!!
D/HeadsetStateMachine( 6234): Enter Disconnected: -2, size: 0
D/HeadsetPhoneState( 6234): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 6234): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetStateMachine( 6234): [BTUI] change sampling rate to 8000 when device is disconnected
V/AudioFlinger(  335): setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6234
D/audio_hw_primary(  335): adev_set_parameters: enter: bt_samplerate=8000
V/voice   (  335): voice_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  335): voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  335): voice_extn_compress_voip_set_parameters: exit
V/voice   (  335): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  335): LGE_platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  335): platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  335): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  335): lge_platform_set_loopback_parameters: enter: 
V/audio_hw_primary(  335): adev_set_parameters: exit with code(0)
E/audio_a2dp_hw(  335): adev_set_parameters: ERROR: set param called even when stream out is null
V/ToneGenerator( 6234): ToneGenerator destructor
V/ToneGenerator( 6234): stopTone
V/ToneGenerator( 6234): Delete Track: 0xb4928a80
V/AudioPolicyService(  335): AudioCommandThread() adding release output 2
V/AudioPolicyService(  335): inserting command: 6 at index 0, num commands 0
V/AudioFlinger(  335): PlaybackThread::Track destructor
V/AudioPolicyService(  335): AudioCommandThread() waking up
V/AudioFlinger(  335): removeClient_l() pid 6234, calling pid 335
V/AudioPolicyService(  335): AudioCommandThread() processing release output 2
V/AudioPolicyManager(  335): releaseOutput() 2
V/AudioPolicyService(  335): AudioCommandThread() going to sleep
V/AudioTrack( 6234): ~AudioTrack, releasing session id from 6234 on behalf of 6234
V/AudioFlinger(  335): releasing 16 from 6234 for 6234
V/AudioFlinger(  335):  decremented refcount to 0
V/AudioFlinger(  335): purging stale effects
V/AudioManager( 6234): registerRemoteController: size of Media player list: 0
E/AudioManager( 6234): No RCC entry present to update
E/RemoteController( 6234): Cannot set synchronization mode on an unregistered RemoteController
,I/BluetoothAvrcpQcomServiceJni( 6234): classInitQcomNative: succeeds
D/LGBluetoothAvrcpQcomAdapter( 6234): [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
I/BluetoothAvrcpQcomServiceJni( 6234): initQcomNative: succeeds
E/BluetoothAdapterService( 6234): File transfer profiles supported!!
D/LGBluetoothAvrcpQcomAdapter( 6234): [BTUI] [+] updateMediaPlayerInfo
E/BluetoothAdapterService( 6234): File transfer profiles supported!!
,V/LGMDMManager( 6234): Create singleton instance
I/BluetoothAdapterState( 6234): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,V/SIM_STK ( 1031): Menu title from STK is T-Mobile
V/SIM_STK ( 1031): Menu title from STK is T-Mobile
,I/art     ( 1031): Explicit concurrent mark sweep GC freed 22997(1173KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 1.700ms total 104.564ms
,W/ActivityManager( 1031): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
D/LGBluetoothAvrcpQcomAdapter( 6234): [BTUI] installed app name: Music
E/ActivityThread( 6299): Failed to find provider info for com.lge.lgaccount.provider
,W/LG Account v2.2( 6299): No ProfileInfo entries
I/LG Account v2.2( 6299): isEnabled: false
I/Feature ( 6299): [Lifetracker]ver: 4.21.112(40211120)
I/Feature ( 6299): [Lifetracker]Country: EU
I/Feature ( 6299): [Lifetracker]Operator: OPEN
I/Feature ( 6299): [Lifetracker]Ranking support: false
I/Feature ( 6299): [Lifetracker]Comfort support: false
I/Feature ( 6299): [Lifetracker]Accessory: true
I/Feature ( 6299): [Lifetracker]Health device: true
D/LGBluetoothAvrcpQcomAdapter( 6234): [BTUI] installed app name: Google Play Music
I/Feature ( 6299): [Lifetracker]Extra Pedometer: false
I/Feature ( 6299): [Lifetracker]Blood glucose device: false
D/LGBluetoothAvrcpQcomAdapter( 6234): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 6234): [BTUI]          displayName: Music
I/Feature ( 6299): [Lifetracker]Device Number: 3
D/LGBluetoothAvrcpQcomAdapter( 6234): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 6234): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6234): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 6234): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6234): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 6234): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6234): [BTUI] [-] updateMediaPlayerInfo
I/BluetoothA2dpServiceJni( 6234): classInitNative
I/BluetoothA2dpServiceJni( 6234): classInitNative: succeeds
D/A2dpStateMachine( 6234): make
I/bluedroid-qcom( 6234): get_profile_interface a2dp
I/GKI_LINUX( 6234): gki_task_entry task_id=2 [A2DP-MEDIA] starting
,I/LGBluetoothA2dpServiceJni( 6234): classInitNative: succeeds
I/LGBluetoothA2dpAdapter( 6234): [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
D/BluetoothAdapterService( 6234): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16bde43b
D/HeadsetStateMachine( 6234): Proxy object connected
D/A2dpStateMachine( 6234): Enter Disconnected: -2
D/LGBluetoothHfpAdapter( 6234): [BTUI] queryPhoneState
D/LGBluetoothHfpAdapter( 6234): Try to query the phonestate on bind
D/BluetoothPhoneService.BluetoothLTECall( 1850):  call mBluetoothHeadset.phoneStateChanged()
I/BluetoothHidServiceJni( 6234): classInitNative: succeeds
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
,D/HidService( 6234): Received start request. Starting profile...
I/bluedroid-qcom( 6234): get_profile_interface hidhost
D/BluetoothAdapterService( 6234): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16bde43b
I/BluetoothHealthServiceJni( 6234): classInitNative: succeeds
D/HealthService( 6234): Received start request. Starting profile...
I/bluedroid-qcom( 6234): get_profile_interface health
I/LGBluetoothHealthServiceJni( 6234): classInitNative: succeeds
D/BluetoothAdapterService( 6234): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16bde43b
D/BluetoothAdapterService( 6234): Profile still not running:com.android.bluetooth.gatt.GattService
D/HeadsetStateMachine( 6234): Disconnected process message: 10, size: 0
,I/BluetoothPanServiceJni( 6234): classInitNative(L105): succeeds
D/HeadsetPhoneState( 6234): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 6234): Disconnected process message: 11, size: 0
D/PanService( 6234): Received start request. Starting profile...
D/BluetoothPanServiceJni( 6234): initializeNative(L110): pan
I/bluedroid-qcom( 6234): get_profile_interface pan
E/wpa_supplicant( 6270): USIM:  scard_init function
I/wpa_supplicant( 6270): Trying to associate with SSID 'NG700'
I/LGBluetoothPanAdapter( 6234): [BTUI] getInstance : create [LGBluetoothPanAdapter]
D/BluetoothAdapterService( 6234): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16bde43b
D/BluetoothPermissionRequest( 6260): onReceive
D/LGBluetoothFeatureConfig( 6260):  get() - isFeatureLoaded : false
,I/BtGatt.JNI( 6234): classInitNative(L901): classInitNative: Success!
D/BtGatt.DebugUtils( 6234): handleDebugAction() action=null
D/BtGatt.GattService( 6234): Received start request. Starting profile...
D/BtGatt.GattService( 6234): start()
I/bluedroid-qcom( 6234): get_profile_interface gatt
D/BtGatt.AdvertiseManager( 6234): advertise manager created
I/ActivityManager( 1031): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6351 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,W/FormManager( 6316): Network not available. Please check & try again.
D/BluetoothAdapterService( 6234): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16bde43b
D/BluetoothAdapterService( 6234): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16bde43b
I/LGBluetoothMapAdapter( 6234): [BTUI] getInstance : create [LGBluetoothMapAdapter]
V/BluetoothMapService( 6234): BluetoothMapBinder()
D/BluetoothMapService( 6234): Received start request. Starting profile...
D/BluetoothMapService( 6234): start()
D/BluetoothManagerService( 1031): Message: 20
D/BluetoothManagerService( 1031): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1a3e6320:true
D/BluetoothMapEmailSettingsLoader( 6234): Found 0 applications
,D/BluetoothMapEmailAppObserver( 6234): createReceiver()
D/BluetoothMapEmailAppObserver( 6234): initObservers()
D/BluetoothMapEmailAppObserver( 6234): getEnabledAccountItems()
D/BluetoothAdapterService( 6234): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16bde43b
V/FormManager( 6316): Network unavailable.
D/LGBluetoothResetSettingReceiver( 6260): return without doing reset settings.
I/ActivityManager( 1031): Killing 5483:com.lge.appbox.client/u0a11 (adj 15): empty #17
D/BluetoothAdapterService( 6234): Profile still not running:com.android.bluetooth.gatt.GattService
,D/BluetoothAdapterService( 6234): Profile still not running:com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 6234): Profile still not running:com.android.bluetooth.gatt.GattService
V/PanService( 6234): [BTUI] SIM Extra State :ABSENT
D/BluetoothAdapterService( 6234): Profile still not running:com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 6234): Profile still not running:com.android.bluetooth.map.BluetoothMapService
,V/BluetoothMapService( 6234): Handler(): got msg=1
D/BluetoothAdapterState( 6234): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid-qcom( 6234): enable
I/bt_hci_bdroid( 6234): init
I/GKI_LINUX( 6234): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 6234): btu_task pending for preload complete event
I/bt_vendor( 6234): bt-vendor : init
I/bt_vendor( 6234): bt-vendor : get_bt_soc_type
E/bt_vendor( 6234): get_bt_soc_type: Failed to get soc type
I/bt_vendor( 6234): init: Local BD Address : c0:64:73:54:3f:58
D/bt_userial_mct( 6234): userial_init
D/bt_hci_bdroid( 6234): set_power 1
I/bt_vendor( 6234): bt-vendor : BT_VND_OP_POWER_CTRL: On
I/bt_vendor( 6234): Starting hciattach daemon
I/bt_vendor( 6234): try to set true
,W/sh      ( 6374): type=1400 audit(0.0:155): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/sh      ( 6374): type=1400 audit(0.0:156): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/wpa_supplicant( 6270): wlan0: Associated with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 6270): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 6270): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
,I/qcom-bluetooth( 6375): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
W/libprocessgroup( 1031): failed to open /acct/uid_10011/pid_5483/cgroup.procs: No such file or directory
V/FormManager( 6316): Network unavailable.
D/LGBluetoothOppAdapter( 6234): [BTUI] getInstance : create [LGBluetoothOppAdapter]
,D/Tethering( 1031): sendTetherStateChangedBroadcast 1, 0, 0
,I/ActivityManager( 1031): Killing 5504:com.android.contacts/u0a19 (adj 15): empty #17
I/qcom-bluetooth( 6381): /system/etc/init.qcom.bt.sh: Transport : smd 
,D/PCSuite ( 6351): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/qcom-bluetooth( 6384): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
I/qcom-bluetooth( 6386): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,W/libprocessgroup( 1031): failed to open /acct/uid_10019/pid_5504/cgroup.procs: No such file or directory
V/BluetoothFtpReceiver( 6234): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6234): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 6234): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 6234): SapReceiver onReceive 
V/BluetoothSapReceiver( 6234): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6234):  Bluetooth Adapter state = 11
I/qcom-bluetooth( 6387): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
I/qcom-bluetooth( 6388): /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,V/WiFiOffLoadBroadcast( 6260): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
D/WifiService( 1031): New client listening to asynchronous messages
,I/qcom-bluetooth( 6389): /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
I/ActivityManager( 1031): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6394 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/libmdmdetect( 6393): ESOC framework not supported
E/Diag_Lib( 6393):  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,D/LgDataFeature( 6260): LgDataFeature() Constructor: none
D/LgDataFeature( 6260): LgDataFeature() Constructor Done, null
D/WiFiOffLoadUpdatePriority( 6260): remove : truetruefalse
D/bthci_qcomm_linux( 6393): [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:64:C0)
D/bthci_qcomm_common( 6393): [BTUI] bt_hci_qcomm_init:
D/bthci_qcomm_common( 6393): [BTUI]     BDADDR: 58:3F:54:73:64:C0
D/bthci_qcomm_common( 6393): [BTUI]     BR/EDR: Class 1
D/bthci_qcomm_common( 6393): [BTUI]     LE: Class 2
D/bthci_qcomm_common( 6393): [BTUI]     Ref Clock: 32M
D/btqsocnvmtags( 6393): [BTUI] init_riva_entries: set NORMAL power settings
,D/WiFiOffLoadUpdatePriority( 6260): remove2
,V/WiFiOffLoadSharedPrefsUtils( 6260): save wifi state
V/WiFiOffLoadSharedPrefsUtils( 6260): save remove
D/WiFiOffLoadBroadcast( 6260): mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
D/WiFiOffLoadBroadcast( 6260): S: false, R: true
W/ResourcesManager( 6394): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/UsbSettingsReceiver( 6260): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6260): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6260): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6260): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6260): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 6260): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6260): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6260): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6260): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6260): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6260): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 6260): [AUTORUN] setTetherStatus() : status=false
,I/ActivityManager( 1031): Killing 5881:com.lge.email/u0a23 (adj 15): empty #17
W/libprocessgroup( 1031): failed to open /acct/uid_10023/pid_5881/cgroup.procs: No such file or directory
,E/WifiStateMachine( 1031):  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
E/WifiStateMachine( 1031):  SupplicantStartingState CMD_START_DRIVER 0 0
E/WifiStateMachine( 1031):  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
I/ActivityManager( 1031): Killing 5530:com.android.gallery3d/u0a27 (adj 15): empty #17
E/WifiStateMachine( 1031):  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
E/WifiStateMachine( 1031):  SupplicantStartingState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1031):  DefaultState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1031):  SupplicantStartingState CMD_RECONNECT 0 0
,E/WifiStateMachine( 1031):  DefaultState CMD_RECONNECT 0 0
E/WifiStateMachine( 1031):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1031):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1031):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1031):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1031):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1031):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1031):  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
D/WifiNative-wlan0( 1031): doString: [DRIVER MACADDR]
D/WifiNative-wlan0( 1031):    returned Macaddr = c4:9a:02:7b:60:ac
D/WifiStateMachine( 1031): MAC Addr from driver = c4:9a:02:7b:60:ac
D/WifiOffDelayIfNotUsed( 1031): setPowerSaveActivated(false)
,D/AuthorizationBluetoothService( 2110): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/WifiStateMachine( 1031): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1031): useWiFiOffloading() : false
E/WifiStateMachine( 1031): CONFIG_LGE_WLAN_PATH : true
W/libprocessgroup( 1031): failed to open /acct/uid_10027/pid_5530/cgroup.procs: No such file or directory
I/rmt_storage(  328): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  328): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  328): wakelock acquired: 1, error no: 42
I/rmt_storage(  328): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236806912)
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiNative-wlan0( 1031): doBoolean: SET update_config 1
D/WifiNative-wlan0( 1031): SET update_config 1: returned true
D/WifiConfigStore( 1031): Loading config and enabling all networks 
D/WifiNative-wlan0( 1031): doString: [LIST_NETWORKS]
D/WifiNative-wlan0( 1031):    returned network id / ssid / bssid / flags 0	NG700	any	[CURRENT]
,D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WfdService( 1940): Waiting for WifiP2p enabling
E/WifiConfigStore( 1031): readNetworkVariablesFromSupplicantFile key=psk
E/WifiConfigStore( 1031): readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
E/WifiConfigStore( 1031): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
I/WifiServerServiceExt( 1031): WIFI_STATE_CHANGED_ACTION [3]
,D/WifiStateMachine( 1031): enableVerboseLogging : level 2
D/WifiNative-wlan0( 1031): doBoolean: SET device_name g3_global_com
D/WifiNative-wlan0( 1031): SET device_name g3_global_com: returned true
D/WifiNative-wlan0( 1031): doBoolean: SET manufacturer LGE
D/WifiNative-wlan0( 1031): SET manufacturer LGE: returned true
D/WifiNative-wlan0( 1031): doBoolean: SET model_name LG-D855
I/WifiServerServiceExt( 1031): batteryPsActivateMsgHandler : state:0 event:3
D/WifiNative-wlan0( 1031): SET model_name LG-D855: returned true
D/WifiNative-wlan0( 1031): doBoolean: SET model_number LG-D855
D/WifiNative-wlan0( 1031): SET model_number LG-D855: returned true
D/WifiNative-wlan0( 1031): doBoolean: SET serial_number LGD8553bed2d08
D/WifiNative-wlan0( 1031): SET serial_number LGD8553bed2d08: returned true
D/WifiNative-wlan0( 1031): doBoolean: SET config_methods physical_display virtual_push_button
D/WifiNative-wlan0( 1031): SET config_methods physical_display virtual_push_button: returned true
D/WifiNative-wlan0( 1031): doBoolean: SET device_type 10-0050F204-5
D/WifiNative-wlan0( 1031): SET device_type 10-0050F204-5: returned true
D/WfdsService( 1940): Supplicant Connection state is changed : true
D/WfdsService( 1940): DefaultState - WIFI_SUPPLICANT_CONNECTED
D/WfdsService( 1940): Set the WFDS Monitor: true
D/WifiStateMachine( 1031): Setting OUI to DA-A1-19
D/WfdsMonitor( 1940): WfdsMonitorThread create
D/WifiNative-wlan0( 1031): doBoolean: SCAN_INTERVAL 120
D/WfdsMonitor( 1940): WFDS Monitor is created and started
D/WfdsService( 1940): WiFi: Supplicant connection re-established
D/WifiNative-wlan0( 1031): SCAN_INTERVAL 120: returned true
D/WifiNative-HAL( 1031): Setting external_sim to 1
D/WifiNative-wlan0( 1031): doBoolean: SET external_sim 1
,D/WifiNative-wlan0( 1031): SET external_sim 1: returned true
I/WifiNative-HAL( 1031): startHal
E/wifi    ( 1031): getStaticLongField sWifiHalHandle 0x9899e8dc
E/CtrlSupplicant( 1940): Access OK "@android:wpa_wlan0"
E/WifiHAL ( 1031): Could not connect handle
D/wifi    ( 1031): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x402126
I/WifiNative-HAL( 1031): Could not start hal
D/WifiStateMachine( 1031): Setting OUI to DA-A1-19
I/WifiNative-HAL( 1031): startHal
E/wifi    ( 1031): getStaticLongField sWifiHalHandle 0x9899e85c
E/WifiHAL ( 1031): Could not connect handle
D/wifi    ( 1031): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x4020ba
I/WifiNative-HAL( 1031): Could not start hal
E/CtrlSupplicant( 1940): Succeed to open control connection
D/WifiNative-wlan0( 1031): doBoolean: STA_AUTOCONNECT 1
E/CtrlSupplicant( 1940): Succeed to open monitor connection
D/WfdsMonitor( 1940): Supplicant connection established
D/WfdsService( 1940): Connected to the supplicant for wfds
D/WifiNative-wlan0( 1031): STA_AUTOCONNECT 1: returned true
D/WifiNative-wlan0( 1031): doBoolean: DRIVER BTCOEXSCAN-STOP
I/wpa_supplicant( 6270): wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
D/WifiNative-wlan0( 1031): DRIVER BTCOEXSCAN-STOP: returned true
D/PCSuite ( 6351): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/WifiNative-wlan0( 1031): doBoolean: DRIVER RXFILTER-STOP
I/wpa_supplicant( 6270): wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
D/WifiNative-wlan0( 1031): DRIVER RXFILTER-STOP: returned true
D/WifiNative-wlan0( 1031): doBoolean: DRIVER RXFILTER-REMOVE 3
I/wpa_supplicant( 6270): wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
D/WifiNative-wlan0( 1031): DRIVER RXFILTER-REMOVE 3: returned true
D/WifiNative-wlan0( 1031): doBoolean: DRIVER RXFILTER-START
I/wpa_supplicant( 6270): wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
D/WifiHS20( 1031): hidePasspointNotification off =false
D/WifiNative-wlan0( 1031): DRIVER RXFILTER-START: returned true
D/WifiNative-wlan0( 1031): doBoolean: DRIVER RXFILTER-STOP
I/wpa_supplicant( 6270): wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
D/WifiNative-wlan0( 1031): DRIVER RXFILTER-STOP: returned true
D/WifiNative-wlan0( 1031): doBoolean: DRIVER RXFILTER-REMOVE 2
I/wpa_supplicant( 6270): android_multicast_filter_startstop : multicast filter set
I/StatusBar.NetworkController( 1444): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1444): mWifiConnected = false, mWifiLevel = 0
D/WifiNative-wlan0( 1031): DRIVER RXFILTER-REMOVE 2: returned true
D/WifiNative-wlan0( 1031): doBoolean: DRIVER RXFILTER-START
I/wpa_supplicant( 6270): wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
,W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiNative-wlan0( 1031): DRIVER RXFILTER-START: returned true
E/WifiNative: ( 1031): [183,301,085 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
D/WifiNative-wlan0( 1031): doBoolean: RECONNECT
D/WifiNative-wlan0( 1031): RECONNECT: returned true
D/WifiNative-wlan0( 1031): doString: [STATUS]
D/WifiMonitor( 1031): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiNative-wlan0( 1031):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
D/WifiNative-wlan0( 1031): doBoolean: DRIVER SETSUSPENDMODE 1
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=0 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/wpa_supplicant( 6270): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1031): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1031): doBoolean: SET ps 1
D/WifiNative-wlan0( 1031): SET ps 1: returned true
V/WiFiOffLoadBroadcast( 6260): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
D/LGWifiP2pService( 1031): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService( 1031): SCAN_AVAILABLE : 3
D/WifiScanningService( 1031): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL( 1031): startHal
E/wifi    ( 1031): getStaticLongField sWifiHalHandle 0x97b8099c
E/WifiHAL ( 1031): Could not connect handle
D/wifi    ( 1031): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x3020b2
I/WifiNative-HAL( 1031): Could not start hal
D/RttService( 1031): SCAN_AVAILABLE : 3
D/RttService( 1031): DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiScanningService( 1031): could not start HAL
E/WifiStateMachine( 1031):  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
D/CommandListener(  331): Setting iface cfg
D/CommandListener(  331): Trying to bring up p2p0
D/WifiMonitor( 1031): startMonitoring(p2p0) with mConnected = true
D/LGWifiP2pService( 1031): P2pEnablingState
D/LGWifiP2pService( 1031): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): P2p socket connection successful
D/LGWifiP2pService( 1031): P2pEnabledState
,D/LGWifiP2pService( 1031): sending p2p connection changed broadcast
D/WifiNative-p2p0( 1031): doBoolean: SET persistent_reconnect 1
V/FormManager( 6316): Network unavailable.
D/WiFiOffLoadUpdatePriority( 6260): remove : truetruetrue
,V/WfdStateTracker( 1940): WfdStateTracker handleDirectStateChangedEvent: 2
D/WfdsService( 1940): WifiP2pState is changed : true
D/WifiService( 1031): New client listening to asynchronous messages
D/WfdsService( 1940): Receive the WFDS_ENABLE Method
D/WfdsService( 1940): Set the WFDS Monitor: true
E/WifiStateMachine( 1031):  DisconnectedState CMD_START_DRIVER 0 0
D/WfdsService( 1940): Connected to the supplicant for wfds
D/WfdsJNI ( 1940): doCommand: WFDS_SET TRUE
I/wpa_supplicant( 6270): WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
E/WifiStateMachine( 1031):  ConnectModeState CMD_START_DRIVER 0 0
D/WifiNative-p2p0( 1031): SET persistent_reconnect 1: returned true
D/WfdsJNI ( 1940): doCommand: WFDS_GET_MAC_ADDRESS
D/WifiNative-p2p0( 1031): doBoolean: SET device_name G3-1
I/wpa_supplicant( 6270): WFDS: wfds_supplicant_wfds_cmd: cmd = GET_MAC_ADDRESS
E/WifiStateMachine( 1031):  DriverStartedState CMD_START_DRIVER 0 0
D/WfdsJNI ( 1940): doCommand: IFNAME=wlan0 GET_CAPABILITY channels
D/WfdsService( 1940): selectPreferredScanChannel [36]
D/WfdsService( 1940): STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7b:60:ac
E/WifiStateMachine( 1031):  DisconnectedState what:132106 1 0
D/WifiNative-p2p0( 1031): SET device_name G3-1: returned true
D/LGWifiP2pService( 1031): [LGE_P2P] initializeP2pSettings() check postfix
D/LGWifiP2pService( 1031): before postfix = G3-1
D/WifiServerServiceExt( 1031): postfix byte check : 4
D/LGWifiP2pService( 1031): after postfix = G3-1
D/WifiNative-p2p0( 1031): doBoolean: SET p2p_ssid_postfix -G3-1
E/WifiStateMachine( 1031):  ConnectModeState what:132106 1 0
D/WifiNative-p2p0( 1031): SET p2p_ssid_postfix -G3-1: returned true
D/WifiNative-p2p0( 1031): doBoolean: SET device_type 10-0050F204-5
D/WifiNative-p2p0( 1031): SET device_type 10-0050F204-5: returned true
E/WifiStateMachine( 1031):  DriverStartedState what:132106 1 0
D/WifiNative-p2p0( 1031): doBoolean: SET config_methods virtual_push_button physical_display keypad
I/WifiServerServiceExt( 1031): setWifiDualbandAPConnection band : 1
E/wpa_supplicant( 6270): nWIFIDualbandAPConnection: 1
E/WifiStateMachine( 1031):  DisconnectedState what:132096 -100 0
V/FormManager( 6316): Network unavailable.
D/WfdsService( 1940): WIFI_P2P_CONNECTION_CHANGED_ACTION
E/WifiStateMachine( 1031):  ConnectModeState what:132096 -100 0
E/WifiStateMachine( 1031):  DriverStartedState what:132096 -100 0
D/WfdsService( 1940): isConnected: false
I/WifiServerServiceExt( 1031): set CMD_DISCONNECT_RSSI_LVL : -100
E/wpa_supplicant( 6270): disconnect_rssi_lvl: -100
D/WifiNative-p2p0( 1031): SET config_methods virtual_push_button physical_display keypad: returned true
E/WifiStateMachine( 1031):  DisconnectedState CMD_SET_COUNTRY_CODE 1 0 cz
E/WifiStateMachine( 1031):  ConnectModeState CMD_SET_COUNTRY_CODE 1 0 cz
D/WifiNative-p2p0( 1031): doBoolean: P2P_SET conc_pref p2p
E/WifiStateMachine( 1031):  DriverStartedState CMD_SET_COUNTRY_CODE 1 0 cz
D/WifiNative-wlan0( 1031): doBoolean: DRIVER COUNTRY CZ
D/WifiNative-p2p0( 1031): P2P_SET conc_pref p2p: returned true
D/WifiNative-HAL( 1031): p2pGetDeviceAddress
D/WifiNative-HAL( 1031): p2pGetDeviceAddress returning 02:9a:02:7b:60:ac
,D/LGWifiP2pService( 1031): DeviceAddress: 02:9a:02:7b:60:ac
D/WifiNative-p2p0( 1031): doBoolean: P2P_FLUSH
I/wpa_supplicant( 6270): wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
I/wpa_supplicant( 6270): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
I/wpa_supplicant( 6270): [LGE_PATCH] driver_cmd() country:CZ
I/wpa_supplicant( 6270): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
I/wpa_supplicant( 6270): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiNative-wlan0( 1031): DRIVER COUNTRY CZ: returned true
D/WifiMonitor( 1031): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=1 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1031): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1031): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
D/WifiMonitor( 1031): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1031): WifiMonitor:p2p0 cnt=2 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WfdsMonitor( 1940): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WfdsMonitor( 1940): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiStateMachine( 1031):  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine( 1031):  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
I/WfdStateTracker( 1940): handleP2pThisDeviceChanged
D/WfdsService( 1940): WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
E/WifiStateMachine( 1031):  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
D/WifiNative-wlan0( 1031): doBoolean: DRIVER SETBAND 0
D/WfdsService( 1940): Update P2p Interface State: 3
W/FormManager( 6316): Network not available. Please check & try again.
E/WifiMonitor( 1031): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1031): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
I/wpa_supplicant( 6270): wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
D/WifiMonitor( 1031): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
I/wpa_supplicant( 6270): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
E/WifiMonitor( 1031): WifiMonitor:p2p0 cnt=3 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1031): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1031): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiMonitor( 1031): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=4 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
E/WifiMonitor( 1031): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
E/WifiMonitor( 1031): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
D/WifiNative-wlan0( 1031): DRIVER SETBAND 0: returned true
D/WifiNative-wlan0( 1031): doBoolean: BSS_FLUSH 0
D/WifiNative-p2p0( 1031): P2P_FLUSH: returned true
D/WifiNative-p2p0( 1031): doBoolean: P2P_SERVICE_FLUSH
D/WifiNative-wlan0( 1031): BSS_FLUSH 0: returned true
D/WifiNative-wlan0( 1031): doBoolean: SCAN
I/wpa_supplicant( 6270): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1031): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=5 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1031): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1031): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-wlan0( 1031): SCAN: returned true
D/WifiNative-p2p0( 1031): P2P_SERVICE_FLUSH: returned true
E/WifiStateMachine( 1031):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 0 0 rt=183334  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WifiNative-p2p0( 1031): doString: [LIST_NETWORKS]
D/WifiNative-p2p0( 1031):    returned network id / ssid / bssid / flags
D/WifiNative-p2p0( 1031): doBoolean: SAVE_CONFIG
E/WifiStateM,achine( 1031):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 0 0 rt=183336  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
I/StatusBar.NetworkController( 1444): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1444): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1031):  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1031):  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1031):  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1031):  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1031):  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/WifiServerServiceExt( 1031): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1031): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1031):  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1031):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1031):  DisconnectedState CMD_SAVE_CONFIG uid=1000 0 0
E/WifiStateMachine( 1031):  ConnectModeState CMD_SAVE_CONFIG uid=1000 0 0
D/WifiNative-wlan0( 1031): doBoolean: SAVE_CONFIG
I/rmt_storage(  328): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  328): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
I/rmt_storage(  328): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236806912) wakelock released: 1, error no: 0
I/rmt_storage(  328): 
I/rmt_storage(  328): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
E/Diag_Lib(  880): [IMS_FATAL]| 3347 | 905 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
D/WifiNative-p2p0( 1031): SAVE_CONFIG: returned true
D/LGWifiP2pService( 1031): sending p2p persistent groups changed broadcast
,D/LGWifiP2pService( 1031): InactiveState
D/LGWifiP2pService( 1031): InactiveState{ when=-36ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): P2pEnabledState{ when=-36ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1031): doBoolean: DRIVER COUNTRY CZ
,D/WifiNative-wlan0( 1031): SAVE_CONFIG: returned true
D/WiFiOffLoadUpdatePriority( 6260): remove1
V/WiFiOffLoadSharedPrefsUtils( 6260): save remove
I/wpa_supplicant( 6270): wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
I/wpa_supplicant( 6270): p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
D/WfdsMonitor( 1940): Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
I/wpa_supplicant( 6270): [LGE_PATCH] driver_cmd() country:CZ
D/WifiMonitor( 1031): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
I/wpa_supplicant( 6270): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1031): WifiMonitor:p2p0 cnt=6 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
D/WfdsMonitor( 1940): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1031): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1031): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
D/WifiMonitor( 1031): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,E/WifiMonitor( 1031): WifiMonitor:p2p0 cnt=7 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1031): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1031): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
I/wpa_supplicant( 6270): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiNative-p2p0( 1031): DRIVER COUNTRY CZ: returned true
D/LGWifiP2pService( 1031): InactiveState{ when=-41ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): P2pEnabledState{ when=-41ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): InactiveState{ when=-11ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): P2pEnabledState{ when=-11ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): DefaultState{ when=-11ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): InactiveState{ when=-11ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsMonitor( 1940): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/LGWifiP2pService( 1031): P2pEnabledState{ when=-11ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1031): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/LGWifiP2pService( 1031): DefaultState{ when=-11ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiMonitor( 1031): WifiMonitor:p2p0 cnt=8 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/LGWifiP2pService( 1031): InactiveState{ when=-11ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): P2pEnabledState{ when=-12ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): DefaultState{ when=-12ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiMonitor( 1031): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1031): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/LGWifiP2pService( 1031): InactiveState{ when=-12ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): P2pEnabledState{ when=-12ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): DefaultState{ when=-12ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
W/WfdsService( 1940): DefaultState - msg [9441285] is not handled
E/WifiServerServiceExt( 1031): No p2p device connected
D/WiFiOffLoadBroadcast( 6260): mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
D/WiFiOffLoadBroadcast( 6260): S: false, R: false
E/WifiStateMachine( 1031):  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1031):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
,D/WiFiOffLoadUpdatePriority( 6260): saved SSID: "NG700"
D/WiFiOffLoadUpdatePriority( 6260): connected SSID: null
D/WiFiOffLoadUpdatePriority( 6260): private wpa: "NG700" 300
D/WifiServiceImplEx( 1031): addOrUpdateNetwork pid=6260, uid=1000, packageName=android.uid.system:1000
E/addOrUpdateNetwork( 1031):  uid = 1000 SSID "NG700" nid=0
E/WifiStateMachine( 1031):  DisconnectedState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=0
E/WifiStateMachine( 1031):  ConnectModeState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=0
E/WifiConfigStore( 1031):  key="NG700"WPA_PSK netId=0 uid=0/1000
D/WifiServerServiceExt( 1031): addOrUpdateNetwork: mThisIsFirstEnableing = false
D/WifiNative-wlan0( 1031): doBoolean: SET_NETWORK 0 ssid 4e47373030
D/WifiNative-wlan0( 1031): SET_NETWORK 0 ssid 4e47373030: returned true
D/WifiNative-wlan0( 1031): doBoolean: SET_NETWORK 0 key_mgmt WPA-PSK
,D/WifiNative-wlan0( 1031): SET_NETWORK 0 key_mgmt WPA-PSK: returned true
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
D/WiFiOffLoadUpdatePriority( 6260):  ssid "NG700" prio 300
D/WiFiOffLoadUpdatePriority( 6260): configuration updated: 0
E/WifiStateMachine( 1031):  DisconnectedState CMD_SAVE_CONFIG uid=1000 0 0
E/WifiStateMachine( 1031):  ConnectModeState CMD_SAVE_CONFIG uid=1000 0 0
D/WifiNative-wlan0( 1031): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1031): SAVE_CONFIG: returned true
D/WiFiOffLoadUpdatePriority( 6260): configuration saved: true
,D/LGDMClient( 3956): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 3956): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 3956): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 3956): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/PostponalbeReceiver( 5169): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,D/LGDMClient( 3956): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/LGDMClient( 3956): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 3956): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/PCSuite ( 6351): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6351): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6351): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6260): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6260): MCCMNC not supported: null
D/QRemote ( 6047): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6047): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6047): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,V/[BNRBootReceiver]( 5995): boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,D/BNRAndroBeam( 5995): [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
V/[BNRBootReceiver]( 5995): Boot Receiver Return
D/PostponalbeReceiver( 5169): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 6260): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6260): MCCMNC not supported: null
D/QRemote ( 6047): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6047): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6047): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
E/QC-QMI  ( 6393): qmi_client [6393] 13: failed to locate client data
,E/QC-QMI  (  474): qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
E/QC-QMI  (  474): QMUX qmux_client_id=13 not found in qmux client list, unable to remove
I/qcom-bluetooth( 6434): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:64:c0 
,I/qcom-bluetooth( 6435): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,I/bt_vendor( 6234): bluetooth satus is on
D/bt_hci_bdroid( 6234): preload
D/bt_userial_mct( 6234): userial_open(port:0)
,I/bt_vendor( 6234): bt-vendor : BT_VND_OP_USERIAL_OPEN
I/bt_vendor( 6234): Done intiailizing UART
I/bt_vendor( 6234): Done intiailizing UART
I/bt_userial_mct( 6234): CMD=66, EVT=66, ACL_Out=67, ACL_In=67
I/bt_vendor( 6234): Bluetooth Firmware and transport layer are initialized
I/bt-btu  ( 6234): btu_task received preload complete event
W/bt-l2cap( 6234): L2CAP - L2CA_Register() called for PSM: 0x0001
W/bt-l2cap( 6234): L2CAP - L2CA_Register() called for PSM: 0x001f
W/bt-l2cap( 6234): L2CAP - L2CA_Register() called for PSM: 0x0003
D/bt_userial_mct( 6234): Entering userial_read_thread()
I/        ( 6234): BTE_InitTraceLevels -- TRC_HCI
I/        ( 6234): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 6234): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 6234): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 6234): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 6234): BTE_InitTraceLevels -- TRC_A2D
I/        ( 6234): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 6234): BTE_InitTraceLevels -- TRC_BTM
I/        ( 6234): BTE_InitTraceLevels -- TRC_HID_HOST
I/        ( 6234): BTE_InitTraceLevels -- TRC_GAP
I/        ( 6234): BTE_InitTraceLevels -- TRC_PAN
I/        ( 6234): BTE_InitTraceLevels -- TRC_SDP
I/        ( 6234): BTE_InitTraceLevels -- TRC_GATT
I/        ( 6234): BTE_InitTraceLevels -- TRC_SMP
I/        ( 6234): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 6234): BTE_InitTraceLevels -- TRC_BTIF
W/bt-btm  ( 6234): btm_decode_ext_features_page Secure conn Controller support Enabled
E/bt-btm  ( 6234): BTM_SecRegister:p_cb_info->p_le_callback == 0xa0228061 
E/bt-btm  ( 6234): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0228061 
,E/bt-btif ( 6234): Calling BTA_HhEnable
E/bt-btif ( 6234): btif_storage_get_adapter_property service_mask:0x2140040
D/BluetoothAdapterProperties( 6234): Address is:58:3F:54:73:64:C0
D/BluetoothManagerService( 1031): Bluetooth Adapter name changed to G3-1
D/BluetoothManagerService( 1031): Stored Bluetooth name: G3-1
,D/BluetoothAdapterProperties( 6234): Name is: G3-1
D/BluetoothAdapterProperties( 6234): Scan Mode:20
D/BluetoothAdapterProperties( 6234): Discoverable Timeout:120
D/bt_hci_bdroid( 6234): postload
D/bte_conf( 6234): Device ID record 1 : primary
D/bte_conf( 6234):   vendorId            = 00c4
D/bte_conf( 6234):   vendorIdSource      = 0001
D/bte_conf( 6234):   product             = 13a1
D/bte_conf( 6234):   version             = 1000
D/bte_conf( 6234):   clientExecutableURL = 
D/bte_conf( 6234):   serviceDescription  = 
D/bte_conf( 6234):   documentationURL    = 
D/bt_hci_bdroid( 6234): Used up Tx Cmd credits
D/bte_conf( 6234): bte_load_did_conf no section named DID2.
D/BluetoothAdapterState( 6234): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
,D/BluetoothAdapterProperties( 6234): ScanMode =  20
D/BluetoothAdapterProperties( 6234): State =  11
D/BluetoothAdapterProperties( 6234): mDiscoverableTimeout = 120
V/LGBluetoothServiceAdapter( 6234): [BTUI] state:11, scanmode:20, timeout:120
D/BluetoothAdapterProperties( 6234): Setting state to 12
I/BluetoothAdapterState( 6234): Bluetooth adapter state changed: 11-> 12
D/btif_config_util( 6234): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
W/sh      ( 6439): type=1400 audit(0.0:157): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,W/sh      ( 6439): type=1400 audit(0.0:158): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/BluetoothManagerService( 1031): Message: 60
D/BluetoothManagerService( 1031): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService( 1031): Broadcasting onBluetoothStateChange(true) to 5 receivers.
I/BluetoothAdapterState( 6234): Entering On State
,D/BluetoothHeadset( 1850): onBluetoothStateChange: up=true
D/LGBluetoothServiceAdapter( 6234): [BTUI] OnState
D/LGBluetoothServiceAdapter( 6234): [BTUI]         global_name: G3-1
D/LGBluetoothServiceAdapter( 6234): [BTUI]         local_name: G3-1
D/BluetoothAdapterService( 6234): [BTUI] autoConnect() : not allowed
D/BluetoothHeadset( 1031): onBluetoothStateChange: up=true
D/BluetoothA2dp( 1031): onBluetoothStateChange: up=true
D/bt_hci_bdroid( 6234): Used up Tx Cmd credits
,D/BluetoothHeadset( 1850): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1850): onBluetoothStateChange: up=true
E/bt_mct  ( 6234): hci lib postload completed
W/bt-l2cap( 6234): L2CAP - L2CA_Register() called for PSM: 0x0019
W/bt-l2cap( 6234): L2CAP - L2CA_Register() called for PSM: 0x0017
W/bt-l2cap( 6234): L2CAP - L2CA_Register() called for PSM: 0x001b
W/bt-l2cap( 6234): L2CAP - L2CA_Register() called for PSM: 0x0011
W/bt-l2cap( 6234): L2CAP - L2CA_Register() called for PSM: 0x0013
W/bt-l2cap( 6234): L2CAP - L2CA_Register() called for PSM: 0x000f
W/bt-smp  ( 6234): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6234): Plain text(LSB ~ MSB) = 9c 21 5b 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6234): Encrypted text(LSB ~ MSB) = 20 3e f4 d0 3f ef 4b a6 42 be 9b cc 3c 09 c7 26 
W/bt-btm  ( 6234): Stopping oneshot timer
D/BluetoothAdapterProperties( 6234): Discoverable Timeout:120
D/LGBluetoothDeviceModeControllManager( 6234): adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
D/BluetoothPanServiceJni( 6234): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,W/bt-smp  ( 6234): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6234): Plain text(LSB ~ MSB) = 63 f1 6d 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6234): Encrypted text(LSB ~ MSB) = f0 36 d7 93 fc 4b 4e d7 6b 2d a4 54 19 d1 a9 26 
W/bt-btm  ( 6234): Stopping oneshot timer
W/bt-smp  ( 6234): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6234): Plain text(LSB ~ MSB) = e3 61 4c 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6234): Encrypted text(LSB ~ MSB) = 47 c4 ab f9 13 f3 04 87 34 e5 79 03 53 89 f7 8c 
,D/LGBluetoothDeviceModeControllManager( 6234): [BTUI] checkDeviceModeAndSet, sinkMode : false
W/bt-btm  ( 6234): Stopping oneshot timer
E/BluetoothManagerService( 1031): Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
,D/BluetoothManagerService( 1031): Bluetooth State Change Intent: 11 -> 12
W/bt-smp  ( 6234): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6234): Plain text(LSB ~ MSB) = 67 3f 6f 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6234): Encrypted text(LSB ~ MSB) = e0 c3 ed b4 02 3e 19 17 44 b5 9b 16 b5 41 72 61 
W/bt-btm  ( 6234): Stopping oneshot timer
D/BluetoothManagerService( 1031): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,D/BluetoothManagerService( 1031): Message: 40
D/BluetoothManagerService( 1031): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
D/LGBluetoothAPIService( 1940): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/LGBluetoothAPIService( 1940): Message: 1
D/LGBluetoothAPIService( 1940): MESSAGE_BOOT_COMPLETED
I/[SystemUI]BluetoothHandler( 1444): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
I/LGBluetoothAPIService( 1940): [BTUI] LGBluetoothAPIService Binding Success
,I/qcom-bt-wlan-coex( 6460): /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,I/BluetoothMapService( 6234): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 6234): STATE_ON
W/bt-smp  ( 6234): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6234): Plain text(LSB ~ MSB) = 0d 7b 42 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6234): Encrypted text(LSB ~ MSB) = 8d c0 60 27 97 bf 79 d8 f6 b3 e9 19 4d 6a 99 d1 
W/bt-btm  ( 6234): Stopping oneshot timer
D/LGBluetoothAPIServer( 6234): [BTUI] onCreate()
D/LGBluetoothAPIServer( 6234): [BTUI] onBind()
D/LGBluetoothAPIService( 1940): [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
,D/LGBluetoothAPIService( 1940): Message: 100
,D/LGBluetoothAPIService( 1940): MESSAGE_BLUETOOTH_SERVICE_CONNECTED
W/ContextImpl( 6260): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
D/BluetoothAdapterService( 6234): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16bde43b
V/BluetoothPbapService( 6234): Pbap Service onCreate
V/BluetoothPbapService( 6234): Starting PBAP service
D/LGBluetoothPbapAdapter( 6234): [BTUI] getInstance : create
V/BluetoothPbapService( 6234): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 6234): state: 12
,V/BluetoothMapService( 6234): Handler(): got msg=1
D/BluetoothMapMasInstance( 6234): Map Service startRfcommSocketListener
V/BluetoothPbapReceiver( 6234): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 6234): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6234): ***********state = 12
D/BluetoothMapMasInstance( 6234): MAS initSocket()
V/BluetoothPbapService( 6234): Handler(): got msg=1
D/BluetoothMapMasInstance( 6234):   masId = 00
D/BluetoothMapMasInstance( 6234):   msgTypes = 0e
D/BluetoothMapMasInstance( 6234):   masName = SMS/MMS
D/BluetoothMapMasInstance( 6234):   SDP string = 000eSMS/MMS
V/BluetoothPbapService( 6234): Pbap Service startRfcommSocketListener
V/BluetoothPbapService( 6234): Pbap Service initSocket
D/BluetoothManagerService( 1031): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/LocalBluetoothProfileManager( 6260): Adding local A2DP profile
W/BluetoothAdapter( 6234): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothManagerService( 1031): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1031): Message: 30
,D/LGBluetoothServiceAdapter( 6234): [BTUI] createSocketChannel FD=73 mFd=0
V/BluetoothMapMasInstance( 6234): Succeed to create listening socket 
D/BluetoothMapMasInstance( 6234): Accepting socket connection...
D/BluetoothAdapterProperties( 6234): Scan Mode:21
D/LGBluetoothDeviceModeControllManager( 6234): getDeviceMode  deviceMode 0
D/LocalBluetoothProfileManager( 6260): Adding local HEADSET profile
W/BluetoothAdapter( 6234): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothManagerService( 1031): Message: 30
D/LGBluetoothServiceAdapter( 6234): [BTUI] createSocketChannel FD=75 mFd=73
V/BluetoothPbapService( 6234): Succeed to create listening socket 
V/BluetoothPbapService( 6234): Accepting socket connection...
D/BluetoothManagerService( 1031): Message: 30
,D/BluetoothManagerService( 1031): Message: 30
D/LocalBluetoothProfileManager( 6260): Adding local MAP profile
D/BluetoothMap( 6260): Create BluetoothMap proxy object
D/BluetoothManagerService( 1031): Message: 30
D/BluetoothManagerService( 1031): Message: 30
,D/LocalBluetoothProfileManager( 6260): LocalBluetoothProfileManager construction complete
V/BluetoothPbapService( 6234): Pbap Service onBind
D/LGBluetoothUserBindClient( 6260): [BTUI] initUserBindClient
,W/ContextImpl( 6260): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
D/DockEventReceiver( 6260): finishStartingService: stopping service
,D/BluetoothA2dp( 6260): Proxy object connected
D/A2dpProfile( 6260): Bluetooth service connected
D/BluetoothHeadset( 6260): Proxy object connected
,D/HeadsetProfile( 6260): Bluetooth service connected
D/BluetoothInputDevice( 6260): Proxy object connected
D/HidProfile( 6260): Bluetooth service connected
D/BluetoothPan( 6260): BluetoothPAN Proxy object connected
D/PanProfile( 6260): Bluetooth service connected
,D/BluetoothMap( 6260): Proxy object connected
D/MapProfile( 6260): Bluetooth service connected
D/BluetoothMap( 6260): getConnectedDevices()
V/BluetoothMapService( 6234): getConnectedDevices()
D/BluetoothPbap( 6260): Proxy object connected
D/PbapServerProfile( 6260): Bluetooth service connected
D/LGBluetoothUserBindClient( 6260): [BTUI] onServiceConnected
D/BluetoothPermissionRequest( 6260): onReceive
,D/LGBluetoothFeatureConfig( 6260): isPrivacyLogsEnabled : true
D/LGBluetoothUtils( 6260): [BTUI] FileNotFound: readProperty
D/LGBluetoothResetSettingReceiver( 6260): return without doing reset settings.
V/BluetoothOppReceiver( 6234): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,I/LGBluetoothOppAdapter( 6234): [BTUI] startOppService()
V/BluetoothOppManager( 6234): restoreApplicationData! falsefalsenullnull
,D/LGBluetoothFeatureConfig( 6234): isPrivacyLogsEnabled : true
V/BtOppService( 6234): onCreate
,V/BluetoothOppNotification( 6234): send message
V/BtOppService( 6234): Starting RfcommListener
,D/BluetoothOppPreference( 6234): Dumping Names:  
D/BluetoothOppPreference( 6234): {}
D/BluetoothOppPreference( 6234): Dumping Channels:  
D/BluetoothOppPreference( 6234): {}
V/BtOppService( 6234): onStartCommand
,V/BtOppService( 6234): pendingUpdate is true keepUpdateThread is false sListenStarted is true
V/BluetoothFtpReceiver( 6234): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpReceiver( 6234): BluetoothFtpReceiver Start Service
V/BluetoothOppNotification( 6234): new notify threadi!
V/BluetoothOppNotification( 6234): send delay message
V/BtOppService( 6234): start RfcommListener
,V/BtOppService( 6234): RfcommListener started
V/BluetoothOppProvider( 6234): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6234): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
V/BtOppService( 6234): Deleted complete outbound shares, number =  0
,V/BtOppRfcommListener( 6234): Starting RFCOMM listener....
D/BluetoothManagerService( 1031): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6234): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 6234): [BTUI] createSocketChannel FD=78 mFd=75
V/BtOppRfcommListener( 6234): Started RFCOMM listener....
I/BtOppRfcommListener( 6234): Accept thread started.
V/BtOppRfcommListener( 6234): Accepting connection...
D/BluetoothAdapterService( 6234): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16bde43b
V/BluetoothFtpService( 6234): Ftp Service onCreate
I/BluetoothFtpService( 6234): Ftp Service onCreate
V/BluetoothFtpService( 6234): Ftp Service onStartCommand
V/BluetoothFtpService( 6234): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpService( 6234): Starting Listening on sockets
V/BluetoothSapReceiver( 6234): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 6234): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 6234): SapReceiver onReceive 
V/BluetoothSapReceiver( 6234): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6234):  Bluetooth Adapter state = 12
V/BluetoothSapReceiver( 6234): Calling SAP service start service with action = null
V/BluetoothOppProvider( 6234): created cursor android.database.sqlite.SQLiteCursor@2b5d3e32 on behalf of 
V/BluetoothOppProvider( 6234): created cursor android.database.sqlite.SQLiteCursor@2c52e783 on behalf of 
V/BluetoothOppNotification( 6234): mUpdateCompleteNotification = true
V/BtOppService( 6234): Deleted complete inbound failed shares, number = 0
V/BluetoothOppProvider( 6234): starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
V/BtOppService( 6234): ContentObserver received notification
V/BluetoothFtpService( 6234): Handler(): got msg=1
V/BluetoothFtpService( 6234): Ftp Service startRfcommSocketListener
V/BluetoothFtpService( 6234): Ftp Service initSocket
V/BtOppService( 6234): pendingUpdate is true keepUpdateThread is false sListenStarted is true
V/BluetoothOppProvider( 6234): created cursor android.database.sqlite.SQLiteCursor@3428ad00 on behalf of 
V/BluetoothOppProvider( 6234): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6234): created cursor android.database.sqlite.SQLiteCursor@2807d939 on behalf of 
V/BluetoothOppProvider( 6234): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppNotification( 6234): update too frequent, put in queue
V/BluetoothOppProvider( 6234): created cursor android.database.sqlite.SQLiteCursor@2a9d0b7e on behalf of 
V/BtOppService( 6234): pendingUpdate is false keepUpdateThread is false sListenStarted is true
V/BluetoothOppNotification( 6234): outbound: succ-0  fail-0
D/BluetoothManagerService( 1031): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6234): getBluetoothService() called with no BluetoothManagerCallback
V/BluetoothOppNotification( 6234): outbound notification was removed.
V/BluetoothOppProvider( 6234): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 6234): created cursor android.database.sqlite.SQLiteCursor@1fd278df on behalf of 
V/BluetoothOppNotification( 6234): inbound: succ-0  fail-0
V/BluetoothOppNotification( 6234): inbound notification was removed.
V/BluetoothOppProvider( 6234): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6234): created cursor android.database.sqlite.SQLiteCursor@8eb992c on behalf of 
D/AuthorizationBluetoothService( 2110): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/LGBluetoothServiceAdapter( 6234): [BTUI] createSocketChannel FD=80 mFd=78
V/BluetoothFtpService( 6234): Succeed to create listening socket on channel 20
V/BtOppService( 6234): ContentObserver received notification
V/BluetoothFtpService:RfcommSocketAcceptThread( 6234): Run Accept thread
V/BtOppService( 6234): pendingUpdate is true keepUpdateThread is false sListenStarted is true
V/BluetoothOppProvider( 6234): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6234): created cursor android.database.sqlite.SQLiteCursor@3903cff5 on behalf of 
V/BluetoothOppNotification( 6234): update too frequent, put in queue
V/BtOppService( 6234): pendingUpdate is false keepUpdateThread is false sListenStarted is true
D/BluetoothAdapterService( 6234): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16bde43b
V/BluetoothSapService( 6234): Sap Service onCreate
V/BluetoothSapService( 6234): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 6234): state: 12
V/BluetoothSapService( 6234): Starting SAP server process
V/BluetoothSapService( 6234): SAP Service startRfcommListenerThread
V/BluetoothSapService( 6234): Sap Service initRfcommSocket
D/BluetoothManagerService( 1031): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6234): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 6234): [BTUI] createSocketChannel FD=82 mFd=80
V/BluetoothSapService( 6234): Succeed to create listening socket 
V/BluetoothSapService( 6234): Accepting socket connection...
W/sapd    ( 6481): type=1400 audit(0.0:159): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/sapd    ( 6481): type=1400 audit(0.0:160): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
V/BT_SAP  ( 6481): Event pipe created
V/BT_SAP  ( 6481): create_server_socket qcom.sap.server
V/BT_SAP  ( 6481): created socket fd 6
V/BluetoothOppNotification( 6234): new notify threadi!
V/BluetoothOppNotification( 6234): send delay message
,V/BluetoothOppProvider( 6234): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6234): created cursor android.database.sqlite.SQLiteCursor@298e7671 on behalf of 
,V/BluetoothOppNotification( 6234): mUpdateCompleteNotification = true
V/BluetoothOppProvider( 6234): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 6234): created cursor android.database.sqlite.SQLiteCursor@26250c56 on behalf of 
V/BluetoothOppNotification( 6234): outbound: succ-0  fail-0
V/BluetoothOppNotification( 6234): outbound notification was removed.
V/BluetoothOppProvider( 6234): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 6234): created cursor android.database.sqlite.SQLiteCursor@280ca4d7 on behalf of 
V/BluetoothOppNotification( 6234): inbound: succ-0  fail-0
,V/BluetoothOppNotification( 6234): inbound notification was removed.
V/BluetoothOppProvider( 6234): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6234): created cursor android.database.sqlite.SQLiteCursor@3ce5e1c4 on behalf of 
D/WfdsMonitor( 1940): Event [CTRL-EVENT-SCAN-RESULTS ]
D/WfdsMonitor( 1940): Event [WPS-AP-AVAILABLE ]
,E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=9 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1031): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1031): WifiMonitor:p2p0 cnt=10 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1031): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1031): Event [IFNAME=p2p0 WPS-AP-AVAILABLE ]
,E/WifiMonitor( 1031): WifiMonitor:p2p0 cnt=11 dispatchEvent: WPS-AP-AVAILABLE 
D/LGWifiP2pService( 1031): InactiveState{ when=-6ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): P2pEnabledState{ when=-7ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): DefaultState{ when=-7ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/WifiMonitor( 1031): couldn't identify event type - WPS-AP-AVAILABLE 
E/WifiStateMachine( 1031):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine( 1031):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine( 1031):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine( 1031):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
I/WifiNative-HAL( 1031): startHal
E/wifi    ( 1031): getStaticLongField sWifiHalHandle 0x9899e8cc
E/WifiHAL ( 1031): Could not connect handle
D/wifi    ( 1031): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x5018de
I/WifiNative-HAL( 1031): Could not start hal
D/WifiNative-wlan0( 1031): doString: [BSS RANGE=0- MASK=0x21987]
V/WiFiOffLoadBroadcast( 6260): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,D/WiFiOffLoadBroadcast( 6260): Not supported operator for automatic switch
I/jxcore-log( 6145): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 6145): 
,D/PowerManagerServiceEx( 1031): acquireWakeLockInternal: lock=571795092, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1031
,V/AlarmManager( 1031): RTC_WAKEUP set : Alarm{326929e3 type 0 when 1450226471116 android} when 1450226471116
V/AlarmManager( 1031): ELAPSED_WAKEUP set : Alarm{a1c2fe0 type 2 when 174006 com.google.android.gms} when 174006
V/AlarmManager( 1031): ELAPSED_WAKEUP set : Alarm{bd6d299 type 2 when 179285 com.google.android.gms} when 179285
V/AlarmManager( 1031): RTC_WAKEUP set : Alarm{207a813f type 0 when 1450226473031 com.android.vending} when 1450226473031
,E/WifiStateMachine( 1031):  DisconnectedState CMD_START_SCAN -2 -2 ic=1 proc(ms):2 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=120000 [on:0 tx:0 rx:0 period:-1472470078] from screen [on:0 period:-1472470078]
E/WifiStateMachine( 1031):  ConnectModeState CMD_START_SCAN -2 -2 ic=1 proc(ms):10 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=120000 [on:0 tx:0 rx:0 period:7] from screen [on:0 period:-1472470071]
,E/WifiStateMachine( 1031):  DriverStartedState CMD_START_SCAN -2 -2 ic=1 proc(ms):12 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=120000 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1472470068]
D/WifiNative-wlan0( 1031): doBoolean: SCAN
I/wpa_supplicant( 6270): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1031): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=12 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1031): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1031): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-wlan0( 1031): SCAN: returned true
I/WifiNative-HAL( 1031): startHal
E/wifi    ( 1031): getStaticLongField sWifiHalHandle 0x9899e7dc
E/WifiHAL ( 1031): Could not connect handle
D/wifi    ( 1031): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x4018ca
I/WifiNative-HAL( 1031): Could not start hal
D/libc-netbsd(  331): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1031): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,D/[Concierge]Service( 2593): onStartCommand(). Type : 9
,I/ActivityManager( 1031): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RequestWriter$NetworkStateReceiver: pid=6495 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/PowerManagerServiceEx( 1031): releaseWakeLockInternal: lock=571795092 [*alarm*], flags=0x0
,W/ResourcesManager( 6495): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,V/SIM_STK ( 1031): Menu title from STK is T-Mobile
D/LgDataFeature( 6495): LgDataFeature() Constructor: none
D/LgDataFeature( 6495): LgDataFeature() Constructor Done, null
,V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Babel   ( 6495): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 6495): MmsConfig.loadMmsSettings
I/art     ( 2110): Explicit concurrent mark sweep GC freed 21530(1208KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 30MB/62MB, paused 1.936ms total 47.968ms
I/Babel   ( 6495): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
I/Babel   ( 6495): MmsConfig.loadFromDatabase
,E/Babel   ( 6495): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 6495): MmsConfig.loadFromResources
I/GLSUser ( 2110): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2110): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2110): [GLSUser] Extracting token using key: Auth
E/Babel   ( 6495): canonicalizeMccMnc: invalid mccmnc nullnull
W/GLSActivity( 2110): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/Babel   ( 6495): MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Settings( 6495): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/Finsky  ( 4884): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 4884): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4884): [1] 5.onFinished: Scheduling replication attempt 3.
,W/AudioCapabilities( 6495): Unsupported mime audio/evrc
W/AudioCapabilities( 6495): Unsupported mime audio/qcelp
W/VideoCapabilities( 6495): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6495): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6495): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6495): Unsupported mime audio/evrc
I/ActivityManager( 1031): Killing 5806:com.android.defcontainer/u0a4 (adj 15): empty #17
W/VideoCapabilities( 6495): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 6495): Unsupported mime video/divx
W/VideoCapabilities( 6495): Unsupported mime video/divx311
W/VideoCapabilities( 6495): Unsupported mime video/divx4
W/VideoCapabilities( 6495): Unsupported mime video/mp4v-esdp
I/VideoCapabilities( 6495): Unsupported profile 4 for video/mp4v-es
,W/AudioCapabilities( 6495): Unsupported mime audio/eac3
W/AudioCapabilities( 6495): Unsupported mime audio/ac3
W/AudioCapabilities( 6495): Unsupported mime audio/g726
W/AudioCapabilities( 6495): Unsupported mime audio/wma-voice
W/AudioCapabilities( 6495): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6495): Unsupported mime audio/adpcm
W/VideoCapabilities( 6495): Unsupported mime video/theora
W/VideoCapabilities( 6495): Unsupported mime video/mjpg
,W/libprocessgroup( 1031): failed to open /acct/uid_10004/pid_5806/cgroup.procs: No such file or directory
,E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=13 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1031): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1031): WifiMonitor:p2p0 cnt=14 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1031): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
,D/WifiMonitor( 1031): Event [IFNAME=p2p0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1031): WifiMonitor:p2p0 cnt=15 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1031): couldn't identify event type - WPS-AP-AVAILABLE 
D/WfdsMonitor( 1940): Event [CTRL-EVENT-SCAN-RESULTS ]
D/WfdsMonitor( 1940): Event [WPS-AP-AVAILABLE ]
E/WifiStateMachine( 1031):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=9 known=0 got=9 bcn=0
D/LGWifiP2pService( 1031): InactiveState{ when=-14ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): P2pEnabledState{ when=-14ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): DefaultState{ when=-14ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 1031):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=9 known=0 got=9 bcn=0
E/WifiStateMachine( 1031):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=9 known=0 got=9 bcn=0
E/WifiStateMachine( 1031):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=9 known=0 got=9 bcn=0
D/WifiNative-wlan0( 1031): doString: [BSS RANGE=0- MASK=0x21987]
,V/WiFiOffLoadBroadcast( 6260): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,D/WiFiOffLoadBroadcast( 6260): Not supported operator for automatic switch
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 192869363106; DSPS: 6460375; Offset : -4298622860
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 212871096849; DSPS: 7115792; Offset : -4298628697
,V/AlarmManager( 1031): RTC_WAKEUP set : Alarm{2d003228 type 0 when 1450226496440 com.android.vending} when 1450226496440
,V/SIM_STK ( 1031): Menu title from STK is T-Mobile
,V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2110): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2110): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2110): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2110): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 4884): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 4884): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4884): [1] 5.onFinished: Scheduling replication attempt 4.
,I/[SystemUI]TimeTickManager( 1444): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1444): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1444): called onTimeUpdated()
I/[SystemUI]Clock( 1444): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1444): called onTimeUpdated()
I/[SystemUI]DateView( 1444): called onTimeUpdated()
I/[SystemUI]DateView( 1444): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1444): handleTimeUpdate
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 232873311320; DSPS: 7771225; Offset : -4298641983
,D/PowerManagerServiceEx( 1031): acquireWakeLockInternal: lock=571795092, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1031
,V/AlarmManager( 1031): RTC_WAKEUP set : Alarm{68dba3b type 0 when 1450226522404 com.android.vending} when 1450226522404
,D/[Concierge]Service( 2593): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1031): releaseWakeLockInternal: lock=571795092 [*alarm*], flags=0x0
,V/SIM_STK ( 1031): Menu title from STK is T-Mobile
,V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2110): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2110): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2110): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2110): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 4884): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4884): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4884): [1] 5.onFinished: Scheduling replication attempt 5.
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 252875265428; DSPS: 8426649; Offset : -4298640922
,V/AlarmManager( 1031): ELAPSED_WAKEUP set : Alarm{3b9a2ca5 type 2 when 255731 android} when 255731
,D/libc-netbsd(  331): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1031): DNSproblemNotiEnabled is disabled ignore DNS fail CB
V/AlarmManager( 1031): RTC_WAKEUP set : Alarm{f5da82b type 0 when 1450226545758 com.android.vending} when 1450226545758
,V/SIM_STK ( 1031): Menu title from STK is T-Mobile
,V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2110): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2110): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2110): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2110): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 4884): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 4884): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4884): [1] 5.onFinished: Giving up after 6 failures.
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 272877418024; DSPS: 9082079; Offset : -4298624503
,I/[SystemUI]TimeTickManager( 1444): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1444): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1444): called onTimeUpdated()
I/[SystemUI]Clock( 1444): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1444): called onTimeUpdated()
I/[SystemUI]DateView( 1444): called onTimeUpdated()
I/[SystemUI]DateView( 1444): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1444): handleTimeUpdate
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 292879957339; DSPS: 9737522; Offset : -4298618095
,I/[SystemUI]LGPowerUI( 1444): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1444): On Skip Timer : true
,D/WifiController( 1031): battery changed pluggedType: 2
,D/LGDMClient( 3956): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1940): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1940): Battery Level Remaining: 100%
D/LEDHandler( 1940): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1444): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1444): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1444): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 6234): Disconnected process message: 10, size: 0
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LGDMClient( 3956): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 312882957905; DSPS: 10392981; Offset : -4298638900
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 332885136126; DSPS: 11048412; Offset : -4298627401
,I/[SystemUI]TimeTickManager( 1444): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1444): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1444): called onTimeUpdated()
I/[SystemUI]Clock( 1444): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1444): called onTimeUpdated()
I/[SystemUI]DateView( 1444): called onTimeUpdated()
I/[SystemUI]DateView( 1444): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1444): handleTimeUpdate
V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 352887738983; DSPS: 11703857; Offset : -4298617028
,I/art     ( 1031): Explicit concurrent mark sweep GC freed 41225(1964KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 44MB/66MB, paused 2.532ms total 197.840ms
,I/GLSUser ( 2110): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2110): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2110): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2110): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1397): onNotificationPosted
D/SmartCoverUpdateMonitor( 1397): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1397): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1397): handleNotificationPosted(true)
D/QuickCircle( 1397): onNotificationPosted() : isPosted true
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
,D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1397): updateNotificationData: count=3
W/GLSActivity( 2110): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2110): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2110): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2110): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2110): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2110): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2110): 	at android.os.Binder.execTransact(Binder.java:446)
E/PlayEventLogger( 4884): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4884): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4884): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 4884): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4884): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 4884): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4884): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 4884): Ignoring header User-Agent because its value was null.
,D/QuickStatusbarLayout( 1397): Notification difference=198
D/QuickStatusbarLayout( 1397): child = android.widget.LinearLayout{2b5d3e32 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/libc-netbsd(  331): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1031): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 372889753715; DSPS: 12359283; Offset : -4298618044
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 392892244228; DSPS: 13014725; Offset : -4298629843
,I/[SystemUI]TimeTickManager( 1444): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1444): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1444): called onTimeUpdated()
I/[SystemUI]Clock( 1444): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1444): called onTimeUpdated()
I/[SystemUI]DateView( 1444): called onTimeUpdated()
I/[SystemUI]DateView( 1444): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1444): handleTimeUpdate
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 412894539585; DSPS: 13670160; Offset : -4298623226
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 432896570932; DSPS: 14325587; Offset : -4298636531
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 452899060716; DSPS: 14981028; Offset : -4298618853
,D/PowerManagerServiceEx( 1031): acquireWakeLockInternal: lock=571795092, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1031
,V/AlarmManager( 1031): ELAPSED_WAKEUP set : Alarm{ac846e8 type 2 when 418149 com.google.android.gms} when 418149
,D/libc-netbsd(  331): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1031): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,D/[Concierge]Service( 2593): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1031): releaseWakeLockInternal: lock=571795092 [*alarm*], flags=0x0
,I/[SystemUI]TimeTickManager( 1444): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1444): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1444): called onTimeUpdated()
I/[SystemUI]Clock( 1444): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1444): called onTimeUpdated()
I/[SystemUI]DateView( 1444): called onTimeUpdated()
I/[SystemUI]DateView( 1444): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1444): handleTimeUpdate
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 472902286906; DSPS: 15636494; Offset : -4298627552
,I/[SystemUI]LGPowerUI( 1444): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1444): On Skip Timer : true
,D/KeyguardUpdateMonitor( 1444): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 282
,I/[SystemUI]LGPowerUI( 1444): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController( 1031): battery changed pluggedType: 2
D/LEDHandler( 1940): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1940): Battery Level Remaining: 100%
D/LEDHandler( 1940): Battery Temp: 282, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1444): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3956): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3956): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,D/HeadsetStateMachine( 6234): Disconnected process message: 10, size: 0
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 492903957680; DSPS: 16291909; Offset : -4298635036
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 512906084287; DSPS: 16947338; Offset : -4298614247
,I/[SystemUI]TimeTickManager( 1444): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1444): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1444): called onTimeUpdated()
I/[SystemUI]Clock( 1444): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1444): called onTimeUpdated()
I/[SystemUI]DateView( 1444): called onTimeUpdated()
I/[SystemUI]DateView( 1444): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1444): handleTimeUpdate
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 532908547768; DSPS: 17602779; Offset : -4298622585
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 552910991511; DSPS: 18258219; Offset : -4298620404
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 572913281087; DSPS: 18913654; Offset : -4298619465
,I/[SystemUI]TimeTickManager( 1444): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1444): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1444): called onTimeUpdated()
I/[SystemUI]Clock( 1444): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1444): called onTimeUpdated()
I/[SystemUI]DateView( 1444): called onTimeUpdated()
I/[SystemUI]DateView( 1444): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1444): handleTimeUpdate
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 592915580871; DSPS: 19569090; Offset : -4298639199
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 612917733830; DSPS: 20224520; Offset : -4298622445
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 632920641012; DSPS: 20879975; Offset : -4298614354
,I/ActivityManager( 1031): Killing 5553:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,W/libprocessgroup( 1031): failed to open /acct/uid_10080/pid_5553/cgroup.procs: No such file or directory
,I/[SystemUI]TimeTickManager( 1444): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1444): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1444): called onTimeUpdated()
I/[SystemUI]Clock( 1444): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1444): called onTimeUpdated()
I/[SystemUI]DateView( 1444): called onTimeUpdated()
I/[SystemUI]DateView( 1444): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1444): handleTimeUpdate
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 652923283400; DSPS: 21535422; Offset : -4298626891
,V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2110): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2110): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2110): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2110): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/GLSActivity( 2110): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2110): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2110): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2110): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2110): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2110): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2110): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 4884): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4884): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4884): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 4884): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4884): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 4884): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4884): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 4884): Ignoring header User-Agent because its value was null.
D/libc-netbsd(  331): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1031): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/QuickStatusbarLayout( 1397): Notification difference=198
D/QuickStatusbarLayout( 1397): child = android.widget.LinearLayout{2b5d3e32 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 672925904538; DSPS: 22190868; Offset : -4298630474
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 692927802916; DSPS: 22846290; Offset : -4298624003
,I/[SystemUI]TimeTickManager( 1444): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1444): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1444): called onTimeUpdated()
I/[SystemUI]Clock( 1444): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1444): called onTimeUpdated()
I/[SystemUI]DateView( 1444): called onTimeUpdated()
I/[SystemUI]DateView( 1444): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1444): handleTimeUpdate
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 712929763845; DSPS: 23501714; Offset : -4298616147
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 732932481130; DSPS: 24157163; Offset : -4298615057
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 752935159508; DSPS: 24812611; Offset : -4298622355
,I/[SystemUI]TimeTickManager( 1444): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1444): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1444): called onTimeUpdated()
I/[SystemUI]Clock( 1444): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1444): called onTimeUpdated()
I/[SystemUI]DateView( 1444): called onTimeUpdated()
I/[SystemUI]DateView( 1444): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1444): handleTimeUpdate
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 772937688822; DSPS: 25468054; Offset : -4298625818
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 792939759388; DSPS: 26123482; Offset : -4298630552
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 812942273339; DSPS: 26778924; Offset : -4298619017
,I/[SystemUI]TimeTickManager( 1444): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1444): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1444): called onTimeUpdated()
I/[SystemUI]Clock( 1444): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1444): called onTimeUpdated()
I/[SystemUI]DateView( 1444): called onTimeUpdated()
I/[SystemUI]DateView( 1444): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1444): handleTimeUpdate
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 832944662550; DSPS: 27434363; Offset : -4298640669
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 852946979730; DSPS: 28089798; Offset : -4298612150
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 872948723993; DSPS: 28745216; Offset : -4298638142
,I/[SystemUI]TimeTickManager( 1444): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1444): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1444): called onTimeUpdated()
I/[SystemUI]Clock( 1444): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1444): called onTimeUpdated()
I/[SystemUI]DateView( 1444): called onTimeUpdated()
I/[SystemUI]DateView( 1444): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1444): handleTimeUpdate
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 892950646590; DSPS: 29400639; Offset : -4298638152
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 912952806113; DSPS: 30056070; Offset : -4298645350
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 932954996314; DSPS: 30711501; Offset : -4298621975
,I/[SystemUI]TimeTickManager( 1444): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1444): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1444): called onTimeUpdated()
I/[SystemUI]Clock( 1444): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1444): called onTimeUpdated()
I/[SystemUI]DateView( 1444): called onTimeUpdated()
I/[SystemUI]DateView( 1444): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1444): handleTimeUpdate
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 952957289692; DSPS: 31366936; Offset : -4298617311
,V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2110): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2110): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2110): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2110): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/GLSActivity( 2110): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2110): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2110): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2110): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2110): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2110): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2110): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 4884): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4884): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4884): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 4884): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4884): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 4884): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4884): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 4884): Ignoring header User-Agent because its value was null.
D/libc-netbsd(  331): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1031): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,D/QuickStatusbarLayout( 1397): Notification difference=198
D/QuickStatusbarLayout( 1397): child = android.widget.LinearLayout{2b5d3e32 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 972959617652; DSPS: 32022373; Offset : -4298639075
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 992961950771; DSPS: 32677809; Offset : -4298625266
,D/PowerManagerServiceEx( 1031): acquireWakeLockInternal: lock=571795092, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1031
,V/AlarmManager( 1031): ELAPSED_WAKEUP set : Alarm{5bf4dcf type 2 when 915900 com.google.android.gms} when 915900
,D/[Concierge]Service( 2593): onStartCommand(). Type : 9
,D/libc-netbsd(  331): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1031): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/PowerManagerServiceEx( 1031): releaseWakeLockInternal: lock=571795092 [*alarm*], flags=0x0
,I/[SystemUI]TimeTickManager( 1444): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1444): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1444): called onTimeUpdated()
I/[SystemUI]Clock( 1444): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1444): called onTimeUpdated()
I/[SystemUI]DateView( 1444): called onTimeUpdated()
I/[SystemUI]DateView( 1444): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1444): handleTimeUpdate
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1012964230450; DSPS: 33333244; Offset : -4298634379
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1032966715078; DSPS: 33988685; Offset : -4298621805
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1052969387414; DSPS: 34644133; Offset : -4298634886
,I/[SystemUI]TimeTickManager( 1444): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1444): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1444): called onTimeUpdated()
I/[SystemUI]Clock( 1444): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1444): called onTimeUpdated()
I/[SystemUI]DateView( 1444): called onTimeUpdated()
I/[SystemUI]DateView( 1444): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1444): handleTimeUpdate
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1072971455115; DSPS: 35299560; Offset : -4298611915
,D/PowerManagerServiceEx( 1031): acquireWakeLockInternal: lock=571795092, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1031
,V/AlarmManager( 1031): ELAPSED_WAKEUP set : Alarm{3943635c type 2 when 1084259 com.android.bluetooth} when 1084259
,W/bt-smp  ( 6234): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6234): Plain text(LSB ~ MSB) = 5d cb 58 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6234): Encrypted text(LSB ~ MSB) = e9 42 4b 59 6e 75 6c c4 37 b3 1a 55 e4 0a e7 5d 
W/bt-btm  ( 6234): Stopping oneshot timer
D/[Concierge]Service( 2593): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1031): releaseWakeLockInternal: lock=571795092 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1092974125159; DSPS: 35955008; Offset : -4298627418
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1112976740047; DSPS: 36610454; Offset : -4298637041
,I/[SystemUI]TimeTickManager( 1444): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1444): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1444): called onTimeUpdated()
I/[SystemUI]Clock( 1444): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1444): called onTimeUpdated()
I/[SystemUI]DateView( 1444): called onTimeUpdated()
I/[SystemUI]DateView( 1444): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1444): handleTimeUpdate
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1132978718164; DSPS: 37265878; Offset : -4298612205
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1152981629563; DSPS: 37921334; Offset : -4298630520
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1172983393254; DSPS: 38576752; Offset : -4298636745
,I/[SystemUI]TimeTickManager( 1444): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1444): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1444): called onTimeUpdated()
I/[SystemUI]Clock( 1444): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1444): called onTimeUpdated()
I/[SystemUI]DateView( 1444): called onTimeUpdated()
I/[SystemUI]DateView( 1444): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1444): handleTimeUpdate
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1192985593506; DSPS: 39232184; Offset : -4298633706
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1212988267457; DSPS: 39887632; Offset : -4298645537
,I/UsageStatsService( 1031): User[0] Flushing usage stats to disk
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1232990418023; DSPS: 40543062; Offset : -4298631070
,I/[SystemUI]TimeTickManager( 1444): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1444): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1444): called onTimeUpdated()
I/[SystemUI]Clock( 1444): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1444): called onTimeUpdated()
I/[SystemUI]DateView( 1444): called onTimeUpdated()
I/[SystemUI]DateView( 1444): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1444): handleTimeUpdate
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1252992514004; DSPS: 41198490; Offset : -4298610260
,V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2110): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2110): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2110): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2110): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/GLSActivity( 2110): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2110): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2110): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2110): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2110): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2110): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2110): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 4884): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4884): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4884): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 4884): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4884): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 4884): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4884): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 4884): Ignoring header User-Agent because its value was null.
D/QuickStatusbarLayout( 1397): Notification difference=198
D/QuickStatusbarLayout( 1397): child = android.widget.LinearLayout{2b5d3e32 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  331): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1031): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1272995012226; DSPS: 41853932; Offset : -4298614505
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1292997542895; DSPS: 42509375; Offset : -4298616820
,I/[SystemUI]TimeTickManager( 1444): setTimeTickHandler, called onTimeChanged(),
I/KeyguardUpdateMonitor( 1444): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1444): called onTimeUpdated()
I/[SystemUI]Clock( 1444): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1444): called onTimeUpdated()
I/[SystemUI]DateView( 1444): called onTimeUpdated()
I/[SystemUI]DateView( 1444): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1444): handleTimeUpdate
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1313001296898; DSPS: 43164858; Offset : -4298616402
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1333003579391; DSPS: 43820293; Offset : -4298622752
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1353005704331; DSPS: 44475723; Offset : -4298633939
,I/[SystemUI]TimeTickManager( 1444): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1444): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1444): called onTimeUpdated()
I/[SystemUI]Clock( 1444): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1444): called onTimeUpdated()
I/[SystemUI]DateView( 1444): called onTimeUpdated()
I/[SystemUI]DateView( 1444): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1444): handleTimeUpdate
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1373007853906; DSPS: 45131153; Offset : -4298620620
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1393010416920; DSPS: 45786597; Offset : -4298621057
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1413013352641; DSPS: 46442053; Offset : -4298615101
,I/[SystemUI]TimeTickManager( 1444): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1444): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1444): called onTimeUpdated()
I/[SystemUI]Clock( 1444): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1444): called onTimeUpdated()
I/[SystemUI]DateView( 1444): called onTimeUpdated()
I/[SystemUI]DateView( 1444): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1444): handleTimeUpdate
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1433015859821; DSPS: 47097495; Offset : -4298610390
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1453018053563; DSPS: 47752927; Offset : -4298613809
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1473020936160; DSPS: 48408382; Offset : -4298630537
,I/[SystemUI]TimeTickManager( 1444): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1444): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1444): called onTimeUpdated()
I/[SystemUI]Clock( 1444): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1444): called onTimeUpdated()
I/[SystemUI]DateView( 1444): called onTimeUpdated()
I/[SystemUI]DateView( 1444): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1444): handleTimeUpdate
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1493023526257; DSPS: 49063827; Offset : -4298634383
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1513025610311; DSPS: 49719255; Offset : -4298625550
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1533027878324; DSPS: 50374689; Offset : -4298615656
,I/[SystemUI]TimeTickManager( 1444): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1444): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1444): called onTimeUpdated()
I/[SystemUI]Clock( 1444): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1444): called onTimeUpdated()
I/[SystemUI]DateView( 1444): called onTimeUpdated()
I/[SystemUI]DateView( 1444): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1444): handleTimeUpdate
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1553030645817; DSPS: 51030140; Offset : -4298625366
,V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2110): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2110): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2110): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2110): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/GLSActivity( 2110): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2110): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2110): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2110): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2110): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2110): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2110): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 4884): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4884): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4884): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 4884): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4884): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 4884): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4884): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 4884): Ignoring header User-Agent because its value was null.
D/libc-netbsd(  331): default dns: query_ipv6=0, query_ipv4=0
D/QuickStatusbarLayout( 1397): Notification difference=198
D/QuickStatusbarLayout( 1397): child = android.widget.LinearLayout{2b5d3e32 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/DSQN    ( 1031): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1573033287945; DSPS: 51685587; Offset : -4298638424
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1593035201844; DSPS: 52341009; Offset : -4298616406
,I/[SystemUI]TimeTickManager( 1444): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1444): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1444): called onTimeUpdated()
I/[SystemUI]Clock( 1444): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1444): called onTimeUpdated()
I/[SystemUI]DateView( 1444): called onTimeUpdated()
I/[SystemUI]DateView( 1444): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1444): handleTimeUpdate
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1613037684544; DSPS: 52996451; Offset : -4298636148
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1633039847505; DSPS: 53651882; Offset : -4298640066
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1653042375154; DSPS: 54307324; Offset : -4298614649
,I/[SystemUI]LGPowerUI( 1444): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1444): On Skip Timer : true
,D/WifiController( 1031): battery changed pluggedType: 2
,D/LGDMClient( 3956): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3956): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
D/LEDHandler( 1940): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1940): Battery Level Remaining: 100%
D/LEDHandler( 1940): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1444): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1444): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1444): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 6234): Disconnected process message: 10, size: 0
,W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]TimeTickManager( 1444): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1444): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1444): called onTimeUpdated()
I/[SystemUI]Clock( 1444): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1444): called onTimeUpdated()
I/[SystemUI]DateView( 1444): called onTimeUpdated()
I/[SystemUI]DateView( 1444): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1444): handleTimeUpdate
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1673044696761; DSPS: 54962761; Offset : -4298643053
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1693046977430; DSPS: 55618195; Offset : -4298620657
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1713049150183; DSPS: 56273627; Offset : -4298645327
,I/[SystemUI]TimeTickManager( 1444): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1444): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1444): called onTimeUpdated()
I/[SystemUI]Clock( 1444): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1444): called onTimeUpdated()
I/[SystemUI]DateView( 1444): called onTimeUpdated()
I/[SystemUI]DateView( 1444): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1444): handleTimeUpdate
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1733051760592; DSPS: 56929072; Offset : -4298628859
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1753054091783; DSPS: 57584508; Offset : -4298616848
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1773056861618; DSPS: 58239959; Offset : -4298624217
,I/[SystemUI]TimeTickManager( 1444): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1444): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1444): called onTimeUpdated()
I/[SystemUI]Clock( 1444): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1444): called onTimeUpdated()
I/[SystemUI]DateView( 1444): called onTimeUpdated()
I/[SystemUI]DateView( 1444): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1444): handleTimeUpdate
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1793059067860; DSPS: 58895391; Offset : -4298615240
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1813065437801; DSPS: 59550960; Offset : -4298623526
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1833067358470; DSPS: 60206383; Offset : -4298625412
,I/[SystemUI]TimeTickManager( 1444): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1444): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1444): called onTimeUpdated()
I/[SystemUI]Clock( 1444): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1444): called onTimeUpdated()
I/[SystemUI]DateView( 1444): called onTimeUpdated()
I/[SystemUI]DateView( 1444): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1444): handleTimeUpdate
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1853069612837; DSPS: 60861817; Offset : -4298629424
,V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ProcessStatsService( 1031): Prepared write state in 11ms
,I/GLSUser ( 2110): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2110): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2110): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2110): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2110): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
,D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1397): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1397): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1397): updateNotificationData: count=3
W/GLSActivity( 2110): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2110): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2110): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2110): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2110): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2110): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2110): 	at android.os.Binder.execTransact(Binder.java:446)
E/PlayEventLogger( 4884): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4884): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4884): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 4884): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4884): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 4884): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4884): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 4884): Ignoring header User-Agent because its value was null.
,D/QuickStatusbarLayout( 1397): Notification difference=198
,D/QuickStatusbarLayout( 1397): child = android.widget.LinearLayout{2b5d3e32 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/libc-netbsd(  331): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1031): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/ProcessStatsService( 1031): Pruning old procstats: /data/system/procstats/state-2015-12-15-12-18-33.bin
,I/[SystemUI]LGPowerUI( 1444): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1444): On Skip Timer : true
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1873072717935; DSPS: 61517279; Offset : -4298636910
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1893075214385; DSPS: 62172720; Offset : -4298612306
,I/[SystemUI]TimeTickManager( 1444): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1444): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1444): called onTimeUpdated()
I/[SystemUI]Clock( 1444): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1444): called onTimeUpdated()
I/[SystemUI]DateView( 1444): called onTimeUpdated()
I/[SystemUI]DateView( 1444): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1444): handleTimeUpdate
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1913077533388; DSPS: 62828157; Offset : -4298643209
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1933079794005; DSPS: 63483591; Offset : -4298641023
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1953081890717; DSPS: 64139019; Offset : -4298619350
,I/[SystemUI]TimeTickManager( 1444): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1444): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1444): called onTimeUpdated()
I/[SystemUI]Clock( 1444): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1444): called onTimeUpdated()
I/[SystemUI]DateView( 1444): called onTimeUpdated()
I/[SystemUI]DateView( 1444): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1444): handleTimeUpdate
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1973083902636; DSPS: 64794445; Offset : -4298621695
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 1993086279555; DSPS: 65449883; Offset : -4298625199
,TIME-OUT KILL (timeout was 1800000ms)
```
