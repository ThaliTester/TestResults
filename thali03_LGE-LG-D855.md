#### Test 57972094912017a_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
I/[SystemUI]LGPowerUI( 1456): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1456): On Skip Timer : true
,D/KeyguardUpdateMonitor( 1456): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 294
I/[SystemUI]LGPowerUI( 1456): onReceive = android.intent.action.BATTERY_CHANGED
--------- beginning of system
D/WifiController( 1030): battery changed pluggedType: 2
D/LEDHandler( 1963): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1963): Battery Level Remaining: 100%
D/LEDHandler( 1963): Battery Temp: 294, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1456): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3963): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3963): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/MainApplication( 5929): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/AndroidRuntime( 5973): 
D/AndroidRuntime( 5973): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5973): CheckJNI is OFF
D/AndroidRuntime( 5973): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1030): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1963): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1030): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1030): setTaskToReturnTo : TaskRecord{1ce15eff #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1030): setTaskToReturnTo : TaskRecord{1ce15eff #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1030): AppWindowTokenEx init.. 
E/GBMv2   (  344): DFP En is all cleared set to be enabled
I/ActivityManager( 1030): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5988 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 5973): Shutting down VM
I/art     (  348): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 268us total 33.108ms
I/art     (  348): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 252us total 26.419ms
V/ActivityManager( 1030): Display changed displayId=0
D/DSDPConnection( 1867): Display #0 changed.
I/art     (  348): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 292us total 21.944ms
D/SplitWindowPolicy( 1963): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1963): topRunningActivity=ActivityInfo{19fee54a co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1963): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1963): topRunningActivity=ActivityInfo{1ca05cbb co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 5988): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 5988): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 5988): Loading: webviewchromium
,I/LibraryLoader( 5988): Time to load native libraries: 5 ms (timestamps 936-941)
I/LibraryLoader( 5988): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5988): Binding Chromium to main looper Looper (main, tid 1) {3fdaf07}
,I/LibraryLoader( 5988): Expected native library version number "",actual native library version number ""
I/chromium( 5988): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5988): Initializing chromium process, renderers=0
,W/art     ( 5988): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 5988): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,W/chromium( 5988): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 5988): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 5988): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
V/AudioPolicyService(  319): registerClient() client 0xb57dae40, uid 10311
,D/BluetoothManagerService( 1030): Message: 20
D/BluetoothManagerService( 1030): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c12b91:true
,D/BluetoothAdapter( 5988): 616683572: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 5988): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5988): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5988): Build Date: 12/12/14 금
I/Adreno-EGL( 5988): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 5988): Remote Branch: 
I/Adreno-EGL( 5988): Local Patches: 
I/Adreno-EGL( 5988): Reconstruct Branch: 
W/chromium( 5988): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 5988): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 5988): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5988): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 5988): CordovaWebView is running on device made by: LGE
,W/art     ( 5988): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5988): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 5988): Render dirty regions requested: true
I/OpenGLRenderer( 5988): Initialized EGL, version 1.4
W/ActivityManager( 1030): Activity pause timeout for ActivityRecord{2f2154cc u0 com.test.thalitest/.MainActivity t4}
D/OpenGLRenderer( 5988): Enabling debug mode 0
D/Atlas   ( 5988): Validating map...
,D/SplitWindow( 1030): check instance of lgWin Window{3e9db783 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/LgDataFeature( 5988): LgDataFeature() Constructor: none
D/LgDataFeature( 5988): LgDataFeature() Constructor Done, null
,I/SystemUI[Framework]( 1030): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
,D/PhoneStatusBar( 1456): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
W/PhoneWindowManagerEx( 1030): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1030): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1030): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1030): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@27959770,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1030): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1456): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1456):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1456): , Keyguard show=false, IME shown=false, Panel expanded=false
I/ActivityManager( 1030): Displayed com.test.thalitest/.MainActivity: +642ms (total +791ms)
I/Timeline( 5988): Timeline: Activity_idle id: android.os.BinderProxy@2da5b664 time:111383
,I/Timeline( 1030): Timeline: Activity_windows_visible id: ActivityRecord{2f2154cc u0 com.test.thalitest/.MainActivity t4} time:111384
D/JsMessageQueue( 5988): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium( 5988): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 5988): 
,D/jxcore_app_log( 5988): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435204352
,E/GBMv2   (  344): DFP En is all cleared set to be enabled
E/GBMv2   (  344): Set value is all cleared set the max
I/GBMv2   (  344): DFP Enabled. Ignore VFP set
,I/chromium( 5988): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 5988): 
I/chromium( 5988): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,V/AlarmManager( 1030): RTC_WAKEUP set : Alarm{3f3f292c type 0 when 1454420839017 com.android.vending} when 1454420839017
,W/jxcore-log( 5988): Initializing JXcore engine
W/jxcore-log( 5988): JXcore engine is ready
W/ContextImpl( 4167): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,W/Thread-678( 6061): type=1400 audit(0.0:148): avc: denied { ioctl } for path="socket:[9891]" dev="sockfs" ino=9891 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/Thread-678( 6061): type=1400 audit(0.0:149): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-678( 6061): type=1400 audit(0.0:150): avc: denied { ioctl } for path="socket:[10085]" dev="sockfs" ino=10085 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-678( 6061): type=1400 audit(0.0:151): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/Thread-678( 6061): type=1400 audit(0.0:152): avc: denied { ioctl } for path="socket:[29914]" dev="sockfs" ino=29914 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
W/jxcore-log( 5988): Starting JXcore engine
,V/SIM_STK ( 1030): Menu title from STK is T-Mobile
,W/jxcore-log( 5988): Platform android
W/jxcore-log( 5988): 
W/jxcore-log( 5988): Process ARCH arm
W/jxcore-log( 5988): 
,V/GLSActivity( 2185): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2185): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2185): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2185): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2185): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2185): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 4815): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4815): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4815): [1] 5.onFinished: Scheduling replication attempt 1.
I/jxcore-log( 5988): JXcore Cordova bridge is ready!
I/jxcore-log( 5988): 
W/jxcore-log( 5988): JXcore engine is started
,I/CloudHub( 2154): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19980
,I/jxcore-log( 5988): Toggling radios to true
I/jxcore-log( 5988): 
,D/BluetoothManagerService( 1030): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1030): enable():  mBluetooth =null mBinding = false
,D/LocationManagerService( 1030): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1030): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1030): JNI:system_update. Event-4
D/BluetoothManagerService( 1030): Message: 1
D/BluetoothManagerService( 1030): MESSAGE_ENABLE: mBluetooth = null
D/WifiService( 1030): New client listening to asynchronous messages
,I/ActivityManager( 1030): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=6092 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,D/WifiServiceImplEx( 1030): setWifiEnabled: true pid=5988, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1030): setWifiEnabled: true pid=5988, uid=10311
E/WifiService( 1030): Invoking mWifiStateMachine.setWifiEnabled
D/LocationManagerService( 1030): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1030): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1030): JNI:system_update. Event-4
,D/WifiServiceImplEx( 1030): disconnect pid=5988, uid=10311, packageName=com.test.thalitest
E/WifiStateMachine( 1030):  InitialState CMD_START_SUPPLICANT 0 0
I/LGFTMITEM( 1030): [GET_FTM][id=6], offset=12288
D/WifiServiceImplEx( 1030): reconnect pid=5988, uid=10311, packageName=com.test.thalitest
I/jxcore-log( 5988): Radios toggled
I/jxcore-log( 5988): 
I/jxcore-log( 5988): My device name is: LGE-LG-D855
I/jxcore-log( 5988): 
E/WifiUtil( 1030): wfc_util_ffile_check_copy(): pid[1030] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
E/WifiUtil( 1030): wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
E/WifiUtil( 1030): wfc_util_ffile_check_copy(): pid[1030] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
E/WifiUtil( 1030): wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
I/WifiUtil( 1030): Intf0MacAddress=C49A027B60AC
E/WifiHW  ( 1030): unknown target_country: EU , set to default
E/WifiHW  ( 1030): [wifi_ensure_config_files] default country1 = GB
E/WifiHW  ( 1030): [wifi_ensure_config_files] default country2 = GB
I/WifiUtil( 1030): gEnableBmps=1
,W/ResourcesManager( 6092): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager( 6092): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6092): Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 6092): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/BluetoothAdapterApp( 6092): Loading JNI Library
,D/BluetoothAdapterApp( 6092): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@29538b2b Instance Count = 1
,D/BluetoothAdapterApp( 6092): onCreate
,D/ProfileConfigQcom( 6092): [BTUI] HeadsetService is supported
D/ProfileConfigQcom( 6092): Adding HeadsetService
D/ProfileConfigQcom( 6092): [BTUI] A2dpService is supported
D/ProfileConfigQcom( 6092): Adding A2dpService
,D/ProfileConfigQcom( 6092): [BTUI] HidService is supported
D/ProfileConfigQcom( 6092): Adding HidService
D/ProfileConfigQcom( 6092): [BTUI] HealthService is supported
,D/ProfileConfigQcom( 6092): Adding HealthService
D/LGBluetoothFeatureConfig( 6092): isSupportPan() :  mTargetOp=OPEN
D/SoftapController(  314): Softap fwReload - Ok
D/ProfileConfigQcom( 6092): [BTUI] PanService is supported
D/ProfileConfigQcom( 6092): Adding PanService
,D/ProfileConfigQcom( 6092): [BTUI] GattService is supported
D/ProfileConfigQcom( 6092): Adding GattService
D/ProfileConfigQcom( 6092): [BTUI] BluetoothMapService is supported
D/ProfileConfigQcom( 6092): Adding BluetoothMapService
D/ProfileConfigQcom( 6092): [BTUI] HeadsetClientService is NOT supported
D/Tethering( 1030): sendTetherStateChangedBroadcast 0, 0, 0
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=0
D/Tethering( 1030): InitialState.processMessage what=4
D/CommandListener(  314): Setting iface cfg
D/CommandListener(  314): Trying to bring down wlan0
D/DSQN    ( 1030): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/CommandListener(  314): Clearing all IP addresses on wlan0
D/BluetoothAdapterState( 6092): make
,I/LGFMServiceAdapter( 6092): [FM] LGFMServiceAdapter : create
I/bluedroid-qcom( 6092): init
I/BluetoothAdapterState( 6092): Entering OffState
I/bte_conf( 6092): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
I/bte_conf( 6092): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 6092): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 6092): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
D/BTIF_CORE( 6092): [BTUI] lge_load_bluetooth_address
I/bluedroid-qcom( 6092): get_profile_interface socket
I/bluedroid-qcom( 6092): get_profile_interface map_client
I/GKI_LINUX( 6092): gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothAdapterProperties( 6092): Address is:58:3F:54:73:64:C0
W/bdaddr_loader( 6140): type=1400 audit(0.0:153): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/bdaddr_loader( 6140): type=1400 audit(0.0:154): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/lge_bdaddr_loader( 6140): [BTUI] bdaddr_loader ::: START
D/lge_bdaddr_loader( 6140): [BTUI] bluetooth_load_bdaddress
I/LGFTMITEM( 6140): [GET_FTM][id=8], offset=16384
D/lge_bdaddr_loader( 6140): [BTUI] bdaddr to set in property : 58:3F:54:73:64:C0
,I/ActivityManager( 1030): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=6142 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/Tethering( 1030): sendTetherStateChangedBroadcast 0, 0, 0
D/BluetoothManagerService( 1030): Message: 20
D/BluetoothManagerService( 1030): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@33c6c71d:true
,D/BluetoothManagerService( 1030): Bluetooth Adapter name changed to G3-1
D/BluetoothManagerService( 1030): Stored Bluetooth name: G3-1
E/lge_bdaddr_loader( 6140): [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:64:C0
D/lge_bdaddr_loader( 6140): [BTUI] bdaddr_loader ::: END
D/BluetoothAdapterProperties( 6092): Name is: G3-1
D/BluetoothManagerService( 1030): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService( 1030): Message: 40
D/BluetoothManagerService( 1030): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
I/bluedroid-qcom( 6092): config_hci_snoop_log
D/BluetoothManagerService( 1030): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService( 1030): Broadcasting onBluetoothServiceUp() to 7 receivers.
V/LGMDMManagerInternal( 6092): Create singleton instance
,W/ResourcesManager( 6142): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6142): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
D/BluetoothAdapterState( 6092): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 6092): Setting state to 11
I/BluetoothAdapterState( 6092): Bluetooth adapter state changed: 10-> 11
W/ResourcesManager( 6142): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/BluetoothManagerService( 1030): Message: 60
W/ResourcesManager( 6142): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
D/BluetoothManagerService( 1030): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService( 1030): Bluetooth State Change Intent: 10 -> 11
I/LGBluetoothServiceJni( 6092): classInitNative: succeeds
D/LGBluetoothAPIService( 1963): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
I/[SystemUI]BluetoothHandler( 1456): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
D/BluetoothBondStateMachine( 6092): make
,W/ResourcesManager( 6142): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/BluetoothAdapterService( 6092): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c550bd2
D/LGBluetoothServiceAdapter( 6092): [BTUI] check adapter is available - false.
D/BluetoothAdapterService( 6092): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c550bd2
D/LGBluetoothServiceAdapter( 6092): [BTUI] check adapter is available - true : set adapter available.
W/ResourcesManager( 6142): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/LGBluetoothSettingsDBObserver( 6092): [BTUI] register observer for LG device name DB
E/WifiHW  ( 1030): Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
I/BluetoothBondStateMachine( 6092): StableState(): Entering Off State
E/BluetoothAdapterService( 6092): File transfer profiles supported!!
W/wpa_supplicant( 6160): type=1400 audit(0.0:155): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/wpa_supplicant( 6160): type=1400 audit(0.0:156): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,D/BluetoothHeadset( 1030): Proxy object connected
D/BluetoothHeadset( 1867): Proxy object connected
E/BluetoothAdapterService( 6092): File transfer profiles supported!!
D/BluetoothHeadset( 1867): Proxy object connected
D/BluetoothHeadset( 1867): Proxy object connected
D/HeadsetService( 6092): Received start request. Starting profile...
I/LGBluetoothHeadsetServiceJni( 6092): classInitNative: succeeds
D/LGBluetoothHfpAdapter( 6092): Version 1.6
E/BluetoothAdapterService( 6092): File transfer profiles supported!!
D/LGBluetoothFeatureConfig( 6092): isPrivacyLogsEnabled : true
E/BluetoothAdapterService( 6092): File transfer profiles supported!!
I/BluetoothHeadsetServiceJni( 6092): classInitNative: succeeds
D/HeadsetStateMachine( 6092): make
E/BluetoothAdapterService( 6092): File transfer profiles supported!!
E/BluetoothAdapterService( 6092): File transfer profiles supported!!
,E/BluetoothAdapterService( 6092): File transfer profiles supported!!
I/wpa_supplicant( 6160): Successfully initialized wpa_supplicant
V/LGMDMManager( 6092): Create singleton instance
,I/BluetoothAdapterState( 6092): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/LgDataFeature( 6092): LgDataFeature() Constructor: none
D/LgDataFeature( 6092): LgDataFeature() Constructor Done, null
D/HeadsetStateMachine( 6092): max_hf_connections = 1
I/bluedroid-qcom( 6092): get_profile_interface handsfree
V/ToneGenerator( 6092): ToneGenerator constructor: streamType=8, volume=1.000000
V/AudioPolicyService(  319): registerClient() client 0xb57dad60, uid 1002
V/AudioPolicyManager(  319): getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  319): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  319): getOutput() returns output 2
V/AudioSystem( 6092): getOutputSamplingRate() no output descriptor for output 2 in gOutputs
V/AudioFlinger(  319): registerClient() client 0xb55815c8, pid 6092
V/AudioSystem(  319): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  319): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1867): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1867): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 6092): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1030): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1030): ioConfigChanged() opening already existing output! 2
V/AudioSystem(  319): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem(  319): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1030): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1030): ioConfigChanged() opening already existing output! 4
V/ToneGenerator( 6092): Create Track: 0xb4928080
V/AudioTrack( 6092): set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
V/AudioTrack( 6092): set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
V/AudioSystem( 1867): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1867): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 6092): ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
V/AudioSystem( 6092): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 6092): ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
V/AudioPolicyManager(  319): getOutputForAttr() usage=3, content=4, tag= flags=00000000
V/AudioPolicyManager(  319): getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  319): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  319): getOutput() returns output 2
I/AudioFlinger(  319): isAudioPlaybackHookOn() false
V/AudioSystem( 3252): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 3252): ioConfigChanged() opening already existing output! 2
V/AudioPolicyManager(  319): getOutputForAttr() usage=3, content=4, tag= flags=00000000
,V/AudioPolicyManager(  319): getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
V/AudioPolicyManagerEx(  319): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  319): getOutput() returns output 2
V/AudioSystem( 6092): getLatency() output 2, latency 50
V/AudioSystem( 6092): getFrameCount() output 2, frameCount 960
V/AudioTrack( 6092): createTrack_l() output 2 afLatency 50
V/AudioFlinger(  319): [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
V/AudioSystem( 1456): ioConfigChanged() event 0, ioHandle 2
V/AudioFlinger(  319): [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
V/AudioFlinger(  319): [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
V/AudioSystem( 1456): ioConfigChanged() opening already existing output! 2
V/AudioFlinger(  319): [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
V/AudioFlinger(  319): createTrack() lSessionId: 16
V/AudioSystem( 1456): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1456): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 2154): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 2154): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 3252): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 3252): ioConfigChanged() opening already existing output! 4
V/AudioTrack( 6092): AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
V/AudioFlinger(  319): acquiring 16 from 6092, for 6092
V/AudioFlinger(  319):  added new entry for 16
V/ToneGenerator( 6092): ToneGenerator INIT OK, time: 114148
D/BluetoothAdapterService( 6092): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c550bd2
D/HeadsetStateMachine( 6092): Enter Disconnected: -2, size: 0
V/AudioSystem( 2154): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 2154): ioConfigChanged() opening already existing output! 4
D/HeadsetPhoneState( 6092): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 6092): [BTUI] listenForMultiSimPhoneState : start = false
D/BluetoothAdapterService( 6092): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c550bd2
D/HeadsetStateMachine( 6092): [BTUI] change sampling rate to 8000 when device is disconnected
V/AudioFlinger(  319): setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6092
D/audio_hw_primary(  319): adev_set_parameters: enter: bt_samplerate=8000
V/voice   (  319): voice_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  319): voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  319): voice_extn_compress_voip_set_parameters: exit
V/voice   (  319): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  319): LGE_platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  319): platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  319): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  319): lge_platform_set_loopback_parameters: enter: 
V/audio_hw_primary(  319): adev_set_parameters: exit with code(0)
E/audio_a2dp_hw(  319): adev_set_parameters: ERROR: set param called even when stream out is null
V/ToneGenerator( 6092): ToneGenerator destructor
V/ToneGenerator( 6092): stopTone
V/ToneGenerator( 6092): Delete Track: 0xb4928080
V/AudioTrack( 6092): ~AudioTrack, releasing session id from 6092 on behalf of 6092
V/AudioFlinger(  319): releasing 16 from 6092 for 6092
V/AudioFlinger(  319):  decremented refcount to 0
V/AudioFlinger(  319): purging stale effects
D/BluetoothA2dp( 1030): Proxy object connected
V/AudioPolicyService(  319): AudioCommandThread() adding release output 2
V/AudioPolicyService(  319): inserting command: 6 at index 0, num commands 0
V/AudioPolicyService(  319): AudioCommandThread() waking up
V/AudioPolicyService(  319): AudioCommandThread() processing release output 2
V/AudioPolicyManager(  319): releaseOutput() 2
V/AudioPolicyService(  319): AudioCommandThread() going to sleep
V/AudioFl,inger(  319): PlaybackThread::Track destructor
V/AudioFlinger(  319): removeClient_l() pid 6092, calling pid 319
D/A2dpService( 6092): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 6092): classInitNative: succeeds
V/Avrcp   ( 6092): make
D/Avrcp   ( 6092): [BTUI] Use Native AVRCP : init jni
I/bluedroid-qcom( 6092): get_profile_interface avrcp
I/wpa_supplicant( 6160): rfkill: Cannot open RFKILL control device
I/wpa_supplicant( 6160): [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
W/Process ( 1030): Unable to open /proc/6163/status
V/AudioManager( 6092): registerRemoteController: size of Media player list: 0
,E/AudioManager( 6092): No RCC entry present to update
E/RemoteController( 6092): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothAvrcpQcomServiceJni( 6092): classInitQcomNative: succeeds
D/LGBluetoothAvrcpQcomAdapter( 6092): [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
I/BluetoothAvrcpQcomServiceJni( 6092): initQcomNative: succeeds
D/LGBluetoothAvrcpQcomAdapter( 6092): [BTUI] [+] updateMediaPlayerInfo
D/UsbSettingsReceiver( 6142): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6142): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6142): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6142): [AUTORUN] persist.sys.usb.config = ptp_only,adb
,E/WifiStateMachine( 1030): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1030): useWiFiOffloading() : false
E/WifiStateMachine( 1030): CONFIG_LGE_WLAN_PATH : true
D/UsbSettingsReceiver( 6142): [AUTORUN] onReceive() : app userid = 0, current userid = 0
,D/WifiMonitor( 1030): startMonitoring(wlan0) with mConnected = false
D/WifiMonitor( 1030): connecting to supplicant
I/WifiServerServiceExt( 1030): WIFI_STATE_CHANGED_ACTION [2]
V/WfdStateTracker( 1963): WfdStateTracker handleDirectStateChangedEvent: 1
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
D/UsbSettingsControl( 6142): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6142): [AUTORUN] onReceive() : availableList=[]
,D/UsbSettingsReceiver( 6142): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6142): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6142): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 6142): [AUTORUN] setTetherStatus() : status=false
I/ActivityManager( 1030): Killing 5752:com.google.android.partnersetup/u0a8 (adj 15): empty #17
V/SIM_STK ( 1030): Menu title from STK is T-Mobile
V/SIM_STK ( 1030): Menu title from STK is T-Mobile
,I/wpa_supplicant( 6160): rfkill: Cannot open RFKILL control device
,W/ActivityManager( 1030): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
W/libprocessgroup( 1030): failed to open /acct/uid_10008/pid_5752/cgroup.procs: No such file or directory
,D/UsbSettingsReceiver( 6142): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6142): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6142): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6142): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6142): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 6142): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6142): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 6142): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6142): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6142): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 6142): [AUTORUN] setTetherStatus() : status=false
D/LGBluetoothAvrcpQcomAdapter( 6092): [BTUI] installed app name: Music
,D/LGBluetoothAvrcpQcomAdapter( 6092): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6092): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 6092): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 6092): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 6092): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6092): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 6092): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6092): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 6092): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6092): [BTUI] [-] updateMediaPlayerInfo
I/BluetoothA2dpServiceJni( 6092): classInitNative
I/BluetoothA2dpServiceJni( 6092): classInitNative: succeeds
D/A2dpStateMachine( 6092): make
I/bluedroid-qcom( 6092): get_profile_interface a2dp
I/GKI_LINUX( 6092): gki_task_entry task_id=2 [A2DP-MEDIA] starting
I/LGBluetoothA2dpServiceJni( 6092): classInitNative: succeeds
I/LGBluetoothA2dpAdapter( 6092): [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
,D/BluetoothAdapterService( 6092): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c550bd2
I/wpa_supplicant( 6160): [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
I/BluetoothHidServiceJni( 6092): classInitNative: succeeds
I/wpa_supplicant( 6160): p2p0: CTRL-EVENT-AVOID-FREQ ranges=
I/wpa_supplicant( 6160): wlan0: CTRL-EVENT-SCAN-STARTED 
D/A2dpStateMachine( 6092): Enter Disconnected: -2
D/HidService( 6092): Received start request. Starting profile...
I/bluedroid-qcom( 6092): get_profile_interface hidhost
D/BluetoothAdapterService( 6092): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c550bd2
I/BluetoothHealthServiceJni( 6092): classInitNative: succeeds
E/WifiStateMachine( 1030):  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
E/WifiStateMachine( 1030):  SupplicantStartingState CMD_START_DRIVER 0 0
D/HealthService( 6092): Received start request. Starting profile...
E/WifiStateMachine( 1030):  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
E/WifiStateMachine( 1030):  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
E/WifiStateMachine( 1030):  SupplicantStartingState CMD_DISCONNECT 0 0
,E/WifiStateMachine( 1030):  DefaultState CMD_DISCONNECT 0 0
,E/WifiStateMachine( 1030):  SupplicantStartingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1030):  DefaultState CMD_RECONNECT 0 0
E/WifiStateMachine( 1030):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
D/WifiNative-wlan0( 1030): doString: [DRIVER MACADDR]
I/bluedroid-qcom( 6092): get_profile_interface health
D/WifiNative-wlan0( 1030):    returned Macaddr = c4:9a:02:7b:60:ac
I/LGBluetoothHealthServiceJni( 6092): classInitNative: succeeds
D/BluetoothAdapterService( 6092): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c550bd2
D/WifiStateMachine( 1030): MAC Addr from driver = c4:9a:02:7b:60:ac
D/WifiOffDelayIfNotUsed( 1030): setPowerSaveActivated(false)
I/BluetoothPanServiceJni( 6092): classInitNative(L105): succeeds
D/WifiMonitor( 1030): Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
D/WifiMonitor( 1030): Dropping event because (p2p0) is stopped
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=0 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1030): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1030): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/PanService( 6092): Received start request. Starting profile...
D/BluetoothPanServiceJni( 6092): initializeNative(L110): pan
I/bluedroid-qcom( 6092): get_profile_interface pan
I/ActivityManager( 1030): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6174 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,E/WifiStateMachine( 1030): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1030): useWiFiOffloading() : false
E/WifiStateMachine( 1030): CONFIG_LGE_WLAN_PATH : true
I/LGBluetoothPanAdapter( 6092): [BTUI] getInstance : create [LGBluetoothPanAdapter]
D/WifiNative-wlan0( 1030): doBoolean: SET update_config 1
D/BluetoothAdapterService( 6092): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c550bd2
D/WifiNative-wlan0( 1030): SET update_config 1: returned true
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiConfigStore( 1030): Loading config and enabling all networks 
I/BtGatt.JNI( 6092): classInitNative(L901): classInitNative: Success!
I/WifiServerServiceExt( 1030): WIFI_STATE_CHANGED_ACTION [3]
D/WifiNative-wlan0( 1030): doString: [LIST_NETWORKS]
D/WifiNative-wlan0( 1030):    returned network id / ssid / bssid / flags 0	NG700	any	
I/WifiServerServiceExt( 1030): batteryPsActivateMsgHandler : state:0 event:3
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WfdService( 1963): Waiting for WifiP2p enabling
D/BtGatt.DebugUtils( 6092): handleDebugAction() action=null
D/BtGatt.GattService( 6092): Received start request. Starting profile...
D/BtGatt.GattService( 6092): start()
I/bluedroid-qcom( 6092): get_profile_interface gatt
D/BtGatt.AdvertiseManager( 6092): advertise manager created
E/WifiConfigStore( 1030): readNetworkVariablesFromSupplicantFile key=psk
D/BluetoothAdapterService( 6092): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c550bd2
,D/BluetoothAdapterService( 6092): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c550bd2
I/LGBluetoothMapAdapter( 6092): [BTUI] getInstance : create [LGBluetoothMapAdapter]
V/BluetoothMapService( 6092): BluetoothMapBinder()
D/BluetoothMapService( 6092): Received start request. Starting profile...
D/BluetoothMapService( 6092): start()
E/WifiConfigStore( 1030): readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
E/WifiConfigStore( 1030): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
D/WifiStateMachine( 1030): enableVerboseLogging : level 2
D/WifiNative-wlan0( 1030): doBoolean: SET device_name g3_global_com
D/BluetoothMapEmailSettingsLoader( 6092): Found 0 applications
D/BluetoothMapEmailAppObserver( 6092): createReceiver()
D/WifiNative-wlan0( 1030): SET device_name g3_global_com: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET manufacturer LGE
D/WifiNative-wlan0( 1030): SET manufacturer LGE: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET model_name LG-D855
D/WifiNative-wlan0( 1030): SET model_name LG-D855: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET model_number LG-D855
D/WifiNative-wlan0( 1030): SET model_number LG-D855: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET serial_number LGD8553bed2d08
D/BluetoothMapEmailAppObserver( 6092): initObservers()
D/BluetoothMapEmailAppObserver( 6092): getEnabledAccountItems()
D/WifiNative-wlan0( 1030): SET serial_number LGD8553bed2d08: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET config_methods physical_display virtual_push_button
D/WifiNative-wlan0( 1030): SET config_methods physical_display virtual_push_button: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET device_type 10-0050F204-5
,D/WifiNative-wlan0( 1030): SET device_type 10-0050F204-5: returned true
D/WifiStateMachine( 1030): Setting OUI to DA-A1-19
D/WifiNative-wlan0( 1030): doBoolean: SCAN_INTERVAL 120
D/WifiNative-wlan0( 1030): SCAN_INTERVAL 120: returned true
D/WifiNative-HAL( 1030): Setting external_sim to 1
D/WifiNative-wlan0( 1030): doBoolean: SET external_sim 1
D/WifiNative-wlan0( 1030): SET external_sim 1: returned true
I/WifiNative-HAL( 1030): startHal
E/wifi    ( 1030): getStaticLongField sWifiHalHandle 0x989398dc
E/WifiHAL ( 1030): Could not connect handle
D/wifi    ( 1030): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x10228e
I/WifiNative-HAL( 1030): Could not start hal
D/WifiStateMachine( 1030): Setting OUI to DA-A1-19
I/WifiNative-HAL( 1030): startHal
E/wifi    ( 1030): getStaticLongField sWifiHalHandle 0x9893985c
E/WifiHAL ( 1030): Could not connect handle
D/wifi    ( 1030): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x102292
I/WifiNative-HAL( 1030): Could not start hal
D/WifiNative-wlan0( 1030): doBoolean: STA_AUTOCONNECT 1
D/WifiNative-wlan0( 1030): STA_AUTOCONNECT 1: returned true
D/WifiNative-wlan0( 1030): doBoolean: DRIVER BTCOEXSCAN-STOP
I/wpa_supplicant( 6160): wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
D/WfdsService( 1963): Supplicant Connection state is changed : true
,D/WfdsService( 1963): DefaultState - WIFI_SUPPLICANT_CONNECTED
D/WfdsService( 1963): Set the WFDS Monitor: true
D/WifiNative-wlan0( 1030): DRIVER BTCOEXSCAN-STOP: returned true
D/WfdsMonitor( 1963): WfdsMonitorThread create
D/WfdsMonitor( 1963): WFDS Monitor is created and started
D/WfdsService( 1963): WiFi: Supplicant connection re-established
D/WifiNative-wlan0( 1030): doBoolean: DRIVER RXFILTER-STOP
I/wpa_supplicant( 6160): wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
D/WifiNative-wlan0( 1030): DRIVER RXFILTER-STOP: returned true
D/WifiNative-wlan0( 1030): doBoolean: DRIVER RXFILTER-REMOVE 3
I/wpa_supplicant( 6160): wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
D/WifiNative-wlan0( 1030): DRIVER RXFILTER-REMOVE 3: returned true
D/WifiNative-wlan0( 1030): doBoolean: DRIVER RXFILTER-START
I/wpa_supplicant( 6160): wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
D/WifiNative-wlan0( 1030): DRIVER RXFILTER-START: returned true
D/WifiNative-wlan0( 1030): doBoolean: DRIVER RXFILTER-STOP
I/wpa_supplicant( 6160): wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
D/WifiHS20( 1030): hidePasspointNotification off =false
D/WifiNative-wlan0( 1030): DRIVER RXFILTER-STOP: returned true
D/WifiNative-wlan0( 1030): doBoolean: DRIVER RXFILTER-REMOVE 2
I/wpa_supplicant( 6160): android_multicast_filter_startstop : multicast filter set
D/WifiNative-wlan0( 1030): DRIVER RXFILTER-REMOVE 2: returned true
D/WifiNative-wlan0( 1030): doBoolean: DRIVER RXFILTER-START
I/wpa_supplicant( 6160): wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiNative-wlan0( 1030): DRIVER RXFILTER-START: returned true
E/WifiNative: ( 1030): [114,407,648 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
D/WifiNative-wlan0( 1030): doBoolean: RECONNECT
D/WifiNative-wlan0( 1030): RECONNECT: returned true
D/WifiNative-wlan0( 1030): doString: [STATUS]
D/BluetoothAdapterService( 6092): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c550bd2
D/HeadsetStateMachine( 6092): Proxy object connected
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=1 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
I/StatusBar.NetworkController( 1456): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1456): mWifiConnected = false, mWifiLevel = 0
D/LGBluetoothHfpAdapter( 6092): [BTUI] queryPhoneState
D/WifiNative-wlan0( 1030):    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
D/LGBluetoothHfpAdapter( 6092): Try to query the phonestate on bind
D/WifiNative-wlan0( 1030): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 6160): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1030): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET ps 1
D/WifiNative-wlan0( 1030): SET ps 1: returned true
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
D/LGWifiP2pService( 1030): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  314): Setting iface cfg
D/CommandListener(  314): Trying to bring up p2p0
D/WifiMonitor( 1030): startMonitoring(p2p0) with mConnected = true
D/LGWifiP2pService( 1030): P2pEnablingState
D/LGWifiP2pService( 1030): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2p socket connection successful
D/LGWifiP2pService( 1030): P2pEnabledState
D/HeadsetStateMachine( 6092): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 6092): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 6092): Disconnected process message: 11, size: 0
V/WfdStateTracker( 1963): WfdStateTracker handleDirectStateChangedEvent: 2
D/WfdsService( 1963): WifiP2pState is changed : true
D/WfdsService( 1963): Receive the WFDS_ENABLE Method
D/WfdsService( 1963): Set the WFDS Monitor: true
D/WfdsService( 1963): Connected to the supplicant for wfds
D/WfdsJNI ( 1963): doCommand: WFDS_SET TRUE
E/CtrlSupplicant( 1963): Not connected to wap_supplicant - "WFDS_SET TRUE" command dropped.
D/WfdsJNI ( 1963): wfds_send_command: [WFDS_SET TRUE] failed
D/WfdsJNI ( 1963): doCommand: WFDS_GET_MAC_ADDRESS
E/CtrlSupplicant( 1963): Not connected to wap_supplicant - "WFDS_GET_MAC_ADDRESS" command dropped.
D/WfdsJNI ( 1963): wfds_send_command: [WFDS_GET_MAC_ADDRESS] failed
D/WfdsJNI ( 1963): doCommand: IFNAME=wlan0 GET_CAPABILITY channels
E/CtrlSupplicant( 1963): Not connected to wap_supplicant - "IFNAME=wlan0 GET_CAPABILITY channels" command dropped.
D/WfdsJNI ( 1963): wfds_send_command: [IFNAME=wlan0 GET_CAPABILITY channels] failed
D/WfdsService( 1963): selectPreferredScanChannel [0]
D/WfdsService( 1963): STATE : WfdsEnabledState - enter: this device mac null
D/BluetoothAdapterService( 6092): Profile still not running:com.android.bluetooth.gatt.GattService
V/BluetoothPbapReceiver( 6092): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 6092): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6092): ***********state = 11
D/LGWifiP2pService( 1030): sending p2p connection changed broadcast
D/WifiNative-p2p0( 1030): doBoolean: SET persistent_reconnect 1
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
D/BluetoothAdapterService( 6092): Profile still not running:com.android.bluetooth.gatt.GattService
E/CtrlSupplicant( 1963): Access OK "@android:wpa_wlan0"
D/BluetoothPhoneService.BluetoothLTECall( 1867):  call mBluetoothHeadset.phoneStateChanged()
,W/BluetoothHeadset( 1867): Proxy not attached to service
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
E/CtrlSupplicant( 1963): Succeed to open control connection
E/CtrlSupplicant( 1963): Succeed to open monitor connection
D/WfdsMonitor( 1963): Supplicant connection established
D/BluetoothAdapterService( 6092): Profile still not running:com.android.bluetooth.gatt.GattService
D/WfdsService( 1963): Received the Event that WfdsMonitor is connected to supplicant
D/BluetoothAdapterService( 6092): Profile still not running:com.android.bluetooth.gatt.GattService
V/PanService( 6092): [BTUI] SIM Extra State :ABSENT
D/BluetoothAdapterService( 6092): Profile still not running:com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 6092): Profile still not running:com.android.bluetooth.map.BluetoothMapService
V/BluetoothMapService( 6092): Handler(): got msg=1
,D/BluetoothAdapterState( 6092): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid-qcom( 6092): enable
I/bt_hci_bdroid( 6092): init
I/GKI_LINUX( 6092): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 6092): btu_task pending for preload complete event
D/WifiService( 1030): New client listening to asynchronous messages
I/bt_vendor( 6092): bt-vendor : init
I/bt_vendor( 6092): bt-vendor : get_bt_soc_type
E/bt_vendor( 6092): get_bt_soc_type: Failed to get soc type
I/bt_vendor( 6092): init: Local BD Address : c0:64:73:54:3f:58
D/bt_userial_mct( 6092): userial_init
D/bt_hci_bdroid( 6092): set_power 1
I/bt_vendor( 6092): bt-vendor : BT_VND_OP_POWER_CTRL: On
I/bt_vendor( 6092): Starting hciattach daemon
I/bt_vendor( 6092): try to set true
W/sh      ( 6201): type=1400 audit(0.0:157): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/sh      ( 6201): type=1400 audit(0.0:158): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/ActivityManager( 1030): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6197 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
D/LGWifiP2pService( 1030): DeviceAddress: 02:9a:02:7b:60:ac
D/WifiNative-p2p0( 1030): doBoolean: P2P_FLUSH
E/WifiStateMachine( 1030):  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
E/WifiStateMachine( 1030):  DisconnectedState CMD_START_DRIVER 0 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_START_DRIVER 0 0
E/WifiStateMachine( 1030):  DriverStartedState CMD_START_DRIVER 0 0
,D/WifiScanningService( 1030): SCAN_AVAILABLE : 3
D/RttService( 1030): SCAN_AVAILABLE : 3
D/WifiScanningService( 1030): DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL( 1030): startHal
D/RttService( 1030): DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 1030):  DisconnectedState what:132106 1 0
D/WifiNative-p2p0( 1030): P2P_FLUSH: returned true
D/WifiNative-p2p0( 1030): doBoolean: P2P_SERVICE_FLUSH
D/WifiNative-p2p0( 1030): P2P_SERVICE_FLUSH: returned true
D/WifiNative-p2p0( 1030): doString: [LIST_NETWORKS]
D/WifiNative-p2p0( 1030):    returned network id / ssid / bssid / flags
D/WifiNative-p2p0( 1030): doBoolean: SAVE_CONFIG
E/WifiStateMachine( 1030):  ConnectModeState what:132106 1 0
E/WifiStateMachine( 1030):  DriverStartedState what:132106 1 0
I/WifiServerServiceExt( 1030): setWifiDualbandAPConnection band : 1
D/WfdsService( 1963): WIFI_P2P_CONNECTION_CHANGED_ACTION
I/qcom-bluetooth( 6208): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
D/WfdsService( 1963): isConnected: false
I/WfdStateTracker( 1963): handleP2pThisDeviceChanged
D/WfdsService( 1963): WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
E/wpa_supplicant( 6160): nWIFIDualbandAPConnection: 1
D/WfdsService( 1963): Update P2p Interface State: 3
E/WifiStateMachine( 1030):  DisconnectedState what:132096 -100 0
E/WifiStateMachine( 1030):  ConnectModeState what:132096 -100 0
E/WifiStateMachine( 1030):  DriverStartedState what:132096 -100 0
I/WifiServerServiceExt( 1030): set CMD_DISCONNECT_RSSI_LVL : -100
E/wpa_supplicant( 6160): disconnect_rssi_lvl: -100
D/WifiNative-p2p0( 1030): SAVE_CONFIG: returned true
D/LGWifiP2pService( 1030): sending p2p persistent groups changed broadcast
D/LGWifiP2pService( 1030): InactiveState
D/LGWifiP2pService( 1030): InactiveState{ when=-10ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2pEnabledState{ when=-10ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1030): doBoolean: DRIVER COUNTRY CZ
I/wpa_supplicant( 6160): wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
D/WifiNative-p2p0( 1030): DRIVER COUNTRY CZ: returned true
D/LGWifiP2pService( 1030): InactiveState{ when=-1ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2pEnabledState{ when=-1ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 6160): p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
I/wpa_supplicant( 6160): [LGE_PATCH] driver_cmd() country:CZ
I/wpa_supplicant( 6160): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
I/wpa_supplicant( 6160): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WfdsMonitor( 1963): Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
D/WfdsMonitor( 1963): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WfdsMonitor( 1963): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WifiMonitor( 1030): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
E/WifiMonitor( 1030): WifiMonitor:p2p0 cnt=2 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1030): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1030): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
D/WifiMonitor( 1030): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/wifi    ( 1030): getStaticLongField sWifiHalHandle 0x94e6c99c
E/WifiHAL ( 1030): Could not connect handle
D/wifi    ( 1030): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x1022b2
I/WifiNative-HAL( 1030): Could not start hal
E/WifiScanningService( 1030): could not start HAL
E/WifiStateMachine( 1030):  DisconnectedState CMD_SET_COUNTRY_CODE 1 0 cz
E/WifiStateMachine( 1030):  ConnectModeState CMD_SET_COUNTRY_CODE 1 0 cz
E/WifiStateMac,hine( 1030):  DriverStartedState CMD_SET_COUNTRY_CODE 1 0 cz
D/WifiNative-wlan0( 1030): doBoolean: DRIVER COUNTRY CZ
D/LGWifiP2pService( 1030): DefaultState{ when=-1ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 6160): wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
E/WifiMonitor( 1030): WifiMonitor:p2p0 cnt=3 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1030): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1030): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
I/wpa_supplicant( 6160): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
I/wpa_supplicant( 6160): [LGE_PATCH] driver_cmd() country:CZ
I/wpa_supplicant( 6160): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
I/wpa_supplicant( 6160): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WfdsMonitor( 1963): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WfdsMonitor( 1963): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WifiMonitor( 1030): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1030): WifiMonitor:p2p0 cnt=4 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1030): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1030): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
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
D/LGWifiP2pService( 1030): InactiveState{ when=-8ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2pEnabledState{ when=-8ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): DefaultState{ when=-8ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1030): No p2p device connected
D/LGWifiP2pService( 1030): InactiveState{ when=-8ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2pEnabledState{ when=-8ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): DefaultState{ when=-8ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): InactiveState{ when=-8ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2pEnabledState{ when=-8ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): DefaultState{ when=-8ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1030): DRIVER COUNTRY CZ: returned true
E/WifiStateMachine( 1030):  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine( 1030):  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
D/WifiNative-wlan0( 1030): doBoolean: DRIVER SETBAND 0
I/wpa_supplicant( 6160): wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
I/wpa_supplicant( 6160): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
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
E/WifiStateMachine( 1030):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=114481  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
I/StatusBar.NetworkController( 1456): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1456): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [SCANNING]
E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=114484  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine( 1030):  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1030):  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1030):  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1030):  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1030):  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
W/WfdsService( 1963): DefaultState - msg [9441285] is not handled
D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateSCANNING
I/qcom-bluetooth( 6222): /system/etc/init.qcom.bt.sh: Transport : smd 
,I/qcom-bluetooth( 6223): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
I/qcom-bluetooth( 6225): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
I/qcom-bluetooth( 6226): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
I/qcom-bluetooth( 6227): /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 6228): /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
I/libmdmdetect( 6230): ESOC framework not supported
E/Diag_Lib( 6230):  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,D/bthci_qcomm_linux( 6230): [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:64:C0)
D/bthci_qcomm_common( 6230): [BTUI] bt_hci_qcomm_init:
D/bthci_qcomm_common( 6230): [BTUI]     BDADDR: 58:3F:54:73:64:C0
D/bthci_qcomm_common( 6230): [BTUI]     BR/EDR: Class 1
D/bthci_qcomm_common( 6230): [BTUI]     LE: Class 2
D/bthci_qcomm_common( 6230): [BTUI]     Ref Clock: 32M
D/btqsocnvmtags( 6230): [BTUI] init_riva_entries: set NORMAL power settings
,I/art     ( 1030): Explicit concurrent mark sweep GC freed 35365(1819KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 1.470ms total 81.534ms
I/ActivityManager( 1030): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6236 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,W/FormManager( 6174): Network not available. Please check & try again.
E/ActivityThread( 6197): Failed to find provider info for com.lge.lgaccount.provider
,W/LG Account v2.2( 6197): No ProfileInfo entries
I/LG Account v2.2( 6197): isEnabled: false
I/Feature ( 6197): [Lifetracker]ver: 4.21.112(40211120)
I/Feature ( 6197): [Lifetracker]Country: EU
I/Feature ( 6197): [Lifetracker]Operator: OPEN
I/Feature ( 6197): [Lifetracker]Ranking support: false
I/Feature ( 6197): [Lifetracker]Comfort support: false
I/Feature ( 6197): [Lifetracker]Accessory: true
I/Feature ( 6197): [Lifetracker]Health device: true
I/Feature ( 6197): [Lifetracker]Extra Pedometer: false
I/Feature ( 6197): [Lifetracker]Blood glucose device: false
I/Feature ( 6197): [Lifetracker]Device Number: 3
,V/FormManager( 6174): Network unavailable.
V/FormManager( 6174): Network unavailable.
D/BluetoothPermissionRequest( 6142): onReceive
D/LGBluetoothFeatureConfig( 6142):  get() - isFeatureLoaded : false
I/ActivityManager( 1030): Killing 5428:com.lge.appbox.client/u0a11 (adj 15): empty #17
,I/rmt_storage(  308): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  308): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  308): wakelock acquired: 1, error no: 42
I/rmt_storage(  308): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
I/rmt_storage(  308): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
,I/rmt_storage(  308): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
I/rmt_storage(  308): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 22
I/rmt_storage(  308): 
,I/rmt_storage(  308): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
E/Diag_Lib(  901): [IMS_FATAL]| 3347 | 908 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
,W/libprocessgroup( 1030): failed to open /acct/uid_10011/pid_5428/cgroup.procs: No such file or directory
D/BluetoothManagerService( 1030): Message: 20
D/BluetoothManagerService( 1030): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3685fa6d:true
,D/LGBluetoothResetSettingReceiver( 6142): return without doing reset settings.
I/ActivityManager( 1030): Killing 5447:com.android.contacts/u0a19 (adj 15): empty #17
,E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=9 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1030): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1030): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
,E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=10 dispatchEvent: WPS-AP-AVAILABLE 
E/wpa_supplicant( 6160): USIM:  scard_init function
W/WifiMonitor( 1030): couldn't identify event type - WPS-AP-AVAILABLE 
I/wpa_supplicant( 6160): Trying to associate with SSID 'NG700'
E/WifiStateMachine( 1030):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine( 1030):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine( 1030):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine( 1030):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
I/WifiNative-HAL( 1030): startHal
E/wifi    ( 1030): getStaticLongField sWifiHalHandle 0x989398cc
E/WifiHAL ( 1030): Could not connect handle
D/wifi    ( 1030): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x50212e
I/WifiNative-HAL( 1030): Could not start hal
D/WifiNative-wlan0( 1030): doString: [BSS RANGE=0- MASK=0x21987]
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=11 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,D/PCSuite ( 6236): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/LGBluetoothOppAdapter( 6092): [BTUI] getInstance : create [LGBluetoothOppAdapter]
E/WifiStateMachine( 1030):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 11 0 rt=114893  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 11 0 rt=114893  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
W/libprocessgroup( 1030): failed to open /acct/uid_10019/pid_5447/cgroup.procs: No such file or directory
I/StatusBar.NetworkController( 1456): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1456): mWifiConnected = false, mWifiLevel = 0
,W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateASSOCIATING
I/StatusBar.NetworkController( 1456): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1456): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
,V/BluetoothFtpReceiver( 6092): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6092): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 6092): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 6092): SapReceiver onReceive 
V/BluetoothSapReceiver( 6092): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6092):  Bluetooth Adapter state = 11
I/wpa_supplicant( 6160): wlan0: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=12 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1030): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=13 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=14 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1030):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 12 0 rt=114940  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 12 0 rt=114940  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
I/wpa_supplicant( 6160): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=15 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/wpa_supplicant( 6160): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1030): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=16 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1030): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=17 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1030): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiStateMachine( 1030):  DisconnectedState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=114949
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=18 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1030):  ConnectModeState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=114949
E/WifiStateMachine( 1030):  DriverStartedState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=114949
V/WiFiOffLoadBroadcast( 6142): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=114951
E/WifiStateMachine( 1030):  DefaultState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=114951
E/WifiStateMachine( 1030):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 14 0 rt=114952  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
D/WifiService( 1030): New client listening to asynchronous messages
,I/ActivityManager( 1030): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6265 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 14 0 rt=114981  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
I/StatusBar.NetworkController( 1456): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1456): mWifiConnected = false, mWifiLevel = 0
D/Tethering( 1030): sendTetherStateChangedBroadcast 1, 0, 0
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1030):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 15 0 rt=114989  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 15 0 rt=114990  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
I/StatusBar.NetworkController( 1456): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1456): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1030):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=114991
E/WifiStateMachine( 1030):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=114991
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiNative-wlan0( 1030): doString: [STATUS]
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=19 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateASSOCIATED
D/WifiNative-wlan0( 1030):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
I/WifiServiceExtension( 1030): setVHTCapabilityType  : false
D/LgDataFeature( 6142): LgDataFeature() Constructor: none
D/LgDataFeature( 6142): LgDataFeature() Constructor Done, null
,I/WifiServerServiceExt( 1030): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK,
I/WifiServerServiceExt( 1030): setKeepAlivePacketInterval msec : 60
,D/WiFiOffLoadUpdatePriority( 6142): remove : truetruetrue
,I/StatusBar.NetworkController( 1456): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1456): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/StatusBar.NetworkController( 1456): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1456): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/ConnectivityService( 1030): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService( 1030): Got NetworkAgent Messenger
D/ConnectivityService( 1030): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1030): NetworkAgent connected
E/WifiConfigStore( 1030): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1030): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1030): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1030): doBoolean: SAVE_CONFIG
,D/WifiNative-wlan0( 1030): SAVE_CONFIG: returned true
E/WifiConfigStore( 1030): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1030): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1030): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1030): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1030): SAVE_CONFIG: returned true
D/CommandListener(  314): Setting iface cfg
D/DhcpStateMachine( 1030): StoppedState
D/DhcpStateMachine( 1030): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1030): WaitBeforeStartState
E/WifiStateMachine( 1030): Start Dhcp Watchdog 1
E/WifiStateMachine( 1030):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=115061  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1030):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=115061  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=115062  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
W/ResourcesManager( 6265): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateFOUR_WAY_HANDSHAKE
D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1030):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=115066  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1030):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=115067  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=115067  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1030):  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  ObtainingIpState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1030):  L2ConnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1030):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1030):  ObtainingIpState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:-1573067912] from screen [on:0 period:-1573067912]
I/ActivityManager( 1030): Killing 5774:com.lge.email/u0a23 (adj 15): empty #17
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1573067910]
I/WifiNative-HAL( 1030): startHal
E/wifi    ( 1030): getStaticLongField sWifiHalHandle 0x989398bc
E/WifiHAL ( 1030): Could not connect handle
D/wifi    ( 1030): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x302082
I/WifiNative-HAL( 1030): Could not start hal
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
D/AuthorizationBluetoothService( 2185): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/libprocessgroup( 1030): failed to open /acct/uid_10023/pid_5774/cgroup.procs: No such file or directory
D/ConnectivityService( 1030): updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
E/WifiStateMachine( 1030):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1030): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
E/WifiStateMachine( 1030):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=2,0,0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=2,0,0
D/WifiNative-wlan0( 1030): doBoolean: DRIVER SETSUSPENDMODE 0
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/wpa_supplicant( 6160): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
,D/WifiNative-wlan0( 1030): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET ps 0
D/WifiNative-wlan0( 1030): SET ps 0: returned true
D/WifiNative-wlan0( 1030): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 6160): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
,D/WifiNative-wlan0( 1030): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1030): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1030): Current State is mWaitBeforeStartState.
D/LGWifiP2pService( 1030): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2205d076 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2205d076 target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper( 1030): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
V/LgDhcpStateMachineHelper( 1030): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700" is not exist.
E/WifiStateMachine( 1030):  ObtainingIpState CMD_SAVE_CONFIG uid=1000 0 0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_SAVE_CONFIG uid=1000 0 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_SAVE_CONFIG uid=1000 0 0
D/WifiNative-wlan0( 1030): doBoolean: SAVE_CONFIG
D/DhcpStateMachine( 1030): WaitBeforeStartState{ when=-3ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/DhcpStateMachine( 1030): DHCP Start wake lock is acquired.
D/WifiServerServiceExt( 1030): setSupplicantStateCOMPLETED
D/WifiNative-wlan0( 1030): SAVE_CONFIG: returned true
D/WiFiOffLoadUpdatePriority( 6142): remove1
V/WiFiOffLoadSharedPrefsUtils( 6142): save remove
D/WiFiOffLoadBroadcast( 6142): mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
D/WiFiOffLoadBroadcast( 6142): S: false, R: false
,E/WifiStateMachine( 1030):  ObtainingIpState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1030):  L2ConnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
,E/WifiStateMachine( 1030):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/WiFiOffLoadUpdatePriority( 6142): saved SSID: "NG700"
D/WiFiOffLoadUpdatePriority( 6142): connected SSID: null
D/WiFiOffLoadUpdatePriority( 6142): private wpa: "NG700" 300
D/WifiServiceImplEx( 1030): addOrUpdateNetwork pid=6142, uid=1000, packageName=android.uid.system:1000
E/addOrUpdateNetwork( 1030):  uid = 1000 SSID "NG700" nid=0
E/WifiStateMachine( 1030):  ObtainingIpState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=2 any is current
E/WifiStateMachine( 1030):  L2ConnectedState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=2 any is current
E/WifiStateMachine( 1030):  ConnectModeState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=2 any is current
E/WifiConfigStore( 1030):  key="NG700"WPA_PSK netId=0 uid=0/1000
D/WifiServerServiceExt( 1030): addOrUpdateNetwork: mThisIsFirstEnableing = false
D/WifiNative-wlan0( 1030): doBoolean: SET_NETWORK 0 ssid 4e47373030
D/WifiNative-wlan0( 1030): SET_NETWORK 0 ssid 4e47373030: returned true
E/WifiConfigStore( 1030): Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1030): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1030): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET_NETWORK 0 key_mgmt WPA-PSK
D/WifiNative-wlan0( 1030): SET_NETWORK 0 key_mgmt WPA-PSK: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET_NETWORK 0 proto WPA RSN
,D/WifiNative-wlan0( 1030): SET_NETWORK 0 proto WPA RSN: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET_NETWORK 0 pairwise TKIP CCMP
D/WifiNative-wlan0( 1030): SET_NETWORK 0 pairwise TKIP CCMP: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET_NETWORK 0 group WEP40 WEP104 TKIP CCMP
D/WifiNative-wlan0( 1030): SET_NETWORK 0 group WEP40 WEP104 TKIP CCMP: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET_NETWORK 0 priority 300
,D/WifiNative-wlan0( 1030): SET_NETWORK 0 priority 300: returned true
E/WifiConfigStore( 1030): will read network variables netId=0
E/WifiConfigStore( 1030): writeIpAndProxyConfigurationsOnChange: "NG700" -> "NG700" path: /data/misc/wifi/ipconfig.txt
E/WifiConfigStore( 1030):  writeKnownNetworkHistory() num networks:1 needWrite=false
D/WiFiOffLoadUpdatePriority( 6142):  ssid "NG700" prio 300
D/WiFiOffLoadUpdatePriority( 6142): configuration updated: 0
E/WifiStateMachine( 1030):  ObtainingIpState CMD_SAVE_CONFIG uid=1000 0 0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_SAVE_CONFIG uid=1000 0 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_SAVE_CONFIG uid=1000 0 0
D/WifiNative-wlan0( 1030): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1030): SAVE_CONFIG: returned true
,D/WiFiOffLoadUpdatePriority( 6142): configuration saved: true
,I/ActivityManager( 1030): Killing 5469:com.android.gallery3d/u0a27 (adj 15): empty #17
W/libprocessgroup( 1030): failed to open /acct/uid_10027/pid_5469/cgroup.procs: No such file or directory
,D/DhcpStateMachine( 1030): DHCPV4 request on wlan0
,V/LgDhcpStateMachineHelper( 1030): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1030): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
D/PCSuite ( 6236): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
W/dhcpcd  ( 6295): type=1400 audit(0.0:159): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 6295): type=1400 audit(0.0:160): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/FormManager( 6174): Network not available. Please check & try again.
V/WiFiOffLoadBroadcast( 6142): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,V/FormManager( 6174): Network unavailable.
I/dhcpcd  ( 6295): version 5.5.6 starting
,E/dhcpcd  ( 6295): get_duid: m
D/dhcpcd  ( 6295): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 6295): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
V/FormManager( 6174): Network unavailable.
,D/WiFiOffLoadBroadcast( 6142): MCCMNC not supported: null
E/QC-QMI  ( 6230): qmi_client [6230] 13: failed to locate client data
E/QC-QMI  (  475): qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
E/QC-QMI  (  475): QMUX qmux_client_id=13 not found in qmux client list, unable to remove
D/LGDMClient( 3963): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,D/LGDMClient( 3963): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 3963): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 3963): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/PostponalbeReceiver( 5131): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6236): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6236): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6236): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6142): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/LGDMClient( 3963): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/LGDMClient( 3963): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 3963): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,D/WiFiOffLoadBroadcast( 6142): MCCMNC not supported: null
D/dhcpcd  ( 6295): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
,D/dhcpcd  ( 6295): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
I/ActivityManager( 1030): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6311 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
D/dhcpcd  ( 6295): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/dhcpcd  ( 6295): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 6295): wlan0: sending REQUEST (xid 0xe17d6e24), next in 3.85 seconds
I/qcom-bluetooth( 6321): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:64:c0 
,I/qcom-bluetooth( 6328): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,I/bt_vendor( 6092): bluetooth satus is on
D/bt_hci_bdroid( 6092): preload
D/bt_userial_mct( 6092): userial_open(port:0)
I/bt_vendor( 6092): bt-vendor : BT_VND_OP_USERIAL_OPEN
I/bt_vendor( 6092): Done intiailizing UART
I/bt_vendor( 6092): Done intiailizing UART
I/bt_userial_mct( 6092): CMD=66, EVT=66, ACL_Out=67, ACL_In=67
I/bt_vendor( 6092): Bluetooth Firmware and transport layer are initialized
D/bt_userial_mct( 6092): Entering userial_read_thread()
I/bt-btu  ( 6092): btu_task received preload complete event
W/bt-l2cap( 6092): L2CAP - L2CA_Register() called for PSM: 0x0001
W/bt-l2cap( 6092): L2CAP - L2CA_Register() called for PSM: 0x001f
W/bt-l2cap( 6092): L2CAP - L2CA_Register() called for PSM: 0x0003
I/        ( 6092): BTE_InitTraceLevels -- TRC_HCI
I/        ( 6092): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 6092): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 6092): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 6092): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 6092): BTE_InitTraceLevels -- TRC_A2D
I/        ( 6092): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 6092): BTE_InitTraceLevels -- TRC_BTM
,I/        ( 6092): BTE_InitTraceLevels -- TRC_HID_HOST
I/        ( 6092): BTE_InitTraceLevels -- TRC_GAP
I/        ( 6092): BTE_InitTraceLevels -- TRC_PAN
I/        ( 6092): BTE_InitTraceLevels -- TRC_SDP
I/        ( 6092): BTE_InitTraceLevels -- TRC_GATT
I/        ( 6092): BTE_InitTraceLevels -- TRC_SMP
I/        ( 6092): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 6092): BTE_InitTraceLevels -- TRC_BTIF
W/ResourcesManager( 6311): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/bt-btm  ( 6092): btm_decode_ext_features_page Secure conn Controller support Enabled
E/bt-btm  ( 6092): BTM_SecRegister:p_cb_info->p_le_callback == 0xa01d7061 
E/bt-btm  ( 6092): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01d7061 
E/bt-btif ( 6092): Calling BTA_HhEnable
E/bt-btif ( 6092): btif_storage_get_adapter_property service_mask:0x2140040
D/BluetoothAdapterProperties( 6092): Address is:58:3F:54:73:64:C0
W/bt-l2cap( 6092): L2CAP - L2CA_Register() called for PSM: 0x0019
W/bt-l2cap( 6092): L2CAP - L2CA_Register() called for PSM: 0x0017
W/bt-l2cap( 6092): L2CAP - L2CA_Register() called for PSM: 0x001b
W/bt-l2cap( 6092): L2CAP - L2CA_Register() called for PSM: 0x0011
W/bt-l2cap( 6092): L2CAP - L2CA_Register() called for PSM: 0x0013
D/BluetoothManagerService( 1030): Bluetooth Adapter name changed to G3-1
D/BluetoothManagerService( 1030): Stored Bluetooth name: G3-1
D/BluetoothAdapterProperties( 6092): Name is: G3-1
D/BluetoothAdapterProperties( 6092): Scan Mode:20
D/BluetoothAdapterProperties( 6092): Discoverable Timeout:120
D/bt_hci_bdroid( 6092): postload
W/bt-l2cap( 6092): L2CAP - L2CA_Register() called for PSM: 0x000f
D/bt_hci_bdroid( 6092): Used up Tx Cmd credits
,D/bt_hci_bdroid( 6092): Used up Tx Cmd credits
D/bt_hci_bdroid( 6092): Used up Tx Cmd credits
W/bt-smp  ( 6092): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6092): Plain text(LSB ~ MSB) = 34 fc 42 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6092): Encrypted text(LSB ~ MSB) = ab 7a c8 aa b4 62 bf 11 b5 7c fb 45 1a 1e 1f eb 
D/bt_hci_bdroid( 6092): Used up Tx Cmd credits
W/bt-btm  ( 6092): Stopping oneshot timer
E/bt_mct  ( 6092): hci lib postload completed
D/bte_conf( 6092): Device ID record 1 : primary
D/bte_conf( 6092):   vendorId            = 00c4
D/bte_conf( 6092):   vendorIdSource      = 0001
,D/bte_conf( 6092):   product             = 13a1
D/bte_conf( 6092):   version             = 1000
D/bte_conf( 6092):   clientExecutableURL = 
D/bte_conf( 6092):   serviceDescription  = 
D/bte_conf( 6092):   documentationURL    = 
D/bte_conf( 6092): bte_load_did_conf no section named DID2.
D/BluetoothPanServiceJni( 6092): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothAdapterState( 6092): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 6092): ScanMode =  20
D/BluetoothAdapterProperties( 6092): State =  11
D/BluetoothAdapterProperties( 6092): mDiscoverableTimeout = 120
V/LGBluetoothServiceAdapter( 6092): [BTUI] state:11, scanmode:20, timeout:120
D/BluetoothAdapterProperties( 6092): Setting state to 12
I/BluetoothAdapterState( 6092): Bluetooth adapter state changed: 11-> 12
D/BluetoothManagerService( 1030): Message: 60
D/BluetoothManagerService( 1030): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService( 1030): Broadcasting onBluetoothStateChange(true) to 5 receivers.
D/BluetoothA2dp( 1030): onBluetoothStateChange: up=true
W/sh      ( 6335): type=1400 audit(0.0:161): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/sh      ( 6335): type=1400 audit(0.0:162): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/btif_config_util( 6092): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
I/BluetoothAdapterState( 6092): Entering On State
D/LGBluetoothServiceAdapter( 6092): [BTUI] OnState
D/LGBluetoothServiceAdapter( 6092): [BTUI]         global_name: G3-1
D/LGBluetoothServiceAdapter( 6092): [BTUI]         local_name: G3-1
D/BluetoothAdapterService( 6092): [BTUI] autoConnect() : not allowed
,D/BluetoothHeadset( 1867): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1867): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1030): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1867): onBluetoothStateChange: up=true
W/bt-smp  ( 6092): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6092): Plain text(LSB ~ MSB) = 45 93 74 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6092): Encrypted text(LSB ~ MSB) = 6e a0 39 a1 07 9b a3 b1 f8 9d 52 c7 45 35 b5 e9 
W/bt-btm  ( 6092): Stopping oneshot timer
E/BluetoothManagerService( 1030): Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
D/BluetoothManagerService( 1030): Bluetooth State Change Intent: 11 -> 12
D/BluetoothManagerService( 1030): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/LGBluetoothAPIService( 1963): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
I/[SystemUI]BluetoothHandler( 1456): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
D/LGBluetoothAPIService( 1963): Message: 1
D/LGBluetoothAPIService( 1963): MESSAGE_BOOT_COMPLETED
D/BluetoothManagerService( 1030): Message: 40
D/BluetoothManagerService( 1030): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
I/LGBluetoothAPIService( 1963): [BTUI] LGBluetoothAPIService Binding Success
I/BluetoothMapService( 6092): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 6092): STATE_ON
W/bt-smp  ( 6092): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6092): Plain text(LSB ~ MSB) = 15 05 5b 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6092): Encrypted text(LSB ~ MSB) = c8 e5 d0 70 bc e5 f4 c3 b4 ba 9f 54 76 6e 80 25 
W/bt-btm  ( 6092): Stopping oneshot timer
,W/bt-smp  ( 6092): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6092): Plain text(LSB ~ MSB) = e9 63 41 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6092): Encrypted text(LSB ~ MSB) = 79 99 1d 84 45 25 f1 56 8e 17 4f d0 3d 87 85 05 
W/bt-btm  ( 6092): Stopping oneshot timer
D/BluetoothAdapterService( 6092): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c550bd2
V/BluetoothPbapService( 6092): Pbap Service onCreate
V/BluetoothPbapService( 6092): Starting PBAP service
,D/LGBluetoothPbapAdapter( 6092): [BTUI] getInstance : create
V/BluetoothPbapService( 6092): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 6092): state: 12
W/ContextImpl( 6142): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
D/LGBluetoothAPIServer( 6092): [BTUI] onCreate()
D/LGBluetoothAPIServer( 6092): [BTUI] onBind()
V/BluetoothMapService( 6092): Handler(): got msg=1
D/LGBluetoothAPIService( 1963): [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
D/LGBluetoothAPIService( 1963): Message: 100
D/LGBluetoothAPIService( 1963): MESSAGE_BLUETOOTH_SERVICE_CONNECTED
D/BluetoothMapMasInstance( 6092): Map Service startRfcommSocketListener
V/BluetoothPbapService( 6092): Handler(): got msg=1
D/BluetoothMapMasInstance( 6092): MAS initSocket()
V/BluetoothPbapService( 6092): Pbap Service startRfcommSocketListener
,V/BluetoothPbapReceiver( 6092): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 6092): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6092): ***********state = 12
V/BluetoothPbapService( 6092): Pbap Service initSocket
D/BluetoothManagerService( 1030): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/qcom-bt-wlan-coex( 6342): /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
D/LGBluetoothDeviceModeControllManager( 6092): [BTUI] checkDeviceModeAndSet, sinkMode : false
W/bt-smp  ( 6092): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6092): Plain text(LSB ~ MSB) = 7c 95 58 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6092): Encrypted text(LSB ~ MSB) = 76 64 63 9c 21 62 ff cb 4c 9b c6 e6 14 ff 03 b0 
W/bt-btm  ( 6092): Stopping oneshot timer
W/BluetoothAdapter( 6092): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothMapMasInstance( 6092):   masId = 00
D/BluetoothMapMasInstance( 6092):   msgTypes = 0e
D/BluetoothMapMasInstance( 6092):   masName = SMS/MMS
D/BluetoothMapMasInstance( 6092):   SDP string = 000eSMS/MMS
D/BluetoothManagerService( 1030): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/LGBluetoothServiceAdapter( 6092): [BTUI] createSocketChannel FD=73 mFd=0
W/BluetoothAdapter( 6092): getBluetoothService() called with no BluetoothManagerCallback
V/BluetoothPbapService( 6092): Succeed to create listening socket 
V/BluetoothPbapService( 6092): Accepting socket connection...
D/LGBluetoothServiceAdapter( 6092): [BTUI] createSocketChannel FD=75 mFd=73
V/BluetoothMapMasInstance( 6092): Succeed to create listening socket 
D/BluetoothMapMasInstance( 6092): Accepting socket connection...
,D/LocalBluetoothProfileManager( 6142): Adding local A2DP profile
D/BluetoothManagerService( 1030): Message: 30
,D/LocalBluetoothProfileManager( 6142): Adding local HEADSET profile
D/BluetoothManagerService( 1030): Message: 30
D/QRemote ( 6311): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
D/BluetoothManagerService( 1030): Message: 30
D/BluetoothManagerService( 1030): Message: 30
,D/LocalBluetoothProfileManager( 6142): Adding local MAP profile
D/BluetoothMap( 6142): Create BluetoothMap proxy object
D/BluetoothManagerService( 1030): Message: 30
D/BluetoothManagerService( 1030): Message: 30
V/BluetoothPbapService( 6092): Pbap Service onBind
D/LocalBluetoothProfileManager( 6142): LocalBluetoothProfileManager construction complete
D/LGBluetoothUserBindClient( 6142): [BTUI] initUserBindClient
,W/ContextImpl( 6142): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
D/DockEventReceiver( 6142): finishStartingService: stopping service
D/BluetoothA2dp( 6142): Proxy object connected
D/A2dpProfile( 6142): Bluetooth service connected
D/QRemote ( 6311): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,I/QRemote ( 6311): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 6311): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 6311): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 6311): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 6311): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 6311): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6311): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6311): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/BluetoothHeadset( 6142): Proxy object connected
D/HeadsetProfile( 6142): Bluetooth service connected
,D/BluetoothInputDevice( 6142): Proxy object connected
D/HidProfile( 6142): Bluetooth service connected
D/BluetoothPan( 6142): BluetoothPAN Proxy object connected
D/PanProfile( 6142): Bluetooth service connected
I/QRemote ( 6311): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/BluetoothMap( 6142): Proxy object connected
D/MapProfile( 6142): Bluetooth service connected
D/BluetoothMap( 6142): getConnectedDevices()
V/BluetoothMapService( 6092): getConnectedDevices()
V/[BNRBootReceiver]( 5929): boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/BNRAndroBeam( 5929): [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
D/BluetoothAdapterProperties( 6092): Discoverable Timeout:120
D/LGBluetoothDeviceModeControllManager( 6092): adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
D/BluetoothPbap( 6142): Proxy object connected
D/PbapServerProfile( 6142): Bluetooth service connected
D/LGBluetoothUserBindClient( 6142): [BTUI] onServiceConnected
D/BluetoothAdapterProperties( 6092): Scan Mode:21
D/LGBluetoothDeviceModeControllManager( 6092): getDeviceMode  deviceMode 0
D/BluetoothPermissionRequest( 6142): onReceive
V/[BNRBootReceiver]( 5929): Boot Receiver Return
D/PostponalbeReceiver( 5131): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/LGBluetoothFeatureConfig( 6142): isPrivacyLogsEnabled : true
D/LGBluetoothUtils( 6142): [BTUI] FileNotFound: readProperty
,D/QRemote ( 6311): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
D/LGBluetoothResetSettingReceiver( 6142): return without doing reset settings.
D/QRemote ( 6311): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
V/WiFiOffLoadBroadcast( 6142): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
V/BluetoothOppReceiver( 6092): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
I/LGBluetoothOppAdapter( 6092): [BTUI] startOppService()
D/WiFiOffLoadBroadcast( 6142): MCCMNC not supported: null
D/QRemote ( 6311): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6311): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6311): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/BluetoothOppManager( 6092): restoreApplicationData! falsefalsenullnull
V/WiFiOffLoadBroadcast( 6142): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
D/WiFiOffLoadBroadcast( 6142): Not supported operator for automatic switch
D/PostponalbeReceiver( 5131): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6142): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/LGBluetoothFeatureConfig( 6092): isPrivacyLogsEnabled : true
V/BtOppService( 6092): onCreate
V/BluetoothOppNotification( 6092): send message
V/BtOppService( 6092): Starting RfcommListener
D/WiFiOffLoadBroadcast( 6142): MCCMNC not supported: null
D/BluetoothOppPreference( 6092): Dumping Names:  
D/BluetoothOppPreference( 6092): {}
D/BluetoothOppPreference( 6092): Dumping Channels:  
D/BluetoothOppPreference( 6092): {}
V/BtOppService( 6092): onStartCommand
V/BluetoothFtpReceiver( 6092): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpReceiver( 6092): BluetoothFtpReceiver Start Service
,V/BtOppService( 6092): Deleted complete outbound shares, number =  0
D/QRemote ( 6311): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6311): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
V/BluetoothOppNotification( 6092): new notify threadi!
V/BtOppService( 6092): Deleted complete inbound failed shares, number = 0
V/BluetoothOppNotification( 6092): send delay message
V/BtOppService( 6092): start RfcommListener
I/QRemote ( 6311): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/BtOppService( 6092): RfcommListener started
V/BtOppService( 6092): ContentObserver received notification
V/BtOppRfcommListener( 6092): Starting RFCOMM listener....
V/BluetoothOppProvider( 6092): starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
V/BtOppService( 6092): pendingUpdate is true keepUpdateThread is false sListenStarted is true
V/BluetoothOppProvider( 6092): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
D/BluetoothManagerService( 1030): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6092): getBluetoothService() called with no BluetoothManagerCallback
D/PostponalbeReceiver( 5131): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/LGBluetoothServiceAdapter( 6092): [BTUI] createSocketChannel FD=78 mFd=75
V/BtOppRfcommListener( 6092): Started RFCOMM listener....
I/BtOppRfcommListener( 6092): Accept thread started.
V/BtOppRfcommListener( 6092): Accepting connection...
V/BluetoothOppProvider( 6092): created cursor android.database.sqlite.SQLiteCursor@21719a5c on behalf of 
V/BluetoothOppNotification( 6092): update too frequent, put in queue
V/BtOppService( 6092): pendingUpdate is true keepUpdateThread is false sListenStarted is true
,V/BluetoothOppProvider( 6092): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6092): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
V/WiFiOffLoadBroadcast( 6142): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
V/BluetoothOppProvider( 6092): created cursor android.database.sqlite.SQLiteCursor@198ef165 on behalf of 
V/BluetoothOppProvider( 6092): created cursor android.database.sqlite.SQLiteCursor@887be3a on behalf of 
D/BluetoothAdapterService( 6092): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c550bd2
V/BluetoothFtpService( 6092): Ftp Service onCreate
,I/BluetoothFtpService( 6092): Ftp Service onCreate
V/BluetoothFtpService( 6092): Ftp Service onStartCommand
V/BluetoothFtpService( 6092): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpService( 6092): Starting Listening on sockets
V/BtOppService( 6092): ContentObserver received notification
V/BluetoothSapReceiver( 6092): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 6092): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 6092): SapReceiver onReceive 
V/BluetoothSapReceiver( 6092): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6092):  Bluetooth Adapter state = 12
V/BluetoothSapReceiver( 6092): Calling SAP service start service with action = null
V/BluetoothFtpService( 6092): Handler(): got msg=1
V/BluetoothFtpService( 6092): Ftp Service startRfcommSocketListener
V/BluetoothFtpService( 6092): Ftp Service initSocket
D/BluetoothManagerService( 1030): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/AuthorizationBluetoothService( 2185): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
W/BluetoothAdapter( 6092): getBluetoothService() called with no BluetoothManagerCallback
V/BluetoothOppProvider( 6092): created cursor android.database.sqlite.SQLiteCursor@10ac0048 on behalf of 
V/BtOppService( 6092): pendingUpdate is true keepUpdateThread is false sListenStarted is true
D/LGBluetoothServiceAdapter( 6092): [BTUI] createSocketChannel FD=81 mFd=78
V/BluetoothFtpService( 6092): Succeed to create listening socket on channel 20
V/BluetoothFtpService:RfcommSocketAcceptThread( 6092): Run Accept thread
D/WiFiOffLoadBroadcast( 6142): MCCMNC not supported: null
D/QRemote ( 6311): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6311): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6311): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/BluetoothAdapterService( 6092): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c550bd2
V/BluetoothSapService( 6092): Sap Service onCreate
D/PostponalbeReceiver( 5131): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/BluetoothOppProvider( 6092): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
V/BluetoothSapService( 6092): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 6092): state: 12
V/BluetoothSapService( 6092): Starting SAP server process
V/BluetoothSapService( 6092): SAP Service startRfcommListenerThread
V/BluetoothOppProvider( 6092): created cursor android.database.sqlite.SQLiteCursor@37a4d8f4 on behalf of 
W/sapd    ( 6362): type=1400 audit(0.0:163): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
V/BluetoothSapService( 6092): Sap Service initRfcommSocket
W/sapd    ( 6362): type=1400 audit(0.0:164): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
V/BluetoothOppNotification( 6092): update too frequent, put in queue
V/BluetoothOppNotification( 6092): mUpdateCompleteNotification = true
D/BluetoothManagerService( 1030): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6092): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 6092): [BTUI] createSocketChannel FD=84 mFd=81
V/BluetoothSapService( 6092): Succeed to create listening socket 
V/BluetoothSapService( 6092): Accepting socket connection...
V/BluetoothOppProvider( 6092): starting query, database is not null; pr,ojection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/BtOppService( 6092): pendingUpdate is false keepUpdateThread is false sListenStarted is true
V/BluetoothOppProvider( 6092): created cursor android.database.sqlite.SQLiteCursor@2c02e81d on behalf of 
V/BluetoothOppNotification( 6092): outbound: succ-0  fail-0
V/BluetoothOppNotification( 6092): outbound notification was removed.
V/BluetoothOppProvider( 6092): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/WiFiOffLoadBroadcast( 6142): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
V/BluetoothOppProvider( 6092): created cursor android.database.sqlite.SQLiteCursor@363da92 on behalf of 
V/BluetoothOppNotification( 6092): inbound: succ-0  fail-0
V/BluetoothOppNotification( 6092): inbound notification was removed.
V/BluetoothOppProvider( 6092): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
V/BT_SAP  ( 6362): Event pipe created
V/BT_SAP  ( 6362): create_server_socket qcom.sap.server
V/BT_SAP  ( 6362): created socket fd 6
V/BluetoothOppProvider( 6092): created cursor android.database.sqlite.SQLiteCursor@3d08bc63 on behalf of 
,D/WiFiOffLoadBroadcast( 6142): MCCMNC not supported: null
D/QRemote ( 6311): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6311): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6311): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 5131): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6142): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6142): MCCMNC not supported: null
D/QRemote ( 6311): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6311): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6311): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/UsbSettingsReceiver( 6142): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6142): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6142): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6142): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6142): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 6142): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6142): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6142): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6142): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6142): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6142): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 6142): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 5131): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 6142): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6142): MCCMNC not supported: null
D/QRemote ( 6311): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6311): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6311): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 5131): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 6142): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6142): MCCMNC not supported: null
D/QRemote ( 6311): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6311): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6311): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,V/QRemote ( 6311): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6311): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 6311): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
E/WifiStateMachine( 1030):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1030): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
,D/LgDataFeature( 6311): LgDataFeature() Constructor: none
D/LgDataFeature( 6311): LgDataFeature() Constructor Done, null
V/SoundPool( 6311): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
,V/SoundPool( 6311): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 6311): create sampleID=1, fd=32, offset=17813 length=10857164
V/SoundPool( 6311): doLoad: loading sample sampleID=1
I/QRemote ( 6311): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
D/QRemote ( 6311): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
D/UEI.SmartControl( 5893): QS Service created
V/SoundPool( 6311): Start decode
V/MediaPlayer[Native]( 6311): decode(32, 10857164, 17813)
V/MediaPlayerService(  319): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  319): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  319): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  319): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  319): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  319): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  319): player type = 3
V/AwesomePlayer(  319): AwesomePlayer create()
E/QRemote ( 6311): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
V/AwesomePlayer(  319): reset_l() 
V/AwesomePlayer(  319): cancelPlayerEvents
V/AwesomePlayer(  319): setAudioSink() 
D/QRemote ( 6311): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
V/AwesomePlayer(  319): reset_l() 
,V/AudioCache(  319): notify(0xb5474980, 8, 0, 0)
V/AudioCache(  319): ignored
V/AwesomePlayer(  319): cancelPlayerEvents
D/Utils   (  319): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  319): setDataSource_l dataSource
V/LGParserOSAL(  319): SniffLGParser start
V/LGParserOSAL(  319): MainType:5, SubType=0
V/LGParserOSAL(  319): #### check Mime : application/ogg
V/LGParserOSAL(  319): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  319): Use LGExtractor :application/ogg 
V/LGMDMManager( 6311): Create singleton instance
I/UEI.SmartControl( 5893): Service initServices...
D/UEI.SmartControl( 5893): QS start get config
,V/LGParserOSAL(  319): supported mime: application/ogg
V/AwesomePlayer(  319): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  319): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  319): mBitrate = -1 bits/sec
V/AwesomePlayer(  319): AudioTrack Setting
V/AwesomePlayer(  319): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  319): setAudioSource() 
V/MediaPlayerService(  319): prepare
V/AwesomePlayer(  319): prepareAsync_l() 
V/MediaPlayerService(  319): wait for prepare
V/AwesomePlayer(  319): onPrepareAsyncEvent() 
V/AwesomePlayer(  319): initAudioDecoder() 
W/Utils   (  319): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  319): isOffloadSupported()
V/AudioPolicyManager(  319): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  319): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  319): isAudioPlaybackHookOn() false
V/AwesomePlayer(  319): getUseOffload() = 0 
V/OMXCodec(  319): OMXCodec::Create
V/OMXCodec(  319): findMatchingCodecs()
V/OMXCodec(  319): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  319): matchingCodecs.size()=1
V/OMXCodec(  319): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
D/OMXCodec(  319): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  319): LG Codec Adapter start
V/OMXCodec(  319): OMXCodec Createtor
V/OMXCodec(  319): setComponentRole
V/OMXCodec(  319): configureCodec protected=0
V/LGCodecAdapter(  319): called getLGCodecSpecificData
V/LGCodecOSAL(  319): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  319): Called LGconfigureCodecMETA
V/LGCodecOSAL(  319): Called LGconfigureCodecMSG
V/LGCodecOSAL(  319): Not support LGCodec
V/OMXCodec(  319): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  319): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  319): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  319): Could not offload audio decode, try pcm offload
W/Utils   (  319): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  319): isOffloadSupported()
V/AudioPolicyManager(  319): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  319): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  319): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  319): init()
V/OMXCodec(  319): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  319): allocateBuffers
V/OMXCodec(  319): allocateBuffersOnPort portIndex=0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7970 on input port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on input port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on input port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on input port
V/OMXCodec(  319): allocateBuffersOnPort portIndex=1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on output port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on output port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7dd0 on output port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb57c2100 on output port
V/OMXCodec(  319): init() mAsyncCompletion wait!!! 
V/OMXCodec(  319): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  319): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  319): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  319): init() mAsyncCompletion wait!!! 
V/OMXCodec(  319): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  319): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  319): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  319): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  319): finishAsyncPrepare_l() 
V/AudioCache(  319): notify(0xb5474980, 5, 0, 0)
V/AudioCache(  319): ignored
V/AudioCache(  319): notify(0xb5474980, 1, 0, 0)
V/AudioCache(  319): prepared
V/AudioCache(  319): wait - success
V/MediaPlayerService(  319): start
V/AwesomePlayer(  319): play_l() 
V/AwesomePlayer(  319): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  319): createAudioPlayer_l
V/AwesomePlayer(  319): seekAudioIfNecessary_l() 
V/AwesomePlayer(  319): startAudioPlayer_l() 
D/AudioPlayer(  319): start of Playback, useOffload 0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  319): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  319): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  319): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  319): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  319): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885168
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
,V/OMXCodec(  319): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885328
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885648
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044811008
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  319): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  319): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  319): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  319): allocateBuffersOnPort portIndex=1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7dd0 on output port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on output port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on output port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb57c24c0 on output port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  319): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  319): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  319): notify(0xb5474980, 6, 0, 0)
V/AudioCache(  319): ignored
V/MediaPlayerService(  319): wait for playback complete
V/AudioCache(  319): write(0xb0003000, 4096)
V/AudioCache(  319): memcpy(0xac300000, 0xb0003000, 4096)
V/AudioCache(  319): write(0xb0003000, 4096)
V/AudioCache(  319): memcpy(0xac301000, 0xb0003000, 4096)
V/AudioCache(  319): write(0xb0003000, 4096)
V/AudioCache(  319): memcpy(0xac302000, 0xb0003000, 4096)
V/AudioCache(  319): write(0xb0003000, 4096)
V/AudioCache(  319): memcpy(0xac303000, 0xb0003000, 4096)
V/AudioCache(  319): write(0xb0003000, 4096)
V/AudioCache(  319): memcpy(0xac304000, 0xb0003000, 4096)
V/AudioCache(  319): write(0xb0003000, 4096)
V/AudioCache(  319): memcpy(0xac305000, 0xb0003000, 4096)
V/AudioCache(  319): write(0xb0003000, 4096)
V/AudioCache(  319): memcpy(0xac306000, 0xb0003000, 4096)
V/AudioCache(  319): write(0xb0003000, 4096)
V/AudioCache(  319): memcpy(0xac307000, 0xb0003000, 4096)
V/AudioCache(  319): write(0xb0003000, 4096)
V/AudioCache(  319): memcpy(0xac308000, 0xb0003000, 4096)
V/AudioCache(  319): write(0xb0003000, 4096)
V/AudioCache(  319): memcpy(0xac309000, 0xb0003000, 4096)
V/AudioCache(  319): write(0xb0003000, 4096)
V/AudioCache(  319): memcpy(0xac30a000, 0xb0003000, 4096)
V/AudioCache(  319): write(0xb0003000, 4096)
V/AudioCache(  319): memcpy(0xac30b000, 0xb0003000, 4096)
V/AudioCache(  319): write(0xb0003000, 4096)
V/AudioCache(  319): memcpy(0xac30c000, 0xb0003000, 4096)
,V/AudioCache(  319): write(0xb0003000, 4096)
V/AudioCache(  319): memcpy(0xac30d000, 0xb0003000, 4096)
V/AudioCache(  319): write(0xb0003000, 4096)
V/AudioCache(  319): memcpy(0xac30e000, 0xb0003000, 4096)
V/AudioCache(  319): write(0xb0003000, 4096)
V/AudioCache(  319): memcpy(0xac30f000, 0xb0003000, 4096)
V/AudioCache(  319): write(0xb0003000, 4096)
V/AudioCache(  319): memcpy(0xac310000, 0xb0003000, 4096)
V/AudioCache(  319): write(0xb0003000, 4096)
V/AudioCache(  319): memcpy(0xac311000, 0xb0003000, 4096)
V/AudioCache(  319): write(0xb0003000, 4096)
V/AudioCache(  319): memcpy(0xac312000, 0xb0003000, 4096)
V/AudioCache(  319): write(0xb0003000, 4096)
V/AudioCache(  319): memcpy(0xac313000, 0xb0003000, 4096)
V/AudioCache(  319): write(0xb0003000, 4096)
V/AudioCache(  319): memcpy(0xac314000, 0xb0003000, 4096)
V/AudioCache(  319): write(0xb0003000, 4096)
V/AudioCache(  319): memcpy(0xac315000, 0xb0003000, 4096)
V/AudioCache(  319): write(0xb0003000, 4096)
V/AudioCache(  319): memcpy(0xac316000, 0xb0003000, 4096)
V/AudioCache(  319): write(0xb0003000, 4096)
V/AudioCache(  319): memcpy(0xac317000, 0xb0003000, 4096)
V/AudioCache(  319): write(0xb0003000, 4096)
V/AudioCache(  319): memcpy(0xac318000, 0xb0003000, 4096)
V/AudioCache(  319): write(0xb0003000, 4096)
V/AudioCache(  319): memcpy(0xac319000, 0xb0003000, 4096)
V/AudioCache(  319): write(0xb0003000, 4096)
V/AudioCache(  319): memcpy(0xac31a000, 0xb0003000, 4096)
V/AudioCache(  319): write(0xb0003000, 4096)
V/AudioCache(  319): memcpy(0xac31b000, 0xb0003000, 4096)
V/AudioCache(  319): write(0xb0003000, 4096)
V/AudioCache(  319): memcpy(0xac31c000, 0xb0003000, 4096)
V/AudioCache(  319): write(0xb0003000, 4096)
V/AudioCache(  319): memcpy(0xac31d000, 0xb0003000, 4096)
V/AudioCache(  319): write(0xb0003000, 4096)
V/AudioCache(  319): memcpy(0xac31e000, 0xb0003000, 4096)
V/AudioCache(  319): write(0xb0003000, 4096)
V/AudioCache(  319): memcpy(0xac31f000, 0xb0003000, 4096)
V/AudioCache(  319): write(0xb0003000, 4096)
V/AudioCache(  319): memcpy(0xac320000, 0xb0003000, 4096)
V/AudioCache(  319): write(0xb0003000, 4096)
V/AudioCache(  319): memcpy(0xac321000, 0xb0003000, 4096)
V/AudioCache(  319): write(0xb0003000, 4096)
V/AudioCache(  319): memcpy(0xac322000, 0xb0003000, 4096)
V/AudioCache(  319): write(0xb0003000, 4096)
V/AudioCache(  319): memcpy(0xac323000, 0xb0003000, 4096)
V/AudioCache(  319): write(0xb0003000, 4096)
V/AudioCache(  319): memcpy(0xac324000, 0xb0003000, 4096)
V/AudioCache(  319): write(0xb0003000, 4096)
V/AudioCache(  319): memcpy(0xac325000, 0xb0003000, 4096)
V/AudioCache(  319): write(0xb0003000, 4096)
V/AudioCache(  319): memcpy(0xac326000, 0xb0003000, 4096)
V/AudioCache(  319): write(0xb0003000, 4096)
V/AudioCache(  319): memcpy(0xac327000, 0xb0003000, 4096)
V/AudioCache(  319): write(0xb0003000, 4096)
V/AudioCache(  319): memcpy(0xac328000, 0xb0003000, 4096)
V/AudioCache(  319): write(0xb0003000, 4096)
V/AudioCache(  319): memcpy(0xac329000, 0xb0003000, 4096)
V/AudioCache(  319): write(0xb0003000, 4096)
V/AudioCache(  319): memcpy(0xac32a000, 0xb0003000, 4096)
V/AudioCache(  319): write(0xb0003000, 4096)
V/AudioCache(  319): memcpy(0xac32b000, 0xb0003000, 4096)
V/AudioCache(  319): write(0xb0003000, 4096)
V/AudioCache(  319): memcpy(0xac32c000, 0xb0003000, 4096)
V/AudioCache(  319): write(0xb0003000, 4096)
V/AudioCache(  319): memcpy(0xac32d000, 0xb0003000, 4096)
V/AudioCache(  319): write(0xb0003000, 4096)
V/AudioCache(  319): memcpy(0xac32e000, 0xb0003000, 4096)
V/AudioCache(  319): write(0xb0003000, 4096)
V/AudioCache(  319): memcpy(0xac32f000, 0xb0003000, 4096)
V/AudioCache(  319): write(0xb0003000, 4096)
V/AudioCache(  319): memcpy(0xac330000, 0xb0003000, 4096)
V/AudioCache(  319): write(0xb0003000, 4096)
V/AudioCache(  319): memcpy(0xac331000, 0xb0003000, 4096)
V/OMXCodec(  319): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  319): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  319): p,ostAudioEOS() 
V/AudioCache(  319): write(0xb0003000, 280)
V/AudioCache(  319): memcpy(0xac332000, 0xb0003000, 280)
V/AwesomePlayer(  319): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  319): onStreamDone
V/AwesomePlayer(  319): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  319): notify(0xb5474980, 2, 0, 0)
V/AudioCache(  319): playback complete
V/AwesomePlayer(  319): pause_l() 
V/AudioCache(  319): notify(0xb5474980, 7, 0, 0)
V/AudioCache(  319): ignored
V/AwesomePlayer(  319): cancelPlayerEvents
V/AudioCache(  319): wait - success
V/MediaPlayerService(  319): return size 205080, sampleRate=48000, channelCount = 2, format = 1
D/AudioPlayer(  319): Pause Playback at 1068125
V/AwesomePlayer(  319): reset_l() 
V/AudioCache(  319): notify(0xb5474980, 8, 0, 0)
V/AudioCache(  319): ignored
V/AwesomePlayer(  319): cancelPlayerEvents
D/AudioPlayer(  319): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  319): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  319): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  319): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  319): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  319): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7970 on port 0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeing buffer 0xb57c24c0 on port 1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7bf0 on port 1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c90 on port 1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7dd0 on port 1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  319): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  319): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  319): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  319): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  319): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
,V/OMXCodec(  319): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  319): AudioPlayer releasing audio source
D/AudioPlayer(  319): AudioPlayer done releasing audio source
V/AwesomePlayer(  319): reset_l() 
V/AwesomePlayer(  319): cancelPlayerEvents
V/AwesomePlayer(  319): ~AwesomePlayer call
V/AwesomePlayer(  319): reset_l() 
V/AwesomePlayer(  319): cancelPlayerEvents
V/SoundPool( 6311): close(32)
V/SoundPool( 6311): pointer = 0x9ff3f000, size = 205080, sampleRate = 48000, numChannels = 2
,D/QRemote ( 6311): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,D/QRemote ( 6311): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,D/QRemote ( 6311): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:143
I/UEI.SmartControl( 5893): Supports setup maps: true
,D/UEI.SmartControl( 5893): QS start statue = true Error code = 0
I/UEI.SmartControl( 5893): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 5893): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 5893): ### init IR Blaster...
D/serial_port( 5893): Configuring serial port
E/UEI.SmartControl( 5893): UEIBLaster setting for 616
I/UEI.SmartControl( 5893): Setting serial record hearder size = 2
I/UEI.SmartControl( 5893): configuring settings for MAXQ616
I/UEI.SmartControl( 5893): Get version...
D/UEI.SmartControl( 5893): serial port data available: 21
,D/UEI.SmartControl( 5893): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 5893): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 5893): QS saving settings...
,D/UEI.SmartControl( 5893): IR Blaster version: 25672567
,D/UEI.SmartControl( 5893): serial port data available: 4
,W/ContextImpl( 5893): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,E/UEI.SmartControl( 5893): Services init done
D/UEI.SmartControl( 5893): QS Service init finished
D/UEI.SmartControl( 5893): QS Service version name: 2.1.91
D/UEI.SmartControl( 5893): QS Service version code: 201091
I/UEI.SmartControl( 5893): Device manager: loading config....
D/UEI.SmartControl( 5893): Service requested: Control
D/UEI.SmartControl( 5893): ----------- loading internal config...
E/UEI.SmartControl( 5893): Loading SETTINGS...
D/UEI.SmartControl( 5893): Request IControl service: devices are loaded...
,D/UEI.SmartControl( 5893): Internal service binding...
,D/UEI.SmartControl( 5893): -- Open brand translation xml: brands_translations_ko
I/QRemote ( 6311): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 5893): ------ IControl API: 11
D/UEI.SmartControl( 5893): File observer start...
E/UEI.SmartControl( 5893): IR Port is disabled: false
D/UEI.SmartControl( 5893): Starting file observer...
I/UEI.SmartControl( 5893): Registering callback...
I/UEI.SmartControl( 5893): ------ IControl API: 19
I/UEI.SmartControl( 5893): Registering Services Ready callback...
I/UEI.SmartControl( 5893): Notify client services are ready...
I/QRemote ( 6311): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 6311): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 6311): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 6311): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 6311): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 5893): ------ IControl API: 8
D/QRemote ( 6311): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 6311): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 6311): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 6311): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 6311): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6311): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
,D/QRemote ( 6311): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
I/UEI.SmartControl( 5893): Notify AllClients services are ready: 0
I/QRemote ( 6311): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 6311): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 6311): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/UEI.SmartControl( 5893): -----service ready thread exits
V/QRemote ( 6311): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6311): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 6311): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6311): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 6311): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6311): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 6311): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 6311): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1454420846898]
D/QRemote ( 6311): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
I/ActivityManager( 1030): Killing 5809:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,D/QRemote ( 6311): [RemoteControlManager.java:327:handleMessage()] oooooo 140510:retrieveDevices already complete. Do nothing
D/QRemote ( 6311): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,W/libprocessgroup( 1030): failed to open /acct/uid_10061/pid_5809/cgroup.procs: No such file or directory
,V/QRemote ( 6311): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,E/QRemote ( 6311): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,D/QRemote ( 6311): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 6311): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 6311): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 6311): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 6311): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 6311): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,V/BluetoothOppNotification( 6092): new notify threadi!
,V/BluetoothOppNotification( 6092): send delay message
,V/BluetoothOppProvider( 6092): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,V/BluetoothOppProvider( 6092): created cursor android.database.sqlite.SQLiteCursor@3db09060 on behalf of 
V/BluetoothOppNotification( 6092): mUpdateCompleteNotification = true
V/BluetoothOppProvider( 6092): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 6092): created cursor android.database.sqlite.SQLiteCursor@1a6ae919 on behalf of 
,V/BluetoothOppNotification( 6092): outbound: succ-0  fail-0
,V/BluetoothOppNotification( 6092): outbound notification was removed.
V/BluetoothOppProvider( 6092): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 6092): created cursor android.database.sqlite.SQLiteCursor@34e10dde on behalf of 
V/BluetoothOppNotification( 6092): inbound: succ-0  fail-0
,V/BluetoothOppNotification( 6092): inbound notification was removed.
V/BluetoothOppProvider( 6092): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6092): created cursor android.database.sqlite.SQLiteCursor@2dc0bbbf on behalf of 
I/dhcpcd  ( 6295): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
,I/dhcpcd  ( 6295): wlan0: leased 192.168.1.141 for 86400 seconds
,D/dhcpcd  ( 6295): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 6295): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 6295): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 6295): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 6295): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 6295): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 6295): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
E/WifiStateMachine( 1030):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1030): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
,D/DhcpStateMachine( 1030): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper( 1030): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1030): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1030): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1030): Add DhcpResults: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
V/DhcpStateMachine( 1030): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1030): bShouldSendDhcpAction Result: true
D/DhcpStateMachine( 1030): DHCP Start/Renew wake lock is released.
E/WifiStateMachine( 1030):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine( 1030):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/WifiNative-wlan0( 1030): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 6160): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/DhcpStateMachine( 1030): RunningState
D/LGWifiP2pService( 1030): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1030): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1030): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 6160): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1030): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET ps 1
D/WifiNative-wlan0( 1030): SET ps 1: returned true
,D/ConnectivityService( 1030): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
E/WifiStateMachine( 1030):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1030): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1030): ignoring duplicate network state non-change
,I/StatusBar.NetworkController( 1456): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/StatusBar.NetworkController( 1456): mWifiConnected = false, mWifiLevel = 0
D/PostponalbeReceiver( 5131): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
,W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
E/WifiStateMachine( 1030): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/ConnectivityService( 1030): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService( 1030): Adding iface wlan0 to network 100
I/StatusBar.NetworkController( 1456): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1456): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
,W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/WifiHS20( 1030): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
E/ConnectivityService( 1030): Unexpected mtu value: 0, wlan0
D/WifiHS20( 1030): [PASSPOINT] passpointNotification: hs20AP list is checked
D/ConnectivityService( 1030): Adding Route [fe80::/64 -> :: wlan0] to network 100
D/ConnectivityService( 1030): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
D/ConnectivityService( 1030): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
I/StatusBar.NetworkController( 1456): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
V/WfdStateTracker( 1963): handleWifiStateChangedEvent: 1
I/StatusBar.NetworkController( 1456): mWifiConnected = true, mWifiLevel = 2
D/ConnectivityService( 1030): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1030): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 100
D/ConnectivityService( 1030): Setting Dns servers for network 100 to [/192.168.1.1]
D/Nat464Xlat( 1030): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1030): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1030): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): Connected
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
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
D/WIFI    ( 1030): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1030):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
D/libc-netbsd(  314): res_queryN name = clients3.google.com, class = 1, type = 28
I/StatusBar.NetworkController( 1456): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1456): mWifiConnected = true, mWifiLevel = 2
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/TelephonyNetworkFactory-1( 1867): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1867):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,D/ConnectivityService( 1030): Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
E/ConnectivityService( 1030): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1030): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1030): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1030): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1030): [e] list.add(nai) empty : false size: 1
D/ConnectivityService( 1030): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService( 1030): validation of new default Network = false
D/ConnectivityService( 1030): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1030): enableDataServiceNotify 
D/DSQN    ( 1030): start dsqn bin
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  314): res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
D/LocSvc_java( 1030): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1030): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1030): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1030): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java( 1030): Sending msg: 5 arg1:0 arg2:1
D/ConnectivityService( 1030): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1030):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1030):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1030): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1456): CM callback handler got msg 524290
,W/dsqn    ( 6438): type=1400 audit(0.0:165): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 6438): type=1400 audit(0.0:166): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
V/WiFiOffLoadBroadcast( 6142): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  314): res_queryN name = europe.pool.ntp.org, class = 1, type = 1
,D/WiFiOffLoadBroadcast( 6142): MCCMNC not supported: null
D/libc-netbsd(  314): res_queryN name = clients3.google.com, class = 1, type = 1
E/DSQN    ( 6438): DSQN ssw
D/libc-netbsd(  314): res_queryN name = 2.android.pool.ntp.org succeed
D/QRemote ( 6311): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6311): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6311): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/TelephonyIcons( 1456): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PostponalbeReceiver( 5131): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/libc-netbsd(  314): res_queryN name = europe.pool.ntp.org succeed
,V/WiFiOffLoadBroadcast( 6142): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/libc-netbsd(  314): res_queryN name = clients3.google.com succeed
D/WiFiOffLoadBroadcast( 6142): MCCMNC not supported: null
V/NetworkPolicy( 1030): [LG_RESTRICTED] checkMobilePolicy_type()
,D/LGDataListener(  314): argv[0]=dsqncommand
D/LGDataListener(  314): argv[1]=wlan0
D/LGDataListener(  314): argv[2]=1
D/LGDataListener(  314): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1030): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1030): start to monitor internet connection
D/QRemote ( 6311): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6311): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6311): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 5131): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 6236): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6236): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6142): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 02 Feb 2016 13:47:27 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454420847951], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454420847933]}
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
D/LocSvc_java( 1030): NTP server : europe.pool.ntp.org
D/ConnectivityService( 1030): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/LocSvc_java( 1030): NTP server returned: 1454420847495 (Tue Feb 02 14:47:27 GMT+01:00 2016) reference: 117595 certainty: 21 system time offset: -458
D/LocSvc_java( 1030): Sending msg: 10 arg1:0 arg2:1
D/ConnectivityManager.CallbackHandler( 1456): CM callback handler got msg 524290
D/ConnectivityService( 1030): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1030): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1030): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    ( 1030):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1867): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1867):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/WiFiOffLoadBroadcast( 6142): MCCMNC not supported: null
D/QRemote ( 6311): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6311): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6311): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6311): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6311): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,D/PostponalbeReceiver( 5131): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6236): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6236): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6142): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/TelephonyIcons( 1456): null signal icon name: drawable/stat_sys_signal_null
,D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WiFiOffLoadBroadcast( 6142): MCCMNC not supported: null
D/QRemote ( 6311): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6311): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6311): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6311): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6311): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 117722631886; DSPS: 3998442; Offset : -4312275814
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1573064711] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1573064707] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
I/jxcore-log( 5988): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 5988): 
,I/jxcore-log( 5988): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 5988): 
,I/jxcore-log( 5988): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 5988): 
,I/jxcore-log( 5988): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 5988): 
I/jxcore-log( 5988): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 5988): 
,I/jxcore-log( 5988): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 5988): 
,I/jxcore-log( 5988): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 5988): 
,I/jxcore-log( 5988): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 5988): 
V/WifiInternetCheck( 1030): Single check msg out of sync, ignoring.
,D/ConnectivityService( 1030): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1030): MasterInitialState.processMessage what=3
D/AlarmManagerService( 1030): Setting time of day to sec=1454420850
,W/AlarmManagerService( 1030): Unable to set rtc to 1454420850: Invalid argument
D/PostponalbeReceiver( 5131): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 5131): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkMonitor( 5185): type=WIFI subType= reason=null isConnected=true
,D/LIA_Informant_Tips_DateChangeManager( 2698): onReceive() : ACTION_TIME_CHANGED
I/LIA_Informant_Tips_LogTracer( 2698): [Log Tracer - Schedule Transition] Time Change Event Received : 2016-02-02 14:47:30...... Request
I/LIA_Informant_Tips_LogTracer( 2698): [Log Tracer - Schedule Transition] UserGuide, DATE_UPDATE : working count : 6, total count : 163, new day : false...... Request
I/SecureClockService( 1963): Intent.ACTION_TIME_CHANGED 
I/[SystemUI]Clock( 1456): onReceive = android.intent.action.TIME_SET
W/ActivityManager( 1030): getTasks: caller 10029 is using old GET_TASKS but privileged; allowing
,D/LIA_Informant_Tips_DateChangeManager( 2698): DateInfo : SmartTips Total Working Day Count = 163
D/LIA_Informant_Tips_DateChangeManager( 2698): DateInfo : UserGuide Working Duration Count = 6
I/LgeClockWidgetControlView( 1456): time changed, timezoneChanged : false
D/KeyguardUpdateMonitor( 1456): handleTimeUpdate
D/LIA_Informant_Tips_DateChangeManager( 2698): DateInfo : Last Date Check Time = 2016-02-02 14:47:30
I/[LGHome]LGDateChangeReceiver( 2082): [LGDateChangeReceiver.java:78:updateCalendarShortcut()]date=2 currentDate=-1 dayofweek=3 currentDayOfWeek=-1
I/[LGHome]LGCalendarIcon( 2082): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Tue date= 2
,I/[LGHome]LGCalendarIcon( 2082): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Tue date= 2
I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/ActivityManager( 1030): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6462 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/[Concierge]Service( 2608): onStartCommand(). Type : 9
,I/ActivityManager( 1030): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=6481 uid=10054 gids={50054, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1030): Start proc com.android.gallery3d for service com.android.gallery3d/com.lge.gallery.picasa.PicasaService: pid=6497 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/ResourcesManager( 6497): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6497): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6497): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,W/ResourcesManager( 6497): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/AppUp4:AppBoxCP( 6462): onCreate
W/AppUp4:DB( 6462):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6462):  setFingerPrint start
,I/AppUp4:DB( 6462):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 6462):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 6462):  SDK version = 21
I/AppUp4:DB( 6462):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6462): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6462): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6462): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6462): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6462): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 6462): onReceive
D/LgDataFeature( 6462): LgDataFeature() Constructor: none
,D/LgDataFeature( 6462): LgDataFeature() Constructor Done, null
D/AppUp4:CustFacade( 6462): Context : android.app.ReceiverRestrictedContext@22a1165d
,D/AppUp4:CustFacade( 6462): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6462): isPhone : true
D/AppUp4:CustModeStarterReceiver( 6462): begin check event
I/AppUp4:CustModeStarterReceiver( 6462): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6462): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
I/ActivityManager( 1030): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=6519 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/GpsLocationProvider( 1030): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustModeStarterReceiver( 6462): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6462): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6462): handleAsyncCustNotification do not startCustService
I/art     (  348): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 241us total 11.805ms
I/AppConfig( 6497): Total System Memory = 2995761152
,I/art     (  348): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 229us total 11.419ms
D/LGDMClient( 3963): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3963): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 3963): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/SystemHelper( 6497): region [EU], country [EU], operator [OPEN], sub-operator []
I/art     (  348): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 197us total 10.817ms
,W/ContextImpl( 3963): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/LGDMClient( 3963): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/LGDMClient( 3963): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 3302): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 3963): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3963): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 3302): DownloadService onCreate
W/ContextImpl( 3963): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
I/DownloadManager( 3302): in removeSpuriousFiles
V/DownloadManager( 3302): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3302): created cursor android.database.sqlite.SQLiteCursor@3ce8c083 on behalf of 3302
,I/DownloadManager( 3302): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3302): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3302): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3302): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3302): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3302): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3302): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3302): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3302): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3302): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3302): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/ActivityManager( 1030): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6544 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/DownloadManager( 3302): in trimDatabase
V/DownloadManager( 3302): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
E/LGDMClient( 3963): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 3963): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 3963): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3302): DownloadService onStartCommand
V/DownloadManager( 3302): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3302): created cursor android.database.sqlite.SQLiteCursor@24eb787e on behalf of 3302
V/DownloadManager( 3302): created cursor android.database.sqlite.SQLiteCursor@266ce1df on behalf of 3302
V/DownloadManager( 3302): processing inserted download 1
V/DownloadManager( 3302): processing inserted download 4
V/DownloadManager( 3302): processing inserted download 7
V/DownloadManager( 3302): processing inserted download 8
V/DownloadManager( 3302): processing inserted download 9
V/DownloadManager( 3302): processing inserted download 10
V/DownloadManager( 3302): processing inserted download 16
V/DownloadManager( 3302): processing inserted download 17
V/DownloadManager( 3302): processing inserted download 18
V/DownloadManager( 3302): processing inserted download 21
V/DownloadManager( 3302): processing inserted download 22
,V/DownloadManager( 3302): DownloadService onDestroy
,W/ResourcesManager( 6544): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6544): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6544): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6544): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,D/GpsLocationProvider( 1030): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/GpsLocationProvider( 1030): No APN found to select.
I/art     ( 2185): Explicit concurrent mark sweep GC freed 17510(986KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 30MB/62MB, paused 2.297ms total 24.783ms
,I/ReaderUtils( 6481): PortraitW 1440 LandscapeW 2392 SmallestSize 1340 LargestSize 2392 textZoom 4.4999995 isTablet false Memory 256
,W/DriveInitializer( 2392): Background init thread started
,I/LGEmail ( 6544): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
I/ActivityManager( 1030): Killing 5493:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
D/LGEmail ( 6544): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
W/ResourceType( 6544): No package identifier when getting value for resource number 0x00000000
,W/DriveInitializer( 2392): Awaiting to be initialized
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.gms/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 2392): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.gms/files
W/libprocessgroup( 1030): failed to open /acct/uid_10080/pid_5493/cgroup.procs: No such file or directory
,D/LgDataFeature( 6544): LgDataFeature() Constructor: none
D/LgDataFeature( 6544): LgDataFeature() Constructor Done, null
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=6.5, 0.0, 0.0  rx=5.5 bcn=0 [on:0 tx:0 rx:0 period:2543] from screen [on:0 period:-1573062152] gl rssi=-58 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=6.5, 0.0, 0.0  rx=5.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1573062151] gl rssi=-58 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
I/art     ( 1030): Explicit concurrent mark sweep GC freed 68997(3MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 44MB/66MB, paused 1.599ms total 119.230ms
,D/DelayedSyncController( 6519): Delaying sync.
W/GAV2    ( 6481): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/DriveInitializer( 2392): Background init thread ended
,I/BooksApp( 6481): Created application version: 3.2.35 (30235)
,E/Auth.Api.Credentials( 2392): [CredentialSyncAdapter] Unknown sync event.
,I/ActivityManager( 1030): Killing 5512:com.google.android.apps.plus/u0a97 (adj 15): empty #17
D/eas_req ( 6544): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
W/libprocessgroup( 1030): failed to open /acct/uid_10097/pid_5512/cgroup.procs: No such file or directory
,I/BooksSync( 6481): Starting books sync
,D/serial_port( 5893): close(fd = 24)
I/UEI.SmartControl( 5893): Serial port is closed.
,I/LgeMiscReceiver( 3252): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3252): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3252): networkInfo.isConnected() = true
D/PhoneState( 3252): setPdpRejectCasuse : false
I/HubEmail( 6544): JNI_OnLoad()
I/HubEmail( 6544): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6544): registerNatives()
I/HubEmail( 6544): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6544): registerNativeMethods()
I/HubEmail( 6544): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6544): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  314): res_queryN name = static-avc.lglime.com, class = 1, type = 1
I/ActivityManager( 1030): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6601 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
W/Settings( 6544): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 6544): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  314): res_queryN name = www.google.com, class = 1, type = 1
D/libc-netbsd(  314): res_queryN name = static-avc.lglime.com succeed
,D/libc-netbsd(  314): res_queryN name = www.google.com succeed
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  314): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  314): res_queryN name = clients3.google.com succeed
D/DrmBroadcastReceiver( 6601): Receive CONNECTIVITY_ACTION
D/DrmBroadcastReceiver( 6601): 1  network is available. Sync DRM Time with NTP
V/DrmService( 6601): Service onCreate
D/DrmService( 6601): Received new request = 2
,I/DrmSntpClient( 6601): Start Sync process
D/DrmSntpClient( 6601): Server : 0
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  314): res_queryN name = pool.ntp.org, class = 1, type = 1
V/WifiInternetCheck( 1030): isHttpConnectionAvailable - We got a valid response : 204
,I/ActivityManager( 1030): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=6625 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/libc-netbsd(  314): res_queryN name = pool.ntp.org succeed
,D/BooksSync( 6481): started syncMyEbooks
,I/LGDrmClient( 6601): _DRM_ServiceGet() : Bind lgdrm service
,V/ILGDrmService(  333): eDRM_SetDRMTime +++
I/LGDRM   (  333): [DRM] SET TIME : YR=2016, MON=2, DAY=2
I/LGDRM   (  333): [DRM] SET TIME : HR=13, MIN=47, SEC=30
V/ILGDrmService(  333): eDRM_SetDRMTime ---
I/DrmSntpClient( 6601): Synched
D/DrmService( 6601): Completed !! request = 2
D/DrmService( 6601): Request count = 0
V/DrmService( 6601): Service onDestroy
I/ActivityManager( 1030): Killing 5868:com.lge.eula/1000 (adj 15): empty #17
V/FormManager( 6174): There are no updated forms. The schedule will be deleted.
V/FormManager( 6174): Alarm would be updated, because LastCheckTime has been updated.
I/art     ( 6625): Almond Protected OAT
,W/libprocessgroup( 1030): failed to open /acct/uid_1000/pid_5868/cgroup.procs: No such file or directory
,D/WeatherApplication( 6625): removeAccount
D/WeatherApplication( 6625): Account.length = 0
V/GLSActivity( 2185): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/WeatherApplication( 6625): OPERATOR:OPEN
D/WeatherAncestor( 6625): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:47:31
,I/ActivityManager( 1030): Killing 5336:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
D/Weather.Utils( 6625): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6625): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6625): 2 : This is isUpdating : false
,D/WeatherAncestor( 6625): connectivity changed - connection : true
D/UEI.SmartControl( 5893): Internal timer expired: 2
D/UEI.SmartControl( 5893): unbind internal service
D/WeatherService( 6625): 2 : isServiceAlived():false forecastCache:null
I/GLSUser ( 2185): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2185): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2185): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2185): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/ForecastDataCache( 6625): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 6625): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 6625): 2 : Cache is not up-to-date, count: 0
,D/Weather_cast( 6625): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 6625): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:47:31
,I/ActivityManager( 1030): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6646 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/libprocessgroup( 1030): failed to open /acct/uid_10005/pid_5336/cgroup.procs: No such file or directory
V/GLSActivity( 2185): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager( 1030): Killing 2154:com.lge.music/u0a34 (adj 15): empty #17
V/AudioFlinger(  319): 2154 died, releasing its sessions
V/AudioFlinger(  319):  pid 1867 @ 0
V/AudioFlinger(  319):  pid 3252 @ 1
V/AudioFlinger(  319):  pid 3252 @ 2
,W/libprocessgroup( 1030): failed to open /acct/uid_10034/pid_2154/cgroup.procs: No such file or directory
,V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,D/ZenLog  ( 1030): intercepted: 0|com.google.android.gms|1|null|10005,none
V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/ResourcesManager( 1411): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 1411): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/GLSActivity( 2185): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2185): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2185): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2185): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2185): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2185): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2185): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1411): onNotificationPosted
,W/ResourcesManager( 1456): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1456): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
E/BooksAccountManager( 6481): Authentication error
E/BooksAccountManager( 6481): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6481): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6481): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6481): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6481): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6481): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6481): null auth token
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
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1411): updateNotificationData: count=3
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  314): res_queryN name = www.googleapis.com, class = 1, type = 1
,D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{198ef165 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6646): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6646): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6646): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6646): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
D/libc-netbsd(  314): res_queryN name = www.googleapis.com succeed
,V/GLSActivity( 2185): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2185): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 2185): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2185): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2185): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2185): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,D/LgeQuickCoverNLService( 1411): onNotificationPosted
D/SmartCoverUpdateMonitor( 1411): received broadcast com.lge.intent.action.NLDataPosted
W/GLSActivity( 2185): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2185): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2185): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2185): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2185): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2185): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2185): 	at android.os.Binder.execTransact(Binder.java:446)
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
D/ContactsSyncAdapter( 2185): innerSync failed
D/ContactsSyncAdapter( 2185): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2185): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2185): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2185): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2185): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2185): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2185): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2185): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2185): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2185): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2185): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2185): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1411): updateNotificationData: count=3
I/WebViewFactory( 6646): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,D/SyncManager( 1030): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 26794, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager( 1030): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 153641, reason: 10019
I/LibraryLoader( 6646): Loading: webviewchromium
I/LibraryLoader( 6646): Time to load native libraries: 3 ms (timestamps 2647-2650)
I/LibraryLoader( 6646): Expected native library version number "",actual native library version number ""
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{198ef165 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
V/WebViewChromiumFactoryProvider( 6646): Binding Chromium to main looper Looper (main, tid 1) {19af6dfc}
I/LibraryLoader( 6646): Expected native library version number "",actual native library version number ""
I/chromium( 6646): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6646): Initializing chromium process, renderers=0
W/art     ( 6646): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6646): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 6646): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
,I/chromium( 6646): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
V/AudioPolicyService(  319): registerClient() client 0xb558ae40, uid 10093
W/AudioManagerAndroid( 6646): Requires BLUETOOTH permission
I/Adreno-EGL( 6646): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6646): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6646): Build Date: 12/12/14 금
I/Adreno-EGL( 6646): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6646): Remote Branch: 
I/Adreno-EGL( 6646): Local Patches: 
I/Adreno-EGL( 6646): Reconstruct Branch: 
,W/ApiaryClient( 6481): Error response from books API: {
W/ApiaryClient( 6481):  "error": {
W/ApiaryClient( 6481):   "errors": [
W/ApiaryClient( 6481):    {
W/ApiaryClient( 6481):     "domain": "global",
W/ApiaryClient( 6481):     "reason": "required",
W/ApiaryClient( 6481):     "message": "Login Required",
W/ApiaryClient( 6481):     "locationType": "header",
W/ApiaryClient( 6481):     "location": "Authorization"
W/ApiaryClient( 6481):    }
W/ApiaryClient( 6481):   ],
W/ApiaryClient( 6481):   "code": 401,
W/ApiaryClient( 6481):   "message": "Login Required"
W/ApiaryClient( 6481):  }
W/ApiaryClient( 6481): }
,W/ApiaryClient( 6481): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6481): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7956790022025389583&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6481): Headers:
W/ApiaryClient( 6481): accept-encoding: [gzip]
W/ApiaryClient( 6481): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6481): gdata-version: 2
I/ActivityManager( 1030): Start proc com.google.android.apps.plus for service com.google.android.apps.plus/.service.EsSyncAdapterService: pid=6701 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/NSApplication( 6646): Starting up...
,I/ActivityManager( 1030): Killing 4815:com.android.vending/u0a44 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_10044/pid_4815/cgroup.procs: No such file or directory
,W/ResourcesManager( 6701): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  314): res_queryN name = mtalk.google.com, class = 1, type = 1
,I/iu.SyncManager( 2392): SYNC; picasa accounts
,I/GLSActivity( 2185): [ac] getting account id
I/GLSUser ( 2185): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
,D/NetworkLogImpl( 2392): Loaded NetworkSpeedPredictor
I/iu.Environment( 2392): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/iu.UploadsManager( 2392): num queued entries: 0
I/iu.UploadsManager( 2392): num updated entries: 0
I/iu.SyncManager( 2392): NEXT; no task
D/libc-netbsd(  314): res_queryN name = mtalk.google.com succeed
D/ChimeraCfgMgr( 2392): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/ChimeraCfgMgr( 2392): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PostponalbeReceiver( 5131): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.TIME_SET'.
,I/ActivityManager( 1030): Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=6741 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/GLSUser ( 2185): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2185): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2185): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2185): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2185): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1411): updateNotificationData: count=3
,W/Kids    ( 2392): [AccountUtils] Account not ready
W/Kids    ( 2392): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2392): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2392): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2392): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2392): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2392): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2392): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2392): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2392): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2392): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2392): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2392): 	at java.lang.Thread.run(Thread.java:818)
I/art     ( 1030): Explicit concurrent mark sweep GC freed 31727(1408KB) AllocSpace objects, 4(192KB) LOS objects, 33% free, 44MB/66MB, paused 2.215ms total 169.123ms
D/ALBootInit( 6741): ====action==>android.intent.action.TIME_SET
D/ALBootInit( 6741): Alarm ALBootInit: TIME_SET
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{198ef165 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/Alarms  ( 6741): [setNextAlert] start
D/Alarms  ( 6741): [setNextAlert] (1)
D/Alarms  ( 6741):  minTime  = 0
D/Alarms  ( 6741):  -- OK multi -- 0
E/jeny.kim( 6741): [setNextAlert] setNextAlert  temp_Alarmlink + 
E/jeny.kim( 6741): [setNextAlert]setNextAlert temp_AlarmLinkText + 
I/CommonUtil( 6741): BUILD Country: EU
,D/DelayedSyncController( 6519): Delaying sync.
D/Alarms  ( 6741): broadcastToWidgetProvider : false
D/Alarms  ( 6741): Enter formatDayAndTime(final Context context, long timeInMiliSec)
,V/SettingsProvider( 1030): call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
,I/DigitalAppWidgetProvider( 6741): onReceive: android.intent.action.TIME_SET
V/DigitalAppWidgetProvider( 6741): cancelAlarmOnQuarterHour android.app.ReceiverRestrictedContext@3c550bd2
V/DigitalAppWidgetProvider( 6741): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@3c550bd2
D/QuickCoverProvider( 6741): onReceiver
I/indal   ( 1411): SmartCoverWidgetContext createApplicationContext
I/indal   ( 1411): SmartCoverWidgetContext createApplicationContext
,D/WeatherAncestor( 6625): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 14:47:33
D/Weather.Utils( 6625): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6625): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6625): 2 : This is isUpdating : false
,D/WeatherService( 6625): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@103c34a3
D/ForecastDataCache( 6625): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 6625): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 6625): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 6625): 2 : set auto-update time : 2/2 17:47
,D/WeatherAncestor( 6625): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 14:47:33
I/ActivityManager( 1030): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=6773 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1030): Killing 5929:com.lge.bnr/1000 (adj 15): empty #17
,D/GCM     ( 2185): Connected
,W/libprocessgroup( 1030): failed to open /acct/uid_1000/pid_5929/cgroup.procs: No such file or directory
,V/GLSActivity( 2185): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/GCM     ( 2185): Message class com.google.f.a.a.p
I/GLSUser ( 2185): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2185): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2185): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2185): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2185): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/TimeService( 6773): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1454420853669
D/        ( 6773): TimeServiceNative: User Time to be set is 1454420853670
D/QC-time-services( 6773): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 6773): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 6773): Lib:time_genoff_operation: pargs->ts_val = 1454420853670
D/QC-time-services( 6773): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  376): Daemon: Connection accepted:time_genoff
D/QC-time-services(  376): Daemon:Received base = 2, unit = 1, operation = 0,value = 1454420853670
D/QC-time-services(  376): Daemon:genoff_opr: Base = 2, val = 1454420853670, operation = 0
D/QC-time-services(  376): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS5/12/70 6:59:40
D/QC-time-services(  376): Daemon:Value read from RTC seconds = 14021980000
D/QC-time-services(  376): Daemon:new time 1454420853670 
D/QC-time-services(  376): Daemon: delta 1440398873670 genoff 1440398873670 
D/QC-time-services(  376): Daemon:genoff_persistent_update: Writing genoff = 1440398873670 to memory
D/QC-time-services(  376): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  376): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  376): Updating the TOD offset
D/QC-time-services(  376): Daemon:genoff_persistent_update: Writing genoff = 1440398873670 to memory
D/QC-time-services(  376): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  376): Daemon:time_persistent_memory_opr:Genoff write operation 
E/QC-time-services(  376): Daemon:Update to modem bit set
D/QC-time-services(  376): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  376): Daemon: Base = 2, Value being sent to MODEM = 1124434073670
E/QC-time-services( 6773): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
E/QC-time-services(  376): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
E/QC-time-services(  376): Daemon: Time-services: Waiting to acceptconnection
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
W/GLSActivity( 2185): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2185): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2185): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2185): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2185): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2185): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2185): 	at android.os.Binder.execTransact(Binder.java:446)
I/ActivityManager( 1030): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetProvider: pid=6791 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi
,I/ActivityManager( 1030): Killing 6265:com.lge.settings.easy/1000 (adj 15): empty #17
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/libprocessgroup( 1030): failed to open /acct/uid_1000/pid_6265/cgroup.procs: No such file or directory
,E/BooksAccountManager( 6481): Authentication error
E/BooksAccountManager( 6481): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6481): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6481): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6481): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6481): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6481): 	at android.os.Binder.execTransact(Binder.java:446)
,E/HttpHelper( 6481): null auth token
D/LgeQuickCoverNLService( 1411): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1411): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1411): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1411): handleNotificationPosted(true)
,D/QuickCircle( 1411): onNotificationPosted() : isPosted true
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
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{198ef165 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ResourcesManager( 6791): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/CalendarApplication( 6791): CalendarApplication.onCreate()
,D/PreferenceKeysParser( 6791): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 6791): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@300e0921, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@2d482146, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@3fdaf07, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@24c1d834, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@22a1165d, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@3c550bd2, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@103c34a3, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@1abe43a0, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@95dbb59, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@bd4131e, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@e5377ff, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@1653f9cc, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@17a5b415, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@2baa432a, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@1471951b, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@3dace6b8, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@1b3a7c91, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@130167f6, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@238a67f7, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@2da5b664, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@227950cd, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@2fd40d82, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@2df38c93, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@1239d4d0, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@a572cc9, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@23397fce, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@2bc05eef, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@19af6dfc, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@301ccc85, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@3671cada, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@18ddfb0b, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@2e836de8, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@2e2ac01, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@14b1baa6, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@38ef3ce7, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@24158094, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@30cd073d, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@15aedb32, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@3ce8c083, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@2141200, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@2c07da39, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@24eb7
D/GeneralPreferenceUtils( 6791): [migratePrefrenceKeys] Exit: Version(44001600) >= 42001300
,W/ApiaryClient( 6481): Error response from books API: {
W/ApiaryClient( 6481):  "error": {
W/ApiaryClient( 6481):   "errors": [
W/ApiaryClient( 6481):    {
W/ApiaryClient( 6481):     "domain": "global",
W/ApiaryClient( 6481):     "reason": "required",
W/ApiaryClient( 6481):     "message": "Login Required",
W/ApiaryClient( 6481):     "locationType": "header",
W/ApiaryClient( 6481):     "location": "Authorization"
W/ApiaryClient( 6481):    }
W/ApiaryClient( 6481):   ],
W/ApiaryClient( 6481):   "code": 401,
W/ApiaryClient( 6481):   "message": "Login Required"
W/ApiaryClient( 6481):  }
W/ApiaryClient( 6481): }
,W/ApiaryClient( 6481): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6481): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7956790022025389583&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6481): Headers:
W/ApiaryClient( 6481): accept-encoding: [gzip]
W/ApiaryClient( 6481): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6481): gdata-version: 2
D/Config  ( 6791): [init]
,I/Config  ( 6791): LGCalendar ver.4.40.16
,I/Config  ( 6791): start check model
I/Config  ( 6791): start check native_ca
I/Config  ( 6791): Config Operator=OPEN, Country=EU
D/Config  ( 6791): [setDefaultValuesToPref]
D/Config  ( 6791): [parseProfiles]
D/ProfilesParser( 6791): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6791): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6791): [updateProfiletoCountryInfo]
D/GeneralPreference( 6791): [checkAndMigrateOldPreference]
E/AgendaWidgetManager( 6791): [updateWidgets] 
,I/InitNotificationRingtoneService( 6791): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 6791): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/41
I/AlertUtils( 6791): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 6791): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arpeggio.ogg
I/AlertUtils( 6791): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 6791): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
,I/AlertUtils( 6791): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 6791): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 6791): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
,I/AlertUtils( 6791): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 6791): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 6791): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
,I/AlertUtils( 6791): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Afternoon_Walk.ogg
I/AlertUtils( 6791): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 6791): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
,I/AlertUtils( 6791): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 6791): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 6791): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6791): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/41
,I/AlertUtils( 6791): set default noti to content://media/internal/audio/media/41
I/InitNotificationRingtoneService( 6791): End InitializeAlertRingtoneService.onHandleIntent
D/MonthWidgetProvider( 6791): [onReceive]
D/CalendarWidgetProvider( 6791): [onReceive]
D/CalendarWidgetProvider( 6791): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.MonthWidgetProvider }
,W/HolidayIntentService( 6791): onHandleIntent
,D/HolidayDataLoader( 6791): readJsonAsset : holiday.json
D/CalendarTypeController( 6791): [onUpdateAndInitCalendarTime]
D/WeekWidgetProvider( 6791): [onReceive]
D/CalendarWidgetProvider( 6791): [onReceive]
D/CalendarWidgetProvider( 6791): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 6791): [onUpdateAndInitCalendarTime]
I/DigitalAppWidgetProvider( 6741): onReceive: android.intent.action.ALARM_CHANGED
,D/WeatherAncestor( 6625): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 14:47:34
D/Weather.Utils( 6625): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6625): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6625): 2 : This is isUpdating : false
D/Weather_cast( 6625): 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
D/WeatherAncestor( 6625): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 14:47:34
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=3.8, 0.0, 0.0  rx=2.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1573059135] gl rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=3.8, 0.0, 0.0  rx=2.8 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1573059134] gl rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/HolidayIntentService( 6791): onHandleIntent:holiday data empty
I/ActivityManager( 1030): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RequestWriter$NetworkStateReceiver: pid=6815 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager( 1030): Killing 6197:com.lge.lifetracker/u0a37 (adj 15): empty #17
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
W/libprocessgroup( 1030): failed to open /acct/uid_10037/pid_6197/cgroup.procs: No such file or directory
,W/ResourcesManager( 6815): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/LgDataFeature( 6815): LgDataFeature() Constructor: none
D/LgDataFeature( 6815): LgDataFeature() Constructor Done, null
,I/art     ( 2185): Explicit concurrent mark sweep GC freed 18343(1047KB) AllocSpace objects, 13(1616KB) LOS objects, 51% free, 30MB/62MB, paused 976us total 34.521ms
,I/Babel   ( 6815): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 6815): MmsConfig.loadMmsSettings
I/Babel   ( 6815): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
I/Babel   ( 6815): MmsConfig.loadFromDatabase
,E/Babel   ( 6815): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 6815): MmsConfig.loadFromResources
E/Babel   ( 6815): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 6815): MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,W/Settings( 6815): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/AudioCapabilities( 6815): Unsupported mime audio/evrc
W/AudioCapabilities( 6815): Unsupported mime audio/qcelp
,W/VideoCapabilities( 6815): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6815): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6815): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6815): Unsupported mime audio/evrc
W/VideoCapabilities( 6815): Unsupported mime video/x-ms-wmv
W/VideoCapabilities( 6815): Unsupported mime video/divx
W/VideoCapabilities( 6815): Unsupported mime video/divx311
W/VideoCapabilities( 6815): Unsupported mime video/divx4
,W/VideoCapabilities( 6815): Unsupported mime video/mp4v-esdp
I/VideoCapabilities( 6815): Unsupported profile 4 for video/mp4v-es
,W/AudioCapabilities( 6815): Unsupported mime audio/eac3
W/AudioCapabilities( 6815): Unsupported mime audio/ac3
W/AudioCapabilities( 6815): Unsupported mime audio/g726
W/AudioCapabilities( 6815): Unsupported mime audio/wma-voice
W/AudioCapabilities( 6815): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6815): Unsupported mime audio/adpcm
W/ResourcesManager( 6815): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6815): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/VideoCapabilities( 6815): Unsupported mime video/theora
W/VideoCapabilities( 6815): Unsupported mime video/mjpg
,V/JNIHelp ( 6815): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/System  ( 6815): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/system/app/Hangouts/Hangouts.apk"],nativeLibraryDirectories=[/system/app/Hangouts/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6815): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 2185): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2185): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native
I/GLSUser ( 2185): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2185): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2185): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2185): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2185): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2185): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2185): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2185): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2185): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/Babel   ( 6815): UserRecoverableAuthException.
,E/Babel   ( 6815): cfq: BadAuthentication
E/Babel   ( 6815): 	at cfn.a(Unknown Source)
E/Babel   ( 6815): 	at f.a(PG:191)
E/Babel   ( 6815): 	at ava.a(PG:88)
E/Babel   ( 6815): 	at ava.a(PG:128)
E/Babel   ( 6815): 	at bjs.a(PG:255)
E/Babel   ( 6815): 	at bep.a(PG:602)
E/Babel   ( 6815): 	at bep.a(PG:469)
E/Babel   ( 6815): 	at bpo.run(PG:1141)
E/Babel   ( 6815): Error getting auth token
E/Babel   ( 6815): bxl
E/Babel   ( 6815): 	at f.a(PG:201)
E/Babel   ( 6815): 	at ava.a(PG:88)
E/Babel   ( 6815): 	at ava.a(PG:128)
E/Babel   ( 6815): 	at bjs.a(PG:255)
E/Babel   ( 6815): 	at bep.a(PG:602)
E/Babel   ( 6815): 	at bep.a(PG:469)
E/Babel   ( 6815): 	at bpo.run(PG:1141)
I/Babel_RequestWriter( 6815): error sending REQ[fc:8; creat:1454420403702; type:bev-785207299]; took 107 ms (error code == 100)
E/Babel   ( 6815): Account registration failedRedacted-21
E/Babel   ( 6815): bph: null -- null
E/Babel   ( 6815): 	at ava.a(PG:120)
E/Babel   ( 6815): 	at ava.a(PG:128)
E/Babel   ( 6815): 	at bjs.a(PG:255)
E/Babel   ( 6815): 	at bep.a(PG:602)
E/Babel   ( 6815): 	at bep.a(PG:469)
E/Babel   ( 6815): 	at bpo.run(PG:1141)
I/Babel   ( 6815): Account setup failed with error state:106 account:Redacted-21
I/Babel   ( 6815): Account sign in complete with state 106account: Redacted-21
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
I/art     ( 6815): Note: end time exceeds epoch: 
D/LgeQuickCoverNLService( 1411): onNotificationPosted
W/GLSActivity( 2185): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2185): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2185): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2185): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2185): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2185): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2185): 	at android.os.Binder.execTransact(Binder.java:446)
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
,E/BooksAccountManager( 6481): Authentication error
E/BooksAccountManager( 6481): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6481): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6481): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6481): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6481): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6481): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6481): null auth token
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{198ef165 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/jxcore-log( 5988): Test app app.js loaded
I/jxcore-log( 5988): 
,I/GLSUser ( 2185): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native
I/GLSUser ( 2185): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2185): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2185): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/chromium( 5988): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
V/GLSActivity( 2185): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5988): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5988): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5988): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5988): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5988): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5988): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5988): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5988): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5988): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5988): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bb5b9d2 added. We now have 1 listener(s)
I/jxcore-log( 5988): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 5988): 
W/ResourcesManager( 2185): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,D/LgeQuickCoverNLService( 1411): onNotificationPosted
,E/Babel   ( 6815): Unexpected exception while authenticating.
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
E/Babel   ( 6815): cfr: User intervention required. Notification has been pushed.
E/Babel   ( 6815): 	at cfn.b(Unknown Source)
E/Babel   ( 6815): 	at cfn.a(Unknown Source)
E/Babel   ( 6815): 	at f.a(PG:188)
E/Babel   ( 6815): 	at ava.b(PG:143)
E/Babel   ( 6815): 	at bnr.run(PG:5415)
E/Babel   ( 6815): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 6815): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 6815): 	at java.lang.Thread.run(Thread.java:818)
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1411): updateNotificationData: count=3
W/ApiaryClient( 6481): Error response from books API: {
W/ApiaryClient( 6481):  "error": {
W/ApiaryClient( 6481):   "errors": [
W/ApiaryClient( 6481):    {
W/ApiaryClient( 6481):     "domain": "global",
W/ApiaryClient( 6481):     "reason": "required",
W/ApiaryClient( 6481):     "message": "Login Required",
W/ApiaryClient( 6481):     "locationType": "header",
W/ApiaryClient( 6481):     "location": "Authorization"
W/ApiaryClient( 6481):    }
W/ApiaryClient( 6481):   ],
W/ApiaryClient( 6481):   "code": 401,
W/ApiaryClient( 6481):   "message": "Login Required"
W/ApiaryClient( 6481):  }
W/ApiaryClient( 6481): }
W/ApiaryClient( 6481): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6481): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7956790022025389583&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6481): Headers:
W/ApiaryClient( 6481): accept-encoding: [gzip]
W/ApiaryClient( 6481): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6481): gdata-version: 2
,D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{198ef165 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ProcessCpuTracker( 1030): Skipping unknown process pid 6861
,E/BooksSync( 6481): Soft error: 
E/BooksSync( 6481): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6481): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7956790022025389583&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6481): Headers:
E/BooksSync( 6481): accept-encoding: [gzip]
E/BooksSync( 6481): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6481): gdata-version: 2
E/BooksSync( 6481): 
E/BooksSync( 6481): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6481): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6481): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6481): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6481): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6481): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6481): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6481): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6481): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6481): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6481): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6481): {
E/BooksSync( 6481):  "error": {
E/BooksSync( 6481):   "errors": [
E/BooksSync( 6481):    {
E/BooksSync( 6481):     "domain": "global",
E/BooksSync( 6481):     "reason": "required",
E/BooksSync( 6481):     "message": "Login Required",
E/BooksSync( 6481):     "locationType": "header",
E/BooksSync( 6481):     "location": "Authorization"
E/BooksSync( 6481):    }
E/BooksSync( 6481):   ],
E/BooksSync( 6481):   "code": 401,
E/BooksSync( 6481):   "message": "Login Required"
E/BooksSync( 6481):  }
E/BooksSync( 6481): }
E/BooksSync( 6481): 
E/BooksSync( 6481): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6481): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6481): 	... 8 more
,E/BooksSync( 6481): Sync error
E/BooksSync( 6481): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6481): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7956790022025389583&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6481): Headers:
E/BooksSync( 6481): accept-encoding: [gzip]
E/BooksSync( 6481): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6481): gdata-version: 2
E/BooksSync( 6481): 
E/BooksSync( 6481): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6481): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6481): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6481): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6481): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6481): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6481): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6481): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6481): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6481): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6481): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6481): {
E/BooksSync( 6481):  "error": {
E/BooksSync( 6481):   "errors": [
E/BooksSync( 6481):    {
E/BooksSync( 6481):     "domain": "global",
E/BooksSync( 6481):     "reason": "required",
E/BooksSync( 6481):     "message": "Login Required",
E/BooksSync( 6481):     "locationType": "header",
E/BooksSync( 6481):     "location": "Authorization"
E/BooksSync( 6481):    }
E/BooksSync( 6481):   ],
E/BooksSync( 6481):   "code": 401,
E/BooksSync( 6481):   "message": "Login Required"
E/BooksSync( 6481):  }
E/BooksSync( 6481): }
E/BooksSync( 6481): 
E/BooksSync( 6481): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6481): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6481): 	... 8 more
I/BooksSync( 6481): Finished books sync
I/ActivityManager( 1030): Killing 5893:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,D/SyncManager( 1030): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 26765, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/QRemote ( 6311): [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
W/System.err( 6311): android.os.DeadObjectException
,W/System.err( 6311): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6311): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6311): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 6311): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
W/System.err( 6311): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 6311): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 6311): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6311): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6311): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6311): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 6311): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6311): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6311): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 6311): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 6311): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 6311): android.os.DeadObjectException
W/System.err( 6311): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6311): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6311): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 6311): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
W/System.err( 6311): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 6311): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 6311): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6311): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6311): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6311): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 6311): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6311): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6311): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 6311): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 6311): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/QRemote ( 6311): [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
I/ActivityManager( 1030): Killing 6236:com.lge.sync/1000 (adj 15): empty #18
,W/libprocessgroup( 1030): failed to open /acct/uid_1000/pid_5893/cgroup.procs: No such file or directory
W/ActivityManager( 1030): Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,W/libprocessgroup( 1030): failed to open /acct/uid_1000/pid_6236/cgroup.procs: No such file or directory
D/QRemote ( 6311): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
I/QRemote ( 6311): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
I/ActivityManager( 1030): Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6867 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,D/QRemote ( 6311): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,I/GAV2    ( 6481): Thread[GAThread,5,main]: No campaign data found.
,D/UEI.SmartControl( 6867): Quickset Services start...
,I/UEI.SmartControl( 6867): Manufacture = LGE
D/UEI.SmartControl( 6867): Id = LGNevo
D/UEI.SmartControl( 6867): File observer start...
E/UEI.SmartControl( 6867): IR Port is disabled: false
D/UEI.SmartControl( 6867): Starting file observer...
D/UEI.SmartControl( 6867): Extracting JNI libs...
D/UEI.SmartControl( 6867): --- this system supports 32-bit or 64-bit only
V/GLSActivity( 2185): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 2392): Explicit concurrent mark sweep GC freed 16543(1195KB) AllocSpace objects, 18(288KB) LOS objects, 33% free, 32MB/48MB, paused 731us total 73.328ms
,D/UEI.SmartControl( 6867): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 6867): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6867): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/art     ( 1030): Explicit concurrent mark sweep GC freed 17690(847KB) AllocSpace objects, 5(592KB) LOS objects, 33% free, 44MB/66MB, paused 1.259ms total 77.648ms
I/GLSUser ( 2185): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 2185): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2185): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2185): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/UEI.SmartControl( 6867): --- Selecting new region: 6
V/GLSActivity( 2185): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/UEI.SmartControl( 6867): Model = LG-D855
D/UEI.SmartControl( 6867): QS Service created
I/UEI.SmartControl( 6867): Service initServices...
,D/UEI.SmartControl( 6867): QS start get config
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2185): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2185): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2185): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2185): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2185): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2185): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2185): 	at android.os.Binder.execTransact(Binder.java:446)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
D/ContactsSyncAdapter( 2185): innerSync failed
D/ContactsSyncAdapter( 2185): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2185): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2185): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2185): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2185): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2185): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2185): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2185): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2185): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2185): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2185): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2185): 	at android.os.Binder.execTransact(Binder.java:446)
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
D/SyncManager( 1030): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 153641, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
,D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{198ef165 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/UEI.SmartControl( 6867): Loading JNI Libs...
,I/UEI.SmartControl( 6867): Supports setup maps: true
,D/UEI.SmartControl( 6867): QS start statue = true Error code = 0
I/UEI.SmartControl( 6867): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6867): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6867): ### init IR Blaster...
D/serial_port( 6867): Configuring serial port
E/UEI.SmartControl( 6867): UEIBLaster setting for 616
I/UEI.SmartControl( 6867): Setting serial record hearder size = 2
,I/UEI.SmartControl( 6867): configuring settings for MAXQ616
,I/UEI.SmartControl( 6867): Get version...
D/UEI.SmartControl( 6867): serial port data available: 21
,D/UEI.SmartControl( 6867): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 6867): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 6867): QS saving settings...
,D/UEI.SmartControl( 6867): IR Blaster version: 25672567
,D/UEI.SmartControl( 6867): serial port data available: 4
,W/ContextImpl( 6867): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,I/UEI.SmartControl( 6867): Device manager: loading config....
D/UEI.SmartControl( 6867): ----------- loading internal config...
E/UEI.SmartControl( 6867): Services init done
D/UEI.SmartControl( 6867): QS Service init finished
D/UEI.SmartControl( 6867): QS Service version name: 2.1.91
D/UEI.SmartControl( 6867): QS Service version code: 201091
D/UEI.SmartControl( 6867): Service requested: Control
,D/UEI.SmartControl( 6867): Request IControl service: devices are loaded...
I/ActivityManager( 1030): Killing 6142:com.android.settings/1000 (adj 15): empty #17
,I/QRemote ( 6311): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 6867): ------ IControl API: 11
I/UEI.SmartControl( 6867): Registering callback...
I/UEI.SmartControl( 6867): ------ IControl API: 19
I/UEI.SmartControl( 6867): Registering Services Ready callback...
E/UEI.SmartControl( 6867): Loading SETTINGS...
,D/UEI.SmartControl( 6867): -- Open brand translation xml: brands_translations_ko
,D/WifiService( 1030): Client connection lost with reason: 4
,W/libprocessgroup( 1030): failed to open /acct/uid_1000/pid_6142/cgroup.procs: No such file or directory
D/UEI.SmartControl( 6867): Internal service binding...
,I/UEI.SmartControl( 6867): Notify AllClients services are ready: 0
I/QRemote ( 6311): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 6311): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 6311): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 6311): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 6311): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6867): ------ IControl API: 8
D/UEI.SmartControl( 6867): -----service ready thread exits
D/QRemote ( 6311): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 6311): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 6311): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 6311): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 6311): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6311): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 6311): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,V/QRemote ( 6311): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6311): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 6311): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6311): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 6311): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6311): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 6311): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 6311): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1454420857125]
D/QRemote ( 6311): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,V/QRemote ( 6311): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
E/QRemote ( 6311): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6311): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 6311): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 6311): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 6311): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 6311): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 6311): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-53 f=2412 sc=60 link=72 tx=19.9, 0.0, 0.0  rx=16.9 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1573056100] gl rssi=-53 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-53 f=2412 sc=60 link=72 tx=19.9, 0.0, 0.0  rx=16.9 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1573056096] gl rssi=-53 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/GAV4    ( 6646): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager( 1030): Killing 6462:com.lge.appbox.client/u0a11 (adj 15): empty #17
W/libprocessgroup( 1030): failed to open /acct/uid_10011/pid_6462/cgroup.procs: No such file or directory
,I/ActivityManager( 1030): Killing 6174:com.lge.formmanager/u0a26 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_10026/pid_6174/cgroup.procs: No such file or directory
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=11.9, 0.0, 0.0  rx=10.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1573053059] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=11.9, 0.0, 0.0  rx=10.4 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1573053055] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/UEI.SmartControl( 6867): Internal timer expired: 1
,D/UEI.SmartControl( 6867): unbind internal service
,D/serial_port( 6867): close(fd = 25)
,I/UEI.SmartControl( 6867): Serial port is closed.
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=7.5, 0.0, 0.0  rx=6.2 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1573050040] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=7.5, 0.0, 0.0  rx=6.2 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1573050036] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,I/ActivityManager( 1030): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=6926 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager( 1030): RTC_WAKEUP set : Alarm{20b5b2f8 type 0 when 1454420863437 com.android.vending} when 1454420863437
,I/art     (  348): Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 448us total 44.728ms
,V/QRemote ( 6311): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
D/QRemote ( 6311): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:143
,I/art     (  348): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 406us total 27.666ms
I/art     (  348): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 416us total 20.603ms
,D/Finsky  ( 6926): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/LgDataFeature( 6926): LgDataFeature() Constructor: none
D/LgDataFeature( 6926): LgDataFeature() Constructor Done, null
,D/Finsky  ( 6926): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/ActivityManager( 1030): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6984 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/Settings( 6926): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6926): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,V/DownloadManager( 3302): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3302): created cursor android.database.sqlite.SQLiteCursor@382e0f5 on behalf of 6926
W/ResourcesManager( 6984): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6984): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/Finsky  ( 6926): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6926): [1] 2.run: Finished loading 1 libraries.
D/Finsky  ( 6926): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 6926): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/MultiDex( 6984): VM with version 2.1.0 has multidex support
I/MultiDex( 6984): install
I/MultiDex( 6984): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6984): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,V/SIM_STK ( 1030): Menu title from STK is T-Mobile
,W/ActivityThread( 6984): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6984): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3324fd2e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6984): Installed default security provider GmsCore_OpenSSL
D/GCM     ( 2185): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AuthorizationBluetoothService( 2185): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 2392): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
I/ActivityManager( 1030): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=7022 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,D/LocationInitializer( 2392): Restart initialization of location
,W/ResourcesManager( 7022): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7022): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 7022): VM with version 2.1.0 has multidex support
I/MultiDex( 7022): install
,I/MultiDex( 7022): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 7022): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
W/ActivityThread( 7022): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7022): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3324fd2e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7022): Installed default security provider GmsCore_OpenSSL
,D/AuthorizationBluetoothService( 2185): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GmsCoreStatsServiceLauncher( 2392): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
V/Finsky  ( 6926): [1] GearheadStateMonitor.onReady: sIsProjecting:false
D/GCM     ( 2185): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/WearableService( 7022): callingUid 10005, callindPid: 7022
E/MDM     ( 1832): [84] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
D/LocationInitializer( 2392): Restart initialization of location
,E/MDM     ( 1832): [84] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
V/GLSActivity( 2185): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2185): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2185): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2185): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2185): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2185): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6926): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6926): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6926): [1] 5.onFinished: Scheduling replication attempt 2.
,I/ActivityManager( 1030): Killing 6601:com.lge.drmservice/u0a62 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_10062/pid_6601/cgroup.procs: No such file or directory
,D/Finsky  ( 6926): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/AlarmManager( 1030): RTC_WAKEUP set : Alarm{374cf20f type 0 when 1454420865076 com.android.vending} when 1454420865076
V/GLSActivity( 2185): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2185): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2185): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2185): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2185): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2185): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 6926): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 2185): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2185): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2185): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2185): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2185): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2185): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2185): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2185): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2185): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2185): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2185): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2185): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 6926): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/SIM_STK ( 1030): Menu title from STK is T-Mobile
,V/GLSActivity( 2185): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2185): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2185): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2185): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2185): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2185): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 2185): Explicit concurrent mark sweep GC freed 23598(1412KB) AllocSpace objects, 9(1296KB) LOS objects, 51% free, 30MB/62MB, paused 2.152ms total 75.429ms
,W/Finsky  ( 6926): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 6926): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
D/Finsky  ( 6926): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6926): [1] DailyHygiene.reschedule: Scheduling new run in 32 minutes (failures=2)
D/DeviceConnectionService( 1832): client connected with version: 7571000
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=4.2, 0.0, 0.0  rx=3.6 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1573047011] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=4.2, 0.0, 0.0  rx=3.6 bcn=0 [on:0 tx:0 rx:0 period:20] from screen [on:0 period:-1573046991] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 137725057139; DSPS: 4653881; Offset : -4312266866
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=2.1, 0.0, 0.0  rx=1.8 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1573043970] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=2.1, 0.0, 0.0  rx=1.8 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1573043961] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
I/ActivityManager( 1030): Killing 6646:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,I/ActivityManager( 1030): Killing 6497:com.android.gallery3d/u0a27 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_10093/pid_6646/cgroup.procs: No such file or directory
,W/libprocessgroup( 1030): failed to open /acct/uid_10027/pid_6497/cgroup.procs: No such file or directory
I/[SystemUI]QPairHandler( 1456): onReceive = android.intent.action.PACKAGE_CHANGED
,D/SplitUIService( 1884): replaced split : contains_com.google.android.talk / true
,I/InputReader( 1030): Reconfiguring input devices.  changes=0x00000010
,D/SplitUIManager( 1884): split_name #11 / not available #0
I/SplitUIService( 1884): split app #11
,I/[LGHome]EVENT( 2082): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000010 (has extras) }
I/ActivityManager( 1030): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7073 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ResourcesManager( 2082): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/[SystemUI]QSlideListController( 1456): onReceive = android.intent.action.PACKAGE_CHANGED
,I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1456): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.talk
D/administrator( 1030): Handling package changes for user 0
I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/AppUp4:AppBoxCP( 7073): onCreate
,W/AppUp4:DB( 7073):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7073):  setFingerPrint start
I/AppUp4:DB( 7073):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,I/AppUp4:DB( 7073):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7073):  SDK version = 21
,I/AppUp4:DB( 7073):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7073): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 7073): onReceive
,D/LgDataFeature( 7073): LgDataFeature() Constructor: none
D/LgDataFeature( 7073): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7073): Context : android.app.ReceiverRestrictedContext@2d482146
D/AppUp4:CustFacade( 7073): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7073): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7073): begin check event
I/AppUp4:CustModeStarterReceiver( 7073): Event For Nothing, skip.
I/NotificationService( 1030): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService( 1030): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000010 (has extras) }
,W/ResourcesManager( 1030): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/ActivityManager( 1030): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7109 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/ActivityManager( 1030): Killing 6701:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,W/ResourcesManager( 1030): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourceType( 1030): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
W/libprocessgroup( 1030): failed to open /acct/uid_10097/pid_6701/cgroup.procs: No such file or directory
,I/[LGHome]EVENT( 2082): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
W/ResourcesManager( 7109): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7109): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7109): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7109): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7109): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 7109): BUILD Country: EU
I/SystemConfig( 7109): BUILD Operator: OPEN
,I/ActivityManager( 1030): Killing 6519:com.android.chrome/u0a57 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_10057/pid_6519/cgroup.procs: No such file or directory
,I/SystemConfig( 7109): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7109): existFile = false
I/SystemConfig( 7109): canReadFile = false
I/SystemConfig( 7109): systemFeature RCS result false
D/SystemConfig( 7109): refreshRcsSupport() :false
,I/ActivityManager( 1030): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7132 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/ResourcesManager( 7132): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7132): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7132): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 7132): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,I/AppConfig( 7132): Total System Memory = 2995761152
,D/SystemHelper( 7132): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager( 1030): Killing 6544:com.lge.email/u0a23 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_10023/pid_6544/cgroup.procs: No such file or directory
,I/UpdateIcingCorporaServi( 4212): Updating corpora: APPS=com.google.android.talk, CONTACTS=MAYBE
V/SIM_STK ( 1030): Menu title from STK is T-Mobile
,I/ActivityManager( 1030): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7152 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 4212): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/UpdateIcingCorporaServi( 4212): UpdateCorporaTask done [took 80 ms] updated apps [took 80 ms] 
,I/LockScreenSettings( 7152): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7152): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7152): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7152): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7152): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
,D/LockScreenSettings( 7152): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
D/LockScreenSettings( 7152): Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
I/ActivityManager( 1030): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7169 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1030): Killing 5131:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_1000/pid_5131/cgroup.procs: No such file or directory
,W/ResourcesManager( 7169): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/art     ( 1030): Explicit concurrent mark sweep GC freed 36256(1679KB) AllocSpace objects, 3(176KB) LOS objects, 33% free, 44MB/66MB, paused 4.112ms total 196.928ms
,D/PackageBroadcastService( 2392): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.talk
,I/PeopleContactsSync( 2392): CP2 sync disabled
,I/GLSActivity( 2185): [ac] getting account id
,I/GLSUser ( 2185): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.6, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1573040950] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.6, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:6] from screen [on:0 period:-1573040944] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1573037914] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1573037911] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,I/ActivityManager( 1030): Killing 6773:com.qualcomm.timeservice/1000 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_1000/pid_6773/cgroup.procs: No such file or directory
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1573034885] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1573034882] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1456): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1456): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1456): called onTimeUpdated()
,I/[SystemUI]Clock( 1456): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1456): called onTimeUpdated()
,I/[SystemUI]DateView( 1456): called onTimeUpdated()
I/[SystemUI]DateView( 1456): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1456): handleTimeUpdate
,I/[SystemUI]TimeTickManager( 1456): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1456): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1456): called onTimeUpdated()
,I/[SystemUI]Clock( 1456): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1456): called onTimeUpdated()
,I/[SystemUI]DateView( 1456): called onTimeUpdated()
,I/[SystemUI]DateView( 1456): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1456): handleTimeUpdate
D/PowerManagerServiceEx( 1030): acquireWakeLockInternal: lock=709869794, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1030
,V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{2ef92608 type 2 when 150887 android} when 150887
D/[Concierge]Service( 2608): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1030): releaseWakeLockInternal: lock=709869794 [*alarm*], flags=0x0
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1573031858] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1573031855] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1573028828] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1573028825] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,E/WifiStateMachine( 1030):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1030):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,E/WifiStateMachine( 1030):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,E/WifiStateMachine( 1030):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1573025798] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1573025795] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 157729479475; DSPS: 5309386; Offset : -4312269528
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1573022771] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1573022760] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1573019738] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1573019735] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1573016705] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1573016702] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,V/AlarmManager( 1030): RTC_WAKEUP set : Alarm{19fd7fc6 type 0 when 1454420885325 com.android.vending} when 1454420885325
,V/SIM_STK ( 1030): Menu title from STK is T-Mobile
,V/GLSActivity( 2185): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 2185): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2185): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2185): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2185): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2185): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6926): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6926): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6926): [1] 5.onFinished: Scheduling replication attempt 3.
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1573013672] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1573013669] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1573010653] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1573010650] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1573007621] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1573007608] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 177732387176; DSPS: 5964841; Offset : -4312261100
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1573004584] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1573004581] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{b462138 type 2 when 180972 android} when 180972
,I/BooksSync( 6481): Starting books sync
,D/BooksSync( 6481): started syncMyEbooks
,V/GLSActivity( 2185): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2185): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2185): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2185): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2185): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2185): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
,D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2185): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2185): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2185): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2185): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2185): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2185): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2185): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6481): Authentication error
E/BooksAccountManager( 6481): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6481): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6481): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6481): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6481): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6481): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6481): null auth token
,D/LgeQuickCoverNLService( 1411): onNotificationPosted
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
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{198ef165 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,I/GLSUser ( 2185): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 2185): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2185): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2185): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2185): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
,W/ApiaryClient( 6481): Error response from books API: {
W/ApiaryClient( 6481):  "error": {
W/ApiaryClient( 6481):   "errors": [
W/ApiaryClient( 6481):    {
W/ApiaryClient( 6481):     "domain": "global",
W/ApiaryClient( 6481):     "reason": "required",
W/ApiaryClient( 6481):     "message": "Login Required",
W/ApiaryClient( 6481):     "locationType": "header",
W/ApiaryClient( 6481):     "location": "Authorization"
W/ApiaryClient( 6481):    }
W/ApiaryClient( 6481):   ],
W/ApiaryClient( 6481):   "code": 401,
W/ApiaryClient( 6481):   "message": "Login Required"
W/ApiaryClient( 6481):  }
W/ApiaryClient( 6481): }
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/ApiaryClient( 6481): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6481): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=815405099522697424&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6481): Headers:
W/ApiaryClient( 6481): accept-encoding: [gzip]
W/ApiaryClient( 6481): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6481): gdata-version: 2
W/GLSActivity( 2185): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2185): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2185): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2185): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2185): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2185): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2185): 	at android.os.Binder.execTransact(Binder.java:446)
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
D/ContactsSyncAdapter( 2185): innerSync failed
D/ContactsSyncAdapter( 2185): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2185): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2185): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2185): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2185): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2185): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2185): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2185): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2185): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2185): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2185): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2185): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  2
,D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1411): updateNotificationData: count=3
D/SyncManager( 1030): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 153641, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
,D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{198ef165 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/SyncManager( 1030): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 243622, reason: 10019
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1573001556] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1573001555] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,V/GLSActivity( 2185): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2185): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2185): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2185): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2185): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2185): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,W/GLSActivity( 2185): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2185): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2185): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2185): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2185): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2185): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2185): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6481): Authentication error
E/BooksAccountManager( 6481): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6481): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6481): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6481): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6481): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6481): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6481): null auth token
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{198ef165 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6481): Error response from books API: {
W/ApiaryClient( 6481):  "error": {
W/ApiaryClient( 6481):   "errors": [
W/ApiaryClient( 6481):    {
W/ApiaryClient( 6481):     "domain": "global",
W/ApiaryClient( 6481):     "reason": "required",
W/ApiaryClient( 6481):     "message": "Login Required",
W/ApiaryClient( 6481):     "locationType": "header",
W/ApiaryClient( 6481):     "location": "Authorization"
W/ApiaryClient( 6481):    }
W/ApiaryClient( 6481):   ],
W/ApiaryClient( 6481):   "code": 401,
W/ApiaryClient( 6481):   "message": "Login Required"
W/ApiaryClient( 6481):  }
W/ApiaryClient( 6481): }
,W/ApiaryClient( 6481): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6481): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=815405099522697424&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6481): Headers:
W/ApiaryClient( 6481): accept-encoding: [gzip]
W/ApiaryClient( 6481): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6481): gdata-version: 2
,V/GLSActivity( 2185): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2185): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2185): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2185): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2185): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2185): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
W/GLSActivity( 2185): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2185): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2185): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2185): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2185): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2185): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2185): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6481): Authentication error
E/BooksAccountManager( 6481): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6481): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6481): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6481): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6481): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6481): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6481): null auth token
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{198ef165 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6481): Error response from books API: {
W/ApiaryClient( 6481):  "error": {
W/ApiaryClient( 6481):   "errors": [
W/ApiaryClient( 6481):    {
W/ApiaryClient( 6481):     "domain": "global",
W/ApiaryClient( 6481):     "reason": "required",
W/ApiaryClient( 6481):     "message": "Login Required",
W/ApiaryClient( 6481):     "locationType": "header",
W/ApiaryClient( 6481):     "location": "Authorization"
W/ApiaryClient( 6481):    }
W/ApiaryClient( 6481):   ],
W/ApiaryClient( 6481):   "code": 401,
W/ApiaryClient( 6481):   "message": "Login Required"
W/ApiaryClient( 6481):  }
W/ApiaryClient( 6481): }
,W/ApiaryClient( 6481): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6481): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=815405099522697424&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6481): Headers:
W/ApiaryClient( 6481): accept-encoding: [gzip]
W/ApiaryClient( 6481): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6481): gdata-version: 2
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1572998546] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1572998543] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/BooksSync( 6481): Soft error: 
E/BooksSync( 6481): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6481): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=815405099522697424&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6481): Headers:
E/BooksSync( 6481): accept-encoding: [gzip]
E/BooksSync( 6481): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6481): gdata-version: 2
E/BooksSync( 6481): 
E/BooksSync( 6481): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6481): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6481): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6481): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6481): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6481): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6481): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6481): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6481): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6481): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6481): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6481): {
E/BooksSync( 6481):  "error": {
E/BooksSync( 6481):   "errors": [
E/BooksSync( 6481):    {
E/BooksSync( 6481):     "domain": "global",
E/BooksSync( 6481):     "reason": "required",
E/BooksSync( 6481):     "message": "Login Required",
E/BooksSync( 6481):     "locationType": "header",
E/BooksSync( 6481):     "location": "Authorization"
E/BooksSync( 6481):    }
E/BooksSync( 6481):   ],
E/BooksSync( 6481):   "code": 401,
E/BooksSync( 6481):   "message": "Login Required"
E/BooksSync( 6481):  }
E/BooksSync( 6481): }
E/BooksSync( 6481): 
E/BooksSync( 6481): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6481): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6481): 	... 8 more
,E/BooksSync( 6481): Sync error
E/BooksSync( 6481): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6481): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=815405099522697424&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6481): Headers:
E/BooksSync( 6481): accept-encoding: [gzip]
E/BooksSync( 6481): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6481): gdata-version: 2
E/BooksSync( 6481): 
E/BooksSync( 6481): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6481): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6481): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6481): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6481): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6481): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6481): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6481): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6481): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6481): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6481): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6481): {
E/BooksSync( 6481):  "error": {
E/BooksSync( 6481):   "errors": [
E/BooksSync( 6481):    {
E/BooksSync( 6481):     "domain": "global",
E/BooksSync( 6481):     "reason": "required",
E/BooksSync( 6481):     "message": "Login Required",
E/BooksSync( 6481):     "locationType": "header",
E/BooksSync( 6481):     "location": "Authorization"
E/BooksSync( 6481):    }
E/BooksSync( 6481):   ],
E/BooksSync( 6481):   "code": 401,
E/BooksSync( 6481):   "message": "Login Required"
E/BooksSync( 6481):  }
E/BooksSync( 6481): }
E/BooksSync( 6481): 
E/BooksSync( 6481): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6481): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6481): 	... 8 more
I/BooksSync( 6481): Finished books sync
D/SyncManager( 1030): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 158187, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=4.2, 0.0, 0.0  rx=3.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1572995518] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=4.2, 0.0, 0.0  rx=3.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1572995515] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,I/[SystemUI]LGPowerUI( 1456): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1456): On Skip Timer : true
,D/WifiController( 1030): battery changed pluggedType: 2
,D/LEDHandler( 1963): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1963): Battery Level Remaining: 100%
D/LEDHandler( 1963): Battery Temp: 292, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1456): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 292
I/[SystemUI]LGPowerUI( 1456): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 6092): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1456): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3963): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 3963): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=2.1, 0.0, 0.0  rx=1.9 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1572992492] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=2.1, 0.0, 0.0  rx=1.9 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1572992482] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.6, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1572989461] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.6, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1572989449] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.3, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1572986427] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.3, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1572986424] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 197734491908; DSPS: 6620270; Offset : -4312261717
,V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{3d1f747 type 2 when 179220 com.google.android.gms} when 179220
,V/AlarmManager( 1030): RTC_WAKEUP set : Alarm{3ca9389d type 0 when 1454420919593 com.android.vending} when 1454420919593
,V/GLSActivity( 2185): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/SIM_STK ( 1030): Menu title from STK is T-Mobile
,I/VacuumService( 2185): Vacuum at: now=1454420928231 tag=VacuumService
,I/GoogleURLConnFactory( 2185): Using platform SSLCertificateSocketFactory
,W/Uploader( 2185): No account for auth token provided
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  314): res_queryN name = play.googleapis.com, class = 1, type = 1
,D/libc-netbsd(  314): res_queryN name = play.googleapis.com succeed
,V/GLSActivity( 2185): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1030): Explicit concurrent mark sweep GC freed 42711(1968KB) AllocSpace objects, 6(608KB) LOS objects, 33% free, 44MB/66MB, paused 1.959ms total 133.620ms
,W/Uploader( 2185): No account for auth token provided
,I/GLSUser ( 2185): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2185): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2185): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2185): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2185): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6926): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6926): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6926): [1] 5.onFinished: Scheduling replication attempt 4.
,W/Uploader( 2185):  no longer exists, so no auth token.
,W/Uploader( 2185): No account for auth token provided
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1572983396] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:17] from screen [on:0 period:-1572983379] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=7.8, 0.0, 0.0  rx=6.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1572980356] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=7.8, 0.0, 0.0  rx=6.3 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1572980352] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=3.9, 0.0, 0.0  rx=3.2 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1572977322] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=3.9, 0.0, 0.0  rx=3.2 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1572977312] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=2.5, 0.0, 0.0  rx=2.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1572974290] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=2.5, 0.0, 0.0  rx=2.1 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1572974278] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
I/[SystemUI]TimeTickManager( 1456): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1456): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1456): called onTimeUpdated()
I/[SystemUI]Clock( 1456): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1456): called onTimeUpdated()
,I/[SystemUI]DateView( 1456): called onTimeUpdated()
I/[SystemUI]DateView( 1456): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1456): handleTimeUpdate
,D/PowerManagerServiceEx( 1030): acquireWakeLockInternal: lock=709869794, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1030,
,V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{393e06c5 type 2 when 211053 android} when 211053
D/[Concierge]Service( 2608): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1030): releaseWakeLockInternal: lock=709869794 [*alarm*], flags=0x0
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.7, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1572971257] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.7, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1572971254] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1572968229] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1572968226] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 217736538880; DSPS: 7275697; Offset : -4312259579
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1572965201] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:8] from screen [on:0 period:-1572965193] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1572962184] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1572962181] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{6d7181a type 2 when 213427 android} when 213427
,V/AlarmManager( 1030): RTC_WAKEUP set : Alarm{3b089d28 type 0 when 1454420948590 com.android.vending} when 1454420948590
,V/SIM_STK ( 1030): Menu title from STK is T-Mobile
,V/GLSActivity( 2185): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2185): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2185): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2185): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2185): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2185): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6926): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6926): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6926): [1] 5.onFinished: Scheduling replication attempt 5.
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1572959154] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1572959151] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1572956130] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1572956127] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1572953106] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1572953103] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,I/wpa_supplicant( 6160): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/Tethering( 1030): InitialState.processMessage what=4
,D/Tethering( 1030): sendTetherStateChangedBroadcast 0, 0, 0
E/WifiStateMachine( 1030):  ConnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
E/WifiMonitor( 1030): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
D/WifiMonitor( 1030): handleNetworkStateChange: Could not parse disconnect string
E/WifiMonitor( 1030): WifiMonitor notify network disconnect: null reason=0
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,E/WifiStateMachine( 1030):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  ConnectedState NETWORK_DISCONNECTION_EVENT nid=0 reason=0 lastbssid=c0:ff:d4:d3:aa:48 freq=2412 rssi=-63 rt=232865
E/WifiStateMachine( 1030):  L2ConnectedState NETWORK_DISCONNECTION_EVENT nid=0 reason=0 lastbssid=c0:ff:d4:d3:aa:48 freq=2412 rssi=-63 rt=232866
E/WifiStateMachine( 1030):  ConnectModeState NETWORK_DISCONNECTION_EVENT nid=0 reason=0 lastbssid=c0:ff:d4:d3:aa:48 freq=2412 rssi=-63 rt=232866
E/WifiConfigStore( 1030): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1030): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1030): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1030): doBoolean: SAVE_CONFIG
,D/WifiNative-wlan0( 1030): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1030): doBoolean: DRIVER BTCOEXMODE 2
,I/wpa_supplicant( 6160): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
I/wpa_supplicant( 6160): wlan0: CTRL-EVENT-SCAN-STARTED 
D/LGWifiP2pService( 1030): InactiveState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2pEnabledState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1030): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1030): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-wlan0( 1030): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET ps 1
I/ActivityManager( 1030): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=7302 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/WifiNative-wlan0( 1030): SET ps 1: returned true
D/CommandListener(  314): Clearing all IP addresses on wlan0
,D/DhcpStateMachine( 1030): RunningState{ when=-15ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
V/NativeCrypto( 2185): Read error: ssl=0xaa6f6400: I/O error during system call, Connection timed out
V/NativeCrypto( 2185): SSL shutdown failed: ssl=0xaa6f6400: I/O error during system call, Broken pipe
,D/ConnectivityService( 1030): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1030): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,D/WifiHS20( 1030): hidePasspointNotification off =false
I/StatusBar.NetworkController( 1456): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1456): mWifiConnected = false, mWifiLevel = 0
V/WfdStateTracker( 1963): handleWifiStateChangedEvent: 0
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
,W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20( 1030): hidePasspointNotification off =false
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,I/StatusBar.NetworkController( 1456): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1456): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1030): WifiStateMachine: Leaving Connected state
E/WifiStateMachine( 1030):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=233006  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
D/ConnectivityService( 1030): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=233007  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): Forcing reevaluation
E/WifiStateMachine( 1030):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=233008  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): Checking http://clients3.google.com/generate_204 on <unknown ssid>
E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=233010  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine( 1030):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiNetworkAgent( 1030): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine( 1030):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiHS20( 1030): hidePasspointNotification off =false
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/StatusBar.NetworkController( 1456): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1456): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateSCANNING
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/StatusBar.NetworkController( 1456): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1456): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1030): Default network via Wi-Fi disconnect. stop DSQN
,D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1030): disableDataServiceNotify
D/DSQN    ( 1030): stop dsqn bin
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/DSQN    ( 1030): DNSproblemNotiEnabled is disabled ignore DNS fail CB
W/ResourcesManager( 7302): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7302): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 7302): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7302): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 7302): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7302): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ConnectivityService( 1030): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1030):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1030):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1030): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/Nat464Xlat( 1030): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityManager.CallbackHandler( 1456): CM callback handler got msg 524292
D/CSLegacyTypeTracker( 1030): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1030): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1030): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): Disconnected - quitting
V/NetworkPolicy( 1030): [LG_RESTRICTED] !!!isConnected  type  :1
D/LocSvc_java( 1030): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1030): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1030): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1030): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService( 1030): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1030): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1030): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1030): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1030): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1030): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1030):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
V/NetworkPolicy( 1030): [LG_RESTRICTED] !!!isConnected  type  :1
D/LocSvc_java( 1030): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1030): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1030): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1030): ignore wifi update if we are not in OPENING or CLOSING
D/NetworkManagementService( 1030): Removing idletimer
W/Settings( 1030): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1030): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
E/ConnectivityService( 1030): EVENT_NETWORK_INFO_CHANGED from unknown Network,Agent
D/TelephonyNetworkFactory-1( 1867): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1867):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,D/TelephonyIcons( 1456): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/TelephonyIcons( 1456): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
D/UsbSettingsReceiver( 7302): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7302): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7302): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7302): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7302): [AUTORUN] onReceive() : app userid = 0, current userid = 0
,D/UsbSettingsControl( 7302): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7302): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 7302): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7302): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7302): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 7302): [AUTORUN] setTetherStatus() : status=false
,D/DhcpStateMachine( 1030): StoppedState
,I/ActivityManager( 1030): Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=7344 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1030): Killing 6791:com.android.calendar/u0a13 (adj 15): empty #17
W/libprocessgroup( 1030): failed to open /acct/uid_10013/pid_6791/cgroup.procs: No such file or directory
,W/ResourcesManager( 7344): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/PluginManager( 7344): init()
,E/WifiStateMachine( 1030):  DisconnectedState CMD_RSSI_POLL 1 0 0x 00:00:00:00:00:00 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2999] from screen [on:0 period:-1572950082] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  ConnectModeState CMD_RSSI_POLL 1 0 0x 00:00:00:00:00:00 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1572950081] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  DriverStartedState CMD_RSSI_POLL 1 0 0x 00:00:00:00:00:00 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1572950080] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_RSSI_POLL 1 0 0x 00:00:00:00:00:00 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1572950079] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  DefaultState CMD_RSSI_POLL 1 0 0x 00:00:00:00:00:00 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1572950078] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
W/ExternalStrings( 7344): load override strings
W/ExternalStrings( 7344): java.lang.RuntimeException: Unexpected tag, got eat-comment
W/ExternalStrings( 7344): 	at com.mcafee.plugin.af.a(Unknown Source)
W/ExternalStrings( 7344): 	at com.mcafee.plugin.ac.b(Unknown Source)
W/ExternalStrings( 7344): 	at com.mcafee.plugin.ak.d(Unknown Source)
W/ExternalStrings( 7344): 	at com.mcafee.plugin.ak.a(Unknown Source)
W/ExternalStrings( 7344): 	at com.mcafee.app.s.getClassLoader(Unknown Source)
W/ExternalStrings( 7344): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
W/ExternalStrings( 7344): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
W/ExternalStrings( 7344): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
W/ExternalStrings( 7344): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
W/ExternalStrings( 7344): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
W/ExternalStrings( 7344): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ExternalStrings( 7344): 	at android.os.Looper.loop(Looper.java:135)
W/ExternalStrings( 7344): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/ExternalStrings( 7344): 	at java.lang.reflect.Method.invoke(Native Method)
W/ExternalStrings( 7344): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/ExternalStrings( 7344): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/ExternalStrings( 7344): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,D/StatusProvider( 7344): onCreate
V/Signer  ( 7344): override build config not found
,D/Signer  ( 7344): value of property debug is false
D/LGMDMWrapper( 7344): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
,D/LGMDMWrapper( 7344): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
D/LGMDMWrapper( 7344): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
D/LGMDMWrapper( 7344): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
D/LGMDMWrapper( 7344): Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
D/LGMDMWrapper( 7344): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
D/LGMDMWrapper( 7344): Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
D/LGMDMWrapper( 7344): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
D/LGMDMWrapper( 7344): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
D/LGMDMWrapper( 7344): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
D/LGMDMWrapper( 7344): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
D/LGMDMWrapper( 7344): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
D/LGMDMWrapper( 7344): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
V/LGMDMManager( 7344): Create singleton instance
,D/LGMDMWrapper( 7344): LG MDM library v4.0.0 is available on this device.
,W/ContextImpl( 7344): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,D/PostponalbeReceiver( 7344): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/ActivityManager( 1030): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7373 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/ActivityManager( 1030): Killing 6741:com.lge.clock/u0a10 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_10010/pid_6741/cgroup.procs: No such file or directory
,W/ActivityThread( 7344): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
I/PCSuite ( 7373): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 7373): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7373): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7302): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/LgDataFeature( 7302): LgDataFeature() Constructor: none
,D/LgDataFeature( 7302): LgDataFeature() Constructor Done, null
,D/WiFiOffLoadBroadcast( 7302): MCCMNC not supported: null
D/QRemote ( 6311): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6311): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/LgDataFeature( 7344): LgDataFeature() Constructor: none
D/LgDataFeature( 7344): LgDataFeature() Constructor Done, null
I/QRemote ( 6311): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 7344): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 7344): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,I/PCSuite ( 7373): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7373): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7373): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7302): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7302): MCCMNC not supported: null
D/QRemote ( 6311): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6311): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6311): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 7344): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,W/ContextImpl( 7344): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
I/PCSuite ( 7373): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7373): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7373): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7302): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7302): MCCMNC not supported: null
D/QRemote ( 6311): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6311): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6311): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 7344): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 7344): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
V/WiFiOffLoadBroadcast( 7302): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7302): MCCMNC not supported: null
D/QRemote ( 6311): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6311): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6311): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 7344): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
D/PostponalbeReceiver( 7344): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
D/PostponalbeReceiver( 7344): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
D/PostponalbeReceiver( 7344): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
I/ActivityManager( 1030): Killing 6625:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,W/ContextImpl( 7344): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
,W/libprocessgroup( 1030): failed to open /acct/uid_10085/pid_6625/cgroup.procs: No such file or directory
,D/SiteAdvisor( 7344): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
,D/SiteAdvisor( 7344): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
,D/SiteAdvisor( 7344): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
D/SiteAdvisor( 7344): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
D/SiteAdvisor( 7344): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
I/SiteAdvisor( 7344): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
D/SiteAdvisor( 7344): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
,D/SiteAdvisor( 7344): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
,I/wpa_supplicant( 6160): Trying to associate with SSID 'NG700'
,E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1030): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1030): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=25 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1030): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1030):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
E/WifiStateMachine( 1030):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
E/WifiStateMachine( 1030):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
E/WifiStateMachine( 1030):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
D/WifiNative-wlan0( 1030): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1030):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=235055  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=235056  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
I/StatusBar.NetworkController( 1456): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1456): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [SCANNING]
,W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateASSOCIATING
I/StatusBar.NetworkController( 1456): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1456): mWifiConnected = false, mWifiLevel = 0
D/PostponalbeReceiver( 7344): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
,V/WiFiOffLoadBroadcast( 7302): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7302): MCCMNC not supported: null
D/QRemote ( 6311): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6311): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6311): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 7344): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7302): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/wpa_supplicant( 6160): wlan0: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1030): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=28 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WiFiOffLoadBroadcast( 7302): MCCMNC not supported: null
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,E/WifiStateMachine( 1030):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=235169  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=235170  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1030):  DisconnectedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=235172
E/WifiStateMachine( 1030):  ConnectModeState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=235173
E/WifiStateMachine( 1030):  DriverStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=235174
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=235174
E/WifiStateMachine( 1030):  DefaultState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=235175
D/Tethering( 1030): sendTetherStateChangedBroadcast 1, 0, 0
E/WifiStateMachine( 1030):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=235175  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/wpa_supplicant( 6160): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP],
I/wpa_supplicant( 6160): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1030): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=31 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1030): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1030): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=235188  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
D/QRemote ( 6311): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6311): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6311): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/StatusBar.NetworkController( 1456): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1456): mWifiConnected = false, mWifiLevel = 0
,W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1030):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateASSOCIATED
E/WifiStateMachine( 1030):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1030):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=235200  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=235201  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
I/StatusBar.NetworkController( 1456): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1456): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1030):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=235201
E/WifiStateMachine( 1030):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=235202
D/WifiNative-wlan0( 1030): doString: [STATUS]
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiMonitor( 1030): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1030): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1030):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
D/UsbSettingsReceiver( 7302): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7302): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7302): [AUTORUN] sys.usb.state = ptp_only,adb
,D/UsbSettingsReceiver( 7302): [AUTORUN] persist.sys.usb.config = ptp_only,adb
I/WifiServiceExtension( 1030): setVHTCapabilityType  : false
D/UsbSettingsReceiver( 7302): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 7302): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7302): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 7302): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7302): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7302): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 7302): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 7302): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 7344): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/WifiServerServiceExt( 1030): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1030): setKeepAlivePacketInterval msec : 60
I/StatusBar.NetworkController( 1456): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1456): mWifiConnected = false, mWifiLevel = 0
,W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WiFiOffLoadBroadcast( 7302): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/StatusBar.NetworkController( 1456): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1456): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,D/WiFiOffLoadBroadcast( 7302): MCCMNC not supported: null
D/ConnectivityService( 1030): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService( 1030): Got NetworkAgent Messenger
D/ConnectivityService( 1030): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1030): NetworkAgent connected
E/WifiConfigStore( 1030): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1030): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1030): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1030): doBoolean: SAVE_CONFIG
D/QRemote ( 6311): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6311): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6311): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/WifiNative-wlan0( 1030): SAVE_CONFIG: returned true
E/WifiConfigStore( 1030): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1030): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1030): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1030): doBoolean: SAVE_CONFIG
,D/PostponalbeReceiver( 7344): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiNative-wlan0( 1030): SAVE_CONFIG: returned true
D/CommandListener(  314): Setting iface cfg
E/WifiStateMachine( 1030): Start Dhcp Watchdog 2
D/DhcpStateMachine( 1030): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1030): WaitBeforeStartState
E/WifiStateMachine( 1030):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=235258  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1030):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=235258  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
V/WiFiOffLoadBroadcast( 7302): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=235260  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
,D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateFOUR_WAY_HANDSHAKE
D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1030):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=235263  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1030):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=235263  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1030):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=235263  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1030):  ObtainingIpState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1895] from screen [on:0 period:-1572948183] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1572948182] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
D/WiFiOffLoadBroadcast( 7302): MCCMNC not supported: null
D/ConnectivityService( 1030): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
E/WifiStateMachine( 1030):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1030):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1030): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1030):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=100,0,0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=100,0,0
D/WifiNative-wlan0( 1030): doBoolean: DRIVER SETSUSPENDMODE 0
D/QRemote ( 6311): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6311): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6311): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 7344): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/wpa_supplicant( 6160): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
V/WiFiOffLoadBroadcast( 7302): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WifiNative-wlan0( 1030): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET ps 0
D/WifiNative-wlan0( 1030): SET ps 0: returned true
D/WifiNative-wlan0( 1030): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 6160): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1030): DRIVER BTCOEXMODE 1: returned true
D/LGWifiP2pService( 1030): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2205d076 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2205d076 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1030): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1030): DHCP Start wake lock is acquired.
E/WifiStateMachine( 1030): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1030): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1030): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/CommandListener(  314): Setting iface cfg
D/CommandListener(  314): Trying to bring up wlan0
V/LgDhcpStateMachineHelper( 1030): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1030): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1030):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
E/WifiStateMachine( 1030):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
D/WifiNative-wlan0( 1030): doBoolean: DRIVER BTCOEXMODE 2
D/WifiServerServiceExt( 1030): SUPPLICANT_STATE_CHANGED_ACTION
I/wpa_supplicant( 6160): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiServerServiceExt( 1030): setSupplicantStateCOMPLETED
D/LGWifiP2pService( 1030): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1030): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-wlan0( 1030): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1030): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 6160): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1030): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1030): doBoolean: SET ps 1
D/WiFiOffLoadBroadcast( 7302): MCCMNC not supported: null
D/QRemote ( 6311): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6311): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6311): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 7344): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiNative-wlan0( 1030): SET ps 1: returned true
E/WifiStateMachine( 1030):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1030):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1030):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1030): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1030):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1030):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1030):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
D/ConnectivityService( 1030): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1030): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1030): ignoring duplicate network state non-change
V/WiFiOffLoadBroadcast( 7302): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/StatusBar.NetworkController( 1456): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1456): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/ConnectivityService( 1030): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService( 1030): Adding iface wlan0 to network 101
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
E/WifiStateMachine( 1030): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
V/WfdStateTracker( 1963): handleWifiStateChangedEvent: 1
D/WifiHS20( 1030): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20( 1030): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings( 1030): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1030): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1030): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/StatusBar.NetworkController( 1456): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1456): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1456): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/StatusBar.NetworkController( 1456): mWifiConnected = true, mWifiLevel = 2
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WiFiOffLoadBroadcast( 7302): MCCMNC not supported: null
I/StatusBar.NetworkController( 1456): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1456): mWifiConnected = true, mWifiLevel = 2
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
D/QRemote ( 6311): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6311): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6311): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
E/ConnectivityService( 1030): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1030): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/PostponalbeReceiver( 7344): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/ConnectivityService( 1030): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
E/Netd    (  314): netlink response contains error (File exists)
D/ConnectivityService( 1030): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService( 1030): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1030): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService( 1030): Setting Dns servers for network 101 to [/192.168.1.1]
D/Nat464Xlat( 1030): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1030): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1030): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1030): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1030):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1030):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1030):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1030):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): Connected
D/ConnectivityService( 1030):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1030): currentScore = 0, newScore = 20
D/ConnectivityService( 1030):    accepting network in place of null
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1030): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): Checking http://clients3.google.com/generate_204 on "NG700"
D/TelephonyNetworkFactory-1( 1867): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1867):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/WIFI    ( 1030): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1030):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 1030): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1030): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1030): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1030): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1030): [e] list.add(nai) empty : false size: 1
D/ConnectivityService( 1030): Switching, to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService( 1030): validation of new default Network = false
D/ConnectivityService( 1030): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1030): enableDataServiceNotify 
D/DSQN    ( 1030): start dsqn bin
D/LocSvc_java( 1030): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1030): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1030): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1030): ignore wifi update if we are not in OPENING or CLOSING
D/libc-netbsd(  314): res_queryN name = clients3.google.com, class = 1, type = 28
,V/WiFiOffLoadBroadcast( 7302): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7302): MCCMNC not supported: null
D/ConnectivityService( 1030): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1030):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1030):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1030): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1456): CM callback handler got msg 524290
W/dsqn    ( 7450): type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,W/dsqn    ( 7450): type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
V/NetworkPolicy( 1030): [LG_RESTRICTED] checkMobilePolicy_type()
D/TelephonyIcons( 1456): null signal icon name: drawable/stat_sys_signal_null
,D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
E/DSQN    ( 7450): DSQN ssw
D/QRemote ( 6311): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6311): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6311): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 7344): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7302): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7302): MCCMNC not supported: null
D/QRemote ( 6311): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6311): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6311): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 7344): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7373): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 7373): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
D/libc-netbsd(  314): res_queryN name = clients3.google.com, class = 1, type = 1
V/WiFiOffLoadBroadcast( 7302): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7302): MCCMNC not supported: null
D/QRemote ( 6311): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6311): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6311): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6311): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6311): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 7344): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7373): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7373): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7302): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{1b2e6815 type 2 when 235431 com.google.android.gms} when 235431
,D/WiFiOffLoadBroadcast( 7302): MCCMNC not supported: null
D/QRemote ( 6311): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6311): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6311): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,I/QRemote ( 6311): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6311): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/libc-netbsd(  314): res_queryN name = clients3.google.com succeed
,D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  314): res_queryN name = mtalk.google.com, class = 1, type = 1
D/LGDataListener(  314): argv[0]=dsqncommand
D/LGDataListener(  314): argv[1]=wlan0
D/LGDataListener(  314): argv[2]=1
D/LGDataListener(  314): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1030): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1030): start to monitor internet connection
,D/DhcpStateMachine( 1030): DHCPV4 request on wlan0
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 02 Feb 2016 13:49:25 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454420965386], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454420965358]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1030): Validated
D/ConnectivityService( 1030): Validated NetworkAgentInfo [WIFI () - 101]
V/LgDhcpStateMachineHelper( 1030): [bssid] hash key :c0:ff:d4:d3:aa:48
D/ConnectivityService( 1030): rematching NetworkAgentInfo [WIFI () - 101]
D/LgDhcpStateMachineHelper( 1030): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
D/ConnectivityService( 1030):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1030):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1030):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1030): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService( 1030): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1030):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1030):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1030): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1030): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1456): CM callback handler got msg 524290
D/WIFI    ( 1030): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1030):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1030): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory-1( 1867): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1867):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
W/dhcpcd  ( 7458): type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,W/dhcpcd  ( 7458): type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,D/libc-netbsd(  314): res_queryN name = mtalk.google.com succeed
I/dhcpcd  ( 7458): version 5.5.6 starting
E/dhcpcd  ( 7458): get_duid: m
,D/dhcpcd  ( 7458): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 7458): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
D/TelephonyIcons( 1456): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/dhcpcd  ( 7458): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
,D/dhcpcd  ( 7458): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7458): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/dhcpcd  ( 7458): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 7458): wlan0: sending REQUEST (xid 0xb9c8246c), next in 3.95 seconds
,D/GCM     ( 2185): Connected
,D/GCM     ( 2185): Message class com.google.f.a.a.p
,D/ConnectivityService( 1030): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1030): MasterInitialState.processMessage what=3
D/ConnectivityService( 1030): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1030): MasterInitialState.processMessage what=3
D/PostponalbeReceiver( 7344): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,I/NetworkMonitor( 5185): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 5185): type=WIFI subType= reason=null isConnected=true
W/ContextImpl( 7344): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/NetworkStateForAutoUpdateMonitor( 7073): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7073): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7073): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 7073): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7073): onReceive
,D/AppUp4:CustFacade( 7073): Context : android.app.ReceiverRestrictedContext@2d482146
D/AppUp4:CustFacade( 7073): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 7073): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7073): begin check event
I/AppUp4:CustModeStarterReceiver( 7073): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7073): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7073): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7073): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7073): handleAsyncCustNotification do not startCustService
D/LGDMClient( 3963): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3963): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 3963): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,D/GpsLocationProvider( 1030): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 3963): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3302): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3302): DownloadService onCreate
D/LGDMClient( 3963): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,I/LGDMClient( 3963): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/DownloadManager( 3302): in removeSpuriousFiles
V/DownloadManager( 3302): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/LGDMClient( 3963): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3963): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 3302): created cursor android.database.sqlite.SQLiteCursor@11c29e8a on behalf of 3302
I/DownloadManager( 3302): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3302): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3302): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3302): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3302): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3302): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3302): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3302): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3302): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3302): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3302): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/DownloadManager( 3302): in trimDatabase
V/DownloadManager( 3302): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 3302): created cursor android.database.sqlite.SQLiteCursor@17622118 on behalf of 3302
I/ActivityManager( 1030): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7497 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,V/DownloadManager( 3302): DownloadService onStartCommand
V/DownloadManager( 3302): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3302): created cursor android.database.sqlite.SQLiteCursor@14341956 on behalf of 3302
V/DownloadManager( 3302): processing inserted download 1
,V/DownloadManager( 3302): processing inserted download 4
D/GpsLocationProvider( 1030): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1030): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1030): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
V/DownloadManager( 3302): processing inserted download 7
W/ContextImpl( 3963): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3302): processing inserted download 8
E/LGDMClient( 3963): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 3963): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 3963): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/art     (  348): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 440us total 20.295ms
V/DownloadManager( 3302): processing inserted download 9
V/DownloadManager( 3302): processing inserted download 10
V/DownloadManager( 3302): processing inserted download 16
V/DownloadManager( 3302): processing inserted download 17
V/DownloadManager( 3302): processing inserted download 18
V/DownloadManager( 3302): processing inserted download 21
V/DownloadManager( 3302): processing inserted download 22
V/DownloadManager( 3302): DownloadService onDestroy
,I/art     (  348): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 359us total 16.906ms
W/ResourcesManager( 7497): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7497): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
I/art     (  348): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 289us total 13.564ms
W/ResourcesManager( 7497): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,W/ResourcesManager( 7497): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,I/LGEmail ( 7497): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7497): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
W/ResourceType( 7497): No package identifier when getting value for resource number 0x00000000
,D/LgDataFeature( 7497): LgDataFeature() Constructor: none
D/LgDataFeature( 7497): LgDataFeature() Constructor Done, null
,E/WifiStateMachine( 1030):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1030):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1030):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1030):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1030):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,D/ConnectivityService( 1030): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService( 1030): identical MTU - not setting
D/Nat464Xlat( 1030): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1030): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1030):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1030):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1030): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1456): CM callback handler got msg 524295
D/eas_req ( 7497): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/dhcpcd  ( 7458): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
,I/dhcpcd  ( 7458): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 7458): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 7458): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 7458): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 7458): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 7458): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7458): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7458): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,I/ActivityManager( 1030): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7527 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,I/HubEmail( 7497): JNI_OnLoad()
I/HubEmail( 7497): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7497): registerNatives()
I/HubEmail( 7497): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7497): registerNativeMethods()
I/HubEmail( 7497): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,W/art     ( 7497): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/ActivityManager( 1030): Killing 6815:com.google.android.talk/u0a72 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_10072/pid_6815/cgroup.procs: No such file or directory
W/Settings( 7497): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 7497): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/LgeMiscReceiver( 3252): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3252): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 3252): networkInfo.isConnected() = false
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  314): res_queryN name = static-avc.lglime.com, class = 1, type = 1
,I/ActivityManager( 1030): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7576 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/DhcpStateMachine( 1030): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper( 1030): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1030): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1030): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1030): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine( 1030): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1030): bShouldSendDhcpAction Result: false
D/DhcpStateMachine( 1030): DHCP Start/Renew wake lock is released.
,D/DhcpStateMachine( 1030): RunningState
,I/ActivityManager( 1030): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7594 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
I/ActivityManager( 1030): Killing 6984:com.google.android.gms:car/u0a5 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_10005/pid_6984/cgroup.procs: No such file or directory
,I/ActivityManager( 1030): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7611 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1030): Killing 7109:com.android.contacts/u0a19 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_10019/pid_7109/cgroup.procs: No such file or directory
,D/libc-netbsd(  314): res_queryN name = static-avc.lglime.com succeed
,I/art     ( 7611): Almond Protected OAT
,D/WeatherApplication( 7611): removeAccount
D/WeatherApplication( 7611): Account.length = 0
E/WeatherApplication( 7611): OPERATOR:OPEN
,D/WeatherAncestor( 7611): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:49:27
D/Weather.Utils( 7611): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7611): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7611): 2 : This is isUpdating : false
D/WeatherAncestor( 7611): connectivity changed - connection : true
,D/WeatherService( 7611): 2 : isServiceAlived():false forecastCache:null
D/ForecastDataCache( 7611): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7611): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7611): 2 : Cache is not up-to-date, count: 0
,D/Weather_cast( 7611): 2 : isUpdateNeedForAlarm : no city return false
,D/WeatherAncestor( 7611): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:49:27
,V/FormManager( 7527): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7527): Alarm would be updated, because LastCheckTime has been updated.
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 237737951945; DSPS: 7931104; Offset : -4312279824
,I/ActivityManager( 1030): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7631 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1030): Killing 7132:com.android.gallery3d/u0a27 (adj 15): empty #17
W/libprocessgroup( 1030): failed to open /acct/uid_10027/pid_7132/cgroup.procs: No such file or directory
,I/ActivityManager( 1030): Killing 7152:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_10080/pid_7152/cgroup.procs: No such file or directory
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7631): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7631): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7631): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7631): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,I/WebViewFactory( 7631): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7631): Loading: webviewchromium
,I/LibraryLoader( 7631): Time to load native libraries: 6 ms (timestamps 8244-8250)
I/LibraryLoader( 7631): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7631): Binding Chromium to main looper Looper (main, tid 1) {19af6dfc}
,I/LibraryLoader( 7631): Expected native library version number "",actual native library version number ""
,I/chromium( 7631): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=50.0, 0.0, 0.0  rx=43.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1572945177] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=50.0, 0.0, 0.0  rx=43.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1572945176] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,I/BrowserStartupController( 7631): Initializing chromium process, renderers=0
W/art     ( 7631): Attempt to remove local handle scope entry from IRT, ignoring
,D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
W/chromium( 7631): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7631): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
,I/chromium( 7631): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,V/AudioPolicyService(  319): registerClient() client 0xb558a480, uid 10093
,W/AudioManagerAndroid( 7631): Requires BLUETOOTH permission
I/Adreno-EGL( 7631): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7631): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7631): Build Date: 12/12/14 금
I/Adreno-EGL( 7631): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7631): Remote Branch: 
I/Adreno-EGL( 7631): Local Patches: 
I/Adreno-EGL( 7631): Reconstruct Branch: 
,V/WifiInternetCheck( 1030): Single check msg out of sync, ignoring.
D/ConnectivityService( 1030): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1030): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1030): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 5185): type=WIFI subType= reason=null isConnected=true
D/GpsLocationProvider( 1030): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NSApplication( 7631): Starting up...
,I/ActivityManager( 1030): Killing 7022:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
,W/libprocessgroup( 1030): failed to open /acct/uid_10005/pid_7022/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 2392): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 2392): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PostponalbeReceiver( 7344): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 7344): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 7073): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 7073): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7073): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7073): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7073): onReceive
,D/AppUp4:CustFacade( 7073): Context : android.app.ReceiverRestrictedContext@2d482146
,D/AppUp4:CustFacade( 7073): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7073): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7073): begin check event
I/AppUp4:CustModeStarterReceiver( 7073): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 3963): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3963): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 3963): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 3963): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
I/GLSUser ( 2185): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2185): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2185): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2185): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/DownloadManager( 3302): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3302): DownloadService onCreate
I/DownloadManager( 3302): in removeSpuriousFiles
D/LGDMClient( 3963): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/DownloadManager( 3302): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3302): created cursor android.database.sqlite.SQLiteCursor@28e436c4 on behalf of 3302
,I/DownloadManager( 3302): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
,I/DownloadManager( 3302): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3302): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
V/GLSActivity( 2185): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/DownloadManager( 3302): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/LGDMClient( 3963): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/DownloadManager( 3302): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3302): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3302): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3302): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3302): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3302): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3302): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/DownloadManager( 3302): in trimDatabase
V/DownloadManager( 3302): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
D/LGDMClient( 3963): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3963): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 3302): created cursor android.database.sqlite.SQLiteCursor@117339ad on behalf of 3302
V/DownloadManager( 3302): DownloadService onStartCommand
V/DownloadManager( 3302): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3302): created cursor android.database.sqlite.SQLiteCursor@54ffb30 on behalf of 3302
V/DownloadManager( 3302): processing inserted download 1
V/DownloadManager( 3302): processing inserted download 4
V/DownloadManager( 3302): processing inserted download 7
W/ContextImpl( 3963): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
,V/DownloadManager( 3302): processing inserted download 8
V/DownloadManager( 3302): processing inserted download 9
V/DownloadManager( 3302): processing inserted download 10
V/DownloadManager( 3302): processing inserted download 16
V/DownloadManager( 3302): processing inserted download 17
V/DownloadManager( 3302): processing inserted download 18
V/DownloadManager( 3302): processing inserted download 21
V/DownloadManager( 3302): processing inserted download 22
I/art     ( 1030): Explicit concurrent mark sweep GC freed 94488(4MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 44MB/66MB, paused 1.701ms total 110.134ms
,E/LGDMClient( 3963): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
,D/LGDMClient( 3963): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 3963): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3302): DownloadService onDestroy
,W/Settings( 7497): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 7497): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/LgeMiscReceiver( 3252): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3252): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3252): networkInfo.isConnected() = false
D/WeatherAncestor( 7611): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:49:28
,D/Weather.Utils( 7611): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7611): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7611): 2 : This is isUpdating : false
D/WeatherAncestor( 7611): connectivity changed - connection : true
D/WeatherService( 7611): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@103c34a3
D/ForecastDataCache( 7611): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7611): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7611): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7611): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7611): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:49:28
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
,I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/Kids    ( 2392): [AccountUtils] Account not ready
W/Kids    ( 2392): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2392): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2392): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2392): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2392): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2392): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2392): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2392): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2392): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2392): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2392): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2392): 	at java.lang.Thread.run(Thread.java:818)
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
,E/LgeQuickCoverOverlayWindow( 1411): updateNotificationData: count=3
D/ChimeraCfgMgr( 2392): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{198ef165 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/PostponalbeReceiver( 7344): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 7344): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,V/FormManager( 7527): There are no updated forms. The schedule will be deleted.
I/NetworkStateForAutoUpdateMonitor( 7073): [onReceive] BroadcastReceiver onReceive
V/FormManager( 7527): Alarm would be updated, because LastCheckTime has been updated.
I/NetworkStateForAutoUpdateMonitor( 7073): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7073): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7073): [onReceive] request level :IDLE....
I/GLSUser ( 2185): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2185): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2185): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2185): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/AppUp4:CustModeStarterReceiver( 7073): onReceive
,V/GLSActivity( 2185): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AppUp4:CustFacade( 7073): Context : android.app.ReceiverRestrictedContext@2d482146
D/AppUp4:CustFacade( 7073): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7073): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7073): begin check event
I/AppUp4:CustModeStarterReceiver( 7073): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 3963): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3963): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 3963): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 3963): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,V/DownloadManager( 3302): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3963): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/DownloadManager( 3302): DownloadService onCreate
I/LGDMClient( 3963): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/DownloadManager( 3302): in removeSpuriousFiles
V/DownloadManager( 3302): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,W/ContextImpl( 3963): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3302): created cursor android.database.sqlite.SQLiteCursor@3324fd2e on behalf of 3302
E/LGDMClient( 3963): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 3963): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 3963): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
I/DownloadManager( 3302): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3302): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3302): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3302): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3302): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3302): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3302): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3302): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3302): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3302): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3302): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LGDMClient( 3963): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3963): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
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
W/Kids    ( 2392): [AccountUtils] Account not ready
W/Kids    ( 2392): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2392): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2392): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2392): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2392): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2392): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2392): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2392): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2392): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2392): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2392): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2392): 	at java.lang.Thread.run(Thread.java:818)
I/DownloadManager( 3302): in trimDatabase
V/DownloadManager( 3302): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3302): created cursor android.database.sqlite.SQLiteCursor@b7800cf on behalf of 3302
I/LgeMiscReceiver( 3252): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3252): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3252): networkInfo.isConnected() = true
D/PhoneState( 3252): setPdpRejectCasuse : false
W/Settings( 7497): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
V/DownloadManager( 3302): DownloadService onStartCommand
V/DownloadManager( 3302): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3302): created cursor android.database.sqlite.SQLiteCursor@887be3a on behalf of 3302
W/Settings( 7497): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/LgeQuickCoverOverlayWindow( 1411): updateNotificationData: count=3
,V/DownloadManager( 3302): processing inserted download 1
V/DownloadManager( 3302): processing inserted download 4
D/WeatherAncestor( 7611): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:49:28
V/DownloadManager( 3302): processing inserted download 7
V/DownloadManager( 3302): processing inserted download 8
D/Weather.Utils( 7611): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7611): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7611): 2 : This is isUpdating : false
D/WeatherAncestor( 7611): connectivity changed - connection : true
D/WeatherService( 7611): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@103c34a3
V/DownloadManager( 3302): processing inserted download 9
D/ForecastDataCache( 7611): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7611): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7611): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7611): 2 : isUpdateNeedForAlarm : no city return false
V/DownloadManager( 3302): processing inserted download 10
D/WeatherAncestor( 7611): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:49:28
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{198ef165 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
V/DownloadManager( 3302): processing inserted download 16
V/DownloadManager( 3302): processing inserted download 17
V/DownloadManager( 3302): processing inserted download 18
,V/DownloadManager( 3302): processing inserted download 21
V/DownloadManager( 3302): processing inserted download 22
V/DownloadManager( 3302): DownloadService onDestroy
D/ChimeraCfgMgr( 2392): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/GLSUser ( 2185): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 2185): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2185): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2185): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2185): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/FormManager( 7527): There are no updated forms. The schedule will be deleted.
V/FormManager( 7527): Alarm would be updated, because LastCheckTime has been updated.
,V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/Kids    ( 2392): [AccountUtils] Account not ready
W/Kids    ( 2392): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2392): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2392): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2392): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2392): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2392): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2392): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2392): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2392): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2392): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2392): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2392): 	at java.lang.Thread.run(Thread.java:818)
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
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{198ef165 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  314): res_queryN name = www.google.com, class = 1, type = 1
D/libc-netbsd(  314): res_queryN name = www.google.com succeed
,D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  314): res_queryN name = clients3.google.com, class = 1, type = 1
,D/libc-netbsd(  314): res_queryN name = clients3.google.com succeed
V/WifiInternetCheck( 1030): isHttpConnectionAvailable - We got a valid response : 204
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=37.0, 0.0, 0.0  rx=31.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1572942158] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=37.0, 0.0, 0.0  rx=31.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1572942155] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/GAV4    ( 7631): Thread[GAThread,5,main]: No campaign data found.
,V/AlarmManager( 1030): RTC_WAKEUP set : Alarm{226dfc33 type 0 when 1454420974091 com.android.vending} when 1454420974091
,V/SIM_STK ( 1030): Menu title from STK is T-Mobile
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-53 f=2412 sc=60 link=72 tx=24.5, 0.0, 0.0  rx=19.5 bcn=0 [on:0 tx:0 rx:0 period:2999] from screen [on:0 period:-1572939118] gl rssi=-53 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-53 f=2412 sc=60 link=72 tx=24.5, 0.0, 0.0  rx=19.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1572939117] gl rssi=-53 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
,V/GLSActivity( 2185): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2185): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2185): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2185): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2185): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2185): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6926): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6926): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6926): [1] 5.onFinished: Giving up after 6 failures.
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=13.2, 0.0, 0.0  rx=10.2 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1572936098] gl rssi=-62 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=13.2, 0.0, 0.0  rx=10.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1572936095] gl rssi=-62 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,V/AlarmManager( 1030): ELAPSED_WAKEUP set : Alarm{388aaddd type 2 when 248921 android} when 248921
,I/BooksSync( 6481): Starting books sync
,D/BooksSync( 6481): started syncMyEbooks
,V/GLSActivity( 2185): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2185): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2185): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2185): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2185): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2185): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,W/GLSActivity( 2185): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2185): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2185): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2185): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2185): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2185): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2185): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6481): Authentication error
E/BooksAccountManager( 6481): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6481): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6481): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6481): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6481): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6481): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6481): null auth token
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  314): res_queryN name = www.googleapis.com, class = 1, type = 1
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{198ef165 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  314): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 6481): Error response from books API: {
W/ApiaryClient( 6481):  "error": {
W/ApiaryClient( 6481):   "errors": [
W/ApiaryClient( 6481):    {
W/ApiaryClient( 6481):     "domain": "global",
W/ApiaryClient( 6481):     "reason": "required",
W/ApiaryClient( 6481):     "message": "Login Required",
W/ApiaryClient( 6481):     "locationType": "header",
W/ApiaryClient( 6481):     "location": "Authorization"
W/ApiaryClient( 6481):    }
W/ApiaryClient( 6481):   ],
W/ApiaryClient( 6481):   "code": 401,
W/ApiaryClient( 6481):   "message": "Login Required"
W/ApiaryClient( 6481):  }
W/ApiaryClient( 6481): }
,W/ApiaryClient( 6481): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6481): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=6732042259634551590&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6481): Headers:
W/ApiaryClient( 6481): accept-encoding: [gzip]
W/ApiaryClient( 6481): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6481): gdata-version: 2
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=7.1, 0.0, 0.0  rx=5.1 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1572933067] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=7.1, 0.0, 0.0  rx=5.1 bcn=0 [on:0 tx:0 rx:0 period:19] from screen [on:0 period:-1572933048] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,V/GLSActivity( 2185): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 2185): Explicit concurrent mark sweep GC freed 44668(2MB) AllocSpace objects, 20(2MB) LOS objects, 51% free, 30MB/62MB, paused 2.120ms total 76.829ms
,I/GLSUser ( 2185): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2185): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2185): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2185): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2185): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,W/GLSActivity( 2185): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2185): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2185): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2185): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2185): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2185): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2185): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1411): onNotificationPosted
E/BooksAccountManager( 6481): Authentication error
E/BooksAccountManager( 6481): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6481): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6481): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6481): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6481): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6481): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6481): null auth token
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
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{198ef165 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6481): Error response from books API: {
W/ApiaryClient( 6481):  "error": {
W/ApiaryClient( 6481):   "errors": [
W/ApiaryClient( 6481):    {
W/ApiaryClient( 6481):     "domain": "global",
W/ApiaryClient( 6481):     "reason": "required",
W/ApiaryClient( 6481):     "message": "Login Required",
W/ApiaryClient( 6481):     "locationType": "header",
W/ApiaryClient( 6481):     "location": "Authorization"
W/ApiaryClient( 6481):    }
W/ApiaryClient( 6481):   ],
W/ApiaryClient( 6481):   "code": 401,
W/ApiaryClient( 6481):   "message": "Login Required"
W/ApiaryClient( 6481):  }
W/ApiaryClient( 6481): }
,W/ApiaryClient( 6481): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6481): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=6732042259634551590&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6481): Headers:
W/ApiaryClient( 6481): accept-encoding: [gzip]
W/ApiaryClient( 6481): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6481): gdata-version: 2
V/GLSActivity( 2185): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2185): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2185): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2185): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2185): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2185): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1030): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1030): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1030): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1030): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1030): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2185): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2185): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2185): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2185): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2185): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2185): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2185): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6481): Authentication error
E/BooksAccountManager( 6481): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6481): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6481): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6481): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6481): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6481): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6481): null auth token
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
,D/QuickStatusbarLayout( 1411): Notification difference=198
,D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{198ef165 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6481): Error response from books API: {
W/ApiaryClient( 6481):  "error": {
W/ApiaryClient( 6481):   "errors": [
W/ApiaryClient( 6481):    {
W/ApiaryClient( 6481):     "domain": "global",
W/ApiaryClient( 6481):     "reason": "required",
W/ApiaryClient( 6481):     "message": "Login Required",
W/ApiaryClient( 6481):     "locationType": "header",
W/ApiaryClient( 6481):     "location": "Authorization"
W/ApiaryClient( 6481):    }
W/ApiaryClient( 6481):   ],
W/ApiaryClient( 6481):   "code": 401,
W/ApiaryClient( 6481):   "message": "Login Required"
W/ApiaryClient( 6481):  }
W/ApiaryClient( 6481): }
,W/ApiaryClient( 6481): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6481): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=6732042259634551590&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6481): Headers:
W/ApiaryClient( 6481): accept-encoding: [gzip]
W/ApiaryClient( 6481): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6481): gdata-version: 2
,E/BooksSync( 6481): Soft error: 
E/BooksSync( 6481): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6481): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=6732042259634551590&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6481): Headers:
E/BooksSync( 6481): accept-encoding: [gzip]
E/BooksSync( 6481): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6481): gdata-version: 2
E/BooksSync( 6481): 
E/BooksSync( 6481): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6481): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6481): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6481): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6481): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6481): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6481): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6481): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6481): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6481): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6481): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6481): {
E/BooksSync( 6481):  "error": {
E/BooksSync( 6481):   "errors": [
E/BooksSync( 6481):    {
E/BooksSync( 6481):     "domain": "global",
E/BooksSync( 6481):     "reason": "required",
E/BooksSync( 6481):     "message": "Login Required",
E/BooksSync( 6481):     "locationType": "header",
E/BooksSync( 6481):     "location": "Authorization"
E/BooksSync( 6481):    }
E/BooksSync( 6481):   ],
E/BooksSync( 6481):   "code": 401,
E/BooksSync( 6481):   "message": "Login Required"
E/BooksSync( 6481):  }
E/BooksSync( 6481): }
E/BooksSync( 6481): 
E/BooksSync( 6481): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6481): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6481): 	... 8 more
,E/BooksSync( 6481): Sync error
E/BooksSync( 6481): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6481): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=6732042259634551590&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6481): Headers:
E/BooksSync( 6481): accept-encoding: [gzip]
E/BooksSync( 6481): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6481): gdata-version: 2
E/BooksSync( 6481): 
E/BooksSync( 6481): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6481): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6481): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6481): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6481): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6481): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6481): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6481): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6481): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6481): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6481): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6481): {
E/BooksSync( 6481):  "error": {
E/BooksSync( 6481):   "errors": [
E/BooksSync( 6481):    {
E/BooksSync( 6481):     "domain": "global",
E/BooksSync( 6481):     "reason": "required",
E/BooksSync( 6481):     "message": "Login Required",
E/BooksSync( 6481):     "locationType": "header",
E/BooksSync( 6481):     "location": "Authorization"
E/BooksSync( 6481):    }
E/BooksSync( 6481):   ],
E/BooksSync( 6481):   "code": 401,
E/BooksSync( 6481):   "message": "Login Required"
E/BooksSync( 6481):  }
E/BooksSync( 6481): }
E/BooksSync( 6481): 
E/BooksSync( 6481): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6481): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6481): 	... 8 more
I/BooksSync( 6481): Finished books sync
D/SyncManager( 1030): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 248921, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=8.1, 0.0, 0.0  rx=7.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1572930026] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=8.1, 0.0, 0.0  rx=7.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1572930023] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=6.0, 0.0, 0.0  rx=6.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1572926999] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=6.0, 0.0, 0.0  rx=6.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1572926996] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1030): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1030): tsOffsetIs: Apps: 257739899124; DSPS: 8586527; Offset : -4312256242
,I/jxcore-log( 5988): --= Surplus to requirements =--
I/jxcore-log( 5988): 
I/jxcore-log( 5988): ****TEST TOOK:  ms ****
I/jxcore-log( 5988): 
I/jxcore-log( 5988): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5988): 
,D/AndroidRuntime( 7802): 
D/AndroidRuntime( 7802): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7802): CheckJNI is OFF
D/AndroidRuntime( 7802): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1030): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
I/ActivityManager( 1030): Killing 5988:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
,I/WindowState( 1030): WIN DEATH: Window{3e9db783 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService( 1030): Client connection lost with reason: 4
D/InputDispatcher( 1030): Window went away: Window{3e9db783 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/PackageSettings( 1030): Skipping PackageSetting{ba05c8a com.example.hello/10319} due to missing metadata
,E/WifiStateMachine( 1030):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=3.5, 0.0, 0.0  rx=3.8 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1572923972] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1030):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=3.5, 0.0, 0.0  rx=3.8 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:-1572923972] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1030): doString: [SIGNAL_POLL]
,I/ActivityManager( 1030):   Force finishing activity ActivityRecord{2f2154cc u0 com.test.thalitest/.MainActivity t4}
,E/GBMv2   (  344): DFP En is all cleared set to be enabled
W/ActivityManager( 1030): Spurious death for ProcessRecord{115aef80 5988:com.test.thalitest/u0a311}, curProc for 5988: null
,I/ActivityManager( 1030): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
,I/ActivityManager( 1030):   Force finishing activity ActivityRecord{2f2154cc u0 com.test.thalitest/.MainActivity t4 f}
W/ActivityManager( 1030): Duplicate finish request for ActivityRecord{2f2154cc u0 com.test.thalitest/.MainActivity t4 f}
,I/[LGHome]EVENT( 2082): [Launcher.java:5338:onStart()]onStart
D/SplitWindowPolicy( 1963): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1963): topRunningActivity=ActivityInfo{3796d3a2 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[LGHome]EVENT( 2082): [Launcher.java:903:onResume()]onResume
D/SplitWindowPolicy( 1963): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1963): topRunningActivity=ActivityInfo{30ffa833 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[LGHome]EVENT( 2082): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 2082): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/KeyguardModel( 1456): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,D/LIA_Service_RemotePackageHandler( 2038): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
D/LIA_MrGDBLogger_PackageInfoDetector( 2698): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
E/LGBluetoothAvrcpQcomAdapter( 6092): [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
D/LGBluetoothAvrcpQcomAdapter( 6092): [BTUI] [+] updateMediaPlayerInfo
I/InputReader( 1030): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1832): Ignoring removeGeofence because network location is disabled.
,W/System.err( 4167): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 4167): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4167): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4167): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4167): 	at android.os.Handler.handleCallback(Handler.java:739)
D/PostponalbeReceiver( 7344): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
W/System.err( 4167): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4167): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4167): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4167): 	at java.lang.reflect.Method.invoke(Native Method)
,W/System.err( 4167): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4167): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4167): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
I/art     ( 4212): Explicit concurrent mark sweep GC freed 23810(1336KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 547us total 78.997ms
,I/[LGHome]GBoardWebView( 2082): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
,D/ActionManagerService( 1918): notifyUserLog: 1000003
D/LIA_Informant_ActionManagerMessageHandler( 2698): handleMessage: what(1000) actionID(0x1000003)
I/ActivityManager( 1030): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=7834 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,D/SplitUIManager( 1884): split_name #11 / not available #0
D/SplitUIService( 1884): removed split : 
I/[LGHome]LGActivityUtil( 2082): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 2082): [Launcher.java:1056:onResume()]onResume end
I/[SystemUI]QSlideListController( 1456): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]EVENT( 2082): [Launcher.java:1114:onPause()]onPause
D/ActionManagerService( 1918): notifyUserLog: 1000004
D/LIA_Informant_ActionManagerMessageHandler( 2698): handleMessage: what(1000) actionID(0x1000004)
I/[LGHome]GBoardWebView( 2082): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
V/BoardContentProvider( 2698): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,I/GBoardWebViewUtils( 2082): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2082): , create_time: 1430558575574
I/GBoardWebViewUtils( 2082): , expire_time: 0
I/GBoardWebViewUtils( 2082): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2082): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2082): , display: false
I/GBoardWebViewUtils( 2082): , animation: false }
I/GBoardWebViewUtils( 2082): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2082): , create_time: 1430558575600
I/GBoardWebViewUtils( 2082): , expire_time: 0
I/GBoardWebViewUtils( 2082): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2082): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2082): , display: false
I/GBoardWebViewUtils( 2082): , animation: false }
I/GBoardWebViewUtils( 2082): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1453982949437
I/GBoardWebViewUtils( 2082): , create_time: 1453982950152
I/GBoardWebViewUtils( 2082): , expire_time: 0
I/GBoardWebViewUtils( 2082): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide.html?id=guide_1111111111116_1453982949437&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2082): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2082): , display: false
I/GBoardWebViewUtils( 2082): , animation: false }
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1456): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1456): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
D/WallpaperManager( 2082): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
I/SystemUI[Framework]( 1030): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1030): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1030): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1030): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1030): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@27959770,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1030): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
,I/[LGHome]EVENT( 2082): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]GBoardWebView( 2082): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
V/SIM_STK ( 1030): Menu title from STK is T-Mobile
D/SplitUIManager( 1884): split_name #11 / not available #0
I/SplitUIService( 1884): split app #11
,I/LockScreenSettings( 7834): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
,D/KeyguardModel( 1456): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1456): createShortcutInfo...
D/AppUp4:PreloadHelper( 7073): added Exclude : com.test.thalitest
,D/KeyguardModel( 1456): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1456): createShortcutInfo...
V/SIM_STK ( 1030): Menu title from STK is T-Mobile
V/SIM_STK ( 1030): Menu title from STK is T-Mobile
,I/art     ( 1030): Explicit concurrent mark sweep GC freed 42329(2MB) AllocSpace objects, 9(912KB) LOS objects, 33% free, 44MB/66MB, paused 1.916ms total 265.337ms
,I/ActivityManager( 1030): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7854 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/art     ( 1030): WaitForGcToComplete blocked for 262.639ms for cause Explicit
W/ResourcesManager( 1456): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
,W/ResourcesManager( 1456): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1456): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1456): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,W/ResourceType( 1456): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1456): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1456): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1456): createShortcutInfo...
W/ResourcesManager( 1456): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1456): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1456): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1456): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1456): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1456): createShortcutInfo...
,W/ActivityManager( 1030): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
D/LGBluetoothAvrcpQcomAdapter( 6092): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 6092): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6092): [BTUI] === MediaPlayerInfo (playerId:0) ===
W/ResourcesManager( 1456): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/LGBluetoothAvrcpQcomAdapter( 6092): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 6092): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 6092): [BTUI]          playState: 2 (PAUSED)
W/ResourcesManager( 1456): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/LGBluetoothAvrcpQcomAdapter( 6092): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 6092): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6092): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 6092): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6092): [BTUI] [-] updateMediaPlayerInfo
I/[LGHome]EVENT( 2082): [Launcher.java:5349:onStop()]onStop
W/ResourcesManager( 1456): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1456): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1456): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1456): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1456): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1456): createShortcutInfo...
I/ActivityManager( 1030): Killing 7373:com.lge.sync/1000 (adj 15): empty #17
,W/ResourcesManager( 7854): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7854): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7854): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7854): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7854): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/administrator( 1030): Handling package changes for user 0
V/SIM_STK ( 1030): Menu title from STK is T-Mobile
,D/KeyguardModel( 1456): handleShortcutListChanged...
,W/libprocessgroup( 1030): failed to open /acct/uid_1000/pid_7373/cgroup.procs: No such file or directory
D/KeyguardModel( 1456): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1456): createShortcutInfo...
D/KeyguardModel( 1456): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1456): createShortcutInfo...
W/ResourceType( 1456): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1456): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1456): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1456): createShortcutInfo...
W/ResourceType( 1456): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1456): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,D/KeyguardModel( 1456): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1456): createShortcutInfo...
W/ResourceType( 1456): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1456): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1456): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1456): createShortcutInfo...
I/[LGHome]Launcher.Model( 2082): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,D/KeyguardModel( 1456): handleShortcutListChanged...
I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,I/Timeline( 1030): Timeline: Activity_windows_visible id: ActivityRecord{55ad69f u0 com.lge.launcher2/.Launcher t3} time:260064
,I/[LGHome]Launcher.Model( 2082): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/SystemConfig( 7854): BUILD Country: EU
I/SystemConfig( 7854): BUILD Operator: OPEN
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2082): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2082): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/NotificationService( 1030): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1030): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1030): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister( 1030): removeObsoleteFile: deleting file=4_task.xml
D/PhoneStatusBar( 1456): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
I/[SystemUI]NavigationThemeResource( 1456): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1456):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1456): , Keyguard show=false, IME shown=false, Panel expanded=false
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 2082): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/[Concierge]WidgetView( 2082): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
D/[Concierge]Service( 2608): onStartCommand(). Type : 8
D/[Concierge]Service( 2608): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/[Concierge]WidgetView( 2082): change position of spinner
D/[Concierge]Service( 2608): Update widget ID : 11
D/[Concierge]Service( 2608): onStartCommand(). Type : 0
I/[Concierge]WidgetView( 2082): initWebView(). Time : 1454420989998
,I/SystemConfig( 7854): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7854): existFile = false
I/SystemConfig( 7854): canReadFile = false
I/SystemConfig( 7854): systemFeature RCS result false
D/SystemConfig( 7854): refreshRcsSupport() :false
I/ActivityManager( 1030): Killing 6867:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
I/QRemote ( 6311): [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
W/System.err( 6311): android.os.DeadObjectException
W/System.err( 6311): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6311): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6311): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 6311): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
W/System.err( 6311): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 6311): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 6311): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6311): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6311): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6311): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 6311): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6311): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6311): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 6311): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 6311): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 6311): android.os.DeadObjectException
W/System.err( 6311): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6311): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6311): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 6311): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
W/System.err( 6311): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 6311): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 6311): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6311): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6311): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6311): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 6311): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6311): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6311): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 6311): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 6311): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/QRemote ( 6311): [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,W/ResourcesManager( 1030): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourceType( 1030): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/art     ( 1030): Explicit concurrent mark sweep GC freed 8292(482KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 1.337ms total 281.199ms
,D/AndroidRuntime( 7802): Shutting down VM
,W/libprocessgroup( 1030): failed to open /acct/uid_1000/pid_6867/cgroup.procs: No such file or directory
,W/ActivityManager( 1030): Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
D/QRemote ( 6311): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
I/QRemote ( 6311): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,D/VoicemailCleanupService( 2286): Cleaning up data for package: com.test.thalitest
,I/ActivityManager( 1030): Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7878 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,D/QRemote ( 6311): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
I/PackageChangeReceiver( 7497): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
I/ActivityManager( 1030): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7895 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/[Concierge]WebView( 2082): Return exist ConciergeWebView. Reuse : 82206215
D/[Concierge]WidgetView( 2082): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2082): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
I/[LgeWidgetLib]ExtViewHost( 2082): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@3f3e61af
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
,I/[LGHome]Launcher.Model( 2082): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
,--------- beginning of crash
F/libc    ( 7802): Fatal signal 11 (SIGSEGV), code 1, fault addr 0xb45a0840 in tid 7814 (Binder_1)
D/[Concierge]WidgetView( 2082): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2082): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
E/        (  315): invalid crash request of size 0 (from pid=7802 uid=2000)
W/[Concierge]WidgetView( 2082): Widget kill message received. Destory myself. My : 1454420758497, New one : 1454420989998
,D/[Concierge]WidgetView( 2082): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2082): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/[LGHome]EVENT( 2082): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
D/UEI.SmartControl( 7878): Quickset Services start...
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/UEI.SmartControl( 7878): Manufacture = LGE
,D/UEI.SmartControl( 7878): Id = LGNevo
D/UEI.SmartControl( 7878): File observer start...
E/UEI.SmartControl( 7878): IR Port is disabled: false
D/UEI.SmartControl( 7878): Starting file observer...
D/UEI.SmartControl( 7878): Extracting JNI libs...
D/UEI.SmartControl( 7878): --- this system supports 32-bit or 64-bit only
I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
W/ResourcesManager( 7895): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7895): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7895): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 7895): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/[LgeWidgetLib]LgeAppWidgetHostView( 2082): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 2082): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
D/UEI.SmartControl( 7878): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 7878): --- Checking lib: libqs_armeabi-v7a.zip
,D/UEI.SmartControl( 7878): --- Extracting JNI libs: libqs_armeabi-v7a.zip
E/UEI.SmartControl( 7878): unzip: java.io.FileNotFoundException: /data/data/com.uei.lg.quicksetsdk.maxq616/files/libqs_jni.so: open failed: EROFS (Read-only file system)
I/UEI.SmartControl( 7878): --- Selecting new region: 6
E/SharedPreferencesImpl( 2082): Couldn't rename file /data/user/0/com.lge.launcher2/shared_prefs/broadcast.numberbadge.counter.xml to backup file /data/user/0/com.lge.launcher2/shared_prefs/broadcast.numberbadge.counter.xml.bak
I/UEI.SmartControl( 7878): Model = LG-D855
D/UEI.SmartControl( 7878): QS Service created
I/Timeline( 2082): Timeline: Activity_idle id: android.os.BinderProxy@23dafab6 time:260606
I/UEI.SmartControl( 7878): Service initServices...
D/UEI.SmartControl( 7878): QS start get config
I/AppConfig( 7895): Total System Memory = 2995761152
,D/SystemHelper( 7895): region [EU], country [EU], operator [OPEN], sub-operator []
E/SharedPreferencesImpl( 7895): Couldn't rename file /data/data/com.android.gallery3d/shared_prefs/com.android.gallery3d_preferences.xml to backup file /data/data/com.android.gallery3d/shared_prefs/com.android.gallery3d_preferences.xml.bak
I/ActivityManager( 1030): Killing 7302:com.android.settings/1000 (adj 15): empty #17

```
