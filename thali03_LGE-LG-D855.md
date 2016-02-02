#### Test 575312435db8e90_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
I/MusicWidget( 2699): mDelayedStopHandler : unbind
I/MusicBrowser( 2258): [MediaPlaybackService.java:2869:onUnbind()] oooooo 
I/MusicBrowser( 2258): [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2258): [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2258): [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2258): [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2258): [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2258): [MediaPlaybackService.java:2046:onDestroy()] oooooo 
I/MusicBrowser( 2258): [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
I/MediaFocusControl( 1029):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@28e324bbcom.lge.music.MediaPlaybackService$5@189cdd8
D/MusicBrowser( 2258): [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2258): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2258): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2258): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2258): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@b62e566
I/MusicBrowser( 2258): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2258): [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2258): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2258): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2258): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2258): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2258): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2258): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2258): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2258): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2258): [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2258): [MediaPlaybackService.java:6704:release()] oooooo 
I/MusicBrowser( 2258): [MediaPlaybackService.java:6665:stop()] oooooo 
V/MediaPlayer[Native]( 2258): reset
V/MediaPlayer[Native]( 2258): setListener
V/MediaPlayer[Native]( 2258): disconnect
V/MediaPlayer[Native]( 2258): destructor
V/AudioFlinger(  320): releasing 13 from 2258 for -1
V/AudioFlinger(  320):  decremented refcount to 0
V/AudioFlinger(  320): purging stale effects
V/MediaPlayer[Native]( 2258): disconnect
D/MusicBrowser( 2258): [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
I/SmartShareClient( 2258): [SmartShareManagerClient] smartshare client supported version code: 305000
I/SmartShareClient( 2258): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2258): [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
I/MusicBrowser( 2258): [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2258): [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2258): [SmartShareManagerClient] unregisterListener: 829728049
W/SmartShareClient( 2258): [SmartShareManagerClient] unregisterListener invalid listener: 829728049
I/SmartShareClient( 2258): [SmartShareManagerClient] terminate service: 2258/MediaPlaybackService/457449148
E/HomeCloudIF( 2258): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2258): [SmartShareManagerClient] unbindService context:android.app.Application@de57416
V/CloudHub( 2258): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
V/CloudHub( 2258): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2258): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
D/MusicBrowser( 2258): [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
--------- beginning of system
I/ActivityManager( 1029): Killing 5948:com.google.android.partnersetup/u0a8 (adj 15): empty #17
I/CloudHub( 2258): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29989
W/libprocessgroup( 1029): failed to open /acct/uid_10008/pid_5948/cgroup.procs: No such file or directory
,D/AndroidRuntime( 6195): 
D/AndroidRuntime( 6195): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6195): CheckJNI is OFF
D/AndroidRuntime( 6195): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1029): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1974): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1029): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1029): setTaskToReturnTo : TaskRecord{11034ae3 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1029): setTaskToReturnTo : TaskRecord{11034ae3 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1029): AppWindowTokenEx init.. 
E/GBMv2   (  341): DFP En is all cleared set to be enabled
I/ActivityManager( 1029): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6215 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6195): Shutting down VM
V/ActivityManager( 1029): Display changed displayId=0
D/DSDPConnection( 1866): Display #0 changed.
D/SplitWindowPolicy( 1974): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1974): topRunningActivity=ActivityInfo{3dc8d3e3 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1974): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1974): topRunningActivity=ActivityInfo{3a391e0 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 6215): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/WebViewFactory( 6215): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
I/LibraryLoader( 6215): Loading: webviewchromium
I/LibraryLoader( 6215): Time to load native libraries: 3 ms (timestamps 7469-7472)
I/LibraryLoader( 6215): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6215): Binding Chromium to main looper Looper (main, tid 1) {1b441ebc}
I/LibraryLoader( 6215): Expected native library version number "",actual native library version number ""
I/chromium( 6215): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6215): Initializing chromium process, renderers=0
W/art     ( 6215): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6215): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,V/AudioPolicyService(  320): registerClient() client 0xb14fd880, uid 10311
,W/chromium( 6215): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6215): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 6215): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
D/BluetoothManagerService( 1029): Message: 20
D/BluetoothManagerService( 1029): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@20da1855:true
D/BluetoothAdapter( 6215): 516329029: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 6215): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6215): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6215): Build Date: 12/12/14 금
I/Adreno-EGL( 6215): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6215): Remote Branch: 
I/Adreno-EGL( 6215): Local Patches: 
I/Adreno-EGL( 6215): Reconstruct Branch: 
,W/chromium( 6215): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 6215): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 6215): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6215): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6215): CordovaWebView is running on device made by: LGE
,W/art     ( 6215): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6215): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6215): Render dirty regions requested: true
I/OpenGLRenderer( 6215): Initialized EGL, version 1.4
D/OpenGLRenderer( 6215): Enabling debug mode 0
,D/Atlas   ( 6215): Validating map...
,D/SplitWindow( 1029): check instance of lgWin Window{186b8f27 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/LgDataFeature( 6215): LgDataFeature() Constructor: none
D/LgDataFeature( 6215): LgDataFeature() Constructor Done, null
,I/SystemUI[Framework]( 1029): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
,W/PhoneWindowManagerEx( 1029): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1029): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1029): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1029): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@eed5435,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1029): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/PhoneStatusBar( 1472): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1472): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1472):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1472): , Keyguard show=false, IME shown=false, Panel expanded=false
I/ActivityManager( 1029): Displayed com.test.thalitest/.MainActivity: +613ms (total +680ms)
I/Timeline( 1029): Timeline: Activity_windows_visible id: ActivityRecord{dca3ce0 u0 com.test.thalitest/.MainActivity t4} time:107950
I/Timeline( 6215): Timeline: Activity_idle id: android.os.BinderProxy@1c0092b5 time:107951
,I/chromium( 6215): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6215): 
,D/JsMessageQueue( 6215): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium( 6215): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 6215): 
,D/jxcore_app_log( 6215): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435211392
,I/chromium( 6215): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/GBMv2   (  341): DFP En is all cleared set to be enabled
E/GBMv2   (  341): Set value is all cleared set the max
I/GBMv2   (  341): DFP Enabled. Ignore VFP set
,W/jxcore-log( 6215): Initializing JXcore engine
W/jxcore-log( 6215): JXcore engine is ready
,W/Thread-724( 6278): type=1400 audit(0.0:148): avc: denied { ioctl } for path="socket:[7400]" dev="sockfs" ino=7400 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-724( 6278): type=1400 audit(0.0:149): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-724( 6278): type=1400 audit(0.0:150): avc: denied { ioctl } for path="socket:[9832]" dev="sockfs" ino=9832 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/Thread-724( 6278): type=1400 audit(0.0:151): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/Thread-724( 6278): type=1400 audit(0.0:152): avc: denied { ioctl } for path="socket:[29594]" dev="sockfs" ino=29594 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
W/jxcore-log( 6215): Starting JXcore engine
,W/jxcore-log( 6215): Platform android
W/jxcore-log( 6215): 
W/jxcore-log( 6215): Process ARCH arm
W/jxcore-log( 6215): 
,I/jxcore-log( 6215): JXcore Cordova bridge is ready!
I/jxcore-log( 6215): 
W/jxcore-log( 6215): JXcore engine is started
,I/jxcore-log( 6215): Toggling radios to true
I/jxcore-log( 6215): 
,D/BluetoothManagerService( 1029): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1029): enable():  mBluetooth =null mBinding = false
D/BluetoothManagerService( 1029): Message: 1
D/BluetoothManagerService( 1029): MESSAGE_ENABLE: mBluetooth = null
,D/LocationManagerService( 1029): getAllProviders()=[passive, gps, network]
D/WifiService( 1029): New client listening to asynchronous messages
D/Ulp_jni ( 1029): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1029): JNI:system_update. Event-4
I/ActivityManager( 1029): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=6281 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
D/WifiServiceImplEx( 1029): setWifiEnabled: true pid=6215, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1029): setWifiEnabled: true pid=6215, uid=10311
E/WifiService( 1029): Invoking mWifiStateMachine.setWifiEnabled
,D/LocationManagerService( 1029): getAllProviders()=[passive, gps, network]
E/WifiStateMachine( 1029):  InitialState CMD_START_SUPPLICANT 0 0
I/LGFTMITEM( 1029): [GET_FTM][id=6], offset=12288
D/Ulp_jni ( 1029): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1029): JNI:system_update. Event-4
E/WifiUtil( 1029): wfc_util_ffile_check_copy(): pid[1029] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
E/WifiUtil( 1029): wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
E/WifiUtil( 1029): wfc_util_ffile_check_copy(): pid[1029] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
E/WifiUtil( 1029): wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
I/WifiUtil( 1029): Intf0MacAddress=C49A027B60AC
E/WifiHW  ( 1029): unknown target_country: EU , set to default
E/WifiHW  ( 1029): [wifi_ensure_config_files] default country1 = GB
E/WifiHW  ( 1029): [wifi_ensure_config_files] default country2 = GB
I/WifiUtil( 1029): gEnableBmps=1
D/WifiServiceImplEx( 1029): disconnect pid=6215, uid=10311, packageName=com.test.thalitest
D/WifiServiceImplEx( 1029): reconnect pid=6215, uid=10311, packageName=com.test.thalitest
I/jxcore-log( 6215): Radios toggled
I/jxcore-log( 6215): 
I/jxcore-log( 6215): My device name is: LGE-LG-D855
I/jxcore-log( 6215): 
,W/ResourcesManager( 6281): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager( 6281): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6281): Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 6281): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/BluetoothAdapterApp( 6281): Loading JNI Library
,D/Tethering( 1029): sendTetherStateChangedBroadcast 1, 0, 0
,D/SoftapController(  315): Softap fwReload - Ok
D/CommandListener(  315): Setting iface cfg
D/Tethering( 1029): InitialState.processMessage what=4
D/CommandListener(  315): Trying to bring down wlan0
D/CommandListener(  315): Clearing all IP addresses on wlan0
D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1029): DNSproblemNotiEnabled is disabled ignore DNS fail CB
E/WifiHW  ( 1029): Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,E/WifiStateMachine( 1029): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1029): useWiFiOffloading() : false
E/WifiStateMachine( 1029): CONFIG_LGE_WLAN_PATH : true
W/wpa_supplicant( 6313): type=1400 audit(0.0:153): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/wpa_supplicant( 6313): type=1400 audit(0.0:154): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,I/wpa_supplicant( 6313): Successfully initialized wpa_supplicant
,I/ActivityManager( 1029): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=6314 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/Tethering( 1029): sendTetherStateChangedBroadcast 0, 0, 0
,I/wpa_supplicant( 6313): rfkill: Cannot open RFKILL control device
I/wpa_supplicant( 6313): [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
D/WifiMonitor( 1029): startMonitoring(wlan0) with mConnected = false
I/art     (  355): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 293us total 16.568ms
D/WifiMonitor( 1029): connecting to supplicant
D/BluetoothAdapterApp( 6281): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@15a0f990 Instance Count = 1
,V/WfdStateTracker( 1974): WfdStateTracker handleDirectStateChangedEvent: 1
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
I/WifiServerServiceExt( 1029): WIFI_STATE_CHANGED_ACTION [2]
I/art     (  355): Explicit concurrent mark sweep GC freed 8(256B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 289us total 13.071ms
D/BluetoothAdapterApp( 6281): onCreate
I/art     (  355): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 259us total 12.381ms
,D/ProfileConfigQcom( 6281): [BTUI] HeadsetService is supported
D/ProfileConfigQcom( 6281): Adding HeadsetService
D/ProfileConfigQcom( 6281): [BTUI] A2dpService is supported
D/ProfileConfigQcom( 6281): Adding A2dpService
D/ProfileConfigQcom( 6281): [BTUI] HidService is supported
D/ProfileConfigQcom( 6281): Adding HidService
D/ProfileConfigQcom( 6281): [BTUI] HealthService is supported
D/ProfileConfigQcom( 6281): Adding HealthService
D/LGBluetoothFeatureConfig( 6281): isSupportPan() :  mTargetOp=OPEN
D/ProfileConfigQcom( 6281): [BTUI] PanService is supported
D/ProfileConfigQcom( 6281): Adding PanService
D/ProfileConfigQcom( 6281): [BTUI] GattService is supported
D/ProfileConfigQcom( 6281): Adding GattService
D/ProfileConfigQcom( 6281): [BTUI] BluetoothMapService is supported
D/ProfileConfigQcom( 6281): Adding BluetoothMapService
D/ProfileConfigQcom( 6281): [BTUI] HeadsetClientService is NOT supported
,W/ResourcesManager( 6314): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6314): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6314): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6314): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 6314): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6314): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/BluetoothManagerService( 1029): Message: 20
D/BluetoothManagerService( 1029): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@30549c96:true
D/BluetoothAdapterState( 6281): make
I/LGFMServiceAdapter( 6281): [FM] LGFMServiceAdapter : create
I/bluedroid-qcom( 6281): init
I/BluetoothAdapterState( 6281): Entering OffState
I/bte_conf( 6281): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 6281): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 6281): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 6281): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
D/BTIF_CORE( 6281): [BTUI] lge_load_bluetooth_address
I/bluedroid-qcom( 6281): get_profile_interface socket
W/bdaddr_loader( 6342): type=1400 audit(0.0:155): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/bluedroid-qcom( 6281): get_profile_interface map_client
I/GKI_LINUX( 6281): gki_task_entry task_id=1 [BTIF] starting
W/bdaddr_loader( 6342): type=1400 audit(0.0:156): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/BluetoothManagerService( 1029): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService( 1029): Message: 40
D/BluetoothManagerService( 1029): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
D/BluetoothAdapterProperties( 6281): Address is:58:3F:54:73:64:C0
I/wpa_supplicant( 6313): rfkill: Cannot open RFKILL control device
,D/BluetoothAdapterProperties( 6281): Name is: G3-1
D/lge_bdaddr_loader( 6342): [BTUI] bdaddr_loader ::: START
D/lge_bdaddr_loader( 6342): [BTUI] bluetooth_load_bdaddress
I/LGFTMITEM( 6342): [GET_FTM][id=8], offset=16384
D/lge_bdaddr_loader( 6342): [BTUI] bdaddr to set in property : 58:3F:54:73:64:C0
D/BluetoothManagerService( 1029): Bluetooth Adapter name changed to G3-1
D/BluetoothManagerService( 1029): Stored Bluetooth name: G3-1
I/bluedroid-qcom( 6281): config_hci_snoop_log
D/BluetoothManagerService( 1029): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService( 1029): Broadcasting onBluetoothServiceUp() to 7 receivers.
E/lge_bdaddr_loader( 6342): [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:64:C0
D/lge_bdaddr_loader( 6342): [BTUI] bdaddr_loader ::: END
V/LGMDMManagerInternal( 6281): Create singleton instance
,D/BluetoothAdapterState( 6281): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,D/BluetoothAdapterProperties( 6281): Setting state to 11
I/BluetoothAdapterState( 6281): Bluetooth adapter state changed: 10-> 11
D/BluetoothManagerService( 1029): Message: 60
D/BluetoothManagerService( 1029): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
I/LGBluetoothServiceJni( 6281): classInitNative: succeeds
D/BluetoothManagerService( 1029): Bluetooth State Change Intent: 10 -> 11
D/LGBluetoothAPIService( 1974): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
I/[SystemUI]BluetoothHandler( 1472): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
D/BluetoothBondStateMachine( 6281): make
D/UsbSettingsReceiver( 6314): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6314): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6314): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6314): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6314): [AUTORUN] onReceive() : app userid = 0, current userid = 0
I/wpa_supplicant( 6313): [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,D/BluetoothAdapterService( 6281): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@368bf2cb
D/LGBluetoothServiceAdapter( 6281): [BTUI] check adapter is available - false.
I/BluetoothBondStateMachine( 6281): StableState(): Entering Off State
I/wpa_supplicant( 6313): p2p0: CTRL-EVENT-AVOID-FREQ ranges=
D/BluetoothAdapterService( 6281): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@368bf2cb
D/LGBluetoothServiceAdapter( 6281): [BTUI] check adapter is available - true : set adapter available.
I/wpa_supplicant( 6313): wlan0: CTRL-EVENT-SCAN-STARTED 
D/LGBluetoothSettingsDBObserver( 6281): [BTUI] register observer for LG device name DB
D/UsbSettingsControl( 6314): [AUTORUN] getUsbConnected() : connected=true
E/WifiStateMachine( 1029):  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
D/UsbSettingsReceiver( 6314): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6314): [AUTORUN] onReceive() : activeList=[]
,D/UsbSettingsReceiver( 6314): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6314): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6314): [AUTORUN] onReceive() : TetherState Changed=wlan0
E/WifiStateMachine( 1029):  SupplicantStartingState CMD_START_DRIVER 0 0
E/WifiStateMachine( 1029):  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
D/UsbSettingsControl( 6314): [AUTORUN] setTetherStatus() : status=false
E/WifiStateMachine( 1029):  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
E/WifiStateMachine( 1029):  SupplicantStartingState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1029):  DefaultState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1029):  SupplicantStartingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1029):  DefaultState CMD_RECONNECT 0 0
E/WifiStateMachine( 1029):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
I/ActivityManager( 1029): Killing 5588:com.lge.appbox.client/u0a11 (adj 15): empty #17
E/WifiStateMachine( 1029):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1029):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1029):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1029):  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
D/WifiMonitor( 1029): Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
D/WifiMonitor( 1029): Dropping event because (p2p0) is stopped
D/WifiMonitor( 1029): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=0 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1029): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1029): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-wlan0( 1029): doString: [DRIVER MACADDR]
D/WifiNative-wlan0( 1029):    returned Macaddr = c4:9a:02:7b:60:ac
D/WifiStateMachine( 1029): MAC Addr from driver = c4:9a:02:7b:60:ac
D/WifiOffDelayIfNotUsed( 1029): setPowerSaveActivated(false)
E/BluetoothAdapterService( 6281): File transfer profiles supported!!
,E/WifiStateMachine( 1029): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1029): useWiFiOffloading() : false
E/WifiStateMachine( 1029): CONFIG_LGE_WLAN_PATH : true
,V/BluetoothPbapReceiver( 6281): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 6281): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6281): ***********state = 11
W/libprocessgroup( 1029): failed to open /acct/uid_10011/pid_5588/cgroup.procs: No such file or directory
D/WifiNative-wlan0( 1029): doBoolean: SET update_config 1
W/Settings( 1029): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1029): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetService( 6281): Received start request. Starting profile...
D/WfdService( 1974): Waiting for WifiP2p enabling
I/LGBluetoothHeadsetServiceJni( 6281): classInitNative: succeeds
D/LGBluetoothHfpAdapter( 6281): Version 1.6
D/BluetoothHeadset( 1866): Proxy object connected
I/WifiServerServiceExt( 1029): WIFI_STATE_CHANGED_ACTION [3]
D/BluetoothHeadset( 1866): Proxy object connected
D/BluetoothHeadset( 1866): Proxy object connected
D/LGBluetoothFeatureConfig( 6281): isPrivacyLogsEnabled : true
I/BluetoothHeadsetServiceJni( 6281): classInitNative: succeeds
D/WifiNative-wlan0( 1029): SET update_config 1: returned true
D/WifiConfigStore( 1029): Loading config and enabling all networks 
E/BluetoothAdapterService( 6281): File transfer profiles supported!!
D/HeadsetStateMachine( 6281): make
D/WifiNative-wlan0( 1029): doString: [LIST_NETWORKS]
D/WifiNative-wlan0( 1029):    returned network id / ssid / bssid / flags 0	NG700	any	
I/WifiServerServiceExt( 1029): batteryPsActivateMsgHandler : state:0 event:3
,D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiConfigStore( 1029): readNetworkVariablesFromSupplicantFile key=psk
E/WifiConfigStore( 1029): readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
E/WifiConfigStore( 1029): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
D/UsbSettingsReceiver( 6314): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6314): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6314): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6314): [AUTORUN] persist.sys.usb.config = ptp_only,adb
,I/ActivityManager( 1029): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6347 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
D/WifiStateMachine( 1029): enableVerboseLogging : level 2
D/WifiNative-wlan0( 1029): doBoolean: SET device_name g3_global_com
D/UsbSettingsReceiver( 6314): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/LgDataFeature( 6281): LgDataFeature() Constructor: none
D/LgDataFeature( 6281): LgDataFeature() Constructor Done, null
D/WifiNative-wlan0( 1029): SET device_name g3_global_com: returned true
D/WifiNative-wlan0( 1029): doBoolean: SET manufacturer LGE
D/WifiNative-wlan0( 1029): SET manufacturer LGE: returned true
D/WifiNative-wlan0( 1029): doBoolean: SET model_name LG-D855
D/WifiNative-wlan0( 1029): SET model_name LG-D855: returned true
D/WifiNative-wlan0( 1029): doBoolean: SET model_number LG-D855
E/BluetoothAdapterService( 6281): File transfer profiles supported!!
D/WifiNative-wlan0( 1029): SET model_number LG-D855: returned true
D/WifiNative-wlan0( 1029): doBoolean: SET serial_number LGD8553bed2d08
D/WifiNative-wlan0( 1029): SET serial_number LGD8553bed2d08: returned true
D/WifiNative-wlan0( 1029): doBoolean: SET config_methods physical_display virtual_push_button
D/WifiNative-wlan0( 1029): SET config_methods physical_display virtual_push_button: returned true
D/WifiNative-wlan0( 1029): doBoolean: SET device_type 10-0050F204-5
D/WifiNative-wlan0( 1029): SET device_type 10-0050F204-5: returned true
D/WfdsService( 1974): Supplicant Connection state is changed : true
D/WfdsService( 1974): DefaultState - WIFI_SUPPLICANT_CONNECTED
D/WfdsService( 1974): Set the WFDS Monitor: true
D/WifiStateMachine( 1029): Setting OUI to DA-A1-19
D/WifiNative-wlan0( 1029): doBoolean: SCAN_INTERVAL 120
D/HeadsetStateMachine( 6281): max_hf_connections = 1
I/bluedroid-qcom( 6281): get_profile_interface handsfree
D/WfdsMonitor( 1974): WfdsMonitorThread create
D/WfdsMonitor( 1974): WFDS Monitor is created and started
D/WfdsService( 1974): WiFi: Supplicant connection re-established
D/WifiNative-wlan0( 1029): SCAN_INTERVAL 120: returned true
D/WifiNative-HAL( 1029): Setting external_sim to 1
,D/WifiNative-wlan0( 1029): doBoolean: SET external_sim 1
V/ToneGenerator( 6281): ToneGenerator constructor: streamType=8, volume=1.000000
V/AudioPolicyService(  320): registerClient() client 0xb148ff60, uid 1002
E/BluetoothAdapterService( 6281): File transfer profiles supported!!
V/AudioPolicyManager(  320): getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  320): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  320): getOutput() returns output 2
D/WifiNative-wlan0( 1029): SET external_sim 1: returned true
V/AudioSystem( 6281): getOutputSamplingRate() no output descriptor for output 2 in gOutputs
I/WifiNative-HAL( 1029): startHal
E/wifi    ( 1029): getStaticLongField sWifiHalHandle 0x989278dc
E/WifiHAL ( 1029): Could not connect handle
V/AudioFlinger(  320): registerClient() client 0xb5581880, pid 6281
D/wifi    ( 1029): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x6019da
I/WifiNative-HAL( 1029): Could not start hal
D/WifiStateMachine( 1029): Setting OUI to DA-A1-19
I/WifiNative-HAL( 1029): startHal
E/wifi    ( 1029): getStaticLongField sWifiHalHandle 0x9892785c
E/WifiHAL ( 1029): Could not connect handle
V/AudioSystem(  320): ioConfigChanged() event 0, ioHandle 2
D/wifi    ( 1029): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x5019c2
V/AudioSystem(  320): ioConfigChanged() opening already existing output! 2
I/WifiNative-HAL( 1029): Could not start hal
D/WifiNative-wlan0( 1029): doBoolean: STA_AUTOCONNECT 1
V/AudioSystem( 1029): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1029): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 3301): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 3301): ioConfigChanged() opening already existing output! 2
D/WifiNative-wlan0( 1029): STA_AUTOCONNECT 1: returned true
V/AudioSystem(  320): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem(  320): ioConfigChanged() opening already existing output! 4
V/ToneGenerator( 6281): Create Track: 0xb4928080
V/AudioSystem( 6281): ioConfigChanged() event 0, ioHandle 2
V/AudioTrack( 6281): set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
V/AudioSystem( 6281): ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
V/AudioTrack( 6281): set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
V/AudioSystem( 1029): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1029): ioConfigChanged() opening already existing output! 4
V/AudioPolicyManager(  320): getOutputForAttr() usage=3, content=4, tag= flags=00000000
V/AudioPolicyManager(  320): getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioSystem( 6281): ioConfigChanged() event 0, ioHandle 4
V/AudioPolicyManagerEx(  320): AudioPolicyManagerEx: getOutputForDevice
V/AudioSystem( 6281): ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
V/AudioPolicyManagerEx(  320): getOutput() returns output 2
I/AudioFlinger(  320): isAudioPlaybackHookOn() false
V/AudioPolicyManager(  320): getOutputForAttr() usage=3, content=4, tag= flags=00000000
V/AudioPolicyManager(  320): getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
V/AudioPolicyManagerEx(  320): AudioPolicyManagerEx: getOutputForDevice
V/AudioSystem( 1472): ioConfigChanged() event 0, ioHandle 2
V/AudioPolicyManagerEx(  320): getOutput() returns output 2
V/AudioSystem( 1472): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1472): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 6281): getLatency() output 2, latency 50
V/AudioSystem( 6281): getFrameCount() output 2, frameCount 960
V/AudioSystem( 1472): ioConfigChanged() opening already existing output! 4
V/AudioTrack( 6281): createTrack_l() output 2 afLatency 50
V/AudioSystem( 2258): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 2258): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 2258): ioConfigChanged() event 0, ioHandle 4
V/AudioFlinger(  320): [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
V/AudioSystem( 2258): ioConfigChanged() opening already existing output! 4
V/AudioFlinger(  320): [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
V/AudioFlinger(  320): [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
V/AudioFlinger(  320): [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
V/AudioFlinger(  320): createTrack() lSessionId: 16
V/AudioSystem( 3301): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 3301): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1866): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1866): ioConfigChanged() opening already existing output! 2
D/WifiNative-wlan0( 1029): doBoolean: DRIVER BTCOEXSCAN-STOP
I/wpa_supplicant( 6313): wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
V/AudioSystem( 1866): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1866): ioConfigChanged() opening already existing output! 4
V/AudioTrack( 6281): AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
D/WifiNative-wlan0( 1029): DRIVER BTCOEXSCAN-STOP: returned true
V/AudioFlinger(  320): acquiring 16 from 6281, for 6281
V/AudioFlinger(  320):  added new entry for 16
V/ToneGenerator( 6281): ToneGenerator INIT OK, time: 110807
D/BluetoothAdapterService( 6281): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@368bf2cb
D/HeadsetStateMachine( 6281): Enter Disconnected: -2, size: 0
D/HeadsetPhoneState( 6281): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 6281): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetStateMachine( 6281): [BTUI] change sampling rate to 8000 when device is disconnected
V/AudioFlinger(  320): setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6281
D/audio_hw_primary(  320): adev_set_parameters: enter: bt_samplerate=8000
V/voice   (  320): voice_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  320): voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  320): voice_extn_compress_voip_set_parameters: exit
V/voice   (  320): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  320): LGE_platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  320): platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  320): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  320): lge_platform_set_loopback_parameters: enter: 
V/audio_hw_primary(  320): adev_set_parameters: exit with code(0)
E/audio_a2dp_hw(  320): adev_set_parameters: ERROR: set param called even when stream out is null
V/ToneGenerator( 6281): ToneGenerator destructor
V/ToneGenerator( 6281): stopTone
V/ToneGenerator( 6281): Delete Track: 0xb4928080
D/BluetoothAdapterService( 6281): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@368bf2cb
D/WifiNative-wlan0( 1029): doBoolean: DRIVER RXFILTER-STOP
W/Process ( 1029): Unable to open /proc/6357/status
I/wpa_supplicant( 6313): wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
V/AudioTrack( 6281): ~AudioTrack, releasing session id from 6281 on behalf of 6281
V/AudioFlinger(  320): releasing 16 from 6281 for 6281
V/AudioFlinger(  320):  decremented refcount to 0
V/AudioFlinger(  320): purging stale effects
V/AudioPolicyService(  320): AudioCommandThread() adding release output 2
V/AudioPolicyService(  320): inserting command: 6 at index 0, num commands 0
V/AudioPolicyService(  320): AudioCommandThread() waking up
V/AudioPolicyService(  320): AudioCommandThread() processing release output 2
V/AudioPolicyManager(  320): releaseOutput() 2
V/AudioPolicyService(  320): AudioCommandThread() going to sleep
V/AudioFlinger(  320): PlaybackThread::Track destructor
V/AudioFlinger(  320): removeClient_l() pid 6281, calling pid 320
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
D/A2dpService( 6281): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 6281): classInitNative: succeeds
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
V/Avrcp   ( 6281): make
D/Avrcp   ( 6281): [BTUI] Use Native AVRCP : init jni
I/bluedroid-qcom( 6281): get_profile_interface avrcp
E/BluetoothAdapterService( 6281): File transfer profiles supported!!
D/WifiNative-wlan0( 1029): DRIVER RXFILTER-STOP: returned true
D/WifiNative-wlan0( 1029): doBoolean: DRIVER RXFILTER-REMOVE 3
I/wpa_supplicant( 6313): wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
D/WifiNative-wlan0( 1029): DRIVER RXFILTER-REMOVE 3: returned true
D/WifiNative-wlan0( 1029): doBoolean: DRIVER RXFILTER-START
I/wpa_supplicant( 6313): wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
D/WifiNative-wlan0( 1029): DRIVER RXFILTER-START: returned true
D/WifiNative-wlan0( 1029): doBoolean: DRIVER RXFILTER-STOP
I/wpa_supplicant( 6313): wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
D/WifiNative-wlan0( 1029): DRIVER RXFILTER-STOP: returned true
D/WifiNative-wlan0( 1029): doBoolean: DRIVER RXFILTER-REMOVE 2
I/wpa_supplicant( 6313): android_multicast_filter_startstop : multicast filter set
D/WifiNative-wlan0( 1029): DRIVER RXFILTER-REMOVE 2: returned true
D/WifiNative-wlan0( 1029): doBoolean: DRIVER RXFILTER-START
I/wpa_supplicant( 6313): wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
D/WifiNative-wlan0( 1029): DRIVER RXFILTER-START: returned true
E/WifiNative: ( 1029): [110,809,109 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
D/WifiNative-wlan0( 1029): doBoolean: RECONNECT
D/WifiNative-wlan0( 1029): RECONNECT: returned true
D/WifiNative-wlan0( 1029): doString: [STATUS]
D/WifiMonitor( 1029): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=1 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
E/BluetoothAdapterService( 6281): File transfer profiles supported!!
D/WifiNative-wlan0( 1029):    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
D/WifiNative-wlan0( 1029): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 6313): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1029): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1029): doBoolean: SET ps 1
D/WifiNative-wlan0( 1029): SET ps 1: returned true
D/LGWifiP2pService( 1029): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
E/CtrlSupplicant( 1974): Access OK "@android:wpa_wlan0"
E/CtrlSupplicant( 1974): Succeed to open control connection
E/CtrlSupplicant( 1974): Succeed to open monitor connection
D/CommandListener(  315): Setting iface cfg
D/CommandListener(  315): Trying to bring up p2p0
D/WifiMonitor( 1029): startMonitoring(p2p0) with mConnected = true
D/LGWifiP2pService( 1029): P2pEnablingState
D/LGWifiP2pService( 1029): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): P2p socket connection successful
D/LGWifiP2pService( 1029): P2pEnabledState
D/LGWifiP2pService( 1029): sending p2p connection changed broadcast
V/AudioManager( 6281): registerRemoteController: size of Media player list: 0
D/WfdsMonitor( 1974): Supplicant connection established
V/WfdStateTracker( 1974): WfdStateTracker handleDirectStateChangedEvent: 2
D/WfdsService( 1974): WifiP2pState is changed : true
D/WifiService( 1029): New client listening to asynchronous messages
D/WifiNative-p2p0( 1029): doBoolean: SET persistent_reconnect 1
D/WifiNative-p2p0( 1029): SET persistent_reconnect 1: returned true
D/WifiNative-p2p0( 1029): doBoolean: SET device_name G3-1
E/WifiStateMachine( 1029):  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
D/WifiNative-p2p0( 1029): SET device_name G3-1: returned true
D/WfdsService( 1974): Connected to the supplicant for wfds
D/LGWifiP2pService( 1029): [LGE_P2P] initializeP2pSettings() check postfix
D/WfdsJNI ( 1974): doCommand: WFDS_SET TRUE
D/LGWifiP2pService( 1029): before postfix = G3-1
I/wpa_supplicant( 6313): WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
D/WifiServerServiceExt( 1029): postfix byte check : 4
D/LGWifiP2pService( 1029): after postfix = G3-1
D/WifiNative-p2p0( 1029): doBoolean: SET p2p_ssid_postfix -G3-1
D/WifiNative-p2p0( 1029): SET p2p_ssid_postfix -G3-1: returned true
D/WfdsJNI ( 1974): doCommand: WFDS_GET_MAC_ADDRESS
D/WifiNative-p2p0( 1029): doBoolean: SET device_type 10-0050F204-5
I/wpa_supplicant( 6313): WFDS: wfds_supplicant_wfds_cmd: cmd = GET_MAC_ADDRESS
D/WifiNative-p2p0( 1029): SET device_type 10-0050F204-5: returned true
D/WifiNative-p2p0( 1029): doBoolean: SET config_methods virtual_push_button physical_display keypad
E/AudioManager( 6281): No RCC entry present to update
E/RemoteController( 6281): Cannot set synchronization mode on an unregistered RemoteController
E/WifiStateMachine( 1029):  DisconnectedState CMD_START_DRIVER 0 0
D/WfdsJNI ( 1974): doCommand: IFNAME=wlan0 GET_CAPABILITY channels
D/WifiNative-p2p0( 1029): SET config_methods virtual_push_button physical_display keypad: returned true
D/WifiNative-p2p0( 1029): doBoolean: P2P_SET conc_pref p2p
D/WfdsService( 1974): selectPreferredScanChannel [36]
D/WfdsService( 1974): STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7b:60:ac
E/WifiStateMachine( 1029):  ConnectModeState CMD_START_DRIVER 0 0
D/WfdsService( 1974): DefaultState - WFDS_ENABLE(DISABLE)
E/WifiStateMachine( 1029):  DriverStartedState CMD_START_DRIVER 0 0
E/WifiStateMachine( 1029):  DisconnectedState what:132106 1 0
E/WifiStateMachine( 1029):  ConnectModeState what:132106 1 0
E/WifiStateMachine( 1029):  DriverStartedState what:132106 1 0
I/WifiServerServiceExt( 1029): setWifiDualbandAPConnection band : 1
I/BluetoothAvrcpQcomServiceJni( 6281): classInitQcomNative: succeeds
E/wpa_supplicant( 6313): nWIFIDualbandAPConnection: 1
E/WifiStateMachine( 1029):  DisconnectedState what:132096 -100 0
E/WifiStateMachine( 1029):  ConnectModeState what:132096 -100 0
D/LGBluetoothAvrcpQcomAdapter( 6281): [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
I/BluetoothAvrcpQcomServiceJni( 6281): initQcomNative: succeeds
E/WifiStateMachine( 1029):  DriverStartedState what:132096 -100 0
I/WifiServerServiceExt( 1029): set CMD_DISCONNECT_RSSI_LVL : -100
,D/WifiNative-p2p0( 1029): P2P_SET conc_pref p2p: returned true
D/WifiNative-HAL( 1029): p2pGetDeviceAddress
E/wpa_supplicant( 6313): disconnect_rssi_lvl: -100
E/WifiStateMachine( 1029):  DisconnectedState CMD_SET_COUNTRY_CODE 1 0 cz
E/WifiStateMachine( 1029):  ConnectModeState CMD_SET_COUNTRY_CODE 1 0 cz
E/WifiStateMachine( 1029):  DriverStartedState CMD_SET_COUNTRY_CODE 1 0 cz
D/WifiNative-wlan0( 1029): doBoolean: DRIVER COUNTRY CZ
D/WifiNative-HAL( 1029): p2pGetDeviceAddress returning 
W/Settings( 6138): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/wpa_supplicant( 6313): wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
I/wpa_supplicant( 6313): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
D/WifiMonitor( 1029): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=2 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1029): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1029): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
I/wpa_supplicant( 6313): [LGE_PATCH] driver_cmd() country:CZ
I/wpa_supplicant( 6313): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiNative-wlan0( 1029): DRIVER COUNTRY CZ: returned true
E/WifiStateMachine( 1029):  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
I/wpa_supplicant( 6313): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiStateMachine( 1029):  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine( 1029):  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
D/WifiNative-wlan0( 1029): doBoolean: DRIVER SETBAND 0
I/wpa_supplicant( 6313): wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
I/wpa_supplicant( 6313): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
D/WfdsMonitor( 1974): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WifiMonitor( 1029): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1029): WifiMonitor:p2p0 cnt=3 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WfdsMonitor( 1974): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1029): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1029): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiMonitor( 1029): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1029): WifiMonitor:p2p0 cnt=4 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1029): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1029): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiMonitor( 1029): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=5 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
E/WifiMonitor( 1029): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
E/WifiMonitor( 1029): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
D/WifiNative-wlan0( 1029): DRIVER SETBAND 0: returned true
D/WifiNative-wlan0( 1029): doBoolean: BSS_FLUSH 0
D/WifiNative-wlan0( 1029): BSS_FLUSH 0: returned true
D/WifiNative-wlan0( 1029): doBoolean: SCAN
D/WifiNative-wlan0( 1029): SCAN: returned false
E/WifiStateMachine( 1029):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=110830  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/LGWifiP2pService( 1029): DeviceAddress: 
D/WifiNative-p2p0( 1029): doBoolean: P2P_FLUSH
E/WifiStateMachine( 1029):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=110836  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/WifiNative-p2p0( 1029): P2P_FLUSH: returned true
D/WifiNative-p2p0( 1029): doBoolean: P2P_SERVICE_FLUSH
D/WfdsService( 1974): WIFI_P2P_CONNECTION_CHANGED_ACTION
D/WifiNative-p2p0( 1029): P2P_SERVICE_FLUSH: returned true
D/WifiNative-p2p0( 1029): doString: [LIST_NETWORKS]
D/WifiNative-p2p0( 1029):    returned network id / ssid / bssid / flags
D/WfdsService( 1974): isConnected: false
D/WifiNative-p2p0( 1029): doBoolean: SAVE_CONFIG
E/WifiStateMachine( 1029):  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1029):  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1029):  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/BluetoothAdapterService( 6281): File transfer profiles supported!!
E/WifiStateMachine( 1029):  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1029):  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
D/LGBluetoothAvrcpQcomAdapter( 6281): [BTUI] [+] updateMediaPlayerInfo
D/WifiNative-p2p0( 1029): SAVE_CONFIG: returned true
D/LGWifiP2pService( 1029): sending p2p persistent groups changed broadcast
I/WfdStateTracker( 1974): handleP2pThisDeviceChanged
D/WfdsService( 1974): WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
D/WfdsService( 1974): Update P2p Interface State: 3
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/UsbSettingsControl( 6314): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6314): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 6314): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6314): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6314): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 6314): [AUTORUN] setTetherStatus() : status=false
,V/LGMDMManager( 6281): Create singleton instance
I/BluetoothAdapterState( 6281): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
D/LGWifiP2pService( 1029): InactiveState
D/LGWifiP2pService( 1029): InactiveState{ when=-55ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1029): P2pEnabledState{ when=-55ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1029): doBoolean: DRIVER COUNTRY CZ
I/wpa_supplicant( 6313): wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
I/wpa_supplicant( 6313): p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
I/wpa_supplicant( 6313): [LGE_PATCH] driver_cmd() country:CZ
I/wpa_supplicant( 6313): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
I/wpa_supplicant( 6313): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
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
D/WfdsMonitor( 1974): Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
D/WfdsMonitor( 1974): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WfdsMonitor( 1974): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WifiNative-p2p0( 1029): DRIVER COUNTRY CZ: returned true
D/LGWifiP2pService( 1029): InactiveState{ when=-50ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): P2pEnabledState{ when=-50ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): InactiveState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): P2pEnabledState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): DefaultState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): InactiveState{ when=0 what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): P2pEnabledState{ when=0 what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): DefaultState{ when=0 what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
W/WfdsService( 1974): DefaultState - msg [9441285] is not handled
I/ActivityManager( 1029): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6369 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,I/art     ( 1029): Explicit concurrent mark sweep GC freed 33914(1710KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 4.319ms total 176.127ms
D/BluetoothHeadset( 1029): Proxy object connected
V/SIM_STK ( 1029): Menu title from STK is T-Mobile
V/SIM_STK ( 1029): Menu title from STK is T-Mobile
,D/WifiHS20( 1029): hidePasspointNotification off =false
E/ActivityThread( 6347): Failed to find provider info for com.lge.lgaccount.provider
W/LG Account v2.2( 6347): No ProfileInfo entries
I/LG Account v2.2( 6347): isEnabled: false
I/Feature ( 6347): [Lifetracker]ver: 4.21.112(40211120)
I/Feature ( 6347): [Lifetracker]Country: EU
I/Feature ( 6347): [Lifetracker]Operator: OPEN
I/Feature ( 6347): [Lifetracker]Ranking support: false
I/Feature ( 6347): [Lifetracker]Comfort support: false
I/Feature ( 6347): [Lifetracker]Accessory: true
I/Feature ( 6347): [Lifetracker]Health device: true
I/Feature ( 6347): [Lifetracker]Extra Pedometer: false
I/Feature ( 6347): [Lifetracker]Blood glucose device: false
I/Feature ( 6347): [Lifetracker]Device Number: 3
W/Settings( 1029): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1029): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1029): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/BluetoothA2dp( 1029): Proxy object connected
D/WifiScanningService( 1029): SCAN_AVAILABLE : 3
D/RttService( 1029): SCAN_AVAILABLE : 3
D/WifiScanningService( 1029): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL( 1029): startHal
E/wifi    ( 1029): getStaticLongField sWifiHalHandle 0x97b0599c
E/WifiHAL ( 1029): Could not connect handle
D/wifi    ( 1029): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x5022b6
I/WifiNative-HAL( 1029): Could not start hal
E/WifiScanningService( 1029): could not start HAL
,D/LGWifiP2pService( 1029): InactiveState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): P2pEnabledState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): DefaultState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): InactiveState{ when=0 what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): P2pEnabledState{ when=0 what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): DefaultState{ when=0 what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService( 1029): DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
W/Settings( 1029): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1029): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1029): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WifiServerServiceExt( 1029): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1029): setSupplicantStateSCANNING
E/WifiServerServiceExt( 1029): No p2p device connected
D/BluetoothPermissionRequest( 6314): onReceive
D/LGBluetoothFeatureConfig( 6314):  get() - isFeatureLoaded : false
D/BluetoothManagerService( 1029): Message: 20
D/BluetoothManagerService( 1029): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2c85c64:true
D/LGBluetoothResetSettingReceiver( 6314): return without doing reset settings.
I/ActivityManager( 1029): Killing 5610:com.android.contacts/u0a19 (adj 15): empty #17
,E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=9 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/wpa_supplicant( 6313): USIM:  scard_init function
E/WifiMonitor( 1029): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1029): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=10 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1029): couldn't identify event type - WPS-AP-AVAILABLE 
I/wpa_supplicant( 6313): Trying to associate with SSID 'NG700'
E/WifiStateMachine( 1029):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
,D/WifiMonitor( 1029): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=11 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1029):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine( 1029):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine( 1029):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
I/WifiNative-HAL( 1029): startHal
E/wifi    ( 1029): getStaticLongField sWifiHalHandle 0x989278cc
E/WifiHAL ( 1029): Could not connect handle
D/wifi    ( 1029): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x402216
I/WifiNative-HAL( 1029): Could not start hal
D/WifiNative-wlan0( 1029): doString: [BSS RANGE=0- MASK=0x21987]
W/libprocessgroup( 1029): failed to open /acct/uid_10019/pid_5610/cgroup.procs: No such file or directory
,W/ActivityManager( 1029): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
E/WifiStateMachine( 1029):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 11 0 rt=111133  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,D/LGBluetoothAvrcpQcomAdapter( 6281): [BTUI] installed app name: Music
,W/Settings( 1029): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1029): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1029): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1029):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 11 0 rt=111147  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
D/LGBluetoothAvrcpQcomAdapter( 6281): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6281): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 6281): [BTUI]          displayName: Music
W/Settings( 1029): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGBluetoothAvrcpQcomAdapter( 6281): [BTUI]          packageName: com.lge.music
W/Settings( 1029): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1029): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/LGBluetoothAvrcpQcomAdapter( 6281): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6281): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 6281): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6281): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 6281): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6281): [BTUI] [-] updateMediaPlayerInfo
I/BluetoothA2dpServiceJni( 6281): classInitNative
I/BluetoothA2dpServiceJni( 6281): classInitNative: succeeds
D/A2dpStateMachine( 6281): make
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/WifiServerServiceExt( 1029): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1029): setSupplicantStateASSOCIATING
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
I/bluedroid-qcom( 6281): get_profile_interface a2dp
I/GKI_LINUX( 6281): gki_task_entry task_id=2 [A2DP-MEDIA] starting
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/LGBluetoothA2dpServiceJni( 6281): classInitNative: succeeds
I/LGBluetoothA2dpAdapter( 6281): [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
D/A2dpStateMachine( 6281): Enter Disconnected: -2
D/BluetoothAdapterService( 6281): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@368bf2cb
I/BluetoothHidServiceJni( 6281): classInitNative: succeeds
D/HidService( 6281): Received start request. Starting profile...
I/bluedroid-qcom( 6281): get_profile_interface hidhost
D/BluetoothAdapterService( 6281): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@368bf2cb
D/HeadsetStateMachine( 6281): Proxy object connected
D/LGBluetoothHfpAdapter( 6281): [BTUI] queryPhoneState
D/LGBluetoothHfpAdapter( 6281): Try to query the phonestate on bind
D/BluetoothPhoneService.BluetoothLTECall( 1866):  call mBluetoothHeadset.phoneStateChanged()
W/BluetoothHeadset( 1866): Proxy not attached to service
I/BluetoothHealthServiceJni( 6281): classInitNative: succeeds
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
,D/HealthService( 6281): Received start request. Starting profile...
I/bluedroid-qcom( 6281): get_profile_interface health
I/LGBluetoothHealthServiceJni( 6281): classInitNative: succeeds
D/BluetoothAdapterService( 6281): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@368bf2cb
D/BluetoothAdapterService( 6281): Profile still not running:com.android.bluetooth.gatt.GattService
D/HeadsetStateMachine( 6281): Disconnected process message: 10, size: 0
I/BluetoothPanServiceJni( 6281): classInitNative(L105): succeeds
D/HeadsetPhoneState( 6281): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 6281): Disconnected process message: 11, size: 0
D/PanService( 6281): Received start request. Starting profile...
D/BluetoothPanServiceJni( 6281): initializeNative(L110): pan
I/bluedroid-qcom( 6281): get_profile_interface pan
I/ActivityManager( 1029): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6400 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/LGBluetoothPanAdapter( 6281): [BTUI] getInstance : create [LGBluetoothPanAdapter]
D/BluetoothAdapterService( 6281): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@368bf2cb
I/BtGatt.JNI( 6281): classInitNative(L901): classInitNative: Success!
I/wpa_supplicant( 6313): wlan0: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1029): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=12 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1029): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=13 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1029): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=14 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1029):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 12 0 rt=111203  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1029):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 12 0 rt=111203  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
D/BtGatt.DebugUtils( 6281): handleDebugAction() action=null
E/WifiStateMachine( 1029):  DisconnectedState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=111204
D/BtGatt.GattService( 6281): Received start request. Starting profile...
D/BtGatt.GattService( 6281): start()
I/bluedroid-qcom( 6281): get_profile_interface gatt
E/WifiStateMachine( 1029):  ConnectModeState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=111204
D/BtGatt.AdvertiseManager( 6281): advertise manager created
E/WifiStateMachine( 1029):  DriverStartedState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=111205
E/WifiStateMachine( 1029):  SupplicantStartedState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=111205
E/WifiStateMachine( 1029):  DefaultState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=111206
E/WifiStateMachine( 1029):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 14 0 rt=111206  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
W/Settings( 1029): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1029): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1029): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
D/Tethering( 1029): sendTetherStateChangedBroadcast 1, 0, 0
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
I/wpa_supplicant( 6313): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 6313): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
,D/WifiMonitor( 1029): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=15 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1029): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=16 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1029): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1029): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=17 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1029): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1029): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=18 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1029):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 14 0 rt=111217  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
W/Settings( 1029): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1029): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1029): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
E/WifiStateMachine( 1029):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
D/BluetoothAdapterService( 6281): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@368bf2cb
D/WifiServerServiceExt( 1029): SUPPLICANT_STATE_CHANGED_ACTION
,D/WifiServerServiceExt( 1029): setSupplicantStateASSOCIATED
E/WifiStateMachine( 1029):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1029):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1029):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1029):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1029):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 15 0 rt=111226  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1029):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 15 0 rt=111226  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
D/BluetoothAdapterService( 6281): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@368bf2cb
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
I/LGBluetoothMapAdapter( 6281): [BTUI] getInstance : create [LGBluetoothMapAdapter]
V/BluetoothMapService( 6281): BluetoothMapBinder()
D/BluetoothMapService( 6281): Received start request. Starting profile...
D/BluetoothMapService( 6281): start()
E/WifiStateMachine( 1029):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=111234
E/WifiStateMachine( 1029):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=111234
D/BluetoothMapEmailSettingsLoader( 6281): Found 0 applications
D/BluetoothMapEmailAppObserver( 6281): createReceiver()
D/WifiNative-wlan0( 1029): doString: [STATUS]
D/WifiMonitor( 1029): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=19 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/WifiNative-wlan0( 1029):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
D/BluetoothMapEmailAppObserver( 6281): initObservers()
D/BluetoothMapEmailAppObserver( 6281): getEnabledAccountItems()
I/WifiServiceExtension( 1029): setVHTCapabilityType  : false
I/WifiServerServiceExt( 1029): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1029): setKeepAlivePacketInterval msec : 60
W/FormManager( 6369): Network not available. Please check & try again.
D/BluetoothAdapterService( 6281): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@368bf2cb
D/LGBluetoothOppAdapter( 6281): [BTUI] getInstance : create [LGBluetoothOppAdapter]
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1029): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1029): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1029): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/BluetoothAdapterService( 6281): Profile still not running:com.android.bluetooth.gatt.GattService
,W/Settings( 1029): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1029): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1029): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
D/BluetoothAdapterService( 6281): Profile still not running:com.android.bluetooth.gatt.GattService
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
V/FormManager( 6369): Network unavailable.
D/BluetoothAdapterService( 6281): Profile still not running:com.android.bluetooth.gatt.GattService
V/PanService( 6281): [BTUI] SIM Extra State :ABSENT
D/BluetoothAdapterService( 6281): Profile still not running:com.android.bluetooth.gatt.GattService
,V/FormManager( 6369): Network unavailable.
D/ConnectivityService( 1029): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/BluetoothAdapterService( 6281): Profile still not running:com.android.bluetooth.map.BluetoothMapService
V/BluetoothMapService( 6281): Handler(): got msg=1
D/ConnectivityService( 1029): Got NetworkAgent Messenger
D/ConnectivityService( 1029): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1029): NetworkAgent connected
D/BluetoothAdapterState( 6281): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid-qcom( 6281): enable
I/GKI_LINUX( 6281): gki_task_entry task_id=0 [BTU] starting
I/bt_hci_bdroid( 6281): init
I/bt-btu  ( 6281): btu_task pending for preload complete event
E/WifiConfigStore( 1029): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1029): doBoolean: SET_NETWORK 0 bssid any
V/BluetoothFtpReceiver( 6281): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6281): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 6281): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 6281): SapReceiver onReceive 
V/BluetoothSapReceiver( 6281): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6281):  Bluetooth Adapter state = 11
I/bt_vendor( 6281): bt-vendor : init
I/bt_vendor( 6281): bt-vendor : get_bt_soc_type
E/bt_vendor( 6281): get_bt_soc_type: Failed to get soc type
I/bt_vendor( 6281): init: Local BD Address : c0:64:73:54:3f:58
D/bt_userial_mct( 6281): userial_init
D/bt_hci_bdroid( 6281): set_power 1
I/bt_vendor( 6281): bt-vendor : BT_VND_OP_POWER_CTRL: On
I/bt_vendor( 6281): Starting hciattach daemon
I/bt_vendor( 6281): try to set true
D/WifiNative-wlan0( 1029): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1029): doBoolean: SAVE_CONFIG
W/sh      ( 6424): type=1400 audit(0.0:157): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/sh      ( 6424): type=1400 audit(0.0:158): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,I/qcom-bluetooth( 6425): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
D/WifiNative-wlan0( 1029): SAVE_CONFIG: returned true
E/WifiConfigStore( 1029): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1029): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1029): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1029): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1029): SAVE_CONFIG: returned true
,I/ActivityManager( 1029): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6427 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1029): Killing 5969:com.lge.email/u0a23 (adj 15): empty #17
D/CommandListener(  315): Setting iface cfg
D/PCSuite ( 6400): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,I/qcom-bluetooth( 6451): /system/etc/init.qcom.bt.sh: Transport : smd 
,I/qcom-bluetooth( 6452): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
I/qcom-bluetooth( 6454): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 6455): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
I/qcom-bluetooth( 6456): /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
I/qcom-bluetooth( 6457): /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,W/libprocessgroup( 1029): failed to open /acct/uid_10023/pid_5969/cgroup.procs: No such file or directory
E/WifiStateMachine( 1029): Start Dhcp Watchdog 1
E/WifiStateMachine( 1029):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=111372  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1029):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=111372  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1029):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=111373  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/DhcpStateMachine( 1029): StoppedState
D/DhcpStateMachine( 1029): StoppedState{ when=-2ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1029): WaitBeforeStartState
D/WifiServerServiceExt( 1029): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1029): setSupplicantStateFOUR_WAY_HANDSHAKE
D/WifiServerServiceExt( 1029): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1029): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1029):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=111375  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1029):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=111375  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1029):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=111375  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1029):  ObtainingIpState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:-1581579251] from screen [on:0 period:-1581579251]
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1581579250]
I/WifiNative-HAL( 1029): startHal
E/wifi    ( 1029): getStaticLongField sWifiHalHandle 0x989278bc
E/WifiHAL ( 1029): Could not connect handle
D/wifi    ( 1029): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x402162
I/WifiNative-HAL( 1029): Could not start hal
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
I/libmdmdetect( 6459): ESOC framework not supported
E/Diag_Lib( 6459):  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,W/ResourcesManager( 6427): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WiFiOffLoadBroadcast( 6314): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
D/ConnectivityService( 1029): updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
E/WifiStateMachine( 1029):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1029):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1029):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1029):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1029):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1029): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
D/WifiServerServiceExt( 1029): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1029): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1029):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
D/WifiNative-wlan0( 1029): doBoolean: DRIVER SETSUSPENDMODE 0
D/bthci_qcomm_linux( 6459): [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:64:C0)
D/bthci_qcomm_common( 6459): [BTUI] bt_hci_qcomm_init:
D/bthci_qcomm_common( 6459): [BTUI]     BDADDR: 58:3F:54:73:64:C0
D/bthci_qcomm_common( 6459): [BTUI]     BR/EDR: Class 1
D/bthci_qcomm_common( 6459): [BTUI]     LE: Class 2
D/bthci_qcomm_common( 6459): [BTUI]     Ref Clock: 32M
D/btqsocnvmtags( 6459): [BTUI] init_riva_entries: set NORMAL power settings
D/WifiService( 1029): New client listening to asynchronous messages
I/ActivityManager( 1029): Killing 5634:com.android.gallery3d/u0a27 (adj 15): empty #17
,I/wpa_supplicant( 6313): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
,D/WifiNative-wlan0( 1029): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1029): doBoolean: SET ps 0
D/WifiNative-wlan0( 1029): SET ps 0: returned true
D/WifiNative-wlan0( 1029): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 6313): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1029): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1029): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1029): Current State is mWaitBeforeStartState.
D/LGWifiP2pService( 1029): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@cb9f8eb target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@cb9f8eb target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper( 1029): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
V/LgDhcpStateMachineHelper( 1029): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700" is not exist.
D/DhcpStateMachine( 1029): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1029): DHCP Start wake lock is acquired.
D/LgDataFeature( 6314): LgDataFeature() Constructor: none
D/LgDataFeature( 6314): LgDataFeature() Constructor Done, null
,D/WiFiOffLoadUpdatePriority( 6314): remove : truetruetrue
D/AuthorizationBluetoothService( 2128): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/libprocessgroup( 1029): failed to open /acct/uid_10027/pid_5634/cgroup.procs: No such file or directory
I/rmt_storage(  312): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  312): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  312): wakelock acquired: 1, error no: 42
I/rmt_storage(  312): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
E/WifiStateMachine( 1029):  ObtainingIpState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1029):  L2ConnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1029):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
,D/WifiServerServiceExt( 1029): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1029): setSupplicantStateCOMPLETED
,E/WifiStateMachine( 1029):  ObtainingIpState CMD_SAVE_CONFIG uid=1000 0 0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_SAVE_CONFIG uid=1000 0 0
E/WifiStateMachine( 1029):  ConnectModeState CMD_SAVE_CONFIG uid=1000 0 0
D/WifiNative-wlan0( 1029): doBoolean: SAVE_CONFIG
,D/WifiNative-wlan0( 1029): SAVE_CONFIG: returned true
D/WiFiOffLoadUpdatePriority( 6314): remove1
V/WiFiOffLoadSharedPrefsUtils( 6314): save remove
,I/rmt_storage(  312): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
,I/rmt_storage(  312): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
I/rmt_storage(  312): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 22
I/rmt_storage(  312): 
D/WiFiOffLoadBroadcast( 6314): mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
D/WiFiOffLoadBroadcast( 6314): S: false, R: false
,I/rmt_storage(  312): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
E/Diag_Lib(  885): [IMS_FATAL]| 3347 | 911 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
E/WifiStateMachine( 1029):  ObtainingIpState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1029):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/WiFiOffLoadUpdatePriority( 6314): saved SSID: "NG700"
D/WiFiOffLoadUpdatePriority( 6314): connected SSID: null
D/WiFiOffLoadUpdatePriority( 6314): private wpa: "NG700" 300
D/WifiServiceImplEx( 1029): addOrUpdateNetwork pid=6314, uid=1000, packageName=android.uid.system:1000
E/addOrUpdateNetwork( 1029):  uid = 1000 SSID "NG700" nid=0
E/WifiStateMachine( 1029):  ObtainingIpState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=2 any is current
E/WifiStateMachine( 1029):  L2ConnectedState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=2 any is current
E/WifiStateMachine( 1029):  ConnectModeState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=2 any is current
E/WifiConfigStore( 1029):  key="NG700"WPA_PSK netId=0 uid=0/1000
D/WifiServerServiceExt( 1029): addOrUpdateNetwork: mThisIsFirstEnableing = false
D/WifiNative-wlan0( 1029): doBoolean: SET_NETWORK 0 ssid 4e47373030
,D/WifiNative-wlan0( 1029): SET_NETWORK 0 ssid 4e47373030: returned true
E/WifiConfigStore( 1029): Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1029): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1029): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1029): doBoolean: SET_NETWORK 0 key_mgmt WPA-PSK
D/WifiNative-wlan0( 1029): SET_NETWORK 0 key_mgmt WPA-PSK: returned true
D/WifiNative-wlan0( 1029): doBoolean: SET_NETWORK 0 proto WPA RSN
D/WifiNative-wlan0( 1029): SET_NETWORK 0 proto WPA RSN: returned true
,D/WifiNative-wlan0( 1029): doBoolean: SET_NETWORK 0 pairwise TKIP CCMP
D/WifiNative-wlan0( 1029): SET_NETWORK 0 pairwise TKIP CCMP: returned true
D/WifiNative-wlan0( 1029): doBoolean: SET_NETWORK 0 group WEP40 WEP104 TKIP CCMP
D/WifiNative-wlan0( 1029): SET_NETWORK 0 group WEP40 WEP104 TKIP CCMP: returned true
D/WifiNative-wlan0( 1029): doBoolean: SET_NETWORK 0 priority 300
D/WifiNative-wlan0( 1029): SET_NETWORK 0 priority 300: returned true
E/WifiConfigStore( 1029): will read network variables netId=0
E/WifiConfigStore( 1029): writeIpAndProxyConfigurationsOnChange: "NG700" -> "NG700" path: /data/misc/wifi/ipconfig.txt
E/WifiConfigStore( 1029):  writeKnownNetworkHistory() num networks:1 needWrite=false
D/WiFiOffLoadUpdatePriority( 6314):  ssid "NG700" prio 300
D/WiFiOffLoadUpdatePriority( 6314): configuration updated: 0
E/WifiStateMachine( 1029):  ObtainingIpState CMD_SAVE_CONFIG uid=1000 0 0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_SAVE_CONFIG uid=1000 0 0
E/WifiStateMachine( 1029):  ConnectModeState CMD_SAVE_CONFIG uid=1000 0 0
D/WifiNative-wlan0( 1029): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1029): SAVE_CONFIG: returned true
D/WiFiOffLoadUpdatePriority( 6314): configuration saved: true
,I/ActivityManager( 1029): Killing 5228:com.wsandroid.suite.lge/1000 (adj 15): empty #17
D/DhcpStateMachine( 1029): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper( 1029): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1029): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
W/dhcpcd  ( 6464): type=1400 audit(0.0:159): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,W/dhcpcd  ( 6464): type=1400 audit(0.0:160): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/dhcpcd  ( 6464): version 5.5.6 starting
E/dhcpcd  ( 6464): get_duid: m
D/dhcpcd  ( 6464): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 6464): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
W/libprocessgroup( 1029): failed to open /acct/uid_1000/pid_5228/cgroup.procs: No such file or directory
,D/dhcpcd  ( 6464): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 6464): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 6464): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,D/PCSuite ( 6400): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/dhcpcd  ( 6464): wlan0: discarding expired lease
I/dhcpcd  ( 6464): wlan0: broadcasting for a lease
D/dhcpcd  ( 6464): wlan0: sending DISCOVER (xid 0x37c3471e), next in 4.11 seconds
V/WiFiOffLoadBroadcast( 6314): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
W/FormManager( 6369): Network not available. Please check & try again.
D/WiFiOffLoadBroadcast( 6314): MCCMNC not supported: null
V/FormManager( 6369): Network unavailable.
,V/FormManager( 6369): Network unavailable.
D/LGDMClient( 4031): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 4031): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 4031): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4031): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/LGDMClient( 4031): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/LGDMClient( 4031): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 4031): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,I/ActivityManager( 1029): Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=6476 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,W/ResourcesManager( 6476): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/PluginManager( 6476): init()
,W/ExternalStrings( 6476): load override strings
W/ExternalStrings( 6476): java.lang.RuntimeException: Unexpected tag, got eat-comment
W/ExternalStrings( 6476): 	at com.mcafee.plugin.af.a(Unknown Source)
W/ExternalStrings( 6476): 	at com.mcafee.plugin.ac.b(Unknown Source)
W/ExternalStrings( 6476): 	at com.mcafee.plugin.ak.d(Unknown Source)
W/ExternalStrings( 6476): 	at com.mcafee.plugin.ak.a(Unknown Source)
W/ExternalStrings( 6476): 	at com.mcafee.app.s.getClassLoader(Unknown Source)
W/ExternalStrings( 6476): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
W/ExternalStrings( 6476): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
W/ExternalStrings( 6476): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
W/ExternalStrings( 6476): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
W/ExternalStrings( 6476): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
W/ExternalStrings( 6476): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ExternalStrings( 6476): 	at android.os.Looper.loop(Looper.java:135)
W/ExternalStrings( 6476): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/ExternalStrings( 6476): 	at java.lang.reflect.Method.invoke(Native Method)
W/ExternalStrings( 6476): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/ExternalStrings( 6476): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/ExternalStrings( 6476): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
D/StatusProvider( 6476): onCreate
,V/Signer  ( 6476): override build config not found
D/Signer  ( 6476): value of property debug is false
,D/LGMDMWrapper( 6476): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
D/LGMDMWrapper( 6476): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
D/LGMDMWrapper( 6476): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
,D/LGMDMWrapper( 6476): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
D/LGMDMWrapper( 6476): Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
D/LGMDMWrapper( 6476): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
D/LGMDMWrapper( 6476): Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
D/LGMDMWrapper( 6476): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
D/LGMDMWrapper( 6476): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
D/LGMDMWrapper( 6476): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
D/LGMDMWrapper( 6476): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
D/LGMDMWrapper( 6476): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
D/LGMDMWrapper( 6476): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
V/LGMDMManager( 6476): Create singleton instance
D/LGMDMWrapper( 6476): LG MDM library v4.0.0 is available on this device.
,D/PostponalbeReceiver( 6476): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 6400): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
W/ContextImpl( 6476): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
E/QC-QMI  ( 6459): qmi_client [6459] 13: failed to locate client data
E/QC-QMI  (  455): qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
E/QC-QMI  (  455): QMUX qmux_client_id=13 not found in qmux client list, unable to remove
D/PCSuite ( 6400): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6400): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6314): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6314): MCCMNC not supported: null
I/ActivityManager( 1029): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6511 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/ActivityManager( 1029): Killing 5654:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
I/qcom-bluetooth( 6532): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:64:c0 
,I/qcom-bluetooth( 6534): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
I/bt_vendor( 6281): bluetooth satus is on
D/bt_hci_bdroid( 6281): preload
D/bt_userial_mct( 6281): userial_open(port:0)
I/bt_vendor( 6281): bt-vendor : BT_VND_OP_USERIAL_OPEN
,I/bt_vendor( 6281): Done intiailizing UART
I/bt_vendor( 6281): Done intiailizing UART
I/bt_userial_mct( 6281): CMD=66, EVT=66, ACL_Out=67, ACL_In=67
I/bt_vendor( 6281): Bluetooth Firmware and transport layer are initialized
I/bt-btu  ( 6281): btu_task received preload complete event
D/bt_userial_mct( 6281): Entering userial_read_thread()
W/bt-l2cap( 6281): L2CAP - L2CA_Register() called for PSM: 0x0001
W/bt-l2cap( 6281): L2CAP - L2CA_Register() called for PSM: 0x001f
W/bt-l2cap( 6281): L2CAP - L2CA_Register() called for PSM: 0x0003
I/        ( 6281): BTE_InitTraceLevels -- TRC_HCI
I/        ( 6281): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 6281): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 6281): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 6281): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 6281): BTE_InitTraceLevels -- TRC_A2D
I/        ( 6281): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 6281): BTE_InitTraceLevels -- TRC_BTM
I/        ( 6281): BTE_InitTraceLevels -- TRC_HID_HOST
I/        ( 6281): BTE_InitTraceLevels -- TRC_GAP
I/        ( 6281): BTE_InitTraceLevels -- TRC_PAN
I/        ( 6281): BTE_InitTraceLevels -- TRC_SDP
I/        ( 6281): BTE_InitTraceLevels -- TRC_GATT
I/        ( 6281): BTE_InitTraceLevels -- TRC_SMP
I/        ( 6281): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 6281): BTE_InitTraceLevels -- TRC_BTIF
W/bt-btm  ( 6281): btm_decode_ext_features_page Secure conn Controller support Enabled
E/bt-btm  ( 6281): BTM_SecRegister:p_cb_info->p_le_callback == 0xa01c3061 
E/bt-btm  ( 6281): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01c3061 
,E/bt-btif ( 6281): Calling BTA_HhEnable
E/bt-btif ( 6281): btif_storage_get_adapter_property service_mask:0x2140040
D/BluetoothAdapterProperties( 6281): Address is:58:3F:54:73:64:C0
W/bt-l2cap( 6281): L2CAP - L2CA_Register() called for PSM: 0x0019
W/bt-l2cap( 6281): L2CAP - L2CA_Register() called for PSM: 0x0017
W/bt-l2cap( 6281): L2CAP - L2CA_Register() called for PSM: 0x001b
W/bt-l2cap( 6281): L2CAP - L2CA_Register() called for PSM: 0x0011
W/bt-l2cap( 6281): L2CAP - L2CA_Register() called for PSM: 0x0013
W/bt-smp  ( 6281): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6281): Plain text(LSB ~ MSB) = cb fa 4b 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6281): Encrypted text(LSB ~ MSB) = 4f ba 88 68 5a 6d 37 0d 3e 59 d6 d2 ac d2 15 5a 
W/bt-btm  ( 6281): Stopping oneshot timer
W/libprocessgroup( 1029): failed to open /acct/uid_10080/pid_5654/cgroup.procs: No such file or directory
,W/ActivityThread( 6476): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
D/BluetoothManagerService( 1029): Bluetooth Adapter name changed to G3-1
D/BluetoothAdapterProperties( 6281): Name is: G3-1
D/BluetoothManagerService( 1029): Stored Bluetooth name: G3-1
D/BluetoothAdapterProperties( 6281): Scan Mode:20
D/BluetoothAdapterProperties( 6281): Discoverable Timeout:120
D/bt_hci_bdroid( 6281): postload
W/bt-l2cap( 6281): L2CAP - L2CA_Register() called for PSM: 0x000f
D/bt_hci_bdroid( 6281): Used up Tx Cmd credits
D/bt_hci_bdroid( 6281): Used up Tx Cmd credits
D/bt_hci_bdroid( 6281): Used up Tx Cmd credits
D/bt_hci_bdroid( 6281): Used up Tx Cmd credits
E/bt_mct  ( 6281): hci lib postload completed
D/bte_conf( 6281): Device ID record 1 : primary
D/bte_conf( 6281):   vendorId            = 00c4
D/bte_conf( 6281):   vendorIdSource      = 0001
D/bte_conf( 6281):   product             = 13a1
D/bte_conf( 6281):   version             = 1000
D/bte_conf( 6281):   clientExecutableURL = 
D/bte_conf( 6281):   serviceDescription  = 
D/bte_conf( 6281):   documentationURL    = 
D/bte_conf( 6281): bte_load_did_conf no section named DID2.
,D/BluetoothPanServiceJni( 6281): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothAdapterState( 6281): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 6281): ScanMode =  20
D/BluetoothAdapterProperties( 6281): State =  11
D/BluetoothAdapterProperties( 6281): mDiscoverableTimeout = 120
V/LGBluetoothServiceAdapter( 6281): [BTUI] state:11, scanmode:20, timeout:120
D/BluetoothAdapterProperties( 6281): Setting state to 12
I/BluetoothAdapterState( 6281): Bluetooth adapter state changed: 11-> 12
D/BluetoothManagerService( 1029): Message: 60
D/BluetoothManagerService( 1029): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService( 1029): Broadcasting onBluetoothStateChange(true) to 5 receivers.
D/BluetoothHeadset( 1029): onBluetoothStateChange: up=true
I/BluetoothAdapterState( 6281): Entering On State
W/sh      ( 6540): type=1400 audit(0.0:161): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/btif_config_util( 6281): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
W/sh      ( 6540): type=1400 audit(0.0:162): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/BluetoothHeadset( 1866): onBluetoothStateChange: up=true
D/LGBluetoothServiceAdapter( 6281): [BTUI] OnState
D/LGBluetoothServiceAdapter( 6281): [BTUI]         global_name: G3-1
D/LGBluetoothServiceAdapter( 6281): [BTUI]         local_name: G3-1
D/BluetoothHeadset( 1866): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1866): onBluetoothStateChange: up=true
D/BluetoothA2dp( 1029): onBluetoothStateChange: up=true
D/BluetoothAdapterService( 6281): [BTUI] autoConnect() : not allowed
E/BluetoothManagerService( 1029): Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
D/BluetoothManagerService( 1029): Bluetooth State Change Intent: 11 -> 12
D/LGBluetoothAPIService( 1974): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/LGBluetoothAPIService( 1974): Message: 1
,D/LGBluetoothAPIService( 1974): MESSAGE_BOOT_COMPLETED
,D/BluetoothManagerService( 1029): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService( 1029): Message: 40
D/BluetoothManagerService( 1029): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
I/[SystemUI]BluetoothHandler( 1472): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
I/BluetoothMapService( 6281): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 6281): STATE_ON
V/BluetoothMapService( 6281): Handler(): got msg=1
D/BluetoothMapMasInstance( 6281): Map Service startRfcommSocketListener
I/LGBluetoothAPIService( 1974): [BTUI] LGBluetoothAPIService Binding Success
W/ContextImpl( 6314): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,D/BluetoothAdapterService( 6281): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@368bf2cb
V/BluetoothPbapService( 6281): Pbap Service onCreate
V/BluetoothPbapService( 6281): Starting PBAP service
D/LGBluetoothPbapAdapter( 6281): [BTUI] getInstance : create
D/BluetoothAdapterProperties( 6281): Discoverable Timeout:120
D/LGBluetoothDeviceModeControllManager( 6281): adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
V/BluetoothPbapService( 6281): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 6281): state: 12
D/BluetoothMapMasInstance( 6281): MAS initSocket()
D/LGBluetoothAPIServer( 6281): [BTUI] onCreate()
D/LGBluetoothAPIServer( 6281): [BTUI] onBind()
V/BluetoothPbapService( 6281): Handler(): got msg=1
D/LGBluetoothAPIService( 1974): [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
D/LGBluetoothAPIService( 1974): Message: 100
D/LGBluetoothAPIService( 1974): MESSAGE_BLUETOOTH_SERVICE_CONNECTED
V/BluetoothPbapService( 6281): Pbap Service startRfcommSocketListener
V/BluetoothPbapReceiver( 6281): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 6281): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6281): ***********state = 12
,D/BluetoothMapMasInstance( 6281):   masId = 00
D/BluetoothMapMasInstance( 6281):   msgTypes = 0e
D/BluetoothMapMasInstance( 6281):   masName = SMS/MMS
D/BluetoothMapMasInstance( 6281):   SDP string = 000eSMS/MMS
D/BluetoothManagerService( 1029): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
V/BluetoothPbapService( 6281): Pbap Service initSocket
D/BluetoothManagerService( 1029): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/LocalBluetoothProfileManager( 6314): Adding local A2DP profile
D/BluetoothManagerService( 1029): Message: 30
W/BluetoothAdapter( 6281): getBluetoothService() called with no BluetoothManagerCallback
W/BluetoothAdapter( 6281): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 6281): [BTUI] createSocketChannel FD=73 mFd=0
D/LGBluetoothServiceAdapter( 6281): [BTUI] createSocketChannel FD=75 mFd=73
V/BluetoothPbapService( 6281): Succeed to create listening socket 
V/BluetoothPbapService( 6281): Accepting socket connection...
V/BluetoothMapMasInstance( 6281): Succeed to create listening socket 
D/BluetoothMapMasInstance( 6281): Accepting socket connection...
D/BluetoothAdapterProperties( 6281): Scan Mode:21
D/LocalBluetoothProfileManager( 6314): Adding local HEADSET profile
D/LGBluetoothDeviceModeControllManager( 6281): getDeviceMode  deviceMode 0
I/qcom-bt-wlan-coex( 6550): /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
D/BluetoothManagerService( 1029): Message: 30
,D/LGBluetoothDeviceModeControllManager( 6281): [BTUI] checkDeviceModeAndSet, sinkMode : false
D/BluetoothManagerService( 1029): Message: 30
D/BluetoothManagerService( 1029): Message: 30
D/LocalBluetoothProfileManager( 6314): Adding local MAP profile
D/BluetoothMap( 6314): Create BluetoothMap proxy object
D/BluetoothManagerService( 1029): Message: 30
W/ResourcesManager( 6511): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService( 1029): Message: 30
V/BluetoothPbapService( 6281): Pbap Service onBind
D/LocalBluetoothProfileManager( 6314): LocalBluetoothProfileManager construction complete
D/LGBluetoothUserBindClient( 6314): [BTUI] initUserBindClient
W/ContextImpl( 6314): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
D/DockEventReceiver( 6314): finishStartingService: stopping service
D/BluetoothA2dp( 6314): Proxy object connected
D/A2dpProfile( 6314): Bluetooth service connected
D/BluetoothHeadset( 6314): Proxy object connected
,D/HeadsetProfile( 6314): Bluetooth service connected
D/QRemote ( 6511): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
D/BluetoothInputDevice( 6314): Proxy object connected
D/HidProfile( 6314): Bluetooth service connected
D/BluetoothPan( 6314): BluetoothPAN Proxy object connected
D/PanProfile( 6314): Bluetooth service connected
D/BluetoothMap( 6314): Proxy object connected
D/MapProfile( 6314): Bluetooth service connected
D/BluetoothMap( 6314): getConnectedDevices()
V/BluetoothMapService( 6281): getConnectedDevices()
D/BluetoothPbap( 6314): Proxy object connected
D/PbapServerProfile( 6314): Bluetooth service connected
,D/LGBluetoothUserBindClient( 6314): [BTUI] onServiceConnected
D/BluetoothPermissionRequest( 6314): onReceive
D/LGBluetoothFeatureConfig( 6314): isPrivacyLogsEnabled : true
D/LGBluetoothUtils( 6314): [BTUI] FileNotFound: readProperty
D/LGBluetoothResetSettingReceiver( 6314): return without doing reset settings.
V/BluetoothOppReceiver( 6281): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
I/LGBluetoothOppAdapter( 6281): [BTUI] startOppService()
V/BluetoothOppManager( 6281): restoreApplicationData! falsefalsenullnull
,D/LGBluetoothFeatureConfig( 6281): isPrivacyLogsEnabled : true
V/BtOppService( 6281): onCreate
,V/BluetoothOppNotification( 6281): send message
V/BtOppService( 6281): Starting RfcommListener
D/BluetoothOppPreference( 6281): Dumping Names:  
D/BluetoothOppPreference( 6281): {}
D/BluetoothOppPreference( 6281): Dumping Channels:  
D/BluetoothOppPreference( 6281): {}
V/BtOppService( 6281): onStartCommand
V/BtOppService( 6281): pendingUpdate is true keepUpdateThread is false sListenStarted is true
D/QRemote ( 6511): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
V/BluetoothFtpReceiver( 6281): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpReceiver( 6281): BluetoothFtpReceiver Start Service
I/QRemote ( 6511): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 6511): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 6511): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 6511): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
V/BluetoothOppNotification( 6281): new notify threadi!
V/BluetoothOppNotification( 6281): send delay message
V/BtOppService( 6281): start RfcommListener
D/QRemote ( 6511): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
V/BtOppService( 6281): RfcommListener started
V/BtOppRfcommListener( 6281): Starting RFCOMM listener....
D/BluetoothManagerService( 1029): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6281): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 6281): [BTUI] createSocketChannel FD=78 mFd=75
V/BtOppRfcommListener( 6281): Started RFCOMM listener....
I/BtOppRfcommListener( 6281): Accept thread started.
V/BtOppRfcommListener( 6281): Accepting connection...
,D/QRemote ( 6511): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
V/BluetoothOppProvider( 6281): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6281): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
V/BtOppService( 6281): Deleted complete outbound shares, number =  0
D/BluetoothAdapterService( 6281): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@368bf2cb
V/BluetoothFtpService( 6281): Ftp Service onCreate
I/BluetoothFtpService( 6281): Ftp Service onCreate
V/BluetoothFtpService( 6281): Ftp Service onStartCommand
V/BluetoothFtpService( 6281): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpService( 6281): Starting Listening on sockets
V/BluetoothSapReceiver( 6281): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 6281): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 6281): SapReceiver onReceive 
V/BtOppService( 6281): Deleted complete inbound failed shares, number = 0
V/BluetoothSapReceiver( 6281): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6281):  Bluetooth Adapter state = 12
V/BluetoothSapReceiver( 6281): Calling SAP service start service with action = null
V/BluetoothOppProvider( 6281): starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
,V/BluetoothOppProvider( 6281): created cursor android.database.sqlite.SQLiteCursor@320ab302 on behalf of 
V/BtOppService( 6281): ContentObserver received notification
V/BtOppService( 6281): ContentObserver received notification
V/BluetoothFtpService( 6281): Handler(): got msg=1
V/BluetoothFtpService( 6281): Ftp Service startRfcommSocketListener
V/BluetoothFtpService( 6281): Ftp Service initSocket
V/BluetoothOppProvider( 6281): created cursor android.database.sqlite.SQLiteCursor@6a50413 on behalf of 
V/BluetoothOppProvider( 6281): created cursor android.database.sqlite.SQLiteCursor@1532b650 on behalf of 
V/BluetoothOppNotification( 6281): mUpdateCompleteNotification = true
D/BluetoothManagerService( 1029): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6281): getBluetoothService() called with no BluetoothManagerCallback
V/BluetoothOppProvider( 6281): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
D/AuthorizationBluetoothService( 2128): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/QRemote ( 6511): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/LGBluetoothServiceAdapter( 6281): [BTUI] createSocketChannel FD=81 mFd=78
V/BluetoothFtpService( 6281): Succeed to create listening socket on channel 20
V/BluetoothFtpService:RfcommSocketAcceptThread( 6281): Run Accept thread
D/QRemote ( 6511): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
V/BtOppService( 6281): pendingUpdate is true keepUpdateThread is false sListenStarted is true
V/BluetoothOppProvider( 6281): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6281): created cursor android.database.sqlite.SQLiteCursor@c043049 on behalf of 
V/BluetoothOppNotification( 6281): update too frequent, put in queue
V/BtOppService( 6281): pendingUpdate is false keepUpdateThread is false sListenStarted is true
V/BluetoothOppProvider( 6281): created cursor android.database.sqlite.SQLiteCursor@5f4fd4e on behalf of 
V/BluetoothOppNotification( 6281): outbound: succ-0  fail-0
V/BluetoothOppNotification( 6281): outbound notification was removed.
V/BluetoothOppProvider( 6281): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
D/LgDataFeature( 6476): LgDataFeature() Constructor: none
D/LgDataFeature( 6476): LgDataFeature() Constructor Done, null
V/BluetoothOppProvider( 6281): created cursor android.database.sqlite.SQLiteCursor@26d1ce6f on behalf of 
V/BluetoothOppNotification( 6281): inbound: succ-0  fail-0
V/BluetoothOppNotification( 6281): inbound notification was removed.
V/BluetoothOppProvider( 6281): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,D/BluetoothAdapterService( 6281): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@368bf2cb
V/BluetoothSapService( 6281): Sap Service onCreate
V/BluetoothOppProvider( 6281): created cursor android.database.sqlite.SQLiteCursor@36568805 on behalf of 
,V/BluetoothSapService( 6281): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 6281): state: 12
V/BluetoothSapService( 6281): Starting SAP server process
V/BluetoothSapService( 6281): SAP Service startRfcommListenerThread
I/QRemote ( 6511): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/BluetoothSapService( 6281): Sap Service initRfcommSocket
W/sapd    ( 6573): type=1400 audit(0.0:163): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/BluetoothManagerService( 1029): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/sapd    ( 6573): type=1400 audit(0.0:164): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/BluetoothAdapter( 6281): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 6281): [BTUI] createSocketChannel FD=83 mFd=81
V/BluetoothSapService( 6281): Succeed to create listening socket 
V/BluetoothSapService( 6281): Accepting socket connection...
D/QRemote ( 6511): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
V/[BNRBootReceiver]( 6082): boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/BNRAndroBeam( 6082): [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
V/[BNRBootReceiver]( 6082): Boot Receiver Return
V/BT_SAP  ( 6573): Event pipe created
V/BT_SAP  ( 6573): create_server_socket qcom.sap.server
V/BT_SAP  ( 6573): created socket fd 6
,D/QRemote ( 6511): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,D/PostponalbeReceiver( 6476): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 6476): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
V/WiFiOffLoadBroadcast( 6314): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6314): MCCMNC not supported: null
D/QRemote ( 6511): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6511): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6511): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/WiFiOffLoadBroadcast( 6314): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
D/WiFiOffLoadBroadcast( 6314): Not supported operator for automatic switch
D/PostponalbeReceiver( 6476): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 6476): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,V/WiFiOffLoadBroadcast( 6314): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6314): MCCMNC not supported: null
D/QRemote ( 6511): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6511): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6511): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6476): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 6476): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
V/WiFiOffLoadBroadcast( 6314): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6314): MCCMNC not supported: null
D/QRemote ( 6511): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6511): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6511): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6476): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 6476): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
W/ContextImpl( 6476): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
,V/WiFiOffLoadBroadcast( 6314): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6314): MCCMNC not supported: null
D/QRemote ( 6511): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6511): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6511): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/SiteAdvisor( 6476): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
D/UsbSettingsReceiver( 6314): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6314): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6314): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6314): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6314): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 6314): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6314): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6314): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6314): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6314): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6314): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 6314): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6476): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 6476): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
V/WiFiOffLoadBroadcast( 6314): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/SiteAdvisor( 6476): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
D/SiteAdvisor( 6476): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
D/SiteAdvisor( 6476): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
D/SiteAdvisor( 6476): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
D/WiFiOffLoadBroadcast( 6314): MCCMNC not supported: null
I/SiteAdvisor( 6476): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
D/SiteAdvisor( 6476): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
D/QRemote ( 6511): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6511): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/SiteAdvisor( 6476): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
I/QRemote ( 6511): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6476): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 6476): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,V/WiFiOffLoadBroadcast( 6314): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6314): MCCMNC not supported: null
D/QRemote ( 6511): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6511): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6511): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6476): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 6476): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
V/WiFiOffLoadBroadcast( 6314): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6314): MCCMNC not supported: null
D/QRemote ( 6511): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6511): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6511): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6476): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
V/QRemote ( 6511): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,D/QRemote ( 6511): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 6511): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,I/dhcpcd  ( 6464): wlan0: offered 192.168.1.141 from 192.168.1.1
D/dhcpcd  ( 6464): wlan0: sending REQUEST (xid 0x37c3471e), next in 3.12 seconds
D/LgDataFeature( 6511): LgDataFeature() Constructor: none
D/LgDataFeature( 6511): LgDataFeature() Constructor Done, null
,V/SoundPool( 6511): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 6511): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 6511): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 6511): doLoad: loading sample sampleID=1
,V/SoundPool( 6511): Start decode
V/MediaPlayer[Native]( 6511): decode(31, 10857164, 17813)
V/MediaPlayerService(  320): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  320): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  320): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  320): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  320): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  320): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  320): player type = 3
,V/AwesomePlayer(  320): AwesomePlayer create()
V/AwesomePlayer(  320): reset_l() 
V/AwesomePlayer(  320): cancelPlayerEvents
V/AwesomePlayer(  320): setAudioSink() 
V/AwesomePlayer(  320): reset_l() 
V/AudioCache(  320): notify(0xb5474580, 8, 0, 0)
V/AudioCache(  320): ignored
V/AwesomePlayer(  320): cancelPlayerEvents
D/Utils   (  320): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  320): setDataSource_l dataSource
V/LGParserOSAL(  320): SniffLGParser start
V/LGParserOSAL(  320): MainType:5, SubType=0
V/LGParserOSAL(  320): #### check Mime : application/ogg
V/LGParserOSAL(  320): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  320): Use LGExtractor :application/ogg 
I/QRemote ( 6511): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
D/UEI.SmartControl( 6055): QS Service created
D/QRemote ( 6511): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
E/QRemote ( 6511): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6511): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
I/dhcpcd  ( 6464): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
,V/LGMDMManager( 6511): Create singleton instance
I/UEI.SmartControl( 6055): Service initServices...
D/UEI.SmartControl( 6055): QS start get config
V/LGParserOSAL(  320): supported mime: application/ogg
,V/AwesomePlayer(  320): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  320): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  320): mBitrate = -1 bits/sec
V/AwesomePlayer(  320): AudioTrack Setting
V/AwesomePlayer(  320): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  320): setAudioSource() 
V/MediaPlayerService(  320): prepare
V/AwesomePlayer(  320): prepareAsync_l() 
V/MediaPlayerService(  320): wait for prepare
V/AwesomePlayer(  320): onPrepareAsyncEvent() 
V/AwesomePlayer(  320): initAudioDecoder() 
W/Utils   (  320): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  320): isOffloadSupported()
V/AudioPolicyManager(  320): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  320): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  320): isAudioPlaybackHookOn() false
V/AwesomePlayer(  320): getUseOffload() = 0 
V/OMXCodec(  320): OMXCodec::Create
V/OMXCodec(  320): findMatchingCodecs()
V/OMXCodec(  320): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  320): matchingCodecs.size()=1
V/OMXCodec(  320): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
D/OMXCodec(  320): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  320): LG Codec Adapter start
V/OMXCodec(  320): OMXCodec Createtor
V/OMXCodec(  320): setComponentRole
V/OMXCodec(  320): configureCodec protected=0
V/LGCodecAdapter(  320): called getLGCodecSpecificData
V/LGCodecOSAL(  320): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  320): Called LGconfigureCodecMETA
V/LGCodecOSAL(  320): Called LGconfigureCodecMSG
V/LGCodecOSAL(  320): Not support LGCodec
V/OMXCodec(  320): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  320): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  320): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  320): Could not offload audio decode, try pcm offload
W/Utils   (  320): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  320): isOffloadSupported()
V/AudioPolicyManager(  320): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  320): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  320): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  320): init()
V/OMXCodec(  320): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  320): allocateBuffers
V/OMXCodec(  320): allocateBuffersOnPort portIndex=0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc790 on input port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc7e0 on input port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc880 on input port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc8d0 on input port
V/OMXCodec(  320): allocateBuffersOnPort portIndex=1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc920 on output port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc9c0 on output port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb14fca10 on output port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb14fce70 on output port
V/OMXCodec(  320): in,it() mAsyncCompletion wait!!! 
V/OMXCodec(  320): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  320): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  320): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  320): init() mAsyncCompletion wait!!! 
V/OMXCodec(  320): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  320): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  320): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  320): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  320): finishAsyncPrepare_l() 
V/AudioCache(  320): notify(0xb5474580, 5, 0, 0)
V/AudioCache(  320): ignored
V/AudioCache(  320): notify(0xb5474580, 1, 0, 0)
V/AudioCache(  320): prepared
V/AudioCache(  320): wait - success
V/MediaPlayerService(  320): start
V/AwesomePlayer(  320): play_l() 
V/AwesomePlayer(  320): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  320): createAudioPlayer_l
V/AwesomePlayer(  320): seekAudioIfNecessary_l() 
V/AwesomePlayer(  320): startAudioPlayer_l() 
D/AudioPlayer(  320): start of Playback, useOffload 0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  320): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  320): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  320): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  320): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  320): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974796064
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974796224
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974796304
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974797424
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  320): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  320): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  320): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  320): allocateBuffersOnPort portIndex=1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb14fca10 on output port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc9c0 on output port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc920 on output port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] allocated buffer 0xb173d1f0 on output port
V/OMXCodec(  320): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  320): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  320): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  320): notify(0xb5474580, 6, 0, 0)
V/AudioCache(  320): ignored
V/MediaPlayerService(  320): wait for playback complete
V/AudioCache(  320): write(0xb57dc000, 4096)
V/AudioCache(  320): memcpy(0xab700000, 0xb57dc000, 4096)
,D/QRemote ( 6511): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
V/AudioCache(  320): write(0xb57dc000, 4096)
V/AudioCache(  320): memcpy(0xab701000, 0xb57dc000, 4096)
D/QRemote ( 6511): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
V/AudioCache(  320): write(0xb57dc000, 4096)
V/AudioCache(  320): memcpy(0xab702000, 0xb57dc000, 4096)
V/AudioCache(  320): write(0xb57dc000, 4096)
V/AudioCache(  320): memcpy(0xab703000, 0xb57dc000, 4096)
V/AudioCache(  320): write(0xb57dc000, 4096)
V/AudioCache(  320): memcpy(0xab704000, 0xb57dc000, 4096)
V/AudioCache(  320): write(0xb57dc000, 4096)
V/AudioCache(  320): memcpy(0xab705000, 0xb57dc000, 4096)
D/QRemote ( 6511): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:2072
V/AudioCache(  320): write(0xb57dc000, 4096)
V/AudioCache(  320): memcpy(0xab706000, 0xb57dc000, 4096)
V/AudioCache(  320): write(0xb57dc000, 4096)
V/AudioCache(  320): memcpy(0xab707000, 0xb57dc000, 4096)
V/AudioCache(  320): write(0xb57dc000, 4096)
V/AudioCache(  320): memcpy(0xab708000, 0xb57dc000, 4096)
V/AudioCache(  320): write(0xb57dc000, 4096)
V/AudioCache(  320): memcpy(0xab709000, 0xb57dc000, 4096)
V/AudioCache(  320): write(0xb57dc000, 4096)
V/AudioCache(  320): memcpy(0xab70a000, 0xb57dc000, 4096)
D/PostponalbeReceiver( 6476): WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
V/AudioCache(  320): write(0xb57dc000, 4096)
V/AudioCache(  320): memcpy(0xab70b000, 0xb57dc000, 4096)
V/AudioCache(  320): write(0xb57dc000, 4096)
V/AudioCache(  320): memcpy(0xab70c000, 0xb57dc000, 4096)
V/AudioCache(  320): write(0xb57dc000, 4096)
V/AudioCache(  320): memcpy(0xab70d000, 0xb57dc000, 4096)
,V/AudioCache(  320): write(0xb57dc000, 4096)
V/AudioCache(  320): memcpy(0xab70e000, 0xb57dc000, 4096)
V/AudioCache(  320): write(0xb57dc000, 4096)
V/AudioCache(  320): memcpy(0xab70f000, 0xb57dc000, 4096)
V/AudioCache(  320): write(0xb57dc000, 4096)
V/AudioCache(  320): memcpy(0xab710000, 0xb57dc000, 4096)
V/AudioCache(  320): write(0xb57dc000, 4096)
V/AudioCache(  320): memcpy(0xab711000, 0xb57dc000, 4096)
V/AudioCache(  320): write(0xb57dc000, 4096)
V/AudioCache(  320): memcpy(0xab712000, 0xb57dc000, 4096)
V/AudioCache(  320): write(0xb57dc000, 4096)
V/AudioCache(  320): memcpy(0xab713000, 0xb57dc000, 4096)
V/AudioCache(  320): write(0xb57dc000, 4096)
V/AudioCache(  320): memcpy(0xab714000, 0xb57dc000, 4096)
V/AudioCache(  320): write(0xb57dc000, 4096)
V/AudioCache(  320): memcpy(0xab715000, 0xb57dc000, 4096)
V/AudioCache(  320): write(0xb57dc000, 4096)
V/AudioCache(  320): memcpy(0xab716000, 0xb57dc000, 4096)
V/AudioCache(  320): write(0xb57dc000, 4096)
V/AudioCache(  320): memcpy(0xab717000, 0xb57dc000, 4096)
V/AudioCache(  320): write(0xb57dc000, 4096)
V/AudioCache(  320): memcpy(0xab718000, 0xb57dc000, 4096)
V/AudioCache(  320): write(0xb57dc000, 4096)
V/AudioCache(  320): memcpy(0xab719000, 0xb57dc000, 4096)
V/AudioCache(  320): write(0xb57dc000, 4096)
,V/AudioCache(  320): memcpy(0xab71a000, 0xb57dc000, 4096)
V/AudioCache(  320): write(0xb57dc000, 4096)
V/AudioCache(  320): memcpy(0xab71b000, 0xb57dc000, 4096)
V/AudioCache(  320): write(0xb57dc000, 4096)
V/AudioCache(  320): memcpy(0xab71c000, 0xb57dc000, 4096)
V/AudioCache(  320): write(0xb57dc000, 4096)
V/AudioCache(  320): memcpy(0xab71d000, 0xb57dc000, 4096)
V/AudioCache(  320): write(0xb57dc000, 4096)
V/AudioCache(  320): memcpy(0xab71e000, 0xb57dc000, 4096)
V/AudioCache(  320): write(0xb57dc000, 4096)
V/AudioCache(  320): memcpy(0xab71f000, 0xb57dc000, 4096)
V/AudioCache(  320): write(0xb57dc000, 4096)
V/AudioCache(  320): memcpy(0xab720000, 0xb57dc000, 4096)
V/AudioCache(  320): write(0xb57dc000, 4096)
V/AudioCache(  320): memcpy(0xab721000, 0xb57dc000, 4096)
V/AudioCache(  320): write(0xb57dc000, 4096)
V/AudioCache(  320): memcpy(0xab722000, 0xb57dc000, 4096)
V/AudioCache(  320): write(0xb57dc000, 4096)
V/AudioCache(  320): memcpy(0xab723000, 0xb57dc000, 4096)
V/AudioCache(  320): write(0xb57dc000, 4096)
V/AudioCache(  320): memcpy(0xab724000, 0xb57dc000, 4096)
V/AudioCache(  320): write(0xb57dc000, 4096)
V/AudioCache(  320): memcpy(0xab725000, 0xb57dc000, 4096)
V/AudioCache(  320): write(0xb57dc000, 4096)
V/AudioCache(  320): memcpy(0xab726000, 0xb57dc000, 4096)
V/AudioCache(  320): write(0xb57dc000, 4096)
V/AudioCache(  320): memcpy(0xab727000, 0xb57dc000, 4096)
V/AudioCache(  320): write(0xb57dc000, 4096)
V/AudioCache(  320): memcpy(0xab728000, 0xb57dc000, 4096)
V/AudioCache(  320): write(0xb57dc000, 4096)
V/AudioCache(  320): memcpy(0xab729000, 0xb57dc000, 4096)
I/dhcpcd  ( 6464): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 6464): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 6464): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 6464): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 6464): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 6464): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 6464): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 6464): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason BOUND
E/WifiStateMachine( 1029):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
V/AudioCache(  320): write(0xb57dc000, 4096)
V/AudioCache(  320): memcpy(0xab72a000, 0xb57dc000, 4096)
E/WifiStateMachine( 1029):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1029):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
V/AudioCache(  320): write(0xb57dc000, 4096)
V/AudioCache(  320): memcpy(0xab72b000, 0xb57dc000, 4096)
E/WifiStateMachine( 1029):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1029):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
V/AudioCache(  320): write(0xb57dc000, 4096)
V/AudioCache(  320): memcpy(0xab72c000, 0xb57dc000, 4096)
D/ConnectivityService( 1029): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
V/AudioCache(  320): write(0xb57dc000, 4096)
V/AudioCache(  320): memcpy(0xab72d000, 0xb57dc000, 4096)
V/AudioCache(  320): write(0xb57dc000, 4096)
V/AudioCache(  320): memcpy(0xab72e000, 0xb57dc000, 4096)
V/AudioCache(  320): write(0xb57dc000, 4096)
V/AudioCache(  320): memcpy(0xab72f000, 0xb57dc000, 4096)
V/AudioCache(  320): write(0xb57dc000, 4096)
V/AudioCache(  320): memcpy(0xab730000, 0xb57dc000, 4096)
V/AudioCache(  320): write(0xb57dc000, 4096)
V/AudioCache(  320): memcpy(0xab731000, 0xb57dc000, 4096)
V/OMXCodec(  320): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  320): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  320): postAudioEOS() 
V/AudioCache(  320): write(0xb57dc000, 280)
V/AudioCache(  320): memcpy(0xab732000, 0xb57dc000, 280)
V/AwesomePlayer(  320): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  320): onStreamDone
V/AwesomePlayer(  320): MEDIA_PLAYBACK_CO,MPLETE
V/AudioCache(  320): notify(0xb5474580, 2, 0, 0)
V/AudioCache(  320): playback complete
V/AwesomePlayer(  320): pause_l() 
V/AudioCache(  320): notify(0xb5474580, 7, 0, 0)
V/AudioCache(  320): ignored
V/AwesomePlayer(  320): cancelPlayerEvents
V/AudioCache(  320): wait - success
V/MediaPlayerService(  320): return size 205080, sampleRate=48000, channelCount = 2, format = 1
D/AudioPlayer(  320): Pause Playback at 1068125
V/AwesomePlayer(  320): reset_l() 
V/AudioCache(  320): notify(0xb5474580, 8, 0, 0)
V/AudioCache(  320): ignored
V/AwesomePlayer(  320): cancelPlayerEvents
D/AudioPlayer(  320): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  320): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  320): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  320): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  320): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  320): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc8d0 on port 0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc880 on port 0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc7e0 on port 0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc790 on port 0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeing buffer 0xb173d1f0 on port 1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc920 on port 1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc9c0 on port 1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeing buffer 0xb14fca10 on port 1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  320): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  320): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  320): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  320): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  320): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  320): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
V/OMXCodec(  320): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  320): AudioPlayer releasing audio source
D/AudioPlayer(  320): AudioPlayer done releasing audio source
V/AwesomePlayer(  320): reset_l() 
V/AwesomePlayer(  320): cancelPlayerEvents
V/AwesomePlayer(  320): ~AwesomePlayer call
,V/AwesomePlayer(  320): reset_l() 
V/AwesomePlayer(  320): cancelPlayerEvents
V/SoundPool( 6511): close(31)
V/SoundPool( 6511): pointer = 0x9ff29000, size = 205080, sampleRate = 48000, numChannels = 2
,D/PostponalbeReceiver( 6476): WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
D/PostponalbeReceiver( 6476): WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
D/PostponalbeReceiver( 6476): WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
D/PostponalbeReceiver( 6476): WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,D/PostponalbeReceiver( 6476): WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
D/PostponalbeReceiver( 6476): WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
E/WifiStateMachine( 1029):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4
E/WifiStateMachine( 1029):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4
E/WifiStateMachine( 1029):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4
E/WifiStateMachine( 1029):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4
E/WifiStateMachine( 1029):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4
E/WifiStateMachine( 1029):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4
D/ConnectivityService( 1029): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
,D/DhcpStateMachine( 1029): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper( 1029): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1029): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1029): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1029): Add DhcpResults: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
V/DhcpStateMachine( 1029): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1029): bShouldSendDhcpAction Result: true
D/DhcpStateMachine( 1029): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1029): RunningState
E/WifiStateMachine( 1029):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine( 1029):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/LGWifiP2pService( 1029): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1029): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 6313): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1029): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1029): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 6313): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1029): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1029): doBoolean: SET ps 1
D/WifiNative-wlan0( 1029): SET ps 1: returned true
E/WifiStateMachine( 1029):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1029): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1029): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
,D/ConnectivityService( 1029): ignoring duplicate network state non-change
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1029): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
W/Settings( 1029): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1029): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1029): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,E/WifiStateMachine( 1029): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/PostponalbeReceiver( 6476): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/ConnectivityService( 1029): Adding iface wlan0 to network 100
W/Settings( 1029): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1029): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1029): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/WifiHS20( 1029): [PASSPOINT] passpointNotification: hs20AP list is checked
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = true, mWifiLevel = 2
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1029): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1029): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1029): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20( 1029): [PASSPOINT] passpointNotification: hs20AP list is checked
,V/WfdStateTracker( 1974): handleWifiStateChangedEvent: 1
E/ConnectivityService( 1029): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1029): Adding Route [fe80::/64 -> :: wlan0] to network 100
W/Settings( 1029): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1029): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1029): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/ConnectivityService( 1029): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
D/ConnectivityService( 1029): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,D/ConnectivityService( 1029): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1029): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 100
D/ConnectivityService( 1029): Setting Dns servers for network 100 to [/192.168.1.1]
D/Nat464Xlat( 1029): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1029): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1029): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1029): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1029): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1029): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1029): Checking http://clients3.google.com/generate_204 on "NG700"
,D/ConnectivityService( 1029): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1029):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1029):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1029):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1029):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1029):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1029): currentScore = 0, newScore = 20
D/ConnectivityService( 1029):    accepting network in place of null
D/ConnectivityService( 1029): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1029): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1029):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1866): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1866):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/ConnectivityService( 1029): Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
D/libc-netbsd(  315): res_queryN name = clients3.google.com, class = 1, type = 28
E/ConnectivityService( 1029): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,fe80::c69a:2ff:fe7b:60ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1029): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1029): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService( 1029): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1029): [e] list.add(nai) empty : false size: 1
D/ConnectivityService( 1029): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,fe80::c69a:2ff:fe7b:60ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/LocSvc_java( 1029): Sending msg: 4 arg1:1 arg2:1
D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  315): res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
D/libc-netbsd(  315): res_queryN name = 2.android.pool.ntp.org., class = 1, type = 1
D/DSQN    ( 1029): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = true, mWifiLevel = 2
D/LocSvc_java( 1029): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1029): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1029): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java( 1029): Sending msg: 5 arg1:0 arg2:1
,D/ConnectivityService( 1029): validation of new default Network = false
D/ConnectivityService( 1029): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1029): enableDataServiceNotify 
D/DSQN    ( 1029): start dsqn bin
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  315): res_queryN name = europe.pool.ntp.org, class = 1, type = 1
D/ConnectivityService( 1029): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1029):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1029):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1029): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1472): CM callback handler got msg 524290
W/dsqn    ( 6617): type=1400 audit(0.0:165): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 6617): type=1400 audit(0.0:166): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6840 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
E/DSQN    ( 6617): DSQN ssw
,V/WiFiOffLoadBroadcast( 6314): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/UEI.SmartControl( 6055): Supports setup maps: true
V/NetworkPolicy( 1029): [LG_RESTRICTED] checkMobilePolicy_type()
D/UEI.SmartControl( 6055): QS start statue = true Error code = 0
I/UEI.SmartControl( 6055): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6055): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6055): ### init IR Blaster...
,D/serial_port( 6055): Configuring serial port
D/WiFiOffLoadBroadcast( 6314): MCCMNC not supported: null
,E/UEI.SmartControl( 6055): UEIBLaster setting for 616
I/UEI.SmartControl( 6055): Setting serial record hearder size = 2
I/UEI.SmartControl( 6055): configuring settings for MAXQ616
I/UEI.SmartControl( 6055): Get version...
D/QRemote ( 6511): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6511): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6511): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/TelephonyIcons( 1472): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PostponalbeReceiver( 6476): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/UEI.SmartControl( 6055): serial port data available: 21
V/WiFiOffLoadBroadcast( 6314): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6314): MCCMNC not supported: null
D/QRemote ( 6511): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6511): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6511): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6476): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6400): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6400): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6314): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6314): MCCMNC not supported: null
D/UEI.SmartControl( 6055): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 6055): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 6055): QS saving settings...
D/UEI.SmartControl( 6055): IR Blaster version: 25672567
D/QRemote ( 6511): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6511): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6511): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6511): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6511): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 6476): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 6400): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6400): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6314): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6314): MCCMNC not supported: null
D/UEI.SmartControl( 6055): serial port data available: 4
D/QRemote ( 6511): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6511): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 6511): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6511): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 6511): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
I/UEI.SmartControl( 6055): Device manager: loading config....
W/ContextImpl( 6055): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,D/UEI.SmartControl( 6055): ----------- loading internal config...
E/UEI.SmartControl( 6055): Services init done
D/UEI.SmartControl( 6055): QS Service init finished
D/UEI.SmartControl( 6055): QS Service version name: 2.1.91
D/UEI.SmartControl( 6055): QS Service version code: 201091
D/UEI.SmartControl( 6055): Service requested: Control
E/UEI.SmartControl( 6055): Loading SETTINGS...
D/UEI.SmartControl( 6055): -- Open brand translation xml: brands_translations_ko
D/UEI.SmartControl( 6055): Request IControl service: devices are loaded...
D/UEI.SmartControl( 6055): Internal service binding...
I/QRemote ( 6511): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 6055): ------ IControl API: 11
D/UEI.SmartControl( 6055): File observer start...
E/UEI.SmartControl( 6055): IR Port is disabled: false
D/UEI.SmartControl( 6055): Starting file observer...
,I/UEI.SmartControl( 6055): Registering callback...
I/UEI.SmartControl( 6055): ------ IControl API: 19
I/UEI.SmartControl( 6055): Registering Services Ready callback...
I/UEI.SmartControl( 6055): Notify client services are ready...
I/QRemote ( 6511): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 6511): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 6511): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
I/UEI.SmartControl( 6055): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6055): -----service ready thread exits
I/QRemote ( 6511): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 6511): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 6511): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 6511): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 6511): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
,I/UEI.SmartControl( 6055): ------ IControl API: 8
D/QRemote ( 6511): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 6511): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 6511): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 6511): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 6511): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6511): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 6511): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
D/QRemote ( 6511): [RemoteControlManager.java:327:handleMessage()] oooooo 140510:retrieveDevices already complete. Do nothing
V/QRemote ( 6511): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,D/QRemote ( 6511): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 6511): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6511): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,D/QRemote ( 6511): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6511): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 6511): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 6511): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1454412336181]
D/QRemote ( 6511): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
I/ActivityManager( 1029): Killing 6000:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,D/QRemote ( 6511): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,W/libprocessgroup( 1029): failed to open /acct/uid_10061/pid_6000/cgroup.procs: No such file or directory
,V/QRemote ( 6511): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
E/QRemote ( 6511): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6511): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 6511): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 6511): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 6511): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 6511): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/libc-netbsd(  315): res_queryN name = clients3.google.com, class = 1, type = 1
,D/QRemote ( 6511): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,V/BluetoothOppNotification( 6281): new notify threadi!
D/libc-netbsd(  315): res_queryN name = europe.pool.ntp.org succeed
,V/BluetoothOppNotification( 6281): send delay message
V/BluetoothOppProvider( 6281): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,V/BluetoothOppProvider( 6281): created cursor android.database.sqlite.SQLiteCursor@886ff68 on behalf of 
V/BluetoothOppNotification( 6281): mUpdateCompleteNotification = true
V/BluetoothOppProvider( 6281): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 6281): created cursor android.database.sqlite.SQLiteCursor@35bc9f81 on behalf of 
V/BluetoothOppNotification( 6281): outbound: succ-0  fail-0
V/BluetoothOppNotification( 6281): outbound notification was removed.
V/BluetoothOppProvider( 6281): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 6281): created cursor android.database.sqlite.SQLiteCursor@38af6826 on behalf of 
V/BluetoothOppNotification( 6281): inbound: succ-0  fail-0
V/BluetoothOppNotification( 6281): inbound notification was removed.
V/BluetoothOppProvider( 6281): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6281): created cursor android.database.sqlite.SQLiteCursor@7cf1c67 on behalf of 
,D/libc-netbsd(  315): res_queryN name = clients3.google.com succeed
,D/LocSvc_java( 1029): NTP server : europe.pool.ntp.org
D/LocSvc_java( 1029): NTP server returned: 1454412336821 (Tue Feb 02 12:25:36 GMT+01:00 2016) reference: 113802 certainty: 35 system time offset: 301
,D/LocSvc_java( 1029): Sending msg: 10 arg1:0 arg2:1
D/LGDataListener(  315): argv[0]=dsqncommand
D/LGDataListener(  315): argv[1]=wlan0
D/LGDataListener(  315): argv[2]=1
D/LGDataListener(  315): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1029): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1029): start to monitor internet connection
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1029): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 02 Feb 2016 11:25:36 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454412336564], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454412336519]}
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
,D/ConnectivityService( 1029): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    ( 1029): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1029):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityManager.CallbackHandler( 1472): CM callback handler got msg 524290
D/TelephonyNetworkFactory-1( 1866): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1866):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/TelephonyIcons( 1472): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1581576240] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1581576238] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
,V/AlarmManager( 1029): RTC_WAKEUP set : Alarm{307514c type 0 when 1454412334270 com.android.vending} when 1454412334270
,W/ContextImpl( 4285): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,V/SIM_STK ( 1029): Menu title from STK is T-Mobile
,V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 6215): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 6215): 
,D/Finsky  ( 5705): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5705): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 5705): [1] 5.onFinished: Scheduling replication attempt 2.
I/CloudHub( 2258): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19979
,I/jxcore-log( 6215): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 6215): 
,I/jxcore-log( 6215): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 6215): ,
I/jxcore-log( 6215): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
I/jxcore-log( 6215): 
,I/jxcore-log( 6215): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 6215): 
V/WifiInternetCheck( 1029): Single check msg out of sync, ignoring.
,D/ConnectivityService( 1029): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1029): MasterInitialState.processMessage what=3
D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  315): res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
I/NetworkMonitor( 5323): type=WIFI subType= reason=null isConnected=true
,D/PostponalbeReceiver( 6476): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,D/libc-netbsd(  315): res_queryN name = 2.android.pool.ntp.org succeed
,D/AlarmManagerService( 1029): Setting time of day to sec=1454412339
,W/AlarmManagerService( 1029): Unable to set rtc to 1454412339: Invalid argument
,I/GoogleURLConnFactory( 2128): Using platform SSLCertificateSocketFactory
W/ContextImpl( 6476): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,D/GpsLocationProvider( 1029): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager( 1029): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6672 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
,I/SecureClockService( 1974): Intent.ACTION_TIME_CHANGED 
I/[SystemUI]Clock( 1472): onReceive = android.intent.action.TIME_SET
I/LgeClockWidgetControlView( 1472): time changed, timezoneChanged : false
D/LIA_Informant_Tips_DateChangeManager( 3564): onReceive() : ACTION_TIME_CHANGED
I/LIA_Informant_Tips_LogTracer( 3564): [Log Tracer - Schedule Transition] Time Change Event Received : 2016-02-02 12:25:39...... Request
I/LIA_Informant_Tips_LogTracer( 3564): [Log Tracer - Schedule Transition] UserGuide, DATE_UPDATE : working count : 6, total count : 163, new day : false...... Request
D/LIA_Informant_Tips_DateChangeManager( 3564): DateInfo : SmartTips Total Working Day Count = 163
D/LIA_Informant_Tips_DateChangeManager( 3564): DateInfo : UserGuide Working Duration Count = 6
D/LIA_Informant_Tips_DateChangeManager( 3564): DateInfo : Last Date Check Time = 2016-02-02 12:25:39
I/CalendarProvider2( 5503): onReceive() android.intent.action.TIME_SET
D/CalendarProvider2( 5503): Scheduling check of next Alarm
,W/ActivityManager( 1029): getTasks: caller 10029 is using old GET_TASKS but privileged; allowing
I/[LGHome]LGDateChangeReceiver( 2087): [LGDateChangeReceiver.java:78:updateCalendarShortcut()]date=2 currentDate=-1 dayofweek=3 currentDayOfWeek=-1
I/[LGHome]LGCalendarIcon( 2087): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Tue date= 2
I/[LGHome]LGCalendarIcon( 2087): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Tue date= 2
I/[LGHome]Launcher( 2087): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,D/[Concierge]Service( 2574): onStartCommand(). Type : 9
,I/AppUp4:AppBoxCP( 6672): onCreate
,W/AppUp4:DB( 6672):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6672):  setFingerPrint start
I/AppUp4:DB( 6672):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,I/ActivityManager( 1029): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=6695 uid=10054 gids={50054, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/AppUp4:DB( 6672):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 6672):  SDK version = 21
I/AppUp4:DB( 6672):  beforefinger == newfinger no write in DB
,I/ActivityManager( 1029): Start proc com.android.gallery3d for service com.android.gallery3d/com.lge.gallery.picasa.PicasaService: pid=6713 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
D/AppUp4:AppBoxApplication( 6672): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6672): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6672): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 6672): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6672): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6672): onReceive
,W/ResourcesManager( 6713): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6713): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6713): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 6713): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,D/LgDataFeature( 6672): LgDataFeature() Constructor: none
D/LgDataFeature( 6672): LgDataFeature() Constructor Done, null
D/AppUp4:CustFacade( 6672): Context : android.app.ReceiverRestrictedContext@2841c99a
,D/AppUp4:CustFacade( 6672): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6672): isPhone : true
D/AppUp4:CustModeStarterReceiver( 6672): begin check event
I/AppUp4:CustModeStarterReceiver( 6672): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6672): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6672): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6672): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6672): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1029): Killing 5680:com.google.android.apps.plus/u0a97 (adj 15): empty #17
I/art     ( 1029): Explicit concurrent mark sweep GC freed 70413(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 44MB/66MB, paused 1.398ms total 75.253ms
,D/LGDMClient( 4031): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4031): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/libprocessgroup( 1029): failed to open /acct/uid_10097/pid_5680/cgroup.procs: No such file or directory
,W/ContextImpl( 4031): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
I/AppConfig( 6713): Total System Memory = 2995761152
D/SystemHelper( 6713): region [EU], country [EU], operator [OPEN], sub-operator []
W/ContextImpl( 4031): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,I/ActivityManager( 1029): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=6733 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ReaderUtils( 6695): PortraitW 1440 LandscapeW 2392 SmallestSize 1340 LargestSize 2392 textZoom 4.4999995 isTablet false Memory 256
D/LGDMClient( 4031): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,D/GpsLocationProvider( 1029): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/LGDMClient( 4031): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,D/LGDMClient( 4031): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4031): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 3356): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,W/ContextImpl( 4031): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3356): DownloadService onCreate
E/LGDMClient( 4031): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4031): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4031): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/DownloadManager( 3356): in removeSpuriousFiles
V/DownloadManager( 3356): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3356): created cursor android.database.sqlite.SQLiteCursor@38c83ca1 on behalf of 3356
I/DownloadManager( 3356): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3356): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3356): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3356): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3356): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3356): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3356): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3356): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3356): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3356): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3356): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/DownloadManager( 3356): in trimDatabase
V/DownloadManager( 3356): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3356): created cursor android.database.sqlite.SQLiteCursor@3257ce87 on behalf of 3356
I/ActivityManager( 1029): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6760 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,E/GpsLocationProvider( 1029): No APN found to select.
I/art     (  355): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 217us total 12.646ms
,I/art     (  355): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 182us total 9.095ms
V/DownloadManager( 3356): DownloadService onStartCommand
V/DownloadManager( 3356): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/art     (  355): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 183us total 8.826ms
V/DownloadManager( 3356): created cursor android.database.sqlite.SQLiteCursor@b8b01dd on behalf of 3356
V/DownloadManager( 3356): processing inserted download 1
V/DownloadManager( 3356): processing inserted download 4
V/DownloadManager( 3356): processing inserted download 7
V/DownloadManager( 3356): processing inserted download 8
,W/GAV2    ( 6695): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,V/DownloadManager( 3356): processing inserted download 9
V/DownloadManager( 3356): processing inserted download 10
V/DownloadManager( 3356): processing inserted download 16
V/DownloadManager( 3356): processing inserted download 17
V/DownloadManager( 3356): processing inserted download 18
V/DownloadManager( 3356): processing inserted download 21
V/DownloadManager( 3356): processing inserted download 22
V/DownloadManager( 3356): DownloadService onDestroy
,I/BooksApp( 6695): Created application version: 3.2.35 (30235)
,W/ResourcesManager( 6760): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6760): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6760): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6760): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/DriveInitializer( 2340): Background init thread started
,I/ActivityManager( 1029): Killing 6035:com.lge.eula/1000 (adj 15): empty #17
,E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.gms/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 2340): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.gms/files
W/libprocessgroup( 1029): failed to open /acct/uid_1000/pid_6035/cgroup.procs: No such file or directory
,V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/VacuumService( 2128): Vacuum at: now=1454412340245 tag=VacuumService
I/LGEmail ( 6760): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6760): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,W/DriveInitializer( 2340): Background init thread ended
,I/GLSUser ( 2128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/ads_measurement
,I/GLSUser ( 2128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/ads_measurement without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/Auth.Api.Credentials( 2340): [CredentialSyncAdapter] Unknown sync event.
D/DelayedSyncController( 6733): Delaying sync.
I/BooksSync( 6695): Starting books sync
E/Ads     ( 2340): [JAMS] Failed to get OAuth token: com.google.android.gms.auth.ad: BadAuthentication
,W/ResourceType( 6760): No package identifier when getting value for resource number 0x00000000
D/LgDataFeature( 6760): LgDataFeature() Constructor: none
D/LgDataFeature( 6760): LgDataFeature() Constructor Done, null
,I/art     ( 2128): Explicit concurrent mark sweep GC freed 17756(1006KB) AllocSpace objects, 2(32KB) LOS objects, 51% free, 30MB/62MB, paused 2.799ms total 51.273ms
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=5.8, 0.0, 0.0  rx=5.0 bcn=0 [on:0 tx:0 rx:0 period:3298] from screen [on:0 period:-1581572924] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=5.8, 0.0, 0.0  rx=5.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1581572923] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,I/ActivityManager( 1029): Killing 5469:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
,D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  315): res_queryN name = www.google.com, class = 1, type = 1
,W/libprocessgroup( 1029): failed to open /acct/uid_10005/pid_5469/cgroup.procs: No such file or directory
,D/eas_req ( 6760): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
I/HubEmail( 6760): JNI_OnLoad()
I/HubEmail( 6760): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6760): registerNatives()
I/HubEmail( 6760): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6760): registerNativeMethods()
I/HubEmail( 6760): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6760): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,W/Settings( 6760): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 6760): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/BooksSync( 6695): started syncMyEbooks
,I/LgeMiscReceiver( 3301): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3301): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 3301): networkInfo.isConnected() = true
D/PhoneState( 3301): setPdpRejectCasuse : false
D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  315): res_queryN name = static-avc.lglime.com, class = 1, type = 1
D/libc-netbsd(  315): res_queryN name = www.google.com succeed
,D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  315): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  315): res_queryN name = clients3.google.com succeed
I/ActivityManager( 1029): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6824 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/libc-netbsd(  315): res_queryN name = static-avc.lglime.com succeed
V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2128): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2128): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2128): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2128): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2128): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2128): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2128): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1412): onNotificationPosted
E/BooksAccountManager( 6695): Authentication error
E/BooksAccountManager( 6695): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6695): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6695): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6695): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6695): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6695): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6695): null auth token
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
D/DrmBroadcastReceiver( 6824): Receive CONNECTIVITY_ACTION
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
,E/LgeQuickCoverOverlayWindow( 1412): updateNotificationData: count=3
D/DrmBroadcastReceiver( 6824): 1  network is available. Sync DRM Time with NTP
V/DrmService( 6824): Service onCreate
D/DrmService( 6824): Received new request = 2
,I/DrmSntpClient( 6824): Start Sync process
D/DrmSntpClient( 6824): Server : 0
D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  315): res_queryN name = www.googleapis.com, class = 1, type = 1
D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  315): res_queryN name = pool.ntp.org, class = 1, type = 1
D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{320ab302 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,I/ActivityManager( 1029): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=6845 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd(  315): res_queryN name = www.googleapis.com succeed
D/libc-netbsd(  315): res_queryN name = pool.ntp.org succeed
,V/WifiInternetCheck( 1029): isHttpConnectionAvailable - We got a valid response : 204
D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 117902684750; DSPS: 4004748; Offset : -4327379870
I/LGDrmClient( 6824): _DRM_ServiceGet() : Bind lgdrm service
I/art     ( 6845): Almond Protected OAT
,V/ILGDrmService(  326): eDRM_SetDRMTime +++
I/LGDRM   (  326): [DRM] SET TIME : YR=2016, MON=2, DAY=2
I/LGDRM   (  326): [DRM] SET TIME : HR=11, MIN=25, SEC=39
V/ILGDrmService(  326): eDRM_SetDRMTime ---
I/DrmSntpClient( 6824): Synched
D/DrmService( 6824): Completed !! request = 2
D/DrmService( 6824): Request count = 0
V/DrmService( 6824): Service onDestroy
I/ActivityManager( 1029): Killing 5503:com.android.providers.calendar/u0a14 (adj 15): empty #17
,V/FormManager( 6369): There are no updated forms. The schedule will be deleted.
,V/FormManager( 6369): Alarm would be updated, because LastCheckTime has been updated.
W/libprocessgroup( 1029): failed to open /acct/uid_10014/pid_5503/cgroup.procs: No such file or directory
,D/WeatherApplication( 6845): removeAccount
D/WeatherApplication( 6845): Account.length = 0
E/WeatherApplication( 6845): OPERATOR:OPEN
,D/WeatherAncestor( 6845): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:25:41
D/Weather.Utils( 6845): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6845): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6845): 2 : This is isUpdating : false
I/ActivityManager( 1029): Killing 6138:com.google.android.talk/u0a72 (adj 15): empty #17
D/WeatherAncestor( 6845): connectivity changed - connection : true
,D/WeatherService( 6845): 2 : isServiceAlived():false forecastCache:null
D/ForecastDataCache( 6845): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 6845): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 6845): 2 : Cache is not up-to-date, count: 0
,D/Weather_cast( 6845): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 6845): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:25:41
,W/libprocessgroup( 1029): failed to open /acct/uid_10072/pid_6138/cgroup.procs: No such file or directory
,I/ActivityManager( 1029): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6869 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1029): Killing 2258:com.lge.music/u0a34 (adj 15): empty #17
V/AudioFlinger(  320): 2258 died, releasing its sessions
V/AudioFlinger(  320):  pid 1866 @ 0
V/AudioFlinger(  320):  pid 3301 @ 1
V/AudioFlinger(  320):  pid 3301 @ 2
,W/ApiaryClient( 6695): Error response from books API: {
W/ApiaryClient( 6695):  "error": {
W/ApiaryClient( 6695):   "errors": [
W/ApiaryClient( 6695):    {
W/ApiaryClient( 6695):     "domain": "global",
W/ApiaryClient( 6695):     "reason": "required",
W/ApiaryClient( 6695):     "message": "Login Required",
W/ApiaryClient( 6695):     "locationType": "header",
W/ApiaryClient( 6695):     "location": "Authorization"
W/ApiaryClient( 6695):    }
W/ApiaryClient( 6695):   ],
W/ApiaryClient( 6695):   "code": 401,
W/ApiaryClient( 6695):   "message": "Login Required"
W/ApiaryClient( 6695):  }
W/ApiaryClient( 6695): }
W/ApiaryClient( 6695): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6695): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7581685757272136675&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6695): Headers:
W/ApiaryClient( 6695): accept-encoding: [gzip]
W/ApiaryClient( 6695): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6695): gdata-version: 2
,W/libprocessgroup( 1029): failed to open /acct/uid_10034/pid_2258/cgroup.procs: No such file or directory
,I/art     ( 1029): Explicit concurrent mark sweep GC freed 29621(1309KB) AllocSpace objects, 4(192KB) LOS objects, 33% free, 43MB/65MB, paused 1.503ms total 104.753ms
,V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6869): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6869): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GLSUser ( 2128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 2128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/UEI.SmartControl( 6055): Internal timer expired: 4
D/UEI.SmartControl( 6055): unbind internal service
V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6869): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6869): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
,D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2128): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2128): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2128): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2128): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2128): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2128): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2128): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1412): onNotificationPosted
D/SmartCoverUpdateMonitor( 1412): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1412): MSG_NOTIFICATION_POSTED
D/ContactsSyncAdapter( 2128): innerSync failed
D/ContactsSyncAdapter( 2128): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2128): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2128): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2128): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2128): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2128): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2128): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2128): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2128): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2128): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2128): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2128): 	at android.os.Binder.execTransact(Binder.java:446)
D/SmartCoverUpdateMonitor( 1412): handleNotificationPosted(true)
D/QuickCircle( 1412): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1412): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
,D/LgeQuickCoverNotificationData( 1412): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post do just update job
D/LgeQuickCoverNotificationData( 1412): showAll3
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1412): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  1
,D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1412): updateNotificationData: count=3
D/serial_port( 6055): close(fd = 24)
I/UEI.SmartControl( 6055): Serial port is closed.
D/SyncManager( 1029): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 27121, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager( 1029): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 149208, reason: 10019
,D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{320ab302 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/ActivityManager( 1029): Start proc com.google.android.apps.plus for service com.google.android.apps.plus/.service.EsSyncAdapterService: pid=6901 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 6901): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/WebViewFactory( 6869): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 6869): Loading: webviewchromium
I/LibraryLoader( 6869): Time to load native libraries: 2 ms (timestamps 8674-8676)
I/LibraryLoader( 6869): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6869): Binding Chromium to main looper Looper (main, tid 1) {2a3d636d}
,I/LibraryLoader( 6869): Expected native library version number "",actual native library version number ""
I/chromium( 6869): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6869): Initializing chromium process, renderers=0
,W/art     ( 6869): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6869): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
V/AudioPolicyService(  320): registerClient() client 0xb148fda0, uid 10093
I/chromium( 6869): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
,I/chromium( 6869): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
W/AudioManagerAndroid( 6869): Requires BLUETOOTH permission
,I/Adreno-EGL( 6869): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6869): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6869): Build Date: 12/12/14 금
I/Adreno-EGL( 6869): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6869): Remote Branch: 
I/Adreno-EGL( 6869): Local Patches: 
I/Adreno-EGL( 6869): Reconstruct Branch: 
,I/GLSActivity( 2128): [ac] getting account id
D/DelayedSyncController( 6733): Delaying sync.
I/GLSUser ( 2128): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
,I/NSApplication( 6869): Starting up...
,I/GoogleURLConnFactory( 2340): Using platform SSLCertificateSocketFactory
I/ActivityManager( 1029): Killing 6427:com.lge.settings.easy/1000 (adj 15): empty #17
W/libprocessgroup( 1029): failed to open /acct/uid_1000/pid_6427/cgroup.procs: No such file or directory
,V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  315): res_queryN name = mtalk.google.com, class = 1, type = 1
I/GLSUser ( 2128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: mail
I/GLSUser ( 2128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> mail without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/CheckinService( 2340): Checking schedule, now: 1454412342025 next: 1454344295582
I/CheckinService( 2340): active receiver: enabled
,I/CheckinService( 2340): Preparing to send checkin request
I/EventLogService( 2340): Accumulating logs since 1454411403617
I/GLSUser ( 2128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/gcm
I/GLSUser ( 2128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/gcm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/libc-netbsd(  315): res_queryN name = mtalk.google.com succeed
V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/iu.SyncManager( 2340): SYNC; picasa accounts
,V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
,D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  2
W/GLSActivity( 2128): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2128): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2128): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2128): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2128): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2128): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2128): 	at android.os.Binder.execTransact(Binder.java:446)
D/NetworkLogImpl( 2340): Loaded NetworkSpeedPredictor
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1412): updateNotificationData: count=3
W/SubscribedFeeds( 2340): Hard error
I/iu.Environment( 2340): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
D/SyncManager( 1029): failed sync operation thalitester@gmail.com u0 (com.google), subscribedfeeds, PERIODIC, currentRunTime 40699, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager( 1029): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), subscribedfeeds, PERIODIC, currentRunTime 150762, reason: Periodic
,D/ChimeraCfgMgr( 2340): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{320ab302 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/ChimeraCfgMgr( 2340): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/PostponalbeReceiver( 6476): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.TIME_SET'.
,I/art     ( 2340): Explicit concurrent mark sweep GC freed 17173(1244KB) AllocSpace objects, 20(320KB) LOS objects, 49% free, 32MB/64MB, paused 14.780ms total 93.529ms
,I/ActivityManager( 1029): Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=6975 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
I/iu.UploadsManager( 2340): num queued entries: 0
I/iu.UploadsManager( 2340): num updated entries: 0
,I/GcmGroups( 2340): Failed to subscribe to group.
I/GcmGroups( 2340): com.google.android.gms.auth.ad: BadAuthentication
I/GcmGroups( 2340): 	at com.google.android.gms.auth.p.b(SourceFile:442)
I/GcmGroups( 2340): 	at com.google.android.gms.auth.p.a(SourceFile:365)
I/GcmGroups( 2340): 	at com.google.android.gms.auth.p.a(SourceFile:318)
I/GcmGroups( 2340): 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:443)
I/GcmGroups( 2340): 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:333)
I/GcmGroups( 2340): 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:240)
I/GcmGroups( 2340): 	at com.google.android.gms.gcm.gmsproc.GcmReceiverService.onHandleIntent(SourceFile:50)
I/GcmGroups( 2340): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
I/GcmGroups( 2340): 	at android.os.Handler.dispatchMessage(Handler.java:102)
I/GcmGroups( 2340): 	at android.os.Looper.loop(Looper.java:135)
I/GcmGroups( 2340): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/GcmGroups( 2340): Groups upload failed, retrying in 24000:00:00
I/iu.SyncManager( 2340): NEXT; no task
,I/GLSUser ( 2128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/Kids    ( 2340): [AccountUtils] Account not ready
W/Kids    ( 2340): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2340): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2340): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2340): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2340): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2340): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2340): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2340): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2340): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2340): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2340): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2340): 	at java.lang.Thread.run(Thread.java:818)
,D/ALBootInit( 6975): ====action==>android.intent.action.TIME_SET
D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{320ab302 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/ALBootInit( 6975): Alarm ALBootInit: TIME_SET
D/Alarms  ( 6975): [setNextAlert] start
I/PeopleSync( 2340): onPerformSync() [5005f081]
D/Alarms  ( 6975): [setNextAlert] (1)
D/Alarms  ( 6975):  minTime  = 0
D/Alarms  ( 6975):  -- OK multi -- 0
,E/jeny.kim( 6975): [setNextAlert] setNextAlert  temp_Alarmlink + 
E/jeny.kim( 6975): [setNextAlert]setNextAlert temp_AlarmLinkText + 
,I/ThermalEngine(  335): Thermal-Server: Thermal received msg from  override
,I/Thermal-Lib( 3076): Thermal-Lib-Client: Client request sent
,I/CheckinRequestBuilder( 2340): Checkin reason type: 12 attempt count: 1
D/WifiService( 1029): New client listening to asynchronous messages
E/ActivityThread( 2340): Failed to find provider info for com.google.android.wearable.settings
,I/PeopleDatabaseHelper( 2340): cleanUpNonGplusAccounts done.
V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GoogleURLConnFactory( 2128): Using platform SSLCertificateSocketFactory
I/art     ( 1029): Explicit concurrent mark sweep GC freed 28794(1230KB) AllocSpace objects, 4(448KB) LOS objects, 33% free, 44MB/66MB, paused 1.526ms total 86.962ms
,I/CommonUtil( 6975): BUILD Country: EU
D/GCM     ( 2128): Connected
D/Alarms  ( 6975): broadcastToWidgetProvider : false
,I/GLSUser ( 2128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
W/Uploader( 2128): No account for auth token provided
V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Alarms  ( 6975): Enter formatDayAndTime(final Context context, long timeInMiliSec)
D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  315): res_queryN name = play.googleapis.com, class = 1, type = 1
,V/SettingsProvider( 1029): call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
I/DigitalAppWidgetProvider( 6975): onReceive: android.intent.action.TIME_SET
D/LgeQuickCoverNLService( 1412): onNotificationPosted
W/GLSActivity( 2128): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2128): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2128): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2128): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2128): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2128): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2128): 	at android.os.Binder.execTransact(Binder.java:446)
V/DigitalAppWidgetProvider( 6975): cancelAlarmOnQuarterHour android.app.ReceiverRestrictedContext@368bf2cb
D/SmartCoverUpdateMonitor( 1412): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1412): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1412): handleNotificationPosted(true)
D/QuickCircle( 1412): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1412): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
,D/LgeQuickCoverNotificationData( 1412): post do just update job
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
E/BooksAccountManager( 6695): Authentication error
E/BooksAccountManager( 6695): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6695): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6695): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6695): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6695): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6695): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6695): null auth token
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
V/DigitalAppWidgetProvider( 6975): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@368bf2cb
E/LgeQuickCoverOverlayWindow( 1412): updateNotificationData: count=3
D/QuickCoverProvider( 6975): onReceiver
D/WeatherAncestor( 6845): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 12:25:42
,D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{320ab302 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/indal   ( 1412): SmartCoverWidgetContext createApplicationContext
I/indal   ( 1412): SmartCoverWidgetContext createApplicationContext
D/Weather.Utils( 6845): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6845): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6845): 2 : This is isUpdating : false
D/WeatherService( 6845): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@31926aa8
D/ForecastDataCache( 6845): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 6845): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 6845): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 6845): 2 : set auto-update time : 2/2 15:25
,D/WeatherAncestor( 6845): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 12:25:42
D/libc-netbsd(  315): res_queryN name = play.googleapis.com succeed
,D/GCM     ( 2128): Message class com.google.f.a.a.p
,I/ActivityManager( 1029): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=7008 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
I/ActivityManager( 1029): Killing 6082:com.lge.bnr/1000 (adj 15): empty #17
W/ApiaryClient( 6695): Error response from books API: {
W/ApiaryClient( 6695):  "error": {
W/ApiaryClient( 6695):   "errors": [
W/ApiaryClient( 6695):    {
W/ApiaryClient( 6695):     "domain": "global",
W/ApiaryClient( 6695):     "reason": "required",
W/ApiaryClient( 6695):     "message": "Login Required",
W/ApiaryClient( 6695):     "locationType": "header",
W/ApiaryClient( 6695):     "location": "Authorization"
W/ApiaryClient( 6695):    }
W/ApiaryClient( 6695):   ],
W/ApiaryClient( 6695):   "code": 401,
W/ApiaryClient( 6695):   "message": "Login Required"
W/ApiaryClient( 6695):  }
W/ApiaryClient( 6695): }
W/ApiaryClient( 6695): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6695): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7581685757272136675&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6695): Headers:
W/ApiaryClient( 6695): accept-encoding: [gzip]
W/ApiaryClient( 6695): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6695): gdata-version: 2
,I/art     ( 2128): Explicit concurrent mark sweep GC freed 29986(1694KB) AllocSpace objects, 15(1904KB) LOS objects, 51% free, 30MB/62MB, paused 1.261ms total 42.307ms
W/libprocessgroup( 1029): failed to open /acct/uid_1000/pid_6082/cgroup.procs: No such file or directory
,D/TimeService( 7008): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1454412342599
D/        ( 7008): TimeServiceNative: User Time to be set is 1454412342599
D/QC-time-services( 7008): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 7008): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 7008): Lib:time_genoff_operation: pargs->ts_val = 1454412342599
D/QC-time-services(  374): Daemon: Connection accepted:time_genoff
D/QC-time-services(  374): Daemon:Received base = 2, unit = 1, operation = 0,value = 1454412342599
D/QC-time-services(  374): Daemon:genoff_opr: Base = 2, val = 1454412342599, operation = 0
D/QC-time-services(  374): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS5/12/70 4:37:49
D/QC-time-services(  374): Daemon:Value read from RTC seconds = 14013469000
D/QC-time-services(  374): Daemon:new time 1454412342599 
D/QC-time-services(  374): Daemon: delta 1440398873599 genoff 1440398873599 
D/QC-time-services(  374): Daemon:genoff_persistent_update: Writing genoff = 1440398873599 to memory
D/QC-time-services(  374): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  374): Daemon:time_persistent_memory_opr:Genoff write operation 
D/QC-time-services( 7008): Lib:time_genoff_operation: Send to server  passed!!
,D/QC-time-services(  374): Updating the TOD offset
D/QC-time-services(  374): Daemon:genoff_persistent_update: Writing genoff = 1440398873599 to memory
D/QC-time-services(  374): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  374): Daemon:time_persistent_memory_opr:Genoff write operation 
E/QC-time-services(  374): Daemon:Update to modem bit set
D/QC-time-services(  374): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  374): Daemon: Base = 2, Value being sent to MODEM = 1124434073599
E/QC-time-services( 7008): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
E/QC-time-services(  374): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,E/QC-time-services(  374): Daemon: Time-services: Waiting to acceptconnection
,I/ActivityManager( 1029): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetProvider: pid=7027 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi
I/ActivityManager( 1029): Killing 6347:com.lge.lifetracker/u0a37 (adj 15): empty #17
W/libprocessgroup( 1029): failed to open /acct/uid_10037/pid_6347/cgroup.procs: No such file or directory
,W/Uploader( 2128): No account for auth token provided
I/GLSUser ( 2128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 2128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 7027): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/CalendarApplication( 7027): CalendarApplication.onCreate()
,D/PreferenceKeysParser( 7027): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 7027): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@1623128e, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@46a5aaf, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@1b441ebc, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@1ec68e45, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@2841c99a, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@368bf2cb, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@31926aa8, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@1dc6c9c1, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@b62e566, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@de4f0a7, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@33f78954, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@173540fd, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@1c27f1f2, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@3be5f043, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@26ede6c0, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@819eff9, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@2dbf3b3e, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@e6d4d9f, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@1a2aaeec, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@1c0092b5, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@5efcd4a, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@28e324bb, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@189cdd8, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@3174a531, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@de57416, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@33155197, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@30b9ef84, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@2a3d636d, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@3bcbba2, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@19d37033, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@25a87ff0, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@359c969, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@38ceefee, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@3d4adc8f, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@dadab1c, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@30bc9325, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@28be1cfa, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@2922b2ab, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@31785d08, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@38c83ca1, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@35410ec6, lg_preferences_recent,_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@3257ce87,
I/PeopleSync( 2340): Setting subscription: result=true [5005f081]
D/GeneralPreferenceUtils( 7027): [migratePrefrenceKeys] Exit: Version(44001600) >= 42001300
V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
,D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/Config  ( 7027): [init]
D/LgeQuickCoverNLService( 1412): onNotificationPosted
I/Config  ( 7027): LGCalendar ver.4.40.16
I/Config  ( 7027): start check model
I/Config  ( 7027): start check native_ca
I/Config  ( 7027): Config Operator=OPEN, Country=EU
D/SmartCoverUpdateMonitor( 1412): received broadcast com.lge.intent.action.NLDataPosted
D/Config  ( 7027): [setDefaultValuesToPref]
E/SmartCoverUpdateMonitor( 1412): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1412): handleNotificationPosted(true)
D/Config  ( 7027): [parseProfiles]
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
D/ProfilesParser( 7027): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 7027): [debug_displayParseInfos] profile.operator = null
D/Config  ( 7027): [updateProfiletoCountryInfo]
D/GeneralPreference( 7027): [checkAndMigrateOldPreference]
I/PeopleSync( 2340): Starting sync, feed=null [5005f081]
W/CheckinRequestBuilder( 2340): awaiting user notification for token
,D/QuickStatusbarLayout( 1412): Notification difference=198
,D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{320ab302 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
E/AgendaWidgetManager( 7027): [updateWidgets] 
,W/Uploader( 2128): No account for auth token provided
I/ActivityManager( 1029): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7050 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/Uploader( 2128): No account for auth token provided
I/InitNotificationRingtoneService( 7027): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 7027): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/41
,W/ResourcesManager( 7050): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7050): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/MonthWidgetProvider( 7027): [onReceive]
D/CalendarWidgetProvider( 7027): [onReceive]
D/CalendarWidgetProvider( 7027): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.MonthWidgetProvider }
I/AlertUtils( 7027): [getCalendarNotiSoundURIFromCursor] getCount()= 21
D/CalendarTypeController( 7027): [onUpdateAndInitCalendarTime]
D/WeekWidgetProvider( 7027): [onReceive]
,D/CalendarWidgetProvider( 7027): [onReceive]
D/CalendarWidgetProvider( 7027): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.WeekWidgetProvider }
I/MultiDex( 7050): VM with version 2.1.0 has multidex support
D/CalendarTypeController( 7027): [onUpdateAndInitCalendarTime]
I/MultiDex( 7050): install
I/MultiDex( 7050): VM has multidex support, MultiDex support library is disabled.
I/AlertUtils( 7027): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arpeggio.ogg
,W/HolidayIntentService( 7027): onHandleIntent
I/AlertUtils( 7027): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
D/HolidayDataLoader( 7027): readJsonAsset : holiday.json
,I/AlertUtils( 7027): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 7027): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 7027): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 7027): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
,V/JNIHelp ( 7050): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
I/AlertUtils( 7027): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
,I/AlertUtils( 7027): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 7027): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 7027): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Afternoon_Walk.ogg
,D/GCM     ( 2128): GcmService start Intent { act=com.google.android.gcm.intent.SEND flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.gcm.intent.SEND
W/Uploader( 2128):  no longer exists, so no auth token.
I/AlertUtils( 7027): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/DigitalAppWidgetProvider( 6975): onReceive: android.intent.action.ALARM_CHANGED
I/AlertUtils( 7027): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
,E/HolidayIntentService( 7027): onHandleIntent:holiday data empty
I/AlertUtils( 7027): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 7027): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/ActivityManager( 1029): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RequestWriter$NetworkStateReceiver: pid=7074 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/AlertUtils( 7027): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
,I/AlertUtils( 7027): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/41
W/BaseAppContext( 2340): Using Auth Proxy for data requests.
I/AlertUtils( 7027): set default noti to content://media/internal/audio/media/41
W/ActivityThread( 7050): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7050): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@326b6777: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7050): Installed default security provider GmsCore_OpenSSL
I/InitNotificationRingtoneService( 7027): End InitializeAlertRingtoneService.onHandleIntent
I/ActivityManager( 1029): Killing 6400:com.lge.sync/1000 (adj 15): empty #17
,W/libprocessgroup( 1029): failed to open /acct/uid_1000/pid_6400/cgroup.procs: No such file or directory
W/BaseAppContext( 2340): Using Auth Proxy for data requests.
,W/Uploader( 2128): No account for auth token provided
W/BaseAppContext( 2340): Using Auth Proxy for data requests.
,W/ResourcesManager( 7074): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=4.9, 0.0, 0.0  rx=3.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1581569917] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-56 f=2412 sc=60 link=72 tx=4.9, 0.0, 0.0  rx=3.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1581569916] gl rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,I/PeopleSync( 2340): Sync start: cannotHavePeople=true isPageExistenceCheckOnly=false
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,W/GLSActivity( 2128): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2128): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2128): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2128): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2128): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2128): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2128): 	at android.os.Binder.execTransact(Binder.java:446)
D/WVCdm   (  320): Instantiating CDM.
I/WVCdm   (  320): CdmEngine::OpenSession
I/WVCdm   (  320): Level3 Library Sep 25 2014 17:10:03
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
E/BooksAccountManager( 6695): Authentication error
E/BooksAccountManager( 6695): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6695): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6695): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6695): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6695): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6695): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6695): null auth token
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgDataFeature( 7074): LgDataFeature() Constructor: none
D/LgDataFeature( 7074): LgDataFeature() Constructor Done, null
E/LgeQuickCoverOverlayWindow( 1412): updateNotificationData: count=3
,W/WVCdm   (  320): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{320ab302 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,I/GLSUser ( 2128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.media.upload https://www.googleapis.com/auth/plus.pages.manage https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.profiles.read https://www.googleapis.com/auth/plus.profiles.write https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/plus.applications.manage https://www.googleapis.com/auth/plus.settings
I/GLSUser ( 2128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.media.upload https://www.googleapis.com/auth/plus.pages.manage https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.profiles.read https://www.googleapis.com/auth/plus.profiles.write https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/plus.applications.manage https://www.googleapis.com/auth/plus.settings without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/DrmWidevineDash(  320): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  320): Service_Initialize: starts!
D/QSEECOMAPI: (  320): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  320): App is not loaded in QSEE
D/QSEECOMAPI: (  320): Loaded image: APP id = 3
,D/DrmWidevineDash(  320): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  320): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb0a43000
E/DrmWidevineDash(  320): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb0a43000
D/DrmWidevineDash(  320): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  320): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  320): hlos api version =  9
D/DrmWidevineDash(  320): tz api version =  8
D/DrmWidevineDash(  320): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  320): OEMCrypto_IsKeyboxValid: starts!
,W/ApiaryClient( 6695): Error response from books API: {
W/ApiaryClient( 6695):  "error": {
W/ApiaryClient( 6695):   "errors": [
W/ApiaryClient( 6695):    {
W/ApiaryClient( 6695):     "domain": "global",
W/ApiaryClient( 6695):     "reason": "required",
W/ApiaryClient( 6695):     "message": "Login Required",
W/ApiaryClient( 6695):     "locationType": "header",
W/ApiaryClient( 6695):     "location": "Authorization"
W/ApiaryClient( 6695):    }
W/ApiaryClient( 6695):   ],
W/ApiaryClient( 6695):   "code": 401,
W/ApiaryClient( 6695):   "message": "Login Required"
W/ApiaryClient( 6695):  }
W/ApiaryClient( 6695): }
,W/ApiaryClient( 6695): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6695): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7581685757272136675&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6695): Headers:
W/ApiaryClient( 6695): accept-encoding: [gzip]
W/ApiaryClient( 6695): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6695): gdata-version: 2
I/Babel   ( 7074): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 7074): MmsConfig.loadMmsSettings
,I/Babel   ( 7074): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
I/Babel   ( 7074): MmsConfig.loadFromDatabase
D/DrmWidevineDash(  320): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  320): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  320): OEMCrypto_OpenSession: starts! SID=0xab307940
D/DrmWidevineDash(  320): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  320): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  320): OEMCrypto_GetRandom: starts! randomData=0xb1426888, dataLength=8
D/DrmWidevineDash(  320): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  320): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb579f200, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  320): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  320): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  320): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  320): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  320): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  320): OEMCrypto_GetDeviceID: starts! deviceID=0xb1480840, idLength=0xb0eff710
E/Babel   ( 7074): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 7074): MmsConfig.loadFromResources
I/GoogleURLConnFactory( 7050): Using platform SSLCertificateSocketFactory
E/Babel   ( 7074): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 7074): MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,D/DrmWidevineDash(  320): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  320): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  320): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  320): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  320): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  320): OEMCrypto_GetHDCPCapability: starts!
I/PeopleSync( 2340): Sync finished, successful=false, took 130ms
D/DrmWidevineDash(  320): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  320): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  320): hlos api version =  9
D/DrmWidevineDash(  320): tz api version =  8
D/DrmWidevineDash(  320): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  320): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  320): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  320): PrepareKeyRequest: nonce=4140444862
D/DrmWidevineDash(  320): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb14bf200
D/DrmWidevineDash(  320): message_length=1597, signature=0xb17442c0, signature_length=2968516340
,D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  315): res_queryN name = www.googleapis.com, class = 1, type = 1
D/libc-netbsd(  315): res_queryN name = www.googleapis.com succeed
W/Settings( 7074): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/DrmWidevineDash(  320): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  320): CdmEngine::CloseSession
D/DrmWidevineDash(  320): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  320): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  320): L3 Terminate.
D/DrmWidevineDash(  320): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  320): Service_Uninitialize: starts!
D/QSEECOMAPI: (  320): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  320): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  320): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  320): OEMCrypto_Terminate: ends! returns 0
W/AudioCapabilities( 7074): Unsupported mime audio/evrc
W/AudioCapabilities( 7074): Unsupported mime audio/qcelp
I/PeopleSync( 2340): Cannot authenticate [5005f081]
I/PeopleSync( 2340): com.google.android.gms.auth.ad: BadAuthentication
I/PeopleSync( 2340): 	at com.google.android.gms.auth.p.b(SourceFile:442)
I/PeopleSync( 2340): 	at com.google.android.gms.auth.p.a(SourceFile:365)
I/PeopleSync( 2340): 	at com.google.android.gms.auth.p.a(SourceFile:310)
I/PeopleSync( 2340): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
I/PeopleSync( 2340): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
I/PeopleSync( 2340): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
I/PeopleSync( 2340): 	at com.google.android.gms.people.service.g.b(SourceFile:171)
I/PeopleSync( 2340): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
I/PeopleSync( 2340): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
I/PeopleSync( 2340): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
I/PeopleSync( 2340): 	at com.google.android.gms.plus.service.v2whitelisted.b.a(SourceFile:1184)
I/PeopleSync( 2340): 	at com.google.android.gms.people.sync.aa.g(SourceFile:1086)
I/PeopleSync( 2340): 	at com.google.android.gms.people.sync.aa.a(SourceFile:241)
I/PeopleSync( 2340): 	at com.google.android.gms.people.sync.s.a(SourceFile:283)
I/PeopleSync( 2340): 	at com.google.android.gms.people.sync.s.a(SourceFile:191)
I/PeopleSync( 2340): 	at com.google.android.gms.people.sync.s.a(SourceFile:93)
I/PeopleSync( 2340): 	at com.google.android.gms.common.j.a.onPerformSync(SourceFile:81)
I/PeopleSync( 2340): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
W/VideoCapabilities( 7074): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7074): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 7074): Unsupported mime audio/qcelp
W/AudioCapabilities( 7074): Unsupported mime audio/evrc
W/VideoCapabilities( 7074): Unsupported mime video/x-ms-wmv
D/WeatherAncestor( 6845): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 12:25:43
,D/Weather.Utils( 6845): 2 : the weather widgets(using time tick) are gone.
W/VideoCapabilities( 7074): Unsupported mime video/divx
D/Weather.Utils( 6845): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6845): 2 : This is isUpdating : false
D/Weather_cast( 6845): 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
D/WeatherAncestor( 6845): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 12:25:43
W/VideoCapabilities( 7074): Unsupported mime video/divx311
W/VideoCapabilities( 7074): Unsupported mime video/divx4
D/GCM     ( 2128): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
W/VideoCapabilities( 7074): Unsupported mime video/mp4v-esdp
D/AuthorizationBluetoothService( 2128): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/ResourcesManager( 7074): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7074): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/GmsCoreStatsServiceLauncher( 2340): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
I/VideoCapabilities( 7074): Unsupported profile 4 for video/mp4v-es
,W/AudioCapabilities( 7074): Unsupported mime audio/eac3
I/ActivityManager( 1029): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=7111 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
W/AudioCapabilities( 7074): Unsupported mime audio/ac3
W/AudioCapabilities( 7074): Unsupported mime audio/g726
,D/LocationInitializer( 2340): Restart initialization of location
W/AudioCapabilities( 7074): Unsupported mime audio/wma-voice
W/AudioCapabilities( 7074): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7074): Unsupported mime audio/adpcm
V/JNIHelp ( 7074): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/VideoCapabilities( 7074): Unsupported mime video/theora
W/VideoCapabilities( 7074): Unsupported mime video/mjpg
W/System  ( 7074): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/system/app/Hangouts/Hangouts.apk"],nativeLibraryDirectories=[/system/app/Hangouts/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7074): Installed default security provider GmsCore_OpenSSL
,I/art     ( 1029): Explicit concurrent mark sweep GC freed 14142(709KB) AllocSpace objects, 5(464KB) LOS objects, 33% free, 44MB/66MB, paused 1.144ms total 67.372ms
,I/PeopleSync( 2340): ***Sync finished***, duration: 1686 [5005f081]
W/ResourcesManager( 7111): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7111): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 7111): VM with version 2.1.0 has multidex support
I/MultiDex( 7111): install
I/MultiDex( 7111): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 7111): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/SyncManager( 1029): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.gms.people, PERIODIC, currentRunTime 40811, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager( 1029): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.gms.people, PERIODIC, currentRunTime 152697, reason: Periodic
I/GLSUser ( 2128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native
,I/GLSUser ( 2128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityThread( 7111): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7111): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@326b6777: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7111): Installed default security provider GmsCore_OpenSSL
D/AuthorizationBluetoothService( 2128): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/GCM     ( 2128): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/ActivityManager( 1029): Start proc com.google.android.syncadapters.calendar for service com.google.android.syncadapters.calendar/.CalendarSyncAdapterService: pid=7136 uid=10069 gids={50069, 9997, 3003} abi=armeabi-v7a
,E/Babel   ( 7074): UserRecoverableAuthException.
E/Babel   ( 7074): cfq: BadAuthentication
E/Babel   ( 7074): 	at cfn.a(Unknown Source)
E/Babel   ( 7074): 	at f.a(PG:191)
E/Babel   ( 7074): 	at ava.a(PG:88)
E/Babel   ( 7074): 	at ava.a(PG:128)
E/Babel   ( 7074): 	at bjs.a(PG:255)
E/Babel   ( 7074): 	at bep.a(PG:602)
E/Babel   ( 7074): 	at bep.a(PG:469)
E/Babel   ( 7074): 	at bpo.run(PG:1141)
E/Babel   ( 7074): Error getting auth token
E/Babel   ( 7074): bxl
E/Babel   ( 7074): 	at f.a(PG:201)
E/Babel   ( 7074): 	at ava.a(PG:88)
E/Babel   ( 7074): 	at ava.a(PG:128)
E/Babel   ( 7074): 	at bjs.a(PG:255)
E/Babel   ( 7074): 	at bep.a(PG:602)
E/Babel   ( 7074): 	at bep.a(PG:469)
E/Babel   ( 7074): 	at bpo.run(PG:1141)
I/Babel_RequestWriter( 7074): error sending REQ[fc:12; creat:1454093426768; type:bev-160892552]; took 101 ms (error code == 100)
E/Babel   ( 7074): Account registration failedRedacted-21
E/Babel   ( 7074): bph: null -- null
E/Babel   ( 7074): 	at ava.a(PG:120)
E/Babel   ( 7074): 	at ava.a(PG:128)
E/Babel   ( 7074): 	at bjs.a(PG:255)
E/Babel   ( 7074): 	at bep.a(PG:602)
E/Babel   ( 7074): 	at bep.a(PG:469)
E/Babel   ( 7074): 	at bpo.run(PG:1141)
I/Babel   ( 7074): Account setup failed with error state:106 account:Redacted-21
I/Babel   ( 7074): Account sign in complete with state 106account: Redacted-21
V/GmsCoreStatsServiceLauncher( 2340): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
I/art     (  355): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 193us total 11.707ms
D/WearableService( 7111): callingUid 10005, callindPid: 7111
I/art     (  355): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 192us total 8.938ms
,I/art     (  355): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 191us total 8.945ms
E/MDM     ( 1831): [86] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/art     ( 7074): Note: end time exceeds epoch: 
D/LocationInitializer( 2340): Restart initialization of location
E/MDM     ( 1831): [86] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,W/AbstractGoogleClient( 7136): Application name is not set. Call Builder#setApplicationName.
,I/ActivityManager( 1029): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=7158 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi
,I/GLSUser ( 2128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native
I/GLSUser ( 2128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 7158): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,W/ResourcesManager( 2128): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1412): onNotificationPosted
D/SmartCoverUpdateMonitor( 1412): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1412): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1412): handleNotificationPosted(true)
D/QuickCircle( 1412): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1412): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post do just update job
,D/LgeQuickCoverNotificationData( 1412): showAll3
,D/LgeQuickCoverNotificationData( 1412): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
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
D/CalendarProvider2( 7158): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@15a0f990
E/Babel   ( 7074): Unexpected exception while authenticating.
E/Babel   ( 7074): cfr: User intervention required. Notification has been pushed.
E/Babel   ( 7074): 	at cfn.b(Unknown Source)
E/Babel   ( 7074): 	at cfn.a(Unknown Source)
E/Babel   ( 7074): 	at f.a(PG:188)
E/Babel   ( 7074): 	at ava.b(PG:143)
E/Babel   ( 7074): 	at bnr.run(PG:5415)
E/Babel   ( 7074): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 7074): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 7074): 	at java.lang.Thread.run(Thread.java:818)
D/CalendarProvider2( 7158): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 7158): Created com.android.providers.calendar.CalendarAlarmManager@1ec68e45(com.android.providers.calendar.CalendarProvider2@15a0f990)
D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{320ab302 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/dex2oat ( 7177): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_dg_cache/C8B498C535D74E10EB2660A2D73552617B0E1F6D/the.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_dg_cache/C8B498C535D74E10EB2660A2D73552617B0E1F6D/opt/the.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 7177): dex2oat took 22.529ms (threads: 4)
,I/art     ( 2128): Explicit concurrent mark sweep GC freed 29559(1673KB) AllocSpace objects, 11(1351KB) LOS objects, 50% free, 30MB/62MB, paused 769us total 23.237ms
,I/GLSUser ( 2128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.calendar, service: oauth2:https://www.googleapis.com/auth/calendar
,I/GLSUser ( 2128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/calendar without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
,I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
E/CalendarSyncAdapter( 7136): Exception in onPerformLoggedSync 
E/CalendarSyncAdapter( 7136): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/CalendarSyncAdapter( 7136): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(GoogleRequestInitializer.java:152)
E/CalendarSyncAdapter( 7136): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(GoogleRequestInitializer.java:89)
E/CalendarSyncAdapter( 7136): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:858)
E/CalendarSyncAdapter( 7136): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(AbstractGoogleClientRequest.java:410)
E/CalendarSyncAdapter( 7136): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(AbstractGoogleClientRequest.java:343)
E/CalendarSyncAdapter( 7136): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(AbstractGoogleClientRequest.java:460)
E/CalendarSyncAdapter( 7136): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.processAccountCalendars(CalendarSyncAdapterApiary.java:1510)
E/CalendarSyncAdapter( 7136): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.updateCalendarsFromServerFeed(CalendarSyncAdapterApiary.java:1024)
E/CalendarSyncAdapter( 7136): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.getServerDiffs(CalendarSyncAdapterApiary.java:906)
E/CalendarSyncAdapter( 7136): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.performSync(CalendarSyncAdapterApiary.java:430)
E/CalendarSyncAdapter( 7136): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.onPerformLoggedSync(CalendarSyncAdapterApiary.java:335)
E/CalendarSyncAdapter( 7136): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
E/CalendarSyncAdapter( 7136): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/CalendarSyncAdapter( 7136): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notif,ication has been pushed.
E/CalendarSyncAdapter( 7136): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/CalendarSyncAdapter( 7136): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/CalendarSyncAdapter( 7136): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(GoogleRequestInitializer.java:140)
E/CalendarSyncAdapter( 7136): 	... 12 more
I/ActivityManager( 1029): Killing 6055:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,I/QRemote ( 6511): [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
W/System.err( 6511): android.os.DeadObjectException
W/System.err( 6511): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6511): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6511): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 6511): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
W/System.err( 6511): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 6511): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 6511): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6511): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6511): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6511): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 6511): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6511): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6511): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 6511): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 6511): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 6511): android.os.DeadObjectException
W/System.err( 6511): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6511): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6511): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 6511): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
W/System.err( 6511): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{320ab302 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/System.err( 6511): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 6511): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6511): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6511): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6511): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 6511): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6511): 	at java.lang.reflect.Method.invoke(Method.java:372)
,W/System.err( 6511): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 6511): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 6511): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/QRemote ( 6511): [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
E/BooksSync( 6695): Soft error: 
E/BooksSync( 6695): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6695): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7581685757272136675&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6695): Headers:
E/BooksSync( 6695): accept-encoding: [gzip]
E/BooksSync( 6695): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6695): gdata-version: 2
E/BooksSync( 6695): 
E/BooksSync( 6695): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6695): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6695): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6695): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6695): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6695): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6695): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6695): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6695): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6695): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6695): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6695): {
E/BooksSync( 6695):  "error": {
E/BooksSync( 6695):   "errors": [
E/BooksSync( 6695):    {
E/BooksSync( 6695):     "domain": "global",
E/BooksSync( 6695):     "reason": "required",
E/BooksSync( 6695):     "message": "Login Required",
E/BooksSync( 6695):     "locationType": "header",
E/BooksSync( 6695):     "location": "Authorization"
E/BooksSync( 6695):    }
E/BooksSync( 6695):   ],
E/BooksSync( 6695):   "code": 401,
E/BooksSync( 6695):   "message": "Login Required"
E/BooksSync( 6695):  }
E/BooksSync( 6695): }
E/BooksSync( 6695): 
E/BooksSync( 6695): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6695): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6695): 	... 8 more
E/BooksSync( 6695): Sync error
E/BooksSync( 6695): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6695): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-7581685757272136675&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6695): Headers:
E/BooksSync( 6695): accept-encoding: [gzip]
E/BooksSync( 6695): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6695): gdata-version: 2
E/BooksSync( 6695): 
E/BooksSync( 6695): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6695): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( ,6695): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6695): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6695): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6695): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6695): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6695): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6695): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6695): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6695): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6695): {
E/BooksSync( 6695):  "error": {
E/BooksSync( 6695):   "errors": [
E/BooksSync( 6695):    {
E/BooksSync( 6695):     "domain": "global",
E/BooksSync( 6695):     "reason": "required",
E/BooksSync( 6695):     "message": "Login Required",
E/BooksSync( 6695):     "locationType": "header",
E/BooksSync( 6695):     "location": "Authorization"
E/BooksSync( 6695):    }
E/BooksSync( 6695):   ],
E/BooksSync( 6695):   "code": 401,
E/BooksSync( 6695):   "message": "Login Required"
E/BooksSync( 6695):  }
E/BooksSync( 6695): }
E/BooksSync( 6695): 
E/BooksSync( 6695): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6695): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6695): 	... 8 more
,I/BooksSync( 6695): Finished books sync
E/libprocessgroup( 1029): failed to kill 1 processes for processgroup 6055
,I/dex2oat ( 7187): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=37 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,W/ActivityManager( 1029): Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,I/jxcore-log( 6215): Test app app.js loaded
I/jxcore-log( 6215): 
V/AlarmManager( 1029): ELAPSED_WAKEUP set : Alarm{2c5c03e6 type 2 when 121536 com.android.providers.calendar} when 121536
I/chromium( 6215): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/ActivityManager( 1029): Killing 6314:com.android.settings/1000 (adj 15): empty #17
D/QRemote ( 6511): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
I/QRemote ( 6511): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
D/SyncManager( 1029): failed sync operation thalitester@gmail.com u0 (com.google), com.android.calendar, PERIODIC, currentRunTime 40823, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager( 1029): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.calendar, PERIODIC, currentRunTime 154418, reason: Periodic
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6215): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6215): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6215): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6215): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6215): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6215): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6215): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6215): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6215): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6215): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34780fc1 added. We now have 1 listener(s)
,D/WifiService( 1029): Client connection lost with reason: 4
,I/jxcore-log( 6215): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 6215): 
I/dex2oat ( 7187): dex2oat took 57.522ms (threads: 4)
I/Adreno-EGL( 7050): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7050): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7050): Build Date: 12/12/14 금
I/Adreno-EGL( 7050): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7050): Remote Branch: 
I/Adreno-EGL( 7050): Local Patches: 
I/Adreno-EGL( 7050): Reconstruct Branch: 
,W/libprocessgroup( 1029): failed to open /acct/uid_1000/pid_6314/cgroup.procs: No such file or directory
,D/CalendarProviderBroadcastReceiver( 7158): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 7158): [IntentService] WakeLock acquire, start IntentSerivce
I/ActivityManager( 1029): Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7194 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,D/QRemote ( 6511): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,V/QRemote ( 6511): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
D/QRemote ( 6511): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:2072
,D/SyncManager( 1029): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 27086, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/CalendarProvider2( 7158): CalendarProviderIntentService.onCreate()
D/CalendarProvider2( 7158): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 7158): [getOrCreateCalendarAlarmManager]
E/SQLiteLog( 7158): (284) automatic index on view_events(_id)
,D/CalendarProvider2( 7158): [IntentService] Release Lock
D/CalendarProvider2( 7158): CalendarProviderIntentService.onDestroy()
I/ActivityManager( 1029): Killing 5705:com.android.vending/u0a44 (adj 15): empty #17
,D/UEI.SmartControl( 7194): Quickset Services start...
I/UEI.SmartControl( 7194): Manufacture = LGE
D/UEI.SmartControl( 7194): Id = LGNevo
I/Adreno-EGL( 7050): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7050): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7050): Build Date: 12/12/14 금
I/Adreno-EGL( 7050): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7050): Remote Branch: 
I/Adreno-EGL( 7050): Local Patches: 
I/Adreno-EGL( 7050): Reconstruct Branch: 
D/UEI.SmartControl( 7194): File observer start...
,E/UEI.SmartControl( 7194): IR Port is disabled: false
D/UEI.SmartControl( 7194): Starting file observer...
D/UEI.SmartControl( 7194): Extracting JNI libs...
D/UEI.SmartControl( 7194): --- this system supports 32-bit or 64-bit only
W/libprocessgroup( 1029): failed to open /acct/uid_10044/pid_5705/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 7194): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 7194): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7194): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 7194): --- Selecting new region: 6
I/UEI.SmartControl( 7194): Model = LG-D855
D/UEI.SmartControl( 7194): QS Service created
,I/GAV2    ( 6695): Thread[GAThread,5,main]: No campaign data found.
I/UEI.SmartControl( 7194): Service initServices...
D/UEI.SmartControl( 7194): QS start get config
,I/GCoreUlr( 1831): Uploading GCM registration ID for account#2#
D/UEI.SmartControl( 7194): Loading JNI Libs...
I/WVCdm   (  320): CdmEngine::OpenSession
I/WVCdm   (  320): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  320): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  320): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  320): Service_Initialize: starts!
D/QSEECOMAPI: (  320): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  320): App is not loaded in QSEE
D/QSEECOMAPI: (  320): Loaded image: APP id = 3
D/DrmWidevineDash(  320): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  320): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb0a43000
E/DrmWidevineDash(  320): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb0a43000
I/ActivityManager( 1029): Start proc com.google.android.gm for service com.google.android.gm/.provider.MailSyncAdapterService: pid=7227 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/DrmWidevineDash(  320): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  320): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  320): hlos api version =  9
D/DrmWidevineDash(  320): tz api version =  8
D/DrmWidevineDash(  320): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  320): OEMCrypto_IsKeyboxValid: starts!
D/DrmWidevineDash(  320): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  320): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  320): OEMCrypto_OpenSession: starts! SID=0xb0eff940
,D/DrmWidevineDash(  320): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  320): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  320): OEMCrypto_GetRandom: starts! randomData=0xb16994d0, dataLength=8
D/DrmWidevineDash(  320): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  320): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb14d7000, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  320): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  320): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  320): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  320): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  320): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  320): OEMCrypto_GetDeviceID: starts! deviceID=0xb1480880, idLength=0xab307710
D/DrmWidevineDash(  320): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  320): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  320): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  320): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  320): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  320): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  320): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  320): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  320): hlos api version =  9
D/DrmWidevineDash(  320): tz api version =  8
D/DrmWidevineDash(  320): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  320): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  320): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  320): PrepareKeyRequest: nonce=141354204
D/DrmWidevineDash(  320): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb57aa600
D/DrmWidevineDash(  320): message_length=1631, signature=0xb547fb00, signature_length=2872080116
,W/BaseAppContext( 1831): Using Auth Proxy for data requests.
,I/GLSUser ( 1831): [ChannelManager] Attempting to channel bind connection HttpClient.
,I/GLSUser ( 1831): [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
,D/DrmWidevineDash(  320): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  320): CdmEngine::CloseSession
D/DrmWidevineDash(  320): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  320): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  320): L3 Terminate.
D/DrmWidevineDash(  320): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  320): Service_Uninitialize: starts!
D/QSEECOMAPI: (  320): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  320): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  320): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  320): OEMCrypto_Terminate: ends! returns 0
W/ActivityManager( 1029): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/ActivityThread( 7227): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
W/ActivityManager( 1029): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/LgDataFeature( 7050): LgDataFeature() Constructor: none
D/LgDataFeature( 7050): LgDataFeature() Constructor Done, null
I/Adreno-EGL( 7050): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7050): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7050): Build Date: 12/12/14 금
I/Adreno-EGL( 7050): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7050): Remote Branch: 
I/Adreno-EGL( 7050): Local Patches: 
I/Adreno-EGL( 7050): Reconstruct Branch: 
W/ActivityManager( 1029): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/Gmail   ( 7227): getAccountsCursor
W/ActivityManager( 1029): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/ActivityManager( 1029): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/Gmail   ( 7227): Observing account changes for notifications
V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/userlocation.reporting
I/GLSUser ( 2128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/userlocation.reporting without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/ActivityManager( 1029): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 7227): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
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
,I/CheckinRequestBuilder( 2340): Classify the device as Phone.
D/SyncManager( 1029): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.location.reporting, PERIODIC, currentRunTime 40882, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager( 1029): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.location.reporting, PERIODIC, currentRunTime 155027, reason: Periodic
W/ActivityManager( 1029): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/UEI.SmartControl( 7194): Supports setup maps: true
,D/UEI.SmartControl( 7194): QS start statue = true Error code = 0
I/UEI.SmartControl( 7194): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 7194): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 7194): ### init IR Blaster...
I/Gmail   ( 7227): getAccountsCursor
E/Gmail   ( 7227): Error finding the version of the Email provider.....
E/Gmail   ( 7227): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 7227): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 7227): 	at com.google.android.gm.EmailMigrationService.aU(SourceFile:1235)
E/Gmail   ( 7227): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:187)
E/Gmail   ( 7227): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 7227): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 7227): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 7227): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 7227): We do not support migrating this version of the Email provider.
D/serial_port( 7194): Configuring serial port
,V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/UEI.SmartControl( 7194): UEIBLaster setting for 616
I/UEI.SmartControl( 7194): Setting serial record hearder size = 2
I/UEI.SmartControl( 7194): configuring settings for MAXQ616
I/UEI.SmartControl( 7194): Get version...
V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/UEI.SmartControl( 7194): serial port data available: 21
D/UEI.SmartControl( 7194): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 7194): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 7194): QS saving settings...
D/UEI.SmartControl( 7194): IR Blaster version: 25672567
,E/SQLiteLog( 7227): (283) recovered 1411 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
I/art     ( 2340): Explicit concurrent mark sweep GC freed 14100(933KB) AllocSpace objects, 6(96KB) LOS objects, 49% free, 32MB/64MB, paused 3.134ms total 57.857ms
D/UEI.SmartControl( 7194): serial port data available: 4
,I/art     ( 1029): Explicit concurrent mark sweep GC freed 25505(1092KB) AllocSpace objects, 4(320KB) LOS objects, 33% free, 44MB/66MB, paused 1.466ms total 109.528ms
,I/UEI.SmartControl( 7194): Device manager: loading config....
D/UEI.SmartControl( 7194): ----------- loading internal config...
W/ContextImpl( 7194): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
E/UEI.SmartControl( 7194): Services init done
D/UEI.SmartControl( 7194): QS Service init finished
D/UEI.SmartControl( 7194): QS Service version name: 2.1.91
,D/UEI.SmartControl( 7194): QS Service version code: 201091
D/UEI.SmartControl( 7194): Service requested: Control
W/Gmail   ( 7227): Sync started for account: account:61035162
E/UEI.SmartControl( 7194): Loading SETTINGS...
D/UEI.SmartControl( 7194): -- Open brand translation xml: brands_translations_ko
D/UEI.SmartControl( 7194): Request IControl service: devices are loaded...
,I/ActivityManager( 1029): Killing 6672:com.lge.appbox.client/u0a11 (adj 15): empty #17
I/QRemote ( 6511): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 7194): ------ IControl API: 11
I/UEI.SmartControl( 7194): Registering callback...
I/UEI.SmartControl( 7194): ------ IControl API: 19
I/UEI.SmartControl( 7194): Registering Services Ready callback...
I/UEI.SmartControl( 7194): Notify client services are ready...
I/QRemote ( 6511): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
I/UEI.SmartControl( 7194): Notify AllClients services are ready: 0
I/QRemote ( 6511): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/UEI.SmartControl( 7194): -----service ready thread exits
D/QRemote ( 6511): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 6511): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 6511): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 6511): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 7194): ------ IControl API: 8
D/QRemote ( 6511): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 6511): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 6511): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 6511): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 6511): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6511): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
I/Gmail   ( 7227): notifyAccountChanged
I/Gmail   ( 7227): getAccountsCursor
,D/UEI.SmartControl( 7194): Internal service binding...
W/libprocessgroup( 1029): failed to open /acct/uid_10011/pid_6672/cgroup.procs: No such file or directory
D/QRemote ( 6511): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
I/Gmail   ( 7227): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/QRemote ( 6511): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,D/QRemote ( 6511): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
I/Gmail   ( 7227): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
E/QRemote ( 6511): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6511): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 6511): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6511): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 6511): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 6511): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1454412345602]
I/Gmail   ( 7227): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 7227): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 7227): notifyAccountChanged
D/QRemote ( 6511): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,V/QRemote ( 6511): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
E/QRemote ( 6511): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6511): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 6511): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 6511): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 6511): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 6511): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  315): res_queryN name = android.clients.google.com, class = 1, type = 1
D/QRemote ( 6511): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
I/Gmail   ( 7227): getAccountsCursor
,V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/libc-netbsd(  315): res_queryN name = android.clients.google.com succeed
,I/Gmail   ( 7227): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 5310, normalSync: true
W/ResourcesManager( 7227): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7227): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7227): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/System  ( 7227): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[directory "."],nativeLibraryDirectories=[/vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7227): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/reminders
I/GLSUser ( 2128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/reminders without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/ReminderSync( 2340): AuthError [T SyncAdapterThread-1:id=279:priority=5:group=main]
,D/SyncManager( 1029): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.gms.reminders, PERIODIC, currentRunTime 40983, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager( 1029): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.gms.reminders, PERIODIC, currentRunTime 153043, reason: Periodic
,I/ActivityManager( 1029): Start proc com.google.android.apps.docs for service com.google.android.apps.docs/.sync.syncadapter.DocsSyncAdapterService: pid=7287 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/art     ( 2128): Explicit concurrent mark sweep GC freed 11936(644KB) AllocSpace objects, 3(432KB) LOS objects, 50% free, 30MB/62MB, paused 1.694ms total 66.624ms
I/GLSUser ( 2128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gm, service: mail
I/GLSUser ( 2128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> mail without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2128): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2128): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2128): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2128): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2128): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2128): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2128): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1412): onNotificationPosted
V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1412): updateNotificationData: count=3
I/GLSUser ( 2128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gm, service: mail
,I/GLSUser ( 2128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> mail without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{320ab302 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/DocsApplication( 7287): Installing DEX configuration.
D/DexInstaller( 7287): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
,I/PackageInfoHelper( 7287): Provided clientMode=RELEASE, packageInfo=PackageInfo{15a0f990 com.google.android.apps.docs}
D/TAG     ( 7287): onCreate()
D/CrossAppStateProvider( 7287): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1412): onNotificationPosted
D/SmartCoverUpdateMonitor( 1412): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1412): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1412): handleNotificationPosted(true)
D/QuickCircle( 1412): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1412): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
,D/LgeQuickCoverNotificationData( 1412): post do just update job
D/LgeQuickCoverNotificationData( 1412): showAll3
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1412): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1412): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  1
W/GLSActivity( 2128): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2128): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2128): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2128): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2128): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2128): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2128): 	at android.os.Binder.execTransact(Binder.java:446)
,D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1412): updateNotificationData: count=3
I/Gmail   ( 7227): notifyAccountChanged
I/Gmail   ( 7227): getAccountsCursor
,V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{320ab302 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/Gmail   ( 7227): notifyAccountChanged
W/Gmail   ( 7227): Sync complete for account: account:61035162
I/Gmail   ( 7227): getAccountsCursor
,V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/CheckinTask( 2340): Sending checkin request (9678 bytes)
,D/SyncManager( 1029): failed sync operation thalitester@gmail.com u0 (com.google), gmail-ls, PERIODIC, currentRunTime 40933, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager( 1029): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), gmail-ls, PERIODIC, currentRunTime 155201, reason: Periodic
I/SyncAdapterService( 6869): Ignoring sync request for non-current account
,I/ActivityManager( 1029): Killing 6369:com.lge.formmanager/u0a26 (adj 15): empty #17
,W/libprocessgroup( 1029): failed to open /acct/uid_10026/pid_6369/cgroup.procs: No such file or directory
,W/BaseAppContext( 2340): Using Auth Proxy for data requests.
,W/BaseAppContext( 2340): Using Auth Proxy for data requests.
W/BaseAppContext( 2340): Using Auth Proxy for data requests.
,W/BaseAppContext( 2340): Using Auth Proxy for data requests.
W/BaseAppContext( 2340): Using Auth Proxy for data requests.
,W/BaseAppContext( 2340): Using Auth Proxy for data requests.
,W/BaseAppContext( 2340): Using Auth Proxy for data requests.
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-53 f=2412 sc=60 link=72 tx=32.4, 0.0, 0.0  rx=27.8 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1581566908] gl rssi=-53 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-53 f=2412 sc=60 link=72 tx=32.4, 0.0, 0.0  rx=27.8 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1581566907] gl rssi=-53 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/GAV4    ( 6869): Thread[GAThread,5,main]: No campaign data found.
,I/CheckinResponseProcessor( 2340): From server: 12 gservices updates and 0 deletes
D/ChimeraCfgMgr( 2340): Loading module com.google.android.gms.games from APK com.google.android.gms
,I/GoogleHttpClient( 5323): Falling back to old http client 0 java.lang.NoSuchMethodException: <init> [class android.content.Context, class java.lang.String, boolean, boolean]
,V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/CertBlacklister( 1029): Certificate blacklist changed, updating...
I/CertBlacklister( 1029): Certificate blacklist updated
I/GLSUser ( 2128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.music, service: sj
I/GLSUser ( 2128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> sj without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GservicesProvider( 2128): main difference update completed
,I/ActivityManager( 1029): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GservicesChangedReceiver: pid=7326 uid=10008 gids={50008, 9997, 3003} abi=armeabi-v7a
,I/CheckinRequestBuilder( 2340): Checkin reason type: 12 attempt count: 1
E/ActivityThread( 2340): Failed to find provider info for com.google.android.wearable.settings
,V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
W/GLSActivity( 2128): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2128): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2128): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2128): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2128): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2128): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2128): 	at android.os.Binder.execTransact(Binder.java:446)
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
,E/LgeQuickCoverOverlayWindow( 1412): updateNotificationData: count=3
D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{320ab302 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/MusicSyncAdapter( 5323): Sync failed due to an authentication issue.
,D/SyncManager( 1029): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.music.MusicContent, PERIODIC, currentRunTime 41019, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager( 1029): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.music.MusicContent, PERIODIC, currentRunTime 156492, reason: Periodic
,I/ActivityManager( 1029): Start proc com.google.android.videos for service com.google.android.videos/.store.SyncService: pid=7344 uid=10103 gids={50103, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/art     ( 1029): Explicit concurrent mark sweep GC freed 30413(1326KB) AllocSpace objects, 7(496KB) LOS objects, 33% free, 44MB/66MB, paused 1.560ms total 98.240ms
,I/ActivityManager( 1029): Killing 6824:com.lge.drmservice/u0a62 (adj 15): empty #17
,D/LgDataFeature( 7287): LgDataFeature() Constructor: none
D/LgDataFeature( 7287): LgDataFeature() Constructor Done, null
,W/libprocessgroup( 1029): failed to open /acct/uid_10062/pid_6824/cgroup.procs: No such file or directory
,W/GAV2    ( 7287): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ResourcesManager( 7344): Asset path '/system/framework/com.google.widevine.software.drm.jar' does not exist or contains no resources.
I/ContactAccountLoggerTas( 4328): canRun() : Opted Out
I/ActivityManager( 1029): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=7386 uid=10059 gids={50059, 9997, 3003} abi=armeabi-v7a
,D/WifiService( 1029): acquireWifiLockLocked: WifiLock{SyncManager type=1 binder=android.os.BinderProxy@db709b}
I/Search.GservicesUpdateTask( 4328): Updating Gservices keys
D/LgDataFeature( 7326): LgDataFeature() Constructor: none
D/LgDataFeature( 7326): LgDataFeature() Constructor Done, null
,E/UpdateRequestReceiver( 7386): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 7386): Received malformed URL while handling Gservices.CHANGED_ACTION
E/UpdateRequestReceiver( 7386): Received malformed URL while handling Gservices.CHANGED_ACTION
E/UpdateRequestReceiver( 7386): Received malformed URL while handling Gservices.CHANGED_ACTION
I/art     ( 2128): Explicit concurrent mark sweep GC freed 17160(929KB) AllocSpace objects, 8(1152KB) LOS objects, 50% free, 30MB/62MB, paused 854us total 93.264ms
,I/GStaticConfiguration( 4328): #getNewConfigurationUrl [pref=2015_09_15_14_04_18, gservice=2016_01_27_20_58_17
,D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  315): res_queryN name = www.gstatic.com, class = 1, type = 1
,I/ActivityManager( 1029): Killing 6733:com.android.chrome/u0a57 (adj 15): empty #17
,D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  315): res_queryN name = ssl.gstatic.com, class = 1, type = 1
,W/libprocessgroup( 1029): failed to open /acct/uid_10057/pid_6733/cgroup.procs: No such file or directory
,D/libc-netbsd(  315): res_queryN name = www.gstatic.com succeed
,D/libc-netbsd(  315): res_queryN name = ssl.gstatic.com succeed
,I/SystemUpdateService( 2340): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
,D/SystemUpdateService( 2340): onCreate
D/SystemUpdateService( 2340): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
D/GCM     ( 2128): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
,D/SystemEventReceiver( 2340): Received GSERVICES_CHANGED broadcast
I/SystemUpdateService( 2340): cancelUpdate (empty URL)
I/SystemUpdateService( 2340): active receiver: disabled
I/OcrUtils( 2340): Updating ocr activity enabled=false
D/LgDataFeature( 7344): LgDataFeature() Constructor: none
D/LgDataFeature( 7344): LgDataFeature() Constructor Done, null
D/SystemUpdateService( 2340): onDestroy
,I/GCoreUlr( 1831): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,I/art     ( 1831): Explicit concurrent mark sweep GC freed 16485(948KB) AllocSpace objects, 6(96KB) LOS objects, 50% free, 31MB/63MB, paused 772us total 33.527ms
E/DataBuffer( 1831): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@378c3727)
,I/GCoreUlr( 1831): DispatchingService.onCreate()
I/ActivityManager( 1029): Killing 6713:com.android.gallery3d/u0a27 (adj 15): empty #17
,W/libprocessgroup( 1029): failed to open /acct/uid_10027/pid_6713/cgroup.procs: No such file or directory
,I/GCoreUlr( 1831): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,I/art     ( 2340): Explicit concurrent mark sweep GC freed 22056(1357KB) AllocSpace objects, 11(175KB) LOS objects, 49% free, 32MB/64MB, paused 1.051ms total 43.022ms
,I/GLSUser ( 2128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 2128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PlayMovies( 7344): PersistentCache.cleanup:103 Cache is below limit, no need to shrink: [size=0, limit=5242880]
,D/PlayMovies( 7344): TransferService.onCreate:52 creating transfer service
,V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,D/LgeQuickCoverNLService( 1412): onNotificationPosted
I/art     ( 2128): Explicit concurrent mark sweep GC freed 6114(281KB) AllocSpace objects, 0(0B) LOS objects, 50% free, 31MB/63MB, paused 1.539ms total 22.598ms
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
,E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.videos/files/Movies/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/CheckinRequestBuilder( 2340): awaiting user notification for token
W/ContextImpl( 7344): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.videos/files/Movies
W/AudioCapabilities( 7344): Unsupported mime audio/evrc
W/AudioCapabilities( 7344): Unsupported mime audio/qcelp
D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{320ab302 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/VideoCapabilities( 7344): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7344): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 7344): Unsupported mime audio/qcelp
W/AudioCapabilities( 7344): Unsupported mime audio/evrc
I/CheckinRequestBuilder( 2340): Classify the device as Phone.
W/VideoCapabilities( 7344): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 7344): Unsupported mime video/divx
W/VideoCapabilities( 7344): Unsupported mime video/divx311
W/VideoCapabilities( 7344): Unsupported mime video/divx4
I/GLSUser ( 2128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.videos, service: oauth2:https://www.googleapis.com/auth/android_video https://www.googleapis.com/auth/youtube https://www.googleapis.com/auth/pos
I/GLSUser ( 2128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/android_video https://www.googleapis.com/auth/youtube https://www.googleapis.com/auth/pos without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
W/VideoCapabilities( 7344): Unsupported mime video/mp4v-esdp
V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VideoCapabilities( 7344): Unsupported profile 4 for video/mp4v-es
,W/AudioCapabilities( 7344): Unsupported mime audio/eac3
W/AudioCapabilities( 7344): Unsupported mime audio/ac3
W/AudioCapabilities( 7344): Unsupported mime audio/g726
W/AudioCapabilities( 7344): Unsupported mime audio/wma-voice
W/AudioCapabilities( 7344): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7344): Unsupported mime audio/adpcm
W/VideoCapabilities( 7344): Unsupported mime video/theora
,W/VideoCapabilities( 7344): Unsupported mime video/mjpg
I/GCoreUlr( 1831): WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=10, mName='AuthError'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 1831): Unbound from all location providers
V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1412): onNotificationPosted
D/SmartCoverUpdateMonitor( 1412): received broadcast com.lge.intent.action.NLDataPosted
,E/SmartCoverUpdateMonitor( 1412): MSG_NOTIFICATION_POSTED
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
W/ResourcesManager( 2340): Asset path '/system/framework/com.google.widevine.software.drm.jar' does not exist or contains no resources.
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
I/GCoreUlr( 1831): DispatchingService.onDestroy()
E/LgeQuickCoverOverlayWindow( 1412): updateNotificationData: count=3
E/PlayMovies( 7344): GmsAccountManagerWrapper.blockingGetAuthTokenInternal:100 Cannot get user auth
E/PlayMovies( 7344): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/PlayMovies( 7344): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/PlayMovies( 7344): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/PlayMovies( 7344): 	at com.google.android.videos.accounts.GmsAccountManagerWrapper.blockingGetAuthTokenInternal(GmsAccountManagerWrapper.java:85)
E/PlayMovies( 7344): 	at com.google.android.videos.accounts.AccountManagerWrapper.blockingGetAuthToken(AccountManagerWrapper.java:186)
E/PlayMovies( 7344): 	at com.google.android.videos.accounts.AccountManagerWrapper.blockingAuthenticate(AccountManagerWrapper.java:162)
E/PlayMovies( 7344): 	at com.google.android.videos.store.SyncService$SyncAdapter.onPerformSync(SyncService.java:225)
E/PlayMovies( 7344): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{320ab302 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,I/art     ( 2128): Explicit concurrent mark sweep GC freed 6697(333KB) AllocSpace objects, 4(576KB) LOS objects, 50% free, 31MB/63MB, paused 828us total 34.725ms
I/ActivityManager( 1029): Killing 6760:com.lge.email/u0a23 (adj 15): empty #17
,D/SyncManager( 1029): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.videos.sync, PERIODIC, currentRunTime 41027, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager( 1029): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.videos.sync, PERIODIC, currentRunTime 156447, reason: Periodic
I/CheckinTask( 2340): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/art     ( 1029): Explicit concurrent mark sweep GC freed 15689(802KB) AllocSpace objects, 6(352KB) LOS objects, 33% free, 44MB/66MB, paused 1.286ms total 73.081ms
,I/ContactAccountLoggerTas( 4328): canRun() : Opted Out
I/ContactAccountLoggerTas( 4328): canRun() : Opted Out
I/ContactAccountLoggerTas( 4328): canRun() : Opted Out
,W/Search.LoginHelper( 4328): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 4328): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
I/ContactAccountLoggerTas( 4328): canRun() : Opted Out
W/libprocessgroup( 1029): failed to open /acct/uid_10023/pid_6760/cgroup.procs: No such file or directory
,V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GCoreUlr( 1831): Unbound from all location providers
,I/CheckinService( 2340): Checking schedule, now: 1454412348172 next: 1454998378987
I/CheckinService( 2340): active receiver: disabled
,I/GLSUser ( 2128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.docs, service: oauth2: https://www.googleapis.com/auth/drive
I/GLSUser ( 2128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5323): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,I/CheckinService( 2340): Checking schedule, now: 1454412348214 next: 1454998378987
E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/CheckinService( 2340): active receiver: disabled
W/ContextImpl( 5323): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5323): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5323): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ArtDownloadService( 5323): Setting cache size 0
W/ArtDownloadService( 5323): Setting cache size 0
,V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2128): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2128): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2128): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2128): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2128): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2128): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2128): 	at android.os.Binder.execTransact(Binder.java:446)
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
W/PsynchoHelperImpl( 7287): Error fetching or saving configuration
W/PsynchoHelperImpl( 7287): java.io.IOException: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
W/PsynchoHelperImpl( 7287): 	at Op.a(ApiaryPsynchoConfigurationAccessor.java:145)
W/PsynchoHelperImpl( 7287): 	at Op.a(ApiaryPsynchoConfigurationAccessor.java:215)
W/PsynchoHelperImpl( 7287): 	at OQ.a(PsynchoHelperImpl.java:60)
W/PsynchoHelperImpl( 7287): 	at agr.a(DriveSpecificSyncManager.java:27)
W/PsynchoHelperImpl( 7287): 	at agO.a(LegacySyncManager.java:678)
W/PsynchoHelperImpl( 7287): 	at agO.b(LegacySyncManager.java:582)
W/PsynchoHelperImpl( 7287): 	at agO.a(LegacySyncManager.java:467)
W/PsynchoHelperImpl( 7287): 	at agO.a(LegacySyncManager.java:97)
W/PsynchoHelperImpl( 7287): 	at agQ.run(LegacySyncManager.java:419)
W/PsynchoHelperImpl( 7287): 	at ami.a(NetworkUtilitiesImpl.java:31)
W/PsynchoHelperImpl( 7287): 	at agP.run(LegacySyncManager.java:416)
W/PsynchoHelperImpl( 7287): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
W/PsynchoHelperImpl( 7287): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
W/PsynchoHelperImpl( 7287): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
W/PsynchoHelperImpl( 7287): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
W/PsynchoHelperImpl( 7287): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
W/PsynchoHelperImpl( 7287): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1412): updateNotificationData: count=3
I/MusicLeanback( 5323): Conditions not met for autocaching.
I/MusicLeanback( 5323): Stop autocaching.
E/Auth.Api.Credentials( 2340): [CredentialSyncAdapter] Unknown sync event.
D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{320ab302 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SyncManager( 1029): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.gms.auth.api.credentials, USER, currentRunTime 125194, EXPEDITED, reason: 10005, SyncResult: syncAlreadyInProgress: true stats []
,D/WearableClient( 5323): WearableClientImpl.onPostInitHandler: done
D/WearableClient( 5323): WearableClientImpl.onPostInitHandler: done
E/GmsUtils( 5323): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5323): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/cache
I/GLSUser ( 2128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.docs, service: writely
I/GLSUser ( 2128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> writely without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ContextImpl( 5323): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/cache
D/ChimeraCfgMgr( 2340): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/GCM     ( 2128): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/SyncManager( 1029): handleSyncHandlerMessage: dropping since the sync is no longer active: startTime 125143, mTimeoutStartTime 125143, mHistoryRowId 27, syncOperation thalitester@gmail.com u0 (com.google), com.google.android.gms.auth.api.credentials, PERIODIC, currentRunTime 155542, reason: Periodic
D/ChimeraCfgMgr( 2340): Loading module com.google.android.gms.kids from APK com.google.android.gms
V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2128): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2128): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2128): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2128): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2128): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2128): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2128): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpIssuerBase( 7287): Attempt to consume entity of HttpIssuer when no request is executing.
E/HttpIssuerBase( 7287): Attempt to close HttpIssuer when no request is executing.
E/HttpIssuerBase( 7287): java.io.IOException
E/HttpIssuerBase( 7287): 	at TG.b(HttpIssuerBase.java:188)
E/HttpIssuerBase( 7287): 	at Tj.b(DefaultAuthenticatedHttpIssuer.java:151)
E/HttpIssuerBase( 7287): 	at afE.a(AccountMetadataUpdater.java:227)
E/HttpIssuerBase( 7287): 	at afE.a(AccountMetadataUpdater.java:140)
E/HttpIssuerBase( 7287): 	at agO.a(LegacySyncManager.java:828)
E/HttpIssuerBase( 7287): 	at agO.b(LegacySyncManager.java:588)
E/HttpIssuerBase( 7287): 	at agO.a(LegacySyncManager.java:467)
E/HttpIssuerBase( 7287): 	at agO.a(LegacySyncManager.java:97)
E/HttpIssuerBase( 7287): 	at agQ.run(LegacySyncManager.java:419)
E/HttpIssuerBase( 7287): 	at ami.a(NetworkUtilitiesImpl.java:31)
E/HttpIssuerBase( 7287): 	at agP.run(LegacySyncManager.java:416)
E/SyncManager( 7287): AuthenticatorException
E/SyncManager( 7287): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/SyncManager( 7287): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/SyncManager( 7287): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/SyncManager( 7287): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/SyncManager( 7287): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/SyncManager( 7287): 	at android.os.Binder.execTransact(Binder.java:446)
W/ResourcesManager( 1412): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1412): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/GLSUser ( 2128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2128): [GLSUser] Extracting token using key: Auth
D/LgeQuickCoverNLService( 1412): onNotificationPosted
W/GLSActivity( 2128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
W/GAV2    ( 7287): SyncManager-thalitester@gmail.com: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,D/SmartCoverUpdateMonitor( 1412): received broadcast com.lge.intent.action.NLDataPosted
,D/WifiService( 1029): releaseWifiLockLocked: WifiLock{SyncManager type=1 binder=android.os.BinderProxy@db709b}
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
W/ResourcesManager( 1412): Asset path '/system/framework/com.lge.systemui.jar' does not exist or contains no resources.
W/ResourcesManager( 1412): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  2
,D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
,I/ActivityManager( 1029): Killing 6476:com.wsandroid.suite.lge/1000 (adj 15): empty #17
D/SyncManager( 1029): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.docs, PERIODIC, currentRunTime 40986, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager( 1029): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.apps.docs, PERIODIC, currentRunTime 156292, reason: Periodic
,W/libprocessgroup( 1029): failed to open /acct/uid_1000/pid_6476/cgroup.procs: No such file or directory
,E/LgeQuickCoverOverlayWindow( 1412): updateNotificationData: count=3
D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{320ab302 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/Kids    ( 2340): [AccountUtils] Account not ready
W/Kids    ( 2340): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2340): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2340): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2340): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2340): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2340): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2340): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2340): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2340): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2340): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2340): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2340): 	at java.lang.Thread.run(Thread.java:818)
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
,V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{320ab302 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,I/GLSUser ( 2128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 2128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,W/GLSActivity( 2128): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2128): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2128): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2128): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2128): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2128): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2128): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1412): onNotificationPosted
D/ContactsSyncAdapter( 2128): innerSync failed
D/ContactsSyncAdapter( 2128): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2128): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2128): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2128): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2128): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2128): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2128): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2128): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2128): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2128): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2128): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2128): 	at android.os.Binder.execTransact(Binder.java:446)
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
,D/SyncManager( 1029): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 149208, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
,D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{320ab302 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,I/ActivityManager( 1029): Killing 7008:com.qualcomm.timeservice/1000 (adj 15): empty #17
,W/libprocessgroup( 1029): failed to open /acct/uid_1000/pid_7008/cgroup.procs: No such file or directory
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=66.7, 0.0, 0.0  rx=64.4 bcn=0 [on:0 tx:0 rx:0 period:3007] from screen [on:0 period:-1581563894] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=66.7, 0.0, 0.0  rx=64.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1581563891] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,I/ThermalEngine(  335): Thermal-Server: Thermal received msg from  override
,I/Thermal-Lib( 3076): Thermal-Lib-Client: Client request sent
I/GAV2    ( 7227): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager( 1029): Killing 7027:com.android.calendar/u0a13 (adj 15): empty #17
,W/libprocessgroup( 1029): failed to open /acct/uid_10013/pid_7027/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 7194): Internal timer expired: 1
,D/UEI.SmartControl( 7194): unbind internal service
,D/serial_port( 7194): close(fd = 25)
I/UEI.SmartControl( 7194): Serial port is closed.
I/GAV2    ( 7287): Thread[GAThread,5,main]: No campaign data found.
,I/GAV2    ( 6901): Thread[GAThread,5,main]: No campaign data found.
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=52.9, 0.0, 0.0  rx=49.2 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1581560867] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=52.9, 0.0, 0.0  rx=49.2 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1581560857] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,I/ActivityManager( 1029): Killing 6975:com.lge.clock/u0a10 (adj 15): empty #17
,W/libprocessgroup( 1029): failed to open /acct/uid_10010/pid_6975/cgroup.procs: No such file or directory
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=26.4, 0.0, 0.0  rx=24.6 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1581557838] gl rssi=-64 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=26.4, 0.0, 0.0  rx=24.6 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1581557837] gl rssi=-64 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,W/PackageSettings( 1029): Skipping PackageSetting{3388f223 com.example.hello/10319} due to missing metadata
,I/[SystemUI]QPairHandler( 1472): onReceive = android.intent.action.PACKAGE_CHANGED
,D/SplitUIService( 1892): replaced split : contains_com.google.android.talk / true
,I/InputReader( 1029): Reconfiguring input devices.  changes=0x00000010
,D/SplitUIManager( 1892): split_name #11 / not available #0
I/SplitUIService( 1892): split app #11
,I/ActivityManager( 1029): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7494 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/InputReader( 1029): Reconfiguring input devices.  changes=0x00000010
I/[LGHome]EVENT( 2087): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000010 (has extras) }
,I/[LGHome]EVENT( 2087): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.videos flg=0x4000010 (has extras) }
I/[LGHome]EVENT( 2087): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/InputReader( 1029): Reconfiguring input devices.  changes=0x00000010
,I/[SystemUI]QSlideListController( 1472): onReceive = android.intent.action.PACKAGE_CHANGED
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1472): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.talk
I/[SystemUI]QPairHandler( 1472): onReceive = android.intent.action.PACKAGE_CHANGED
W/ResourcesManager( 2087): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/[SystemUI]QSlideListController( 1472): onReceive = android.intent.action.PACKAGE_CHANGED
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1472): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.videos
I/[SystemUI]QPairHandler( 1472): onReceive = android.intent.action.PACKAGE_CHANGED
,I/[SystemUI]QSlideListController( 1472): onReceive = android.intent.action.PACKAGE_CHANGED
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1472): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
D/administrator( 1029): Handling package changes for user 0
I/[LGHome]Launcher( 2087): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/AppUp4:AppBoxCP( 7494): onCreate
W/AppUp4:DB( 7494):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7494):  setFingerPrint start
I/AppUp4:DB( 7494):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 7494):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7494):  SDK version = 21
I/AppUp4:DB( 7494):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 7494): AppBoxApplication onCreate()
,I/AppUp4:CustModeStarterReceiver( 7494): onReceive
I/[LGHome]Launcher( 2087): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2087): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
D/LgDataFeature( 7494): LgDataFeature() Constructor: none
D/LgDataFeature( 7494): LgDataFeature() Constructor Done, null
,I/NotificationService( 1029): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService( 1029): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000010 (has extras) }
D/AppUp4:CustFacade( 7494): Context : android.app.ReceiverRestrictedContext@46a5aaf
D/AppUp4:CustFacade( 7494): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7494): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7494): begin check event
I/AppUp4:CustModeStarterReceiver( 7494): Event For Nothing, skip.
W/ResourcesManager( 1029): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/ActivityManager( 1029): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7530 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/ActivityManager( 1029): Killing 7074:com.google.android.talk/u0a72 (adj 15): empty #17
,W/ResourcesManager( 1029): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourceType( 1029): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
W/libprocessgroup( 1029): failed to open /acct/uid_10072/pid_7074/cgroup.procs: No such file or directory
,D/administrator( 1029): Handling package changes for user 0
I/[LGHome]EVENT( 2087): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/NotificationService( 1029): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService( 1029): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.videos flg=0x4000010 (has extras) }
,D/administrator( 1029): Handling package changes for user 0
W/ResourcesManager( 7530): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7530): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7530): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7530): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7530): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourceType( 1029): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/[LGHome]EVENT( 2087): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/NotificationService( 1029): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService( 1029): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService( 1029): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService( 1029): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService( 1029): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService( 1029): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@186bd74d
,W/ResourceType( 1029): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/[LGHome]EVENT( 2087): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,V/GmsNetworkLocationProvi( 1831): DISABLE
I/GCoreNlp( 1831): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
D/LocationProviderProxy( 1029): applying state to connected service
,I/SystemConfig( 7530): BUILD Country: EU
,I/SystemConfig( 7530): BUILD Operator: OPEN
,I/ActivityManager( 1029): Killing 6845:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=13.7, 0.0, 0.0  rx=12.8 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:-1581554817] gl rssi=-64 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=13.7, 0.0, 0.0  rx=12.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1581554814] gl rssi=-64 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
W/libprocessgroup( 1029): failed to open /acct/uid_10085/pid_6845/cgroup.procs: No such file or directory
,I/SystemConfig( 7530): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7530): existFile = false
I/SystemConfig( 7530): canReadFile = false
,I/SystemConfig( 7530): systemFeature RCS result false
D/SystemConfig( 7530): refreshRcsSupport() :false
I/ActivityManager( 1029): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7554 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/ResourcesManager( 7554): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7554): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7554): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 7554): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,I/AppConfig( 7554): Total System Memory = 2995761152
,D/SystemHelper( 7554): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager( 1029): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=7576 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager( 1029): RTC_WAKEUP set : Alarm{9925775 type 0 when 1454412358111 com.android.vending} when 1454412358111
I/ActivityManager( 1029): Killing 7158:com.android.providers.calendar/u0a14 (adj 15): empty #17
,I/art     (  355): Explicit concurrent mark sweep GC freed 705(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 450us total 31.106ms
,I/art     (  355): Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 411us total 20.232ms
,I/art     (  355): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 414us total 19.495ms
,W/libprocessgroup( 1029): failed to open /acct/uid_10014/pid_7158/cgroup.procs: No such file or directory
I/UpdateIcingCorporaServi( 4328): Updating corpora: APPS=com.google.android.talk, CONTACTS=MAYBE
,I/ActivityManager( 1029): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7594 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,V/SIM_STK ( 1029): Menu title from STK is T-Mobile
,W/ResourcesManager( 4328): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 4328): UpdateCorporaTask done [took 103 ms] updated apps [took 103 ms] 
,I/LockScreenSettings( 7594): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/Finsky  ( 7576): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/LockScreenSettings( 7594): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7594): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7594): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7594): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7594): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
D/LockScreenSettings( 7594): Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,D/LgDataFeature( 7576): LgDataFeature() Constructor: none
,D/LgDataFeature( 7576): LgDataFeature() Constructor Done, null
,I/art     ( 1029): Explicit concurrent mark sweep GC freed 57024(3MB) AllocSpace objects, 15(758KB) LOS objects, 33% free, 44MB/66MB, paused 2.487ms total 126.566ms
,I/ActivityManager( 1029): Killing 6695:com.google.android.apps.books/u0a54 (adj 15): empty #17
,D/Finsky  ( 7576): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/libprocessgroup( 1029): failed to open /acct/uid_10054/pid_6695/cgroup.procs: No such file or directory
,I/ActivityManager( 1029): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=7643 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
W/Settings( 7576): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 7576): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,V/DownloadManager( 3356): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3356): created cursor android.database.sqlite.SQLiteCursor@16d8cc23 on behalf of 7576
,W/ResourcesManager( 7643): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7643): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Finsky  ( 7576): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 7576): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7576): [1] 2.run: Finished loading 1 libraries.
,I/MultiDex( 7643): VM with version 2.1.0 has multidex support
I/MultiDex( 7643): install
I/MultiDex( 7643): VM has multidex support, MultiDex support library is disabled.
D/PackageBroadcastService( 2340): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.talk
,I/AppUp4:CustModeStarterReceiver( 7494): onReceive
,D/AppUp4:CustFacade( 7494): Context : android.app.ReceiverRestrictedContext@46a5aaf
D/AppUp4:CustFacade( 7494): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7494): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7494): begin check event
I/AppUp4:CustModeStarterReceiver( 7494): Event For Nothing, skip.
,D/Finsky  ( 7576): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/PeopleContactsSync( 2340): CP2 sync disabled
,V/JNIHelp ( 7643): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/UpdateIcingCorporaServi( 4328): Updating corpora: APPS=com.google.android.videos, CONTACTS=MAYBE
D/LockScreenSettings( 7594): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7594): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7594): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7594): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7594): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
D/LockScreenSettings( 7594): Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,V/SIM_STK ( 1029): Menu title from STK is T-Mobile
D/PackageBroadcastService( 2340): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.videos
,V/SIM_STK ( 1029): Menu title from STK is T-Mobile
I/UpdateIcingCorporaServi( 4328): UpdateCorporaTask done [took 60 ms] updated apps [took 60 ms] 
,I/ActivityManager( 1029): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7673 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/PeopleContactsSync( 2340): CP2 sync disabled
,W/ActivityThread( 7643): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7643): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@326b6777: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7643): Installed default security provider GmsCore_OpenSSL
,W/ResourcesManager( 7673): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/LgDataFeature( 7673): LgDataFeature() Constructor: none
D/LgDataFeature( 7673): LgDataFeature() Constructor Done, null
,I/Babel   ( 7673): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 7673): MmsConfig.loadMmsSettings
,I/Babel   ( 7673): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,I/Babel   ( 7673): MmsConfig.loadFromDatabase
V/Finsky  ( 7576): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,E/Babel   ( 7673): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 7673): MmsConfig.loadFromResources
E/Babel   ( 7673): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 7673): MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,W/AudioCapabilities( 7673): Unsupported mime audio/evrc
W/AudioCapabilities( 7673): Unsupported mime audio/qcelp
W/Settings( 7673): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/VideoCapabilities( 7673): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7673): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 7673): Unsupported mime audio/qcelp
W/AudioCapabilities( 7673): Unsupported mime audio/evrc
V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/AppUp4:CustModeStarterReceiver( 7494): onReceive
,D/AppUp4:CustFacade( 7494): Context : android.app.ReceiverRestrictedContext@46a5aaf
D/AppUp4:CustFacade( 7494): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7494): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7494): begin check event
I/AppUp4:CustModeStarterReceiver( 7494): Event For Nothing, skip.
W/VideoCapabilities( 7673): Unsupported mime video/x-ms-wmv
W/VideoCapabilities( 7673): Unsupported mime video/divx
,I/GLSUser ( 2128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/VideoCapabilities( 7673): Unsupported mime video/divx311
W/VideoCapabilities( 7673): Unsupported mime video/divx4
I/UpdateIcingCorporaServi( 4328): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
D/LockScreenSettings( 7594): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7594): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7594): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7594): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7594): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,D/LockScreenSettings( 7594): Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
W/VideoCapabilities( 7673): Unsupported mime video/mp4v-esdp
I/art     ( 2128): Explicit concurrent mark sweep GC freed 15501(918KB) AllocSpace objects, 13(1872KB) LOS objects, 50% free, 30MB/62MB, paused 1.395ms total 29.344ms
D/GCM     ( 2128): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/ActivityManager( 1029): Killing 7194:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,D/PackageBroadcastService( 2340): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/VideoCapabilities( 7673): Unsupported profile 4 for video/mp4v-es
I/QRemote ( 6511): [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
W/System.err( 6511): android.os.DeadObjectException
W/System.err( 6511): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6511): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6511): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 6511): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
W/System.err( 6511): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 6511): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 6511): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6511): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6511): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6511): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 6511): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6511): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6511): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 6511): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 6511): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 6511): android.os.DeadObjectException
W/System.err( 6511): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6511): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6511): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 6511): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
W/System.err( 6511): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 6511): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 6511): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6511): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6511): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6511): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 6511): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6511): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6511): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 6511): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,E/UEI.SmartControl( 6511): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
,I/QRemote ( 6511): [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
W/AudioCapabilities( 7673): Unsupported mime audio/eac3
W/AudioCapabilities( 7673): Unsupported mime audio/ac3
W/AudioCapabilities( 7673): Unsupported mime audio/g726
W/AudioCapabilities( 7673): Unsupported mime audio/wma-voice
W/AudioCapabilities( 7673): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7673): Unsupported mime audio/adpcm
W/VideoCapabilities( 7673): Unsupported mime video/theora
W/VideoCapabilities( 7673): Unsupported mime video/mjpg
I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
I/PackageBroadcastService( 2340): Null package name or gms related package.  Ignoreing.
,W/libprocessgroup( 1029): failed to open /acct/uid_1000/pid_7194/cgroup.procs: No such file or directory
W/ActivityManager( 1029): Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
D/PowerManagerServiceEx( 1029): acquireWakeLockInternal: lock=307177574, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1029
D/QRemote ( 6511): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
V/AlarmManager( 1029): RTC_WAKEUP set : Alarm{1dc77fbe type 0 when 1454412360451 com.android.vending} when 1454412360451
D/Finsky  ( 7576): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,I/QRemote ( 6511): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
I/ActivityManager( 1029): Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7722 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,D/AuthorizationBluetoothService( 2128): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GmsCoreStatsServiceLauncher( 2340): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/QRemote ( 6511): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/[Concierge]Service( 2574): onStartCommand(). Type : 9
,D/Finsky  ( 7576): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 7576): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7576): [1] 5.onFinished: Scheduling replication attempt 3.
I/GLSUser ( 2128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/WearableService( 7111): callingUid 10005, callindPid: 7111
V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 2340): updateResources: need to parse f{com.google.android.gms}
,E/MDM     ( 1831): [97] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
D/PowerManagerServiceEx( 1029): releaseWakeLockInternal: lock=307177574 [*alarm*], flags=0x0
D/LocationInitializer( 2340): Restart initialization of location
,W/Finsky  ( 7576): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/UEI.SmartControl( 7722): Quickset Services start...
,I/UEI.SmartControl( 7722): Manufacture = LGE
D/UEI.SmartControl( 7722): Id = LGNevo
D/UEI.SmartControl( 7722): File observer start...
E/UEI.SmartControl( 7722): IR Port is disabled: false
D/UEI.SmartControl( 7722): Starting file observer...
D/UEI.SmartControl( 7722): Extracting JNI libs...
D/UEI.SmartControl( 7722): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 7722): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 7722): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7722): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/SIM_STK ( 1029): Menu title from STK is T-Mobile
I/UpdateIcingCorporaServi( 4328): UpdateCorporaTask done [took 593 ms] updated apps [took 592 ms] 
,I/UEI.SmartControl( 7722): --- Selecting new region: 6
,I/UEI.SmartControl( 7722): Model = LG-D855
D/UEI.SmartControl( 7722): QS Service created
V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/UEI.SmartControl( 7722): Service initServices...
,D/UEI.SmartControl( 7722): QS start get config
,I/GLSUser ( 2128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 7576): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/UEI.SmartControl( 7722): Loading JNI Libs...
,V/SIM_STK ( 1029): Menu title from STK is T-Mobile
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 137904272502; DSPS: 4660160; Offset : -4327378459
,V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 7576): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 7576): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
D/Finsky  ( 7576): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7576): [1] DailyHygiene.reschedule: Scheduling new run in 9 minutes (failures=1)
,D/Finsky  ( 7576): [1] VerifyInstalledPackagesReceiver.onReceive: Verify installed apps requested
D/DeviceConnectionService( 1831): client connected with version: 7571000
D/Finsky  ( 7576): [1] VerifyInstalledPackagesTask.onPreExecute: Verifying installed apps
,I/UEI.SmartControl( 7722): Supports setup maps: true
,V/SIM_STK ( 1029): Menu title from STK is T-Mobile
D/UEI.SmartControl( 7722): QS start statue = true Error code = 0
I/UEI.SmartControl( 7722): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 7722): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 7722): ### init IR Blaster...
D/serial_port( 7722): Configuring serial port
,E/UEI.SmartControl( 7722): UEIBLaster setting for 616
,I/UEI.SmartControl( 7722): Setting serial record hearder size = 2
I/UEI.SmartControl( 7722): configuring settings for MAXQ616
I/UEI.SmartControl( 7722): Get version...
,D/UEI.SmartControl( 7722): serial port data available: 21
D/UEI.SmartControl( 7722): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 7722): IR Blaster version: 256702256704300002
,I/UEI.SmartControl( 7722): QS saving settings...
D/UEI.SmartControl( 7722): IR Blaster version: 25672567
,D/UEI.SmartControl( 7722): serial port data available: 4
,I/UEI.SmartControl( 7722): Device manager: loading config....
D/UEI.SmartControl( 7722): ----------- loading internal config...
,W/ContextImpl( 7722): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
E/UEI.SmartControl( 7722): Loading SETTINGS...
,D/UEI.SmartControl( 7722): -- Open brand translation xml: brands_translations_ko
I/UEI.SmartControl( 7722): Notify AllClients services are ready: 0
D/UEI.SmartControl( 7722): -----service ready thread exits
,I/art     ( 1029): Explicit concurrent mark sweep GC freed 22255(985KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 2.666ms total 142.234ms
,E/UEI.SmartControl( 7722): Services init done
D/UEI.SmartControl( 7722): QS Service init finished
D/UEI.SmartControl( 7722): QS Service version name: 2.1.91
D/UEI.SmartControl( 7722): QS Service version code: 201091
D/UEI.SmartControl( 7722): Service requested: Control
I/QRemote ( 6511): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 7722): ------ IControl API: 11
I/UEI.SmartControl( 7722): Registering callback...
,I/UEI.SmartControl( 7722): ------ IControl API: 19
I/UEI.SmartControl( 7722): Registering Services Ready callback...,
I/UEI.SmartControl( 7722): Notify client services are ready...
I/QRemote ( 6511): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 6511): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 6511): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 6511): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 6511): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 7722): ------ IControl API: 8
D/QRemote ( 6511): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 6511): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 6511): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 6511): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/UEI.SmartControl( 7722): Internal service binding...
D/QRemote ( 6511): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6511): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 6511): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
V/QRemote ( 6511): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6511): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 6511): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6511): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 6511): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6511): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 6511): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 6511): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1454412361378]
,D/QRemote ( 6511): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
V/QRemote ( 6511): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
E/QRemote ( 6511): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6511): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 6511): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 6511): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 6511): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
,D/QRemote ( 6511): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 6511): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
I/ActivityManager( 1029): Killing 6869:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,I/ActivityManager( 1029): Killing 7227:com.google.android.gm/u0a64 (adj 15): empty #18
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=6.9, 0.0, 0.0  rx=6.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1581551795] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=6.9, 0.0, 0.0  rx=6.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1581551792] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,W/libprocessgroup( 1029): failed to open /acct/uid_10093/pid_6869/cgroup.procs: No such file or directory
W/libprocessgroup( 1029): failed to open /acct/uid_10064/pid_7227/cgroup.procs: No such file or directory
,I/ActivityManager( 1029): Waited long enough for: ServiceRecord{281fd7dc u0 com.google.android.music/.download.artwork.ArtDownloadService}
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=4.9, 0.0, 0.0  rx=4.2 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1581548776] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=4.9, 0.0, 0.0  rx=4.2 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1581548767] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
I/ActivityManager( 1029): Killing 7136:com.google.android.syncadapters.calendar/u0a69 (adj 15): empty #17
,W/libprocessgroup( 1029): failed to open /acct/uid_10069/pid_7136/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 7722): Internal timer expired: 1
,D/UEI.SmartControl( 7722): unbind internal service
,D/serial_port( 7722): close(fd = 25)
,I/UEI.SmartControl( 7722): Serial port is closed.
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=3.0, 0.0, 0.0  rx=2.6 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1581545745] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=3.0, 0.0, 0.0  rx=2.6 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1581545733] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,V/AlarmManager( 1029): ELAPSED_WAKEUP set : Alarm{4d3b318 type 2 when 146942 android} when 146942
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.5, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1581542710] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.5, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1581542707] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1581539688] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1581539685] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1029):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,E/WifiStateMachine( 1029):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1029):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,E/WifiStateMachine( 1029):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1581536659] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1581536656] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1581533631] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1581533628] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 157905937026; DSPS: 5315574; Offset : -4327362900
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1581530602] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1581530599] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1581527573] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1581527570] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,V/AlarmManager( 1029): RTC_WAKEUP set : Alarm{279dfb65 type 0 when 1454412380824 com.android.vending} when 1454412380824
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1581524548] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1581524547] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,V/SIM_STK ( 1029): Menu title from STK is T-Mobile
,V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7576): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 7576): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7576): [1] 5.onFinished: Scheduling replication attempt 4.
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1581521529] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1581521526] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1581518502] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1581518499] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1581515476] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1581515467] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,V/AlarmManager( 1029): ELAPSED_WAKEUP set : Alarm{1da4b5bf type 2 when 176978 android} when 176978
,I/ActivityManager( 1029): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=7804 uid=10054 gids={50054, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ReaderUtils( 7804): PortraitW 1440 LandscapeW 2392 SmallestSize 1340 LargestSize 2392 textZoom 4.4999995 isTablet false Memory 256
,W/GAV2    ( 7804): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 7804): Created application version: 3.2.35 (30235)
,I/BooksSync( 7804): Starting books sync
,V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
,I/GLSUser ( 2128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/GLSActivity( 2128): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2128): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2128): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2128): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2128): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2128): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2128): 	at android.os.Binder.execTransact(Binder.java:446)
,D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/ContactsSyncAdapter( 2128): innerSync failed
D/ContactsSyncAdapter( 2128): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2128): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2128): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2128): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2128): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2128): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2128): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2128): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2128): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2128): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2128): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2128): 	at android.os.Binder.execTransact(Binder.java:446)
E/LgeQuickCoverOverlayWindow( 1412): updateNotificationData: count=3
D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{320ab302 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/SyncManager( 1029): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 149208, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager( 1029): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 238975, reason: 10019
D/BooksSync( 7804): started syncMyEbooks
,E/Auth.Api.Credentials( 2340): [CredentialSyncAdapter] Unknown sync event.
,V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2128): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2128): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2128): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2128): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2128): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2128): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2128): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7804): Authentication error
E/BooksAccountManager( 7804): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7804): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7804): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7804): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7804): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7804): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7804): null auth token
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
,D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  315): res_queryN name = www.googleapis.com, class = 1, type = 1
D/libc-netbsd(  315): res_queryN name = www.googleapis.com succeed
D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{320ab302 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1581512445] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1581512442] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 177907855404; DSPS: 5970997; Offset : -4327367181
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.7, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1581509431] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.7, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1581509427] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,I/GAV2    ( 7804): Thread[GAThread,5,main]: No campaign data found.
,W/ApiaryClient( 7804): Error response from books API: {
W/ApiaryClient( 7804):  "error": {
W/ApiaryClient( 7804):   "errors": [
W/ApiaryClient( 7804):    {
W/ApiaryClient( 7804):     "domain": "global",
W/ApiaryClient( 7804):     "reason": "required",
W/ApiaryClient( 7804):     "message": "Login Required",
W/ApiaryClient( 7804):     "locationType": "header",
W/ApiaryClient( 7804):     "location": "Authorization"
W/ApiaryClient( 7804):    }
W/ApiaryClient( 7804):   ],
W/ApiaryClient( 7804):   "code": 401,
W/ApiaryClient( 7804):   "message": "Login Required"
W/ApiaryClient( 7804):  }
W/ApiaryClient( 7804): }
,W/ApiaryClient( 7804): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7804): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-2989690487633901096&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7804): Headers:
W/ApiaryClient( 7804): accept-encoding: [gzip]
W/ApiaryClient( 7804): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7804): gdata-version: 2
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=2.9, 0.0, 0.0  rx=3.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1581506400] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=2.9, 0.0, 0.0  rx=3.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1581506397] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 2128): Explicit concurrent mark sweep GC freed 22169(1289KB) AllocSpace objects, 6(864KB) LOS objects, 50% free, 30MB/62MB, paused 2.320ms total 58.106ms
,V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/GLSActivity( 2128): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2128): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2128): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2128): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2128): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2128): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2128): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7804): Authentication error
E/BooksAccountManager( 7804): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7804): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7804): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7804): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7804): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7804): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7804): null auth token
D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{320ab302 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 7804): Error response from books API: {
W/ApiaryClient( 7804):  "error": {
W/ApiaryClient( 7804):   "errors": [
W/ApiaryClient( 7804):    {
W/ApiaryClient( 7804):     "domain": "global",
W/ApiaryClient( 7804):     "reason": "required",
W/ApiaryClient( 7804):     "message": "Login Required",
W/ApiaryClient( 7804):     "locationType": "header",
W/ApiaryClient( 7804):     "location": "Authorization"
W/ApiaryClient( 7804):    }
W/ApiaryClient( 7804):   ],
W/ApiaryClient( 7804):   "code": 401,
W/ApiaryClient( 7804):   "message": "Login Required"
W/ApiaryClient( 7804):  }
W/ApiaryClient( 7804): }
W/ApiaryClient( 7804): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7804): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-2989690487633901096&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7804): Headers:
W/ApiaryClient( 7804): accept-encoding: [gzip]
W/ApiaryClient( 7804): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7804): gdata-version: 2
,V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
,D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{320ab302 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/GLSActivity( 2128): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2128): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2128): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2128): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2128): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2128): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2128): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7804): Authentication error
E/BooksAccountManager( 7804): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7804): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7804): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7804): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7804): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7804): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7804): null auth token
,W/ApiaryClient( 7804): Error response from books API: {
W/ApiaryClient( 7804):  "error": {
W/ApiaryClient( 7804):   "errors": [
W/ApiaryClient( 7804):    {
W/ApiaryClient( 7804):     "domain": "global",
W/ApiaryClient( 7804):     "reason": "required",
W/ApiaryClient( 7804):     "message": "Login Required",
W/ApiaryClient( 7804):     "locationType": "header",
W/ApiaryClient( 7804):     "location": "Authorization"
W/ApiaryClient( 7804):    }
W/ApiaryClient( 7804):   ],
W/ApiaryClient( 7804):   "code": 401,
W/ApiaryClient( 7804):   "message": "Login Required"
W/ApiaryClient( 7804):  }
W/ApiaryClient( 7804): }
,W/ApiaryClient( 7804): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7804): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-2989690487633901096&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7804): Headers:
W/ApiaryClient( 7804): accept-encoding: [gzip]
W/ApiaryClient( 7804): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7804): gdata-version: 2
,E/BooksSync( 7804): Soft error: 
E/BooksSync( 7804): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7804): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-2989690487633901096&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7804): Headers:
E/BooksSync( 7804): accept-encoding: [gzip]
E/BooksSync( 7804): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7804): gdata-version: 2
E/BooksSync( 7804): 
E/BooksSync( 7804): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7804): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7804): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7804): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7804): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7804): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7804): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7804): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7804): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7804): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7804): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7804): {
E/BooksSync( 7804):  "error": {
E/BooksSync( 7804):   "errors": [
E/BooksSync( 7804):    {
E/BooksSync( 7804):     "domain": "global",
E/BooksSync( 7804):     "reason": "required",
E/BooksSync( 7804):     "message": "Login Required",
E/BooksSync( 7804):     "locationType": "header",
E/BooksSync( 7804):     "location": "Authorization"
E/BooksSync( 7804):    }
E/BooksSync( 7804):   ],
E/BooksSync( 7804):   "code": 401,
E/BooksSync( 7804):   "message": "Login Required"
E/BooksSync( 7804):  }
E/BooksSync( 7804): }
E/BooksSync( 7804): 
E/BooksSync( 7804): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7804): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7804): 	... 8 more
,E/BooksSync( 7804): Sync error
E/BooksSync( 7804): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7804): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-2989690487633901096&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7804): Headers:
E/BooksSync( 7804): accept-encoding: [gzip]
E/BooksSync( 7804): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7804): gdata-version: 2
E/BooksSync( 7804): 
E/BooksSync( 7804): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7804): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7804): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7804): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7804): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7804): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7804): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7804): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7804): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7804): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7804): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7804): {
E/BooksSync( 7804):  "error": {
E/BooksSync( 7804):   "errors": [
E/BooksSync( 7804):    {
E/BooksSync( 7804):     "domain": "global",
E/BooksSync( 7804):     "reason": "required",
E/BooksSync( 7804):     "message": "Login Required",
E/BooksSync( 7804):     "locationType": "header",
E/BooksSync( 7804):     "location": "Authorization"
E/BooksSync( 7804):    }
E/BooksSync( 7804):   ],
E/BooksSync( 7804):   "code": 401,
E/BooksSync( 7804):   "message": "Login Required"
E/BooksSync( 7804):  }
E/BooksSync( 7804): }
E/BooksSync( 7804): 
E/BooksSync( 7804): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7804): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7804): 	... 8 more
I/BooksSync( 7804): Finished books sync
I/ActivityManager( 1029): Killing 7326:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,D/SyncManager( 1029): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 153894, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,W/libprocessgroup( 1029): failed to open /acct/uid_10008/pid_7326/cgroup.procs: No such file or directory
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=5.9, 0.0, 0.0  rx=5.6 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1581503373] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=5.9, 0.0, 0.0  rx=5.6 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1581503362] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=5.0, 0.0, 0.0  rx=4.8 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1581500341] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=5.0, 0.0, 0.0  rx=4.8 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1581500337] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,V/AlarmManager( 1029): RTC_WAKEUP set : Alarm{1c730a05 type 0 when 1454412409049 com.android.vending} when 1454412409049
,V/SIM_STK ( 1029): Menu title from STK is T-Mobile
,V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1029): Explicit concurrent mark sweep GC freed 40041(1738KB) AllocSpace objects, 6(608KB) LOS objects, 33% free, 44MB/66MB, paused 2.024ms total 98.498ms
,I/GLSUser ( 2128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7576): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7576): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7576): [1] 5.onFinished: Scheduling replication attempt 5.
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=3.0, 0.0, 0.0  rx=2.9 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1581497313] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=3.0, 0.0, 0.0  rx=2.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1581497310] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=1.5, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1581494284] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=1.5, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1581494280] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 197909977167; DSPS: 6626427; Offset : -4327381649
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1581491256] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1581491246] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1581488231] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1581488228] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1581485204] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1581485201] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,D/PowerManagerServiceEx( 1029): acquireWakeLockInternal: lock=307177574, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1029
,V/AlarmManager( 1029): ELAPSED_WAKEUP set : Alarm{22bde35f type 2 when 207078 android} when 207078
D/[Concierge]Service( 2574): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1029): releaseWakeLockInternal: lock=307177574 [*alarm*], flags=0x0
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1581482176] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1581482166] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1581479145] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1581479132] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1581476111] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1581476108] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1581473081] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1581473078] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 217912137316; DSPS: 7281858; Offset : -4327388300
,V/AlarmManager( 1029): RTC_WAKEUP set : Alarm{2ea37e75 type 0 when 1454412434102 com.android.vending} when 1454412434102
,V/SIM_STK ( 1029): Menu title from STK is T-Mobile
,V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7576): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7576): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 7576): [1] 5.onFinished: Giving up after 6 failures.
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1581470058] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1581470055] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1581467032] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1581467031] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1581464010] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1581464007] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1581460981] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1581460978] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1581457949] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1581457946] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1581454920] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1581454917] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 237913996996; DSPS: 7937278; Offset : -4327359753
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1581451898] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1581451895] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,V/AlarmManager( 1029): ELAPSED_WAKEUP set : Alarm{2ccc624f type 2 when 210555 android} when 210555
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1581448866] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1581448856] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1581445836] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:14] from screen [on:0 period:-1581445822] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1581442801] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1581442798] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1581439772] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1581439769] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,V/AlarmManager( 1029): ELAPSED_WAKEUP set : Alarm{31141ddc type 2 when 250902 android} when 250902
,I/BooksSync( 7804): Starting books sync
,D/BooksSync( 7804): started syncMyEbooks
,V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/GLSActivity( 2128): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2128): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2128): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2128): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2128): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2128): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2128): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7804): Authentication error
E/BooksAccountManager( 7804): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7804): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7804): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7804): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7804): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7804): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7804): null auth token
D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{320ab302 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 7804): Error response from books API: {
W/ApiaryClient( 7804):  "error": {
W/ApiaryClient( 7804):   "errors": [
W/ApiaryClient( 7804):    {
W/ApiaryClient( 7804):     "domain": "global",
W/ApiaryClient( 7804):     "reason": "required",
W/ApiaryClient( 7804):     "message": "Login Required",
W/ApiaryClient( 7804):     "locationType": "header",
W/ApiaryClient( 7804):     "location": "Authorization"
W/ApiaryClient( 7804):    }
W/ApiaryClient( 7804):   ],
W/ApiaryClient( 7804):   "code": 401,
W/ApiaryClient( 7804):   "message": "Login Required"
W/ApiaryClient( 7804):  }
W/ApiaryClient( 7804): }
,W/ApiaryClient( 7804): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7804): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-998635558696550727&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7804): Headers:
W/ApiaryClient( 7804): accept-encoding: [gzip]
W/ApiaryClient( 7804): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7804): gdata-version: 2
,V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2128): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{320ab302 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/GLSActivity( 2128): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2128): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2128): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2128): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2128): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2128): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2128): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7804): Authentication error
E/BooksAccountManager( 7804): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7804): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7804): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7804): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7804): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7804): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7804): null auth token
,W/ApiaryClient( 7804): Error response from books API: {
W/ApiaryClient( 7804):  "error": {
W/ApiaryClient( 7804):   "errors": [
W/ApiaryClient( 7804):    {
W/ApiaryClient( 7804):     "domain": "global",
W/ApiaryClient( 7804):     "reason": "required",
W/ApiaryClient( 7804):     "message": "Login Required",
W/ApiaryClient( 7804):     "locationType": "header",
W/ApiaryClient( 7804):     "location": "Authorization"
W/ApiaryClient( 7804):    }
W/ApiaryClient( 7804):   ],
W/ApiaryClient( 7804):   "code": 401,
W/ApiaryClient( 7804):   "message": "Login Required"
W/ApiaryClient( 7804):  }
W/ApiaryClient( 7804): }
,W/ApiaryClient( 7804): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7804): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-998635558696550727&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7804): Headers:
W/ApiaryClient( 7804): accept-encoding: [gzip]
W/ApiaryClient( 7804): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7804): gdata-version: 2
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1581436743] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1581436740] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/GLSActivity( 2128): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2128): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2128): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2128): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2128): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2128): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2128): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7804): Authentication error
E/BooksAccountManager( 7804): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7804): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7804): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7804): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7804): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7804): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7804): null auth token
D/QuickStatusbarLayout( 1412): Notification difference=198
D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{320ab302 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 7804): Error response from books API: {
W/ApiaryClient( 7804):  "error": {
W/ApiaryClient( 7804):   "errors": [
W/ApiaryClient( 7804):    {
W/ApiaryClient( 7804):     "domain": "global",
W/ApiaryClient( 7804):     "reason": "required",
W/ApiaryClient( 7804):     "message": "Login Required",
W/ApiaryClient( 7804):     "locationType": "header",
W/ApiaryClient( 7804):     "location": "Authorization"
W/ApiaryClient( 7804):    }
W/ApiaryClient( 7804):   ],
W/ApiaryClient( 7804):   "code": 401,
W/ApiaryClient( 7804):   "message": "Login Required"
W/ApiaryClient( 7804):  }
W/ApiaryClient( 7804): }
,W/ApiaryClient( 7804): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7804): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-998635558696550727&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7804): Headers:
W/ApiaryClient( 7804): accept-encoding: [gzip]
W/ApiaryClient( 7804): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7804): gdata-version: 2
,E/BooksSync( 7804): Soft error: 
E/BooksSync( 7804): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7804): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-998635558696550727&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7804): Headers:
E/BooksSync( 7804): accept-encoding: [gzip]
E/BooksSync( 7804): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7804): gdata-version: 2
E/BooksSync( 7804): 
E/BooksSync( 7804): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7804): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7804): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7804): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7804): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7804): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7804): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7804): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7804): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7804): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7804): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7804): {
E/BooksSync( 7804):  "error": {
E/BooksSync( 7804):   "errors": [
E/BooksSync( 7804):    {
E/BooksSync( 7804):     "domain": "global",
E/BooksSync( 7804):     "reason": "required",
E/BooksSync( 7804):     "message": "Login Required",
E/BooksSync( 7804):     "locationType": "header",
E/BooksSync( 7804):     "location": "Authorization"
E/BooksSync( 7804):    }
E/BooksSync( 7804):   ],
E/BooksSync( 7804):   "code": 401,
E/BooksSync( 7804):   "message": "Login Required"
E/BooksSync( 7804):  }
E/BooksSync( 7804): }
E/BooksSync( 7804): 
E/BooksSync( 7804): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7804): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7804): 	... 8 more
,E/BooksSync( 7804): Sync error
E/BooksSync( 7804): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7804): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-998635558696550727&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7804): Headers:
E/BooksSync( 7804): accept-encoding: [gzip]
E/BooksSync( 7804): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7804): gdata-version: 2
E/BooksSync( 7804): 
E/BooksSync( 7804): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7804): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7804): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7804): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7804): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7804): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7804): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7804): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7804): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7804): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7804): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7804): {
E/BooksSync( 7804):  "error": {
E/BooksSync( 7804):   "errors": [
E/BooksSync( 7804):    {
E/BooksSync( 7804):     "domain": "global",
E/BooksSync( 7804):     "reason": "required",
E/BooksSync( 7804):     "message": "Login Required",
E/BooksSync( 7804):     "locationType": "header",
E/BooksSync( 7804):     "location": "Authorization"
E/BooksSync( 7804):    }
E/BooksSync( 7804):   ],
E/BooksSync( 7804):   "code": 401,
E/BooksSync( 7804):   "message": "Login Required"
E/BooksSync( 7804):  }
E/BooksSync( 7804): }
E/BooksSync( 7804): 
E/BooksSync( 7804): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7804): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7804): 	... 8 more
I/BooksSync( 7804): Finished books sync
D/SyncManager( 1029): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 250902, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=2.4, 0.0, 0.0  rx=2.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1581433716] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=2.4, 0.0, 0.0  rx=2.4 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1581433705] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 257916112405; DSPS: 8592708; Offset : -4327380652
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=2.7, 0.0, 0.0  rx=2.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1581430685] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=2.7, 0.0, 0.0  rx=2.7 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1581430681] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.8, 0.0, 0.0  rx=1.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1581427646] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.8, 0.0, 0.0  rx=1.8 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1581427635] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1581424613] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1581424610] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=4.0, 0.0, 0.0  rx=3.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1581421586] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=4.0, 0.0, 0.0  rx=3.5 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1581421576] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=2.0, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1581418555] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=2.0, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1581418543] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1581415522] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1581415519] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1581412492] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1581412489] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 277917967241; DSPS: 9248128; Offset : -4327356663
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1581409464] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1581409461] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,D/PowerManagerServiceEx( 1029): acquireWakeLockInternal: lock=307177574, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1029
,V/AlarmManager( 1029): ELAPSED_WAKEUP set : Alarm{4332972 type 2 when 280963 android} when 280963
D/[Concierge]Service( 2574): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1029): releaseWakeLockInternal: lock=307177574 [*alarm*], flags=0x0
,E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1581406435] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1581406425] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1029):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1581403404] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1029):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1581403401] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1029): doString: [SIGNAL_POLL]
,I/wpa_supplicant( 6313): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/WifiMonitor( 1029): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0]
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
E/WifiMonitor( 1029): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
D/WifiMonitor( 1029): handleNetworkStateChange: Could not parse disconnect string
E/WifiMonitor( 1029): WifiMonitor notify network disconnect: null reason=0
D/WifiMonitor( 1029): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1029):  ConnectedState NETWORK_DISCONNECTION_EVENT nid=0 reason=0 lastbssid=c0:ff:d4:d3:aa:48 freq=2412 rssi=-64 rt=287851
E/WifiStateMachine( 1029):  L2ConnectedState NETWORK_DISCONNECTION_EVENT nid=0 reason=0 lastbssid=c0:ff:d4:d3:aa:48 freq=2412 rssi=-64 rt=287851
E/WifiStateMachine( 1029):  ConnectModeState NETWORK_DISCONNECTION_EVENT nid=0 reason=0 lastbssid=c0:ff:d4:d3:aa:48 freq=2412 rssi=-64 rt=287851
E/WifiConfigStore( 1029): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1029): doBoolean: SET_NETWORK 0 bssid any
,D/Tethering( 1029): InitialState.processMessage what=4
D/Tethering( 1029): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiNative-wlan0( 1029): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1029): doBoolean: SAVE_CONFIG
,D/WifiNative-wlan0( 1029): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1029): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 6313): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1029): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1029): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1029): doBoolean: SET ps 1
D/WifiNative-wlan0( 1029): SET ps 1: returned true
D/DhcpStateMachine( 1029): RunningState{ when=-9ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  315): Clearing all IP addresses on wlan0
D/WifiMonitor( 1029): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,V/NativeCrypto( 2128): Read error: ssl=0xaa6eba00: I/O error during system call, Connection timed out
,I/jxcore-log( 6215): Toggling radios to false
I/jxcore-log( 6215): 
I/wpa_supplicant( 6313): wlan0: CTRL-EVENT-SCAN-STARTED 
,I/ActivityManager( 1029): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=7942 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/BluetoothManagerService( 1029): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1029): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@209591c3 mBinding = false
,D/WifiMonitor( 1029): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1029): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1029): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/ConnectivityService( 1029): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
V/NativeCrypto( 2128): SSL shutdown failed: ssl=0xaa6eba00: I/O error during system call, Broken pipe
D/ConnectivityService( 1029): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
E/WifiStateMachine( 1029): WifiStateMachine: Leaving Connected state
D/WifiHS20( 1029): hidePasspointNotification off =false
,E/WifiStateMachine( 1029):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=288051  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1029):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=288051  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1029):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1029):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1029):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1029):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1029):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/LocationManagerService( 1029): getAllProviders()=[passive, gps, network]
E/WifiStateMachine( 1029):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=288054  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/Ulp_jni ( 1029): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1029): JNI:system_update. Event-4
D/BluetoothManagerService( 1029): Message: 2
V/WfdStateTracker( 1974): handleWifiStateChangedEvent: 0
W/Settings( 1029): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1029): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1029): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/WifiHS20( 1029): hidePasspointNotification off =false
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1029): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1029): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1029): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,D/BluetoothManagerService( 1029): Sending off request.
D/WifiServiceImplEx( 1029): setWifiEnabled: false pid=6215, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1029): setWifiEnabled: false pid=6215, uid=10311
E/WifiService( 1029): Invoking mWifiStateMachine.setWifiEnabled
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1029): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1029): ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1029): DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1029): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1029): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1029): Checking http://clients3.google.com/generate_204 on <unknown ssid>
,I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
I/jxcore-log( 6215): Radios toggled
I/jxcore-log( 6215): 
D/LGBluetoothServiceAdapter( 6281): [BTUI] Precleanup
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/BluetoothAdapterState( 6281): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 6281): Setting state to 13
I/BluetoothAdapterState( 6281): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterProperties( 6281): onBluetoothDisable()
I/BluetoothAdapterState( 6281): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
D/BluetoothManagerService( 1029): Message: 60
D/BluetoothManagerService( 1029): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService( 1029): Bluetooth State Change Intent: 12 -> 13
D/LocationManagerService( 1029): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1029): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1029): JNI:system_update. Event-4
D/WifiHS20( 1029): hidePasspointNotification off =false
W/Settings( 1029): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1029): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1029): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
,D/BluetoothAdapterProperties( 6281): Scan Mode:20
D/BluetoothAdapterState( 6281): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/btif_config_util( 6281): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
V/BluetoothPbapService( 6281): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
W/bt-l2cap( 6281): L2CAP - L2CA_Deregister() called for PSM: 0x000f
W/bt-btif ( 6281): bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
V/BluetoothSapService( 6281): Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothFtpService:RfcommSocketAcceptThread( 6281): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/BtOppRfcommListener( 6281): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 6281): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 6281): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 6281): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
V/BluetoothMapMasInstance( 6281): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
V/BluetoothMapMasInstance( 6281): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
V/BluetoothMapMasInstance( 6281): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 6281): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 6281): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
V/AlarmManager( 1029): ELAPSED_WAKEUP set : Alarm{2e4a2d79 type 2 when 288094 com.google.android.gms} when 288094
W/bt-l2cap( 6281): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 6281): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 6281): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 6281): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 6281): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 6281): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 6281): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 6281): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 6281): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 6281): L2CAP - L2CA_Deregister() called for PSM: 0x0011
W/bt-l2cap( 6281): L2CAP - L2CA_Deregister() called for PSM: 0x0013
E/bt-btif ( 6281): bta_gattc_deregister Deregister Failedm unknown client cif
D/LGBluetoothAPIService( 1974): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,I/BluetoothMapService( 6281): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 6281): STATE_TURNING_OFF
V/BluetoothMapService( 6281): Handler(): got msg=4
D/BluetoothMapService( 6281): MAP Service closeService in
D/BluetoothMapMasInstance( 6281): MAP Service shutdown
D/LGBluetoothMapAdapter( 6281): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 6281): MAP Service closeService out
D/ConnectivityService( 1029): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1029): disableDataServiceNotify
D/DSQN    ( 1029): stop dsqn bin
I/[SystemUI]BluetoothHandler( 1472): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
V/BtOppService( 6281): Receiver DISABLED_ACTION 
I/BtOppRfcommListener( 6281): stopping Accept Thread
D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=0
V/BtOppRfcommListener( 6281): close mBtServerSocket
V/BtOppRfcommListener( 6281): waiting for thread to terminate
I/BtOppRfcommListener( 6281): BluetoothSocket listen thread finished
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1029): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
V/BtOppRfcommListener( 6281): done waiting for thread to terminate
D/DSQN    ( 1029): DNSproblemNotiEnabled is disabled ignore DNS fail CB
E/WifiStateMachine( 1029):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=288117  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine( 1029):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1029):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1029):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1029):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1029):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1029):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1029):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1029):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1029):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1029):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiNetworkAgent( 1029): NetworkAgent: NetworkAgent channel lost
V/BtOppService( 6281): onDestroy
E/WifiStateMachine( 1029):  DisconnectedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1029):  ConnectModeState CMD_STOP_SUPPLICANT 0 0
W/Settings( 1029): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/WifiStateMachine( 1029):  DriverStartedState CMD_STOP_SUPPLICANT 0 0
W/Settings( 1029): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1029): NETWORK_STATE_CHANGED_ACTION [SCANNING]
E/WifiStateMachine( 1029):  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
D/LGBluetoothOppAdapter( 6281): [BTUI] LGBluetoothOppAdapter cleanup
D/WifiServerServiceExt( 1029): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1029): setSupplicantStateDISCONNECTED
D/WifiScanningService( 1029): SCAN_AVAILABLE : 1
D/RttService( 1029): SCAN_AVAILABLE : 1
D/WifiScanningService( 1029): DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService( 1029): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1029): stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@2bf7abd9
D/LGWifiP2pService( 1029): P2pDisablingState
D/LGWifiP2pService( 1029): P2pDisablingState{ when=0 what=147458 targe,t=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): p2p socket connection lost
D/LGWifiP2pService( 1029): P2pDisabledState
,V/WfdStateTracker( 1974): WfdStateTracker handleDirectStateChangedEvent: 0
D/WfdsService( 1974): WifiP2pState is changed : false
D/WfdsService( 1974): WfdsEnabledState: Receive the WFDS_DISABLE message
D/WfdsService( 1974): Set the WFDS Monitor: false
E/WifiStateMachine( 1029):  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
D/LGWifiP2pService( 1029): P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1029): DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WfdsMonitor( 1974): WFDS Monitor is stopped
D/WfdsService( 1974): STATE : WfdsDisabledState - enter
D/WifiNative-wlan0( 1029): doBoolean: DRIVER BTCOEXMODE 2
D/CtrlSupplicant( 1974): Received on exit socket, terminate
E/CtrlSupplicant( 1974): wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
D/WfdsMonitor( 1974): Event [CTRL-EVENT-TERMINATING  - connection closed]
I/wpa_supplicant( 6313): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
W/WfdsSession:Controller( 1974): DefaultState - msg [9441355] is not handled
D/WfdsMonitor( 1974): WfdsMonitorThread is received the interrupt - closing
D/WifiNative-wlan0( 1029): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1029): doBoolean: SET ps 1
D/WifiServerServiceExt( 1029): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1029): setSupplicantStateSCANNING
D/WifiNative-wlan0( 1029): SET ps 1: returned true
W/WfdsService( 1974): DefaultState - msg [9445378] is not handled
D/CommandListener(  315): Clearing all IP addresses on wlan0
D/ConnectivityService( 1029): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1029):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1029):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1029): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat( 1029): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityManager.CallbackHandler( 1472): CM callback handler got msg 524292
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1029): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1029): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1029): Disconnected - quitting
D/WifiHS20( 1029): hidePasspointNotification off =false
W/ResourcesManager( 7942): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/CSLegacyTypeTracker( 1029): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,fe80::c69a:2ff:fe7b:60ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1029): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
W/ResourcesManager( 7942): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
D/ConnectivityService( 1029): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
W/ResourcesManager( 7942): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7942): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 7942): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7942): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
W/Settings( 1029): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1029): Setting wifi_sleep_,policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1029): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiNative-p2p0( 1029): doBoolean: TERMINATE
D/WifiNative-p2p0( 1029): TERMINATE: returned true
E/WifiStateMachine( 1029): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1029): useWiFiOffloading() : false
E/WifiStateMachine( 1029): CONFIG_LGE_WLAN_PATH : true
D/WifiHS20( 1029): hidePasspointNotification off =false
W/Settings( 1029): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1029): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1029): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/ConnectivityService( 1029): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1029): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1029): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1029): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1029): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService( 1029): Removing idletimer
,D/TelephonyNetworkFactory-1( 1866): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1866):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/WIFI    ( 1029): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1029):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
V/NetworkPolicy( 1029): [LG_RESTRICTED] !!!isConnected  type  :1
D/LocSvc_java( 1029): Sending msg: 4 arg1:0 arg2:1
V/WfdStateTracker( 1974): WfdStateTracker handleDirectStateChangedEvent: 6
V/NetworkPolicy( 1029): [LG_RESTRICTED] !!!isConnected  type  :1
W/Settings( 1029): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1029): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
E/ConnectivityService( 1029): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
I/WifiServerServiceExt( 1029): WIFI_STATE_CHANGED_ACTION [0]
D/LocSvc_java( 1029): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1029): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
,D/LocSvc_java( 1029): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java( 1029): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1029): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1029): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1029): ignore wifi update if we are not in OPENING or CLOSING
D/DhcpStateMachine( 1029): StoppedState
D/DhcpStateMachine( 1029): StoppedState{ when=-25ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine( 1029):  SupplicantStoppingState CMD_ON_QUIT 0 0
E/WifiStateMachine( 1029):  DefaultState CMD_ON_QUIT 0 0
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/TelephonyIcons( 1472): null signal icon name: drawable/stat_sys_signal_null
,D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/TelephonyIcons( 1472): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/UsbSettingsReceiver( 7942): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7942): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7942): [AUTORUN] sys.usb.state = ptp_only,adb
,D/UsbSettingsReceiver( 7942): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7942): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 7942): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7942): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 7942): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7942): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7942): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 7942): [AUTORUN] setTetherStatus() : status=false
I/ActivityManager( 1029): Killing 7386:com.google.android.configupdater/u0a59 (adj 15): empty #17
W/ContextImpl( 7942): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,V/BluetoothPbapReceiver( 6281): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 6281): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6281): ***********state = 13
,V/BluetoothPbapReceiver( 6281): ***********Calling start service!!!! with action = null
W/libprocessgroup( 1029): failed to open /acct/uid_10059/pid_7386/cgroup.procs: No such file or directory
V/BluetoothPbapService( 6281): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 6281): state: 13
V/BluetoothPbapService( 6281): Pbap Service closeService in
D/BluetoothManagerService( 1029): Message: 20
D/BluetoothManagerService( 1029): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ef02a6c:true
I/ActivityManager( 1029): Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=7986 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,V/BluetoothPbapService( 6281): successfully stopped pbap service
,V/BluetoothPbapService( 6281): Pbap Service closeService out
V/BluetoothPbapService( 6281): Pbap Service onDestroy
V/BluetoothPbapService( 6281): Pbap Service closeService in
V/BluetoothPbapService( 6281): Pbap Service closeService out
D/LGBluetoothPbapAdapter( 6281): [BTUI] cleanup
D/BluetoothManagerService( 1029): Message: 30
I/ActivityManager( 1029): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=8003 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,D/BluetoothManagerService( 1029): Message: 30
,D/LocalBluetoothProfileManager( 7942): Adding local MAP profile
D/BluetoothMap( 7942): Create BluetoothMap proxy object
D/BluetoothManagerService( 1029): Message: 30
W/ResourcesManager( 7986): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/BluetoothManagerService( 1029): Message: 30
,D/LocalBluetoothProfileManager( 7942): LocalBluetoothProfileManager construction complete
D/LGBluetoothFeatureConfig( 7942):  get() - isFeatureLoaded : false
D/PluginManager( 7986): init()
,D/LGBluetoothUserBindClient( 7942): [BTUI] initUserBindClient
,W/ContextImpl( 7942): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
,D/DockEventReceiver( 7942): finishStartingService: stopping service
D/BluetoothInputDevice( 7942): Proxy object connected
D/HidProfile( 7942): Bluetooth service connected
D/BluetoothPan( 7942): BluetoothPAN Proxy object connected
D/PanProfile( 7942): Bluetooth service connected
D/BluetoothMap( 7942): Proxy object connected
D/MapProfile( 7942): Bluetooth service connected
D/BluetoothMap( 7942): getConnectedDevices()
D/BluetoothMap( 7942): Bluetooth is Not enabled
D/LGBluetoothUserBindClient( 7942): [BTUI] onServiceConnected
,E/ActivityThread( 8003): Failed to find provider info for com.lge.lgaccount.provider
W/LG Account v2.2( 8003): No ProfileInfo entries
I/LG Account v2.2( 8003): isEnabled: false
I/Feature ( 8003): [Lifetracker]ver: 4.21.112(40211120)
I/Feature ( 8003): [Lifetracker]Country: EU
I/Feature ( 8003): [Lifetracker]Operator: OPEN
I/Feature ( 8003): [Lifetracker]Ranking support: false
I/Feature ( 8003): [Lifetracker]Comfort support: false
I/Feature ( 8003): [Lifetracker]Accessory: true
I/Feature ( 8003): [Lifetracker]Health device: true
I/Feature ( 8003): [Lifetracker]Extra Pedometer: false
I/Feature ( 8003): [Lifetracker]Blood glucose device: false
I/Feature ( 8003): [Lifetracker]Device Number: 3
,D/LGBluetoothAuthorization( 7942): [BTUI] cancel All Notification
,D/BluetoothPermissionRequest( 7942): onReceive
D/LGBluetoothAuthorization( 7942): [BTUI] cancel All Notification
D/LGBluetoothResetSettingReceiver( 7942): return without doing reset settings.
I/ActivityManager( 1029): Killing 7344:com.google.android.videos/u0a103 (adj 15): empty #17
,V/BluetoothOppReceiver( 6281): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
D/BluetoothOppNotification( 6281): [BTUI] cancel opp incoming file confirm notification
D/BluetoothOppNotification( 6281): [BTUI] cancel opp active transfer file notification
,W/libprocessgroup( 1029): failed to open /acct/uid_10103/pid_7344/cgroup.procs: No such file or directory
V/BluetoothFtpReceiver( 6281): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothFtpReceiver( 6281): BluetoothFtpReceiver Start Service
V/BluetoothFtpService( 6281): Ftp Service onStartCommand
V/BluetoothFtpService( 6281): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpService( 6281): Ftp Service closeService
E/BluetoothFtpService:RfcommSocketAcceptThread( 6281): Shutdown
V/BluetoothFtpService( 6281): successfully stopped ftp service
V/BluetoothSapReceiver( 6281): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 6281): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 6281): SapReceiver onReceive 
V/BluetoothSapReceiver( 6281): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6281):  Bluetooth Adapter state = 13
V/BluetoothSapReceiver( 6281): Calling SAP service start service with action = null
V/BluetoothFtpService( 6281): Ftp Service onDestroy
V/BluetoothFtpService( 6281): Ftp Service closeService
I/ActivityManager( 1029): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=8029 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,V/BluetoothSapService( 6281): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 6281): state: 13
V/BluetoothSapService( 6281): Stopping SAP server process
V/BluetoothSapService( 6281): Sap Service closeSapService in
V/BluetoothSapService( 6281): Close listen Socket : 
V/BluetoothSapService( 6281): Close rfcomm Socket : 
V/BluetoothSapService( 6281): Close sapd  Socket : 
,V/BluetoothSapService( 6281): Sap Service closeSapService out
,V/BluetoothSapService( 6281): Sap Service onDestroy
V/BluetoothSapService( 6281): Sap Service closeSapService in
V/BluetoothSapService( 6281): Close listen Socket : 
V/BluetoothSapService( 6281): Close rfcomm Socket : 
V/BluetoothSapService( 6281): Close sapd  Socket : 
V/BluetoothSapService( 6281): Sap Service closeSapService out
,W/ResourcesManager( 8029): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/ActivityManager( 1029): Killing 7050:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
,D/AuthorizationBluetoothService( 2128): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
W/libprocessgroup( 1029): failed to open /acct/uid_10005/pid_7050/cgroup.procs: No such file or directory
,W/ExternalStrings( 7986): load override strings
W/ExternalStrings( 7986): java.lang.RuntimeException: Unexpected tag, got eat-comment
W/ExternalStrings( 7986): 	at com.mcafee.plugin.af.a(Unknown Source)
W/ExternalStrings( 7986): 	at com.mcafee.plugin.ac.b(Unknown Source)
W/ExternalStrings( 7986): 	at com.mcafee.plugin.ak.d(Unknown Source)
W/ExternalStrings( 7986): 	at com.mcafee.plugin.ak.a(Unknown Source)
W/ExternalStrings( 7986): 	at com.mcafee.app.s.getClassLoader(Unknown Source)
W/ExternalStrings( 7986): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
W/ExternalStrings( 7986): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
W/ExternalStrings( 7986): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
W/ExternalStrings( 7986): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
W/ExternalStrings( 7986): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
W/ExternalStrings( 7986): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ExternalStrings( 7986): 	at android.os.Looper.loop(Looper.java:135)
W/ExternalStrings( 7986): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/ExternalStrings( 7986): 	at java.lang.reflect.Method.invoke(Native Method)
W/ExternalStrings( 7986): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/ExternalStrings( 7986): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/ExternalStrings( 7986): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,D/StatusProvider( 7986): onCreate
,V/Signer  ( 7986): override build config not found
D/Signer  ( 7986): value of property debug is false
,D/bt_hci_bdroid( 6281): cleanup
,D/LGMDMWrapper( 7986): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
D/LGMDMWrapper( 7986): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
D/LGMDMWrapper( 7986): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
D/LGMDMWrapper( 7986): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
I/bt_lpm  ( 6281): LPM is already off!!!
,D/LGMDMWrapper( 7986): Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
W/bt-btif ( 6281): ag scb idx 1 not allocated
E/bt-btif ( 6281): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 6281): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 6281): L2CAP - PSM: 0x0019 not found for deregistration
D/LGMDMWrapper( 7986): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
W/bt-l2cap( 6281): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 6281): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 6281): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 6281): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 6281): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 6281): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 6281): L2CAP - L2CA_Deregister() called for PSM: 0x0017
D/LGMDMWrapper( 7986): Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
W/bt-l2cap( 6281): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 6281): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 6281): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 6281): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 6281): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 6281): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 6281): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 6281): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 6281): L2CAP - PSM: 0x001b not found for deregistration
D/LGMDMWrapper( 7986): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
E/bt-btif ( 6281): bta_gattc_deregister Deregister Failedm unknown client cif
I/bt_userial_mct( 6281): exiting userial_read_thread
D/bt_userial_mct( 6281): Leaving userial_evt_read_thread()
D/bt_userial_mct( 6281): userial_close_reader Joined userial reader thread: 0
I/bt_vendor( 6281): hw_epilog_process
D/LGMDMWrapper( 7986): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
D/LGMDMWrapper( 7986): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
D/bt_hci_bdroid( 6281): cleanup Finalizing cleanup
D/bt_userial_mct( 6281): userial_close
E/bt_userial_mct( 6281): pthread_join() FAILED result:3
I/bt_vendor( 6281): bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
D/LGMDMWrapper( 7986): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
D/LGMDMWrapper( 7986): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
,D/LGMDMWrapper( 7986): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
V/LGMDMManager( 7986): Create singleton instance
,D/LGMDMWrapper( 7986): LG MDM library v4.0.0 is available on this device.
,D/bt_hci_bdroid( 6281): set_power 0
,I/bt_vendor( 6281): bt-vendor : BT_VND_OP_POWER_CTRL: Off
I/bt_vendor( 6281): bluetooth satus is on
I/bt_vendor( 6281): bt-vendor : resetting BT status
I/bt_vendor( 6281): Starting hciattach daemon
I/bt_vendor( 6281): try to set false
I/bt_vendor( 6281): Starting hciattach daemon
I/bt_vendor( 6281): try to set false
,I/bt_vendor( 6281): cleanup
I/GKI_LINUX( 6281): gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 6281): GKI_exit_task 0 done
I/GKI_LINUX( 6281): GKI_shutdown(): task [BTU] terminated
D/BluetoothAdapterState( 6281): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/HeadsetService( 6281): Received stop request...Stopping profile...
,I/LGBluetoothHfpAdapter( 6281): [BTUI] LGBluetoothHfpAdapter cleanup
W/LGBluetoothHeadsetServiceJni( 6281): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 6281): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@368bf2cb
D/HeadsetStateMachine( 6281): Exit Disconnected: -1
D/BluetoothHeadset( 1866): Proxy object disconnected
D/BluetoothHeadset( 1866): Proxy object disconnected
D/BluetoothHeadset( 1866): Proxy object disconnected
D/BluetoothHeadset( 1029): Proxy object disconnected
D/AudioService( 1029): onServiceDisconnected: Bluetooth profile: 1
D/A2dpService( 6281): Received stop request...Stopping profile...
D/A2dpStateMachine( 6281): Exit Disconnected: -1
D/LGBluetoothAvrcpQcomAdapter( 6281): [BTUI] cleanup
D/LGBluetoothA2dpAdapter( 6281): [BTUI] LGBluetoothA2dpAdapter cleanup
W/LGBluetoothA2dpServiceJni( 6281): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 6281): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@368bf2cb
,D/BluetoothAdapterState( 6281): Stopping profile services that were post enabled
D/BluetoothA2dp( 1029): Proxy object disconnected
D/AudioService( 1029): onServiceDisconnected: Bluetooth profile: 2
D/HidService( 6281): Received stop request...Stopping profile...
D/BluetoothAdapterService( 6281): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@368bf2cb
D/HeadsetStateMachine( 6281): Unbinding service...
D/BluetoothInputDevice( 7942): Proxy object disconnected
D/HidProfile( 7942): Bluetooth service disconnected
D/HeadsetPhoneState( 6281): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 6281): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetPhoneState( 6281): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 6281): [BTUI] listenForMultiSimPhoneState : start = false
W/BluetoothHeadsetServiceJni( 6281): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 6281): Cleaning up Bluetooth Handsfree callback object
I/LGBluetoothHfpAdapter( 6281): [BTUI] LGBluetoothHfpAdapter cleanup
D/HealthService( 6281): Received stop request...Stopping profile...
D/BluetoothAdapterService( 6281): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@368bf2cb
D/PanService( 6281): Received stop request...Stopping profile...
D/BluetoothAdapterService( 6281): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@368bf2cb
D/BluetoothPan( 7942): BluetoothPAN Proxy object disconnected
D/PanProfile( 7942): Bluetooth service disconnected
D/BtGatt.DebugUtils( 6281): handleDebugAction() action=null
D/BtGatt.GattService( 6281): Received stop request...Stopping profile...
D/BtGatt.GattService( 6281): stop()
D/BtGatt.AdvertiseManager( 6281): advertise clients cleared
,D/BluetoothAdapterService( 6281): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@368bf2cb
D/BluetoothMapService( 6281): Received stop request...Stopping profile...
D/BluetoothMapService( 6281): stop()
D/BluetoothMapEmailAppObserver( 6281): deinitObservers()
D/BluetoothMapEmailAppObserver( 6281): removeReceiver()
D/BluetoothAdapterService( 6281): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@368bf2cb
D/BluetoothMap( 7942): Proxy object disconnected
D/MapProfile( 7942): Bluetooth service disconnected
I/BluetoothA2dpServiceJni( 6281): cleanupNative
I/GKI_LINUX( 6281): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 6281): GKI_exit_task 2 done
I/GKI_LINUX( 6281): GKI_shutdown(): task [A2DP-MEDIA] terminated
W/BluetoothHidServiceJni( 6281): Cleaning up Bluetooth HID Interface...
W/BluetoothHidServiceJni( 6281): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 6281): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 6281): Cleaning up Bluetooth Health object
W/LGBluetoothHealthServiceJni( 6281): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 6281): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 6281): Cleaning up Bluetooth PAN callback object
V/BluetoothMapService( 6281): Handler(): got msg=4
D/BluetoothMapService( 6281): MAP Service closeService in
D/LGBluetoothMapAdapter( 6281): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 6281): MAP Service closeService out
D/BluetoothMapService( 6281): cleanup()
D/BluetoothMapService( 6281): MAP Service closeService in
D/LGBluetoothMapAdapter( 6281): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 6281): MAP Service closeService out
D/BluetoothAdapterState( 6281): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 6281): Setting state to 10
I/BluetoothAdapterState( 6281): Bluetooth adapter state changed: 13-> 10
,D/BluetoothManagerService( 1029): Message: 60
D/BluetoothManagerService( 1029): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService( 1029): Broadcasting onBluetoothStateChange(false) to 9 receivers.
D/BluetoothHeadset( 1029): onBluetoothStateChange: up=false
I/BluetoothAdapterState( 6281): Entering OffState
D/BluetoothMap( 7942): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1866): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1866): onBluetoothStateChange: up=false
D/BluetoothInputDevice( 7942): onBluetoothStateChange: up=false
D/BluetoothPan( 7942): onBluetoothStateChange on: false
D/BluetoothHeadset( 1866): onBluetoothStateChange: up=false
D/BluetoothA2dp( 1029): onBluetoothStateChange: up=false
D/BluetoothPbap( 7942): onBluetoothStateChange: up=false
D/BluetoothManagerService( 1029): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService( 1029): Broadcasting onBluetoothServiceDown() to 8 receivers.
D/BluetoothManagerService( 1029): Calling onQBluetoothServiceDown callbacks
D/BluetoothManagerService( 1029): Broadcasting onQBluetoothServiceDown() to 0 receivers.
D/BluetoothManagerService( 1029): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@209591c3 mBinding = false
D/BluetoothManagerService( 1029): Sending unbind request.
D/BluetoothManagerService( 1029): Bluetooth State Change Intent: 13 -> 10
D/LGBluetoothAPIService( 1974): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/LGBluetoothAPIService( 1974): Message: 2
D/LGBluetoothAPIService( 1974): unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@3310e337 mBinding = false
D/LGBluetoothAPIService( 1974): Sending unbind request.
,I/[SystemUI]BluetoothHandler( 1472): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
D/LGBluetoothFeatureConfig( 7942): isPrivacyLogsEnabled : true
E/LGBluetoothEventManager( 7942): [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
D/LGBluetoothEventManager( 7942): [BTUI] clear device connection state
D/BluetoothAdapter( 1472): 708455293: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1472): 708455293: getState() :  mService = null. Returning STATE_OFF
W/ContextImpl( 7986): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
D/PostponalbeReceiver( 7986): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 7942): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,I/GKI_LINUX( 6281): gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 6281): GKI_exit_task 1 done
I/GKI_LINUX( 6281): GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 6281): cleanupNative: return from cleanup
I/art     ( 6281): --- WEIRD: removing null entry 246
W/art     ( 6281): JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
W/LGBluetoothServiceJni( 6281): Cleaning up Bluetooth Service callback object
I/ActivityManager( 1029): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8063 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,D/LGBluetoothSettingsDBObserver( 6281): [BTUI] unregister observer for LG device name DB
D/DockEventReceiver( 7942): finishStartingService: stopping service
I/art     ( 6281): System.exit called, status: 0
I/AndroidRuntime( 6281): VM exiting with result code 0, cleanup skipped.
I/ActivityManager( 1029): Killing 7673:com.google.android.talk/u0a72 (adj 15): empty #17
V/AudioFlinger(  320): 6281 died, releasing its sessions
V/AudioFlinger(  320):  pid 1866 @ 0
V/AudioFlinger(  320):  pid 3301 @ 1
,V/AudioFlinger(  320):  pid 3301 @ 2
,D/LGBluetoothUserBindClient( 7942): [BTUI] onServiceDisconnected
W/ActivityThread( 7986): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/ActivityManager( 1029): Process com.android.bluetooth (pid 6281) has died
W/ActivityManager( 1029): Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,W/libprocessgroup( 1029): failed to open /acct/uid_10072/pid_7673/cgroup.procs: No such file or directory
,D/BluetoothPermissionRequest( 7942): onReceive
D/LGBluetoothUtils( 7942): [BTUI] FileNotFound: readProperty
D/BluetoothDiscoverableTimeoutReceiver( 7942): cancelDiscoverableAlarm(): Enter
D/LGBluetoothResetSettingReceiver( 7942): return without doing reset settings.
I/PCSuite ( 8063): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 8063): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 8063): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager( 1029): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=8097 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,V/WiFiOffLoadBroadcast( 7942): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/art     (  355): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 446us total 39.335ms
,D/LgDataFeature( 7942): LgDataFeature() Constructor: none
,D/LgDataFeature( 7942): LgDataFeature() Constructor Done, null
W/ResourcesManager( 8097): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager( 8097): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 8097): Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 8097): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/WiFiOffLoadBroadcast( 7942): MCCMNC not supported: null
D/QRemote ( 6511): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6511): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6511): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 7986): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 7986): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
I/art     (  355): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 404us total 18.768ms
I/PCSuite ( 8063): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 8063): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 8063): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7942): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/BluetoothAdapterApp( 8097): Loading JNI Library
,D/WiFiOffLoadBroadcast( 7942): MCCMNC not supported: null
D/QRemote ( 6511): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6511): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6511): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
I/art     (  355): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 348us total 16.720ms
D/PostponalbeReceiver( 7986): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 7986): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
I/PCSuite ( 8063): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 8063): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 8063): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7942): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7942): MCCMNC not supported: null
D/LgDataFeature( 7986): LgDataFeature() Constructor: none
D/LgDataFeature( 7986): LgDataFeature() Constructor Done, null
D/QRemote ( 6511): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6511): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6511): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,I/ActivityManager( 1029): Killing 7494:com.lge.appbox.client/u0a11 (adj 15): empty #17
D/BluetoothAdapterApp( 8097): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@15a0f990 Instance Count = 1
D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1029): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,V/AlarmManager( 1029): ELAPSED_WAKEUP set : Alarm{31e94ecc type 2 when 289712 com.google.android.gms} when 289712
W/libprocessgroup( 1029): failed to open /acct/uid_10011/pid_7494/cgroup.procs: No such file or directory
,D/BluetoothAdapterApp( 8097): onCreate
D/PostponalbeReceiver( 7986): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 7986): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
V/WiFiOffLoadBroadcast( 7942): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/ProfileConfigQcom( 8097): [BTUI] HeadsetService is supported
D/ProfileConfigQcom( 8097): Adding HeadsetService
D/ProfileConfigQcom( 8097): [BTUI] A2dpService is supported
D/ProfileConfigQcom( 8097): Adding A2dpService
D/ProfileConfigQcom( 8097): [BTUI] HidService is supported
,D/ProfileConfigQcom( 8097): Adding HidService
D/ProfileConfigQcom( 8097): [BTUI] HealthService is supported
,D/ProfileConfigQcom( 8097): Adding HealthService
D/LGBluetoothFeatureConfig( 8097): isSupportPan() :  mTargetOp=OPEN
D/ProfileConfigQcom( 8097): [BTUI] PanService is supported
D/ProfileConfigQcom( 8097): Adding PanService
D/ProfileConfigQcom( 8097): [BTUI] GattService is supported
D/ProfileConfigQcom( 8097): Adding GattService
D/ProfileConfigQcom( 8097): [BTUI] BluetoothMapService is supported
D/ProfileConfigQcom( 8097): Adding BluetoothMapService
D/WiFiOffLoadBroadcast( 7942): MCCMNC not supported: null
D/ProfileConfigQcom( 8097): [BTUI] HeadsetClientService is NOT supported
D/LGBluetoothOppAdapter( 8097): [BTUI] getInstance : create [LGBluetoothOppAdapter]
W/ContextImpl( 7986): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
D/QRemote ( 6511): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6511): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6511): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/LGMDMManagerInternal( 8097): Create singleton instance
D/LGBluetoothUserBindClient( 7942): [BTUI] onServiceConnected
D/PostponalbeReceiver( 7986): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 7986): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
I/PCSuite ( 8063): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 8063): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 8063): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7942): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/SiteAdvisor( 7986): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
D/WiFiOffLoadBroadcast( 7942): MCCMNC not supported: null
D/QRemote ( 6511): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6511): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/SiteAdvisor( 7986): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
,D/SiteAdvisor( 7986): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
I/QRemote ( 6511): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/SiteAdvisor( 7986): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
D/SiteAdvisor( 7986): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
D/PostponalbeReceiver( 7986): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/SiteAdvisor( 7986): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
W/ContextImpl( 7986): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
I/PCSuite ( 8063): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 8063): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 8063): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/SiteAdvisor( 7986): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
,V/WiFiOffLoadBroadcast( 7942): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/SiteAdvisor( 7986): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
D/WiFiOffLoadBroadcast( 7942): MCCMNC not supported: null
,D/QRemote ( 6511): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6511): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6511): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,I/ActivityManager( 1029): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8125 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,V/BluetoothFtpReceiver( 8097): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothSapReceiver( 8097): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 8097): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 8097): SapReceiver onReceive 
V/BluetoothSapReceiver( 8097): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 8097):  Bluetooth Adapter state = 10
D/LGBluetoothProfileConnectionReceiver_EasySetting( 8029): [BTUI] STATE_OFF : reset connected device information EasySettings
,I/ActivityManager( 1029): Killing 7530:com.android.contacts/u0a19 (adj 15): empty #17
,D/AuthorizationBluetoothService( 2128): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
W/libprocessgroup( 1029): failed to open /acct/uid_10019/pid_7530/cgroup.procs: No such file or directory
,E/WifiStateMachine( 1029):  SupplicantStoppingState CMD_RSSI_POLL 1 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2998] from screen [on:0 period:-1581400373] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1029):  DefaultState CMD_RSSI_POLL 1 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1581400371] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/PCSuite ( 8063): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7942): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,D/WiFiOffLoadBroadcast( 7942): MCCMNC not supported: null
,W/FormManager( 8125): Network not available. Please check & try again.
,D/PostponalbeReceiver( 7986): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
D/PostponalbeReceiver( 7986): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
D/PostponalbeReceiver( 7986): WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
V/FormManager( 8125): Network unavailable.
V/FormManager( 8125): Network unavailable.
,I/ActivityManager( 1029): Killing 7554:com.android.gallery3d/u0a27 (adj 15): empty #17
,I/wpa_supplicant( 6313): p2p0: CTRL-EVENT-TERMINATING 
I/wpa_supplicant( 6313): monitor socket send errors count : 1
I/wpa_supplicant( 6313): CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1974-2\x00 that cannot receive messages
,W/wpa_supplicant( 6313): USIM:  scard_deinit function
D/WifiMonitor( 1029): Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
,D/WifiMonitor( 1029): Dropping event because (p2p0) is stopped
D/WifiMonitor( 1029): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1029):  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=290069  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: DISCONNECTED
E/WifiStateMachine( 1029):  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=290069  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: DISCONNECTED
W/libprocessgroup( 1029): failed to open /acct/uid_10027/pid_7554/cgroup.procs: No such file or directory
,D/PostponalbeReceiver( 7986): WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
D/PostponalbeReceiver( 7986): WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/wpa_supplicant( 6313): wlan0: CTRL-EVENT-TERMINATING 
D/WifiMonitor( 1029): Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
E/WifiMonitor( 1029): WifiMonitor:wlan0 cnt=25 dispatchEvent: CTRL-EVENT-TERMINATING 
D/WifiMonitor( 1029): Disconnecting from the supplicant, no more events
E/WifiStateMachine( 1029):  SupplicantStoppingState SUP_DISCONNECTION_EVENT 25 0
D/PostponalbeReceiver( 7986): WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
V/AlarmManager( 1029): ELAPSED_WAKEUP set : Alarm{31f0ab64 type 2 when 290142 com.google.android.gms} when 290142
,D/WifiOffDelayIfNotUsed( 1029): stopMonitoring
,E/WifiStateMachine( 1029): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1029): useWiFiOffloading() : false
E/WifiStateMachine( 1029): CONFIG_LGE_WLAN_PATH : true
D/WfdsService( 1974): Supplicant Connection state is changed : false
,D/WfdsService( 1974): DefaultState - WIFI_SUPPLICANT_DISCONNECTED
D/WfdsService( 1974): Set the WFDS Monitor: false
D/WfdsMonitor( 1974): WFDS Monitor is stopped
D/LGDMClient( 4031): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
V/WfdStateTracker( 1974): WfdStateTracker handleDirectStateChangedEvent: 0
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/WifiServerServiceExt( 1029): WIFI_STATE_CHANGED_ACTION [1]
W/Settings( 1831): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/WifiServerServiceExt( 1029): batteryPsActivateMsgHandler : state:0 event:1
I/WifiServerServiceExt( 1029): batteryPsActivateMsgHandler : this is not treated
D/LGDMClient( 4031): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4031): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4031): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,D/LGDMClient( 4031): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,I/PCSuite ( 8063): [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
D/PCSuite ( 8063): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 8063): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/LGDMClient( 4031): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 4031): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/WiFiOffLoadBroadcast( 7942): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,W/FormManager( 8125): Network not available. Please check & try again.
V/FormManager( 8125): Network unavailable.
D/WiFiOffLoadBroadcast( 7942): MCCMNC not supported: null
V/FormManager( 8125): Network unavailable.
,V/AlarmManager( 1029): ELAPSED_WAKEUP set : Alarm{8bf19d0 type 2 when 290328 com.google.android.gms} when 290328
,V/AlarmManager( 1029): ELAPSED_WAKEUP set : Alarm{3a1b8dc9 type 2 when 290682 com.google.android.gms} when 290682
,D/ConnectivityService( 1029): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1029): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1029): MasterInitialState.processMessage what=3
D/ConnectivityService( 1029): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1029): MasterInitialState.processMessage what=3
D/PostponalbeReceiver( 7986): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,I/NetworkMonitor( 5323): type=WIFI subType= reason=null isConnected=false
,I/NetworkMonitor( 5323): type=WIFI subType= reason=null isConnected=false
,W/ContextImpl( 7986): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/ActivityManager( 1029): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=8173 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/GpsLocationProvider( 1029): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1029): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1029): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/AlarmManager( 1029): ELAPSED_WAKEUP set : Alarm{7a627ef type 2 when 291389 com.google.android.gms} when 291389
,I/art     ( 1029): Explicit concurrent mark sweep GC freed 89868(4MB) AllocSpace objects, 5(464KB) LOS objects, 33% free, 44MB/66MB, paused 1.931ms total 158.410ms
,I/AppUp4:AppBoxCP( 8173): onCreate
,W/AppUp4:DB( 8173):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 8173):  setFingerPrint start
I/AppUp4:DB( 8173):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 8173):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 8173):  SDK version = 21
I/AppUp4:DB( 8173):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 8173): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 8173): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 8173): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 8173): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 8173): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 8173): onReceive
,D/LgDataFeature( 8173): LgDataFeature() Constructor: none
,D/LgDataFeature( 8173): LgDataFeature() Constructor Done, null
D/AppUp4:CustFacade( 8173): Context : android.app.ReceiverRestrictedContext@2841c99a
D/AppUp4:CustFacade( 8173): isCustomizationCompleted : false
D/AppUp4:CustFacade( 8173): isPhone : true
D/AppUp4:CustModeStarterReceiver( 8173): begin check event
,I/AppUp4:CustModeStarterReceiver( 8173): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 8173): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 8173): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 8173): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 8173): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1029): Killing 7594:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,D/LGDMClient( 4031): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
W/libprocessgroup( 1029): failed to open /acct/uid_10080/pid_7594/cgroup.procs: No such file or directory
D/LGDMClient( 4031): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 4031): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,W/ContextImpl( 4031): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,D/LGDMClient( 4031): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/LGDMClient( 4031): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4031): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,I/ActivityManager( 1029): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=8215 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,W/ResourcesManager( 8215): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8215): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 8215): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 8215): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,I/LGEmail ( 8215): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 8215): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,W/ResourceType( 8215): No package identifier when getting value for resource number 0x00000000
,D/LgDataFeature( 8215): LgDataFeature() Constructor: none
,D/LgDataFeature( 8215): LgDataFeature() Constructor Done, null
,D/eas_req ( 8215): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/HubEmail( 8215): JNI_OnLoad()
I/HubEmail( 8215): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 8215): registerNatives()
I/HubEmail( 8215): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 8215): registerNativeMethods()
I/HubEmail( 8215): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,W/art     ( 8215): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
W/FormManager( 8125): Network not available. Please check & try again.
V/FormManager( 8125): Network unavailable.
,W/Settings( 8215): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/LgeMiscReceiver( 3301): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3301): action = android.net.conn.CONNECTIVITY_CHANGE
,V/FormManager( 8125): Network unavailable.
I/LgeMiscReceiver( 3301): networkInfo.isConnected() = false
I/ActivityManager( 1029): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=8244 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1029): Killing 6901:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,W/libprocessgroup( 1029): failed to open /acct/uid_10097/pid_6901/cgroup.procs: No such file or directory
,I/ActivityManager( 1029): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=8262 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
I/ActivityManager( 1029): Killing 7643:com.google.android.gms:car/u0a5 (adj 15): empty #17
,W/libprocessgroup( 1029): failed to open /acct/uid_10005/pid_7643/cgroup.procs: No such file or directory
,I/ActivityManager( 1029): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=8279 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1029): Killing 7111:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
,W/libprocessgroup( 1029): failed to open /acct/uid_10005/pid_7111/cgroup.procs: No such file or directory
I/art     ( 8279): Almond Protected OAT
,D/WeatherApplication( 8279): removeAccount
,D/WeatherApplication( 8279): Account.length = 0
E/WeatherApplication( 8279): OPERATOR:OPEN
D/WeatherAncestor( 8279): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:28:36
D/Weather.Utils( 8279): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 8279): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 8279): 2 : This is isUpdating : false
,D/WeatherAncestor( 8279): connectivity changed - connection : true
D/WeatherService( 8279): 2 : isServiceAlived():false forecastCache:null
D/ForecastDataCache( 8279): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 8279): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 8279): 2 : Cache is not up-to-date, count: 0
,D/Weather_cast( 8279): 2 : isUpdateNeedForAlarm : no city return false
,D/WeatherAncestor( 8279): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:28:36
,D/LGWifiP2pService( 1029): P2pDisabledState{ when=-5ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1029): DefaultState{ when=-5ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine( 1029):  InitialState CMD_STOP_SUPPLICANT_FAILED 1 0
E/WifiStateMachine( 1029):  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
I/ActivityManager( 1029): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=8297 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1029): Killing 7287:com.google.android.apps.docs/u0a61 (adj 15): empty #17
W/libprocessgroup( 1029): failed to open /acct/uid_10061/pid_7287/cgroup.procs: No such file or directory
,E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8297): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8297): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8297): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8297): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/WebViewFactory( 8297): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 8297): Loading: webviewchromium
,I/LibraryLoader( 8297): Time to load native libraries: 7 ms (timestamps 3612-3619)
I/LibraryLoader( 8297): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 8297): Binding Chromium to main looper Looper (main, tid 1) {33155197}
,I/LibraryLoader( 8297): Expected native library version number "",actual native library version number ""
I/chromium( 8297): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 8297): Initializing chromium process, renderers=0
,W/art     ( 8297): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 8297): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 8297): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 8297): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
V/AudioPolicyService(  320): registerClient() client 0xb148f060, uid 10093
W/AudioManagerAndroid( 8297): Requires BLUETOOTH permission
I/Adreno-EGL( 8297): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 8297): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 8297): Build Date: 12/12/14 금
I/Adreno-EGL( 8297): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 8297): Remote Branch: 
I/Adreno-EGL( 8297): Local Patches: 
I/Adreno-EGL( 8297): Reconstruct Branch: 
,I/NSApplication( 8297): Starting up...
,I/ActivityManager( 1029): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=8352 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1029): Killing 7576:com.android.vending/u0a44 (adj 15): empty #17
,W/libprocessgroup( 1029): failed to open /acct/uid_10044/pid_7576/cgroup.procs: No such file or directory
,W/ResourcesManager( 8352): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/iu.Environment( 2340): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 2340): num queued entries: 0
I/iu.UploadsManager( 2340): num updated entries: 0
I/iu.SyncManager( 2340): NEXT; no task
D/ChimeraCfgMgr( 2340): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PostponalbeReceiver( 7986): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 7986): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 8173): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 8173): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 8173): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 8173): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 8173): onReceive
,D/AppUp4:CustFacade( 8173): Context : android.app.ReceiverRestrictedContext@2841c99a
D/AppUp4:CustFacade( 8173): isCustomizationCompleted : false
D/AppUp4:CustFacade( 8173): isPhone : true
D/AppUp4:CustModeStarterReceiver( 8173): begin check event
I/AppUp4:CustModeStarterReceiver( 8173): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4031): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4031): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 4031): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4031): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/eas_req ( 8215): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
D/LGDMClient( 4031): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,D/LGDMClient( 4031): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4031): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/LgeMiscReceiver( 3301): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 3301): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3301): networkInfo.isConnected() = false
W/Settings( 8215): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/FormManager( 8125): Network not available. Please check & try again.
I/GLSActivity( 2128): [ac] getting account id
D/WeatherAncestor( 8279): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:28:37
D/Weather.Utils( 8279): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 8279): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 8279): 2 : This is isUpdating : false
D/WeatherAncestor( 8279): connectivity changed - connection : true
D/WeatherService( 8279): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@31926aa8
D/ForecastDataCache( 8279): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 8279): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 8279): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 8279): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 8279): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:28:37
V/FormManager( 8125): Network unavailable.
,I/GLSUser ( 2128): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
V/FormManager( 8125): Network unavailable.
D/ChimeraCfgMgr( 2340): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1029): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 297921781921; DSPS: 9903613; Offset : -4327356603
,I/GAV4    ( 8297): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager( 1029): Killing 7804:com.google.android.apps.books/u0a54 (adj 15): empty #17
,W/libprocessgroup( 1029): failed to open /acct/uid_10054/pid_7804/cgroup.procs: No such file or directory
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
I/[SystemUI]Clock( 1472): called onTimeUpdated()
I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 317923916653; DSPS: 10559043; Offset : -4327358152
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 337925745135; DSPS: 11214463; Offset : -4327360726
,D/PowerManagerServiceEx( 1029): acquireWakeLockInternal: lock=307177574, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1029
,D/[Concierge]Service( 2574): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1029): releaseWakeLockInternal: lock=307177574 [*alarm*], flags=0x0
,I/ActivityManager( 1029): Killing 8003:com.lge.lifetracker/u0a37 (adj 15): empty #17
,W/libprocessgroup( 1029): failed to open /acct/uid_10037/pid_8003/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 357927848562; DSPS: 11869892; Offset : -4327363089
,I/[SystemUI]LGPowerUI( 1472): onReceive = com.lge.android.intent.action.BATTERYEX
,I/[SystemUI]LGPowerUI( 1472): On Skip Timer : true
,D/WifiController( 1029): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1472): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
,I/[SystemUI]LGPowerUI( 1472): onReceive = android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1974): ACTION_BATTERY_CHANGED : plugged type=2
,D/LEDHandler( 1974): Battery Level Remaining: 100%
D/LEDHandler( 1974): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
,D/LGDMClient( 4031): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4031): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,I/[SystemUI]BatterySaverHandler( 1472): onReceive = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
,I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 377929842463; DSPS: 12525318; Offset : -4327383426
,D/PowerManagerServiceEx( 1029): acquireWakeLockInternal: lock=307177574, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1029
,I/ActivityManager( 1029): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=8438 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,D/[Concierge]Service( 2574): onStartCommand(). Type : 9
,I/DigitalAppWidgetProvider( 8438): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 8438): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@46a5aaf
D/PowerManagerServiceEx( 1029): releaseWakeLockInternal: lock=307177574 [*alarm*], flags=0x0
I/ActivityManager( 1029): Killing 7722:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
I/QRemote ( 6511): [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
W/System.err( 6511): android.os.DeadObjectException
W/System.err( 6511): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6511): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6511): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 6511): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
W/System.err( 6511): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 6511): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 6511): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6511): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6511): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6511): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 6511): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6511): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6511): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 6511): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,E/UEI.SmartControl( 6511): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 6511): android.os.DeadObjectException
,W/System.err( 6511): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6511): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6511): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 6511): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
W/System.err( 6511): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 6511): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 6511): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6511): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6511): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6511): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 6511): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6511): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6511): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 6511): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 6511): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/QRemote ( 6511): [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
W/libprocessgroup( 1029): failed to open /acct/uid_1000/pid_7722/cgroup.procs: No such file or directory
W/ActivityManager( 1029): Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,D/QRemote ( 6511): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
I/QRemote ( 6511): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
I/ActivityManager( 1029): Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=8473 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/QRemote ( 6511): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,D/UEI.SmartControl( 8473): Quickset Services start...
,I/UEI.SmartControl( 8473): Manufacture = LGE
,D/UEI.SmartControl( 8473): Id = LGNevo
D/UEI.SmartControl( 8473): File observer start...
E/UEI.SmartControl( 8473): IR Port is disabled: false
,D/UEI.SmartControl( 8473): Starting file observer...
D/UEI.SmartControl( 8473): Extracting JNI libs...
,D/UEI.SmartControl( 8473): --- this system supports 32-bit or 64-bit only
,D/UEI.SmartControl( 8473): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 8473): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 8473): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 8473): --- Selecting new region: 6
,I/UEI.SmartControl( 8473): Model = LG-D855
,D/UEI.SmartControl( 8473): QS Service created
,I/UEI.SmartControl( 8473): Service initServices...
D/UEI.SmartControl( 8473): QS start get config
,D/UEI.SmartControl( 8473): Loading JNI Libs...
,I/UEI.SmartControl( 8473): Supports setup maps: true
,D/UEI.SmartControl( 8473): QS start statue = true Error code = 0
I/UEI.SmartControl( 8473): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 8473): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 8473): ### init IR Blaster...
D/serial_port( 8473): Configuring serial port
E/UEI.SmartControl( 8473): UEIBLaster setting for 616
I/UEI.SmartControl( 8473): Setting serial record hearder size = 2
I/UEI.SmartControl( 8473): configuring settings for MAXQ616
I/UEI.SmartControl( 8473): Get version...
D/UEI.SmartControl( 8473): serial port data available: 21
,D/UEI.SmartControl( 8473): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 8473): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 8473): QS saving settings...
D/UEI.SmartControl( 8473): IR Blaster version: 25672567
,D/UEI.SmartControl( 8473): serial port data available: 4
,I/UEI.SmartControl( 8473): Device manager: loading config....
,D/UEI.SmartControl( 8473): ----------- loading internal config...
,W/ContextImpl( 8473): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,E/UEI.SmartControl( 8473): Services init done
D/UEI.SmartControl( 8473): QS Service init finished
D/UEI.SmartControl( 8473): QS Service version name: 2.1.91
D/UEI.SmartControl( 8473): QS Service version code: 201091
D/UEI.SmartControl( 8473): Service requested: Control
E/UEI.SmartControl( 8473): Loading SETTINGS...
,D/UEI.SmartControl( 8473): Request IControl service: devices are loaded...
I/ActivityManager( 1029): Killing 6511:com.lge.qremote/u0a112 (adj 15): empty #17
D/UEI.SmartControl( 8473): -- Open brand translation xml: brands_translations_ko
,I/UEI.SmartControl( 8473): Notify AllClients services are ready: 0,
D/UEI.SmartControl( 8473): -----service ready thread exits
,W/libprocessgroup( 1029): failed to open /acct/uid_10112/pid_6511/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 8473): Internal service binding...
,V/AlarmManager( 1029): ELAPSED_WAKEUP set : Alarm{106691a7 type 2 when 383531 android} when 383531
,D/serial_port( 8473): close(fd = 25)
,I/UEI.SmartControl( 8473): Serial port is closed.
,D/UEI.SmartControl( 8473): Internal timer expired: 1
D/UEI.SmartControl( 8473): unbind internal service
,D/UEI.SmartControl( 8473): Service.onUnbind: IControl
,D/UEI.SmartControl( 8473): Service.onDestroy
,D/UEI.SmartControl( 8473): Lock is in USE false
,D/UEI.SmartControl( 8473): unbind internal service
,W/System.err( 8473): java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@b62e566
W/System.err( 8473): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
,W/System.err( 8473): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
,W/System.err( 8473): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
,W/System.err( 8473): 	at com.uei.control.Service.c(Unknown Source)
,W/System.err( 8473): 	at com.uei.control.Service.onDestroy(Unknown Source)
W/System.err( 8473): 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
W/System.err( 8473): 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
,W/System.err( 8473): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
W/System.err( 8473): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 8473): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 8473): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 8473): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 8473): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 8473): 	,at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 8473): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 8473): java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@b62e566
I/UEI.SmartControl( 8473): Serial port is closed.
I/UEI.SmartControl( 8473): Serial port is closed.
D/UEI.SmartControl( 8473): Blaster closed
D/UEI.SmartControl( 8473): Shut down QS...
D/UEI.SmartControl( 8473): Stopping QS lib
,D/UEI.SmartControl( 8473): QS lib stop result = true
D/UEI.SmartControl( 8473): Stopped QS lib
D/UEI.SmartControl( 8473): Stopped file observer...
D/UEI.SmartControl( 8473): QS shutdown complete
D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 397932490633; DSPS: 13180764; Offset : -4327359612
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 417934569011; DSPS: 13836192; Offset : -4327356533
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
,I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 437936448326; DSPS: 14491614; Offset : -4327369283
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 457938578057; DSPS: 15147044; Offset : -4327375886
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 477941201540; DSPS: 15802490; Offset : -4327376732
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
,I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 497943113980; DSPS: 16457912; Offset : -4327356382
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 517944958659; DSPS: 17113333; Offset : -4327373432
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 537947008600; DSPS: 17768760; Offset : -4327368064
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
,I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 557948995623; DSPS: 18424185; Offset : -4327364735
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 577951457388; DSPS: 19079626; Offset : -4327374895
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 597953566025; DSPS: 19735055; Offset : -4327372100
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
,I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 617955375132; DSPS: 20390474; Offset : -4327363400,
,I/[SystemUI]LGPowerUI( 1472): onReceive = com.lge.android.intent.action.BATTERYEX
,I/[SystemUI]LGPowerUI( 1472): On Skip Timer : true
,D/WifiController( 1029): battery changed pluggedType: 2
,D/LEDHandler( 1974): ACTION_BATTERY_CHANGED : plugged type=2
,D/LEDHandler( 1974): Battery Level Remaining: 100%
,D/LEDHandler( 1974): Battery Temp: 282, mChargingStatus=5, mChargingStop=false
,D/KeyguardUpdateMonitor( 1472): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 282
,I/[SystemUI]LGPowerUI( 1472): onReceive = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]BatterySaverHandler( 1472): onReceive = android.intent.action.BATTERY_CHANGED
,D/LGDMClient( 4031): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4031): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 637957350385; DSPS: 21045899; Offset : -4327371712,
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 657959269023; DSPS: 21701322; Offset : -4327375863
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 677961188703; DSPS: 22356745; Offset : -4327378530
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 697963106664; DSPS: 23012167; Offset : -4327352738
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 717965077229; DSPS: 23667592; Offset : -4327365868
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
,I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 737967156336; DSPS: 24323020; Offset : -4327361825
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 757969136016; DSPS: 24978445; Offset : -4327366075
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 777971392154; DSPS: 25633879; Offset : -4327368081
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
,I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 797973554647; DSPS: 26289310; Offset : -4327372232
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 817975473285; DSPS: 26944733; Offset : -4327376280
,D/PowerManagerServiceEx( 1029): acquireWakeLockInternal: lock=307177574, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1029
,I/ActivityManager( 1029): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.DailyHygiene: pid=8553 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager( 1029): RTC_WAKEUP set : Alarm{a371654 type 0 when 1454412943660 com.android.vending} when 1454412943660
,D/[Concierge]Service( 2574): onStartCommand(). Type : 9
,I/art     (  355): Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 437us total 52.180ms
,I/art     (  355): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 359us total 36.037ms
,I/art     (  355): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 361us total 26.028ms
,D/PowerManagerServiceEx( 1029): releaseWakeLockInternal: lock=307177574 [*alarm*], flags=0x0
,D/Finsky  ( 8553): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/LgDataFeature( 8553): LgDataFeature() Constructor: none
D/LgDataFeature( 8553): LgDataFeature() Constructor Done, null
,D/Finsky  ( 8553): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/ActivityManager( 1029): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=8612 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/Settings( 8553): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 8553): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 8553): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/DownloadManager( 3356): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3356): created cursor android.database.sqlite.SQLiteCursor@e93c520 on behalf of 8553
,D/Finsky  ( 8553): [1] GmsCoreHelper.cleanupNlp: result=false type=4
V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 8553): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 8553): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 8553): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/GLSUser ( 2128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 8553): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 1029): Explicit concurrent mark sweep GC freed 39780(1834KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 2.032ms total 143.817ms
,V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 8612): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 8612): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/GLSUser ( 2128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/MultiDex( 8612): VM with version 2.1.0 has multidex support
I/MultiDex( 8612): install
I/MultiDex( 8612): VM has multidex support, MultiDex support library is disabled.
,W/Finsky  ( 8553): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
V/JNIHelp ( 8612): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 8612): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 8612): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@326b6777: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8612): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 2128): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 2128): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 2340): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 837976968121; DSPS: 27600142; Offset : -4327375738
,I/ActivityManager( 1029): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=8655 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
D/LocationInitializer( 2340): Restart initialization of location
,W/ResourcesManager( 8655): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 8655): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/art     ( 2128): Explicit concurrent mark sweep GC freed 27450(1611KB) AllocSpace objects, 11(1584KB) LOS objects, 50% free, 30MB/62MB, paused 1.562ms total 28.517ms
,I/MultiDex( 8655): VM with version 2.1.0 has multidex support
I/MultiDex( 8655): install
I/MultiDex( 8655): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 8655): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 8655): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 8655): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@326b6777: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8655): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 8655): callingUid 10005, callindPid: 8655
V/Finsky  ( 8553): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,E/MDM     ( 1831): [82] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/GCM     ( 2128): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 2128): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GmsCoreStatsServiceLauncher( 2340): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
V/SIM_STK ( 1029): Menu title from STK is T-Mobile
E/MDM     ( 1831): [85] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 2340): Restart initialization of location
V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 8553): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
D/Finsky  ( 8553): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 8553): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 8553): [1] DailyHygiene.reschedule: Scheduling new run in 27 minutes (failures=2)
I/ActivityManager( 1029): Killing 8029:com.lge.settings.easy/1000 (adj 15): empty #17
D/DeviceConnectionService( 1831): client connected with version: 7571000
,W/libprocessgroup( 1029): failed to open /acct/uid_1000/pid_8029/cgroup.procs: No such file or directory
,I/ActivityManager( 1029): Killing 8097:com.android.bluetooth/1002 (adj 15): empty #17
,D/LGBluetoothUserBindClient( 7942): [BTUI] onServiceDisconnected
,W/libprocessgroup( 1029): failed to open /acct/uid_1002/pid_8097/cgroup.procs: No such file or directory
,W/ActivityManager( 1029): Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
I/ActivityManager( 1029): Killing 8063:com.lge.sync/1000 (adj 15): empty #17
,W/libprocessgroup( 1029): failed to open /acct/uid_1000/pid_8063/cgroup.procs: No such file or directory
,I/ActivityManager( 1029): Start proc com.android.bluetooth for service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer: pid=8702 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,W/ResourcesManager( 8702): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager( 8702): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 8702): Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
,W/ResourcesManager( 8702): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/BluetoothAdapterApp( 8702): Loading JNI Library
,D/BluetoothAdapterApp( 8702): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@15a0f990 Instance Count = 1
,D/BluetoothAdapterApp( 8702): onCreate
D/ProfileConfigQcom( 8702): [BTUI] HeadsetService is supported
D/ProfileConfigQcom( 8702): Adding HeadsetService
D/ProfileConfigQcom( 8702): [BTUI] A2dpService is supported
D/ProfileConfigQcom( 8702): Adding A2dpService
D/ProfileConfigQcom( 8702): [BTUI] HidService is supported
D/ProfileConfigQcom( 8702): Adding HidService
,D/ProfileConfigQcom( 8702): [BTUI] HealthService is supported
D/ProfileConfigQcom( 8702): Adding HealthService
D/LGBluetoothFeatureConfig( 8702): isSupportPan() :  mTargetOp=OPEN
D/ProfileConfigQcom( 8702): [BTUI] PanService is supported
D/ProfileConfigQcom( 8702): Adding PanService
D/ProfileConfigQcom( 8702): [BTUI] GattService is supported
D/ProfileConfigQcom( 8702): Adding GattService
D/ProfileConfigQcom( 8702): [BTUI] BluetoothMapService is supported
D/ProfileConfigQcom( 8702): Adding BluetoothMapService
D/ProfileConfigQcom( 8702): [BTUI] HeadsetClientService is NOT supported
I/ActivityManager( 1029): Killing 7942:com.android.settings/1000 (adj 15): empty #17
W/libprocessgroup( 1029): failed to open /acct/uid_1000/pid_7942/cgroup.procs: No such file or directory
,D/PowerManagerServiceEx( 1029): acquireWakeLockInternal: lock=307177574, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1029
,V/AlarmManager( 1029): RTC_WAKEUP set : Alarm{3bf323f1 type 0 when 1454413076172 com.android.vending} when 1454413076172
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
D/[Concierge]Service( 2574): onStartCommand(). Type : 9
D/PowerManagerServiceEx( 1029): releaseWakeLockInternal: lock=307177574 [*alarm*], flags=0x0
,V/SIM_STK ( 1029): Menu title from STK is T-Mobile
,V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2128): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 8553): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 8553): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 8553): [1] 5.onFinished: Scheduling replication attempt 1.
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 857979136655; DSPS: 28255573; Offset : -4327375228
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 877981628054; DSPS: 28911014; Offset : -4327355517
,V/AlarmManager( 1029): RTC_WAKEUP set : Alarm{3d6e8ec8 type 0 when 1454413100404 com.android.vending} when 1454413100404
,V/SIM_STK ( 1029): Menu title from STK is T-Mobile
,V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 8553): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 8553): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 8553): [1] 5.onFinished: Scheduling replication attempt 2.
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 897983608202; DSPS: 29566439; Offset : -4327359064
,V/AlarmManager( 1029): RTC_WAKEUP set : Alarm{10002d5b type 0 when 1454413125466 com.android.vending} when 1454413125466
,V/SIM_STK ( 1029): Menu title from STK is T-Mobile
,V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 8553): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 8553): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 8553): [1] 5.onFinished: Scheduling replication attempt 3.
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
,I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 917985587986; DSPS: 30221864; Offset : -4327362897
,D/PowerManagerServiceEx( 1029): acquireWakeLockInternal: lock=307177574, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1029
,V/AlarmManager( 1029): RTC_WAKEUP set : Alarm{362d6c1a type 0 when 1454413155880 com.android.vending} when 1454413155880
,D/[Concierge]Service( 2574): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1029): releaseWakeLockInternal: lock=307177574 [*alarm*], flags=0x0
,V/SIM_STK ( 1029): Menu title from STK is T-Mobile
,V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 8553): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 8553): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 8553): [1] 5.onFinished: Scheduling replication attempt 4.
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 937987666624; DSPS: 30877292; Offset : -4327359610
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 957989743440; DSPS: 31532720; Offset : -4327358016
,V/AlarmManager( 1029): RTC_WAKEUP set : Alarm{3cc34f35 type 0 when 1454413176583 com.android.vending} when 1454413176583
,V/SIM_STK ( 1029): Menu title from STK is T-Mobile
,V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2128): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 8553): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 8553): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 8553): [1] 5.onFinished: Scheduling replication attempt 5.
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 977992431089; DSPS: 32188168; Offset : -4327355992
,D/PowerManagerServiceEx( 1029): acquireWakeLockInternal: lock=307177574, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1029
,V/AlarmManager( 1029): RTC_WAKEUP set : Alarm{a80299c type 0 when 1454413209973 com.android.vending} when 1454413209973
,D/[Concierge]Service( 2574): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1029): releaseWakeLockInternal: lock=307177574 [*alarm*], flags=0x0
,V/SIM_STK ( 1029): Menu title from STK is T-Mobile
,V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 8553): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 8553): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 8553): [1] 5.onFinished: Giving up after 6 failures.
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 997994521706; DSPS: 32843597; Offset : -4327370905
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1017996343573; DSPS: 33499017; Offset : -4327380197
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
,I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1037998511690; DSPS: 34154448; Offset : -4327378621
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1058001317464; DSPS: 34809900; Offset : -4327380437
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1078003341936; DSPS: 35465326; Offset : -4327370437
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
,I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1098005377865; DSPS: 36120753; Offset : -4327379161
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1118007113483; DSPS: 36776170; Offset : -4327382992
,V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 1029): Explicit concurrent mark sweep GC freed 24987(1021KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 2.508ms total 173.122ms
,V/NotificationService( 1029): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1029): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1029): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1029): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1029): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
,D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1412): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1412): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1412): updateNotificationData: count=3
,W/GLSActivity( 2128): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2128): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2128): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2128): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2128): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2128): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2128): 	at android.os.Binder.execTransact(Binder.java:446)
E/PlayEventLogger( 8553): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 8553): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 8553): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 8553): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 8553): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 8553): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 8553): 	at android.os.Binder.execTransact(Binder.java:446)
D/QuickStatusbarLayout( 1412): Notification difference=198
,D/QuickStatusbarLayout( 1412): child = android.widget.LinearLayout{320ab302 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/System  ( 8553): Ignoring header User-Agent because its value was null.
D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1029): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1138008797329; DSPS: 37431585; Offset : -4327377275
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1158010723051; DSPS: 38087008; Offset : -4327374316
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1178012583773; DSPS: 38742429; Offset : -4327375349
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1198014429077; DSPS: 39397849; Offset : -4327361073
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
,I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
I/[SystemUI]DateView( 1472): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1218016505892; DSPS: 40053277; Offset : -4327359479
,I/UsageStatsService( 1029): User[0] Flushing usage stats to disk
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1238018304739; DSPS: 40708696; Offset : -4327361196
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1258021156086; DSPS: 41364150; Offset : -4327378397
,I/[SystemUI]TimeTickManager( 1472): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1472): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1472): called onTimeUpdated()
,I/[SystemUI]Clock( 1472): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
,I/[SystemUI]DateView( 1472): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1472): handleTimeUpdate
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1278023258682; DSPS: 42019579; Offset : -4327381436
,D/PowerManagerServiceEx( 1029): acquireWakeLockInternal: lock=307177574, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1029
,I/DigitalAppWidgetProvider( 8438): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,D/[Concierge]Service( 2574): onStartCommand(). Type : 9
,V/DigitalAppWidgetProvider( 8438): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@46a5aaf
,D/PowerManagerServiceEx( 1029): releaseWakeLockInternal: lock=307177574 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1298025322008; DSPS: 42675006; Offset : -4327362657
,TIME-OUT KILL (timeout was 1200000ms),D/sensors_hal_Time( 1029): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1029): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1029): tsOffsetIs: Apps: 1318027442677; DSPS: 43330436; Offset : -4327378453
D/AndroidRuntime( 8855): 
D/AndroidRuntime( 8855): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8855): CheckJNI is OFF
D/AndroidRuntime( 8855): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1029): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
I/ActivityManager( 1029): Killing 6215:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
W/PackageSettings( 1029): Skipping PackageSetting{3388f223 com.example.hello/10319} due to missing metadata
D/WifiService( 1029): Client connection lost with reason: 4
I/WindowState( 1029): WIN DEATH: Window{186b8f27 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher( 1029): Window went away: Window{186b8f27 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/ActivityManager( 1029):   Force finishing activity ActivityRecord{dca3ce0 u0 com.test.thalitest/.MainActivity t4}
E/GBMv2   (  341): DFP En is all cleared set to be enabled
W/ActivityManager( 1029): Spurious death for ProcessRecord{118d2493 6215:com.test.thalitest/u0a311}, curProc for 6215: null
I/ActivityManager( 1029): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
I/ActivityManager( 1029):   Force finishing activity ActivityRecord{dca3ce0 u0 com.test.thalitest/.MainActivity t4 f}
W/ActivityManager( 1029): Duplicate finish request for ActivityRecord{dca3ce0 u0 com.test.thalitest/.MainActivity t4 f}
D/SplitWindowPolicy( 1974): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
I/[LGHome]EVENT( 2087): [Launcher.java:5338:onStart()]onStart
D/SplitWindowPolicy( 1974): topRunningActivity=ActivityInfo{16f5b0a4 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[LGHome]EVENT( 2087): [Launcher.java:903:onResume()]onResume
D/SplitWindowPolicy( 1974): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1974): topRunningActivity=ActivityInfo{25465e0d co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[LGHome]EVENT( 2087): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 2087): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/KeyguardModel( 1472): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/InputReader( 1029): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1831): Ignoring removeGeofence because network location is disabled.
D/LIA_Service_RemotePackageHandler( 2046): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
D/LIA_MrGDBLogger_PackageInfoDetector( 3564): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
I/art     (  355): Background concurrent mark sweep GC freed 786(33KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 7.575ms total 26.272ms
D/PostponalbeReceiver( 7986): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
W/System.err( 4285): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 4285): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4285): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4285): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4285): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4285): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4285): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4285): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4285): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4285): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4285): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4285): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
V/SIM_STK ( 1029): Menu title from STK is T-Mobile
D/SplitUIManager( 1892): split_name #11 / not available #0
D/SplitUIService( 1892): removed split : 
I/ActivityManager( 1029): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=8887 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
I/[LGHome]GBoardWebView( 2087): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
D/ActionManagerService( 1935): notifyUserLog: 1000003
D/LIA_Informant_ActionManagerMessageHandler( 3564): handleMessage: what(1000) actionID(0x1000003)
I/[LGHome]LGActivityUtil( 2087): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/art     ( 4328): Explicit concurrent mark sweep GC freed 63575(3MB) AllocSpace objects, 14(309KB) LOS objects, 34% free, 30MB/46MB, paused 598us total 165.980ms
I/[SystemUI]QSlideListController( 1472): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]EVENT( 2087): [Launcher.java:1056:onResume()]onResume end
I/[LGHome]EVENT( 2087): [Launcher.java:1114:onPause()]onPause
I/art     ( 1029): Explicit concurrent mark sweep GC freed 11920(937KB) AllocSpace objects, 7(240KB) LOS objects, 33% free, 44MB/66MB, paused 2.992ms total 182.508ms
I/art     ( 1029): WaitForGcToComplete blocked for 140.151ms for cause Explicit
I/[LGHome]GBoardWebView( 2087): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
D/ActionManagerService( 1935): notifyUserLog: 1000004
D/LIA_Informant_ActionManagerMessageHandler( 3564): handleMessage: what(1000) actionID(0x1000004)
D/AppUp4:PreloadHelper( 8173): added Exclude : com.test.thalitest
V/BoardContentProvider( 3564): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1472): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1472): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
D/SplitUIManager( 1892): split_name #11 / not available #0
I/SplitUIService( 1892): split app #11
I/ActivityManager( 1029): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=8907 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/GBoardWebViewUtils( 2087): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2087): , create_time: 1430558575574
I/GBoardWebViewUtils( 2087): , expire_time: 0
I/GBoardWebViewUtils( 2087): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2087): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2087): , display: false
I/GBoardWebViewUtils( 2087): , animation: false }
I/GBoardWebViewUtils( 2087): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2087): , create_time: 1430558575600
I/GBoardWebViewUtils( 2087): , expire_time: 0
I/GBoardWebViewUtils( 2087): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2087): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2087): , display: false
I/GBoardWebViewUtils( 2087): , animation: false }
I/GBoardWebViewUtils( 2087): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1453982949437
I/GBoardWebViewUtils( 2087): , create_time: 1453982950152
I/GBoardWebViewUtils( 2087): , expire_time: 0
I/GBoardWebViewUtils( 2087): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide.html?id=guide_1111111111116_1453982949437&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2087): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2087): , display: false
I/GBoardWebViewUtils( 2087): , animation: false }
I/LockScreenSettings( 8887): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
I/SystemUI[Framework]( 1029): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1029): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1029): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1029): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1029): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@eed5435,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1029): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/WallpaperManager( 2087): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
D/administrator( 1029): Handling package changes for user 0
I/[LGHome]EVENT( 2087): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]GBoardWebView( 2087): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
D/KeyguardModel( 1472): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1472): createShortcutInfo...
D/KeyguardModel( 1472): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1472): createShortcutInfo...
W/ResourcesManager( 1472): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1472): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1472): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1472): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1472): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1472): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1472): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1472): createShortcutInfo...
W/ResourcesManager( 8907): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8907): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 8907): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 8907): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 8907): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 1472): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1472): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1472): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1472): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1472): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1472): createShortcutInfo...
W/ResourcesManager( 1472): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1472): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1472): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1472): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1472): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1472): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1472): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1472): createShortcutInfo...
D/KeyguardModel( 1472): handleShortcutListChanged...
D/KeyguardModel( 1472): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1472): createShortcutInfo...
D/KeyguardModel( 1472): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1472): createShortcutInfo...
W/ResourceType( 1472): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1472): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1472): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1472): createShortcutInfo...
W/ResourceType( 1472): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1472): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1472): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1472): createShortcutInfo...
W/ResourceType( 1472): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1472): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1472): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1472): createShortcutInfo...
I/ActivityManager( 1029): Killing 8215:com.lge.email/u0a23 (adj 15): empty #17
V/SIM_STK ( 1029): Menu title from STK is T-Mobile
I/NotificationService( 1029): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1029): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1029): Receieved: android.intent.action.PACKAGE_REMOVED
D/KeyguardModel( 1472): handleShortcutListChanged...
W/libprocessgroup( 1029): failed to open /acct/uid_10023/pid_8215/cgroup.procs: No such file or directory
I/art     ( 1029): Explicit concurrent mark sweep GC freed 6955(366KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 1.506ms total 178.203ms
I/[LGHome]EVENT( 2087): [Launcher.java:5349:onStop()]onStop
D/PhoneStatusBar( 1472): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
I/[SystemUI]NavigationThemeResource( 1472): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1472):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1472): , Keyguard show=false, IME shown=false, Panel expanded=false
D/TaskPersister( 1029): removeObsoleteFile: deleting file=4_task.xml
I/SystemConfig( 8907): BUILD Country: EU
I/SystemConfig( 8907): BUILD Operator: OPEN
I/[LGHome]Launcher.Model( 2087): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2087): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2087): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2087): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2087): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2087): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/Timeline( 1029): Timeline: Activity_windows_visible id: ActivityRecord{1d5ba05e u0 com.lge.launcher2/.Launcher t3} time:1320316
I/[LGHome]Launcher.Model( 2087): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2087): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2087): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2087): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/ActivityManager( 1029): Killing 8125:com.lge.formmanager/u0a26 (adj 15): empty #17
I/[LGHome]EVENT( 2087): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 2087): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2087): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[Concierge]WidgetView( 2087): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
D/AndroidRuntime( 8855): Shutting down VM
W/ResourcesManager( 1029): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourceType( 1029): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
D/[Concierge]Service( 2574): onStartCommand(). Type : 8
D/[Concierge]Service( 2574): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
W/libprocessgroup( 1029): failed to open /acct/uid_10026/pid_8125/cgroup.procs: No such file or directory
D/[Concierge]WidgetView( 2087): change position of spinner
D/[Concierge]Service( 2574): Update widget ID : 11
D/[Concierge]Service( 2574): onStartCommand(). Type : 0
I/[Concierge]WidgetView( 2087): initWebView(). Time : 1454413543413
I/SystemConfig( 8907): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 8907): existFile = false
I/SystemConfig( 8907): canReadFile = false
I/SystemConfig( 8907): systemFeature RCS result false
D/SystemConfig( 8907): refreshRcsSupport() :false
D/VoicemailCleanupService( 2189): Cleaning up data for package: com.test.thalitest
I/ActivityManager( 1029): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8931 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/[Concierge]WebView( 2087): Return exist ConciergeWebView. Reuse : 228945730
D/[Concierge]WidgetView( 2087): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2087): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
I/[LgeWidgetLib]ExtViewHost( 2087): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@257f8fb0
I/[LGHome]EVENT( 2087): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2087): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2087): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2087): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/[Concierge]WidgetView( 2087): isWidgetUpdateSkippable ? true
I/[LGHome]EVENT( 2087): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
D/[Concierge]WidgetBroadcastReceiver( 2087): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
W/[Concierge]WidgetView( 2087): Widget kill message received. Destory myself. My : 1454412250654, New one : 1454413543413
D/[Concierge]WidgetView( 2087): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2087): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/[LGHome]Launcher( 2087): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2087): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2087): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2087): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2087): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2087): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2087): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2087): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
W/ResourcesManager( 8931): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8931): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 8931): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 8931): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/[LgeWidgetLib]LgeAppWidgetHostView( 2087): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
E/[LgeWidgetLib]LgeAppWidgetHostView( 2087): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2087): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 2087): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/LGEmail ( 8931): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
I/Timeline( 2087): Timeline: Activity_idle id: android.os.BinderProxy@679315f time:1320579
D/LGEmail ( 8931): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
W/ResourceType( 8931): No package identifier when getting value for resource number 0x00000000
D/LgDataFeature( 8931): LgDataFeature() Constructor: none
D/LgDataFeature( 8931): LgDataFeature() Constructor Done, null
I/PackageChangeReceiver( 8931): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)

```
