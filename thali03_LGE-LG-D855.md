#### Test 58752353dc32d9f_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
D/MusicBrowser( 2227): [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2227): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2227): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2227): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2227): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@1d93b82f
I/MusicBrowser( 2227): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2227): [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2227): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2227): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2227): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2227): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2227): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2227): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2227): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2227): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2227): [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2227): [MediaPlaybackService.java:6704:release()] oooooo 
I/MusicBrowser( 2227): [MediaPlaybackService.java:6665:stop()] oooooo 
V/MediaPlayer[Native]( 2227): reset
V/MediaPlayer[Native]( 2227): setListener
V/MediaPlayer[Native]( 2227): disconnect
V/MediaPlayer[Native]( 2227): destructor
V/AudioFlinger(  325): releasing 13 from 2227 for -1
V/AudioFlinger(  325):  decremented refcount to 0
V/AudioFlinger(  325): purging stale effects
V/MediaPlayer[Native]( 2227): disconnect
D/MusicBrowser( 2227): [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
I/SmartShareClient( 2227): [SmartShareManagerClient] smartshare client supported version code: 305000
I/SmartShareClient( 2227): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2227): [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
I/MusicBrowser( 2227): [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2227): [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2227): [SmartShareManagerClient] unregisterListener: 595951294
W/SmartShareClient( 2227): [SmartShareManagerClient] unregisterListener invalid listener: 595951294
I/SmartShareClient( 2227): [SmartShareManagerClient] terminate service: 2227/MediaPlaybackService/915817485
E/HomeCloudIF( 2227): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2227): [SmartShareManagerClient] unbindService context:android.app.Application@11690b1f
V/CloudHub( 2227): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
V/CloudHub( 2227): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2227): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
D/MusicBrowser( 2227): [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
--------- beginning of system
I/ActivityManager( 1031): Killing 5724:com.android.defcontainer/u0a4 (adj 15): empty #17
I/CloudHub( 2227): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29988
,W/libprocessgroup( 1031): failed to open /acct/uid_10004/pid_5724/cgroup.procs: No such file or directory
D/AndroidRuntime( 6046): 
D/AndroidRuntime( 6046): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6046): CheckJNI is OFF
D/AndroidRuntime( 6046): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1031): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1961): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1031): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1031): setTaskToReturnTo : TaskRecord{31ec72a #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1031): setTaskToReturnTo : TaskRecord{31ec72a #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1031): AppWindowTokenEx init.. 
E/GBMv2   (  350): DFP En is all cleared set to be enabled
I/ActivityManager( 1031): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6063 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6046): Shutting down VM
V/ActivityManager( 1031): Display changed displayId=0
D/DSDPConnection( 1866): Display #0 changed.
D/SplitWindowPolicy( 1961): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1961): topRunningActivity=ActivityInfo{11cad948 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1961): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1961): topRunningActivity=ActivityInfo{3742a3e1 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 6063): convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,I/WebViewFactory( 6063): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 6063): Loading: webviewchromium
,I/LibraryLoader( 6063): Time to load native libraries: 5 ms (timestamps 4851-4856)
I/LibraryLoader( 6063): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6063): Binding Chromium to main looper Looper (main, tid 1) {35c51fc2}
,I/LibraryLoader( 6063): Expected native library version number "",actual native library version number ""
I/chromium( 6063): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6063): Initializing chromium process, renderers=0
,W/art     ( 6063): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6063): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
V/AudioPolicyService(  325): registerClient() client 0xb57bc0c0, uid 10311
,D/BluetoothManagerService( 1031): Message: 20
D/BluetoothManagerService( 1031): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6d61a64:true
D/BluetoothAdapter( 6063): 111661523: getState() :  mService = null. Returning STATE_OFF
W/chromium( 6063): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6063): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 6063): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
,I/Adreno-EGL( 6063): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6063): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6063): Build Date: 12/12/14 금
I/Adreno-EGL( 6063): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6063): Remote Branch: 
I/Adreno-EGL( 6063): Local Patches: 
I/Adreno-EGL( 6063): Reconstruct Branch: 
,W/chromium( 6063): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 6063): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 6063): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6063): onDetachedFromWindow called when already detached. Ignoring
I/PhoneWindow( 6063): [generateLayout] setColorNavigationBar => color=0x ff000001
D/PhoneWindowEx( 6063): [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
I/PhoneWindow( 6063): [setNavigationBarColor2] color=0x fff5f5f5
,D/SystemWebViewEngine( 6063): CordovaWebView is running on device made by: LGE
,W/art     ( 6063): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6063): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6063): Render dirty regions requested: true
,I/OpenGLRenderer( 6063): Initialized EGL, version 1.4
D/OpenGLRenderer( 6063): Enabling debug mode 0
D/Atlas   ( 6063): Validating map...
D/SplitWindow( 1031): check instance of lgWin Window{16d1bc7e u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/LgDataFeature( 6063): LgDataFeature() Constructor: none
,D/LgDataFeature( 6063): LgDataFeature() Constructor Done, null
I/ActivityManager( 1031): Displayed com.test.thalitest/.MainActivity: +597ms (total +700ms)
I/Timeline( 1031): Timeline: Activity_windows_visible id: ActivityRecord{2945c91b u0 com.test.thalitest/.MainActivity t4} time:105256
I/Timeline( 6063): Timeline: Activity_idle id: android.os.BinderProxy@23857ebe time:105259
I/chromium( 6063): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6063): 
D/JsMessageQueue( 6063): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 6063): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435202176
I/chromium( 6063): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 6063): 
I/chromium( 6063): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
E/GBMv2   (  350): DFP En is all cleared set to be enabled
E/GBMv2   (  350): Set value is all cleared set the max
I/GBMv2   (  350): DFP Enabled. Ignore VFP set
,W/jxcore-log( 6063): Initializing JXcore engine
W/jxcore-log( 6063): JXcore engine is ready
,W/Thread-694( 6114): type=1400 audit(0.0:148): avc: denied { ioctl } for path="socket:[10243]" dev="sockfs" ino=10243 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/Thread-694( 6114): type=1400 audit(0.0:149): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-694( 6114): type=1400 audit(0.0:150): avc: denied { ioctl } for path="socket:[10079]" dev="sockfs" ino=10079 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-694( 6114): type=1400 audit(0.0:151): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
,W/Thread-694( 6114): type=1400 audit(0.0:152): avc: denied { ioctl } for path="socket:[30341]" dev="sockfs" ino=30341 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
W/jxcore-log( 6063): Starting JXcore engine
,W/jxcore-log( 6063): Platform android
W/jxcore-log( 6063): 
W/jxcore-log( 6063): Process ARCH arm
W/jxcore-log( 6063): 
,I/jxcore-log( 6063): JXcore Cordova bridge is ready!
I/jxcore-log( 6063): 
W/jxcore-log( 6063): JXcore engine is started
,I/jxcore-log( 6063): Toggling radios to true
I/jxcore-log( 6063): 
,D/BluetoothManagerService( 1031): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1031): enable():  mBluetooth =null mBinding = false
,D/LocationManagerService( 1031): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1031): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1031): JNI:system_update. Event-4
D/BluetoothManagerService( 1031): Message: 1
D/BluetoothManagerService( 1031): MESSAGE_ENABLE: mBluetooth = null
D/WifiService( 1031): New client listening to asynchronous messages
,I/ActivityManager( 1031): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=6117 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,D/WifiServiceImplEx( 1031): setWifiEnabled: true pid=6063, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1031): setWifiEnabled: true pid=6063, uid=10311
E/WifiService( 1031): Invoking mWifiStateMachine.setWifiEnabled
,D/LocationManagerService( 1031): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1031): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1031): JNI:system_update. Event-4
E/WifiStateMachine( 1031):  InitialState CMD_START_SUPPLICANT 0 0
I/LGFTMITEM( 1031): [GET_FTM][id=6], offset=12288
D/WifiServiceImplEx( 1031): disconnect pid=6063, uid=10311, packageName=com.test.thalitest
D/WifiServiceImplEx( 1031): reconnect pid=6063, uid=10311, packageName=com.test.thalitest
I/jxcore-log( 6063): Radios toggled
I/jxcore-log( 6063): 
,I/jxcore-log( 6063): My device name is: LGE-LG-D855
I/jxcore-log( 6063): 
E/WifiUtil( 1031): wfc_util_ffile_check_copy(): pid[1031] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
E/WifiUtil( 1031): wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
E/WifiUtil( 1031): wfc_util_ffile_check_copy(): pid[1031] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
E/WifiUtil( 1031): wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
I/WifiUtil( 1031): Intf0MacAddress=C49A027B60AC
E/WifiHW  ( 1031): unknown target_country: EU , set to default
E/WifiHW  ( 1031): [wifi_ensure_config_files] default country1 = GB
E/WifiHW  ( 1031): [wifi_ensure_config_files] default country2 = GB
I/WifiUtil( 1031): gEnableBmps=1
,W/ResourcesManager( 6117): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager( 6117): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6117): Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 6117): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/BluetoothAdapterApp( 6117): Loading JNI Library
,D/SoftapController(  320): Softap fwReload - Ok
,D/CommandListener(  320): Setting iface cfg
D/CommandListener(  320): Trying to bring down wlan0
D/CommandListener(  320): Clearing all IP addresses on wlan0
E/WifiHW  ( 1031): Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,E/WifiStateMachine( 1031): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1031): useWiFiOffloading() : false
E/WifiStateMachine( 1031): CONFIG_LGE_WLAN_PATH : true
V/WfdStateTracker( 1961): WfdStateTracker handleDirectStateChangedEvent: 1
W/wpa_supplicant( 6143): type=1400 audit(0.0:153): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/wpa_supplicant( 6143): type=1400 audit(0.0:154): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiMonitor( 1031): startMonitoring(wlan0) with mConnected = false
D/WifiMonitor( 1031): connecting to supplicant
I/wpa_supplicant( 6143): Successfully initialized wpa_supplicant
,I/ActivityManager( 1031): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6144 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
D/Tethering( 1031): sendTetherStateChangedBroadcast 1, 0, 0
D/Tethering( 1031): InitialState.processMessage what=4
D/Tethering( 1031): sendTetherStateChangedBroadcast 0, 0, 0
I/WifiServerServiceExt( 1031): WIFI_STATE_CHANGED_ACTION [2]
D/libc-netbsd(  320): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1031): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/wpa_supplicant( 6143): rfkill: Cannot open RFKILL control device
I/wpa_supplicant( 6143): [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,D/BluetoothAdapterApp( 6117): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@30f2bbd1 Instance Count = 1
,D/BluetoothAdapterApp( 6117): onCreate
D/ProfileConfigQcom( 6117): [BTUI] HeadsetService is supported
,D/ProfileConfigQcom( 6117): Adding HeadsetService
D/ProfileConfigQcom( 6117): [BTUI] A2dpService is supported
D/ProfileConfigQcom( 6117): Adding A2dpService
D/ProfileConfigQcom( 6117): [BTUI] HidService is supported
D/ProfileConfigQcom( 6117): Adding HidService
D/ProfileConfigQcom( 6117): [BTUI] HealthService is supported
D/ProfileConfigQcom( 6117): Adding HealthService
D/LGBluetoothFeatureConfig( 6117): isSupportPan() :  mTargetOp=OPEN
D/ProfileConfigQcom( 6117): [BTUI] PanService is supported
D/ProfileConfigQcom( 6117): Adding PanService
D/ProfileConfigQcom( 6117): [BTUI] GattService is supported
D/ProfileConfigQcom( 6117): Adding GattService
D/ProfileConfigQcom( 6117): [BTUI] BluetoothMapService is supported
D/ProfileConfigQcom( 6117): Adding BluetoothMapService
D/ProfileConfigQcom( 6117): [BTUI] HeadsetClientService is NOT supported
I/ActivityManager( 1031): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6178 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,D/BluetoothManagerService( 1031): Message: 20
D/BluetoothManagerService( 1031): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1d24412e:true
D/BluetoothAdapterState( 6117): make
,W/FormManager( 6144): Network not available. Please check & try again.
I/wpa_supplicant( 6143): rfkill: Cannot open RFKILL control device
V/FormManager( 6144): Network unavailable.
V/FormManager( 6144): Network unavailable.
,I/LGFMServiceAdapter( 6117): [FM] LGFMServiceAdapter : create
I/bluedroid-qcom( 6117): init
I/BluetoothAdapterState( 6117): Entering OffState
I/bte_conf( 6117): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
I/bte_conf( 6117): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 6117): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 6117): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
D/BTIF_CORE( 6117): [BTUI] lge_load_bluetooth_address
I/bluedroid-qcom( 6117): get_profile_interface socket
I/bluedroid-qcom( 6117): get_profile_interface map_client
I/GKI_LINUX( 6117): gki_task_entry task_id=1 [BTIF] starting
D/BluetoothManagerService( 1031): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService( 1031): Message: 40
D/BluetoothManagerService( 1031): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
D/BluetoothAdapterProperties( 6117): Address is:58:3F:54:73:64:C0
D/BluetoothAdapterProperties( 6117): Name is: G3-1
D/BluetoothManagerService( 1031): Bluetooth Adapter name changed to G3-1
,D/BluetoothManagerService( 1031): Stored Bluetooth name: G3-1
W/bdaddr_loader( 6200): type=1400 audit(0.0:155): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/bdaddr_loader( 6200): type=1400 audit(0.0:156): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/bluedroid-qcom( 6117): config_hci_snoop_log
D/BluetoothManagerService( 1031): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService( 1031): Broadcasting onBluetoothServiceUp() to 7 receivers.
D/lge_bdaddr_loader( 6200): [BTUI] bdaddr_loader ::: START
D/lge_bdaddr_loader( 6200): [BTUI] bluetooth_load_bdaddress
I/LGFTMITEM( 6200): [GET_FTM][id=8], offset=16384
D/lge_bdaddr_loader( 6200): [BTUI] bdaddr to set in property : 58:3F:54:73:64:C0
I/ActivityManager( 1031): Killing 5822:com.google.android.partnersetup/u0a8 (adj 15): empty #17
V/LGMDMManagerInternal( 6117): Create singleton instance
E/lge_bdaddr_loader( 6200): [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:64:C0
D/lge_bdaddr_loader( 6200): [BTUI] bdaddr_loader ::: END
D/PCSuite ( 6178): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,D/BluetoothAdapterState( 6117): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 6117): Setting state to 11
I/BluetoothAdapterState( 6117): Bluetooth adapter state changed: 10-> 11
,I/wpa_supplicant( 6143): [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
I/LGBluetoothServiceJni( 6117): classInitNative: succeeds
D/BluetoothManagerService( 1031): Message: 60
D/BluetoothManagerService( 1031): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
I/wpa_supplicant( 6143): p2p0: CTRL-EVENT-AVOID-FREQ ranges=
I/wpa_supplicant( 6143): wlan0: CTRL-EVENT-SCAN-STARTED 
D/BluetoothManagerService( 1031): Bluetooth State Change Intent: 10 -> 11
E/WifiStateMachine( 1031):  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
E/WifiStateMachine( 1031):  SupplicantStartingState CMD_START_DRIVER 0 0
D/WifiMonitor( 1031): Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
D/WifiMonitor( 1031): Dropping event because (p2p0) is stopped
D/WifiMonitor( 1031): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiStateMachine( 1031):  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=0 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine( 1031):  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
E/WifiMonitor( 1031): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1031): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine( 1031):  SupplicantStartingState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1031):  DefaultState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1031):  SupplicantStartingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1031):  DefaultState CMD_RECONNECT 0 0
E/WifiStateMachine( 1031):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1031):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1031):  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
D/WifiNative-wlan0( 1031): doString: [DRIVER MACADDR]
D/WifiNative-wlan0( 1031):    returned Macaddr = c4:9a:02:7b:60:ac
D/WifiStateMachine( 1031): MAC Addr from driver = c4:9a:02:7b:60:ac
D/WifiOffDelayIfNotUsed( 1031): setPowerSaveActivated(false)
I/ActivityManager( 1031): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6205 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1031): Killing 5537:com.lge.appbox.client/u0a11 (adj 15): empty #17
,E/WifiStateMachine( 1031): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1031): useWiFiOffloading() : false
E/WifiStateMachine( 1031): CONFIG_LGE_WLAN_PATH : true
D/WifiNative-wlan0( 1031): doBoolean: SET update_config 1
D/WifiNative-wlan0( 1031): SET update_config 1: returned true
D/WifiConfigStore( 1031): Loading config and enabling all networks 
D/WifiNative-wlan0( 1031): doString: [LIST_NETWORKS]
,D/WifiNative-wlan0( 1031):    returned network id / ssid / bssid / flags 0	NG700	any	
D/BluetoothBondStateMachine( 6117): make
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
W/libprocessgroup( 1031): failed to open /acct/uid_10011/pid_5537/cgroup.procs: No such file or directory
D/BluetoothAdapterService( 6117): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1394d110
D/WfdService( 1961): Waiting for WifiP2p enabling
D/LGBluetoothAPIService( 1961): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/LGBluetoothServiceAdapter( 6117): [BTUI] check adapter is available - false.
D/BluetoothAdapterService( 6117): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1394d110
D/LGBluetoothServiceAdapter( 6117): [BTUI] check adapter is available - true : set adapter available.
I/WifiServerServiceExt( 1031): WIFI_STATE_CHANGED_ACTION [3]
D/LGBluetoothSettingsDBObserver( 6117): [BTUI] register observer for LG device name DB
W/libprocessgroup( 1031): failed to open /acct/uid_10008/pid_5822/cgroup.procs: No such file or directory
I/WifiServerServiceExt( 1031): batteryPsActivateMsgHandler : state:0 event:3
I/BluetoothBondStateMachine( 6117): StableState(): Entering Off State
E/WifiConfigStore( 1031): readNetworkVariablesFromSupplicantFile key=psk
,E/WifiConfigStore( 1031): readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
E/WifiConfigStore( 1031): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
D/WifiStateMachine( 1031): enableVerboseLogging : level 2
D/WifiNative-wlan0( 1031): doBoolean: SET device_name g3_global_com
D/WifiNative-wlan0( 1031): SET device_name g3_global_com: returned true
D/WifiNative-wlan0( 1031): doBoolean: SET manufacturer LGE
D/WifiNative-wlan0( 1031): SET manufacturer LGE: returned true
D/WifiNative-wlan0( 1031): doBoolean: SET model_name LG-D855
D/WifiNative-wlan0( 1031): SET model_name LG-D855: returned true
D/WifiNative-wlan0( 1031): doBoolean: SET model_number LG-D855
D/WifiNative-wlan0( 1031): SET model_number LG-D855: returned true
D/WifiNative-wlan0( 1031): doBoolean: SET serial_number LGD8553bed2d08
D/WifiNative-wlan0( 1031): SET serial_number LGD8553bed2d08: returned true
D/WifiNative-wlan0( 1031): doBoolean: SET config_methods physical_display virtual_push_button
D/WifiNative-wlan0( 1031): SET config_methods physical_display virtual_push_button: returned true
D/WifiNative-wlan0( 1031): doBoolean: SET device_type 10-0050F204-5
D/WifiNative-wlan0( 1031): SET device_type 10-0050F204-5: returned true
I/[SystemUI]BluetoothHandler( 1459): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
D/WifiStateMachine( 1031): Setting OUI to DA-A1-19
D/WifiNative-wlan0( 1031): doBoolean: SCAN_INTERVAL 120
D/WfdsService( 1961): Supplicant Connection state is changed : true
D/WfdsService( 1961): DefaultState - WIFI_SUPPLICANT_CONNECTED
D/WifiNative-wlan0( 1031): SCAN_INTERVAL 120: returned true
D/WifiNative-HAL( 1031): Setting external_sim to 1
,D/WfdsService( 1961): Set the WFDS Monitor: true
D/WifiNative-wlan0( 1031): doBoolean: SET external_sim 1
D/WifiNative-wlan0( 1031): SET external_sim 1: returned true
I/WifiNative-HAL( 1031): startHal
E/wifi    ( 1031): getStaticLongField sWifiHalHandle 0x9895b8dc
E/WifiHAL ( 1031): Could not connect handle
,D/wifi    ( 1031): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x10220e
I/WifiNative-HAL( 1031): Could not start hal
D/WifiStateMachine( 1031): Setting OUI to DA-A1-19
I/WifiNative-HAL( 1031): startHal
E/wifi    ( 1031): getStaticLongField sWifiHalHandle 0x9895b85c
E/WifiHAL ( 1031): Could not connect handle
D/wifi    ( 1031): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x102212
I/WifiNative-HAL( 1031): Could not start hal
D/WifiNative-wlan0( 1031): doBoolean: STA_AUTOCONNECT 1
D/WifiNative-wlan0( 1031): STA_AUTOCONNECT 1: returned true
E/BluetoothAdapterService( 6117): File transfer profiles supported!!
D/WifiNative-wlan0( 1031): doBoolean: DRIVER BTCOEXSCAN-STOP
I/wpa_supplicant( 6143): wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
D/WifiNative-wlan0( 1031): DRIVER BTCOEXSCAN-STOP: returned true
D/WfdsMonitor( 1961): WfdsMonitorThread create
D/WfdsMonitor( 1961): WFDS Monitor is created and started
D/WfdsService( 1961): WiFi: Supplicant connection re-established
D/WifiNative-wlan0( 1031): doBoolean: DRIVER RXFILTER-STOP
I/wpa_supplicant( 6143): wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
D/WifiNative-wlan0( 1031): DRIVER RXFILTER-STOP: returned true
D/WifiNative-wlan0( 1031): doBoolean: DRIVER RXFILTER-REMOVE 3
I/wpa_supplicant( 6143): wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
D/WifiNative-wlan0( 1031): DRIVER RXFILTER-REMOVE 3: returned true
D/WifiNative-wlan0( 1031): doBoolean: DRIVER RXFILTER-START
I/wpa_supplicant( 6143): wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
D/WifiNative-wlan0( 1031): DRIVER RXFILTER-START: returned true
D/WifiNative-wlan0( 1031): doBoolean: DRIVER RXFILTER-STOP
I/wpa_supplicant( 6143): wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
D/WifiHS20( 1031): hidePasspointNotification off =false
D/WifiNative-wlan0( 1031): DRIVER RXFILTER-STOP: returned true
D/WifiNative-wlan0( 1031): doBoolean: DRIVER RXFILTER-REMOVE 2
I/wpa_supplicant( 6143): android_multicast_filter_startstop : multicast filter set
D/WifiNative-wlan0( 1031): DRIVER RXFILTER-REMOVE 2: returned true
D/WifiNative-wlan0( 1031): doBoolean: DRIVER RXFILTER-START
I/wpa_supplicant( 6143): wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
D/WifiNative-wlan0( 1031): DRIVER RXFILTER-START: returned true
E/BluetoothAdapterService( 6117): File transfer profiles supported!!
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/WifiNative: ( 1031): [108,364,898 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiNative-wlan0( 1031): doBoolean: RECONNECT
D/WifiNative-wlan0( 1031): RECONNECT: returned true
D/WifiNative-wlan0( 1031): doString: [STATUS]
D/BluetoothHeadset( 1866): Proxy object connected
D/WifiMonitor( 1031): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=1 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/BluetoothHeadset( 1031): Proxy object connected
D/WifiNative-wlan0( 1031):    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
D/WifiNative-wlan0( 1031): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 6143): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1031): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1031): doBoolean: SET ps 1
D/WifiNative-wlan0( 1031): SET ps 1: returned true
D/LGWifiP2pService( 1031): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothHeadset( 1866): Proxy object connected
D/BluetoothHeadset( 1866): Proxy object connected
D/CommandListener(  320): Setting, iface cfg
D/HeadsetService( 6117): Received start request. Starting profile...
D/CommandListener(  320): Trying to bring up p2p0
D/WifiMonitor( 1031): startMonitoring(p2p0) with mConnected = true
D/LGWifiP2pService( 1031): P2pEnablingState
D/LGWifiP2pService( 1031): P2pEnablingState{ when=-1ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): P2p socket connection successful
D/LGWifiP2pService( 1031): P2pEnabledState
I/LGBluetoothHeadsetServiceJni( 6117): classInitNative: succeeds
D/LGBluetoothHfpAdapter( 6117): Version 1.6
E/WifiStateMachine( 1031):  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
E/WifiStateMachine( 1031):  DisconnectedState CMD_START_DRIVER 0 0
E/WifiStateMachine( 1031):  ConnectModeState CMD_START_DRIVER 0 0
E/WifiStateMachine( 1031):  DriverStartedState CMD_START_DRIVER 0 0
E/BluetoothAdapterService( 6117): File transfer profiles supported!!
E/WifiStateMachine( 1031):  DisconnectedState what:132106 1 0
E/WifiStateMachine( 1031):  ConnectModeState what:132106 1 0
E/WifiStateMachine( 1031):  DriverStartedState what:132106 1 0
I/WifiServerServiceExt( 1031): setWifiDualbandAPConnection band : 1
D/LGBluetoothFeatureConfig( 6117): isPrivacyLogsEnabled : true
E/wpa_supplicant( 6143): nWIFIDualbandAPConnection: 1
D/LGWifiP2pService( 1031): sending p2p connection changed broadcast
D/WifiNative-p2p0( 1031): doBoolean: SET persistent_reconnect 1
I/BluetoothHeadsetServiceJni( 6117): classInitNative: succeeds
D/HeadsetStateMachine( 6117): make
D/WifiNative-p2p0( 1031): SET persistent_reconnect 1: returned true
D/WifiNative-p2p0( 1031): doBoolean: SET device_name G3-1
D/WifiNative-p2p0( 1031): SET device_name G3-1: returned true
D/LGWifiP2pService( 1031): [LGE_P2P] initializeP2pSettings() check postfix
D/LGWifiP2pService( 1031): before postfix = G3-1
D/WifiScanningService( 1031): SCAN_AVAILABLE : 3
D/WifiServerServiceExt( 1031): postfix byte check : 4
D/LGWifiP2pService( 1031): after postfix = G3-1
D/RttService( 1031): SCAN_AVAILABLE : 3
D/WifiNative-p2p0( 1031): doBoolean: SET p2p_ssid_postfix -G3-1
V/WfdStateTracker( 1961): WfdStateTracker handleDirectStateChangedEvent: 2
D/WfdsService( 1961): WifiP2pState is changed : true
D/WfdsService( 1961): Receive the WFDS_ENABLE Method
D/WfdsService( 1961): Set the WFDS Monitor: true
D/WifiScanningService( 1031): DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL( 1031): startHal
D/WfdsService( 1961): Connected to the supplicant for wfds
D/RttService( 1031): DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsJNI ( 1961): doCommand: WFDS_SET TRUE
E/CtrlSupplicant( 1961): Not connected to wap_supplicant - "WFDS_SET TRUE" command dropped.
D/WfdsJNI ( 1961): wfds_send_command: [WFDS_SET TRUE] failed
D/WfdsJNI ( 1961): doCommand: WFDS_GET_MAC_ADDRESS
E/CtrlSupplicant( 1961): Not connected to wap_supplicant - "WFDS_GET_MAC_ADDRESS" command dropped.
D/WfdsJNI ( 1961): wfds_send_command: [WFDS_GET_MAC_ADDRESS] failed
D/WfdsJNI ( 1961): doCommand: IFNAME=wlan0 GET_CAPABILITY channels
E/CtrlSupplicant( 1961): Not connected to wap_supplicant - "IFNAME=wlan0 GET_CAPABILITY channels" command dropped.
D/WfdsJNI ( 1961): wfds_send_command: [IFNAME=wlan0 GET_CAPABILITY channels] failed
D/WfdsService( 1961): selectPreferredScanChannel [0]
D/WfdsService( 1961): STATE : WfdsEnabledState - enter: this device mac null
D/WfdsService( 1961): WIFI_P2P_CONNECTION_CHANGED_ACTION
D/WfdsService( 1961): isConnected: false
D/WifiNative-p2p0( 1031): SET p2p_ssid_postfix -G3-1: returned true
D/WifiNative-p2p0( 1031): doBoolean: SET device_type 10-0050F204-5
D/WifiNative-p2p0( 1031): SET device_type 10-0050F204-5: returned true
D/WifiNative-p2p0( 1031): doBoolean: SET config_methods virtual_push_button physical_display keypad
D/WifiNative-p2p0( 1031): SET config_methods virtual_push_button physical_display keypad: returned true
D/WifiNative-p2p0( 1031): doBoolean: P2P_SET conc_pref p2p
D/WifiNative-p2p0( 1031): P2P_SET conc_pref p2p: returned true
D/WifiNative-HAL( 1031): p2pGetDeviceAddress
D/WifiNative-HAL( 1031): p2pGetDeviceAddress returning 
E/WifiStateMachine( 1031):  DisconnectedState what:132096 -100 0
E/WifiStateMachine( 1031):  ConnectModeState what:132096 -100 0
E/WifiStateMachine( 1031):  DriverStartedState what:132096 -100 0
I/WifiServerServiceExt( 1031): set CMD_DISCONNECT_RSSI_LVL : -100
E/wpa_supplicant( 6143): disconnect_rssi_lvl: -100
E/CtrlSupplicant( 1961): Access OK "@android:wpa_wlan0"
E/CtrlSupplicant( 1961): Succeed to open control connection
E/CtrlSupplicant( 1961): Succeed to open monitor connection
E/WifiStateMachine( 1031):  DisconnectedState CMD_SET_COUNTRY_CODE 1 0 cz
E/WifiStateMachine( 1031):  ConnectModeState CMD_SET_COUNTRY_CODE 1 0 cz
E/WifiStateMachine( 1031):  DriverStartedState CMD_SET_COUNTRY_CODE 1 0 cz
D/WifiNative-wlan0( 1031): doBoolean: DRIVER COUNTRY CZ
D/WfdsMonitor( 1961): Supplicant connection established
I/wpa_supplicant( 6143): wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
D/WfdsService( 1961): Received the Event that WfdsMonitor is connected to supplicant
I/wpa_supplicant( 6143): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
I/wpa_supplicant( 6143): [LGE_PATCH] driver_cmd() country:CZ
I/wpa_supplicant( 6143): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiMonitor( 1031): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=2 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
I/wpa_supplicant( 6143): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/BluetoothAdapterService( 6117): File transfer profiles supported!!
E/WifiMonitor( 1031): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1031): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
D/WifiMonitor( 1031): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1031): WifiMonitor:p2p0 cnt=3 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiNative-wlan0( 1031): DRIVER COUNTRY CZ: returned true
E/WifiMonitor( 1031): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1031): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiMonitor( 1031): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1031): WifiMonitor:p2p0 cnt=4 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1031): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1031): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiStateMachine( 1031):  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
D/WfdsMonitor( 1961): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WfdsMonitor( 1961): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiStateMachine( 1031):  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine( 1031):  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
D/WifiNative-wlan0( 1031): doBoolean: DRIVER SETBAND 0
I/wpa_supplicant( 6143): wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
I/wpa_supplicant( 6143): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
D/WifiMonitor( 1031): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=5 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
E/WifiMonitor( 1031): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
E/WifiMonitor( 1031): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
E/BluetoothAdapterService( 6117): File transfer profiles supported!!
D/WifiNative-wlan0( 1031): DRIVER SETBAND 0: returned true
D/WifiNative-wlan0( 1031): doBoolean: BSS_FLUSH 0
D/WifiNative-wlan0( 1031): BSS_FLUSH 0: returned true
D/WifiNative-wlan0( 1031): doBoolean: SCAN
D/WifiNative-wlan0( 1031): SCAN: returned false
E/WifiStateMachine( 1031):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=108396  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine( 1031):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=108400  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/BluetoothAdapterService( 6117): File transfer profiles supported!!
E/WifiStateMachine( 1031):  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1031):  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1031):  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1031):  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1031):  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,D/LgDataFeature( 6117): LgDataFeature() Constructor: none
D/LgDataFeature( 6117): LgDataFeature() Constructor Done, null
I/StatusBar.NetworkController( 1459): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1459): mWifiConnected = false, mWifiLevel = 0
E/wifi    ( 1031): getStaticLongField sWifiHalHandle 0x94f6b99c
E/WifiHAL ( 1031): Could not connect handle
D/wifi    ( 1031): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x10223a
I/WifiNative-HAL( 1031): Could not start hal
E/WifiScanningService( 1031): could not start HAL
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/LGWifiP2pService( 1031): DeviceAddress: 
D/WifiNative-p2p0( 1031): doBoolean: P2P_FLUSH
I/WfdStateTracker( 1961): handleP2pThisDeviceChanged
D/WifiServerServiceExt( 1031): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1031): setSupplicantStateSCANNING
D/HeadsetStateMachine( 6117): max_hf_connections = 1
I/bluedroid-qcom( 6117): get_profile_interface handsfree
D/WifiNative-p2p0( 1031): P2P_FLUSH: returned true
D/WifiNative-p2p0( 1031): doBoolean: P2P_SERVICE_FLUSH
D/WfdsService( 1961): WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
D/WfdsService( 1961): Update P2p Interface State: 3
D/WifiNative-p2p0( 1031): P2P_SERVICE_FLUSH: returned true
D/WifiNative-p2p0( 1031): doString: [LIST_NETWORKS]
D/WifiNative-p2p0( 1031):    returned network id / ssid / bssid / flags
D/WifiNative-p2p0( 1031): doBoolean: SAVE_CONFIG
V/ToneGenerator( 6117): ToneGenerator constructor: streamType=8, volume=1.000000
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
E/BluetoothAdapterService( 6117): File transfer profiles supported!!
V/AudioPolicyService(  325): registerClient() client 0xb558a820, uid 1002
V/AudioPolicyManager(  325): getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  325): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  325): getOutput() returns output 2
V/AudioSystem( 6117): getOutputSamplingRate() no output descriptor for output 2 in gOutputs
I/StatusBar.NetworkController( 1459): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1459): mWifiConnected = false, mWifiLevel = 0
V/AudioFlinger(  325): registerClient() client 0xb1433040, pid 6117
V/AudioSystem(  325): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  325): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1031): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1459): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1031): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1459): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 6117): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1866): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1866): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 2227): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 2227): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 3275): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 3275): ioConfigChanged() opening already existing output! 2
V/AudioSystem(  325): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 6117): ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
V/AudioSystem(  325): ioConfigChanged() opening already existing output! 4
V/ToneGenerator( 6117): Create Track: 0xb4928080
V/AudioTrack( 6117): set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
V/AudioTrack( 6117): set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
V/AudioSystem( 1866): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1866): ioConfigChanged() opening already existing output! 4
V/AudioPolicyManager(  325): getOutputForAttr() usage=3, content=4, tag= flags=00000000
V/AudioSystem( 6117): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 6117): ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
V/AudioPolicyManager(  325): getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  325): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  325): getOutput() returns output 2
V/AudioSystem( 1031): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1031): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 3275): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 3275): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1459): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1459): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 2227): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 2227): ioConfigChanged() opening already existing output! 4
I/AudioFlinger(  325): isAudioPlaybackHookOn() false
V/AudioPolicyManager(  325): getOutputForAttr() usage=3, content=4, tag= flags=00000000
V/AudioPolicyManager(  325): getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
V/AudioPolicyManagerEx(  325): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  325): getOutput() returns output 2
V/AudioSystem( 6117): getLatency() output 2, latency 50
V/AudioSystem( 6117): getFrameCount() output 2, frameCount 960
V/AudioTrack( 6117): createTrack_l() output 2 afLatency 50
V/AudioFlinger(  325): [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
V/AudioFlinger(  325): [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
V/AudioFlinger(  325): [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
V/AudioFlinger(  325): [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
V/AudioFlinger(  325): createTrack() lSessionId: 16
V/AudioTrack( 6117): AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiNative-p2p0( 1031): SAVE_CONFIG: returned true
D/LGWifiP2pService( 1031): sending p2p persistent groups changed broadcast
D/LGWifiP2pService( 1031): InactiveState
D/LGWifiP2pService( 1031): InactiveState{ when=-44ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): P2pEnabledState{ when=-44ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1031): doBoolean: DRIVER COUNTRY CZ
I/wpa_supplicant( 6143): wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
I/wpa_supplicant( 6143): p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
I/wpa_supplicant( 6143): [LGE_PATCH] driver_cmd() country:CZ
I/wpa_supplicant( 6143): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
I/wpa_supplicant( 6143): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiService( 1031): New client listening to asynchronous messages
D/WfdsMonitor( 1961): Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
D/WfdsMonitor( 1961): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WfdsMonitor( 1961): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
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
D/LGWifiP2pService( 1031): InactiveState{ when=-13ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): P2pEnabledState{ when=-13ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): InactiveState{ when=-3ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): P2pEnabledState{ when=-3ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): DefaultState{ when=-3ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): InactiveState{ when=-3ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): P2pEnabledState{ when=-3ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): DefaultState{ when=-3ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): InactiveState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): P2pEnabledState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): DefaultState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): InactiveState{ when=0 what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): P2pEnabledState{ when=0 what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): DefaultState{ when=0 what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
W/WfdsService( 1961): DefaultState - msg [9441285] is not handled
E/WifiServerServiceExt( 1031): No p2p device connected
V/AudioFlinger(  325): acquiring 16 from 6117, for 6117
V/AudioFlinger(  325):  added new entry for 16
V/ToneGenerator( 6117): ToneGenerator INIT OK, time: 108450
D/BluetoothAdapterService( 6117): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1394d110
D/HeadsetStateMachine( 6117): Enter Disconnected: -2, size: 0
D/HeadsetPhoneState( 6117): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 6117): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetStateMachine( 6117): [BTUI] change sampling rate to 8000 when device is disconnected
V/AudioFlinger(  325): setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6117
D/BluetoothAdapterService( 6117): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1394d110
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
V/ToneGenerator( 6117): ToneGenerator destructor
V/ToneGenerator( 6117): stopTone
V/ToneGenerator( 6117): Delete Track: 0xb4928080
V/AudioTrack( 6117): ~AudioTrack, releasing session id from 6117 on behalf of 6117
V/AudioFlinger(  325): releasing 16 from 6117 for 6117
V/AudioFlinger(  325):  decremented refcount to 0
V/AudioFlinger(  325): purging stale effects
V/AudioPolicyService(  325): AudioCommandThread() adding release output 2
V/AudioPolicyService(  325): inserting command: 6 at index 0, num commands 0
D/BluetoothA2dp( 1031): Proxy object connected
V/AudioFlinger(  325): PlaybackThread::Track destructor
V/AudioFlinger(  325): removeClient_l() pid 6117, calling pid 325
V/AudioPolicyService(  325): AudioCommandThread() waking up
V/AudioPolicyService(  325): AudioCommandThread() processing release output 2
V/AudioPolicyManager(  325): releaseOutput() 2
V/AudioPolicyService(  325): AudioCommandThread() going to sleep
D/A2dpService( 6117): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 6117): classInitNative: succeeds
V/Avrcp   ( 6117): make
D/Avrcp   ( 6117): [BTUI] Use Native AVRCP : init jni
I/bluedroid-qcom( 6117): get_profile_interface avrcp
V/LGMDMManager( 6117): Create singleton instance
I/BluetoothAdapterState( 6117): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
V/AudioManager( 6117): registerRemoteController: size of Media player list: 0
,E/AudioManager( 6117): No RCC entry present to update
E/RemoteController( 6117): Cannot set synchronization mode on an unregistered RemoteController
W/ResourcesManager( 6205): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6205): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6205): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6205): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
I/BluetoothAvrcpQcomServiceJni( 6117): classInitQcomNative: succeeds
W/ResourcesManager( 6205): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/LGBluetoothAvrcpQcomAdapter( 6117): [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
I/BluetoothAvrcpQcomServiceJni( 6117): initQcomNative: succeeds
W/ResourcesManager( 6205): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/LGBluetoothAvrcpQcomAdapter( 6117): [BTUI] [+] updateMediaPlayerInfo
V/SIM_STK ( 1031): Menu title from STK is T-Mobile
V/SIM_STK ( 1031): Menu title from STK is T-Mobile
,I/wpa_supplicant( 6143): [LGE_PATCH]scan interval[0] = 2 sec.
D/WfdsMonitor( 1961): Event [CTRL-EVENT-SCAN-RESULTS ]
D/WfdsMonitor( 1961): Event [WPS-AP-AVAILABLE ]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=9 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1031): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1031): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=10 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1031): couldn't identify event type - WPS-AP-AVAILABLE 
E/WifiMonitor( 1031): WifiMonitor:p2p0 cnt=11 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1031): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/LGWifiP2pService( 1031): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1031): Event [IFNAME=p2p0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1031): WifiMonitor:p2p0 cnt=12 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1031): couldn't identify event type - WPS-AP-AVAILABLE 
E/WifiStateMachine( 1031):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine( 1031):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine( 1031):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine( 1031):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
I/WifiNative-HAL( 1031): startHal
E/wifi    ( 1031): getStaticLongField sWifiHalHandle 0x9895b8cc
E/WifiHAL ( 1031): Could not connect handle
D/wifi    ( 1031): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x102296
I/WifiNative-HAL( 1031): Could not start hal
D/WifiNative-wlan0( 1031): doString: [BSS RANGE=0- MASK=0x21987]
,I/ActivityManager( 1031): Killing 5558:com.android.contacts/u0a19 (adj 15): empty #17
,V/WiFiOffLoadBroadcast( 6205): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,D/WifiService( 1031): New client listening to asynchronous messages
,D/LgDataFeature( 6205): LgDataFeature() Constructor: none
D/LgDataFeature( 6205): LgDataFeature() Constructor Done, null
,D/WiFiOffLoadUpdatePriority( 6205): remove : truetruetrue
E/WifiStateMachine( 1031):  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1031):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1031):  DisconnectedState CMD_SAVE_CONFIG uid=1000 0 0
E/WifiStateMachine( 1031):  ConnectModeState CMD_SAVE_CONFIG uid=1000 0 0
,D/WifiNative-wlan0( 1031): doBoolean: SAVE_CONFIG
,D/WifiNative-wlan0( 1031): SAVE_CONFIG: returned true
D/WiFiOffLoadUpdatePriority( 6205): remove1
V/WiFiOffLoadSharedPrefsUtils( 6205): save remove
D/WiFiOffLoadBroadcast( 6205): mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
D/WiFiOffLoadBroadcast( 6205): S: false, R: false
,E/WifiStateMachine( 1031):  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1031):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/WiFiOffLoadUpdatePriority( 6205): saved SSID: "NG700"
D/WiFiOffLoadUpdatePriority( 6205): connected SSID: null
D/WiFiOffLoadUpdatePriority( 6205): private wpa: "NG700" 300
D/WifiServiceImplEx( 1031): addOrUpdateNetwork pid=6205, uid=1000, packageName=android.uid.system:1000
E/addOrUpdateNetwork( 1031):  uid = 1000 SSID "NG700" nid=0
E/WifiStateMachine( 1031):  DisconnectedState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=2
E/WifiStateMachine( 1031):  ConnectModeState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=2
E/WifiConfigStore( 1031):  key="NG700"WPA_PSK netId=0 uid=0/1000
D/WifiServerServiceExt( 1031): addOrUpdateNetwork: mThisIsFirstEnableing = false
D/WifiNative-wlan0( 1031): doBoolean: SET_NETWORK 0 ssid 4e47373030
,D/WifiNative-wlan0( 1031): SET_NETWORK 0 ssid 4e47373030: returned true
D/WifiNative-wlan0( 1031): doBoolean: SET_NETWORK 0 key_mgmt WPA-PSK
D/WifiNative-wlan0( 1031): SET_NETWORK 0 key_mgmt WPA-PSK: returned true
,D/WifiNative-wlan0( 1031): doBoolean: SET_NETWORK 0 proto WPA RSN
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
W/libprocessgroup( 1031): failed to open /acct/uid_10019/pid_5558/cgroup.procs: No such file or directory
,W/ActivityManager( 1031): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
D/WiFiOffLoadUpdatePriority( 6205):  ssid "NG700" prio 300
D/WiFiOffLoadUpdatePriority( 6205): configuration updated: 0
E/WifiStateMachine( 1031):  DisconnectedState CMD_SAVE_CONFIG uid=1000 0 0
E/WifiStateMachine( 1031):  ConnectModeState CMD_SAVE_CONFIG uid=1000 0 0
D/WifiNative-wlan0( 1031): doBoolean: SAVE_CONFIG
D/LGBluetoothAvrcpQcomAdapter( 6117): [BTUI] installed app name: Music
D/WifiNative-wlan0( 1031): SAVE_CONFIG: returned true
D/LGBluetoothAvrcpQcomAdapter( 6117): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6117): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 6117): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 6117): [BTUI]          packageName: com.lge.music
,D/LGBluetoothAvrcpQcomAdapter( 6117): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6117): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 6117): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6117): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 6117): [BTUI]          playState: 2 (PAUSED)
,D/LGBluetoothAvrcpQcomAdapter( 6117): [BTUI] [-] updateMediaPlayerInfo
I/BluetoothA2dpServiceJni( 6117): classInitNative
I/BluetoothA2dpServiceJni( 6117): classInitNative: succeeds
D/A2dpStateMachine( 6117): make
D/WiFiOffLoadUpdatePriority( 6205): configuration saved: true
I/bluedroid-qcom( 6117): get_profile_interface a2dp
I/GKI_LINUX( 6117): gki_task_entry task_id=2 [A2DP-MEDIA] starting
I/LGBluetoothA2dpServiceJni( 6117): classInitNative: succeeds
I/LGBluetoothA2dpAdapter( 6117): [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
D/BluetoothAdapterService( 6117): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1394d110
I/BluetoothHidServiceJni( 6117): classInitNative: succeeds
D/HidService( 6117): Received start request. Starting profile...
I/bluedroid-qcom( 6117): get_profile_interface hidhost
D/BluetoothAdapterService( 6117): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1394d110
I/BluetoothHealthServiceJni( 6117): classInitNative: succeeds
D/A2dpStateMachine( 6117): Enter Disconnected: -2
D/HealthService( 6117): Received start request. Starting profile...
I/bluedroid-qcom( 6117): get_profile_interface health
I/LGBluetoothHealthServiceJni( 6117): classInitNative: succeeds
D/BluetoothAdapterService( 6117): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1394d110
I/BluetoothPanServiceJni( 6117): classInitNative(L105): succeeds
,D/PanService( 6117): Received start request. Starting profile...
D/BluetoothPanServiceJni( 6117): initializeNative(L110): pan
I/bluedroid-qcom( 6117): get_profile_interface pan
I/LGBluetoothPanAdapter( 6117): [BTUI] getInstance : create [LGBluetoothPanAdapter]
D/BluetoothAdapterService( 6117): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1394d110
I/BtGatt.JNI( 6117): classInitNative(L901): classInitNative: Success!
,D/BtGatt.DebugUtils( 6117): handleDebugAction() action=null
D/BtGatt.GattService( 6117): Received start request. Starting profile...
D/BtGatt.GattService( 6117): start()
I/bluedroid-qcom( 6117): get_profile_interface gatt
D/BtGatt.AdvertiseManager( 6117): advertise manager created
D/UsbSettingsReceiver( 6205): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6205): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6205): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6205): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6205): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/BluetoothAdapterService( 6117): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1394d110
D/HeadsetStateMachine( 6117): Proxy object connected
D/LGBluetoothHfpAdapter( 6117): [BTUI] queryPhoneState
D/LGBluetoothHfpAdapter( 6117): Try to query the phonestate on bind
D/BluetoothPhoneService.BluetoothLTECall( 1866):  call mBluetoothHeadset.phoneStateChanged()
,W/BluetoothHeadset( 1866): Proxy not attached to service
D/BluetoothHeadset( 1866): java.lang.Throwable
D/BluetoothHeadset( 1866): 	at android.bluetooth.BluetoothHeadset.phoneStateChanged(BluetoothHeadset.java:826)
D/BluetoothHeadset( 1866): 	at com.android.phone.BluetoothPhoneService$BluetoothLTECall.handleQueryPhoneState(BluetoothPhoneService.java:1527)
D/BluetoothHeadset( 1866): 	at com.android.phone.BluetoothPhoneService$BluetoothLTECall.access$700(BluetoothPhoneService.java:1360)
D/BluetoothHeadset( 1866): 	at com.android.phone.BluetoothPhoneService$1.handleMessage(BluetoothPhoneService.java:268)
D/BluetoothHeadset( 1866): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BluetoothHeadset( 1866): 	at android.os.Looper.loop(Looper.java:135)
D/BluetoothHeadset( 1866): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
D/BluetoothHeadset( 1866): 	at java.lang.reflect.Method.invoke(Native Method)
D/BluetoothHeadset( 1866): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/BluetoothHeadset( 1866): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
D/BluetoothHeadset( 1866): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
D/BluetoothAdapterService( 6117): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1394d110
I/LGBluetoothMapAdapter( 6117): [BTUI] getInstance : create [LGBluetoothMapAdapter]
V/BluetoothMapService( 6117): BluetoothMapBinder()
D/BluetoothMapService( 6117): Received start request. Starting profile...
D/BluetoothMapService( 6117): start()
D/BluetoothMapEmailSettingsLoader( 6117): Found 0 applications
D/BluetoothMapEmailAppObserver( 6117): createReceiver()
D/BluetoothMapEmailAppObserver( 6117): initObservers()
D/BluetoothMapEmailAppObserver( 6117): getEnabledAccountItems()
D/BluetoothAdapterService( 6117): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1394d110
,D/BluetoothAdapterService( 6117): Profile still not running:com.android.bluetooth.gatt.GattService
D/HeadsetStateMachine( 6117): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 6117): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 6117): Disconnected process message: 11, size: 0
V/BluetoothPbapReceiver( 6117): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 6117): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6117): ***********state = 11
D/UsbSettingsControl( 6205): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6205): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 6205): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6205): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6205): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 6205): [AUTORUN] setTetherStatus() : status=false
D/BluetoothAdapterService( 6117): Profile still not running:com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 6117): Profile still not running:com.android.bluetooth.gatt.GattService
,D/BluetoothAdapterService( 6117): Profile still not running:com.android.bluetooth.gatt.GattService
V/PanService( 6117): [BTUI] SIM Extra State :ABSENT
D/BluetoothAdapterService( 6117): Profile still not running:com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 6117): Profile still not running:com.android.bluetooth.map.BluetoothMapService
V/BluetoothMapService( 6117): Handler(): got msg=1
D/BluetoothAdapterState( 6117): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid-qcom( 6117): enable
I/GKI_LINUX( 6117): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 6117): btu_task pending for preload complete event
I/bt_hci_bdroid( 6117): init
I/bt_vendor( 6117): bt-vendor : init
I/bt_vendor( 6117): bt-vendor : get_bt_soc_type
E/bt_vendor( 6117): get_bt_soc_type: Failed to get soc type
I/bt_vendor( 6117): init: Local BD Address : c0:64:73:54:3f:58
D/bt_userial_mct( 6117): userial_init
,D/bt_hci_bdroid( 6117): set_power 1
I/bt_vendor( 6117): bt-vendor : BT_VND_OP_POWER_CTRL: On
I/bt_vendor( 6117): Starting hciattach daemon
I/bt_vendor( 6117): try to set true
W/sh      ( 6245): type=1400 audit(0.0:157): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/sh      ( 6245): type=1400 audit(0.0:158): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/ActivityManager( 1031): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6246 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
D/PCSuite ( 6178): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6205): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
I/qcom-bluetooth( 6253): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
D/WiFiOffLoadBroadcast( 6205): MCCMNC not supported: null
D/LGDMClient( 3956): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,D/LGDMClient( 3956): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 3956): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
I/qcom-bluetooth( 6272): /system/etc/init.qcom.bt.sh: Transport : smd 
,I/qcom-bluetooth( 6273): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
I/qcom-bluetooth( 6275): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 6276): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
I/qcom-bluetooth( 6277): /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 6278): /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
I/libmdmdetect( 6280): ESOC framework not supported
E/Diag_Lib( 6280):  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,D/bthci_qcomm_linux( 6280): [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:64:C0)
,D/bthci_qcomm_common( 6280): [BTUI] bt_hci_qcomm_init:
D/bthci_qcomm_common( 6280): [BTUI]     BDADDR: 58:3F:54:73:64:C0
D/bthci_qcomm_common( 6280): [BTUI]     BR/EDR: Class 1
D/bthci_qcomm_common( 6280): [BTUI]     LE: Class 2
D/bthci_qcomm_common( 6280): [BTUI]     Ref Clock: 32M
D/btqsocnvmtags( 6280): [BTUI] init_riva_entries: set NORMAL power settings
I/art     ( 1031): Explicit concurrent mark sweep GC freed 48510(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 44MB/66MB, paused 2.138ms total 166.340ms
,W/FormManager( 6144): Network not available. Please check & try again.
W/ContextImpl( 3956): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/PostponalbeReceiver( 5189): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/FormManager( 6144): Network unavailable.
I/PCSuite ( 6178): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6178): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6178): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6205): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/rmt_storage(  309): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  309): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  309): wakelock acquired: 1, error no: 42
I/rmt_storage(  309): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
D/WiFiOffLoadBroadcast( 6205): MCCMNC not supported: null
V/FormManager( 6144): Network unavailable.
,D/LGDMClient( 3956): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/LGDMClient( 3956): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
D/QRemote ( 6001): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/LGDMClient( 3956): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,D/QRemote ( 6001): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
E/ActivityThread( 6246): Failed to find provider info for com.lge.lgaccount.provider
,W/LG Account v2.2( 6246): No ProfileInfo entries
I/LG Account v2.2( 6246): isEnabled: false
I/Feature ( 6246): [Lifetracker]ver: 4.21.112(40211120)
I/Feature ( 6246): [Lifetracker]Country: EU
I/Feature ( 6246): [Lifetracker]Operator: OPEN
I/Feature ( 6246): [Lifetracker]Ranking support: false
I/Feature ( 6246): [Lifetracker]Comfort support: false
I/Feature ( 6246): [Lifetracker]Accessory: true
I/Feature ( 6246): [Lifetracker]Health device: true
I/Feature ( 6246): [Lifetracker]Extra Pedometer: false
I/Feature ( 6246): [Lifetracker]Blood glucose device: false
I/Feature ( 6246): [Lifetracker]Device Number: 3
I/rmt_storage(  309): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  309): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  309): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 22
I/rmt_storage(  309): 
I/rmt_storage(  309): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
E/Diag_Lib(  897): [IMS_FATAL]| 3347 | 907 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
I/QRemote ( 6001): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/BluetoothPermissionRequest( 6205): onReceive
,D/LGBluetoothFeatureConfig( 6205):  get() - isFeatureLoaded : false
V/[BNRBootReceiver]( 5981): boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/BNRAndroBeam( 5981): [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
V/[BNRBootReceiver]( 5981): Boot Receiver Return
D/BluetoothManagerService( 1031): Message: 20
,D/BluetoothManagerService( 1031): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2a29694a:true
D/PostponalbeReceiver( 5189): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/LGBluetoothResetSettingReceiver( 6205): return without doing reset settings.
D/LGBluetoothOppAdapter( 6117): [BTUI] getInstance : create [LGBluetoothOppAdapter]
,V/WiFiOffLoadBroadcast( 6205): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6205): MCCMNC not supported: null
D/QRemote ( 6001): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6001): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6001): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/WiFiOffLoadBroadcast( 6205): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
D/WiFiOffLoadBroadcast( 6205): Not supported operator for automatic switch
,I/ActivityManager( 1031): Killing 5847:com.lge.email/u0a23 (adj 15): empty #17
W/libprocessgroup( 1031): failed to open /acct/uid_10023/pid_5847/cgroup.procs: No such file or directory
,V/BluetoothFtpReceiver( 6117): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6117): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 6117): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 6117): SapReceiver onReceive 
,V/BluetoothSapReceiver( 6117): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6117):  Bluetooth Adapter state = 11
,I/ActivityManager( 1031): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6292 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,W/ResourcesManager( 6292): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/ActivityManager( 1031): Killing 5580:com.android.gallery3d/u0a27 (adj 15): empty #17
,W/libprocessgroup( 1031): failed to open /acct/uid_10027/pid_5580/cgroup.procs: No such file or directory
,D/AuthorizationBluetoothService( 2134): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
E/QC-QMI  ( 6280): qmi_client [6280] 13: failed to locate client data
,E/QC-QMI  (  462): qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
E/QC-QMI  (  462): QMUX qmux_client_id=13 not found in qmux client list, unable to remove
I/qcom-bluetooth( 6315): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:64:c0 
,I/qcom-bluetooth( 6316): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
I/bt_vendor( 6117): bluetooth satus is on
D/bt_hci_bdroid( 6117): preload
,D/bt_userial_mct( 6117): userial_open(port:0)
I/bt_vendor( 6117): bt-vendor : BT_VND_OP_USERIAL_OPEN
,I/bt_vendor( 6117): Done intiailizing UART
I/bt_vendor( 6117): Done intiailizing UART
I/bt_userial_mct( 6117): CMD=66, EVT=66, ACL_Out=67, ACL_In=67
I/bt_vendor( 6117): Bluetooth Firmware and transport layer are initialized
D/bt_userial_mct( 6117): Entering userial_read_thread()
I/bt-btu  ( 6117): btu_task received preload complete event
W/bt-l2cap( 6117): L2CAP - L2CA_Register() called for PSM: 0x0001
W/bt-l2cap( 6117): L2CAP - L2CA_Register() called for PSM: 0x001f
W/bt-l2cap( 6117): L2CAP - L2CA_Register() called for PSM: 0x0003
I/        ( 6117): BTE_InitTraceLevels -- TRC_HCI
I/        ( 6117): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 6117): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 6117): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 6117): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 6117): BTE_InitTraceLevels -- TRC_A2D
I/        ( 6117): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 6117): BTE_InitTraceLevels -- TRC_BTM
I/        ( 6117): BTE_InitTraceLevels -- TRC_HID_HOST
I/        ( 6117): BTE_InitTraceLevels -- TRC_GAP
I/        ( 6117): BTE_InitTraceLevels -- TRC_PAN
I/        ( 6117): BTE_InitTraceLevels -- TRC_SDP
I/        ( 6117): BTE_InitTraceLevels -- TRC_GATT
I/        ( 6117): BTE_InitTraceLevels -- TRC_SMP
I/        ( 6117): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 6117): BTE_InitTraceLevels -- TRC_BTIF
W/bt-btm  ( 6117): btm_decode_ext_features_page Secure conn Controller support Enabled
E/bt-btm  ( 6117): BTM_SecRegister:p_cb_info->p_le_callback == 0xa01d7061 
E/bt-btm  ( 6117): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01d7061 
,E/bt-btif ( 6117): Calling BTA_HhEnable
E/bt-btif ( 6117): btif_storage_get_adapter_property service_mask:0x2140040
,D/BluetoothAdapterProperties( 6117): Address is:58:3F:54:73:64:C0
W/bt-l2cap( 6117): L2CAP - L2CA_Register() called for PSM: 0x0019
W/bt-l2cap( 6117): L2CAP - L2CA_Register() called for PSM: 0x0017
W/bt-l2cap( 6117): L2CAP - L2CA_Register() called for PSM: 0x001b
W/bt-l2cap( 6117): L2CAP - L2CA_Register() called for PSM: 0x0011
W/bt-l2cap( 6117): L2CAP - L2CA_Register() called for PSM: 0x0013
D/BluetoothAdapterProperties( 6117): Name is: G3-1
D/BluetoothManagerService( 1031): Bluetooth Adapter name changed to G3-1
D/BluetoothAdapterProperties( 6117): Scan Mode:20
D/BluetoothAdapterProperties( 6117): Discoverable Timeout:120
D/bt_hci_bdroid( 6117): postload
D/bt_hci_bdroid( 6117): Used up Tx Cmd credits
D/BluetoothManagerService( 1031): Stored Bluetooth name: G3-1
W/bt-l2cap( 6117): L2CAP - L2CA_Register() called for PSM: 0x000f
D/bt_hci_bdroid( 6117): Used up Tx Cmd credits
D/bt_hci_bdroid( 6117): Used up Tx Cmd credits
D/bte_conf( 6117): Device ID record 1 : primary
D/bte_conf( 6117):   vendorId            = 00c4
D/bte_conf( 6117):   vendorIdSource      = 0001
D/bt_hci_bdroid( 6117): Used up Tx Cmd credits
D/bte_conf( 6117):   product             = 13a1
D/bte_conf( 6117):   version             = 1000
D/bte_conf( 6117):   clientExecutableURL = 
E/bt_mct  ( 6117): hci lib postload completed
D/bte_conf( 6117):   serviceDescription  = 
D/bte_conf( 6117):   documentationURL    = 
D/bte_conf( 6117): bte_load_did_conf no section named DID2.
D/BluetoothAdapterState( 6117): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 6117): ScanMode =  20
D/BluetoothAdapterProperties( 6117): State =  11
D/BluetoothAdapterProperties( 6117): mDiscoverableTimeout = 120
W/bt-smp  ( 6117): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
V/LGBluetoothServiceAdapter( 6117): [BTUI] state:11, scanmode:20, timeout:120
W/bt-smp  ( 6117): Plain text(LSB ~ MSB) = ee 3c 79 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6117): Encrypted text(LSB ~ MSB) = 15 69 d4 c3 dd 79 82 58 9a 13 41 7b 48 df a0 da 
W/bt-btm  ( 6117): Stopping oneshot timer
D/BluetoothAdapterProperties( 6117): Setting state to 12
W/sh      ( 6320): type=1400 audit(0.0:159): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/sh      ( 6320): type=1400 audit(0.0:160): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,I/BluetoothAdapterState( 6117): Bluetooth adapter state changed: 11-> 12
D/BluetoothPanServiceJni( 6117): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/btif_config_util( 6117): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
D/BluetoothManagerService( 1031): Message: 60
D/BluetoothManagerService( 1031): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService( 1031): Broadcasting onBluetoothStateChange(true) to 5 receivers.
D/BluetoothA2dp( 1031): onBluetoothStateChange: up=true
I/BluetoothAdapterState( 6117): Entering On State
D/BluetoothHeadset( 1866): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1866): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1866): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1031): onBluetoothStateChange: up=true
D/LGBluetoothServiceAdapter( 6117): [BTUI] OnState
D/LGBluetoothServiceAdapter( 6117): [BTUI]         global_name: G3-1
D/LGBluetoothServiceAdapter( 6117): [BTUI]         local_name: G3-1
D/BluetoothAdapterService( 6117): [BTUI] autoConnect() : not allowed
E/BluetoothManagerService( 1031): Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
D/BluetoothManagerService( 1031): Bluetooth State Change Intent: 11 -> 12
D/BluetoothManagerService( 1031): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,D/BluetoothManagerService( 1031): Message: 40
D/BluetoothManagerService( 1031): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
W/bt-smp  ( 6117): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6117): Plain text(LSB ~ MSB) = 93 0c 64 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6117): Encrypted text(LSB ~ MSB) = 2c 42 fe 5f 24 bf 29 6b 03 fa bf 8c f1 30 fc 9b 
W/bt-btm  ( 6117): Stopping oneshot timer
,D/LGBluetoothAPIService( 1961): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/LGBluetoothAPIService( 1961): Message: 1
D/LGBluetoothAPIService( 1961): MESSAGE_BOOT_COMPLETED
I/[SystemUI]BluetoothHandler( 1459): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
I/qcom-bt-wlan-coex( 6326): /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
W/bt-smp  ( 6117): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6117): Plain text(LSB ~ MSB) = 64 86 51 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6117): Encrypted text(LSB ~ MSB) = 5c b1 29 0a 73 23 95 a3 5a 84 24 9a ee d8 a0 00 
W/bt-btm  ( 6117): Stopping oneshot timer
,D/BluetoothAdapterProperties( 6117): Discoverable Timeout:120
D/LGBluetoothDeviceModeControllManager( 6117): adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
W/bt-smp  ( 6117): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6117): Plain text(LSB ~ MSB) = e1 41 40 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6117): Encrypted text(LSB ~ MSB) = ed ea a9 59 04 f7 c2 20 7a b4 03 75 0f 49 e6 c7 
W/bt-btm  ( 6117): Stopping oneshot timer
D/LGBluetoothDeviceModeControllManager( 6117): [BTUI] checkDeviceModeAndSet, sinkMode : false
I/BluetoothMapService( 6117): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 6117): STATE_ON
V/BluetoothMapService( 6117): Handler(): got msg=1
D/BluetoothMapMasInstance( 6117): Map Service startRfcommSocketListener
W/bt-smp  ( 6117): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6117): Plain text(LSB ~ MSB) = 96 1d 46 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6117): Encrypted text(LSB ~ MSB) = 7c 53 c6 39 e1 0f fc 67 2d 28 67 c9 88 94 31 61 
W/bt-btm  ( 6117): Stopping oneshot timer
I/LGBluetoothAPIService( 1961): [BTUI] LGBluetoothAPIService Binding Success
,D/BluetoothMapMasInstance( 6117): MAS initSocket()
D/BluetoothMapMasInstance( 6117):   masId = 00
D/BluetoothMapMasInstance( 6117):   msgTypes = 0e
D/BluetoothMapMasInstance( 6117):   masName = SMS/MMS
D/BluetoothMapMasInstance( 6117):   SDP string = 000eSMS/MMS
D/BluetoothManagerService( 1031): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6117): getBluetoothService() called with no BluetoothManagerCallback
W/ContextImpl( 6205): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
D/LGBluetoothAPIServer( 6117): [BTUI] onCreate()
D/LGBluetoothAPIServer( 6117): [BTUI] onBind()
D/LGBluetoothServiceAdapter( 6117): [BTUI] createSocketChannel FD=73 mFd=0
V/BluetoothMapMasInstance( 6117): Succeed to create listening socket 
D/BluetoothMapMasInstance( 6117): Accepting socket connection...
D/BluetoothAdapterProperties( 6117): Scan Mode:21
D/LGBluetoothDeviceModeControllManager( 6117): getDeviceMode  deviceMode 0
,D/LGBluetoothAPIService( 1961): [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
D/LGBluetoothAPIService( 1961): Message: 100
D/LGBluetoothAPIService( 1961): MESSAGE_BLUETOOTH_SERVICE_CONNECTED
D/LocalBluetoothProfileManager( 6205): Adding local A2DP profile
D/BluetoothAdapterService( 6117): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1394d110
,V/BluetoothPbapService( 6117): Pbap Service onCreate
V/BluetoothPbapService( 6117): Starting PBAP service
D/LGBluetoothPbapAdapter( 6117): [BTUI] getInstance : create
V/BluetoothPbapService( 6117): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 6117): state: 12
V/BluetoothPbapReceiver( 6117): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 6117): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6117): ***********state = 12
D/BluetoothManagerService( 1031): Message: 30
V/BluetoothPbapService( 6117): Handler(): got msg=1
V/BluetoothPbapService( 6117): Pbap Service startRfcommSocketListener
V/BluetoothPbapService( 6117): Pbap Service initSocket
D/BluetoothManagerService( 1031): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6117): getBluetoothService() called with no BluetoothManagerCallback
D/LocalBluetoothProfileManager( 6205): Adding local HEADSET profile
D/BluetoothManagerService( 1031): Message: 30
,D/LGBluetoothServiceAdapter( 6117): [BTUI] createSocketChannel FD=75 mFd=73
V/BluetoothPbapService( 6117): Succeed to create listening socket 
V/BluetoothPbapService( 6117): Accepting socket connection...
D/BluetoothManagerService( 1031): Message: 30
D/BluetoothManagerService( 1031): Message: 30
,D/LocalBluetoothProfileManager( 6205): Adding local MAP profile
D/BluetoothMap( 6205): Create BluetoothMap proxy object
D/BluetoothManagerService( 1031): Message: 30
D/BluetoothManagerService( 1031): Message: 30
V/BluetoothPbapService( 6117): Pbap Service onBind
D/LocalBluetoothProfileManager( 6205): LocalBluetoothProfileManager construction complete
,D/LGBluetoothUserBindClient( 6205): [BTUI] initUserBindClient
W/ContextImpl( 6205): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
D/DockEventReceiver( 6205): finishStartingService: stopping service
,D/BluetoothA2dp( 6205): Proxy object connected
D/A2dpProfile( 6205): Bluetooth service connected
D/BluetoothHeadset( 6205): Proxy object connected
,D/HeadsetProfile( 6205): Bluetooth service connected
D/BluetoothInputDevice( 6205): Proxy object connected
D/HidProfile( 6205): Bluetooth service connected
D/BluetoothPan( 6205): BluetoothPAN Proxy object connected
D/PanProfile( 6205): Bluetooth service connected
D/BluetoothMap( 6205): Proxy object connected
D/MapProfile( 6205): Bluetooth service connected
,D/BluetoothMap( 6205): getConnectedDevices()
V/BluetoothMapService( 6117): getConnectedDevices()
D/BluetoothPbap( 6205): Proxy object connected
D/PbapServerProfile( 6205): Bluetooth service connected
D/LGBluetoothUserBindClient( 6205): [BTUI] onServiceConnected
D/BluetoothPermissionRequest( 6205): onReceive
D/LGBluetoothFeatureConfig( 6205): isPrivacyLogsEnabled : true
D/LGBluetoothUtils( 6205): [BTUI] FileNotFound: readProperty
D/LGBluetoothResetSettingReceiver( 6205): return without doing reset settings.
V/BluetoothOppReceiver( 6117): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,I/LGBluetoothOppAdapter( 6117): [BTUI] startOppService()
V/BluetoothOppManager( 6117): restoreApplicationData! falsefalsenullnull
,D/LGBluetoothFeatureConfig( 6117): isPrivacyLogsEnabled : true
,V/BtOppService( 6117): onCreate
V/BluetoothOppNotification( 6117): send message
V/BtOppService( 6117): Starting RfcommListener
D/BluetoothOppPreference( 6117): Dumping Names:  
D/BluetoothOppPreference( 6117): {}
D/BluetoothOppPreference( 6117): Dumping Channels:  
D/BluetoothOppPreference( 6117): {}
V/BtOppService( 6117): onStartCommand
V/BtOppService( 6117): pendingUpdate is true keepUpdateThread is false sListenStarted is true
,V/BluetoothFtpReceiver( 6117): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpReceiver( 6117): BluetoothFtpReceiver Start Service
V/BluetoothOppNotification( 6117): new notify threadi!
V/BluetoothOppNotification( 6117): send delay message
V/BtOppService( 6117): start RfcommListener
V/BluetoothOppProvider( 6117): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
V/BtOppService( 6117): Deleted complete outbound shares, number =  0
V/BluetoothOppProvider( 6117): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,V/BluetoothOppProvider( 6117): created cursor android.database.sqlite.SQLiteCursor@222742a on behalf of 
V/BtOppService( 6117): Deleted complete inbound failed shares, number = 0
V/BluetoothOppProvider( 6117): starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6117): created cursor android.database.sqlite.SQLiteCursor@2a8c721b on behalf of 
V/BluetoothOppNotification( 6117): mUpdateCompleteNotification = true
V/BtOppService( 6117): RfcommListener started
V/BluetoothOppProvider( 6117): created cursor android.database.sqlite.SQLiteCursor@472ffb8 on behalf of 
V/BtOppRfcommListener( 6117): Starting RFCOMM listener....
D/BluetoothManagerService( 1031): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6117): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 6117): [BTUI] createSocketChannel FD=81 mFd=75
V/BtOppRfcommListener( 6117): Started RFCOMM listener....
I/BtOppRfcommListener( 6117): Accept thread started.
V/BtOppRfcommListener( 6117): Accepting connection...
V/BluetoothOppProvider( 6117): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/BtOppService( 6117): pendingUpdate is true keepUpdateThread is false sListenStarted is true
V/BluetoothOppProvider( 6117): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,V/BluetoothOppProvider( 6117): created cursor android.database.sqlite.SQLiteCursor@2f312191 on behalf of 
V/BluetoothOppNotification( 6117): update too frequent, put in queue
V/BluetoothOppProvider( 6117): created cursor android.database.sqlite.SQLiteCursor@174ba8f6 on behalf of 
V/BtOppService( 6117): pendingUpdate is false keepUpdateThread is false sListenStarted is true
V/BluetoothOppNotification( 6117): outbound: succ-0  fail-0
V/BluetoothOppNotification( 6117): outbound notification was removed.
V/BluetoothOppProvider( 6117): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
D/BluetoothAdapterService( 6117): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1394d110
V/BluetoothFtpService( 6117): Ftp Service onCreate
I/BluetoothFtpService( 6117): Ftp Service onCreate
V/BluetoothFtpService( 6117): Ftp Service onStartCommand
V/BluetoothFtpService( 6117): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpService( 6117): Starting Listening on sockets
V/BluetoothOppProvider( 6117): created cursor android.database.sqlite.SQLiteCursor@3d345f64 on behalf of 
V/BluetoothSapReceiver( 6117): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 6117): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 6117): SapReceiver onReceive 
V/BluetoothSapReceiver( 6117): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6117):  Bluetooth Adapter state = 12
V/BluetoothSapReceiver( 6117): Calling SAP service start service with action = null
V/BluetoothOppNotification( 6117): inbound: succ-0  fail-0
V/BtOppService( 6117): ContentObserver received notification
V/BluetoothOppNotification( 6117): inbound notification was removed.
V/BtOppService( 6117): ContentObserver received notification
V/BluetoothFtpService( 6117): Handler(): got msg=1
,V/BluetoothFtpService( 6117): Ftp Service startRfcommSocketListener
V/BluetoothFtpService( 6117): Ftp Service initSocket
V/BtOppService( 6117): pendingUpdate is true keepUpdateThread is false sListenStarted is true
V/BluetoothOppProvider( 6117): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6117): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6117): created cursor android.database.sqlite.SQLiteCursor@2fb545cd on behalf of 
V/BluetoothOppNotification( 6117): update too frequent, put in queue
D/BluetoothManagerService( 1031): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6117): getBluetoothService() called with no BluetoothManagerCallback
V/BluetoothOppProvider( 6117): created cursor android.database.sqlite.SQLiteCursor@15015e82 on behalf of 
V/BtOppService( 6117): pendingUpdate is false keepUpdateThread is false sListenStarted is true
D/AuthorizationBluetoothService( 2134): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
V/BluetoothFtpService( 6117): Succeed to create listening socket on channel 20
V/BluetoothFtpService:RfcommSocketAcceptThread( 6117): Run Accept thread
D/BluetoothAdapterService( 6117): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1394d110
V/BluetoothSapService( 6117): Sap Service onCreate
,V/BluetoothSapService( 6117): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 6117): state: 12
V/BluetoothSapService( 6117): Starting SAP server process
V/BluetoothSapService( 6117): SAP Service startRfcommListenerThread
V/BluetoothSapService( 6117): Sap Service initRfcommSocket
D/BluetoothManagerService( 1031): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6117): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 6117): [BTUI] createSocketChannel FD=82 mFd=81
V/BluetoothSapService( 6117): Succeed to create listening socket 
V/BluetoothSapService( 6117): Accepting socket connection...
W/sapd    ( 6355): type=1400 audit(0.0:161): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,W/sapd    ( 6355): type=1400 audit(0.0:162): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/wpa_supplicant( 6143): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1031): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=13 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1031): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1031): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
V/BT_SAP  ( 6355): Event pipe created
V/BT_SAP  ( 6355): create_server_socket qcom.sap.server
V/BT_SAP  ( 6355): created socket fd 6
,V/AlarmManager( 1031): RTC_WAKEUP set : Alarm{334b237c type 0 when 1455113546651 com.android.vending} when 1455113546651
V/AlarmManager( 1031): RTC_WAKEUP set : Alarm{29b61405 type 0 when 1455113548963 android} when 1455113548963
,E/WifiStateMachine( 1031):  DisconnectedState CMD_START_SCAN -2 -2 ic=1 proc(ms):1 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=120000 [on:0 tx:0 rx:0 period:-880361890] from screen [on:0 period:-880361890]
E/WifiStateMachine( 1031):  ConnectModeState CMD_START_SCAN -2 -2 ic=1 proc(ms):2 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=120000 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-880361889]
,E/WifiStateMachine( 1031):  DriverStartedState CMD_START_SCAN -2 -2 ic=1 proc(ms):3 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=120000 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:-880361889]
D/WifiNative-wlan0( 1031): doBoolean: SCAN
D/WifiNative-wlan0( 1031): SCAN: returned false
V/QRemote ( 6001): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
D/QRemote ( 6001): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:9026
W/ContextImpl( 4205): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,V/SIM_STK ( 1031): Menu title from STK is T-Mobile
,V/GLSActivity( 2134): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2134): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2134): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2134): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2134): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2134): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 4906): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 4906): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4906): [1] 5.onFinished: Scheduling replication attempt 1.
,V/BluetoothOppNotification( 6117): new notify threadi!
V/BluetoothOppNotification( 6117): send delay message
,V/BluetoothOppProvider( 6117): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6117): created cursor android.database.sqlite.SQLiteCursor@3c6ae0ce on behalf of 
V/BluetoothOppNotification( 6117): mUpdateCompleteNotification = true
V/BluetoothOppProvider( 6117): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,V/BluetoothOppProvider( 6117): created cursor android.database.sqlite.SQLiteCursor@3754abef on behalf of 
V/BluetoothOppNotification( 6117): outbound: succ-0  fail-0
V/BluetoothOppNotification( 6117): outbound notification was removed.
V/BluetoothOppProvider( 6117): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 6117): created cursor android.database.sqlite.SQLiteCursor@54a36fc on behalf of 
V/BluetoothOppNotification( 6117): inbound: succ-0  fail-0
,V/BluetoothOppNotification( 6117): inbound notification was removed.
,V/BluetoothOppProvider( 6117): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,V/BluetoothOppProvider( 6117): created cursor android.database.sqlite.SQLiteCursor@20426185 on behalf of 
I/wpa_supplicant( 6143): [LGE_PATCH]scan interval[1] = 3 sec.
,D/WfdsMonitor( 1961): Event [CTRL-EVENT-SCAN-RESULTS ]
D/WfdsMonitor( 1961): Event [WPS-AP-AVAILABLE ]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=14 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1031): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1031): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=15 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1031): couldn't identify event type - WPS-AP-AVAILABLE 
E/WifiMonitor( 1031): WifiMonitor:p2p0 cnt=16 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1031): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1031): Event [IFNAME=p2p0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1031): WifiMonitor:p2p0 cnt=17 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1031): couldn't identify event type - WPS-AP-AVAILABLE 
E/WifiStateMachine( 1031):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=1 known=0 got=1 bcn=0
E/WifiStateMachine( 1031):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=1 known=0 got=1 bcn=0
E/WifiStateMachine( 1031):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=1 known=0 got=1 bcn=0
E/WifiStateMachine( 1031):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=1 known=0 got=1 bcn=0
I/WifiNative-HAL( 1031): startHal
E/wifi    ( 1031): getStaticLongField sWifiHalHandle 0x9895b8cc
E/WifiHAL ( 1031): Could not connect handle
D/wifi    ( 1031): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x70183a
I/WifiNative-HAL( 1031): Could not start hal
D/WifiNative-wlan0( 1031): doString: [BSS RANGE=0- MASK=0x21987]
D/LGWifiP2pService( 1031): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
V/WiFiOffLoadBroadcast( 6205): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,D/WiFiOffLoadBroadcast( 6205): Not supported operator for automatic switch
I/jxcore-log( 6063): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 6063): 
,I/jxcore-log( 6063): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 6063): 
,I/jxcore-log( 6063): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 6063): 
I/jxcore-log( 6063): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 6063): 
,I/jxcore-log( 6063): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 6063): 
,I/jxcore-log( 6063): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log( 6063): 
,I/CloudHub( 2227): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19977
,I/wpa_supplicant( 6143): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1031): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=18 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1031): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1031): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,E/wpa_supplicant( 6143): USIM:  scard_init function
I/wpa_supplicant( 6143): Trying to associate with SSID 'NG700'
,E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=19 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1031): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1031): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=20 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1031): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1031): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1031):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=1 known=0 got=1 bcn=0
E/WifiStateMachine( 1031):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=1 known=0 got=1 bcn=0
E/WifiStateMachine( 1031):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=1 known=0 got=1 bcn=0
E/WifiStateMachine( 1031):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=1 known=0 got=1 bcn=0
D/WifiNative-wlan0( 1031): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1031):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=117690  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/StatusBar.NetworkController( 1459): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1459): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
E/WifiStateMachine( 1031):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=117696  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
D/WifiServerServiceExt( 1031): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1031): setSupplicantStateASSOCIATING
I/StatusBar.NetworkController( 1459): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1459): mWifiConnected = false, mWifiLevel = 0
,D/PostponalbeReceiver( 5189): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WiFiOffLoadBroadcast( 6205): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6205): MCCMNC not supported: null
D/QRemote ( 6001): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6001): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6001): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 117790161366; DSPS: 4000585; Offset : -4313243081
,D/PostponalbeReceiver( 5189): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6205): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6205): MCCMNC not supported: null
D/QRemote ( 6001): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6001): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6001): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/wpa_supplicant( 6143): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/WifiMonitor( 1031): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1031): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=23 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1031): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1031):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=118314  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1031):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=118314  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1031):  DisconnectedState CMD_ASSOCIATED_BSSID 23 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=118316
E/WifiStateMachine( 1031):  ConnectModeState CMD_ASSOCIATED_BSSID 23 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=118316
E/WifiStateMachine( 1031):  DriverStartedState CMD_ASSOCIATED_BSSID 23 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=118316
I/wpa_supplicant( 6143): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 6143): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1031): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=25 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1031): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=26 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1031): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1031): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1031): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1031): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1031):  SupplicantStartedState CMD_ASSOCIATED_BSSID 23 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=118321
E/WifiStateMachine( 1031):  DefaultState CMD_ASSOCIATED_BSSID 23 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=118322
E/WifiStateMachine( 1031):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=118322  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
,I/StatusBar.NetworkController( 1459): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1459): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/Tethering( 1031): sendTetherStateChangedBroadcast 1, 0, 0
E/WifiStateMachine( 1031):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=118341  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
,E/WifiStateMachine( 1031):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 25 0 rt=118343  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/WifiStateMachine( 1031):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 25 0 rt=118344  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
E/WifiStateMachine( 1031):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=118345
E/WifiStateMachine( 1031):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=118345
D/WifiNative-wlan0( 1031): doString: [STATUS]
D/WifiMonitor( 1031): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1031):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
I/StatusBar.NetworkController( 1459): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1459): mWifiConnected = false, mWifiLevel = 0
D/libc-netbsd(  320): default dns: query_ipv6=0, query_ipv4=0
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
D/DSQN    ( 1031): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/WifiServiceExtension( 1031): setVHTCapabilityType  : false
D/WifiServerServiceExt( 1031): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1031): setSupplicantStateASSOCIATED
,D/PostponalbeReceiver( 5189): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/WifiServerServiceExt( 1031): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1031): setKeepAlivePacketInterval msec : 60
I/StatusBar.NetworkController( 1459): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1459): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
V/WiFiOffLoadBroadcast( 6205): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/StatusBar.NetworkController( 1459): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1459): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WiFiOffLoadBroadcast( 6205): MCCMNC not supported: null
D/ConnectivityService( 1031): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,D/QRemote ( 6001): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6001): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/ConnectivityService( 1031): Got NetworkAgent Messenger
D/ConnectivityService( 1031): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1031): NetworkAgent connected
E/WifiConfigStore( 1031): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1031): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1031): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1031): doBoolean: SAVE_CONFIG
I/QRemote ( 6001): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 5189): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiNative-wlan0( 1031): SAVE_CONFIG: returned true
E/WifiConfigStore( 1031): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1031): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1031): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1031): doBoolean: SAVE_CONFIG
,V/WiFiOffLoadBroadcast( 6205): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WifiNative-wlan0( 1031): SAVE_CONFIG: returned true
D/CommandListener(  320): Setting iface cfg
E/WifiStateMachine( 1031): Start Dhcp Watchdog 1
D/DhcpStateMachine( 1031): StoppedState
D/DhcpStateMachine( 1031): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1031): WaitBeforeStartState
E/WifiStateMachine( 1031):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 28 0 rt=118428  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
,E/WifiStateMachine( 1031):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 28 0 rt=118429  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1031):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 28 0 rt=118429  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WifiServerServiceExt( 1031): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1031): setSupplicantStateFOUR_WAY_HANDSHAKE
D/WifiServerServiceExt( 1031): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1031): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1031):  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1031):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1031):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1031):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1031):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1031):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=118432  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1031):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=118432  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1031):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=118432  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1031):  ObtainingIpState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:7369] from screen [on:0 period:-880354517]
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:-880354517]
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/WiFiOffLoadBroadcast( 6205): MCCMNC not supported: null
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1031): updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,E/WifiStateMachine( 1031):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
D/QRemote ( 6001): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 1031):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
D/QRemote ( 6001): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
E/WifiStateMachine( 1031):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
I/QRemote ( 6001): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
E/WifiStateMachine( 1031):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1031):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1031): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
E/WifiStateMachine( 1031):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
D/UsbSettingsReceiver( 6205): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6205): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6205): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6205): [AUTORUN] persist.sys.usb.config = ptp_only,adb
E/WifiStateMachine( 1031):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
D/WifiNative-wlan0( 1031): doBoolean: DRIVER SETSUSPENDMODE 0
D/UsbSettingsReceiver( 6205): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 6205): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6205): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6205): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6205): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6205): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6205): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 6205): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 5189): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 6205): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6205): MCCMNC not supported: null
D/QRemote ( 6001): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6001): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6001): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 5189): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6205): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/wpa_supplicant( 6143): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1031): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1031): doBoolean: SET ps 0
D/WifiNative-wlan0( 1031): SET ps 0: returned true
D/WifiNative-wlan0( 1031): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 6143): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1031): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1031): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1031): Current State is mWaitBeforeStartState.
D/LGWifiP2pService( 1031): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@14b8bfe3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@14b8bfe3 target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper( 1031): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
V/LgDhcpStateMachineHelper( 1031): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700" is not exist.
D/DhcpStateMachine( 1031): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1031): DHCP Start wake lock is acquired.
D/WifiServerServiceExt( 1031): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1031): setSupplicantStateCOMPLETED
D/WiFiOffLoadBroadcast( 6205): MCCMNC not supported: null
,D/QRemote ( 6001): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6001): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6001): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/jxcore-log( 6063): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 6063): 
,I/jxcore-log( 6063): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
I/jxcore-log( 6063): 
,I/jxcore-log( 6063): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 6063): 
I/jxcore-log( 6063): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 6063): 
,D/DhcpStateMachine( 1031): DHCPV4 request on wlan0
,V/LgDhcpStateMachineHelper( 1031): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1031): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
W/dhcpcd  ( 6419): type=1400 audit(0.0:163): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 6419): type=1400 audit(0.0:164): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,I/dhcpcd  ( 6419): version 5.5.6 starting
E/dhcpcd  ( 6419): get_duid: m
D/dhcpcd  ( 6419): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 6419): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,D/dhcpcd  ( 6419): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 6419): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 6419): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,I/dhcpcd  ( 6419): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 6419): wlan0: sending REQUEST (xid 0x427af8bc), next in 3.20 seconds
I/jxcore-log( 6063): Test app app.js loaded
I/jxcore-log( 6063): 
,I/chromium( 6063): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6063): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6063): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6063): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6063): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6063): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6063): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6063): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6063): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6063): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6063): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29910eeb added. We now have 1 listener(s)
,I/jxcore-log( 6063): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 6063): 
,E/WifiStateMachine( 1031):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1031):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 1031):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1031):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1031):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1031): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
I/dhcpcd  ( 6419): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
,I/dhcpcd  ( 6419): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 6419): wlan0: adding IP address 192.168.1.141/24
,D/dhcpcd  ( 6419): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 6419): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 6419): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 6419): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 6419): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 6419): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,E/WifiStateMachine( 1031):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1031):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1031):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1031):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1031):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,D/ConnectivityService( 1031): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
,D/DhcpStateMachine( 1031): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper( 1031): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1031): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1031): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1031): Add DhcpResults: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
V/DhcpStateMachine( 1031): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1031): bShouldSendDhcpAction Result: true
E/WifiStateMachine( 1031):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine( 1031):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/WifiNative-wlan0( 1031): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 6143): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1031): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1031): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1031): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 6143): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1031): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1031): doBoolean: SET ps 1
D/DhcpStateMachine( 1031): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1031): RunningState
,D/WifiNative-wlan0( 1031): SET ps 1: returned true
,D/ConnectivityService( 1031): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
E/WifiStateMachine( 1031):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1031): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1031): ignoring duplicate network state non-change
I/StatusBar.NetworkController( 1459): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1459): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
,W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/StatusBar.NetworkController( 1459): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1459): mWifiConnected = false, mWifiLevel = 0
,D/ConnectivityService( 1031): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1031): Adding iface wlan0 to network 100
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,E/WifiStateMachine( 1031): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/WifiHS20( 1031): [PASSPOINT] passpointNotification: hs20AP list is checked
I/StatusBar.NetworkController( 1459): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
V/WfdStateTracker( 1961): handleWifiStateChangedEvent: 1
,W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20( 1031): [PASSPOINT] passpointNotification: hs20AP list is checked
,I/StatusBar.NetworkController( 1459): mWifiConnected = true, mWifiLevel = 2
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
E/ConnectivityService( 1031): Unexpected mtu value: 0, wlan0
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/ConnectivityService( 1031): Adding Route [fe80::/64 -> :: wlan0] to network 100
,D/ConnectivityService( 1031): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
D/ConnectivityService( 1031): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
D/ConnectivityService( 1031): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1031): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 100
D/ConnectivityService( 1031): Setting Dns servers for network 100 to [/192.168.1.1]
D/Nat464Xlat( 1031): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1031): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1031): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1031): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1031):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1031):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1031):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1031):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1031):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1031): currentScore = 0, newScore = 20
D/ConnectivityService( 1031):    accepting network in place of null
D/ConnectivityService( 1031): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1031): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1031): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1031): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1031): Checking http://clients3.google.com/generate_204 on "NG700"
D/WIFI    ( 1031): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1031):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/ConnectivityService( 1031): Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
I/StatusBar.NetworkController( 1459): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/TelephonyNetworkFactory-1( 1866): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/StatusBar.NetworkController( 1459): mWifiConnected = true, mWifiLevel = 2
D/TelephonyNetworkFactory-1( 1866):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
D/libc-netbsd(  320): res_queryN name = clients3.google.com, class = 1, type = 28
D/PostponalbeReceiver( 5189): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/ConnectivityService( 1031): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1031): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1031): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1031): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1031): [e] list.add(nai) empty : false size: 1
D/ConnectivityService( 1031): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/LocSvc_java( 1031): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1031): getAGpsConnectionInfo connType - 4
,D/LocSvc_java( 1031): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1031): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java( 1031): Sending msg: 5 arg1:0 arg2:1
D/ConnectivityService( 1031): validation of new default Network = false
D/ConnectivityService( 1031): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1031): enableDataServiceNotify 
D/DSQN    ( 1031): start dsqn bin
D/libc-netbsd(  320): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  320): res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
D/libc-netbsd(  320): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  320): res_queryN name = europe.pool.ntp.org, class = 1, type = 1
D/ConnectivityService( 1031): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1031):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1031):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService( 1031): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1459): CM callback handler got msg 524290
W/dsqn    ( 6478): type=1400 audit(0.0:165): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 6478): type=1400 audit(0.0:166): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
V/WiFiOffLoadBroadcast( 6205): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6205): MCCMNC not supported: null
D/QRemote ( 6001): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6001): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/TelephonyIcons( 1459): null signal icon name: drawable/stat_sys_signal_null
,D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
I/QRemote ( 6001): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
E/DSQN    ( 6478): DSQN ssw
D/PostponalbeReceiver( 5189): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6205): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/libc-netbsd(  320): res_queryN name = clients3.google.com, class = 1, type = 1
D/WiFiOffLoadBroadcast( 6205): MCCMNC not supported: null
D/libc-netbsd(  320): res_queryN name = 2.android.pool.ntp.org succeed
D/QRemote ( 6001): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6001): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6001): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 5189): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 6178): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6178): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6205): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6205): MCCMNC not supported: null
D/QRemote ( 6001): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6001): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6001): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6001): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6001): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 5189): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 6178): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6178): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
D/libc-netbsd(  320): res_queryN name = clients3.google.com succeed
V/WiFiOffLoadBroadcast( 6205): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6205): MCCMNC not supported: null
D/QRemote ( 6001): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6001): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
V/NetworkPolicy( 1031): [LG_RESTRICTED] checkMobilePolicy_type()
D/QRemote ( 6001): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6001): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6001): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/libc-netbsd(  320): res_queryN name = europe.pool.ntp.org succeed
,D/LGDataListener(  320): argv[0]=dsqncommand
D/LGDataListener(  320): argv[1]=wlan0
D/LGDataListener(  320): argv[2]=1
D/LGDataListener(  320): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1031): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1031): start to monitor internet connection
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-880351509] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-880351505] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1031): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 10 Feb 2016 14:12:41 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1455113561995], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1455113561550]}
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1031): Don't send network conditions - lacking user consent.
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1031): Validated
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
,D/ConnectivityManager.CallbackHandler( 1459): CM callback handler got msg 524290
D/ConnectivityService( 1031): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1866): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1866):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/WIFI    ( 1031): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1031):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1031): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/TelephonyIcons( 1459): null signal icon name: drawable/stat_sys_signal_null
,D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WifiInternetCheck( 1031): Single check msg out of sync, ignoring.
,D/ConnectivityService( 1031): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1031): MasterInitialState.processMessage what=3
,D/GpsLocationProvider( 1031): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/AlarmManagerService( 1031): Setting time of day to sec=1455113564
,W/AlarmManagerService( 1031): Unable to set rtc to 1455113564: Invalid argument
,D/KeyguardUpdateMonitor( 1459): handleTimeUpdate
,I/SecureClockService( 1961): Intent.ACTION_TIME_CHANGED 
I/[SystemUI]Clock( 1459): onReceive = android.intent.action.TIME_SET
D/LIA_Informant_Tips_DateChangeManager( 2694): onReceive() : ACTION_TIME_CHANGED
I/LIA_Informant_Tips_LogTracer( 2694): [Log Tracer - Schedule Transition] Time Change Event Received : 2016-02-10 15:12:44...... Request
I/LIA_Informant_Tips_LogTracer( 2694): [Log Tracer - Schedule Transition] UserGuide, DATE_UPDATE : working count : 7, total count : 171, new day : false...... Request
D/LIA_Informant_Tips_DateChangeManager( 2694): DateInfo : SmartTips Total Working Day Count = 171
,D/LIA_Informant_Tips_DateChangeManager( 2694): DateInfo : UserGuide Working Duration Count = 7
D/LIA_Informant_Tips_DateChangeManager( 2694): DateInfo : Last Date Check Time = 2016-02-10 15:12:44
I/LgeClockWidgetControlView( 1459): time changed, timezoneChanged : false
D/PostponalbeReceiver( 5189): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ActivityManager( 1031): getTasks: caller 10029 is using old GET_TASKS but privileged; allowing
I/[LGHome]LGDateChangeReceiver( 2082): [LGDateChangeReceiver.java:78:updateCalendarShortcut()]date=10 currentDate=-1 dayofweek=4 currentDayOfWeek=-1
I/[LGHome]LGCalendarIcon( 2082): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Wed date= 10
I/[LGHome]LGCalendarIcon( 2082): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Wed date= 10
I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
W/ContextImpl( 5189): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/GoogleURLConnFactory( 2134): Using platform SSLCertificateSocketFactory
I/NetworkMonitor( 5262): type=WIFI subType= reason=null isConnected=true
D/[Concierge]Service( 2587): onStartCommand(). Type : 9
I/ActivityManager( 1031): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6520 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/ActivityManager( 1031): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=6538 uid=10054 gids={50054, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/art     (  355): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 276us total 20.119ms
I/art     (  355): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 259us total 11.833ms
I/AppUp4:AppBoxCP( 6520): onCreate
W/AppUp4:DB( 6520):  [AppBoxDatabaseHelper] construct
I/art     (  355): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 226us total 11.297ms
I/AppUp4:DB( 6520):  setFingerPrint start
I/AppUp4:DB( 6520):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 6520):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 6520):  SDK version = 21
I/AppUp4:DB( 6520):  beforefinger == newfinger no write in DB
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=5.8, 0.0, 0.0  rx=4.0 bcn=0 [on:0 tx:0 rx:0 period:2677] from screen [on:0 period:-880348799] gl rssi=-59 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=5.8, 0.0, 0.0  rx=4.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-880348798] gl rssi=-59 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
I/ActivityManager( 1031): Start proc com.android.gallery3d for service com.android.gallery3d/com.lge.gallery.picasa.PicasaService: pid=6555 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
D/AppUp4:AppBoxApplication( 6520): AppBoxApplication onCreate()
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
I/NetworkStateForAutoUpdateMonitor( 6520): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6520): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6520): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6520): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6520): onReceive
W/ResourcesManager( 6555): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6555): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6555): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 6555): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
D/LgDataFeature( 6520): LgDataFeature() Constructor: none
D/LgDataFeature( 6520): LgDataFeature() Constructor Done, null
D/AppUp4:CustFacade( 6520): Context : android.app.ReceiverRestrictedContext@6a7d1d3
D/AppUp4:CustFacade( 6520): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6520): isPhone : true
D/AppUp4:CustModeStarterReceiver( 6520): begin check event
I/AppUp4:CustModeStarterReceiver( 6520): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6520): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6520): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6520): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6520): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1031): Killing 5609:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
D/LGDMClient( 3956): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3956): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/libprocessgroup( 1031): failed to open /acct/uid_10080/pid_5609/cgroup.procs: No such file or directory
W/ContextImpl( 3956): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 3956): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/LGDMClient( 3956): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/LGDMClient( 3956): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3956): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 3300): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
I/AppConfig( 6555): Total System Memory = 2995761152
I/LGDMClient( 3956): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 3300): DownloadService onCreate
I/DownloadManager( 3300): in removeSpuriousFiles
V/DownloadManager( 3300): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3300): created cursor android.database.sqlite.SQLiteCursor@ad44ae9 on behalf of 3300
I/DownloadManager( 3300): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3300): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3300): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3300): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3300): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3300): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3300): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3300): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3300): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3300): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3300): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/DownloadManager( 3300): in trimDatabase
V/DownloadManager( 3300): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
D/SystemHelper( 6555): region [EU], country [EU], operator [OPEN], sub-operator []
V/DownloadManager( 3300): created cursor android.database.sqlite.SQLiteCursor@246d136e on behalf of 3300
I/ActivityManager( 1031): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6582 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
V/DownloadManager( 3300): DownloadService onStartCommand
V/DownloadManager( 3300): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3300): created cursor android.database.sqlite.SQLiteCursor@9e53a9c on behalf of 3300
W/ContextImpl( 3956): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3300): processing inserted download 1
E/LGDMClient( 3956): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
V/DownloadManager( 3300): processing inserted download 4
V/DownloadManager( 3300): processing inserted download 7
D/LGDMClient( 3956): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
V/DownloadManager( 3300): processing inserted download 8
D/LGDMClient( 3956): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3300): processing inserted download 9
V/DownloadManager( 3300): processing inserted download 10
V/DownloadManager( 3300): processing inserted download 16
V/DownloadManager( 3300): processing inserted download 17
V/DownloadManager( 3300): processing inserted download 18
V/DownloadManager( 3300): processing inserted download 21
V/DownloadManager( 3300): processing inserted download 22
V/DownloadManager( 3300): DownloadService onDestroy
W/ResourcesManager( 6582): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6582): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6582): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6582): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/ActivityManager( 1031): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=6600 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ReaderUtils( 6538): PortraitW 1440 LandscapeW 2392 SmallestSize 1340 LargestSize 2392 textZoom 4.4999995 isTablet false Memory 256
I/VacuumService( 2134): Vacuum at: now=1455113564816 tag=VacuumService
I/LGEmail ( 6582): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
I/art     ( 2134): Explicit concurrent mark sweep GC freed 24620(1434KB) AllocSpace objects, 2(32KB) LOS objects, 51% free, 30MB/62MB, paused 730us total 30.269ms
D/LGEmail ( 6582): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
W/DriveInitializer( 2367): Background init thread started
V/GLSActivity( 2134): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.gms/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 2367): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.gms/files
D/GpsLocationProvider( 1031): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/art     ( 1031): Explicit concurrent mark sweep GC freed 60713(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 44MB/66MB, paused 1.260ms total 78.020ms
I/ThermalEngine(  344): Thermal-Server: Thermal received msg from  override
I/Thermal-Lib( 3112): Thermal-Lib-Client: Client request sent
E/GpsLocationProvider( 1031): No APN found to select.
W/ResourceType( 6582): No package identifier when getting value for resource number 0x00000000
W/GAV2    ( 6538): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/BooksApp( 6538): Created application version: 3.2.35 (30235)
W/DriveInitializer( 2367): Background init thread ended
I/ActivityManager( 1031): Killing 5895:com.google.android.apps.docs/u0a61 (adj 15): empty #17
D/LgDataFeature( 6582): LgDataFeature() Constructor: none
D/LgDataFeature( 6582): LgDataFeature() Constructor Done, null
D/DelayedSyncController( 6600): Delaying sync.
W/libprocessgroup( 1031): failed to open /acct/uid_10061/pid_5895/cgroup.procs: No such file or directory
I/ActivityManager( 1031): Killing 5627:com.google.android.apps.plus/u0a97 (adj 15): empty #17
I/GLSUser ( 2134): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/ads_measurement
I/GLSUser ( 2134): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/ads_measurement without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2134): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2134): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
W/libprocessgroup( 1031): failed to open /acct/uid_10097/pid_5627/cgroup.procs: No such file or directory
V/GLSActivity( 2134): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/Ads     ( 2367): [JAMS] Failed to get OAuth token: com.google.android.gms.auth.ad: BadAuthentication
E/Auth.Api.Credentials( 2367): [CredentialSyncAdapter] Unknown sync event.
I/BooksSync( 6538): Starting books sync
D/eas_req ( 6582): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
I/HubEmail( 6582): JNI_OnLoad()
I/HubEmail( 6582): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6582): registerNatives()
I/HubEmail( 6582): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6582): registerNativeMethods()
I/HubEmail( 6582): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6582): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/LgeMiscReceiver( 3275): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3275): action = android.net.conn.CONNECTIVITY_CHANGE
W/Settings( 6582): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/LgeMiscReceiver( 3275): networkInfo.isConnected() = true
D/PhoneState( 3275): setPdpRejectCasuse : false
W/Settings( 6582): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/libc-netbsd(  320): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  320): res_queryN name = static-avc.lglime.com, class = 1, type = 1
I/ActivityManager( 1031): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6662 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
I/GoogleURLConnFactory( 2134): Using platform SSLCertificateSocketFactory
W/Uploader( 2134): No account for auth token provided
D/libc-netbsd(  320): res_queryN name = static-avc.lglime.com succeed
,D/libc-netbsd(  320): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  320): res_queryN name = play.googleapis.com, class = 1, type = 1
D/DrmBroadcastReceiver( 6662): Receive CONNECTIVITY_ACTION
D/BooksSync( 6538): started syncMyEbooks
D/DrmBroadcastReceiver( 6662): 1  network is available. Sync DRM Time with NTP
V/DrmService( 6662): Service onCreate
D/DrmService( 6662): Received new request = 2
,I/DrmSntpClient( 6662): Start Sync process
D/DrmSntpClient( 6662): Server : 0
D/libc-netbsd(  320): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  320): res_queryN name = pool.ntp.org, class = 1, type = 1
,I/ActivityManager( 1031): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=6688 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/libc-netbsd(  320): res_queryN name = play.googleapis.com succeed
,D/libc-netbsd(  320): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  320): res_queryN name = www.google.com, class = 1, type = 1
,I/art     ( 6688): Almond Protected OAT
,V/GLSActivity( 2134): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/FormManager( 6144): There are no updated forms. The schedule will be deleted.
D/libc-netbsd(  320): res_queryN name = pool.ntp.org succeed
,V/FormManager( 6144): Alarm would be updated, because LastCheckTime has been updated.
I/GLSUser ( 2134): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2134): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2134): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2134): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2134): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 1031): Killing 5957:com.lge.eula/1000 (adj 15): empty #17
,D/libc-netbsd(  320): res_queryN name = www.google.com succeed
D/libc-netbsd(  320): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  320): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  320): res_queryN name = clients3.google.com succeed
I/LGDrmClient( 6662): _DRM_ServiceGet() : Bind lgdrm service
V/ILGDrmService(  330): eDRM_SetDRMTime +++
I/LGDRM   (  330): [DRM] SET TIME : YR=2016, MON=2, DAY=10
I/LGDRM   (  330): [DRM] SET TIME : HR=14, MIN=12, SEC=45
,V/ILGDrmService(  330): eDRM_SetDRMTime ---
I/DrmSntpClient( 6662): Synched
D/DrmService( 6662): Completed !! request = 2
D/DrmService( 6662): Request count = 0
W/libprocessgroup( 1031): failed to open /acct/uid_1000/pid_5957/cgroup.procs: No such file or directory
,D/WeatherApplication( 6688): removeAccount
V/DrmService( 6662): Service onDestroy
D/WeatherApplication( 6688): Account.length = 0
E/WeatherApplication( 6688): OPERATOR:OPEN
I/ActivityManager( 1031): Killing 5411:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
D/WeatherAncestor( 6688): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:12:45
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/Weather.Utils( 6688): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6688): 2 : All the weather widget is gone.
V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
W/GLSActivity( 2134): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2134): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2134): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2134): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2134): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2134): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2134): 	at android.os.Binder.execTransact(Binder.java:446)
,D/UpdateThreadPoolManager( 6688): 2 : This is isUpdating : false
,D/WeatherAncestor( 6688): connectivity changed - connection : true
D/WeatherService( 6688): 2 : isServiceAlived():false forecastCache:null
D/ForecastDataCache( 6688): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 6688): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 6688): 2 : Cache is not up-to-date, count: 0
D/Weather_cast( 6688): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 6688): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:12:45
,I/ActivityManager( 1031): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6709 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1031): Killing 2227:com.lge.music/u0a34 (adj 15): empty #17
,V/WifiInternetCheck( 1031): isHttpConnectionAvailable - We got a valid response : 204
V/AudioFlinger(  325): 2227 died, releasing its sessions
V/AudioFlinger(  325):  pid 1866 @ 0
V/AudioFlinger(  325):  pid 3275 @ 1
V/AudioFlinger(  325):  pid 3275 @ 2
W/libprocessgroup( 1031): failed to open /acct/uid_10005/pid_5411/cgroup.procs: No such file or directory
,I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/libprocessgroup( 1031): failed to open /acct/uid_10034/pid_2227/cgroup.procs: No such file or directory
D/LgeQuickCoverNLService( 1410): onNotificationPosted
D/SmartCoverUpdateMonitor( 1410): received broadcast com.lge.intent.action.NLDataPosted
E/BooksAccountManager( 6538): Authentication error
E/BooksAccountManager( 6538): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6538): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6538): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6538): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6538): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6538): 	at android.os.Binder.execTransact(Binder.java:446)
E/SmartCoverUpdateMonitor( 1410): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1410): handleNotificationPosted(true)
D/QuickCircle( 1410): onNotificationPosted() : isPosted true
E/HttpHelper( 6538): null auth token
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
,E/LgeQuickCoverOverlayWindow( 1410): updateNotificationData: count=3
W/Uploader( 2134): No account for auth token provided
D/libc-netbsd(  320): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  320): res_queryN name = www.googleapis.com, class = 1, type = 1
,D/QuickStatusbarLayout( 1410): Notification difference=198
D/QuickStatusbarLayout( 1410): child = android.widget.LinearLayout{2a8c721b V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/DelayedSyncController( 6600): Delaying sync.
,D/libc-netbsd(  320): res_queryN name = www.googleapis.com succeed
E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6709): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6709): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6709): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6709): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,W/Uploader( 2134):  no longer exists, so no auth token.
V/GLSActivity( 2134): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2134): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 2134): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2134): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2134): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2134): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Uploader( 2134): No account for auth token provided
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2134): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2134): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2134): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2134): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2134): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2134): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2134): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1410): onNotificationPosted
D/ContactsSyncAdapter( 2134): innerSync failed
D/ContactsSyncAdapter( 2134): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2134): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2134): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2134): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2134): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2134): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2134): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2134): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2134): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2134): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2134): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2134): 	at android.os.Binder.execTransact(Binder.java:446)
D/SmartCoverUpdateMonitor( 1410): received broadcast com.lge.intent.action.NLDataPosted
,E/SmartCoverUpdateMonitor( 1410): MSG_NOTIFICATION_POSTED
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
D/SyncManager( 1031): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 27091, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager( 1031): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 156597, reason: 10019
D/QuickStatusbarLayout( 1410): Notification difference=198
D/QuickStatusbarLayout( 1410): child = android.widget.LinearLayout{2a8c721b V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,I/GoogleURLConnFactory( 2367): Using platform SSLCertificateSocketFactory
V/GLSActivity( 2134): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/WebViewFactory( 6709): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,W/Uploader( 2134): No account for auth token provided
I/LibraryLoader( 6709): Loading: webviewchromium
I/LibraryLoader( 6709): Time to load native libraries: 2 ms (timestamps 5625-5627)
I/LibraryLoader( 6709): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6709): Binding Chromium to main looper Looper (main, tid 1) {896c8ca}
I/LibraryLoader( 6709): Expected native library version number "",actual native library version number ""
I/chromium( 6709): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6709): Initializing chromium process, renderers=0
W/art     ( 6709): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6709): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
V/AudioPolicyService(  325): registerClient() client 0xb101eb40, uid 10093
I/chromium( 6709): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 6709): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,W/AudioManagerAndroid( 6709): Requires BLUETOOTH permission
W/ApiaryClient( 6538): Error response from books API: {
W/ApiaryClient( 6538):  "error": {
W/ApiaryClient( 6538):   "errors": [
W/ApiaryClient( 6538):    {
W/ApiaryClient( 6538):     "domain": "global",
W/ApiaryClient( 6538):     "reason": "required",
W/ApiaryClient( 6538):     "message": "Login Required",
W/ApiaryClient( 6538):     "locationType": "header",
W/ApiaryClient( 6538):     "location": "Authorization"
W/ApiaryClient( 6538):    }
W/ApiaryClient( 6538):   ],
W/ApiaryClient( 6538):   "code": 401,
W/ApiaryClient( 6538):   "message": "Login Required"
W/ApiaryClient( 6538):  }
W/ApiaryClient( 6538): }
I/Adreno-EGL( 6709): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6709): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6709): Build Date: 12/12/14 금
I/Adreno-EGL( 6709): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6709): Remote Branch: 
I/Adreno-EGL( 6709): Local Patches: 
I/Adreno-EGL( 6709): Reconstruct Branch: 
W/ApiaryClient( 6538): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6538): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=4091843801435115809&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6538): Headers:
W/ApiaryClient( 6538): accept-encoding: [gzip]
W/ApiaryClient( 6538): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6538): gdata-version: 2
,W/Uploader( 2134): No account for auth token provided
I/art     ( 1031): Explicit concurrent mark sweep GC freed 34044(1456KB) AllocSpace objects, 5(336KB) LOS objects, 33% free, 44MB/66MB, paused 1.646ms total 75.315ms
,I/GLSUser ( 2134): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: mail
I/GLSUser ( 2134): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> mail without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2134): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2134): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2134): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NSApplication( 6709): Starting up...
,V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
W/GLSActivity( 2134): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2134): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2134): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2134): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2134): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2134): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2134): 	at android.os.Binder.execTransact(Binder.java:446)
,I/ActivityManager( 1031): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6773 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1031): Killing 5981:com.lge.bnr/1000 (adj 15): empty #17
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,W/SubscribedFeeds( 2367): Hard error
D/LgeQuickCoverNLService( 1410): onNotificationPosted
W/libprocessgroup( 1031): failed to open /acct/uid_1000/pid_5981/cgroup.procs: No such file or directory
D/SmartCoverUpdateMonitor( 1410): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1410): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1410): handleNotificationPosted(true)
D/QuickCircle( 1410): onNotificationPosted() : isPosted true
,D/LgeQuickCoverNotificationData( 1410): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
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
D/SyncManager( 1031): failed sync operation thalitester@gmail.com u0 (com.google), subscribedfeeds, PERIODIC, currentRunTime 39705, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,W/ResourcesManager( 6773): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/SyncManager( 1031): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), subscribedfeeds, PERIODIC, currentRunTime 157413, reason: Periodic
D/QuickStatusbarLayout( 1410): Notification difference=198
D/QuickStatusbarLayout( 1410): child = android.widget.LinearLayout{2a8c721b V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/PeopleSync( 2367): onPerformSync() [5005f081]
,I/PeopleDatabaseHelper( 2367): cleanUpNonGplusAccounts done.
,V/GLSActivity( 2134): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSActivity( 2134): [ac] getting account id
,I/GLSUser ( 2134): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
D/libc-netbsd(  320): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  320): res_queryN name = mtalk.google.com, class = 1, type = 1
,I/art     ( 2367): Explicit concurrent mark sweep GC freed 16460(1229KB) AllocSpace objects, 21(336KB) LOS objects, 49% free, 32MB/64MB, paused 1.382ms total 50.519ms
,D/libc-netbsd(  320): res_queryN name = mtalk.google.com succeed
,I/GLSUser ( 2134): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/gcm
I/GLSUser ( 2134): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/gcm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2134): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2134): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2134): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 2134): Explicit concurrent mark sweep GC freed 29821(1666KB) AllocSpace objects, 11(1351KB) LOS objects, 50% free, 30MB/62MB, paused 7.840ms total 51.757ms
,I/GcmGroups( 2367): Failed to subscribe to group.
I/GcmGroups( 2367): com.google.android.gms.auth.ad: BadAuthentication
I/GcmGroups( 2367): 	at com.google.android.gms.auth.p.b(SourceFile:442)
I/GcmGroups( 2367): 	at com.google.android.gms.auth.p.a(SourceFile:365)
I/GcmGroups( 2367): 	at com.google.android.gms.auth.p.a(SourceFile:318)
I/GcmGroups( 2367): 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:443)
I/GcmGroups( 2367): 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:333)
I/GcmGroups( 2367): 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:240)
I/GcmGroups( 2367): 	at com.google.android.gms.gcm.gmsproc.GcmReceiverService.onHandleIntent(SourceFile:50)
I/GcmGroups( 2367): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
I/GcmGroups( 2367): 	at android.os.Handler.dispatchMessage(Handler.java:102)
I/GcmGroups( 2367): 	at android.os.Looper.loop(Looper.java:135)
I/GcmGroups( 2367): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/GcmGroups( 2367): Groups upload failed, retrying in 24000:00:00
I/iu.SyncManager( 2367): SYNC; picasa accounts
,D/NetworkLogImpl( 2367): Loaded NetworkSpeedPredictor
,I/iu.Environment( 2367): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/iu.UploadsManager( 2367): num queued entries: 0
I/iu.UploadsManager( 2367): num updated entries: 0
I/iu.SyncManager( 2367): NEXT; no task
D/ChimeraCfgMgr( 2367): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 2367): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
D/PostponalbeReceiver( 5189): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.TIME_SET'.
I/ActivityManager( 1031): Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=6810 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/PeopleSync( 2367): Setting subscription: result=true [5005f081]
,I/PeopleSync( 2367): Starting sync, feed=null [5005f081]
D/ALBootInit( 6810): ====action==>android.intent.action.TIME_SET
,D/ALBootInit( 6810): Alarm ALBootInit: TIME_SET
,D/Alarms  ( 6810): [setNextAlert] start
W/BaseAppContext( 2367): Using Auth Proxy for data requests.
D/Alarms  ( 6810): [setNextAlert] (1)
,D/Alarms  ( 6810):  minTime  = 0
D/Alarms  ( 6810):  -- OK multi -- 0
E/jeny.kim( 6810): [setNextAlert] setNextAlert  temp_Alarmlink + 
E/jeny.kim( 6810): [setNextAlert]setNextAlert temp_AlarmLinkText + 
W/BaseAppContext( 2367): Using Auth Proxy for data requests.
W/BaseAppContext( 2367): Using Auth Proxy for data requests.
,I/CommonUtil( 6810): BUILD Country: EU
D/Alarms  ( 6810): broadcastToWidgetProvider : false
D/Alarms  ( 6810): Enter formatDayAndTime(final Context context, long timeInMiliSec)
I/PeopleSync( 2367): Sync start: cannotHavePeople=true isPageExistenceCheckOnly=false
V/SettingsProvider( 1031): call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
I/DigitalAppWidgetProvider( 6810): onReceive: android.intent.action.TIME_SET
,V/DigitalAppWidgetProvider( 6810): cancelAlarmOnQuarterHour android.app.ReceiverRestrictedContext@1394d110
V/DigitalAppWidgetProvider( 6810): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@1394d110
D/QuickCoverProvider( 6810): onReceiver
I/indal   ( 1410): SmartCoverWidgetContext createApplicationContext
I/indal   ( 1410): SmartCoverWidgetContext createApplicationContext
D/WeatherAncestor( 6688): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 15:12:46
,D/Weather.Utils( 6688): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6688): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6688): 2 : This is isUpdating : false
I/GLSUser ( 2134): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.media.upload https://www.googleapis.com/auth/plus.pages.manage https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.profiles.read https://www.googleapis.com/auth/plus.profiles.write https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/plus.applications.manage https://www.googleapis.com/auth/plus.settings
I/GLSUser ( 2134): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.media.upload https://www.googleapis.com/auth/plus.pages.manage https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.profiles.read https://www.googleapis.com/auth/plus.profiles.write https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/plus.applications.manage https://www.googleapis.com/auth/plus.settings without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2134): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2134): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/WeatherService( 6688): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@30701409
V/GLSActivity( 2134): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ForecastDataCache( 6688): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 6688): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 6688): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 6688): 2 : set auto-update time : 2/10 18:12
D/WeatherAncestor( 6688): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 15:12:46
,D/GCM     ( 2134): Connected
I/ActivityManager( 1031): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=6834 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1031): Killing 6246:com.lge.lifetracker/u0a37 (adj 15): empty #17
W/libprocessgroup( 1031): failed to open /acct/uid_10037/pid_6246/cgroup.procs: No such file or directory
,I/PeopleSync( 2367): Sync finished, successful=false, took 83ms
D/GCM     ( 2134): Message class com.google.f.a.a.p
I/PeopleSync( 2367): Cannot authenticate [5005f081]
I/PeopleSync( 2367): com.google.android.gms.auth.ad: BadAuthentication
I/PeopleSync( 2367): 	at com.google.android.gms.auth.p.b(SourceFile:442)
I/PeopleSync( 2367): 	at com.google.android.gms.auth.p.a(SourceFile:365)
I/PeopleSync( 2367): 	at com.google.android.gms.auth.p.a(SourceFile:310)
I/PeopleSync( 2367): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
I/PeopleSync( 2367): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
I/PeopleSync( 2367): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
I/PeopleSync( 2367): 	at com.google.android.gms.people.service.g.b(SourceFile:171)
I/PeopleSync( 2367): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
I/PeopleSync( 2367): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
I/PeopleSync( 2367): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
I/PeopleSync( 2367): 	at com.google.android.gms.plus.service.v2whitelisted.b.a(SourceFile:1184)
I/PeopleSync( 2367): 	at com.google.android.gms.people.sync.aa.g(SourceFile:1086)
I/PeopleSync( 2367): 	at com.google.android.gms.people.sync.aa.a(SourceFile:241)
I/PeopleSync( 2367): 	at com.google.android.gms.people.sync.s.a(SourceFile:283)
I/PeopleSync( 2367): 	at com.google.android.gms.people.sync.s.a(SourceFile:191)
I/PeopleSync( 2367): 	at com.google.android.gms.people.sync.s.a(SourceFile:93)
I/PeopleSync( 2367): 	at com.google.android.gms.common.j.a.onPerformSync(SourceFile:81)
I/PeopleSync( 2367): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/TimeService( 6834): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1455113566401
D/        ( 6834): TimeServiceNative: User Time to be set is 1455113566401
D/QC-time-services( 6834): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 6834): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 6834): Lib:time_genoff_operation: pargs->ts_val = 1455113566401
D/QC-time-services(  383): Daemon: Connection accepted:time_genoff
D/QC-time-services(  383): Daemon:Received base = 2, unit = 1, operation = 0,value = 1455113566401
D/QC-time-services(  383): Daemon:genoff_opr: Base = 2, val = 1455113566401, operation = 0
D/QC-time-services(  383): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS5/20/70 7:24:48
D/QC-time-services(  383): Daemon:Value read from RTC seconds = 14714688000
,D/QC-time-services( 6834): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  383): Daemon:new time 1455113566401 
D/QC-time-services(  383): Daemon: delta 1440398878401 genoff 1440398878401 
D/QC-time-services(  383): Daemon:genoff_persistent_update: Writing genoff = 1440398878401 to memory
D/QC-time-services(  383): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  383): Daemon:time_persistent_memory_opr:Genoff write operation 
D/QC-time-services(  383): Updating the TOD offset
D/QC-time-services(  383): Daemon:genoff_persistent_update: Writing genoff = 1440398878401 to memory
D/QC-time-services(  383): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  383): Daemon:time_persistent_memory_opr:Genoff write operation 
E/QC-time-services(  383): Daemon:Update to modem bit set
D/QC-time-services(  383): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  383): Daemon: Base = 2, Value being sent to MODEM = 1124434078401
E/QC-time-services( 6834): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
E/QC-time-services(  383): Daemon: Time-services: Waiting to acceptconnection
,I/ActivityManager( 1031): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetProvider: pid=6853 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi
,I/ActivityManager( 1031): Killing 6292:com.lge.settings.easy/1000 (adj 15): empty #17
W/libprocessgroup( 1031): failed to open /acct/uid_1000/pid_6292/cgroup.procs: No such file or directory
,W/ResourcesManager( 6853): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/PeopleSync( 2367): ***Sync finished***, duration: 611 [5005f081]
D/SyncManager( 1031): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.gms.people, PERIODIC, currentRunTime 39820, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager( 1031): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.gms.people, PERIODIC, currentRunTime 157929, reason: Periodic
D/CalendarApplication( 6853): CalendarApplication.onCreate()
D/PreferenceKeysParser( 6853): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 6853): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@28a8d937, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@399d6ea4, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@3696440d, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@35c51fc2, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@6a7d1d3, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@1394d110, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@30701409, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@dc9760e, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@1d93b82f, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@3d5dee3c, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@3dfce7c5, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@3aaae51a, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@18ada84b, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@2039b228, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@3fc93b41, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@e0238e6, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@c2c7e27, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@368bc8d4, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@38ad4a7d, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@828fd72, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@2ed8d5c3, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@1b469e40, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@6c91179, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@23857ebe, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@11690b1f, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@24175e6c, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@30404c35, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@896c8ca, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@2f9d3a3b, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@3251f558, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@3fb676b1, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@36c0a796, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@371b3f17, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@269d0f04, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@2c8acced, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@2dd7a722, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@200ab5b3, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@235e1770, lg_preferences_alerts_default_ringtone=com.a,ndroid.calendar.adaptation.PreferenceKey$KeyData@ad44ae9, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@246d136e, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@3370fa0f, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@9e53a9
,D/GeneralPreferenceUtils( 6853): [migratePrefrenceKeys] Exit: Version(44001600) >= 42001300
I/ActivityManager( 1031): Start proc com.google.android.syncadapters.calendar for service com.google.android.syncadapters.calendar/.CalendarSyncAdapterService: pid=6872 uid=10069 gids={50069, 9997, 3003} abi=armeabi-v7a
D/Config  ( 6853): [init]
I/Config  ( 6853): LGCalendar ver.4.40.16
I/Config  ( 6853): start check model
I/Config  ( 6853): start check native_ca
,I/Config  ( 6853): Config Operator=OPEN, Country=EU
D/Config  ( 6853): [setDefaultValuesToPref]
D/Config  ( 6853): [parseProfiles]
D/ProfilesParser( 6853): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6853): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6853): [updateProfiletoCountryInfo]
D/GeneralPreference( 6853): [checkAndMigrateOldPreference]
I/art     (  355): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 198us total 10.336ms
E/AgendaWidgetManager( 6853): [updateWidgets] 
I/art     (  355): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 188us total 8.969ms
,I/InitNotificationRingtoneService( 6853): Start InitializeAlertRingtoneService.onHandleIntent
I/art     (  355): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 192us total 9.222ms
I/AlertUtils( 6853): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/41
,I/AlertUtils( 6853): [getCalendarNotiSoundURIFromCursor] getCount()= 21
I/AlertUtils( 6853): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arpeggio.ogg
,I/AlertUtils( 6853): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 6853): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 6853): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 6853): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
,I/AlertUtils( 6853): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 6853): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 6853): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 6853): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 6853): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Afternoon_Walk.ogg
,W/AbstractGoogleClient( 6872): Application name is not set. Call Builder#setApplicationName.
,W/HolidayIntentService( 6853): onHandleIntent
D/MonthWidgetProvider( 6853): [onReceive]
D/CalendarWidgetProvider( 6853): [onReceive]
,D/CalendarWidgetProvider( 6853): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/HolidayDataLoader( 6853): readJsonAsset : holiday.json
I/ActivityManager( 1031): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6892 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi
D/CalendarTypeController( 6853): [onUpdateAndInitCalendarTime]
D/WeekWidgetProvider( 6853): [onReceive]
D/CalendarWidgetProvider( 6853): [onReceive]
D/CalendarWidgetProvider( 6853): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 6853): [onUpdateAndInitCalendarTime]
,W/ResourcesManager( 6892): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/art     ( 1031): Explicit concurrent mark sweep GC freed 21636(991KB) AllocSpace objects, 3(176KB) LOS objects, 33% free, 44MB/66MB, paused 1.827ms total 77.183ms
I/AlertUtils( 6853): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
,I/AlertUtils( 6853): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 6853): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 6853): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 6853): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6853): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/41
I/AlertUtils( 6853): set default noti to content://media/internal/audio/media/41
,I/InitNotificationRingtoneService( 6853): End InitializeAlertRingtoneService.onHandleIntent
D/GCM     ( 2134): GcmService start Intent { act=com.google.android.gcm.intent.SEND flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.gcm.intent.SEND
D/CalendarProvider2( 6892): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@30f2bbd1
I/DigitalAppWidgetProvider( 6810): onReceive: android.intent.action.ALARM_CHANGED
,D/WeatherAncestor( 6688): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 15:12:46
,D/Weather.Utils( 6688): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6688): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6688): 2 : This is isUpdating : false
E/HolidayIntentService( 6853): onHandleIntent:holiday data empty
D/Weather_cast( 6688): 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
D/WeatherAncestor( 6688): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 15:12:46
I/ActivityManager( 1031): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RequestWriter$NetworkStateReceiver: pid=6912 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager( 1031): Killing 4906:com.android.vending/u0a44 (adj 15): empty #17
D/CalendarProvider2( 6892): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 6892): Created com.android.providers.calendar.CalendarAlarmManager@35c51fc2(com.android.providers.calendar.CalendarProvider2@30f2bbd1)
,W/libprocessgroup( 1031): failed to open /acct/uid_10044/pid_4906/cgroup.procs: No such file or directory
V/GLSActivity( 2134): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 6912): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/GLSUser ( 2134): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2134): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2134): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2134): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2134): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2134): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2134): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2134): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2134): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2134): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2134): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2134): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6538): Authentication error
E/BooksAccountManager( 6538): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6538): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6538): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6538): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6538): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6538): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6538): null auth token
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
D/LgeQuickCoverOverlayWindow( 1410): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1410): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1410): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1410): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1410): updateNotificationData: count=3
D/QuickStatusbarLayout( 1410): Notification difference=198
,D/QuickStatusbarLayout( 1410): child = android.widget.LinearLayout{2a8c721b V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/LgDataFeature( 6912): LgDataFeature() Constructor: none
D/LgDataFeature( 6912): LgDataFeature() Constructor Done, null
I/GLSUser ( 2134): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.calendar, service: oauth2:https://www.googleapis.com/auth/calendar
,I/GLSUser ( 2134): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/calendar without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2134): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2134): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2134): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ApiaryClient( 6538): Error response from books API: {
W/ApiaryClient( 6538):  "error": {
W/ApiaryClient( 6538):   "errors": [
W/ApiaryClient( 6538):    {
W/ApiaryClient( 6538):     "domain": "global",
W/ApiaryClient( 6538):     "reason": "required",
W/ApiaryClient( 6538):     "message": "Login Required",
W/ApiaryClient( 6538):     "locationType": "header",
W/ApiaryClient( 6538):     "location": "Authorization"
W/ApiaryClient( 6538):    }
W/ApiaryClient( 6538):   ],
W/ApiaryClient( 6538):   "code": 401,
W/ApiaryClient( 6538):   "message": "Login Required"
W/ApiaryClient( 6538):  }
W/ApiaryClient( 6538): }
W/ApiaryClient( 6538): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6538): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=4091843801435115809&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6538): Headers:
W/ApiaryClient( 6538): accept-encoding: [gzip]
W/ApiaryClient( 6538): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6538): gdata-version: 2
,V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,D/LgeQuickCoverNLService( 1410): onNotificationPosted
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
E/CalendarSyncAdapter( 6872): Exception in onPerformLoggedSync 
E/CalendarSyncAdapter( 6872): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/CalendarSyncAdapter( 6872): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(GoogleRequestInitializer.java:152)
E/CalendarSyncAdapter( 6872): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(GoogleRequestInitializer.java:89)
E/CalendarSyncAdapter( 6872): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:858)
E/CalendarSyncAdapter( 6872): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(AbstractGoogleClientRequest.java:410)
E/CalendarSyncAdapter( 6872): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(AbstractGoogleClientRequest.java:343)
E/CalendarSyncAdapter( 6872): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(AbstractGoogleClientRequest.java:460)
E/CalendarSyncAdapter( 6872): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.processAccountCalendars(CalendarSyncAdapterApiary.java:1510)
E/CalendarSyncAdapter( 6872): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.updateCalendarsFromServerFeed(CalendarSyncAdapterApiary.java:1024)
E/CalendarSyncAdapter( 6872): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.getServerDiffs(CalendarSyncAdapterApiary.java:906)
E/CalendarSyncAdapter( 6872): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.performSync(CalendarSyncAdapterApiary.java:430)
E/CalendarSyncAdapter( 6872): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.onPerformLoggedSync(CalendarSyncAdapterApiary.java:335)
E/CalendarSyncAdapter( 6872): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
E/CalendarSyncAdapter( 6872): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/CalendarSyncAdapter( 6872): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/CalendarSyncAdapter( 6872): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/CalendarSyncAdapter( 6872): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/CalendarSyncAdapter( 6872): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(GoogleRequestInitializer.java:140)
E/CalendarSyncAdapter( 6872): 	... 12 mo,re
I/ActivityManager( 1031): Killing 6178:com.lge.sync/1000 (adj 15): empty #17
I/Babel   ( 6912): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 6912): MmsConfig.loadMmsSettings
D/QuickStatusbarLayout( 1410): Notification difference=198
D/QuickStatusbarLayout( 1410): child = android.widget.LinearLayout{2a8c721b V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/AudioCapabilities( 6912): Unsupported mime audio/evrc
,W/AudioCapabilities( 6912): Unsupported mime audio/qcelp
W/VideoCapabilities( 6912): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6912): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6912): Unsupported mime audio/qcelp
W/AudioCapabilities( 6912): Unsupported mime audio/evrc
W/VideoCapabilities( 6912): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 6912): Unsupported mime video/divx
W/VideoCapabilities( 6912): Unsupported mime video/divx311
W/VideoCapabilities( 6912): Unsupported mime video/divx4
W/VideoCapabilities( 6912): Unsupported mime video/mp4v-esdp
I/VideoCapabilities( 6912): Unsupported profile 4 for video/mp4v-es
,W/AudioCapabilities( 6912): Unsupported mime audio/eac3
W/AudioCapabilities( 6912): Unsupported mime audio/ac3
W/AudioCapabilities( 6912): Unsupported mime audio/g726
W/AudioCapabilities( 6912): Unsupported mime audio/wma-voice
W/AudioCapabilities( 6912): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6912): Unsupported mime audio/adpcm
W/VideoCapabilities( 6912): Unsupported mime video/theora
W/VideoCapabilities( 6912): Unsupported mime video/mjpg
W/libprocessgroup( 1031): failed to open /acct/uid_1000/pid_6178/cgroup.procs: No such file or directory
,D/SyncManager( 1031): failed sync operation thalitester@gmail.com u0 (com.google), com.android.calendar, PERIODIC, currentRunTime 39963, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
I/ActivityManager( 1031): Killing 5876:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
D/SyncManager( 1031): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.calendar, PERIODIC, currentRunTime 159431, reason: Periodic
I/Babel   ( 6912): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
I/Babel   ( 6912): MmsConfig.loadFromDatabase
I/QRemote ( 6001): [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
W/System.err( 6001): android.os.DeadObjectException
W/System.err( 6001): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6001): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6001): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 6001): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
,W/System.err( 6001): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 6001): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 6001): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6001): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6001): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6001): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 6001): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6001): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6001): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 6001): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 6001): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 6001): android.os.DeadObjectException
W/System.err( 6001): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6001): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6001): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 6001): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
W/System.err( 6001): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 6001): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 6001): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6001): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6001): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6001): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 6001): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6001): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6001): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 6001): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 6001): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/QRemote ( 6001): [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,E/Babel   ( 6912): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 6912): MmsConfig.loadFromResources
E/Babel   ( 6912): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 6912): MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
E/libprocessgroup( 1031): failed to kill 1 processes for processgroup 5876
,W/ActivityManager( 1031): Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,W/Settings( 6912): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/QRemote ( 6001): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
I/QRemote ( 6001): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,I/ActivityManager( 1031): Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6950 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,D/QRemote ( 6001): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,D/UEI.SmartControl( 6950): Quickset Services start...
,I/UEI.SmartControl( 6950): Manufacture = LGE
D/UEI.SmartControl( 6950): Id = LGNevo
D/UEI.SmartControl( 6950): File observer start...
E/UEI.SmartControl( 6950): IR Port is disabled: false
D/UEI.SmartControl( 6950): Starting file observer...
D/UEI.SmartControl( 6950): Extracting JNI libs...
D/UEI.SmartControl( 6950): --- this system supports 32-bit or 64-bit only
W/ResourcesManager( 6912): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6912): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/UEI.SmartControl( 6950): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 6950): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6950): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,V/JNIHelp ( 6912): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/UEI.SmartControl( 6950): --- Selecting new region: 6
I/UEI.SmartControl( 6950): Model = LG-D855
D/UEI.SmartControl( 6950): QS Service created
I/UEI.SmartControl( 6950): Service initServices...
,D/UEI.SmartControl( 6950): QS start get config
,I/GCoreUlr( 1831): Uploading GCM registration ID for account#2#
W/System  ( 6912): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/system/app/Hangouts/Hangouts.apk"],nativeLibraryDirectories=[/system/app/Hangouts/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6912): Installed default security provider GmsCore_OpenSSL
,W/BaseAppContext( 1831): Using Auth Proxy for data requests.
,D/UEI.SmartControl( 6950): Loading JNI Libs...
I/GLSUser ( 1831): [ChannelManager] Attempting to channel bind connection HttpClient.
,I/GLSUser ( 1831): [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
I/GLSUser ( 2134): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/userlocation.reporting
I/GLSUser ( 2134): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/userlocation.reporting without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2134): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2134): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2134): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=5.4, 0.0, 0.0  rx=3.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-880345788] gl rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=5.4, 0.0, 0.0  rx=3.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-880345787] gl rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/GLSUser ( 2134): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native
I/GLSUser ( 2134): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2134): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2134): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2134): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/GCoreUlr( 1831): 
E/GCoreUlr( 1831): com.google.android.gms.auth.ad: BadAuthentication
E/GCoreUlr( 1831): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/GCoreUlr( 1831): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/GCoreUlr( 1831): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/GCoreUlr( 1831): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/GCoreUlr( 1831): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/GCoreUlr( 1831): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/GCoreUlr( 1831): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/GCoreUlr( 1831): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/GCoreUlr( 1831): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/GCoreUlr( 1831): 	at com.google.android.location.reporting.c.c.a(SourceFile:166)
E/GCoreUlr( 1831): 	at com.google.android.location.reporting.c.g.a(SourceFile:111)
E/GCoreUlr( 1831): 	at com.google.android.location.reporting.service.t.b(SourceFile:220)
E/GCoreUlr( 1831): 	at com.google.android.location.reporting.service.t.a(SourceFile:173)
E/GCoreUlr( 1831): 	at com.google.android.location.reporting.service.s.onPerformSync(SourceFile:149)
E/GCoreUlr( 1831): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/Babel   ( 6912): UserRecoverableAuthException.
E/Babel   ( 6912): cfq: BadAuthentication
E/Babel   ( 6912): 	at cfn.a(Unknown Source)
E/Babel   ( 6912): 	at f.a(PG:191)
E/Babel   ( 6912): 	at ava.a(PG:88)
E/Babel   ( 6912): 	at ava.a(PG:128)
E/Babel   ( 6912): 	at bjs.a(PG:255)
E/Babel   ( 6912): 	at bep.a(PG:602)
E/Babel   ( 6912): 	at bep.a(PG:469)
E/Babel   ( 6912): 	at bpo.run(PG:1141)
E/Babel   ( 6912): Error getting auth token
E/Babel   ( 6912): bxl
E/Babel   ( 6912): 	at f.a(PG:201)
E/Babel   ( 6912): 	at ava.a(PG:88)
E/Babel   ( 6912): 	at ava.a(PG:128)
E/Babel   ( 6912): 	at bjs.a(PG:255)
E/Babel   ( 6912): 	at bep.a(PG:602)
E/Babel   ( 6912): 	at bep.a(PG:469)
E/Babel   ( 6912): 	at bpo.run(PG:1141)
I/Babel_RequestWriter( 6912): error sending REQ[fc:12; creat:1455067840947; type:bev-252085865]; took 107 ms (error code == 100)
,E/Babel   ( 6912): Account registration failedRedacted-21
E/Babel   ( 6912): bph: null -- null
E/Babel   ( 6912): 	at ava.a(PG:120)
E/Babel   ( 6912): 	at ava.a(PG:128)
E/Babel   ( 6912): 	at bjs.a(PG:255)
E/Babel   ( 6912): 	at bep.a(PG:602)
E/Babel   ( 6912): 	at bep.a(PG:469)
E/Babel   ( 6912): 	at bpo.run(PG:1141)
I/Babel   ( 6912): Account setup failed with error state:106 account:Redacted-21
I/Babel   ( 6912): Account sign in complete with state 106account: Redacted-21
D/SyncManager( 1031): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.location.reporting, PERIODIC, currentRunTime 39983, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager( 1031): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.location.reporting, PERIODIC, currentRunTime 158913, reason: Periodic
I/art     ( 6912): Note: end time exceeds epoch: 
,I/GLSUser ( 2134): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native
,I/GLSUser ( 2134): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2134): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2134): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2134): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 2134): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1410): onNotificationPosted
D/SmartCoverUpdateMonitor( 1410): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1410): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1410): handleNotificationPosted(true)
D/QuickCircle( 1410): onNotificationPosted() : isPosted true
E/Babel   ( 6912): Unexpected exception while authenticating.
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
E/Babel   ( 6912): cfr: User intervention required. Notification has been pushed.
E/Babel   ( 6912): 	at cfn.b(Unknown Source)
E/Babel   ( 6912): 	at cfn.a(Unknown Source)
E/Babel   ( 6912): 	at f.a(PG:188)
E/Babel   ( 6912): 	at ava.b(PG:143)
E/Babel   ( 6912): 	at bnr.run(PG:5415)
E/Babel   ( 6912): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 6912): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 6912): 	at java.lang.Thread.run(Thread.java:818)
D/LgeQuickCoverOverlayWindow( 1410): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1410): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1410): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1410): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1410): updateNotificationData: count=3
,D/QuickStatusbarLayout( 1410): Notification difference=198
D/QuickStatusbarLayout( 1410): child = android.widget.LinearLayout{2a8c721b V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,I/UEI.SmartControl( 6950): Supports setup maps: true
,D/UEI.SmartControl( 6950): QS start statue = true Error code = 0
I/UEI.SmartControl( 6950): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6950): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6950): ### init IR Blaster...
D/serial_port( 6950): Configuring serial port
,E/UEI.SmartControl( 6950): UEIBLaster setting for 616
I/UEI.SmartControl( 6950): Setting serial record hearder size = 2
I/art     ( 2134): Explicit concurrent mark sweep GC freed 28015(1593KB) AllocSpace objects, 11(1328KB) LOS objects, 50% free, 30MB/62MB, paused 1.181ms total 47.420ms
I/UEI.SmartControl( 6950): configuring settings for MAXQ616
I/UEI.SmartControl( 6950): Get version...
D/UEI.SmartControl( 6950): serial port data available: 21
,D/UEI.SmartControl( 6950): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 6950): IR Blaster version: 256702256704300002
,I/UEI.SmartControl( 6950): QS saving settings...
D/UEI.SmartControl( 6950): IR Blaster version: 25672567
D/UEI.SmartControl( 6950): serial port data available: 4
,I/UEI.SmartControl( 6950): Device manager: loading config....
D/UEI.SmartControl( 6950): ----------- loading internal config...
,W/ContextImpl( 6950): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,E/UEI.SmartControl( 6950): Loading SETTINGS...
D/UEI.SmartControl( 6950): -- Open brand translation xml: brands_translations_ko
,I/UEI.SmartControl( 6950): Notify AllClients services are ready: 0
,D/UEI.SmartControl( 6950): -----service ready thread exits
,I/ActivityManager( 1031): Start proc com.google.android.gm for service com.google.android.gm/.provider.MailSyncAdapterService: pid=7000 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/UEI.SmartControl( 6950): Services init done
D/UEI.SmartControl( 6950): QS Service init finished
,D/UEI.SmartControl( 6950): QS Service version name: 2.1.91
D/UEI.SmartControl( 6950): QS Service version code: 201091
V/GLSActivity( 2134): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/UEI.SmartControl( 6950): Service requested: Control
I/QRemote ( 6001): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/ActivityManager( 1031): Killing 6205:com.android.settings/1000 (adj 15): empty #17
,I/UEI.SmartControl( 6950): ------ IControl API: 11
I/UEI.SmartControl( 6950): Registering callback...
I/UEI.SmartControl( 6950): ------ IControl API: 19
I/UEI.SmartControl( 6950): Registering Services Ready callback...
I/UEI.SmartControl( 6950): Notify client services are ready...
I/QRemote ( 6001): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
,D/QRemote ( 6001): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 6001): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/WifiService( 1031): Client connection lost with reason: 4
D/QRemote ( 6001): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 6001): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6950): ------ IControl API: 8
D/QRemote ( 6001): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 6001): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 6001): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 6001): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 6001): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6001): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
W/libprocessgroup( 1031): failed to open /acct/uid_1000/pid_6205/cgroup.procs: No such file or directory
D/UEI.SmartControl( 6950): Internal service binding...
,D/QRemote ( 6001): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
V/QRemote ( 6001): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,D/QRemote ( 6001): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 6001): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6001): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 6001): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6001): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 6001): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
,D/QRemote ( 6001): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1455113567971]
D/QRemote ( 6001): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
I/GLSUser ( 2134): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2134): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2134): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2134): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/QRemote ( 6001): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
V/GLSActivity( 2134): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/QRemote ( 6001): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6001): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 6001): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 6001): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 6001): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 6001): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 6001): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/GLSActivity( 2134): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2134): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2134): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2134): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2134): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2134): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2134): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverOverlayWindow( 1410): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1410): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1410): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1410): isNotificationForCurrentUser : true
E/BooksAccountManager( 6538): Authentication error
E/BooksAccountManager( 6538): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6538): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6538): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6538): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6538): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6538): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6538): null auth token
D/LgeQuickCoverOverlayWindow( 1410): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1410): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1410): updateNotificationData: count=3
,D/QuickStatusbarLayout( 1410): Notification difference=198
D/QuickStatusbarLayout( 1410): child = android.widget.LinearLayout{2a8c721b V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6538): Error response from books API: {
W/ApiaryClient( 6538):  "error": {
W/ApiaryClient( 6538):   "errors": [
W/ApiaryClient( 6538):    {
W/ApiaryClient( 6538):     "domain": "global",
W/ApiaryClient( 6538):     "reason": "required",
W/ApiaryClient( 6538):     "message": "Login Required",
W/ApiaryClient( 6538):     "locationType": "header",
W/ApiaryClient( 6538):     "location": "Authorization"
W/ApiaryClient( 6538):    }
W/ApiaryClient( 6538):   ],
W/ApiaryClient( 6538):   "code": 401,
W/ApiaryClient( 6538):   "message": "Login Required"
W/ApiaryClient( 6538):  }
W/ApiaryClient( 6538): }
,W/ApiaryClient( 6538): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6538): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=4091843801435115809&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6538): Headers:
W/ApiaryClient( 6538): accept-encoding: [gzip]
W/ApiaryClient( 6538): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6538): gdata-version: 2
W/ActivityManager( 1031): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/ActivityThread( 7000): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
W/ActivityManager( 1031): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager( 1031): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,W/ActivityManager( 1031): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/ActivityManager( 1031): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/art     ( 1031): Explicit concurrent mark sweep GC freed 20165(913KB) AllocSpace objects, 5(592KB) LOS objects, 33% free, 44MB/66MB, paused 1.957ms total 120.481ms
,I/Gmail   ( 7000): Observing account changes for notifications
W/ActivityManager( 1031): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 7000): getAccountsCursor
,V/GLSActivity( 2134): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 7000): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager( 1031): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/Gmail   ( 7000): Sync started for account: account:61035162
,E/Gmail   ( 7000): Error finding the version of the Email provider.....
E/Gmail   ( 7000): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 7000): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 7000): 	at com.google.android.gm.EmailMigrationService.aU(SourceFile:1235)
E/Gmail   ( 7000): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:187)
E/Gmail   ( 7000): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 7000): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 7000): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 7000): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/EmailMigration( 7000): We do not support migrating this version of the Email provider.
I/Gmail   ( 7000): getAccountsCursor
V/GLSActivity( 2134): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SQLiteLog( 7000): (283) recovered 1624 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,I/Gmail   ( 7000): notifyAccountChanged
,I/Gmail   ( 7000): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 7000): notifyAccountChanged
I/Gmail   ( 7000): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 7000): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 7000): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 7000): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 5310, normalSync: true
,V/GLSActivity( 2134): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 7000): getAccountsCursor
I/Gmail   ( 7000): getAccountsCursor
,V/GLSActivity( 2134): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 7000): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7000): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7000): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/System  ( 7000): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[directory "."],nativeLibraryDirectories=[/vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7000): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 2134): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2134): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gm, service: mail
I/GLSUser ( 2134): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> mail without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2134): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2134): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2134): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
,W/GLSActivity( 2134): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2134): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2134): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2134): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2134): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2134): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2134): 	at android.os.Binder.execTransact(Binder.java:446)
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1410): onNotificationPosted
,V/GLSActivity( 2134): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
D/QuickStatusbarLayout( 1410): Notification difference=198
D/QuickStatusbarLayout( 1410): child = android.widget.LinearLayout{2a8c721b V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,I/GLSUser ( 2134): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gm, service: mail
I/GLSUser ( 2134): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> mail without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2134): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2134): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2134): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2134): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2134): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2134): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2134): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2134): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2134): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2134): 	at android.os.Binder.execTransact(Binder.java:446)
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
I/Gmail   ( 7000): notifyAccountChanged
,I/Gmail   ( 7000): getAccountsCursor
V/GLSActivity( 2134): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/QuickStatusbarLayout( 1410): Notification difference=198
D/QuickStatusbarLayout( 1410): child = android.widget.LinearLayout{2a8c721b V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/Gmail   ( 7000): notifyAccountChanged
,W/Gmail   ( 7000): Sync complete for account: account:61035162
I/Gmail   ( 7000): getAccountsCursor
V/GLSActivity( 2134): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/SyncManager( 1031): failed sync operation thalitester@gmail.com u0 (com.google), gmail-ls, PERIODIC, currentRunTime 40040, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager( 1031): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), gmail-ls, PERIODIC, currentRunTime 159221, reason: Periodic
,I/ActivityManager( 1031): Killing 6520:com.lge.appbox.client/u0a11 (adj 15): empty #17
,W/libprocessgroup( 1031): failed to open /acct/uid_10011/pid_6520/cgroup.procs: No such file or directory
,E/BooksSync( 6538): Soft error: 
E/BooksSync( 6538): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6538): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=4091843801435115809&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6538): Headers:
E/BooksSync( 6538): accept-encoding: [gzip]
E/BooksSync( 6538): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6538): gdata-version: 2
E/BooksSync( 6538): 
E/BooksSync( 6538): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6538): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6538): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6538): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6538): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6538): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6538): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6538): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6538): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6538): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6538): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6538): {
E/BooksSync( 6538):  "error": {
E/BooksSync( 6538):   "errors": [
E/BooksSync( 6538):    {
E/BooksSync( 6538):     "domain": "global",
E/BooksSync( 6538):     "reason": "required",
E/BooksSync( 6538):     "message": "Login Required",
E/BooksSync( 6538):     "locationType": "header",
E/BooksSync( 6538):     "location": "Authorization"
E/BooksSync( 6538):    }
E/BooksSync( 6538):   ],
E/BooksSync( 6538):   "code": 401,
E/BooksSync( 6538):   "message": "Login Required"
E/BooksSync( 6538):  }
E/BooksSync( 6538): }
E/BooksSync( 6538): 
E/BooksSync( 6538): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6538): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6538): 	... 8 more
E/BooksSync( 6538): Sync error
E/BooksSync( 6538): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6538): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=4091843801435115809&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6538): Headers:
E/BooksSync( 6538): accept-encoding: [gzip]
E/BooksSync( 6538): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6538): gdata-version: 2
E/BooksSync( 6538): 
E/BooksSync( 6538): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6538): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6538): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6538): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6538): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6538): 	at com.google.android.apps.books.data.NetworkTaskQ,ueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6538): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6538): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6538): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6538): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6538): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6538): {
E/BooksSync( 6538):  "error": {
E/BooksSync( 6538):   "errors": [
E/BooksSync( 6538):    {
E/BooksSync( 6538):     "domain": "global",
E/BooksSync( 6538):     "reason": "required",
E/BooksSync( 6538):     "message": "Login Required",
E/BooksSync( 6538):     "locationType": "header",
E/BooksSync( 6538):     "location": "Authorization"
E/BooksSync( 6538):    }
E/BooksSync( 6538):   ],
E/BooksSync( 6538):   "code": 401,
E/BooksSync( 6538):   "message": "Login Required"
E/BooksSync( 6538):  }
E/BooksSync( 6538): }
E/BooksSync( 6538): 
E/BooksSync( 6538): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6538): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6538): 	... 8 more
I/BooksSync( 6538): Finished books sync
,D/SyncManager( 1031): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 27052, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
I/ActivityManager( 1031): Killing 6144:com.lge.formmanager/u0a26 (adj 15): empty #17
W/libprocessgroup( 1031): failed to open /acct/uid_10026/pid_6144/cgroup.procs: No such file or directory
,I/ActivityManager( 1031): Start proc com.google.android.apps.docs for service com.google.android.apps.docs/.sync.syncadapter.DocsSyncAdapterService: pid=7046 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/DocsApplication( 7046): Installing DEX configuration.
,D/DexInstaller( 7046): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
I/PackageInfoHelper( 7046): Provided clientMode=RELEASE, packageInfo=PackageInfo{30f2bbd1 com.google.android.apps.docs}
D/TAG     ( 7046): onCreate()
,D/CrossAppStateProvider( 7046): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
I/GLSUser ( 2134): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/reminders
,I/GLSUser ( 2134): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/reminders without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2134): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2134): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2134): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/ReminderSync( 2367): AuthError [T SyncAdapterThread-1:id=267:priority=5:group=main]
,D/SyncManager( 1031): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.gms.reminders, PERIODIC, currentRunTime 40055, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager( 1031): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.gms.reminders, PERIODIC, currentRunTime 160683, reason: Periodic
,I/SyncAdapterService( 6709): Ignoring sync request for non-current account
,W/BaseAppContext( 2367): Using Auth Proxy for data requests.
,W/BaseAppContext( 2367): Using Auth Proxy for data requests.
W/BaseAppContext( 2367): Using Auth Proxy for data requests.
,W/BaseAppContext( 2367): Using Auth Proxy for data requests.
I/art     ( 2134): Explicit concurrent mark sweep GC freed 14064(795KB) AllocSpace objects, 8(1152KB) LOS objects, 50% free, 30MB/62MB, paused 1.502ms total 48.800ms
,W/BaseAppContext( 2367): Using Auth Proxy for data requests.
,W/BaseAppContext( 2367): Using Auth Proxy for data requests.
,I/art     ( 2367): Explicit concurrent mark sweep GC freed 11876(741KB) AllocSpace objects, 5(80KB) LOS objects, 49% free, 32MB/64MB, paused 1.345ms total 77.235ms
,W/BaseAppContext( 2367): Using Auth Proxy for data requests.
,I/GoogleHttpClient( 5262): Falling back to old http client 0 java.lang.NoSuchMethodException: <init> [class android.content.Context, class java.lang.String, boolean, boolean]
,I/GAV2    ( 6538): Thread[GAThread,5,main]: No campaign data found.
,I/art     ( 1031): Explicit concurrent mark sweep GC freed 24149(1057KB) AllocSpace objects, 5(336KB) LOS objects, 33% free, 44MB/66MB, paused 2.045ms total 130.056ms
,V/GLSActivity( 2134): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2134): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.music, service: sj
I/GLSUser ( 2134): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> sj without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2134): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2134): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2134): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/GLSActivity( 2134): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2134): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2134): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2134): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2134): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2134): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2134): 	at android.os.Binder.execTransact(Binder.java:446)
,D/QuickStatusbarLayout( 1410): Notification difference=198
D/QuickStatusbarLayout( 1410): child = android.widget.LinearLayout{2a8c721b V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/MusicSyncAdapter( 5262): Sync failed due to an authentication issue.
,D/SyncManager( 1031): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.music.MusicContent, PERIODIC, currentRunTime 40067, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager( 1031): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.music.MusicContent, PERIODIC, currentRunTime 160741, reason: Periodic
,E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5262): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5262): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5262): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5262): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/ActivityManager( 1031): Start proc com.google.android.videos for service com.google.android.videos/.store.SyncService: pid=7087 uid=10103 gids={50103, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ArtDownloadService( 5262): Setting cache size 0
,W/ResourcesManager( 7087): Asset path '/system/framework/com.google.widevine.software.drm.jar' does not exist or contains no resources.
,W/ArtDownloadService( 5262): Setting cache size 0
I/ActivityManager( 1031): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=7114 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/MusicLeanback( 5262): Conditions not met for autocaching.
I/MusicLeanback( 5262): Stop autocaching.
,W/ResourcesManager( 7114): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7114): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/MultiDex( 7114): VM with version 2.1.0 has multidex support
I/MultiDex( 7114): install
I/MultiDex( 7114): VM has multidex support, MultiDex support library is disabled.
,I/GAV4    ( 6709): Thread[GAThread,5,main]: No campaign data found.
V/JNIHelp ( 7114): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5262): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/cache
E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5262): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/cache
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=30.2, 0.0, 0.0  rx=25.2 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-880342773] gl rssi=-60 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=30.2, 0.0, 0.0  rx=25.2 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-880342772] gl rssi=-60 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
D/LgDataFeature( 7087): LgDataFeature() Constructor: none
D/LgDataFeature( 7087): LgDataFeature() Constructor Done, null
,W/ActivityThread( 7114): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7114): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2ba82cc: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7114): Installed default security provider GmsCore_OpenSSL
D/GCM     ( 2134): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 2134): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GmsCoreStatsServiceLauncher( 2367): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
D/WearableService( 7114): callingUid 10005, callindPid: 7114
D/LgDataFeature( 7046): LgDataFeature() Constructor: none
D/LgDataFeature( 7046): LgDataFeature() Constructor Done, null
,D/LocationInitializer( 2367): Restart initialization of location
E/MDM     ( 1831): [86] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/WearableClient( 5262): WearableClientImpl.onPostInitHandler: done
D/WearableClient( 5262): WearableClientImpl.onPostInitHandler: done
E/GmsUtils( 5262): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,D/PlayMovies( 7087): PersistentCache.cleanup:103 Cache is below limit, no need to shrink: [size=0, limit=5242880]
,W/GAV2    ( 7046): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/PlayMovies( 7087): TransferService.onCreate:52 creating transfer service
,W/AudioCapabilities( 7087): Unsupported mime audio/evrc
,W/AudioCapabilities( 7087): Unsupported mime audio/qcelp
W/VideoCapabilities( 7087): Unrecognized profile 2130706433 for video/avc
D/WifiService( 1031): acquireWifiLockLocked: WifiLock{SyncManager type=1 binder=android.os.BinderProxy@307cdf2d}
E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.videos/files/Movies/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7087): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.videos/files/Movies
W/AudioCapabilities( 7087): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 7087): Unsupported mime audio/qcelp
W/AudioCapabilities( 7087): Unsupported mime audio/evrc
W/VideoCapabilities( 7087): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 7087): Unsupported mime video/divx
W/VideoCapabilities( 7087): Unsupported mime video/divx311
W/VideoCapabilities( 7087): Unsupported mime video/divx4
W/ResourcesManager( 2367): Asset path '/system/framework/com.google.widevine.software.drm.jar' does not exist or contains no resources.
,W/VideoCapabilities( 7087): Unsupported mime video/mp4v-esdp
D/libc-netbsd(  320): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  320): res_queryN name = ssl.gstatic.com, class = 1, type = 1
I/VideoCapabilities( 7087): Unsupported profile 4 for video/mp4v-es
,W/AudioCapabilities( 7087): Unsupported mime audio/eac3
W/AudioCapabilities( 7087): Unsupported mime audio/ac3
I/GLSUser ( 2134): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.videos, service: oauth2:https://www.googleapis.com/auth/android_video https://www.googleapis.com/auth/youtube https://www.googleapis.com/auth/pos
I/GLSUser ( 2134): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/android_video https://www.googleapis.com/auth/youtube https://www.googleapis.com/auth/pos without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2134): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2134): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
W/AudioCapabilities( 7087): Unsupported mime audio/g726
W/AudioCapabilities( 7087): Unsupported mime audio/wma-voice
W/AudioCapabilities( 7087): Unsupported mime audio/x-ms-wma
V/GLSActivity( 2134): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/AudioCapabilities( 7087): Unsupported mime audio/adpcm
W/VideoCapabilities( 7087): Unsupported mime video/theora
,W/VideoCapabilities( 7087): Unsupported mime video/mjpg
D/libc-netbsd(  320): res_queryN name = ssl.gstatic.com succeed
,V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
D/LgeQuickCoverOverlayWindow( 1410): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1410): isNotificationForCurrentUser : true
E/PlayMovies( 7087): GmsAccountManagerWrapper.blockingGetAuthTokenInternal:100 Cannot get user auth
E/PlayMovies( 7087): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/PlayMovies( 7087): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/PlayMovies( 7087): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/PlayMovies( 7087): 	at com.google.android.videos.accounts.GmsAccountManagerWrapper.blockingGetAuthTokenInternal(GmsAccountManagerWrapper.java:85)
E/PlayMovies( 7087): 	at com.google.android.videos.accounts.AccountManagerWrapper.blockingGetAuthToken(AccountManagerWrapper.java:186)
E/PlayMovies( 7087): 	at com.google.android.videos.accounts.AccountManagerWrapper.blockingAuthenticate(AccountManagerWrapper.java:162)
E/PlayMovies( 7087): 	at com.google.android.videos.store.SyncService$SyncAdapter.onPerformSync(SyncService.java:225)
E/PlayMovies( 7087): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/LgeQuickCoverOverlayWindow( 1410): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1410): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1410): updateNotificationData: count=3
D/SyncManager( 1031): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.videos.sync, PERIODIC, currentRunTime 40069, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager( 1031): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.videos.sync, PERIODIC, currentRunTime 161480, reason: Periodic
,I/ActivityManager( 1031): Killing 6662:com.lge.drmservice/u0a62 (adj 15): empty #17
D/QuickStatusbarLayout( 1410): Notification difference=198
D/QuickStatusbarLayout( 1410): child = android.widget.LinearLayout{2a8c721b V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/libprocessgroup( 1031): failed to open /acct/uid_10062/pid_6662/cgroup.procs: No such file or directory
,I/ActivityManager( 1031): Killing 6600:com.android.chrome/u0a57 (adj 15): empty #17
,W/libprocessgroup( 1031): failed to open /acct/uid_10057/pid_6600/cgroup.procs: No such file or directory
,E/Auth.Api.Credentials( 2367): [CredentialSyncAdapter] Unknown sync event.
,V/GLSActivity( 2134): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2134): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 2134): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2134): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2134): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/LocSvc_java( 1031): requestTime failed
D/LocSvc_java( 1031): Sending msg: 10 arg1:0 arg2:1
V/GLSActivity( 2134): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2134): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2134): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2134): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2134): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2134): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2134): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2134): 	at android.os.Binder.execTransact(Binder.java:446)
,D/ContactsSyncAdapter( 2134): innerSync failed
D/ContactsSyncAdapter( 2134): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2134): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2134): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2134): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2134): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2134): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2134): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2134): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2134): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2134): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2134): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2134): 	at android.os.Binder.execTransact(Binder.java:446)
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
D/LgeQuickCoverOverlayWindow( 1410): [native noti] inex =  1
,D/LgeQuickCoverNotificationData( 1410): isNotificationForCurrentUser : true
D/SyncManager( 1031): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 156597, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
D/LgeQuickCoverOverlayWindow( 1410): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1410): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1410): updateNotificationData: count=3
D/QuickStatusbarLayout( 1410): Notification difference=198
D/QuickStatusbarLayout( 1410): child = android.widget.LinearLayout{2a8c721b V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,I/ActivityManager( 1031): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=7195 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager( 1031): RTC_WAKEUP set : Alarm{1018ba36 type 0 when 1455113571853 com.android.vending} when 1455113571853
,D/Finsky  ( 7195): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/LgDataFeature( 7195): LgDataFeature() Constructor: none
D/LgDataFeature( 7195): LgDataFeature() Constructor Done, null
,D/Finsky  ( 7195): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/ActivityManager( 1031): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=7250 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/Settings( 7195): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7195): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ResourcesManager( 7250): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7250): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/DownloadManager( 3300): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,D/Finsky  ( 7195): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7195): [1] 2.run: Finished loading 1 libraries.
V/DownloadManager( 3300): created cursor android.database.sqlite.SQLiteCursor@1b4d282b on behalf of 7195
,I/ActivityManager( 1031): Killing 6555:com.android.gallery3d/u0a27 (adj 15): empty #17
D/Finsky  ( 7195): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/MultiDex( 7250): VM with version 2.1.0 has multidex support
I/MultiDex( 7250): install
I/MultiDex( 7250): VM has multidex support, MultiDex support library is disabled.
,W/libprocessgroup( 1031): failed to open /acct/uid_10027/pid_6555/cgroup.procs: No such file or directory
,V/JNIHelp ( 7250): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/Finsky  ( 7195): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
V/SIM_STK ( 1031): Menu title from STK is T-Mobile
,D/UEI.SmartControl( 6950): Internal timer expired: 1
D/UEI.SmartControl( 6950): unbind internal service
W/ActivityThread( 7250): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7250): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2ba82cc: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7250): Installed default security provider GmsCore_OpenSSL
D/GCM     ( 2134): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 2134): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GmsCoreStatsServiceLauncher( 2367): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/serial_port( 6950): close(fd = 25)
I/UEI.SmartControl( 6950): Serial port is closed.
,E/MDM     ( 1831): [87] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 2367): Restart initialization of location
,V/Finsky  ( 7195): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,I/art     ( 1031): Explicit concurrent mark sweep GC freed 33786(1583KB) AllocSpace objects, 10(544KB) LOS objects, 33% free, 44MB/66MB, paused 2.055ms total 96.122ms
,I/art     ( 2134): Explicit concurrent mark sweep GC freed 12773(715KB) AllocSpace objects, 9(1296KB) LOS objects, 50% free, 30MB/62MB, paused 1.742ms total 47.424ms
,V/GLSActivity( 2134): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2134): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2134): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2134): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2134): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2134): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GAV2    ( 7000): Thread[GAThread,5,main]: No campaign data found.
,D/Finsky  ( 7195): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 7195): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7195): [1] 5.onFinished: Scheduling replication attempt 2.
V/AlarmManager( 1031): RTC_WAKEUP set : Alarm{5429304 type 0 when 1455113573399 com.android.vending} when 1455113573399
,D/Finsky  ( 7195): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
V/GLSActivity( 2134): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2134): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2134): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2134): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2134): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2134): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 7195): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 2134): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2134): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 2134): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2134): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2134): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2134): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=17.6, 0.0, 0.0  rx=14.1 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-880339758] gl rssi=-60 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=17.6, 0.0, 0.0  rx=14.1 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-880339757] gl rssi=-60 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
V/GLSActivity( 2134): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2134): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 2134): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2134): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2134): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2134): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 7195): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/SIM_STK ( 1031): Menu title from STK is T-Mobile
,V/GLSActivity( 2134): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2134): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2134): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2134): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2134): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2134): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 7195): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 7195): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
D/Finsky  ( 7195): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7195): [1] DailyHygiene.reschedule: Scheduling new run in 10 minutes (failures=1)
I/ActivityManager( 1031): Killing 5189:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,D/DeviceConnectionService( 1831): client connected with version: 7571000
I/ActivityManager( 1031): Killing 6582:com.lge.email/u0a23 (adj 15): empty #18
,W/libprocessgroup( 1031): failed to open /acct/uid_1000/pid_5189/cgroup.procs: No such file or directory
,W/libprocessgroup( 1031): failed to open /acct/uid_10023/pid_6582/cgroup.procs: No such file or directory
I/ThermalEngine(  344): Thermal-Server: Thermal received msg from  override
,I/Thermal-Lib( 3112): Thermal-Lib-Client: Client request sent
I/GAV2    ( 7046): Thread[GAThread,5,main]: No campaign data found.
,V/GLSActivity( 2134): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2134): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.docs, service: oauth2: https://www.googleapis.com/auth/drive
I/GLSUser ( 2134): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2134): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2134): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2134): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
,D/LgeQuickCoverOverlayWindow( 1410): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1410): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1410): [native noti] inex =  2
,D/LgeQuickCoverNotificationData( 1410): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1410): updateNotificationData: count=3
W/GLSActivity( 2134): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2134): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2134): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2134): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2134): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2134): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2134): 	at android.os.Binder.execTransact(Binder.java:446)
W/PsynchoHelperImpl( 7046): Error fetching or saving configuration
W/PsynchoHelperImpl( 7046): java.io.IOException: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
W/PsynchoHelperImpl( 7046): 	at Op.a(ApiaryPsynchoConfigurationAccessor.java:145)
W/PsynchoHelperImpl( 7046): 	at Op.a(ApiaryPsynchoConfigurationAccessor.java:215)
W/PsynchoHelperImpl( 7046): 	at OQ.a(PsynchoHelperImpl.java:60)
W/PsynchoHelperImpl( 7046): 	at agr.a(DriveSpecificSyncManager.java:27)
W/PsynchoHelperImpl( 7046): 	at agO.a(LegacySyncManager.java:678)
W/PsynchoHelperImpl( 7046): 	at agO.b(LegacySyncManager.java:582)
W/PsynchoHelperImpl( 7046): 	at agO.a(LegacySyncManager.java:467)
W/PsynchoHelperImpl( 7046): 	at agO.a(LegacySyncManager.java:97)
W/PsynchoHelperImpl( 7046): 	at agQ.run(LegacySyncManager.java:419)
W/PsynchoHelperImpl( 7046): 	at ami.a(NetworkUtilitiesImpl.java:31)
W/PsynchoHelperImpl( 7046): 	at agP.run(LegacySyncManager.java:416)
W/PsynchoHelperImpl( 7046): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
W/PsynchoHelperImpl( 7046): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
W/PsynchoHelperImpl( 7046): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
W/PsynchoHelperImpl( 7046): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
W/PsynchoHelperImpl( 7046): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
W/PsynchoHelperImpl( 7046): 	at android.os.Binder.execTransact(Binder.java:446)
D/QuickStatusbarLayout( 1410): Notification difference=198
D/QuickStatusbarLayout( 1410): child = android.widget.LinearLayout{2a8c721b V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,V/GLSActivity( 2134): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2134): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.docs, service: writely
,I/GLSUser ( 2134): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> writely without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2134): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2134): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2134): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,D/LgeQuickCoverNLService( 1410): onNotificationPosted
D/SmartCoverUpdateMonitor( 1410): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1410): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1410): handleNotificationPosted(true)
D/QuickCircle( 1410): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1410): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1410): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
,D/LgeQuickCoverNotificationData( 1410): post do just update job
D/LgeQuickCoverNotificationData( 1410): showAll3
D/LgeQuickCoverNotificationData( 1410): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1410): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1410): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1410): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1410): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1410): isNotificationForCurrentUser : true
W/GLSActivity( 2134): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2134): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2134): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2134): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2134): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2134): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2134): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverOverlayWindow( 1410): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1410): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1410): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1410): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1410): updateNotificationData: count=3
E/HttpIssuerBase( 7046): Attempt to consume entity of HttpIssuer when no request is executing.
E/HttpIssuerBase( 7046): Attempt to close HttpIssuer when no request is executing.
E/HttpIssuerBase( 7046): java.io.IOException
E/HttpIssuerBase( 7046): 	at TG.b(HttpIssuerBase.java:188)
E/HttpIssuerBase( 7046): 	at Tj.b(DefaultAuthenticatedHttpIssuer.java:151)
E/HttpIssuerBase( 7046): 	at afE.a(AccountMetadataUpdater.java:227)
E/HttpIssuerBase( 7046): 	at afE.a(AccountMetadataUpdater.java:140)
E/HttpIssuerBase( 7046): 	at agO.a(LegacySyncManager.java:828)
E/HttpIssuerBase( 7046): 	at agO.b(LegacySyncManager.java:588)
E/HttpIssuerBase( 7046): 	at agO.a(LegacySyncManager.java:467)
E/HttpIssuerBase( 7046): 	at agO.a(LegacySyncManager.java:97)
E/HttpIssuerBase( 7046): 	at agQ.run(LegacySyncManager.java:419)
E/HttpIssuerBase( 7046): 	at ami.a(NetworkUtilitiesImpl.java:31)
E/HttpIssuerBase( 7046): 	at agP.run(LegacySyncManager.java:416)
E/SyncManager( 7046): AuthenticatorException
E/SyncManager( 7046): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/SyncManager( 7046): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/SyncManager( 7046): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/SyncManager( 7046): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/SyncManager( 7046): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/SyncManager( 7046): 	at android.os.Binder.execTransact(Binder.java:446)
W/GAV2    ( 7046): SyncManager-thalitester@gmail.com: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
D/WifiService( 1031): releaseWifiLockLocked: WifiLock{SyncManager type=1 binder=android.os.BinderProxy@307cdf2d}
,D/QuickStatusbarLayout( 1410): Notification difference=198
,D/QuickStatusbarLayout( 1410): child = android.widget.LinearLayout{2a8c721b V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/SyncManager( 1031): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.docs, PERIODIC, currentRunTime 40058, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager( 1031): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.apps.docs, PERIODIC, currentRunTime 166393, reason: Periodic
I/ActivityManager( 1031): Killing 6834:com.qualcomm.timeservice/1000 (adj 15): empty #17
,W/libprocessgroup( 1031): failed to open /acct/uid_1000/pid_6834/cgroup.procs: No such file or directory
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=15.3, 0.0, 0.0  rx=13.1 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-880336736] gl rssi=-60 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=15.3, 0.0, 0.0  rx=13.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-880336733] gl rssi=-60 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 137791890160; DSPS: 4656002; Offset : -4313270197
,I/ActivityManager( 1031): Killing 6853:com.android.calendar/u0a13 (adj 15): empty #17
,W/libprocessgroup( 1031): failed to open /acct/uid_10013/pid_6853/cgroup.procs: No such file or directory
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=12.6, 0.0, 0.0  rx=11.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-880333709] gl rssi=-60 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=12.6, 0.0, 0.0  rx=11.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-880333705] gl rssi=-60 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1459): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1459): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1459): called onTimeUpdated()
I/[SystemUI]Clock( 1459): called onTimeUpdated()
I/LgeClockWidgetControlView( 1459): called onTimeUpdated()
I/[SystemUI]DateView( 1459): called onTimeUpdated()
I/[SystemUI]DateView( 1459): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1459): handleTimeUpdate
,I/[SystemUI]TimeTickManager( 1459): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1459): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1459): called onTimeUpdated()
I/[SystemUI]Clock( 1459): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1459): called onTimeUpdated()
I/[SystemUI]DateView( 1459): called onTimeUpdated()
I/[SystemUI]DateView( 1459): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1459): handleTimeUpdate
I/InputReader( 1031): Reconfiguring input devices.  changes=0x00000010
,I/[SystemUI]QPairHandler( 1459): onReceive = android.intent.action.PACKAGE_CHANGED
D/SplitUIService( 1883): replaced split : contains_com.google.android.talk / true
,D/SplitUIManager( 1883): split_name #11 / not available #0
I/SplitUIService( 1883): split app #11
,I/[LGHome]EVENT( 2082): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000010 (has extras) }
,I/ActivityManager( 1031): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7336 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/InputReader( 1031): Reconfiguring input devices.  changes=0x00000010
,I/[SystemUI]QSlideListController( 1459): onReceive = android.intent.action.PACKAGE_CHANGED
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1459): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.talk
,I/[SystemUI]QPairHandler( 1459): onReceive = android.intent.action.PACKAGE_CHANGED
I/[SystemUI]QSlideListController( 1459): onReceive = android.intent.action.PACKAGE_CHANGED
,I/[LGHome]EVENT( 2082): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.videos flg=0x4000010 (has extras) }
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1459): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.videos
D/administrator( 1031): Handling package changes for user 0
,W/ResourcesManager( 2082): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/AppUp4:AppBoxCP( 7336): onCreate
W/AppUp4:DB( 7336):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7336):  setFingerPrint start
I/AppUp4:DB( 7336):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 7336):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7336):  SDK version = 21
I/AppUp4:DB( 7336):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7336): AppBoxApplication onCreate()
,I/AppUp4:CustModeStarterReceiver( 7336): onReceive
,I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,D/LgDataFeature( 7336): LgDataFeature() Constructor: none
D/LgDataFeature( 7336): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7336): Context : android.app.ReceiverRestrictedContext@399d6ea4
D/AppUp4:CustFacade( 7336): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7336): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7336): begin check event
I/AppUp4:CustModeStarterReceiver( 7336): Event For Nothing, skip.
I/NotificationService( 1031): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService( 1031): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000010 (has extras) }
,W/ResourcesManager( 1031): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager( 1031): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7374 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/ActivityManager( 1031): Killing 6892:com.android.providers.calendar/u0a14 (adj 15): empty #17
,I/art     (  355): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 306us total 13.955ms
I/art     (  355): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 251us total 12.334ms
,I/art     (  355): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 226us total 11.534ms
,W/ResourcesManager( 1031): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourceType( 1031): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,W/libprocessgroup( 1031): failed to open /acct/uid_10014/pid_6892/cgroup.procs: No such file or directory
,D/administrator( 1031): Handling package changes for user 0
,W/ResourcesManager( 7374): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7374): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7374): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7374): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7374): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourceType( 1031): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/NotificationService( 1031): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService( 1031): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.videos flg=0x4000010 (has extras) }
,I/[LGHome]EVENT( 2082): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/SystemConfig( 7374): BUILD Country: EU
I/SystemConfig( 7374): BUILD Operator: OPEN
,I/ActivityManager( 1031): Killing 6810:com.lge.clock/u0a10 (adj 15): empty #17
,W/libprocessgroup( 1031): failed to open /acct/uid_10010/pid_6810/cgroup.procs: No such file or directory
,I/SystemConfig( 7374): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7374): existFile = false
I/SystemConfig( 7374): canReadFile = false
I/SystemConfig( 7374): systemFeature RCS result false
D/SystemConfig( 7374): refreshRcsSupport() :false
I/ActivityManager( 1031): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7397 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/ResourcesManager( 7397): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7397): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7397): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 7397): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,I/AppConfig( 7397): Total System Memory = 2995761152
,D/SystemHelper( 7397): region [EU], country [EU], operator [OPEN], sub-operator []
I/ActivityManager( 1031): Killing 6688:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,W/libprocessgroup( 1031): failed to open /acct/uid_10085/pid_6688/cgroup.procs: No such file or directory
,I/UpdateIcingCorporaServi( 4252): Updating corpora: APPS=com.google.android.talk, CONTACTS=MAYBE
V/SIM_STK ( 1031): Menu title from STK is T-Mobile
I/ActivityManager( 1031): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7420 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 4252): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 4252): UpdateCorporaTask done [took 85 ms] updated apps [took 85 ms] 
,I/LockScreenSettings( 7420): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7420): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7420): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7420): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
,D/LockScreenSettings( 7420): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7420): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
D/LockScreenSettings( 7420): Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
I/ActivityManager( 1031): Killing 6872:com.google.android.syncadapters.calendar/u0a69 (adj 15): empty #17
,D/PackageBroadcastService( 2367): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.talk
W/libprocessgroup( 1031): failed to open /acct/uid_10069/pid_6872/cgroup.procs: No such file or directory
,I/PeopleContactsSync( 2367): CP2 sync disabled
,I/AppUp4:CustModeStarterReceiver( 7336): onReceive
D/AppUp4:CustFacade( 7336): Context : android.app.ReceiverRestrictedContext@399d6ea4
D/AppUp4:CustFacade( 7336): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7336): isPhone : true
,D/AppUp4:CustModeStarterReceiver( 7336): begin check event
,I/AppUp4:CustModeStarterReceiver( 7336): Event For Nothing, skip.
I/UpdateIcingCorporaServi( 4252): Updating corpora: APPS=com.google.android.videos, CONTACTS=MAYBE
,D/LockScreenSettings( 7420): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,D/LockScreenSettings( 7420): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7420): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7420): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7420): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
D/LockScreenSettings( 7420): Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
D/PackageBroadcastService( 2367): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.videos
,I/PeopleContactsSync( 2367): CP2 sync disabled
,V/SIM_STK ( 1031): Menu title from STK is T-Mobile
I/UpdateIcingCorporaServi( 4252): UpdateCorporaTask done [took 141 ms] updated apps [took 141 ms] 
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=6.3, 0.0, 0.0  rx=5.5 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-880330678] gl rssi=-60 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=6.3, 0.0, 0.0  rx=5.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-880330675] gl rssi=-60 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=3.7, 0.0, 0.0  rx=3.3 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-880327650] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=3.7, 0.0, 0.0  rx=3.3 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-880327646] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=1.8, 0.0, 0.0  rx=1.6 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-880324623] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=1.8, 0.0, 0.0  rx=1.6 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-880324613] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-880321594] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-880321591] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/PowerManagerServiceEx( 1031): acquireWakeLockInternal: lock=977884044, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1031
,V/AlarmManager( 1031): RTC_WAKEUP set : Alarm{1b48f2fe type 0 when 1455113593768 com.android.vending} when 1455113593768
,D/[Concierge]Service( 2587): onStartCommand(). Type : 9
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-880318561] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-880318557] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,V/AlarmManager( 1031): ELAPSED_WAKEUP set : Alarm{68d0a5f type 2 when 154732 android} when 154732
,D/PowerManagerServiceEx( 1031): releaseWakeLockInternal: lock=977884044 [*alarm*], flags=0x0
,V/SIM_STK ( 1031): Menu title from STK is T-Mobile
,V/GLSActivity( 2134): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2134): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2134): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2134): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2134): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2134): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 7195): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7195): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 7195): [1] 5.onFinished: Scheduling replication attempt 3.
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-880315538] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-880315535] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 157793453070; DSPS: 5311413; Offset : -4313263864
,E/WifiStateMachine( 1031):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1031):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,E/WifiStateMachine( 1031):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1031):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1031):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-880312515] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:-880312515] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-880309497] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-880309494] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-880306469] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-880306466] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-880303446] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-880303443] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-880300416] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-880300413] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-880297394] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-880297391] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,V/AlarmManager( 1031): RTC_WAKEUP set : Alarm{8dbb49d type 0 when 1455113615217 com.android.vending} when 1455113615217
,V/SIM_STK ( 1031): Menu title from STK is T-Mobile
,I/art     ( 1031): Explicit concurrent mark sweep GC freed 45467(2MB) AllocSpace objects, 2(288KB) LOS objects, 33% free, 44MB/66MB, paused 1.979ms total 154.362ms
,V/GLSActivity( 2134): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2134): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2134): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2134): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2134): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2134): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7195): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7195): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7195): [1] 5.onFinished: Scheduling replication attempt 4.
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 177795531395; DSPS: 5966841; Offset : -4313260527
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-880294363] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:8] from screen [on:0 period:-880294355] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-880291334] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-880291331] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-880288311] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-880288299] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,V/AlarmManager( 1031): ELAPSED_WAKEUP set : Alarm{15175c37 type 2 when 185318 android} when 185318
,I/BooksSync( 6538): Starting books sync
,D/BooksSync( 6538): started syncMyEbooks
,V/GLSActivity( 2134): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2134): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 2134): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2134): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2134): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2134): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1410): onNotificationPosted
D/SmartCoverUpdateMonitor( 1410): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1410): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1410): handleNotificationPosted(true)
D/QuickCircle( 1410): onNotificationPosted() : isPosted true
,D/LgeQuickCoverNotificationData( 1410): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1410): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1410): post do just update job
D/LgeQuickCoverNotificationData( 1410): showAll3
D/LgeQuickCoverNotificationData( 1410): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1410): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1410): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1410): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1410): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1410): isNotificationForCurrentUser : true
W/GLSActivity( 2134): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2134): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2134): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2134): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2134): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2134): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2134): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverOverlayWindow( 1410): [native noti] inex =  1
D/ContactsSyncAdapter( 2134): innerSync failed
D/ContactsSyncAdapter( 2134): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2134): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2134): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2134): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2134): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2134): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2134): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2134): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2134): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2134): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2134): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2134): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNotificationData( 1410): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1410): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1410): isNotificationForCurrentUser : true
,E/LgeQuickCoverOverlayWindow( 1410): updateNotificationData: count=3
D/QuickStatusbarLayout( 1410): Notification difference=198
D/QuickStatusbarLayout( 1410): child = android.widget.LinearLayout{2a8c721b V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/SyncManager( 1031): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 156597, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager( 1031): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 247664, reason: 10019
I/GLSUser ( 2134): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2134): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2134): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2134): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2134): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2134): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2134): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2134): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2134): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2134): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2134): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2134): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6538): Authentication error
E/BooksAccountManager( 6538): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6538): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6538): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6538): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6538): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6538): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6538): null auth token
W/ResourcesManager( 1410): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 1410): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
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
W/ResourcesManager( 1410): Asset path '/system/framework/com.lge.systemui.jar' does not exist or contains no resources.
W/ResourcesManager( 1410): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/LgeQuickCoverOverlayWindow( 1410): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1410): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1410): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1410): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1410): updateNotificationData: count=3
D/QuickStatusbarLayout( 1410): Notification difference=198
D/QuickStatusbarLayout( 1410): child = android.widget.LinearLayout{2a8c721b V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6538): Error response from books API: {
W/ApiaryClient( 6538):  "error": {
W/ApiaryClient( 6538):   "errors": [
W/ApiaryClient( 6538):    {
W/ApiaryClient( 6538):     "domain": "global",
W/ApiaryClient( 6538):     "reason": "required",
W/ApiaryClient( 6538):     "message": "Login Required",
W/ApiaryClient( 6538):     "locationType": "header",
W/ApiaryClient( 6538):     "location": "Authorization"
W/ApiaryClient( 6538):    }
W/ApiaryClient( 6538):   ],
W/ApiaryClient( 6538):   "code": 401,
W/ApiaryClient( 6538):   "message": "Login Required"
W/ApiaryClient( 6538):  }
W/ApiaryClient( 6538): }
,W/ApiaryClient( 6538): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6538): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=8620698161093814615&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6538): Headers:
W/ApiaryClient( 6538): accept-encoding: [gzip]
W/ApiaryClient( 6538): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6538): gdata-version: 2
,V/GLSActivity( 2134): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2134): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2134): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2134): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2134): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2134): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
,W/GLSActivity( 2134): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2134): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2134): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2134): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2134): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2134): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2134): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6538): Authentication error
E/BooksAccountManager( 6538): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6538): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6538): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6538): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6538): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6538): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6538): null auth token
D/QuickStatusbarLayout( 1410): Notification difference=198
D/QuickStatusbarLayout( 1410): child = android.widget.LinearLayout{2a8c721b V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6538): Error response from books API: {
W/ApiaryClient( 6538):  "error": {
W/ApiaryClient( 6538):   "errors": [
W/ApiaryClient( 6538):    {
W/ApiaryClient( 6538):     "domain": "global",
W/ApiaryClient( 6538):     "reason": "required",
W/ApiaryClient( 6538):     "message": "Login Required",
W/ApiaryClient( 6538):     "locationType": "header",
W/ApiaryClient( 6538):     "location": "Authorization"
W/ApiaryClient( 6538):    }
W/ApiaryClient( 6538):   ],
W/ApiaryClient( 6538):   "code": 401,
W/ApiaryClient( 6538):   "message": "Login Required"
W/ApiaryClient( 6538):  }
W/ApiaryClient( 6538): }
,W/ApiaryClient( 6538): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6538): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=8620698161093814615&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6538): Headers:
W/ApiaryClient( 6538): accept-encoding: [gzip]
W/ApiaryClient( 6538): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6538): gdata-version: 2
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-880285282] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,V/GLSActivity( 2134): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:28] from screen [on:0 period:-880285254] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,I/GLSUser ( 2134): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2134): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2134): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2134): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2134): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/GLSActivity( 2134): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2134): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2134): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2134): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2134): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2134): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2134): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6538): Authentication error
E/BooksAccountManager( 6538): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6538): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6538): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6538): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6538): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6538): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6538): null auth token
D/QuickStatusbarLayout( 1410): Notification difference=198
D/QuickStatusbarLayout( 1410): child = android.widget.LinearLayout{2a8c721b V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6538): Error response from books API: {
W/ApiaryClient( 6538):  "error": {
W/ApiaryClient( 6538):   "errors": [
W/ApiaryClient( 6538):    {
W/ApiaryClient( 6538):     "domain": "global",
W/ApiaryClient( 6538):     "reason": "required",
W/ApiaryClient( 6538):     "message": "Login Required",
W/ApiaryClient( 6538):     "locationType": "header",
W/ApiaryClient( 6538):     "location": "Authorization"
W/ApiaryClient( 6538):    }
W/ApiaryClient( 6538):   ],
W/ApiaryClient( 6538):   "code": 401,
W/ApiaryClient( 6538):   "message": "Login Required"
W/ApiaryClient( 6538):  }
W/ApiaryClient( 6538): }
,W/ApiaryClient( 6538): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6538): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=8620698161093814615&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6538): Headers:
W/ApiaryClient( 6538): accept-encoding: [gzip]
W/ApiaryClient( 6538): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6538): gdata-version: 2
,E/BooksSync( 6538): Soft error: 
E/BooksSync( 6538): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6538): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=8620698161093814615&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6538): Headers:
E/BooksSync( 6538): accept-encoding: [gzip]
E/BooksSync( 6538): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6538): gdata-version: 2
E/BooksSync( 6538): 
E/BooksSync( 6538): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6538): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6538): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6538): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6538): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6538): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6538): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6538): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6538): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6538): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6538): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6538): {
E/BooksSync( 6538):  "error": {
E/BooksSync( 6538):   "errors": [
E/BooksSync( 6538):    {
E/BooksSync( 6538):     "domain": "global",
E/BooksSync( 6538):     "reason": "required",
E/BooksSync( 6538):     "message": "Login Required",
E/BooksSync( 6538):     "locationType": "header",
E/BooksSync( 6538):     "location": "Authorization"
E/BooksSync( 6538):    }
E/BooksSync( 6538):   ],
E/BooksSync( 6538):   "code": 401,
E/BooksSync( 6538):   "message": "Login Required"
E/BooksSync( 6538):  }
E/BooksSync( 6538): }
E/BooksSync( 6538): 
E/BooksSync( 6538): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6538): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6538): 	... 8 more
,E/BooksSync( 6538): Sync error
E/BooksSync( 6538): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6538): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=8620698161093814615&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6538): Headers:
E/BooksSync( 6538): accept-encoding: [gzip]
E/BooksSync( 6538): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6538): gdata-version: 2
E/BooksSync( 6538): 
E/BooksSync( 6538): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6538): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6538): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6538): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6538): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6538): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6538): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6538): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6538): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6538): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6538): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6538): {
E/BooksSync( 6538):  "error": {
E/BooksSync( 6538):   "errors": [
E/BooksSync( 6538):    {
E/BooksSync( 6538):     "domain": "global",
E/BooksSync( 6538):     "reason": "required",
E/BooksSync( 6538):     "message": "Login Required",
E/BooksSync( 6538):     "locationType": "header",
E/BooksSync( 6538):     "location": "Authorization"
E/BooksSync( 6538):    }
E/BooksSync( 6538):   ],
E/BooksSync( 6538):   "code": 401,
E/BooksSync( 6538):   "message": "Login Required"
E/BooksSync( 6538):  }
E/BooksSync( 6538): }
E/BooksSync( 6538): 
E/BooksSync( 6538): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6538): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6538): 	... 8 more
I/BooksSync( 6538): Finished books sync
D/SyncManager( 1031): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 159386, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=2.7, 0.0, 0.0  rx=2.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-880282233] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=2.7, 0.0, 0.0  rx=2.7 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-880282222] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=2.4, 0.0, 0.0  rx=2.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-880279205] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=2.4, 0.0, 0.0  rx=2.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-880279202] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=1.7, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-880276175] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=1.7, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-880276172] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 197797385919; DSPS: 6622262; Offset : -4313267653
,V/AlarmManager( 1031): RTC_WAKEUP set : Alarm{1132a7ff type 0 when 1455113636566 com.android.vending} when 1455113636566
,V/SIM_STK ( 1031): Menu title from STK is T-Mobile
,V/GLSActivity( 2134): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2134): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2134): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2134): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2134): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2134): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7195): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 7195): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 7195): [1] 5.onFinished: Scheduling replication attempt 5.
I/[SystemUI]TimeTickManager( 1459): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1459): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1459): called onTimeUpdated()
,I/[SystemUI]Clock( 1459): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1459): called onTimeUpdated()
,I/[SystemUI]DateView( 1459): called onTimeUpdated()
I/[SystemUI]DateView( 1459): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1459): handleTimeUpdate
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=1.3, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-880273154] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=1.3, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-880273152] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-880270131] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-880270121] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-880267102] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-880267091] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-880264068] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-880264065] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-880261038] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-880261035] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-880258015] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-880258012] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/PowerManagerServiceEx( 1031): acquireWakeLockInternal: lock=977884044, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1031
,V/AlarmManager( 1031): ELAPSED_WAKEUP set : Alarm{3fc2dcc9 type 2 when 215378 android} when 215378
D/[Concierge]Service( 2587): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1031): releaseWakeLockInternal: lock=977884044 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 217799482629; DSPS: 7277690; Offset : -4313246138
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-880254987] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-880254984] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-880251962] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-880251952] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-880248931] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-880248919] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-880245896] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-880245893] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-880242873] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-880242864] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
V/AlarmManager( 1031): ELAPSED_WAKEUP set : Alarm{11b36fce type 2 when 210456 android} when 210456
,V/AlarmManager( 1031): RTC_WAKEUP set : Alarm{2412ddfc type 0 when 1455113659676 com.android.vending} when 1455113659676
,V/SIM_STK ( 1031): Menu title from STK is T-Mobile
,V/GLSActivity( 2134): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 2134): Explicit concurrent mark sweep GC freed 34448(2MB) AllocSpace objects, 15(2MB) LOS objects, 50% free, 30MB/62MB, paused 1.865ms total 66.962ms
,I/GLSUser ( 2134): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2134): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2134): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2134): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2134): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7195): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7195): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7195): [1] 5.onFinished: Giving up after 6 failures.
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-880239844] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-880239840] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-880236807] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-880236804] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 237802015226; DSPS: 7933133; Offset : -4313246526
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-880233777] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-880233774] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-880230747] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-880230744] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-880227726] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-880227723] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-880224697] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-880224694] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,V/AlarmManager( 1031): ELAPSED_WAKEUP set : Alarm{1dc1687e type 2 when 249914 android} when 249914
,I/BooksSync( 6538): Starting books sync
,D/BooksSync( 6538): started syncMyEbooks
,V/GLSActivity( 2134): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2134): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2134): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2134): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2134): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2134): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/GLSActivity( 2134): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2134): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2134): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2134): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2134): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2134): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2134): 	at android.os.Binder.execTransact(Binder.java:446)
,D/QuickStatusbarLayout( 1410): Notification difference=198
D/QuickStatusbarLayout( 1410): child = android.widget.LinearLayout{2a8c721b V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
E/BooksAccountManager( 6538): Authentication error
E/BooksAccountManager( 6538): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6538): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6538): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6538): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6538): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6538): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6538): null auth token
,W/ApiaryClient( 6538): Error response from books API: {
W/ApiaryClient( 6538):  "error": {
W/ApiaryClient( 6538):   "errors": [
W/ApiaryClient( 6538):    {
W/ApiaryClient( 6538):     "domain": "global",
W/ApiaryClient( 6538):     "reason": "required",
W/ApiaryClient( 6538):     "message": "Login Required",
W/ApiaryClient( 6538):     "locationType": "header",
W/ApiaryClient( 6538):     "location": "Authorization"
W/ApiaryClient( 6538):    }
W/ApiaryClient( 6538):   ],
W/ApiaryClient( 6538):   "code": 401,
W/ApiaryClient( 6538):   "message": "Login Required"
W/ApiaryClient( 6538):  }
W/ApiaryClient( 6538): }
,W/ApiaryClient( 6538): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6538): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2015382318891851387&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6538): Headers:
W/ApiaryClient( 6538): accept-encoding: [gzip]
W/ApiaryClient( 6538): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6538): gdata-version: 2
,V/GLSActivity( 2134): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2134): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2134): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2134): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2134): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2134): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/WifiStateMachine( 1031):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-880221672] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-880221671] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1031): doString: [SIGNAL_POLL]
,V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
,E/LgeQuickCoverOverlayWindow( 1410): updateNotificationData: count=3
W/GLSActivity( 2134): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2134): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2134): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2134): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2134): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2134): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2134): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6538): Authentication error
E/BooksAccountManager( 6538): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6538): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6538): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6538): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6538): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6538): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6538): null auth token
,D/QuickStatusbarLayout( 1410): Notification difference=198
,D/QuickStatusbarLayout( 1410): child = android.widget.LinearLayout{2a8c721b V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6538): Error response from books API: {
W/ApiaryClient( 6538):  "error": {
W/ApiaryClient( 6538):   "errors": [
W/ApiaryClient( 6538):    {
W/ApiaryClient( 6538):     "domain": "global",
W/ApiaryClient( 6538):     "reason": "required",
W/ApiaryClient( 6538):     "message": "Login Required",
W/ApiaryClient( 6538):     "locationType": "header",
W/ApiaryClient( 6538):     "location": "Authorization"
W/ApiaryClient( 6538):    }
W/ApiaryClient( 6538):   ],
W/ApiaryClient( 6538):   "code": 401,
W/ApiaryClient( 6538):   "message": "Login Required"
W/ApiaryClient( 6538):  }
W/ApiaryClient( 6538): }
,W/ApiaryClient( 6538): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6538): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2015382318891851387&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6538): Headers:
W/ApiaryClient( 6538): accept-encoding: [gzip]
W/ApiaryClient( 6538): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6538): gdata-version: 2
,I/jxcore-log( 6063): --= Surplus to requirements =--
I/jxcore-log( 6063): 
,I/jxcore-log( 6063): ****TEST TOOK:  ms ****
I/jxcore-log( 6063): 
I/jxcore-log( 6063): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6063): 
,V/GLSActivity( 2134): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2134): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2134): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2134): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2134): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2134): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/AndroidRuntime( 7595): 
D/AndroidRuntime( 7595): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7595): CheckJNI is OFF
,I/art     ( 1031): Explicit concurrent mark sweep GC freed 49230(2MB) AllocSpace objects, 7(880KB) LOS objects, 33% free, 44MB/66MB, paused 1.945ms total 142.729ms
,V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1410): onNotificationPosted
W/GLSActivity( 2134): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2134): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2134): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2134): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2134): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2134): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2134): 	at android.os.Binder.execTransact(Binder.java:446)
D/SmartCoverUpdateMonitor( 1410): received broadcast com.lge.intent.action.NLDataPosted
E/BooksAccountManager( 6538): Authentication error
E/BooksAccountManager( 6538): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6538): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6538): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6538): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6538): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6538): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6538): null auth token
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
,D/LgeQuickCoverNotificationData( 1410): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1410): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1410): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1410): updateNotificationData: count=3
D/QuickStatusbarLayout( 1410): Notification difference=198
,D/QuickStatusbarLayout( 1410): child = android.widget.LinearLayout{2a8c721b V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/AndroidRuntime( 7595): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1031): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
I/ActivityManager( 1031): Killing 6063:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
,W/ApiaryClient( 6538): Error response from books API: {
W/ApiaryClient( 6538):  "error": {
W/ApiaryClient( 6538):   "errors": [
W/ApiaryClient( 6538):    {
W/ApiaryClient( 6538):     "domain": "global",
W/ApiaryClient( 6538):     "reason": "required",
W/ApiaryClient( 6538):     "message": "Login Required",
W/ApiaryClient( 6538):     "locationType": "header",
W/ApiaryClient( 6538):     "location": "Authorization"
W/ApiaryClient( 6538):    }
W/ApiaryClient( 6538):   ],
W/ApiaryClient( 6538):   "code": 401,
W/ApiaryClient( 6538):   "message": "Login Required"
W/ApiaryClient( 6538):  }
W/ApiaryClient( 6538): }
,W/ApiaryClient( 6538): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6538): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2015382318891851387&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6538): Headers:
W/ApiaryClient( 6538): accept-encoding: [gzip]
W/ApiaryClient( 6538): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6538): gdata-version: 2
,W/PackageSettings( 1031): Skipping PackageSetting{2e79d288 com.example.hello/10319} due to missing metadata
,I/WindowState( 1031): WIN DEATH: Window{16d1bc7e u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService( 1031): Client connection lost with reason: 4
,D/InputDispatcher( 1031): Window went away: Window{16d1bc7e u0 com.test.thalitest/com.test.thalitest.MainActivity}
,E/libprocessgroup( 1031): failed to kill 1 processes for processgroup 6063
,I/ActivityManager( 1031):   Force finishing activity ActivityRecord{2945c91b u0 com.test.thalitest/.MainActivity t4}
,E/GBMv2   (  350): DFP En is all cleared set to be enabled
,W/ActivityManager( 1031): Spurious death for ProcessRecord{abfd724 6063:com.test.thalitest/u0a311}, curProc for 6063: null
I/ActivityManager( 1031): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
I/ActivityManager( 1031):   Force finishing activity ActivityRecord{2945c91b u0 com.test.thalitest/.MainActivity t4 f}
W/ActivityManager( 1031): Duplicate finish request for ActivityRecord{2945c91b u0 com.test.thalitest/.MainActivity t4 f}
,I/[LGHome]EVENT( 2082): [Launcher.java:5338:onStart()]onStart
D/SplitWindowPolicy( 1961): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1961): topRunningActivity=ActivityInfo{1e112ede co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
,I/[LGHome]EVENT( 2082): [Launcher.java:903:onResume()]onResume
D/SplitWindowPolicy( 1961): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1961): topRunningActivity=ActivityInfo{274cc8bf co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[LGHome]EVENT( 2082): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 2082): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/KeyguardModel( 1459): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
D/LIA_Service_RemotePackageHandler( 2038): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
D/LIA_MrGDBLogger_PackageInfoDetector( 2694): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
,E/LGBluetoothAvrcpQcomAdapter( 6117): [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
D/LGBluetoothAvrcpQcomAdapter( 6117): [BTUI] [+] updateMediaPlayerInfo
W/GeofencerStateMachine( 1831): Ignoring removeGeofence because network location is disabled.
,W/System.err( 4205): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 4205): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4205): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4205): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4205): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4205): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4205): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4205): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4205): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4205): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4205): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4205): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,I/art     ( 4252): Explicit concurrent mark sweep GC freed 28658(1641KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 29MB/45MB, paused 634us total 76.962ms
V/SIM_STK ( 1031): Menu title from STK is T-Mobile
,I/InputReader( 1031): Reconfiguring input devices.  changes=0x00000010
,D/administrator( 1031): Handling package changes for user 0
,I/ActivityManager( 1031): Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=7635 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,D/ActionManagerService( 1917): notifyUserLog: 1000003
I/[LGHome]GBoardWebView( 2082): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
D/LIA_Informant_ActionManagerMessageHandler( 2694): handleMessage: what(1000) actionID(0x1000003)
I/[LGHome]LGActivityUtil( 2082): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 2082): [Launcher.java:1056:onResume()]onResume end
I/[SystemUI]QSlideListController( 1459): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]EVENT( 2082): [Launcher.java:1114:onPause()]onPause
I/[LGHome]GBoardWebView( 2082): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
,D/ActionManagerService( 1917): notifyUserLog: 1000004
,D/LIA_Informant_ActionManagerMessageHandler( 2694): handleMessage: what(1000) actionID(0x1000004)
,V/BoardContentProvider( 2694): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
I/GBoardWebViewUtils( 2082): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
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
I/GBoardWebViewUtils( 2082): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1454599632914
I/GBoardWebViewUtils( 2082): , create_time: 1454599633839
I/GBoardWebViewUtils( 2082): , expire_time: 0
I/GBoardWebViewUtils( 2082): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide.html?id=guide_1111111111116_1454599632914&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2082): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2082): , display: false
I/GBoardWebViewUtils( 2082): , animation: false }
D/KeyguardModel( 1459): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1459): createShortcutInfo...
D/WallpaperManager( 2082): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
,D/KeyguardModel( 1459): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1459): createShortcutInfo...
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1459): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1459): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
W/ResourcesManager( 1459): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1459): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1459): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1459): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1459): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1459): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/SplitUIManager( 1883): split_name #11 / not available #0
D/SplitUIService( 1883): removed split : 
D/KeyguardModel( 1459): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1459): createShortcutInfo...
,I/[LGHome]EVENT( 2082): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]GBoardWebView( 2082): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
W/ResourcesManager( 1459): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1459): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1459): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1459): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1459): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
,D/KeyguardModel( 1459): createShortcutInfo...
V/SIM_STK ( 1031): Menu title from STK is T-Mobile
V/SIM_STK ( 1031): Menu title from STK is T-Mobile
W/ResourcesManager( 1459): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 1459): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1459): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1459): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1459): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1459): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1459): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1459): createShortcutInfo...
D/SplitUIManager( 1883): split_name #11 / not available #0
I/SplitUIService( 1883): split app #11
D/KeyguardModel( 1459): handleShortcutListChanged...
D/KeyguardModel( 1459): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1459): createShortcutInfo...
D/KeyguardModel( 1459): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1459): createShortcutInfo...
W/ResourceType( 1459): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1459): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1459): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1459): createShortcutInfo...
W/ResourceType( 1459): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1459): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1459): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1459): createShortcutInfo...
W/ResourceType( 1459): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1459): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,D/KeyguardModel( 1459): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1459): createShortcutInfo...
V/SIM_STK ( 1031): Menu title from STK is T-Mobile
,D/KeyguardModel( 1459): handleShortcutListChanged...
W/ActivityManager( 1031): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
D/LGBluetoothAvrcpQcomAdapter( 6117): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 6117): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6117): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 6117): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 6117): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 6117): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6117): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 6117): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6117): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 6117): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6117): [BTUI] [-] updateMediaPlayerInfo
,I/[LGHome]EVENT( 2082): [Launcher.java:5349:onStop()]onStop
W/ResourcesManager( 7635): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
I/NotificationService( 1031): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1031): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService( 1031): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister( 1031): removeObsoleteFile: deleting file=4_task.xml
I/art     ( 1031): Explicit concurrent mark sweep GC freed 13933(1063KB) AllocSpace objects, 3(176KB) LOS objects, 33% free, 44MB/67MB, paused 1.972ms total 308.586ms
,I/[LGHome]Launcher.Model( 2082): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
D/AndroidRuntime( 7595): Shutting down VM
,D/PluginManager( 7635): init()
I/Timeline( 1031): Timeline: Activity_windows_visible id: ActivityRecord{35f6d8c7 u0 com.lge.launcher2/.Launcher t3} time:253904
I/[LGHome]Launcher.Model( 2082): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2082): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2082): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 2082): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[Concierge]WidgetView( 2082): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
,D/[Concierge]Service( 2587): onStartCommand(). Type : 8
D/[Concierge]Service( 2587): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/[Concierge]Service( 2587): Update widget ID : 11
D/[Concierge]WidgetView( 2082): change position of spinner
I/[Concierge]WidgetView( 2082): initWebView(). Time : 1455113694025
D/[Concierge]Service( 2587): onStartCommand(). Type : 0
,I/[Concierge]WebView( 2082): Return exist ConciergeWebView. Reuse : 795980196
D/[Concierge]WidgetView( 2082): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2082): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
I/[LgeWidgetLib]ExtViewHost( 2082): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@1098ea8a
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
,W/ResourcesManager( 1031): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/[LGHome]Launcher.Model( 2082): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
W/ResourceType( 1031): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/[Concierge]WidgetView( 2082): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2082): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
W/[Concierge]WidgetView( 2082): Widget kill message received. Destory myself. My : 1455113468500, New one : 1455113694025
D/[Concierge]WidgetView( 2082): Unregister all receivers
,W/[Concierge]WidgetBroadcastReceiver( 2082): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/[LGHome]EVENT( 2082): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LgeWidgetLib]LgeAppWidgetHostView( 2082): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 2082): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/Timeline( 2082): Timeline: Activity_idle id: android.os.BinderProxy@1d206994 time:254110
,W/ExternalStrings( 7635): load override strings
W/ExternalStrings( 7635): java.lang.RuntimeException: Unexpected tag, got eat-comment
W/ExternalStrings( 7635): 	at com.mcafee.plugin.af.a(Unknown Source)
W/ExternalStrings( 7635): 	at com.mcafee.plugin.ac.b(Unknown Source)
W/ExternalStrings( 7635): 	at com.mcafee.plugin.ak.d(Unknown Source)
W/ExternalStrings( 7635): 	at com.mcafee.plugin.ak.a(Unknown Source)
W/ExternalStrings( 7635): 	at com.mcafee.app.s.getClassLoader(Unknown Source)
W/ExternalStrings( 7635): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
W/ExternalStrings( 7635): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
W/ExternalStrings( 7635): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
W/ExternalStrings( 7635): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
W/ExternalStrings( 7635): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
W/ExternalStrings( 7635): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ExternalStrings( 7635): 	at android.os.Looper.loop(Looper.java:135)
W/ExternalStrings( 7635): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/ExternalStrings( 7635): 	at java.lang.reflect.Method.invoke(Native Method)
W/ExternalStrings( 7635): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/ExternalStrings( 7635): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/ExternalStrings( 7635): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,D/StatusProvider( 7635): onCreate
I/chromium( 2082): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,V/Signer  ( 7635): override build config not found
D/Signer  ( 7635): value of property debug is false
D/LGMDMWrapper( 7635): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
,D/LGMDMWrapper( 7635): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
D/LGMDMWrapper( 7635): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
D/LGMDMWrapper( 7635): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
D/LGMDMWrapper( 7635): Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
D/LGMDMWrapper( 7635): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
D/LGMDMWrapper( 7635): Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
D/LGMDMWrapper( 7635): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
D/LGMDMWrapper( 7635): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
D/LGMDMWrapper( 7635): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
D/LGMDMWrapper( 7635): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
D/LGMDMWrapper( 7635): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
D/LGMDMWrapper( 7635): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
I/GBoardtInterface( 2082): onReloaded()
V/LGMDMManager( 7635): Create singleton instance
I/GBoardWebViewClient( 2082): onPageFinished url:file:///android_asset/www/main.html
,V/BoardContentProvider( 2694): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
V/BoardContentProvider( 2694): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/ActionManagerService( 1917): notifyUserLog: 1000001
,D/LIA_Informant_ActionManagerMessageHandler( 2694): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 2694): onEvent() : ACTION_BOARD_ENABLED
D/ActionManagerService( 1917): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 2694): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 2694): onEvent() : ACTION_BOARD_ENABLED
D/LIA_Informant_Tips_FormEventRepository( 2694): getSize() : size - 0
D/LIA_Informant_Tips_SmartTipsActionManager( 2694): onSettingEvent() : GBoard On - add scheduler - 0
V/BoardContentProvider( 2694): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,D/GBoardUriUtils( 2082): fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
D/GBoardWebViewUtils( 2082): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial

```
