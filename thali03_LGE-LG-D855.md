#### Test 586024278176cca_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
I/MusicWidget( 2642): mDelayedStopHandler : unbind
,I/MusicBrowser( 2140): [MediaPlaybackService.java:2869:onUnbind()] oooooo 
I/MusicBrowser( 2140): [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2140): [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2140): [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2140): [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2140): [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2140): [MediaPlaybackService.java:2046:onDestroy()] oooooo 
I/MusicBrowser( 2140): [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
I/MediaFocusControl( 1032):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@a5e81afcom.lge.music.MediaPlaybackService$5@321ab9bc
D/MusicBrowser( 2140): [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2140): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2140): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2140): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2140): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@3db1e4ea
I/MusicBrowser( 2140): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2140): [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2140): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2140): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2140): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2140): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2140): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2140): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2140): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2140): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2140): [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2140): [MediaPlaybackService.java:6704:release()] oooooo 
I/MusicBrowser( 2140): [MediaPlaybackService.java:6665:stop()] oooooo 
V/MediaPlayer[Native]( 2140): reset
V/MediaPlayer[Native]( 2140): setListener
V/MediaPlayer[Native]( 2140): disconnect
V/MediaPlayer[Native]( 2140): destructor
V/AudioFlinger(  327): releasing 13 from 2140 for -1
V/AudioFlinger(  327):  decremented refcount to 0
V/AudioFlinger(  327): purging stale effects
V/MediaPlayer[Native]( 2140): disconnect
D/MusicBrowser( 2140): [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
I/SmartShareClient( 2140): [SmartShareManagerClient] smartshare client supported version code: 305000
I/SmartShareClient( 2140): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2140): [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
I/MusicBrowser( 2140): [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2140): [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2140): [SmartShareManagerClient] unregisterListener: 492866885
W/SmartShareClient( 2140): [SmartShareManagerClient] unregisterListener invalid listener: 492866885
I/SmartShareClient( 2140): [SmartShareManagerClient] terminate service: 2140/MediaPlaybackService/980476768
E/HomeCloudIF( 2140): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2140): [SmartShareManagerClient] unbindService context:android.app.Application@35855c9a
V/CloudHub( 2140): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
V/CloudHub( 2140): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2140): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
D/MusicBrowser( 2140): [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
--------- beginning of system
I/ActivityManager( 1032): Killing 5850:com.google.android.partnersetup/u0a8 (adj 15): empty #17
I/CloudHub( 2140): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29972
W/libprocessgroup( 1032): failed to open /acct/uid_10008/pid_5850/cgroup.procs: No such file or directory
D/AndroidRuntime( 6117): 
D/AndroidRuntime( 6117): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6117): CheckJNI is OFF
D/AndroidRuntime( 6117): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1032): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1928): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1032): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1032): setTaskToReturnTo : TaskRecord{2379a898 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1032): setTaskToReturnTo : TaskRecord{2379a898 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1032): AppWindowTokenEx init.. 
E/GBMv2   (  343): DFP En is all cleared set to be enabled
I/ActivityManager( 1032): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6138 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6117): Shutting down VM
V/ActivityManager( 1032): Display changed displayId=0
D/DSDPConnection( 1840): Display #0 changed.
D/SplitWindowPolicy( 1928): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1928): topRunningActivity=ActivityInfo{2ce2b457 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1928): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1928): topRunningActivity=ActivityInfo{1c37b44 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 6138): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/WebViewFactory( 6138): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 6138): Loading: webviewchromium
I/LibraryLoader( 6138): Time to load native libraries: 3 ms (timestamps 5469-5472)
I/LibraryLoader( 6138): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6138): Binding Chromium to main looper Looper (main, tid 1) {3a70e360}
I/LibraryLoader( 6138): Expected native library version number "",actual native library version number ""
I/chromium( 6138): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6138): Initializing chromium process, renderers=0
W/art     ( 6138): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6138): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,W/chromium( 6138): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6138): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 6138): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
V/AudioPolicyService(  327): registerClient() client 0xb100fd80, uid 10311
,D/BluetoothManagerService( 1032): Message: 20
D/BluetoothManagerService( 1032): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@65fc062:true
D/BluetoothAdapter( 6138): 60309529: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 6138): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6138): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6138): Build Date: 12/12/14 금
I/Adreno-EGL( 6138): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6138): Remote Branch: 
I/Adreno-EGL( 6138): Local Patches: 
I/Adreno-EGL( 6138): Reconstruct Branch: 
,W/chromium( 6138): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 6138): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 6138): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6138): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6138): CordovaWebView is running on device made by: LGE
,W/art     ( 6138): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6138): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6138): Render dirty regions requested: true
I/OpenGLRenderer( 6138): Initialized EGL, version 1.4
D/OpenGLRenderer( 6138): Enabling debug mode 0
,D/Atlas   ( 6138): Validating map...
D/SplitWindow( 1032): check instance of lgWin Window{b42220c u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/LgDataFeature( 6138): LgDataFeature() Constructor: none
D/LgDataFeature( 6138): LgDataFeature() Constructor Done, null
,I/SystemUI[Framework]( 1032): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
,D/PhoneStatusBar( 1463): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
W/PhoneWindowManagerEx( 1032): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1032): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1032): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1032): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@32acc222,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1032): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1463): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1463):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1463): , Keyguard show=false, IME shown=false, Panel expanded=false
I/ActivityManager( 1032): Displayed com.test.thalitest/.MainActivity: +536ms (total +626ms)
I/Timeline( 1032): Timeline: Activity_windows_visible id: ActivityRecord{29bb48f1 u0 com.test.thalitest/.MainActivity t4} time:105876
,I/Timeline( 6138): Timeline: Activity_idle id: android.os.BinderProxy@319c6189 time:105880
D/JsMessageQueue( 6138): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6138): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435194624
,I/chromium( 6138): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 6138): 
,I/chromium( 6138): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/chromium( 6138): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6138): 
,E/GBMv2   (  343): DFP En is all cleared set to be enabled
E/GBMv2   (  343): Set value is all cleared set the max
I/GBMv2   (  343): DFP Enabled. Ignore VFP set
,W/jxcore-log( 6138): Initializing JXcore engine
W/jxcore-log( 6138): JXcore engine is ready
,W/Thread-719( 6190): type=1400 audit(0.0:148): avc: denied { ioctl } for path="socket:[7320]" dev="sockfs" ino=7320 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-719( 6190): type=1400 audit(0.0:149): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,W/Thread-719( 6190): type=1400 audit(0.0:150): avc: denied { ioctl } for path="socket:[10548]" dev="sockfs" ino=10548 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-719( 6190): type=1400 audit(0.0:151): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/Thread-719( 6190): type=1400 audit(0.0:152): avc: denied { ioctl } for path="socket:[29074]" dev="sockfs" ino=29074 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
W/jxcore-log( 6138): Starting JXcore engine
,W/jxcore-log( 6138): Platform android
W/jxcore-log( 6138): 
W/jxcore-log( 6138): Process ARCH arm
W/jxcore-log( 6138): 
,I/jxcore-log( 6138): JXcore Cordova bridge is ready!
I/jxcore-log( 6138): 
W/jxcore-log( 6138): JXcore engine is started
,I/jxcore-log( 6138): Toggling radios to true
I/jxcore-log( 6138): 
,D/BluetoothManagerService( 1032): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1032): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService( 1032): Message: 1
D/BluetoothManagerService( 1032): MESSAGE_ENABLE: mBluetooth = null
D/LocationManagerService( 1032): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1032): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1032): JNI:system_update. Event-4
D/WifiService( 1032): New client listening to asynchronous messages
,I/ActivityManager( 1032): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=6194 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
D/WifiServiceImplEx( 1032): setWifiEnabled: true pid=6138, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1032): setWifiEnabled: true pid=6138, uid=10311
E/WifiService( 1032): Invoking mWifiStateMachine.setWifiEnabled
,D/LocationManagerService( 1032): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1032): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,D/Ulp_jni ( 1032): JNI:system_update. Event-4
E/WifiStateMachine( 1032):  InitialState CMD_START_SUPPLICANT 0 0
I/LGFTMITEM( 1032): [GET_FTM][id=6], offset=12288
D/WifiServiceImplEx( 1032): disconnect pid=6138, uid=10311, packageName=com.test.thalitest
D/WifiServiceImplEx( 1032): reconnect pid=6138, uid=10311, packageName=com.test.thalitest
I/jxcore-log( 6138): Radios toggled
I/jxcore-log( 6138): 
E/WifiUtil( 1032): wfc_util_ffile_check_copy(): pid[1032] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
E/WifiUtil( 1032): wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
E/WifiUtil( 1032): wfc_util_ffile_check_copy(): pid[1032] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
E/WifiUtil( 1032): wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
I/WifiUtil( 1032): Intf0MacAddress=C49A027B60AC
E/WifiHW  ( 1032): unknown target_country: EU , set to default
E/WifiHW  ( 1032): [wifi_ensure_config_files] default country1 = GB
E/WifiHW  ( 1032): [wifi_ensure_config_files] default country2 = GB
I/WifiUtil( 1032): gEnableBmps=1
I/jxcore-log( 6138): My device name is: LGE-LG-D855
I/jxcore-log( 6138): 
,W/ResourcesManager( 6194): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager( 6194): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6194): Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 6194): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/BluetoothAdapterApp( 6194): Loading JNI Library
,D/BluetoothAdapterApp( 6194): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@cf5fbf4 Instance Count = 1
D/Tethering( 1032): sendTetherStateChangedBroadcast 1, 0, 0
,D/SoftapController(  323): Softap fwReload - Ok
D/CommandListener(  323): Setting iface cfg
D/CommandListener(  323): Trying to bring down wlan0
D/libc-netbsd(  323): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1032): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,D/CommandListener(  323): Clearing all IP addresses on wlan0
E/WifiHW  ( 1032): Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
I/ActivityManager( 1032): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=6226 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,D/BluetoothAdapterApp( 6194): onCreate
E/WifiStateMachine( 1032): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1032): useWiFiOffloading() : false
E/WifiStateMachine( 1032): CONFIG_LGE_WLAN_PATH : true
V/WfdStateTracker( 1928): WfdStateTracker handleDirectStateChangedEvent: 1
W/wpa_supplicant( 6232): type=1400 audit(0.0:153): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/wpa_supplicant( 6232): type=1400 audit(0.0:154): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/WifiServerServiceExt( 1032): WIFI_STATE_CHANGED_ACTION [2]
D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiMonitor( 1032): startMonitoring(wlan0) with mConnected = false
I/wpa_supplicant( 6232): Successfully initialized wpa_supplicant
,D/WifiMonitor( 1032): connecting to supplicant
I/wpa_supplicant( 6232): rfkill: Cannot open RFKILL control device
I/wpa_supplicant( 6232): [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
D/Tethering( 1032): InitialState.processMessage what=4
D/Tethering( 1032): sendTetherStateChangedBroadcast 0, 0, 0
,D/ProfileConfigQcom( 6194): [BTUI] HeadsetService is supported
,D/ProfileConfigQcom( 6194): Adding HeadsetService
D/ProfileConfigQcom( 6194): [BTUI] A2dpService is supported
,D/ProfileConfigQcom( 6194): Adding A2dpService
D/ProfileConfigQcom( 6194): [BTUI] HidService is supported
D/ProfileConfigQcom( 6194): Adding HidService
D/ProfileConfigQcom( 6194): [BTUI] HealthService is supported
D/ProfileConfigQcom( 6194): Adding HealthService
D/LGBluetoothFeatureConfig( 6194): isSupportPan() :  mTargetOp=OPEN
D/ProfileConfigQcom( 6194): [BTUI] PanService is supported
D/ProfileConfigQcom( 6194): Adding PanService
D/ProfileConfigQcom( 6194): [BTUI] GattService is supported
D/ProfileConfigQcom( 6194): Adding GattService
D/ProfileConfigQcom( 6194): [BTUI] BluetoothMapService is supported
D/ProfileConfigQcom( 6194): Adding BluetoothMapService
D/ProfileConfigQcom( 6194): [BTUI] HeadsetClientService is NOT supported
D/BluetoothManagerService( 1032): Message: 20
D/BluetoothManagerService( 1032): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3ff3d02f:true
,W/ResourcesManager( 6226): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6226): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6226): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/BluetoothAdapterState( 6194): make
W/ResourcesManager( 6226): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 6226): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6226): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/LGFMServiceAdapter( 6194): [FM] LGFMServiceAdapter : create
I/bluedroid-qcom( 6194): init
I/BluetoothAdapterState( 6194): Entering OffState
I/bte_conf( 6194): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
I/bte_conf( 6194): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 6194): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 6194): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
D/BTIF_CORE( 6194): [BTUI] lge_load_bluetooth_address
I/bluedroid-qcom( 6194): get_profile_interface socket
I/bluedroid-qcom( 6194): get_profile_interface map_client
,W/bdaddr_loader( 6253): type=1400 audit(0.0:155): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/bdaddr_loader( 6253): type=1400 audit(0.0:156): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/GKI_LINUX( 6194): gki_task_entry task_id=1 [BTIF] starting
D/BluetoothManagerService( 1032): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
I/wpa_supplicant( 6232): rfkill: Cannot open RFKILL control device
D/BluetoothManagerService( 1032): Message: 40
D/BluetoothManagerService( 1032): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
D/BluetoothAdapterProperties( 6194): Address is:58:3F:54:73:64:C0
D/BluetoothAdapterProperties( 6194): Name is: G3-1
D/BluetoothManagerService( 1032): Bluetooth Adapter name changed to G3-1
D/BluetoothManagerService( 1032): Stored Bluetooth name: G3-1
I/bluedroid-qcom( 6194): config_hci_snoop_log
D/BluetoothManagerService( 1032): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService( 1032): Broadcasting onBluetoothServiceUp() to 7 receivers.
V/LGMDMManagerInternal( 6194): Create singleton instance
D/lge_bdaddr_loader( 6253): [BTUI] bdaddr_loader ::: START
D/lge_bdaddr_loader( 6253): [BTUI] bluetooth_load_bdaddress
I/LGFTMITEM( 6253): [GET_FTM][id=8], offset=16384
,D/lge_bdaddr_loader( 6253): [BTUI] bdaddr to set in property : 58:3F:54:73:64:C0
E/lge_bdaddr_loader( 6253): [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:64:C0
D/lge_bdaddr_loader( 6253): [BTUI] bdaddr_loader ::: END
,I/wpa_supplicant( 6232): [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
I/wpa_supplicant( 6232): p2p0: CTRL-EVENT-AVOID-FREQ ranges=
I/wpa_supplicant( 6232): wlan0: CTRL-EVENT-SCAN-STARTED 
,E/WifiStateMachine( 1032):  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
E/WifiStateMachine( 1032):  SupplicantStartingState CMD_START_DRIVER 0 0
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
W/Settings( 1032): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1032): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/WifiStateMachine( 1032): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1032): useWiFiOffloading() : false
E/WifiStateMachine( 1032): CONFIG_LGE_WLAN_PATH : true
I/WifiServerServiceExt( 1032): WIFI_STATE_CHANGED_ACTION [3]
D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
I/WifiServerServiceExt( 1032): batteryPsActivateMsgHandler : state:0 event:3
D/WfdService( 1928): Waiting for WifiP2p enabling
D/WifiNative-wlan0( 1032): doBoolean: SET update_config 1
D/WifiNative-wlan0( 1032): SET update_config 1: returned true
D/WifiConfigStore( 1032): Loading config and enabling all networks 
D/WifiNative-wlan0( 1032): doString: [LIST_NETWORKS]
D/WifiNative-wlan0( 1032):    returned network id / ssid / bssid / flags 0	NG700	any	
D/BluetoothAdapterState( 6194): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
E/WifiConfigStore( 1032): readNetworkVariablesFromSupplicantFile key=psk
D/WifiMonitor( 1032): Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
D/BluetoothAdapterProperties( 6194): Setting state to 11
D/WifiMonitor( 1032): Dropping event because (p2p0) is stopped
I/BluetoothAdapterState( 6194): Bluetooth adapter state changed: 10-> 11
D/WifiMonitor( 1032): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
D/BluetoothManagerService( 1032): Message: 60
,D/BluetoothManagerService( 1032): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService( 1032): Bluetooth State Change Intent: 10 -> 11
I/LGBluetoothServiceJni( 6194): classInitNative: succeeds
E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=0 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1032): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1032): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/LGBluetoothAPIService( 1928): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
I/[SystemUI]BluetoothHandler( 1463): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
E/WifiConfigStore( 1032): readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
E/WifiConfigStore( 1032): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
D/WifiStateMachine( 1032): enableVerboseLogging : level 2
D/WifiNative-wlan0( 1032): doBoolean: SET device_name g3_global_com
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
D/WfdsService( 1928): Supplicant Connection state is changed : true
D/WfdsService( 1928): DefaultState - WIFI_SUPPLICANT_CONNECTED
D/WfdsService( 1928): Set the WFDS Monitor: true
D/WifiStateMachine( 1032): Setting OUI to DA-A1-19
D/WifiNative-wlan0( 1032): doBoolean: SCAN_INTERVAL 120
D/WifiNative-wlan0( 1032): SCAN_INTERVAL 120: returned true
D/WifiNative-HAL( 1032): Setting external_sim to 1
D/WifiNative-wlan0( 1032): doBoolean: SET external_sim 1
D/WifiNative-wlan0( 1032): SET external_sim 1: returned true
I/WifiNative-HAL( 1032): startHal
D/WfdsMonitor( 1928): WfdsMonitorThread create
E/wifi    ( 1032): getStaticLongField sWifiHalHandle 0x9894c8dc
E/WifiHAL ( 1032): Could not connect handle
D/wifi    ( 1032): halHandle = 0x0, mVM = 0xb487c280, mCls = 0xa01ad2
I/WifiNative-HAL( 1032): Could not start hal
D/WfdsMonitor( 1928): WFDS Monitor is created and started
D/WfdsService( 1928): WiFi: Supplicant connection re-established
D/WifiStateMachine( 1032): Setting OUI to DA-A1-19
I/WifiNative-HAL( 1032): startHal
E/wifi    ( 1032): getStaticLongField sWifiHalHandle 0x9894c85c
E/WifiHAL ( 1032): Could not connect handle
D/wifi    ( 1032): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x701ace
I/WifiNative-HAL( 1032): Could not start hal
D/WifiNative-wlan0( 1032): doBoolean: STA_AUTOCONNECT 1
D/WifiNative-wlan0( 1032): STA_AUTOCONNECT 1: returned true
D/WifiNative-wlan0( 1032): doBoolean: DRIVER BTCOEXSCAN-STOP
I/wpa_supplicant( 6232): wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
D/WifiNative-wlan0( 1032): DRIVER BTCOEXSCAN-STOP: returned true
D/WifiHS20( 1032): hidePasspointNotification off =false
E/CtrlSupplicant( 1928): Access OK "@android:wpa_wlan0"
E/CtrlSupplicant( 1928): Succeed to open control connection
E/CtrlSupplicant( 1928): Succeed to open monitor connection
W/Settings( 1032): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1032): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1032): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiNative-wlan0( 1032): doBoolean: DRIVER RXFILTER-STOP
I/wpa_supplicant( 6232): wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
D/WfdsMonitor( 1928): Supplicant connection established
D/WfdsService( 1928): Connected to the supplicant for wfds
D/WifiNative-wlan0( 1032): DRIVER RXFILTER-STOP: returned true
D/WifiNative-wlan0( 1032): doBoolean: DRIVER RXFILTER-REMOVE 3
I/wpa_supplicant( 6232): wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
D/WifiNative-wlan0( 1032): DRIVER RXFILTER-REMOVE 3: returned true
D/WifiNative-wlan0( 1032): doBoolean: DRIVER RXFILTER-START
I/wpa_supplicant( 6232): wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
D/WifiNative-wlan0( 1032): DRIVER RXFILTER-START: returned true
D/WifiNative-wlan0( 1032): doBoolean: DRIVER RXFILTER-STOP
I/wpa_supplicant( 6232): wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
D/WifiNative-wlan0( 1032): DRIVER RXFILTER-STOP: returned true
D/WifiNative-wlan0( 1032): doBoolean: DRIVER RXFILTER-REMOVE 2
I/wpa_supplicant( 6232): android_multicast_filter_startstop : multicast filter set
D/WifiNative-wlan0( 1032): DRIVER RXFILTER-REMOVE 2: returned true
D/WifiNative-wlan0( 1032): doBoolean: DRIVER RXFILTER-START
I/wpa_supplicant( 6232): wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
,D/WifiNative-wlan0( 1032): DRIVER RXFILTER-START: returned true
E/WifiNative: ( 1032): [108,693,205 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
D/WifiNative-wlan0( 1032): doBoolean: RECONNECT
D/WifiNative-wlan0( 1032): RECONNECT: returned true
D/WifiNative-wlan0( 1032): doString: [STATUS]
D/WifiMonitor( 1032): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=1 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiNative-wlan0( 1032):    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
D/WifiNative-wlan0( 1032): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 6232): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1032): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1032): doBoolean: SET ps 1
D/WifiNative-wlan0( 1032): SET ps 1: returned true
D/LGWifiP2pService( 1032): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService( 1032): SCAN_AVAILABLE : 3
D/RttService( 1032): SCAN_AVAILABLE : 3
D/WifiScanningService( 1032): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL( 1032): startHal
E/wifi    ( 1032): getStaticLongField sWifiHalHandle 0x9652b99c
E/WifiHAL ( 1032): Could not connect handle
D/wifi    ( 1032): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x801aca
I/WifiNative-HAL( 1032): Could not start hal
E/WifiScanningService( 1032): could not start HAL
D/RttService( 1032): DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  323): Setting iface cfg
D/CommandListener(  323): Trying to bring up p2p0
E/WifiStateMachine( 1032):  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
D/WifiMonitor( 1032): startMonitoring(p2p0) with mConnected = true
D/LGWifiP2pService( 1032): P2pEnablingState
D/LGWifiP2pService( 1032): P2pEnablingState{ when=-1ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 1032):  DisconnectedState CMD_START_DRIVER 0 0
D/LGWifiP2pService( 1032): P2p socket connection successful
D/LGWifiP2pService( 1032): P2pEnabledState
E/WifiStateMachine( 1032):  ConnectModeState CMD_START_DRIVER 0 0
E/WifiStateMachine( 1032):  DriverStartedState CMD_START_DRIVER 0 0
E/WifiStateMachine( 1032):  DisconnectedState what:132106 1 0
E/WifiStateMachine( 1032):  ConnectModeState what:132106 1 0
E/WifiStateMachine( 1032):  DriverStartedState what:132106 1 0
I/WifiServerServiceExt( 1032): setWifiDualbandAPConnection band : 1
E/wpa_supplicant( 6232): nWIFIDualbandAPConnection: 1
E/WifiStateMachine( 1032):  DisconnectedState what:132096 -100 0
D/LGWifiP2pService( 1032): sending p2p connection changed broadcast
E/WifiStateMachine( 1032):  ConnectModeState what:132096 -100 0
E/WifiStateMachine( 1032):  DriverStartedState what:132096 -100 0
I/WifiServerServiceExt( 1032): set CMD_DISCONNECT_RSSI_LVL : -100
E/wpa_supplicant( 6232): disconnect_rssi_lvl: -100
D/WifiNative-p2p0( 1032): doBoolean: SET persistent_reconnect 1
E/WifiStateMachine( 1032):  DisconnectedState CMD_SET_COUNTRY_CODE 1 0 cz
V/WfdStateTracker( 1928): WfdStateTracker handleDirectStateChangedEvent: 2
D/WfdsService( 1928): WifiP2pState is changed : true
D/WfdsService( 1928): Receive the WFDS_ENABLE Method
D/WfdsService( 1928): Set the WFDS Monitor: true
D/WfdsService( 1928): Connected to the supplicant for wfds
D/WfdsJNI ( 1928): doCommand: WFDS_SET TRUE
I/wpa_supplicant( 6232): WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
D/WfdsJNI ( 1928): doCommand: WFDS_GET_MAC_ADDRESS
I/wpa_supplicant( 6232): WFDS: wfds_supplicant_wfds_cmd: cmd = GET_MAC_ADDRESS
D/WfdsJNI ( 1928): doCommand: IFNAME=wlan0 GET_CAPABILITY channels
D/WfdsService( 1928): selectPreferredScanChannel [36]
D/WfdsService( 1928): STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7b:60:ac
D/WifiNative-p2p0( 1032): SET persistent_reconnect 1: returned true
D/WifiNative-p2p0( 1032): doBoolean: SET device_name G3-1
D/WfdsService( 1928): WIFI_P2P_CONNECTION_CHANGED_ACTION
D/WifiNative-p2p0( 1032): SET device_name G3-1: returned true
D/LGWifiP2pService( 1032): [LGE_P2P] initializeP2pSettings() check postfix
D/LGWifiP2pService( 1032): before postfix = G3-1
D/WifiServerServiceExt( 1032): postfix byte check : 4
D/LGWifiP2pService( 1032): after postfix = G3-1
D/WifiNative-p2p0( 1032): doBoolean: SET p2p_ssid_postfix -G3-1
D/WfdsService( 1928): isConnected: false
D/WifiNative-p2p0( 1032): SET p2p_ssid_postfix -G3-1: returned true
D/WifiNative-p2p0( 1032): doBoolean: SET device_type 10-0050F204-5
D/WifiNative-p2p0( 1032): SET device_type 10-0050F204-5: returned true
D/WifiNative-p2p0( 1032): doBoolean: SET config_methods virtual_push_button physical_display keypad
E/WifiStateMachine( 1032):  ConnectModeState CMD_SET_COUNTRY_CODE 1 0 cz
E/WifiStateMachine( 1032):  DriverStartedState CMD_SET_COUNTRY_CODE 1 0 cz
D/WifiNative-p2p0( 1032): SET config_methods virtual_push_button physical_display keypad: returned true
D/WifiNative-p2p0( 1032): doBoolean: P2P_SET conc_pref p2p
D/WifiNative-wlan0( 1032): doBoolean: DRIVER COUNTRY CZ
D/WifiNative-p2p0( 1032): P2P_SET conc_pref p2p: returned true
D/WifiNative-HAL( 1032): p2pGetDeviceAddress
I/wpa_supplicant( 6232): wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
I/wpa_supplicant( 6232): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
D/WifiMonitor( 1032): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=2 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1032): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1032): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
I/wpa_supplicant( 6232): [LGE_PATCH] driver_cmd() country:CZ
I/wpa_supplicant( 6232): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiMonitor( 1032): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WfdsMonitor( 1928): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1032): WifiMonitor:p2p0 cnt=3 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1032): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1032): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
I/wpa_supplicant( 6232): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WfdsMonitor( 1928): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WifiMonitor( 1032): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1032): WifiMonitor:p2p0 cnt=4 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1032): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1032): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiNative-wlan0( 1032): DRIVER COUNTRY CZ: returned true
I/StatusBar.NetworkController( 1463): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1463): mWifiConnected = false, mWifiLevel = 0
,E/WifiStateMachine( 1032):  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine( 1032):  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine( 1032):  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
D/WifiNative-wlan0( 1032): doBoolean: DRIVER SETBAND 0
I/wpa_supplicant( 6232): wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
I/wpa_supplicant( 6232): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
D/WifiMonitor( 1032): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=5 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
E/WifiMonitor( 1032): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
E/WifiMonitor( 1032): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
D/WifiNative-HAL( 1032): p2pGetDeviceAddress returning 02:9a:02:7b:60:ac
D/LGWifiP2pService( 1032): DeviceAddress: 02:9a:02:7b:60:ac
D/WifiNative-p2p0( 1032): doBoolean: P2P_FLUSH
D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiNative-wlan0( 1032): DRIVER SETBAND 0: returned true
D/WifiNative-wlan0( 1032): doBoolean: BSS_FLUSH 0
D/WifiNative-wlan0( 1032): BSS_FLUSH 0: returned true
D/WifiNative-wlan0( 1032): doBoolean: SCAN
I/WfdStateTracker( 1928): handleP2pThisDeviceChanged
D/WfdsService( 1928): WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
D/WfdsService( 1928): Update P2p Interface State: 3
D/WifiNative-wlan0( 1032): SCAN: returned false
E/WifiStateMachine( 1032):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=108741  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/WifiNative-p2p0( 1032): P2P_FLUSH: returned true
D/WifiNative-p2p0( 1032): doBoolean: P2P_SERVICE_FLUSH
D/WifiNative-p2p0( 1032): P2P_SERVICE_FLUSH: returned true
D/WifiNative-p2p0( 1032): doString: [LIST_NETWORKS]
D/WifiNative-p2p0( 1032):    returned network id / ssid / bssid / flags
D/WifiNative-p2p0( 1032): doBoolean: SAVE_CONFIG
I/art     ( 1032): Explicit concurrent mark sweep GC freed 35216(1795KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 44MB/66MB, paused 3.974ms total 135.210ms
E/WifiStateMachine( 1032):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=108745  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine( 1032):  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1032):  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1032):  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
D/WifiService( 1032): New client listening to asynchronous messages
D/BluetoothBondStateMachine( 6194): make
E/WifiStateMachine( 1032):  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1032):  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
D/WifiNative-p2p0( 1032): SAVE_CONFIG: returned true
D/BluetoothAdapterService( 6194): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25af6abf
D/LGWifiP2pService( 1032): sending p2p persistent groups changed broadcast
D/LGBluetoothServiceAdapter( 6194): [BTUI] check adapter is available - false.
D/BluetoothAdapterService( 6194): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25af6abf
D/LGBluetoothServiceAdapter( 6194): [BTUI] check adapter is available - true : set adapter available.
D/LGBluetoothSettingsDBObserver( 6194): [BTUI] register observer for LG device name DB
I/StatusBar.NetworkController( 1463): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1463): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1032): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1032): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1032): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WifiServerServiceExt( 1032): SUPPLICANT_STATE_CHANGED_ACTION
D/LGWifiP2pService( 1032): InactiveState
D/WifiServerServiceExt( 1032): setSupplicantStateSCANNING
D/LGWifiP2pService( 1032): InactiveState{ when=-24ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): P2pEnabledState{ when=-24ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1032): doBoolean: DRIVER COUNTRY CZ
D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
I/wpa_supplicant( 6232): wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
I/wpa_supplicant( 6232): p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
I/wpa_supplicant( 6232): [LGE_PATCH] driver_cmd() country:CZ
I/wpa_supplicant( 6232): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
I/BluetoothBondStateMachine( 6194): StableState(): Entering Off State
D/WifiNative-p2p0( 1032): DRIVER COUNTRY CZ: returned true
D/LGWifiP2pService( 1032): InactiveState{ when=-12ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): P2pEnabledState{ when=-12ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): InactiveState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): P2pEnabledState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): DefaultState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 6232): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/LGWifiP2pService( 1032): InactiveState{ when=0 what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): P2pEnabledState{ when=0 what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): DefaultState{ when=0 what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): InactiveState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): P2pEnabledState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): DefaultState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): InactiveState{ when=0 what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1032): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
D/LGWifiP2pService( 1032): P2pEnabledState{ when=0 what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): DefaultState{ when=0 what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiMonitor( 1032): WifiMonitor:p2p0 cnt=6 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1032): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1032): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
D/WfdsMonitor( 1928): Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
D/WifiMonitor( 1032): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WfdsMonitor( 1928): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiServerServiceExt( 1032): No p2p device connected
E/WifiMonitor( 1032): WifiMonitor:p2p0 cnt=7 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WfdsMonitor( 1928): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1032): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1032): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiMonitor( 1032): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1032): WifiMonitor:p2p0 cnt=8 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1032): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1032): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
W/WfdsService( 1928): DefaultState - msg [9441285] is not handled
E/BluetoothAdapterService( 6194): File transfer profiles supported!!
E/BluetoothAdapterService( 6194): File transfer profiles supported!!
D/BluetoothHeadset( 1032): Proxy object connected
D/BluetoothHeadset( 1840): Proxy object connected
D/HeadsetService( 6194): Received start request. Starting profile...
I/LGBluetoothHeadsetServiceJni( 6194): classInitNative: succeeds
D/LGBluetoothHfpAdapter( 6194): Version 1.6
D/BluetoothHeadset( 1840): Proxy object connected
D/BluetoothHeadset( 1840): Proxy object connected
D/LGBluetoothFeatureConfig( 6194): isPrivacyLogsEnabled : true
,I/BluetoothHeadsetServiceJni( 6194): classInitNative: succeeds
D/HeadsetStateMachine( 6194): make
E/BluetoothAdapterService( 6194): File transfer profiles supported!!
E/BluetoothAdapterService( 6194): File transfer profiles supported!!
E/BluetoothAdapterService( 6194): File transfer profiles supported!!
E/BluetoothAdapterService( 6194): File transfer profiles supported!!
E/BluetoothAdapterService( 6194): File transfer profiles supported!!
D/LgDataFeature( 6194): LgDataFeature() Constructor: none
D/LgDataFeature( 6194): LgDataFeature() Constructor Done, null
V/LGMDMManager( 6194): Create singleton instance
D/HeadsetStateMachine( 6194): max_hf_connections = 1
I/bluedroid-qcom( 6194): get_profile_interface handsfree
I/BluetoothAdapterState( 6194): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
V/ToneGenerator( 6194): ToneGenerator constructor: streamType=8, volume=1.000000
V/AudioPolicyService(  327): registerClient() client 0xb100ff80, uid 1002
V/AudioPolicyManager(  327): getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  327): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  327): getOutput() returns output 2
V/AudioSystem( 6194): getOutputSamplingRate() no output descriptor for output 2 in gOutputs
V/AudioFlinger(  327): registerClient() client 0xb1433058, pid 6194
V/AudioSystem(  327): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem(  327): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1463): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1463): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 2140): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 2140): ioConfigChanged() opening already existing output! 4
V/AudioSystem(  327): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  327): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1463): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1463): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 2140): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 2140): ioConfigChanged() opening already existing output! 2
V/ToneGenerator( 6194): Create Track: 0xb4928080
V/AudioTrack( 6194): set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
V/AudioTrack( 6194): set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
V/AudioSystem( 6194): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 6194): ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
V/AudioSystem( 6194): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1032): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1032): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 6194): ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
V/AudioSystem( 1032): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1032): ioConfigChanged() opening already existing output! 2
V/AudioPolicyManager(  327): getOutputForAttr() usage=3, content=4, tag= flags=00000000
V/AudioPolicyManager(  327): getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  327): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  327): getOutput() returns output 2
I/AudioFlinger(  327): isAudioPlaybackHookOn() false
V/AudioPolicyManager(  327): getOutputForAttr() usage=3, content=4, tag= flags=00000000
V/AudioPolicyManager(  327): getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
V/AudioPolicyManagerEx(  327): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  327): getOutput() returns output 2
V/AudioSystem( 6194): getLatency() output 2, latency 50
V/AudioSystem( 6194): getFrameCount() output 2, frameCount 960
V/AudioTrack( 6194): createTrack_l() output 2 afLatency 50
V/AudioFlinger(  327): [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
V/AudioFlinger(  327): [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
V/AudioFlinger(  327): [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
V/AudioFlinger(  327): [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
V/AudioFlinger(  327): createTrack() lSessionId: 16
V/AudioSystem( 1840): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1840): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1840): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1840): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 3295): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 3295): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 3295): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 3295): ioConfigChanged() opening already existing output! 2
V/AudioTrack( 6194): AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
V/AudioFlinger(  327): acquiring 16 from 6194, for 6194
V/AudioFlinger(  327):  added new entry for 16
V/ToneGenerator( 6194): ToneGenerator INIT OK, time: 108822
D/BluetoothAdapterService( 6194): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25af6abf
D/HeadsetStateMachine( 6194): Enter Disconnected: -2, size: 0
D/HeadsetPhoneState( 6194): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 6194): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetStateMachine( 6194): [BTUI] change sampling rate to 8000 when device is disconnected
D/BluetoothAdapterService( 6194): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25af6abf
V/AudioFlinger(  327): setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6194
D/audio_hw_primary(  327): adev_set_parameters: enter: bt_samplerate=8000
V/voice   (  327): voice_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  327): voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  327): voice_extn_compress_voip_set_parameters: exit
V/voice   (  327): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  327): LGE_platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  327): platform_set_parameters: enter: bt_samplerate=8000
D/A2dpService( 6194): Received start request. Starting profile...
V/msm8974_platform(  327): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  327): lge_platform_set_loopback_parameters: enter: 
V/audio_hw_primary(  327): adev_set_parameters: exit with code(0)
E/audio_a2dp_hw(  327): adev_set_parameters: ERROR: set param called even when stream out is null
D/BluetoothA2dp( 1032): Proxy object connected
I/BluetoothAvrcpServiceJni( 6194): classInitNative: succeeds
,V/ToneGenerator( 6194): ToneGenerator destructor
V/ToneGenerator( 6194): stopTone
V/ToneGenerator( 6194): Delete Track: 0xb4928080
V/Avrcp   ( 6194): make
D/Avrcp   ( 6194): [BTUI] Use Native AVRCP : init jni
I/bluedroid-qcom( 6194): get_profile_interface avrcp
V/AudioTrack( 6194): ~AudioTrack, releasing session id from 6194 on behalf of 6194
V/AudioFlinger(  327): releasing 16 from 6194 for 6194
V/AudioFlinger(  327):  decremented refcount to 0
V/AudioFlinger(  327): purging stale effects
D/UsbSettingsReceiver( 6226): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
W/Process ( 1032): Unable to open /proc/6261/status
V/AudioPolicyService(  327): AudioCommandThread() adding release output 2
V/AudioPolicyService(  327): inserting command: 6 at index 0, num commands 0
V/AudioPolicyService(  327): AudioCommandThread() waking up
D/UsbSettingsReceiver( 6226): [AUTORUN] sys.usb.config = ptp_only,adb
V/AudioPolicyService(  327): AudioCommandThread() processing release output 2
V/AudioPolicyManager(  327): releaseOutput() 2
V/AudioPolicyService(  327): AudioCommandThread() going to sleep
V/AudioFlinger(  327): PlaybackThread::Track destructor
V/AudioFlinger(  327): removeClient_l() pid 6194, calling pid 327
D/UsbSettingsReceiver( 6226): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6226): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6226): [AUTORUN] onReceive() : app userid = 0, current userid = 0
V/AudioManager( 6194): registerRemoteController: size of Media player list: 0
D/UsbSettingsControl( 6226): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6226): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6226): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6226): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6226): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6226): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 6226): [AUTORUN] setTetherStatus() : status=false
,E/AudioManager( 6194): No RCC entry present to update
E/RemoteController( 6194): Cannot set synchronization mode on an unregistered RemoteController
I/ActivityManager( 1032): Killing 5484:com.lge.appbox.client/u0a11 (adj 15): empty #17
I/BluetoothAvrcpQcomServiceJni( 6194): classInitQcomNative: succeeds
D/LGBluetoothAvrcpQcomAdapter( 6194): [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
I/BluetoothAvrcpQcomServiceJni( 6194): initQcomNative: succeeds
W/libprocessgroup( 1032): failed to open /acct/uid_10011/pid_5484/cgroup.procs: No such file or directory
,D/LGBluetoothAvrcpQcomAdapter( 6194): [BTUI] [+] updateMediaPlayerInfo
I/ActivityManager( 1032): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6266 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,I/art     (  356): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 481us total 21.854ms
I/art     (  356): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 404us total 18.391ms
,V/SIM_STK ( 1032): Menu title from STK is T-Mobile
V/SIM_STK ( 1032): Menu title from STK is T-Mobile
I/art     (  356): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 372us total 16.387ms
,E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=9 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/wpa_supplicant( 6232): USIM:  scard_init function
E/WifiMonitor( 1032): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1032): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=10 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1032): couldn't identify event type - WPS-AP-AVAILABLE 
I/wpa_supplicant( 6232): Trying to associate with SSID 'NG700'
E/WifiStateMachine( 1032):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine( 1032):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine( 1032):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine( 1032):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
I/WifiNative-HAL( 1032): startHal
E/wifi    ( 1032): getStaticLongField sWifiHalHandle 0x9894c8cc
E/WifiHAL ( 1032): Could not connect handle
D/wifi    ( 1032): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x701ffa
I/WifiNative-HAL( 1032): Could not start hal
D/WifiNative-wlan0( 1032): doString: [BSS RANGE=0- MASK=0x21987]
D/WifiMonitor( 1032): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=11 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,E/WifiStateMachine( 1032):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 11 0 rt=109079  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
I/StatusBar.NetworkController( 1463): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1463): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1032): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1032): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1032): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1032): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1032): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1032): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
E/WifiStateMachine( 1032):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 11 0 rt=109085  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
I/StatusBar.NetworkController( 1463): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1463): mWifiConnected = false, mWifiLevel = 0
D/WifiServerServiceExt( 1032): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1032): setSupplicantStateASSOCIATING
D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
I/ActivityManager( 1032): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6287 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,W/FormManager( 6266): Network not available. Please check & try again.
V/FormManager( 6266): Network unavailable.
,W/ActivityManager( 1032): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
V/FormManager( 6266): Network unavailable.
D/LGBluetoothAvrcpQcomAdapter( 6194): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 6194): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6194): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 6194): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 6194): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 6194): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6194): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 6194): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6194): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 6194): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6194): [BTUI] [-] updateMediaPlayerInfo
I/BluetoothA2dpServiceJni( 6194): classInitNative
I/BluetoothA2dpServiceJni( 6194): classInitNative: succeeds
D/A2dpStateMachine( 6194): make
I/bluedroid-qcom( 6194): get_profile_interface a2dp
I/GKI_LINUX( 6194): gki_task_entry task_id=2 [A2DP-MEDIA] starting
I/LGBluetoothA2dpServiceJni( 6194): classInitNative: succeeds
I/LGBluetoothA2dpAdapter( 6194): [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
D/BluetoothAdapterService( 6194): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25af6abf
I/BluetoothHidServiceJni( 6194): classInitNative: succeeds
I/ActivityManager( 1032): Killing 5505:com.android.contacts/u0a19 (adj 15): empty #17
D/A2dpStateMachine( 6194): Enter Disconnected: -2
,D/HidService( 6194): Received start request. Starting profile...
I/bluedroid-qcom( 6194): get_profile_interface hidhost
D/BluetoothAdapterService( 6194): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25af6abf
I/BluetoothHealthServiceJni( 6194): classInitNative: succeeds
D/HealthService( 6194): Received start request. Starting profile...
I/bluedroid-qcom( 6194): get_profile_interface health
,I/LGBluetoothHealthServiceJni( 6194): classInitNative: succeeds
D/BluetoothAdapterService( 6194): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25af6abf
I/BluetoothPanServiceJni( 6194): classInitNative(L105): succeeds
D/PanService( 6194): Received start request. Starting profile...
D/BluetoothPanServiceJni( 6194): initializeNative(L110): pan
I/bluedroid-qcom( 6194): get_profile_interface pan
I/wpa_supplicant( 6232): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/WifiMonitor( 1032): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=12 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1032): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=13 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1032): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=14 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1032):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 12 0 rt=109182  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1032):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 12 0 rt=109182  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1032):  DisconnectedState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=109183
E/WifiStateMachine( 1032):  ConnectModeState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=109183
E/WifiStateMachine( 1032):  DriverStartedState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=109183
E/WifiStateMachine( 1032):  SupplicantStartedState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=109184
E/WifiStateMachine( 1032):  DefaultState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=109184
E/WifiStateMachine( 1032):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 14 0 rt=109184  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
I/wpa_supplicant( 6232): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1032): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
I/wpa_supplicant( 6232): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=15 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1032): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=16 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1032): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1032): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=17 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1032): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1032): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=18 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,W/libprocessgroup( 1032): failed to open /acct/uid_10019/pid_5505/cgroup.procs: No such file or directory
I/LGBluetoothPanAdapter( 6194): [BTUI] getInstance : create [LGBluetoothPanAdapter]
D/BluetoothAdapterService( 6194): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25af6abf
,I/BtGatt.JNI( 6194): classInitNative(L901): classInitNative: Success!
D/Tethering( 1032): sendTetherStateChangedBroadcast 1, 0, 0
W/Settings( 1032): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1032): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1032): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/StatusBar.NetworkController( 1463): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1463): mWifiConnected = false, mWifiLevel = 0
,E/WifiStateMachine( 1032):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 14 0 rt=109291  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
W/Settings( 1032): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1032): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1032): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/BtGatt.DebugUtils( 6194): handleDebugAction() action=null
D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiServerServiceExt( 1032): SUPPLICANT_STATE_CHANGED_ACTION
D/BtGatt.GattService( 6194): Received start request. Starting profile...
D/WifiServerServiceExt( 1032): setSupplicantStateASSOCIATED
D/BtGatt.GattService( 6194): start()
I/bluedroid-qcom( 6194): get_profile_interface gatt
I/StatusBar.NetworkController( 1463): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1463): mWifiConnected = false, mWifiLevel = 0
D/BtGatt.AdvertiseManager( 6194): advertise manager created
E/WifiStateMachine( 1032):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 15 0 rt=109301  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
,D/BluetoothAdapterService( 6194): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25af6abf
D/BluetoothAdapterService( 6194): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25af6abf
I/LGBluetoothMapAdapter( 6194): [BTUI] getInstance : create [LGBluetoothMapAdapter]
D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
V/BluetoothMapService( 6194): BluetoothMapBinder()
E/WifiStateMachine( 1032):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 15 0 rt=109309  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
D/BluetoothMapService( 6194): Received start request. Starting profile...
D/BluetoothMapService( 6194): start()
E/WifiStateMachine( 1032):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=109310
E/WifiStateMachine( 1032):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=109310
D/WifiNative-wlan0( 1032): doString: [STATUS]
D/WifiMonitor( 1032): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1032): WifiMonitor:wlan0 cnt=19 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1032):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
D/BluetoothMapEmailSettingsLoader( 6194): Found 0 applications
D/BluetoothMapEmailAppObserver( 6194): createReceiver()
I/WifiServiceExtension( 1032): setVHTCapabilityType  : false
D/BluetoothMapEmailAppObserver( 6194): initObservers()
D/BluetoothMapEmailAppObserver( 6194): getEnabledAccountItems()
,I/WifiServerServiceExt( 1032): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1032): setKeepAlivePacketInterval msec : 60
D/BluetoothAdapterService( 6194): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25af6abf
W/Settings( 1032): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 6194): Proxy object connected
W/Settings( 1032): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1032): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/LGBluetoothHfpAdapter( 6194): [BTUI] queryPhoneState
D/LGBluetoothHfpAdapter( 6194): Try to query the phonestate on bind
I/StatusBar.NetworkController( 1463): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1463): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1032): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1032): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1032): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/BluetoothPhoneService.BluetoothLTECall( 1840):  call mBluetoothHeadset.phoneStateChanged()
D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
W/BluetoothHeadset( 1840): Proxy not attached to service
D/BluetoothHeadset( 1840): java.lang.Throwable
D/BluetoothHeadset( 1840): 	at android.bluetooth.BluetoothHeadset.phoneStateChanged(BluetoothHeadset.java:826)
D/BluetoothHeadset( 1840): 	at com.android.phone.BluetoothPhoneService$BluetoothLTECall.handleQueryPhoneState(BluetoothPhoneService.java:1527)
D/BluetoothHeadset( 1840): 	at com.android.phone.BluetoothPhoneService$BluetoothLTECall.access$700(BluetoothPhoneService.java:1360)
D/BluetoothHeadset( 1840): 	at com.android.phone.BluetoothPhoneService$1.handleMessage(BluetoothPhoneService.java:268)
D/BluetoothHeadset( 1840): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BluetoothHeadset( 1840): 	at android.os.Looper.loop(Looper.java:135)
D/BluetoothHeadset( 1840): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
D/BluetoothHeadset( 1840): 	at java.lang.reflect.Method.invoke(Native Method)
D/BluetoothHeadset( 1840): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/BluetoothHeadset( 1840): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
D/BluetoothHeadset( 1840): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
I/StatusBar.NetworkController( 1463): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1463): mWifiConnected = false, mWifiLevel = 0
D/BluetoothAdapterService( 6194): Profile still not running:com.android.bluetooth.gatt.GattService
D/HeadsetStateMachine( 6194): Disconnected process message: 10, size: 0
V/BluetoothPbapReceiver( 6194): PbapReceiver onReceive 
,V/BluetoothPbapReceiver( 6194): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
V/BluetoothPbapReceiver( 6194): ***********state = 11
D/HeadsetPhoneState( 6194): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 6194): Disconnected process message: 11, size: 0
V/AlarmManager( 1032): RTC_WAKEUP set : Alarm{26e27991 type 0 when 1454935055800 com.android.vending} when 1454935055800
D/BluetoothAdapterService( 6194): Profile still not running:com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 6194): Profile still not running:com.android.bluetooth.gatt.GattService
D/ConnectivityService( 1032): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService( 1032): Got NetworkAgent Messenger
E/WifiConfigStore( 1032): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService( 1032): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1032): NetworkAgent connected
,D/WifiNative-wlan0( 1032): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1032): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1032): doBoolean: SAVE_CONFIG
D/BluetoothAdapterService( 6194): Profile still not running:com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 6194): Profile still not running:com.android.bluetooth.gatt.GattService
V/PanService( 6194): [BTUI] SIM Extra State :ABSENT
D/BluetoothAdapterService( 6194): Profile still not running:com.android.bluetooth.map.BluetoothMapService
V/BluetoothMapService( 6194): Handler(): got msg=1
D/BluetoothAdapterState( 6194): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid-qcom( 6194): enable
I/GKI_LINUX( 6194): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 6194): btu_task pending for preload complete event
I/bt_hci_bdroid( 6194): init
,D/PCSuite ( 6287): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/bt_vendor( 6194): bt-vendor : init
I/bt_vendor( 6194): bt-vendor : get_bt_soc_type
E/bt_vendor( 6194): get_bt_soc_type: Failed to get soc type
I/bt_vendor( 6194): init: Local BD Address : c0:64:73:54:3f:58
D/bt_userial_mct( 6194): userial_init
D/bt_hci_bdroid( 6194): set_power 1
I/bt_vendor( 6194): bt-vendor : BT_VND_OP_POWER_CTRL: On
I/bt_vendor( 6194): Starting hciattach daemon
I/bt_vendor( 6194): try to set true
,I/ActivityManager( 1032): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6318 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
D/WifiNative-wlan0( 1032): SAVE_CONFIG: returned true
E/WifiConfigStore( 1032): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1032): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1032): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1032): doBoolean: SAVE_CONFIG
W/sh      ( 6327): type=1400 audit(0.0:157): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/sh      ( 6327): type=1400 audit(0.0:158): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/WifiNative-wlan0( 1032): SAVE_CONFIG: returned true
D/CommandListener(  323): Setting iface cfg
E/WifiStateMachine( 1032): Start Dhcp Watchdog 1
,E/WifiStateMachine( 1032):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=109386  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1032):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=109386  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
I/qcom-bluetooth( 6332): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
E/WifiStateMachine( 1032):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=109387  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1032):  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1032):  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1032):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1032):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1032):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1032):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/DhcpStateMachine( 1032): StoppedState
D/DhcpStateMachine( 1032): StoppedState{ when=-4ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1032): WaitBeforeStartState
D/WifiServerServiceExt( 1032): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1032): setSupplicantStateFOUR_WAY_HANDSHAKE
D/WifiServerServiceExt( 1032): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1032): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1032):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=109390  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1032):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=109390  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1032):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=109391  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1032):  ObtainingIpState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:-1058856667] from screen [on:0 period:-1058856667]
E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1058856666]
I/WifiNative-HAL( 1032): startHal
E/wifi    ( 1032): getStaticLongField sWifiHalHandle 0x9894c8bc
E/WifiHAL ( 1032): Could not connect handle
D/wifi    ( 1032): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x401f3e
I/WifiNative-HAL( 1032): Could not start hal
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1032): updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
E/WifiStateMachine( 1032):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1032):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1032):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1032):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1032):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1032):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1032): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
D/WifiServerServiceExt( 1032): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1032): setSupplicantStateCOMPLETED
V/WiFiOffLoadBroadcast( 6226): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,E/WifiStateMachine( 1032):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
E/WifiStateMachine( 1032):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
D/WifiNative-wlan0( 1032): doBoolean: DRIVER SETSUSPENDMODE 0
D/WifiService( 1032): New client listening to asynchronous messages
,I/qcom-bluetooth( 6346): /system/etc/init.qcom.bt.sh: Transport : smd 
V/SIM_STK ( 1032): Menu title from STK is T-Mobile
I/qcom-bluetooth( 6347): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
I/wpa_supplicant( 6232): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/LgDataFeature( 6226): LgDataFeature() Constructor: none
D/LgDataFeature( 6226): LgDataFeature() Constructor Done, null
,D/WifiNative-wlan0( 1032): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1032): doBoolean: SET ps 0
D/WifiNative-wlan0( 1032): SET ps 0: returned true
D/WifiNative-wlan0( 1032): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 6232): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1032): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1032): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1032): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1032): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
V/LgDhcpStateMachineHelper( 1032): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700" is not exist.
D/LGWifiP2pService( 1032): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@32814300 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@32814300 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1032): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1032): DHCP Start wake lock is acquired.
D/WifiServerServiceExt( 1032): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1032): setSupplicantStateCOMPLETED
I/qcom-bluetooth( 6349): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
D/WiFiOffLoadUpdatePriority( 6226): remove : truetruetrue
,I/qcom-bluetooth( 6350): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
E/WifiStateMachine( 1032):  ObtainingIpState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1032):  L2ConnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1032):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
I/qcom-bluetooth( 6351): /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
E/WifiStateMachine( 1032):  ObtainingIpState CMD_SAVE_CONFIG uid=1000 0 0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_SAVE_CONFIG uid=1000 0 0
E/WifiStateMachine( 1032):  ConnectModeState CMD_SAVE_CONFIG uid=1000 0 0
D/WifiNative-wlan0( 1032): doBoolean: SAVE_CONFIG
I/qcom-bluetooth( 6353): /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
E/ActivityThread( 6318): Failed to find provider info for com.lge.lgaccount.provider
W/LG Account v2.2( 6318): No ProfileInfo entries
I/LG Account v2.2( 6318): isEnabled: false
D/WifiNative-wlan0( 1032): SAVE_CONFIG: returned true
I/Feature ( 6318): [Lifetracker]ver: 4.21.112(40211120)
D/WiFiOffLoadUpdatePriority( 6226): remove1
I/Feature ( 6318): [Lifetracker]Country: EU
I/Feature ( 6318): [Lifetracker]Operator: OPEN
V/WiFiOffLoadSharedPrefsUtils( 6226): save remove
I/Feature ( 6318): [Lifetracker]Ranking support: false
I/Feature ( 6318): [Lifetracker]Comfort support: false
I/Feature ( 6318): [Lifetracker]Accessory: true
I/Feature ( 6318): [Lifetracker]Health device: true
I/Feature ( 6318): [Lifetracker]Extra Pedometer: false
I/Feature ( 6318): [Lifetracker]Blood glucose device: false
I/Feature ( 6318): [Lifetracker]Device Number: 3
I/libmdmdetect( 6357): ESOC framework not supported
,E/Diag_Lib( 6357):  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
D/WiFiOffLoadBroadcast( 6226): mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
D/WiFiOffLoadBroadcast( 6226): S: false, R: false
E/WifiStateMachine( 1032):  ObtainingIpState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1032):  L2ConnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1032):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/WiFiOffLoadUpdatePriority( 6226): saved SSID: "NG700"
D/WiFiOffLoadUpdatePriority( 6226): connected SSID: null
D/WiFiOffLoadUpdatePriority( 6226): private wpa: "NG700" 300
D/WifiServiceImplEx( 1032): addOrUpdateNetwork pid=6226, uid=1000, packageName=android.uid.system:1000
E/addOrUpdateNetwork( 1032):  uid = 1000 SSID "NG700" nid=0
,E/WifiStateMachine( 1032):  ObtainingIpState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=2 any is current
E/WifiStateMachine( 1032):  L2ConnectedState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=2 any is current
E/WifiStateMachine( 1032):  ConnectModeState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=2 any is current
E/WifiConfigStore( 1032):  key="NG700"WPA_PSK netId=0 uid=0/1000
D/WifiServerServiceExt( 1032): addOrUpdateNetwork: mThisIsFirstEnableing = false
D/WifiNative-wlan0( 1032): doBoolean: SET_NETWORK 0 ssid 4e47373030
D/bthci_qcomm_linux( 6357): [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:64:C0)
D/bthci_qcomm_common( 6357): [BTUI] bt_hci_qcomm_init:
D/bthci_qcomm_common( 6357): [BTUI]     BDADDR: 58:3F:54:73:64:C0
D/bthci_qcomm_common( 6357): [BTUI]     BR/EDR: Class 1
D/bthci_qcomm_common( 6357): [BTUI]     LE: Class 2
D/bthci_qcomm_common( 6357): [BTUI]     Ref Clock: 32M
D/btqsocnvmtags( 6357): [BTUI] init_riva_entries: set NORMAL power settings
D/WifiNative-wlan0( 1032): SET_NETWORK 0 ssid 4e47373030: returned true
E/WifiConfigStore( 1032): Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1032): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1032): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1032): doBoolean: SET_NETWORK 0 key_mgmt WPA-PSK
D/WifiNative-wlan0( 1032): SET_NETWORK 0 key_mgmt WPA-PSK: returned true
D/WifiNative-wlan0( 1032): doBoolean: SET_NETWORK 0 proto WPA RSN
,D/WifiNative-wlan0( 1032): SET_NETWORK 0 proto WPA RSN: returned true
D/WifiNative-wlan0( 1032): doBoolean: SET_NETWORK 0 pairwise TKIP CCMP
D/WifiNative-wlan0( 1032): SET_NETWORK 0 pairwise TKIP CCMP: returned true
D/WifiNative-wlan0( 1032): doBoolean: SET_NETWORK 0 group WEP40 WEP104 TKIP CCMP
D/WifiNative-wlan0( 1032): SET_NETWORK 0 group WEP40 WEP104 TKIP CCMP: returned true
D/WifiNative-wlan0( 1032): doBoolean: SET_NETWORK 0 priority 300
D/WifiNative-wlan0( 1032): SET_NETWORK 0 priority 300: returned true
E/WifiConfigStore( 1032): will read network variables netId=0
E/WifiConfigStore( 1032): writeIpAndProxyConfigurationsOnChange: "NG700" -> "NG700" path: /data/misc/wifi/ipconfig.txt
E/WifiConfigStore( 1032):  writeKnownNetworkHistory() num networks:1 needWrite=false
D/WiFiOffLoadUpdatePriority( 6226):  ssid "NG700" prio 300
D/WiFiOffLoadUpdatePriority( 6226): configuration updated: 0
E/WifiStateMachine( 1032):  ObtainingIpState CMD_SAVE_CONFIG uid=1000 0 0
E/WifiStateMachine( 1032):  L2ConnectedState CMD_SAVE_CONFIG uid=1000 0 0
E/WifiStateMachine( 1032):  ConnectModeState CMD_SAVE_CONFIG uid=1000 0 0
D/WifiNative-wlan0( 1032): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1032): SAVE_CONFIG: returned true
,D/WiFiOffLoadUpdatePriority( 6226): configuration saved: true
D/BluetoothPermissionRequest( 6226): onReceive
D/LGBluetoothFeatureConfig( 6226):  get() - isFeatureLoaded : false
,D/BluetoothManagerService( 1032): Message: 20
D/BluetoothManagerService( 1032): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@23378f2c:true
D/LGBluetoothResetSettingReceiver( 6226): return without doing reset settings.
,I/ActivityManager( 1032): Killing 5872:com.lge.email/u0a23 (adj 15): empty #17
,I/rmt_storage(  318): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  318): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  318): wakelock acquired: 1, error no: 42
,I/rmt_storage(  318): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
D/DhcpStateMachine( 1032): DHCPV4 request on wlan0
,V/LgDhcpStateMachineHelper( 1032): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1032): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
D/LGBluetoothOppAdapter( 6194): [BTUI] getInstance : create [LGBluetoothOppAdapter]
,W/libprocessgroup( 1032): failed to open /acct/uid_10023/pid_5872/cgroup.procs: No such file or directory
V/GLSActivity( 2041): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/rmt_storage(  318): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  318): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  318): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 22
I/rmt_storage(  318): 
I/rmt_storage(  318): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
W/dhcpcd  ( 6361): type=1400 audit(0.0:159): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
E/Diag_Lib(  902): [IMS_FATAL]| 3347 | 909 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
,W/dhcpcd  ( 6361): type=1400 audit(0.0:160): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/UsbSettingsReceiver( 6226): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,D/UsbSettingsReceiver( 6226): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6226): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6226): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6226): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 6226): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6226): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6226): [AUTORUN] onReceive() : activeList=[]
V/BluetoothFtpReceiver( 6194): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
D/UsbSettingsReceiver( 6226): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6226): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6226): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 6226): [AUTORUN] setTetherStatus() : status=false
V/BluetoothSapReceiver( 6194): [BTUI] checkServiceStart
I/dhcpcd  ( 6361): version 5.5.6 starting
V/BluetoothSapReceiver( 6194): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 6194): SapReceiver onReceive 
V/BluetoothSapReceiver( 6194): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6194):  Bluetooth Adapter state = 11
E/dhcpcd  ( 6361): get_duid: m
D/dhcpcd  ( 6361): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 6361): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
I/ActivityManager( 1032): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6365 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,D/PCSuite ( 6287): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6226): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,D/WiFiOffLoadBroadcast( 6226): MCCMNC not supported: null
I/GLSUser ( 2041): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2041): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2041): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2041): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
W/FormManager( 6266): Network not available. Please check & try again.
V/GLSActivity( 2041): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LGDMClient( 3976): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 3976): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 3976): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/FormManager( 6266): Network unavailable.
W/ContextImpl( 3976): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/FormManager( 6266): Network unavailable.
,D/Finsky  ( 5610): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 5610): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 5610): [1] 5.onFinished: Scheduling replication attempt 2.
,W/ResourcesManager( 6365): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/dhcpcd  ( 6361): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 6361): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 6361): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 6361): wlan0: discarding expired lease
I/dhcpcd  ( 6361): wlan0: broadcasting for a lease
D/dhcpcd  ( 6361): wlan0: sending DISCOVER (xid 0x2813ab1), next in 4.88 seconds
D/PostponalbeReceiver( 5160): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/ActivityManager( 1032): Killing 5528:com.android.gallery3d/u0a27 (adj 15): empty #17
I/PCSuite ( 6287): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6287): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6287): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,D/LGDMClient( 3976): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/LGDMClient( 3976): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 3976): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/AuthorizationBluetoothService( 2041): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/libprocessgroup( 1032): failed to open /acct/uid_10027/pid_5528/cgroup.procs: No such file or directory
V/WiFiOffLoadBroadcast( 6226): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6226): MCCMNC not supported: null
D/QRemote ( 6034): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6034): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6034): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,V/[BNRBootReceiver]( 6004): boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/BNRAndroBeam( 6004): [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,V/[BNRBootReceiver]( 6004): Boot Receiver Return
D/PostponalbeReceiver( 5160): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6226): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6226): MCCMNC not supported: null
D/QRemote ( 6034): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6034): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6034): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/WiFiOffLoadBroadcast( 6226): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,D/WiFiOffLoadBroadcast( 6226): Not supported operator for automatic switch
D/PostponalbeReceiver( 5160): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6226): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6226): MCCMNC not supported: null
D/QRemote ( 6034): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6034): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6034): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 5160): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6226): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6226): MCCMNC not supported: null
D/QRemote ( 6034): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6034): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6034): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 5160): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6226): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6226): MCCMNC not supported: null
D/QRemote ( 6034): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6034): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6034): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 5160): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6226): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6226): MCCMNC not supported: null
D/QRemote ( 6034): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6034): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6034): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 5160): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6226): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6226): MCCMNC not supported: null
D/QRemote ( 6034): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6034): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6034): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 5160): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6226): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6226): MCCMNC not supported: null
D/QRemote ( 6034): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6034): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6034): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,V/QRemote ( 6034): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
D/QRemote ( 6034): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:8839
I/ActivityManager( 1032): Killing 5554:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
W/ContextImpl( 4201): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,E/WifiStateMachine( 1032):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1032):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1032):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1032):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1032):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1032):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1032): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
,W/libprocessgroup( 1032): failed to open /acct/uid_10080/pid_5554/cgroup.procs: No such file or directory
,E/QC-QMI  ( 6357): qmi_client [6357] 13: failed to locate client data
,E/QC-QMI  (  469): qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
E/QC-QMI  (  469): QMUX qmux_client_id=13 not found in qmux client list, unable to remove
I/qcom-bluetooth( 6405): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:64:c0 
,I/qcom-bluetooth( 6406): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
I/bt_vendor( 6194): bluetooth satus is on
D/bt_hci_bdroid( 6194): preload
D/bt_userial_mct( 6194): userial_open(port:0)
I/bt_vendor( 6194): bt-vendor : BT_VND_OP_USERIAL_OPEN
I/bt_vendor( 6194): Done intiailizing UART
I/bt_vendor( 6194): Done intiailizing UART
I/bt_userial_mct( 6194): CMD=66, EVT=66, ACL_Out=67, ACL_In=67
I/bt_vendor( 6194): Bluetooth Firmware and transport layer are initialized
D/bt_userial_mct( 6194): Entering userial_read_thread()
I/bt-btu  ( 6194): btu_task received preload complete event
,W/bt-l2cap( 6194): L2CAP - L2CA_Register() called for PSM: 0x0001
W/bt-l2cap( 6194): L2CAP - L2CA_Register() called for PSM: 0x001f
W/bt-l2cap( 6194): L2CAP - L2CA_Register() called for PSM: 0x0003
I/        ( 6194): BTE_InitTraceLevels -- TRC_HCI
I/        ( 6194): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 6194): BTE_InitTraceLevels -- TRC_RFCOMM
,I/        ( 6194): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 6194): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 6194): BTE_InitTraceLevels -- TRC_A2D
I/        ( 6194): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 6194): BTE_InitTraceLevels -- TRC_BTM
I/        ( 6194): BTE_InitTraceLevels -- TRC_HID_HOST
I/        ( 6194): BTE_InitTraceLevels -- TRC_GAP
I/        ( 6194): BTE_InitTraceLevels -- TRC_PAN
I/        ( 6194): BTE_InitTraceLevels -- TRC_SDP
I/        ( 6194): BTE_InitTraceLevels -- TRC_GATT
I/        ( 6194): BTE_InitTraceLevels -- TRC_SMP
I/        ( 6194): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 6194): BTE_InitTraceLevels -- TRC_BTIF
W/bt-btm  ( 6194): btm_decode_ext_features_page Secure conn Controller support Enabled
E/bt-btm  ( 6194): BTM_SecRegister:p_cb_info->p_le_callback == 0xa01ce061 
E/bt-btm  ( 6194): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01ce061 
E/bt-btif ( 6194): Calling BTA_HhEnable
E/bt-btif ( 6194): btif_storage_get_adapter_property service_mask:0x2140040
D/BluetoothAdapterProperties( 6194): Address is:58:3F:54:73:64:C0
W/bt-l2cap( 6194): L2CAP - L2CA_Register() called for PSM: 0x0019
W/bt-l2cap( 6194): L2CAP - L2CA_Register() called for PSM: 0x0017
W/bt-l2cap( 6194): L2CAP - L2CA_Register() called for PSM: 0x001b
W/bt-l2cap( 6194): L2CAP - L2CA_Register() called for PSM: 0x0011
W/bt-l2cap( 6194): L2CAP - L2CA_Register() called for PSM: 0x0013
,D/BluetoothManagerService( 1032): Bluetooth Adapter name changed to G3-1
D/BluetoothManagerService( 1032): Stored Bluetooth name: G3-1
D/BluetoothAdapterProperties( 6194): Name is: G3-1
D/BluetoothAdapterProperties( 6194): Scan Mode:20
D/BluetoothAdapterProperties( 6194): Discoverable Timeout:120
D/bt_hci_bdroid( 6194): postload
D/bt_hci_bdroid( 6194): Used up Tx Cmd credits
D/bt_hci_bdroid( 6194): Used up Tx Cmd credits
D/bt_hci_bdroid( 6194): Used up Tx Cmd credits
D/bt_hci_bdroid( 6194): Used up Tx Cmd credits
E/bt_mct  ( 6194): hci lib postload completed
W/bt-l2cap( 6194): L2CAP - L2CA_Register() called for PSM: 0x000f
D/bte_conf( 6194): Device ID record 1 : primary
D/bte_conf( 6194):   vendorId            = 00c4
D/bte_conf( 6194):   vendorIdSource      = 0001
D/bte_conf( 6194):   product             = 13a1
,D/bte_conf( 6194):   version             = 1000
D/bte_conf( 6194):   clientExecutableURL = 
D/bte_conf( 6194):   serviceDescription  = 
D/bte_conf( 6194):   documentationURL    = 
D/bte_conf( 6194): bte_load_did_conf no section named DID2.
W/bt-smp  ( 6194): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6194): Plain text(LSB ~ MSB) = 37 d3 50 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6194): Encrypted text(LSB ~ MSB) = 4b df 02 47 96 8d 77 0c d6 e3 72 68 93 b2 cd 0b 
W/bt-btm  ( 6194): Stopping oneshot timer
,D/BluetoothAdapterState( 6194): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
,D/BluetoothAdapterProperties( 6194): ScanMode =  20
D/BluetoothAdapterProperties( 6194): State =  11
D/BluetoothAdapterProperties( 6194): mDiscoverableTimeout = 120
V/LGBluetoothServiceAdapter( 6194): [BTUI] state:11, scanmode:20, timeout:120
D/BluetoothAdapterProperties( 6194): Setting state to 12
I/BluetoothAdapterState( 6194): Bluetooth adapter state changed: 11-> 12
D/BluetoothPanServiceJni( 6194): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/btif_config_util( 6194): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
W/sh      ( 6413): type=1400 audit(0.0:161): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/sh      ( 6413): type=1400 audit(0.0:162): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,W/bt-smp  ( 6194): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6194): Plain text(LSB ~ MSB) = 85 d4 63 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6194): Encrypted text(LSB ~ MSB) = 0f 04 3d 21 c3 17 dd 39 65 69 fb 0e 25 4a 8f db 
W/bt-btm  ( 6194): Stopping oneshot timer
D/BluetoothManagerService( 1032): Message: 60
D/BluetoothManagerService( 1032): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService( 1032): Broadcasting onBluetoothStateChange(true) to 5 receivers.
,I/BluetoothAdapterState( 6194): Entering On State
D/BluetoothHeadset( 1840): onBluetoothStateChange: up=true
W/bt-smp  ( 6194): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6194): Plain text(LSB ~ MSB) = 5c ea 46 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6194): Encrypted text(LSB ~ MSB) = 5b 3c 78 bc c3 e1 db ee df ef 3c a2 8e e8 7c bc 
W/bt-btm  ( 6194): Stopping oneshot timer
D/BluetoothHeadset( 1032): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1840): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1840): onBluetoothStateChange: up=true
D/BluetoothA2dp( 1032): onBluetoothStateChange: up=true
W/bt-smp  ( 6194): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6194): Plain text(LSB ~ MSB) = e3 96 54 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6194): Encrypted text(LSB ~ MSB) = 5d b9 27 57 a5 78 93 7d 43 da 06 de 72 21 97 72 
W/bt-btm  ( 6194): Stopping oneshot timer
D/LGBluetoothServiceAdapter( 6194): [BTUI] OnState
D/LGBluetoothServiceAdapter( 6194): [BTUI]         global_name: G3-1
,D/LGBluetoothServiceAdapter( 6194): [BTUI]         local_name: G3-1
D/BluetoothAdapterService( 6194): [BTUI] autoConnect() : not allowed
W/bt-smp  ( 6194): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6194): Plain text(LSB ~ MSB) = 6d cc 5b 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6194): Encrypted text(LSB ~ MSB) = 57 a5 36 e2 e6 35 71 48 cd 2c c9 4b d6 23 a7 e0 
W/bt-btm  ( 6194): Stopping oneshot timer
E/BluetoothManagerService( 1032): Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
D/BluetoothManagerService( 1032): Bluetooth State Change Intent: 11 -> 12
D/BluetoothManagerService( 1032): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,D/BluetoothAdapterProperties( 6194): Discoverable Timeout:120
D/LGBluetoothDeviceModeControllManager( 6194): adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
I/qcom-bt-wlan-coex( 6419): /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,D/BluetoothManagerService( 1032): Message: 40
D/BluetoothManagerService( 1032): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
D/LGBluetoothAPIService( 1928): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
I/[SystemUI]BluetoothHandler( 1463): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
D/LGBluetoothAPIService( 1928): Message: 1
D/LGBluetoothAPIService( 1928): MESSAGE_BOOT_COMPLETED
I/BluetoothMapService( 6194): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 6194): STATE_ON
D/LGBluetoothDeviceModeControllManager( 6194): [BTUI] checkDeviceModeAndSet, sinkMode : false
,I/LGBluetoothAPIService( 1928): [BTUI] LGBluetoothAPIService Binding Success
D/BluetoothAdapterService( 6194): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25af6abf
V/BluetoothPbapService( 6194): Pbap Service onCreate
V/BluetoothPbapService( 6194): Starting PBAP service
,D/LGBluetoothPbapAdapter( 6194): [BTUI] getInstance : create
V/BluetoothPbapService( 6194): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 6194): state: 12
V/BluetoothMapService( 6194): Handler(): got msg=1
D/BluetoothMapMasInstance( 6194): Map Service startRfcommSocketListener
D/BluetoothMapMasInstance( 6194): MAS initSocket()
D/BluetoothMapMasInstance( 6194):   masId = 00
D/BluetoothMapMasInstance( 6194):   msgTypes = 0e
D/BluetoothMapMasInstance( 6194):   masName = SMS/MMS
D/BluetoothMapMasInstance( 6194):   SDP string = 000eSMS/MMS
D/BluetoothManagerService( 1032): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6194): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 6194): [BTUI] createSocketChannel FD=73 mFd=0
D/BluetoothAdapterProperties( 6194): Scan Mode:21
D/LGBluetoothDeviceModeControllManager( 6194): getDeviceMode  deviceMode 0
V/BluetoothMapMasInstance( 6194): Succeed to create listening socket 
D/BluetoothMapMasInstance( 6194): Accepting socket connection...
W/ContextImpl( 6226): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,D/LGBluetoothAPIServer( 6194): [BTUI] onCreate()
D/LGBluetoothAPIServer( 6194): [BTUI] onBind()
D/LGBluetoothAPIService( 1928): [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
D/LGBluetoothAPIService( 1928): Message: 100
V/BluetoothPbapService( 6194): Handler(): got msg=1
D/LGBluetoothAPIService( 1928): MESSAGE_BLUETOOTH_SERVICE_CONNECTED
V/BluetoothPbapService( 6194): Pbap Service startRfcommSocketListener
V/BluetoothPbapReceiver( 6194): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 6194): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6194): ***********state = 12
V/BluetoothPbapService( 6194): Pbap Service initSocket
,D/BluetoothManagerService( 1032): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6194): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 6194): [BTUI] createSocketChannel FD=75 mFd=73
V/BluetoothPbapService( 6194): Succeed to create listening socket 
V/BluetoothPbapService( 6194): Accepting socket connection...
D/LocalBluetoothProfileManager( 6226): Adding local A2DP profile
D/BluetoothManagerService( 1032): Message: 30
D/LocalBluetoothProfileManager( 6226): Adding local HEADSET profile
D/BluetoothManagerService( 1032): Message: 30
D/BluetoothManagerService( 1032): Message: 30
,D/BluetoothManagerService( 1032): Message: 30
D/LocalBluetoothProfileManager( 6226): Adding local MAP profile
D/BluetoothMap( 6226): Create BluetoothMap proxy object
D/BluetoothManagerService( 1032): Message: 30
D/BluetoothManagerService( 1032): Message: 30
,D/LocalBluetoothProfileManager( 6226): LocalBluetoothProfileManager construction complete
V/BluetoothPbapService( 6194): Pbap Service onBind
D/LGBluetoothUserBindClient( 6226): [BTUI] initUserBindClient
W/ContextImpl( 6226): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
D/DockEventReceiver( 6226): finishStartingService: stopping service
,D/BluetoothA2dp( 6226): Proxy object connected
D/A2dpProfile( 6226): Bluetooth service connected
D/BluetoothHeadset( 6226): Proxy object connected
D/HeadsetProfile( 6226): Bluetooth service connected
D/BluetoothInputDevice( 6226): Proxy object connected
D/HidProfile( 6226): Bluetooth service connected
D/BluetoothPan( 6226): BluetoothPAN Proxy object connected
D/PanProfile( 6226): Bluetooth service connected
D/BluetoothMap( 6226): Proxy object connected
,D/MapProfile( 6226): Bluetooth service connected
D/BluetoothMap( 6226): getConnectedDevices()
V/BluetoothMapService( 6194): getConnectedDevices()
D/BluetoothPbap( 6226): Proxy object connected
D/PbapServerProfile( 6226): Bluetooth service connected
D/LGBluetoothUserBindClient( 6226): [BTUI] onServiceConnected
D/BluetoothPermissionRequest( 6226): onReceive
D/LGBluetoothFeatureConfig( 6226): isPrivacyLogsEnabled : true
D/LGBluetoothUtils( 6226): [BTUI] FileNotFound: readProperty
D/LGBluetoothResetSettingReceiver( 6226): return without doing reset settings.
V/BluetoothOppReceiver( 6194): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,I/LGBluetoothOppAdapter( 6194): [BTUI] startOppService()
V/BluetoothOppManager( 6194): restoreApplicationData! falsefalsenullnull
D/LGBluetoothFeatureConfig( 6194): isPrivacyLogsEnabled : true
V/BtOppService( 6194): onCreate
,V/BluetoothOppNotification( 6194): send message
V/BtOppService( 6194): Starting RfcommListener
D/BluetoothOppPreference( 6194): Dumping Names:  
D/BluetoothOppPreference( 6194): {}
D/BluetoothOppPreference( 6194): Dumping Channels:  
D/BluetoothOppPreference( 6194): {}
V/BtOppService( 6194): onStartCommand
,V/BtOppService( 6194): pendingUpdate is true keepUpdateThread is false sListenStarted is true
,V/BluetoothFtpReceiver( 6194): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpReceiver( 6194): BluetoothFtpReceiver Start Service
V/BluetoothOppNotification( 6194): new notify threadi!
V/BluetoothOppNotification( 6194): send delay message
V/BtOppService( 6194): start RfcommListener
V/BtOppService( 6194): Deleted complete outbound shares, number =  0
V/BtOppService( 6194): RfcommListener started
V/BtOppRfcommListener( 6194): Starting RFCOMM listener....
D/BluetoothManagerService( 1032): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
V/BtOppService( 6194): Deleted complete inbound failed shares, number = 0
W/BluetoothAdapter( 6194): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 6194): [BTUI] createSocketChannel FD=78 mFd=75
V/BtOppRfcommListener( 6194): Started RFCOMM listener....
,I/BtOppRfcommListener( 6194): Accept thread started.
V/BtOppRfcommListener( 6194): Accepting connection...
V/BluetoothOppProvider( 6194): starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6194): created cursor android.database.sqlite.SQLiteCursor@2aa6aba1 on behalf of 
V/BluetoothOppProvider( 6194): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6194): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6194): created cursor android.database.sqlite.SQLiteCursor@10c851c6 on behalf of 
V/BluetoothOppProvider( 6194): created cursor android.database.sqlite.SQLiteCursor@33595587 on behalf of 
V/BluetoothOppNotification( 6194): mUpdateCompleteNotification = true
V/BtOppService( 6194): pendingUpdate is true keepUpdateThread is false sListenStarted is true
V/BluetoothOppProvider( 6194): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6194): created cursor android.database.sqlite.SQLiteCursor@282bcb4 on behalf of 
V/BluetoothOppNotification( 6194): update too frequent, put in queue
V/BluetoothOppProvider( 6194): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,V/BluetoothOppProvider( 6194): created cursor android.database.sqlite.SQLiteCursor@e6160dd on behalf of 
,V/BluetoothOppNotification( 6194): outbound: succ-0  fail-0
V/BtOppService( 6194): pendingUpdate is false keepUpdateThread is false sListenStarted is true
V/BluetoothOppNotification( 6194): outbound notification was removed.
V/BluetoothOppProvider( 6194): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
D/BluetoothAdapterService( 6194): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25af6abf
V/BluetoothFtpService( 6194): Ftp Service onCreate
I/BluetoothFtpService( 6194): Ftp Service onCreate
V/BluetoothFtpService( 6194): Ftp Service onStartCommand
V/BluetoothFtpService( 6194): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpService( 6194): Starting Listening on sockets
V/BluetoothOppProvider( 6194): created cursor android.database.sqlite.SQLiteCursor@13ebc323 on behalf of 
V/BluetoothSapReceiver( 6194): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 6194): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 6194): SapReceiver onReceive 
V/BluetoothSapReceiver( 6194): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6194):  Bluetooth Adapter state = 12
V/BluetoothSapReceiver( 6194): Calling SAP service start service with action = null
V/BluetoothOppNotification( 6194): inbound: succ-0  fail-0
V/BtOppService( 6194): ContentObserver received notification
V/BtOppService( 6194): ContentObserver received notification
V/BluetoothFtpService( 6194): Handler(): got msg=1
V/BtOppService( 6194): pendingUpdate is true keepUpdateThread is false sListenStarted is true
V/BluetoothOppProvider( 6194): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
V/BluetoothFtpService( 6194): Ftp Service startRfcommSocketListener
V/BluetoothFtpService( 6194): Ftp Service initSocket
,D/BluetoothManagerService( 1032): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
V/BluetoothOppProvider( 6194): created cursor android.database.sqlite.SQLiteCursor@20e8f020 on behalf of 
V/BluetoothOppNotification( 6194): inbound notification was removed.
V/BluetoothOppProvider( 6194): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
W/BluetoothAdapter( 6194): getBluetoothService() called with no BluetoothManagerCallback
V/BluetoothOppNotification( 6194): update too frequent, put in queue
V/BluetoothOppProvider( 6194): created cursor android.database.sqlite.SQLiteCursor@15182dd9 on behalf of 
V/BtOppService( 6194): pendingUpdate is false keepUpdateThread is false sListenStarted is true
D/AuthorizationBluetoothService( 2041): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/LGBluetoothServiceAdapter( 6194): [BTUI] createSocketChannel FD=80 mFd=78
V/BluetoothFtpService( 6194): Succeed to create listening socket on channel 20
V/BluetoothFtpService:RfcommSocketAcceptThread( 6194): Run Accept thread
,D/BluetoothAdapterService( 6194): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25af6abf
V/BluetoothSapService( 6194): Sap Service onCreate
V/BluetoothSapService( 6194): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 6194): state: 12
,V/BluetoothSapService( 6194): Starting SAP server process
V/BluetoothSapService( 6194): SAP Service startRfcommListenerThread
,V/BluetoothSapService( 6194): Sap Service initRfcommSocket
D/BluetoothManagerService( 1032): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6194): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 6194): [BTUI] createSocketChannel FD=82 mFd=80
V/BluetoothSapService( 6194): Succeed to create listening socket 
V/BluetoothSapService( 6194): Accepting socket connection...
W/sapd    ( 6448): type=1400 audit(0.0:163): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/sapd    ( 6448): type=1400 audit(0.0:164): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
V/BT_SAP  ( 6448): Event pipe created
V/BT_SAP  ( 6448): create_server_socket qcom.sap.server
V/BT_SAP  ( 6448): created socket fd 6
,I/dhcpcd  ( 6361): wlan0: offered 192.168.1.141 from 192.168.1.1
D/dhcpcd  ( 6361): wlan0: sending REQUEST (xid 0x2813ab1), next in 3.51 seconds
,V/BluetoothOppNotification( 6194): new notify threadi!
V/BluetoothOppNotification( 6194): send delay message
,V/BluetoothOppProvider( 6194): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6194): created cursor android.database.sqlite.SQLiteCursor@cd4ce95 on behalf of 
V/BluetoothOppNotification( 6194): mUpdateCompleteNotification = true
V/BluetoothOppProvider( 6194): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 6194): created cursor android.database.sqlite.SQLiteCursor@29cb8baa on behalf of 
V/BluetoothOppNotification( 6194): outbound: succ-0  fail-0
V/BluetoothOppNotification( 6194): outbound notification was removed.
V/BluetoothOppProvider( 6194): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 6194): created cursor android.database.sqlite.SQLiteCursor@3fb4739b on behalf of 
V/BluetoothOppNotification( 6194): inbound: succ-0  fail-0
V/BluetoothOppNotification( 6194): inbound notification was removed.
V/BluetoothOppProvider( 6194): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6194): created cursor android.database.sqlite.SQLiteCursor@1ff0a338 on behalf of 
,E/WifiStateMachine( 1032):  ObtainingIpState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1058853658] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1058853656] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,I/dhcpcd  ( 6361): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
,I/dhcpcd  ( 6361): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 6361): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 6361): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 6361): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 6361): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 6361): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 6361): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 6361): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason BOUND
,E/WifiStateMachine( 1032):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1032):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1032):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1032):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1032):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 1032):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,D/ConnectivityService( 1032): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
D/DhcpStateMachine( 1032): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper( 1032): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1032): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1032): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1032): Add DhcpResults: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
V/DhcpStateMachine( 1032): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1032): bShouldSendDhcpAction Result: true
E/WifiStateMachine( 1032):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine( 1032):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/WifiNative-wlan0( 1032): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 6232): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1032): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1032): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1032): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1032): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 6232): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1032): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1032): doBoolean: SET ps 1
,D/DhcpStateMachine( 1032): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1032): RunningState
D/WifiNative-wlan0( 1032): SET ps 1: returned true
,D/ConnectivityService( 1032): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
E/WifiStateMachine( 1032):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1032):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1032): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1032): ignoring duplicate network state non-change
,I/StatusBar.NetworkController( 1463): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1463): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1032): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1032): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1032): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,D/ConnectivityService( 1032): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService( 1032): Adding iface wlan0 to network 100
W/Settings( 1032): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1032): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1032): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PostponalbeReceiver( 5160): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/StatusBar.NetworkController( 1463): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1463): mWifiConnected = false, mWifiLevel = 0
E/ConnectivityService( 1032): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1032): Adding Route [fe80::/64 -> :: wlan0] to network 100
D/WifiHS20( 1032): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings( 1032): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1032): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1032): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,V/WfdStateTracker( 1928): handleWifiStateChangedEvent: 1
D/WifiHS20( 1032): [PASSPOINT] passpointNotification: hs20AP list is checked
,D/ConnectivityService( 1032): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
W/Settings( 1032): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1032): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1032): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/ConnectivityService( 1032): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1032): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1032): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 100
I/StatusBar.NetworkController( 1463): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1463): mWifiConnected = true, mWifiLevel = 3
D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1032): Setting Dns servers for network 100 to [/192.168.1.1]
E/WifiStateMachine( 1032): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/Nat464Xlat( 1032): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1032): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1032): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1032): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1032):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1032):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1032):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1032):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1032):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1032): currentScore = 0, newScore = 20
D/ConnectivityService( 1032):    accepting network in place of null
D/ConnectivityService( 1032): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WIFI    ( 1032): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1032):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1032): Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1032): DefaultState{ when=-7ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1032): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1032): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/TelephonyNetworkFactory-1( 1840): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1840):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1032): Checking http://clients3.google.com/generate_204 on "NG700"
V/WiFiOffLoadBroadcast( 6226): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/libc-netbsd(  323): res_queryN name = clients3.google.com, class = 1, type = 28
E/ConnectivityService( 1032): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1032): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1032): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1032): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1032): [e] list.add(nai) empty : false size: 1
D/ConnectivityService( 1032): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/LocSvc_java( 1032): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1032): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1032): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1032): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java( 1032): Sending msg: 5 arg1:0 arg2:1
,I/StatusBar.NetworkController( 1463): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1463): mWifiConnected = true, mWifiLevel = 3
D/libc-netbsd(  323): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  323): res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1032): validation of new default Network = false
D/ConnectivityService( 1032): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1032): enableDataServiceNotify 
D/DSQN    ( 1032): start dsqn bin
D/libc-netbsd(  323): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  323): res_queryN name = europe.pool.ntp.org, class = 1, type = 1
D/WiFiOffLoadBroadcast( 6226): MCCMNC not supported: null
D/ConnectivityService( 1032): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1032):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1032):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1032): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1463): CM callback handler got msg 524290
,W/dsqn    ( 6494): type=1400 audit(0.0:165): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 6494): type=1400 audit(0.0:166): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/QRemote ( 6034): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6034): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6034): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 5160): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/DSQN    ( 6494): DSQN ssw
,V/WiFiOffLoadBroadcast( 6226): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/TelephonyIcons( 1463): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
D/libc-netbsd(  323): res_queryN name = clients3.google.com, class = 1, type = 1
D/WiFiOffLoadBroadcast( 6226): MCCMNC not supported: null
D/QRemote ( 6034): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6034): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6034): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/libc-netbsd(  323): res_queryN name = 2.android.pool.ntp.org succeed
D/PostponalbeReceiver( 5160): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6287): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6287): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6226): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6226): MCCMNC not supported: null
D/QRemote ( 6034): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6034): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6034): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,I/QRemote ( 6034): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 6034): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 5160): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/libc-netbsd(  323): res_queryN name = clients3.google.com succeed
I/PCSuite ( 6287): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6287): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6226): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6226): MCCMNC not supported: null
D/QRemote ( 6034): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6034): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6034): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6034): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6034): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/LGDataListener(  323): argv[0]=dsqncommand
D/LGDataListener(  323): argv[1]=wlan0
D/LGDataListener(  323): argv[2]=1
D/LGDataListener(  323): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1032): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1032): start to monitor internet connection
V/NetworkPolicy( 1032): [LG_RESTRICTED] checkMobilePolicy_type()
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1032): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 08 Feb 2016 12:37:40 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454935060416], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454935060391]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1032): Don't send network conditions - lacking user consent.
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1032): Validated
D/ConnectivityService( 1032): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1032): rematching NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService( 1032):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1032):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1032):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1032): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService( 1032): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1032):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1032):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1032): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1032): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1463): CM callback handler got msg 524290
D/ConnectivityService( 1032): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory-1( 1840): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1032): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1840):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/WIFI    ( 1032):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyIcons( 1463): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/jxcore-log( 6138): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 6138): 
,D/libc-netbsd(  323): res_queryN name = europe.pool.ntp.org succeed
,D/LocSvc_java( 1032): NTP server : europe.pool.ntp.org
D/LocSvc_java( 1032): NTP server returned: 1454935060426 (Mon Feb 08 13:37:40 GMT+01:00 2016) reference: 113396 certainty: 33 system time offset: -256
D/LocSvc_java( 1032): Sending msg: 10 arg1:0 arg2:1
,W/ProcessCpuTracker( 1032): Skipping unknown process pid 6480
W/ProcessCpuTracker( 1032): Skipping unknown process pid 6481
W/ProcessCpuTracker( 1032): Skipping unknown process pid 6493
W/ProcessCpuTracker( 1032): Skipping unknown process pid 6495
W/ProcessCpuTracker( 1032): Skipping unknown process pid 6505
,I/jxcore-log( 6138): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 6138): 
,I/jxcore-log( 6138): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 6138): 
,I/jxcore-log( 6138): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 6138): 
I/jxcore-log( 6138): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 6138): 
,I/jxcore-log( 6138): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log( 6138): 
,I/CloudHub( 2140): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19953
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1058850641] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1058850638] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
,V/WifiInternetCheck( 1032): Single check msg out of sync, ignoring.
,D/ConnectivityService( 1032): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1032): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1032): MasterInitialState.processMessage what=3
D/AlarmManagerService( 1032): Setting time of day to sec=1454935063
W/AlarmManagerService( 1032): Unable to set rtc to 1454935063: Invalid argument
D/PostponalbeReceiver( 5160): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 5160): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
D/KeyguardUpdateMonitor( 1463): handleTimeUpdate
I/[SystemUI]Clock( 1463): onReceive = android.intent.action.TIME_SET
,I/SecureClockService( 1928): Intent.ACTION_TIME_CHANGED 
D/LIA_Informant_Tips_DateChangeManager( 2685): onReceive() : ACTION_TIME_CHANGED
I/LgeClockWidgetControlView( 1463): time changed, timezoneChanged : false
I/LIA_Informant_Tips_LogTracer( 2685): [Log Tracer - Schedule Transition] Time Change Event Received : 2016-02-08 13:37:43...... Request
I/LIA_Informant_Tips_LogTracer( 2685): [Log Tracer - Schedule Transition] UserGuide, DATE_UPDATE : working count : 5, total count : 169, new day : false...... Request
D/LIA_Informant_Tips_DateChangeManager( 2685): DateInfo : SmartTips Total Working Day Count = 169
D/LIA_Informant_Tips_DateChangeManager( 2685): DateInfo : UserGuide Working Duration Count = 5
D/LIA_Informant_Tips_DateChangeManager( 2685): DateInfo : Last Date Check Time = 2016-02-08 13:37:43
I/NetworkMonitor( 5239): type=WIFI subType= reason=null isConnected=true
W/ActivityManager( 1032): getTasks: caller 10029 is using old GET_TASKS but privileged; allowing
,I/[LGHome]LGDateChangeReceiver( 2020): [LGDateChangeReceiver.java:78:updateCalendarShortcut()]date=8 currentDate=-1 dayofweek=2 currentDayOfWeek=-1
I/[LGHome]LGCalendarIcon( 2020): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Mon date= 8
I/[LGHome]LGCalendarIcon( 2020): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Mon date= 8
I/[LGHome]Launcher( 2020): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/CalendarProvider2( 6071): onReceive() android.intent.action.TIME_SET
D/CalendarProvider2( 6071): Scheduling check of next Alarm
,I/ActivityManager( 1032): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=6532 uid=10054 gids={50054, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1032): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6550 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/ActivityManager( 1032): Start proc com.android.gallery3d for service com.android.gallery3d/com.lge.gallery.picasa.PicasaService: pid=6567 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
D/[Concierge]Service( 2604): onStartCommand(). Type : 9
I/GoogleURLConnFactory( 2041): Using platform SSLCertificateSocketFactory
,I/AppUp4:AppBoxCP( 6550): onCreate
W/AppUp4:DB( 6550):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6550):  setFingerPrint start
I/AppUp4:DB( 6550):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,W/ResourcesManager( 6567): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6567): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6567): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 6567): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/AppUp4:DB( 6550):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 6550):  SDK version = 21
I/AppUp4:DB( 6550):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6550): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6550): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6550): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6550): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6550): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6550): onReceive
,D/LgDataFeature( 6550): LgDataFeature() Constructor: none
D/LgDataFeature( 6550): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 6550): Context : android.app.ReceiverRestrictedContext@17b118de
D/AppUp4:CustFacade( 6550): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6550): isPhone : true
D/AppUp4:CustModeStarterReceiver( 6550): begin check event
I/AppUp4:CustModeStarterReceiver( 6550): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6550): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
I/AppConfig( 6567): Total System Memory = 2995761152
D/AppUp4:CustModeStarterReceiver( 6550): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6550): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6550): handleAsyncCustNotification do not startCustService
,I/ActivityManager( 1032): Killing 5921:com.google.android.apps.docs/u0a61 (adj 15): empty #17
D/SystemHelper( 6567): region [EU], country [EU], operator [OPEN], sub-operator []
,D/LGDMClient( 3976): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3976): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/libprocessgroup( 1032): failed to open /acct/uid_10061/pid_5921/cgroup.procs: No such file or directory
W/ContextImpl( 3976): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
I/ActivityManager( 1032): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=6591 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ReaderUtils( 6532): PortraitW 1440 LandscapeW 2392 SmallestSize 1340 LargestSize 2392 textZoom 4.4999995 isTablet false Memory 256
W/ContextImpl( 3976): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/LGDMClient( 3976): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,V/DownloadManager( 3323): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,I/LGDMClient( 3976): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 3323): DownloadService onCreate
I/DownloadManager( 3323): in removeSpuriousFiles
V/DownloadManager( 3323): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,D/LGDMClient( 3976): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3976): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 3323): created cursor android.database.sqlite.SQLiteCursor@9851b5 on behalf of 3323
I/DownloadManager( 3323): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3323): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3323): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3323): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3323): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3323): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3323): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3323): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3323): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3323): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3323): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/DownloadManager( 3323): in trimDatabase
V/DownloadManager( 3323): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,I/ActivityManager( 1032): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6617 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
W/ContextImpl( 3976): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
,W/DriveInitializer( 2333): Background init thread started
,D/GpsLocationProvider( 1032): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/art     ( 1032): Explicit concurrent mark sweep GC freed 77182(3MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 44MB/66MB, paused 1.347ms total 92.029ms
V/DownloadManager( 3323): DownloadService onStartCommand
,E/LGDMClient( 3976): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.gms/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 2333): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.gms/files
D/LGDMClient( 3976): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 3976): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3323): created cursor android.database.sqlite.SQLiteCursor@1417d8d8 on behalf of 3323
,V/DownloadManager( 3323): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3323): created cursor android.database.sqlite.SQLiteCursor@21495431 on behalf of 3323
E/GpsLocationProvider( 1032): No APN found to select.
,W/GAV2    ( 6532): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
V/DownloadManager( 3323): processing inserted download 1
V/DownloadManager( 3323): processing inserted download 4
V/DownloadManager( 3323): processing inserted download 7
,V/DownloadManager( 3323): processing inserted download 8
V/DownloadManager( 3323): processing inserted download 9
V/DownloadManager( 3323): processing inserted download 10
V/DownloadManager( 3323): processing inserted download 16
V/DownloadManager( 3323): processing inserted download 17
V/DownloadManager( 3323): processing inserted download 18
V/DownloadManager( 3323): processing inserted download 21
V/DownloadManager( 3323): processing inserted download 22
V/DownloadManager( 3323): DownloadService onDestroy
,I/BooksApp( 6532): Created application version: 3.2.35 (30235)
I/ActivityManager( 1032): Killing 5583:com.google.android.apps.plus/u0a97 (adj 15): empty #17
W/ResourcesManager( 6617): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6617): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6617): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6617): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/ThermalEngine(  337): Thermal-Server: Thermal received msg from  override
I/Thermal-Lib( 3092): Thermal-Lib-Client: Client request sent
,W/libprocessgroup( 1032): failed to open /acct/uid_10097/pid_5583/cgroup.procs: No such file or directory
,I/LGEmail ( 6617): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
W/DriveInitializer( 2333): Background init thread ended
V/GLSActivity( 2041): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DelayedSyncController( 6591): Delaying sync.
D/LGEmail ( 6617): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
I/BooksSync( 6532): Starting books sync
,I/ActivityManager( 1032): Killing 5979:com.lge.eula/1000 (adj 15): empty #17
W/ResourceType( 6617): No package identifier when getting value for resource number 0x00000000
,W/libprocessgroup( 1032): failed to open /acct/uid_1000/pid_5979/cgroup.procs: No such file or directory
,I/GLSUser ( 2041): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/ads_measurement
I/GLSUser ( 2041): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/ads_measurement without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2041): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2041): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/LgDataFeature( 6617): LgDataFeature() Constructor: none
D/LgDataFeature( 6617): LgDataFeature() Constructor Done, null
V/GLSActivity( 2041): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/Ads     ( 2333): [JAMS] Failed to get OAuth token: com.google.android.gms.auth.ad: BadAuthentication
,E/Auth.Api.Credentials( 2333): [CredentialSyncAdapter] Unknown sync event.
,I/VacuumService( 2041): Vacuum at: now=1454935064148 tag=VacuumService
,D/eas_req ( 6617): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,D/BooksSync( 6532): started syncMyEbooks
I/LgeMiscReceiver( 3295): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3295): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3295): networkInfo.isConnected() = true
D/PhoneState( 3295): setPdpRejectCasuse : false
,I/HubEmail( 6617): JNI_OnLoad()
,I/HubEmail( 6617): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6617): registerNatives()
I/HubEmail( 6617): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6617): registerNativeMethods()
I/HubEmail( 6617): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6617): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
D/libc-netbsd(  323): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  323): res_queryN name = www.google.com, class = 1, type = 1
D/libc-netbsd(  323): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  323): res_queryN name = static-avc.lglime.com, class = 1, type = 1
,I/ActivityManager( 1032): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6683 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,W/Settings( 6617): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 6617): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/libc-netbsd(  323): res_queryN name = www.google.com succeed
D/libc-netbsd(  323): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  323): res_queryN name = clients3.google.com, class = 1, type = 1
,D/libc-netbsd(  323): res_queryN name = clients3.google.com succeed
V/GLSActivity( 2041): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DrmBroadcastReceiver( 6683): Receive CONNECTIVITY_ACTION
,D/DrmBroadcastReceiver( 6683): 1  network is available. Sync DRM Time with NTP
V/DrmService( 6683): Service onCreate
D/DrmService( 6683): Received new request = 2
V/WifiInternetCheck( 1032): isHttpConnectionAvailable - We got a valid response : 204
I/DrmSntpClient( 6683): Start Sync process
I/art     ( 2041): Explicit concurrent mark sweep GC freed 19352(1108KB) AllocSpace objects, 2(32KB) LOS objects, 51% free, 30MB/62MB, paused 1.030ms total 26.634ms
D/DrmSntpClient( 6683): Server : 0
D/libc-netbsd(  323): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  323): res_queryN name = pool.ntp.org, class = 1, type = 1
,I/ActivityManager( 1032): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=6707 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GLSUser ( 2041): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2041): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2041): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2041): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2041): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
I/art     ( 6707): Almond Protected OAT
,V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1413): onNotificationPosted
D/SmartCoverUpdateMonitor( 1413): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1413): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1413): handleNotificationPosted(true)
D/QuickCircle( 1413): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1413): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): post do just update job
D/LgeQuickCoverNotificationData( 1413): showAll3
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1413): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1413): updateNotificationData: count=3
W/GLSActivity( 2041): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2041): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2041): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2041): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2041): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2041): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2041): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6532): Authentication error
E/BooksAccountManager( 6532): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6532): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6532): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6532): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6532): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6532): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6532): null auth token
,D/libc-netbsd(  323): res_queryN name = pool.ntp.org succeed
D/libc-netbsd(  323): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  323): res_queryN name = www.googleapis.com, class = 1, type = 1
D/QuickStatusbarLayout( 1413): Notification difference=198
D/QuickStatusbarLayout( 1413): child = android.widget.LinearLayout{10c851c6 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/WeatherApplication( 6707): removeAccount
D/WeatherApplication( 6707): Account.length = 0
E/WeatherApplication( 6707): OPERATOR:OPEN
D/WeatherAncestor( 6707): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:37:44
D/Weather.Utils( 6707): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6707): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6707): 2 : This is isUpdating : false
,D/WeatherAncestor( 6707): connectivity changed - connection : true
D/WeatherService( 6707): 2 : isServiceAlived():false forecastCache:null
D/ForecastDataCache( 6707): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 6707): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 6707): 2 : Cache is not up-to-date, count: 0
,D/Weather_cast( 6707): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 6707): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:37:44
I/LGDrmClient( 6683): _DRM_ServiceGet() : Bind lgdrm service
V/ILGDrmService(  333): eDRM_SetDRMTime +++
I/LGDRM   (  333): [DRM] SET TIME : YR=2016, MON=2, DAY=8
I/LGDRM   (  333): [DRM] SET TIME : HR=12, MIN=37, SEC=44
D/libc-netbsd(  323): res_queryN name = www.googleapis.com succeed
V/ILGDrmService(  333): eDRM_SetDRMTime ---
,I/DrmSntpClient( 6683): Synched
D/DrmService( 6683): Completed !! request = 2
D/DrmService( 6683): Request count = 0
I/ActivityManager( 1032): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6728 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1032): Killing 5382:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
I/art     (  356): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 203us total 9.565ms
I/art     (  356): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 185us total 8.936ms
I/art     (  356): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 185us total 9.029ms
,V/DrmService( 6683): Service onDestroy
,W/libprocessgroup( 1032): failed to open /acct/uid_10005/pid_5382/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 117551284542; DSPS: 3992744; Offset : -4311990794
W/ApiaryClient( 6532): Error response from books API: {
W/ApiaryClient( 6532):  "error": {
W/ApiaryClient( 6532):   "errors": [
W/ApiaryClient( 6532):    {
W/ApiaryClient( 6532):     "domain": "global",
W/ApiaryClient( 6532):     "reason": "required",
W/ApiaryClient( 6532):     "message": "Login Required",
W/ApiaryClient( 6532):     "locationType": "header",
W/ApiaryClient( 6532):     "location": "Authorization"
W/ApiaryClient( 6532):    }
W/ApiaryClient( 6532):   ],
W/ApiaryClient( 6532):   "code": 401,
W/ApiaryClient( 6532):   "message": "Login Required"
W/ApiaryClient( 6532):  }
W/ApiaryClient( 6532): }
,W/ApiaryClient( 6532): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6532): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1168293796581393201&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6532): Headers:
W/ApiaryClient( 6532): accept-encoding: [gzip]
W/ApiaryClient( 6532): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6532): gdata-version: 2
D/libc-netbsd(  323): res_queryN name = static-avc.lglime.com succeed
I/ActivityManager( 1032): Start proc com.google.android.apps.plus for service com.google.android.apps.plus/.service.EsSyncAdapterService: pid=6746 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1032): Killing 6071:com.android.providers.calendar/u0a14 (adj 15): empty #17
,V/FormManager( 6266): There are no updated forms. The schedule will be deleted.
,V/FormManager( 6266): Alarm would be updated, because LastCheckTime has been updated.
W/libprocessgroup( 1032): failed to open /acct/uid_10014/pid_6071/cgroup.procs: No such file or directory
,I/ActivityManager( 1032): Killing 2140:com.lge.music/u0a34 (adj 15): empty #17
W/ResourcesManager( 6746): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6728): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6728): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
V/AudioFlinger(  327): 2140 died, releasing its sessions
V/AudioFlinger(  327):  pid 1840 @ 0
V/AudioFlinger(  327):  pid 3295 @ 1
V/AudioFlinger(  327):  pid 3295 @ 2
W/ContextImpl( 6728): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6728): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,W/libprocessgroup( 1032): failed to open /acct/uid_10034/pid_2140/cgroup.procs: No such file or directory
,I/art     ( 1032): Explicit concurrent mark sweep GC freed 32113(1419KB) AllocSpace objects, 4(192KB) LOS objects, 33% free, 44MB/66MB, paused 2.263ms total 152.168ms
,I/GLSActivity( 2041): [ac] getting account id
,I/GLSUser ( 2041): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
I/WebViewFactory( 6728): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,D/DelayedSyncController( 6591): Delaying sync.
I/LibraryLoader( 6728): Loading: webviewchromium
,I/LibraryLoader( 6728): Time to load native libraries: 3 ms (timestamps 8344-8347)
I/LibraryLoader( 6728): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6728): Binding Chromium to main looper Looper (main, tid 1) {2581b8c1}
I/LibraryLoader( 6728): Expected native library version number "",actual native library version number ""
I/chromium( 6728): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6728): Initializing chromium process, renderers=0
,W/art     ( 6728): Attempt to remove local handle scope entry from IRT, ignoring
V/AudioPolicyService(  327): registerClient() client 0xb100fd60, uid 10093
W/chromium( 6728): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 6728): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 6728): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
W/AudioManagerAndroid( 6728): Requires BLUETOOTH permission
I/GoogleURLConnFactory( 2333): Using platform SSLCertificateSocketFactory
I/Adreno-EGL( 6728): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6728): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6728): Build Date: 12/12/14 금
I/Adreno-EGL( 6728): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6728): Remote Branch: 
I/Adreno-EGL( 6728): Local Patches: 
I/Adreno-EGL( 6728): Reconstruct Branch: 
,V/GLSActivity( 2041): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2041): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: mail
I/GLSUser ( 2041): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> mail without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2041): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2041): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2041): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=6.6, 0.0, 0.0  rx=5.5 bcn=0 [on:0 tx:0 rx:0 period:2762] from screen [on:0 period:-1058847860] gl rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=6.6, 0.0, 0.0  rx=5.5 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:-1058847860] gl rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
I/NSApplication( 6728): Starting up...
,I/ActivityManager( 1032): Killing 5610:com.android.vending/u0a44 (adj 15): empty #17
V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
W/GLSActivity( 2041): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2041): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2041): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2041): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2041): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2041): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2041): 	at android.os.Binder.execTransact(Binder.java:446)
I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
W/libprocessgroup( 1032): failed to open /acct/uid_10044/pid_5610/cgroup.procs: No such file or directory
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,W/SubscribedFeeds( 2333): Hard error
,V/GLSActivity( 2041): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LgeQuickCoverNLService( 1413): onNotificationPosted
D/SmartCoverUpdateMonitor( 1413): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1413): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1413): handleNotificationPosted(true)
D/QuickCircle( 1413): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1413): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): post do just update job
D/LgeQuickCoverNotificationData( 1413): showAll3
,D/LgeQuickCoverNotificationData( 1413): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1413): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  2
D/SyncManager( 1032): failed sync operation thalitester@gmail.com u0 (com.google), subscribedfeeds, PERIODIC, currentRunTime 40097, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
,E/LgeQuickCoverOverlayWindow( 1413): updateNotificationData: count=3
D/QuickStatusbarLayout( 1413): Notification difference=198
D/QuickStatusbarLayout( 1413): child = android.widget.LinearLayout{10c851c6 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/SyncManager( 1032): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), subscribedfeeds, PERIODIC, currentRunTime 149594, reason: Periodic
,I/GLSUser ( 2041): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2041): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2041): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2041): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2041): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/libc-netbsd(  323): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  323): res_queryN name = mtalk.google.com, class = 1, type = 1
V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2041): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2041): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2041): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2041): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2041): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2041): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2041): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6532): Authentication error
E/BooksAccountManager( 6532): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6532): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6532): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6532): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6532): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6532): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6532): null auth token
D/LgeQuickCoverNLService( 1413): onNotificationPosted
D/SmartCoverUpdateMonitor( 1413): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1413): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1413): handleNotificationPosted(true)
D/QuickCircle( 1413): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1413): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): post do just update job
D/LgeQuickCoverNotificationData( 1413): showAll3
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1413): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1413): updateNotificationData: count=3
I/iu.SyncManager( 2333): SYNC; picasa accounts
,D/QuickStatusbarLayout( 1413): Notification difference=198
D/QuickStatusbarLayout( 1413): child = android.widget.LinearLayout{10c851c6 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/libc-netbsd(  323): res_queryN name = mtalk.google.com succeed
,D/NetworkLogImpl( 2333): Loaded NetworkSpeedPredictor
I/iu.Environment( 2333): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/iu.UploadsManager( 2333): num queued entries: 0
I/iu.UploadsManager( 2333): num updated entries: 0
,I/iu.SyncManager( 2333): NEXT; no task
D/ChimeraCfgMgr( 2333): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/ChimeraCfgMgr( 2333): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/GLSUser ( 2041): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/gcm
I/GLSUser ( 2041): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/gcm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2041): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2041): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2041): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ApiaryClient( 6532): Error response from books API: {
W/ApiaryClient( 6532):  "error": {
W/ApiaryClient( 6532):   "errors": [
W/ApiaryClient( 6532):    {
W/ApiaryClient( 6532):     "domain": "global",
W/ApiaryClient( 6532):     "reason": "required",
W/ApiaryClient( 6532):     "message": "Login Required",
W/ApiaryClient( 6532):     "locationType": "header",
W/ApiaryClient( 6532):     "location": "Authorization"
W/ApiaryClient( 6532):    }
W/ApiaryClient( 6532):   ],
W/ApiaryClient( 6532):   "code": 401,
W/ApiaryClient( 6532):   "message": "Login Required"
W/ApiaryClient( 6532):  }
W/ApiaryClient( 6532): }
W/ApiaryClient( 6532): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6532): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1168293796581393201&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6532): Headers:
W/ApiaryClient( 6532): accept-encoding: [gzip]
W/ApiaryClient( 6532): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6532): gdata-version: 2
,D/PostponalbeReceiver( 5160): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.TIME_SET'.
I/ActivityManager( 1032): Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=6835 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/art     ( 2333): Explicit concurrent mark sweep GC freed 17610(1313KB) AllocSpace objects, 23(368KB) LOS objects, 49% free, 32MB/64MB, paused 1.493ms total 100.996ms
I/GcmGroups( 2333): Failed to subscribe to group.
I/GcmGroups( 2333): com.google.android.gms.auth.ad: BadAuthentication
I/GcmGroups( 2333): 	at com.google.android.gms.auth.p.b(SourceFile:442)
I/GcmGroups( 2333): 	at com.google.android.gms.auth.p.a(SourceFile:365)
I/GcmGroups( 2333): 	at com.google.android.gms.auth.p.a(SourceFile:318)
I/GcmGroups( 2333): 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:443)
I/GcmGroups( 2333): 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:333)
I/GcmGroups( 2333): 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:240)
I/GcmGroups( 2333): 	at com.google.android.gms.gcm.gmsproc.GcmReceiverService.onHandleIntent(SourceFile:50)
I/GcmGroups( 2333): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
I/GcmGroups( 2333): 	at android.os.Handler.dispatchMessage(Handler.java:102)
I/GcmGroups( 2333): 	at android.os.Looper.loop(Looper.java:135)
I/GcmGroups( 2333): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/GLSUser ( 2041): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2041): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2041): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2041): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/GcmGroups( 2333): Groups upload failed, retrying in 24000:00:00
V/GLSActivity( 2041): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/PeopleSync( 2333): onPerformSync() [5005f081]
,V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1413): onNotificationPosted
D/SmartCoverUpdateMonitor( 1413): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1413): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1413): handleNotificationPosted(true)
D/QuickCircle( 1413): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1413): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): post do just update job
D/LgeQuickCoverNotificationData( 1413): showAll3
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
,E/LgeQuickCoverOverlayWindow( 1413): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1413): updateNotificationData: count=3
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
D/QuickStatusbarLayout( 1413): Notification difference=198
D/QuickStatusbarLayout( 1413): child = android.widget.LinearLayout{10c851c6 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/ALBootInit( 6835): ====action==>android.intent.action.TIME_SET
D/ALBootInit( 6835): Alarm ALBootInit: TIME_SET
D/Alarms  ( 6835): [setNextAlert] start
D/Alarms  ( 6835): [setNextAlert] (1)
,D/Alarms  ( 6835):  minTime  = 0
D/Alarms  ( 6835):  -- OK multi -- 0
E/jeny.kim( 6835): [setNextAlert] setNextAlert  temp_Alarmlink + 
E/jeny.kim( 6835): [setNextAlert]setNextAlert temp_AlarmLinkText + 
I/CommonUtil( 6835): BUILD Country: EU
D/Alarms  ( 6835): broadcastToWidgetProvider : false
,I/PeopleDatabaseHelper( 2333): cleanUpNonGplusAccounts done.
V/GLSActivity( 2041): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Alarms  ( 6835): Enter formatDayAndTime(final Context context, long timeInMiliSec)
V/SettingsProvider( 1032): call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
,I/DigitalAppWidgetProvider( 6835): onReceive: android.intent.action.TIME_SET
V/DigitalAppWidgetProvider( 6835): cancelAlarmOnQuarterHour android.app.ReceiverRestrictedContext@25af6abf
,V/DigitalAppWidgetProvider( 6835): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@25af6abf
D/QuickCoverProvider( 6835): onReceiver
I/indal   ( 1413): SmartCoverWidgetContext createApplicationContext
I/indal   ( 1413): SmartCoverWidgetContext createApplicationContext
D/WeatherAncestor( 6707): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 13:37:46
,D/Weather.Utils( 6707): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6707): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6707): 2 : This is isUpdating : false
D/WeatherService( 6707): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@cf0d58c
,I/GoogleURLConnFactory( 2041): Using platform SSLCertificateSocketFactory
D/ForecastDataCache( 6707): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 6707): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 6707): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 6707): 2 : set auto-update time : 2/8 16:37
D/WeatherAncestor( 6707): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 13:37:46
D/GCM     ( 2041): Connected
,W/Uploader( 2041): No account for auth token provided
I/ActivityManager( 1032): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=6861 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/ActivityManager( 1032): Killing 6004:com.lge.bnr/1000 (adj 15): empty #17
,W/libprocessgroup( 1032): failed to open /acct/uid_1000/pid_6004/cgroup.procs: No such file or directory
D/libc-netbsd(  323): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  323): res_queryN name = play.googleapis.com, class = 1, type = 1
D/GCM     ( 2041): Message class com.google.f.a.a.p
,I/jxcore-log( 6138): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 6138): 
I/jxcore-log( 6138): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 6138): 
,I/jxcore-log( 6138): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 6138): 
,D/libc-netbsd(  323): res_queryN name = play.googleapis.com succeed
D/TimeService( 6861): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1454935066348
D/        ( 6861): TimeServiceNative: User Time to be set is 1454935066348
D/QC-time-services( 6861): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 6861): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 6861): Lib:time_genoff_operation: pargs->ts_val = 1454935066348
D/QC-time-services(  368): Daemon: Connection accepted:time_genoff
D/QC-time-services( 6861): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  368): Daemon:Received base = 2, unit = 1, operation = 0,value = 1454935066348
D/QC-time-services(  368): Daemon:genoff_opr: Base = 2, val = 1454935066348, operation = 0
,D/QC-time-services(  368): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS5/18/70 5:49:49
D/QC-time-services(  368): Daemon:Value read from RTC seconds = 14536189000
D/QC-time-services(  368): Daemon:new time 1454935066348 
D/QC-time-services(  368): Daemon: delta 1440398877348 genoff 1440398877348 
D/QC-time-services(  368): Daemon:genoff_persistent_update: Writing genoff = 1440398877348 to memory
D/QC-time-services(  368): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  368): Daemon:time_persistent_memory_opr:Genoff write operation 
D/QC-time-services(  368): Updating the TOD offset
D/QC-time-services(  368): Daemon:genoff_persistent_update: Writing genoff = 1440398877348 to memory
D/QC-time-services(  368): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  368): Daemon:time_persistent_memory_opr:Genoff write operation 
E/QC-time-services(  368): Daemon:Update to modem bit set
D/QC-time-services(  368): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  368): Daemon: Base = 2, Value being sent to MODEM = 1124434077348
,E/QC-time-services(  368): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
E/QC-time-services(  368): Daemon: Time-services: Waiting to acceptconnection
E/QC-time-services( 6861): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,I/ActivityManager( 1032): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetProvider: pid=6881 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi
I/ActivityManager( 1032): Killing 6318:com.lge.lifetracker/u0a37 (adj 15): empty #17
W/libprocessgroup( 1032): failed to open /acct/uid_10037/pid_6318/cgroup.procs: No such file or directory
,I/PeopleSync( 2333): Setting subscription: result=true [5005f081]
W/Uploader( 2041): No account for auth token provided
I/PeopleSync( 2333): Starting sync, feed=null [5005f081]
,W/ResourcesManager( 6881): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/CalendarApplication( 6881): CalendarApplication.onCreate()
,W/Uploader( 2041): No account for auth token provided
D/PreferenceKeysParser( 6881): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 6881): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@36b93592, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@3c1a7b63, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@3a70e360, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@3984019, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@17b118de, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@25af6abf, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@cf0d58c, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@19e3c4d5, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@3db1e4ea, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@2f79f3db, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@159bbe78, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@3028d951, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@194165b6, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@e99f2b7, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@100a4a24, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@32d0b98d, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@b762742, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@510353, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@36b3e490, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@319c6189, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@3e43758e, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@a5e81af, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@321ab9bc, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@1d608d45, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@35855c9a, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@251b89cb, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@eb7b5a8, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@2581b8c1, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@24cca866, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@2b56f7a7, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@25a68454, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@31301ffd, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@15eae4f2, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@2bf16743, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@241191c0, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@3063bef9, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@2c3e5e3e, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@3939349f, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@1d5e09ec, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@9851b5, lg_preferences_alerts_vibratetype=com.android.calendar.adaptati,on.PreferenceKey$KeyData@10be204a, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@12067bbb
D/GeneralPreferenceUtils( 6881): [migratePrefrenceKeys] Exit: Version(44001600) >= 42001300
,D/Config  ( 6881): [init]
I/Config  ( 6881): LGCalendar ver.4.40.16
I/Config  ( 6881): start check model
I/Config  ( 6881): start check native_ca
I/Config  ( 6881): Config Operator=OPEN, Country=EU
D/Config  ( 6881): [setDefaultValuesToPref]
D/Config  ( 6881): [parseProfiles]
,D/ProfilesParser( 6881): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6881): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6881): [updateProfiletoCountryInfo]
D/GeneralPreference( 6881): [checkAndMigrateOldPreference]
I/art     ( 1032): Explicit concurrent mark sweep GC freed 25130(1108KB) AllocSpace objects, 5(464KB) LOS objects, 33% free, 44MB/66MB, paused 1.518ms total 86.745ms
,E/AgendaWidgetManager( 6881): [updateWidgets] 
I/InitNotificationRingtoneService( 6881): Start InitializeAlertRingtoneService.onHandleIntent
,I/AlertUtils( 6881): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/41
W/Uploader( 2041):  no longer exists, so no auth token.
W/BaseAppContext( 2333): Using Auth Proxy for data requests.
,I/AlertUtils( 6881): [getCalendarNotiSoundURIFromCursor] getCount()= 21
W/BaseAppContext( 2333): Using Auth Proxy for data requests.
,V/GLSActivity( 2041): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 3323): Explicit concurrent mark sweep GC freed 5410(343KB) AllocSpace objects, 0(0B) LOS objects, 36% free, 27MB/43MB, paused 559us total 37.595ms
,W/Uploader( 2041): No account for auth token provided
I/AlertUtils( 6881): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arpeggio.ogg
I/GLSUser ( 2041): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2041): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2041): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2041): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/AlertUtils( 6881): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
,V/GLSActivity( 2041): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/BaseAppContext( 2333): Using Auth Proxy for data requests.
I/AlertUtils( 6881): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 6881): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 6881): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
,I/AlertUtils( 6881): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 6881): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 6881): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 6881): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
,V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2041): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2041): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2041): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2041): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2041): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2041): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2041): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6532): Authentication error
E/BooksAccountManager( 6532): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6532): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6532): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6532): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6532): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6532): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6532): null auth token
I/PeopleSync( 2333): Sync start: cannotHavePeople=true isPageExistenceCheckOnly=false
I/AlertUtils( 6881): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Afternoon_Walk.ogg
D/LgeQuickCoverNLService( 1413): onNotificationPosted
D/SmartCoverUpdateMonitor( 1413): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1413): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1413): handleNotificationPosted(true)
D/QuickCircle( 1413): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1413): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
,D/LgeQuickCoverNotificationData( 1413): post do just update job
D/LgeQuickCoverNotificationData( 1413): showAll3
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1413): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
I/AlertUtils( 6881): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
E/LgeQuickCoverOverlayWindow( 1413): updateNotificationData: count=3
I/AlertUtils( 6881): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 6881): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
D/MonthWidgetProvider( 6881): [onReceive]
D/CalendarWidgetProvider( 6881): [onReceive]
D/CalendarWidgetProvider( 6881): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.MonthWidgetProvider }
W/HolidayIntentService( 6881): onHandleIntent
D/HolidayDataLoader( 6881): readJsonAsset : holiday.json
,D/QuickStatusbarLayout( 1413): Notification difference=198
D/QuickStatusbarLayout( 1413): child = android.widget.LinearLayout{10c851c6 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/CalendarTypeController( 6881): [onUpdateAndInitCalendarTime]
W/Uploader( 2041): No account for auth token provided
D/WeekWidgetProvider( 6881): [onReceive]
D/CalendarWidgetProvider( 6881): [onReceive]
D/CalendarWidgetProvider( 6881): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 6881): [onUpdateAndInitCalendarTime]
I/AlertUtils( 6881): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 6881): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6881): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/41
,I/AlertUtils( 6881): set default noti to content://media/internal/audio/media/41
I/InitNotificationRingtoneService( 6881): End InitializeAlertRingtoneService.onHandleIntent
,I/GLSUser ( 2041): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.media.upload https://www.googleapis.com/auth/plus.pages.manage https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.profiles.read https://www.googleapis.com/auth/plus.profiles.write https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/plus.applications.manage https://www.googleapis.com/auth/plus.settings
,I/GLSUser ( 2041): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.media.upload https://www.googleapis.com/auth/plus.pages.manage https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.profiles.read https://www.googleapis.com/auth/plus.profiles.write https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/plus.applications.manage https://www.googleapis.com/auth/plus.settings without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2041): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2041): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2041): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ApiaryClient( 6532): Error response from books API: {
W/ApiaryClient( 6532):  "error": {
W/ApiaryClient( 6532):   "errors": [
W/ApiaryClient( 6532):    {
W/ApiaryClient( 6532):     "domain": "global",
W/ApiaryClient( 6532):     "reason": "required",
W/ApiaryClient( 6532):     "message": "Login Required",
W/ApiaryClient( 6532):     "locationType": "header",
W/ApiaryClient( 6532):     "location": "Authorization"
W/ApiaryClient( 6532):    }
W/ApiaryClient( 6532):   ],
W/ApiaryClient( 6532):   "code": 401,
W/ApiaryClient( 6532):   "message": "Login Required"
W/ApiaryClient( 6532):  }
W/ApiaryClient( 6532): }
W/ApiaryClient( 6532): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6532): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1168293796581393201&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6532): Headers:
W/ApiaryClient( 6532): accept-encoding: [gzip]
W/ApiaryClient( 6532): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6532): gdata-version: 2
E/HolidayIntentService( 6881): onHandleIntent:holiday data empty
I/ActivityManager( 1032): Killing 6365:com.lge.settings.easy/1000 (adj 15): empty #17
,I/art     ( 2041): Explicit concurrent mark sweep GC freed 39936(2MB) AllocSpace objects, 16(1815KB) LOS objects, 50% free, 30MB/62MB, paused 974us total 50.405ms
,W/libprocessgroup( 1032): failed to open /acct/uid_1000/pid_6365/cgroup.procs: No such file or directory
,D/GCM     ( 2041): GcmService start Intent { act=com.google.android.gcm.intent.SEND flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.gcm.intent.SEND
I/DigitalAppWidgetProvider( 6835): onReceive: android.intent.action.ALARM_CHANGED
I/jxcore-log( 6138): Test app app.js loaded
I/jxcore-log( 6138): 
D/WeatherAncestor( 6707): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 13:37:47
D/Weather.Utils( 6707): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6707): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6707): 2 : This is isUpdating : false
D/Weather_cast( 6707): 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
D/WeatherAncestor( 6707): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 13:37:47
I/chromium( 6138): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/PeopleSync( 2333): Sync finished, successful=false, took 162ms
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6138): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6138): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6138): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6138): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6138): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6138): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6138): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6138): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6138): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6138): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cbf216d added. We now have 1 listener(s)
I/jxcore-log( 6138): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 6138): 
I/ActivityManager( 1032): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RequestWriter$NetworkStateReceiver: pid=6907 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/PeopleSync( 2333): Cannot authenticate [5005f081]
I/PeopleSync( 2333): com.google.android.gms.auth.ad: BadAuthentication
I/PeopleSync( 2333): 	at com.google.android.gms.auth.p.b(SourceFile:442)
I/PeopleSync( 2333): 	at com.google.android.gms.auth.p.a(SourceFile:365)
I/PeopleSync( 2333): 	at com.google.android.gms.auth.p.a(SourceFile:310)
I/PeopleSync( 2333): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
I/PeopleSync( 2333): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
I/PeopleSync( 2333): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
I/PeopleSync( 2333): 	at com.google.android.gms.people.service.g.b(SourceFile:171)
I/PeopleSync( 2333): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
I/PeopleSync( 2333): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
I/PeopleSync( 2333): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
I/PeopleSync( 2333): 	at com.google.android.gms.plus.service.v2whitelisted.b.a(SourceFile:1184)
I/PeopleSync( 2333): 	at com.google.android.gms.people.sync.aa.g(SourceFile:1086)
I/PeopleSync( 2333): 	at com.google.android.gms.people.sync.aa.a(SourceFile:241)
I/PeopleSync( 2333): 	at com.google.android.gms.people.sync.s.a(SourceFile:283)
I/PeopleSync( 2333): 	at com.google.android.gms.people.sync.s.a(SourceFile:191)
I/PeopleSync( 2333): 	at com.google.android.gms.people.sync.s.a(SourceFile:93)
I/PeopleSync( 2333): 	at com.google.android.gms.common.j.a.onPerformSync(SourceFile:81)
I/PeopleSync( 2333): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,W/ResourcesManager( 6907): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/PeopleSync( 2333): ***Sync finished***, duration: 1247 [5005f081]
,D/SyncManager( 1032): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.gms.people, PERIODIC, currentRunTime 40210, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager( 1032): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.gms.people, PERIODIC, currentRunTime 152399, reason: Periodic
,D/LgDataFeature( 6907): LgDataFeature() Constructor: none
D/LgDataFeature( 6907): LgDataFeature() Constructor Done, null
I/ActivityManager( 1032): Start proc com.google.android.syncadapters.calendar for service com.google.android.syncadapters.calendar/.CalendarSyncAdapterService: pid=6929 uid=10069 gids={50069, 9997, 3003} abi=armeabi-v7a
,I/Babel   ( 6907): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 6907): MmsConfig.loadMmsSettings
I/Babel   ( 6907): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
I/Babel   ( 6907): MmsConfig.loadFromDatabase
,E/Babel   ( 6907): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 6907): MmsConfig.loadFromResources
E/Babel   ( 6907): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 6907): MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
W/Settings( 6907): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/AudioCapabilities( 6907): Unsupported mime audio/evrc
,W/AudioCapabilities( 6907): Unsupported mime audio/qcelp
W/VideoCapabilities( 6907): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6907): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6907): Unsupported mime audio/qcelp
W/AudioCapabilities( 6907): Unsupported mime audio/evrc
W/VideoCapabilities( 6907): Unsupported mime video/x-ms-wmv
,W/AbstractGoogleClient( 6929): Application name is not set. Call Builder#setApplicationName.
,W/VideoCapabilities( 6907): Unsupported mime video/divx
W/VideoCapabilities( 6907): Unsupported mime video/divx311
,W/VideoCapabilities( 6907): Unsupported mime video/divx4
W/VideoCapabilities( 6907): Unsupported mime video/mp4v-esdp
I/ActivityManager( 1032): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6957 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi
,W/ResourcesManager( 6907): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6907): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/VideoCapabilities( 6907): Unsupported profile 4 for video/mp4v-es
,W/AudioCapabilities( 6907): Unsupported mime audio/eac3
W/AudioCapabilities( 6907): Unsupported mime audio/ac3
W/AudioCapabilities( 6907): Unsupported mime audio/g726
,W/AudioCapabilities( 6907): Unsupported mime audio/wma-voice
W/AudioCapabilities( 6907): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6907): Unsupported mime audio/adpcm
W/VideoCapabilities( 6907): Unsupported mime video/theora
W/VideoCapabilities( 6907): Unsupported mime video/mjpg
W/ResourcesManager( 6957): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
V/JNIHelp ( 6907): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/CalendarProvider2( 6957): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@cf5fbf4
,D/CalendarProvider2( 6957): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 6957): Created com.android.providers.calendar.CalendarAlarmManager@3984019(com.android.providers.calendar.CalendarProvider2@cf5fbf4)
W/System  ( 6907): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/system/app/Hangouts/Hangouts.apk"],nativeLibraryDirectories=[/system/app/Hangouts/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6907): Installed default security provider GmsCore_OpenSSL
I/GLSUser ( 2041): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native
I/GLSUser ( 2041): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2041): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2041): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2041): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/Babel   ( 6907): UserRecoverableAuthException.
E/Babel   ( 6907): cfq: BadAuthentication
E/Babel   ( 6907): 	at cfn.a(Unknown Source)
E/Babel   ( 6907): 	at f.a(PG:191)
E/Babel   ( 6907): 	at ava.a(PG:88)
E/Babel   ( 6907): 	at ava.a(PG:128)
E/Babel   ( 6907): 	at bjs.a(PG:255)
E/Babel   ( 6907): 	at bep.a(PG:602)
E/Babel   ( 6907): 	at bep.a(PG:469)
E/Babel   ( 6907): 	at bpo.run(PG:1141)
E/Babel   ( 6907): Error getting auth token
,E/Babel   ( 6907): bxl
E/Babel   ( 6907): 	at f.a(PG:201)
E/Babel   ( 6907): 	at ava.a(PG:88)
E/Babel   ( 6907): 	at ava.a(PG:128)
E/Babel   ( 6907): 	at bjs.a(PG:255)
E/Babel   ( 6907): 	at bep.a(PG:602)
E/Babel   ( 6907): 	at bep.a(PG:469)
E/Babel   ( 6907): 	at bpo.run(PG:1141)
I/Babel_RequestWriter( 6907): error sending REQ[fc:8; creat:1454718958062; type:bev-343128940]; took 77 ms (error code == 100)
E/Babel   ( 6907): Account registration failedRedacted-21
E/Babel   ( 6907): bph: null -- null
E/Babel   ( 6907): 	at ava.a(PG:120)
E/Babel   ( 6907): 	at ava.a(PG:128)
E/Babel   ( 6907): 	at bjs.a(PG:255)
E/Babel   ( 6907): 	at bep.a(PG:602)
E/Babel   ( 6907): 	at bep.a(PG:469)
E/Babel   ( 6907): 	at bpo.run(PG:1141)
I/Babel   ( 6907): Account setup failed with error state:106 account:Redacted-21
I/Babel   ( 6907): Account sign in complete with state 106account: Redacted-21
I/GLSUser ( 2041): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native
I/art     ( 6907): Note: end time exceeds epoch: 
I/GLSUser ( 2041): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2041): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2041): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2041): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 2041): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
,I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1413): onNotificationPosted
D/SmartCoverUpdateMonitor( 1413): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1413): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1413): handleNotificationPosted(true)
D/QuickCircle( 1413): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1413): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): post do just update job
D/LgeQuickCoverNotificationData( 1413): showAll3
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1413): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
,E/LgeQuickCoverOverlayWindow( 1413): updateNotificationData: count=3
E/Babel   ( 6907): Unexpected exception while authenticating.
E/Babel   ( 6907): cfr: User intervention required. Notification has been pushed.
E/Babel   ( 6907): 	at cfn.b(Unknown Source)
E/Babel   ( 6907): 	at cfn.a(Unknown Source)
E/Babel   ( 6907): 	at f.a(PG:188)
E/Babel   ( 6907): 	at ava.b(PG:143)
E/Babel   ( 6907): 	at bnr.run(PG:5415)
E/Babel   ( 6907): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 6907): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 6907): 	at java.lang.Thread.run(Thread.java:818)
I/GLSUser ( 2041): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.calendar, service: oauth2:https://www.googleapis.com/auth/calendar
I/GLSUser ( 2041): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/calendar without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2041): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2041): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2041): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/QuickStatusbarLayout( 1413): Notification difference=198
D/QuickStatusbarLayout( 1413): child = android.widget.LinearLayout{10c851c6 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1413): onNotificationPosted
D/SmartCoverUpdateMonitor( 1413): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1413): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1413): handleNotificationPosted(true)
D/QuickCircle( 1413): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1413): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): post do just update job
D/LgeQuickCoverNotificationData( 1413): showAll3
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1413): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
E/CalendarSyncAdapter( 6929): Exception in onPerformLoggedSync 
E/CalendarSyncAdapter( 6929): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/CalendarSyncAdapter( 6929): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(GoogleRequestInitializer.java:152)
E/CalendarSyncAdapter( 6929): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(GoogleRequestInitializer.java:89)
E/CalendarSyncAdapter( 6929): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:858)
E/CalendarSyncAdapter( 6929): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(AbstractGoogleClientRequest.java:410)
E/CalendarSyncAdapter( 6929): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(AbstractGoogleClientRequest.java:343)
E/CalendarSyncAdapter( 6929): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(AbstractGoogleClientRequest.java:460)
E/CalendarSyncAdapter( 6929): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.processAccountCalendars(CalendarSyncAdapterApiary.java:1510)
E/CalendarSyncAdapter( 6929): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.updateCalendarsFromServerFeed(CalendarSyncAdapterApiary.java:1024)
E/CalendarSyncAdapter( 6929): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.getServerDiffs(CalendarSyncAdapterApiary.java:906)
E/CalendarSyncAdapter( 6929): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.performSync(CalendarSyncAdapterApiary.java:430)
E/CalendarSyncAdapter( 6929): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.onPerformLoggedSync(CalendarSyncAdapterApiary.java:335)
E/CalendarSyncAdapter( 6929): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
E/CalendarSyncAdapter( 6929): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/CalendarSyncAdapter( 6929): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User interv,ention required. Notification has been pushed.
E/CalendarSyncAdapter( 6929): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/CalendarSyncAdapter( 6929): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/CalendarSyncAdapter( 6929): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(GoogleRequestInitializer.java:140)
E/CalendarSyncAdapter( 6929): 	... 12 more
E/LgeQuickCoverOverlayWindow( 1413): updateNotificationData: count=3
I/ActivityManager( 1032): Killing 6287:com.lge.sync/1000 (adj 15): empty #17
,D/QuickStatusbarLayout( 1413): Notification difference=198
D/QuickStatusbarLayout( 1413): child = android.widget.LinearLayout{10c851c6 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/libprocessgroup( 1032): failed to open /acct/uid_1000/pid_6287/cgroup.procs: No such file or directory
,D/SyncManager( 1032): failed sync operation thalitester@gmail.com u0 (com.google), com.android.calendar, PERIODIC, currentRunTime 40276, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager( 1032): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.calendar, PERIODIC, currentRunTime 152133, reason: Periodic
I/ActivityManager( 1032): Killing 5902:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
I/QRemote ( 6034): [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
W/System.err( 6034): android.os.DeadObjectException
W/System.err( 6034): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6034): 	at android.os.BinderProxy.transact(Binder.java:496)
,W/System.err( 6034): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 6034): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
W/System.err( 6034): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 6034): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 6034): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6034): 	at android.os.Handler.dispatchMessage(Handler.java:95)
,W/System.err( 6034): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6034): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 6034): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6034): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6034): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 6034): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 6034): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 6034): android.os.DeadObjectException
W/System.err( 6034): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6034): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6034): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 6034): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
W/System.err( 6034): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 6034): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 6034): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6034): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6034): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6034): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 6034): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6034): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6034): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 6034): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 6034): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/QRemote ( 6034): [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
E/BooksSync( 6532): Soft error: 
E/BooksSync( 6532): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6532): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1168293796581393201&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6532): Headers:
E/BooksSync( 6532): accept-encoding: [gzip]
E/BooksSync( 6532): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6532): gdata-version: 2
E/BooksSync( 6532): 
E/BooksSync( 6532): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6532): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6532): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6532): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6532): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6532): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6532): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6532): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6532): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6532): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6532): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6532): {
E/BooksSync( 6532):  "error": {
E/BooksSync( 6532):   "errors": [
E/BooksSync( 653,2):    {
E/BooksSync( 6532):     "domain": "global",
E/BooksSync( 6532):     "reason": "required",
E/BooksSync( 6532):     "message": "Login Required",
E/BooksSync( 6532):     "locationType": "header",
E/BooksSync( 6532):     "location": "Authorization"
E/BooksSync( 6532):    }
E/BooksSync( 6532):   ],
E/BooksSync( 6532):   "code": 401,
E/BooksSync( 6532):   "message": "Login Required"
E/BooksSync( 6532):  }
E/BooksSync( 6532): }
E/BooksSync( 6532): 
E/BooksSync( 6532): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6532): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6532): 	... 8 more
E/BooksSync( 6532): Sync error
E/BooksSync( 6532): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6532): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-1168293796581393201&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6532): Headers:
E/BooksSync( 6532): accept-encoding: [gzip]
E/BooksSync( 6532): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6532): gdata-version: 2
E/BooksSync( 6532): 
E/BooksSync( 6532): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6532): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6532): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6532): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6532): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6532): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6532): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6532): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6532): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6532): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6532): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6532): {
E/BooksSync( 6532):  "error": {
E/BooksSync( 6532):   "errors": [
E/BooksSync( 6532):    {
E/BooksSync( 6532):     "domain": "global",
E/BooksSync( 6532):     "reason": "required",
E/BooksSync( 6532):     "message": "Login Required",
E/BooksSync( 6532):     "locationType": "header",
E/BooksSync( 6532):     "location": "Authorization"
E/BooksSync( 6532):    }
E/BooksSync( 6532):   ],
E/BooksSync( 6532):   "code": 401,
E/BooksSync( 6532):   "message": "Login Required"
E/BooksSync( 6532):  }
E/BooksSync( 6532): }
E/BooksSync( 6532): 
E/BooksSync( 6532): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6532): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6532): 	... 8 more
I/BooksSync( 6532): Finished books sync
,W/libprocessgroup( 1032): failed to open /acct/uid_1000/pid_5902/cgroup.procs: No such file or directory
W/ActivityManager( 1032): Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
D/QRemote ( 6034): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
I/QRemote ( 6034): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,I/ActivityManager( 1032): Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6989 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/QRemote ( 6034): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,D/UEI.SmartControl( 6989): Quickset Services start...
,I/UEI.SmartControl( 6989): Manufacture = LGE
D/UEI.SmartControl( 6989): Id = LGNevo
D/UEI.SmartControl( 6989): File observer start...
E/UEI.SmartControl( 6989): IR Port is disabled: false
V/AlarmManager( 1032): ELAPSED_WAKEUP set : Alarm{1599f250 type 2 when 121100 com.android.providers.calendar} when 121100
D/CalendarProviderBroadcastReceiver( 6957): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/UEI.SmartControl( 6989): Starting file observer...
D/CalendarProviderBroadcastReceiver( 6957): [IntentService] WakeLock acquire, start IntentSerivce
D/UEI.SmartControl( 6989): Extracting JNI libs...
D/UEI.SmartControl( 6989): --- this system supports 32-bit or 64-bit only
,D/CalendarProvider2( 6957): CalendarProviderIntentService.onCreate()
D/CalendarProvider2( 6957): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 6957): [getOrCreateCalendarAlarmManager]
E/SQLiteLog( 6957): (284) automatic index on view_events(_id)
,D/CalendarProvider2( 6957): [IntentService] Release Lock
,D/CalendarProvider2( 6957): CalendarProviderIntentService.onDestroy()
I/ActivityManager( 1032): Killing 6226:com.android.settings/1000 (adj 15): empty #17
,D/SyncManager( 1032): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 26689, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
D/WifiService( 1032): Client connection lost with reason: 4
,D/UEI.SmartControl( 6989): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 6989): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6989): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,W/libprocessgroup( 1032): failed to open /acct/uid_1000/pid_6226/cgroup.procs: No such file or directory
,I/UEI.SmartControl( 6989): --- Selecting new region: 6
,I/UEI.SmartControl( 6989): Model = LG-D855
,D/UEI.SmartControl( 6989): QS Service created
,I/art     ( 1032): Explicit concurrent mark sweep GC freed 19616(925KB) AllocSpace objects, 5(464KB) LOS objects, 33% free, 44MB/66MB, paused 2.432ms total 88.369ms
,I/UEI.SmartControl( 6989): Service initServices...
D/UEI.SmartControl( 6989): QS start get config
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-54 f=2412 sc=60 link=72 tx=15.8, 0.0, 0.0  rx=12.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1058844850] gl rssi=-54 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-54 f=2412 sc=60 link=72 tx=15.8, 0.0, 0.0  rx=12.8 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:-1058844850] gl rssi=-54 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,D/UEI.SmartControl( 6989): Loading JNI Libs...
,I/ActivityManager( 1032): Start proc com.google.android.gm for service com.google.android.gm/.provider.MailSyncAdapterService: pid=7024 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GCoreUlr( 1805): Uploading GCM registration ID for account#2#
,W/BaseAppContext( 1805): Using Auth Proxy for data requests.
,I/GLSUser ( 1805): [ChannelManager] Attempting to channel bind connection HttpClient.
,I/GLSUser ( 1805): [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
,W/ActivityManager( 1032): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/ActivityThread( 7024): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
W/ActivityManager( 1032): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/GLSUser ( 2041): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/userlocation.reporting
I/GLSUser ( 2041): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/userlocation.reporting without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2041): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2041): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2041): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/GCoreUlr( 1805): 
E/GCoreUlr( 1805): com.google.android.gms.auth.ad: BadAuthentication
E/GCoreUlr( 1805): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/GCoreUlr( 1805): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/GCoreUlr( 1805): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/GCoreUlr( 1805): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/GCoreUlr( 1805): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/GCoreUlr( 1805): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/GCoreUlr( 1805): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/GCoreUlr( 1805): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/GCoreUlr( 1805): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/GCoreUlr( 1805): 	at com.google.android.location.reporting.c.c.a(SourceFile:166)
E/GCoreUlr( 1805): 	at com.google.android.location.reporting.c.g.a(SourceFile:111)
E/GCoreUlr( 1805): 	at com.google.android.location.reporting.service.t.b(SourceFile:220)
E/GCoreUlr( 1805): 	at com.google.android.location.reporting.service.t.a(SourceFile:173)
E/GCoreUlr( 1805): 	at com.google.android.location.reporting.service.s.onPerformSync(SourceFile:149)
E/GCoreUlr( 1805): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,I/Gmail   ( 7024): getAccountsCursor
,D/SyncManager( 1032): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.location.reporting, PERIODIC, currentRunTime 40441, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager( 1032): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.location.reporting, PERIODIC, currentRunTime 153654, reason: Periodic
V/GLSActivity( 2041): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1032): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
W/ActivityManager( 1032): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/ActivityManager( 1032): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
I/Gmail   ( 7024): Observing account changes for notifications
,W/ActivityManager( 1032): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/GAV2    ( 7024): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/UEI.SmartControl( 6989): Supports setup maps: true
D/UEI.SmartControl( 6989): QS start statue = true Error code = 0
I/UEI.SmartControl( 6989): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6989): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6989): ### init IR Blaster...
,D/serial_port( 6989): Configuring serial port
E/UEI.SmartControl( 6989): UEIBLaster setting for 616
I/UEI.SmartControl( 6989): Setting serial record hearder size = 2
I/UEI.SmartControl( 6989): configuring settings for MAXQ616
I/UEI.SmartControl( 6989): Get version...
,W/ActivityManager( 1032): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
V/GLSActivity( 2041): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/UEI.SmartControl( 6989): serial port data available: 21
W/Gmail   ( 7024): Sync started for account: account:61035162
,I/GAV2    ( 6532): Thread[GAThread,5,main]: No campaign data found.
I/Gmail   ( 7024): getAccountsCursor
E/Gmail   ( 7024): Error finding the version of the Email provider.....
E/Gmail   ( 7024): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 7024): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 7024): 	at com.google.android.gm.EmailMigrationService.aU(SourceFile:1235)
E/Gmail   ( 7024): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:187)
E/Gmail   ( 7024): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 7024): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 7024): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 7024): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 7024): We do not support migrating this version of the Email provider.
I/GLSUser ( 2041): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 2041): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2041): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2041): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2041): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/UEI.SmartControl( 6989): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 6989): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 6989): QS saving settings...
D/UEI.SmartControl( 6989): IR Blaster version: 25672567
V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/UEI.SmartControl( 6989): serial port data available: 4
W/GLSActivity( 2041): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2041): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2041): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2041): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2041): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2041): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2041): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1413): onNotificationPosted
D/SmartCoverUpdateMonitor( 1413): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1413): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1413): handleNotificationPosted(true)
D/QuickCircle( 1413): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1413): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): post do just update job
D/LgeQuickCoverNotificationData( 1413): showAll3
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 1,0|com.google.android.gms|1|null|10005
,D/LgeQuickCoverNotificationData( 1413): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1413): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  1
D/ContactsSyncAdapter( 2041): innerSync failed
D/ContactsSyncAdapter( 2041): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2041): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2041): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2041): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2041): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2041): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2041): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2041): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2041): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2041): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2041): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2041): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1413): updateNotificationData: count=3
,D/SyncManager( 1032): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, PERIODIC, currentRunTime 40464, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager( 1032): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, PERIODIC, currentRunTime 153342, reason: Periodic
D/QuickStatusbarLayout( 1413): Notification difference=198
D/QuickStatusbarLayout( 1413): child = android.widget.LinearLayout{10c851c6 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ContextImpl( 6989): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
E/SQLiteLog( 7024): (283) recovered 1519 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,I/UEI.SmartControl( 6989): Device manager: loading config....
D/UEI.SmartControl( 6989): ----------- loading internal config...
E/UEI.SmartControl( 6989): Services init done
D/UEI.SmartControl( 6989): QS Service init finished
D/UEI.SmartControl( 6989): QS Service version name: 2.1.91
D/UEI.SmartControl( 6989): QS Service version code: 201091
D/UEI.SmartControl( 6989): Service requested: Control
E/UEI.SmartControl( 6989): Loading SETTINGS...
D/UEI.SmartControl( 6989): Request IControl service: devices are loaded...
I/QRemote ( 6034): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 6989): ------ IControl API: 11
I/ActivityManager( 1032): Killing 6034:com.lge.qremote/u0a112 (adj 15): empty #17
I/UEI.SmartControl( 6989): Registering callback...
D/UEI.SmartControl( 6989): -- Open brand translation xml: brands_translations_ko
,I/UEI.SmartControl( 6989): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6989): -----service ready thread exits
D/UEI.SmartControl( 6989): Internal service binding...
,W/libprocessgroup( 1032): failed to open /acct/uid_10112/pid_6034/cgroup.procs: No such file or directory
,I/Gmail   ( 7024): notifyAccountChanged
,I/Gmail   ( 7024): getAccountsCursor
,V/GLSActivity( 2041): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 7024): notifyAccountChanged
I/Gmail   ( 7024): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 7024): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 7024): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 7024): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 7024): getAccountsCursor
,V/GLSActivity( 2041): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 2041): Explicit concurrent mark sweep GC freed 19762(1131KB) AllocSpace objects, 9(1296KB) LOS objects, 50% free, 30MB/62MB, paused 1.018ms total 32.523ms
I/Gmail   ( 7024): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 5310, normalSync: true
,W/ResourcesManager( 7024): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7024): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7024): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/GLSUser ( 2041): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/reminders
I/GLSUser ( 2041): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/reminders without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2041): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2041): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2041): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/ReminderSync( 2333): AuthError [T SyncAdapterThread-1:id=269:priority=5:group=main]
,D/SyncManager( 1032): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.gms.reminders, PERIODIC, currentRunTime 40484, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager( 1032): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.gms.reminders, PERIODIC, currentRunTime 152535, reason: Periodic
I/ActivityManager( 1032): Start proc com.google.android.apps.docs for service com.google.android.apps.docs/.sync.syncadapter.DocsSyncAdapterService: pid=7085 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/System  ( 7024): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[directory "."],nativeLibraryDirectories=[/vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7024): Installed default security provider GmsCore_OpenSSL
V/GLSActivity( 2041): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2041): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gm, service: mail
,I/GLSUser ( 2041): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> mail without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2041): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2041): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2041): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 1032): Explicit concurrent mark sweep GC freed 23447(988KB) AllocSpace objects, 3(176KB) LOS objects, 33% free, 44MB/66MB, paused 1.771ms total 101.054ms
,V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,W/GLSActivity( 2041): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2041): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2041): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2041): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2041): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2041): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2041): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1413): onNotificationPosted
V/GLSActivity( 2041): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/SmartCoverUpdateMonitor( 1413): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1413): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1413): handleNotificationPosted(true)
D/QuickCircle( 1413): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1413): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): post do just update job
D/LgeQuickCoverNotificationData( 1413): showAll3
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1413): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  1
,D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1413): updateNotificationData: count=3
,D/QuickStatusbarLayout( 1413): Notification difference=198
D/QuickStatusbarLayout( 1413): child = android.widget.LinearLayout{10c851c6 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/DocsApplication( 7085): Installing DEX configuration.
D/DexInstaller( 7085): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
I/GLSUser ( 2041): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gm, service: mail
I/GLSUser ( 2041): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> mail without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2041): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2041): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/PackageInfoHelper( 7085): Provided clientMode=RELEASE, packageInfo=PackageInfo{cf5fbf4 com.google.android.apps.docs}
,V/GLSActivity( 2041): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/TAG     ( 7085): onCreate()
D/CrossAppStateProvider( 7085): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1413): onNotificationPosted
D/SmartCoverUpdateMonitor( 1413): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1413): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1413): handleNotificationPosted(true)
D/QuickCircle( 1413): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1413): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): post do just update job
D/LgeQuickCoverNotificationData( 1413): showAll3
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1413): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
W/GLSActivity( 2041): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2041): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2041): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2041): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2041): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2041): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2041): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1413): updateNotificationData: count=3
,I/Gmail   ( 7024): notifyAccountChanged
I/Gmail   ( 7024): getAccountsCursor
V/GLSActivity( 2041): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/QuickStatusbarLayout( 1413): Notification difference=198
D/QuickStatusbarLayout( 1413): child = android.widget.LinearLayout{10c851c6 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,I/Gmail   ( 7024): notifyAccountChanged
W/Gmail   ( 7024): Sync complete for account: account:61035162
I/Gmail   ( 7024): getAccountsCursor
V/GLSActivity( 2041): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/SyncManager( 1032): failed sync operation thalitester@gmail.com u0 (com.google), gmail-ls, PERIODIC, currentRunTime 40460, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager( 1032): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), gmail-ls, PERIODIC, currentRunTime 152835, reason: Periodic
I/SyncAdapterService( 6728): Ignoring sync request for non-current account
,I/ActivityManager( 1032): Killing 6550:com.lge.appbox.client/u0a11 (adj 15): empty #17
,W/libprocessgroup( 1032): failed to open /acct/uid_10011/pid_6550/cgroup.procs: No such file or directory
,W/BaseAppContext( 2333): Using Auth Proxy for data requests.
,W/BaseAppContext( 2333): Using Auth Proxy for data requests.
W/BaseAppContext( 2333): Using Auth Proxy for data requests.
,W/BaseAppContext( 2333): Using Auth Proxy for data requests.
,W/BaseAppContext( 2333): Using Auth Proxy for data requests.
,I/GAV4    ( 6728): Thread[GAThread,5,main]: No campaign data found.
,I/art     ( 2333): Explicit concurrent mark sweep GC freed 12249(760KB) AllocSpace objects, 5(80KB) LOS objects, 49% free, 32MB/64MB, paused 1.170ms total 48.358ms
,W/BaseAppContext( 2333): Using Auth Proxy for data requests.
,W/BaseAppContext( 2333): Using Auth Proxy for data requests.
,D/ChimeraCfgMgr( 2333): Loading module com.google.android.gms.games from APK com.google.android.gms
,I/GoogleHttpClient( 5239): Falling back to old http client 0 java.lang.NoSuchMethodException: <init> [class android.content.Context, class java.lang.String, boolean, boolean]
,V/GLSActivity( 2041): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2041): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.music, service: sj
I/GLSUser ( 2041): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> sj without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2041): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2041): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2041): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1413): onNotificationPosted
D/SmartCoverUpdateMonitor( 1413): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1413): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1413): handleNotificationPosted(true)
D/QuickCircle( 1413): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1413): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): post do just update job
D/LgeQuickCoverNotificationData( 1413): showAll3
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1413): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
W/GLSActivity( 2041): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2041): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2041): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2041): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2041): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2041): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2041): 	at android.os.Binder.execTransact(Binder.java:446)
E/LgeQuickCoverOverlayWindow( 1413): updateNotificationData: count=3
I/ActivityManager( 1032): Killing 6266:com.lge.formmanager/u0a26 (adj 15): empty #17
D/QuickStatusbarLayout( 1413): Notification difference=198
D/QuickStatusbarLayout( 1413): child = android.widget.LinearLayout{10c851c6 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/libprocessgroup( 1032): failed to open /acct/uid_10026/pid_6266/cgroup.procs: No such file or directory
,W/MusicSyncAdapter( 5239): Sync failed due to an authentication issue.
,D/SyncManager( 1032): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.music.MusicContent, PERIODIC, currentRunTime 40507, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager( 1032): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.music.MusicContent, PERIODIC, currentRunTime 153503, reason: Periodic
,I/ActivityManager( 1032): Start proc com.google.android.videos for service com.google.android.videos/.store.SyncService: pid=7123 uid=10103 gids={50103, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/art     (  356): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 375us total 14.581ms
I/art     (  356): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 252us total 11.737ms
,E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5239): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/art     (  356): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 227us total 11.048ms
,E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5239): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5239): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5239): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,W/ArtDownloadService( 5239): Setting cache size 0
,W/ResourcesManager( 7123): Asset path '/system/framework/com.google.widevine.software.drm.jar' does not exist or contains no resources.
,I/ActivityManager( 1032): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=7146 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/MusicLeanback( 5239): Conditions not met for autocaching.
I/MusicLeanback( 5239): Stop autocaching.
W/ArtDownloadService( 5239): Setting cache size 0
W/ResourcesManager( 7146): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7146): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 7146): VM with version 2.1.0 has multidex support
I/MultiDex( 7146): install
I/MultiDex( 7146): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 7146): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 7146): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7146): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3949c9ab: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7146): Installed default security provider GmsCore_OpenSSL
D/LgDataFeature( 7085): LgDataFeature() Constructor: none
D/LgDataFeature( 7085): LgDataFeature() Constructor Done, null
D/GCM     ( 2041): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AuthorizationBluetoothService( 2041): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GmsCoreStatsServiceLauncher( 2333): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 7146): callingUid 10005, callindPid: 7146
,D/LocationInitializer( 2333): Restart initialization of location
E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5239): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/cache
E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5239): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/cache
E/MDM     ( 1805): [86] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/WearableClient( 5239): WearableClientImpl.onPostInitHandler: done
D/WearableClient( 5239): WearableClientImpl.onPostInitHandler: done
E/GmsUtils( 5239): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
D/LgDataFeature( 7123): LgDataFeature() Constructor: none
D/LgDataFeature( 7123): LgDataFeature() Constructor Done, null
,W/GAV2    ( 7085): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/WifiService( 1032): acquireWifiLockLocked: WifiLock{SyncManager type=1 binder=android.os.BinderProxy@1f565dcb}
,D/libc-netbsd(  323): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  323): res_queryN name = ssl.gstatic.com, class = 1, type = 1
,D/libc-netbsd(  323): res_queryN name = ssl.gstatic.com succeed
,D/PlayMovies( 7123): PersistentCache.cleanup:103 Cache is below limit, no need to shrink: [size=0, limit=5242880]
,D/PlayMovies( 7123): TransferService.onCreate:52 creating transfer service
W/AudioCapabilities( 7123): Unsupported mime audio/evrc
,W/AudioCapabilities( 7123): Unsupported mime audio/qcelp
W/VideoCapabilities( 7123): Unrecognized profile 2130706433 for video/avc
I/art     ( 2041): Explicit concurrent mark sweep GC freed 14369(797KB) AllocSpace objects, 8(1152KB) LOS objects, 50% free, 30MB/62MB, paused 799us total 23.893ms
W/AudioCapabilities( 7123): Unsupported mime audio/amr-wb-plus
,E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.videos/files/Movies/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7123): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.videos/files/Movies
W/AudioCapabilities( 7123): Unsupported mime audio/qcelp
W/AudioCapabilities( 7123): Unsupported mime audio/evrc
W/VideoCapabilities( 7123): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 7123): Unsupported mime video/divx
W/VideoCapabilities( 7123): Unsupported mime video/divx311
W/VideoCapabilities( 7123): Unsupported mime video/divx4
W/VideoCapabilities( 7123): Unsupported mime video/mp4v-esdp
W/ResourcesManager( 2333): Asset path '/system/framework/com.google.widevine.software.drm.jar' does not exist or contains no resources.
,I/VideoCapabilities( 7123): Unsupported profile 4 for video/mp4v-es
I/GLSUser ( 2041): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.videos, service: oauth2:https://www.googleapis.com/auth/android_video https://www.googleapis.com/auth/youtube https://www.googleapis.com/auth/pos
I/GLSUser ( 2041): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/android_video https://www.googleapis.com/auth/youtube https://www.googleapis.com/auth/pos without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2041): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2041): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/AudioCapabilities( 7123): Unsupported mime audio/eac3
V/GLSActivity( 2041): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/AudioCapabilities( 7123): Unsupported mime audio/ac3
W/AudioCapabilities( 7123): Unsupported mime audio/g726
W/AudioCapabilities( 7123): Unsupported mime audio/wma-voice
W/AudioCapabilities( 7123): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7123): Unsupported mime audio/adpcm
W/VideoCapabilities( 7123): Unsupported mime video/theora
,W/VideoCapabilities( 7123): Unsupported mime video/mjpg
V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,D/LgeQuickCoverNLService( 1413): onNotificationPosted
I/art     ( 1032): Explicit concurrent mark sweep GC freed 26586(1224KB) AllocSpace objects, 8(640KB) LOS objects, 33% free, 44MB/66MB, paused 1.244ms total 73.733ms
,E/PlayMovies( 7123): GmsAccountManagerWrapper.blockingGetAuthTokenInternal:100 Cannot get user auth
E/PlayMovies( 7123): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/PlayMovies( 7123): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/PlayMovies( 7123): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/PlayMovies( 7123): 	at com.google.android.videos.accounts.GmsAccountManagerWrapper.blockingGetAuthTokenInternal(GmsAccountManagerWrapper.java:85)
E/PlayMovies( 7123): 	at com.google.android.videos.accounts.AccountManagerWrapper.blockingGetAuthToken(AccountManagerWrapper.java:186)
E/PlayMovies( 7123): 	at com.google.android.videos.accounts.AccountManagerWrapper.blockingAuthenticate(AccountManagerWrapper.java:162)
E/PlayMovies( 7123): 	at com.google.android.videos.store.SyncService$SyncAdapter.onPerformSync(SyncService.java:225)
E/PlayMovies( 7123): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/SmartCoverUpdateMonitor( 1413): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1413): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1413): handleNotificationPosted(true)
D/QuickCircle( 1413): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1413): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): post do just update job
D/LgeQuickCoverNotificationData( 1413): showAll3
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1413): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  2
I/ActivityManager( 1032): Killing 6567:com.android.gallery3d/u0a27 (adj 15): empty #17
D/SyncManager( 1032): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.videos.sync, PERIODIC, currentRunTime 40510, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager( 1032): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.videos.sync, PERIODIC, currentRunTime 155995, reason: Periodic
,D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
W/libprocessgroup( 1032): failed to open /acct/uid_10027/pid_6567/cgroup.procs: No such file or directory
,E/LgeQuickCoverOverlayWindow( 1413): updateNotificationData: count=3
D/QuickStatusbarLayout( 1413): Notification difference=198
D/QuickStatusbarLayout( 1413): child = android.widget.LinearLayout{10c851c6 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
E/Auth.Api.Credentials( 2333): [CredentialSyncAdapter] Unknown sync event.
,V/GLSActivity( 2041): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2041): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.docs, service: oauth2: https://www.googleapis.com/auth/drive
I/GLSUser ( 2041): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2041): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2041): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2041): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
,I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2041): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2041): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2041): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2041): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2041): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2041): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2041): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1413): onNotificationPosted
W/PsynchoHelperImpl( 7085): Error fetching or saving configuration
W/PsynchoHelperImpl( 7085): java.io.IOException: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
W/PsynchoHelperImpl( 7085): 	at Op.a(ApiaryPsynchoConfigurationAccessor.java:145)
W/PsynchoHelperImpl( 7085): 	at Op.a(ApiaryPsynchoConfigurationAccessor.java:215)
W/PsynchoHelperImpl( 7085): 	at OQ.a(PsynchoHelperImpl.java:60)
W/PsynchoHelperImpl( 7085): 	at agr.a(DriveSpecificSyncManager.java:27)
W/PsynchoHelperImpl( 7085): 	at agO.a(LegacySyncManager.java:678)
W/PsynchoHelperImpl( 7085): 	at agO.b(LegacySyncManager.java:582)
W/PsynchoHelperImpl( 7085): 	at agO.a(LegacySyncManager.java:467)
W/PsynchoHelperImpl( 7085): 	at agO.a(LegacySyncManager.java:97)
W/PsynchoHelperImpl( 7085): 	at agQ.run(LegacySyncManager.java:419)
W/PsynchoHelperImpl( 7085): 	at ami.a(NetworkUtilitiesImpl.java:31)
W/PsynchoHelperImpl( 7085): 	at agP.run(LegacySyncManager.java:416)
W/PsynchoHelperImpl( 7085): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
W/PsynchoHelperImpl( 7085): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
W/PsynchoHelperImpl( 7085): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
W/PsynchoHelperImpl( 7085): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
W/PsynchoHelperImpl( 7085): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
W/PsynchoHelperImpl( 7085): 	at android.os.Binder.execTransact(Binder.java:446)
D/SmartCoverUpdateMonitor( 1413): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1413): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1413): handleNotificationPosted(true)
D/QuickCircle( 1413): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1413): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): post do just update job
D/LgeQuickCoverNotificationData( 1413): showAll3
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1413): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1413): updateNotificationData: count=3
I/GLSUser ( 2041): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 2041): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2041): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2041): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2041): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/QuickStatusbarLayout( 1413): Notification difference=198
D/QuickStatusbarLayout( 1413): child = android.widget.LinearLayout{10c851c6 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1413): onNotificationPosted
D/SmartCoverUpdateMonitor( 1413): received broadcast com.lge.intent.action.NLDataPosted
W/GLSActivity( 2041): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2041): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2041): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2041): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2041): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2041): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2041): 	at android.os.Binder.execTransact(Binder.java:446)
E/SmartCoverUpdateMonitor( 1413): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1413): handleNotificationPosted(true)
D/QuickCircle( 1413): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1413): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): post do just update job
D/LgeQuickCoverNotificationData( 1413): showAll3
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1413): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1413): updateNotificationData: count=3
D/ContactsSyncAdapter( 2041): innerSync failed
D/ContactsSyncAdapter( 2041): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2041): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2041): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2041): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2041): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2041): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2041): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2041): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2041): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2041): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2041): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2041): 	at android.os.Binder.execTransact(Binder.java:446)
D/SyncManager( 1032): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 153342, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
,I/GLSUser ( 2041): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.docs, service: writely
I/GLSUser ( 2041): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> writely without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2041): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2041): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/QuickStatusbarLayout( 1413): Notification difference=198
D/QuickStatusbarLayout( 1413): child = android.widget.LinearLayout{10c851c6 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
V/GLSActivity( 2041): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1413): onNotificationPosted
W/GLSActivity( 2041): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2041): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2041): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2041): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2041): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2041): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2041): 	at android.os.Binder.execTransact(Binder.java:446)
D/SmartCoverUpdateMonitor( 1413): received broadcast com.lge.intent.action.NLDataPosted
E/HttpIssuerBase( 7085): Attempt to consume entity of HttpIssuer when no request is executing.
E/HttpIssuerBase( 7085): Attempt to close HttpIssuer when no request is executing.
E/HttpIssuerBase( 7085): java.io.IOException
E/HttpIssuerBase( 7085): 	at TG.b(HttpIssuerBase.java:188)
E/HttpIssuerBase( 7085): 	at Tj.b(DefaultAuthenticatedHttpIssuer.java:151)
E/HttpIssuerBase( 7085): 	at afE.a(AccountMetadataUpdater.java:227)
E/HttpIssuerBase( 7085): 	at afE.a(AccountMetadataUpdater.java:140)
E/HttpIssuerBase( 7085): 	at agO.a(LegacySyncManager.java:828)
E/HttpIssuerBase( 7085): 	at agO.b(LegacySyncManager.java:588)
E/HttpIssuerBase( 7085): 	at agO.a(LegacySyncManager.java:467)
E/HttpIssuerBase( 7085): 	at agO.a(LegacySyncManager.java:97)
E/HttpIssuerBase( 7085): 	at agQ.run(LegacySyncManager.java:419)
E/HttpIssuerBase( 7085): 	at ami.a(NetworkUtilitiesImpl.java:31)
E/HttpIssuerBase( 7085): 	at agP.run(LegacySyncManager.java:416)
E/SmartCoverUpdateMonitor( 1413): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1413): handleNotificationPosted(true)
D/QuickCircle( 1413): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1413): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): post do just update job
D/LgeQuickCoverNotificationData( 1413): showAll3
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1413): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
E/SyncManager( 7085): AuthenticatorException
E/SyncManager( 7085): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/SyncManager( 7085): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/SyncManager( 7085): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/SyncManager( 7085): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/SyncManager( 7085): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/SyncManager( 7085): 	at android.os.Binder.execTransact(Binder.java:446)
W/GAV2    ( 7085): SyncM,anager-thalitester@gmail.com: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
D/WifiService( 1032): releaseWifiLockLocked: WifiLock{SyncManager type=1 binder=android.os.BinderProxy@1f565dcb}
E/LgeQuickCoverOverlayWindow( 1413): updateNotificationData: count=3
,D/SyncManager( 1032): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.docs, PERIODIC, currentRunTime 40495, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
I/ActivityManager( 1032): Killing 6683:com.lge.drmservice/u0a62 (adj 15): empty #17
D/SyncManager( 1032): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.apps.docs, PERIODIC, currentRunTime 156207, reason: Periodic
,D/QuickStatusbarLayout( 1413): Notification difference=198
D/QuickStatusbarLayout( 1413): child = android.widget.LinearLayout{10c851c6 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/libprocessgroup( 1032): failed to open /acct/uid_10062/pid_6683/cgroup.procs: No such file or directory
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=26.9, 0.0, 0.0  rx=21.4 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:-1058841833] gl rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=26.9, 0.0, 0.0  rx=21.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1058841830] gl rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,I/ThermalEngine(  337): Thermal-Server: Thermal received msg from  override
,I/Thermal-Lib( 3092): Thermal-Lib-Client: Client request sent
I/ActivityManager( 1032): Killing 6591:com.android.chrome/u0a57 (adj 15): empty #17
W/libprocessgroup( 1032): failed to open /acct/uid_10057/pid_6591/cgroup.procs: No such file or directory
,I/GAV2    ( 7024): Thread[GAThread,5,main]: No campaign data found.
,D/UEI.SmartControl( 6989): Internal timer expired: 1
,D/UEI.SmartControl( 6989): unbind internal service
,D/UEI.SmartControl( 6989): Service.onUnbind: IControl
,D/UEI.SmartControl( 6989): Service.onDestroy
D/UEI.SmartControl( 6989): Lock is in USE false
D/UEI.SmartControl( 6989): unbind internal service
W/System.err( 6989): java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@3db1e4ea
W/System.err( 6989): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
,W/System.err( 6989): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
W/System.err( 6989): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
W/System.err( 6989): 	at com.uei.control.Service.c(Unknown Source)
W/System.err( 6989): 	at com.uei.control.Service.onDestroy(Unknown Source)
W/System.err( 6989): 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
W/System.err( 6989): 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
W/System.err( 6989): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
W/System.err( 6989): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6989): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6989): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 6989): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6989): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6989): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 6989): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 6989): java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@3db1e4ea
D/serial_port( 6989): close(fd = 25)
I/UEI.SmartControl( 6989): Serial port is closed.
I/UEI.SmartControl( 6989): Serial port is closed.
D/UEI.SmartControl( 6989): Blaster closed
D/UEI.SmartControl( 6989): Shut down QS...
D/UEI.SmartControl( 6989): Stopping QS lib
D/UEI.SmartControl( 6989): QS lib stop result = true
D/UEI.SmartControl( 6989): Stopped QS lib
,D/UEI.SmartControl( 6989): Stopped file observer...
D/UEI.SmartControl( 6989): QS shutdown complete
E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=23.5, 0.0, 0.0  rx=18.7 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1058838809] gl rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=23.5, 0.0, 0.0  rx=18.7 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1058838808] gl rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,I/ActivityManager( 1032): Killing 6617:com.lge.email/u0a23 (adj 15): empty #17
,W/libprocessgroup( 1032): failed to open /acct/uid_10023/pid_6617/cgroup.procs: No such file or directory
,I/GAV2    ( 7085): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager( 1032): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=7233 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager( 1032): RTC_WAKEUP set : Alarm{12e00f26 type 0 when 1454935077087 com.android.vending} when 1454935077087
,D/Finsky  ( 7233): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/LgDataFeature( 7233): LgDataFeature() Constructor: none
D/LgDataFeature( 7233): LgDataFeature() Constructor Done, null
,D/Finsky  ( 7233): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/ActivityManager( 1032): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=7274 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=12.2, 0.0, 0.0  rx=9.8 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1058835788] gl rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=12.2, 0.0, 0.0  rx=9.8 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1058835787] gl rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,W/Settings( 7233): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 7233): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ResourcesManager( 7274): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7274): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/Finsky  ( 7233): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7233): [1] 2.run: Finished loading 1 libraries.
,V/DownloadManager( 3323): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3323): created cursor android.database.sqlite.SQLiteCursor@971897 on behalf of 7233
D/Finsky  ( 7233): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/MultiDex( 7274): VM with version 2.1.0 has multidex support
,I/MultiDex( 7274): install
I/MultiDex( 7274): VM has multidex support, MultiDex support library is disabled.
D/Finsky  ( 7233): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
V/JNIHelp ( 7274): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,V/SIM_STK ( 1032): Menu title from STK is T-Mobile
,W/ActivityThread( 7274): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7274): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3949c9ab: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7274): Installed default security provider GmsCore_OpenSSL
D/GCM     ( 2041): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AuthorizationBluetoothService( 2041): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 2333): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
D/WearableService( 7146): callingUid 10005, callindPid: 7146
,E/MDM     ( 1805): [87] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
D/LocationInitializer( 2333): Restart initialization of location
,V/GLSActivity( 2041): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2041): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2041): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2041): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2041): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2041): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/Finsky  ( 7233): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,D/Finsky  ( 7233): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7233): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 7233): [1] 5.onFinished: Scheduling replication attempt 3.
I/ActivityManager( 1032): Killing 5160:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,W/libprocessgroup( 1032): failed to open /acct/uid_1000/pid_5160/cgroup.procs: No such file or directory
,V/AlarmManager( 1032): RTC_WAKEUP set : Alarm{2fc5c63f type 0 when 1454935078470 com.android.vending} when 1454935078470
,D/Finsky  ( 7233): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
V/GLSActivity( 2041): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2041): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2041): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2041): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2041): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2041): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 7233): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 2041): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2041): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2041): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2041): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2041): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2041): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2041): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2041): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2041): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2041): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2041): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2041): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 7233): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/SIM_STK ( 1032): Menu title from STK is T-Mobile
,V/GLSActivity( 2041): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2041): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 2041): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2041): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2041): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2041): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1032): Explicit concurrent mark sweep GC freed 33332(1486KB) AllocSpace objects, 6(480KB) LOS objects, 33% free, 44MB/66MB, paused 2.917ms total 147.809ms
,W/Finsky  ( 7233): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 7233): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
D/Finsky  ( 7233): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7233): [1] DailyHygiene.reschedule: Giving up. (failures=6)
D/Finsky  ( 7233): [1] VerifyInstalledPackagesReceiver.onReceive: Verify installed apps requested
,D/DeviceConnectionService( 1805): client connected with version: 7571000
,D/Finsky  ( 7233): [1] VerifyInstalledPackagesTask.onPreExecute: Verifying installed apps
V/SIM_STK ( 1032): Menu title from STK is T-Mobile
,I/art     ( 2041): Explicit concurrent mark sweep GC freed 24611(1455KB) AllocSpace objects, 11(1584KB) LOS objects, 50% free, 30MB/62MB, paused 1.901ms total 53.903ms
,I/[SystemUI]TimeTickManager( 1463): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1463): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1463): called onTimeUpdated()
,I/[SystemUI]Clock( 1463): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1463): called onTimeUpdated()
,I/[SystemUI]DateView( 1463): called onTimeUpdated()
,I/[SystemUI]DateView( 1463): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1463): handleTimeUpdate
,I/[SystemUI]TimeTickManager( 1463): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1463): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1463): called onTimeUpdated()
,I/[SystemUI]Clock( 1463): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1463): called onTimeUpdated()
,I/[SystemUI]DateView( 1463): called onTimeUpdated()
I/[SystemUI]DateView( 1463): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1463): handleTimeUpdate
E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=6.1, 0.0, 0.0  rx=4.9 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1058832772] gl rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=6.1, 0.0, 0.0  rx=4.9 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1058832768] gl rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,I/[SystemUI]QPairHandler( 1463): onReceive = android.intent.action.PACKAGE_CHANGED
,D/SplitUIService( 1857): replaced split : contains_com.google.android.talk / true
,I/InputReader( 1032): Reconfiguring input devices.  changes=0x00000010
,D/SplitUIManager( 1857): split_name #11 / not available #0
I/SplitUIService( 1857): split app #11
,I/ActivityManager( 1032): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7343 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/InputReader( 1032): Reconfiguring input devices.  changes=0x00000010
I/[SystemUI]QSlideListController( 1463): onReceive = android.intent.action.PACKAGE_CHANGED
,I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1463): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.talk
I/[SystemUI]QPairHandler( 1463): onReceive = android.intent.action.PACKAGE_CHANGED
,I/[SystemUI]QSlideListController( 1463): onReceive = android.intent.action.PACKAGE_CHANGED
D/administrator( 1032): Handling package changes for user 0
,I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1463): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.videos
I/[LGHome]EVENT( 2020): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000010 (has extras) }
I/[LGHome]EVENT( 2020): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.videos flg=0x4000010 (has extras) }
,W/ResourcesManager( 2020): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/[LGHome]Launcher( 2020): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/AppUp4:AppBoxCP( 7343): onCreate
W/AppUp4:DB( 7343):  [AppBoxDatabaseHelper] construct
,I/[LGHome]Launcher( 2020): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/AppUp4:DB( 7343):  setFingerPrint start
I/AppUp4:DB( 7343):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 7343):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7343):  SDK version = 21
I/AppUp4:DB( 7343):  beforefinger == newfinger no write in DB
,I/NotificationService( 1032): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService( 1032): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000010 (has extras) }
D/AppUp4:AppBoxApplication( 7343): AppBoxApplication onCreate()
W/ResourcesManager( 1032): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/AppUp4:CustModeStarterReceiver( 7343): onReceive
D/administrator( 1032): Handling package changes for user 0
I/NotificationService( 1032): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService( 1032): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.videos flg=0x4000010 (has extras) }
,D/LgDataFeature( 7343): LgDataFeature() Constructor: none
D/LgDataFeature( 7343): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7343): Context : android.app.ReceiverRestrictedContext@3c1a7b63
,D/AppUp4:CustFacade( 7343): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7343): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7343): begin check event
I/AppUp4:CustModeStarterReceiver( 7343): Event For Nothing, skip.
W/ResourcesManager( 1032): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourceType( 1032): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/ActivityManager( 1032): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7378 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/ActivityManager( 1032): Killing 6861:com.qualcomm.timeservice/1000 (adj 15): empty #17
W/libprocessgroup( 1032): failed to open /acct/uid_1000/pid_6861/cgroup.procs: No such file or directory
I/[LGHome]EVENT( 2020): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,W/ResourceType( 1032): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/[LGHome]EVENT( 2020): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
W/ResourcesManager( 7378): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7378): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7378): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7378): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7378): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 7378): BUILD Country: EU
I/SystemConfig( 7378): BUILD Operator: OPEN
,I/ActivityManager( 1032): Killing 6881:com.android.calendar/u0a13 (adj 15): empty #17
,W/libprocessgroup( 1032): failed to open /acct/uid_10013/pid_6881/cgroup.procs: No such file or directory
,I/ActivityManager( 1032): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7405 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/SystemConfig( 7378): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7378): existFile = false
I/SystemConfig( 7378): canReadFile = false
I/SystemConfig( 7378): systemFeature RCS result false
D/SystemConfig( 7378): refreshRcsSupport() :false
,W/ResourcesManager( 7405): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7405): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7405): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 7405): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/AppConfig( 7405): Total System Memory = 2995761152
,D/SystemHelper( 7405): region [EU], country [EU], operator [OPEN], sub-operator []
I/ActivityManager( 1032): Killing 6835:com.lge.clock/u0a10 (adj 15): empty #17
,W/libprocessgroup( 1032): failed to open /acct/uid_10010/pid_6835/cgroup.procs: No such file or directory
,I/UpdateIcingCorporaServi( 4250): Updating corpora: APPS=com.google.android.talk, CONTACTS=MAYBE
I/ActivityManager( 1032): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7426 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,V/SIM_STK ( 1032): Menu title from STK is T-Mobile
W/ResourcesManager( 4250): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 4250): UpdateCorporaTask done [took 88 ms] updated apps [took 88 ms] 
I/LockScreenSettings( 7426): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7426): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7426): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7426): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7426): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7426): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
D/LockScreenSettings( 7426): Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,I/ActivityManager( 1032): Killing 6707:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,W/libprocessgroup( 1032): failed to open /acct/uid_10085/pid_6707/cgroup.procs: No such file or directory
,D/PackageBroadcastService( 2333): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.talk
I/AppUp4:CustModeStarterReceiver( 7343): onReceive
,I/PeopleContactsSync( 2333): CP2 sync disabled
,D/AppUp4:CustFacade( 7343): Context : android.app.ReceiverRestrictedContext@3c1a7b63
D/AppUp4:CustFacade( 7343): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7343): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7343): begin check event
I/AppUp4:CustModeStarterReceiver( 7343): Event For Nothing, skip.
I/UpdateIcingCorporaServi( 4250): Updating corpora: APPS=com.google.android.videos, CONTACTS=MAYBE
,D/LockScreenSettings( 7426): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7426): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7426): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7426): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7426): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
D/LockScreenSettings( 7426): Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
D/PackageBroadcastService( 2333): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.videos
,I/PeopleContactsSync( 2333): CP2 sync disabled
,V/SIM_STK ( 1032): Menu title from STK is T-Mobile
I/UpdateIcingCorporaServi( 4250): UpdateCorporaTask done [took 127 ms] updated apps [took 126 ms] 
,I/ActivityManager( 1032): Killing 6907:com.google.android.talk/u0a72 (adj 15): empty #17
,W/libprocessgroup( 1032): failed to open /acct/uid_10072/pid_6907/cgroup.procs: No such file or directory
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=3.6, 0.0, 0.0  rx=3.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1058829748] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=3.6, 0.0, 0.0  rx=3.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1058829745] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 137553871149; DSPS: 4648188; Offset : -4311968523
,I/ActivityManager( 1032): Waited long enough for: ServiceRecord{3bc35230 u0 com.google.android.music/.download.artwork.ArtDownloadService}
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=2.3, 0.0, 0.0  rx=2.0 bcn=0 [on:0 tx:0 rx:0 period:2999] from screen [on:0 period:-1058826719] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=2.3, 0.0, 0.0  rx=2.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1058826718] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1058823699] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1058823696] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1058820676] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1058820666] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
D/PowerManagerServiceEx( 1032): acquireWakeLockInternal: lock=515277617, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1032
,V/AlarmManager( 1032): ELAPSED_WAKEUP set : Alarm{2b211b97 type 2 when 146563 android} when 146563
D/[Concierge]Service( 2604): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1032): releaseWakeLockInternal: lock=515277617 [*alarm*], flags=0x0
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1058817643] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1058817640] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1032):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1032):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1032):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,E/WifiStateMachine( 1032):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1032):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1058814617] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1058814616] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1058811596] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1058811586] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 157555482548; DSPS: 5303601; Offset : -4311974738
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1058808565] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1058808561] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,V/AlarmManager( 1032): RTC_WAKEUP set : Alarm{1399bf08 type 0 when 1454935098710 com.android.vending} when 1454935098710
,V/SIM_STK ( 1032): Menu title from STK is T-Mobile
,V/GLSActivity( 2041): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2041): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2041): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2041): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2041): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2041): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7233): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 7233): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 7233): [1] 5.onFinished: Scheduling replication attempt 4.
E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1058805537] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1058805525] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1058802504] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1058802501] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1058799469] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1058799466] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1058796443] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1058796440] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1058793412] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1058793409] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1058790385] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1058790381] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,V/AlarmManager( 1032): ELAPSED_WAKEUP set : Alarm{16564aaa type 2 when 177129 android} when 177129
,V/GLSActivity( 2041): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2041): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 2041): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2041): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2041): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2041): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2041): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2041): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2041): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2041): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2041): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2041): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2041): 	at android.os.Binder.execTransact(Binder.java:446)
D/ContactsSyncAdapter( 2041): innerSync failed
D/ContactsSyncAdapter( 2041): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2041): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2041): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2041): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2041): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2041): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2041): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2041): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2041): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2041): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2041): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2041): 	at android.os.Binder.execTransact(Binder.java:446)
,W/ResourcesManager( 1413): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1413): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/LgeQuickCoverNLService( 1413): onNotificationPosted
D/SmartCoverUpdateMonitor( 1413): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1413): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1413): handleNotificationPosted(true)
D/QuickCircle( 1413): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1413): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): post do just update job
D/LgeQuickCoverNotificationData( 1413): showAll3
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1413): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
W/ResourcesManager( 1413): Asset path '/system/framework/com.lge.systemui.jar' does not exist or contains no resources.
W/ResourcesManager( 1413): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 177562855978; DSPS: 5959203; Offset : -4311985859
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1413): updateNotificationData: count=3
,D/QuickStatusbarLayout( 1413): Notification difference=198
D/QuickStatusbarLayout( 1413): child = android.widget.LinearLayout{10c851c6 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/BooksSync( 6532): Starting books sync
,D/SyncManager( 1032): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 153342, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager( 1032): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 240629, reason: 10019
D/BooksSync( 6532): started syncMyEbooks
,V/GLSActivity( 2041): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2041): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2041): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2041): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2041): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2041): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1413): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1413): received broadcast com.lge.intent.action.NLDataPosted
W/GLSActivity( 2041): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2041): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2041): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2041): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2041): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2041): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2041): 	at android.os.Binder.execTransact(Binder.java:446)
E/SmartCoverUpdateMonitor( 1413): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1413): handleNotificationPosted(true)
D/QuickCircle( 1413): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1413): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): post do just update job
D/LgeQuickCoverNotificationData( 1413): showAll3
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1413): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
E/BooksAccountManager( 6532): Authentication error
E/BooksAccountManager( 6532): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6532): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6532): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6532): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6532): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6532): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6532): null auth token
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1413): updateNotificationData: count=3
D/QuickStatusbarLayout( 1413): Notification difference=198
D/QuickStatusbarLayout( 1413): child = android.widget.LinearLayout{10c851c6 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6532): Error response from books API: {
W/ApiaryClient( 6532):  "error": {
W/ApiaryClient( 6532):   "errors": [
W/ApiaryClient( 6532):    {
W/ApiaryClient( 6532):     "domain": "global",
W/ApiaryClient( 6532):     "reason": "required",
W/ApiaryClient( 6532):     "message": "Login Required",
W/ApiaryClient( 6532):     "locationType": "header",
W/ApiaryClient( 6532):     "location": "Authorization"
W/ApiaryClient( 6532):    }
W/ApiaryClient( 6532):   ],
W/ApiaryClient( 6532):   "code": 401,
W/ApiaryClient( 6532):   "message": "Login Required"
W/ApiaryClient( 6532):  }
W/ApiaryClient( 6532): }
,W/ApiaryClient( 6532): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6532): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3929697830301934194&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6532): Headers:
W/ApiaryClient( 6532): accept-encoding: [gzip]
W/ApiaryClient( 6532): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6532): gdata-version: 2
,V/GLSActivity( 2041): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2041): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2041): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2041): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2041): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2041): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1413): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1413): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1413): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1413): handleNotificationPosted(true)
D/QuickCircle( 1413): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1413): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): post do just update job
D/LgeQuickCoverNotificationData( 1413): showAll3
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1413): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1413): updateNotificationData: count=3
W/GLSActivity( 2041): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2041): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2041): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2041): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2041): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2041): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2041): 	at android.os.Binder.execTransact(Binder.java:446)
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1058787356] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/QuickStatusbarLayout( 1413): Notification difference=198
D/QuickStatusbarLayout( 1413): child = android.widget.LinearLayout{10c851c6 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1058787354] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
E/BooksAccountManager( 6532): Authentication error
E/BooksAccountManager( 6532): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6532): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6532): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6532): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6532): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6532): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6532): null auth token
,W/ApiaryClient( 6532): Error response from books API: {
W/ApiaryClient( 6532):  "error": {
W/ApiaryClient( 6532):   "errors": [
W/ApiaryClient( 6532):    {
W/ApiaryClient( 6532):     "domain": "global",
W/ApiaryClient( 6532):     "reason": "required",
W/ApiaryClient( 6532):     "message": "Login Required",
W/ApiaryClient( 6532):     "locationType": "header",
W/ApiaryClient( 6532):     "location": "Authorization"
W/ApiaryClient( 6532):    }
W/ApiaryClient( 6532):   ],
W/ApiaryClient( 6532):   "code": 401,
W/ApiaryClient( 6532):   "message": "Login Required"
W/ApiaryClient( 6532):  }
W/ApiaryClient( 6532): }
,W/ApiaryClient( 6532): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized,
W/ApiaryClient( 6532): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3929697830301934194&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6532): Headers:
W/ApiaryClient( 6532): accept-encoding: [gzip]
W/ApiaryClient( 6532): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6532): gdata-version: 2
V/GLSActivity( 2041): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2041): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2041): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2041): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2041): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2041): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1413): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1413): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1413): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1413): handleNotificationPosted(true)
D/QuickCircle( 1413): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1413): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): post do just update job
D/LgeQuickCoverNotificationData( 1413): showAll3
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1413): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
,E/LgeQuickCoverOverlayWindow( 1413): updateNotificationData: count=3
W/GLSActivity( 2041): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2041): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2041): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2041): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2041): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2041): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2041): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6532): Authentication error
E/BooksAccountManager( 6532): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6532): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6532): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6532): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6532): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6532): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6532): null auth token
D/QuickStatusbarLayout( 1413): Notification difference=198
D/QuickStatusbarLayout( 1413): child = android.widget.LinearLayout{10c851c6 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6532): Error response from books API: {
W/ApiaryClient( 6532):  "error": {
W/ApiaryClient( 6532):   "errors": [
W/ApiaryClient( 6532):    {
W/ApiaryClient( 6532):     "domain": "global",
W/ApiaryClient( 6532):     "reason": "required",
W/ApiaryClient( 6532):     "message": "Login Required",
W/ApiaryClient( 6532):     "locationType": "header",
W/ApiaryClient( 6532):     "location": "Authorization"
W/ApiaryClient( 6532):    }
W/ApiaryClient( 6532):   ],
W/ApiaryClient( 6532):   "code": 401,
W/ApiaryClient( 6532):   "message": "Login Required"
W/ApiaryClient( 6532):  }
W/ApiaryClient( 6532): }
,W/ApiaryClient( 6532): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6532): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3929697830301934194&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6532): Headers:
W/ApiaryClient( 6532): accept-encoding: [gzip]
W/ApiaryClient( 6532): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6532): gdata-version: 2
,V/AlarmManager( 1032): RTC_WAKEUP set : Alarm{312fbde3 type 0 when 1454935126263 com.android.vending} when 1454935126263
,E/BooksSync( 6532): Soft error: 
E/BooksSync( 6532): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6532): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3929697830301934194&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6532): Headers:
E/BooksSync( 6532): accept-encoding: [gzip]
E/BooksSync( 6532): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6532): gdata-version: 2
E/BooksSync( 6532): 
E/BooksSync( 6532): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6532): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6532): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6532): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6532): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6532): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6532): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6532): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6532): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6532): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6532): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6532): {
E/BooksSync( 6532):  "error": {
E/BooksSync( 6532):   "errors": [
E/BooksSync( 6532):    {
E/BooksSync( 6532):     "domain": "global",
E/BooksSync( 6532):     "reason": "required",
E/BooksSync( 6532):     "message": "Login Required",
E/BooksSync( 6532):     "locationType": "header",
E/BooksSync( 6532):     "location": "Authorization"
E/BooksSync( 6532):    }
E/BooksSync( 6532):   ],
E/BooksSync( 6532):   "code": 401,
E/BooksSync( 6532):   "message": "Login Required"
E/BooksSync( 6532):  }
E/BooksSync( 6532): }
E/BooksSync( 6532): 
E/BooksSync( 6532): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6532): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6532): 	... 8 more
,E/BooksSync( 6532): Sync error
E/BooksSync( 6532): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6532): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3929697830301934194&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6532): Headers:
E/BooksSync( 6532): accept-encoding: [gzip]
E/BooksSync( 6532): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6532): gdata-version: 2
E/BooksSync( 6532): 
E/BooksSync( 6532): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6532): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6532): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6532): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6532): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6532): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6532): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6532): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6532): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6532): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6532): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6532): {
E/BooksSync( 6532):  "error": {
E/BooksSync( 6532):   "errors": [
E/BooksSync( 6532):    {
E/BooksSync( 6532):     "domain": "global",
E/BooksSync( 6532):     "reason": "required",
E/BooksSync( 6532):     "message": "Login Required",
E/BooksSync( 6532):     "locationType": "header",
E/BooksSync( 6532):     "location": "Authorization"
E/BooksSync( 6532):    }
E/BooksSync( 6532):   ],
E/BooksSync( 6532):   "code": 401,
E/BooksSync( 6532):   "message": "Login Required"
E/BooksSync( 6532):  }
E/BooksSync( 6532): }
E/BooksSync( 6532): 
E/BooksSync( 6532): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6532): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6532): 	... 8 more
I/BooksSync( 6532): Finished books sync
,D/SyncManager( 1032): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 153997, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/SIM_STK ( 1032): Menu title from STK is T-Mobile
,V/GLSActivity( 2041): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1032): Explicit concurrent mark sweep GC freed 48974(2MB) AllocSpace objects, 6(608KB) LOS objects, 33% free, 44MB/66MB, paused 2.659ms total 103.532ms
,I/GLSUser ( 2041): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2041): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2041): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2041): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2041): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7233): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7233): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7233): [1] 5.onFinished: Scheduling replication attempt 5.
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=1.7, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1058784339] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=1.7, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1058784337] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=3.3, 0.0, 0.0  rx=3.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1058781314] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=3.3, 0.0, 0.0  rx=3.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1058781311] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=1.7, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1058778285] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=1.7, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1058778275] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=1.3, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1058775253] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=1.3, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1058775250] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1463): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1463): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1463): called onTimeUpdated()
,I/[SystemUI]Clock( 1463): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1463): called onTimeUpdated()
,I/[SystemUI]DateView( 1463): called onTimeUpdated()
,I/[SystemUI]DateView( 1463): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1463): handleTimeUpdate
E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1058772226] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:15] from screen [on:0 period:-1058772211] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1058769190] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1058769187] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 197564909355; DSPS: 6614630; Offset : -4311977888
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1058766167] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1058766158] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1058763137] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1058763124] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,D/PowerManagerServiceEx( 1032): acquireWakeLockInternal: lock=515277617, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1032
,V/AlarmManager( 1032): RTC_WAKEUP set : Alarm{33a3ad37 type 0 when 1454935148676 com.android.vending} when 1454935148676
,D/[Concierge]Service( 2604): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1032): releaseWakeLockInternal: lock=515277617 [*alarm*], flags=0x0
,V/SIM_STK ( 1032): Menu title from STK is T-Mobile
,V/GLSActivity( 2041): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2041): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2041): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2041): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2041): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2041): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7233): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7233): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 7233): [1] 5.onFinished: Giving up after 6 failures.
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1058760104] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1058760101] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,V/AlarmManager( 1032): ELAPSED_WAKEUP set : Alarm{299fef41 type 2 when 207213 android} when 207213
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1058757079] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1058757078] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1058754061] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1058754058] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1058751035] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1058751026] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 217566990858; DSPS: 7270058; Offset : -4311971555
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1058748006] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1058747997] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1058744976] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1058744964] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1058741942] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1058741939] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1058738913] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1058738910] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1058735888] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1058735885] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
V/AlarmManager( 1032): ELAPSED_WAKEUP set : Alarm{144dce6 type 2 when 207340 android} when 207340
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1058732858] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:8] from screen [on:0 period:-1058732850] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1058729833] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1058729829] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 237569055538; DSPS: 7925486; Offset : -4311982096
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1058726803] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1058726800] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1058723774] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1058723771] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1058720750] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1058720747] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,V/AlarmManager( 1032): ELAPSED_WAKEUP set : Alarm{5845227 type 2 when 246948 android} when 246948
,I/BooksSync( 6532): Starting books sync
,D/BooksSync( 6532): started syncMyEbooks
,V/GLSActivity( 2041): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2041): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2041): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2041): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2041): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2041): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1413): onNotificationPosted
D/SmartCoverUpdateMonitor( 1413): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1413): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1413): handleNotificationPosted(true)
D/QuickCircle( 1413): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1413): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): post do just update job
D/LgeQuickCoverNotificationData( 1413): showAll3
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1413): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1413): updateNotificationData: count=3
W/GLSActivity( 2041): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2041): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2041): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2041): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2041): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2041): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2041): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6532): Authentication error
E/BooksAccountManager( 6532): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6532): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6532): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6532): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6532): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6532): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6532): null auth token
D/QuickStatusbarLayout( 1413): Notification difference=198
D/QuickStatusbarLayout( 1413): child = android.widget.LinearLayout{10c851c6 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6532): Error response from books API: {
W/ApiaryClient( 6532):  "error": {
W/ApiaryClient( 6532):   "errors": [
W/ApiaryClient( 6532):    {
W/ApiaryClient( 6532):     "domain": "global",
W/ApiaryClient( 6532):     "reason": "required",
W/ApiaryClient( 6532):     "message": "Login Required",
W/ApiaryClient( 6532):     "locationType": "header",
W/ApiaryClient( 6532):     "location": "Authorization"
W/ApiaryClient( 6532):    }
W/ApiaryClient( 6532):   ],
W/ApiaryClient( 6532):   "code": 401,
W/ApiaryClient( 6532):   "message": "Login Required"
W/ApiaryClient( 6532):  }
W/ApiaryClient( 6532): }
,W/ApiaryClient( 6532): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6532): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-5397024584537003708&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6532): Headers:
W/ApiaryClient( 6532): accept-encoding: [gzip]
W/ApiaryClient( 6532): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6532): gdata-version: 2
,V/GLSActivity( 2041): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2041): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2041): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2041): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2041): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2041): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1413): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1413): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1413): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1413): handleNotificationPosted(true)
D/QuickCircle( 1413): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1413): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): post do just update job
D/LgeQuickCoverNotificationData( 1413): showAll3
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1413): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1413): updateNotificationData: count=3
W/GLSActivity( 2041): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2041): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2041): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2041): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2041): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2041): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2041): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6532): Authentication error
E/BooksAccountManager( 6532): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6532): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6532): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6532): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6532): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6532): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6532): null auth token
D/QuickStatusbarLayout( 1413): Notification difference=198
D/QuickStatusbarLayout( 1413): child = android.widget.LinearLayout{10c851c6 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,I/[SystemUI]LGPowerUI( 1463): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1463): On Skip Timer : true
,D/KeyguardUpdateMonitor( 1463): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 291
I/[SystemUI]LGPowerUI( 1463): onReceive = android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1928): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1928): Battery Level Remaining: 100%
D/LEDHandler( 1928): Battery Temp: 291, mChargingStatus=5, mChargingStop=false
,D/WifiController( 1032): battery changed pluggedType: 2
W/Settings( 1032): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1032): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 6194): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1463): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3976): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3976): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ApiaryClient( 6532): Error response from books API: {
W/ApiaryClient( 6532):  "error": {
W/ApiaryClient( 6532):   "errors": [
W/ApiaryClient( 6532):    {
W/ApiaryClient( 6532):     "domain": "global",
W/ApiaryClient( 6532):     "reason": "required",
W/ApiaryClient( 6532):     "message": "Login Required",
W/ApiaryClient( 6532):     "locationType": "header",
W/ApiaryClient( 6532):     "location": "Authorization"
W/ApiaryClient( 6532):    }
W/ApiaryClient( 6532):   ],
W/ApiaryClient( 6532):   "code": 401,
W/ApiaryClient( 6532):   "message": "Login Required"
W/ApiaryClient( 6532):  }
W/ApiaryClient( 6532): }
,W/ApiaryClient( 6532): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6532): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-5397024584537003708&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6532): Headers:
W/ApiaryClient( 6532): accept-encoding: [gzip]
W/ApiaryClient( 6532): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6532): gdata-version: 2
E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1058717721] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1058717720] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
V/GLSActivity( 2041): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2041): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2041): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2041): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2041): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2041): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1032): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1032): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1032): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1032): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1032): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1413): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1413): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1413): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1413): handleNotificationPosted(true)
D/QuickCircle( 1413): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1413): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): post do just update job
D/LgeQuickCoverNotificationData( 1413): showAll3
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1413): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1413): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1413): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1413): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1413): updateNotificationData: count=3
W/GLSActivity( 2041): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2041): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2041): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2041): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2041): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2041): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2041): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6532): Authentication error
E/BooksAccountManager( 6532): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6532): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6532): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6532): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6532): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6532): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6532): null auth token
D/QuickStatusbarLayout( 1413): Notification difference=198
D/QuickStatusbarLayout( 1413): child = android.widget.LinearLayout{10c851c6 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6532): Error response from books API: {
W/ApiaryClient( 6532):  "error": {
W/ApiaryClient( 6532):   "errors": [
W/ApiaryClient( 6532):    {
W/ApiaryClient( 6532):     "domain": "global",
W/ApiaryClient( 6532):     "reason": "required",
W/ApiaryClient( 6532):     "message": "Login Required",
W/ApiaryClient( 6532):     "locationType": "header",
W/ApiaryClient( 6532):     "location": "Authorization"
W/ApiaryClient( 6532):    }
W/ApiaryClient( 6532):   ],
W/ApiaryClient( 6532):   "code": 401,
W/ApiaryClient( 6532):   "message": "Login Required"
W/ApiaryClient( 6532):  }
W/ApiaryClient( 6532): }
,W/ApiaryClient( 6532): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6532): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-5397024584537003708&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6532): Headers:
W/ApiaryClient( 6532): accept-encoding: [gzip]
W/ApiaryClient( 6532): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6532): gdata-version: 2
,E/BooksSync( 6532): Soft error: 
E/BooksSync( 6532): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6532): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-5397024584537003708&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6532): Headers:
E/BooksSync( 6532): accept-encoding: [gzip]
E/BooksSync( 6532): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6532): gdata-version: 2
E/BooksSync( 6532): 
E/BooksSync( 6532): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6532): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6532): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6532): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6532): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6532): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6532): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6532): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6532): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6532): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6532): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6532): {
E/BooksSync( 6532):  "error": {
E/BooksSync( 6532):   "errors": [
E/BooksSync( 6532):    {
E/BooksSync( 6532):     "domain": "global",
E/BooksSync( 6532):     "reason": "required",
E/BooksSync( 6532):     "message": "Login Required",
E/BooksSync( 6532):     "locationType": "header",
E/BooksSync( 6532):     "location": "Authorization"
E/BooksSync( 6532):    }
E/BooksSync( 6532):   ],
E/BooksSync( 6532):   "code": 401,
E/BooksSync( 6532):   "message": "Login Required"
E/BooksSync( 6532):  }
E/BooksSync( 6532): }
E/BooksSync( 6532): 
E/BooksSync( 6532): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6532): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6532): 	... 8 more
,E/BooksSync( 6532): Sync error
E/BooksSync( 6532): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6532): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-5397024584537003708&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6532): Headers:
E/BooksSync( 6532): accept-encoding: [gzip]
E/BooksSync( 6532): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6532): gdata-version: 2
E/BooksSync( 6532): 
E/BooksSync( 6532): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6532): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6532): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6532): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6532): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6532): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6532): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6532): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6532): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6532): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6532): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6532): {
E/BooksSync( 6532):  "error": {
E/BooksSync( 6532):   "errors": [
E/BooksSync( 6532):    {
E/BooksSync( 6532):     "domain": "global",
E/BooksSync( 6532):     "reason": "required",
E/BooksSync( 6532):     "message": "Login Required",
E/BooksSync( 6532):     "locationType": "header",
E/BooksSync( 6532):     "location": "Authorization"
E/BooksSync( 6532):    }
E/BooksSync( 6532):   ],
E/BooksSync( 6532):   "code": 401,
E/BooksSync( 6532):   "message": "Login Required"
E/BooksSync( 6532):  }
E/BooksSync( 6532): }
E/BooksSync( 6532): 
E/BooksSync( 6532): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6532): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6532): 	... 8 more
I/BooksSync( 6532): Finished books sync
D/SyncManager( 1032): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 246948, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=2.7, 0.0, 0.0  rx=2.7 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1058714712] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=2.7, 0.0, 0.0  rx=2.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1058714709] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1463): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1463): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1463): called onTimeUpdated()
,I/[SystemUI]Clock( 1463): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1463): called onTimeUpdated()
I/[SystemUI]DateView( 1463): called onTimeUpdated()
I/[SystemUI]DateView( 1463): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1463): handleTimeUpdate
,E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=2.4, 0.0, 0.0  rx=2.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1058711683] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=2.4, 0.0, 0.0  rx=2.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1058711680] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,I/jxcore-log( 6138): --= Surplus to requirements =--
I/jxcore-log( 6138): 
I/jxcore-log( 6138): ****TEST TOOK:  ms ****
I/jxcore-log( 6138): 
I/jxcore-log( 6138): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6138): 
,D/AndroidRuntime( 7609): 
D/AndroidRuntime( 7609): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7609): CheckJNI is OFF
D/sensors_hal_Time( 1032): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1032): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1032): tsOffsetIs: Apps: 257574125635; DSPS: 8581012; Offset : -4311976720
,D/AndroidRuntime( 7609): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1032): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
I/ActivityManager( 1032): Killing 6138:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
E/WifiStateMachine( 1032):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=1.7, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1058708657] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1032):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=1.7, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1058708656] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1032): doString: [SIGNAL_POLL]
,I/WindowState( 1032): WIN DEATH: Window{b42220c u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService( 1032): Client connection lost with reason: 4
D/InputDispatcher( 1032): Window went away: Window{b42220c u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/PackageSettings( 1032): Skipping PackageSetting{346b5e97 com.example.hello/10319} due to missing metadata
,I/ActivityManager( 1032):   Force finishing activity ActivityRecord{29bb48f1 u0 com.test.thalitest/.MainActivity t4}
,E/GBMv2   (  343): DFP En is all cleared set to be enabled
,W/ActivityManager( 1032): Spurious death for ProcessRecord{37bbf459 6138:com.test.thalitest/u0a311}, curProc for 6138: null
I/ActivityManager( 1032): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
,I/ActivityManager( 1032):   Force finishing activity ActivityRecord{29bb48f1 u0 com.test.thalitest/.MainActivity t4 f}
W/ActivityManager( 1032): Duplicate finish request for ActivityRecord{29bb48f1 u0 com.test.thalitest/.MainActivity t4 f}
,I/[LGHome]EVENT( 2020): [Launcher.java:5338:onStart()]onStart
D/SplitWindowPolicy( 1928): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1928): topRunningActivity=ActivityInfo{16e8ebe5 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[LGHome]EVENT( 2020): [Launcher.java:903:onResume()]onResume
I/[LGHome]EVENT( 2020): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
D/SplitWindowPolicy( 1928): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
I/[LGHome]Launcher.Model( 2020): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/SplitWindowPolicy( 1928): topRunningActivity=ActivityInfo{112a66ba co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
,D/ActionManagerService( 1893): notifyUserLog: 1000003
I/[LGHome]GBoardWebView( 2020): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
D/LIA_Informant_ActionManagerMessageHandler( 2685): handleMessage: what(1000) actionID(0x1000003)
I/[LGHome]LGActivityUtil( 2020): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,I/[LGHome]EVENT( 2020): [Launcher.java:1056:onResume()]onResume end
I/[LGHome]EVENT( 2020): [Launcher.java:1114:onPause()]onPause
,D/KeyguardModel( 1463): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/InputReader( 1032): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1805): Ignoring removeGeofence because network location is disabled.
,D/LIA_Service_RemotePackageHandler( 1983): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
D/LIA_MrGDBLogger_PackageInfoDetector( 2685): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
E/LGBluetoothAvrcpQcomAdapter( 6194): [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
D/LGBluetoothAvrcpQcomAdapter( 6194): [BTUI] [+] updateMediaPlayerInfo
,W/System.err( 4201): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 4201): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4201): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4201): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4201): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4201): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4201): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4201): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4201): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4201): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4201): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4201): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,V/SIM_STK ( 1032): Menu title from STK is T-Mobile
I/ActivityManager( 1032): Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=7639 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/art     ( 4250): Explicit concurrent mark sweep GC freed 28660(1641KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 29MB/45MB, paused 613us total 53.060ms
,I/[LGHome]GBoardWebView( 2020): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
D/ActionManagerService( 1893): notifyUserLog: 1000004
D/LIA_Informant_ActionManagerMessageHandler( 2685): handleMessage: what(1000) actionID(0x1000004)
V/BoardContentProvider( 2685): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
I/[SystemUI]QSlideListController( 1463): onReceive = android.intent.action.PACKAGE_REMOVED
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
I/GBoardWebViewUtils( 2020): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1454599632914
I/GBoardWebViewUtils( 2020): , create_time: 1454599633839
I/GBoardWebViewUtils( 2020): , expire_time: 0
I/GBoardWebViewUtils( 2020): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide.html?id=guide_1111111111116_1454599632914&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2020): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2020): , display: false
I/GBoardWebViewUtils( 2020): , animation: false }
,D/KeyguardModel( 1463): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1463): createShortcutInfo...
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1463): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1463): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
D/WallpaperManager( 2020): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
,D/KeyguardModel( 1463): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1463): createShortcutInfo...
I/SystemUI[Framework]( 1032): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1032): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1032): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1032): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1032): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@32acc222,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1032): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
W/ResourcesManager( 1463): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1463): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1463): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
I/art     ( 1032): Explicit concurrent mark sweep GC freed 44773(2MB) AllocSpace objects, 6(480KB) LOS objects, 33% free, 44MB/66MB, paused 2.382ms total 184.417ms
W/ResourcesManager( 1463): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1463): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1463): Failure retrieving resources for com.android.mms: Resource ID #0x0
I/art     ( 1032): WaitForGcToComplete blocked for 60.252ms for cause Explicit
D/KeyguardModel( 1463): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1463): createShortcutInfo...
I/[LGHome]GBoardWebView( 2020): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
W/ResourcesManager( 1463): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1463): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/SplitUIManager( 1857): split_name #11 / not available #0
D/SplitUIService( 1857): removed split : 
W/ResourceType( 1463): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1463): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1463): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1463): createShortcutInfo...
,V/SIM_STK ( 1032): Menu title from STK is T-Mobile
,V/SIM_STK ( 1032): Menu title from STK is T-Mobile
W/ResourcesManager( 1463): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1463): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1463): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1463): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1463): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1463): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/SplitUIManager( 1857): split_name #11 / not available #0
I/SplitUIService( 1857): split app #11
D/administrator( 1032): Handling package changes for user 0
D/KeyguardModel( 1463): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1463): createShortcutInfo...
D/KeyguardModel( 1463): handleShortcutListChanged...
,D/KeyguardModel( 1463): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1463): createShortcutInfo...
D/KeyguardModel( 1463): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1463): createShortcutInfo...
W/ResourceType( 1463): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1463): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1463): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1463): createShortcutInfo...
W/ResourceType( 1463): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1463): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1463): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1463): createShortcutInfo...
W/ResourceType( 1463): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1463): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1463): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1463): createShortcutInfo...
,W/ResourcesManager( 7639): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
I/[LGHome]EVENT( 2020): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,W/ActivityManager( 1032): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
D/LGBluetoothAvrcpQcomAdapter( 6194): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 6194): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6194): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 6194): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 6194): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 6194): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6194): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 6194): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6194): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 6194): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6194): [BTUI] [-] updateMediaPlayerInfo
V/SIM_STK ( 1032): Menu title from STK is T-Mobile
I/[LGHome]EVENT( 2020): [Launcher.java:5349:onStop()]onStop
,D/PluginManager( 7639): init()
D/KeyguardModel( 1463): handleShortcutListChanged...
I/NotificationService( 1032): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
,D/BackupManagerService( 1032): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1032): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister( 1032): removeObsoleteFile: deleting file=4_task.xml
D/PhoneStatusBar( 1463): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
I/[SystemUI]NavigationThemeResource( 1463): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1463):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1463): , Keyguard show=false, IME shown=false, Panel expanded=false
I/[LGHome]Launcher.Model( 2020): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 2020): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2020): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2020): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2020): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2020): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,I/Timeline( 1032): Timeline: Activity_windows_visible id: ActivityRecord{17973c13 u0 com.lge.launcher2/.Launcher t3} time:258331
I/[LGHome]Launcher.Model( 2020): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2020): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2020): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2020): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
W/ResourcesManager( 1032): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourceType( 1032): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/[LGHome]EVENT( 2020): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,I/[LGHome]Launcher.Model( 2020): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2020): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[Concierge]WidgetView( 2020): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
D/[Concierge]Service( 2604): onStartCommand(). Type : 8
D/[Concierge]Service( 2604): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/[Concierge]Service( 2604): Update widget ID : 11
D/[Concierge]WidgetView( 2020): change position of spinner
,I/art     ( 1032): Explicit concurrent mark sweep GC freed 10232(561KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 1.981ms total 230.177ms
I/[Concierge]WidgetView( 2020): initWebView(). Time : 1454935205401
D/[Concierge]Service( 2604): onStartCommand(). Type : 0
I/[Concierge]WebView( 2020): Return exist ConciergeWebView. Reuse : 803767262
D/[Concierge]WidgetView( 2020): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2020): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
I/[LgeWidgetLib]ExtViewHost( 2020): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@1bf1257c
I/[LGHome]EVENT( 2020): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2020): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2020): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2020): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
I/[LGHome]EVENT( 2020): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
D/[Concierge]WidgetView( 2020): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2020): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,W/[Concierge]WidgetView( 2020): Widget kill message received. Destory myself. My : 1454934975296, New one : 1454935205401
D/[Concierge]WidgetView( 2020): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2020): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/[LGHome]Launcher( 2020): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2020): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2020): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2020): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2020): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
,I/[LGHome]EVENT( 2020): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2020): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2020): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
D/AndroidRuntime( 7609): Shutting down VM
,I/[LgeWidgetLib]LgeAppWidgetHostView( 2020): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 2020): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2020): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 2020): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/Timeline( 2020): Timeline: Activity_idle id: android.os.BinderProxy@15e3bb13 time:258514
,W/ExternalStrings( 7639): load override strings
W/ExternalStrings( 7639): java.lang.RuntimeException: Unexpected tag, got eat-comment
W/ExternalStrings( 7639): 	at com.mcafee.plugin.af.a(Unknown Source)
W/ExternalStrings( 7639): 	at com.mcafee.plugin.ac.b(Unknown Source)
W/ExternalStrings( 7639): 	at com.mcafee.plugin.ak.d(Unknown Source)
W/ExternalStrings( 7639): 	at com.mcafee.plugin.ak.a(Unknown Source)
W/ExternalStrings( 7639): 	at com.mcafee.app.s.getClassLoader(Unknown Source)
W/ExternalStrings( 7639): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
W/ExternalStrings( 7639): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
W/ExternalStrings( 7639): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
W/ExternalStrings( 7639): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
W/ExternalStrings( 7639): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
W/ExternalStrings( 7639): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ExternalStrings( 7639): 	at android.os.Looper.loop(Looper.java:135)
W/ExternalStrings( 7639): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/ExternalStrings( 7639): 	at java.lang.reflect.Method.invoke(Native Method)
W/ExternalStrings( 7639): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/ExternalStrings( 7639): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/ExternalStrings( 7639): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,D/StatusProvider( 7639): onCreate
V/Signer  ( 7639): override build config not found
D/Signer  ( 7639): value of property debug is false
,I/chromium( 2020): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,D/LGMDMWrapper( 7639): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
D/LGMDMWrapper( 7639): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
D/LGMDMWrapper( 7639): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
D/LGMDMWrapper( 7639): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
D/LGMDMWrapper( 7639): Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
D/LGMDMWrapper( 7639): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
,D/LGMDMWrapper( 7639): Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
D/LGMDMWrapper( 7639): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
D/LGMDMWrapper( 7639): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
D/LGMDMWrapper( 7639): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
D/LGMDMWrapper( 7639): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
D/LGMDMWrapper( 7639): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
D/LGMDMWrapper( 7639): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
V/LGMDMManager( 7639): Create singleton instance
,I/GBoardtInterface( 2020): onReloaded()
I/GBoardWebViewClient( 2020): onPageFinished url:file:///android_asset/www/main.html
V/BoardContentProvider( 2685): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,V/BoardContentProvider( 2685): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/ActionManagerService( 1893): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 2685): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 2685): onEvent() : ACTION_BOARD_ENABLED
,D/ActionManagerService( 1893): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 2685): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 2685): onEvent() : ACTION_BOARD_ENABLED
D/LIA_Informant_Tips_FormEventRepository( 2685): getSize() : size - 0
D/LIA_Informant_Tips_SmartTipsActionManager( 2685): onSettingEvent() : GBoard On - add scheduler - 0
V/BoardContentProvider( 2685): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/GBoardUriUtils( 2020): fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
D/GBoardWebViewUtils( 2020): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
D/GBoardUriUtils( 2020): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
D/GBoardWebViewUtils( 2020): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
D/GBoardUriUtils( 2020): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide2.html?id=guide_1111111111116_1454599632914&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
D/GBoardWebViewUtils( 2020): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide2.html?id=guide_1111111111116_1454599632914&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
,D/LGMDMWrapper( 7639): LG MDM library v4.0.0 is available on this device.
,D/PostponalbeReceiver( 7639): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,W/ContextImpl( 7639): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
E/SQLiteDatabase( 7343): Error inserting package=com.test.thalitest
E/SQLiteDatabase( 7343): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
E/SQLiteDatabase( 7343): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 7343): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:787)
E/SQLiteDatabase( 7343): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:926)
E/SQLiteDatabase( 7343): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 7343): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1572)
E/SQLiteDatabase( 7343): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1442)
E/SQLiteDatabase( 7343): 	at com.lge.appbox.databases.AppBoxContentProvider.insert(AppBoxContentProvider.java:220)
E/SQLiteDatabase( 7343): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:238)
E/SQLiteDatabase( 7343): 	at android.content.ContentResolver.insert(ContentResolver.java:1223)
E/SQLiteDatabase( 7343): 	at com.lge.appbox.manager.PreloadListManagerHelper.addExcludeApp(PreloadListManagerHelper.java:134)
E/SQLiteDatabase( 7343): 	at com.lge.appbox.manager.PreloadListManagerHelper.addExcludeAppInternal(PreloadListManagerHelper.java:115)
E/SQLiteDatabase( 7343): 	at com.lge.appbox.manager.PreloadListManagerHelper.onRemoveAppEvent(PreloadListManagerHelper.java:100)
E/SQLiteDatabase( 7343): 	at com.lge.appbox.manager.PreloadListManagerHelper.updateExDb(PreloadListManagerHelper.java:65)
E/SQLiteDatabase( 7343): 	at com.lge.appbox.manager.PreloadListManagerHelper.onReceive(PreloadListManagerHelper.java:46)
E/SQLiteDatabase( 7343): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2586)
E/SQLiteDatabase( 7343): 	at android.app.ActivityThread.access$1700(ActivityThread.java:148)
E/SQLiteDatabase( 7343): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1360)
E/SQLiteDatabase( 7343): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7343): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 7343): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
E/SQLiteDatabase( 7343): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 7343): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 7343): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
E/SQLiteDatabase( 7343): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,I/ActivityManager( 1032): Killing 6929:com.google.android.syncadapters.calendar/u0a69 (adj 15): empty #17
W/ActivityThread( 7639): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());

```
