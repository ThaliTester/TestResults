#### Test 579720943a29850_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
I/MusicWidget( 2653): mDelayedStopHandler : unbind
I/MusicBrowser( 2228): [MediaPlaybackService.java:2869:onUnbind()] oooooo 
I/MusicBrowser( 2228): [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2228): [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2228): [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2228): [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2228): [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2228): [MediaPlaybackService.java:2046:onDestroy()] oooooo 
I/MusicBrowser( 2228): [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
I/MediaFocusControl( 1029):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@34de33cacom.lge.music.MediaPlaybackService$5@e9fc93b
D/MusicBrowser( 2228): [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2228): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2228): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2228): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2228): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@7d42241
I/MusicBrowser( 2228): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2228): [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2228): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2228): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2228): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2228): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2228): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2228): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2228): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2228): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2228): [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2228): [MediaPlaybackService.java:6704:release()] oooooo 
I/MusicBrowser( 2228): [MediaPlaybackService.java:6665:stop()] oooooo 
V/MediaPlayer[Native]( 2228): reset
V/MediaPlayer[Native]( 2228): setListener
V/MediaPlayer[Native]( 2228): disconnect
V/MediaPlayer[Native]( 2228): destructor
V/AudioFlinger(  324): releasing 13 from 2228 for -1
V/AudioFlinger(  324):  decremented refcount to 0
V/AudioFlinger(  324): purging stale effects
V/MediaPlayer[Native]( 2228): disconnect
D/MusicBrowser( 2228): [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
I/SmartShareClient( 2228): [SmartShareManagerClient] smartshare client supported version code: 305000
I/SmartShareClient( 2228): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2228): [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
I/MusicBrowser( 2228): [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2228): [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2228): [SmartShareManagerClient] unregisterListener: 133879896
W/SmartShareClient( 2228): [SmartShareManagerClient] unregisterListener invalid listener: 133879896
I/SmartShareClient( 2228): [SmartShareManagerClient] terminate service: 2228/MediaPlaybackService/344299311
E/HomeCloudIF( 2228): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2228): [SmartShareManagerClient] unbindService context:android.app.Application@3fc91db1
V/CloudHub( 2228): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
V/CloudHub( 2228): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2228): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
D/MusicBrowser( 2228): [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
--------- beginning of system
I/ActivityManager( 1029): Killing 5811:com.google.android.partnersetup/u0a8 (adj 15): empty #17
I/CloudHub( 2228): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29989
W/libprocessgroup( 1029): failed to open /acct/uid_10008/pid_5811/cgroup.procs: No such file or directory
,D/AndroidRuntime( 6035): 
D/AndroidRuntime( 6035): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6035): CheckJNI is OFF
D/AndroidRuntime( 6035): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1029): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1961): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1029): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1029): setTaskToReturnTo : TaskRecord{2a9da03b #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1029): setTaskToReturnTo : TaskRecord{2a9da03b #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1029): AppWindowTokenEx init.. 
E/GBMv2   (  343): DFP En is all cleared set to be enabled
I/ActivityManager( 1029): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6055 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6035): Shutting down VM
V/ActivityManager( 1029): Display changed displayId=0
D/DSDPConnection( 1868): Display #0 changed.
D/SplitWindowPolicy( 1961): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1961): topRunningActivity=ActivityInfo{27197692 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1961): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1961): topRunningActivity=ActivityInfo{2ee42863 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 6055): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/WebViewFactory( 6055): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
I/LibraryLoader( 6055): Loading: webviewchromium
I/LibraryLoader( 6055): Time to load native libraries: 4 ms (timestamps 4703-4707)
I/LibraryLoader( 6055): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6055): Binding Chromium to main looper Looper (main, tid 1) {1485972f}
I/LibraryLoader( 6055): Expected native library version number "",actual native library version number ""
I/chromium( 6055): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6055): Initializing chromium process, renderers=0
W/art     ( 6055): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6055): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
V/AudioPolicyService(  324): registerClient() client 0xb57beae0, uid 10311
D/BluetoothManagerService( 1029): Message: 20
D/BluetoothManagerService( 1029): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1a9802ed:true
D/BluetoothAdapter( 6055): 239853884: getState() :  mService = null. Returning STATE_OFF
W/chromium( 6055): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6055): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 6055): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
I/Adreno-EGL( 6055): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6055): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6055): Build Date: 12/12/14 금
I/Adreno-EGL( 6055): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6055): Remote Branch: 
I/Adreno-EGL( 6055): Local Patches: 
I/Adreno-EGL( 6055): Reconstruct Branch: 
W/chromium( 6055): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 6055): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 6055): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6055): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6055): CordovaWebView is running on device made by: LGE
W/art     ( 6055): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6055): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 6055): Render dirty regions requested: true
I/OpenGLRenderer( 6055): Initialized EGL, version 1.4
D/OpenGLRenderer( 6055): Enabling debug mode 0
D/Atlas   ( 6055): Validating map...
D/SplitWindow( 1029): check instance of lgWin Window{12ab8aff u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/LgDataFeature( 6055): LgDataFeature() Constructor: none
D/LgDataFeature( 6055): LgDataFeature() Constructor Done, null
I/SystemUI[Framework]( 1029): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1029): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1029): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1029): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1029): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@5ab3a44,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1029): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/PhoneStatusBar( 1454): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1454): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1454):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1454): , Keyguard show=false, IME shown=false, Panel expanded=false
I/ActivityManager( 1029): Displayed com.test.thalitest/.MainActivity: +624ms (total +725ms)
I/Timeline( 1029): Timeline: Activity_windows_visible id: ActivityRecord{14916358 u0 com.test.thalitest/.MainActivity t4} time:105143
I/Timeline( 6055): Timeline: Activity_idle id: android.os.BinderProxy@21e8116c time:105149
I/chromium( 6055): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6055): 
D/JsMessageQueue( 6055): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 6055): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435094784
I/chromium( 6055): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 6055): 
I/chromium( 6055): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
E/GBMv2   (  343): DFP En is all cleared set to be enabled
E/GBMv2   (  343): Set value is all cleared set the max
,I/GBMv2   (  343): DFP Enabled. Ignore VFP set
W/jxcore-log( 6055): Initializing JXcore engine
,W/jxcore-log( 6055): JXcore engine is ready
,W/Thread-683( 6114): type=1400 audit(0.0:148): avc: denied { ioctl } for path="socket:[8446]" dev="sockfs" ino=8446 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-683( 6114): type=1400 audit(0.0:149): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,W/Thread-683( 6114): type=1400 audit(0.0:150): avc: denied { ioctl } for path="socket:[10899]" dev="sockfs" ino=10899 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-683( 6114): type=1400 audit(0.0:151): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/Thread-683( 6114): type=1400 audit(0.0:152): avc: denied { ioctl } for path="socket:[28462]" dev="sockfs" ino=28462 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
W/jxcore-log( 6055): Starting JXcore engine
,W/jxcore-log( 6055): Platform android
W/jxcore-log( 6055): 
W/jxcore-log( 6055): Process ARCH arm
W/jxcore-log( 6055): 
,I/jxcore-log( 6055): JXcore Cordova bridge is ready!
I/jxcore-log( 6055): 
,W/jxcore-log( 6055): JXcore engine is started
,I/jxcore-log( 6055): Toggling radios to true
I/jxcore-log( 6055): 
,D/BluetoothManagerService( 1029): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1029): enable():  mBluetooth =null mBinding = false
D/BluetoothManagerService( 1029): Message: 1
D/BluetoothManagerService( 1029): MESSAGE_ENABLE: mBluetooth = null
,D/LocationManagerService( 1029): getAllProviders()=[passive, gps, network]
D/WifiService( 1029): New client listening to asynchronous messages
D/Ulp_jni ( 1029): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1029): JNI:system_update. Event-4
I/ActivityManager( 1029): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=6118 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,D/WifiServiceImplEx( 1029): setWifiEnabled: true pid=6055, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1029): setWifiEnabled: true pid=6055, uid=10311
E/WifiService( 1029): Invoking mWifiStateMachine.setWifiEnabled
D/WifiServiceImplEx( 1029): disconnect pid=6055, uid=10311, packageName=com.test.thalitest
D/LocationManagerService( 1029): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1029): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1029): JNI:system_update. Event-4
E/WifiStateMachine( 1029):  InitialState CMD_DISCONNECT 0 0
,E/WifiStateMachine( 1029):  DefaultState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1029):  InitialState CMD_START_SUPPLICANT 0 0
I/LGFTMITEM( 1029): [GET_FTM][id=6], offset=12288
D/WifiServiceImplEx( 1029): reconnect pid=6055, uid=10311, packageName=com.test.thalitest
I/jxcore-log( 6055): Radios toggled
I/jxcore-log( 6055): 
I/jxcore-log( 6055): My device name is: LGE-LG-D855
I/jxcore-log( 6055): 
E/WifiUtil( 1029): wfc_util_ffile_check_copy(): pid[1029] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
E/WifiUtil( 1029): wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
E/WifiUtil( 1029): wfc_util_ffile_check_copy(): pid[1029] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
E/WifiUtil( 1029): wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
I/WifiUtil( 1029): Intf0MacAddress=C49A027B60AC
E/WifiHW  ( 1029): unknown target_country: EU , set to default
E/WifiHW  ( 1029): [wifi_ensure_config_files] default country1 = GB
E/WifiHW  ( 1029): [wifi_ensure_config_files] default country2 = GB
I/WifiUtil( 1029): gEnableBmps=1
,W/ResourcesManager( 6118): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager( 6118): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6118): Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 6118): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/BluetoothAdapterApp( 6118): Loading JNI Library
,D/BluetoothAdapterApp( 6118): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@39e9c0d3 Instance Count = 1
,D/SoftapController(  318): Softap fwReload - Ok
D/Tethering( 1029): sendTetherStateChangedBroadcast 1, 0, 0
,D/CommandListener(  318): Setting iface cfg
D/CommandListener(  318): Trying to bring down wlan0
D/CommandListener(  318): Clearing all IP addresses on wlan0
D/Tethering( 1029): InitialState.processMessage what=4
D/libc-netbsd(  318): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1029): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/ActivityManager( 1029): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=6150 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/Tethering( 1029): sendTetherStateChangedBroadcast 0, 0, 0
,D/BluetoothAdapterApp( 6118): onCreate
,W/ResourcesManager( 6150): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6150): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6150): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6150): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 6150): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6150): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/ProfileConfigQcom( 6118): [BTUI] HeadsetService is supported
D/ProfileConfigQcom( 6118): Adding HeadsetService
D/ProfileConfigQcom( 6118): [BTUI] A2dpService is supported
D/ProfileConfigQcom( 6118): Adding A2dpService
D/ProfileConfigQcom( 6118): [BTUI] HidService is supported
D/ProfileConfigQcom( 6118): Adding HidService
D/ProfileConfigQcom( 6118): [BTUI] HealthService is supported
D/ProfileConfigQcom( 6118): Adding HealthService
D/LGBluetoothFeatureConfig( 6118): isSupportPan() :  mTargetOp=OPEN
D/ProfileConfigQcom( 6118): [BTUI] PanService is supported
D/ProfileConfigQcom( 6118): Adding PanService
D/ProfileConfigQcom( 6118): [BTUI] GattService is supported
D/ProfileConfigQcom( 6118): Adding GattService
E/WifiHW  ( 1029): Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
D/ProfileConfigQcom( 6118): [BTUI] BluetoothMapService is supported
D/ProfileConfigQcom( 6118): Adding BluetoothMapService
D/ProfileConfigQcom( 6118): [BTUI] HeadsetClientService is NOT supported
W/wpa_supplicant( 6173): type=1400 audit(0.0:153): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/wpa_supplicant( 6173): type=1400 audit(0.0:154): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,I/wpa_supplicant( 6173): Successfully initialized wpa_supplicant
,D/BluetoothManagerService( 1029): Message: 20
D/BluetoothManagerService( 1029): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2707bece:true
D/BluetoothAdapterState( 6118): make
I/LGFMServiceAdapter( 6118): [FM] LGFMServiceAdapter : create
I/bluedroid-qcom( 6118): init
I/BluetoothAdapterState( 6118): Entering OffState
I/bte_conf( 6118): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 6118): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 6118): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 6118): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
D/BTIF_CORE( 6118): [BTUI] lge_load_bluetooth_address
I/wpa_supplicant( 6173): rfkill: Cannot open RFKILL control device
I/wpa_supplicant( 6173): [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
W/bdaddr_loader( 6178): type=1400 audit(0.0:155): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/bdaddr_loader( 6178): type=1400 audit(0.0:156): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/bluedroid-qcom( 6118): get_profile_interface socket
I/bluedroid-qcom( 6118): get_profile_interface map_client
D/BluetoothManagerService( 1029): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService( 1029): Message: 40
D/BluetoothManagerService( 1029): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
I/GKI_LINUX( 6118): gki_task_entry task_id=1 [BTIF] starting
D/lge_bdaddr_loader( 6178): [BTUI] bdaddr_loader ::: START
D/lge_bdaddr_loader( 6178): [BTUI] bluetooth_load_bdaddress
I/LGFTMITEM( 6178): [GET_FTM][id=8], offset=16384
I/bluedroid-qcom( 6118): config_hci_snoop_log
D/BluetoothAdapterProperties( 6118): Address is:58:3F:54:73:64:C0
D/lge_bdaddr_loader( 6178): [BTUI] bdaddr to set in property : 58:3F:54:73:64:C0
D/BluetoothManagerService( 1029): Bluetooth Adapter name changed to G3-1
D/BluetoothManagerService( 1029): Stored Bluetooth name: G3-1
D/BluetoothAdapterProperties( 6118): Name is: G3-1
D/BluetoothManagerService( 1029): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService( 1029): Broadcasting onBluetoothServiceUp() to 7 receivers.
,E/lge_bdaddr_loader( 6178): [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:64:C0
D/lge_bdaddr_loader( 6178): [BTUI] bdaddr_loader ::: END
V/LGMDMManagerInternal( 6118): Create singleton instance
E/WifiStateMachine( 1029): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1029): useWiFiOffloading() : false
E/WifiStateMachine( 1029): CONFIG_LGE_WLAN_PATH : true
D/WifiMonitor( 1029): startMonitoring(wlan0) with mConnected = false
D/WifiMonitor( 1029): connecting to supplicant
,I/WifiServerServiceExt( 1029): WIFI_STATE_CHANGED_ACTION [2]
V/WfdStateTracker( 1961): WfdStateTracker handleDirectStateChangedEvent: 1
D/StatusBar.NetworkController( 1454): refreshViews: Data not connected!! Set no data type icon / Roaming
D/BluetoothAdapterState( 6118): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 6118): Setting state to 11
I/BluetoothAdapterState( 6118): Bluetooth adapter state changed: 10-> 11
,D/BluetoothManagerService( 1029): Message: 60
D/BluetoothManagerService( 1029): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService( 1029): Bluetooth State Change Intent: 10 -> 11
I/LGBluetoothServiceJni( 6118): classInitNative: succeeds
D/LGBluetoothAPIService( 1961): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,I/[SystemUI]BluetoothHandler( 1454): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
D/UsbSettingsReceiver( 6150): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6150): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6150): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6150): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6150): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/BluetoothBondStateMachine( 6118): make
D/BluetoothAdapterService( 6118): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1671901a
D/LGBluetoothServiceAdapter( 6118): [BTUI] check adapter is available - false.
D/BluetoothAdapterService( 6118): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1671901a
D/LGBluetoothServiceAdapter( 6118): [BTUI] check adapter is available - true : set adapter available.
D/LGBluetoothSettingsDBObserver( 6118): [BTUI] register observer for LG device name DB
,I/BluetoothBondStateMachine( 6118): StableState(): Entering Off State
D/UsbSettingsControl( 6150): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6150): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6150): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6150): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6150): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6150): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 6150): [AUTORUN] setTetherStatus() : status=false
I/ActivityManager( 1029): Killing 5506:com.lge.appbox.client/u0a11 (adj 15): empty #17
E/BluetoothAdapterService( 6118): File transfer profiles supported!!
I/wpa_supplicant( 6173): rfkill: Cannot open RFKILL control device
V/BluetoothPbapReceiver( 6118): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 6118): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6118): ***********state = 11
W/libprocessgroup( 1029): failed to open /acct/uid_10011/pid_5506/cgroup.procs: No such file or directory
,E/BluetoothAdapterService( 6118): File transfer profiles supported!!
D/BluetoothHeadset( 1029): Proxy object connected
,D/BluetoothHeadset( 1868): Proxy object connected
D/UsbSettingsReceiver( 6150): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6150): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6150): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6150): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/HeadsetService( 6118): Received start request. Starting profile...
I/LGBluetoothHeadsetServiceJni( 6118): classInitNative: succeeds
D/LGBluetoothHfpAdapter( 6118): Version 1.6
D/BluetoothHeadset( 1868): Proxy object connected
D/BluetoothHeadset( 1868): Proxy object connected
D/LGBluetoothFeatureConfig( 6118): isPrivacyLogsEnabled : true
I/BluetoothHeadsetServiceJni( 6118): classInitNative: succeeds
D/HeadsetStateMachine( 6118): make
I/wpa_supplicant( 6173): [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,I/wpa_supplicant( 6173): p2p0: CTRL-EVENT-AVOID-FREQ ranges=
I/wpa_supplicant( 6173): wlan0: CTRL-EVENT-SCAN-STARTED 
D/LgDataFeature( 6118): LgDataFeature() Constructor: none
D/LgDataFeature( 6118): LgDataFeature() Constructor Done, null
E/WifiStateMachine( 1029):  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
E/WifiStateMachine( 1029):  SupplicantStartingState CMD_START_DRIVER 0 0
D/WifiMonitor( 1029): Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
D/WifiMonitor( 1029): Dropping event because (p2p0) is stopped
D/WifiMonitor( 1029): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiStateMachine( 1029):  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
E/WifiStateMachine( 1029):  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
E/WifiStateMachine( 1029):  SupplicantStartingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1029):  DefaultState CMD_RECONNECT 0 0
E/WifiStateMachine( 1029):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1029):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=0 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1029): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1029): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine( 1029):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
,E/WifiStateMachine( 1029):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1029):  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
D/WifiNative-wlan0( 1029): doString: [DRIVER MACADDR]
D/WifiNative-wlan0( 1029):    returned Macaddr = c4:9a:02:7b:60:ac
D/WifiStateMachine( 1029): MAC Addr from driver = c4:9a:02:7b:60:ac
D/WifiOffDelayIfNotUsed( 1029): setPowerSaveActivated(false)
I/ActivityManager( 1029): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6184 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
D/UsbSettingsReceiver( 6150): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/HeadsetStateMachine( 6118): max_hf_connections = 1
I/bluedroid-qcom( 6118): get_profile_interface handsfree
V/ToneGenerator( 6118): ToneGenerator constructor: streamType=8, volume=1.000000
,V/AudioPolicyService(  324): registerClient() client 0xb57bedc0, uid 1002
V/AudioPolicyManager(  324): getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  324): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  324): getOutput() returns output 2
V/AudioSystem( 6118): getOutputSamplingRate() no output descriptor for output 2 in gOutputs
V/AudioFlinger(  324): registerClient() client 0xb55815e0, pid 6118
E/WifiStateMachine( 1029): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1029): useWiFiOffloading() : false
E/WifiStateMachine( 1029): CONFIG_LGE_WLAN_PATH : true
D/UsbSettingsControl( 6150): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6150): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 6150): [AUTORUN] onReceive() : activeList=[]
V/AudioSystem(  324): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem(  324): ioConfigChanged() opening already existing output! 4
V/ToneGenerator( 6118): Create Track: 0xb4928a80
V/AudioTrack( 6118): set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
V/AudioTrack( 6118): set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
V/AudioSystem( 1454): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1454): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1868): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1868): ioConfigChanged() opening already existing output! 4
V/AudioPolicyManager(  324): getOutputForAttr() usage=3, content=4, tag= flags=00000000
V/AudioPolicyManager(  324): getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  324): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  324): getOutput() returns output 2
V/AudioSystem( 1029): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1029): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 2228): ioConfigChanged() event 0, ioHandle 4
,V/AudioSystem( 2228): ioConfigChanged() opening already existing output! 4
W/Settings( 1029): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/AudioSystem(  324): ioConfigChanged() event 0, ioHandle 2
W/Settings( 1029): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/AudioSystem(  324): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1454): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1454): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1868): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1868): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1029): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1029): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 6118): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 6118): ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
D/WifiNative-wlan0( 1029): doBoolean: SET update_config 1
V/AudioSystem( 6118): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 6118): ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
V/AudioSystem( 2228): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 2228): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 3303): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 3303): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 3303): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 3303): ioConfigChanged() opening already existing output! 2
D/WfdService( 1961): Waiting for WifiP2p enabling
I/AudioFlinger(  324): isAudioPlaybackHookOn() false
D/WifiNative-wlan0( 1029): SET update_config 1: returned true
D/WifiConfigStore( 1029): Loading config and enabling all networks 
V/AudioPolicyManager(  324): getOutputForAttr() usage=3, content=4, tag= flags=00000000
V/AudioPolicyManager(  324): getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
V/AudioPolicyManagerEx(  324): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  324): getOutput() returns output 2
D/WifiNative-wlan0( 1029): doString: [LIST_NETWORKS]
V/AudioSystem( 6118): getLatency() output 2, latency 50
V/AudioSystem( 6118): getFrameCount() output 2, frameCount 960
I/WifiServerServiceExt( 1029): WIFI_STATE_CHANGED_ACTION [3]
V/AudioTrack( 6118): createTrack_l() output 2 afLatency 50
D/WifiNative-wlan0( 1029):    returned network id / ssid / bssid / flags 0	NG700	any	
V/AudioFlinger(  324): [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
V/AudioFlinger(  324): [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
V/AudioFlinger(  324): [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
V/AudioFlinger(  324): [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
V/AudioFlinger(  324): createTrack() lSessionId: 16
D/StatusBar.NetworkController( 1454): refreshViews: Data not connected!! Set no data type icon / Roaming
V/AudioTrack( 6118): AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
V/AudioFlinger(  324): acquiring 16 from 6118, for 6118
V/AudioFlinger(  324):  added new entry for 16
V/ToneGenerator( 6118): ToneGenerator INIT OK, time: 108361
E/BluetoothAdapterService( 6118): File transfer profiles supported!!
D/BluetoothAdapterService( 6118): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1671901a
D/HeadsetStateMachine( 6118): Enter Disconnected: -2, size: 0
D/HeadsetPhoneState( 6118): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 6118): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetStateMachine( 6118): [BTUI] change sampling rate to 8000 when device is disconnected
D/BluetoothAdapterService( 6118): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1671901a
V/AudioFlinger(  324): setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6118
D/audio_hw_primary(  324): adev_set_parameters: enter: bt_samplerate=8000
V/voice   (  324): voice_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  324): voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  324): voice_extn_compress_voip_set_parameters: exit
V/voice   (  324): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  324): LGE_platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  324): platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  324): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  324): lge_platform_set_loopback_parameters: enter: 
V/audio_hw_primary(  324): adev_set_parameters: exit with code(0)
E/audio_a2dp_hw(  324): adev_set_parameters: ERROR: set param called even when stream out is null
V/ToneGenerator( 6118): ToneGenerator destructor
V/ToneGenerator( 6118): stopTone
V/ToneGenerator( 6118): Delete Track: 0xb4928a80
I/WifiServerServiceExt( 1029): batteryPsActivateMsgHandler : state:0 event:3
D/BluetoothA2dp( 1029): Proxy object connected
D/UsbSettingsReceiver( 6150): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6150): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 6150): [AUTORUN] setTetherStatus() : status=false
V/AudioTrack( 6118): ~AudioTrack, releasing session id from 6118 on behalf of 6118
D/A2dpService( 6118): Received start request. Starting profile...
V/AudioPolicyService(  324): AudioCommandThread() adding release output 2
V/AudioPolicyService(  324): inserting command: 6 at index 0, num commands 0
V/AudioPolicyService(  324): AudioCommandThread() waking up
V/AudioPolicyService(  324): AudioCommandThread() processing release output 2
I/BluetoothAvrcpServiceJni( 6118): classInitNative: succeeds
V/AudioPolicyManager(  324): releaseOutput() 2
V/AudioPolicyService(  324): AudioCommandThread() going to sleep
V/AudioFlinger(  324): PlaybackThread::Track destructor
V/AudioFlinger(  324): removeClient_l() pid 6118, calling pid 324
V/AudioFlinger(  324): releasing 16 from 6118 for 6118
V/AudioFlinger(  324):  decremented refcount to 0
V/AudioFlinger(  324): purging stale effects
V/Avrcp   ( 6118): make
E/WifiConfigStore( 1029): readNetworkVariablesFromSupplicantFile key=psk
D/Avrcp   ( 6118): [BTUI] Use Native AVRCP : init jni
I/bluedroid-qcom( 6118): get_profile_interface avrcp
W/Process ( 1029): Unable to open /proc/6195/status
E/WifiConfigStore( 1029): readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
E/WifiConfigStore( 1029): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,I/ActivityManager( 1029): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6202 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
D/WifiStateMachine( 1029): enableVerboseLogging : level 2
D/WifiNative-wlan0( 1029): doBoolean: SET device_name g3_global_com
D/WifiNative-wlan0( 1029): SET device_name g3_global_com: returned true
D/WifiNative-wlan0( 1029): doBoolean: SET manufacturer LGE
D/WifiNative-wlan0( 1029): SET manufacturer LGE: returned true
D/WifiNative-wlan0( 1029): doBoolean: SET model_name LG-D855
D/WifiNative-wlan0( 1029): SET model_name LG-D855: returned true
D/WifiNative-wlan0( 1029): doBoolean: SET model_number LG-D855
E/BluetoothAdapterService( 6118): File transfer profiles supported!!
D/WifiNative-wlan0( 1029): SET model_number LG-D855: returned true
D/WifiNative-wlan0( 1029): doBoolean: SET serial_number LGD8553bed2d08
D/WifiNative-wlan0( 1029): SET serial_number LGD8553bed2d08: returned true
D/WifiNative-wlan0( 1029): doBoolean: SET config_methods physical_display virtual_push_button
D/WifiNative-wlan0( 1029): SET config_methods physical_display virtual_push_button: returned true
D/WifiNative-wlan0( 1029): doBoolean: SET device_type 10-0050F204-5
D/WifiNative-wlan0( 1029): SET device_type 10-0050F204-5: returned true
V/AudioManager( 6118): registerRemoteController: size of Media player list: 0
E/BluetoothAdapterService( 6118): File transfer profiles supported!!
E/AudioManager( 6118): No RCC entry present to update
E/RemoteController( 6118): Cannot set synchronization mode on an unregistered RemoteController
D/WifiStateMachine( 1029): Setting OUI to DA-A1-19
D/WifiNative-wlan0( 1029): doBoolean: SCAN_INTERVAL 120
D/WifiNative-wlan0( 1029): SCAN_INTERVAL 120: returned true
D/WifiNative-HAL( 1029): Setting external_sim to 1
D/WifiNative-wlan0( 1029): doBoolean: SET external_sim 1
D/WifiNative-wlan0( 1029): SET external_sim 1: returned true
I/WifiNative-HAL( 1029): startHal
E/wifi    ( 1029): getStaticLongField sWifiHalHandle 0x9892b8dc
E/WifiHAL ( 1029): Could not connect handle
D/wifi    ( 1029): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x20186a
I/WifiNative-HAL( 1029): Could not start hal
D/WifiStateMachine( 1029): Setting OUI to DA-A1-19
I/WifiNative-HAL( 1029): startHal
E/wifi    ( 1029): getStaticLongField sWifiHalHandle 0x9892b85c
E/WifiHAL ( 1029): Could not connect handle
I/BluetoothAvrcpQcomServiceJni( 6118): classInitQcomNative: succeeds
D/wifi    ( 1029): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x201862
I/WifiNative-HAL( 1029): Could not start hal
D/WifiNative-wlan0( 1029): doBoolean: STA_AUTOCONNECT 1
D/WifiNative-wlan0( 1029): STA_AUTOCONNECT 1: returned true
D/LGBluetoothAvrcpQcomAdapter( 6118): [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
D/WifiNative-wlan0( 1029): doBoolean: DRIVER BTCOEXSCAN-STOP
I/BluetoothAvrcpQcomServiceJni( 6118): initQcomNative: succeeds
D/WfdsService( 1961): Supplicant Connection state is changed : true
I/wpa_supplicant( 6173): wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
D/WfdsService( 1961): DefaultState - WIFI_SUPPLICANT_CONNECTED
D/WfdsService( 1961): Set the WFDS Monitor: true
D/WifiNative-wlan0( 1029): DRIVER BTCOEXSCAN-STOP: returned true
D/WifiNative-wlan0( 1029): doBoolean: DRIVER RXFILTER-STOP
D/WfdsMonitor( 1961): WfdsMonitorThread create
I/wpa_supplicant( 6173): wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
D/WfdsMonitor( 1961): WFDS Monitor is created and started
D/WfdsService( 1961): WiFi: Supplicant connection re-established
D/WifiHS20( 1029): hidePasspointNotification off =false
W/Settings( 1029): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1029): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1029): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/StatusBar.NetworkController( 1454): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1454): mWifiConnected = false, mWifiLevel = 0
E/BluetoothAdapterService( 6118): File transfer profiles supported!!
D/WifiNative-wlan0( 1029): DRIVER RXFILTER-STOP: returned true
D/WifiNative-wlan0( 1029): doBoolean: DRIVER RXFILTER-REMOVE 3
I/wpa_supplicant( 6173): wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
D/StatusBar.NetworkController( 1454): refreshViews: Data not connected!! Set no data type icon / Roaming
E/BluetoothAdapterService( 6118): File transfer profiles supported!!
E/CtrlSupplicant( 1961): Access OK "@android:wpa_wlan0"
E/CtrlSupplicant( 1961): Succeed to open control connection
E/CtrlSupplicant( 1961): Succeed to open monitor connection
D/WfdsMonitor( 1961): Supplicant connection established
D/LGBluetoothAvrcpQcomAdapter( 6118): [BTUI] [+] updateMediaPlayerInfo
D/WfdsService( 1961): Connected to the supplicant for wfds
D/WifiNative-wlan0( 1029): DRIVER RXFILTER-REMOVE 3: returned true
D/WifiNative-wlan0( 1029): doBoolean: DRIVER RXFILTER-START
I/wpa_supplicant( 6173): wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
D/WifiNative-wlan0( 1029): DRIVER RXFILTER-START: returned true
D/WifiNative-wlan0( 1029): doBoolean: DRIVER RXFILTER-STOP
I/wpa_supplicant( 6173): wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
D/WifiNative-wlan0( 1029): DRIVER RXFILTER-STOP: returned true
D/WifiNative-wlan0( 1029): doBoolean: DRIVER RXFILTER-REMOVE 2
I/wpa_supplicant( 6173): android_multicast_filter_startstop : multicast filter set
D/WifiNative-wlan0( 1029): DRIVER RXFILTER-REMOVE 2: returned true
D/WifiNative-wlan0( 1029): doBoolean: DRIVER RXFILTER-START
I/wpa_supplicant( 6173): wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
D/WifiNative-wlan0( 1029): DRIVER RXFILTER-START: returned true
E/WifiNative: ( 1029): [108,408,962 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
D/WifiNative-wlan0( 1029): doBoolean: RECONNECT
D/WifiNative-wlan0( 1029): RECONNECT: returned true
D/WifiNative-wlan0( 1029): doString: [STATUS]
D/WifiMonitor( 1029): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=1 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiNative-wlan0( 1029):    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
D/WifiNative-wlan0( 1029): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 6173): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1029): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1029): doBoolean: SET ps 1
D/WifiNative-wlan0( 1029): SET ps 1: returned true
D/LGWifiP2pService( 1029): P2pDisabledState{ when=-4ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  318): Setting iface cfg
D/CommandListener(  318): Trying to bring up p2p0
D/WifiMonitor( 1029): startMonitoring(p2p0) with mConnected = true
D/LGWifiP2pService( 1029): P2pEnablingState
D/LGWifiP2pService( 1029): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): P2p socket connection successful
D/LGWifiP2pService( 1029): P2pEnabledState
D/WifiService( 1029): New client listening to asynchronous messages
,E/WifiStateMachine( 1029):  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
E/WifiStateMachine( 1029):  DisconnectedState CMD_START_DRIVER 0 0
E/WifiStateMachine( 1029):  ConnectModeState CMD_START_DRIVER 0 0
E/WifiStateMachine( 1029):  DriverStartedState CMD_START_DRIVER 0 0
E/WifiStateMachine( 1029):  DisconnectedState what:132106 1 0
E/WifiStateMachine( 1029):  ConnectModeState what:132106 1 0
E/WifiStateMachine( 1029):  DriverStartedState what:132106 1 0
I/WifiServerServiceExt( 1029): setWifiDualbandAPConnection band : 1
E/wpa_supplicant( 6173): nWIFIDualbandAPConnection: 1
D/LGWifiP2pService( 1029): sending p2p connection changed broadcast
E/WifiStateMachine( 1029):  DisconnectedState what:132096 -100 0
E/WifiStateMachine( 1029):  ConnectModeState what:132096 -100 0
E/WifiStateMachine( 1029):  DriverStartedState what:132096 -100 0
D/WifiNative-p2p0( 1029): doBoolean: SET persistent_reconnect 1
D/WifiNative-p2p0( 1029): SET persistent_reconnect 1: returned true
D/WifiNative-p2p0( 1029): doBoolean: SET device_name G3-1
D/WifiNative-p2p0( 1029): SET device_name G3-1: returned true
D/LGWifiP2pService( 1029): [LGE_P2P] initializeP2pSettings() check postfix
D/LGWifiP2pService( 1029): before postfix = G3-1
D/WifiServerServiceExt( 1029): postfix byte check : 4
D/LGWifiP2pService( 1029): after postfix = G3-1
D/WifiScanningService( 1029): SCAN_AVAILABLE : 3
D/WifiNative-p2p0( 1029): doBoolean: SET p2p_ssid_postfix -G3-1
D/RttService( 1029): SCAN_AVAILABLE : 3
D/WifiScanningService( 1029): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL( 1029): startHal
D/RttService( 1029): DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1029): SET p2p_ssid_postfix -G3-1: returned true
D/WifiNative-p2p0( 1029): doBoolean: SET device_type 10-0050F204-5
V/WfdStateTracker( 1961): WfdStateTracker handleDirectStateChangedEvent: 2
D/WfdsService( 1961): WifiP2pState is changed : true
D/WifiNative-p2p0( 1029): SET device_type 10-0050F204-5: returned true
D/WifiNative-p2p0( 1029): doBoolean: SET config_methods virtual_push_button physical_display keypad
D/WifiNative-p2p0( 1029): SET config_methods virtual_push_button physical_display keypad: returned true
E/wifi    ( 1029): getStaticLongField sWifiHalHandle 0x94f6b99c
E/WifiHAL ( 1029): Could not connect handle
D/wifi    ( 1029): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x5013fe
I/WifiNative-HAL( 1029): Could not start hal
E/WifiScanningService( 1029): could not start HAL
D/WifiNative-p2p0( 1029): doBoolean: P2P_SET conc_pref p2p
D/WifiNative-p2p0( 1029): P2P_SET conc_pref p2p: returned true
D/WfdsService( 1961): Receive the WFDS_ENABLE Method
D/WifiNative-HAL( 1029): p2pGetDeviceAddress
D/WfdsService( 1961): Set the WFDS Monitor: true
D/WfdsService( 1961): Connected to the supplicant for wfds
D/WfdsJNI ( 1961): doCommand: WFDS_SET TRUE
I/wpa_supplicant( 6173): WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
D/WfdsJNI ( 1961): doCommand: WFDS_GET_MAC_ADDRESS
I/wpa_supplicant( 6173): WFDS: wfds_supplicant_wfds_cmd: cmd = GET_MAC_ADDRESS
D/WfdsJNI ( 1961): doCommand: IFNAME=wlan0 GET_CAPABILITY channels
D/WfdsService( 1961): selectPreferredScanChannel [36]
D/WfdsService( 1961): STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7b:60:ac
D/WifiNative-HAL( 1029): p2pGetDeviceAddress returning 02:9a:02:7b:60:ac
I/WifiServerServiceExt( 1029): set CMD_DISCONNECT_RSSI_LVL : -100
E/wpa_supplicant( 6173): disconnect_rssi_lvl: -100
E/WifiStateMachine( 1029):  DisconnectedState CMD_SET_COUNTRY_CODE 1 0 cz
E/WifiStateMachine( 1029):  ConnectModeState CMD_SET_COUNTRY_CODE 1 0 cz
E/WifiStateMachine( 1029):  DriverStartedState CMD_SET_COUNTRY_CODE 1 0 cz
D/WifiNative-wlan0( 1029): doBoolean: DRIVER COUNTRY CZ
I/wpa_supplicant( 6173): wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
I/wpa_supplicant( 6173): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
I/wpa_supplicant( 6173): [LGE_PATCH] driver_cmd() country:CZ
I/wpa_supplicant( 6173): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
I/wpa_supplicant( 6173): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WfdsMonitor( 1961): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WfdsMonitor( 1961): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WifiMonitor( 1029): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=2 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1029): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1029): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
D/WifiMonitor( 1029): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
V/LGMDMManager( 6118): Create singleton instance
E/WifiMonitor( 1029): WifiMonitor:p2p0 cnt=3 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1029): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1029): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiMonitor( 1029): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1029): WifiMonitor:p2p0 cnt=4 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1029): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1029): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/LGWifiP2pService( 1029): DeviceAddress: 02:9a:02:7b:60:ac
D/WifiNative-p2p0( 1029): doBoolean: P2P_FLUSH
D/WifiNative-wlan0( 1029): DRIVER COUNTRY CZ: returned true
D/WfdsService( 1961): WIFI_P2P_CONNECTION_CHANGED_ACTION
E/WifiStateMachine( 1029):  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine( 1029):  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine( 1029):  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
D/WifiNative-wlan0( 1029): doBoolean: DRIVER SETBAND 0
I/wpa_supplicant( 6173): wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
I/wpa_supplicant( 6173): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
D/WfdsService( 1961): isConnected: false
,D/WifiMonitor( 1029): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=5 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
E/WifiMonitor( 1029): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
E/WifiMonitor( 1029): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
D/WifiNative-wlan0( 1029): DRIVER SETBAND 0: returned true
D/WifiNative-wlan0( 1029): doBoolean: BSS_FLUSH 0
I/WfdStateTracker( 1961): handleP2pThisDeviceChanged
D/WfdsService( 1961): WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
D/WfdsService( 1961): Update P2p Interface State: 3
D/WifiNative-wlan0( 1029): BSS_FLUSH 0: returned true
D/WifiNative-p2p0( 1029): P2P_FLUSH: returned true
D/WifiNative-p2p0( 1029): doBoolean: P2P_SERVICE_FLUSH
D/WifiNative-p2p0( 1029): P2P_SERVICE_FLUSH: returned true
D/WifiNative-p2p0( 1029): doString: [LIST_NETWORKS]
D/WifiNative-p2p0( 1029):    returned network id / ssid / bssid / flags
D/WifiNative-p2p0( 1029): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1029): doBoolean: SCAN
I/BluetoothAdapterState( 6118): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
D/WifiNative-p2p0( 1029): SAVE_CONFIG: returned true
D/LGWifiP2pService( 1029): sending p2p persistent groups changed broadcast
D/LGWifiP2pService( 1029): InactiveState
D/LGWifiP2pService( 1029): InactiveState{ when=-19ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): P2pEnabledState{ when=-19ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1029): doBoolean: DRIVER COUNTRY CZ
I/wpa_supplicant( 6173): wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
I/wpa_supplicant( 6173): p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
I/wpa_supplicant( 6173): [LGE_PATCH] driver_cmd() country:CZ
I/wpa_supplicant( 6173): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
I/wpa_supplicant( 6173): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,D/WfdsMonitor( 1961): Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
D/WfdsMonitor( 1961): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WfdsMonitor( 1961): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WifiMonitor( 1029): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
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
D/WifiNative-p2p0( 1029): DRIVER COUNTRY CZ: returned true
D/LGWifiP2pService( 1029): InactiveState{ when=-14ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): P2pEnabledState{ when=-15ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): InactiveState{ when=-1ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): P2pEnabledState{ when=-1ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): DefaultState{ when=-1ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): InactiveState{ when=-1ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): P2pEnabledState{ when=-1ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): DefaultState{ when=-1ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): InactiveState{ when=-1ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): P2pEnabledState{ when=-1ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): DefaultState{ when=-1ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
W/WfdsService( 1961): DefaultState - msg [9441285] is not handled
D/WifiNative-wlan0( 1029): SCAN: returned false
E/WifiStateMachine( 1029):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=108481  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine( 1029):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=108481  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine( 1029):  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1029):  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1029):  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1029):  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1029):  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
D/LGWifiP2pService( 1029): InactiveState{ when=-5ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): P2pEnabledState{ when=-5ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandle,r }
D/LGWifiP2pService( 1029): DefaultState{ when=-5ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1029): No p2p device connected
W/Settings( 1029): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1029): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1029): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WifiServerServiceExt( 1029): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1029): setSupplicantStateSCANNING
I/StatusBar.NetworkController( 1454): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1454): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1454): refreshViews: Data not connected!! Set no data type icon / Roaming
V/SIM_STK ( 1029): Menu title from STK is T-Mobile
V/SIM_STK ( 1029): Menu title from STK is T-Mobile
,E/ActivityThread( 6184): Failed to find provider info for com.lge.lgaccount.provider
W/LG Account v2.2( 6184): No ProfileInfo entries
I/LG Account v2.2( 6184): isEnabled: false
I/Feature ( 6184): [Lifetracker]ver: 4.21.112(40211120)
I/Feature ( 6184): [Lifetracker]Country: EU
I/Feature ( 6184): [Lifetracker]Operator: OPEN
I/Feature ( 6184): [Lifetracker]Ranking support: false
I/Feature ( 6184): [Lifetracker]Comfort support: false
I/Feature ( 6184): [Lifetracker]Accessory: true
I/Feature ( 6184): [Lifetracker]Health device: true
I/Feature ( 6184): [Lifetracker]Extra Pedometer: false
I/Feature ( 6184): [Lifetracker]Blood glucose device: false
I/Feature ( 6184): [Lifetracker]Device Number: 3
,I/ActivityManager( 1029): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6229 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,W/ActivityManager( 1029): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
W/FormManager( 6202): Network not available. Please check & try again.
D/LGBluetoothAvrcpQcomAdapter( 6118): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 6118): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6118): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 6118): [BTUI]          displayName: Music
,D/LGBluetoothAvrcpQcomAdapter( 6118): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 6118): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6118): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 6118): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6118): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 6118): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6118): [BTUI] [-] updateMediaPlayerInfo
I/BluetoothA2dpServiceJni( 6118): classInitNative
I/BluetoothA2dpServiceJni( 6118): classInitNative: succeeds
D/A2dpStateMachine( 6118): make
I/bluedroid-qcom( 6118): get_profile_interface a2dp
I/GKI_LINUX( 6118): gki_task_entry task_id=2 [A2DP-MEDIA] starting
I/LGBluetoothA2dpServiceJni( 6118): classInitNative: succeeds
I/LGBluetoothA2dpAdapter( 6118): [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
D/BluetoothAdapterService( 6118): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1671901a
D/A2dpStateMachine( 6118): Enter Disconnected: -2
D/HeadsetStateMachine( 6118): Proxy object connected
D/LGBluetoothHfpAdapter( 6118): [BTUI] queryPhoneState
D/LGBluetoothHfpAdapter( 6118): Try to query the phonestate on bind
D/BluetoothPermissionRequest( 6150): onReceive
D/LGBluetoothFeatureConfig( 6150):  get() - isFeatureLoaded : false
D/BluetoothPhoneService.BluetoothLTECall( 1868):  call mBluetoothHeadset.phoneStateChanged()
W/BluetoothHeadset( 1868): Proxy not attached to service
D/BluetoothHeadset( 1868): java.lang.Throwable
D/BluetoothHeadset( 1868): 	at android.bluetooth.BluetoothHeadset.phoneStateChanged(BluetoothHeadset.java:826)
D/BluetoothHeadset( 1868): 	at com.android.phone.BluetoothPhoneService$BluetoothLTECall.handleQueryPhoneState(BluetoothPhoneService.java:1527)
D/BluetoothHeadset( 1868): 	at com.android.phone.BluetoothPhoneService$BluetoothLTECall.access$700(BluetoothPhoneService.java:1360)
D/BluetoothHeadset( 1868): 	at com.android.phone.BluetoothPhoneService$1.handleMessage(BluetoothPhoneService.java:268)
D/BluetoothHeadset( 1868): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BluetoothHeadset( 1868): 	at android.os.Looper.loop(Looper.java:135)
D/BluetoothHeadset( 1868): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
D/BluetoothHeadset( 1868): 	at java.lang.reflect.Method.invoke(Native Method)
D/BluetoothHeadset( 1868): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/BluetoothHeadset( 1868): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
D/BluetoothHeadset( 1868): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
D/BluetoothAdapterService( 6118): Profile still not running:com.android.bluetooth.gatt.GattService
D/HeadsetStateMachine( 6118): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 6118): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
I/BluetoothHidServiceJni( 6118): classInitNative: succeeds
D/HeadsetStateMachine( 6118): Disconnected process message: 11, size: 0
D/HidService( 6118): Received start request. Starting profile...
I/bluedroid-qcom( 6118): get_profile_interface hidhost
D/BluetoothAdapterService( 6118): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1671901a
I/BluetoothHealthServiceJni( 6118): classInitNative: succeeds
D/HealthService( 6118): Received start request. Starting profile...
,I/bluedroid-qcom( 6118): get_profile_interface health
I/LGBluetoothHealthServiceJni( 6118): classInitNative: succeeds
D/BluetoothAdapterService( 6118): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1671901a
I/BluetoothPanServiceJni( 6118): classInitNative(L105): succeeds
D/PanService( 6118): Received start request. Starting profile...
D/BluetoothPanServiceJni( 6118): initializeNative(L110): pan
I/bluedroid-qcom( 6118): get_profile_interface pan
D/BluetoothManagerService( 1029): Message: 20
D/BluetoothManagerService( 1029): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@bc6fc65:true
V/FormManager( 6202): Network unavailable.
I/LGBluetoothPanAdapter( 6118): [BTUI] getInstance : create [LGBluetoothPanAdapter]
D/BluetoothAdapterService( 6118): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1671901a
I/BtGatt.JNI( 6118): classInitNative(L901): classInitNative: Success!
V/FormManager( 6202): Network unavailable.
D/BtGatt.DebugUtils( 6118): handleDebugAction() action=null
D/BtGatt.GattService( 6118): Received start request. Starting profile...
D/BtGatt.GattService( 6118): start()
I/bluedroid-qcom( 6118): get_profile_interface gatt
D/BtGatt.AdvertiseManager( 6118): advertise manager created
D/LGBluetoothResetSettingReceiver( 6150): return without doing reset settings.
I/ActivityManager( 1029): Killing 5526:com.android.contacts/u0a19 (adj 15): empty #17
,D/PCSuite ( 6229): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,I/ThermalEngine(  337): Thermal-Server: Thermal received msg from  override
I/Thermal-Lib( 3070): Thermal-Lib-Client: Client request sent
W/libprocessgroup( 1029): failed to open /acct/uid_10019/pid_5526/cgroup.procs: No such file or directory
,I/ActivityManager( 1029): Killing 5838:com.lge.email/u0a23 (adj 15): empty #17
V/WiFiOffLoadBroadcast( 6150): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,D/WifiService( 1029): New client listening to asynchronous messages
D/LgDataFeature( 6150): LgDataFeature() Constructor: none
D/LgDataFeature( 6150): LgDataFeature() Constructor Done, null
,D/WiFiOffLoadUpdatePriority( 6150): remove : truetruetrue
E/WifiStateMachine( 1029):  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1029):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1029):  DisconnectedState CMD_SAVE_CONFIG uid=1000 0 0
,E/WifiStateMachine( 1029):  ConnectModeState CMD_SAVE_CONFIG uid=1000 0 0
D/WifiNative-wlan0( 1029): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1029): SAVE_CONFIG: returned true
,D/WiFiOffLoadUpdatePriority( 6150): remove1
V/WiFiOffLoadSharedPrefsUtils( 6150): save remove
D/WiFiOffLoadBroadcast( 6150): mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
D/WiFiOffLoadBroadcast( 6150): S: false, R: false
E/WifiStateMachine( 1029):  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1029):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
,D/WiFiOffLoadUpdatePriority( 6150): saved SSID: "NG700"
D/WiFiOffLoadUpdatePriority( 6150): connected SSID: null
D/WiFiOffLoadUpdatePriority( 6150): private wpa: "NG700" 300
D/WifiServiceImplEx( 1029): addOrUpdateNetwork pid=6150, uid=1000, packageName=android.uid.system:1000
E/addOrUpdateNetwork( 1029):  uid = 1000 SSID "NG700" nid=0
W/libprocessgroup( 1029): failed to open /acct/uid_10023/pid_5838/cgroup.procs: No such file or directory
E/WifiStateMachine( 1029):  DisconnectedState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=2
E/WifiStateMachine( 1029):  ConnectModeState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=2
,E/WifiConfigStore( 1029):  key="NG700"WPA_PSK netId=0 uid=0/1000
D/WifiServerServiceExt( 1029): addOrUpdateNetwork: mThisIsFirstEnableing = false
D/WifiNative-wlan0( 1029): doBoolean: SET_NETWORK 0 ssid 4e47373030
D/BluetoothAdapterService( 6118): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1671901a
D/BluetoothAdapterService( 6118): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1671901a
I/LGBluetoothMapAdapter( 6118): [BTUI] getInstance : create [LGBluetoothMapAdapter]
V/AlarmManager( 1029): RTC_WAKEUP set : Alarm{25109f63 type 0 when 1454414859616 com.android.vending} when 1454414859616
V/AlarmManager( 1029): RTC_WAKEUP set : Alarm{2363760 type 0 when 1454414863361 android} when 1454414863361
V/BluetoothMapService( 6118): BluetoothMapBinder()
D/BluetoothMapService( 6118): Received start request. Starting profile...
,D/BluetoothMapService( 6118): start()
D/WifiNative-wlan0( 1029): SET_NETWORK 0 ssid 4e47373030: returned true
D/WifiNative-wlan0( 1029): doBoolean: SET_NETWORK 0 key_mgmt WPA-PSK
D/WifiNative-wlan0( 1029): SET_NETWORK 0 key_mgmt WPA-PSK: returned true
D/WifiNative-wlan0( 1029): doBoolean: SET_NETWORK 0 proto WPA RSN
D/WifiNative-wlan0( 1029): SET_NETWORK 0 proto WPA RSN: returned true
D/WifiNative-wlan0( 1029): doBoolean: SET_NETWORK 0 pairwise TKIP CCMP
D/WifiNative-wlan0( 1029): SET_NETWORK 0 pairwise TKIP CCMP: returned true
D/WifiNative-wlan0( 1029): doBoolean: SET_NETWORK 0 group WEP40 WEP104 TKIP CCMP
D/WifiNative-wlan0( 1029): SET_NETWORK 0 group WEP40 WEP104 TKIP CCMP: returned true
D/WifiNative-wlan0( 1029): doBoolean: SET_NETWORK 0 priority 300
D/WifiNative-wlan0( 1029): SET_NETWORK 0 priority 300: returned true
E/WifiConfigStore( 1029): will read network variables netId=0
D/BluetoothMapEmailSettingsLoader( 6118): Found 0 applications
D/BluetoothMapEmailAppObserver( 6118): createReceiver()
D/BluetoothMapEmailAppObserver( 6118): initObservers()
D/BluetoothMapEmailAppObserver( 6118): getEnabledAccountItems()
E/WifiConfigStore( 1029): writeIpAndProxyConfigurationsOnChange: "NG700" -> "NG700" path: /data/misc/wifi/ipconfig.txt
E/WifiConfigStore( 1029):  writeKnownNetworkHistory() num networks:1 needWrite=false
D/WiFiOffLoadUpdatePriority( 6150):  ssid "NG700" prio 300
D/WiFiOffLoadUpdatePriority( 6150): configuration updated: 0
E/WifiStateMachine( 1029):  DisconnectedState CMD_SAVE_CONFIG uid=1000 0 0
E/WifiStateMachine( 1029):  ConnectModeState CMD_SAVE_CONFIG uid=1000 0 0
D/WifiNative-wlan0( 1029): doBoolean: SAVE_CONFIG
D/BluetoothAdapterService( 6118): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1671901a
,D/BluetoothAdapterService( 6118): Profile still not running:com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 6118): Profile still not running:com.android.bluetooth.gatt.GattService
I/wpa_supplicant( 6173): [LGE_PATCH]scan interval[0] = 2 sec.
D/WifiNative-wlan0( 1029): SAVE_CONFIG: returned true
D/WfdsMonitor( 1961): Event [CTRL-EVENT-SCAN-RESULTS ]
D/WfdsMonitor( 1961): Event [WPS-AP-AVAILABLE ]
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=9 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1029): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1029): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
D/WiFiOffLoadUpdatePriority( 6150): configuration saved: true
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=10 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1029): couldn't identify event type - WPS-AP-AVAILABLE 
E/WifiMonitor( 1029): WifiMonitor:p2p0 cnt=11 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1029): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1029): Event [IFNAME=p2p0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1029): WifiMonitor:p2p0 cnt=12 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1029): couldn't identify event type - WPS-AP-AVAILABLE 
D/LGWifiP2pService( 1029): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothAdapterService( 6118): Profile still not running:com.android.bluetooth.gatt.GattService
,E/WifiStateMachine( 1029):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine( 1029):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine( 1029):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine( 1029):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
I/WifiNative-HAL( 1029): startHal
E/wifi    ( 1029): getStaticLongField sWifiHalHandle 0x9892b8cc
E/WifiHAL ( 1029): Could not connect handle
D/wifi    ( 1029): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x1021da
I/WifiNative-HAL( 1029): Could not start hal
D/WifiNative-wlan0( 1029): doString: [BSS RANGE=0- MASK=0x21987]
D/BluetoothAdapterService( 6118): Profile still not running:com.android.bluetooth.gatt.GattService
V/PanService( 6118): [BTUI] SIM Extra State :ABSENT
D/LGBluetoothOppAdapter( 6118): [BTUI] getInstance : create [LGBluetoothOppAdapter]
D/BluetoothAdapterService( 6118): Profile still not running:com.android.bluetooth.map.BluetoothMapService
V/BluetoothMapService( 6118): Handler(): got msg=1
D/BluetoothAdapterState( 6118): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid-qcom( 6118): enable
I/bt_hci_bdroid( 6118): init
I/GKI_LINUX( 6118): gki_task_entry task_id=0 [BTU] starting
,I/bt-btu  ( 6118): btu_task pending for preload complete event
D/PCSuite ( 6229): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6150): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
V/BluetoothFtpReceiver( 6118): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
I/bt_vendor( 6118): bt-vendor : init
I/bt_vendor( 6118): bt-vendor : get_bt_soc_type
E/bt_vendor( 6118): get_bt_soc_type: Failed to get soc type
I/bt_vendor( 6118): init: Local BD Address : c0:64:73:54:3f:58
D/bt_userial_mct( 6118): userial_init
D/bt_hci_bdroid( 6118): set_power 1
I/bt_vendor( 6118): bt-vendor : BT_VND_OP_POWER_CTRL: On
I/bt_vendor( 6118): Starting hciattach daemon
I/bt_vendor( 6118): try to set true
D/WiFiOffLoadBroadcast( 6150): MCCMNC not supported: null
W/sh      ( 6269): type=1400 audit(0.0:157): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/sh      ( 6269): type=1400 audit(0.0:158): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
V/BluetoothSapReceiver( 6118): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 6118): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 6118): SapReceiver onReceive 
V/BluetoothSapReceiver( 6118): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6118):  Bluetooth Adapter state = 11
,I/qcom-bluetooth( 6270): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
V/SIM_STK ( 1029): Menu title from STK is T-Mobile
I/ActivityManager( 1029): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6275 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,W/FormManager( 6202): Network not available. Please check & try again.
V/FormManager( 6202): Network unavailable.
D/LGDMClient( 3250): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,D/LGDMClient( 3250): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
I/qcom-bluetooth( 6285): /system/etc/init.qcom.bt.sh: Transport : smd 
V/FormManager( 6202): Network unavailable.
W/ContextImpl( 3250): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
I/qcom-bluetooth( 6292): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
W/ContextImpl( 3250): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/PostponalbeReceiver( 5146): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/LGDMClient( 3250): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/LGDMClient( 3250): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 3250): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,I/qcom-bluetooth( 6297): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
I/PCSuite ( 6229): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6229): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6229): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6150): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/qcom-bluetooth( 6298): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,I/qcom-bluetooth( 6301): /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
D/WiFiOffLoadBroadcast( 6150): MCCMNC not supported: null
W/ResourcesManager( 6275): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
I/qcom-bluetooth( 6302): /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
D/AuthorizationBluetoothService( 2126): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/QRemote ( 5980): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 5980): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/libmdmdetect( 6304): ESOC framework not supported
,E/Diag_Lib( 6304):  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
I/QRemote ( 5980): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/[BNRBootReceiver]( 5959): boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/BNRAndroBeam( 5959): [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
D/bthci_qcomm_linux( 6304): [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:64:C0)
D/bthci_qcomm_common( 6304): [BTUI] bt_hci_qcomm_init:
D/bthci_qcomm_common( 6304): [BTUI]     BDADDR: 58:3F:54:73:64:C0
D/bthci_qcomm_common( 6304): [BTUI]     BR/EDR: Class 1
D/bthci_qcomm_common( 6304): [BTUI]     LE: Class 2
D/bthci_qcomm_common( 6304): [BTUI]     Ref Clock: 32M
D/btqsocnvmtags( 6304): [BTUI] init_riva_entries: set NORMAL power settings
V/[BNRBootReceiver]( 5959): Boot Receiver Return
D/PostponalbeReceiver( 5146): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6150): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6150): MCCMNC not supported: null
D/QRemote ( 5980): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 5980): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 5980): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
I/ActivityManager( 1029): Killing 5547:com.android.gallery3d/u0a27 (adj 15): empty #17
,E/WifiStateMachine( 1029):  DisconnectedState CMD_START_SCAN -2 -2 ic=1 proc(ms):0 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=120000 [on:0 tx:0 rx:0 period:-1579049699] from screen [on:0 period:-1579049699]
E/WifiStateMachine( 1029):  ConnectModeState CMD_START_SCAN -2 -2 ic=1 proc(ms):1 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=120000 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:-1579049699]
E/WifiStateMachine( 1029):  DriverStartedState CMD_START_SCAN -2 -2 ic=1 proc(ms):2 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=120000 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1579049698]
D/WifiNative-wlan0( 1029): doBoolean: SCAN
I/wpa_supplicant( 6173): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1029): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=13 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1029): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1029): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-wlan0( 1029): SCAN: returned true
I/WifiNative-HAL( 1029): startHal
E/wifi    ( 1029): getStaticLongField sWifiHalHandle 0x9892b7dc
E/WifiHAL ( 1029): Could not connect handle
D/wifi    ( 1029): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x1021fa
I/WifiNative-HAL( 1029): Could not start hal
,I/rmt_storage(  307): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  307): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  307): wakelock acquired: 1, error no: 42
I/rmt_storage(  307): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
,W/libprocessgroup( 1029): failed to open /acct/uid_10027/pid_5547/cgroup.procs: No such file or directory
,V/QRemote ( 5980): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
D/QRemote ( 5980): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:3916
,V/WiFiOffLoadBroadcast( 6150): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,D/WiFiOffLoadBroadcast( 6150): Not supported operator for automatic switch
W/ContextImpl( 4179): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2126): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2126): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2126): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2126): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 4852): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4852): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4852): [1] 5.onFinished: Scheduling replication attempt 1.
I/rmt_storage(  307): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  307): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
I/rmt_storage(  307): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 22
I/rmt_storage(  307): 
,I/rmt_storage(  307): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
E/Diag_Lib(  900): [IMS_FATAL]| 3347 | 907 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
I/ActivityManager( 1029): Killing 5570:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
W/libprocessgroup( 1029): failed to open /acct/uid_10080/pid_5570/cgroup.procs: No such file or directory
,E/QC-QMI  ( 6304): qmi_client [6304] 13: failed to locate client data
E/QC-QMI  (  464): qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
E/QC-QMI  (  464): QMUX qmux_client_id=13 not found in qmux client list, unable to remove
,I/qcom-bluetooth( 6322): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:64:c0 
,I/qcom-bluetooth( 6323): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
I/bt_vendor( 6118): bluetooth satus is on
D/bt_hci_bdroid( 6118): preload
D/bt_userial_mct( 6118): userial_open(port:0)
I/bt_vendor( 6118): bt-vendor : BT_VND_OP_USERIAL_OPEN
,I/bt_vendor( 6118): Done intiailizing UART
I/bt_vendor( 6118): Done intiailizing UART
I/bt_userial_mct( 6118): CMD=66, EVT=66, ACL_Out=67, ACL_In=67
I/bt_vendor( 6118): Bluetooth Firmware and transport layer are initialized
I/bt-btu  ( 6118): btu_task received preload complete event
W/bt-l2cap( 6118): L2CAP - L2CA_Register() called for PSM: 0x0001
W/bt-l2cap( 6118): L2CAP - L2CA_Register() called for PSM: 0x001f
D/bt_userial_mct( 6118): Entering userial_read_thread()
W/bt-l2cap( 6118): L2CAP - L2CA_Register() called for PSM: 0x0003
I/        ( 6118): BTE_InitTraceLevels -- TRC_HCI
I/        ( 6118): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 6118): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 6118): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 6118): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 6118): BTE_InitTraceLevels -- TRC_A2D
I/        ( 6118): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 6118): BTE_InitTraceLevels -- TRC_BTM
I/        ( 6118): BTE_InitTraceLevels -- TRC_HID_HOST
I/        ( 6118): BTE_InitTraceLevels -- TRC_GAP
I/        ( 6118): BTE_InitTraceLevels -- TRC_PAN
I/        ( 6118): BTE_InitTraceLevels -- TRC_SDP
I/        ( 6118): BTE_InitTraceLevels -- TRC_GATT
I/        ( 6118): BTE_InitTraceLevels -- TRC_SMP
I/        ( 6118): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 6118): BTE_InitTraceLevels -- TRC_BTIF
W/bt-btm  ( 6118): btm_decode_ext_features_page Secure conn Controller support Enabled
E/bt-btm  ( 6118): BTM_SecRegister:p_cb_info->p_le_callback == 0xa01c8061 
E/bt-btm  ( 6118): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01c8061 
,E/bt-btif ( 6118): Calling BTA_HhEnable
E/bt-btif ( 6118): btif_storage_get_adapter_property service_mask:0x2140040
W/bt-l2cap( 6118): L2CAP - L2CA_Register() called for PSM: 0x0019
,W/bt-l2cap( 6118): L2CAP - L2CA_Register() called for PSM: 0x0017
D/BluetoothAdapterProperties( 6118): Address is:58:3F:54:73:64:C0
W/bt-l2cap( 6118): L2CAP - L2CA_Register() called for PSM: 0x001b
W/bt-l2cap( 6118): L2CAP - L2CA_Register() called for PSM: 0x0011
W/bt-l2cap( 6118): L2CAP - L2CA_Register() called for PSM: 0x0013
D/BluetoothManagerService( 1029): Bluetooth Adapter name changed to G3-1
D/BluetoothAdapterProperties( 6118): Name is: G3-1
D/BluetoothManagerService( 1029): Stored Bluetooth name: G3-1
D/BluetoothAdapterProperties( 6118): Scan Mode:20
D/BluetoothAdapterProperties( 6118): Discoverable Timeout:120
D/bt_hci_bdroid( 6118): postload
D/bt_hci_bdroid( 6118): Used up Tx Cmd credits
W/bt-l2cap( 6118): L2CAP - L2CA_Register() called for PSM: 0x000f
,W/bt-smp  ( 6118): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6118): Plain text(LSB ~ MSB) = c3 35 51 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6118): Encrypted text(LSB ~ MSB) = 15 70 6b bb ae 6e e4 88 aa 0b ae 5d ad be 09 3c 
W/bt-btm  ( 6118): Stopping oneshot timer
D/bt_hci_bdroid( 6118): Used up Tx Cmd credits
,D/bt_hci_bdroid( 6118): Used up Tx Cmd credits
D/bt_hci_bdroid( 6118): Used up Tx Cmd credits
D/bt_hci_bdroid( 6118): Used up Tx Cmd credits
E/bt_mct  ( 6118): hci lib postload completed
D/bte_conf( 6118): Device ID record 1 : primary
D/bte_conf( 6118):   vendorId            = 00c4
D/bte_conf( 6118):   vendorIdSource      = 0001
D/bte_conf( 6118):   product             = 13a1
D/bte_conf( 6118):   version             = 1000
D/bte_conf( 6118):   clientExecutableURL = 
D/bte_conf( 6118):   serviceDescription  = 
D/bte_conf( 6118):   documentationURL    = 
D/bte_conf( 6118): bte_load_did_conf no section named DID2.
D/BluetoothPanServiceJni( 6118): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothAdapterState( 6118): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
,D/BluetoothAdapterProperties( 6118): ScanMode =  20
D/BluetoothAdapterProperties( 6118): State =  11
D/BluetoothAdapterProperties( 6118): mDiscoverableTimeout = 120
V/LGBluetoothServiceAdapter( 6118): [BTUI] state:11, scanmode:20, timeout:120
D/BluetoothAdapterProperties( 6118): Setting state to 12
I/BluetoothAdapterState( 6118): Bluetooth adapter state changed: 11-> 12
D/BluetoothManagerService( 1029): Message: 60
D/BluetoothManagerService( 1029): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService( 1029): Broadcasting onBluetoothStateChange(true) to 5 receivers.
W/sh      ( 6327): type=1400 audit(0.0:159): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/sh      ( 6327): type=1400 audit(0.0:160): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,W/bt-smp  ( 6118): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6118): Plain text(LSB ~ MSB) = 10 e6 44 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6118): Encrypted text(LSB ~ MSB) = be a0 44 b5 5d c2 29 c2 8f 16 a6 46 e1 99 bf aa 
W/bt-btm  ( 6118): Stopping oneshot timer
D/btif_config_util( 6118): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
W/bt-smp  ( 6118): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6118): Plain text(LSB ~ MSB) = d1 57 59 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6118): Encrypted text(LSB ~ MSB) = a8 f0 0d 8b b2 a2 15 23 4b aa 34 51 e6 4f 1a 58 
W/bt-btm  ( 6118): Stopping oneshot timer
,I/BluetoothAdapterState( 6118): Entering On State
D/BluetoothHeadset( 1868): onBluetoothStateChange: up=true
W/bt-smp  ( 6118): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6118): Plain text(LSB ~ MSB) = f0 21 57 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6118): Encrypted text(LSB ~ MSB) = a5 70 94 32 60 27 80 eb fe 9a 73 14 c1 07 2b be 
W/bt-btm  ( 6118): Stopping oneshot timer
,D/LGBluetoothServiceAdapter( 6118): [BTUI] OnState
D/LGBluetoothServiceAdapter( 6118): [BTUI]         global_name: G3-1
D/LGBluetoothServiceAdapter( 6118): [BTUI]         local_name: G3-1
D/BluetoothAdapterService( 6118): [BTUI] autoConnect() : not allowed
D/BluetoothA2dp( 1029): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1868): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1868): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1029): onBluetoothStateChange: up=true
D/BluetoothManagerService( 1029): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,D/BluetoothAdapterProperties( 6118): Discoverable Timeout:120
D/LGBluetoothDeviceModeControllManager( 6118): adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
E/BluetoothManagerService( 1029): Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
D/BluetoothManagerService( 1029): Bluetooth State Change Intent: 11 -> 12
,D/LGBluetoothAPIService( 1961): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/LGBluetoothAPIService( 1961): Message: 1
D/LGBluetoothAPIService( 1961): MESSAGE_BOOT_COMPLETED
W/bt-smp  ( 6118): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6118): Plain text(LSB ~ MSB) = 8b 45 53 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6118): Encrypted text(LSB ~ MSB) = 4f 08 bf 2e 66 06 c7 a8 18 6b 1c b5 48 53 cc d5 
W/bt-btm  ( 6118): Stopping oneshot timer
I/[SystemUI]BluetoothHandler( 1454): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
D/LGBluetoothDeviceModeControllManager( 6118): [BTUI] checkDeviceModeAndSet, sinkMode : false
,D/BluetoothManagerService( 1029): Message: 40
D/BluetoothManagerService( 1029): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
I/BluetoothMapService( 6118): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
I/qcom-bt-wlan-coex( 6341): /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
D/BluetoothMapService( 6118): STATE_ON
V/BluetoothMapService( 6118): Handler(): got msg=1
D/BluetoothMapMasInstance( 6118): Map Service startRfcommSocketListener
D/LGBluetoothAPIServer( 6118): [BTUI] onCreate()
D/LGBluetoothAPIServer( 6118): [BTUI] onBind()
D/BluetoothMapMasInstance( 6118): MAS initSocket()
,D/BluetoothMapMasInstance( 6118):   masId = 00
D/BluetoothMapMasInstance( 6118):   msgTypes = 0e
D/BluetoothMapMasInstance( 6118):   masName = SMS/MMS
D/BluetoothMapMasInstance( 6118):   SDP string = 000eSMS/MMS
I/LGBluetoothAPIService( 1961): [BTUI] LGBluetoothAPIService Binding Success
D/BluetoothManagerService( 1029): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/LGBluetoothAPIService( 1961): [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
D/LGBluetoothAPIService( 1961): Message: 100
D/LGBluetoothAPIService( 1961): MESSAGE_BLUETOOTH_SERVICE_CONNECTED
W/BluetoothAdapter( 6118): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 6118): [BTUI] createSocketChannel FD=73 mFd=0
V/BluetoothMapMasInstance( 6118): Succeed to create listening socket 
D/BluetoothMapMasInstance( 6118): Accepting socket connection...
D/BluetoothAdapterProperties( 6118): Scan Mode:21
D/LGBluetoothDeviceModeControllManager( 6118): getDeviceMode  deviceMode 0
W/ContextImpl( 6150): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,D/BluetoothAdapterService( 6118): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1671901a
V/BluetoothPbapService( 6118): Pbap Service onCreate
V/BluetoothPbapService( 6118): Starting PBAP service
D/LGBluetoothPbapAdapter( 6118): [BTUI] getInstance : create
V/BluetoothPbapService( 6118): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 6118): state: 12
V/BluetoothPbapReceiver( 6118): PbapReceiver onReceive 
D/LocalBluetoothProfileManager( 6150): Adding local A2DP profile
V/BluetoothPbapReceiver( 6118): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6118): ***********state = 12
V/BluetoothPbapService( 6118): Handler(): got msg=1
V/BluetoothPbapService( 6118): Pbap Service startRfcommSocketListener
V/BluetoothPbapService( 6118): Pbap Service initSocket
D/BluetoothManagerService( 1029): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6118): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 6118): [BTUI] createSocketChannel FD=75 mFd=73
V/BluetoothPbapService( 6118): Succeed to create listening socket 
V/BluetoothPbapService( 6118): Accepting socket connection...
D/BluetoothManagerService( 1029): Message: 30
D/LocalBluetoothProfileManager( 6150): Adding local HEADSET profile
,D/BluetoothManagerService( 1029): Message: 30
D/BluetoothManagerService( 1029): Message: 30
D/BluetoothManagerService( 1029): Message: 30
D/LocalBluetoothProfileManager( 6150): Adding local MAP profile
D/BluetoothMap( 6150): Create BluetoothMap proxy object
D/BluetoothManagerService( 1029): Message: 30
D/BluetoothManagerService( 1029): Message: 30
,V/BluetoothPbapService( 6118): Pbap Service onBind
D/LocalBluetoothProfileManager( 6150): LocalBluetoothProfileManager construction complete
D/LGBluetoothUserBindClient( 6150): [BTUI] initUserBindClient
W/ContextImpl( 6150): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
D/DockEventReceiver( 6150): finishStartingService: stopping service
D/BluetoothA2dp( 6150): Proxy object connected
D/A2dpProfile( 6150): Bluetooth service connected
,D/BluetoothHeadset( 6150): Proxy object connected
,D/HeadsetProfile( 6150): Bluetooth service connected
D/BluetoothInputDevice( 6150): Proxy object connected
D/HidProfile( 6150): Bluetooth service connected
D/BluetoothPan( 6150): BluetoothPAN Proxy object connected
D/PanProfile( 6150): Bluetooth service connected
D/BluetoothMap( 6150): Proxy object connected
D/MapProfile( 6150): Bluetooth service connected
D/BluetoothMap( 6150): getConnectedDevices()
V/BluetoothMapService( 6118): getConnectedDevices()
D/BluetoothPbap( 6150): Proxy object connected
D/PbapServerProfile( 6150): Bluetooth service connected
D/LGBluetoothUserBindClient( 6150): [BTUI] onServiceConnected
D/BluetoothPermissionRequest( 6150): onReceive
D/LGBluetoothFeatureConfig( 6150): isPrivacyLogsEnabled : true
D/LGBluetoothUtils( 6150): [BTUI] FileNotFound: readProperty
D/LGBluetoothResetSettingReceiver( 6150): return without doing reset settings.
,V/BluetoothOppReceiver( 6118): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
I/LGBluetoothOppAdapter( 6118): [BTUI] startOppService()
V/BluetoothOppManager( 6118): restoreApplicationData! falsefalsenullnull
D/LGBluetoothFeatureConfig( 6118): isPrivacyLogsEnabled : true
V/BtOppService( 6118): onCreate
,V/BluetoothOppNotification( 6118): send message
,V/BtOppService( 6118): Starting RfcommListener
D/BluetoothOppPreference( 6118): Dumping Names:  
D/BluetoothOppPreference( 6118): {}
D/BluetoothOppPreference( 6118): Dumping Channels:  
D/BluetoothOppPreference( 6118): {}
V/BtOppService( 6118): onStartCommand
V/BluetoothFtpReceiver( 6118): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpReceiver( 6118): BluetoothFtpReceiver Start Service
V/BluetoothOppNotification( 6118): new notify threadi!
V/BtOppService( 6118): pendingUpdate is true keepUpdateThread is false sListenStarted is true
V/BluetoothOppNotification( 6118): send delay message
,V/BtOppService( 6118): start RfcommListener
V/BtOppService( 6118): Deleted complete outbound shares, number =  0
V/BtOppService( 6118): Deleted complete inbound failed shares, number = 0
V/BtOppService( 6118): RfcommListener started
,V/BluetoothOppProvider( 6118): starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
V/BtOppRfcommListener( 6118): Starting RFCOMM listener....
D/BluetoothManagerService( 1029): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
V/BluetoothOppProvider( 6118): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6118): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
W/BluetoothAdapter( 6118): getBluetoothService() called with no BluetoothManagerCallback
V/BluetoothOppProvider( 6118): created cursor android.database.sqlite.SQLiteCursor@2d8df264 on behalf of 
D/LGBluetoothServiceAdapter( 6118): [BTUI] createSocketChannel FD=79 mFd=75
V/BtOppRfcommListener( 6118): Started RFCOMM listener....
I/BtOppRfcommListener( 6118): Accept thread started.
V/BtOppRfcommListener( 6118): Accepting connection...
V/BluetoothOppProvider( 6118): created cursor android.database.sqlite.SQLiteCursor@2a2dccd on behalf of 
V/BluetoothOppNotification( 6118): mUpdateCompleteNotification = true
V/BluetoothOppProvider( 6118): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 6118): created cursor android.database.sqlite.SQLiteCursor@122ca982 on behalf of 
V/BluetoothOppProvider( 6118): created cursor android.database.sqlite.SQLiteCursor@3535f893 on behalf of 
V/BluetoothOppNotification( 6118): outbound: succ-0  fail-0
V/BtOppService( 6118): pendingUpdate is false keepUpdateThread is false sListenStarted is true
V/BluetoothOppNotification( 6118): outbound notification was removed.
V/BluetoothOppProvider( 6118): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 6118): created cursor android.database.sqlite.SQLiteCursor@2e69d0d0 on behalf of 
V/BluetoothOppNotification( 6118): inbound: succ-0  fail-0
,V/BluetoothOppNotification( 6118): inbound notification was removed.
V/BluetoothOppProvider( 6118): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6118): created cursor android.database.sqlite.SQLiteCursor@118d78c9 on behalf of 
D/BluetoothAdapterService( 6118): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1671901a
V/BluetoothFtpService( 6118): Ftp Service onCreate
I/BluetoothFtpService( 6118): Ftp Service onCreate
V/BluetoothFtpService( 6118): Ftp Service onStartCommand
V/BluetoothFtpService( 6118): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpService( 6118): Starting Listening on sockets
V/BluetoothSapReceiver( 6118): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 6118): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 6118): SapReceiver onReceive 
V/BluetoothSapReceiver( 6118): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6118):  Bluetooth Adapter state = 12
V/BluetoothSapReceiver( 6118): Calling SAP service start service with action = null
V/BtOppService( 6118): ContentObserver received notification
V/BtOppService( 6118): ContentObserver received notification
V/BluetoothFtpService( 6118): Handler(): got msg=1
V/BluetoothFtpService( 6118): Ftp Service startRfcommSocketListener
V/BluetoothFtpService( 6118): Ftp Service initSocket
V/BtOppService( 6118): pendingUpdate is true keepUpdateThread is false sListenStarted is true
V/BluetoothOppProvider( 6118): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6118): created cursor android.database.sqlite.SQLiteCursor@22bd8aef on behalf of 
V/BluetoothOppNotification( 6118): update too frequent, put in queue
V/BtOppService( 6118): pendingUpdate is false keepUpdateThread is false sListenStarted is true
D/AuthorizationBluetoothService( 2126): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/BluetoothManagerService( 1029): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6118): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 6118): [BTUI] createSocketChannel FD=80 mFd=79
V/BluetoothFtpService( 6118): Succeed to create listening socket on channel 20
,V/BluetoothFtpService:RfcommSocketAcceptThread( 6118): Run Accept thread
D/BluetoothAdapterService( 6118): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1671901a
,V/BluetoothSapService( 6118): Sap Service onCreate
V/BluetoothSapService( 6118): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 6118): state: 12
V/BluetoothSapService( 6118): Starting SAP server process
V/BluetoothSapService( 6118): SAP Service startRfcommListenerThread
,V/BluetoothSapService( 6118): Sap Service initRfcommSocket
D/BluetoothManagerService( 1029): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6118): getBluetoothService() called with no BluetoothManagerCallback
W/sapd    ( 6362): type=1400 audit(0.0:161): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/sapd    ( 6362): type=1400 audit(0.0:162): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
V/BT_SAP  ( 6362): Event pipe created
V/BT_SAP  ( 6362): create_server_socket qcom.sap.server
V/BT_SAP  ( 6362): created socket fd 6
,D/LGBluetoothServiceAdapter( 6118): [BTUI] createSocketChannel FD=82 mFd=80
V/BluetoothSapService( 6118): Succeed to create listening socket 
V/BluetoothSapService( 6118): Accepting socket connection...
E/wpa_supplicant( 6173): USIM:  scard_init function
I/wpa_supplicant( 6173): Trying to associate with SSID 'NG700'
,E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=14 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1029): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1029): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=15 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1029): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1029): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=16 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1029):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1029):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1029):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1029):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
D/WifiNative-wlan0( 1029): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1029):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 16 0 rt=111088  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
I/StatusBar.NetworkController( 1454): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1454): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1454): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1029): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1029): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1029): NETWORK_STATE_CHANGED_ACTION [SCANNING]
E/WifiStateMachine( 1029):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 16 0 rt=111105  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
W/Settings( 1029): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1029): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1029): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/WifiServerServiceExt( 1029): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1029): setSupplicantStateASSOCIATING
I/StatusBar.NetworkController( 1454): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1454): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1454): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WiFiOffLoadBroadcast( 6150): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
D/WiFiOffLoadBroadcast( 6150): Not supported operator for automatic switch
D/PostponalbeReceiver( 5146): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6150): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6150): MCCMNC not supported: null
D/QRemote ( 5980): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 5980): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 5980): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 5146): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6150): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6150): MCCMNC not supported: null
D/QRemote ( 5980): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 5980): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 5980): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
V/BluetoothOppNotification( 6118): new notify threadi!
V/BluetoothOppNotification( 6118): send delay message
,V/BluetoothOppProvider( 6118): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6118): created cursor android.database.sqlite.SQLiteCursor@2081e70b on behalf of 
V/BluetoothOppNotification( 6118): mUpdateCompleteNotification = true
V/BluetoothOppProvider( 6118): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 6118): created cursor android.database.sqlite.SQLiteCursor@2936e9e8 on behalf of 
V/BluetoothOppNotification( 6118): outbound: succ-0  fail-0
,V/BluetoothOppNotification( 6118): outbound notification was removed.
V/BluetoothOppProvider( 6118): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
I/art     ( 1029): Explicit concurrent mark sweep GC freed 47419(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 3.093ms total 151.754ms
,V/BluetoothOppProvider( 6118): created cursor android.database.sqlite.SQLiteCursor@19167801 on behalf of 
V/BluetoothOppNotification( 6118): inbound: succ-0  fail-0
V/BluetoothOppNotification( 6118): inbound notification was removed.
V/BluetoothOppProvider( 6118): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6118): created cursor android.database.sqlite.SQLiteCursor@18e796a6 on behalf of 
I/ThermalEngine(  337): Thermal-Server: Thermal received msg from  override
,I/Thermal-Lib( 3070): Thermal-Lib-Client: Client request sent
I/jxcore-log( 6055): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 6055): 
,I/jxcore-log( 6055): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 6055): 
,I/jxcore-log( 6055): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 6055): 
,I/jxcore-log( 6055): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 6055): 
I/jxcore-log( 6055): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 6055): 
,I/jxcore-log( 6055): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 6055): 
,I/jxcore-log( 6055): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 6055): 
I/jxcore-log( 6055): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 6055): 
I/wpa_supplicant( 6173): wlan0: CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1
D/WifiMonitor( 1029): Event [IFNAME=wlan0 CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1]
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=17 dispatchEvent: CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1
D/WifiMonitor( 1029): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=18 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=00:00:00:00:00:00 SSID=NG700
,E/WifiStateMachine( 1029):  DisconnectedState ASSOCIATION_REJECTION_EVENT 17 1 c0:ff:d4:d3:aa:48 blacklist=false rt=113379
,E/WifiStateMachine( 1029):  ConnectModeState ASSOCIATION_REJECTION_EVENT 17 1 c0:ff:d4:d3:aa:48 blacklist=false rt=113379
E/WifiStateMachine( 1029):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=113379  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: DISCONNECTED
I/StatusBar.NetworkController( 1454): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1454): mWifiConnected = false, mWifiLevel = 0
D/WifiHS20( 1029): hidePasspointNotification off =false
W/Settings( 1029): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1029): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed( 1029): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/StatusBar.NetworkController( 1454): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1029):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=113386  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: DISCONNECTED
D/WifiServerServiceExt( 1029): SUPPLICANT_STATE_CHANGED_ACTION
,D/WifiServerServiceExt( 1029): setSupplicantStateDISCONNECTED
D/PostponalbeReceiver( 5146): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 6229): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6229): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6229): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6150): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6150): MCCMNC not supported: null
D/QRemote ( 5980): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 5980): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 5980): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/WifiMonitor( 1029): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=19 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
I/wpa_supplicant( 6173): wlan0: CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine( 1029):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=113476  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/WifiMonitor( 1029): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1029): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1029): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,I/StatusBar.NetworkController( 1454): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/StatusBar.NetworkController( 1454): mWifiConnected = false, mWifiLevel = 0
D/WifiHS20( 1029): hidePasspointNotification off =false
,W/Settings( 1029): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1029): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1029): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/StatusBar.NetworkController( 1454): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1029):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=113484  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/PostponalbeReceiver( 5146): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/Settings( 1029): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/StatusBar.NetworkController( 1454): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/Settings( 1029): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/StatusBar.NetworkController( 1454): mWifiConnected = false, mWifiLevel = 0
D/WifiOffDelayIfNotUsed( 1029): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WifiServerServiceExt( 1029): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1029): setSupplicantStateSCANNING
D/StatusBar.NetworkController( 1454): refreshViews: Data not connected!! Set no data type icon / Roaming
I/PCSuite ( 6229): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6229): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6229): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6150): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6150): MCCMNC not supported: null
,D/QRemote ( 5980): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 5980): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 5980): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 5146): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6150): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6150): MCCMNC not supported: null
D/QRemote ( 5980): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 5980): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 5980): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
I/CloudHub( 2228): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19987
,I/wpa_supplicant( 6173): Trying to associate with SSID 'NG700'
,E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1029): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1029): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=22 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1029): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1029): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1029):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 dur:2155 bcn=0
E/WifiStateMachine( 1029):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 dur:2155 bcn=0
E/WifiStateMachine( 1029):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 dur:2155 bcn=0
E/WifiStateMachine( 1029):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 dur:2155 bcn=0
D/WifiNative-wlan0( 1029): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1029):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=115587  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,I/StatusBar.NetworkController( 1454): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1454): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1454): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1029): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1029): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1029): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/StatusBar.NetworkController( 1454): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1454): mWifiConnected = false, mWifiLevel = 0
D/PostponalbeReceiver( 5146): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,W/Settings( 1029): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1029): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1029): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/StatusBar.NetworkController( 1454): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1029):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=115607  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
D/WifiServerServiceExt( 1029): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1029): setSupplicantStateASSOCIATING
,V/WiFiOffLoadBroadcast( 6150): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6150): MCCMNC not supported: null
D/QRemote ( 5980): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 5980): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 5980): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 5146): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6150): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6150): MCCMNC not supported: null
D/QRemote ( 5980): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 5980): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 5980): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/Tethering( 1029): sendTetherStateChangedBroadcast 1, 0, 0
,I/wpa_supplicant( 6173): wlan0: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1029): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1029): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=25 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1029): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/libc-netbsd(  318): default dns: query_ipv6=0, query_ipv4=0
E/WifiStateMachine( 1029):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1029):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1029):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1029):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1029):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1029):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=115718  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1029):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=115718  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1029):  DisconnectedState CMD_ASSOCIATED_BSSID 25 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=115718
E/WifiStateMachine( 1029):  ConnectModeState CMD_ASSOCIATED_BSSID 25 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=115719
D/DSQN    ( 1029): DNSproblemNotiEnabled is disabled ignore DNS fail CB
E/WifiStateMachine( 1029):  DriverStartedState CMD_ASSOCIATED_BSSID 25 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=115719
E/WifiStateMachine( 1029):  SupplicantStartedState CMD_ASSOCIATED_BSSID 25 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=115719
E/WifiStateMachine( 1029):  DefaultState CMD_ASSOCIATED_BSSID 25 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=115719
E/WifiStateMachine( 1029):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=115719  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
I/wpa_supplicant( 6173): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 6173): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1029): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1029): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=28 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1029): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1029): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1029): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1029): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1029):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=115723  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
D/UsbSettingsReceiver( 6150): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettings,Receiver( 6150): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6150): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6150): [AUTORUN] persist.sys.usb.config = ptp_only,adb
W/Settings( 1029): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1029): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1029): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,I/StatusBar.NetworkController( 1454): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1454): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1029): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1029): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1029): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
E/WifiStateMachine( 1029):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=115726  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1029):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=115727  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1029):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=115727
E/WifiStateMachine( 1029):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=115727
D/WifiNative-wlan0( 1029): doString: [STATUS]
D/WifiMonitor( 1029): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiServerServiceExt( 1029): SUPPLICANT_STATE_CHANGED_ACTION
D/StatusBar.NetworkController( 1454): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiServerServiceExt( 1029): setSupplicantStateASSOCIATED
D/WifiNative-wlan0( 1029):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
I/StatusBar.NetworkController( 1454): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1454): mWifiConnected = false, mWifiLevel = 0
D/UsbSettingsReceiver( 6150): [AUTORUN] onReceive() : app userid = 0, current userid = 0
I/WifiServiceExtension( 1029): setVHTCapabilityType  : false
D/StatusBar.NetworkController( 1454): refreshViews: Data not connected!! Set no data type icon / Roaming
D/UsbSettingsControl( 6150): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6150): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6150): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6150): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6150): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6150): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 6150): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 5146): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/WifiServerServiceExt( 1029): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1029): setKeepAlivePacketInterval msec : 60
I/StatusBar.NetworkController( 1454): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1454): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1029): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1029): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1029): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/StatusBar.NetworkController( 1454): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1029): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1029): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1029): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/StatusBar.NetworkController( 1454): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1454): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1454): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WiFiOffLoadBroadcast( 6150): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/ConnectivityService( 1029): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService( 1029): Got NetworkAgent Messenger
D/ConnectivityService( 1029): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1029): NetworkAgent connected
E/WifiConfigStore( 1029): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1029): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1029): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1029): doBoolean: SAVE_CONFIG
D/WiFiOffLoadBroadcast( 6150): MCCMNC not supported: null
D/WifiNative-wlan0( 1029): SAVE_CONFIG: returned true
E/WifiConfigStore( 1029): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1029): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1029): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1029): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1029): SAVE_CONFIG: returned true
D/CommandListener(  318): Setting iface cfg
,D/QRemote ( 5980): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 5980): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 5980): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 5146): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/DhcpStateMachine( 1029): StoppedState
E/WifiStateMachine( 1029): Start Dhcp Watchdog 1
D/DhcpStateMachine( 1029): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1029): WaitBeforeStartState
E/WifiStateMachine( 1029):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=115775  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1029):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=115776  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1029):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=115776  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WifiServerServiceExt( 1029): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1029): setSupplicantStateFOUR_WAY_HANDSHAKE
V/WiFiOffLoadBroadcast( 6150): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WifiServerServiceExt( 1029): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1029): setSupplicantStateGROUP_HANDSHAKE
,E/WifiStateMachine( 1029):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 31 0 rt=115779  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1029):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 31 0 rt=115779  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1029):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 31 0 rt=115780  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1029):  ObtainingIpState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:6851] from screen [on:0 period:-1579042846]
D/WiFiOffLoadBroadcast( 6150): MCCMNC not supported: null
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:-1579042846]
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
D/StatusBar.NetworkController( 1454): refreshViews: Data not connected!! Set no data type icon / Roaming
D/QRemote ( 5980): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 5980): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 5980): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 5146): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/ConnectivityService( 1029): updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
E/WifiStateMachine( 1029):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1029):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1029):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1029):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 1029):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1029): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
E/WifiStateMachine( 1029):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
D/WifiNative-wlan0( 1029): doBoolean: DRIVER SETSUSPENDMODE 0
V/WiFiOffLoadBroadcast( 6150): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6150): MCCMNC not supported: null
D/QRemote ( 5980): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 5980): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 5980): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 5146): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 6150): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6150): MCCMNC not supported: null
D/QRemote ( 5980): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 5980): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 5980): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/wpa_supplicant( 6173): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1029): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1029): doBoolean: SET ps 0
D/WifiNative-wlan0( 1029): SET ps 0: returned true
D/WifiNative-wlan0( 1029): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 6173): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
,D/WifiNative-wlan0( 1029): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1029): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
D/LGWifiP2pService( 1029): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@18825280 target=com.android.internal.util.StateMachine$SmHandler }
V/DhcpStateMachine( 1029): Current State is mWaitBeforeStartState.
D/LGWifiP2pService( 1029): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@18825280 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1029): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper( 1029): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
V/LgDhcpStateMachineHelper( 1029): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700" is not exist.
D/DhcpStateMachine( 1029): DHCP Start wake lock is acquired.
D/WifiServerServiceExt( 1029): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1029): setSupplicantStateCOMPLETED
D/WifiServerServiceExt( 1029): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1029): setSupplicantStateCOMPLETED
D/DhcpStateMachine( 1029): DHCPV4 request on wlan0
,V/LgDhcpStateMachineHelper( 1029): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1029): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
W/dhcpcd  ( 6421): type=1400 audit(0.0:163): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 6421): type=1400 audit(0.0:164): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,I/dhcpcd  ( 6421): version 5.5.6 starting
E/dhcpcd  ( 6421): get_duid: m
,D/dhcpcd  ( 6421): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 6421): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
D/dhcpcd  ( 6421): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 6421): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 6421): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,I/dhcpcd  ( 6421): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 6421): wlan0: sending REQUEST (xid 0x5dfaf799), next in 4.99 seconds
E/WifiStateMachine( 1029):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1029):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1029):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 1029):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 1029):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1029): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 117640667928; DSPS: 3995774; Offset : -4312876711
,I/dhcpcd  ( 6421): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
,I/dhcpcd  ( 6421): wlan0: leased 192.168.1.141 for 86400 seconds
,D/dhcpcd  ( 6421): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 6421): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 6421): wlan0: adding default route via 192.168.1.1
,E/WifiStateMachine( 1029):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
D/dhcpcd  ( 6421): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
E/WifiStateMachine( 1029):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1029):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
D/dhcpcd  ( 6421): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
E/WifiStateMachine( 1029):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/dhcpcd  ( 6421): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 6421): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
E/WifiStateMachine( 1029):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1029):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1029): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
,D/DhcpStateMachine( 1029): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper( 1029): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1029): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1029): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1029): Add DhcpResults: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
V/DhcpStateMachine( 1029): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1029): bShouldSendDhcpAction Result: true
D/DhcpStateMachine( 1029): DHCP Start/Renew wake lock is released.
E/WifiStateMachine( 1029):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine( 1029):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/WifiNative-wlan0( 1029): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 6173): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1029): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1029): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 6173): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1029): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1029): doBoolean: SET ps 1
,D/LGWifiP2pService( 1029): InactiveState{ when=-7ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): P2pEnabledState{ when=-8ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1029): SET ps 1: returned true
E/WifiStateMachine( 1029):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1029): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
E/WifiStateMachine( 1029): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/ConnectivityService( 1029): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
D/ConnectivityService( 1029): ignoring duplicate network state non-change
,D/ConnectivityService( 1029): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService( 1029): Adding iface wlan0 to network 100
D/DhcpStateMachine( 1029): RunningState
I/StatusBar.NetworkController( 1454): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1454): mWifiConnected = false, mWifiLevel = 0
,E/ConnectivityService( 1029): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1029): Adding Route [fe80::/64 -> :: wlan0] to network 100
D/ConnectivityService( 1029): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
D/ConnectivityService( 1029): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,D/ConnectivityService( 1029): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1029): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 100
D/ConnectivityService( 1029): Setting Dns servers for network 100 to [/192.168.1.1]
D/StatusBar.NetworkController( 1454): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1029): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1029): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1029): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/StatusBar.NetworkController( 1454): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1454): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1454): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1029): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1029): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1029): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/WifiHS20( 1029): [PASSPOINT] passpointNotification: hs20AP list is checked
V/WfdStateTracker( 1961): handleWifiStateChangedEvent: 1
I/StatusBar.NetworkController( 1454): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1454): mWifiConnected = true, mWifiLevel = 2
,D/StatusBar.NetworkController( 1454): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1029): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1029): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1029): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20( 1029): [PASSPOINT] passpointNotification: hs20AP list is checked
,W/Settings( 1029): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1029): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
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
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1029): DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1029): Connected
D/TelephonyNetworkFactory-1( 1868): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1029): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/TelephonyNetworkFactory-1( 1868):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1029): Checking http://clients3.google.com/generate_204 on "NG700"
D/PostponalbeReceiver( 5146): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WIFI    ( 1029): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1029):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1029): Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
,I/StatusBar.NetworkController( 1454): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1454): mWifiConnected = true, mWifiLevel = 2
D/StatusBar.NetworkController( 1454): refreshViews: Data not connected!! Set no data type icon / Roaming
E/ConnectivityService( 1029): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1029): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1029): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/libc-netbsd(  318): res_queryN name = clients3.google.com, class = 1, type = 28
D/ConnectivityService( 1029): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
,D/CSLegacyTypeTracker( 1029): [e] list.add(nai) empty : false size: 1
D/ConnectivityService( 1029): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/LocSvc_java( 1029): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1029): getAGpsConnectionInfo connType - 4
D/ConnectivityService( 1029): validation of new default Network = false
D/ConnectivityService( 1029): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1029): enableDataServiceNotify 
D/DSQN    ( 1029): start dsqn bin
D/LocSvc_java( 1029): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1029): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java( 1029): Sending msg: 5 arg1:0 arg2:1
D/libc-netbsd(  318): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  318): res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
D/ConnectivityService( 1029): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1029):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1029):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1029): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1454): CM callback handler got msg 524290
W/dsqn    ( 6469): type=1400 audit(0.0:165): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 6469): type=1400 audit(0.0:166): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6828 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,D/libc-netbsd(  318): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  318): res_queryN name = europe.pool.ntp.org, class = 1, type = 1
V/WiFiOffLoadBroadcast( 6150): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/TelephonyIcons( 1454): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1454): refreshViews: Data not connected!! Set no data type icon / Roaming
E/DSQN    ( 6469): DSQN ssw
D/StatusBar.NetworkController( 1454): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WiFiOffLoadBroadcast( 6150): MCCMNC not supported: null
D/QRemote ( 5980): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 5980): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 5980): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 5146): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6150): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/libc-netbsd(  318): res_queryN name = clients3.google.com, class = 1, type = 1
D/WiFiOffLoadBroadcast( 6150): MCCMNC not supported: null
D/QRemote ( 5980): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 5980): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 5980): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/libc-netbsd(  318): res_queryN name = 2.android.pool.ntp.org succeed
D/PostponalbeReceiver( 5146): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/libc-netbsd(  318): res_queryN name = europe.pool.ntp.org succeed
I/PCSuite ( 6229): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6229): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6150): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6150): MCCMNC not supported: null
D/libc-netbsd(  318): res_queryN name = clients3.google.com succeed
,D/QRemote ( 5980): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 5980): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 5980): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 5980): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 5980): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 5146): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,D/LGDataListener(  318): argv[0]=dsqncommand
D/LGDataListener(  318): argv[1]=wlan0
D/LGDataListener(  318): argv[2]=1
D/LGDataListener(  318): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1029): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1029): start to monitor internet connection
V/NetworkPolicy( 1029): [LG_RESTRICTED] checkMobilePolicy_type()
I/jxcore-log( 6055): Test app app.js loaded
I/jxcore-log( 6055): 
I/PCSuite ( 6229): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6229): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
D/LocSvc_java( 1029): NTP server : europe.pool.ntp.org
D/LocSvc_java( 1029): NTP server returned: 1454414872377 (Tue Feb 02 13:07:52 GMT+01:00 2016) reference: 118514 certainty: 22 system time offset: -854
,D/LocSvc_java( 1029): Sending msg: 10 arg1:0 arg2:1
V/WiFiOffLoadBroadcast( 6150): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6055): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6055): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6055): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6055): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6055): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6055): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6055): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6055): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6055): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6055): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30337e1a added. We now have 1 listener(s)
I/jxcore-log( 6055): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 6055): 
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1029): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 02 Feb 2016 12:07:52 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454414873239], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454414873220]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1029): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1029): Validated
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
D/ConnectivityManager.CallbackHandler( 1454): CM callback handler got msg 524290
D/WIFI    ( 1029): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/chromium( 6055): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/WIFI    ( 1029):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1868): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1868):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DU,N&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/WiFiOffLoadBroadcast( 6150): MCCMNC not supported: null
,D/QRemote ( 5980): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 5980): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 5980): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 5980): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 5980): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/TelephonyIcons( 1454): null signal icon name: drawable/stat_sys_signal_null
,D/StatusBar.NetworkController( 1454): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/StatusBar.NetworkController( 1454): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1579039838] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1579039834] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
D/StatusBar.NetworkController( 1454): refreshViews: Data not connected!! Set no data type icon / Roaming
,V/WifiInternetCheck( 1029): Single check msg out of sync, ignoring.
,D/ConnectivityService( 1029): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1029): MasterInitialState.processMessage what=3
D/AlarmManagerService( 1029): Setting time of day to sec=1454414875
,W/AlarmManagerService( 1029): Unable to set rtc to 1454414875: Invalid argument
D/KeyguardUpdateMonitor( 1454): handleTimeUpdate
,I/SecureClockService( 1961): Intent.ACTION_TIME_CHANGED 
I/[SystemUI]Clock( 1454): onReceive = android.intent.action.TIME_SET
D/LIA_Informant_Tips_DateChangeManager( 2720): onReceive() : ACTION_TIME_CHANGED
,I/LIA_Informant_Tips_LogTracer( 2720): [Log Tracer - Schedule Transition] Time Change Event Received : 2016-02-02 13:07:55...... Request
I/LIA_Informant_Tips_LogTracer( 2720): [Log Tracer - Schedule Transition] UserGuide, DATE_UPDATE : working count : 6, total count : 163, new day : false...... Request
D/LIA_Informant_Tips_DateChangeManager( 2720): DateInfo : SmartTips Total Working Day Count = 163
D/LIA_Informant_Tips_DateChangeManager( 2720): DateInfo : UserGuide Working Duration Count = 6
D/LIA_Informant_Tips_DateChangeManager( 2720): DateInfo : Last Date Check Time = 2016-02-02 13:07:55
I/CalendarProvider2( 5402): onReceive() android.intent.action.TIME_SET
D/CalendarProvider2( 5402): Scheduling check of next Alarm
I/LgeClockWidgetControlView( 1454): time changed, timezoneChanged : false
,D/PostponalbeReceiver( 5146): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ActivityManager( 1029): getTasks: caller 10029 is using old GET_TASKS but privileged; allowing
,I/[LGHome]LGDateChangeReceiver( 2083): [LGDateChangeReceiver.java:78:updateCalendarShortcut()]date=2 currentDate=-1 dayofweek=3 currentDayOfWeek=-1
,I/[LGHome]LGCalendarIcon( 2083): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Tue date= 2
I/[LGHome]LGCalendarIcon( 2083): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Tue date= 2
,I/[LGHome]Launcher( 2083): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/NetworkMonitor( 5190): type=WIFI subType= reason=null isConnected=true
,W/ContextImpl( 5146): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/ActivityManager( 1029): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6505 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/[Concierge]Service( 2607): onStartCommand(). Type : 9
,I/AppUp4:AppBoxCP( 6505): onCreate
W/AppUp4:DB( 6505):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 6505):  setFingerPrint start
I/AppUp4:DB( 6505):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 6505):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 6505):  SDK version = 21
I/AppUp4:DB( 6505):  beforefinger == newfinger no write in DB
I/ActivityManager( 1029): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=6524 uid=10054 gids={50054, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/AppUp4:AppBoxApplication( 6505): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6505): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6505): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6505): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6505): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 6505): onReceive
,D/LgDataFeature( 6505): LgDataFeature() Constructor: none
D/LgDataFeature( 6505): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 6505): Context : android.app.ReceiverRestrictedContext@25575ec5
D/AppUp4:CustFacade( 6505): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6505): isPhone : true
D/AppUp4:CustModeStarterReceiver( 6505): begin check event
I/AppUp4:CustModeStarterReceiver( 6505): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6505): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
I/ActivityManager( 1029): Start proc com.android.gallery3d for service com.android.gallery3d/com.lge.gallery.picasa.PicasaService: pid=6544 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,D/AppUp4:CustModeStarterReceiver( 6505): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6505): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6505): handleAsyncCustNotification do not startCustService
,I/ActivityManager( 1029): Killing 5868:com.google.android.apps.docs/u0a61 (adj 15): empty #17
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=6.8, 0.0, 0.0  rx=5.5 bcn=0 [on:0 tx:0 rx:0 period:2149] from screen [on:0 period:-1579037673] gl rssi=-57 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=6.8, 0.0, 0.0  rx=5.5 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:-1579037673] gl rssi=-57 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,D/LGDMClient( 3250): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,W/libprocessgroup( 1029): failed to open /acct/uid_10061/pid_5868/cgroup.procs: No such file or directory
D/LGDMClient( 3250): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 3250): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 3250): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/StatusBar.NetworkController( 1454): refreshViews: Data not connected!! Set no data type icon / Roaming
V/DownloadManager( 3364): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3364): DownloadService onCreate
D/LGDMClient( 3250): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/LGDMClient( 3250): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/DownloadManager( 3364): in removeSpuriousFiles
V/DownloadManager( 3364): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3364): created cursor android.database.sqlite.SQLiteCursor@1391772b on behalf of 3364
I/DownloadManager( 3364): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3364): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3364): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3364): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3364): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3364): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3364): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3364): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3364): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3364): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3364): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/DownloadManager( 3364): in trimDatabase
V/DownloadManager( 3364): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3364): created cursor android.database.sqlite.SQLiteCursor@3d810788 on behalf of 3364
W/ResourcesManager( 6544): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6544): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/LGDMClient( 3250): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
W/ResourcesManager( 6544): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
D/LGDMClient( 3250): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
W/ResourcesManager( 6544): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,I/ActivityManager( 1029): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6568 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,V/DownloadManager( 3364): DownloadService onStartCommand
V/DownloadManager( 3364): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3364): created cursor android.database.sqlite.SQLiteCursor@122e5b07 on behalf of 3364
V/DownloadManager( 3364): processing inserted download 1
W/ContextImpl( 3250): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
,V/DownloadManager( 3364): processing inserted download 4
V/DownloadManager( 3364): processing inserted download 7
I/art     (  348): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 272us total 13.127ms
V/DownloadManager( 3364): processing inserted download 8
V/DownloadManager( 3364): processing inserted download 9
E/LGDMClient( 3250): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
V/DownloadManager( 3364): processing inserted download 10
D/LGDMClient( 3250): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 3250): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3364): processing inserted download 16
V/DownloadManager( 3364): processing inserted download 17
V/DownloadManager( 3364): processing inserted download 18
V/DownloadManager( 3364): processing inserted download 21
V/DownloadManager( 3364): processing inserted download 22
I/art     (  348): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 199us total 10.573ms
,I/art     (  348): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 205us total 9.942ms
I/ActivityManager( 1029): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=6586 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/DownloadManager( 3364): DownloadService onDestroy
D/GpsLocationProvider( 1029): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/AppConfig( 6544): Total System Memory = 2995761152
,D/SystemHelper( 6544): region [EU], country [EU], operator [OPEN], sub-operator []
,W/ResourcesManager( 6568): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6568): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6568): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6568): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/ReaderUtils( 6524): PortraitW 1440 LandscapeW 2392 SmallestSize 1340 LargestSize 2392 textZoom 4.4999995 isTablet false Memory 256
,I/art     ( 2126): Explicit concurrent mark sweep GC freed 18718(1033KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 30MB/62MB, paused 911us total 21.692ms
,I/LGEmail ( 6568): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,W/GAV2    ( 6524): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/LGEmail ( 6568): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
W/DriveInitializer( 2333): Background init thread started
I/BooksApp( 6524): Created application version: 3.2.35 (30235)
,W/ResourceType( 6568): No package identifier when getting value for resource number 0x00000000
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.gms/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 2333): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.gms/files
D/LgDataFeature( 6568): LgDataFeature() Constructor: none
D/LgDataFeature( 6568): LgDataFeature() Constructor Done, null
,D/GpsLocationProvider( 1029): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/DriveInitializer( 2333): Background init thread ended
E/GpsLocationProvider( 1029): No APN found to select.
I/BooksSync( 6524): Starting books sync
,D/DelayedSyncController( 6586): Delaying sync.
I/ActivityManager( 1029): Killing 5595:com.google.android.apps.plus/u0a97 (adj 15): empty #17
D/eas_req ( 6568): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,W/libprocessgroup( 1029): failed to open /acct/uid_10097/pid_5595/cgroup.procs: No such file or directory
,I/ActivityManager( 1029): Killing 5936:com.lge.eula/1000 (adj 15): empty #17
W/libprocessgroup( 1029): failed to open /acct/uid_1000/pid_5936/cgroup.procs: No such file or directory
,I/HubEmail( 6568): JNI_OnLoad()
I/HubEmail( 6568): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6568): registerNatives()
I/HubEmail( 6568): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6568): registerNativeMethods()
I/HubEmail( 6568): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6568): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,W/Settings( 6568): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/LgeMiscReceiver( 3303): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) },
I/LgeMiscReceiver( 3303): action = android.net.conn.CONNECTIVITY_CHANGE
W/Settings( 6568): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/LgeMiscReceiver( 3303): networkInfo.isConnected() = true
D/PhoneState( 3303): setPdpRejectCasuse : false
D/libc-netbsd(  318): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  318): res_queryN name = static-avc.lglime.com, class = 1, type = 1
I/ActivityManager( 1029): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6646 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,D/libc-netbsd(  318): res_queryN name = static-avc.lglime.com succeed
,D/BooksSync( 6524): started syncMyEbooks
E/Auth.Api.Credentials( 2333): [CredentialSyncAdapter] Unknown sync event.
,D/DrmBroadcastReceiver( 6646): Receive CONNECTIVITY_ACTION
,D/DrmBroadcastReceiver( 6646): 1  network is available. Sync DRM Time with NTP
,V/DrmService( 6646): Service onCreate
D/DrmService( 6646): Received new request = 2
I/DrmSntpClient( 6646): Start Sync process
,D/DrmSntpClient( 6646): Server : 0
,D/libc-netbsd(  318): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  318): res_queryN name = pool.ntp.org, class = 1, type = 1
V/FormManager( 6202): There are no updated forms. The schedule will be deleted.
,V/FormManager( 6202): Alarm would be updated, because LastCheckTime has been updated.
I/ActivityManager( 1029): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=6669 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1029): Killing 5363:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
,D/libc-netbsd(  318): res_queryN name = pool.ntp.org succeed
I/LGDrmClient( 6646): _DRM_ServiceGet() : Bind lgdrm service
,V/ILGDrmService(  330): eDRM_SetDRMTime +++
,I/LGDRM   (  330): [DRM] SET TIME : YR=2016, MON=2, DAY=2
I/LGDRM   (  330): [DRM] SET TIME : HR=12, MIN=7, SEC=56
D/libc-netbsd(  318): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  318): res_queryN name = www.google.com, class = 1, type = 1
V/ILGDrmService(  330): eDRM_SetDRMTime ---
I/DrmSntpClient( 6646): Synched
D/DrmService( 6646): Completed !! request = 2
D/DrmService( 6646): Request count = 0
W/libprocessgroup( 1029): failed to open /acct/uid_10005/pid_5363/cgroup.procs: No such file or directory
V/DrmService( 6646): Service onDestroy
V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 1029): Killing 5402:com.android.providers.calendar/u0a14 (adj 15): empty #17
,I/art     ( 6669): Almond Protected OAT
,D/libc-netbsd(  318): res_queryN name = www.google.com succeed
,D/libc-netbsd(  318): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  318): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  318): res_queryN name = clients3.google.com succeed
W/libprocessgroup( 1029): failed to open /acct/uid_10014/pid_5402/cgroup.procs: No such file or directory
,V/WifiInternetCheck( 1029): isHttpConnectionAvailable - We got a valid response : 204
D/WeatherApplication( 6669): removeAccount
D/WeatherApplication( 6669): Account.length = 0
E/WeatherApplication( 6669): OPERATOR:OPEN
D/WeatherAncestor( 6669): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:7:56
,D/Weather.Utils( 6669): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6669): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6669): 2 : This is isUpdating : false
D/WeatherAncestor( 6669): connectivity changed - connection : true
D/WeatherService( 6669): 2 : isServiceAlived():false forecastCache:null
I/GLSUser ( 2126): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2126): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2126): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2126): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ForecastDataCache( 6669): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 6669): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 6669): 2 : Cache is not up-to-date, count: 0
,D/Weather_cast( 6669): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 6669): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:7:56
,I/ActivityManager( 1029): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6692 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1029): Killing 2228:com.lge.music/u0a34 (adj 15): empty #17
V/AudioFlinger(  324): 2228 died, releasing its sessions
V/AudioFlinger(  324):  pid 1868 @ 0
V/AudioFlinger(  324):  pid 3303 @ 1
,V/AudioFlinger(  324):  pid 3303 @ 2
D/MediaSessionService( 1029): clear user.mLastMediaButtonReceiver
,W/libprocessgroup( 1029): failed to open /acct/uid_10034/pid_2228/cgroup.procs: No such file or directory
,I/art     ( 1029): Explicit concurrent mark sweep GC freed 66303(3MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 44MB/66MB, paused 1.639ms total 122.277ms
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6692): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6692): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,D/ZenLog  ( 1029): intercepted: 0|com.google.android.gms|1|null|10005,none
V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/GLSActivity( 2126): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2126): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2126): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2126): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2126): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2126): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2126): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6524): Authentication error
E/BooksAccountManager( 6524): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6524): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6524): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6524): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6524): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6524): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6524): null auth token
W/ContextImpl( 6692): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
W/ResourcesManager( 1454): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1454): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6692): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/ResourcesManager( 1411): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1411): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/libc-netbsd(  318): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  318): res_queryN name = www.googleapis.com, class = 1, type = 1
D/LgeQuickCoverNLService( 1411): onNotificationPosted
D/SmartCoverUpdateMonitor( 1411): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1411): MSG_NOTIFICATION_POSTED
,D/SmartCoverUpdateMonitor( 1411): handleNotificationPosted(true)
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
I/GLSUser ( 2126): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 2126): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2126): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2126): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1411): updateNotificationData: count=3
V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{2a2dccd V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,D/libc-netbsd(  318): res_queryN name = www.googleapis.com succeed
V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
,I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2126): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2126): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2126): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2126): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2126): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2126): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2126): 	at android.os.Binder.execTransact(Binder.java:446)
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
D/LgeQuickCoverNotificationData( 1411): isNotificationFor,CurrentUser : true
E/LgeQuickCoverOverlayWindow( 1411): updateNotificationData: count=3
,D/SyncManager( 1029): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 26771, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager( 1029): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 156014, reason: 10019
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{2a2dccd V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/DelayedSyncController( 6586): Delaying sync.
I/WebViewFactory( 6692): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 6692): Loading: webviewchromium
,I/LibraryLoader( 6692): Time to load native libraries: 4 ms (timestamps 3242-3246)
,I/LibraryLoader( 6692): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6692): Binding Chromium to main looper Looper (main, tid 1) {31712204}
I/LibraryLoader( 6692): Expected native library version number "",actual native library version number ""
I/chromium( 6692): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6692): Initializing chromium process, renderers=0
,W/art     ( 6692): Attempt to remove local handle scope entry from IRT, ignoring
V/AudioPolicyService(  324): registerClient() client 0xb558a420, uid 10093
,W/chromium( 6692): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
W/AudioManagerAndroid( 6692): Requires BLUETOOTH permission
I/chromium( 6692): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 6692): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
I/Adreno-EGL( 6692): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6692): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6692): Build Date: 12/12/14 금
I/Adreno-EGL( 6692): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6692): Remote Branch: 
I/Adreno-EGL( 6692): Local Patches: 
I/Adreno-EGL( 6692): Reconstruct Branch: 
,W/ApiaryClient( 6524): Error response from books API: {
W/ApiaryClient( 6524):  "error": {
W/ApiaryClient( 6524):   "errors": [
W/ApiaryClient( 6524):    {
W/ApiaryClient( 6524):     "domain": "global",
W/ApiaryClient( 6524):     "reason": "required",
W/ApiaryClient( 6524):     "message": "Login Required",
W/ApiaryClient( 6524):     "locationType": "header",
W/ApiaryClient( 6524):     "location": "Authorization"
W/ApiaryClient( 6524):    }
W/ApiaryClient( 6524):   ],
W/ApiaryClient( 6524):   "code": 401,
W/ApiaryClient( 6524):   "message": "Login Required"
W/ApiaryClient( 6524):  }
W/ApiaryClient( 6524): }
,W/ApiaryClient( 6524): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6524): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-8684895916163472261&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6524): Headers:
W/ApiaryClient( 6524): accept-encoding: [gzip]
W/ApiaryClient( 6524): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6524): gdata-version: 2
,I/NSApplication( 6692): Starting up...
,I/ActivityManager( 1029): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6763 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1029): Killing 4852:com.android.vending/u0a44 (adj 15): empty #17
W/libprocessgroup( 1029): failed to open /acct/uid_10044/pid_4852/cgroup.procs: No such file or directory
,W/ResourcesManager( 6763): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/GLSActivity( 2126): [ac] getting account id
D/libc-netbsd(  318): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  318): res_queryN name = mtalk.google.com, class = 1, type = 1
,I/GLSUser ( 2126): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
I/iu.SyncManager( 2333): SYNC; picasa accounts
,D/NetworkLogImpl( 2333): Loaded NetworkSpeedPredictor
,D/libc-netbsd(  318): res_queryN name = mtalk.google.com succeed
I/iu.Environment( 2333): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/iu.UploadsManager( 2333): num queued entries: 0
,I/iu.UploadsManager( 2333): num updated entries: 0
I/iu.SyncManager( 2333): NEXT; no task
D/ChimeraCfgMgr( 2333): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/ChimeraCfgMgr( 2333): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PostponalbeReceiver( 5146): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.TIME_SET'.
,I/GLSUser ( 2126): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2126): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2126): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2126): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/ActivityManager( 1029): Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=6817 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1411): onNotificationPosted
D/SmartCoverUpdateMonitor( 1411): received broadcast com.lge.intent.action.NLDataPosted
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
W/Kids    ( 2333): [AccountUtils] Account not ready
W/Kids    ( 2333): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2333): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2333): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2333): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2333): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2333): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2333): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2333): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2333): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2333): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2333): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2333): 	at java.lang.Thread.run(Thread.java:818)
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{2a2dccd V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/ALBootInit( 6817): ====action==>android.intent.action.TIME_SET
,D/ALBootInit( 6817): Alarm ALBootInit: TIME_SET
D/Alarms  ( 6817): [setNextAlert] start
D/GCM     ( 2126): Connected
,D/Alarms  ( 6817): [setNextAlert] (1)
,D/Alarms  ( 6817):  minTime  = 0
D/Alarms  ( 6817):  -- OK multi -- 0
E/jeny.kim( 6817): [setNextAlert] setNextAlert  temp_Alarmlink + 
E/jeny.kim( 6817): [setNextAlert]setNextAlert temp_AlarmLinkText + 
D/GCM     ( 2126): Message class com.google.f.a.a.p
,I/CommonUtil( 6817): BUILD Country: EU
D/Alarms  ( 6817): broadcastToWidgetProvider : false
D/Alarms  ( 6817): Enter formatDayAndTime(final Context context, long timeInMiliSec)
,V/SettingsProvider( 1029): call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
I/DigitalAppWidgetProvider( 6817): onReceive: android.intent.action.TIME_SET
,V/DigitalAppWidgetProvider( 6817): cancelAlarmOnQuarterHour android.app.ReceiverRestrictedContext@1671901a
V/DigitalAppWidgetProvider( 6817): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@1671901a
D/QuickCoverProvider( 6817): onReceiver
I/indal   ( 1411): SmartCoverWidgetContext createApplicationContext
I/indal   ( 1411): SmartCoverWidgetContext createApplicationContext
,D/WeatherAncestor( 6669): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 13:7:58
,D/Weather.Utils( 6669): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6669): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6669): 2 : This is isUpdating : false
D/WeatherService( 6669): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@365e774b
,D/ForecastDataCache( 6669): 2 : lastUpdatedTime: 1430558561343
,D/ForecastDataCache( 6669): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 6669): 2 : Cache is up-to-date, count: 0
V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Weather_cast( 6669): 2 : set auto-update time : 2/2 16:7
D/WeatherAncestor( 6669): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 13:7:58
,I/ActivityManager( 1029): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=6842 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/ActivityManager( 1029): Killing 5959:com.lge.bnr/1000 (adj 15): empty #17
W/libprocessgroup( 1029): failed to open /acct/uid_1000/pid_5959/cgroup.procs: No such file or directory
,I/GLSUser ( 2126): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2126): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2126): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2126): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/TimeService( 6842): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1454414878362
D/        ( 6842): TimeServiceNative: User Time to be set is 1454414878363
D/QC-time-services( 6842): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 6842): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 6842): Lib:time_genoff_operation: pargs->ts_val = 1454414878363
D/QC-time-services( 6842): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  427): Daemon: Connection accepted:time_genoff
V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,D/QC-time-services(  427): Daemon:Received base = 2, unit = 1, operation = 0,value = 1454414878363
D/QC-time-services(  427): Daemon:genoff_opr: Base = 2, val = 1454414878363, operation = 0
D/QC-time-services(  427): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS5/12/70 5:20:5
D/QC-time-services(  427): Daemon:Value read from RTC seconds = 14016005000
D/QC-time-services(  427): Daemon:new time 1454414878363 
D/QC-time-services(  427): Daemon: delta 1440398873363 genoff 1440398873363 
D/QC-time-services(  427): Daemon:genoff_persistent_update: Writing genoff = 1440398873363 to memory
D/QC-time-services(  427): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  427): Daemon:time_persistent_memory_opr:Genoff write operation 
W/GLSActivity( 2126): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2126): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2126): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2126): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2126): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2126): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2126): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1411): onNotificationPosted
D/SmartCoverUpdateMonitor( 1411): received broadcast com.lge.intent.action.NLDataPosted
E/BooksAccountManager( 6524): Authentication error
E/BooksAccountManager( 6524): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6524): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6524): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6524): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6524): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6524): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6524): null auth token
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
,D/QC-time-services(  427): Updating the TOD offset
D/QC-time-services(  427): Daemon:genoff_persistent_update: Writing genoff = 1440398873363 to memory
D/QC-time-services(  427): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  427): Daemon:time_persistent_memory_opr:Genoff write operation 
E/QC-time-services(  427): Daemon:Update to modem bit set
D/QC-time-services(  427): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  427): Daemon: Base = 2, Value being sent to MODEM = 1124434073363
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
E/QC-time-services( 6842): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
E/QC-time-services(  427): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
E/QC-time-services(  427): Daemon: Time-services: Waiting to acceptconnection
E/LgeQuickCoverOverlayWindow( 1411): updateNotificationData: count=3
D/QuickStatusbarLayout( 1411): Notification difference=198
,D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{2a2dccd V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/ActivityManager( 1029): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetProvider: pid=6860 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi
,I/ActivityManager( 1029): Killing 6184:com.lge.lifetracker/u0a37 (adj 15): empty #17
W/ApiaryClient( 6524): Error response from books API: {
W/ApiaryClient( 6524):  "error": {
W/ApiaryClient( 6524):   "errors": [
W/ApiaryClient( 6524):    {
W/ApiaryClient( 6524):     "domain": "global",
W/ApiaryClient( 6524):     "reason": "required",
W/ApiaryClient( 6524):     "message": "Login Required",
W/ApiaryClient( 6524):     "locationType": "header",
W/ApiaryClient( 6524):     "location": "Authorization"
W/ApiaryClient( 6524):    }
W/ApiaryClient( 6524):   ],
W/ApiaryClient( 6524):   "code": 401,
W/ApiaryClient( 6524):   "message": "Login Required"
W/ApiaryClient( 6524):  }
W/ApiaryClient( 6524): }
,W/ApiaryClient( 6524): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6524): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-8684895916163472261&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6524): Headers:
W/ApiaryClient( 6524): accept-encoding: [gzip]
W/ApiaryClient( 6524): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6524): gdata-version: 2
W/libprocessgroup( 1029): failed to open /acct/uid_10037/pid_6184/cgroup.procs: No such file or directory
,W/ResourcesManager( 6860): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/CalendarApplication( 6860): CalendarApplication.onCreate()
,D/PreferenceKeysParser( 6860): [debug_displayParseInfos] preference keys.size() = 44
,D/PreferenceKeysParser( 6860): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@1e411b09, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@29eb710e, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@1485972f, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@e4be13c, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@25575ec5, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@1671901a, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@365e774b, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@3d93d528, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@7d42241, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@370893e6, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@159b3d27, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@32e51bd4, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@13ffa17d, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@aba0872, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@39f484c3, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@1f622140, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@3a69d879, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@59c39be, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@2410aa1f, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@21e8116c, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@aa68335, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@34de33ca, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@e9fc93b, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@7fad858, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@3fc91db1, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@1793c296, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@2537be17, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@31712204, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@18a0e3ed, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@38417222, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@cf024b3, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@2e05a70, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@37b4d1e9, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@13288e6e, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@1abe590f, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@12c8ad9c, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@6ffa3a5, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@1553237a, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@1391772b, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@3d810788, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@1b6bd521, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@5ffd46, 
,D/GeneralPreferenceUtils( 6860): [migratePrefrenceKeys] Exit: Version(44001600) >= 42001300
D/Config  ( 6860): [init]
,I/Config  ( 6860): LGCalendar ver.4.40.16
I/Config  ( 6860): start check model
I/Config  ( 6860): start check native_ca
I/Config  ( 6860): Config Operator=OPEN, Country=EU
D/Config  ( 6860): [setDefaultValuesToPref]
D/Config  ( 6860): [parseProfiles]
D/ProfilesParser( 6860): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6860): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6860): [updateProfiletoCountryInfo]
D/GeneralPreference( 6860): [checkAndMigrateOldPreference]
E/AgendaWidgetManager( 6860): [updateWidgets] 
,I/InitNotificationRingtoneService( 6860): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 6860): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/41
,I/AlertUtils( 6860): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 6860): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arpeggio.ogg
I/AlertUtils( 6860): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 6860): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
,I/AlertUtils( 6860): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 6860): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 6860): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
,I/AlertUtils( 6860): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-53 f=2412 sc=60 link=72 tx=4.9, 0.0, 0.0  rx=3.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1579034644] gl rssi=-53 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-53 f=2412 sc=60 link=72 tx=4.9, 0.0, 0.0  rx=3.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1579034641] gl rssi=-53 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
D/StatusBar.NetworkController( 1454): refreshViews: Data not connected!! Set no data type icon / Roaming
,W/HolidayIntentService( 6860): onHandleIntent
,D/HolidayDataLoader( 6860): readJsonAsset : holiday.json
D/MonthWidgetProvider( 6860): [onReceive]
D/CalendarWidgetProvider( 6860): [onReceive]
D/CalendarWidgetProvider( 6860): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 6860): [onUpdateAndInitCalendarTime]
D/WeekWidgetProvider( 6860): [onReceive]
D/CalendarWidgetProvider( 6860): [onReceive]
D/CalendarWidgetProvider( 6860): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.WeekWidgetProvider }
,D/CalendarTypeController( 6860): [onUpdateAndInitCalendarTime]
I/art     ( 1029): Explicit concurrent mark sweep GC freed 23653(1092KB) AllocSpace objects, 4(448KB) LOS objects, 33% free, 44MB/66MB, paused 3.121ms total 147.250ms
,I/AlertUtils( 6860): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
,I/AlertUtils( 6860): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
,I/AlertUtils( 6860): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Afternoon_Walk.ogg
I/AlertUtils( 6860): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 6860): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
,I/AlertUtils( 6860): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 6860): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 6860): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6860): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/41
,I/AlertUtils( 6860): set default noti to content://media/internal/audio/media/41
I/InitNotificationRingtoneService( 6860): End InitializeAlertRingtoneService.onHandleIntent
E/HolidayIntentService( 6860): onHandleIntent:holiday data empty
,I/ActivityManager( 1029): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RequestWriter$NetworkStateReceiver: pid=6884 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager( 1029): Killing 6275:com.lge.settings.easy/1000 (adj 15): empty #17
W/libprocessgroup( 1029): failed to open /acct/uid_1000/pid_6275/cgroup.procs: No such file or directory
,W/ResourcesManager( 6884): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/LgDataFeature( 6884): LgDataFeature() Constructor: none
D/LgDataFeature( 6884): LgDataFeature() Constructor Done, null
,I/[SystemUI]TimeTickManager( 1454): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1454): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1454): called onTimeUpdated()
,I/[SystemUI]Clock( 1454): called onTimeUpdated()
I/LgeClockWidgetControlView( 1454): called onTimeUpdated()
I/[SystemUI]DateView( 1454): called onTimeUpdated()
I/[SystemUI]DateView( 1454): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1454): handleTimeUpdate
,I/Babel   ( 6884): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 6884): MmsConfig.loadMmsSettings
,I/Babel   ( 6884): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
I/Babel   ( 6884): MmsConfig.loadFromDatabase
,E/Babel   ( 6884): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 6884): MmsConfig.loadFromResources
E/Babel   ( 6884): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 6884): MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,W/AudioCapabilities( 6884): Unsupported mime audio/evrc
W/Settings( 6884): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/AudioCapabilities( 6884): Unsupported mime audio/qcelp
W/VideoCapabilities( 6884): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6884): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6884): Unsupported mime audio/qcelp
W/AudioCapabilities( 6884): Unsupported mime audio/evrc
I/GCM     ( 2333): Message from null null
E/GCM     ( 2333): Dropping message from null
,I/DigitalAppWidgetProvider( 6817): onReceive: android.intent.action.ALARM_CHANGED
D/WeatherAncestor( 6669): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 13:7:59
W/VideoCapabilities( 6884): Unsupported mime video/x-ms-wmv
D/Weather.Utils( 6669): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6669): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6669): 2 : This is isUpdating : false
D/Weather_cast( 6669): 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
D/WeatherAncestor( 6669): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 13:7:59
W/VideoCapabilities( 6884): Unsupported mime video/divx
,W/VideoCapabilities( 6884): Unsupported mime video/divx311
W/VideoCapabilities( 6884): Unsupported mime video/divx4
W/VideoCapabilities( 6884): Unsupported mime video/mp4v-esdp
,W/ResourcesManager( 6884): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6884): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/VideoCapabilities( 6884): Unsupported profile 4 for video/mp4v-es
,W/AudioCapabilities( 6884): Unsupported mime audio/eac3
,W/AudioCapabilities( 6884): Unsupported mime audio/ac3
W/AudioCapabilities( 6884): Unsupported mime audio/g726
W/AudioCapabilities( 6884): Unsupported mime audio/wma-voice
W/AudioCapabilities( 6884): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 6884): Unsupported mime audio/adpcm
W/VideoCapabilities( 6884): Unsupported mime video/theora
V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/VideoCapabilities( 6884): Unsupported mime video/mjpg
V/JNIHelp ( 6884): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/art     ( 2126): Explicit concurrent mark sweep GC freed 18476(1048KB) AllocSpace objects, 13(1616KB) LOS objects, 51% free, 30MB/62MB, paused 1.387ms total 68.519ms
,I/GLSUser ( 2126): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2126): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2126): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2126): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,W/GLSActivity( 2126): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2126): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2126): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2126): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2126): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2126): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2126): 	at android.os.Binder.execTransact(Binder.java:446)
,D/LgeQuickCoverNLService( 1411): onNotificationPosted
D/SmartCoverUpdateMonitor( 1411): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1411): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1411): handleNotificationPosted(true)
D/QuickCircle( 1411): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1411): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1411): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1411): post do just update job
,D/LgeQuickCoverNotificationData( 1411): showAll3
D/LgeQuickCoverNotificationData( 1411): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1411): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1411): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1411): showNotificationWithSetupData: display=false
E/BooksAccountManager( 6524): Authentication error
E/BooksAccountManager( 6524): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6524): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6524): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6524): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6524): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6524): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6524): null auth token
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  1
W/System  ( 6884): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/system/app/Hangouts/Hangouts.apk"],nativeLibraryDirectories=[/system/app/Hangouts/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
I/ProviderInstaller( 6884): Installed default security provider GmsCore_OpenSSL
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1411): updateNotificationData: count=3
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{2a2dccd V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6524): Error response from books API: {
W/ApiaryClient( 6524):  "error": {
W/ApiaryClient( 6524):   "errors": [
W/ApiaryClient( 6524):    {
W/ApiaryClient( 6524):     "domain": "global",
W/ApiaryClient( 6524):     "reason": "required",
W/ApiaryClient( 6524):     "message": "Login Required",
W/ApiaryClient( 6524):     "locationType": "header",
W/ApiaryClient( 6524):     "location": "Authorization"
W/ApiaryClient( 6524):    }
W/ApiaryClient( 6524):   ],
W/ApiaryClient( 6524):   "code": 401,
W/ApiaryClient( 6524):   "message": "Login Required"
W/ApiaryClient( 6524):  }
W/ApiaryClient( 6524): }
,W/ApiaryClient( 6524): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6524): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-8684895916163472261&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6524): Headers:
W/ApiaryClient( 6524): accept-encoding: [gzip]
W/ApiaryClient( 6524): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6524): gdata-version: 2
I/GLSUser ( 2126): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native
,I/GLSUser ( 2126): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2126): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2126): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/Babel   ( 6884): UserRecoverableAuthException.
E/Babel   ( 6884): cfq: BadAuthentication
E/Babel   ( 6884): 	at cfn.a(Unknown Source)
E/Babel   ( 6884): 	at f.a(PG:191)
E/Babel   ( 6884): 	at ava.a(PG:88)
E/Babel   ( 6884): 	at ava.a(PG:128)
E/Babel   ( 6884): 	at bjs.a(PG:255)
E/Babel   ( 6884): 	at bep.a(PG:602)
E/Babel   ( 6884): 	at bep.a(PG:469)
E/Babel   ( 6884): 	at bpo.run(PG:1141)
E/Babel   ( 6884): Error getting auth token
E/Babel   ( 6884): bxl
E/Babel   ( 6884): 	at f.a(PG:201)
E/Babel   ( 6884): 	at ava.a(PG:88)
E/Babel   ( 6884): 	at ava.a(PG:128)
E/Babel   ( 6884): 	at bjs.a(PG:255)
E/Babel   ( 6884): 	at bep.a(PG:602)
E/Babel   ( 6884): 	at bep.a(PG:469)
E/Babel   ( 6884): 	at bpo.run(PG:1141)
I/Babel_RequestWriter( 6884): error sending REQ[fc:8; creat:1454413608286; type:bev-611571371]; took 105 ms (error code == 100)
,E/Babel   ( 6884): Account registration failedRedacted-21
E/Babel   ( 6884): bph: null -- null
E/Babel   ( 6884): 	at ava.a(PG:120)
E/Babel   ( 6884): 	at ava.a(PG:128)
E/Babel   ( 6884): 	at bjs.a(PG:255)
E/Babel   ( 6884): 	at bep.a(PG:602)
E/Babel   ( 6884): 	at bep.a(PG:469)
E/Babel   ( 6884): 	at bpo.run(PG:1141)
I/Babel   ( 6884): Account setup failed with error state:106 account:Redacted-21
I/Babel   ( 6884): Account sign in complete with state 106account: Redacted-21
I/art     ( 6884): Note: end time exceeds epoch: 
,I/GLSUser ( 2126): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native
I/GLSUser ( 2126): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2126): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2126): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 2126): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
,I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
E/Babel   ( 6884): Unexpected exception while authenticating.
E/Babel   ( 6884): cfr: User intervention required. Notification has been pushed.
E/Babel   ( 6884): 	at cfn.b(Unknown Source)
E/Babel   ( 6884): 	at cfn.a(Unknown Source)
E/Babel   ( 6884): 	at f.a(PG:188)
E/Babel   ( 6884): 	at ava.b(PG:143)
E/Babel   ( 6884): 	at bnr.run(PG:5415)
E/Babel   ( 6884): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 6884): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 6884): 	at java.lang.Thread.run(Thread.java:818)
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
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{2a2dccd V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,I/[SystemUI]TimeTickManager( 1454): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1454): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1454): called onTimeUpdated()
I/[SystemUI]Clock( 1454): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1454): called onTimeUpdated()
,I/[SystemUI]DateView( 1454): called onTimeUpdated()
,I/[SystemUI]DateView( 1454): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1454): handleTimeUpdate
D/PowerManagerServiceEx( 1029): acquireWakeLockInternal: lock=967045253, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1029
,V/AlarmManager( 1029): ELAPSED_WAKEUP set : Alarm{139df720 type 2 when 126551 com.android.providers.calendar} when 126551
,I/ActivityManager( 1029): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=6932 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi
,D/[Concierge]Service( 2607): onStartCommand(). Type : 9
,W/ResourcesManager( 6932): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarProvider2( 6932): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@39e9c0d3
,D/CalendarProvider2( 6932): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 6932): Created com.android.providers.calendar.CalendarAlarmManager@e4be13c(com.android.providers.calendar.CalendarProvider2@39e9c0d3)
D/CalendarProviderBroadcastReceiver( 6932): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 6932): [IntentService] WakeLock acquire, start IntentSerivce
D/PowerManagerServiceEx( 1029): releaseWakeLockInternal: lock=967045253 [*alarm*], flags=0x0
,D/CalendarProvider2( 6932): CalendarProviderIntentService.onCreate()
D/CalendarProvider2( 6932): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 6932): [getOrCreateCalendarAlarmManager]
E/SQLiteLog( 6932): (284) automatic index on view_events(_id)
D/CalendarProvider2( 6932): [IntentService] Release Lock
E/BooksSync( 6524): Soft error: 
E/BooksSync( 6524): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6524): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-8684895916163472261&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6524): Headers:
E/BooksSync( 6524): accept-encoding: [gzip]
E/BooksSync( 6524): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6524): gdata-version: 2
E/BooksSync( 6524): 
E/BooksSync( 6524): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6524): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6524): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6524): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6524): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6524): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6524): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6524): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6524): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6524): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6524): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6524): {
E/BooksSync( 6524):  "error": {
E/BooksSync( 6524):   "errors": [
E/BooksSync( 6524):    {
E/BooksSync( 6524):     "domain": "global",
E/BooksSync( 6524):     "reason": "required",
E/BooksSync( 6524):     "message": "Login Required",
E/BooksSync( 6524):     "locationType": "header",
E/BooksSync( 6524):     "location": "Authorization"
E/BooksSync( 6524):    }
E/BooksSync( 6524):   ],
E/BooksSync( 6524):   "code": 401,
E/BooksSync( 6524):   "message": "Login Required"
E/BooksSync( 6524):  }
E/BooksSync( 6524): }
E/BooksSync( 6524): 
E/BooksSync( 6524): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6524): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6524): 	... 8 more
E/BooksSync( 6524): Sync error
E/BooksSync( 6524): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6524): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-8684895916163472261&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6524): Headers:
E/BooksSync( 6524): accept-encoding: [gzip]
E/BooksSync( 6524): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6524): gdata-version: 2
E/BooksSync( 6524): 
E/BooksSync( 6524): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6524): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute,Once(ApiaryClientImpl.java:224)
E/BooksSync( 6524): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6524): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6524): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6524): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6524): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6524): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6524): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6524): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6524): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6524): {
E/BooksSync( 6524):  "error": {
E/BooksSync( 6524):   "errors": [
E/BooksSync( 6524):    {
E/BooksSync( 6524):     "domain": "global",
E/BooksSync( 6524):     "reason": "required",
E/BooksSync( 6524):     "message": "Login Required",
E/BooksSync( 6524):     "locationType": "header",
E/BooksSync( 6524):     "location": "Authorization"
E/BooksSync( 6524):    }
E/BooksSync( 6524):   ],
E/BooksSync( 6524):   "code": 401,
E/BooksSync( 6524):   "message": "Login Required"
E/BooksSync( 6524):  }
E/BooksSync( 6524): }
E/BooksSync( 6524): 
E/BooksSync( 6524): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6524): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6524): 	... 8 more
,I/BooksSync( 6524): Finished books sync
D/CalendarProvider2( 6932): CalendarProviderIntentService.onDestroy()
I/ActivityManager( 1029): Killing 6229:com.lge.sync/1000 (adj 15): empty #17
W/libprocessgroup( 1029): failed to open /acct/uid_1000/pid_6229/cgroup.procs: No such file or directory
,D/SyncManager( 1029): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 26739, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
I/ActivityManager( 1029): Killing 5894:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,I/QRemote ( 5980): [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
W/System.err( 5980): android.os.DeadObjectException
W/System.err( 5980): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5980): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5980): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 5980): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
W/System.err( 5980): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 5980): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 5980): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5980): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5980): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5980): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 5980): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5980): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5980): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 5980): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 5980): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 5980): android.os.DeadObjectException
W/System.err( 5980): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5980): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5980): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 5980): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
,W/System.err( 5980): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 5980): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
,W/System.err( 5980): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5980): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5980): 	at android.os.Looper.loop(Looper.java:135)
,W/System.err( 5980): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 5980): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5980): 	at java.lang.reflect.Method.invoke(Method.java:372)
,W/System.err( 5980): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 5980): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 5980): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/QRemote ( 5980): [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
W/libprocessgroup( 1029): failed to open /acct/uid_1000/pid_5894/cgroup.procs: No such file or directory
W/ActivityManager( 1029): Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,D/QRemote ( 5980): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
,I/QRemote ( 5980): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
I/ActivityManager( 1029): Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6986 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,D/QRemote ( 5980): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
I/art     (  348): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 463us total 30.620ms
,I/art     (  348): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 441us total 21.592ms
,I/art     (  348): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 442us total 20.768ms
I/GAV2    ( 6524): Thread[GAThread,5,main]: No campaign data found.
D/UEI.SmartControl( 6986): Quickset Services start...
,I/UEI.SmartControl( 6986): Manufacture = LGE
D/UEI.SmartControl( 6986): Id = LGNevo
D/UEI.SmartControl( 6986): File observer start...
E/UEI.SmartControl( 6986): IR Port is disabled: false
D/UEI.SmartControl( 6986): Starting file observer...
D/UEI.SmartControl( 6986): Extracting JNI libs...
D/UEI.SmartControl( 6986): --- this system supports 32-bit or 64-bit only
V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2126): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 2126): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2126): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2126): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
,I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1411): onNotificationPosted
W/GLSActivity( 2126): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2126): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2126): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2126): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2126): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2126): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2126): 	at android.os.Binder.execTransact(Binder.java:446)
D/SmartCoverUpdateMonitor( 1411): received broadcast com.lge.intent.action.NLDataPosted
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
D/SyncManager( 1029): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 156014, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
D/UEI.SmartControl( 6986): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 6986): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6986): --- Extracting JNI libs: libqs_armeabi-v7a.zip
E/LgeQuickCoverOverlayWindow( 1411): updateNotificationData: count=3
,D/QuickStatusbarLayout( 1411): Notification difference=198
,D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{2a2dccd V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/UEI.SmartControl( 6986): --- Selecting new region: 6
I/UEI.SmartControl( 6986): Model = LG-D855
,D/UEI.SmartControl( 6986): QS Service created
I/UEI.SmartControl( 6986): Service initServices...
,D/UEI.SmartControl( 6986): QS start get config
,D/UEI.SmartControl( 6986): Loading JNI Libs...
,I/UEI.SmartControl( 6986): Supports setup maps: true
,D/UEI.SmartControl( 6986): QS start statue = true Error code = 0
,I/UEI.SmartControl( 6986): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6986): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6986): ### init IR Blaster...
D/serial_port( 6986): Configuring serial port
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=20.9, 0.0, 0.0  rx=17.9 bcn=0 [on:0 tx:0 rx:0 period:3007] from screen [on:0 period:-1579031627] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/UEI.SmartControl( 6986): UEIBLaster setting for 616
I/UEI.SmartControl( 6986): Setting serial record hearder size = 2
I/UEI.SmartControl( 6986): configuring settings for MAXQ616
I/UEI.SmartControl( 6986): Get version...
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=20.9, 0.0, 0.0  rx=17.9 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1579031625] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
D/UEI.SmartControl( 6986): serial port data available: 21
,D/UEI.SmartControl( 6986): MAXQ616 A2-X4 software.
,I/UEI.SmartControl( 6986): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 6986): QS saving settings...
D/UEI.SmartControl( 6986): IR Blaster version: 25672567
,D/UEI.SmartControl( 6986): serial port data available: 4
,I/UEI.SmartControl( 6986): Device manager: loading config....
D/UEI.SmartControl( 6986): ----------- loading internal config...
W/ContextImpl( 6986): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,E/UEI.SmartControl( 6986): Services init done
D/UEI.SmartControl( 6986): QS Service init finished
D/UEI.SmartControl( 6986): QS Service version name: 2.1.91
D/UEI.SmartControl( 6986): QS Service version code: 201091
D/UEI.SmartControl( 6986): Service requested: Control
E/UEI.SmartControl( 6986): Loading SETTINGS...
,D/UEI.SmartControl( 6986): Request IControl service: devices are loaded...
I/QRemote ( 5980): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 6986): ------ IControl API: 11
I/ActivityManager( 1029): Killing 6150:com.android.settings/1000 (adj 15): empty #17
I/UEI.SmartControl( 6986): Registering callback...
I/UEI.SmartControl( 6986): ------ IControl API: 19
I/UEI.SmartControl( 6986): Registering Services Ready callback...
D/UEI.SmartControl( 6986): -- Open brand translation xml: brands_translations_ko
,D/WifiService( 1029): Client connection lost with reason: 4
I/UEI.SmartControl( 6986): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6986): -----service ready thread exits
I/QRemote ( 5980): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
,D/QRemote ( 5980): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 5980): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 5980): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 5980): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
D/UEI.SmartControl( 6986): Internal service binding...
W/libprocessgroup( 1029): failed to open /acct/uid_1000/pid_6150/cgroup.procs: No such file or directory
I/GAV4    ( 6692): Thread[GAThread,5,main]: No campaign data found.
I/UEI.SmartControl( 6986): ------ IControl API: 8
D/QRemote ( 5980): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 5980): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
,D/QRemote ( 5980): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 5980): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 5980): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 5980): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 5980): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
V/QRemote ( 5980): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 5980): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 5980): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 5980): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 5980): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 5980): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 5980): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 5980): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1454414881922]
D/QRemote ( 5980): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,V/QRemote ( 5980): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,E/QRemote ( 5980): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,D/QRemote ( 5980): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 5980): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 5980): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 5980): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 5980): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 5980): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
I/ActivityManager( 1029): Killing 6505:com.lge.appbox.client/u0a11 (adj 15): empty #17
,W/libprocessgroup( 1029): failed to open /acct/uid_10011/pid_6505/cgroup.procs: No such file or directory
,I/ActivityManager( 1029): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=7052 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/AlarmManager( 1029): RTC_WAKEUP set : Alarm{25d38580 type 0 when 1454414883826 com.android.vending} when 1454414883826
,D/Finsky  ( 7052): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/LgDataFeature( 7052): LgDataFeature() Constructor: none
,D/LgDataFeature( 7052): LgDataFeature() Constructor Done, null
,D/Finsky  ( 7052): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/ActivityManager( 1029): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=7103 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
W/Settings( 7052): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 7052): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,V/DownloadManager( 3364): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3364): created cursor android.database.sqlite.SQLiteCursor@140fa25d on behalf of 7052
,D/Finsky  ( 7052): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7052): [1] 2.run: Finished loading 1 libraries.
,W/ResourcesManager( 7103): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7103): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/Finsky  ( 7052): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/Finsky  ( 7052): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/MultiDex( 7103): VM with version 2.1.0 has multidex support
I/MultiDex( 7103): install
I/MultiDex( 7103): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 7103): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,V/SIM_STK ( 1029): Menu title from STK is T-Mobile
,W/ActivityThread( 7103): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7103): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@39c843f6: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7103): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 2126): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AuthorizationBluetoothService( 2126): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 2333): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
I/ActivityManager( 1029): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=7132 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,D/LocationInitializer( 2333): Restart initialization of location
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=12.0, 0.0, 0.0  rx=9.9 bcn=0 [on:0 tx:0 rx:0 period:2998] from screen [on:0 period:-1579028604] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=12.0, 0.0, 0.0  rx=9.9 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1579028603] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,W/ResourcesManager( 7132): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7132): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/MultiDex( 7132): VM with version 2.1.0 has multidex support
I/MultiDex( 7132): install
I/MultiDex( 7132): VM has multidex support, MultiDex support library is disabled.
,I/ActivityManager( 1029): Killing 6202:com.lge.formmanager/u0a26 (adj 15): empty #17
I/art     ( 2333): Explicit concurrent mark sweep GC freed 17951(1264KB) AllocSpace objects, 18(288KB) LOS objects, 49% free, 32MB/64MB, paused 1.022ms total 50.307ms
,W/libprocessgroup( 1029): failed to open /acct/uid_10026/pid_6202/cgroup.procs: No such file or directory
V/JNIHelp ( 7132): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 7132): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7132): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@39c843f6: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7132): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 7132): callingUid 10005, callindPid: 7132
,V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1029): Explicit concurrent mark sweep GC freed 26609(1240KB) AllocSpace objects, 6(480KB) LOS objects, 33% free, 44MB/66MB, paused 1.825ms total 112.774ms
,D/GCM     ( 2126): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 2126): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/MDM     ( 1832): [84] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
V/GmsCoreStatsServiceLauncher( 2333): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,V/Finsky  ( 7052): [1] GearheadStateMonitor.onReady: sIsProjecting:false
I/GLSUser ( 2126): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2126): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2126): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2126): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/MDM     ( 1832): [85] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
D/LocationInitializer( 2333): Restart initialization of location
,D/Finsky  ( 7052): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7052): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7052): [1] 5.onFinished: Scheduling replication attempt 2.
,I/ActivityManager( 1029): Killing 6544:com.android.gallery3d/u0a27 (adj 15): empty #17
I/ActivityManager( 1029): Killing 6646:com.lge.drmservice/u0a62 (adj 15): empty #18
,W/libprocessgroup( 1029): failed to open /acct/uid_10027/pid_6544/cgroup.procs: No such file or directory
,W/libprocessgroup( 1029): failed to open /acct/uid_10062/pid_6646/cgroup.procs: No such file or directory
V/AlarmManager( 1029): RTC_WAKEUP set : Alarm{3e462ef8 type 0 when 1454414885281 com.android.vending} when 1454414885281
D/Finsky  ( 7052): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2126): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2126): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2126): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2126): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 7052): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2126): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2126): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2126): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2126): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2126): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2126): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2126): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2126): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 7052): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/SIM_STK ( 1029): Menu title from STK is T-Mobile
,V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2126): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2126): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2126): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2126): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 7052): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 7052): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
D/Finsky  ( 7052): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7052): [1] DailyHygiene.reschedule: Scheduling new run in 860 minutes (failures=5)
D/DeviceConnectionService( 1832): client connected with version: 7571000
,D/UEI.SmartControl( 6986): Internal timer expired: 1
,D/UEI.SmartControl( 6986): unbind internal service
,D/serial_port( 6986): close(fd = 25)
,I/UEI.SmartControl( 6986): Serial port is closed.
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=6.5, 0.0, 0.0  rx=5.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1579025589] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=6.5, 0.0, 0.0  rx=5.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1579025586] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,I/ActivityManager( 1029): Killing 6692:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,W/libprocessgroup( 1029): failed to open /acct/uid_10093/pid_6692/cgroup.procs: No such file or directory
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=4.2, 0.0, 0.0  rx=3.2 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1579022560] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=4.2, 0.0, 0.0  rx=3.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1579022557] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 137642411931; DSPS: 4651191; Offset : -4312880571
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=2.6, 0.0, 0.0  rx=2.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1579019536] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=2.6, 0.0, 0.0  rx=2.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1579019533] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,I/[SystemUI]QPairHandler( 1454): onReceive = android.intent.action.PACKAGE_CHANGED
,I/InputReader( 1029): Reconfiguring input devices.  changes=0x00000010
,D/SplitUIService( 1885): replaced split : contains_com.google.android.talk / true
I/ActivityManager( 1029): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7176 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/administrator( 1029): Handling package changes for user 0
,I/[SystemUI]QSlideListController( 1454): onReceive = android.intent.action.PACKAGE_CHANGED
I/[LGHome]EVENT( 2083): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000010 (has extras) }
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1454): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.talk
,D/SplitUIManager( 1885): split_name #11 / not available #0
I/SplitUIService( 1885): split app #11
W/ResourcesManager( 2083): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/[LGHome]Launcher( 2083): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/AppUp4:AppBoxCP( 7176): onCreate
,W/AppUp4:DB( 7176):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7176):  setFingerPrint start
I/AppUp4:DB( 7176):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 7176):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7176):  SDK version = 21
I/AppUp4:DB( 7176):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7176): AppBoxApplication onCreate()
,I/AppUp4:CustModeStarterReceiver( 7176): onReceive
,I/NotificationService( 1029): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService( 1029): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000010 (has extras) }
,W/ResourcesManager( 1029): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/LgDataFeature( 7176): LgDataFeature() Constructor: none
D/LgDataFeature( 7176): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7176): Context : android.app.ReceiverRestrictedContext@29eb710e
D/AppUp4:CustFacade( 7176): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7176): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7176): begin check event
I/AppUp4:CustModeStarterReceiver( 7176): Event For Nothing, skip.
W/ResourcesManager( 1029): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourceType( 1029): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/ActivityManager( 1029): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7212 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/ActivityManager( 1029): Killing 6586:com.android.chrome/u0a57 (adj 15): empty #17
,I/[LGHome]EVENT( 2083): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
W/libprocessgroup( 1029): failed to open /acct/uid_10057/pid_6586/cgroup.procs: No such file or directory
W/ResourcesManager( 7212): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7212): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7212): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7212): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7212): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/SystemConfig( 7212): BUILD Country: EU
I/SystemConfig( 7212): BUILD Operator: OPEN
,I/SystemConfig( 7212): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7212): existFile = false
I/SystemConfig( 7212): canReadFile = false
I/SystemConfig( 7212): systemFeature RCS result false
D/SystemConfig( 7212): refreshRcsSupport() :false
,I/ActivityManager( 1029): Killing 6763:com.google.android.apps.plus/u0a97 (adj 15): empty #17
W/libprocessgroup( 1029): failed to open /acct/uid_10097/pid_6763/cgroup.procs: No such file or directory
,I/ActivityManager( 1029): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7235 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/ResourcesManager( 7235): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7235): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 7235): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 7235): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/AppConfig( 7235): Total System Memory = 2995761152
,D/SystemHelper( 7235): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager( 1029): Killing 6568:com.lge.email/u0a23 (adj 15): empty #17
,W/libprocessgroup( 1029): failed to open /acct/uid_10023/pid_6568/cgroup.procs: No such file or directory
,I/UpdateIcingCorporaServi( 4224): Updating corpora: APPS=com.google.android.talk, CONTACTS=MAYBE
,I/ActivityManager( 1029): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7259 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,V/SIM_STK ( 1029): Menu title from STK is T-Mobile
,W/ResourcesManager( 4224): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 4224): UpdateCorporaTask done [took 121 ms] updated apps [took 121 ms] 
,I/LockScreenSettings( 7259): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7259): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,D/LockScreenSettings( 7259): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
,D/LockScreenSettings( 7259): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7259): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7259): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
D/LockScreenSettings( 7259): Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
I/ActivityManager( 1029): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7281 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1029): Killing 5146:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,W/libprocessgroup( 1029): failed to open /acct/uid_1000/pid_5146/cgroup.procs: No such file or directory
,W/ResourcesManager( 7281): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/PackageBroadcastService( 2333): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.talk
,I/PeopleContactsSync( 2333): CP2 sync disabled
,I/art     ( 2126): Explicit concurrent mark sweep GC freed 24616(1462KB) AllocSpace objects, 9(1296KB) LOS objects, 51% free, 30MB/62MB, paused 1.449ms total 90.929ms
,I/GLSActivity( 2126): [ac] getting account id
,I/GLSUser ( 2126): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.8, 0.0, 0.0  rx=1.6 bcn=0 [on:0 tx:0 rx:0 period:2999] from screen [on:0 period:-1579016516] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.8, 0.0, 0.0  rx=1.6 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:-1579016516] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1579013498] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1579013495] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,I/ActivityManager( 1029): Killing 6842:com.qualcomm.timeservice/1000 (adj 15): empty #17
,W/libprocessgroup( 1029): failed to open /acct/uid_1000/pid_6842/cgroup.procs: No such file or directory
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1579010471] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1579010468] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,V/AlarmManager( 1029): RTC_WAKEUP set : Alarm{37c3f8e type 0 when 1454414905654 com.android.vending} when 1454414905654
,V/SIM_STK ( 1029): Menu title from STK is T-Mobile
,V/AlarmManager( 1029): ELAPSED_WAKEUP set : Alarm{d1883af type 2 when 151944 android} when 151944
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1579007444] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1579007443] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2126): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2126): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2126): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2126): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7052): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7052): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7052): [1] 5.onFinished: Scheduling replication attempt 3.
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1579004421] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1579004418] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,E/WifiStateMachine( 1029):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,E/WifiStateMachine( 1029):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1029):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,E/WifiStateMachine( 1029):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 157644601403; DSPS: 5306623; Offset : -4312888364
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1579001397] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1579001394] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1578998372] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1578998369] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1578995344] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1578995335] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1578992315] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1578992304] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1578989283] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1578989280] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1578986260] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1578986257] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1578983230] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1578983227] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 177646702645; DSPS: 5962051; Offset : -4312862344
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1578980205] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1578980195] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
V/AlarmManager( 1029): RTC_WAKEUP set : Alarm{1e3da83e type 0 when 1454414925948 com.android.vending} when 1454414925948
,V/SIM_STK ( 1029): Menu title from STK is T-Mobile
,V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1029): Explicit concurrent mark sweep GC freed 38194(1759KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 2.181ms total 125.008ms
,I/GLSUser ( 2126): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2126): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2126): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2126): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7052): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7052): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7052): [1] 5.onFinished: Scheduling replication attempt 4.
,V/AlarmManager( 1029): ELAPSED_WAKEUP set : Alarm{266724f0 type 2 when 181961 android} when 181961
,I/BooksSync( 6524): Starting books sync
,D/BooksSync( 6524): started syncMyEbooks
,V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2126): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
,I/GLSUser ( 2126): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2126): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2126): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
,D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  2
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
E/LgeQuickCoverOverlayWindow( 1411): updateNotificationData: count=3
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{2a2dccd V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/SyncManager( 1029): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 156014, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager( 1029): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 248051, reason: 10019
I/GLSUser ( 2126): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2126): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2126): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2126): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2126): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2126): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2126): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2126): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2126): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2126): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2126): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6524): Authentication error
E/BooksAccountManager( 6524): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6524): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6524): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6524): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6524): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6524): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6524): null auth token
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
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{2a2dccd V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1578977173] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1578977172] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
W/ApiaryClient( 6524): Error response from books API: {
W/ApiaryClient( 6524):  "error": {
W/ApiaryClient( 6524):   "errors": [
W/ApiaryClient( 6524):    {
W/ApiaryClient( 6524):     "domain": "global",
W/ApiaryClient( 6524):     "reason": "required",
W/ApiaryClient( 6524):     "message": "Login Required",
W/ApiaryClient( 6524):     "locationType": "header",
W/ApiaryClient( 6524):     "location": "Authorization"
W/ApiaryClient( 6524):    }
W/ApiaryClient( 6524):   ],
W/ApiaryClient( 6524):   "code": 401,
W/ApiaryClient( 6524):   "message": "Login Required"
W/ApiaryClient( 6524):  }
W/ApiaryClient( 6524): }
W/ApiaryClient( 6524): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6524): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=1856378167573806517&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6524): Headers:
W/ApiaryClient( 6524): accept-encoding: [gzip]
W/ApiaryClient( 6524): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6524): gdata-version: 2
,V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2126): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2126): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2126): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2126): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
,E/BooksAccountManager( 6524): Authentication error
E/BooksAccountManager( 6524): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6524): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6524): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6524): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6524): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6524): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6524): null auth token
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{2a2dccd V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6524): Error response from books API: {
W/ApiaryClient( 6524):  "error": {
W/ApiaryClient( 6524):   "errors": [
W/ApiaryClient( 6524):    {
W/ApiaryClient( 6524):     "domain": "global",
W/ApiaryClient( 6524):     "reason": "required",
W/ApiaryClient( 6524):     "message": "Login Required",
W/ApiaryClient( 6524):     "locationType": "header",
W/ApiaryClient( 6524):     "location": "Authorization"
W/ApiaryClient( 6524):    }
W/ApiaryClient( 6524):   ],
W/ApiaryClient( 6524):   "code": 401,
W/ApiaryClient( 6524):   "message": "Login Required"
W/ApiaryClient( 6524):  }
W/ApiaryClient( 6524): }
,W/ApiaryClient( 6524): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6524): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=1856378167573806517&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6524): Headers:
W/ApiaryClient( 6524): accept-encoding: [gzip]
W/ApiaryClient( 6524): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6524): gdata-version: 2
,V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2126): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2126): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2126): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2126): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
E/BooksAccountManager( 6524): Authentication error
E/BooksAccountManager( 6524): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6524): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6524): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6524): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6524): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6524): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6524): null auth token
,D/QuickStatusbarLayout( 1411): Notification difference=198
,D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{2a2dccd V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6524): Error response from books API: {
W/ApiaryClient( 6524):  "error": {
W/ApiaryClient( 6524):   "errors": [
W/ApiaryClient( 6524):    {
W/ApiaryClient( 6524):     "domain": "global",
W/ApiaryClient( 6524):     "reason": "required",
W/ApiaryClient( 6524):     "message": "Login Required",
W/ApiaryClient( 6524):     "locationType": "header",
W/ApiaryClient( 6524):     "location": "Authorization"
W/ApiaryClient( 6524):    }
W/ApiaryClient( 6524):   ],
W/ApiaryClient( 6524):   "code": 401,
W/ApiaryClient( 6524):   "message": "Login Required"
W/ApiaryClient( 6524):  }
W/ApiaryClient( 6524): }
,W/ApiaryClient( 6524): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6524): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=1856378167573806517&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6524): Headers:
W/ApiaryClient( 6524): accept-encoding: [gzip]
W/ApiaryClient( 6524): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6524): gdata-version: 2
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1578974162] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1578974159] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/BooksSync( 6524): Soft error: 
E/BooksSync( 6524): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6524): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=1856378167573806517&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6524): Headers:
E/BooksSync( 6524): accept-encoding: [gzip]
E/BooksSync( 6524): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6524): gdata-version: 2
E/BooksSync( 6524): 
E/BooksSync( 6524): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6524): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6524): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6524): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6524): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6524): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6524): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6524): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6524): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6524): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6524): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6524): {
E/BooksSync( 6524):  "error": {
E/BooksSync( 6524):   "errors": [
E/BooksSync( 6524):    {
E/BooksSync( 6524):     "domain": "global",
E/BooksSync( 6524):     "reason": "required",
E/BooksSync( 6524):     "message": "Login Required",
E/BooksSync( 6524):     "locationType": "header",
E/BooksSync( 6524):     "location": "Authorization"
E/BooksSync( 6524):    }
E/BooksSync( 6524):   ],
E/BooksSync( 6524):   "code": 401,
E/BooksSync( 6524):   "message": "Login Required"
E/BooksSync( 6524):  }
E/BooksSync( 6524): }
E/BooksSync( 6524): 
E/BooksSync( 6524): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6524): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6524): 	... 8 more
,E/BooksSync( 6524): Sync error
E/BooksSync( 6524): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6524): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=1856378167573806517&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6524): Headers:
E/BooksSync( 6524): accept-encoding: [gzip]
E/BooksSync( 6524): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6524): gdata-version: 2
E/BooksSync( 6524): 
E/BooksSync( 6524): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6524): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6524): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6524): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6524): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6524): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6524): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6524): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6524): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6524): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6524): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6524): {
E/BooksSync( 6524):  "error": {
E/BooksSync( 6524):   "errors": [
E/BooksSync( 6524):    {
E/BooksSync( 6524):     "domain": "global",
E/BooksSync( 6524):     "reason": "required",
E/BooksSync( 6524):     "message": "Login Required",
E/BooksSync( 6524):     "locationType": "header",
E/BooksSync( 6524):     "location": "Authorization"
E/BooksSync( 6524):    }
E/BooksSync( 6524):   ],
E/BooksSync( 6524):   "code": 401,
E/BooksSync( 6524):   "message": "Login Required"
E/BooksSync( 6524):  }
E/BooksSync( 6524): }
E/BooksSync( 6524): 
E/BooksSync( 6524): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6524): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6524): 	... 8 more
I/BooksSync( 6524): Finished books sync
D/SyncManager( 1029): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 157117, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/[SystemUI]TimeTickManager( 1454): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1454): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1454): called onTimeUpdated()
,I/[SystemUI]Clock( 1454): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1454): called onTimeUpdated()
I/[SystemUI]DateView( 1454): called onTimeUpdated()
I/[SystemUI]DateView( 1454): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1454): handleTimeUpdate
I/[SystemUI]LGPowerUI( 1454): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1454): On Skip Timer : true
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=3.6, 0.0, 0.0  rx=3.8 bcn=0 [on:0 tx:0 rx:0 period:3015] from screen [on:0 period:-1578971125] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=3.6, 0.0, 0.0  rx=3.8 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1578971124] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
D/WifiController( 1029): battery changed pluggedType: 2
,D/LEDHandler( 1961): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1961): Battery Level Remaining: 100%
D/LEDHandler( 1961): Battery Temp: 290, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1454): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 290
I/[SystemUI]LGPowerUI( 1454): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings( 1029): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1029): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 6118): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1454): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3250): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3250): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=1.8, 0.0, 0.0  rx=1.9 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1578968106] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=1.8, 0.0, 0.0  rx=1.9 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1578968097] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1578965076] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1578965065] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1578962045] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1578962035] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 197648621387; DSPS: 6617474; Offset : -4312866079
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1578959014] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1578959001] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1578955988] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1578955985] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1578952961] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1578952958] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1578949931] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1578949928] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1578946903] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1578946899] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,D/PowerManagerServiceEx( 1029): acquireWakeLockInternal: lock=967045253, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1029
,V/AlarmManager( 1029): ELAPSED_WAKEUP set : Alarm{3cd0b880 type 2 when 208924 android} when 208924
V/AlarmManager( 1029): ELAPSED_WAKEUP set : Alarm{3015beb9 type 2 when 212017 android} when 212017
V/AlarmManager( 1029): ELAPSED_WAKEUP set : Alarm{1574c2fe type 2 when 179355 com.google.android.gms} when 179355
V/AlarmManager( 1029): RTC_WAKEUP set : Alarm{3ec8dcac type 0 when 1454414954924 com.android.vending} when 1454414954924
,D/[Concierge]Service( 2607): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1029): releaseWakeLockInternal: lock=967045253 [*alarm*], flags=0x0
,V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/SIM_STK ( 1029): Menu title from STK is T-Mobile
,I/VacuumService( 2126): Vacuum at: now=1454414968966 tag=VacuumService
,I/GoogleURLConnFactory( 2126): Using platform SSLCertificateSocketFactory
,W/Uploader( 2126): No account for auth token provided
D/libc-netbsd(  318): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  318): res_queryN name = play.googleapis.com, class = 1, type = 1
,V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc-netbsd(  318): res_queryN name = play.googleapis.com succeed
,I/GLSUser ( 2126): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2126): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2126): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2126): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7052): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7052): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7052): [1] 5.onFinished: Scheduling replication attempt 5.
,I/GLSUser ( 2126): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 2126): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2126): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2126): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
,D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  1
,D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1411): updateNotificationData: count=3
E/Uploader( 2126): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 2126): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 2126): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 2126): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 2126): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 2126): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 2126): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 2126): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 2126): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 2126): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 2126): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 2126): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 2126): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{2a2dccd V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1578943875] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1578943871] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,W/Uploader( 2126): No account for auth token provided
,W/Uploader( 2126): No account for auth token provided
,W/Uploader( 2126):  no longer exists, so no auth token.
,W/Uploader( 2126): No account for auth token provided
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 217651167474; DSPS: 7272918; Offset : -4312883625
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=5.3, 0.0, 0.0  rx=4.3 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1578940861] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=5.3, 0.0, 0.0  rx=4.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1578940858] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=7.2, 0.0, 0.0  rx=4.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1578937832] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=7.2, 0.0, 0.0  rx=4.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1578937829] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=4.1, 0.0, 0.0  rx=2.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1578934804] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=4.1, 0.0, 0.0  rx=2.8 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1578934795] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=2.0, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1578931776] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=2.0, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1578931773] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.5, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1578928747] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.5, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1578928744] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.3, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1578925724] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.3, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1578925714] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1578922692] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1578922689] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 237653000330; DSPS: 7928338; Offset : -4312881824
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1578919663] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1578919659] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1578916634] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1578916624] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,V/AlarmManager( 1029): RTC_WAKEUP set : Alarm{212eb43f type 0 when 1454414989166 com.android.vending} when 1454414989166
,V/SIM_STK ( 1029): Menu title from STK is T-Mobile
,V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2126): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2126): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2126): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2126): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7052): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 7052): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 7052): [1] 5.onFinished: Giving up after 6 failures.
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1578913603] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1578913599] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1454): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1454): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1454): called onTimeUpdated()
I/[SystemUI]Clock( 1454): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1454): called onTimeUpdated()
I/[SystemUI]DateView( 1454): called onTimeUpdated()
I/[SystemUI]DateView( 1454): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1454): handleTimeUpdate
,D/PowerManagerServiceEx( 1029): acquireWakeLockInternal: lock=967045253, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1029
,V/AlarmManager( 1029): ELAPSED_WAKEUP set : Alarm{1d78f09 type 2 when 246325 android} when 246325
D/[Concierge]Service( 2607): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1029): releaseWakeLockInternal: lock=967045253 [*alarm*], flags=0x0
,I/BooksSync( 6524): Starting books sync
,D/BooksSync( 6524): started syncMyEbooks
,V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2126): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2126): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2126): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2126): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2126): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2126): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2126): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2126): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2126): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2126): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2126): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6524): Authentication error
E/BooksAccountManager( 6524): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6524): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6524): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6524): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6524): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6524): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6524): null auth token
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
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{2a2dccd V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6524): Error response from books API: {
W/ApiaryClient( 6524):  "error": {
W/ApiaryClient( 6524):   "errors": [
W/ApiaryClient( 6524):    {
W/ApiaryClient( 6524):     "domain": "global",
W/ApiaryClient( 6524):     "reason": "required",
W/ApiaryClient( 6524):     "message": "Login Required",
W/ApiaryClient( 6524):     "locationType": "header",
W/ApiaryClient( 6524):     "location": "Authorization"
W/ApiaryClient( 6524):    }
W/ApiaryClient( 6524):   ],
W/ApiaryClient( 6524):   "code": 401,
W/ApiaryClient( 6524):   "message": "Login Required"
W/ApiaryClient( 6524):  }
W/ApiaryClient( 6524): }
,W/ApiaryClient( 6524): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6524): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=1998408275161122779&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6524): Headers:
W/ApiaryClient( 6524): accept-encoding: [gzip]
W/ApiaryClient( 6524): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6524): gdata-version: 2
,V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1029): Explicit concurrent mark sweep GC freed 47608(2MB) AllocSpace objects, 7(880KB) LOS objects, 33% free, 44MB/66MB, paused 3.109ms total 171.995ms
,I/GLSUser ( 2126): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2126): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2126): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2126): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2126): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2126): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2126): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2126): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2126): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2126): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2126): 	at android.os.Binder.execTransact(Binder.java:446)
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
E/BooksAccountManager( 6524): Authentication error
E/BooksAccountManager( 6524): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6524): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6524): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6524): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6524): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6524): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6524): null auth token
E/LgeQuickCoverOverlayWindow( 1411): updateNotificationData: count=3
,D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{2a2dccd V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6524): Error response from books API: {
W/ApiaryClient( 6524):  "error": {
W/ApiaryClient( 6524):   "errors": [
W/ApiaryClient( 6524):    {
W/ApiaryClient( 6524):     "domain": "global",
W/ApiaryClient( 6524):     "reason": "required",
W/ApiaryClient( 6524):     "message": "Login Required",
W/ApiaryClient( 6524):     "locationType": "header",
W/ApiaryClient( 6524):     "location": "Authorization"
W/ApiaryClient( 6524):    }
W/ApiaryClient( 6524):   ],
W/ApiaryClient( 6524):   "code": 401,
W/ApiaryClient( 6524):   "message": "Login Required"
W/ApiaryClient( 6524):  }
W/ApiaryClient( 6524): }
,W/ApiaryClient( 6524): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6524): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=1998408275161122779&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6524): Headers:
W/ApiaryClient( 6524): accept-encoding: [gzip]
W/ApiaryClient( 6524): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6524): gdata-version: 2
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1578910576] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1578910563] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2126): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2126): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2126): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2126): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
,E/BooksAccountManager( 6524): Authentication error
E/BooksAccountManager( 6524): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6524): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6524): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6524): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6524): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6524): 	at android.os.Binder.execTransact(Binder.java:446)
,E/HttpHelper( 6524): null auth token
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{2a2dccd V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6524): Error response from books API: {
W/ApiaryClient( 6524):  "error": {
W/ApiaryClient( 6524):   "errors": [
W/ApiaryClient( 6524):    {
W/ApiaryClient( 6524):     "domain": "global",
W/ApiaryClient( 6524):     "reason": "required",
W/ApiaryClient( 6524):     "message": "Login Required",
W/ApiaryClient( 6524):     "locationType": "header",
W/ApiaryClient( 6524):     "location": "Authorization"
W/ApiaryClient( 6524):    }
W/ApiaryClient( 6524):   ],
W/ApiaryClient( 6524):   "code": 401,
W/ApiaryClient( 6524):   "message": "Login Required"
W/ApiaryClient( 6524):  }
W/ApiaryClient( 6524): }
,W/ApiaryClient( 6524): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6524): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=1998408275161122779&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6524): Headers:
W/ApiaryClient( 6524): accept-encoding: [gzip]
W/ApiaryClient( 6524): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6524): gdata-version: 2
E/BooksSync( 6524): Soft error: 
E/BooksSync( 6524): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6524): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=1998408275161122779&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6524): Headers:
E/BooksSync( 6524): accept-encoding: [gzip]
E/BooksSync( 6524): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6524): gdata-version: 2
E/BooksSync( 6524): 
E/BooksSync( 6524): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6524): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6524): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6524): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6524): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6524): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6524): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6524): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6524): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6524): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6524): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6524): {
E/BooksSync( 6524):  "error": {
E/BooksSync( 6524):   "errors": [
E/BooksSync( 6524):    {
E/BooksSync( 6524):     "domain": "global",
E/BooksSync( 6524):     "reason": "required",
E/BooksSync( 6524):     "message": "Login Required",
E/BooksSync( 6524):     "locationType": "header",
E/BooksSync( 6524):     "location": "Authorization"
E/BooksSync( 6524):    }
E/BooksSync( 6524):   ],
E/BooksSync( 6524):   "code": 401,
E/BooksSync( 6524):   "message": "Login Required"
E/BooksSync( 6524):  }
E/BooksSync( 6524): }
E/BooksSync( 6524): 
E/BooksSync( 6524): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6524): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6524): 	... 8 more
,E/BooksSync( 6524): Sync error
E/BooksSync( 6524): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6524): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=1998408275161122779&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6524): Headers:
E/BooksSync( 6524): accept-encoding: [gzip]
E/BooksSync( 6524): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6524): gdata-version: 2
E/BooksSync( 6524): 
E/BooksSync( 6524): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6524): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6524): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6524): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6524): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6524): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6524): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6524): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6524): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6524): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6524): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6524): {
E/BooksSync( 6524):  "error": {
E/BooksSync( 6524):   "errors": [
E/BooksSync( 6524):    {
E/BooksSync( 6524):     "domain": "global",
E/BooksSync( 6524):     "reason": "required",
E/BooksSync( 6524):     "message": "Login Required",
E/BooksSync( 6524):     "locationType": "header",
E/BooksSync( 6524):     "location": "Authorization"
E/BooksSync( 6524):    }
E/BooksSync( 6524):   ],
E/BooksSync( 6524):   "code": 401,
E/BooksSync( 6524):   "message": "Login Required"
E/BooksSync( 6524):  }
E/BooksSync( 6524): }
E/BooksSync( 6524): 
E/BooksSync( 6524): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6524): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6524): 	... 8 more
I/BooksSync( 6524): Finished books sync
D/SyncManager( 1029): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 246325, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=2.4, 0.0, 0.0  rx=3.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1578907541] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=2.4, 0.0, 0.0  rx=3.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1578907538] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=2.7, 0.0, 0.0  rx=3.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1578904513] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=2.7, 0.0, 0.0  rx=3.7 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1578904509] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,I/jxcore-log( 6055): --= Surplus to requirements =--
I/jxcore-log( 6055): 
I/jxcore-log( 6055): ****TEST TOOK:  ms ****
I/jxcore-log( 6055): ,
I/jxcore-log( 6055): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6055): 
,D/AndroidRuntime( 7460): 
D/AndroidRuntime( 7460): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7460): CheckJNI is OFF
D/AndroidRuntime( 7460): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1029): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
I/ActivityManager( 1029): Killing 6055:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
,W/PackageSettings( 1029): Skipping PackageSetting{1933a5d2 com.example.hello/10319} due to missing metadata
,I/WindowState( 1029): WIN DEATH: Window{12ab8aff u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService( 1029): Client connection lost with reason: 4
D/InputDispatcher( 1029): Window went away: Window{12ab8aff u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/ActivityManager( 1029):   Force finishing activity ActivityRecord{14916358 u0 com.test.thalitest/.MainActivity t4}
,E/GBMv2   (  343): DFP En is all cleared set to be enabled
,W/ActivityManager( 1029): Spurious death for ProcessRecord{1daab19c 6055:com.test.thalitest/u0a311}, curProc for 6055: null
I/ActivityManager( 1029): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
I/ActivityManager( 1029):   Force finishing activity ActivityRecord{14916358 u0 com.test.thalitest/.MainActivity t4 f}
W/ActivityManager( 1029): Duplicate finish request for ActivityRecord{14916358 u0 com.test.thalitest/.MainActivity t4 f}
I/[LGHome]EVENT( 2083): [Launcher.java:5338:onStart()]onStart
I/[LGHome]EVENT( 2083): [Launcher.java:903:onResume()]onResume
D/SplitWindowPolicy( 1961): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
,D/SplitWindowPolicy( 1961): topRunningActivity=ActivityInfo{2fb945ea co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
D/SplitWindowPolicy( 1961): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1961): topRunningActivity=ActivityInfo{22c40db co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[LGHome]EVENT( 2083): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 2083): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/ActionManagerService( 1919): notifyUserLog: 1000003
D/LIA_Informant_ActionManagerMessageHandler( 2720): handleMessage: what(1000) actionID(0x1000003)
I/[LGHome]GBoardWebView( 2083): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
D/KeyguardModel( 1454): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/[LGHome]LGActivityUtil( 2083): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/InputReader( 1029): Reconfiguring input devices.  changes=0x00000010
,I/art     ( 4224): Explicit concurrent mark sweep GC freed 21826(1265KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 524us total 51.848ms
D/LIA_MrGDBLogger_PackageInfoDetector( 2720): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
D/LIA_Service_RemotePackageHandler( 2038): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
,W/GeofencerStateMachine( 1832): Ignoring removeGeofence because network location is disabled.
E/LGBluetoothAvrcpQcomAdapter( 6118): [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
D/LGBluetoothAvrcpQcomAdapter( 6118): [BTUI] [+] updateMediaPlayerInfo
W/System.err( 4179): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 4179): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4179): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4179): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4179): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4179): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4179): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4179): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4179): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4179): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4179): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4179): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
V/SIM_STK ( 1029): Menu title from STK is T-Mobile
,I/ActivityManager( 1029): Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=7485 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/[LGHome]EVENT( 2083): [Launcher.java:1056:onResume()]onResume end
,I/[LGHome]EVENT( 2083): [Launcher.java:1114:onPause()]onPause
,I/[SystemUI]QSlideListController( 1454): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]GBoardWebView( 2083): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
D/ActionManagerService( 1919): notifyUserLog: 1000004
D/LIA_Informant_ActionManagerMessageHandler( 2720): handleMessage: what(1000) actionID(0x1000004)
V/BoardContentProvider( 2720): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
I/GBoardWebViewUtils( 2083): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2083): , create_time: 1430558575574
I/GBoardWebViewUtils( 2083): , expire_time: 0
I/GBoardWebViewUtils( 2083): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2083): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2083): , display: false
I/GBoardWebViewUtils( 2083): , animation: false }
I/GBoardWebViewUtils( 2083): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2083): , create_time: 1430558575600
I/GBoardWebViewUtils( 2083): , expire_time: 0
I/GBoardWebViewUtils( 2083): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2083): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2083): , display: false
I/GBoardWebViewUtils( 2083): , animation: false }
I/GBoardWebViewUtils( 2083): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1453982949437
I/GBoardWebViewUtils( 2083): , create_time: 1453982950152
I/GBoardWebViewUtils( 2083): , expire_time: 0
I/GBoardWebViewUtils( 2083): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide.html?id=guide_1111111111116_1453982949437&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2083): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2083): , display: false
I/GBoardWebViewUtils( 2083): , animation: false }
,D/WallpaperManager( 2083): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
D/KeyguardModel( 1454): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1454): createShortcutInfo...
,I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1454): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1454): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
I/SystemUI[Framework]( 1029): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1029): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1029): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1029): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1029): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@5ab3a44,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1029): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/KeyguardModel( 1454): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1454): createShortcutInfo...
,I/[LGHome]GBoardWebView( 2083): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
W/ResourcesManager( 1454): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1454): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1454): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1454): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1454): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1454): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/SplitUIManager( 1885): split_name #11 / not available #0
D/SplitUIService( 1885): removed split : 
D/KeyguardModel( 1454): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1454): createShortcutInfo...
,I/art     ( 1029): Explicit concurrent mark sweep GC freed 17815(1169KB) AllocSpace objects, 5(336KB) LOS objects, 33% free, 44MB/66MB, paused 1.823ms total 219.240ms
I/art     ( 1029): WaitForGcToComplete blocked for 83.132ms for cause Explicit
W/ResourcesManager( 1454): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1454): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1454): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1454): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,W/ResourcesManager( 7485): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
V/SIM_STK ( 1029): Menu title from STK is T-Mobile
V/SIM_STK ( 1029): Menu title from STK is T-Mobile
D/SplitUIManager( 1885): split_name #11 / not available #0
I/SplitUIService( 1885): split app #11
D/KeyguardModel( 1454): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1454): createShortcutInfo...
,W/ResourcesManager( 1454): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1454): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1454): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1454): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1454): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1454): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1454): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1454): createShortcutInfo...
D/administrator( 1029): Handling package changes for user 0
I/[LGHome]EVENT( 2083): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/PluginManager( 7485): init()
,I/[LGHome]EVENT( 2083): [Launcher.java:5349:onStop()]onStop
,D/KeyguardModel( 1454): handleShortcutListChanged...
V/SIM_STK ( 1029): Menu title from STK is T-Mobile
W/ActivityManager( 1029): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
D/KeyguardModel( 1454): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/LGBluetoothAvrcpQcomAdapter( 6118): [BTUI] installed app name: Music
D/KeyguardModel( 1454): createShortcutInfo...
D/LGBluetoothAvrcpQcomAdapter( 6118): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6118): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 6118): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 6118): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 6118): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6118): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 6118): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6118): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 6118): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6118): [BTUI] [-] updateMediaPlayerInfo
D/KeyguardModel( 1454): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1454): createShortcutInfo...
,W/ResourceType( 1454): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1454): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1454): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1454): createShortcutInfo...
W/ResourceType( 1454): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1454): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1454): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1454): createShortcutInfo...
,W/ResourceType( 1454): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1454): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1454): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1454): createShortcutInfo...
D/KeyguardModel( 1454): handleShortcutListChanged...
I/[LGHome]Launcher.Model( 2083): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 2083): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2083): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2083): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2083): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2083): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/NotificationService( 1029): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1029): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1029): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister( 1029): removeObsoleteFile: deleting file=4_task.xml
D/PhoneStatusBar( 1454): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
I/[SystemUI]NavigationThemeResource( 1454): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1454):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1454): , Keyguard show=false, IME shown=false, Panel expanded=false
I/[LGHome]Launcher.Model( 2083): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2083): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/Timeline( 1029): Timeline: Activity_windows_visible id: ActivityRecord{1a9ade19 u0 com.lge.launcher2/.Launcher t3} time:256768
,I/ThermalEngine(  337): Thermal-Server: Thermal received msg from  override
I/Thermal-Lib( 3070): Thermal-Lib-Client: Client request sent
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2083): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2083): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/[LGHome]EVENT( 2083): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 2083): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2083): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/[Concierge]WidgetView( 2083): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
D/[Concierge]Service( 2607): onStartCommand(). Type : 8
D/[Concierge]Service( 2607): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/[Concierge]Service( 2607): Update widget ID : 11
D/[Concierge]WidgetView( 2083): change position of spinner
I/[Concierge]WidgetView( 2083): initWebView(). Time : 1454415010658
,D/[Concierge]Service( 2607): onStartCommand(). Type : 0
I/art     ( 1029): Explicit concurrent mark sweep GC freed 6756(415KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 2.457ms total 221.012ms
,I/[Concierge]WebView( 2083): Return exist ConciergeWebView. Reuse : 122494931
D/[Concierge]WidgetView( 2083): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2083): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
I/[LgeWidgetLib]ExtViewHost( 2083): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@14f558a
I/[LGHome]EVENT( 2083): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2083): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2083): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
W/ResourcesManager( 1029): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/[LGHome]EVENT( 2083): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/[Concierge]WidgetView( 2083): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2083): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
W/[Concierge]WidgetView( 2083): Widget kill message received. Destory myself. My : 1454414782771, New one : 1454415010658
D/[Concierge]WidgetView( 2083): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2083): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,I/[LGHome]Launcher( 2083): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2083): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2083): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2083): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
W/ResourceType( 1029): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/[LGHome]EVENT( 2083): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2083): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2083): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2083): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LgeWidgetLib]LgeAppWidgetHostView( 2083): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
E/[LgeWidgetLib]LgeAppWidgetHostView( 2083): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2083): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
,I/[LGHome]EVENT( 2083): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/[LGHome]Launcher( 2083): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
D/AndroidRuntime( 7460): Shutting down VM
,I/Timeline( 2083): Timeline: Activity_idle id: android.os.BinderProxy@680d47e time:256915
W/ExternalStrings( 7485): load override strings
W/ExternalStrings( 7485): java.lang.RuntimeException: Unexpected tag, got eat-comment
W/ExternalStrings( 7485): 	at com.mcafee.plugin.af.a(Unknown Source)
W/ExternalStrings( 7485): 	at com.mcafee.plugin.ac.b(Unknown Source)
W/ExternalStrings( 7485): 	at com.mcafee.plugin.ak.d(Unknown Source)
W/ExternalStrings( 7485): 	at com.mcafee.plugin.ak.a(Unknown Source)
W/ExternalStrings( 7485): 	at com.mcafee.app.s.getClassLoader(Unknown Source)
W/ExternalStrings( 7485): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
W/ExternalStrings( 7485): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
W/ExternalStrings( 7485): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
W/ExternalStrings( 7485): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
W/ExternalStrings( 7485): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
W/ExternalStrings( 7485): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ExternalStrings( 7485): 	at android.os.Looper.loop(Looper.java:135)
W/ExternalStrings( 7485): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/ExternalStrings( 7485): 	at java.lang.reflect.Method.invoke(Native Method)
W/ExternalStrings( 7485): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/ExternalStrings( 7485): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/ExternalStrings( 7485): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,D/StatusProvider( 7485): onCreate
V/Signer  ( 7485): override build config not found
,D/Signer  ( 7485): value of property debug is false
I/chromium( 2083): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,D/LGMDMWrapper( 7485): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
D/LGMDMWrapper( 7485): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
D/LGMDMWrapper( 7485): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
D/LGMDMWrapper( 7485): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
D/LGMDMWrapper( 7485): Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
D/LGMDMWrapper( 7485): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
D/LGMDMWrapper( 7485): Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
D/LGMDMWrapper( 7485): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
D/LGMDMWrapper( 7485): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
D/LGMDMWrapper( 7485): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
D/LGMDMWrapper( 7485): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
D/LGMDMWrapper( 7485): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
D/LGMDMWrapper( 7485): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
,V/LGMDMManager( 7485): Create singleton instance
I/GBoardtInterface( 2083): onReloaded()
,I/GBoardWebViewClient( 2083): onPageFinished url:file:///android_asset/www/main.html
V/BoardContentProvider( 2720): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
V/BoardContentProvider( 2720): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/ActionManagerService( 1919): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 2720): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 2720): onEvent() : ACTION_BOARD_ENABLED
D/ActionManagerService( 1919): notifyUserLog: 1000001
,D/LIA_Informant_ActionManagerMessageHandler( 2720): handleMessage: what(1000) actionID(0x1000001)
,D/LIA_Informant_Tips_SmartTipsActionManager( 2720): onEvent() : ACTION_BOARD_ENABLED
D/LIA_Informant_Tips_FormEventRepository( 2720): getSize() : size - 0
D/LIA_Informant_Tips_SmartTipsActionManager( 2720): onSettingEvent() : GBoard On - add scheduler - 0
V/BoardContentProvider( 2720): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/GBoardUriUtils( 2083): fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
D/GBoardWebViewUtils( 2083): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
D/GBoardUriUtils( 2083): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
D/GBoardWebViewUtils( 2083): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
D/GBoardUriUtils( 2083): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide2.html?id=guide_1111111111116_1453982949437&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
D/GBoardWebViewUtils( 2083): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide2.html?id=guide_1111111111116_1453982949437&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
D/LGMDMWrapper( 7485): LG MDM library v4.0.0 is available on this device.
,D/PostponalbeReceiver( 7485): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,W/ContextImpl( 7485): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
D/AppUp4:PreloadHelper( 7176): added Exclude : com.test.thalitest
,I/ActivityManager( 1029): Killing 6860:com.android.calendar/u0a13 (adj 15): empty #17
W/ActivityThread( 7485): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,E/SQLiteDatabase( 7485): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 7485): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7485): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7485): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.ConfigManager.c(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.ConfigManager.ab(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.fw.ws.WSLicenseService.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.g.b.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.applock.AppLockComponent.a_(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.applock.AppLockComponent.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7485): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7485): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7485): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7485): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7485): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7485): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7485): 	at com.mcafee.d.c.run(Unknown Source)
,W/libprocessgroup( 1029): failed to open /acct/uid_10013/pid_6860/cgroup.procs: No such file or directory
E/SQLiteLog( 2194): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
D/VoicemailCleanupService( 2194): Cleaning up data for package: com.test.thalitest
D/ContactsProvider2ForLG( 2194): performBackgroundTask SQLiteDiskIOException during query
D/ContactsProvider2ForLG( 2194): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
D/ContactsProvider2ForLG( 2194): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
D/ContactsProvider2ForLG( 2194): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:560)
D/ContactsProvider2ForLG( 2194): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
D/ContactsProvider2ForLG( 2194): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
D/ContactsProvider2ForLG( 2194): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
D/ContactsProvider2ForLG( 2194): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
D/ContactsProvider2ForLG( 2194): 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:394)
D/ContactsProvider2ForLG( 2194): 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:363)
D/ContactsProvider2ForLG( 2194): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:974)
D/ContactsProvider2ForLG( 2194): 	at com.android.providers.contacts.ContactsProvider2ForLG.performBackgroundTask(ContactsProvider2ForLG.java:375)
D/ContactsProvider2ForLG( 2194): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:748)
D/ContactsProvider2ForLG( 2194): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/ContactsProvider2ForLG( 2194): 	at android.os.Looper.loop(Looper.java:135)
D/ContactsProvider2ForLG( 2194): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteDatabase( 7485): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/lockedapplications'.
E/SQLiteDatabase( 7485): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7485): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7485): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 7485): 	at com.mcafee.applock.a.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.applock.d.d(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.applock.d.<init>(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.applock.d.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.modes.adapt.a.<init>(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.modes.adapt.a.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.modes.adapt.ModesLockHelper.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.applock.h.<init>(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.applock.f.<init>(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.applock.f.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.applock.AppLockComponent.d(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.applock.AppLockComponent.a_(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.applock.AppLockComponent.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7485): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7485): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7485): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7485): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7485): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7485): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7485): 	at com.mcafee.d.c.run(Unknown Source)
E/SQLiteOpenHelper( 7485): Couldn't open lockedapplications for writing (will try read-only):
E/SQLiteOpenHelper( 7485): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7485): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7485): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 7485): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 7485): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQ,LiteConnectionPool.java:463)
E/SQLiteOpenHelper( 7485): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 7485): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 7485): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteOpenHelper( 7485): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteOpenHelper( 7485): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteOpenHelper( 7485): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteOpenHelper( 7485): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 7485): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 7485): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 7485): 	at com.mcafee.applock.a.a(Unknown Source)
E/SQLiteOpenHelper( 7485): 	at com.mcafee.applock.d.d(Unknown Source)
E/SQLiteOpenHelper( 7485): 	at com.mcafee.applock.d.<init>(Unknown Source)
E/SQLiteOpenHelper( 7485): 	at com.mcafee.applock.d.a(Unknown Source)
E/SQLiteOpenHelper( 7485): 	at com.mcafee.modes.adapt.a.<init>(Unknown Source)
E/SQLiteOpenHelper( 7485): 	at com.mcafee.modes.adapt.a.a(Unknown Source)
E/SQLiteOpenHelper( 7485): 	at com.mcafee.modes.adapt.ModesLockHelper.a(Unknown Source)
E/SQLiteOpenHelper( 7485): 	at com.mcafee.applock.h.<init>(Unknown Source)
E/SQLiteOpenHelper( 7485): 	at com.mcafee.applock.f.<init>(Unknown Source)
E/SQLiteOpenHelper( 7485): 	at com.mcafee.applock.f.a(Unknown Source)
E/SQLiteOpenHelper( 7485): 	at com.mcafee.applock.AppLockComponent.d(Unknown Source)
E/SQLiteOpenHelper( 7485): 	at com.mcafee.applock.AppLockComponent.a_(Unknown Source)
E/SQLiteOpenHelper( 7485): 	at com.mcafee.applock.AppLockComponent.a(Unknown Source)
E/SQLiteOpenHelper( 7485): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteOpenHelper( 7485): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteOpenHelper( 7485): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteOpenHelper( 7485): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteOpenHelper( 7485): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteOpenHelper( 7485): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteOpenHelper( 7485): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 7485): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 7485): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteOpenHelper( 7485): 	at com.mcafee.d.c.run(Unknown Source)
W/SQLiteOpenHelper( 7485): Opened lockedapplications in read-only mode
E/SQLiteLog( 2194): (3850) statement aborts at 37: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
--------- beginning of crash
E/AndroidRuntime( 2194): FATAL EXCEPTION: IntentService[VoicemailCleanupService]
E/AndroidRuntime( 2194): Process: android.process.acore, PID: 2194
E/AndroidRuntime( 2194): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2194): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 2194): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:739)
E/AndroidRuntime( 2194): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
E/AndroidRuntime( 2194): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 2194): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1600)
E/AndroidRuntime( 2194): 	at com.android.providers.contacts.util.DbModifierWithNotification.delete(DbModifierWithNotification.java:161)
E/AndroidRunti,me( 2194): 	at com.android.providers.contacts.voicemail.VoicemailContentTable.delete(VoicemailContentTable.java:229)
E/AndroidRuntime( 2194): 	at com.android.providers.contacts.voicemail.VoicemailContentProvider.delete(VoicemailContentProvider.java:135)
E/AndroidRuntime( 2194): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
E/AndroidRuntime( 2194): 	at android.content.ContentResolver.delete(ContentResolver.java:1315)
E/AndroidRuntime( 2194): 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
E/AndroidRuntime( 2194): 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
E/AndroidRuntime( 2194): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2194): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2194): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 2194): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager( 1029): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=7529 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/Process ( 2194): Sending signal. PID: 2194 SIG: 9
E/DropBoxManagerService( 1029): Can't write: system_app_crash
E/DropBoxManagerService( 1029): java.io.FileNotFoundException: /data/system/dropbox/drop109.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1029): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 1029): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 1029): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 1029): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1029): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 1029): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
E/DropBoxManagerService( 1029): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1029): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1029): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 1029): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 1029): 	... 5 more
E/SQLiteDatabase( 7485): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 7485): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7485): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7485): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.ConfigManager.b(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.notificationtray.e.<init>(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.notificationtray.e.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.notificationtray.NotificationComponent.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7485): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7485): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7485): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7485): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7485): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7485): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7485): 	at com.mcafee.d.c.run(Unknown Source)
E/SQLiteDatabase( 7485): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 7485): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7485): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7485): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.ConfigManager.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.wavesecure.utils.CommonPhoneUtils.o(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.wavesecure.utils.y.v(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7485): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7485): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7485): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7485): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7485): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7485): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7485): 	at com.mcafee.d.c.run(Unknown Source)
E/SQLiteDatabase( 7485): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 7485): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7485): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7485): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.ConfigManager.d(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.wavesecure.utils.CommonPhoneUtils.o(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.wavesecure.utils.y.v(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7485): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7485): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7485): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7485): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7485): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7485): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7485): 	at com.mcafee.d.c.run(Unknown Source)
,E/SQLiteDatabase( 7485): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 7485): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7485): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7485): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.ConfigManager.c(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.ConfigManager.m(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7485): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7485): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7485): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7485): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7485): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7485): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7485): 	at com.mcafee.d.c.run(Unknown Source)
E/SQLiteDatabase( 7485): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 7485): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7485): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7485): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.ConfigManager.c(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.wavesecure.c2dm.a.d(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.wavesecure.c2dm.a.c(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.wavesecure.notification.g.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7485): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7485): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7485): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7485): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7485): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7485): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7485): 	at com.mcafee.d.c.run(Unknown Source)
D/LgDataFeature( 7485): LgDataFeature() Constructor: none
D/LgDataFeature( 7485): LgDataFeature() Constructor Done, null
I/GBoardtInterface( 2083): exportHTML()
E/SQLiteDatabase( 7485): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 7485): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7485): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7485): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.ConfigManager.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.ConfigManager.b(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.ConfigManager.J(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.wavesecure.c2dm.a.d(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.wavesecure.c2dm.a.c(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.wavesecure.notification.g.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7485): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7485): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7485): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7485): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7485): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7485): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7485): 	at com.mcafee.d.c.run(Unknown Source)
E/SQLiteDatabase( 7485): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 7485): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7485): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7485): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.ConfigManager.d(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.ConfigManager.r(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.wavesecure.notification.c.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7485): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7485): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7485): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7485): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7485): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7485): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7485): 	at com.mcafee.d.c.run(Unknown Source)
E/SQLiteDatabase( 7485): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 7485): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7485): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7485): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.ConfigManager.c(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.wavesecure.notification.r.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7485): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7485): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7485): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7485): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7485): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7485): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7485): 	at com.mcafee.d.c.run(Unknown Source)
E/SQLiteDatabase( 7485): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 7485): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7485): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7485): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.ConfigManager.c(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.wavesecure.notification.o.d(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.notificationtray.a.b.b(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.notificationtray.a.b.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.notificationtray.a.c.run(Unknown Source)
E/SQLiteDatabase( 7485): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7485): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7485): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7485): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7485): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7485): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7485): 	at com.mcafee.d.c.run(Unknown Source)
,E/SQLiteDatabase( 7485): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 7485): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7485): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7485): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.ConfigManager.c(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.wavesecure.notification.q.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7485): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7485): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7485): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7485): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7485): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7485): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7485): 	at com.mcafee.d.c.run(Unknown Source)
E/SQLiteDatabase( 7485): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 7485): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7485): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7485): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.ConfigManager.b(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.ConfigManager.aq(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.MSSComponentConfig.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.wavesecure.dataStorage.WSFeatureConfig.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.wavesecure.backup.BaseBackup.b(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.wavesecure.core.WSComponent.c(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7485): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7485): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7485): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7485): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7485): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7485): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7485): 	at com.mcafee.d.c.run(Unknown Source)
E/SQLiteDatabase( 7485): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 7485): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7485): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7485): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.ConfigManager.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.MSSComponentConfig.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.wavesecure.dataStorage.WSFeatureConfig.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.wavesecure.backup.BaseBackup.b(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.wavesecure.core.WSComponent.c(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7485): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7485): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7485): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7485): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7485): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7485): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7485): 	at com.mcafee.d.c.run(Unknown Source)
E/SQLiteDatabase( 7485): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 7485): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7485): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7485): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.ConfigManager.e(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.ConfigManager.d(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.wavesecure.dataStorage.WSFeatureConfig.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.wavesecure.backup.BaseBackup.b(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.wavesecure.core.WSComponent.c(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7485): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7485): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7485): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7485): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7485): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7485): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7485): 	at com.mcafee.d.c.run(Unknown Source)
E/SQLiteDatabase( 7485): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 7485): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7485): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7485): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.ConfigManager.c(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.ConfigManager.N(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.ConfigManager.d(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.wavesecure.dataStorage.WSFeatureConfig.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.wavesecure.backup.BaseBackup.b(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.wavesecure.core.WSComponent.c(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7485): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7485): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7485): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7485): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7485): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7485): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7485): 	at com.mcafee.d.c.run(Unknown Source)
E/SQLiteDatabase( 7485): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 7485): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7485): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7485): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.ConfigManager.b(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7485): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7485): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7485): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7485): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7485): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7485): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7485): 	at com.mcafee.d.c.run(Unknown Source)
E/SQLiteDatabase( 7485): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 7485): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7485): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7485): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.wsstorage.ConfigManager.c(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7485): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7485): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7485): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7485): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7485): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7485): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7485): 	at com.mcafee.d.c.run(Unknown Source)
I/GBoardtInterface( 2083): exportHTML()
W/ContextImpl( 7485): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
I/GBoardtInterface( 2083): exportHTML()
,I/ActivityManager( 1029): Process android.process.acore (pid 2194) has died
W/ActivityManager( 1029): Scheduling restart of crashed service com.android.providers.contacts/com.lge.providers.contacts.AliveAcoreService in 1000ms
W/ActivityManager( 1029): Scheduling restart of crashed service com.android.providers.contacts/.voicemail.VoicemailCleanupService in 11000ms
E/SiteAdvisor( 7485): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Unable to copy asset file during initialization.
E/SiteAdvisor( 7485): java.io.FileNotFoundException: /data/data/com.wsandroid.suite.lge/files/sa_oem.txt: open failed: EROFS (Read-only file system)
E/SiteAdvisor( 7485): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/SiteAdvisor( 7485): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/SiteAdvisor( 7485): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/SiteAdvisor( 7485): 	at java.io.FileWriter.<init>(FileWriter.java:42)
E/SiteAdvisor( 7485): 	at com.mcafee.android.a.c.<init>(Unknown Source)
E/SiteAdvisor( 7485): 	at com.mcafee.android.a.c.<init>(Unknown Source)
E/SiteAdvisor( 7485): 	at com.mcafee.android.a.a.<init>(Unknown Source)
E/SiteAdvisor( 7485): 	at com.mcafee.android.a.a.a(Unknown Source)
E/SiteAdvisor( 7485): 	at com.mcafee.android.mmssuite.SAComponent.a(Unknown Source)
E/SiteAdvisor( 7485): 	at com.mcafee.c.b.b(Unknown Source)
E/SiteAdvisor( 7485): 	at com.mcafee.framework.b.a(Unknown Source)
E/SiteAdvisor( 7485): 	at com.mcafee.app.t.run(Unknown Source)
E/SiteAdvisor( 7485): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SiteAdvisor( 7485): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SiteAdvisor( 7485): 	at com.mcafee.d.f.run(Unknown Source)
E/SiteAdvisor( 7485): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SiteAdvisor( 7485): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SiteAdvisor( 7485): 	at java.lang.Thread.run(Thread.java:818)
E/SiteAdvisor( 7485): 	at com.mcafee.d.c.run(Unknown Source)
E/SiteAdvisor( 7485): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/SiteAdvisor( 7485): 	at libcore.io.Posix.open(Native Method)
E/SiteAdvisor( 7485): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/SiteAdvisor( 7485): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/SiteAdvisor( 7485): 	... 18 more
,D/SiteAdvisor( 7485): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
D/SiteAdvisor( 7485): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
D/SiteAdvisor( 7485): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
D/SiteAdvisor( 7485): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
D/SiteAdvisor( 7485): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
I/SiteAdvisor( 7485): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
D/SiteAdvisor( 7485): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
,D/SiteAdvisor( 7485): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
W/ResourcesManager( 7529): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7529): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7529): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7529): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
E/SQLiteDatabase( 7485): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/csf_call_log'.
E/SQLiteDatabase( 7485): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7485): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7485): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 7485): 	at com.mcafee.utils.d.a.d(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.utils.d.a.<init>(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.csf.frame.e.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.csf.frame.l.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.csf.frame.r.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.csf.frame.s.b(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.csf.frame.FirewallFrame.c(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.csf.frame.FirewallFrame.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.csf.frame.y.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.csf.frame.r.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.csf.frame.s.run(Unknown Source)
E/SQLiteDatabase( 7485): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 7485): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 7485): 	at com.mcafee.d.e.dispatchMessage(Unknown Source)
E/SQLiteDatabase( 7485): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 7485): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteDatabase( 7485): 	at com.mcafee.csf.frame.q.run(Unknown Source)
E/SQLiteOpenHelper( 7485): Couldn't open csf_call_log for writing (will try read-only):
E/SQLiteOpenHelper( 7485): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7485): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7485): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 7485): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper(, 7485): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 7485): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 7485): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 7485): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteOpenHelper( 7485): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteOpenHelper( 7485): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteOpenHelper( 7485): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteOpenHelper( 7485): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 7485): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 7485): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 7485): 	at com.mcafee.utils.d.a.d(Unknown Source)
E/SQLiteOpenHelper( 7485): 	at com.mcafee.utils.d.a.<init>(Unknown Source)
E/SQLiteOpenHelper( 7485): 	at com.mcafee.csf.frame.e.a(Unknown Source)
E/SQLiteOpenHelper( 7485): 	at com.mcafee.csf.frame.l.a(Unknown Source)
E/SQLiteOpenHelper( 7485): 	at com.mcafee.csf.frame.r.a(Unknown Source)
E/SQLiteOpenHelper( 7485): 	at com.mcafee.csf.frame.s.b(Unknown Source)
E/SQLiteOpenHelper( 7485): 	at com.mcafee.csf.frame.FirewallFrame.c(Unknown Source)
E/SQLiteOpenHelper( 7485): 	at com.mcafee.csf.frame.FirewallFrame.a(Unknown Source)
E/SQLiteOpenHelper( 7485): 	at com.mcafee.csf.frame.y.a(Unknown Source)
E/SQLiteOpenHelper( 7485): 	at com.mcafee.csf.frame.r.a(Unknown Source)
E/SQLiteOpenHelper( 7485): 	at com.mcafee.csf.frame.s.run(Unknown Source)
E/SQLiteOpenHelper( 7485): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteOpenHelper( 7485): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteOpenHelper( 7485): 	at com.mcafee.d.e.dispatchMessage(Unknown Source)
E/SQLiteOpenHelper( 7485): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteOpenHelper( 7485): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 7485): 	at com.mcafee.csf.frame.q.run(Unknown Source)
W/SQLiteOpenHelper( 7485): Opened csf_call_log in read-only mode
,E/SQLiteDatabase( 7485): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/white_list'.
E/SQLiteDatabase( 7485): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7485): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7485): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 7485): 	at com.mcafee.csf.frame.h.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.csf.frame.a.e(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.csf.frame.a.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.csf.frame.ap.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.csf.frame.r.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.csf.frame.s.b(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.csf.frame.FirewallFrame.c(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.csf.frame.FirewallFrame.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.csf.frame.al.b(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.csf.frame.y.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.csf.frame.r.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.csf.frame.s.run(Unknown Source)
E/SQLiteDatabase( 7485): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 7485): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 7485): 	at com.mcafee.d.e.dispatchMessage(Unknown Source)
E/SQLiteDatabase( 7485): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 7485): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteDatabase( 7485): 	at com.mcafee.csf.frame.q.run(Unknown Source)
E/SQLiteOpenHelper( 7485): Couldn't open white_list for writing (will try read-only):
E/SQLiteOpenHelper( 7485): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7485): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7485): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 7485): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 7485): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 7485): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 7485): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 7485): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteOpenHelper( 7485): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQ,LiteOpenHelper( 7485): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteOpenHelper( 7485): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteOpenHelper( 7485): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 7485): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 7485): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 7485): 	at com.mcafee.csf.frame.h.a(Unknown Source)
E/SQLiteOpenHelper( 7485): 	at com.mcafee.csf.frame.a.e(Unknown Source)
E/SQLiteOpenHelper( 7485): 	at com.mcafee.csf.frame.a.a(Unknown Source)
E/SQLiteOpenHelper( 7485): 	at com.mcafee.csf.frame.ap.a(Unknown Source)
E/SQLiteOpenHelper( 7485): 	at com.mcafee.csf.frame.r.a(Unknown Source)
E/SQLiteOpenHelper( 7485): 	at com.mcafee.csf.frame.s.b(Unknown Source)
E/SQLiteOpenHelper( 7485): 	at com.mcafee.csf.frame.FirewallFrame.c(Unknown Source)
E/SQLiteOpenHelper( 7485): 	at com.mcafee.csf.frame.FirewallFrame.a(Unknown Source)
E/SQLiteOpenHelper( 7485): 	at com.mcafee.csf.frame.al.b(Unknown Source)
E/SQLiteOpenHelper( 7485): 	at com.mcafee.csf.frame.y.a(Unknown Source)
E/SQLiteOpenHelper( 7485): 	at com.mcafee.csf.frame.r.a(Unknown Source)
E/SQLiteOpenHelper( 7485): 	at com.mcafee.csf.frame.s.run(Unknown Source)
E/SQLiteOpenHelper( 7485): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteOpenHelper( 7485): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteOpenHelper( 7485): 	at com.mcafee.d.e.dispatchMessage(Unknown Source)
E/SQLiteOpenHelper( 7485): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteOpenHelper( 7485): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 7485): 	at com.mcafee.csf.frame.q.run(Unknown Source)
W/SQLiteOpenHelper( 7485): Opened white_list in read-only mode
E/SQLiteDatabase( 7485): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/black_list'.
E/SQLiteDatabase( 7485): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7485): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7485): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7485): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 7485): 	at com.mcafee.csf.frame.h.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.csf.frame.a.e(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.csf.frame.a.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.csf.frame.k.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.csf.frame.r.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.csf.frame.s.b(Unknown Source)
E/SQLiteDatabase( 7485):, 	at com.mcafee.csf.frame.FirewallFrame.c(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.csf.frame.FirewallFrame.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.csf.frame.al.b(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.csf.frame.y.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.csf.frame.r.a(Unknown Source)
E/SQLiteDatabase( 7485): 	at com.mcafee.csf.frame.s.run(Unknown Source)
E/SQLiteDatabase( 7485): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 7485): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 7485): 	at com.mcafee.d.e.dispatchMessage(Unknown Source)
E/SQLiteDatabase( 7485): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 7485): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteDatabase( 7485): 	at com.mcafee.csf.frame.q.run(Unknown Source)
E/SQLiteOpenHelper( 7485): Couldn't open black_list for writing (will try read-only):
E/SQLiteOpenHelper( 7485): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7485): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7485): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 7485): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 7485): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 7485): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 7485): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 7485): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteOpenHelper( 7485): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteOpenHelper( 7485): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteOpenHelper( 7485): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteOpenHelper( 7485): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 7485): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 7485): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 7485): 	at com.mcafee.csf.frame.h.a(Unknown Source)
E/SQLiteOpenHelper( 7485): 	at com.mcafee.csf.frame.a.e(Unknown Source)
E/SQLiteOpenHelper( 7485): 	at com.mcafee.csf.frame.a.a(Unknown Source)
E/SQLiteOpenHelper( 7485): 	at com.mcafee.csf.frame.k.a(Unknown Source)
E/SQLiteOpenHelper( 7485): 	at com.mcafee.csf.frame.r.a(Unknown Source)
E/SQLiteOpenHelper( 7485): 	at com.mcafee.csf.frame.s.b(Unknown Source)
E/SQLiteOpenHelper( 7485): 	at com.mcafee.csf.frame.FirewallFrame.c(Unknown Source)
E/SQLiteOpenHelper( 7485): 	at com.mcafee.csf.frame.FirewallFrame.a(Unknown Source)
E/SQLiteOpenHelper( 7485): 	at com.mcafee.csf.frame.al.b(Unknown Source)
E/SQLiteOpenHelper( 7485): 	at com.mcafee.csf.frame.y.a(Unknown Source)
E/SQLiteOpenHelper( 7485): 	at com.mcafee.csf.frame.r.a(Unknown Source)
E/SQLiteOpenHelper( 7485): 	at com.mcafee.csf.frame.s.run(Unknown Source)
E/SQLiteOpenHelper( 7485): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteOpenHelper( 7485): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteOpenHelper( 7485): 	at com.mcafee.d.e.dispatchMessage(Unknown Source)
E/SQLiteOpenHelper( 7485): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteOpenHelper( 7485): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 7485): 	at com.mcafee.csf.frame.q.run(Unknown Source)
W/SQLiteOpenHelper( 7485): Opened black_list in read-only mode
E/SQLiteDatabase( 7529): Failed to open database '/data/data/com.lge.email/databases/Downloads.db'.
E/SQLiteDatabase( 7529): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7529): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7529): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7529): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7529): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7529): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7529): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7529): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7529): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7529): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7529): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7529): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7529): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7529): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7529): 	at com.lge.email.ui.largefile.DownloadProvider.onCreate(DownloadProvider.java:51)
E/SQLiteDatabase( 7529): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
E/SQLiteDatabase( 7529): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
E/SQLiteDatabase( 7529): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
E/SQLiteDatabase( 7529): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
E/SQLiteDatabase( 7529): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
E/SQLiteDatabase( 7529): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
E/SQLiteDatabase( 7529): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
E/SQLiteDatabase( 7529): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7529): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 7529): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
E/SQLiteDatabase( 7529): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 7529): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 7529): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
E/SQLiteDatabase( 7529): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
W/System.err( 7529): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 7529): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 7529): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
W/System.err( 7529): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
W/System.err( 7529): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/System.err( 7529): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/System.err( 7529): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
,W/System.err( 7529): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
W/System.err( 7529): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
W/System.err( 7529): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
W/System.err( 7529): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
W/System.err( 7529): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
W/System.err( 7529): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
W/System.err( 7529): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
W/System.err( 7529): 	at com.lge.email.ui.largefile.DownloadProvider.onCreate(DownloadProvider.java:51)
W/System.err( 7529): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
W/System.err( 7529): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
W/System.err( 7529): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
W/System.err( 7529): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
W/System.err( 7529): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
W/System.err( 7529): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
W/System.err( 7529): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
W/System.err( 7529): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7529): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7529): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 7529): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7529): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7529): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 7529): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
I/ActivityManager( 1029): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2ForLG: pid=7555 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/art     (  348): Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 245us total 10.555ms
E/SQLiteDatabase( 7529): Failed to open database '/data/data/com.lge.email/databases/sqt.db'.
E/SQLiteDatabase( 7529): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7529): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7529): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7529): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7529): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7529): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7529): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7529): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7529): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7529): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7529): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7529): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7529): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7529): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7529): 	at com.lge.email.providers.sqt.SqtProvider.onCreate(SqtProvider.java:155)
E/SQLiteDatabase( 7529): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
E/SQLiteDatabase( 7529): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
E/SQLiteDatabase( 7529): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
E/SQLiteDatabase( 7529): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
E/SQLiteDatabase( 7529): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
E/SQLiteDatabase( 7529): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
E/SQLiteDatabase( 7529): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
E/SQLiteDatabase( 7529): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7529): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 7529): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
E/SQLiteDatabase( 7529): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 7529): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 7529): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
E/SQLiteDatabase( 7529): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
D/AndroidRuntime( 7529): Shutting down VM
E/AndroidRuntime( 7529): FATAL EXCEPTION: main
E/AndroidRuntime( 7529): Process: com.lge.email, PID: 7529
E/AndroidRuntime( 7529): java.lang.RuntimeException: Unable to get provider com.lge.email.providers.sqt.SqtProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7529): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5017)
E/AndroidRuntime( 7529): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
E/AndroidRuntime( 7529): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
E/AndroidRuntime( 7529): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
E/AndroidRuntime( 7529): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
E/AndroidRuntime( 7529): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7529): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 7529): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
E/AndroidRuntime( 7529): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 7529): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 7529): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
E/AndroidRuntime( 7529): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/AndroidRuntime( 7529): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7529): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7529): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 7529): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 7529): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 7529): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 7529): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 7529): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/AndroidRuntime( 7529): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/AndroidRuntime( 7529): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/AndroidRuntime( 7529): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/AndroidRuntime( 7529): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 7529): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 7529): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 7529): 	at com.lge.email.providers.sqt.SqtProvider.onCreate(SqtProvider.java:155)
E/AndroidRuntime( 7529): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
E/AndroidRuntime( 7529): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
E/AndroidRuntime( 7529): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
E/AndroidRuntime( 7529): 	... 11 more
I/Process ( 7529): Sending signal. PID: 7529 SIG: 9
E/DropBoxManagerService( 1029): Can't write: system_app_crash
E/DropBoxManagerService( 1029): java.io.FileNotFoundException: /data/system/dropbox/drop110.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1029): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 1029): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 1029): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 1029): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1029): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 1029): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
E/DropBoxManagerService( 1029): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1029): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1029): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 1029): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 1029): 	... 5 more
I/art     (  348): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 181us total 9.330ms
,E/lowmemorykiller(  276): Error writing /proc/7529/oom_score_adj; errno=22
I/ActivityManager( 1029): Killing 6817:com.lge.clock/u0a10 (adj 15): empty #17
I/art     (  348): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 184us total 9.122ms
I/ActivityManager( 1029): Killing 6884:com.google.android.talk/u0a72 (adj 15): empty #18

```
