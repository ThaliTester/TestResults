#### Test 58380500c26a9ef_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
I/MusicWidget( 2588): mDelayedStopHandler : unbind
,I/MusicBrowser( 2189): [MediaPlaybackService.java:2869:onUnbind()] oooooo 
I/MusicBrowser( 2189): [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2189): [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2189): [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2189): [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2189): [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2189): [MediaPlaybackService.java:2046:onDestroy()] oooooo 
I/MusicBrowser( 2189): [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
I/MediaFocusControl( 1103):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@272eb1cdcom.lge.music.MediaPlaybackService$5@3a9c5a82
D/MusicBrowser( 2189): [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2189): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2189): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2189): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2189): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@2d7898a0
I/MusicBrowser( 2189): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2189): [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2189): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2189): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2189): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2189): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2189): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2189): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2189): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2189): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2189): [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2189): [MediaPlaybackService.java:6704:release()] oooooo 
I/MusicBrowser( 2189): [MediaPlaybackService.java:6665:stop()] oooooo 
V/MediaPlayer[Native]( 2189): reset
V/MediaPlayer[Native]( 2189): setListener
V/MediaPlayer[Native]( 2189): disconnect
V/MediaPlayer[Native]( 2189): destructor
V/AudioFlinger(  319): releasing 13 from 2189 for -1
V/AudioFlinger(  319):  decremented refcount to 0
V/AudioFlinger(  319): purging stale effects
V/MediaPlayer[Native]( 2189): disconnect
D/MusicBrowser( 2189): [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
I/SmartShareClient( 2189): [SmartShareManagerClient] smartshare client supported version code: 305000
I/SmartShareClient( 2189): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2189): [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
I/MusicBrowser( 2189): [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2189): [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2189): [SmartShareManagerClient] unregisterListener: 447894931
W/SmartShareClient( 2189): [SmartShareManagerClient] unregisterListener invalid listener: 447894931
I/SmartShareClient( 2189): [SmartShareManagerClient] terminate service: 2189/MediaPlaybackService/640441926
E/HomeCloudIF( 2189): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2189): [SmartShareManagerClient] unbindService context:android.app.Application@36b369d0
V/CloudHub( 2189): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
V/CloudHub( 2189): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2189): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
D/MusicBrowser( 2189): [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
--------- beginning of system
I/ActivityManager( 1103): Killing 5700:com.google.android.partnersetup/u0a8 (adj 15): empty #17
I/CloudHub( 2189): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29978
W/libprocessgroup( 1103): failed to open /acct/uid_10008/pid_5700/cgroup.procs: No such file or directory
D/AndroidRuntime( 6014): 
D/AndroidRuntime( 6014): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6014): CheckJNI is OFF
D/AndroidRuntime( 6014): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1103): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1948): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1103): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1103): setTaskToReturnTo : TaskRecord{fd8cc85 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1103): setTaskToReturnTo : TaskRecord{fd8cc85 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1103): AppWindowTokenEx init.. 
E/GBMv2   (  344): DFP En is all cleared set to be enabled
I/ActivityManager( 1103): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6035 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6014): Shutting down VM
V/ActivityManager( 1103): Display changed displayId=0
D/DSDPConnection( 1860): Display #0 changed.
D/SplitWindowPolicy( 1948): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1948): topRunningActivity=ActivityInfo{1fa8cbb5 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1948): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1948): topRunningActivity=ActivityInfo{2bee124a co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 6035): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/WebViewFactory( 6035): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
I/LibraryLoader( 6035): Loading: webviewchromium
,I/LibraryLoader( 6035): Time to load native libraries: 4 ms (timestamps 5174-5178)
I/LibraryLoader( 6035): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6035): Binding Chromium to main looper Looper (main, tid 1) {262c5e46}
I/LibraryLoader( 6035): Expected native library version number "",actual native library version number ""
I/chromium( 6035): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6035): Initializing chromium process, renderers=0
W/art     ( 6035): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6035): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,V/AudioPolicyService(  319): registerClient() client 0xb54f5040, uid 10311
D/BluetoothManagerService( 1103): Message: 20
D/BluetoothManagerService( 1103): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3acb3ce7:true
W/chromium( 6035): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 6035): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 6035): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
D/BluetoothAdapter( 6035): 901883911: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 6035): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6035): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6035): Build Date: 12/12/14 금
I/Adreno-EGL( 6035): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6035): Remote Branch: 
I/Adreno-EGL( 6035): Local Patches: 
I/Adreno-EGL( 6035): Reconstruct Branch: 
,W/chromium( 6035): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 6035): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 6035): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6035): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6035): CordovaWebView is running on device made by: LGE
,W/art     ( 6035): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6035): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6035): Render dirty regions requested: true
I/OpenGLRenderer( 6035): Initialized EGL, version 1.4
D/OpenGLRenderer( 6035): Enabling debug mode 0
D/Atlas   ( 6035): Validating map...
,D/SplitWindow( 1103): check instance of lgWin Window{22b2c3a9 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/LgDataFeature( 6035): LgDataFeature() Constructor: none
D/LgDataFeature( 6035): LgDataFeature() Constructor Done, null
,I/SystemUI[Framework]( 1103): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
,D/PhoneStatusBar( 1451): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1451): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1451):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1451): , Keyguard show=false, IME shown=false, Panel expanded=false
W/PhoneWindowManagerEx( 1103): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1103): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1103): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1103): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3a0e000,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1103): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/Timeline( 6035): Timeline: Activity_idle id: android.os.BinderProxy@1ebea0f7 time:105640
,I/ActivityManager( 1103): Displayed com.test.thalitest/.MainActivity: +607ms (total +734ms)
I/Timeline( 1103): Timeline: Activity_windows_visible id: ActivityRecord{17dcada u0 com.test.thalitest/.MainActivity t4} time:105646
I/chromium( 6035): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6035): 
,D/JsMessageQueue( 6035): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium( 6035): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 6035): 
,E/GBMv2   (  344): DFP En is all cleared set to be enabled
E/GBMv2   (  344): Set value is all cleared set the max
I/GBMv2   (  344): DFP Enabled. Ignore VFP set
D/jxcore_app_log( 6035): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435094784
,I/chromium( 6035): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 6035): Initializing JXcore engine
W/jxcore-log( 6035): JXcore engine is ready
,W/Thread-684( 6086): type=1400 audit(0.0:146): avc: denied { ioctl } for path="socket:[9894]" dev="sockfs" ino=9894 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/Thread-684( 6086): type=1400 audit(0.0:147): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-684( 6086): type=1400 audit(0.0:148): avc: denied { ioctl } for path="socket:[10382]" dev="sockfs" ino=10382 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-684( 6086): type=1400 audit(0.0:149): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/Thread-684( 6086): type=1400 audit(0.0:150): avc: denied { ioctl } for path="socket:[28891]" dev="sockfs" ino=28891 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
W/jxcore-log( 6035): Starting JXcore engine
,W/jxcore-log( 6035): Platform android
W/jxcore-log( 6035): 
W/jxcore-log( 6035): Process ARCH arm
W/jxcore-log( 6035): 
,I/jxcore-log( 6035): JXcore Cordova bridge is ready!
I/jxcore-log( 6035): 
W/jxcore-log( 6035): JXcore engine is started
,I/jxcore-log( 6035): Toggling radios to true
I/jxcore-log( 6035): 
,D/BluetoothManagerService( 1103): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1103): enable():  mBluetooth =null mBinding = false
,D/LocationManagerService( 1103): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1103): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1103): JNI:system_update. Event-4
D/BluetoothManagerService( 1103): Message: 1
D/BluetoothManagerService( 1103): MESSAGE_ENABLE: mBluetooth = null
D/WifiService( 1103): New client listening to asynchronous messages
,I/ActivityManager( 1103): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=6090 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
D/WifiServiceImplEx( 1103): setWifiEnabled: true pid=6035, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1103): setWifiEnabled: true pid=6035, uid=10311
E/WifiService( 1103): Invoking mWifiStateMachine.setWifiEnabled
,D/LocationManagerService( 1103): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1103): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1103): JNI:system_update. Event-4
D/WifiServiceImplEx( 1103): disconnect pid=6035, uid=10311, packageName=com.test.thalitest
E/WifiStateMachine( 1103):  InitialState CMD_START_SUPPLICANT 0 0
I/LGFTMITEM( 1103): [GET_FTM][id=6], offset=12288
D/WifiServiceImplEx( 1103): reconnect pid=6035, uid=10311, packageName=com.test.thalitest
E/WifiUtil( 1103): wfc_util_ffile_check_copy(): pid[1103] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
E/WifiUtil( 1103): wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
E/WifiUtil( 1103): wfc_util_ffile_check_copy(): pid[1103] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
E/WifiUtil( 1103): wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
I/WifiUtil( 1103): Intf0MacAddress=C49A027B60AC
E/WifiHW  ( 1103): unknown target_country: EU , set to default
E/WifiHW  ( 1103): [wifi_ensure_config_files] default country1 = GB
E/WifiHW  ( 1103): [wifi_ensure_config_files] default country2 = GB
I/WifiUtil( 1103): gEnableBmps=1
I/jxcore-log( 6035): Radios toggled
I/jxcore-log( 6035): 
I/jxcore-log( 6035): My device name is: LGE-LG-D855
I/jxcore-log( 6035): 
,W/ResourcesManager( 6090): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager( 6090): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6090): Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 6090): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/SoftapController(  313): Softap fwReload - Ok
,D/BluetoothAdapterApp( 6090): Loading JNI Library
D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=0
,D/Tethering( 1103): sendTetherStateChangedBroadcast 1, 0, 0
D/Tethering( 1103): InitialState.processMessage what=4
D/CommandListener(  313): Setting iface cfg
D/CommandListener(  313): Trying to bring down wlan0
D/CommandListener(  313): Clearing all IP addresses on wlan0
,I/ActivityManager( 1103): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=6116 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/DSQN    ( 1103): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/Tethering( 1103): sendTetherStateChangedBroadcast 0, 0, 0
E/WifiHW  ( 1103): Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,E/WifiStateMachine( 1103): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1103): useWiFiOffloading() : false
E/WifiStateMachine( 1103): CONFIG_LGE_WLAN_PATH : true
D/WifiMonitor( 1103): startMonitoring(wlan0) with mConnected = false
D/WifiMonitor( 1103): connecting to supplicant
I/WifiServerServiceExt( 1103): WIFI_STATE_CHANGED_ACTION [2]
V/WfdStateTracker( 1948): WfdStateTracker handleDirectStateChangedEvent: 1
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
W/wpa_supplicant( 6133): type=1400 audit(0.0:151): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/wpa_supplicant( 6133): type=1400 audit(0.0:152): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,D/BluetoothAdapterApp( 6090): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@236b747a Instance Count = 1
I/wpa_supplicant( 6133): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 6133): rfkill: Cannot open RFKILL control device
I/wpa_supplicant( 6133): [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,D/BluetoothAdapterApp( 6090): onCreate
W/ResourcesManager( 6116): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6116): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6116): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6116): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 6116): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6116): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/ProfileConfigQcom( 6090): [BTUI] HeadsetService is supported
,D/ProfileConfigQcom( 6090): Adding HeadsetService
D/ProfileConfigQcom( 6090): [BTUI] A2dpService is supported
D/ProfileConfigQcom( 6090): Adding A2dpService
D/ProfileConfigQcom( 6090): [BTUI] HidService is supported
D/ProfileConfigQcom( 6090): Adding HidService
D/ProfileConfigQcom( 6090): [BTUI] HealthService is supported
D/ProfileConfigQcom( 6090): Adding HealthService
D/LGBluetoothFeatureConfig( 6090): isSupportPan() :  mTargetOp=OPEN
D/ProfileConfigQcom( 6090): [BTUI] PanService is supported
D/ProfileConfigQcom( 6090): Adding PanService
D/ProfileConfigQcom( 6090): [BTUI] GattService is supported
D/ProfileConfigQcom( 6090): Adding GattService
D/ProfileConfigQcom( 6090): [BTUI] BluetoothMapService is supported
D/ProfileConfigQcom( 6090): Adding BluetoothMapService
D/ProfileConfigQcom( 6090): [BTUI] HeadsetClientService is NOT supported
D/BluetoothManagerService( 1103): Message: 20
D/BluetoothManagerService( 1103): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@351c9060:true
,D/BluetoothAdapterState( 6090): make
I/LGFMServiceAdapter( 6090): [FM] LGFMServiceAdapter : create
I/BluetoothAdapterState( 6090): Entering OffState
I/bluedroid-qcom( 6090): init
I/bte_conf( 6090): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
I/bte_conf( 6090): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 6090): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 6090): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
D/BTIF_CORE( 6090): [BTUI] lge_load_bluetooth_address
I/bluedroid-qcom( 6090): get_profile_interface socket
,I/GKI_LINUX( 6090): gki_task_entry task_id=1 [BTIF] starting
I/bluedroid-qcom( 6090): get_profile_interface map_client
W/bdaddr_loader( 6150): type=1400 audit(0.0:153): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/bdaddr_loader( 6150): type=1400 audit(0.0:154): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/BluetoothAdapterProperties( 6090): Address is:58:3F:54:73:64:C0
D/BluetoothManagerService( 1103): Bluetooth Adapter name changed to G3-1
D/BluetoothManagerService( 1103): Stored Bluetooth name: G3-1
D/BluetoothAdapterProperties( 6090): Name is: G3-1
D/BluetoothManagerService( 1103): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService( 1103): Message: 40
D/BluetoothManagerService( 1103): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
D/lge_bdaddr_loader( 6150): [BTUI] bdaddr_loader ::: START
D/lge_bdaddr_loader( 6150): [BTUI] bluetooth_load_bdaddress
I/LGFTMITEM( 6150): [GET_FTM][id=8], offset=16384
I/bluedroid-qcom( 6090): config_hci_snoop_log
D/BluetoothManagerService( 1103): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService( 1103): Broadcasting onBluetoothServiceUp() to 7 receivers.
D/lge_bdaddr_loader( 6150): [BTUI] bdaddr to set in property : 58:3F:54:73:64:C0
E/lge_bdaddr_loader( 6150): [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:64:C0
D/lge_bdaddr_loader( 6150): [BTUI] bdaddr_loader ::: END
,V/LGMDMManagerInternal( 6090): Create singleton instance
D/UsbSettingsReceiver( 6116): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6116): [AUTORUN] sys.usb.config = ptp_only,adb
,D/UsbSettingsReceiver( 6116): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6116): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6116): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 6116): [AUTORUN] getUsbConnected() : connected=true
,D/UsbSettingsReceiver( 6116): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6116): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6116): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6116): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6116): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 6116): [AUTORUN] setTetherStatus() : status=false
D/UsbSettingsReceiver( 6116): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6116): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6116): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6116): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6116): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 6116): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6116): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 6116): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6116): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6116): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 6116): [AUTORUN] setTetherStatus() : status=false
I/wpa_supplicant( 6133): rfkill: Cannot open RFKILL control device
,D/BluetoothAdapterState( 6090): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 6090): Setting state to 11
I/BluetoothAdapterState( 6090): Bluetooth adapter state changed: 10-> 11
I/LGBluetoothServiceJni( 6090): classInitNative: succeeds
D/BluetoothManagerService( 1103): Message: 60
D/BluetoothManagerService( 1103): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService( 1103): Bluetooth State Change Intent: 10 -> 11
,I/ActivityManager( 1103): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6153 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,I/ActivityManager( 1103): Killing 5434:com.lge.appbox.client/u0a11 (adj 15): empty #17
I/wpa_supplicant( 6133): [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,I/wpa_supplicant( 6133): p2p0: CTRL-EVENT-AVOID-FREQ ranges=
I/wpa_supplicant( 6133): wlan0: CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine( 1103):  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
E/WifiStateMachine( 1103):  SupplicantStartingState CMD_START_DRIVER 0 0
E/WifiStateMachine( 1103):  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
E/WifiStateMachine( 1103):  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
D/WifiMonitor( 1103): Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
,E/WifiStateMachine( 1103):  SupplicantStartingState CMD_DISCONNECT 0 0
D/WifiMonitor( 1103): Dropping event because (p2p0) is stopped
E/WifiStateMachine( 1103):  DefaultState CMD_DISCONNECT 0 0
D/WifiMonitor( 1103): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1103): WifiMonitor:wlan0 cnt=0 dispatchEvent: CTRL-EVENT-SCAN-STARTED ,
E/WifiMonitor( 1103): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1103): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine( 1103):  SupplicantStartingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1103):  DefaultState CMD_RECONNECT 0 0
E/WifiStateMachine( 1103):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1103):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1103):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1103):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1103):  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
D/WifiNative-wlan0( 1103): doString: [DRIVER MACADDR]
D/WifiNative-wlan0( 1103):    returned Macaddr = c4:9a:02:7b:60:ac
D/WifiStateMachine( 1103): MAC Addr from driver = c4:9a:02:7b:60:ac
D/WifiOffDelayIfNotUsed( 1103): setPowerSaveActivated(false)
,I/[SystemUI]BluetoothHandler( 1451): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
D/LGBluetoothAPIService( 1948): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothBondStateMachine( 6090): make
W/libprocessgroup( 1103): failed to open /acct/uid_10011/pid_5434/cgroup.procs: No such file or directory
D/BluetoothAdapterService( 6090): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cc375d
D/LGBluetoothServiceAdapter( 6090): [BTUI] check adapter is available - false.
D/BluetoothAdapterService( 6090): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cc375d
D/LGBluetoothServiceAdapter( 6090): [BTUI] check adapter is available - true : set adapter available.
E/WifiStateMachine( 1103): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1103): useWiFiOffloading() : false
E/WifiStateMachine( 1103): CONFIG_LGE_WLAN_PATH : true
I/BluetoothBondStateMachine( 6090): StableState(): Entering Off State
,D/LGBluetoothSettingsDBObserver( 6090): [BTUI] register observer for LG device name DB
W/Settings( 1103): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1103): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/BluetoothAdapterService( 6090): File transfer profiles supported!!
D/WifiNative-wlan0( 1103): doBoolean: SET update_config 1
V/BluetoothPbapReceiver( 6090): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 6090): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6090): ***********state = 11
D/WfdService( 1948): Waiting for WifiP2p enabling
D/WifiNative-wlan0( 1103): SET update_config 1: returned true
D/WifiConfigStore( 1103): Loading config and enabling all networks 
D/WifiNative-wlan0( 1103): doString: [LIST_NETWORKS]
I/WifiServerServiceExt( 1103): WIFI_STATE_CHANGED_ACTION [3]
D/WifiNative-wlan0( 1103):    returned network id / ssid / bssid / flags 0	NG700	any	
I/WifiServerServiceExt( 1103): batteryPsActivateMsgHandler : state:0 event:3
E/WifiConfigStore( 1103): readNetworkVariablesFromSupplicantFile key=psk
,E/WifiConfigStore( 1103): readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
E/WifiConfigStore( 1103): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
I/ActivityManager( 1103): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6172 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,D/BluetoothHeadset( 1860): Proxy object connected
D/WifiStateMachine( 1103): enableVerboseLogging : level 2
D/WifiNative-wlan0( 1103): doBoolean: SET device_name g3_global_com
D/BluetoothHeadset( 1103): Proxy object connected
D/HeadsetService( 6090): Received start request. Starting profile...
I/LGBluetoothHeadsetServiceJni( 6090): classInitNative: succeeds
D/LGBluetoothHfpAdapter( 6090): Version 1.6
D/BluetoothHeadset( 1860): Proxy object connected
D/BluetoothHeadset( 1860): Proxy object connected
D/LGBluetoothFeatureConfig( 6090): isPrivacyLogsEnabled : true
I/BluetoothHeadsetServiceJni( 6090): classInitNative: succeeds
D/HeadsetStateMachine( 6090): make
D/WifiNative-wlan0( 1103): SET device_name g3_global_com: returned true
D/WifiNative-wlan0( 1103): doBoolean: SET manufacturer LGE
D/WifiNative-wlan0( 1103): SET manufacturer LGE: returned true
D/WifiNative-wlan0( 1103): doBoolean: SET model_name LG-D855
,D/WifiNative-wlan0( 1103): SET model_name LG-D855: returned true
D/WifiNative-wlan0( 1103): doBoolean: SET model_number LG-D855
E/BluetoothAdapterService( 6090): File transfer profiles supported!!
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiNative-wlan0( 1103): SET model_number LG-D855: returned true
D/WifiNative-wlan0( 1103): doBoolean: SET serial_number LGD8553bed2d08
D/WifiNative-wlan0( 1103): SET serial_number LGD8553bed2d08: returned true
D/WifiNative-wlan0( 1103): doBoolean: SET config_methods physical_display virtual_push_button
D/WifiNative-wlan0( 1103): SET config_methods physical_display virtual_push_button: returned true
D/WifiNative-wlan0( 1103): doBoolean: SET device_type 10-0050F204-5
D/WifiNative-wlan0( 1103): SET device_type 10-0050F204-5: returned true
D/WifiStateMachine( 1103): Setting OUI to DA-A1-19
D/WifiNative-wlan0( 1103): doBoolean: SCAN_INTERVAL 120
D/WfdsService( 1948): Supplicant Connection state is changed : true
D/WfdsService( 1948): DefaultState - WIFI_SUPPLICANT_CONNECTED
D/WfdsService( 1948): Set the WFDS Monitor: true
D/WfdsMonitor( 1948): WfdsMonitorThread create
D/WfdsMonitor( 1948): WFDS Monitor is created and started
D/WfdsService( 1948): WiFi: Supplicant connection re-established
D/WifiNative-wlan0( 1103): SCAN_INTERVAL 120: returned true
D/WifiNative-HAL( 1103): Setting external_sim to 1
D/WifiNative-wlan0( 1103): doBoolean: SET external_sim 1
,D/WifiNative-wlan0( 1103): SET external_sim 1: returned true
I/WifiNative-HAL( 1103): startHal
E/wifi    ( 1103): getStaticLongField sWifiHalHandle 0x988358dc
E/WifiHAL ( 1103): Could not connect handle
D/wifi    ( 1103): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x701d4e
I/WifiNative-HAL( 1103): Could not start hal
E/CtrlSupplicant( 1948): Access OK "@android:wpa_wlan0"
D/WifiStateMachine( 1103): Setting OUI to DA-A1-19
I/WifiNative-HAL( 1103): startHal
E/wifi    ( 1103): getStaticLongField sWifiHalHandle 0x9883585c
E/WifiHAL ( 1103): Could not connect handle
D/wifi    ( 1103): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x301d4a
I/WifiNative-HAL( 1103): Could not start hal
D/WifiNative-wlan0( 1103): doBoolean: STA_AUTOCONNECT 1
E/CtrlSupplicant( 1948): Succeed to open control connection
E/CtrlSupplicant( 1948): Succeed to open monitor connection
D/WfdsMonitor( 1948): Supplicant connection established
D/WfdsService( 1948): Connected to the supplicant for wfds
D/WifiNative-wlan0( 1103): STA_AUTOCONNECT 1: returned true
D/WifiNative-wlan0( 1103): doBoolean: DRIVER BTCOEXSCAN-STOP
I/wpa_supplicant( 6133): wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
D/WifiNative-wlan0( 1103): DRIVER BTCOEXSCAN-STOP: returned true
D/LgDataFeature( 6090): LgDataFeature() Constructor: none
,D/LgDataFeature( 6090): LgDataFeature() Constructor Done, null
I/ActivityManager( 1103): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6196 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,D/WifiNative-wlan0( 1103): doBoolean: DRIVER RXFILTER-STOP
I/wpa_supplicant( 6133): wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
D/WifiHS20( 1103): hidePasspointNotification off =false
D/WifiNative-wlan0( 1103): DRIVER RXFILTER-STOP: returned true
D/WifiNative-wlan0( 1103): doBoolean: DRIVER RXFILTER-REMOVE 3
I/wpa_supplicant( 6133): wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
D/WifiNative-wlan0( 1103): DRIVER RXFILTER-REMOVE 3: returned true
D/WifiNative-wlan0( 1103): doBoolean: DRIVER RXFILTER-START
I/wpa_supplicant( 6133): wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
D/WifiNative-wlan0( 1103): DRIVER RXFILTER-START: returned true
D/WifiNative-wlan0( 1103): doBoolean: DRIVER RXFILTER-STOP
I/wpa_supplicant( 6133): wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
D/WifiNative-wlan0( 1103): DRIVER RXFILTER-STOP: returned true
D/WifiNative-wlan0( 1103): doBoolean: DRIVER RXFILTER-REMOVE 2
I/wpa_supplicant( 6133): android_multicast_filter_startstop : multicast filter set
D/WifiNative-wlan0( 1103): DRIVER RXFILTER-REMOVE 2: returned true
D/WifiNative-wlan0( 1103): doBoolean: DRIVER RXFILTER-START
I/wpa_supplicant( 6133): wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
D/WifiNative-wlan0( 1103): DRIVER RXFILTER-START: returned true
I/StatusBar.NetworkController( 1451): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1451): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1103): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1103): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1103): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/HeadsetStateMachine( 6090): max_hf_connections = 1
I/bluedroid-qcom( 6090): get_profile_interface handsfree
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
V/ToneGenerator( 6090): ToneGenerator constructor: streamType=8, volume=1.000000
V/AudioPolicyService(  319): registerClient() client 0xb54f52e0, uid 1002
V/AudioPolicyManager(  319): getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  319): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  319): getOutput() returns output 2
V/AudioSystem( 6090): getOutputSamplingRate() no output descriptor for output 2 in gOutputs
V/AudioFlinger(  319): registerClient() client 0xb14330e8, pid 6090
V/AudioSystem(  319): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  319): ioConfigChanged() opening already existing output! 2
,V/ToneGenerator( 6090): Create Track: 0xb4928a80
V/AudioTrack( 6090): set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
V/AudioTrack( 6090): set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
V/AudioPolicyManager(  319): getOutputForAttr() usage=3, content=4, tag= flags=00000000
V/AudioPolicyManager(  319): getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  319): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  319): getOutput() returns output 2
V/AudioSystem( 6090): getOutputSamplingRate() no output descriptor for output 2 in gOutputs
V/AudioSystem( 6090): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 6090): ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
V/AudioSystem( 1103): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1103): ioConfigChanged() opening already existing output! 2
E/BluetoothAdapterService( 6090): File transfer profiles supported!!
V/AudioSystem( 1451): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1451): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1860): ioConfigChanged() event 0, ioHandle 2
I/AudioFlinger(  319): isAudioPlaybackHookOn() false
V/AudioSystem( 1860): ioConfigChanged() opening already existing output! 2
V/AudioSystem(  319): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem(  319): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1860): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1860): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 2189): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 2189): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 2189): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 2189): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1103): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1103): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 3196): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 3196): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1451): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 3196): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1451): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 3196): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 6090): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 6090): ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
V/AudioPolicyManager(  319): getOutputForAttr() usage=3, content=4, tag= flags=00000000
V/AudioPolicyManager(  319): getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
V/AudioPolicyManagerEx(  319): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  319): getOutput() returns output 2
V/AudioSystem( 6090): getLatency() output 2, latency 50
V/AudioSystem( 6090): getFrameCount() output 2, frameCount 960
V/AudioTrack( 6090): createTrack_l() output 2 afLatency 50
E/WifiNative: ( 1103): [109,053,757 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
V/AudioFlinger(  319): [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
V/AudioFlinger(  319): [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
V/AudioFlinger(  319): [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
V/AudioFlinger(  319): [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
V/AudioFlinger(  319): createTrack() lSessionId: 16
D/WifiNative-wlan0( 1103): doBoolean: RECONNECT
D/WifiNative-wlan0( 1103): RECONNECT: returned true
D/WifiNative-wlan0( 1103): doString: [STATUS]
V/AudioTrack( 6090): AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
V/AudioFlinger(  319): acquiring 16 from 6090, for 6090
V/AudioFlinger(  319):  added new entry for 16
V/ToneGenerator( 6090): ToneGenerator INIT OK, time: 109078
D/BluetoothAdapterService( 6090): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cc375d
D/WifiMonitor( 1103): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1103): WifiMonitor:wlan0 cnt=1 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HeadsetStateMachine( 6090): Enter Disconnected: -2, size: 0
D/HeadsetPhoneState( 6090): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 6090): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetStateMachine( 6090): [BTUI] change sampling rate to 8000 when device is disconnected
D/WifiNative-wlan0( 1103):    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
D/WifiNative-wlan0( 1103): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 6133): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1103): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1103): doBoolean: SET ps 1
D/WifiNative-wlan0( 1103): SET ps 1: returned true
D/LGWifiP2pService( 1103): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 1103):  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
D/WifiScanningService( 1103): SCAN_AVAILABLE : 3
E/WifiStateMachine( 1103):  DisconnectedState CMD_START_DRIVER 0 0
D/RttService( 1103): SCAN_AVAILABLE : 3
D/CommandListener(  313): Setting iface cfg
D/WifiScanningService( 1103): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  313): Trying to bring up p2p0
I/WifiNative-HAL( 1103): startHal
E/wifi    ( 1103): getStaticLongField sWifiHalHandle 0x94d5c99c
E/WifiStateMachine( 1103):  ConnectModeState CMD_START_DRIVER 0 0
E/WifiHAL ( 1103): Could not connect handle
D/WifiMonitor( 1103): startMonitoring(p2p0) with mConnected = true
D/wifi    ( 1103): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x501c2a
I/WifiNative-HAL( 1103): Could not start hal
D/LGWifiP2pService( 1103): P2pEnablingState
E/WifiScanningService( 1103): could not start HAL
D/LGWifiP2pService( 1103): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1103): P2p socket connection successful
D/RttService( 1103): DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1103): P2pEnabledState
E/WifiStateMachine( 1103):  DriverStartedState CMD_START_DRIVER 0 0
V/AudioFlinger(  319): setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6090
D/LGWifiP2pService( 1103): sending p2p connection changed broadcast
E/WifiStateMachine( 1103):  DisconnectedState what:132106 1 0
E/WifiStateMachine( 1103):  ConnectModeState what:132106 1 0
E/WifiStateMachine( 1103):  DriverStartedState what:132106 1 0
I/WifiServerServiceExt( 1103): setWifiDualbandAPConnection band : 1
E/wpa_supplicant( 6133): nWIFIDualbandAPConnection: 1
E/WifiStateMachine( 1103):  DisconnectedState what:132096 -100 0
V/WfdStateTracker( 1948): WfdStateTracker handleDirectStateChangedEvent: 2
E/WifiStateMachine( 1103):  ConnectModeState what:132096 -100 0
D/WfdsService( 1948): WifiP2pState is changed : true
D/WfdsService( 1948): Receive the WFDS_ENABLE Method
D/WfdsService( 1948): Set the WFDS Monitor: true
D/WfdsService( 1948): Connected to the supplicant for wfds
D/WfdsJNI ( 1948): doCommand: WFDS_SET TRUE
I/wpa_supplicant( 6133): WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
D/WfdsJNI ( 1948): doCommand: WFDS_GET_MAC_ADDRESS
I/wpa_supplicant( 6133): WFDS: wfds_supplicant_wfds_cmd: cmd = GET_MAC_ADDRESS
D/WfdsJNI ( 1948): doCommand: IFNAME=wlan0 GET_CAPABILITY channels
D/WfdsService( 1948): selectPreferredScanChannel [36]
D/WfdsService( 1948): STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7b:60:ac
D/audio_hw_primary(  319): adev_set_parameters: enter: bt_samplerate=8000
V/voice   (  319): voice_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  319): voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  319): voice_extn_compress_voip_set_parameters: exit
V/voice   (  319): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  319): LGE_platform_set_parameters: enter: bt_samplerate=8000
E/WifiStateMachine( 1103):  DriverStartedState what:132096 -100 0
V/msm8974_platform(  319): platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  319): platform_set_parameters: exit with code(0)
I/WifiServerServiceExt( 1103): set CMD_DISCONNECT_RSSI_LVL : -100
V/lge_audio_loopback(  319): lge_platform_set_loopback_parameters: enter: 
V/audio_hw_primary(  319): adev_set_parameters: exit with code(0)
E/audio_a2dp_hw(  319): adev_set_parameters: ERROR: set param called even when stream out is null
E/wpa_supplicant( 6133): disconnect_rssi_lvl: -100
V/ToneGenerator( 6090): ToneGenerator destructor
V/ToneGenerator( 6090): stopTone
V/ToneGenerator( 6090): Delete Track: 0xb4928a80
E/BluetoothAdapterService( 6090): File transfer profiles supported!!
V/AudioTrack( 6090): ~AudioTrack, releasing session id from 6090 on behalf of 6090
V/AudioFlinger(  319): releasing 16 from 6090 for 6090
V/AudioFlinger(  319):  decremented refcount to 0
V/AudioFlinger(  319): purging stale effects
V/AudioPolicyService(  319): AudioCommandThread() adding release output 2
V/AudioPolicyService(  319): inserting command: 6 at index 0, num commands 0
V/AudioFlinger(  319): PlaybackThread::Track destructor
V/AudioPolicyService(  319): AudioCommandThread() waking up
V/AudioPolicyService(  319): AudioCommandThread() processing release output 2
V/AudioFlinger(  319): removeClient_l() pid 6090, calling pid 319
V/AudioPolicyManager(  319): releaseOutput() 2
V/AudioPolicyService(  319): AudioCommandThread() going to sleep
D/WifiNative-p2p0( 1103): doBoolean: SET persistent_reconnect 1
D/WifiNative-p2p0( 1103): SET persistent_reconnect 1: returned true
D/WifiNative-p2p0( 1103): doBoolean: SET device_name G3-1
D/WifiNative-p2p0( 1103): SET device_name G3-1: returned true
D/LGWifiP2pService( 1103): [LGE_P2P] initializeP2pSettings() check postfix
D/LGWifiP2pService( 1103): before postfix = G3-1
D/WifiServerServiceExt( 1103): postfix byte check : 4
D/LGWifiP2pService( 1103): after postfix = G3-1
D/WifiNative-p2p0( 1103): doBoolean: SET p2p_ssid_postfix -G3-1
E/BluetoothAdapterService( 6090): File transfer profiles supported!!
,D/WifiNative-p2p0( 1103): SET p2p_ssid_postfix -G3-1: returned true
D/WifiNative-p2p0( 1103): doBoolean: SET device_type 10-0050F204-5
D/WifiNative-p2p0( 1103): SET device_type 10-0050F204-5: returned true
D/WifiNative-p2p0( 1103): doBoolean: SET config_methods virtual_push_button physical_display keypad
D/WifiNative-p2p0( 1103): SET config_methods virtual_push_button physical_display keypad: returned true
D/WifiNative-p2p0( 1103): doBoolean: P2P_SET conc_pref p2p
D/WifiNative-p2p0( 1103): P2P_SET conc_pref p2p: returned true
D/WifiNative-HAL( 1103): p2pGetDeviceAddress
D/WifiNative-HAL( 1103): p2pGetDeviceAddress returning 02:9a:02:7b:60:ac
D/BluetoothAdapterService( 6090): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cc375d
D/LGWifiP2pService( 1103): DeviceAddress: 02:9a:02:7b:60:ac
D/WifiNative-p2p0( 1103): doBoolean: P2P_FLUSH
D/WifiNative-p2p0( 1103): P2P_FLUSH: returned true
D/WifiNative-p2p0( 1103): doBoolean: P2P_SERVICE_FLUSH
D/WfdsService( 1948): WIFI_P2P_CONNECTION_CHANGED_ACTION
D/WifiNative-p2p0( 1103): P2P_SERVICE_FLUSH: returned true
D/WifiNative-p2p0( 1103): doString: [LIST_NETWORKS]
E/WifiStateMachine( 1103):  DisconnectedState CMD_SET_COUNTRY_CODE 1 0 cz
D/BluetoothA2dp( 1103): Proxy object connected
D/A2dpService( 6090): Received start request. Starting profile...
D/WifiNative-p2p0( 1103):    returned network id / ssid / bssid / flags
I/BluetoothAvrcpServiceJni( 6090): classInitNative: succeeds
D/WifiNative-p2p0( 1103): doBoolean: SAVE_CONFIG
V/Avrcp   ( 6090): make
E/WifiStateMachine( 1103):  ConnectModeState CMD_SET_COUNTRY_CODE 1 0 cz
E/WifiStateMachine( 1103):  DriverStartedState CMD_SET_COUNTRY_CODE 1 0 cz
D/Avrcp   ( 6090): [BTUI] Use Native AVRCP : init jni
I/bluedroid-qcom( 6090): get_profile_interface avrcp
D/WifiNative-wlan0( 1103): doBoolean: DRIVER COUNTRY CZ
E/BluetoothAdapterService( 6090): File transfer profiles supported!!
V/AudioManager( 6090): registerRemoteController: size of Media player list: 0
D/WfdsService( 1948): isConnected: false
I/WfdStateTracker( 1948): handleP2pThisDeviceChanged
D/WfdsService( 1948): WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
D/WfdsService( 1948): Update P2p Interface State: 3
D/WifiNative-p2p0( 1103): SAVE_CONFIG: returned true
D/LGWifiP2pService( 1103): sending p2p persistent groups changed broadcast
D/LGWifiP2pService( 1103): InactiveState
D/LGWifiP2pService( 1103): InactiveState{ when=-14ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1103): P2pEnabledState{ when=-14ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1103): doBoolean: DRIVER COUNTRY CZ
I/wpa_supplicant( 6133): wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
I/wpa_supplicant( 6133): p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
I/wpa_supplicant( 6133): [LGE_PATCH] driver_cmd() country:CZ
I/wpa_supplicant( 6133): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
I/wpa_supplicant( 6133): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WfdsMonitor( 1948): Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
D/WfdsMonitor( 1948): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WfdsMonitor( 1948): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WifiMonitor( 1103): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
E/WifiMonitor( 1103): WifiMonitor:p2p0 cnt=2 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1103): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1103): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
D/WifiMonitor( 1103): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1103): WifiMonitor:p2p0 cnt=3 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1103): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1103): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiMonitor( 1103): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1103): WifiMonitor:p2p0 cnt=4 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1103): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1103): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiNative-p2p0( 1103): DRIVER COUNTRY CZ: returned true
D/LGWifiP2pService( 1103): InactiveState{ when=-3ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1103): P2pEnabledState{ when=-3ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1103): DefaultState{ when=-3ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1103): InactiveState{ when=-3ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1103): P2pEnabledState{ when=-3ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1103): DefaultState{ when=-3ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1103): InactiveState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1103): P2pEnabledState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1103): DefaultState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1103): InactiveState{ when=0 what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1103): P2pEnabledState{ when=0 what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1103): DefaultState{ when=0 what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1103): No p2p device connected
W/WfdsService( 1948): DefaultState - msg [9441285] is not handled
I/wpa_supplicant( 6133): wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
I/wpa_supplicant( 6133): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
D/WifiMonitor( 1103): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
E/WifiMonitor( 1103): WifiMonitor:wlan0 cnt=5 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1103): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1103): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
I/wpa_supplicant( 6133): [LGE_PATCH] driver_cmd() country:CZ
I/wpa_supplicant( 6133): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WfdsMonitor( 1948): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WifiNative-wlan0( 1103): DRIVER COUNTRY CZ: returned true
I/wpa_supplicant( 6133): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiStateMachine( 1103):  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine( 1103):  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine( 1103):  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
D/WifiNative-wlan0( 1103): doBoolean: DRIVER SETBAND 0
I/wpa_supplicant( 6133): wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
D/LGWifiP2pService( 1103): InactiveState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 6133): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
D/LGWifiP2pService( 1103): P2pEnabledState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsMonitor( 1948): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WifiNative-wlan0( 1103): DRIVER SETBAND 0: returned true
W/FormManager( 6153): Network not available. Please check & try again.
D/WifiNative-wlan0( 1103): doBoolean: BSS_FLUSH 0
D/WifiNative-wlan0( 1103): BSS_FLUSH 0: returned true
D/WifiNative-wlan0( 1103): doBoolean: SCAN
D/WifiNative-wlan0( 1103): SCAN: returned false
E/WifiStateMachine( 1103):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=109105  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/WifiMonitor( 1103): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1103): WifiMonitor:p2p0 cnt=6 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1103): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1103): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiMonitor( 1103): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1103): WifiMonitor:p2p0 cnt=7 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1103): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1103): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiMonitor( 1103): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
E/WifiMonitor( 1103): WifiMonitor:wlan0 cnt=8 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
E/WifiMonitor( 1103): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
E/WifiMonitor( 1103): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
V/FormManager( 6153): Network unavailable.
E/BluetoothAdapterService( 6090): File transfer profiles supported!!
V/FormManager( 6153): Network unavailable.
E/WifiStateMachine( 1103):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=109111  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine( 1103):  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1103):  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1103):  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1103):  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1103):  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/AudioManager( 6090): No RCC entry present to update
E/RemoteController( 6090): Cannot set synchronization mode on an unregistered RemoteController
W/Settings( 1103): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1103): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1103): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/StatusBar.NetworkController( 1451): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1451): mWifiConnected = false, mWifiLevel = 0
D/WifiServerServiceExt( 1103): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1103): setSupplicantStateSCANNING
I/BluetoothAvrcpQcomServiceJni( 6090): classInitQcomNative: succeeds
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
D/LGBluetoothAvrcpQcomAdapter( 6090): [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
I/BluetoothAvrcpQcomServiceJni( 6090): initQcomNative: succeeds
,V/LGMDMManager( 6090): Create singleton instance
I/BluetoothAdapterState( 6090): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
D/LGBluetoothAvrcpQcomAdapter( 6090): [BTUI] [+] updateMediaPlayerInfo
D/WifiService( 1103): New client listening to asynchronous messages
I/ActivityManager( 1103): Killing 5453:com.android.contacts/u0a19 (adj 15): empty #17
D/PCSuite ( 6196): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/SIM_STK ( 1103): Menu title from STK is T-Mobile
V/SIM_STK ( 1103): Menu title from STK is T-Mobile
,W/libprocessgroup( 1103): failed to open /acct/uid_10019/pid_5453/cgroup.procs: No such file or directory
,E/wpa_supplicant( 6133): USIM:  scard_init function
I/wpa_supplicant( 6133): Trying to associate with SSID 'NG700'
E/WifiMonitor( 1103): WifiMonitor:wlan0 cnt=9 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1103): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1103): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1103): WifiMonitor:wlan0 cnt=10 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1103): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1103): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1103): WifiMonitor:wlan0 cnt=11 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1103):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine( 1103):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine( 1103):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine( 1103):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
I/WifiNative-HAL( 1103): startHal
E/wifi    ( 1103): getStaticLongField sWifiHalHandle 0x988358cc
E/WifiHAL ( 1103): Could not connect handle
D/wifi    ( 1103): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x30204e
I/WifiNative-HAL( 1103): Could not start hal
D/WifiNative-wlan0( 1103): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1103):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 11 0 rt=109266  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,E/WifiStateMachine( 1103):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 11 0 rt=109267  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
I/StatusBar.NetworkController( 1451): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1451): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1103): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1103): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1103): NETWORK_STATE_CHANGED_ACTION [SCANNING]
W/Settings( 1103): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1103): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1103): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1451): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1451): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
E/ActivityThread( 6172): Failed to find provider info for com.lge.lgaccount.provider
W/LG Account v2.2( 6172): No ProfileInfo entries
I/LG Account v2.2( 6172): isEnabled: false
I/Feature ( 6172): [Lifetracker]ver: 4.21.112(40211120)
I/Feature ( 6172): [Lifetracker]Country: EU
I/Feature ( 6172): [Lifetracker]Operator: OPEN
I/Feature ( 6172): [Lifetracker]Ranking support: false
I/Feature ( 6172): [Lifetracker]Comfort support: false
I/Feature ( 6172): [Lifetracker]Accessory: true
I/Feature ( 6172): [Lifetracker]Health device: true
I/Feature ( 6172): [Lifetracker]Extra Pedometer: false
I/Feature ( 6172): [Lifetracker]Blood glucose device: false
I/Feature ( 6172): [Lifetracker]Device Number: 3
D/WifiServerServiceExt( 1103): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1103): setSupplicantStateASSOCIATING
,I/ActivityManager( 1103): Killing 5721:com.lge.email/u0a23 (adj 15): empty #17
V/WiFiOffLoadBroadcast( 6116): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
D/WifiService( 1103): New client listening to asynchronous messages
,D/LgDataFeature( 6116): LgDataFeature() Constructor: none
,D/LgDataFeature( 6116): LgDataFeature() Constructor Done, null
D/WiFiOffLoadUpdatePriority( 6116): remove : truetruetrue
E/WifiStateMachine( 1103):  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1103):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1103):  DisconnectedState CMD_SAVE_CONFIG uid=1000 0 0
E/WifiStateMachine( 1103):  ConnectModeState CMD_SAVE_CONFIG uid=1000 0 0
D/WifiNative-wlan0( 1103): doBoolean: SAVE_CONFIG
,D/WifiNative-wlan0( 1103): SAVE_CONFIG: returned true
D/WiFiOffLoadUpdatePriority( 6116): remove1
V/WiFiOffLoadSharedPrefsUtils( 6116): save remove
D/WiFiOffLoadBroadcast( 6116): mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
D/WiFiOffLoadBroadcast( 6116): S: false, R: false
,E/WifiStateMachine( 1103):  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1103):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/WiFiOffLoadUpdatePriority( 6116): saved SSID: "NG700"
D/WiFiOffLoadUpdatePriority( 6116): connected SSID: null
D/WiFiOffLoadUpdatePriority( 6116): private wpa: "NG700" 300
D/WifiServiceImplEx( 1103): addOrUpdateNetwork pid=6116, uid=1000, packageName=android.uid.system:1000
E/addOrUpdateNetwork( 1103):  uid = 1000 SSID "NG700" nid=0
E/WifiStateMachine( 1103):  DisconnectedState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=2
E/WifiStateMachine( 1103):  ConnectModeState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=2
E/WifiConfigStore( 1103):  key="NG700"WPA_PSK netId=0 uid=0/1000
D/WifiServerServiceExt( 1103): addOrUpdateNetwork: mThisIsFirstEnableing = false
D/WifiNative-wlan0( 1103): doBoolean: SET_NETWORK 0 ssid 4e47373030
,D/WifiNative-wlan0( 1103): SET_NETWORK 0 ssid 4e47373030: returned true
D/WifiNative-wlan0( 1103): doBoolean: SET_NETWORK 0 key_mgmt WPA-PSK
D/WifiNative-wlan0( 1103): SET_NETWORK 0 key_mgmt WPA-PSK: returned true
D/WifiNative-wlan0( 1103): doBoolean: SET_NETWORK 0 proto WPA RSN
D/WifiNative-wlan0( 1103): SET_NETWORK 0 proto WPA RSN: returned true
D/WifiNative-wlan0( 1103): doBoolean: SET_NETWORK 0 pairwise TKIP CCMP
,W/ActivityManager( 1103): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
D/WifiNative-wlan0( 1103): SET_NETWORK 0 pairwise TKIP CCMP: returned true
D/WifiNative-wlan0( 1103): doBoolean: SET_NETWORK 0 group WEP40 WEP104 TKIP CCMP
D/WifiNative-wlan0( 1103): SET_NETWORK 0 group WEP40 WEP104 TKIP CCMP: returned true
D/WifiNative-wlan0( 1103): doBoolean: SET_NETWORK 0 priority 300
D/WifiNative-wlan0( 1103): SET_NETWORK 0 priority 300: returned true
W/libprocessgroup( 1103): failed to open /acct/uid_10023/pid_5721/cgroup.procs: No such file or directory
E/WifiConfigStore( 1103): will read network variables netId=0
E/WifiConfigStore( 1103): writeIpAndProxyConfigurationsOnChange: "NG700" -> "NG700" path: /data/misc/wifi/ipconfig.txt
E/WifiConfigStore( 1103):  writeKnownNetworkHistory() num networks:1 needWrite=false
D/WiFiOffLoadUpdatePriority( 6116):  ssid "NG700" prio 300
D/WiFiOffLoadUpdatePriority( 6116): configuration updated: 0
E/WifiStateMachine( 1103):  DisconnectedState CMD_SAVE_CONFIG uid=1000 0 0
E/WifiStateMachine( 1103):  ConnectModeState CMD_SAVE_CONFIG uid=1000 0 0
D/WifiNative-wlan0( 1103): doBoolean: SAVE_CONFIG
D/LGBluetoothAvrcpQcomAdapter( 6090): [BTUI] installed app name: Music
D/WifiNative-wlan0( 1103): SAVE_CONFIG: returned true
,D/WiFiOffLoadUpdatePriority( 6116): configuration saved: true
D/LGBluetoothAvrcpQcomAdapter( 6090): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6090): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 6090): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 6090): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 6090): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6090): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 6090): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6090): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 6090): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6090): [BTUI] [-] updateMediaPlayerInfo
I/BluetoothA2dpServiceJni( 6090): classInitNative
I/BluetoothA2dpServiceJni( 6090): classInitNative: succeeds
D/A2dpStateMachine( 6090): make
I/bluedroid-qcom( 6090): get_profile_interface a2dp
I/GKI_LINUX( 6090): gki_task_entry task_id=2 [A2DP-MEDIA] starting
I/LGBluetoothA2dpServiceJni( 6090): classInitNative: succeeds
I/LGBluetoothA2dpAdapter( 6090): [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
D/BluetoothAdapterService( 6090): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cc375d
D/A2dpStateMachine( 6090): Enter Disconnected: -2
D/HeadsetStateMachine( 6090): Proxy object connected
D/LGBluetoothHfpAdapter( 6090): [BTUI] queryPhoneState
D/LGBluetoothHfpAdapter( 6090): Try to query the phonestate on bind
,D/BluetoothPhoneService.BluetoothLTECall( 1860):  call mBluetoothHeadset.phoneStateChanged()
I/BluetoothHidServiceJni( 6090): classInitNative: succeeds
W/BluetoothHeadset( 1860): Proxy not attached to service
D/BluetoothHeadset( 1860): java.lang.Throwable
D/BluetoothHeadset( 1860): 	at android.bluetooth.BluetoothHeadset.phoneStateChanged(BluetoothHeadset.java:826)
D/BluetoothHeadset( 1860): 	at com.android.phone.BluetoothPhoneService$BluetoothLTECall.handleQueryPhoneState(BluetoothPhoneService.java:1527)
D/BluetoothHeadset( 1860): 	at com.android.phone.BluetoothPhoneService$BluetoothLTECall.access$700(BluetoothPhoneService.java:1360)
D/BluetoothHeadset( 1860): 	at com.android.phone.BluetoothPhoneService$1.handleMessage(BluetoothPhoneService.java:268)
D/BluetoothHeadset( 1860): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BluetoothHeadset( 1860): 	at android.os.Looper.loop(Looper.java:135)
D/BluetoothHeadset( 1860): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
D/BluetoothHeadset( 1860): 	at java.lang.reflect.Method.invoke(Native Method)
D/BluetoothHeadset( 1860): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/BluetoothHeadset( 1860): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
D/BluetoothHeadset( 1860): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
D/HidService( 6090): Received start request. Starting profile...
I/bluedroid-qcom( 6090): get_profile_interface hidhost
D/BluetoothAdapterService( 6090): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cc375d
I/BluetoothHealthServiceJni( 6090): classInitNative: succeeds
D/BluetoothPermissionRequest( 6116): onReceive
D/LGBluetoothFeatureConfig( 6116):  get() - isFeatureLoaded : false
D/HealthService( 6090): Received start request. Starting profile...
I/bluedroid-qcom( 6090): get_profile_interface health
I/LGBluetoothHealthServiceJni( 6090): classInitNative: succeeds
D/BluetoothAdapterService( 6090): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cc375d
D/BluetoothAdapterService( 6090): Profile still not running:com.android.bluetooth.gatt.GattService
D/HeadsetStateMachine( 6090): Disconnected process message: 10, size: 0
,I/BluetoothPanServiceJni( 6090): classInitNative(L105): succeeds
D/HeadsetPhoneState( 6090): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 6090): Disconnected process message: 11, size: 0
D/PanService( 6090): Received start request. Starting profile...
D/BluetoothPanServiceJni( 6090): initializeNative(L110): pan
I/bluedroid-qcom( 6090): get_profile_interface pan
I/LGBluetoothPanAdapter( 6090): [BTUI] getInstance : create [LGBluetoothPanAdapter]
D/BluetoothAdapterService( 6090): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cc375d
I/BtGatt.JNI( 6090): classInitNative(L901): classInitNative: Success!
,D/BluetoothManagerService( 1103): Message: 20
D/BluetoothManagerService( 1103): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1f16a5d8:true
D/BtGatt.DebugUtils( 6090): handleDebugAction() action=null
D/BtGatt.GattService( 6090): Received start request. Starting profile...
D/BtGatt.GattService( 6090): start()
I/bluedroid-qcom( 6090): get_profile_interface gatt
D/BtGatt.AdvertiseManager( 6090): advertise manager created
I/ActivityManager( 1103): Killing 5480:com.android.gallery3d/u0a27 (adj 15): empty #17
D/LGBluetoothResetSettingReceiver( 6116): return without doing reset settings.
W/libprocessgroup( 1103): failed to open /acct/uid_10027/pid_5480/cgroup.procs: No such file or directory
,D/BluetoothAdapterService( 6090): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cc375d
,D/BluetoothAdapterService( 6090): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cc375d
I/LGBluetoothMapAdapter( 6090): [BTUI] getInstance : create [LGBluetoothMapAdapter]
V/BluetoothMapService( 6090): BluetoothMapBinder()
,D/BluetoothMapService( 6090): Received start request. Starting profile...
D/BluetoothMapService( 6090): start()
D/BluetoothMapEmailSettingsLoader( 6090): Found 0 applications
D/BluetoothMapEmailAppObserver( 6090): createReceiver()
D/BluetoothMapEmailAppObserver( 6090): initObservers()
D/BluetoothMapEmailAppObserver( 6090): getEnabledAccountItems()
,D/BluetoothAdapterService( 6090): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cc375d
D/BluetoothAdapterService( 6090): Profile still not running:com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 6090): Profile still not running:com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 6090): Profile still not running:com.android.bluetooth.gatt.GattService
,D/PCSuite ( 6196): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
W/FormManager( 6153): Network not available. Please check & try again.
D/BluetoothAdapterService( 6090): Profile still not running:com.android.bluetooth.gatt.GattService
V/PanService( 6090): [BTUI] SIM Extra State :ABSENT
V/FormManager( 6153): Network unavailable.
D/LGBluetoothOppAdapter( 6090): [BTUI] getInstance : create [LGBluetoothOppAdapter]
V/FormManager( 6153): Network unavailable.
,D/BluetoothAdapterService( 6090): Profile still not running:com.android.bluetooth.map.BluetoothMapService
V/BluetoothMapService( 6090): Handler(): got msg=1
D/BluetoothAdapterState( 6090): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid-qcom( 6090): enable
I/GKI_LINUX( 6090): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 6090): btu_task pending for preload complete event
I/bt_hci_bdroid( 6090): init
V/WiFiOffLoadBroadcast( 6116): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
I/bt_vendor( 6090): bt-vendor : init
I/bt_vendor( 6090): bt-vendor : get_bt_soc_type
E/bt_vendor( 6090): get_bt_soc_type: Failed to get soc type
I/bt_vendor( 6090): init: Local BD Address : c0:64:73:54:3f:58
D/bt_userial_mct( 6090): userial_init
,D/WiFiOffLoadBroadcast( 6116): MCCMNC not supported: null
D/bt_hci_bdroid( 6090): set_power 1
I/bt_vendor( 6090): bt-vendor : BT_VND_OP_POWER_CTRL: On
I/bt_vendor( 6090): Starting hciattach daemon
I/bt_vendor( 6090): try to set true
V/BluetoothFtpReceiver( 6090): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
W/sh      ( 6241): type=1400 audit(0.0:155): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/sh      ( 6241): type=1400 audit(0.0:156): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
V/BluetoothSapReceiver( 6090): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 6090): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 6090): SapReceiver onReceive 
V/BluetoothSapReceiver( 6090): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6090):  Bluetooth Adapter state = 11
I/qcom-bluetooth( 6242): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,I/ActivityManager( 1103): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6247 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,D/LGDMClient( 3956): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 3956): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 3956): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
I/qcom-bluetooth( 6254): /system/etc/init.qcom.bt.sh: Transport : smd 
W/ContextImpl( 3956): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
I/qcom-bluetooth( 6259): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,D/PostponalbeReceiver( 5173): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6196): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
I/qcom-bluetooth( 6268): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,D/LGDMClient( 3956): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/LGDMClient( 3956): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
D/PCSuite ( 6196): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6196): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/LGDMClient( 3956): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/qcom-bluetooth( 6271): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
V/WiFiOffLoadBroadcast( 6116): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/qcom-bluetooth( 6273): /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 6274): /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
W/ResourcesManager( 6247): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/libmdmdetect( 6276): ESOC framework not supported
,E/Diag_Lib( 6276):  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,D/WiFiOffLoadBroadcast( 6116): MCCMNC not supported: null
D/AuthorizationBluetoothService( 2117): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/bthci_qcomm_linux( 6276): [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:64:C0)
D/bthci_qcomm_common( 6276): [BTUI] bt_hci_qcomm_init:
D/bthci_qcomm_common( 6276): [BTUI]     BDADDR: 58:3F:54:73:64:C0
D/bthci_qcomm_common( 6276): [BTUI]     BR/EDR: Class 1
D/bthci_qcomm_common( 6276): [BTUI]     LE: Class 2
D/bthci_qcomm_common( 6276): [BTUI]     Ref Clock: 32M
D/btqsocnvmtags( 6276): [BTUI] init_riva_entries: set NORMAL power settings
I/ActivityManager( 1103): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6278 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/ActivityManager( 1103): Killing 5511:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
I/rmt_storage(  307): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  307): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  307): wakelock acquired: 1, error no: 42
I/rmt_storage(  307): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
,W/libprocessgroup( 1103): failed to open /acct/uid_10080/pid_5511/cgroup.procs: No such file or directory
,W/ResourcesManager( 6278): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/rmt_storage(  307): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  307): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
I/rmt_storage(  307): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 22
I/rmt_storage(  307): 
,I/rmt_storage(  307): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
E/Diag_Lib(  852): [IMS_FATAL]| 3347 | 873 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
D/QRemote ( 6278): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 6278): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
I/QRemote ( 6278): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 6278): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 6278): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 6278): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 6278): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 6278): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6278): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6278): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6278): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/QRemote ( 6278): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
V/[BNRBootReceiver]( 5879): boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/BNRAndroBeam( 5879): [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
D/QRemote ( 6278): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
V/[BNRBootReceiver]( 5879): Boot Receiver Return
D/PostponalbeReceiver( 5173): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6116): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6116): MCCMNC not supported: null
D/QRemote ( 6278): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6278): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6278): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/WiFiOffLoadBroadcast( 6116): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,D/WiFiOffLoadBroadcast( 6116): Not supported operator for automatic switch
D/PostponalbeReceiver( 5173): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6116): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6116): MCCMNC not supported: null
D/QRemote ( 6278): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6278): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6278): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 5173): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6116): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6116): MCCMNC not supported: null
D/QRemote ( 6278): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6278): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6278): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,V/QRemote ( 6278): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6278): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 6278): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,D/LgDataFeature( 6278): LgDataFeature() Constructor: none
D/LgDataFeature( 6278): LgDataFeature() Constructor Done, null
,V/SoundPool( 6278): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 6278): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 6278): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 6278): doLoad: loading sample sampleID=1
V/SoundPool( 6278): Start decode
V/MediaPlayer[Native]( 6278): decode(31, 10857164, 17813)
V/MediaPlayerService(  319): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  319): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  319): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  319): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  319): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  319): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  319): player type = 3
V/AwesomePlayer(  319): AwesomePlayer create()
V/AwesomePlayer(  319): reset_l() 
V/AwesomePlayer(  319): cancelPlayerEvents
V/AwesomePlayer(  319): setAudioSink() 
V/AwesomePlayer(  319): reset_l() 
V/AudioCache(  319): notify(0xb1432cc0, 8, 0, 0)
V/AudioCache(  319): ignored
V/AwesomePlayer(  319): cancelPlayerEvents
I/QRemote ( 6278): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
D/Utils   (  319): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  319): setDataSource_l dataSource
V/LGParserOSAL(  319): SniffLGParser start
V/LGParserOSAL(  319): MainType:5, SubType=0
V/LGParserOSAL(  319): #### check Mime : application/ogg
V/LGParserOSAL(  319): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  319): Use LGExtractor :application/ogg 
D/UEI.SmartControl( 5849): QS Service created
D/QRemote ( 6278): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
E/QRemote ( 6278): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6278): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,V/LGMDMManager( 6278): Create singleton instance
V/LGParserOSAL(  319): supported mime: application/ogg
V/AwesomePlayer(  319): setDataSource_l() extractor countTracks=1
,V/AwesomePlayer(  319): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  319): mBitrate = -1 bits/sec
V/AwesomePlayer(  319): AudioTrack Setting
I/UEI.SmartControl( 5849): Service initServices...
D/UEI.SmartControl( 5849): QS start get config
V/AwesomePlayer(  319): AudioTrack Setting channelCount = 2
,V/AwesomePlayer(  319): setAudioSource() 
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
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on input port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on input port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d80 on input port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7dd0 on input port
V/OMXCodec(  319): allocateBuffersOnPort portIndex=1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ec0 on output port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb57bb290 on output port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb57bb2e0 on output port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb57bb380 on output port
V/OMXCodec(  319): init() mAsyncCompletion wait!!! 
V/OMXCodec(  319): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  319): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  319): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  319): init() mAsyncCompletion wait!!! 
V/OMXCodec(  ,319): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  319): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  319): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  319): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  319): finishAsyncPrepare_l() 
V/AudioCache(  319): notify(0xb1432cc0, 5, 0, 0)
V/AudioCache(  319): ignored
V/AudioCache(  319): notify(0xb1432cc0, 1, 0, 0)
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
V/OMXCodec(  319): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885888
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044782736
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044782816
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044782976
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  319): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  319): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  319): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  319): allocateBuffersOnPort portIndex=1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb57bb2e0 on output port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb57bb290 on output port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ec0 on output port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb1434240 on output port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  319): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  319): open(48000, 2, 0x0, 1, 4)
,V/AudioCache(  319): notify(0xb1432cc0, 6, 0, 0)
V/AudioCache(  319): ignored
V/MediaPlayerService(  319): wait for playback complete
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab700000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab701000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab702000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab703000, 0xb165f000, 4096)
,V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab704000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab705000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab706000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab707000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab708000, 0xb165f000, 4096)
,V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab709000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab70a000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
,V/AudioCache(  319): memcpy(0xab70b000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab70c000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab70d000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab70e000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab70f000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab710000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab711000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab712000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab713000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab714000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab715000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab716000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab717000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab718000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab719000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab71a000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab71b000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab71c000, 0xb165f000, 4096)
,V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab71d000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab71e000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab71f000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab720000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab721000, 0xb165f000, 4096)
,V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab722000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab723000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab724000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab725000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab726000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab727000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab728000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab729000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab72a000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab72b000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab72c000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab72d000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab72e000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab72f000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab730000, 0xb165f000, 4096)
V/AudioCache(  319): write(0xb165f000, 4096)
V/AudioCache(  319): memcpy(0xab731000, 0xb165f000, 4096)
V/OMXCodec(  319): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  319): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  319): postAudioEOS() 
V/AudioCache(  319): write(0xb165f000, 280)
V/AudioCache(  319): memcpy(0xab732000, 0xb165f000, 280)
V/AwesomePlayer(  319): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  319): onStreamDone
V/AwesomePlayer(  319): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  319): notify(0xb1432cc0, 2, 0, 0)
V/AudioCache(  319): playback complete
V/AwesomePlayer(  319): pause_l() 
V/AudioCache(  319): notify(0xb1432cc0, 7, 0, 0)
V/AudioCache(  319): ignored
V/AwesomePlayer(  319): cancelPlayerEvents
D/AudioPlayer(  319): Pause Playback at 1068125
V/AudioCache(  319): wait - success
V/MediaPlayerService(  319): return size 205080, sampleRate=48000, channelCount = 2, format = 1
,D/QRemote ( 6278): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6278): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
V/AwesomePlayer(  319): reset_l() 
V/AudioCache(  319): notify(0xb1432cc0, 8, 0, 0)
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
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7dd0 on port 0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7d80 on port 0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c90 on port 0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7bf0 on port 0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeing buffer 0xb1434240 on port 1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ec0 on port 1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeing buffer 0xb57bb290 on port 1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeing buffer 0xb57bb2e0 on port 1
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
D/QRemote ( 6278): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:8421
V/OMXCodec(  319): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  319): AudioPlayer releasing audio source
D/AudioPlayer(  319): AudioPlayer done releasing audio source
V/AwesomePlayer(  319): reset_l() 
V/AwesomePlayer(  319): cancelPlayerEvents
V/AwesomePlayer(  319): ~AwesomePlayer call
V/AwesomePlayer(  319): reset_l() 
V/AwesomePlayer(  319): cancelPlayerEvents
V/SoundPool( 6278): close(31)
V/SoundPool( 6278): pointer = 0x9ff34000, size = 205080, sampleRate = 48000, numChannels = 2
V/AlarmManager( 1103): RTC_WAKEUP set : Alarm{b1f0423 type 0 when 1454983630242 com.android.vending} when 1454983630242
,V/AlarmManager( 1103): RTC_WAKEUP set : Alarm{5899d20 type 0 when 1454983638166 android} when 1454983638166
E/WifiStateMachine( 1103):  DisconnectedState CMD_START_SCAN -2 -2 ic=1 proc(ms):2 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=120000 [on:0 tx:0 rx:0 period:-1010273913] from screen [on:0 period:-1010273913]
E/WifiStateMachine( 1103):  ConnectModeState CMD_START_SCAN -2 -2 ic=1 proc(ms):7 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=120000 [on:0 tx:0 rx:0 period:6] from screen [on:0 period:-1010273907]
E/WifiStateMachine( 1103):  DriverStartedState CMD_START_SCAN -2 -2 ic=1 proc(ms):11 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=120000 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1010273906]
D/WifiNative-wlan0( 1103): doBoolean: SCAN
D/WifiNative-wlan0( 1103): SCAN: returned false
,W/ContextImpl( 4190): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,V/SIM_STK ( 1103): Menu title from STK is T-Mobile
,I/UEI.SmartControl( 5849): Supports setup maps: true
D/UEI.SmartControl( 5849): QS start statue = true Error code = 0
I/UEI.SmartControl( 5849): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 5849): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 5849): ### init IR Blaster...
,D/serial_port( 5849): Configuring serial port
E/UEI.SmartControl( 5849): UEIBLaster setting for 616
I/UEI.SmartControl( 5849): Setting serial record hearder size = 2
I/UEI.SmartControl( 5849): configuring settings for MAXQ616
I/UEI.SmartControl( 5849): Get version...
D/UEI.SmartControl( 5849): serial port data available: 21
,D/UEI.SmartControl( 5849): MAXQ616 A2-X4 software.
,I/UEI.SmartControl( 5849): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 5849): QS saving settings...
D/UEI.SmartControl( 5849): IR Blaster version: 25672567
,D/UEI.SmartControl( 5849): serial port data available: 4
W/ContextImpl( 5849): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,E/UEI.SmartControl( 5849): Services init done
D/UEI.SmartControl( 5849): QS Service init finished
D/UEI.SmartControl( 5849): QS Service version name: 2.1.91
D/UEI.SmartControl( 5849): QS Service version code: 201091
D/UEI.SmartControl( 5849): Service requested: Control
I/UEI.SmartControl( 5849): Device manager: loading config....
I/QRemote ( 6278): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
D/UEI.SmartControl( 5849): ----------- loading internal config...
I/UEI.SmartControl( 5849): ------ IControl API: 11
D/UEI.SmartControl( 5849): File observer start...
E/UEI.SmartControl( 5849): IR Port is disabled: false
D/UEI.SmartControl( 5849): Starting file observer...
I/UEI.SmartControl( 5849): Registering callback...
D/UEI.SmartControl( 5849): Internal service binding...
I/UEI.SmartControl( 5849): ------ IControl API: 19
I/UEI.SmartControl( 5849): Registering Services Ready callback...
E/UEI.SmartControl( 5849): Loading SETTINGS...
D/UEI.SmartControl( 5849): -- Open brand translation xml: brands_translations_ko
V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2117): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2117): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2117): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2117): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/UEI.SmartControl( 5849): Notify AllClients services are ready: 0
D/UEI.SmartControl( 5849): -----service ready thread exits
I/QRemote ( 6278): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 6278): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 6278): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 6278): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 6278): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 5849): ------ IControl API: 8
E/QC-QMI  ( 6276): qmi_client [6276] 13: failed to locate client data
E/QC-QMI  (  486): qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
E/QC-QMI  (  486): QMUX qmux_client_id=13 not found in qmux client list, unable to remove
,D/QRemote ( 6278): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 6278): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 6278): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 6278): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 6278): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6278): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/Finsky  ( 4885): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 4885): [1] 5.onFinished: Installation state replication failed.
D/QRemote ( 6278): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
D/Finsky  ( 4885): [1] 5.onFinished: Scheduling replication attempt 1.
V/QRemote ( 6278): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6278): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,E/QRemote ( 6278): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6278): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 6278): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6278): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 6278): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 6278): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1454983639713]
D/QRemote ( 6278): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
I/ActivityManager( 1103): Killing 5757:com.google.android.apps.docs/u0a61 (adj 15): empty #17
D/QRemote ( 6278): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,I/qcom-bluetooth( 6327): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:64:c0 
,W/libprocessgroup( 1103): failed to open /acct/uid_10061/pid_5757/cgroup.procs: No such file or directory
,V/QRemote ( 6278): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
E/QRemote ( 6278): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6278): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
,D/QRemote ( 6278): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 6278): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
I/qcom-bluetooth( 6328): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
D/QRemote ( 6278): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 6278): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 6278): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,I/bt_vendor( 6090): bluetooth satus is on
D/bt_hci_bdroid( 6090): preload
D/bt_userial_mct( 6090): userial_open(port:0)
I/bt_vendor( 6090): bt-vendor : BT_VND_OP_USERIAL_OPEN
I/bt_vendor( 6090): Done intiailizing UART
,I/bt_vendor( 6090): Done intiailizing UART
I/bt_userial_mct( 6090): CMD=66, EVT=66, ACL_Out=67, ACL_In=67
,I/bt_vendor( 6090): Bluetooth Firmware and transport layer are initialized
I/bt-btu  ( 6090): btu_task received preload complete event
D/bt_userial_mct( 6090): Entering userial_read_thread()
W/bt-l2cap( 6090): L2CAP - L2CA_Register() called for PSM: 0x0001
W/bt-l2cap( 6090): L2CAP - L2CA_Register() called for PSM: 0x001f
W/bt-l2cap( 6090): L2CAP - L2CA_Register() called for PSM: 0x0003
I/        ( 6090): BTE_InitTraceLevels -- TRC_HCI
I/        ( 6090): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 6090): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 6090): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 6090): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 6090): BTE_InitTraceLevels -- TRC_A2D
I/        ( 6090): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 6090): BTE_InitTraceLevels -- TRC_BTM
I/        ( 6090): BTE_InitTraceLevels -- TRC_HID_HOST
I/        ( 6090): BTE_InitTraceLevels -- TRC_GAP
I/        ( 6090): BTE_InitTraceLevels -- TRC_PAN
I/        ( 6090): BTE_InitTraceLevels -- TRC_SDP
I/        ( 6090): BTE_InitTraceLevels -- TRC_GATT
I/        ( 6090): BTE_InitTraceLevels -- TRC_SMP
I/        ( 6090): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 6090): BTE_InitTraceLevels -- TRC_BTIF
W/bt-btm  ( 6090): btm_decode_ext_features_page Secure conn Controller support Enabled
E/bt-btm  ( 6090): BTM_SecRegister:p_cb_info->p_le_callback == 0xa01ce061 
E/bt-btm  ( 6090): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01ce061 
,W/bt-l2cap( 6090): Calling BTA_HhEnable
E/bt-btif ( 6090): Calling BTA_HhEnable
W/bt-l2cap( 6090): L2CAP - L2CA_Register() called for PSM: 0x0017
W/bt-l2cap( 6090): L2CAP - L2CA_Register() called for PSM: 0x001b
W/bt-l2cap( 6090): L2CAP - L2CA_Register() called for PSM: 0x0011
W/bt-l2cap( 6090): L2CAP - L2CA_Register() called for PSM: 0x0013
E/bt-btif ( 6090): btif_storage_get_adapter_property service_mask:0x2140040
D/BluetoothAdapterProperties( 6090): Address is:58:3F:54:73:64:C0
D/BluetoothManagerService( 1103): Bluetooth Adapter name changed to G3-1
D/BluetoothManagerService( 1103): Stored Bluetooth name: G3-1
D/BluetoothAdapterProperties( 6090): Name is: G3-1
,D/BluetoothAdapterProperties( 6090): Scan Mode:20
D/BluetoothAdapterProperties( 6090): Discoverable Timeout:120
D/bt_hci_bdroid( 6090): postload
D/bt_hci_bdroid( 6090): Used up Tx Cmd credits
W/bt-l2cap( 6090): L2CAP - L2CA_Register() called for PSM: 0x000f
W/bt-smp  ( 6090): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6090): Plain text(LSB ~ MSB) = c7 1e 7e 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6090): Encrypted text(LSB ~ MSB) = 24 e4 6e 7e 84 7b e2 65 f8 15 12 f5 c9 49 bb f8 
W/bt-btm  ( 6090): Stopping oneshot timer
D/bt_hci_bdroid( 6090): Used up Tx Cmd credits
,D/bt_hci_bdroid( 6090): Used up Tx Cmd credits
D/bt_hci_bdroid( 6090): Used up Tx Cmd credits
D/bte_conf( 6090): Device ID record 1 : primary
D/bte_conf( 6090):   vendorId            = 00c4
D/bte_conf( 6090):   vendorIdSource      = 0001
D/bte_conf( 6090):   product             = 13a1
D/bte_conf( 6090):   version             = 1000
D/bte_conf( 6090):   clientExecutableURL = 
D/bte_conf( 6090):   serviceDescription  = 
D/bte_conf( 6090):   documentationURL    = 
D/bte_conf( 6090): bte_load_did_conf no section named DID2.
E/bt_mct  ( 6090): hci lib postload completed
D/BluetoothAdapterState( 6090): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 6090): ScanMode =  20
D/BluetoothAdapterProperties( 6090): State =  11
D/BluetoothPanServiceJni( 6090): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothAdapterProperties( 6090): mDiscoverableTimeout = 120
W/sh      ( 6332): type=1400 audit(0.0:157): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,W/sh      ( 6332): type=1400 audit(0.0:158): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/bt-smp  ( 6090): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6090): Plain text(LSB ~ MSB) = b1 99 40 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6090): Encrypted text(LSB ~ MSB) = 30 32 df 66 29 c7 2a 4d 4a bf f7 16 39 f5 d7 5d 
W/bt-btm  ( 6090): Stopping oneshot timer
V/LGBluetoothServiceAdapter( 6090): [BTUI] state:11, scanmode:20, timeout:120
D/BluetoothAdapterProperties( 6090): Setting state to 12
I/BluetoothAdapterState( 6090): Bluetooth adapter state changed: 11-> 12
D/BluetoothManagerService( 1103): Message: 60
D/BluetoothManagerService( 1103): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
I/BluetoothAdapterState( 6090): Entering On State
D/BluetoothManagerService( 1103): Broadcasting onBluetoothStateChange(true) to 5 receivers.
D/BluetoothHeadset( 1860): onBluetoothStateChange: up=true
D/btif_config_util( 6090): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
D/BluetoothHeadset( 1860): onBluetoothStateChange: up=true
D/BluetoothA2dp( 1103): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1103): onBluetoothStateChange: up=true
D/LGBluetoothServiceAdapter( 6090): [BTUI] OnState
D/LGBluetoothServiceAdapter( 6090): [BTUI]         global_name: G3-1
D/BluetoothHeadset( 1860): onBluetoothStateChange: up=true
D/LGBluetoothServiceAdapter( 6090): [BTUI]         local_name: G3-1
E/BluetoothManagerService( 1103): Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
D/BluetoothManagerService( 1103): Bluetooth State Change Intent: 11 -> 12
D/BluetoothAdapterService( 6090): [BTUI] autoConnect() : not allowed
I/[SystemUI]BluetoothHandler( 1451): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
W/bt-smp  ( 6090): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6090): Plain text(LSB ~ MSB) = f7 33 45 00 00 00 00 00 00 00 00 00 00 00 00 00 
D/LGBluetoothAPIService( 1948): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/LGBluetoothAPIService( 1948): Message: 1
D/LGBluetoothAPIService( 1948): MESSAGE_BOOT_COMPLETED
W/bt-smp  ( 6090): Encrypted text(LSB ~ MSB) = 19 1d be db 74 ac 58 f7 e6 04 bc 4c 88 60 28 24 
W/bt-btm  ( 6090): Stopping oneshot timer
D/BluetoothManagerService( 1103): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,D/BluetoothManagerService( 1103): Message: 40
D/BluetoothManagerService( 1103): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
I/BluetoothMapService( 6090): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 6090): STATE_ON
I/LGBluetoothAPIService( 1948): [BTUI] LGBluetoothAPIService Binding Success
D/BluetoothAdapterService( 6090): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cc375d
V/BluetoothPbapService( 6090): Pbap Service onCreate
V/BluetoothPbapService( 6090): Starting PBAP service
,D/LGBluetoothPbapAdapter( 6090): [BTUI] getInstance : create
V/BluetoothMapService( 6090): Handler(): got msg=1
D/BluetoothMapMasInstance( 6090): Map Service startRfcommSocketListener
V/BluetoothPbapService( 6090): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 6090): state: 12
D/BluetoothMapMasInstance( 6090): MAS initSocket()
D/BluetoothMapMasInstance( 6090):   masId = 00
D/BluetoothMapMasInstance( 6090):   msgTypes = 0e
D/BluetoothMapMasInstance( 6090):   masName = SMS/MMS
D/BluetoothMapMasInstance( 6090):   SDP string = 000eSMS/MMS
W/bt-smp  ( 6090): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6090): Plain text(LSB ~ MSB) = e8 14 7f 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6090): Encrypted text(LSB ~ MSB) = 09 70 ef 1e 26 56 3f 65 9f 5b bb 8f 56 9b 9e cf 
D/BluetoothManagerService( 1103): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/bt-btm  ( 6090): Stopping oneshot timer
W/ContextImpl( 6116): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
D/LGBluetoothAPIServer( 6090): [BTUI] onCreate()
D/LGBluetoothAPIServer( 6090): [BTUI] onBind()
,W/BluetoothAdapter( 6090): getBluetoothService() called with no BluetoothManagerCallback
V/BluetoothPbapService( 6090): Handler(): got msg=1
V/BluetoothPbapService( 6090): Pbap Service startRfcommSocketListener
D/LGBluetoothAPIService( 1948): [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
D/LGBluetoothAPIService( 1948): Message: 100
D/LGBluetoothAPIService( 1948): MESSAGE_BLUETOOTH_SERVICE_CONNECTED
V/BluetoothPbapReceiver( 6090): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 6090): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6090): ***********state = 12
V/BluetoothPbapService( 6090): Pbap Service initSocket
W/bt-smp  ( 6090): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6090): Plain text(LSB ~ MSB) = 3a a1 7d 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6090): Encrypted text(LSB ~ MSB) = 8f 7a 86 3a 5c 4b 74 5b e9 4c 53 d8 0d 8a e8 69 
W/bt-btm  ( 6090): Stopping oneshot timer
D/BluetoothManagerService( 1103): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/LGBluetoothDeviceModeControllManager( 6090): [BTUI] checkDeviceModeAndSet, sinkMode : false
D/LGBluetoothServiceAdapter( 6090): [BTUI] createSocketChannel FD=73 mFd=0
W/BluetoothAdapter( 6090): getBluetoothService() called with no BluetoothManagerCallback
V/BluetoothMapMasInstance( 6090): Succeed to create listening socket 
D/BluetoothMapMasInstance( 6090): Accepting socket connection...
D/LGBluetoothServiceAdapter( 6090): [BTUI] createSocketChannel FD=75 mFd=73
V/BluetoothPbapService( 6090): Succeed to create listening socket 
V/BluetoothPbapService( 6090): Accepting socket connection...
D/LocalBluetoothProfileManager( 6116): Adding local A2DP profile
D/BluetoothManagerService( 1103): Message: 30
,I/qcom-bt-wlan-coex( 6341): /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,D/LocalBluetoothProfileManager( 6116): Adding local HEADSET profile
D/BluetoothManagerService( 1103): Message: 30
D/BluetoothManagerService( 1103): Message: 30
D/BluetoothManagerService( 1103): Message: 30
D/LocalBluetoothProfileManager( 6116): Adding local MAP profile
D/BluetoothMap( 6116): Create BluetoothMap proxy object
,D/BluetoothManagerService( 1103): Message: 30
I/art     ( 1103): Explicit concurrent mark sweep GC freed 46111(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 1.964ms total 73.298ms
,D/BluetoothManagerService( 1103): Message: 30
V/BluetoothPbapService( 6090): Pbap Service onBind
D/LocalBluetoothProfileManager( 6116): LocalBluetoothProfileManager construction complete
D/LGBluetoothUserBindClient( 6116): [BTUI] initUserBindClient
W/ContextImpl( 6116): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
,D/DockEventReceiver( 6116): finishStartingService: stopping service
D/BluetoothA2dp( 6116): Proxy object connected
D/A2dpProfile( 6116): Bluetooth service connected
D/BluetoothHeadset( 6116): Proxy object connected
,D/HeadsetProfile( 6116): Bluetooth service connected
D/BluetoothInputDevice( 6116): Proxy object connected
D/HidProfile( 6116): Bluetooth service connected
D/BluetoothPan( 6116): BluetoothPAN Proxy object connected
D/PanProfile( 6116): Bluetooth service connected
D/BluetoothMap( 6116): Proxy object connected
D/MapProfile( 6116): Bluetooth service connected
D/BluetoothMap( 6116): getConnectedDevices()
V/BluetoothMapService( 6090): getConnectedDevices()
D/BluetoothPbap( 6116): Proxy object connected
D/PbapServerProfile( 6116): Bluetooth service connected
D/LGBluetoothUserBindClient( 6116): [BTUI] onServiceConnected
D/BluetoothPermissionRequest( 6116): onReceive
,D/BluetoothAdapterProperties( 6090): Discoverable Timeout:120
D/LGBluetoothDeviceModeControllManager( 6090): adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
D/BluetoothAdapterProperties( 6090): Scan Mode:21
D/LGBluetoothDeviceModeControllManager( 6090): getDeviceMode  deviceMode 0
D/LGBluetoothFeatureConfig( 6116): isPrivacyLogsEnabled : true
D/LGBluetoothUtils( 6116): [BTUI] FileNotFound: readProperty
D/LGBluetoothResetSettingReceiver( 6116): return without doing reset settings.
V/BluetoothOppReceiver( 6090): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
I/LGBluetoothOppAdapter( 6090): [BTUI] startOppService()
V/BluetoothOppManager( 6090): restoreApplicationData! falsefalsenullnull
,D/LGBluetoothFeatureConfig( 6090): isPrivacyLogsEnabled : true
V/BtOppService( 6090): onCreate
,V/BluetoothOppNotification( 6090): send message
V/BtOppService( 6090): Starting RfcommListener
D/BluetoothOppPreference( 6090): Dumping Names:  
D/BluetoothOppPreference( 6090): {}
D/BluetoothOppPreference( 6090): Dumping Channels:  
D/BluetoothOppPreference( 6090): {}
V/BtOppService( 6090): onStartCommand
V/BtOppService( 6090): pendingUpdate is true keepUpdateThread is false sListenStarted is true
V/BluetoothFtpReceiver( 6090): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpReceiver( 6090): BluetoothFtpReceiver Start Service
V/BluetoothOppNotification( 6090): new notify threadi!
,V/BluetoothOppNotification( 6090): send delay message
V/BtOppService( 6090): start RfcommListener
V/BluetoothOppProvider( 6090): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6090): created cursor android.database.sqlite.SQLiteCursor@3dfad9cf on behalf of 
,V/BtOppService( 6090): Deleted complete outbound shares, number =  0
,V/BtOppService( 6090): RfcommListener started
V/BluetoothOppProvider( 6090): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
V/BtOppRfcommListener( 6090): Starting RFCOMM listener....
D/BluetoothManagerService( 1103): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6090): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 6090): [BTUI] createSocketChannel FD=79 mFd=75
V/BtOppRfcommListener( 6090): Started RFCOMM listener....
I/BtOppRfcommListener( 6090): Accept thread started.
V/BtOppRfcommListener( 6090): Accepting connection...
V/BtOppService( 6090): pendingUpdate is true keepUpdateThread is false sListenStarted is true
V/BluetoothOppProvider( 6090): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
V/BtOppService( 6090): Deleted complete inbound failed shares, number = 0
V/BluetoothOppProvider( 6090): starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6090): created cursor android.database.sqlite.SQLiteCursor@1745ff5c on behalf of 
V/BluetoothOppProvider( 6090): created cursor android.database.sqlite.SQLiteCursor@19c3f265 on behalf of 
V/BluetoothOppNotification( 6090): mUpdateCompleteNotification = true
V/BluetoothOppProvider( 6090): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 6090): created cursor android.database.sqlite.SQLiteCursor@b672b3a on behalf of 
V/BluetoothOppNotification( 6090): update too frequent, put in queue
,V/BtOppService( 6090): pendingUpdate is false keepUpdateThread is false sListenStarted is true
V/BluetoothOppProvider( 6090): created cursor android.database.sqlite.SQLiteCursor@32f543eb on behalf of 
D/BluetoothAdapterService( 6090): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cc375d
V/BluetoothFtpService( 6090): Ftp Service onCreate
I/BluetoothFtpService( 6090): Ftp Service onCreate
V/BluetoothFtpService( 6090): Ftp Service onStartCommand
V/BluetoothFtpService( 6090): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpService( 6090): Starting Listening on sockets
V/BluetoothSapReceiver( 6090): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 6090): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 6090): SapReceiver onReceive 
V/BluetoothSapReceiver( 6090): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6090):  Bluetooth Adapter state = 12
V/BluetoothSapReceiver( 6090): Calling SAP service start service with action = null
V/BluetoothOppNotification( 6090): outbound: succ-0  fail-0
V/BtOppService( 6090): ContentObserver received notification
V/BtOppService( 6090): ContentObserver received notification
V/BluetoothFtpService( 6090): Handler(): got msg=1
V/BluetoothFtpService( 6090): Ftp Service startRfcommSocketListener
V/BluetoothFtpService( 6090): Ftp Service initSocket
I/wpa_supplicant( 6133): wlan0: CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1
D/WifiMonitor( 1103): Event [IFNAME=wlan0 CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1]
E/WifiMonitor( 1103): WifiMonitor:wlan0 cnt=12 dispatchEvent: CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1
D/WifiMonitor( 1103): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1103): WifiMonitor:wlan0 cnt=13 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=00:00:00:00:00:00 SSID=NG700
V/BtOppService( 6090): pendingUpdate is true keepUpdateThread is false sListenStarted is true
E/WifiStateMachine( 1103):  DisconnectedState ASSOCIATION_REJECTION_EVENT 12 1 c0:ff:d4:d3:aa:48 blacklist=false rt=111321
V/BluetoothOppProvider( 6090): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
E/WifiStateMachine( 1103):  ConnectModeState ASSOCIATION_REJECTION_EVENT 12 1 c0:ff:d4:d3:aa:48 blacklist=false rt=111322
E/WifiStateMachine( 1103):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 13 0 rt=111322  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: DISCONNECTED
V/BluetoothOppProvider( 6090): created cursor android.database.sqlite.SQLiteCursor@16064fe1 on behalf of 
D/BluetoothManagerService( 1103): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6090): getBluetoothService() called with no BluetoothManagerCallback
V/BluetoothOppNotification( 6090): outbound notification was removed.
V/BluetoothOppNotification( 6090): update too frequent, put in queue
E/WifiStateMachine( 1103):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 13 0 rt=111324  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: DISCONNECTED
V/BtOppService( 6090): pendingUpdate is false keepUpdateThread is false sListenStarted is true
,V/BluetoothOppProvider( 6090): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 6090): created cursor android.database.sqlite.SQLiteCursor@360cc106 on behalf of 
D/AuthorizationBluetoothService( 2117): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
V/BluetoothOppNotification( 6090): inbound: succ-0  fail-0
D/WifiHS20( 1103): hidePasspointNotification off =false
D/LGBluetoothServiceAdapter( 6090): [BTUI] createSocketChannel FD=81 mFd=79
V/BluetoothFtpService( 6090): Succeed to create listening socket on channel 20
I/StatusBar.NetworkController( 1451): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1451): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1103): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1103): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1103): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiServerServiceExt( 1103): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1103): setSupplicantStateDISCONNECTED
V/BluetoothFtpService:RfcommSocketAcceptThread( 6090): Run Accept thread
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PostponalbeReceiver( 5173): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6196): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6196): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6196): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6116): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/BluetoothAdapterService( 6090): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cc375d
V/BluetoothSapService( 6090): Sap Service onCreate
V/BluetoothOppNotification( 6090): inbound notification was removed.
V/BluetoothOppProvider( 6090): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
V/BluetoothSapService( 6090): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 6090): state: 12
V/BluetoothSapService( 6090): Starting SAP server process
V/BluetoothSapService( 6090): SAP Service startRfcommListenerThread
D/WiFiOffLoadBroadcast( 6116): MCCMNC not supported: null
W/sapd    ( 6358): type=1400 audit(0.0:159): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/sapd    ( 6358): type=1400 audit(0.0:160): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
V/BluetoothSapService( 6090): Sap Service initRfcommSocket
V/BluetoothOppProvider( 6090): created cursor android.database.sqlite.SQLiteCursor@1b23e792 on behalf of 
D/BluetoothManagerService( 1103): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6090): getBluetoothService() called with no BluetoothManagerCallback
V/BT_SAP  ( 6358): Event pipe created
V/BT_SAP  ( 6358): create_server_socket qcom.sap.server
V/BT_SAP  ( 6358): created socket fd 6
D/QRemote ( 6278): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6278): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/LGBluetoothServiceAdapter( 6090): [BTUI] createSocketChannel FD=82 mFd=81
V/BluetoothSapService( 6090): Succeed to create listening socket 
V/BluetoothSapService( 6090): Accepting socket connection...
I/QRemote ( 6278): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/WifiMonitor( 1103): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1103): WifiMonitor:wlan0 cnt=14 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
I/wpa_supplicant( 6133): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1103): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1103): WifiMonitor:wlan0 cnt=15 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1103): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1103): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine( 1103):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 14 0 rt=111423  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,I/StatusBar.NetworkController( 1451): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1451): mWifiConnected = false, mWifiLevel = 0
D/WifiHS20( 1103): hidePasspointNotification off =false
W/Settings( 1103): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1103): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1103): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PostponalbeReceiver( 5173): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/WifiStateMachine( 1103):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 14 0 rt=111438  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,I/StatusBar.NetworkController( 1451): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/StatusBar.NetworkController( 1451): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1103): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1103): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1103): NETWORK_STATE_CHANGED_ACTION [SCANNING]
,D/WifiServerServiceExt( 1103): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1103): setSupplicantStateSCANNING
I/PCSuite ( 6196): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6196): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6196): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6116): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6116): MCCMNC not supported: null
D/QRemote ( 6278): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6278): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6278): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 5173): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6116): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6116): MCCMNC not supported: null
D/QRemote ( 6278): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6278): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6278): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/BluetoothOppNotification( 6090): new notify threadi!
V/BluetoothOppNotification( 6090): send delay message
,V/BluetoothOppProvider( 6090): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,V/BluetoothOppProvider( 6090): created cursor android.database.sqlite.SQLiteCursor@2bc44563 on behalf of 
,V/BluetoothOppNotification( 6090): mUpdateCompleteNotification = true
V/BluetoothOppProvider( 6090): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 6090): created cursor android.database.sqlite.SQLiteCursor@3d47e560 on behalf of 
V/BluetoothOppNotification( 6090): outbound: succ-0  fail-0
V/BluetoothOppNotification( 6090): outbound notification was removed.
V/BluetoothOppProvider( 6090): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 6090): created cursor android.database.sqlite.SQLiteCursor@7c01a19 on behalf of 
V/BluetoothOppNotification( 6090): inbound: succ-0  fail-0
V/BluetoothOppNotification( 6090): inbound notification was removed.
V/BluetoothOppProvider( 6090): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6090): created cursor android.database.sqlite.SQLiteCursor@1d14eade on behalf of 
I/jxcore-log( 6035): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 6035): 
,I/wpa_supplicant( 6133): Trying to associate with SSID 'NG700'
E/WifiMonitor( 1103): WifiMonitor:wlan0 cnt=16 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1103): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1103): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1103): WifiMonitor:wlan0 cnt=17 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1103): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1103): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1103): WifiMonitor:wlan0 cnt=18 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1103):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1103):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1103):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1103):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
I/WifiNative-HAL( 1103): startHal
E/wifi    ( 1103): getStaticLongField sWifiHalHandle 0x988358cc
E/WifiHAL ( 1103): Could not connect handle
D/wifi    ( 1103): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x60212e
I/WifiNative-HAL( 1103): Could not start hal
D/WifiNative-wlan0( 1103): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1103):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=113545  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
E/WifiStateMachine( 1103):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=113546  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,I/StatusBar.NetworkController( 1451): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1451): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1103): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1103): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1103): NETWORK_STATE_CHANGED_ACTION [SCANNING]
,I/StatusBar.NetworkController( 1451): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1451): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1103): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1103): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1103): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/WifiServerServiceExt( 1103): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1103): setSupplicantStateASSOCIATING
V/WiFiOffLoadBroadcast( 6116): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
D/WiFiOffLoadBroadcast( 6116): Not supported operator for automatic switch
D/PostponalbeReceiver( 5173): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6116): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/wpa_supplicant( 6133): wlan0: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1103): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1103): WifiMonitor:wlan0 cnt=19 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1103): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1103): WifiMonitor:wlan0 cnt=20 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1103): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1103): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering( 1103): sendTetherStateChangedBroadcast 1, 0, 0
E/WifiStateMachine( 1103):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=113632  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1103):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=113633  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1103):  DisconnectedState CMD_ASSOCIATED_BSSID 20 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=113634
D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=0
E/WifiStateMachine( 1103):  ConnectModeState CMD_ASSOCIATED_BSSID 20 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=113634
D/DSQN    ( 1103): DNSproblemNotiEnabled is disabled ignore DNS fail CB
E/WifiStateMachine( 1103):  DriverStartedState CMD_ASSOCIATED_BSSID 20 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=113635
E/WifiStateMachine( 1103):  SupplicantStartedState CMD_ASSOCIATED_BSSID 20 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=113635
E/WifiStateMachine( 1103):  DefaultState CMD_ASSOCIATED_BSSID 20 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=113636
E/WifiStateMachine( 1103):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=113636  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
I/wpa_supplicant( 6133): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 6133): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1103): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1103): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1103): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1103): WifiMonitor:wlan0 cnt=23 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1103): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1103): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1103): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1103): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1103): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1103): WifiMonitor:wlan0 cnt=25 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
W/Settings( 1103): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1103): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1103): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
E/WifiStateMachine( 1103):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=113641  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
I/StatusBar.NetworkController( ,1451): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/WifiStateMachine( 1103):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
I/StatusBar.NetworkController( 1451): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1103):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1103):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1103):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1103):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,W/Settings( 1103): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1103): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1103): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1451): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1451): mWifiConnected = false, mWifiLevel = 0
D/WifiServerServiceExt( 1103): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1103): setSupplicantStateASSOCIATED
E/WifiStateMachine( 1103):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=113652  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1103):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=113652  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1103):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=113653
E/WifiStateMachine( 1103):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=113653
D/WifiNative-wlan0( 1103): doString: [STATUS]
D/WifiMonitor( 1103): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1103): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1103):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
D/WiFiOffLoadBroadcast( 6116): MCCMNC not supported: null
I/WifiServiceExtension( 1103): setVHTCapabilityType  : false
,D/QRemote ( 6278): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6278): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/WifiServerServiceExt( 1103): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1103): setKeepAlivePacketInterval msec : 60
W/Settings( 1103): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1103): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1103): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/StatusBar.NetworkController( 1451): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1451): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
I/QRemote ( 6278): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,W/Settings( 1103): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1103): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1103): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/PostponalbeReceiver( 5173): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/StatusBar.NetworkController( 1451): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1451): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WiFiOffLoadBroadcast( 6116): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/ConnectivityService( 1103): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService( 1103): Got NetworkAgent Messenger
,E/WifiConfigStore( 1103): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1103): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1103): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1103): doBoolean: SAVE_CONFIG
D/ConnectivityService( 1103): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1103): NetworkAgent connected
D/WiFiOffLoadBroadcast( 6116): MCCMNC not supported: null
D/WifiNative-wlan0( 1103): SAVE_CONFIG: returned true
,E/WifiConfigStore( 1103): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1103): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1103): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1103): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1103): SAVE_CONFIG: returned true
D/CommandListener(  313): Setting iface cfg
D/DhcpStateMachine( 1103): StoppedState
E/WifiStateMachine( 1103): Start Dhcp Watchdog 1
D/DhcpStateMachine( 1103): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1103): WaitBeforeStartState
E/WifiStateMachine( 1103):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 25 0 rt=113694  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
,E/WifiStateMachine( 1103):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 25 0 rt=113695  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1103):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 25 0 rt=113695  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WifiServerServiceExt( 1103): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1103): setSupplicantStateFOUR_WAY_HANDSHAKE
D/WifiServerServiceExt( 1103): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1103): setSupplicantStateGROUP_HANDSHAKE
D/QRemote ( 6278): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6278): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
E/WifiStateMachine( 1103):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=113698  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
I/QRemote ( 6278): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
E/WifiStateMachine( 1103):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=113699  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1103):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=113700  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/UsbSettingsReceiver( 6116): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6116): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6116): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6116): [AUTORUN] persist.sys.usb.config = ptp_only,adb
E/WifiStateMachine( 1103):  ObtainingIpState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3163] from screen [on:0 period:-1010270742]
D/UsbSettingsReceiver( 6116): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 6116): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6116): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6116): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6116): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6116): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6116): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 6116): [AUTORUN] setTetherStatus() : status=false
E/WifiStateMachine( 1103):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1010270741]
D/WifiNative-wlan0( 1103): doString: [SIGNAL_POLL]
D/PostponalbeReceiver( 5173): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/ConnectivityService( 1103): updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
E/WifiStateMachine( 1103):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1103):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1103):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1103):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1103):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1103):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1103): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
E/WifiStateMachine( 1103):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
V/WiFiOffLoadBroadcast( 6116): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 1103):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
D/WifiNative-wlan0( 1103): doBoolean: DRIVER SETSUSPENDMODE 0
D/WiFiOffLoadBroadcast( 6116): MCCMNC not supported: null
D/QRemote ( 6278): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6278): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6278): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 5173): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6116): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6116): MCCMNC not supported: null
D/QRemote ( 6278): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6278): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6278): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 5173): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6116): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/wpa_supplicant( 6133): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1103): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1103): doBoolean: SET ps 0
D/WifiNative-wlan0( 1103): SET ps 0: returned true
D/WifiNative-wlan0( 1103): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 6133): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1103): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1103): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1103): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1103): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
V/LgDhcpStateMachineHelper( 1103): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700" is not exist.
D/WifiServerServiceExt( 1103): SUPPLICANT_STATE_CHANGED_ACTION
D/LGWifiP2pService( 1103): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1fd52c28 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiServerServiceExt( 1103): setSupplicantStateCOMPLETED
,D/LGWifiP2pService( 1103): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1fd52c28 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1103): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1103): DHCP Start wake lock is acquired.
D/WifiServerServiceExt( 1103): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1103): setSupplicantStateCOMPLETED
D/WiFiOffLoadBroadcast( 6116): MCCMNC not supported: null
,D/QRemote ( 6278): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6278): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6278): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 5173): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6116): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6116): MCCMNC not supported: null
D/QRemote ( 6278): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6278): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6278): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/DhcpStateMachine( 1103): DHCPV4 request on wlan0
,V/LgDhcpStateMachineHelper( 1103): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1103): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
W/dhcpcd  ( 6417): type=1400 audit(0.0:161): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 6417): type=1400 audit(0.0:162): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,I/dhcpcd  ( 6417): version 5.5.6 starting
,E/dhcpcd  ( 6417): get_duid: m
D/dhcpcd  ( 6417): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 6417): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
D/dhcpcd  ( 6417): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
,D/dhcpcd  ( 6417): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 6417): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,I/dhcpcd  ( 6417): wlan0: rebinding lease of 192.168.1.141
,D/dhcpcd  ( 6417): wlan0: sending REQUEST (xid 0xf5157ec0), next in 3.13 seconds
I/jxcore-log( 6035): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 6035): 
,I/jxcore-log( 6035): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 6035): 
,I/jxcore-log( 6035): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 6035): 
,I/CloudHub( 2189): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19968
,I/jxcore-log( 6035): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 6035): 
,I/jxcore-log( 6035): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 6035): 
,I/jxcore-log( 6035): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
I/jxcore-log( 6035): 
,I/jxcore-log( 6035): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 6035): 
,I/jxcore-log( 6035): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 6035): 
E/WifiStateMachine( 1103):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1103):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 1103):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 1103):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1103):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1103):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1103): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
D/UEI.SmartControl( 5849): Internal timer expired: 4
D/UEI.SmartControl( 5849): unbind internal service
,D/serial_port( 5849): close(fd = 24)
,I/UEI.SmartControl( 5849): Serial port is closed.
I/dhcpcd  ( 6417): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
I/dhcpcd  ( 6417): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 6417): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 6417): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 6417): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 6417): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
E/WifiStateMachine( 1103):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1103):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1103):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
D/dhcpcd  ( 6417): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
E/WifiStateMachine( 1103):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1103):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/dhcpcd  ( 6417): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 6417): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
E/WifiStateMachine( 1103):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1103): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
D/DhcpStateMachine( 1103): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper( 1103): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1103): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1103): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1103): Add DhcpResults: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
V/DhcpStateMachine( 1103): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1103): bShouldSendDhcpAction Result: true
E/WifiStateMachine( 1103):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine( 1103):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/DhcpStateMachine( 1103): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1103): RunningState
D/LGWifiP2pService( 1103): InactiveState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1103): P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1103): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 6133): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1103): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1103): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 6133): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1103): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1103): doBoolean: SET ps 1
D/WifiNative-wlan0( 1103): SET ps 1: returned true
D/ConnectivityService( 1103): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
E/WifiStateMachine( 1103):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1103):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1103): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1103): ignoring duplicate network state non-change
I/StatusBar.NetworkController( 1451): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1451): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1103): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1103): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1103): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
E/WifiStateMachine( 1103): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/ConnectivityService( 1103): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService( 1103): Adding iface wlan0 to network 100
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1451): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/Settings( 1103): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1103): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1103): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/WifiHS20( 1103): [PASSPOINT] passpointNotification: hs20AP list is checked
V/WfdStateTracker( 1948): handleWifiStateChangedEvent: 1
I/StatusBar.NetworkController( 1451): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1451): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1451): mWifiConnected = true, mWifiLevel = 3
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1103): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1103): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1103): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/PostponalbeReceiver( 5173): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/ConnectivityService( 1103): Unexpected mtu value: 0, wlan0
D/WifiHS20( 1103): [PASSPOINT] passpointNotification: hs20AP list is checked
D/ConnectivityService( 1103): Adding Route [fe80::/64 -> :: wlan0] to network 100
D/ConnectivityService( 1103): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
D/ConnectivityService( 1103): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
D/ConnectivityService( 1103): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1103): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 100
D/ConnectivityService( 1103): Setting Dns servers for network 100 to [/192.168.1.1]
I/StatusBar.NetworkController( 1451): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1451): mWifiConnected = true, mWifiLevel = 3
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1103): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1103): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1103): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/Nat464Xlat( 1103): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1103): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1103): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1103): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1103):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1103):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1103):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1103):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1103):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1103): currentScore = 0, newScore = 20
D/ConnectivityService( 1103):    accepting network in place of null
D/ConnectivityService( 1103): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1103): Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1103): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1103): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1103): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1103): Checking http://clients3.google.com/generate_204 on "NG700"
D/TelephonyNetworkFactory-1( 1860): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1860):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/WIFI    ( 1103): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1103):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 1103): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1103): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1103): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1103): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1103): [e] list.add(nai) empty : false size: 1
D/ConnectivityService( 1103): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService( 1103): validation of new default Network = false
D/ConnectivityService( 1103): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1103): enableDataServiceNotify 
D/DSQN    ( 1103): start dsqn bin
D/LocSvc_java( 1103): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1103): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1103): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1103): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java( 1103): Sending msg: 5 arg1:0 arg2:1
D/libc-netbsd(  313): res_queryN name = clients3.google.com, class = 1, type = 28
D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  313): res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
W/dsqn    ( 6461): type=1400 audit(0.0:163): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 6461): type=1400 audit(0.0:164): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  313): res_queryN name = europe.pool.ntp.org, class = 1, type = 1
D/ConnectivityService( 1103): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1103):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1103):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1103): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1451): CM callback handler got msg 524290
D/TelephonyIcons( 1451): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WiFiOffLoadBroadcast( 6116): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
E/DSQN    ( 6461): DSQN ssw
D/WiFiOffLoadBroadcast( 6116): MCCMNC not supported: null
D/QRemote ( 6278): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6278): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/libc-netbsd(  313): res_queryN name = 2.android.pool.ntp.org succeed
D/libc-netbsd(  313): res_queryN name = clients3.google.com, class = 1, type = 1
I/QRemote ( 6278): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 5173): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6116): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6116): MCCMNC not supported: null
D/QRemote ( 6278): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6278): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6278): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 5173): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6196): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6196): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
D/libc-netbsd(  313): res_queryN name = clients3.google.com succeed
V/WiFiOffLoadBroadcast( 6116): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
V/NetworkPolicy( 1103): [LG_RESTRICTED] checkMobilePolicy_type()
D/WiFiOffLoadBroadcast( 6116): MCCMNC not supported: null
D/LGDataListener(  313): argv[0]=dsqncommand
D/LGDataListener(  313): argv[1]=wlan0
D/LGDataListener(  313): argv[2]=1
D/LGDataListener(  313): notifyDSQN DSQN STARTMONITOR wlan0 1
D/QRemote ( 6278): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/DSQN    ( 1103): DSQM DsqnNotification wlan0  1
D/QRemote ( 6278): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/DSQN    ( 1103): start to monitor internet connection
D/QRemote ( 6278): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
D/libc-netbsd(  313): res_queryN name = europe.pool.ntp.org succeed
I/QRemote ( 6278): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6278): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 5173): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6196): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6196): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6116): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6116): MCCMNC not supported: null
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1103): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 09 Feb 2016 02:07:24 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454983645527], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454983645509]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1103): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1103): Validated
D/ConnectivityService( 1103): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1103): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1103):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1103):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1103):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1103): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService( 1103): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1103):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1103):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1103): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1103): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1451): CM callback handler got msg 524290
D/ConnectivityService( 1103): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    ( 1103): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1103):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1860): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1860):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/QRemote ( 6278): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6278): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6278): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6278): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6278): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/TelephonyIcons( 1451): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
D/LocSvc_java( 1103): NTP server : europe.pool.ntp.org
D/LocSvc_java( 1103): NTP server returned: 1454983644979 (Tue Feb 09 03:07:24 GMT+01:00 2016) reference: 116665 certainty: 27 system time offset: -586
D/LocSvc_java( 1103): Sending msg: 10 arg1:0 arg2:1
E/WifiStateMachine( 1103):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1010267732] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1103):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1010267729] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1103): doString: [SIGNAL_POLL]
D/StatusBar.NetworkController( 1451): refreshViews: Data not connected!! Set no data type icon / Roaming
D/sensors_hal_Time( 1103): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1103): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1103): tsOffsetIs: Apps: 117685885583; DSPS: 3997187; Offset : -4313875290
,V/AlarmManager( 1103): ELAPSED_WAKEUP set : Alarm{15095c7d type 2 when 117846 com.google.android.gms} when 117846
,V/QRemote ( 6278): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
D/QRemote ( 6278): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:8421
,D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  313): res_queryN name = mtalk.google.com, class = 1, type = 1
D/libc-netbsd(  313): res_queryN name = mtalk.google.com succeed
,D/GCM     ( 2117): Connected
,D/GCM     ( 2117): Message class com.google.f.a.a.p
I/ActivityManager( 1103): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RequestWriter$NetworkStateReceiver: pid=6493 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 6493): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/LgDataFeature( 6493): LgDataFeature() Constructor: none
D/LgDataFeature( 6493): LgDataFeature() Constructor Done, null
,I/Babel   ( 6493): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 6493): MmsConfig.loadMmsSettings
I/Babel   ( 6493): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
I/Babel   ( 6493): MmsConfig.loadFromDatabase
,W/Settings( 6493): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/Babel   ( 6493): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 6493): MmsConfig.loadFromResources
E/Babel   ( 6493): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 6493): MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,W/AudioCapabilities( 6493): Unsupported mime audio/evrc
,W/AudioCapabilities( 6493): Unsupported mime audio/qcelp
W/VideoCapabilities( 6493): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6493): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 6493): Unsupported mime audio/qcelp
W/AudioCapabilities( 6493): Unsupported mime audio/evrc
W/VideoCapabilities( 6493): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 6493): Unsupported mime video/divx
W/VideoCapabilities( 6493): Unsupported mime video/divx311
W/VideoCapabilities( 6493): Unsupported mime video/divx4
W/VideoCapabilities( 6493): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6493): Unsupported profile 4 for video/mp4v-es
,W/AudioCapabilities( 6493): Unsupported mime audio/eac3
W/AudioCapabilities( 6493): Unsupported mime audio/ac3
W/AudioCapabilities( 6493): Unsupported mime audio/g726
W/ResourcesManager( 6493): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/AudioCapabilities( 6493): Unsupported mime audio/wma-voice
W/ResourcesManager( 6493): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/AudioCapabilities( 6493): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6493): Unsupported mime audio/adpcm
W/VideoCapabilities( 6493): Unsupported mime video/theora
W/VideoCapabilities( 6493): Unsupported mime video/mjpg
V/JNIHelp ( 6493): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/System  ( 6493): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/system/app/Hangouts/Hangouts.apk"],nativeLibraryDirectories=[/system/app/Hangouts/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6493): Installed default security provider GmsCore_OpenSSL
,I/GLSUser ( 2117): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native
I/GLSUser ( 2117): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2117): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2117): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/Babel   ( 6493): UserRecoverableAuthException.
E/Babel   ( 6493): cfq: BadAuthentication
E/Babel   ( 6493): 	at cfn.a(Unknown Source)
E/Babel   ( 6493): 	at f.a(PG:191)
E/Babel   ( 6493): 	at ava.a(PG:88)
E/Babel   ( 6493): 	at ava.a(PG:128)
E/Babel   ( 6493): 	at bjs.a(PG:255)
E/Babel   ( 6493): 	at bep.a(PG:602)
E/Babel   ( 6493): 	at bep.a(PG:469)
E/Babel   ( 6493): 	at bpo.run(PG:1141)
E/Babel   ( 6493): Error getting auth token
E/Babel   ( 6493): bxl
E/Babel   ( 6493): 	at f.a(PG:201)
E/Babel   ( 6493): 	at ava.a(PG:88)
E/Babel   ( 6493): 	at ava.a(PG:128)
E/Babel   ( 6493): 	at bjs.a(PG:255)
E/Babel   ( 6493): 	at bep.a(PG:602)
E/Babel   ( 6493): 	at bep.a(PG:469)
E/Babel   ( 6493): 	at bpo.run(PG:1141)
I/Babel_RequestWriter( 6493): error sending REQ[fc:12; creat:1454973641906; type:bev-292670397]; took 101 ms (error code == 100)
,E/Babel   ( 6493): Account registration failedRedacted-21
E/Babel   ( 6493): bph: null -- null
E/Babel   ( 6493): 	at ava.a(PG:120)
E/Babel   ( 6493): 	at ava.a(PG:128)
E/Babel   ( 6493): 	at bjs.a(PG:255)
E/Babel   ( 6493): 	at bep.a(PG:602)
E/Babel   ( 6493): 	at bep.a(PG:469)
E/Babel   ( 6493): 	at bpo.run(PG:1141)
I/Babel   ( 6493): Account setup failed with error state:106 account:Redacted-21
I/Babel   ( 6493): Account sign in complete with state 106account: Redacted-21
I/art     ( 6493): Note: end time exceeds epoch: 
,I/GLSUser ( 2117): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native
I/GLSUser ( 2117): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2117): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2117): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 2117): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,V/NotificationService( 1103): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,D/ZenLog  ( 1103): intercepted: 0|com.google.android.gms|1|null|10005,none
V/NotificationService( 1103): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1103): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1103): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1103): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
E/Babel   ( 6493): Unexpected exception while authenticating.
E/Babel   ( 6493): cfr: User intervention required. Notification has been pushed.
E/Babel   ( 6493): 	at cfn.b(Unknown Source)
E/Babel   ( 6493): 	at cfn.a(Unknown Source)
E/Babel   ( 6493): 	at f.a(PG:188)
E/Babel   ( 6493): 	at ava.b(PG:143)
E/Babel   ( 6493): 	at bnr.run(PG:5415)
E/Babel   ( 6493): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 6493): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 6493): 	at java.lang.Thread.run(Thread.java:818)
,W/ResourcesManager( 1451): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1451): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager( 1398): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 1398): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/LgeQuickCoverNLService( 1398): onNotificationPosted
D/SmartCoverUpdateMonitor( 1398): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1398): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1398): handleNotificationPosted(true)
D/QuickCircle( 1398): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1398): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1398): post do add job
D/LgeQuickCoverNotificationData( 1398): add : 2
D/LgeQuickCoverNotificationData( 1398): do add job
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
D/QuickStatusbarLayout( 1398): child = android.widget.LinearLayout{1745ff5c V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,V/WifiInternetCheck( 1103): Single check msg out of sync, ignoring.
,D/ConnectivityService( 1103): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1103): MasterInitialState.processMessage what=3
D/AlarmManagerService( 1103): Setting time of day to sec=1454983647
,W/AlarmManagerService( 1103): Unable to set rtc to 1454983647: Invalid argument
D/GpsLocationProvider( 1103): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/LIA_Informant_Tips_DateChangeManager( 2717): onReceive() : ACTION_TIME_CHANGED
I/LIA_Informant_Tips_LogTracer( 2717): [Log Tracer - Schedule Transition] Time Change Event Received : 2016-02-09 03:07:27...... Request
I/LIA_Informant_Tips_LogTracer( 2717): [Log Tracer - Schedule Transition] UserGuide, DATE_UPDATE : working count : 6, total count : 170, new day : false...... Request
D/LIA_Informant_Tips_DateChangeManager( 2717): DateInfo : SmartTips Total Working Day Count = 170
D/LIA_Informant_Tips_DateChangeManager( 2717): DateInfo : UserGuide Working Duration Count = 6
,D/LIA_Informant_Tips_DateChangeManager( 2717): DateInfo : Last Date Check Time = 2016-02-09 03:07:27
I/SecureClockService( 1948): Intent.ACTION_TIME_CHANGED 
I/[SystemUI]Clock( 1451): onReceive = android.intent.action.TIME_SET
I/LgeClockWidgetControlView( 1451): time changed, timezoneChanged : false
D/PostponalbeReceiver( 5173): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
,I/CalendarProvider2( 4577): onReceive() android.intent.action.TIME_SET
D/CalendarProvider2( 4577): Scheduling check of next Alarm
W/ContextImpl( 5173): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
W/ActivityManager( 1103): getTasks: caller 10029 is using old GET_TASKS but privileged; allowing
I/[LGHome]LGDateChangeReceiver( 2067): [LGDateChangeReceiver.java:78:updateCalendarShortcut()]date=9 currentDate=-1 dayofweek=3 currentDayOfWeek=-1
,I/NetworkMonitor( 5221): type=WIFI subType= reason=null isConnected=true
,I/[LGHome]LGCalendarIcon( 2067): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Tue date= 9
I/[LGHome]LGCalendarIcon( 2067): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Tue date= 9
I/[LGHome]Launcher( 2067): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/ActivityManager( 1103): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6556 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/[Concierge]Service( 2614): onStartCommand(). Type : 9
,I/GoogleURLConnFactory( 2117): Using platform SSLCertificateSocketFactory
,I/ActivityManager( 1103): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=6575 uid=10054 gids={50054, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/WifiStateMachine( 1103):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-50 f=2412 sc=60 link=72 tx=6.2, 0.0, 0.0  rx=5.5 bcn=0 [on:0 tx:0 rx:0 period:2407] from screen [on:0 period:-1010265315] gl rssi=-50 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1103):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-50 f=2412 sc=60 link=72 tx=6.2, 0.0, 0.0  rx=5.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1010265314] gl rssi=-50 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1103): doString: [SIGNAL_POLL]
I/art     (  359): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 348us total 19.144ms
,I/art     (  359): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 272us total 12.751ms
,I/art     (  359): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 249us total 12.220ms
I/ActivityManager( 1103): Start proc com.android.gallery3d for service com.android.gallery3d/com.lge.gallery.picasa.PicasaService: pid=6595 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/AppUp4:AppBoxCP( 6556): onCreate
W/AppUp4:DB( 6556):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 6556):  setFingerPrint start
I/AppUp4:DB( 6556):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 6556):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 6556):  SDK version = 21
I/AppUp4:DB( 6556):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6556): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6556): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6556): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6556): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6556): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6556): onReceive
,W/ResourcesManager( 6595): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6595): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6595): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 6595): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
D/LgDataFeature( 6556): LgDataFeature() Constructor: none
D/LgDataFeature( 6556): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 6556): Context : android.app.ReceiverRestrictedContext@2110dd34
D/AppUp4:CustFacade( 6556): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6556): isPhone : true
D/AppUp4:CustModeStarterReceiver( 6556): begin check event
I/AppUp4:CustModeStarterReceiver( 6556): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6556): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
I/AppConfig( 6595): Total System Memory = 2995761152
,D/SystemHelper( 6595): region [EU], country [EU], operator [OPEN], sub-operator []
D/AppUp4:CustModeStarterReceiver( 6556): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6556): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6556): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1103): Killing 5532:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,D/LGDMClient( 3956): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3956): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/libprocessgroup( 1103): failed to open /acct/uid_10097/pid_5532/cgroup.procs: No such file or directory
,W/ContextImpl( 3956): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
I/ActivityManager( 1103): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=6618 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/GpsLocationProvider( 1103): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ReaderUtils( 6575): PortraitW 1440 LandscapeW 2392 SmallestSize 1340 LargestSize 2392 textZoom 4.4999995 isTablet false Memory 256
W/ContextImpl( 3956): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,V/DownloadManager( 3248): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 3956): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/LGDMClient( 3956): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3956): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/LGDMClient( 3956): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,V/DownloadManager( 3248): DownloadService onCreate
,I/art     ( 2117): Explicit concurrent mark sweep GC freed 31253(1871KB) AllocSpace objects, 7(496KB) LOS objects, 51% free, 30MB/62MB, paused 1.234ms total 50.429ms
I/ActivityManager( 1103): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6647 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/VacuumService( 2117): Vacuum at: now=1454983648555 tag=VacuumService
W/ContextImpl( 3956): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
,E/LGDMClient( 3956): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 3956): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 3956): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
E/GpsLocationProvider( 1103): No APN found to select.
,I/DownloadManager( 3248): in removeSpuriousFiles
V/DownloadManager( 3248): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3248): DownloadService onStartCommand
V/DownloadManager( 3248): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3248): created cursor android.database.sqlite.SQLiteCursor@69ce700 on behalf of 3248
I/DownloadManager( 3248): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3248): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3248): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3248): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3248): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3248): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3248): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3248): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3248): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3248): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3248): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
W/GAV2    ( 6575): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/DownloadManager( 3248): in trimDatabase
V/DownloadManager( 3248): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3248): created cursor android.database.sqlite.SQLiteCursor@9308b39 on behalf of 3248
,V/DownloadManager( 3248): created cursor android.database.sqlite.SQLiteCursor@1b2cd57e on behalf of 3248
V/DownloadManager( 3248): processing inserted download 1
V/DownloadManager( 3248): processing inserted download 4
V/DownloadManager( 3248): processing inserted download 7
V/DownloadManager( 3248): processing inserted download 8
I/BooksApp( 6575): Created application version: 3.2.35 (30235)
V/DownloadManager( 3248): processing inserted download 9
V/DownloadManager( 3248): processing inserted download 10
V/DownloadManager( 3248): processing inserted download 16
,V/DownloadManager( 3248): processing inserted download 17
V/DownloadManager( 3248): processing inserted download 18
V/DownloadManager( 3248): processing inserted download 21
V/DownloadManager( 3248): processing inserted download 22
I/jxcore-log( 6035): Test app app.js loaded
I/jxcore-log( 6035): 
W/ResourcesManager( 6647): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6647): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6647): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6647): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/chromium( 6035): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6035): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6035): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6035): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6035): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6035): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6035): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6035): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6035): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6035): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6035): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3736b8fd added. We now have 1 listener(s)
I/jxcore-log( 6035): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 6035): 
W/DriveInitializer( 2349): Background init thread started
,V/DownloadManager( 3248): DownloadService onDestroy
I/ActivityManager( 1103): Killing 5823:com.lge.eula/1000 (adj 15): empty #17
E/VoldCmdListener(  281): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  281): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.gms/files/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 2349): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.gms/files
W/libprocessgroup( 1103): failed to open /acct/uid_1000/pid_5823/cgroup.procs: No such file or directory
,I/LGEmail ( 6647): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
I/art     ( 1103): Explicit concurrent mark sweep GC freed 60064(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 44MB/66MB, paused 1.344ms total 75.925ms
D/LGEmail ( 6647): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DelayedSyncController( 6618): Delaying sync.
I/BooksSync( 6575): Starting books sync
W/DriveInitializer( 2349): Background init thread ended
I/ActivityManager( 1103): Killing 5328:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
,W/ResourceType( 6647): No package identifier when getting value for resource number 0x00000000
,E/Auth.Api.Credentials( 2349): [CredentialSyncAdapter] Unknown sync event.
W/libprocessgroup( 1103): failed to open /acct/uid_10005/pid_5328/cgroup.procs: No such file or directory
,I/GLSUser ( 2117): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/ads_measurement
I/GLSUser ( 2117): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/ads_measurement without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2117): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2117): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/Ads     ( 2349): [JAMS] Failed to get OAuth token: com.google.android.gms.auth.ad: BadAuthentication
D/LgDataFeature( 6647): LgDataFeature() Constructor: none
D/LgDataFeature( 6647): LgDataFeature() Constructor Done, null
,I/GoogleURLConnFactory( 2117): Using platform SSLCertificateSocketFactory
,W/Uploader( 2117): No account for auth token provided
D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  313): res_queryN name = play.googleapis.com, class = 1, type = 1
,D/libc-netbsd(  313): res_queryN name = play.googleapis.com succeed
,D/eas_req ( 6647): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  313): res_queryN name = www.google.com, class = 1, type = 1
,D/BooksSync( 6575): started syncMyEbooks
I/LgeMiscReceiver( 3196): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3196): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3196): networkInfo.isConnected() = true
D/PhoneState( 3196): setPdpRejectCasuse : false
,I/HubEmail( 6647): JNI_OnLoad()
I/HubEmail( 6647): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6647): registerNatives()
I/HubEmail( 6647): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6647): registerNativeMethods()
I/HubEmail( 6647): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6647): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
D/libc-netbsd(  313): res_queryN name = www.google.com succeed
,D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  313): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  313): res_queryN name = clients3.google.com succeed
I/ActivityManager( 1103): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6717 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,W/Settings( 6647): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  313): res_queryN name = static-avc.lglime.com, class = 1, type = 1
W/Settings( 6647): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/WifiInternetCheck( 1103): isHttpConnectionAvailable - We got a valid response : 204
D/DrmBroadcastReceiver( 6717): Receive CONNECTIVITY_ACTION
,D/DrmBroadcastReceiver( 6717): 1  network is available. Sync DRM Time with NTP
,V/DrmService( 6717): Service onCreate
D/DrmService( 6717): Received new request = 2
I/DrmSntpClient( 6717): Start Sync process
D/DrmSntpClient( 6717): Server : 0
,D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  313): res_queryN name = pool.ntp.org, class = 1, type = 1
I/ActivityManager( 1103): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=6738 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/libc-netbsd(  313): res_queryN name = static-avc.lglime.com succeed
,I/GLSUser ( 2117): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2117): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2117): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2117): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/libc-netbsd(  313): res_queryN name = pool.ntp.org succeed
V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 6738): Almond Protected OAT
,W/Uploader( 2117): No account for auth token provided
V/NotificationService( 1103): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1103): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1103): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1103): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1103): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,D/DelayedSyncController( 6618): Delaying sync.
W/GLSActivity( 2117): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2117): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2117): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2117): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2117): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2117): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2117): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6575): Authentication error
E/BooksAccountManager( 6575): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6575): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6575): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6575): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6575): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6575): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6575): null auth token
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
I/LGDrmClient( 6717): _DRM_ServiceGet() : Bind lgdrm service
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
V/ILGDrmService(  334): eDRM_SetDRMTime +++
I/LGDRM   (  334): [DRM] SET TIME : YR=2016, MON=2, DAY=9
I/LGDRM   (  334): [DRM] SET TIME : HR=2, MIN=7, SEC=29
E/LgeQuickCoverOverlayWindow( 1398): updateNotificationData: count=3
D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  313): res_queryN name = www.googleapis.com, class = 1, type = 1
,V/ILGDrmService(  334): eDRM_SetDRMTime ---
I/DrmSntpClient( 6717): Synched
V/FormManager( 6153): There are no updated forms. The schedule will be deleted.
D/DrmService( 6717): Completed !! request = 2
D/DrmService( 6717): Request count = 0
,V/DrmService( 6717): Service onDestroy
V/FormManager( 6153): Alarm would be updated, because LastCheckTime has been updated.
I/ActivityManager( 1103): Killing 5906:com.android.calendar/u0a13 (adj 15): empty #17
D/QuickStatusbarLayout( 1398): Notification difference=198
D/QuickStatusbarLayout( 1398): child = android.widget.LinearLayout{1745ff5c V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  313): res_queryN name = www.googleapis.com succeed
,W/libprocessgroup( 1103): failed to open /acct/uid_10013/pid_5906/cgroup.procs: No such file or directory
D/WeatherApplication( 6738): removeAccount
,D/WeatherApplication( 6738): Account.length = 0
E/WeatherApplication( 6738): OPERATOR:OPEN
W/Uploader( 2117): No account for auth token provided
D/WeatherAncestor( 6738): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 3:7:29
D/Weather.Utils( 6738): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6738): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6738): 2 : This is isUpdating : false
,D/WeatherAncestor( 6738): connectivity changed - connection : true
D/WeatherService( 6738): 2 : isServiceAlived():false forecastCache:null
I/ActivityManager( 1103): Killing 4577:com.android.providers.calendar/u0a14 (adj 15): empty #17
D/ForecastDataCache( 6738): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 6738): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 6738): 2 : Cache is not up-to-date, count: 0
,D/Weather_cast( 6738): 2 : isUpdateNeedForAlarm : no city return false
,D/WeatherAncestor( 6738): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 3:7:29
I/ActivityManager( 1103): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6762 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1103): Killing 2189:com.lge.music/u0a34 (adj 15): empty #17
,V/AudioFlinger(  319): 2189 died, releasing its sessions
,V/AudioFlinger(  319):  pid 1860 @ 0
V/AudioFlinger(  319):  pid 3196 @ 1
V/AudioFlinger(  319):  pid 3196 @ 2
W/ApiaryClient( 6575): Error response from books API: {
W/ApiaryClient( 6575):  "error": {
W/ApiaryClient( 6575):   "errors": [
W/ApiaryClient( 6575):    {
W/ApiaryClient( 6575):     "domain": "global",
W/ApiaryClient( 6575):     "reason": "required",
W/ApiaryClient( 6575):     "message": "Login Required",
W/ApiaryClient( 6575):     "locationType": "header",
W/ApiaryClient( 6575):     "location": "Authorization"
W/ApiaryClient( 6575):    }
W/ApiaryClient( 6575):   ],
W/ApiaryClient( 6575):   "code": 401,
W/ApiaryClient( 6575):   "message": "Login Required"
W/ApiaryClient( 6575):  }
W/ApiaryClient( 6575): }
,W/ApiaryClient( 6575): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6575): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7155466055136103915&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6575): Headers:
W/ApiaryClient( 6575): accept-encoding: [gzip]
W/ApiaryClient( 6575): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6575): gdata-version: 2
W/libprocessgroup( 1103): failed to open /acct/uid_10014/pid_4577/cgroup.procs: No such file or directory
,W/libprocessgroup( 1103): failed to open /acct/uid_10034/pid_2189/cgroup.procs: No such file or directory
,W/Uploader( 2117):  no longer exists, so no auth token.
,W/Uploader( 2117): No account for auth token provided
V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/VoldCmdListener(  281): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  281): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6762): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,I/GLSUser ( 2117): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
,I/GLSUser ( 2117): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2117): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2117): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
E/VoldCmdListener(  281): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  281): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6762): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/VoldCmdListener(  281): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  281): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6762): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  281): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  281): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6762): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,W/Uploader( 2117): No account for auth token provided
V/NotificationService( 1103): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1103): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1103): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1103): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
,D/NotificationServiceEx( 1103): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1398): onNotificationPosted
W/GLSActivity( 2117): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2117): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2117): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2117): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2117): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2117): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2117): 	at android.os.Binder.execTransact(Binder.java:446)
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
D/ContactsSyncAdapter( 2117): innerSync failed
D/ContactsSyncAdapter( 2117): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2117): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2117): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2117): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2117): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2117): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2117): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2117): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2117): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2117): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2117): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2117): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1398): updateNotificationData: count=3
D/SyncManager( 1103): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 26463, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager( 1103): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 153662, reason: 10019
D/QuickStatusbarLayout( 1398): Notification difference=198
D/QuickStatusbarLayout( 1398): child = android.widget.LinearLayout{1745ff5c V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/ActivityManager( 1103): Start proc com.google.android.apps.plus for service com.google.android.apps.plus/.service.EsSyncAdapterService: pid=6787 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 6787): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/art     ( 2117): Explicit concurrent mark sweep GC freed 25767(1389KB) AllocSpace objects, 8(919KB) LOS objects, 50% free, 30MB/62MB, paused 1.192ms total 51.341ms
I/WebViewFactory( 6762): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 6762): Loading: webviewchromium
I/LibraryLoader( 6762): Time to load native libraries: 4 ms (timestamps 1597-1601)
,I/LibraryLoader( 6762): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6762): Binding Chromium to main looper Looper (main, tid 1) {22b7ef}
I/LibraryLoader( 6762): Expected native library version number "",actual native library version number ""
I/chromium( 6762): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6762): Initializing chromium process, renderers=0
,W/art     ( 6762): Attempt to remove local handle scope entry from IRT, ignoring
V/AudioPolicyService(  319): registerClient() client 0xb100df80, uid 10093
,W/AudioManagerAndroid( 6762): Requires BLUETOOTH permission
W/chromium( 6762): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6762): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 6762): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
I/Adreno-EGL( 6762): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6762): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6762): Build Date: 12/12/14 금
I/Adreno-EGL( 6762): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6762): Remote Branch: 
I/Adreno-EGL( 6762): Local Patches: 
I/Adreno-EGL( 6762): Reconstruct Branch: 
,I/GLSActivity( 2117): [ac] getting account id
I/GLSUser ( 2117): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
,I/art     ( 1103): Explicit concurrent mark sweep GC freed 33140(1486KB) AllocSpace objects, 5(336KB) LOS objects, 33% free, 44MB/66MB, paused 1.743ms total 81.796ms
,I/NSApplication( 6762): Starting up...
,I/ActivityManager( 1103): Killing 5879:com.lge.bnr/1000 (adj 15): empty #17
,W/libprocessgroup( 1103): failed to open /acct/uid_1000/pid_5879/cgroup.procs: No such file or directory
,I/iu.SyncManager( 2349): SYNC; picasa accounts
,D/ConnectivityService( 1103): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1103): ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1103): DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1103): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1103): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1103): Checking http://clients3.google.com/generate_204 on "NG700"
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1103): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 09 Feb 2016 02:07:30 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454983650165], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454983650148]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1103): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1103): Validated
D/ConnectivityService( 1103): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1103): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1103):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1103):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1103):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1103): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService( 1103): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1103):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1103):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1103): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1451): CM callback handler got msg 524290
,D/NetworkLogImpl( 2349): Loaded NetworkSpeedPredictor
I/iu.Environment( 2349): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 2349): num queued entries: 0
I/iu.UploadsManager( 2349): num updated entries: 0
I/iu.SyncManager( 2349): NEXT; no task
D/ChimeraCfgMgr( 2349): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 2349): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PostponalbeReceiver( 5173): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.TIME_SET'.
,I/ActivityManager( 1103): Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=6859 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
I/GLSUser ( 2117): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 2117): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2117): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2117): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1103): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1103): pkg=com.google.android.gms canInterrupt=false intercept=true
,I/NotificationServiceEx( 1103): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1103): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1103): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1398): onNotificationPosted
W/Kids    ( 2349): [AccountUtils] Account not ready
W/Kids    ( 2349): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2349): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2349): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2349): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2349): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2349): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2349): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2349): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2349): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2349): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2349): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2349): 	at java.lang.Thread.run(Thread.java:818)
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
,D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1398): updateNotificationData: count=3
I/[SystemUI]LGPowerUI( 1451): onReceive = com.lge.android.intent.action.BATTERYEX
,I/[SystemUI]LGPowerUI( 1451): On Skip Timer : true
D/QuickStatusbarLayout( 1398): Notification difference=198
D/QuickStatusbarLayout( 1398): child = android.widget.LinearLayout{1745ff5c V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/KeyguardUpdateMonitor( 1451): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 292
I/[SystemUI]LGPowerUI( 1451): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1451): onReceive = android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1948): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1948): Battery Level Remaining: 100%
D/LEDHandler( 1948): Battery Temp: 292, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 6090): Disconnected process message: 10, size: 0
D/LGDMClient( 3956): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/WifiController( 1103): battery changed pluggedType: 2
W/Settings( 1103): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1103): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 3956): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
I/GLSUser ( 2117): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2117): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2117): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2117): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ALBootInit( 6859): ====action==>android.intent.action.TIME_SET
,V/NotificationService( 1103): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/ALBootInit( 6859): Alarm ALBootInit: TIME_SET
V/NotificationService( 1103): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1103): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1103): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1103): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2117): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2117): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2117): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2117): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2117): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2117): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2117): 	at android.os.Binder.execTransact(Binder.java:446)
D/Alarms  ( 6859): [setNextAlert] start
D/LgeQuickCoverNLService( 1398): onNotificationPosted
,E/BooksAccountManager( 6575): Authentication error
E/BooksAccountManager( 6575): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6575): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6575): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6575): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6575): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6575): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6575): null auth token
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
D/Alarms  ( 6859): [setNextAlert] (1)
,D/Alarms  ( 6859):  minTime  = 0
,D/Alarms  ( 6859):  -- OK multi -- 0
E/jeny.kim( 6859): [setNextAlert] setNextAlert  temp_Alarmlink + 
E/jeny.kim( 6859): [setNextAlert]setNextAlert temp_AlarmLinkText + 
D/QuickStatusbarLayout( 1398): Notification difference=198
D/QuickStatusbarLayout( 1398): child = android.widget.LinearLayout{1745ff5c V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/CommonUtil( 6859): BUILD Country: EU
,D/Alarms  ( 6859): broadcastToWidgetProvider : false
D/Alarms  ( 6859): Enter formatDayAndTime(final Context context, long timeInMiliSec)
V/SettingsProvider( 1103): call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
W/ApiaryClient( 6575): Error response from books API: {
W/ApiaryClient( 6575):  "error": {
W/ApiaryClient( 6575):   "errors": [
W/ApiaryClient( 6575):    {
W/ApiaryClient( 6575):     "domain": "global",
W/ApiaryClient( 6575):     "reason": "required",
W/ApiaryClient( 6575):     "message": "Login Required",
W/ApiaryClient( 6575):     "locationType": "header",
W/ApiaryClient( 6575):     "location": "Authorization"
W/ApiaryClient( 6575):    }
W/ApiaryClient( 6575):   ],
W/ApiaryClient( 6575):   "code": 401,
W/ApiaryClient( 6575):   "message": "Login Required"
W/ApiaryClient( 6575):  }
W/ApiaryClient( 6575): }
,W/ApiaryClient( 6575): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6575): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7155466055136103915&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6575): Headers:
W/ApiaryClient( 6575): accept-encoding: [gzip]
W/ApiaryClient( 6575): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6575): gdata-version: 2
,I/DigitalAppWidgetProvider( 6859): onReceive: android.intent.action.TIME_SET
V/DigitalAppWidgetProvider( 6859): cancelAlarmOnQuarterHour android.app.ReceiverRestrictedContext@1cc375d
V/DigitalAppWidgetProvider( 6859): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@1cc375d
,D/QuickCoverProvider( 6859): onReceiver
I/indal   ( 1398): SmartCoverWidgetContext createApplicationContext
I/indal   ( 1398): SmartCoverWidgetContext createApplicationContext
,D/WeatherAncestor( 6738): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 3:7:30
,D/Weather.Utils( 6738): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6738): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6738): 2 : This is isUpdating : false
D/WeatherService( 6738): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2bc018d2
D/ForecastDataCache( 6738): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 6738): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 6738): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 6738): 2 : set auto-update time : 2/9 6:7
,D/WeatherAncestor( 6738): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 3:7:30
,I/ActivityManager( 1103): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=6881 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
I/ActivityManager( 1103): Killing 4885:com.android.vending/u0a44 (adj 15): empty #17
,W/libprocessgroup( 1103): failed to open /acct/uid_10044/pid_4885/cgroup.procs: No such file or directory
,D/TimeService( 6881): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1454983650821
D/        ( 6881): TimeServiceNative: User Time to be set is 1454983650822
D/QC-time-services( 6881): Lib:time_genoff_operation: pargs->base = 2
,D/QC-time-services( 6881): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 6881): Lib:time_genoff_operation: pargs->ts_val = 1454983650822
,D/QC-time-services( 6881): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  427): Daemon: Connection accepted:time_genoff
D/QC-time-services(  427): Daemon:Received base = 2, unit = 1, operation = 0,value = 1454983650822
D/QC-time-services(  427): Daemon:genoff_opr: Base = 2, val = 1454983650822, operation = 0
D/QC-time-services(  427): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS5/18/70 19:19:33
D/QC-time-services(  427): Daemon:Value read from RTC seconds = 14584773000
D/QC-time-services(  427): Daemon:new time 1454983650822 
D/QC-time-services(  427): Daemon: delta 1440398877822 genoff 1440398877822 
D/QC-time-services(  427): Daemon:genoff_persistent_update: Writing genoff = 1440398877822 to memory
D/QC-time-services(  427): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  427): Daemon:time_persistent_memory_opr:Genoff write operation 
D/QC-time-services(  427): Updating the TOD offset
D/QC-time-services(  427): Daemon:genoff_persistent_update: Writing genoff = 1440398877822 to memory
D/QC-time-services(  427): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  427): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services(  427): Daemon:Update to modem bit set
D/QC-time-services(  427): Daemon:genoff_send_modem: Sending data to MODEM !
,D/QC-time-services(  427): Daemon: Base = 2, Value being sent to MODEM = 1124434077822
E/QC-time-services( 6881): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
E/QC-time-services(  427): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
E/QC-time-services(  427): Daemon: Time-services: Waiting to acceptconnection
I/ActivityManager( 1103): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetProvider: pid=6899 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi
I/ActivityManager( 1103): Killing 6172:com.lge.lifetracker/u0a37 (adj 15): empty #17
,W/libprocessgroup( 1103): failed to open /acct/uid_10037/pid_6172/cgroup.procs: No such file or directory
,W/ResourcesManager( 6899): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,E/WifiStateMachine( 1103):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=8.1, 0.0, 0.0  rx=7.2 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1010262298] gl rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1103):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=8.1, 0.0, 0.0  rx=7.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1010262295] gl rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1103): doString: [SIGNAL_POLL]
D/CalendarApplication( 6899): CalendarApplication.onCreate()
,D/PreferenceKeysParser( 6899): [debug_displayParseInfos] preference keys.size() = 44
,D/PreferenceKeysParser( 6899): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@28344088, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@3b191a21, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@262c5e46, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@35c1a807, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@2110dd34, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@1cc375d, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@2bc018d2, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@2cc6bda3, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@2d7898a0, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@699ec59, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@1b62f01e, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@237d90ff, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@2de9ecc, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@2af3f515, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@1c9f02a, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@34a43e1b, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@18bcdbb8, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@3babcd91, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@feee4f6, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@1ebea0f7, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@223ffb64, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@272eb1cd, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@3a9c5a82, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@1ab25593, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@36b369d0, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@1b819dc9, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@6b99cce, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@22b7ef, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@14ad52fc, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@7fd4d85, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@e56b7da, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@138ce40b, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@2bfaa2e8, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@3eca3d01, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@a7877a6, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@1a23b5e7, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@1a4b0594, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@321ca83d, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@2da46832, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@f6bc983, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@69ce700, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@9308b39, lg
,D/GeneralPreferenceUtils( 6899): [migratePrefrenceKeys] Exit: Version(44001600) >= 42001300
,D/Config  ( 6899): [init]
,I/Config  ( 6899): LGCalendar ver.4.40.16
I/Config  ( 6899): start check model
,I/Config  ( 6899): start check native_ca
I/Config  ( 6899): Config Operator=OPEN, Country=EU
D/Config  ( 6899): [setDefaultValuesToPref]
D/Config  ( 6899): [parseProfiles]
,D/ProfilesParser( 6899): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6899): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6899): [updateProfiletoCountryInfo]
D/GeneralPreference( 6899): [checkAndMigrateOldPreference]
E/AgendaWidgetManager( 6899): [updateWidgets] 
,I/InitNotificationRingtoneService( 6899): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 6899): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/41
,I/AlertUtils( 6899): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 6899): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arpeggio.ogg
I/AlertUtils( 6899): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
,I/AlertUtils( 6899): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 6899): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 6899): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
,I/AlertUtils( 6899): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 6899): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
,I/AlertUtils( 6899): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 6899): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
,I/AlertUtils( 6899): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Afternoon_Walk.ogg
I/AlertUtils( 6899): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 6899): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
,I/AlertUtils( 6899): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
,I/art     ( 3248): Explicit concurrent mark sweep GC freed 4651(284KB) AllocSpace objects, 0(0B) LOS objects, 36% free, 27MB/43MB, paused 581us total 35.262ms
,I/AlertUtils( 6899): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 6899): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6899): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/41
,I/AlertUtils( 6899): set default noti to content://media/internal/audio/media/41
I/InitNotificationRingtoneService( 6899): End InitializeAlertRingtoneService.onHandleIntent
,D/MonthWidgetProvider( 6899): [onReceive]
D/CalendarWidgetProvider( 6899): [onReceive]
D/CalendarWidgetProvider( 6899): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.MonthWidgetProvider }
W/HolidayIntentService( 6899): onHandleIntent
,D/HolidayDataLoader( 6899): readJsonAsset : holiday.json
D/CalendarTypeController( 6899): [onUpdateAndInitCalendarTime]
D/WeekWidgetProvider( 6899): [onReceive]
D/CalendarWidgetProvider( 6899): [onReceive]
D/CalendarWidgetProvider( 6899): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 6899): [onUpdateAndInitCalendarTime]
,E/HolidayIntentService( 6899): onHandleIntent:holiday data empty
,I/ActivityManager( 1103): Killing 6247:com.lge.settings.easy/1000 (adj 15): empty #17
I/art     ( 2349): Explicit concurrent mark sweep GC freed 17072(1282KB) AllocSpace objects, 22(352KB) LOS objects, 49% free, 32MB/64MB, paused 1.878ms total 91.095ms
,W/libprocessgroup( 1103): failed to open /acct/uid_1000/pid_6247/cgroup.procs: No such file or directory
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/DigitalAppWidgetProvider( 6859): onReceive: android.intent.action.ALARM_CHANGED
,D/WeatherAncestor( 6738): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 3:7:31
,D/Weather.Utils( 6738): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6738): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6738): 2 : This is isUpdating : false
D/Weather_cast( 6738): 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
D/WeatherAncestor( 6738): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 3:7:31
I/GLSUser ( 2117): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2117): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2117): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2117): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1103): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1103): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1103): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1103): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1103): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2117): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2117): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2117): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2117): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2117): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2117): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2117): 	at android.os.Binder.execTransact(Binder.java:446)
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
,D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  1
,D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
E/BooksAccountManager( 6575): Authentication error
E/BooksAccountManager( 6575): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6575): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6575): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6575): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6575): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6575): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1398): updateNotificationData: count=3
E/HttpHelper( 6575): null auth token
D/QuickStatusbarLayout( 1398): Notification difference=198
D/QuickStatusbarLayout( 1398): child = android.widget.LinearLayout{1745ff5c V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6575): Error response from books API: {
W/ApiaryClient( 6575):  "error": {
W/ApiaryClient( 6575):   "errors": [
W/ApiaryClient( 6575):    {
W/ApiaryClient( 6575):     "domain": "global",
W/ApiaryClient( 6575):     "reason": "required",
W/ApiaryClient( 6575):     "message": "Login Required",
W/ApiaryClient( 6575):     "locationType": "header",
W/ApiaryClient( 6575):     "location": "Authorization"
W/ApiaryClient( 6575):    }
W/ApiaryClient( 6575):   ],
W/ApiaryClient( 6575):   "code": 401,
W/ApiaryClient( 6575):   "message": "Login Required"
W/ApiaryClient( 6575):  }
W/ApiaryClient( 6575): }
W/ApiaryClient( 6575): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6575): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7155466055136103915&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6575): Headers:
W/ApiaryClient( 6575): accept-encoding: [gzip]
W/ApiaryClient( 6575): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6575): gdata-version: 2
,I/ActivityManager( 1103): Killing 6196:com.lge.sync/1000 (adj 15): empty #17
,W/libprocessgroup( 1103): failed to open /acct/uid_1000/pid_6196/cgroup.procs: No such file or directory
,E/BooksSync( 6575): Soft error: 
E/BooksSync( 6575): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6575): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7155466055136103915&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6575): Headers:
E/BooksSync( 6575): accept-encoding: [gzip]
E/BooksSync( 6575): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6575): gdata-version: 2
E/BooksSync( 6575): 
E/BooksSync( 6575): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6575): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6575): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6575): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6575): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6575): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6575): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6575): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6575): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6575): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6575): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6575): {
E/BooksSync( 6575):  "error": {
E/BooksSync( 6575):   "errors": [
E/BooksSync( 6575):    {
E/BooksSync( 6575):     "domain": "global",
E/BooksSync( 6575):     "reason": "required",
E/BooksSync( 6575):     "message": "Login Required",
E/BooksSync( 6575):     "locationType": "header",
E/BooksSync( 6575):     "location": "Authorization"
E/BooksSync( 6575):    }
E/BooksSync( 6575):   ],
E/BooksSync( 6575):   "code": 401,
E/BooksSync( 6575):   "message": "Login Required"
E/BooksSync( 6575):  }
E/BooksSync( 6575): }
E/BooksSync( 6575): 
E/BooksSync( 6575): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6575): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6575): 	... 8 more
,E/BooksSync( 6575): Sync error
E/BooksSync( 6575): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6575): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7155466055136103915&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6575): Headers:
E/BooksSync( 6575): accept-encoding: [gzip]
E/BooksSync( 6575): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6575): gdata-version: 2
E/BooksSync( 6575): 
E/BooksSync( 6575): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6575): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6575): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6575): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6575): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6575): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6575): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6575): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6575): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6575): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6575): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6575): {
E/BooksSync( 6575):  "error": {
E/BooksSync( 6575):   "errors": [
E/BooksSync( 6575):    {
E/BooksSync( 6575):     "domain": "global",
E/BooksSync( 6575):     "reason": "required",
E/BooksSync( 6575):     "message": "Login Required",
E/BooksSync( 6575):     "locationType": "header",
E/BooksSync( 6575):     "location": "Authorization"
E/BooksSync( 6575):    }
E/BooksSync( 6575):   ],
E/BooksSync( 6575):   "code": 401,
E/BooksSync( 6575):   "message": "Login Required"
E/BooksSync( 6575):  }
E/BooksSync( 6575): }
E/BooksSync( 6575): 
E/BooksSync( 6575): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6575): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6575): 	... 8 more
I/BooksSync( 6575): Finished books sync
I/ActivityManager( 1103): Killing 5849:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,D/SyncManager( 1103): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 26419, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/QRemote ( 6278): [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
W/System.err( 6278): android.os.DeadObjectException
W/System.err( 6278): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6278): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6278): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 6278): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
W/System.err( 6278): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 6278): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 6278): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6278): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6278): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6278): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 6278): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6278): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6278): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 6278): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 6278): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 6278): android.os.DeadObjectException
W/System.err( 6278): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6278): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6278): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 6278): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
W/System.err( 6278): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 6278): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 6278): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6278): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6278): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6278): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 6278): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6278): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6278): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 6278): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 6278): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
,I/QRemote ( 6278): [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
W/libprocessgroup( 1103): failed to open /acct/uid_1000/pid_5849/cgroup.procs: No such file or directory
W/ActivityManager( 1103): Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,D/QRemote ( 6278): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
I/QRemote ( 6278): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,I/ActivityManager( 1103): Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6942 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,V/AlarmManager( 1103): ELAPSED_WAKEUP set : Alarm{183165ed type 2 when 124625 com.android.providers.calendar} when 124625
I/art     (  359): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 390us total 31.254ms
D/QRemote ( 6278): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,I/art     (  359): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 298us total 13.887ms
,I/art     (  359): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 284us total 13.644ms
,I/ActivityManager( 1103): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=6975 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi
,D/UEI.SmartControl( 6942): Quickset Services start...
,I/UEI.SmartControl( 6942): Manufacture = LGE
D/UEI.SmartControl( 6942): Id = LGNevo
D/UEI.SmartControl( 6942): File observer start...
E/UEI.SmartControl( 6942): IR Port is disabled: false
D/UEI.SmartControl( 6942): Starting file observer...
D/UEI.SmartControl( 6942): Extracting JNI libs...
D/UEI.SmartControl( 6942): --- this system supports 32-bit or 64-bit only
W/ResourcesManager( 6975): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarProvider2( 6975): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@236b747a
,D/UEI.SmartControl( 6942): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 6942): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6942): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/art     ( 1103): Explicit concurrent mark sweep GC freed 25244(1162KB) AllocSpace objects, 7(496KB) LOS objects, 33% free, 44MB/66MB, paused 1.358ms total 93.260ms
,D/CalendarProvider2( 6975): [getOrCreateCalendarAlarmManager]
I/CalendarProvider2( 6975): Created com.android.providers.calendar.CalendarAlarmManager@35c1a807(com.android.providers.calendar.CalendarProvider2@236b747a)
D/CalendarProviderBroadcastReceiver( 6975): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 6975): [IntentService] WakeLock acquire, start IntentSerivce
D/CalendarProvider2( 6975): CalendarProviderIntentService.onCreate()
,D/CalendarProvider2( 6975): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 6975): [getOrCreateCalendarAlarmManager]
I/UEI.SmartControl( 6942): --- Selecting new region: 6
I/UEI.SmartControl( 6942): Model = LG-D855
D/UEI.SmartControl( 6942): QS Service created
E/SQLiteLog( 6975): (284) automatic index on view_events(_id)
V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/UEI.SmartControl( 6942): Service initServices...
D/UEI.SmartControl( 6942): QS start get config
,D/CalendarProvider2( 6975): [IntentService] Release Lock
D/CalendarProvider2( 6975): CalendarProviderIntentService.onDestroy()
,I/ActivityManager( 1103): Killing 6116:com.android.settings/1000 (adj 15): empty #17
,I/GLSUser ( 2117): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 2117): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2117): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2117): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/WifiService( 1103): Client connection lost with reason: 4
,D/UEI.SmartControl( 6942): Loading JNI Libs...
,W/libprocessgroup( 1103): failed to open /acct/uid_1000/pid_6116/cgroup.procs: No such file or directory
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1103): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1103): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1103): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1103): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1103): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2117): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2117): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2117): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2117): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2117): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2117): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2117): 	at android.os.Binder.execTransact(Binder.java:446)
,D/ContactsSyncAdapter( 2117): innerSync failed
D/ContactsSyncAdapter( 2117): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2117): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2117): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2117): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2117): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2117): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2117): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2117): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2117): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2117): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2117): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2117): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1398): onNotificationPosted
D/SyncManager( 1103): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 153662, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
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
,D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1398): updateNotificationData: count=3
,D/QuickStatusbarLayout( 1398): Notification difference=198
,D/QuickStatusbarLayout( 1398): child = android.widget.LinearLayout{1745ff5c V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/UEI.SmartControl( 6942): Supports setup maps: true
,D/UEI.SmartControl( 6942): QS start statue = true Error code = 0
I/UEI.SmartControl( 6942): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6942): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
,I/UEI.SmartControl( 6942): ### init IR Blaster...
D/serial_port( 6942): Configuring serial port
E/UEI.SmartControl( 6942): UEIBLaster setting for 616
I/UEI.SmartControl( 6942): Setting serial record hearder size = 2
I/UEI.SmartControl( 6942): configuring settings for MAXQ616
I/UEI.SmartControl( 6942): Get version...
D/UEI.SmartControl( 6942): serial port data available: 21
,D/UEI.SmartControl( 6942): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 6942): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 6942): QS saving settings...
D/UEI.SmartControl( 6942): IR Blaster version: 25672567
,D/UEI.SmartControl( 6942): serial port data available: 4
,I/GAV2    ( 6575): Thread[GAThread,5,main]: No campaign data found.
,W/ContextImpl( 6942): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
I/UEI.SmartControl( 6942): Device manager: loading config....
E/UEI.SmartControl( 6942): Services init done
D/UEI.SmartControl( 6942): ----------- loading internal config...
D/UEI.SmartControl( 6942): QS Service init finished
,D/UEI.SmartControl( 6942): QS Service version name: 2.1.91
D/UEI.SmartControl( 6942): QS Service version code: 201091
D/UEI.SmartControl( 6942): Service requested: Control
E/UEI.SmartControl( 6942): Loading SETTINGS...
D/UEI.SmartControl( 6942): Request IControl service: devices are loaded...
I/QRemote ( 6278): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
,I/UEI.SmartControl( 6942): ------ IControl API: 11
I/UEI.SmartControl( 6942): Registering callback...
I/UEI.SmartControl( 6942): ------ IControl API: 19
I/ActivityManager( 1103): Killing 6278:com.lge.qremote/u0a112 (adj 15): empty #17
I/UEI.SmartControl( 6942): Registering Services Ready callback...
D/UEI.SmartControl( 6942): -- Open brand translation xml: brands_translations_ko
I/UEI.SmartControl( 6942): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6942): -----service ready thread exits
,W/libprocessgroup( 1103): failed to open /acct/uid_10112/pid_6278/cgroup.procs: No such file or directory
D/UEI.SmartControl( 6942): Internal service binding...
,E/WifiStateMachine( 1103):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=31.6, 0.0, 0.0  rx=23.6 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1010259285] gl rssi=-51 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1103):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=31.6, 0.0, 0.0  rx=23.6 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1010259273] gl rssi=-51 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1103): doString: [SIGNAL_POLL]
I/GAV4    ( 6762): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager( 1103): Killing 6556:com.lge.appbox.client/u0a11 (adj 15): empty #17
,W/libprocessgroup( 1103): failed to open /acct/uid_10011/pid_6556/cgroup.procs: No such file or directory
,V/AlarmManager( 1103): ELAPSED_WAKEUP set : Alarm{2e6745f7 type 2 when 126938 com.google.android.gms} when 126938
,D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  313): res_queryN name = mtalk.google.com, class = 1, type = 1
D/libc-netbsd(  313): res_queryN name = mtalk.google.com succeed
,D/GCM     ( 2117): Connected
,D/GCM     ( 2117): Message class com.google.f.a.a.p
,E/WifiStateMachine( 1103):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=17.3, 0.0, 0.0  rx=12.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1010256256] gl rssi=-51 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1103):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=17.3, 0.0, 0.0  rx=12.8 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1010256244] gl rssi=-51 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,D/WifiNative-wlan0( 1103): doString: [SIGNAL_POLL]
D/UEI.SmartControl( 6942): Internal timer expired: 1
,D/UEI.SmartControl( 6942): unbind internal service
,D/serial_port( 6942): close(fd = 25)
D/UEI.SmartControl( 6942): Service.onUnbind: IControl
,D/UEI.SmartControl( 6942): Service.onDestroy
D/UEI.SmartControl( 6942): Lock is in USE false
D/UEI.SmartControl( 6942): unbind internal service
W/System.err( 6942): java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@2d7898a0
W/System.err( 6942): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
W/System.err( 6942): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
W/System.err( 6942): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
W/System.err( 6942): 	at com.uei.control.Service.c(Unknown Source)
W/System.err( 6942): 	at com.uei.control.Service.onDestroy(Unknown Source)
W/System.err( 6942): 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
W/System.err( 6942): 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
W/System.err( 6942): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
W/System.err( 6942): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6942): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6942): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 6942): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6942): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6942): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 6942): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 6942): java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@2d7898a0
I/UEI.SmartControl( 6942): Serial port is closed.
I/UEI.SmartControl( 6942): Serial port is closed.
I/UEI.SmartControl( 6942): Serial port is closed.
D/UEI.SmartControl( 6942): Blaster closed
D/UEI.SmartControl( 6942): Shut down QS...
D/UEI.SmartControl( 6942): Stopping QS lib
D/UEI.SmartControl( 6942): QS lib stop result = true
D/UEI.SmartControl( 6942): Stopped QS lib
,D/UEI.SmartControl( 6942): Stopped file observer...
D/UEI.SmartControl( 6942): QS shutdown complete
I/ActivityManager( 1103): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=7028 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager( 1103): RTC_WAKEUP set : Alarm{d543c64 type 0 when 1454983659705 com.android.vending} when 1454983659705
,D/Finsky  ( 7028): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/LgDataFeature( 7028): LgDataFeature() Constructor: none
D/LgDataFeature( 7028): LgDataFeature() Constructor Done, null
,E/WifiStateMachine( 1103):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=13.1, 0.0, 0.0  rx=10.9 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1010253223] gl rssi=-51 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1103):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=13.1, 0.0, 0.0  rx=10.9 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1010253222] gl rssi=-51 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1103): doString: [SIGNAL_POLL]
,D/Finsky  ( 7028): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/ActivityManager( 1103): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=7070 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/Settings( 7028): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7028): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ResourcesManager( 7070): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7070): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/DownloadManager( 3248): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,D/Finsky  ( 7028): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7028): [1] 2.run: Finished loading 1 libraries.
V/DownloadManager( 3248): created cursor android.database.sqlite.SQLiteCursor@769732c on behalf of 7028
D/Finsky  ( 7028): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/MultiDex( 7070): VM with version 2.1.0 has multidex support
I/MultiDex( 7070): install
,I/MultiDex( 7070): VM has multidex support, MultiDex support library is disabled.
D/Finsky  ( 7028): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,V/JNIHelp ( 7070): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 7070): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7070): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1dedb4a9: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7070): Installed default security provider GmsCore_OpenSSL
V/SIM_STK ( 1103): Menu title from STK is T-Mobile
D/GCM     ( 2117): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AuthorizationBluetoothService( 2117): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 2349): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
I/ActivityManager( 1103): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=7107 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,D/LocationInitializer( 2349): Restart initialization of location
,W/ResourcesManager( 7107): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7107): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/MultiDex( 7107): VM with version 2.1.0 has multidex support
,I/MultiDex( 7107): install
I/MultiDex( 7107): VM has multidex support, MultiDex support library is disabled.
V/JNIHelp ( 7107): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 7107): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7107): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1dedb4a9: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7107): Installed default security provider GmsCore_OpenSSL
D/WearableService( 7107): callingUid 10005, callindPid: 7107
,E/MDM     ( 1818): [86] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/GCM     ( 2117): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AuthorizationBluetoothService( 2117): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GmsCoreStatsServiceLauncher( 2349): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,E/MDM     ( 1818): [87] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 2349): Restart initialization of location
V/Finsky  ( 7028): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,I/art     ( 2117): Explicit concurrent mark sweep GC freed 19275(1063KB) AllocSpace objects, 11(1584KB) LOS objects, 51% free, 30MB/62MB, paused 1.162ms total 37.395ms
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2117): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2117): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2117): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2117): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 7028): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7028): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7028): [1] 5.onFinished: Scheduling replication attempt 2.
,I/ActivityManager( 1103): Killing 6717:com.lge.drmservice/u0a62 (adj 15): empty #17
,I/ActivityManager( 1103): Killing 6153:com.lge.formmanager/u0a26 (adj 15): empty #18
,W/libprocessgroup( 1103): failed to open /acct/uid_10062/pid_6717/cgroup.procs: No such file or directory
,W/libprocessgroup( 1103): failed to open /acct/uid_10026/pid_6153/cgroup.procs: No such file or directory
,V/AlarmManager( 1103): RTC_WAKEUP set : Alarm{299b58eb type 0 when 1454983661207 com.android.vending} when 1454983661207
D/Finsky  ( 7028): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2117): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2117): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2117): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2117): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 7028): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2117): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 2117): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2117): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2117): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2117): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 2117): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2117): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2117): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 7028): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/SIM_STK ( 1103): Menu title from STK is T-Mobile
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2117): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2117): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2117): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2117): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 7028): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 7028): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
D/Finsky  ( 7028): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7028): [1] DailyHygiene.reschedule: Scheduling new run in 31 minutes (failures=2)
D/DeviceConnectionService( 1818): client connected with version: 7571000
,I/[SystemUI]QPairHandler( 1451): onReceive = android.intent.action.PACKAGE_CHANGED
,I/InputReader( 1103): Reconfiguring input devices.  changes=0x00000010
,D/SplitUIService( 1879): replaced split : contains_com.google.android.talk / true
I/[LGHome]EVENT( 2067): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000010 (has extras) }
,I/ActivityManager( 1103): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7155 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/[SystemUI]QSlideListController( 1451): onReceive = android.intent.action.PACKAGE_CHANGED
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1451): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.talk
,D/SplitUIManager( 1879): split_name #11 / not available #0
I/SplitUIService( 1879): split app #11
,W/ResourcesManager( 2067): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/administrator( 1103): Handling package changes for user 0
I/[LGHome]Launcher( 2067): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/AppUp4:AppBoxCP( 7155): onCreate
,W/AppUp4:DB( 7155):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7155):  setFingerPrint start
I/AppUp4:DB( 7155):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 7155):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7155):  SDK version = 21
I/AppUp4:DB( 7155):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7155): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 7155): onReceive
,D/LgDataFeature( 7155): LgDataFeature() Constructor: none
D/LgDataFeature( 7155): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7155): Context : android.app.ReceiverRestrictedContext@3b191a21
D/AppUp4:CustFacade( 7155): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7155): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7155): begin check event
I/AppUp4:CustModeStarterReceiver( 7155): Event For Nothing, skip.
I/NotificationService( 1103): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService( 1103): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000010 (has extras) }
,W/ResourcesManager( 1103): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/ActivityManager( 1103): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7190 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/ActivityManager( 1103): Killing 6618:com.android.chrome/u0a57 (adj 15): empty #17
,W/ResourcesManager( 1103): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourceType( 1103): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,W/libprocessgroup( 1103): failed to open /acct/uid_10057/pid_6618/cgroup.procs: No such file or directory
I/[LGHome]EVENT( 2067): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
W/ResourcesManager( 7190): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7190): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7190): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,W/ResourcesManager( 7190): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7190): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/SystemConfig( 7190): BUILD Country: EU
I/SystemConfig( 7190): BUILD Operator: OPEN
,I/ActivityManager( 1103): Killing 6595:com.android.gallery3d/u0a27 (adj 15): empty #17
,W/libprocessgroup( 1103): failed to open /acct/uid_10027/pid_6595/cgroup.procs: No such file or directory
,I/SystemConfig( 7190): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7190): existFile = false
I/SystemConfig( 7190): canReadFile = false
I/SystemConfig( 7190): systemFeature RCS result false
D/SystemConfig( 7190): refreshRcsSupport() :false
I/ActivityManager( 1103): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7214 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/ResourcesManager( 7214): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7214): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7214): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 7214): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,E/WifiStateMachine( 1103):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=6.6, 0.0, 0.0  rx=5.5 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1010250209] gl rssi=-51 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1103):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=6.6, 0.0, 0.0  rx=5.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1010250208] gl rssi=-51 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1103): doString: [SIGNAL_POLL]
I/art     ( 1103): Explicit concurrent mark sweep GC freed 35135(1636KB) AllocSpace objects, 2(160KB) LOS objects, 33% free, 44MB/66MB, paused 3.344ms total 183.449ms
,I/AppConfig( 7214): Total System Memory = 2995761152
D/SystemHelper( 7214): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager( 1103): Killing 6762:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,W/libprocessgroup( 1103): failed to open /acct/uid_10093/pid_6762/cgroup.procs: No such file or directory
,I/UpdateIcingCorporaServi( 4242): Updating corpora: APPS=com.google.android.talk, CONTACTS=MAYBE
,I/ActivityManager( 1103): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7241 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,V/SIM_STK ( 1103): Menu title from STK is T-Mobile
,W/ResourcesManager( 4242): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 4242): UpdateCorporaTask done [took 98 ms] updated apps [took 98 ms] 
,I/LockScreenSettings( 7241): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7241): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7241): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7241): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7241): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7241): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
D/LockScreenSettings( 7241): Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,I/ActivityManager( 1103): Killing 6647:com.lge.email/u0a23 (adj 15): empty #17
,W/libprocessgroup( 1103): failed to open /acct/uid_10023/pid_6647/cgroup.procs: No such file or directory
,D/PackageBroadcastService( 2349): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.talk
I/PeopleContactsSync( 2349): CP2 sync disabled
,I/ActivityManager( 1103): Killing 5173:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,W/libprocessgroup( 1103): failed to open /acct/uid_1000/pid_5173/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1103): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1103): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1103): tsOffsetIs: Apps: 137688017712; DSPS: 4652617; Offset : -4313891320
,E/WifiStateMachine( 1103):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=4.8, 0.0, 0.0  rx=3.7 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1010247196] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1103):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=4.8, 0.0, 0.0  rx=3.7 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1010247195] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1103): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1103):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=2.9, 0.0, 0.0  rx=2.4 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1010244182] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1103):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=2.9, 0.0, 0.0  rx=2.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1010244179] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1103): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1103):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1010241154] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1103):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1010241150] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1103): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1103):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1010238121] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1103):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1010238118] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1103): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1103):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1010235095] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1103):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1010235084] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1103): doString: [SIGNAL_POLL]
V/AlarmManager( 1103): ELAPSED_WAKEUP set : Alarm{244864f type 2 when 150115 android} when 150115
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
,I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
,I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
E/WifiStateMachine( 1103):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1010232063] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1103):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1010232062] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1103): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1103):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,E/WifiStateMachine( 1103):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1103):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1103):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1103):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1103):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,D/PowerManagerServiceEx( 1103): acquireWakeLockInternal: lock=714663608, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1103
,V/AlarmManager( 1103): RTC_WAKEUP set : Alarm{16c0b2e5 type 0 when 1454983681592 com.android.vending} when 1454983681592
,D/[Concierge]Service( 2614): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1103): releaseWakeLockInternal: lock=714663608 [*alarm*], flags=0x0
,V/SIM_STK ( 1103): Menu title from STK is T-Mobile
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2117): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2117): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2117): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2117): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 7028): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7028): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 7028): [1] 5.onFinished: Scheduling replication attempt 3.
,E/WifiStateMachine( 1103):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1010229051] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1103):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1010229048] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1103): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1103): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1103): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1103): tsOffsetIs: Apps: 157689878902; DSPS: 5308038; Offset : -4313891910
,E/WifiStateMachine( 1103):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1010226023] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1103):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1010226020] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1103): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1103):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1010222994] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1103):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1010222991] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1103): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1103):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1010219964] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1103):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1010219961] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1103): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1103):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1010216940] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1103):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1010216937] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1103): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1103):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1010213915] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1103):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1010213905] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1103): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1103):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1010210887] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1103):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1010210876] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1103): doString: [SIGNAL_POLL]
V/AlarmManager( 1103): RTC_WAKEUP set : Alarm{15a50a0c type 0 when 1454983703407 com.android.vending} when 1454983703407
,V/SIM_STK ( 1103): Menu title from STK is T-Mobile
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2117): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2117): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2117): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2117): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7028): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7028): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7028): [1] 5.onFinished: Scheduling replication attempt 4.
,E/WifiStateMachine( 1103):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1010207855] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1103):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:5] from screen [on:0 period:-1010207850] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1103): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1103): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1103): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1103): tsOffsetIs: Apps: 177691831916; DSPS: 5963462; Offset : -4313892048
,E/WifiStateMachine( 1103):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1010204827] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1103):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1010204826] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1103): doString: [SIGNAL_POLL]
,V/AlarmManager( 1103): ELAPSED_WAKEUP set : Alarm{1393960e type 2 when 180719 android} when 180719
,I/BooksSync( 6575): Starting books sync
,D/BooksSync( 6575): started syncMyEbooks
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2117): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 2117): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2117): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2117): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1103): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1103): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1103): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1103): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1103): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2117): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2117): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2117): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2117): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2117): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2117): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2117): 	at android.os.Binder.execTransact(Binder.java:446)
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
D/ContactsSyncAdapter( 2117): innerSync failed
D/ContactsSyncAdapter( 2117): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2117): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2117): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2117): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2117): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2117): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2117): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2117): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2117): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2117): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2117): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2117): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1398): updateNotificationData: count=3
D/QuickStatusbarLayout( 1398): Notification difference=198
D/QuickStatusbarLayout( 1398): child = android.widget.LinearLayout{1745ff5c V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/SyncManager( 1103): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 153662, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager( 1103): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 245743, reason: 10019
I/GLSUser ( 2117): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2117): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2117): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2117): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1103): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1103): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1103): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1103): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1103): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/GLSActivity( 2117): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2117): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2117): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2117): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2117): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2117): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2117): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
,E/BooksAccountManager( 6575): Authentication error
E/BooksAccountManager( 6575): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6575): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6575): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6575): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6575): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6575): 	at android.os.Binder.execTransact(Binder.java:446)
,E/HttpHelper( 6575): null auth token
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1398): updateNotificationData: count=3
D/QuickStatusbarLayout( 1398): Notification difference=198
D/QuickStatusbarLayout( 1398): child = android.widget.LinearLayout{1745ff5c V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6575): Error response from books API: {
W/ApiaryClient( 6575):  "error": {
W/ApiaryClient( 6575):   "errors": [
W/ApiaryClient( 6575):    {
W/ApiaryClient( 6575):     "domain": "global",
W/ApiaryClient( 6575):     "reason": "required",
W/ApiaryClient( 6575):     "message": "Login Required",
W/ApiaryClient( 6575):     "locationType": "header",
W/ApiaryClient( 6575):     "location": "Authorization"
W/ApiaryClient( 6575):    }
W/ApiaryClient( 6575):   ],
W/ApiaryClient( 6575):   "code": 401,
W/ApiaryClient( 6575):   "message": "Login Required"
W/ApiaryClient( 6575):  }
W/ApiaryClient( 6575): }
,W/ApiaryClient( 6575): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6575): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5844802923936335622&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6575): Headers:
W/ApiaryClient( 6575): accept-encoding: [gzip]
W/ApiaryClient( 6575): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6575): gdata-version: 2
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2117): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2117): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2117): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2117): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1103): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1103): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1103): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1103): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1103): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/GLSActivity( 2117): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2117): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2117): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2117): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2117): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2117): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2117): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6575): Authentication error
E/BooksAccountManager( 6575): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6575): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6575): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6575): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6575): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6575): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6575): null auth token
D/QuickStatusbarLayout( 1398): Notification difference=198
D/QuickStatusbarLayout( 1398): child = android.widget.LinearLayout{1745ff5c V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6575): Error response from books API: {
W/ApiaryClient( 6575):  "error": {
W/ApiaryClient( 6575):   "errors": [
W/ApiaryClient( 6575):    {
W/ApiaryClient( 6575):     "domain": "global",
W/ApiaryClient( 6575):     "reason": "required",
W/ApiaryClient( 6575):     "message": "Login Required",
W/ApiaryClient( 6575):     "locationType": "header",
W/ApiaryClient( 6575):     "location": "Authorization"
W/ApiaryClient( 6575):    }
W/ApiaryClient( 6575):   ],
W/ApiaryClient( 6575):   "code": 401,
W/ApiaryClient( 6575):   "message": "Login Required"
W/ApiaryClient( 6575):  }
W/ApiaryClient( 6575): }
,W/ApiaryClient( 6575): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6575): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5844802923936335622&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6575): Headers:
W/ApiaryClient( 6575): accept-encoding: [gzip]
W/ApiaryClient( 6575): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6575): gdata-version: 2
E/WifiStateMachine( 1103):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1010201805] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1103):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1010201802] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1103): doString: [SIGNAL_POLL]
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2117): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2117): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2117): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2117): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1103): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1103): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1103): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1103): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1103): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
,W/GLSActivity( 2117): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2117): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2117): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2117): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2117): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2117): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2117): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6575): Authentication error
E/BooksAccountManager( 6575): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6575): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6575): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6575): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6575): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6575): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6575): null auth token
D/QuickStatusbarLayout( 1398): Notification difference=198
D/QuickStatusbarLayout( 1398): child = android.widget.LinearLayout{1745ff5c V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6575): Error response from books API: {
W/ApiaryClient( 6575):  "error": {
W/ApiaryClient( 6575):   "errors": [
W/ApiaryClient( 6575):    {
W/ApiaryClient( 6575):     "domain": "global",
W/ApiaryClient( 6575):     "reason": "required",
W/ApiaryClient( 6575):     "message": "Login Required",
W/ApiaryClient( 6575):     "locationType": "header",
W/ApiaryClient( 6575):     "location": "Authorization"
W/ApiaryClient( 6575):    }
W/ApiaryClient( 6575):   ],
W/ApiaryClient( 6575):   "code": 401,
W/ApiaryClient( 6575):   "message": "Login Required"
W/ApiaryClient( 6575):  }
W/ApiaryClient( 6575): }
,W/ApiaryClient( 6575): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6575): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5844802923936335622&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6575): Headers:
W/ApiaryClient( 6575): accept-encoding: [gzip]
W/ApiaryClient( 6575): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6575): gdata-version: 2
,E/BooksSync( 6575): Soft error: 
E/BooksSync( 6575): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6575): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5844802923936335622&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6575): Headers:
E/BooksSync( 6575): accept-encoding: [gzip]
E/BooksSync( 6575): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6575): gdata-version: 2
E/BooksSync( 6575): 
E/BooksSync( 6575): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6575): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6575): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6575): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6575): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6575): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6575): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6575): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6575): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6575): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6575): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6575): {
E/BooksSync( 6575):  "error": {
E/BooksSync( 6575):   "errors": [
E/BooksSync( 6575):    {
E/BooksSync( 6575):     "domain": "global",
E/BooksSync( 6575):     "reason": "required",
E/BooksSync( 6575):     "message": "Login Required",
E/BooksSync( 6575):     "locationType": "header",
E/BooksSync( 6575):     "location": "Authorization"
E/BooksSync( 6575):    }
E/BooksSync( 6575):   ],
E/BooksSync( 6575):   "code": 401,
E/BooksSync( 6575):   "message": "Login Required"
E/BooksSync( 6575):  }
E/BooksSync( 6575): }
E/BooksSync( 6575): 
E/BooksSync( 6575): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6575): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6575): 	... 8 more
,E/BooksSync( 6575): Sync error
E/BooksSync( 6575): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6575): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5844802923936335622&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6575): Headers:
E/BooksSync( 6575): accept-encoding: [gzip]
E/BooksSync( 6575): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6575): gdata-version: 2
E/BooksSync( 6575): 
E/BooksSync( 6575): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6575): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6575): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6575): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6575): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6575): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6575): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6575): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6575): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6575): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6575): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6575): {
E/BooksSync( 6575):  "error": {
E/BooksSync( 6575):   "errors": [
E/BooksSync( 6575):    {
E/BooksSync( 6575):     "domain": "global",
E/BooksSync( 6575):     "reason": "required",
E/BooksSync( 6575):     "message": "Login Required",
E/BooksSync( 6575):     "locationType": "header",
E/BooksSync( 6575):     "location": "Authorization"
E/BooksSync( 6575):    }
E/BooksSync( 6575):   ],
E/BooksSync( 6575):   "code": 401,
E/BooksSync( 6575):   "message": "Login Required"
E/BooksSync( 6575):  }
E/BooksSync( 6575): }
E/BooksSync( 6575): 
E/BooksSync( 6575): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6575): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6575): 	... 8 more
I/BooksSync( 6575): Finished books sync
D/SyncManager( 1103): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 157200, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/WifiStateMachine( 1103):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=2.9, 0.0, 0.0  rx=2.9 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1010198784] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1103):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=2.9, 0.0, 0.0  rx=2.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1010198781] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1103): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1103):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=2.4, 0.0, 0.0  rx=2.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1010195757] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1103):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=2.4, 0.0, 0.0  rx=2.4 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1010195748] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1103): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1103):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=1.7, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1010192726] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1103):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=1.7, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1010192713] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1103): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1103):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1010189696] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1103):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1010189695] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1103): doString: [SIGNAL_POLL]
V/AlarmManager( 1103): RTC_WAKEUP set : Alarm{246942a type 0 when 1454983723782 com.android.vending} when 1454983723782
,V/SIM_STK ( 1103): Menu title from STK is T-Mobile
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2117): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2117): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2117): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2117): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7028): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7028): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7028): [1] 5.onFinished: Scheduling replication attempt 5.
,D/sensors_hal_Time( 1103): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1103): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1103): tsOffsetIs: Apps: 197693834721; DSPS: 6618887; Offset : -4313872729
,E/WifiStateMachine( 1103):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:-1010186672] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1103):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1010186671] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1103): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1103):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1010183662] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1103):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1010183661] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1103): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1103):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1010180641] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1103):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1010180638] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1103): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1103):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1010177611] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1103):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1010177608] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1103): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1103):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1010174588] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1103):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1010174579] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1103): doString: [SIGNAL_POLL]
V/AlarmManager( 1103): ELAPSED_WAKEUP set : Alarm{89156fc type 2 when 210774 android} when 210774
,I/[SystemUI]TimeTickManager( 1451): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1451): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1451): called onTimeUpdated()
,I/[SystemUI]Clock( 1451): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
I/[SystemUI]DateView( 1451): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1451): handleTimeUpdate
E/WifiStateMachine( 1103):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1010171553] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1103):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:6] from screen [on:0 period:-1010171547] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1103): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1103):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1010168539] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1103):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1010168536] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1103): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1103): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1103): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1103): tsOffsetIs: Apps: 217695985130; DSPS: 7274318; Offset : -4313889095
,E/WifiStateMachine( 1103):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1010165511] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1103):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-52 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1010165508] gl rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1103): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1103):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1010162483] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1103):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1010162480] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1103): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1103):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1010159456] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1103):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1010159446] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1103): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1103):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1010156422] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1103):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1010156419] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1103): doString: [SIGNAL_POLL]
,V/AlarmManager( 1103): ELAPSED_WAKEUP set : Alarm{314b0185 type 2 when 205216 android} when 205216
,V/AlarmManager( 1103): RTC_WAKEUP set : Alarm{9445bda type 0 when 1454983713669 com.google.android.gms} when 1454983713669
V/AlarmManager( 1103): RTC_WAKEUP set : Alarm{141ae6e8 type 0 when 1454983744856 com.android.vending} when 1454983744856
,D/[Concierge]Service( 2614): onStartCommand(). Type : 9
,I/EventLogService( 2349): Aggregate from 1454981913609 (log), 1454981913609 (data)
,V/SIM_STK ( 1103): Menu title from STK is T-Mobile
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2117): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2117): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2117): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2117): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1103): Explicit concurrent mark sweep GC freed 52348(2MB) AllocSpace objects, 5(592KB) LOS objects, 33% free, 44MB/66MB, paused 1.567ms total 136.087ms
,D/Finsky  ( 7028): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 7028): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 7028): [1] 5.onFinished: Giving up after 6 failures.
,E/WifiStateMachine( 1103):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1010153403] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1103):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1010153400] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1103): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1103):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1010150373] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1103):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1010150370] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1103): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1103): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1103): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1103): tsOffsetIs: Apps: 237698125018; DSPS: 7929748; Offset : -4313885488
,E/WifiStateMachine( 1103):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1010147343] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1103):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1010147340] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1103): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1103):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1010144320] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1103):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1010144317] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1103): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1103):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1010141296] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1103):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1010141295] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1103): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1103):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1010138284] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1103):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1010138280] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1103): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1103):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1010135255] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1103):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1010135245] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1103): doString: [SIGNAL_POLL]
,V/AlarmManager( 1103): ELAPSED_WAKEUP set : Alarm{488fa56 type 2 when 250051 android} when 250051
,I/BooksSync( 6575): Starting books sync
,D/BooksSync( 6575): started syncMyEbooks
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 2117): Explicit concurrent mark sweep GC freed 32504(1921KB) AllocSpace objects, 10(1440KB) LOS objects, 51% free, 30MB/62MB, paused 1.502ms total 59.658ms
,I/GLSUser ( 2117): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2117): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2117): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2117): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1103): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1103): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1103): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1103): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1103): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/GLSActivity( 2117): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2117): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2117): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2117): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2117): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2117): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2117): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
,E/BooksAccountManager( 6575): Authentication error
E/BooksAccountManager( 6575): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6575): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6575): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6575): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6575): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6575): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6575): null auth token
E/LgeQuickCoverOverlayWindow( 1398): updateNotificationData: count=3
D/QuickStatusbarLayout( 1398): Notification difference=198
D/QuickStatusbarLayout( 1398): child = android.widget.LinearLayout{1745ff5c V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6575): Error response from books API: {
W/ApiaryClient( 6575):  "error": {
W/ApiaryClient( 6575):   "errors": [
W/ApiaryClient( 6575):    {
W/ApiaryClient( 6575):     "domain": "global",
W/ApiaryClient( 6575):     "reason": "required",
W/ApiaryClient( 6575):     "message": "Login Required",
W/ApiaryClient( 6575):     "locationType": "header",
W/ApiaryClient( 6575):     "location": "Authorization"
W/ApiaryClient( 6575):    }
W/ApiaryClient( 6575):   ],
W/ApiaryClient( 6575):   "code": 401,
W/ApiaryClient( 6575):   "message": "Login Required"
W/ApiaryClient( 6575):  }
W/ApiaryClient( 6575): }
,W/ApiaryClient( 6575): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6575): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7575264326429459695&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6575): Headers:
W/ApiaryClient( 6575): accept-encoding: [gzip]
W/ApiaryClient( 6575): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6575): gdata-version: 2
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2117): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2117): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2117): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2117): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1103): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1103): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1103): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1103): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1103): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
,W/GLSActivity( 2117): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2117): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2117): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2117): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2117): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2117): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2117): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6575): Authentication error
E/BooksAccountManager( 6575): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6575): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6575): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6575): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6575): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6575): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6575): null auth token
D/QuickStatusbarLayout( 1398): Notification difference=198
D/QuickStatusbarLayout( 1398): child = android.widget.LinearLayout{1745ff5c V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6575): Error response from books API: {
W/ApiaryClient( 6575):  "error": {
W/ApiaryClient( 6575):   "errors": [
W/ApiaryClient( 6575):    {
W/ApiaryClient( 6575):     "domain": "global",
W/ApiaryClient( 6575):     "reason": "required",
W/ApiaryClient( 6575):     "message": "Login Required",
W/ApiaryClient( 6575):     "locationType": "header",
W/ApiaryClient( 6575):     "location": "Authorization"
W/ApiaryClient( 6575):    }
W/ApiaryClient( 6575):   ],
W/ApiaryClient( 6575):   "code": 401,
W/ApiaryClient( 6575):   "message": "Login Required"
W/ApiaryClient( 6575):  }
W/ApiaryClient( 6575): }
,W/ApiaryClient( 6575): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6575): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7575264326429459695&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6575): Headers:
W/ApiaryClient( 6575): accept-encoding: [gzip]
W/ApiaryClient( 6575): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6575): gdata-version: 2
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2117): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2117): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2117): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2117): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2117): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/WifiStateMachine( 1103):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1010132225] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1103):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1010132222] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1103): doString: [SIGNAL_POLL]
V/NotificationService( 1103): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1103): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1103): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1103): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1103): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
,D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1398): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1398): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1398): updateNotificationData: count=3
W/GLSActivity( 2117): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2117): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2117): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2117): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2117): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2117): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2117): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6575): Authentication error
E/BooksAccountManager( 6575): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6575): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6575): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6575): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6575): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6575): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6575): null auth token
D/QuickStatusbarLayout( 1398): Notification difference=198
D/QuickStatusbarLayout( 1398): child = android.widget.LinearLayout{1745ff5c V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6575): Error response from books API: {
W/ApiaryClient( 6575):  "error": {
W/ApiaryClient( 6575):   "errors": [
W/ApiaryClient( 6575):    {
W/ApiaryClient( 6575):     "domain": "global",
W/ApiaryClient( 6575):     "reason": "required",
W/ApiaryClient( 6575):     "message": "Login Required",
W/ApiaryClient( 6575):     "locationType": "header",
W/ApiaryClient( 6575):     "location": "Authorization"
W/ApiaryClient( 6575):    }
W/ApiaryClient( 6575):   ],
W/ApiaryClient( 6575):   "code": 401,
W/ApiaryClient( 6575):   "message": "Login Required"
W/ApiaryClient( 6575):  }
W/ApiaryClient( 6575): }
,W/ApiaryClient( 6575): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6575): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7575264326429459695&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6575): Headers:
W/ApiaryClient( 6575): accept-encoding: [gzip]
W/ApiaryClient( 6575): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6575): gdata-version: 2
I/jxcore-log( 6035): --= Surplus to requirements =--
I/jxcore-log( 6035): 
I/jxcore-log( 6035): ****TEST TOOK:  ms ****
I/jxcore-log( 6035): 
I/jxcore-log( 6035): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6035): 
,E/BooksSync( 6575): Soft error: 
E/BooksSync( 6575): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6575): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7575264326429459695&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6575): Headers:
E/BooksSync( 6575): accept-encoding: [gzip]
E/BooksSync( 6575): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6575): gdata-version: 2
E/BooksSync( 6575): 
E/BooksSync( 6575): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6575): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6575): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6575): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6575): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6575): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6575): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6575): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6575): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6575): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6575): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6575): {
E/BooksSync( 6575):  "error": {
E/BooksSync( 6575):   "errors": [
E/BooksSync( 6575):    {
E/BooksSync( 6575):     "domain": "global",
E/BooksSync( 6575):     "reason": "required",
E/BooksSync( 6575):     "message": "Login Required",
E/BooksSync( 6575):     "locationType": "header",
E/BooksSync( 6575):     "location": "Authorization"
E/BooksSync( 6575):    }
E/BooksSync( 6575):   ],
E/BooksSync( 6575):   "code": 401,
E/BooksSync( 6575):   "message": "Login Required"
E/BooksSync( 6575):  }
E/BooksSync( 6575): }
E/BooksSync( 6575): 
E/BooksSync( 6575): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6575): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6575): 	... 8 more
,E/BooksSync( 6575): Sync error
E/BooksSync( 6575): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6575): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7575264326429459695&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6575): Headers:
E/BooksSync( 6575): accept-encoding: [gzip]
E/BooksSync( 6575): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6575): gdata-version: 2
E/BooksSync( 6575): 
E/BooksSync( 6575): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6575): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6575): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6575): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6575): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6575): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6575): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6575): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6575): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6575): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6575): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6575): {
E/BooksSync( 6575):  "error": {
E/BooksSync( 6575):   "errors": [
E/BooksSync( 6575):    {
E/BooksSync( 6575):     "domain": "global",
E/BooksSync( 6575):     "reason": "required",
E/BooksSync( 6575):     "message": "Login Required",
E/BooksSync( 6575):     "locationType": "header",
E/BooksSync( 6575):     "location": "Authorization"
E/BooksSync( 6575):    }
E/BooksSync( 6575):   ],
E/BooksSync( 6575):   "code": 401,
E/BooksSync( 6575):   "message": "Login Required"
E/BooksSync( 6575):  }
E/BooksSync( 6575): }
E/BooksSync( 6575): 
E/BooksSync( 6575): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6575): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6575): 	... 8 more
I/BooksSync( 6575): Finished books sync
D/SyncManager( 1103): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 250051, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/AndroidRuntime( 7420): 
D/AndroidRuntime( 7420): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7420): CheckJNI is OFF
D/AndroidRuntime( 7420): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1103): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
I/ActivityManager( 1103): Killing 6035:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
,W/PackageSettings( 1103): Skipping PackageSetting{1d9397f5 com.example.hello/10319} due to missing metadata
,I/WindowState( 1103): WIN DEATH: Window{22b2c3a9 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService( 1103): Client connection lost with reason: 4
D/InputDispatcher( 1103): Window went away: Window{22b2c3a9 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/ActivityManager( 1103):   Force finishing activity ActivityRecord{17dcada u0 com.test.thalitest/.MainActivity t4}
,E/GBMv2   (  344): DFP En is all cleared set to be enabled
,W/ActivityManager( 1103): Spurious death for ProcessRecord{309f2a90 6035:com.test.thalitest/u0a311}, curProc for 6035: null
I/ActivityManager( 1103): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
I/ActivityManager( 1103):   Force finishing activity ActivityRecord{17dcada u0 com.test.thalitest/.MainActivity t4 f}
W/ActivityManager( 1103): Duplicate finish request for ActivityRecord{17dcada u0 com.test.thalitest/.MainActivity t4 f}
,I/[LGHome]EVENT( 2067): [Launcher.java:5338:onStart()]onStart
D/SplitWindowPolicy( 1948): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
I/[LGHome]EVENT( 2067): [Launcher.java:903:onResume()]onResume
,D/SplitWindowPolicy( 1948): topRunningActivity=ActivityInfo{2193bc6d co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[LGHome]EVENT( 2067): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 2067): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
D/SplitWindowPolicy( 1948): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1948): topRunningActivity=ActivityInfo{389ea0a2 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
D/ActionManagerService( 1913): notifyUserLog: 1000003
D/LIA_Informant_ActionManagerMessageHandler( 2717): handleMessage: what(1000) actionID(0x1000003)
I/[LGHome]GBoardWebView( 2067): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
D/KeyguardModel( 1451): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,W/GeofencerStateMachine( 1818): Ignoring removeGeofence because network location is disabled.
I/InputReader( 1103): Reconfiguring input devices.  changes=0x00000010
D/LIA_Service_RemotePackageHandler( 2012): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
D/LIA_MrGDBLogger_PackageInfoDetector( 2717): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
,E/LGBluetoothAvrcpQcomAdapter( 6090): [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
D/LGBluetoothAvrcpQcomAdapter( 6090): [BTUI] [+] updateMediaPlayerInfo
I/art     ( 4242): Explicit concurrent mark sweep GC freed 21654(1244KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 29MB/45MB, paused 8.395ms total 74.961ms
,I/ActivityManager( 1103): Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=7453 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/[LGHome]LGActivityUtil( 2067): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 2067): [Launcher.java:1056:onResume()]onResume end
,I/[LGHome]EVENT( 2067): [Launcher.java:1114:onPause()]onPause
W/System.err( 4190): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
I/[SystemUI]QSlideListController( 1451): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]GBoardWebView( 2067): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
D/ActionManagerService( 1913): notifyUserLog: 1000004
D/LIA_Informant_ActionManagerMessageHandler( 2717): handleMessage: what(1000) actionID(0x1000004)
V/BoardContentProvider( 2717): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
I/GBoardWebViewUtils( 2067): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2067): , create_time: 1430558575574
I/GBoardWebViewUtils( 2067): , expire_time: 0
I/GBoardWebViewUtils( 2067): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2067): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2067): , display: false
I/GBoardWebViewUtils( 2067): , animation: false }
I/GBoardWebViewUtils( 2067): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2067): , create_time: 1430558575600
I/GBoardWebViewUtils( 2067): , expire_time: 0
I/GBoardWebViewUtils( 2067): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2067): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2067): , display: false
I/GBoardWebViewUtils( 2067): , animation: false }
I/GBoardWebViewUtils( 2067): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1454599632914
I/GBoardWebViewUtils( 2067): , create_time: 1454599633839
I/GBoardWebViewUtils( 2067): , expire_time: 0
I/GBoardWebViewUtils( 2067): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide.html?id=guide_1111111111116_1454599632914&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2067): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2067): , display: false
I/GBoardWebViewUtils( 2067): , animation: false }
D/KeyguardModel( 1451): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1451): createShortcutInfo...
,D/KeyguardModel( 1451): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1451): createShortcutInfo...
W/ResourcesManager( 1451): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1451): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1451): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1451): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,W/ResourceType( 1451): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1451): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/SplitUIManager( 1879): split_name #11 / not available #0
D/SplitUIService( 1879): removed split : 
D/WallpaperManager( 2067): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
I/SystemUI[Framework]( 1103): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1103): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1103): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1103): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1103): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3a0e000,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1103): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
,I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1451): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1451): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
D/KeyguardModel( 1451): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1451): createShortcutInfo...
I/[LGHome]GBoardWebView( 2067): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
W/ResourcesManager( 1451): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1451): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourceType( 1451): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1451): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1451): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1451): createShortcutInfo...
D/SplitUIManager( 1879): split_name #11 / not available #0
I/SplitUIService( 1879): split app #11
W/ResourcesManager( 1451): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1451): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1451): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1451): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1451): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1451): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,D/KeyguardModel( 1451): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1451): createShortcutInfo...
W/System.err( 4190): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4190): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4190): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4190): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4190): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4190): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4190): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4190): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4190): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4190): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4190): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
V/SIM_STK ( 1103): Menu title from STK is T-Mobile
D/KeyguardModel( 1451): handleShortcutListChanged...
D/KeyguardModel( 1451): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1451): createShortcutInfo...
,D/KeyguardModel( 1451): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1451): createShortcutInfo...
W/ResourceType( 1451): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1451): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1451): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1451): createShortcutInfo...
W/ResourceType( 1451): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1451): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1451): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1451): createShortcutInfo...
W/ResourceType( 1451): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1451): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1451): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1451): createShortcutInfo...
D/KeyguardModel( 1451): handleShortcutListChanged...
I/art     ( 1103): Explicit concurrent mark sweep GC freed 24284(1491KB) AllocSpace objects, 6(480KB) LOS objects, 33% free, 44MB/66MB, paused 2.212ms total 217.902ms
I/art     ( 1103): WaitForGcToComplete blocked for 205.047ms for cause Explicit
,V/SIM_STK ( 1103): Menu title from STK is T-Mobile
,V/SIM_STK ( 1103): Menu title from STK is T-Mobile
I/[LGHome]EVENT( 2067): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]EVENT( 2067): [Launcher.java:5349:onStop()]onStop
W/ResourcesManager( 7453): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/administrator( 1103): Handling package changes for user 0
W/ActivityManager( 1103): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,D/LGBluetoothAvrcpQcomAdapter( 6090): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 6090): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6090): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 6090): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 6090): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 6090): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6090): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 6090): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6090): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 6090): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6090): [BTUI] [-] updateMediaPlayerInfo
V/SIM_STK ( 1103): Menu title from STK is T-Mobile
I/ThermalEngine(  338): Thermal-Server: Thermal received msg from  override
I/Thermal-Lib( 3107): Thermal-Lib-Client: Client request sent
,I/[LGHome]Launcher.Model( 2067): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
D/PluginManager( 7453): init()
I/[LGHome]Launcher( 2067): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2067): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2067): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2067): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2067): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/Timeline( 1103): Timeline: Activity_windows_visible id: ActivityRecord{2a62e7d8 u0 com.lge.launcher2/.Launcher t3} time:255041
,I/[LGHome]Launcher.Model( 2067): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 2067): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2067): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2067): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/[LGHome]EVENT( 2067): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 2067): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2067): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[Concierge]WidgetView( 2067): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
D/[Concierge]Service( 2614): onStartCommand(). Type : 8
,D/[Concierge]Service( 2614): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/[Concierge]Service( 2614): Update widget ID : 11
D/[Concierge]WidgetView( 2067): change position of spinner
I/[Concierge]WidgetView( 2067): initWebView(). Time : 1454983783367
D/[Concierge]Service( 2614): onStartCommand(). Type : 0
I/[Concierge]WebView( 2067): Return exist ConciergeWebView. Reuse : 35049338
D/[Concierge]WidgetView( 2067): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2067): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
I/NotificationService( 1103): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1103): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1103): Receieved: android.intent.action.PACKAGE_REMOVED
,D/TaskPersister( 1103): removeObsoleteFile: deleting file=4_task.xml
D/PhoneStatusBar( 1451): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
I/[SystemUI]NavigationThemeResource( 1451): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1451):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1451): , Keyguard show=false, IME shown=false, Panel expanded=false
I/[LgeWidgetLib]ExtViewHost( 2067): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@1609fa8d
I/[LGHome]EVENT( 2067): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2067): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2067): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2067): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/[Concierge]WidgetBroadcastReceiver( 2067): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
W/[Concierge]WidgetView( 2067): Widget kill message received. Destory myself. My : 1454983557133, New one : 1454983783367
D/[Concierge]WidgetView( 2067): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2067): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,D/[Concierge]WidgetView( 2067): isWidgetUpdateSkippable ? true
I/[LGHome]Launcher( 2067): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2067): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2067): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2067): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2067): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2067): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2067): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2067): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/[LgeWidgetLib]LgeAppWidgetHostView( 2067): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
W/ResourcesManager( 1103): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
E/[LgeWidgetLib]LgeAppWidgetHostView( 2067): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2067): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
W/ResourceType( 1103): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/[LGHome]Launcher( 2067): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/[LGHome]EVENT( 2067): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/Timeline( 2067): Timeline: Activity_idle id: android.os.BinderProxy@2231f351 time:255195
I/art     ( 1103): Explicit concurrent mark sweep GC freed 9432(498KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 1.593ms total 252.024ms
D/AndroidRuntime( 7420): Shutting down VM
,I/chromium( 2067): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,I/GBoardtInterface( 2067): onReloaded()
,W/ExternalStrings( 7453): load override strings
W/ExternalStrings( 7453): java.lang.RuntimeException: Unexpected tag, got eat-comment
W/ExternalStrings( 7453): 	at com.mcafee.plugin.af.a(Unknown Source)
W/ExternalStrings( 7453): 	at com.mcafee.plugin.ac.b(Unknown Source)
W/ExternalStrings( 7453): 	at com.mcafee.plugin.ak.d(Unknown Source)
W/ExternalStrings( 7453): 	at com.mcafee.plugin.ak.a(Unknown Source)
W/ExternalStrings( 7453): 	at com.mcafee.app.s.getClassLoader(Unknown Source)
W/ExternalStrings( 7453): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
W/ExternalStrings( 7453): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
W/ExternalStrings( 7453): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
W/ExternalStrings( 7453): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
W/ExternalStrings( 7453): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
W/ExternalStrings( 7453): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ExternalStrings( 7453): 	at android.os.Looper.loop(Looper.java:135)
W/ExternalStrings( 7453): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/ExternalStrings( 7453): 	at java.lang.reflect.Method.invoke(Native Method)
W/ExternalStrings( 7453): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/ExternalStrings( 7453): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/ExternalStrings( 7453): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
I/GBoardWebViewClient( 2067): onPageFinished url:file:///android_asset/www/main.html
D/StatusProvider( 7453): onCreate
V/BoardContentProvider( 2717): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
V/BoardContentProvider( 2717): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/ActionManagerService( 1913): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 2717): handleMessage: what(1000) actionID(0x1000001)
,D/LIA_Informant_Tips_SmartTipsActionManager( 2717): onEvent() : ACTION_BOARD_ENABLED
,D/ActionManagerService( 1913): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 2717): handleMessage: what(1000) actionID(0x1000001)
V/BoardContentProvider( 2717): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/LIA_Informant_Tips_SmartTipsActionManager( 2717): onEvent() : ACTION_BOARD_ENABLED
D/LIA_Informant_Tips_FormEventRepository( 2717): getSize() : size - 0
D/LIA_Informant_Tips_SmartTipsActionManager( 2717): onSettingEvent() : GBoard On - add scheduler - 0
D/GBoardUriUtils( 2067): fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
D/GBoardWebViewUtils( 2067): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
D/GBoardUriUtils( 2067): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
D/GBoardWebViewUtils( 2067): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
D/GBoardUriUtils( 2067): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide2.html?id=guide_1111111111116_1454599632914&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
D/GBoardWebViewUtils( 2067): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide2.html?id=guide_1111111111116_1454599632914&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
V/Signer  ( 7453): override build config not found
D/Signer  ( 7453): value of property debug is false
,D/LGMDMWrapper( 7453): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
D/LGMDMWrapper( 7453): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
D/LGMDMWrapper( 7453): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
D/LGMDMWrapper( 7453): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
D/LGMDMWrapper( 7453): Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
D/LGMDMWrapper( 7453): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
D/LGMDMWrapper( 7453): Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
,D/LGMDMWrapper( 7453): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
D/LGMDMWrapper( 7453): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
D/LGMDMWrapper( 7453): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
D/LGMDMWrapper( 7453): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
D/LGMDMWrapper( 7453): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
D/LGMDMWrapper( 7453): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
V/LGMDMManager( 7453): Create singleton instance
D/LGMDMWrapper( 7453): LG MDM library v4.0.0 is available on this device.
,D/PostponalbeReceiver( 7453): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,W/ContextImpl( 7453): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
D/AppUp4:PreloadHelper( 7155): added Exclude : com.test.thalitest
,I/ActivityManager( 1103): Killing 6881:com.qualcomm.timeservice/1000 (adj 15): empty #17
W/ActivityThread( 7453): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/libprocessgroup( 1103): failed to open /acct/uid_1000/pid_6881/cgroup.procs: No such file or directory
,E/SQLiteDatabase( 7453): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 7453): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7453): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7453): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.ConfigManager.c(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.ConfigManager.ab(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.fw.ws.WSLicenseService.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.g.b.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.applock.AppLockComponent.a_(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.applock.AppLockComponent.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7453): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7453): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7453): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7453): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7453): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7453): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7453): 	at com.mcafee.d.c.run(Unknown Source)
D/VoicemailCleanupService( 2171): Cleaning up data for package: com.test.thalitest
E/SQLiteLog( 2171): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
D/ContactsProvider2ForLG( 2171): performBackgroundTask SQLiteDiskIOException during query
D/ContactsProvider2ForLG( 2171): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
D/ContactsProvider2ForLG( 2171): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
D/ContactsProvider2ForLG( 2171): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:560)
D/ContactsProvider2ForLG( 2171): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
D/ContactsProvider2ForLG( 2171): 	at android.database.sqlite.SQLiteSession.be,ginTransaction(SQLiteSession.java:298)
D/ContactsProvider2ForLG( 2171): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
D/ContactsProvider2ForLG( 2171): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
D/ContactsProvider2ForLG( 2171): 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:394)
D/ContactsProvider2ForLG( 2171): 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:363)
D/ContactsProvider2ForLG( 2171): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:974)
D/ContactsProvider2ForLG( 2171): 	at com.android.providers.contacts.ContactsProvider2ForLG.performBackgroundTask(ContactsProvider2ForLG.java:375)
D/ContactsProvider2ForLG( 2171): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:748)
D/ContactsProvider2ForLG( 2171): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/ContactsProvider2ForLG( 2171): 	at android.os.Looper.loop(Looper.java:135)
D/ContactsProvider2ForLG( 2171): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 2171): (3850) statement aborts at 37: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
--------- beginning of crash
E/AndroidRuntime( 2171): FATAL EXCEPTION: IntentService[VoicemailCleanupService]
E/AndroidRuntime( 2171): Process: android.process.acore, PID: 2171
E/AndroidRuntime( 2171): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2171): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 2171): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:739)
E/AndroidRuntime( 2171): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
E/AndroidRuntime( 2171): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 2171): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1600)
E/AndroidRuntime( 2171): 	at com.android.providers.contacts.util.DbModifierWithNotification.delete(DbModifierWithNotification.java:161)
E/AndroidRuntime( 2171): 	at com.android.providers.contacts.voicemail.VoicemailContentTable.delete(VoicemailContentTable.java:229)
E/AndroidRuntime( 2171): 	at com.android.providers.contacts.voicemail.VoicemailContentProvider.delete(VoicemailContentProvider.java:135)
E/AndroidRuntime( 2171): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
E/AndroidRuntime( 2171): 	at android.content.ContentResolver.delete(ContentResolver.java:1315)
E/AndroidRuntime( 2171): 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
E/AndroidRuntime( 2171): 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
E/AndroidRuntime( 2171): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2171): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2171): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 2171): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteDatabase( 7453): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/lockedapplications'.
E/SQLiteDatabase( 7453): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7453): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7453): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 7453): 	at com.mcafee.applock.a.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.applock.d.d(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.applock.d.<init>(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.applock.d.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.modes.adapt.a.<init>(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.modes.adapt.a.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.modes.adapt.ModesLockHelper.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.applock.h.<init>(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.applock.f.<init>(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.applock.f.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.applock.AppLockComponent.d(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.applock.AppLockComponent.a_(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.applock.AppLockComponent.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7453): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7453): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7453): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7453): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7453): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7453): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7453): 	at com.mcafee.d.c.run(Unknown Source)
E/SQLiteOpenHelper( 7453): Couldn't open lockedapplications for writing (will try read-only):
E/SQLiteOpenHelper( 7453): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7453): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7453): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 7453): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 7453): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 7453): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 7453): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 7453): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteOpenHelper( 7453): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteOpenHelper( 7453): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteOpenHelper( 7453): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteOpenHelper( 7453): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 7453): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 7453): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 7453): 	at com.mcafee.applock.a.a(Unknown Source)
E/SQLiteOpenHelper( 7453): 	at com.mcafee.applock.d.d(Unknown Source)
E/SQLiteOpenHelper( 7453): 	at com.mcafee.applock.d.<init>(Unknown Source)
E/SQLiteOpenHelper( 7453): 	at com.mcafee.applock.d.a(Unknown Source)
E/SQLiteOpenHelper( 7453): 	at com.mcafee.modes.adapt.a.<init>(Unknown Source)
E/SQLiteOpenHelper( 7453): 	at com.mcafee.modes.adapt.a.a(Unknown Source)
E/SQLiteOpenHelper( 7453): 	at com.mcafee.modes.adapt.ModesLockHelper.a(Unknown Source)
E/SQLiteOpenHelper( 7453): 	at com.mcafee.applock.h.<init>(Unknown Source)
E/SQLiteOpenHelper( 7453): 	at com.mcafee.applock.f.<init>(Unknown Source)
E/SQLiteOpenHelper( 7453): 	at com.mcafee.applock.f.a(Unknown Source)
E/SQLiteOpenHelper( 7453): 	at com.mcafee.applock.AppLockComponent.d(Unknown Source)
E/SQLiteOpenHelper( 7453): 	at com.mcafee.applock.AppLockComponent.a_(Unknown Source)
E/SQLiteOpenHelper( 7453): 	at com.mcafee.applock.AppLockComponent.a(Unknown Source)
E/SQLiteOpenHelper( 7453): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteOpenHelper( 7453): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteOpenHelper( 7453): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteOpenHelper( 7453): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteOpenHelper( 7453): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteOpenHelper( 7453): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteOpenHelper( 7453): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 7453): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 7453): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteOpenHelper( 7453): 	at com.mcafee.d.c.run(Unknown Source)
W/SQLiteOpenHelper( 7453): Opened lockedapplications in read-only mode
I/GBoardtInterface( 2067): exportHTML()
I/ActivityManager( 1103): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=7490 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/Process ( 2171): Sending signal. PID: 2171 SIG: 9
E/SQLiteDatabase( 7453): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 7453): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7453): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7453): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.ConfigManager.b(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.notificationtray.e.<init>(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.notificationtray.e.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.notificationtray.NotificationComponent.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7453): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7453): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7453): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7453): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7453): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7453): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7453): 	at com.mcafee.d.c.run(Unknown Source)
I/GBoardtInterface( 2067): exportHTML()
E/DropBoxManagerService( 1103): Can't write: system_app_crash
E/DropBoxManagerService( 1103): java.io.FileNotFoundException: /data/system/dropbox/drop109.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1103): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 1103): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 1103): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 1103): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1103): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 1103): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
E/DropBoxManagerService( 1103): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1103): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1103): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 1103): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 1103): 	... 5 more
,I/GBoardtInterface( 2067): exportHTML()
I/ActivityManager( 1103): Process android.process.acore (pid 2171) has died
W/ActivityManager( 1103): Scheduling restart of crashed service com.android.providers.contacts/.voicemail.VoicemailCleanupService in 1000ms
W/ActivityManager( 1103): Scheduling restart of crashed service com.android.providers.contacts/com.lge.providers.contacts.AliveAcoreService in 1000ms
,E/SQLiteDatabase( 7453): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 7453): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7453): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7453): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.ConfigManager.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.wavesecure.utils.CommonPhoneUtils.o(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.wavesecure.utils.y.v(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7453): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7453): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7453): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7453): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7453): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7453): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7453): 	at com.mcafee.d.c.run(Unknown Source)
E/SQLiteDatabase( 7453): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 7453): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7453): 	at androi,d.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7453): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7453): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.ConfigManager.d(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.wavesecure.utils.CommonPhoneUtils.o(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.wavesecure.utils.y.v(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7453): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7453): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7453): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7453): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7453): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7453): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7453): 	at com.mcafee.d.c.run(Unknown Source)
E/SQLiteDatabase( 7453): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 7453): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7453): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7453): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.ConfigMana,ger.g(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.ConfigManager.c(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.ConfigManager.m(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7453): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7453): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7453): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7453): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7453): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7453): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7453): 	at com.mcafee.d.c.run(Unknown Source)
E/SQLiteDatabase( 7453): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 7453): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7453): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7453): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.ConfigManager.c(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.wavesecure.c2dm.a.d(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.wavesecure.c2dm.a.c(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.wavesecure.notification.g.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7453): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7453): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7453): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7453): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7453): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7453): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7453): 	at com.mcafee.d.c.run(Unknown Source)
W/ResourcesManager( 7490): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7490): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7490): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7490): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
D/LgDataFeature( 7453): LgDataFeature() Constructor: none
D/LgDataFeature( 7453): LgDataFeature() Constructor Done, null
,E/SQLiteDatabase( 7453): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 7453): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7453): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7453): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.ConfigManager.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.ConfigManager.b(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.ConfigManager.J(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.wavesecure.c2dm.a.d(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.wavesecure.c2dm.a.c(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.wavesecure.notification.g.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7453): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7453): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7453): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7453): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7453): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7453): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7453): 	at com.mcafee.d.c.run(Unknown Source)
E/SQLiteDatabase( 7453): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 7453): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7453): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7453): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.ConfigManager.d(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.ConfigManager.r(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.wavesecure.notification.c.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7453): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7453): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7453): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7453): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7453): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7453): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7453): 	at com.mcafee.d.c.run(Unknown Source)
E/SQLiteDatabase( 7453): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 7453): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7453): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7453): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.ConfigManager.c(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.wavesecure.notification.r.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7453): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7453): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7453): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7453): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7453): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7453): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7453): 	at com.mcafee.d.c.run(Unknown Source)
E/SQLiteDatabase( 7453): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 7453): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7453): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7453): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.ConfigManager.c(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.wavesecure.notification.o.d(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.notificationtray.a.b.b(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.notificationtray.a.b.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.notificationtray.a.c.run(Unknown Source)
E/SQLiteDatabase( 7453): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7453): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7453): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7453): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7453): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7453): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7453): 	at com.mcafee.d.c.run(Unknown Source)
E/SQLiteDatabase( 7453): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 7453): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7453): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7453): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.ConfigManager.c(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.wavesecure.notification.q.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7453): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7453): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7453): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7453): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7453): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7453): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7453): 	at com.mcafee.d.c.run(Unknown Source)
E/SQLiteDatabase( 7453): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 7453): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7453): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7453): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.ConfigManager.b(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.ConfigManager.aq(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.MSSComponentConfig.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.wavesecure.dataStorage.WSFeatureConfig.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.wavesecure.backup.BaseBackup.b(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.wavesecure.core.WSComponent.c(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7453): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7453): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7453): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7453): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7453): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7453): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7453): 	at com.mcafee.d.c.run(Unknown Source)
E/SQLiteDatabase( 7453): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 7453): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7453): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7453): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.ConfigManager.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.MSSComponentConfig.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.wavesecure.dataStorage.WSFeatureConfig.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.wavesecure.backup.BaseBackup.b(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.wavesecure.core.WSComponent.c(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7453): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7453): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7453): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7453): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7453): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7453): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7453): 	at com.mcafee.d.c.run(Unknown Source)
E/SQLiteDatabase( 7453): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 7453): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7453): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7453): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.ConfigManager.e(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.ConfigManager.d(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.wavesecure.dataStorage.WSFeatureConfig.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.wavesecure.backup.BaseBackup.b(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.wavesecure.core.WSComponent.c(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7453): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7453): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7453): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7453): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7453): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7453): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7453): 	at com.mcafee.d.c.run(Unknown Source)
E/SQLiteDatabase( 7453): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 7453): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7453): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7453): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.ConfigManager.c(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.ConfigManager.N(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.ConfigManager.d(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.wavesecure.dataStorage.WSFeatureConfig.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.wavesecure.backup.BaseBackup.b(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.wavesecure.core.WSComponent.c(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7453): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7453): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7453): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7453): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7453): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7453): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7453): 	at com.mcafee.d.c.run(Unknown Source)
E/SQLiteDatabase( 7453): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 7453): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7453): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7453): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.ConfigManager.b(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7453): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7453): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7453): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7453): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7453): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7453): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7453): 	at com.mcafee.d.c.run(Unknown Source)
E/SQLiteDatabase( 7453): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 7453): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7453): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7453): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.wsstorage.ConfigManager.c(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7453): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7453): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7453): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7453): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7453): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7453): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7453): 	at com.mcafee.d.c.run(Unknown Source)
E/SQLiteDatabase( 7490): Failed to open database '/data/data/com.lge.email/databases/Downloads.db'.
E/SQLiteDatabase( 7490): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7490): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7490): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7490): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7490): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7490): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7490): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7490): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7490): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7490): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7490): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7490): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7490): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7490): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(,SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7490): 	at com.lge.email.ui.largefile.DownloadProvider.onCreate(DownloadProvider.java:51)
E/SQLiteDatabase( 7490): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
E/SQLiteDatabase( 7490): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
E/SQLiteDatabase( 7490): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
E/SQLiteDatabase( 7490): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
E/SQLiteDatabase( 7490): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
E/SQLiteDatabase( 7490): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
E/SQLiteDatabase( 7490): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
E/SQLiteDatabase( 7490): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7490): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 7490): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
E/SQLiteDatabase( 7490): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 7490): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 7490): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
E/SQLiteDatabase( 7490): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
W/System.err( 7490): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 7490): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 7490): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
W/System.err( 7490): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
W/System.err( 7490): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/System.err( 7490): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/System.err( 7490): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/System.err( 7490): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
W/System.err( 7490): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
W/System.err( 7490): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
W/System.err( 7490): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
W/System.err( 7490): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
W/System.err( 7490): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
W/System.err( 7490): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
W/System.err( 7490): 	at com.lge.email.ui.largefile.DownloadProvider.onCreate(DownloadProvider.java:51)
W/System.err( 7490): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
W/System.err( 7490): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
W/System.err( 7490): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
W/System.err( 7490): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
W/System.err( 7490): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
W/System.err( 7490): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
W/System.err( 7490): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
W/System.err( 7490): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7490): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7490): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 7490): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7490): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7490): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 7490): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/SQLiteDatabase( 7490): Failed to open database '/data/data/com.lge.email/databases/sqt.db'.
E/SQLiteDatabase( 7490): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7490): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7490): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7490): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7490): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7490): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7490): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7490): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7490): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7490): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7490): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7490): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7490): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7490): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7490): 	at com.lge.email.providers.sqt.SqtProvider.onCreate(SqtProvider.java:155)
E/SQLiteDatabase( 7490): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
E/SQLiteDatabase( 7490): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
E/SQLiteDatabase( 7490): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
E/SQLiteDatabase( 7490): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
E/SQLiteDatabase( 7490): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
E/SQLiteDatabase( 7490): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
E/SQLiteDatabase( 7490): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
E/SQLiteDatabase( 7490): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7490): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 7490): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
E/SQLiteDatabase( 7490): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 7490): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 7490): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
E/SQLiteDatabase( 7490): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
D/AndroidRuntime( 7490): Shutting down VM
E/AndroidRuntime( 7490): FATAL EXCEPTION: main
E/AndroidRuntime( 7490): Process: com.lge.email, PID: 7490
E/AndroidRuntime( 7490): java.lang.RuntimeException: Unable to get provider com.lge.email.providers.sqt.SqtProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7490): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5017)
E/AndroidRuntime( 7490): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
E/AndroidRuntime( 7490): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
E/AndroidRuntime( 7490): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
E/AndroidRuntime( 7490): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
E/AndroidRuntime( 7490): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7490): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 7490): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
E/AndroidRuntime( 7490): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 7490): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 7490): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
E/AndroidRuntime( 7490): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/AndroidRuntime( 7490): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7490): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7490): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 7490): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 7490): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 7490): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 7490): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 7490): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/AndroidRuntime( 7490): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/AndroidRuntime( 7490): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/AndroidRuntime( 7490): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/AndroidRuntime( 7490): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 7490): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 7490): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 7490): 	at com.lge.email.providers.sqt.SqtProvider.onCreate(SqtProvider.java:155)
E/AndroidRuntime( 7490): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
E/AndroidRuntime( 7490): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
E/AndroidRuntime( 7490): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
E/AndroidRuntime( 7490): 	... 11 more
I/Process ( 7490): Sending signal. PID: 7490 SIG: 9
E/DropBoxManagerService( 1103): Can't write: system_app_crash
E/DropBoxManagerService( 1103): java.io.FileNotFoundException: /data/system/dropbox/drop110.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1103): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 1103): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 1103): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 1103): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1103): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 1103): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
E/DropBoxManagerService( 1103): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1103): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1103): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 1103): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 1103): 	... 5 more
,W/ContextImpl( 7453): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
E/SiteAdvisor( 7453): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Unable to copy asset file during initialization.
E/SiteAdvisor( 7453): java.io.FileNotFoundException: /data/data/com.wsandroid.suite.lge/files/sa_oem.txt: open failed: EROFS (Read-only file system)
E/SiteAdvisor( 7453): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/SiteAdvisor( 7453): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/SiteAdvisor( 7453): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/SiteAdvisor( 7453): 	at java.io.FileWriter.<init>(FileWriter.java:42)
E/SiteAdvisor( 7453): 	at com.mcafee.android.a.c.<init>(Unknown Source)
E/SiteAdvisor( 7453): 	at com.mcafee.android.a.c.<init>(Unknown Source)
E/SiteAdvisor( 7453): 	at com.mcafee.android.a.a.<init>(Unknown Source)
E/SiteAdvisor( 7453): 	at com.mcafee.android.a.a.a(Unknown Source)
E/SiteAdvisor( 7453): 	at com.mcafee.android.mmssuite.SAComponent.a(Unknown Source)
E/SiteAdvisor( 7453): 	at com.mcafee.c.b.b(Unknown Source)
E/SiteAdvisor( 7453): 	at com.mcafee.framework.b.a(Unknown Source)
E/SiteAdvisor( 7453): 	at com.mcafee.app.t.run(Unknown Source)
E/SiteAdvisor( 7453): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SiteAdvisor( 7453): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SiteAdvisor( 7453): 	at com.mcafee.d.f.run(Unknown Source)
E/SiteAdvisor( 7453): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SiteAdvisor( 7453): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SiteAdvisor( 7453): 	at java.lang.Thread.run(Thread.java:818)
E/SiteAdvisor( 7453): 	at com.mcafee.d.c.run(Unknown Source)
E/SiteAdvisor( 7453): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/SiteAdvisor( 7453): 	at libcore.io.Posix.open(Native Method)
E/SiteAdvisor( 7453): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/SiteAdvisor( 7453): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/SiteAdvisor( 7453): 	... 18 more
D/SiteAdvisor( 7453): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
D/SiteAdvisor( 7453): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
,D/SiteAdvisor( 7453): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
D/SiteAdvisor( 7453): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
D/SiteAdvisor( 7453): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
I/SiteAdvisor( 7453): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
D/SiteAdvisor( 7453): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
D/SiteAdvisor( 7453): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
E/SQLiteDatabase( 7453): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/csf_call_log'.
E/SQLiteDatabase( 7453): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7453): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7453): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7453): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 7453): 	at com.mcafee.utils.d.a.d(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.utils.d.a.<init>(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.csf.frame.e.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.csf.frame.l.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.csf.frame.r.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.csf.frame.s.b(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.csf.frame.FirewallFrame.c(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.csf.frame.FirewallFrame.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.csf.frame.y.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.csf.frame.r.a(Unknown Source)
E/SQLiteDatabase( 7453): 	at com.mcafee.csf.frame.s.run(Unknown Source)
E/SQLiteDatabase( 7453): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 7453): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 7453): 	at com.mcafee.d.e.dispatchMessage(Unknown Source)
E/SQLiteDatabase( 7453): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 7453): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteDatabase( 7453): 	at com.mcafee.csf.frame.q.run(Unknown Source)
E/SQLiteOpenHelper( 7453): Couldn't op,en csf_call_log for writing (will try read-only):
E/SQLiteOpenHelper( 7453): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7453): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7453): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 7453): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 7453): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 7453): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 7453): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 7453): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteOpenHelper( 7453): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteOpenHelper( 7453): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteOpenHelper( 7453): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteOpenHelper( 7453): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 7453): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 7453): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 7453): 	at com.mcafee.utils.d.a.d(Unknown Source)
E/SQLiteOpenHelper( 7453): 	at com.mcafee.utils.d.a.<init>(Unknown Source)
E/SQLiteOpenHelper( 7453): 	at com.mcafee.csf.frame.e.a(Unknown Source)
E/SQLiteOpenHelper( 7453): 	at com.mcafee.csf.frame.l.a(Unknown Source)
E/SQLiteOpenHelper( 7453): 	at com.mcafee.csf.frame.r.a(Unknown Source)
E/SQLiteOpenHelper( 7453): 	at com.mcafee.csf.frame.s.b(Unknown Source)
E/SQLiteOpenHelper( 7453): 	at com.mcafee.csf.frame.FirewallFrame.c(Unknown Source)
E/SQLiteOpenHelper( 7453): 	at com.mcafee.csf.frame.FirewallFrame.a(Unknown Source)
E/SQLiteOpenHelper( 7453): 	at com.mcafee.csf.frame.y.a(Unknown Source)
E/SQLiteOpenHelper( 7453): 	at com.mcafee.csf.frame.r.a(Unknown Source)
E/SQLiteOpenHelper( 7453): 	at com.mcafee.csf.frame.s.run(Unknown Source)
E/SQLiteOpenHelper( 7453): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteOpenHelper( 7453): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteOpenHelper( 7453): 	at com.mcafee.d.e.dispatchMessage(Unknown Source)
E/SQLiteOpenHelper( 7453): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteOpenHelper( 7453): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 7453): 	at com.mcafee.csf.frame.q.run(Unknown Source)
W/SQLiteOpenHelper( 7453): Opened csf_call_log in read-only mode
,I/ActivityManager( 1103): Process com.lge.email (pid 7490) has died

```
