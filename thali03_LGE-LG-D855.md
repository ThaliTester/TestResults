#### Test 575312431745da8_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
I/MusicWidget( 2694): mDelayedStopHandler : unbind
I/MusicBrowser( 2179): [MediaPlaybackService.java:2869:onUnbind()] oooooo 
I/MusicBrowser( 2179): [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2179): [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2179): [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2179): [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2179): [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2179): [MediaPlaybackService.java:2046:onDestroy()] oooooo 
I/MusicBrowser( 2179): [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
I/MediaFocusControl( 1025):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@38ed8fd8com.lge.music.MediaPlaybackService$5@380a3f31
D/MusicBrowser( 2179): [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2179): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2179): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2179): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2179): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@2f58f766
I/MusicBrowser( 2179): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2179): [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2179): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2179): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2179): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2179): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2179): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2179): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2179): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2179): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2179): [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2179): [MediaPlaybackService.java:6704:release()] oooooo 
I/MusicBrowser( 2179): [MediaPlaybackService.java:6665:stop()] oooooo 
V/MediaPlayer[Native]( 2179): reset
V/MediaPlayer[Native]( 2179): setListener
V/MediaPlayer[Native]( 2179): disconnect
V/MediaPlayer[Native]( 2179): destructor
V/AudioFlinger(  321): releasing 13 from 2179 for -1
V/AudioFlinger(  321):  decremented refcount to 0
V/AudioFlinger(  321): purging stale effects
V/MediaPlayer[Native]( 2179): disconnect
D/MusicBrowser( 2179): [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
I/SmartShareClient( 2179): [SmartShareManagerClient] smartshare client supported version code: 305000
I/SmartShareClient( 2179): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2179): [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
I/MusicBrowser( 2179): [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2179): [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2179): [SmartShareManagerClient] unregisterListener: 209978902
W/SmartShareClient( 2179): [SmartShareManagerClient] unregisterListener invalid listener: 209978902
I/SmartShareClient( 2179): [SmartShareManagerClient] terminate service: 2179/MediaPlaybackService/629358780
E/HomeCloudIF( 2179): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2179): [SmartShareManagerClient] unbindService context:android.app.Application@19157b97
V/CloudHub( 2179): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
V/CloudHub( 2179): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2179): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
D/MusicBrowser( 2179): [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
--------- beginning of system
I/ActivityManager( 1025): Killing 5519:com.lge.appbox.client/u0a11 (adj 15): empty #17
I/CloudHub( 2179): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29989
W/libprocessgroup( 1025): failed to open /acct/uid_10011/pid_5519/cgroup.procs: No such file or directory
V/AlarmManager( 1025): RTC_WAKEUP set : Alarm{1d882bec type 0 when 1454593064651 com.android.vending} when 1454593064651
W/ContextImpl( 4235): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
V/SIM_STK ( 1025): Menu title from STK is T-Mobile
V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2057): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2057): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2057): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2057): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 1025): Explicit concurrent mark sweep GC freed 22008(989KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 3.133ms total 164.173ms
D/Finsky  ( 4891): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 4891): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4891): [1] 5.onFinished: Scheduling replication attempt 1.
,D/AndroidRuntime( 6020): 
D/AndroidRuntime( 6020): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6020): CheckJNI is OFF
D/AndroidRuntime( 6020): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1025): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1928): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1025): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1025): setTaskToReturnTo : TaskRecord{373624ee #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1025): setTaskToReturnTo : TaskRecord{373624ee #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1025): AppWindowTokenEx init.. 
E/GBMv2   (  343): DFP En is all cleared set to be enabled
I/ActivityManager( 1025): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6035 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6020): Shutting down VM
V/ActivityManager( 1025): Display changed displayId=0
D/DSDPConnection( 1839): Display #0 changed.
D/SplitWindowPolicy( 1928): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1928): topRunningActivity=ActivityInfo{3ec21de3 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1928): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1928): topRunningActivity=ActivityInfo{1e5413e0 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/sensors_hal_Time( 1025): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1025): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1025): tsOffsetIs: Apps: 107613967565; DSPS: 3667188; Offset : -4313856717
D/ContextHelper( 6035): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/WebViewFactory( 6035): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
I/LibraryLoader( 6035): Loading: webviewchromium
I/LibraryLoader( 6035): Time to load native libraries: 6 ms (timestamps 7734-7740)
,I/LibraryLoader( 6035): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6035): Binding Chromium to main looper Looper (main, tid 1) {258340bc}
I/LibraryLoader( 6035): Expected native library version number "",actual native library version number ""
I/chromium( 6035): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6035): Initializing chromium process, renderers=0
W/art     ( 6035): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6035): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
V/AudioPolicyService(  321): registerClient() client 0xb101ede0, uid 10311
,W/chromium( 6035): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
D/BluetoothManagerService( 1025): Message: 20
D/BluetoothManagerService( 1025): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2ddea08:true
I/chromium( 6035): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 6035): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
D/BluetoothAdapter( 6035): 67373125: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 6035): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6035): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6035): Build Date: 12/12/14 금
I/Adreno-EGL( 6035): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6035): Remote Branch: 
I/Adreno-EGL( 6035): Local Patches: 
I/Adreno-EGL( 6035): Reconstruct Branch: 
W/chromium( 6035): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 6035): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     ( 6035): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6035): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6035): CordovaWebView is running on device made by: LGE
,W/art     ( 6035): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6035): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6035): Render dirty regions requested: true
I/OpenGLRenderer( 6035): Initialized EGL, version 1.4
D/OpenGLRenderer( 6035): Enabling debug mode 0
,D/Atlas   ( 6035): Validating map...
D/SplitWindow( 1025): check instance of lgWin Window{31cf1802 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/LgDataFeature( 6035): LgDataFeature() Constructor: none
D/LgDataFeature( 6035): LgDataFeature() Constructor Done, null
,I/SystemUI[Framework]( 1025): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
,W/PhoneWindowManagerEx( 1025): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1025): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1025): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1025): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@11b99c28,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1025): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/PhoneStatusBar( 1465): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1465): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1465):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1465): , Keyguard show=false, IME shown=false, Panel expanded=false
I/ActivityManager( 1025): Displayed com.test.thalitest/.MainActivity: +532ms (total +604ms)
I/Timeline( 1025): Timeline: Activity_windows_visible id: ActivityRecord{3f626d8f u0 com.test.thalitest/.MainActivity t4} time:108108
,I/Timeline( 6035): Timeline: Activity_idle id: android.os.BinderProxy@10908cb5 time:108114
I/chromium( 6035): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6035): 
,D/JsMessageQueue( 6035): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium( 6035): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 6035): 
,D/jxcore_app_log( 6035): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435007616
,I/chromium( 6035): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/GBMv2   (  343): DFP En is all cleared set to be enabled
E/GBMv2   (  343): Set value is all cleared set the max
I/GBMv2   (  343): DFP Enabled. Ignore VFP set
,W/jxcore-log( 6035): Initializing JXcore engine
W/jxcore-log( 6035): JXcore engine is ready
,W/Thread-688( 6086): type=1400 audit(0.0:148): avc: denied { ioctl } for path="socket:[8387]" dev="sockfs" ino=8387 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/Thread-688( 6086): type=1400 audit(0.0:149): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-688( 6086): type=1400 audit(0.0:150): avc: denied { ioctl } for path="socket:[8602]" dev="sockfs" ino=8602 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-688( 6086): type=1400 audit(0.0:151): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/Thread-688( 6086): type=1400 audit(0.0:152): avc: denied { ioctl } for path="socket:[30415]" dev="sockfs" ino=30415 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
W/jxcore-log( 6035): Starting JXcore engine
,W/jxcore-log( 6035): Platform android
W/jxcore-log( 6035): 
W/jxcore-log( 6035): Process ARCH arm
W/jxcore-log( 6035): 
,I/jxcore-log( 6035): JXcore Cordova bridge is ready!
I/jxcore-log( 6035): 
,W/jxcore-log( 6035): JXcore engine is started
,I/jxcore-log( 6035): Toggling radios to true
I/jxcore-log( 6035): 
,D/BluetoothManagerService( 1025): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1025): enable():  mBluetooth =null mBinding = false
,D/LocationManagerService( 1025): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1025): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1025): JNI:system_update. Event-4
D/BluetoothManagerService( 1025): Message: 1
D/BluetoothManagerService( 1025): MESSAGE_ENABLE: mBluetooth = null
D/WifiService( 1025): New client listening to asynchronous messages
,I/ActivityManager( 1025): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=6089 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
D/WifiServiceImplEx( 1025): setWifiEnabled: true pid=6035, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1025): setWifiEnabled: true pid=6035, uid=10311
E/WifiService( 1025): Invoking mWifiStateMachine.setWifiEnabled
,D/LocationManagerService( 1025): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1025): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1025): JNI:system_update. Event-4
E/WifiStateMachine( 1025):  InitialState CMD_START_SUPPLICANT 0 0
I/LGFTMITEM( 1025): [GET_FTM][id=6], offset=12288
D/WifiServiceImplEx( 1025): disconnect pid=6035, uid=10311, packageName=com.test.thalitest
D/WifiServiceImplEx( 1025): reconnect pid=6035, uid=10311, packageName=com.test.thalitest
I/jxcore-log( 6035): Radios toggled
I/jxcore-log( 6035): 
I/jxcore-log( 6035): My device name is: LGE-LG-D855
I/jxcore-log( 6035): 
E/WifiUtil( 1025): wfc_util_ffile_check_copy(): pid[1025] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
,E/WifiUtil( 1025): wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
,E/WifiUtil( 1025): wfc_util_ffile_check_copy(): pid[1025] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
E/WifiUtil( 1025): wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
I/WifiUtil( 1025): Intf0MacAddress=C49A027B60AC
E/WifiHW  ( 1025): unknown target_country: EU , set to default
E/WifiHW  ( 1025): [wifi_ensure_config_files] default country1 = GB
E/WifiHW  ( 1025): [wifi_ensure_config_files] default country2 = GB
I/WifiUtil( 1025): gEnableBmps=1
W/ResourcesManager( 6089): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,W/ResourcesManager( 6089): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6089): Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 6089): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/BluetoothAdapterApp( 6089): Loading JNI Library
,D/BluetoothAdapterApp( 6089): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@10d1fb90 Instance Count = 1
,D/SoftapController(  316): Softap fwReload - Ok
,D/CommandListener(  316): Setting iface cfg
D/CommandListener(  316): Trying to bring down wlan0
D/libc-netbsd(  316): default dns: query_ipv6=0, query_ipv4=0
D/Tethering( 1025): sendTetherStateChangedBroadcast 1, 0, 0
D/CommandListener(  316): Clearing all IP addresses on wlan0
D/DSQN    ( 1025): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/Tethering( 1025): InitialState.processMessage what=4
E/WifiHW  ( 1025): Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,E/WifiStateMachine( 1025): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1025): useWiFiOffloading() : false
E/WifiStateMachine( 1025): CONFIG_LGE_WLAN_PATH : true
I/ActivityManager( 1025): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=6115 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,D/Tethering( 1025): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiMonitor( 1025): startMonitoring(wlan0) with mConnected = false
D/WifiMonitor( 1025): connecting to supplicant
D/BluetoothAdapterApp( 6089): onCreate
W/wpa_supplicant( 6116): type=1400 audit(0.0:153): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/wpa_supplicant( 6116): type=1400 audit(0.0:154): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/WifiServerServiceExt( 1025): WIFI_STATE_CHANGED_ACTION [2]
V/WfdStateTracker( 1928): WfdStateTracker handleDirectStateChangedEvent: 1
,D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
I/wpa_supplicant( 6116): Successfully initialized wpa_supplicant
,D/ProfileConfigQcom( 6089): [BTUI] HeadsetService is supported
D/ProfileConfigQcom( 6089): Adding HeadsetService
D/ProfileConfigQcom( 6089): [BTUI] A2dpService is supported
D/ProfileConfigQcom( 6089): Adding A2dpService
D/ProfileConfigQcom( 6089): [BTUI] HidService is supported
D/ProfileConfigQcom( 6089): Adding HidService
D/ProfileConfigQcom( 6089): [BTUI] HealthService is supported
D/ProfileConfigQcom( 6089): Adding HealthService
D/LGBluetoothFeatureConfig( 6089): isSupportPan() :  mTargetOp=OPEN
D/ProfileConfigQcom( 6089): [BTUI] PanService is supported
D/ProfileConfigQcom( 6089): Adding PanService
D/ProfileConfigQcom( 6089): [BTUI] GattService is supported
D/ProfileConfigQcom( 6089): Adding GattService
D/ProfileConfigQcom( 6089): [BTUI] BluetoothMapService is supported
D/ProfileConfigQcom( 6089): Adding BluetoothMapService
D/ProfileConfigQcom( 6089): [BTUI] HeadsetClientService is NOT supported
,I/wpa_supplicant( 6116): rfkill: Cannot open RFKILL control device
I/wpa_supplicant( 6116): [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,D/BluetoothManagerService( 1025): Message: 20
D/BluetoothManagerService( 1025): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@72dcbbd:true
D/BluetoothAdapterState( 6089): make
I/LGFMServiceAdapter( 6089): [FM] LGFMServiceAdapter : create
I/bluedroid-qcom( 6089): init
I/BluetoothAdapterState( 6089): Entering OffState
I/bte_conf( 6089): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
I/bte_conf( 6089): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 6089): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 6089): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
D/BTIF_CORE( 6089): [BTUI] lge_load_bluetooth_address
W/ResourcesManager( 6115): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6115): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
I/bluedroid-qcom( 6089): get_profile_interface socket
I/bluedroid-qcom( 6089): get_profile_interface map_client
I/GKI_LINUX( 6089): gki_task_entry task_id=1 [BTIF] starting
W/ResourcesManager( 6115): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6115): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 6115): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/BluetoothAdapterProperties( 6089): Address is:58:3F:54:73:64:C0
W/ResourcesManager( 6115): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
W/bdaddr_loader( 6148): type=1400 audit(0.0:155): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/bdaddr_loader( 6148): type=1400 audit(0.0:156): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/BluetoothManagerService( 1025): Bluetooth Adapter name changed to G3-1
D/BluetoothAdapterProperties( 6089): Name is: G3-1
D/BluetoothManagerService( 1025): Stored Bluetooth name: G3-1
D/BluetoothManagerService( 1025): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService( 1025): Message: 40
D/BluetoothManagerService( 1025): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
I/bluedroid-qcom( 6089): config_hci_snoop_log
D/BluetoothManagerService( 1025): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService( 1025): Broadcasting onBluetoothServiceUp() to 7 receivers.
D/lge_bdaddr_loader( 6148): [BTUI] bdaddr_loader ::: START
D/lge_bdaddr_loader( 6148): [BTUI] bluetooth_load_bdaddress
I/LGFTMITEM( 6148): [GET_FTM][id=8], offset=16384
D/lge_bdaddr_loader( 6148): [BTUI] bdaddr to set in property : 58:3F:54:73:64:C0
,E/lge_bdaddr_loader( 6148): [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:64:C0
D/lge_bdaddr_loader( 6148): [BTUI] bdaddr_loader ::: END
V/LGMDMManagerInternal( 6089): Create singleton instance
D/BluetoothAdapterState( 6089): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 6089): Setting state to 11
I/BluetoothAdapterState( 6089): Bluetooth adapter state changed: 10-> 11
,I/LGBluetoothServiceJni( 6089): classInitNative: succeeds
D/BluetoothManagerService( 1025): Message: 60
D/BluetoothManagerService( 1025): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService( 1025): Bluetooth State Change Intent: 10 -> 11
D/BluetoothBondStateMachine( 6089): make
I/[SystemUI]BluetoothHandler( 1465): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
D/LGBluetoothAPIService( 1928): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
I/BluetoothBondStateMachine( 6089): StableState(): Entering Off State
D/BluetoothAdapterService( 6089): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c26fccb
D/LGBluetoothServiceAdapter( 6089): [BTUI] check adapter is available - false.
D/BluetoothAdapterService( 6089): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c26fccb
D/LGBluetoothServiceAdapter( 6089): [BTUI] check adapter is available - true : set adapter available.
D/LGBluetoothSettingsDBObserver( 6089): [BTUI] register observer for LG device name DB
E/BluetoothAdapterService( 6089): File transfer profiles supported!!
,E/BluetoothAdapterService( 6089): File transfer profiles supported!!
D/BluetoothHeadset( 1839): Proxy object connected
D/HeadsetService( 6089): Received start request. Starting profile...
D/BluetoothHeadset( 1839): Proxy object connected
I/LGBluetoothHeadsetServiceJni( 6089): classInitNative: succeeds
D/BluetoothHeadset( 1839): Proxy object connected
D/LGBluetoothHfpAdapter( 6089): Version 1.6
D/BluetoothHeadset( 1025): Proxy object connected
D/LGBluetoothFeatureConfig( 6089): isPrivacyLogsEnabled : true
I/BluetoothHeadsetServiceJni( 6089): classInitNative: succeeds
E/BluetoothAdapterService( 6089): File transfer profiles supported!!
D/HeadsetStateMachine( 6089): make
I/wpa_supplicant( 6116): rfkill: Cannot open RFKILL control device
E/BluetoothAdapterService( 6089): File transfer profiles supported!!
,E/BluetoothAdapterService( 6089): File transfer profiles supported!!
E/BluetoothAdapterService( 6089): File transfer profiles supported!!
E/BluetoothAdapterService( 6089): File transfer profiles supported!!
D/LgDataFeature( 6089): LgDataFeature() Constructor: none
D/LgDataFeature( 6089): LgDataFeature() Constructor Done, null
D/HeadsetStateMachine( 6089): max_hf_connections = 1
I/bluedroid-qcom( 6089): get_profile_interface handsfree
V/ToneGenerator( 6089): ToneGenerator constructor: streamType=8, volume=1.000000
V/AudioPolicyService(  321): registerClient() client 0xb101eec0, uid 1002
V/AudioPolicyManager(  321): getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  321): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  321): getOutput() returns output 2
V/AudioSystem( 6089): getOutputSamplingRate() no output descriptor for output 2 in gOutputs
V/AudioFlinger(  321): registerClient() client 0xb55815f8, pid 6089
V/AudioSystem(  321): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  321): ioConfigChanged() opening already existing output! 2
V/ToneGenerator( 6089): Create Track: 0xb4928a80
V/AudioTrack( 6089): set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
V/AudioTrack( 6089): set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
V/AudioPolicyManager(  321): getOutputForAttr() usage=3, content=4, tag= flags=00000000
V/AudioPolicyManager(  321): getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  321): AudioPolicyManagerEx: getOutputForDevice
V/AudioSystem( 1025): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1025): ioConfigChanged() opening already existing output! 2
V/AudioPolicyManagerEx(  321): getOutput() returns output 2
V/AudioSystem(  321): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem(  321): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 6089): getOutputSamplingRate() no output descriptor for output 2 in gOutputs
V/AudioSystem( 1465): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1465): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1839): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1839): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 3294): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 3294): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 2179): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 2179): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1025): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1025): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1465): ioConfigChanged() event 0, ioHandle 4
,V/AudioSystem( 1465): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1839): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1839): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 2179): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 2179): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 3294): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 3294): ioConfigChanged() opening already existing output! 4
I/AudioFlinger(  321): isAudioPlaybackHookOn() false
V/AudioSystem( 6089): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 6089): ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
V/AudioSystem( 6089): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 6089): ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
V/AudioPolicyManager(  321): getOutputForAttr() usage=3, content=4, tag= flags=00000000
V/AudioPolicyManager(  321): getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
V/AudioPolicyManagerEx(  321): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  321): getOutput() returns output 2
V/LGMDMManager( 6089): Create singleton instance
V/AudioSystem( 6089): getLatency() output 2, latency 50
V/AudioSystem( 6089): getFrameCount() output 2, frameCount 960
V/AudioTrack( 6089): createTrack_l() output 2 afLatency 50
V/AudioFlinger(  321): [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
V/AudioFlinger(  321): [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
V/AudioFlinger(  321): [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
V/AudioFlinger(  321): [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
V/AudioFlinger(  321): createTrack() lSessionId: 16
V/AudioTrack( 6089): AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
V/AudioFlinger(  321): acquiring 16 from 6089, for 6089
V/AudioFlinger(  321):  added new entry for 16
V/ToneGenerator( 6089): ToneGenerator INIT OK, time: 110989
D/BluetoothAdapterService( 6089): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c26fccb
D/HeadsetStateMachine( 6089): Enter Disconnected: -2, size: 0
D/HeadsetPhoneState( 6089): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 6089): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetStateMachine( 6089): [BTUI] change sampling rate to 8000 when device is disconnected
V/AudioFlinger(  321): setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6089
D/audio_hw_primary(  321): adev_set_parameters: enter: bt_samplerate=8000
V/voice   (  321): voice_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  321): voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  321): voice_extn_compress_voip_set_parameters: exit
V/voice   (  321): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  321): LGE_platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  321): platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  321): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  321): lge_platform_set_loopback_parameters: enter: 
V/audio_hw_primary(  321): adev_set_parameters: exit with code(0)
E/audio_a2dp_hw(  321): adev_set_parameters: ERROR: set param called even when stream out is null
V/ToneGenerator( 6089): ToneGenerator destructor
V/ToneGenerator( 6089): stopTone
V/ToneGenerator( 6089): Delete Track: 0xb4928a80
V/AudioTrack( 6089): ~AudioTrack, releasing session id from 6089 on behalf of 6089
V/AudioFlinger(  321): releasing 16 from 6089 for 6089
V/AudioFlinger(  321):  decremented refcount to 0
V/AudioFlinger(  321): purging stale effects
V/AudioPolicyService(  321): AudioCommandThread() adding release output 2
V/AudioPolicyService(  321): inserting command: 6 at index 0, num commands 0
V/AudioFlinger(  321): PlaybackThread::Track destructor
V/AudioFlinger(  321): removeClient_l() pid 6089, calling pid 321
V/AudioPolicyService(  321): AudioCommandThread() waking up
V/AudioPolicyService(  321): AudioCommandThread() processing release output 2
V/AudioPolicyManager(  321): releaseOutput() 2
V/AudioPolicyService(  321): AudioCommandThread() going to sleep
D/BluetoothAdapterService( 6089): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c26fccb
D/BluetoothA2dp( 1025): Proxy object connected
I/BluetoothAdapterState( 6089): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
D/A2dpService( 6089): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 6089): classInitNative: succeeds
V/Avrcp   ( 6089): make
D/Avrcp   ( 6089): [BTUI] Use Native AVRCP : init jni
I/bluedroid-qcom( 6089): get_profile_interface avrcp
W/Process ( 1025): Unable to open /proc/6153/status
V/AudioManager( 6089): registerRemoteController: size of Media player list: 0
E/AudioManager( 6089): No RCC entry present to update
E/RemoteController( 6089): Cannot set synchronization mode on an unregistered RemoteController
D/UsbSettingsReceiver( 6115): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6115): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6115): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6115): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6115): [AUTORUN] onReceive() : app userid = 0, current userid = 0
I/BluetoothAvrcpQcomServiceJni( 6089): classInitQcomNative: succeeds
D/LGBluetoothAvrcpQcomAdapter( 6089): [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
I/BluetoothAvrcpQcomServiceJni( 6089): initQcomNative: succeeds
D/LGBluetoothAvrcpQcomAdapter( 6089): [BTUI] [+] updateMediaPlayerInfo
D/UsbSettingsControl( 6115): [AUTORUN] getUsbConnected() : connected=true
,D/UsbSettingsReceiver( 6115): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6115): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6115): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6115): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6115): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 6115): [AUTORUN] setTetherStatus() : status=false
I/ActivityManager( 1025): Killing 5539:com.android.contacts/u0a19 (adj 15): empty #17
I/wpa_supplicant( 6116): [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,I/wpa_supplicant( 6116): p2p0: CTRL-EVENT-AVOID-FREQ ranges=
,I/wpa_supplicant( 6116): wlan0: CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine( 1025):  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
E/WifiStateMachine( 1025):  SupplicantStartingState CMD_START_DRIVER 0 0
E/WifiStateMachine( 1025):  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
D/WifiMonitor( 1025): Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
E/WifiStateMachine( 1025):  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
D/WifiMonitor( 1025): Dropping event because (p2p0) is stopped
D/WifiMonitor( 1025): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiStateMachine( 1025):  SupplicantStartingState CMD_DISCONNECT 0 0
E/WifiMonitor( 1025): WifiMonitor:wlan0 cnt=0 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine( 1025):  DefaultState CMD_DISCONNECT 0 0
E/WifiMonitor( 1025): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine( 1025):  SupplicantStartingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1025):  DefaultState CMD_RECONNECT 0 0
E/WifiStateMachine( 1025):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1025):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1025):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiMonitor( 1025): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine( 1025):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1025):  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
D/WifiNative-wlan0( 1025): doString: [DRIVER MACADDR]
D/WifiNative-wlan0( 1025):    returned Macaddr = c4:9a:02:7b:60:ac
D/WifiStateMachine( 1025): MAC Addr from driver = c4:9a:02:7b:60:ac
D/WifiOffDelayIfNotUsed( 1025): setPowerSaveActivated(false)
V/SIM_STK ( 1025): Menu title from STK is T-Mobile
V/SIM_STK ( 1025): Menu title from STK is T-Mobile
,W/libprocessgroup( 1025): failed to open /acct/uid_10019/pid_5539/cgroup.procs: No such file or directory
D/UsbSettingsReceiver( 6115): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6115): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6115): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6115): [AUTORUN] persist.sys.usb.config = ptp_only,adb
,D/UsbSettingsReceiver( 6115): [AUTORUN] onReceive() : app userid = 0, current userid = 0
W/Settings( 1025): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1025): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/WifiStateMachine( 1025): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1025): useWiFiOffloading() : false
E/WifiStateMachine( 1025): CONFIG_LGE_WLAN_PATH : true
D/WfdService( 1928): Waiting for WifiP2p enabling
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
,W/ActivityManager( 1025): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
D/WifiNative-wlan0( 1025): doBoolean: SET update_config 1
I/WifiServerServiceExt( 1025): WIFI_STATE_CHANGED_ACTION [3]
D/WifiNative-wlan0( 1025): SET update_config 1: returned true
D/WifiConfigStore( 1025): Loading config and enabling all networks 
D/UsbSettingsControl( 6115): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6115): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 6115): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6115): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6115): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/WifiNative-wlan0( 1025): doString: [LIST_NETWORKS]
D/UsbSettingsControl( 6115): [AUTORUN] setTetherStatus() : status=false
D/WifiNative-wlan0( 1025):    returned network id / ssid / bssid / flags 0	NG700	any	
I/WifiServerServiceExt( 1025): batteryPsActivateMsgHandler : state:0 event:3
D/LGBluetoothAvrcpQcomAdapter( 6089): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 6089): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6089): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 6089): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 6089): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 6089): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6089): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 6089): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6089): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 6089): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6089): [BTUI] [-] updateMediaPlayerInfo
I/BluetoothA2dpServiceJni( 6089): classInitNative
I/BluetoothA2dpServiceJni( 6089): classInitNative: succeeds
D/A2dpStateMachine( 6089): make
,I/bluedroid-qcom( 6089): get_profile_interface a2dp
I/GKI_LINUX( 6089): gki_task_entry task_id=2 [A2DP-MEDIA] starting
I/LGBluetoothA2dpServiceJni( 6089): classInitNative: succeeds
I/LGBluetoothA2dpAdapter( 6089): [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
D/BluetoothAdapterService( 6089): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c26fccb
D/A2dpStateMachine( 6089): Enter Disconnected: -2
I/BluetoothHidServiceJni( 6089): classInitNative: succeeds
D/HidService( 6089): Received start request. Starting profile...
I/bluedroid-qcom( 6089): get_profile_interface hidhost
D/BluetoothAdapterService( 6089): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c26fccb
I/BluetoothHealthServiceJni( 6089): classInitNative: succeeds
D/HealthService( 6089): Received start request. Starting profile...
E/WifiConfigStore( 1025): readNetworkVariablesFromSupplicantFile key=psk
I/bluedroid-qcom( 6089): get_profile_interface health
I/LGBluetoothHealthServiceJni( 6089): classInitNative: succeeds
D/BluetoothAdapterService( 6089): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c26fccb
,I/BluetoothPanServiceJni( 6089): classInitNative(L105): succeeds
E/WifiConfigStore( 1025): readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
E/WifiConfigStore( 1025): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
D/PanService( 6089): Received start request. Starting profile...
D/BluetoothPanServiceJni( 6089): initializeNative(L110): pan
I/bluedroid-qcom( 6089): get_profile_interface pan
,I/ActivityManager( 1025): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6164 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,D/WifiStateMachine( 1025): enableVerboseLogging : level 2
D/WifiNative-wlan0( 1025): doBoolean: SET device_name g3_global_com
D/WifiNative-wlan0( 1025): SET device_name g3_global_com: returned true
D/WifiNative-wlan0( 1025): doBoolean: SET manufacturer LGE
D/WifiNative-wlan0( 1025): SET manufacturer LGE: returned true
D/WifiNative-wlan0( 1025): doBoolean: SET model_name LG-D855
D/WifiNative-wlan0( 1025): SET model_name LG-D855: returned true
D/WifiNative-wlan0( 1025): doBoolean: SET model_number LG-D855
D/WifiNative-wlan0( 1025): SET model_number LG-D855: returned true
D/WifiNative-wlan0( 1025): doBoolean: SET serial_number LGD8553bed2d08
D/WifiNative-wlan0( 1025): SET serial_number LGD8553bed2d08: returned true
D/WifiNative-wlan0( 1025): doBoolean: SET config_methods physical_display virtual_push_button
D/WifiNative-wlan0( 1025): SET config_methods physical_display virtual_push_button: returned true
D/WifiNative-wlan0( 1025): doBoolean: SET device_type 10-0050F204-5
D/WifiNative-wlan0( 1025): SET device_type 10-0050F204-5: returned true
,I/LGBluetoothPanAdapter( 6089): [BTUI] getInstance : create [LGBluetoothPanAdapter]
D/BluetoothAdapterService( 6089): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c26fccb
D/WfdsService( 1928): Supplicant Connection state is changed : true
D/WfdsService( 1928): DefaultState - WIFI_SUPPLICANT_CONNECTED
D/WfdsService( 1928): Set the WFDS Monitor: true
I/BtGatt.JNI( 6089): classInitNative(L901): classInitNative: Success!
D/WfdsMonitor( 1928): WfdsMonitorThread create
D/WfdsMonitor( 1928): WFDS Monitor is created and started
D/WfdsService( 1928): WiFi: Supplicant connection re-established
D/WifiStateMachine( 1025): Setting OUI to DA-A1-19
D/WifiNative-wlan0( 1025): doBoolean: SCAN_INTERVAL 120
D/WifiNative-wlan0( 1025): SCAN_INTERVAL 120: returned true
D/WifiNative-HAL( 1025): Setting external_sim to 1
D/WifiNative-wlan0( 1025): doBoolean: SET external_sim 1
D/BtGatt.DebugUtils( 6089): handleDebugAction() action=null
D/WifiNative-wlan0( 1025): SET external_sim 1: returned true
I/WifiNative-HAL( 1025): startHal
E/wifi    ( 1025): getStaticLongField sWifiHalHandle 0x988bf8dc
E/WifiHAL ( 1025): Could not connect handle
D/wifi    ( 1025): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x701fee
I/WifiNative-HAL( 1025): Could not start hal
D/BtGatt.GattService( 6089): Received start request. Starting profile...
D/BtGatt.GattService( 6089): start()
D/WifiStateMachine( 1025): Setting OUI to DA-A1-19
I/bluedroid-qcom( 6089): get_profile_interface gatt
I/WifiNative-HAL( 1025): startHal
E/wifi    ( 1025): getStaticLongField sWifiHalHandle 0x988bf85c
E/WifiHAL ( 1025): Could not connect handle
D/wifi    ( 1025): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x701c7e
I/WifiNative-HAL( 1025): Could not start hal
D/WifiNative-wlan0( 1025): doBoolean: STA_AUTOCONNECT 1
D/BtGatt.AdvertiseManager( 6089): advertise manager created
E/CtrlSupplicant( 1928): Access OK "@android:wpa_wlan0"
D/WifiNative-wlan0( 1025): STA_AUTOCONNECT 1: returned true
D/WifiNative-wlan0( 1025): doBoolean: DRIVER BTCOEXSCAN-STOP
I/wpa_supplicant( 6116): wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
D/WifiNative-wlan0( 1025): DRIVER BTCOEXSCAN-STOP: returned true
D/WifiHS20( 1025): hidePasspointNotification off =false
E/CtrlSupplicant( 1928): Succeed to open control connection
E/CtrlSupplicant( 1928): Succeed to open monitor connection
D/WfdsMonitor( 1928): Supplicant connection established
D/WfdsService( 1928): Connected to the supplicant for wfds
I/StatusBar.NetworkController( 1465): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1465): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
D/BluetoothAdapterService( 6089): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c26fccb
D/BluetoothAdapterService( 6089): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c26fccb
I/LGBluetoothMapAdapter( 6089): [BTUI] getInstance : create [LGBluetoothMapAdapter]
V/BluetoothMapService( 6089): BluetoothMapBinder()
W/Settings( 1025): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1025): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1025): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiNative-wlan0( 1025): doBoolean: DRIVER RXFILTER-STOP
I/wpa_supplicant( 6116): wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
D/BluetoothMapService( 6089): Received start request. Starting profile...
D/BluetoothMapService( 6089): start()
D/WifiNative-wlan0( 1025): DRIVER RXFILTER-STOP: returned true
D/WifiNative-wlan0( 1025): doBoolean: DRIVER RXFILTER-REMOVE 3
I/wpa_supplicant( 6116): wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
D/WifiNative-wlan0( 1025): DRIVER RXFILTER-REMOVE 3: returned true
D/WifiNative-wlan0( 1025): doBoolean: DRIVER RXFILTER-START
I/wpa_supplicant( 6116): wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
D/WifiNative-wlan0( 1025): DRIVER RXFILTER-START: returned true
D/WifiNative-wlan0( 1025): doBoolean: DRIVER RXFILTER-STOP
I/wpa_supplicant( 6116): wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
D/WifiNative-wlan0( 1025): DRIVER RXFILTER-STOP: returned true
D/WifiNative-wlan0( 1025): doBoolean: DRIVER RXFILTER-REMOVE 2
I/wpa_supplicant( 6116): android_multicast_filter_startstop : multicast filter set
D/WifiNative-wlan0( 1025): DRIVER RXFILTER-REMOVE 2: returned true
D/WifiNative-wlan0( 1025): doBoolean: DRIVER RXFILTER-START
I/wpa_supplicant( 6116): wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
D/BluetoothMapEmailSettingsLoader( 6089): Found 0 applications
D/WifiNative-wlan0( 1025): DRIVER RXFILTER-START: returned true
D/BluetoothMapEmailAppObserver( 6089): createReceiver()
,E/WifiNative: ( 1025): [111,195,098 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
D/BluetoothMapEmailAppObserver( 6089): initObservers()
D/WifiNative-wlan0( 1025): doBoolean: RECONNECT
D/BluetoothMapEmailAppObserver( 6089): getEnabledAccountItems()
D/WifiNative-wlan0( 1025): RECONNECT: returned true
D/WifiNative-wlan0( 1025): doString: [STATUS]
D/WifiService( 1025): New client listening to asynchronous messages
D/WifiMonitor( 1025): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1025): WifiMonitor:wlan0 cnt=1 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiNative-wlan0( 1025):    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
D/WifiNative-wlan0( 1025): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 6116): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1025): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1025): doBoolean: SET ps 1
D/WifiNative-wlan0( 1025): SET ps 1: returned true
D/LGWifiP2pService( 1025): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService( 1025): SCAN_AVAILABLE : 3
D/RttService( 1025): SCAN_AVAILABLE : 3
D/WifiScanningService( 1025): DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL( 1025): startHal
E/wifi    ( 1025): getStaticLongField sWifiHalHandle 0x94d7099c
E/WifiHAL ( 1025): Could not connect handle
D/wifi    ( 1025): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x901bea
I/WifiNative-HAL( 1025): Could not start hal
D/CommandListener(  316): Setting iface cfg
D/CommandListener(  316): Trying to bring up p2p0
D/RttService( 1025): DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1025): startMonitoring(p2p0) with mConnected = true
E/WifiScanningService( 1025): could not start HAL
D/LGWifiP2pService( 1025): P2pEnablingState
D/LGWifiP2pService( 1025): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1025): P2p socket connection successful
D/LGWifiP2pService( 1025): P2pEnabledState
D/LGWifiP2pService( 1025): sending p2p connection changed broadcast
D/WifiNative-p2p0( 1025): doBoolean: SET persistent_reconnect 1
E/WifiStateMachine( 1025):  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
E/WifiStateMachine( 1025):  DisconnectedState CMD_START_DRIVER 0 0
V/WfdStateTracker( 1928): WfdStateTracker handleDirectStateChangedEvent: 2
D/WfdsService( 1928): WifiP2pState is changed : true
D/WfdsService( 1928): Receive the WFDS_ENABLE Method
D/WfdsService( 1928): Set the WFDS Monitor: true
D/WfdsService( 1928): Connected to the supplicant for wfds
D/WfdsJNI ( 1928): doCommand: WFDS_SET TRUE
I/wpa_supplicant( 6116): WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
D/WfdsJNI ( 1928): doCommand: WFDS_GET_MAC_ADDRESS
I/wpa_supplicant( 6116): WFDS: wfds_supplicant_wfds_cmd: cmd = GET_MAC_ADDRESS
D/WfdsJNI ( 1928): doCommand: IFNAME=wlan0 GET_CAPABILITY channels
D/WfdsService( 1928): WIFI_P2P_CONNECTION_CHANGED_ACTION
D/WfdsService( 1928): selectPreferredScanChannel [36]
D/WfdsService( 1928): STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7b:60:ac
D/BluetoothAdapterService( 6089): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c26fccb
D/WfdsService( 1928): isConnected: false
D/WifiNative-p2p0( 1025): SET persistent_reconnect 1: returned true
D/HeadsetStateMachine( 6089): Proxy object connected
D/WifiNative-p2p0( 1025): doBoolean: SET device_name G3-1
D/WifiNative-p2p0( 1025): SET device_name G3-1: returned true
D/LGWifiP2pService( 1025): [LGE_P2P] initializeP2pSettings() check postfix
D/LGBluetoothHfpAdapter( 6089): [BTUI] queryPhoneState
D/LGWifiP2pService( 1025): before postfix = G3-1
D/LGBluetoothHfpAd,apter( 6089): Try to query the phonestate on bind
D/WifiServerServiceExt( 1025): postfix byte check : 4
D/LGWifiP2pService( 1025): after postfix = G3-1
D/BluetoothPhoneService.BluetoothLTECall( 1839):  call mBluetoothHeadset.phoneStateChanged()
D/WifiNative-p2p0( 1025): doBoolean: SET p2p_ssid_postfix -G3-1
D/WifiNative-p2p0( 1025): SET p2p_ssid_postfix -G3-1: returned true
D/WifiNative-p2p0( 1025): doBoolean: SET device_type 10-0050F204-5
D/HeadsetStateMachine( 6089): Disconnected process message: 10, size: 0
D/WifiNative-p2p0( 1025): SET device_type 10-0050F204-5: returned true
D/WifiNative-p2p0( 1025): doBoolean: SET config_methods virtual_push_button physical_display keypad
D/HeadsetPhoneState( 6089): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 6089): Disconnected process message: 11, size: 0
D/WifiNative-p2p0( 1025): SET config_methods virtual_push_button physical_display keypad: returned true
D/WifiNative-p2p0( 1025): doBoolean: P2P_SET conc_pref p2p
D/WifiNative-p2p0( 1025): P2P_SET conc_pref p2p: returned true
D/WifiNative-HAL( 1025): p2pGetDeviceAddress
D/WifiNative-HAL( 1025): p2pGetDeviceAddress returning 02:9a:02:7b:60:ac
,D/BluetoothAdapterService( 6089): Profile still not running:com.android.bluetooth.gatt.GattService
V/BluetoothPbapReceiver( 6089): PbapReceiver onReceive 
D/LGWifiP2pService( 1025): DeviceAddress: 02:9a:02:7b:60:ac
D/WifiNative-p2p0( 1025): doBoolean: P2P_FLUSH
V/BluetoothPbapReceiver( 6089): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6089): ***********state = 11
D/WifiNative-p2p0( 1025): P2P_FLUSH: returned true
D/WifiNative-p2p0( 1025): doBoolean: P2P_SERVICE_FLUSH
D/WifiNative-p2p0( 1025): P2P_SERVICE_FLUSH: returned true
D/WifiNative-p2p0( 1025): doString: [LIST_NETWORKS]
D/WifiNative-p2p0( 1025):    returned network id / ssid / bssid / flags
D/WifiNative-p2p0( 1025): doBoolean: SAVE_CONFIG
I/WfdStateTracker( 1928): handleP2pThisDeviceChanged
D/WfdsService( 1928): WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
D/WfdsService( 1928): Update P2p Interface State: 3
W/BluetoothHeadset( 1839): Proxy not attached to service
D/BluetoothHeadset( 1839): java.lang.Throwable
D/BluetoothHeadset( 1839): 	at android.bluetooth.BluetoothHeadset.phoneStateChanged(BluetoothHeadset.java:826)
D/BluetoothHeadset( 1839): 	at com.android.phone.BluetoothPhoneService$BluetoothLTECall.handleQueryPhoneState(BluetoothPhoneService.java:1527)
D/BluetoothHeadset( 1839): 	at com.android.phone.BluetoothPhoneService$BluetoothLTECall.access$700(BluetoothPhoneService.java:1360)
D/BluetoothHeadset( 1839): 	at com.android.phone.BluetoothPhoneService$1.handleMessage(BluetoothPhoneService.java:268)
D/BluetoothHeadset( 1839): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BluetoothHeadset( 1839): 	at android.os.Looper.loop(Looper.java:135)
D/BluetoothHeadset( 1839): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
D/BluetoothHeadset( 1839): 	at java.lang.reflect.Method.invoke(Native Method)
D/BluetoothHeadset( 1839): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/BluetoothHeadset( 1839): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
D/BluetoothHeadset( 1839): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/WifiStateMachine( 1025):  ConnectModeState CMD_START_DRIVER 0 0
E/WifiStateMachine( 1025):  DriverStartedState CMD_START_DRIVER 0 0
E/WifiStateMachine( 1025):  DisconnectedState what:132106 1 0
E/WifiStateMachine( 1025):  ConnectModeState what:132106 1 0
D/BluetoothAdapterService( 6089): Profile still not running:com.android.bluetooth.gatt.GattService
E/WifiStateMachine( 1025):  DriverStartedState what:132106 1 0
I/WifiServerServiceExt( 1025): setWifiDualbandAPConnection band : 1
D/BluetoothAdapterService( 6089): Profile still not running:com.android.bluetooth.gatt.GattService
E/wpa_supplicant( 6116): nWIFIDualbandAPConnection: 1
,E/WifiStateMachine( 1025):  DisconnectedState what:132096 -100 0
E/WifiStateMachine( 1025):  ConnectModeState what:132096 -100 0
D/BluetoothAdapterService( 6089): Profile still not running:com.android.bluetooth.gatt.GattService
E/WifiStateMachine( 1025):  DriverStartedState what:132096 -100 0
D/WifiNative-p2p0( 1025): SAVE_CONFIG: returned true
I/WifiServerServiceExt( 1025): set CMD_DISCONNECT_RSSI_LVL : -100
D/LGWifiP2pService( 1025): sending p2p persistent groups changed broadcast
E/wpa_supplicant( 6116): disconnect_rssi_lvl: -100
E/WifiStateMachine( 1025):  DisconnectedState CMD_SET_COUNTRY_CODE 1 0 cz
E/WifiStateMachine( 1025):  ConnectModeState CMD_SET_COUNTRY_CODE 1 0 cz
E/WifiStateMachine( 1025):  DriverStartedState CMD_SET_COUNTRY_CODE 1 0 cz
D/WifiNative-wlan0( 1025): doBoolean: DRIVER COUNTRY CZ
I/wpa_supplicant( 6116): wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
D/BluetoothAdapterService( 6089): Profile still not running:com.android.bluetooth.gatt.GattService
V/PanService( 6089): [BTUI] SIM Extra State :ABSENT
I/wpa_supplicant( 6116): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
I/wpa_supplicant( 6116): [LGE_PATCH] driver_cmd() country:CZ
I/wpa_supplicant( 6116): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
I/wpa_supplicant( 6116): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/BluetoothAdapterService( 6089): Profile still not running:com.android.bluetooth.map.BluetoothMapService
V/BluetoothMapService( 6089): Handler(): got msg=1
D/WfdsMonitor( 1928): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WfdsMonitor( 1928): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WifiMonitor( 1025): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
E/WifiMonitor( 1025): WifiMonitor:wlan0 cnt=2 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1025): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
D/WifiNative-wlan0( 1025): DRIVER COUNTRY CZ: returned true
E/WifiMonitor( 1025): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
D/WifiMonitor( 1025): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1025): WifiMonitor:p2p0 cnt=3 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1025): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1025): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiMonitor( 1025): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1025): WifiMonitor:p2p0 cnt=4 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1025): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1025): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiStateMachine( 1025):  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
D/BluetoothAdapterState( 6089): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid-qcom( 6089): enable
E/WifiStateMachine( 1025):  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
I/GKI_LINUX( 6089): gki_task_entry task_id=0 [BTU] starting
E/WifiStateMachine( 1025):  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
I/bt-btu  ( 6089): btu_task pending for preload complete event
I/bt_hci_bdroid( 6089): init
D/WifiNative-wlan0( 1025): doBoolean: DRIVER SETBAND 0
I/wpa_supplicant( 6116): wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
I/wpa_supplicant( 6116): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
D/WifiMonitor( 1025): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
E/WifiMonitor( 1025): WifiMonitor:wlan0 cnt=5 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
E/WifiMonitor( 1025): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
E/WifiMonitor( 1025): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
D/WifiNative-wlan0( 1025,): DRIVER SETBAND 0: returned true
D/WifiNative-wlan0( 1025): doBoolean: BSS_FLUSH 0
D/WifiNative-wlan0( 1025): BSS_FLUSH 0: returned true
D/WifiNative-wlan0( 1025): doBoolean: SCAN
I/bt_vendor( 6089): bt-vendor : init
I/bt_vendor( 6089): bt-vendor : get_bt_soc_type
E/bt_vendor( 6089): get_bt_soc_type: Failed to get soc type
I/bt_vendor( 6089): init: Local BD Address : c0:64:73:54:3f:58
D/bt_userial_mct( 6089): userial_init
D/bt_hci_bdroid( 6089): set_power 1
I/bt_vendor( 6089): bt-vendor : BT_VND_OP_POWER_CTRL: On
I/bt_vendor( 6089): Starting hciattach daemon
I/bt_vendor( 6089): try to set true
D/WifiNative-wlan0( 1025): SCAN: returned false
E/WifiStateMachine( 1025):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=111233  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,W/sh      ( 6189): type=1400 audit(0.0:157): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/sh      ( 6189): type=1400 audit(0.0:158): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/ActivityManager( 1025): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6190 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
E/WifiStateMachine( 1025):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=111247  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
I/qcom-bluetooth( 6191): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,E/WifiStateMachine( 1025):  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1025):  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1025):  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1025):  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1025):  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
I/StatusBar.NetworkController( 1465): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LGWifiP2pService( 1025): InactiveState
W/Settings( 1025): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1025): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGWifiP2pService( 1025): InactiveState{ when=-42ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1025): P2pEnabledState{ when=-42ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
D/WifiOffDelayIfNotUsed( 1025): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WifiNative-p2p0( 1025): doBoolean: DRIVER COUNTRY CZ
I/wpa_supplicant( 6116): wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
I/wpa_supplicant( 6116): p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
I/StatusBar.NetworkController( 1465): mWifiConnected = false, mWifiLevel = 0
I/wpa_supplicant( 6116): [LGE_PATCH] driver_cmd() country:CZ
I/wpa_supplicant( 6116): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
I/wpa_supplicant( 6116): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WfdsMonitor( 1928): Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
D/WfdsMonitor( 1928): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WfdsMonitor( 1928): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WifiMonitor( 1025): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
E/WifiMonitor( 1025): WifiMonitor:p2p0 cnt=6 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1025): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1025): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
D/WifiMonitor( 1025): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1025): WifiMonitor:p2p0 cnt=7 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1025): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1025): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiMonitor( 1025): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1025): WifiMonitor:p2p0 cnt=8 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1025): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1025): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiNative-p2p0( 1025): DRIVER COUNTRY CZ: returned true
D/LGWifiP2pService( 1025): InactiveState{ when=-28ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1025): P2pEnabledState{ when=-28ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1025): InactiveState{ when=-3ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1025): P2pEnabledState{ when=-3ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1025): DefaultState{ when=-3ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler, }
D/LGWifiP2pService( 1025): InactiveState{ when=-3ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1025): P2pEnabledState{ when=-3ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1025): DefaultState{ when=-3ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1025): InactiveState{ when=-3ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1025): P2pEnabledState{ when=-3ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1025): DefaultState{ when=-4ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1025): InactiveState{ when=-4ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1025): P2pEnabledState{ when=-4ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1025): DefaultState{ when=-4ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiServerServiceExt( 1025): SUPPLICANT_STATE_CHANGED_ACTION
W/WfdsService( 1928): DefaultState - msg [9441285] is not handled
D/WifiServerServiceExt( 1025): setSupplicantStateSCANNING
E/WifiServerServiceExt( 1025): No p2p device connected
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/qcom-bluetooth( 6213): /system/etc/init.qcom.bt.sh: Transport : smd 
I/qcom-bluetooth( 6214): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
I/qcom-bluetooth( 6216): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 6217): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
W/ProcessCpuTracker( 1025): Skipping unknown process pid 6213
I/qcom-bluetooth( 6218): /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
I/qcom-bluetooth( 6220): /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,I/ActivityManager( 1025): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6221 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/libmdmdetect( 6223): ESOC framework not supported
E/Diag_Lib( 6223):  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,E/ActivityThread( 6190): Failed to find provider info for com.lge.lgaccount.provider
W/LG Account v2.2( 6190): No ProfileInfo entries
I/LG Account v2.2( 6190): isEnabled: false
I/Feature ( 6190): [Lifetracker]ver: 4.21.112(40211120)
I/Feature ( 6190): [Lifetracker]Country: EU
I/Feature ( 6190): [Lifetracker]Operator: OPEN
I/Feature ( 6190): [Lifetracker]Ranking support: false
I/Feature ( 6190): [Lifetracker]Comfort support: false
I/Feature ( 6190): [Lifetracker]Accessory: true
I/Feature ( 6190): [Lifetracker]Health device: true
I/Feature ( 6190): [Lifetracker]Extra Pedometer: false
I/Feature ( 6190): [Lifetracker]Blood glucose device: false
I/Feature ( 6190): [Lifetracker]Device Number: 3
D/bthci_qcomm_linux( 6223): [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:64:C0)
D/bthci_qcomm_common( 6223): [BTUI] bt_hci_qcomm_init:
D/bthci_qcomm_common( 6223): [BTUI]     BDADDR: 58:3F:54:73:64:C0
D/bthci_qcomm_common( 6223): [BTUI]     BR/EDR: Class 1
D/bthci_qcomm_common( 6223): [BTUI]     LE: Class 2
D/bthci_qcomm_common( 6223): [BTUI]     Ref Clock: 32M
D/btqsocnvmtags( 6223): [BTUI] init_riva_entries: set NORMAL power settings
,D/BluetoothPermissionRequest( 6115): onReceive
D/LGBluetoothFeatureConfig( 6115):  get() - isFeatureLoaded : false
W/FormManager( 6164): Network not available. Please check & try again.
V/FormManager( 6164): Network unavailable.
V/FormManager( 6164): Network unavailable.
,D/BluetoothManagerService( 1025): Message: 20
D/BluetoothManagerService( 1025): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2e7a370d:true
D/LGBluetoothResetSettingReceiver( 6115): return without doing reset settings.
I/ActivityManager( 1025): Killing 5798:com.lge.email/u0a23 (adj 15): empty #17
D/PCSuite ( 6221): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,I/rmt_storage(  311): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  311): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  311): wakelock acquired: 1, error no: 42
I/rmt_storage(  311): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
,D/LGBluetoothOppAdapter( 6089): [BTUI] getInstance : create [LGBluetoothOppAdapter]
,W/libprocessgroup( 1025): failed to open /acct/uid_10023/pid_5798/cgroup.procs: No such file or directory
I/ActivityManager( 1025): Killing 5691:com.android.defcontainer/u0a4 (adj 15): empty #17
,I/rmt_storage(  311): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  311): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
I/rmt_storage(  311): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 22
I/rmt_storage(  311): 
,I/rmt_storage(  311): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
E/Diag_Lib(  898): [IMS_FATAL]| 3347 | 906 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
V/WiFiOffLoadBroadcast( 6115): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
D/WifiService( 1025): New client listening to asynchronous messages
,E/WifiMonitor( 1025): WifiMonitor:wlan0 cnt=9 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
I/wpa_supplicant( 6116): [LGE_PATCH]scan interval[0] = 2 sec.
E/WifiMonitor( 1025): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1025): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1025): WifiMonitor:wlan0 cnt=10 dispatchEvent: WPS-AP-AVAILABLE 
D/WfdsMonitor( 1928): Event [CTRL-EVENT-SCAN-RESULTS ]
D/WfdsMonitor( 1928): Event [WPS-AP-AVAILABLE ]
W/WifiMonitor( 1025): couldn't identify event type - WPS-AP-AVAILABLE 
E/WifiMonitor( 1025): WifiMonitor:p2p0 cnt=11 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1025): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1025): Event [IFNAME=p2p0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1025): WifiMonitor:p2p0 cnt=12 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1025): couldn't identify event type - WPS-AP-AVAILABLE 
E/WifiStateMachine( 1025):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
D/LGWifiP2pService( 1025): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1025): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1025): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 1025):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine( 1025):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine( 1025):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
I/WifiNative-HAL( 1025): startHal
E/wifi    ( 1025): getStaticLongField sWifiHalHandle 0x988bf8cc
E/WifiHAL ( 1025): Could not connect handle
D/wifi    ( 1025): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x30215e
I/WifiNative-HAL( 1025): Could not start hal
D/WifiNative-wlan0( 1025): doString: [BSS RANGE=0- MASK=0x21987]
D/LgDataFeature( 6115): LgDataFeature() Constructor: none
D/LgDataFeature( 6115): LgDataFeature() Constructor Done, null
,D/WiFiOffLoadUpdatePriority( 6115): remove : truetruetrue
,W/libprocessgroup( 1025): failed to open /acct/uid_10004/pid_5691/cgroup.procs: No such file or directory
V/BluetoothFtpReceiver( 6089): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,E/WifiStateMachine( 1025):  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
,E/WifiStateMachine( 1025):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
V/BluetoothSapReceiver( 6089): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 6089): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 6089): SapReceiver onReceive 
V/BluetoothSapReceiver( 6089): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6089):  Bluetooth Adapter state = 11
E/WifiStateMachine( 1025):  DisconnectedState CMD_SAVE_CONFIG uid=1000 0 0
,E/WifiStateMachine( 1025):  ConnectModeState CMD_SAVE_CONFIG uid=1000 0 0
D/WifiNative-wlan0( 1025): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1025): SAVE_CONFIG: returned true
D/WiFiOffLoadUpdatePriority( 6115): remove1
V/WiFiOffLoadSharedPrefsUtils( 6115): save remove
D/WiFiOffLoadBroadcast( 6115): mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
D/WiFiOffLoadBroadcast( 6115): S: false, R: false
,E/WifiStateMachine( 1025):  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1025):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/WiFiOffLoadUpdatePriority( 6115): saved SSID: "NG700"
D/WiFiOffLoadUpdatePriority( 6115): connected SSID: null
D/WiFiOffLoadUpdatePriority( 6115): private wpa: "NG700" 300
D/WifiServiceImplEx( 1025): addOrUpdateNetwork pid=6115, uid=1000, packageName=android.uid.system:1000
E/addOrUpdateNetwork( 1025):  uid = 1000 SSID "NG700" nid=0
E/WifiStateMachine( 1025):  DisconnectedState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=2
,E/WifiStateMachine( 1025):  ConnectModeState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=2
E/WifiConfigStore( 1025):  key="NG700"WPA_PSK netId=0 uid=0/1000
D/WifiServerServiceExt( 1025): addOrUpdateNetwork: mThisIsFirstEnableing = false
D/WifiNative-wlan0( 1025): doBoolean: SET_NETWORK 0 ssid 4e47373030
I/ActivityManager( 1025): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6254 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,D/WifiNative-wlan0( 1025): SET_NETWORK 0 ssid 4e47373030: returned true
D/WifiNative-wlan0( 1025): doBoolean: SET_NETWORK 0 key_mgmt WPA-PSK
D/WifiNative-wlan0( 1025): SET_NETWORK 0 key_mgmt WPA-PSK: returned true
,D/WifiNative-wlan0( 1025): doBoolean: SET_NETWORK 0 proto WPA RSN
D/WifiNative-wlan0( 1025): SET_NETWORK 0 proto WPA RSN: returned true
D/WifiNative-wlan0( 1025): doBoolean: SET_NETWORK 0 pairwise TKIP CCMP
D/WifiNative-wlan0( 1025): SET_NETWORK 0 pairwise TKIP CCMP: returned true
D/WifiNative-wlan0( 1025): doBoolean: SET_NETWORK 0 group WEP40 WEP104 TKIP CCMP
D/WifiNative-wlan0( 1025): SET_NETWORK 0 group WEP40 WEP104 TKIP CCMP: returned true
D/WifiNative-wlan0( 1025): doBoolean: SET_NETWORK 0 priority 300
D/WifiNative-wlan0( 1025): SET_NETWORK 0 priority 300: returned true
E/WifiConfigStore( 1025): will read network variables netId=0
E/WifiConfigStore( 1025): writeIpAndProxyConfigurationsOnChange: "NG700" -> "NG700" path: /data/misc/wifi/ipconfig.txt
E/WifiConfigStore( 1025):  writeKnownNetworkHistory() num networks:1 needWrite=false
D/WiFiOffLoadUpdatePriority( 6115):  ssid "NG700" prio 300
D/WiFiOffLoadUpdatePriority( 6115): configuration updated: 0
E/WifiStateMachine( 1025):  DisconnectedState CMD_SAVE_CONFIG uid=1000 0 0
,E/WifiStateMachine( 1025):  ConnectModeState CMD_SAVE_CONFIG uid=1000 0 0
D/WifiNative-wlan0( 1025): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1025): SAVE_CONFIG: returned true
D/WiFiOffLoadUpdatePriority( 6115): configuration saved: true
I/ActivityManager( 1025): Killing 5562:com.android.gallery3d/u0a27 (adj 15): empty #17
,W/libprocessgroup( 1025): failed to open /acct/uid_10027/pid_5562/cgroup.procs: No such file or directory
W/ResourcesManager( 6254): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/PCSuite ( 6221): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6115): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,D/AuthorizationBluetoothService( 2057): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/WiFiOffLoadBroadcast( 6115): MCCMNC not supported: null
W/FormManager( 6164): Network not available. Please check & try again.
V/FormManager( 6164): Network unavailable.
,V/FormManager( 6164): Network unavailable.
D/LGDMClient( 4006): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 4006): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4006): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4006): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
I/ActivityManager( 1025): Killing 5087:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,W/libprocessgroup( 1025): failed to open /acct/uid_1000/pid_5087/cgroup.procs: No such file or directory
,D/LGDMClient( 4006): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,D/LGDMClient( 4006): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 4006): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/ActivityManager( 1025): Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=6276 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,W/ResourcesManager( 6276): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/PluginManager( 6276): init()
,E/QC-QMI  ( 6223): qmi_client [6223] 13: failed to locate client data
,E/QC-QMI  (  473): qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
,E/QC-QMI  (  473): QMUX qmux_client_id=13 not found in qmux client list, unable to remove
W/ExternalStrings( 6276): load override strings
W/ExternalStrings( 6276): java.lang.RuntimeException: Unexpected tag, got eat-comment
W/ExternalStrings( 6276): 	at com.mcafee.plugin.af.a(Unknown Source)
W/ExternalStrings( 6276): 	at com.mcafee.plugin.ac.b(Unknown Source)
W/ExternalStrings( 6276): 	at com.mcafee.plugin.ak.d(Unknown Source)
W/ExternalStrings( 6276): 	at com.mcafee.plugin.ak.a(Unknown Source)
W/ExternalStrings( 6276): 	at com.mcafee.app.s.getClassLoader(Unknown Source)
W/ExternalStrings( 6276): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
W/ExternalStrings( 6276): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
W/ExternalStrings( 6276): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
W/ExternalStrings( 6276): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
W/ExternalStrings( 6276): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
W/ExternalStrings( 6276): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ExternalStrings( 6276): 	at android.os.Looper.loop(Looper.java:135)
W/ExternalStrings( 6276): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/ExternalStrings( 6276): 	at java.lang.reflect.Method.invoke(Native Method)
W/ExternalStrings( 6276): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/ExternalStrings( 6276): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/ExternalStrings( 6276): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,D/StatusProvider( 6276): onCreate
V/Signer  ( 6276): override build config not found
D/Signer  ( 6276): value of property debug is false
,I/qcom-bluetooth( 6296): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:64:c0 
,I/qcom-bluetooth( 6297): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
D/LGMDMWrapper( 6276): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
D/LGMDMWrapper( 6276): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
D/LGMDMWrapper( 6276): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
D/LGMDMWrapper( 6276): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
D/LGMDMWrapper( 6276): Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
D/LGMDMWrapper( 6276): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
D/LGMDMWrapper( 6276): Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
D/LGMDMWrapper( 6276): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
D/LGMDMWrapper( 6276): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
D/LGMDMWrapper( 6276): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
D/LGMDMWrapper( 6276): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
D/LGMDMWrapper( 6276): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
D/LGMDMWrapper( 6276): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
,I/bt_vendor( 6089): bluetooth satus is on
D/bt_hci_bdroid( 6089): preload
D/bt_userial_mct( 6089): userial_open(port:0)
I/bt_vendor( 6089): bt-vendor : BT_VND_OP_USERIAL_OPEN
I/bt_vendor( 6089): Done intiailizing UART
I/bt_vendor( 6089): Done intiailizing UART
I/bt_userial_mct( 6089): CMD=66, EVT=66, ACL_Out=67, ACL_In=67
I/bt_vendor( 6089): Bluetooth Firmware and transport layer are initialized
D/bt_userial_mct( 6089): Entering userial_read_thread()
I/bt-btu  ( 6089): btu_task received preload complete event
W/bt-l2cap( 6089): L2CAP - L2CA_Register() called for PSM: 0x0001
W/bt-l2cap( 6089): L2CAP - L2CA_Register() called for PSM: 0x001f
W/bt-l2cap( 6089): L2CAP - L2CA_Register() called for PSM: 0x0003
I/        ( 6089): BTE_InitTraceLevels -- TRC_HCI
I/        ( 6089): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 6089): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 6089): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 6089): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 6089): BTE_InitTraceLevels -- TRC_A2D
I/        ( 6089): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 6089): BTE_InitTraceLevels -- TRC_BTM
I/        ( 6089): BTE_InitTraceLevels -- TRC_HID_HOST
I/        ( 6089): BTE_InitTraceLevels -- TRC_GAP
I/        ( 6089): BTE_InitTraceLevels -- TRC_PAN
I/        ( 6089): BTE_InitTraceLevels -- TRC_SDP
I/        ( 6089): BTE_InitTraceLevels -- TRC_GATT
I/        ( 6089): BTE_InitTraceLevels -- TRC_SMP
I/        ( 6089): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 6089): BTE_InitTraceLevels -- TRC_BTIF
V/LGMDMManager( 6276): Create singleton instance
,W/bt-btm  ( 6089): btm_decode_ext_features_page Secure conn Controller support Enabled
E/bt-btm  ( 6089): BTM_SecRegister:p_cb_info->p_le_callback == 0xa0140061 
,E/bt-btm  ( 6089): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0140061 
E/bt-btif ( 6089): Calling BTA_HhEnable
E/bt-btif ( 6089): btif_storage_get_adapter_property service_mask:0x2140040
W/bt-l2cap( 6089): L2CAP - L2CA_Register() called for PSM: 0x0019
W/bt-l2cap( 6089): L2CAP - L2CA_Register() called for PSM: 0x0017
W/bt-l2cap( 6089): L2CAP - L2CA_Register() called for PSM: 0x001b
D/BluetoothAdapterProperties( 6089): Address is:58:3F:54:73:64:C0
W/bt-l2cap( 6089): L2CAP - L2CA_Register() called for PSM: 0x0011
W/bt-l2cap( 6089): L2CAP - L2CA_Register() called for PSM: 0x0013
D/BluetoothManagerService( 1025): Bluetooth Adapter name changed to G3-1
D/BluetoothAdapterProperties( 6089): Name is: G3-1
D/BluetoothManagerService( 1025): Stored Bluetooth name: G3-1
D/BluetoothAdapterProperties( 6089): Scan Mode:20
D/BluetoothAdapterProperties( 6089): Discoverable Timeout:120
D/bt_hci_bdroid( 6089): postload
D/bt_hci_bdroid( 6089): Used up Tx Cmd credits
W/bt-l2cap( 6089): L2CAP - L2CA_Register() called for PSM: 0x000f
,D/bt_hci_bdroid( 6089): Used up Tx Cmd credits
D/bte_conf( 6089): Device ID record 1 : primary
D/bte_conf( 6089):   vendorId            = 00c4
D/bte_conf( 6089):   vendorIdSource      = 0001
D/bte_conf( 6089):   product             = 13a1
D/bte_conf( 6089):   version             = 1000
,D/bte_conf( 6089):   clientExecutableURL = 
D/bte_conf( 6089):   serviceDescription  = 
D/bte_conf( 6089):   documentationURL    = 
D/bte_conf( 6089): bte_load_did_conf no section named DID2.
D/bt_hci_bdroid( 6089): Used up Tx Cmd credits
D/bt_hci_bdroid( 6089): Used up Tx Cmd credits
D/LGMDMWrapper( 6276): LG MDM library v4.0.0 is available on this device.
W/sh      ( 6301): type=1400 audit(0.0:159): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/sh      ( 6301): type=1400 audit(0.0:160): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/BluetoothAdapterState( 6089): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 6089): ScanMode =  20
D/BluetoothAdapterProperties( 6089): State =  11
D/BluetoothAdapterProperties( 6089): mDiscoverableTimeout = 120
V/LGBluetoothServiceAdapter( 6089): [BTUI] state:11, scanmode:20, timeout:120
D/BluetoothAdapterProperties( 6089): Setting state to 12
I/BluetoothAdapterState( 6089): Bluetooth adapter state changed: 11-> 12
D/BluetoothManagerService( 1025): Message: 60
D/BluetoothManagerService( 1025): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
,E/bt_mct  ( 6089): hci lib postload completed
I/BluetoothAdapterState( 6089): Entering On State
D/BluetoothPanServiceJni( 6089): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/btif_config_util( 6089): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
D/LGBluetoothServiceAdapter( 6089): [BTUI] OnState
D/LGBluetoothServiceAdapter( 6089): [BTUI]         global_name: G3-1
D/LGBluetoothServiceAdapter( 6089): [BTUI]         local_name: G3-1
D/BluetoothAdapterService( 6089): [BTUI] autoConnect() : not allowed
D/BluetoothManagerService( 1025): Broadcasting onBluetoothStateChange(true) to 5 receivers.
D/BluetoothHeadset( 1839): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1839): onBluetoothStateChange: up=true
D/BluetoothA2dp( 1025): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1839): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1025): onBluetoothStateChange: up=true
E/BluetoothManagerService( 1025): Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
,D/BluetoothManagerService( 1025): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService( 1025): Bluetooth State Change Intent: 11 -> 12
W/bt-smp  ( 6089): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6089): Plain text(LSB ~ MSB) = 63 6a 65 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6089): Encrypted text(LSB ~ MSB) = cd c0 a6 bf 07 bc e5 bd 68 9d 26 78 95 6c c3 4e 
W/bt-btm  ( 6089): Stopping oneshot timer
I/[SystemUI]BluetoothHandler( 1465): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
D/BluetoothManagerService( 1025): Message: 40
D/BluetoothManagerService( 1025): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
D/LGBluetoothAPIService( 1928): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/LGBluetoothAPIService( 1928): Message: 1
D/LGBluetoothAPIService( 1928): MESSAGE_BOOT_COMPLETED
I/BluetoothMapService( 6089): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 6089): STATE_ON
V/BluetoothMapService( 6089): Handler(): got msg=1
D/BluetoothMapMasInstance( 6089): Map Service startRfcommSocketListener
D/BluetoothMapMasInstance( 6089): MAS initSocket()
D/BluetoothMapMasInstance( 6089):   masId = 00
D/BluetoothMapMasInstance( 6089):   msgTypes = 0e
D/BluetoothMapMasInstance( 6089):   masName = SMS/MMS
D/BluetoothMapMasInstance( 6089):   SDP string = 000eSMS/MMS
,D/BluetoothManagerService( 1025): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/LGBluetoothAPIService( 1928): [BTUI] LGBluetoothAPIService Binding Success
W/bt-smp  ( 6089): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6089): Plain text(LSB ~ MSB) = 0a 49 4c 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6089): Encrypted text(LSB ~ MSB) = 5c 99 da cd 53 bf df 0c 35 36 1a f6 9f d2 e0 c2 
W/bt-btm  ( 6089): Stopping oneshot timer
W/BluetoothAdapter( 6089): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 6089): [BTUI] createSocketChannel FD=73 mFd=0
V/BluetoothMapMasInstance( 6089): Succeed to create listening socket 
D/BluetoothMapMasInstance( 6089): Accepting socket connection...
,W/ContextImpl( 6115): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
W/bt-smp  ( 6089): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6089): Plain text(LSB ~ MSB) = 23 68 7b 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6089): Encrypted text(LSB ~ MSB) = 60 66 75 4a 20 f3 cc 4a 63 06 0d 2f c4 34 37 14 
W/bt-btm  ( 6089): Stopping oneshot timer
D/BluetoothAdapterService( 6089): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c26fccb
V/BluetoothPbapService( 6089): Pbap Service onCreate
V/BluetoothPbapService( 6089): Starting PBAP service
D/LGBluetoothPbapAdapter( 6089): [BTUI] getInstance : create
V/BluetoothPbapService( 6089): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 6089): state: 12
W/bt-smp  ( 6089): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6089): Plain text(LSB ~ MSB) = 99 f9 69 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6089): Encrypted text(LSB ~ MSB) = e5 aa 39 05 b4 7e 56 8c bb f6 b6 71 b6 03 1f 0e 
W/bt-btm  ( 6089): Stopping oneshot timer
,D/LGBluetoothDeviceModeControllManager( 6089): [BTUI] checkDeviceModeAndSet, sinkMode : false
D/LGBluetoothAPIServer( 6089): [BTUI] onCreate()
D/LGBluetoothAPIServer( 6089): [BTUI] onBind()
V/BluetoothPbapReceiver( 6089): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 6089): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6089): ***********state = 12
D/LGBluetoothAPIService( 1928): [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
D/LGBluetoothAPIService( 1928): Message: 100
D/LGBluetoothAPIService( 1928): MESSAGE_BLUETOOTH_SERVICE_CONNECTED
V/BluetoothPbapService( 6089): Handler(): got msg=1
V/BluetoothPbapService( 6089): Pbap Service startRfcommSocketListener
W/bt-smp  ( 6089): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6089): Plain text(LSB ~ MSB) = 2e 1a 55 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6089): Encrypted text(LSB ~ MSB) = 13 c8 57 e2 a7 7e 7e 38 75 47 de 5e 7b 39 33 14 
W/bt-btm  ( 6089): Stopping oneshot timer
V/BluetoothPbapService( 6089): Pbap Service initSocket
D/BluetoothManagerService( 1025): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6089): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 6089): [BTUI] createSocketChannel FD=75 mFd=73
V/BluetoothPbapService( 6089): Succeed to create listening socket 
V/BluetoothPbapService( 6089): Accepting socket connection...
,D/LocalBluetoothProfileManager( 6115): Adding local A2DP profile
D/BluetoothManagerService( 1025): Message: 30
D/LocalBluetoothProfileManager( 6115): Adding local HEADSET profile
D/BluetoothManagerService( 1025): Message: 30
I/qcom-bt-wlan-coex( 6316): /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
D/BluetoothManagerService( 1025): Message: 30
D/BluetoothAdapterProperties( 6089): Discoverable Timeout:120
D/LGBluetoothDeviceModeControllManager( 6089): adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
D/BluetoothAdapterProperties( 6089): Scan Mode:21
D/LGBluetoothDeviceModeControllManager( 6089): getDeviceMode  deviceMode 0
D/BluetoothManagerService( 1025): Message: 30
D/LocalBluetoothProfileManager( 6115): Adding local MAP profile
D/BluetoothMap( 6115): Create BluetoothMap proxy object
D/BluetoothManagerService( 1025): Message: 30
D/BluetoothManagerService( 1025): Message: 30
V/BluetoothPbapService( 6089): Pbap Service onBind
D/LocalBluetoothProfileManager( 6115): LocalBluetoothProfileManager construction complete
D/LGBluetoothUserBindClient( 6115): [BTUI] initUserBindClient
W/ContextImpl( 6115): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
,D/DockEventReceiver( 6115): finishStartingService: stopping service
D/BluetoothA2dp( 6115): Proxy object connected
D/A2dpProfile( 6115): Bluetooth service connected
D/PostponalbeReceiver( 6276): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 6276): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,I/PCSuite ( 6221): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6221): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6221): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/BluetoothHeadset( 6115): Proxy object connected
D/HeadsetProfile( 6115): Bluetooth service connected
D/BluetoothInputDevice( 6115): Proxy object connected
D/HidProfile( 6115): Bluetooth service connected
D/BluetoothPan( 6115): BluetoothPAN Proxy object connected
D/PanProfile( 6115): Bluetooth service connected
,D/BluetoothMap( 6115): Proxy object connected
D/MapProfile( 6115): Bluetooth service connected
D/BluetoothMap( 6115): getConnectedDevices()
V/BluetoothMapService( 6089): getConnectedDevices()
D/BluetoothPbap( 6115): Proxy object connected
D/PbapServerProfile( 6115): Bluetooth service connected
D/LGBluetoothUserBindClient( 6115): [BTUI] onServiceConnected
V/WiFiOffLoadBroadcast( 6115): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6115): MCCMNC not supported: null
D/BluetoothPermissionRequest( 6115): onReceive
D/LGBluetoothFeatureConfig( 6115): isPrivacyLogsEnabled : true
D/LGBluetoothUtils( 6115): [BTUI] FileNotFound: readProperty
D/LGBluetoothResetSettingReceiver( 6115): return without doing reset settings.
,I/ActivityManager( 1025): Killing 5833:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,W/ActivityThread( 6276): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,V/BluetoothOppReceiver( 6089): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,W/libprocessgroup( 1025): failed to open /acct/uid_10061/pid_5833/cgroup.procs: No such file or directory
I/LGBluetoothOppAdapter( 6089): [BTUI] startOppService()
V/BluetoothOppManager( 6089): restoreApplicationData! falsefalsenullnull
,D/LGBluetoothFeatureConfig( 6089): isPrivacyLogsEnabled : true
V/BtOppService( 6089): onCreate
,V/BluetoothOppNotification( 6089): send message
V/BtOppService( 6089): Deleted complete outbound shares, number =  0
I/ActivityManager( 1025): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6331 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,V/BtOppService( 6089): Deleted complete inbound failed shares, number = 0
V/BluetoothOppProvider( 6089): starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
V/BtOppService( 6089): Starting RfcommListener
V/BluetoothOppProvider( 6089): created cursor android.database.sqlite.SQLiteCursor@5c261e4 on behalf of 
D/BluetoothOppPreference( 6089): Dumping Names:  
D/BluetoothOppPreference( 6089): {}
D/BluetoothOppPreference( 6089): Dumping Channels:  
D/BluetoothOppPreference( 6089): {}
V/BtOppService( 6089): onStartCommand
V/BtOppService( 6089): pendingUpdate is true keepUpdateThread is false sListenStarted is true
V/BluetoothOppProvider( 6089): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6089): created cursor android.database.sqlite.SQLiteCursor@19c16502 on behalf of 
V/BluetoothOppNotification( 6089): update too frequent, put in queue
V/BtOppService( 6089): pendingUpdate is true keepUpdateThread is false sListenStarted is true
V/BluetoothOppProvider( 6089): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
V/BluetoothFtpReceiver( 6089): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpReceiver( 6089): BluetoothFtpReceiver Start Service
V/BluetoothOppNotification( 6089): new notify threadi!
V/BluetoothOppNotification( 6089): send delay message
V/BtOppService( 6089): ContentObserver received notification
V/BtOppService( 6089): ContentObserver received notification
,V/BluetoothOppProvider( 6089): created cursor android.database.sqlite.SQLiteCursor@5aace13 on behalf of 
V/BtOppService( 6089): start RfcommListener
V/BluetoothOppNotification( 6089): update too frequent, put in queue
V/BtOppService( 6089): RfcommListener started
V/BtOppRfcommListener( 6089): Starting RFCOMM listener....
V/BluetoothOppProvider( 6089): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
D/BluetoothAdapterService( 6089): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c26fccb
V/BluetoothFtpService( 6089): Ftp Service onCreate
I/BluetoothFtpService( 6089): Ftp Service onCreate
V/BluetoothFtpService( 6089): Ftp Service onStartCommand
V/BluetoothFtpService( 6089): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpService( 6089): Starting Listening on sockets
D/BluetoothManagerService( 1025): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,V/BluetoothOppProvider( 6089): created cursor android.database.sqlite.SQLiteCursor@34e80a49 on behalf of 
V/BluetoothOppNotification( 6089): mUpdateCompleteNotification = true
V/BtOppService( 6089): pendingUpdate is true keepUpdateThread is false sListenStarted is true
V/BluetoothSapReceiver( 6089): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 6089): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 6089): SapReceiver onReceive 
V/BluetoothSapReceiver( 6089): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6089):  Bluetooth Adapter state = 12
V/BluetoothSapReceiver( 6089): Calling SAP service start service with action = null
V/BluetoothOppProvider( 6089): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
W/BluetoothAdapter( 6089): getBluetoothService() called with no BluetoothManagerCallback
V/BluetoothOppProvider( 6089): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 6089): created cursor android.database.sqlite.SQLiteCursor@3764cf4e on behalf of 
V/BluetoothFtpService( 6089): Handler(): got msg=1
V/BluetoothFtpService( 6089): Ftp Service startRfcommSocketListener
V/BluetoothFtpService( 6089): Ftp Service initSocket
V/BluetoothOppProvider( 6089): created cursor android.database.sqlite.SQLiteCursor@316a386f on behalf of 
V/BtOppService( 6089): pendingUpdate is false keepUpdateThread is false sListenStarted is true
V/BluetoothOppNotification( 6089): outbound: succ-0  fail-0
V/BluetoothOppNotification( 6089): outbound notification was removed.
V/BluetoothOppProvider( 6089): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
D/LGBluetoothServiceAdapter( 6089): [BTUI] createSocketChannel FD=78 mFd=75
V/BtOppRfcommListener( 6089): Started RFCOMM listener....
I/BtOppRfcommListener( 6089): Accept thread started.
V/BtOppRfcommListener( 6089): Accepting connection...
,D/BluetoothManagerService( 1025): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
V/BluetoothOppProvider( 6089): created cursor android.database.sqlite.SQLiteCursor@3c46097c on behalf of 
W/BluetoothAdapter( 6089): getBluetoothService() called with no BluetoothManagerCallback
V/BluetoothOppNotification( 6089): inbound: succ-0  fail-0
D/LGBluetoothServiceAdapter( 6089): [BTUI] createSocketChannel FD=81 mFd=78
V/BluetoothFtpService( 6089): Succeed to create listening socket on channel 20
V/BluetoothFtpService:RfcommSocketAcceptThread( 6089): Run Accept thread
D/AuthorizationBluetoothService( 2057): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/BluetoothAdapterService( 6089): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c26fccb
V/BluetoothSapService( 6089): Sap Service onCreate
W/ResourcesManager( 6331): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
V/BluetoothOppNotification( 6089): inbound notification was removed.
V/BluetoothOppProvider( 6089): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,V/BluetoothOppProvider( 6089): created cursor android.database.sqlite.SQLiteCursor@16a84168 on behalf of 
V/BluetoothSapService( 6089): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 6089): state: 12
V/BluetoothSapService( 6089): Starting SAP server process
V/BluetoothSapService( 6089): SAP Service startRfcommListenerThread
V/BluetoothSapService( 6089): Sap Service initRfcommSocket
D/BluetoothManagerService( 1025): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6089): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 6089): [BTUI] createSocketChannel FD=83 mFd=81
V/BluetoothSapService( 6089): Succeed to create listening socket 
V/BluetoothSapService( 6089): Accepting socket connection...
W/sapd    ( 6357): type=1400 audit(0.0:161): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/sapd    ( 6357): type=1400 audit(0.0:162): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,D/QRemote ( 6331): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
V/BT_SAP  ( 6357): Event pipe created
V/BT_SAP  ( 6357): create_server_socket qcom.sap.server
V/BT_SAP  ( 6357): created socket fd 6
D/QRemote ( 6331): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
I/QRemote ( 6331): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 6331): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 6331): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 6331): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 6331): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 6331): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6331): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6331): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6331): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/QRemote ( 6331): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
V/[BNRBootReceiver]( 5940): boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/BNRAndroBeam( 5940): [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
D/QRemote ( 6331): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
V/[BNRBootReceiver]( 5940): Boot Receiver Return
D/PostponalbeReceiver( 6276): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 6276): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
D/LgDataFeature( 6276): LgDataFeature() Constructor: none
D/LgDataFeature( 6276): LgDataFeature() Constructor Done, null
,V/WiFiOffLoadBroadcast( 6115): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6115): MCCMNC not supported: null
D/QRemote ( 6331): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6331): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6331): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/WiFiOffLoadBroadcast( 6115): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,D/WiFiOffLoadBroadcast( 6115): Not supported operator for automatic switch
D/PostponalbeReceiver( 6276): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
V/QRemote ( 6331): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6331): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 6331): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,D/LgDataFeature( 6331): LgDataFeature() Constructor: none
,D/LgDataFeature( 6331): LgDataFeature() Constructor Done, null
V/SoundPool( 6331): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 6331): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 6331): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 6331): doLoad: loading sample sampleID=1
V/SoundPool( 6331): Start decode
V/MediaPlayer[Native]( 6331): decode(31, 10857164, 17813)
I/QRemote ( 6331): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
V/MediaPlayerService(  321): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  321): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  321): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  321): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  321): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  321): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  321): player type = 3
V/AwesomePlayer(  321): AwesomePlayer create()
V/AwesomePlayer(  321): reset_l() 
V/AwesomePlayer(  321): cancelPlayerEvents
V/AwesomePlayer(  321): setAudioSink() 
V/AwesomePlayer(  321): reset_l() 
V/AudioCache(  321): notify(0xb5474900, 8, 0, 0)
V/AudioCache(  321): ignored
V/AwesomePlayer(  321): cancelPlayerEvents
D/Utils   (  321): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  321): setDataSource_l dataSource
V/LGParserOSAL(  321): SniffLGParser start
V/LGParserOSAL(  321): MainType:5, SubType=0
V/LGParserOSAL(  321): #### check Mime : application/ogg
V/LGParserOSAL(  321): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  321): Use LGExtractor :application/ogg 
D/UEI.SmartControl( 5915): QS Service created
D/QRemote ( 6331): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,E/QRemote ( 6331): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6331): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
I/UEI.SmartControl( 5915): Service initServices...
D/UEI.SmartControl( 5915): QS start get config
V/LGMDMManager( 6331): Create singleton instance
,V/LGParserOSAL(  321): supported mime: application/ogg
V/AwesomePlayer(  321): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  321): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  321): mBitrate = -1 bits/sec
V/AwesomePlayer(  321): AudioTrack Setting
V/AwesomePlayer(  321): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  321): setAudioSource() 
V/MediaPlayerService(  321): prepare
V/AwesomePlayer(  321): prepareAsync_l() 
V/MediaPlayerService(  321): wait for prepare
V/AwesomePlayer(  321): onPrepareAsyncEvent() 
V/AwesomePlayer(  321): initAudioDecoder() 
W/Utils   (  321): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  321): isOffloadSupported()
V/AudioPolicyManager(  321): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  321): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  321): isAudioPlaybackHookOn() false
V/AwesomePlayer(  321): getUseOffload() = 0 
V/OMXCodec(  321): OMXCodec::Create
V/OMXCodec(  321): findMatchingCodecs()
V/OMXCodec(  321): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  321): matchingCodecs.size()=1
V/OMXCodec(  321): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
D/OMXCodec(  321): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  321): LG Codec Adapter start
V/OMXCodec(  321): OMXCodec Createtor
V/OMXCodec(  321): setComponentRole
V/OMXCodec(  321): configureCodec protected=0
V/LGCodecAdapter(  321): called getLGCodecSpecificData
V/LGCodecOSAL(  321): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  321): Called LGconfigureCodecMETA
V/LGCodecOSAL(  321): Called LGconfigureCodecMSG
V/LGCodecOSAL(  321): Not support LGCodec
V/OMXCodec(  321): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  321): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  321): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  321): Could not offload audio decode, try pcm offload
W/Utils   (  321): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  321): isOffloadSupported()
V/AudioPolicyManager(  321): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  321): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  321): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  321): init()
V/OMXCodec(  321): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  321): allocateBuffers
V/OMXCodec(  321): allocateBuffersOnPort portIndex=0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on input port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on input port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on input port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on input port
V/OMXCodec(  321): allocateBuffersOnPort portIndex=1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on output port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ce0 on output port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d30 on output port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated, buffer 0xb57bf0b0 on output port
V/OMXCodec(  321): init() mAsyncCompletion wait!!! 
W/ContextImpl( 6276): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
V/OMXCodec(  321): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  321): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  321): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  321): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  321): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  321): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  321): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  321): finishAsyncPrepare_l() 
V/AudioCache(  321): notify(0xb5474900, 5, 0, 0)
V/AudioCache(  321): ignored
V/AudioCache(  321): notify(0xb5474900, 1, 0, 0)
V/AudioCache(  321): prepared
V/AudioCache(  321): wait - success
V/MediaPlayerService(  321): start
V/AwesomePlayer(  321): play_l() 
V/AwesomePlayer(  321): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  321): createAudioPlayer_l
V/AwesomePlayer(  321): seekAudioIfNecessary_l() 
V/AwesomePlayer(  321): startAudioPlayer_l() 
D/AudioPlayer(  321): start of Playback, useOffload 0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  321): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  321): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  321): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  321): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  321): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885248
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885408
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885488
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044798640
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  321): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  321): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  321): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  321): allocateBuffersOnPort portIndex=1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d30 on output port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ce0 on output port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on output port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc100 on output port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  321): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
,V/AudioCache(  321): open(48000, 2, 0x0, 1, 4)
,V/AudioCache(  321): notify(0xb5474900, 6, 0, 0)
V/AudioCache(  321): ignored
V/MediaPlayerService(  321): wait for playback complete
V/AudioCache(  321): write(0xb17c7000, 4096)
V/AudioCache(  321): memcpy(0xab700000, 0xb17c7000, 4096)
V/AudioCache(  321): write(0xb17c7000, 4096)
V/AudioCache(  321): memcpy(0xab701000, 0xb17c7000, 4096)
V/AudioCache(  321): write(0xb17c7000, 4096)
V/AudioCache(  321): memcpy(0xab702000, 0xb17c7000, 4096)
V/AudioCache(  321): write(0xb17c7000, 4096)
V/AudioCache(  321): memcpy(0xab703000, 0xb17c7000, 4096)
V/AudioCache(  321): write(0xb17c7000, 4096)
V/AudioCache(  321): memcpy(0xab704000, 0xb17c7000, 4096)
V/AudioCache(  321): write(0xb17c7000, 4096)
V/AudioCache(  321): memcpy(0xab705000, 0xb17c7000, 4096)
V/AudioCache(  321): write(0xb17c7000, 4096)
V/AudioCache(  321): memcpy(0xab706000, 0xb17c7000, 4096)
V/AudioCache(  321): write(0xb17c7000, 4096)
V/AudioCache(  321): memcpy(0xab707000, 0xb17c7000, 4096)
V/AudioCache(  321): write(0xb17c7000, 4096)
V/AudioCache(  321): memcpy(0xab708000, 0xb17c7000, 4096)
V/AudioCache(  321): write(0xb17c7000, 4096)
V/AudioCache(  321): memcpy(0xab709000, 0xb17c7000, 4096)
V/AudioCache(  321): write(0xb17c7000, 4096)
V/AudioCache(  321): memcpy(0xab70a000, 0xb17c7000, 4096)
V/AudioCache(  321): write(0xb17c7000, 4096)
V/AudioCache(  321): memcpy(0xab70b000, 0xb17c7000, 4096)
V/AudioCache(  321): write(0xb17c7000, 4096)
V/AudioCache(  321): memcpy(0xab70c000, 0xb17c7000, 4096)
V/AudioCache(  321): write(0xb17c7000, 4096)
V/AudioCache(  321): memcpy(0xab70d000, 0xb17c7000, 4096)
D/SiteAdvisor( 6276): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
V/AudioCache(  321): write(0xb17c7000, 4096)
V/AudioCache(  321): memcpy(0xab70e000, 0xb17c7000, 4096)
V/AudioCache(  321): write(0xb17c7000, 4096)
V/AudioCache(  321): memcpy(0xab70f000, 0xb17c7000, 4096)
V/AudioCache(  321): write(0xb17c7000, 4096)
V/AudioCache(  321): memcpy(0xab710000, 0xb17c7000, 4096)
V/AudioCache(  321): write(0xb17c7000, 4096)
V/AudioCache(  321): memcpy(0xab711000, 0xb17c7000, 4096)
V/AudioCache(  321): write(0xb17c7000, 4096)
V/AudioCache(  321): memcpy(0xab712000, 0xb17c7000, 4096)
V/AudioCache(  321): write(0xb17c7000, 4096)
V/AudioCache(  321): memcpy(0xab713000, 0xb17c7000, 4096)
V/AudioCache(  321): write(0xb17c7000, 4096)
V/AudioCache(  321): memcpy(0xab714000, 0xb17c7000, 4096)
V/AudioCache(  321): write(0xb17c7000, 4096)
V/AudioCache(  321): memcpy(0xab715000, 0xb17c7000, 4096)
V/AudioCache(  321): write(0xb17c7000, 4096)
V/AudioCache(  321): memcpy(0xab716000, 0xb17c7000, 4096)
V/AudioCache(  321): write(0xb17c7000, 4096)
V/AudioCache(  321): memcpy(0xab717000, 0xb17c7000, 4096)
V/AudioCache(  321): write(0xb17c7000, 4096)
V/AudioCache(  321): memcpy(0xab718000, 0xb17c7000, 4096)
V/AudioCache(  321): write(0xb17c7000, 4096)
V/AudioCache(  321): memcpy(0xab719000, 0xb17c7000, 4096)
V/AudioCache(  321): write(0xb17c7000, 4096)
V/AudioCache(  321): memcpy(0xab71a000, 0xb17c7000, 4096)
V/AudioCache(  321): write(0xb17c7000, 4096)
V/AudioCache(  321): memcpy(0xab71b000, 0xb17c7000, 4096)
V/AudioCache(  321): write(0xb17c7000, 4096)
V/AudioCache(  321): memcpy(0xab71c000, 0xb17c7000, 4096)
V/AudioCache(  321): write(0xb17c7000, 4096)
V/AudioCache(  321): memcpy(0xab71d000, 0xb17c7000, 4096)
V/AudioCache(  321): write(0xb17c7000, 4096)
D/SiteAdvisor( 6276): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
V/AudioCache(  321): memcpy(0xab71e000, 0xb17c7000, 4096)
V/AudioCache(  321): write(0xb17c7000, 4096)
V/AudioCache(  321): memcpy(0xab71f000, 0xb17c7000, 4096)
D/SiteAdvisor( 6276): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
,V/AudioCache(  321): write(0xb17c7000, 4096)
V/AudioCache(  321): memcpy(0xab720000, 0xb17c7000, 4096)
D/SiteAdvisor( 6276): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
D/SiteAdvisor( 6276): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
V/AudioCache(  321): write(0xb17c7000, 4096)
V/AudioCache(  321): memcpy(0xab721000, 0xb17c7000, 4096)
I/SiteAdvisor( 6276): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
V/AudioCache(  321): write(0xb17c7000, 4096)
V/AudioCache(  321): memcpy(0xab722000, 0xb17c7000, 4096)
V/AudioCache(  321): write(0xb17c7000, 4096)
V/AudioCache(  321): memcpy(0xab723000, 0xb17c7000, 4096)
V/AudioCache(  321): write(0xb17c7000, 4096)
V/AudioCache(  321): memcpy(0xab724000, 0xb17c7000, 4096)
V/AudioCache(  321): write(0xb17c7000, 4096)
V/AudioCache(  321): memcpy(0xab725000, 0xb17c7000, 4096)
V/AudioCache(  321): write(0xb17c7000, 4096)
V/AudioCache(  321): memcpy(0xab726000, 0xb17c7000, 4096)
V/AudioCache(  321): write(0xb17c7000, 4096)
V/AudioCache(  321): memcpy(0xab727000, 0xb17c7000, 4096)
,V/AudioCache(  321): write(0xb17c7000, 4096)
V/AudioCache(  321): memcpy(0xab728000, 0xb17c7000, 4096)
V/AudioCache(  321): write(0xb17c7000, 4096)
V/AudioCache(  321): memcpy(0xab729000, 0xb17c7000, 4096)
V/AudioCache(  321): write(0xb17c7000, 4096)
V/AudioCache(  321): memcpy(0xab72a000, 0xb17c7000, 4096)
V/AudioCache(  321): write(0xb17c7000, 4096)
,V/AudioCache(  321): memcpy(0xab72b000, 0xb17c7000, 4096)
V/AudioCache(  321): write(0xb17c7000, 4096)
V/AudioCache(  321): memcpy(0xab72c000, 0xb17c7000, 4096)
V/AudioCache(  321): write(0xb17c7000, 4096)
V/AudioCache(  321): memcpy(0xab72d000, 0xb17c7000, 4096)
V/AudioCache(  321): write(0xb17c7000, 4096)
V/AudioCache(  321): memcpy(0xab72e000, 0xb17c7000, 4096)
V/AudioCache(  321): write(0xb17c7000, 4096)
V/AudioCache(  321): memcpy(0xab72f000, 0xb17c7000, 4096)
V/OMXCodec(  321): [OMX.google.vorbis.decoder] No more output data.
V/AudioCache(  321): write(0xb17c7000, 4096)
V/AudioCache(  321): memcpy(0xab730000, 0xb17c7000, 4096)
V/OMXCodec(  321): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AudioCache(  321): write(0xb17c7000, 4096)
V/AudioCache(  321): memcpy(0xab731000, 0xb17c7000, 4096)
V/OMXCodec(  321): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/OMXCodec(  321): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  321): postAudioEOS() 
V/AudioCache(  321): write(0xb17c7000, 280)
V/AudioCache(  321): memcpy(0xab732000, 0xb17c7000, 280)
V/AwesomePlayer(  321): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  321): onStreamDone
D/SiteAdvisor( 6276): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
V/AwesomePlayer(  321): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  321): notify(0xb5474900, 2, 0, 0)
V/AudioCache(  321): playback complete
V/AwesomePlayer(  321): pause_l() 
V/AudioCache(  321): notify(0xb5474900, 7, 0, 0)
V/AudioCache(  321): ignored
V/AwesomePlayer(  321): cancelPlayerEvents
V/AudioCache(  321): wait - success
V/MediaPlayerService(  321): return size 205080, sampleRate=48000, channelCount = 2, format = 1
D/AudioPlayer(  321): Pause Playback at 1068125
V/AwesomePlayer(  321): reset_l() 
V/AudioCache(  321): notify(0xb5474900, 8, 0, 0)
V/AudioCache(  321): ignored
V/AwesomePlayer(  321): cancelPlayerEvents
D/AudioPlayer(  321): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  321): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  321): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  321): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  321): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  321): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7bf0 on port 0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc100 on port 1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c40 on port 1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ce0 on port 1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7d30 on port 1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer por,tIndex=1,bufIndex=0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  321): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  321): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  321): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  321): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  321): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  321): AudioPlayer releasing audio source
D/AudioPlayer(  321): AudioPlayer done releasing audio source
V/AwesomePlayer(  321): reset_l() 
V/AwesomePlayer(  321): cancelPlayerEvents
V/AwesomePlayer(  321): ~AwesomePlayer call
V/AwesomePlayer(  321): reset_l() 
V/AwesomePlayer(  321): cancelPlayerEvents
D/SiteAdvisor( 6276): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
V/SoundPool( 6331): close(31)
V/SoundPool( 6331): pointer = 0x9fe2a000, size = 205080, sampleRate = 48000, numChannels = 2
,D/QRemote ( 6331): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6331): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,D/QRemote ( 6331): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:7380
D/PostponalbeReceiver( 6276): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
,I/art     ( 1025): Explicit concurrent mark sweep GC freed 42615(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 1.178ms total 68.569ms
,I/UEI.SmartControl( 5915): Supports setup maps: true
,D/UEI.SmartControl( 5915): QS start statue = true Error code = 0
I/UEI.SmartControl( 5915): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 5915): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 5915): ### init IR Blaster...
D/serial_port( 5915): Configuring serial port
E/UEI.SmartControl( 5915): UEIBLaster setting for 616
I/UEI.SmartControl( 5915): Setting serial record hearder size = 2
I/UEI.SmartControl( 5915): configuring settings for MAXQ616
I/UEI.SmartControl( 5915): Get version...
D/UEI.SmartControl( 5915): serial port data available: 21
,D/UEI.SmartControl( 5915): MAXQ616 A2-X4 software.
,I/UEI.SmartControl( 5915): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 5915): QS saving settings...
D/UEI.SmartControl( 5915): IR Blaster version: 25672567
,D/UEI.SmartControl( 5915): serial port data available: 4
,I/UEI.SmartControl( 5915): Device manager: loading config....
,W/ContextImpl( 5915): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
D/UEI.SmartControl( 5915): ----------- loading internal config...
E/UEI.SmartControl( 5915): Services init done
D/UEI.SmartControl( 5915): QS Service init finished
D/UEI.SmartControl( 5915): QS Service version name: 2.1.91
D/UEI.SmartControl( 5915): QS Service version code: 201091
D/UEI.SmartControl( 5915): Service requested: Control
E/UEI.SmartControl( 5915): Loading SETTINGS...
D/UEI.SmartControl( 5915): Request IControl service: devices are loaded...
,D/UEI.SmartControl( 5915): Internal service binding...
I/QRemote ( 6331): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 5915): ------ IControl API: 11
D/UEI.SmartControl( 5915): File observer start...
E/UEI.SmartControl( 5915): IR Port is disabled: false
D/UEI.SmartControl( 5915): Starting file observer...
D/UEI.SmartControl( 5915): -- Open brand translation xml: brands_translations_ko
I/UEI.SmartControl( 5915): Registering callback...
I/UEI.SmartControl( 5915): ------ IControl API: 19
I/UEI.SmartControl( 5915): Registering Services Ready callback...
,I/UEI.SmartControl( 5915): Notify AllClients services are ready: 0
,D/UEI.SmartControl( 5915): -----service ready thread exits
I/QRemote ( 6331): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 6331): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 6331): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 6331): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 6331): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 5915): ------ IControl API: 8
,D/QRemote ( 6331): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 6331): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 6331): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 6331): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 6331): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6331): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 6331): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
V/QRemote ( 6331): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,D/QRemote ( 6331): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 6331): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6331): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 6331): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6331): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 6331): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
,I/wpa_supplicant( 6116): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1025): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1025): WifiMonitor:wlan0 cnt=13 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1025): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1025): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/QRemote ( 6331): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1454593073093]
D/QRemote ( 6331): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
I/ActivityManager( 1025): Killing 5585:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,D/QRemote ( 6331): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,W/libprocessgroup( 1025): failed to open /acct/uid_10080/pid_5585/cgroup.procs: No such file or directory
,V/QRemote ( 6331): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
E/QRemote ( 6331): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6331): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 6331): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 6331): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 6331): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 6331): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 6331): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,V/BluetoothOppNotification( 6089): new notify threadi!
V/BluetoothOppNotification( 6089): send delay message
,V/BluetoothOppProvider( 6089): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,V/BluetoothOppProvider( 6089): created cursor android.database.sqlite.SQLiteCursor@2801b981 on behalf of 
V/BluetoothOppNotification( 6089): mUpdateCompleteNotification = true
V/BluetoothOppProvider( 6089): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 6089): created cursor android.database.sqlite.SQLiteCursor@a077a26 on behalf of 
V/BluetoothOppNotification( 6089): outbound: succ-0  fail-0
V/BluetoothOppNotification( 6089): outbound notification was removed.
V/BluetoothOppProvider( 6089): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 6089): created cursor android.database.sqlite.SQLiteCursor@2bcac667 on behalf of 
V/BluetoothOppNotification( 6089): inbound: succ-0  fail-0
V/BluetoothOppNotification( 6089): inbound notification was removed.
V/BluetoothOppProvider( 6089): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,V/BluetoothOppProvider( 6089): created cursor android.database.sqlite.SQLiteCursor@8740c14 on behalf of 
E/wpa_supplicant( 6116): USIM:  scard_init function
I/wpa_supplicant( 6116): Trying to associate with SSID 'NG700'
,E/WifiMonitor( 1025): WifiMonitor:wlan0 cnt=14 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
,E/WifiMonitor( 1025): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1025): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1025): WifiMonitor:wlan0 cnt=15 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1025): couldn't identify event type - WPS-AP-AVAILABLE 
E/WifiStateMachine( 1025):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=2 known=0 got=2 bcn=0
D/WifiMonitor( 1025): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiStateMachine( 1025):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=2 known=0 got=2 bcn=0
E/WifiMonitor( 1025): WifiMonitor:wlan0 cnt=16 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1025):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=2 known=0 got=2 bcn=0
E/WifiStateMachine( 1025):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=2 known=0 got=2 bcn=0
I/WifiNative-HAL( 1025): startHal
E/wifi    ( 1025): getStaticLongField sWifiHalHandle 0x988bf8cc
E/WifiHAL ( 1025): Could not connect handle
D/wifi    ( 1025): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x602116
I/WifiNative-HAL( 1025): Could not start hal
D/WifiNative-wlan0( 1025): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1025):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 16 0 rt=115636  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
I/jxcore-log( 6035): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 6035): 
,I/StatusBar.NetworkController( 1465): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1465): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1025): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1025): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1025): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PostponalbeReceiver( 6276): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/StatusBar.NetworkController( 1465): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1465): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1025): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1025): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1025): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
E/WifiStateMachine( 1025):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 16 0 rt=115655  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
D/WifiServerServiceExt( 1025): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1025): setSupplicantStateASSOCIATING
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WiFiOffLoadBroadcast( 6115): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6115): MCCMNC not supported: null
D/QRemote ( 6331): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6331): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6331): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6276): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6115): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6115): MCCMNC not supported: null
,D/QRemote ( 6331): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6331): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6331): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/wpa_supplicant( 6116): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/WifiMonitor( 1025): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1025): WifiMonitor:wlan0 cnt=17 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1025): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1025): WifiMonitor:wlan0 cnt=18 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1025): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1025): WifiMonitor:wlan0 cnt=19 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1025):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 17 0 rt=115770  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1025):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 17 0 rt=115770  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1025):  DisconnectedState CMD_ASSOCIATED_BSSID 18 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=115771
E/WifiStateMachine( 1025):  ConnectModeState CMD_ASSOCIATED_BSSID 18 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=115771
E/WifiStateMachine( 1025):  DriverStartedState CMD_ASSOCIATED_BSSID 18 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=115771
E/WifiStateMachine( 1025):  SupplicantStartedState CMD_ASSOCIATED_BSSID 18 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=115772
,E/WifiStateMachine( 1025):  DefaultState CMD_ASSOCIATED_BSSID 18 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=115772
E/WifiStateMachine( 1025):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=115772  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
W/Settings( 1025): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1025): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1025): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/StatusBar.NetworkController( 1465): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1465): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PostponalbeReceiver( 6276): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/Tethering( 1025): sendTetherStateChangedBroadcast 1, 0, 0
E/WifiStateMachine( 1025):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=115779  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
,I/wpa_supplicant( 6116): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 6116): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1025): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1025): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1025): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1025): WifiMonitor:wlan0 cnt=21 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1025): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1025): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1025): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1025): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1025): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1025): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/StatusBar.NetworkController( 1465): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1465): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1025): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1025): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1025): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/WifiServerServiceExt( 1025): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1025): setSupplicantStateASSOCIATED
D/libc-netbsd(  316): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1025): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiServerServiceExt( 1025): SUPPLICANT_STATE_CHANGED_ACTION
,D/WifiServerServiceExt( 1025): setSupplicantStateFOUR_WAY_HANDSHAKE
V/WiFiOffLoadBroadcast( 6115): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 1025):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 20 0 rt=115793  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1025):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 20 0 rt=115794  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1025):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=115795
E/WifiStateMachine( 1025):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=115795
D/WifiNative-wlan0( 1025): doString: [STATUS]
D/WifiMonitor( 1025): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1025): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1025):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
I/WifiServiceExtension( 1025): setVHTCapabilityType  : false
D/WiFiOffLoadBroadcast( 6115): MCCMNC not supported: null
D/QRemote ( 6331): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6331): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6331): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/WifiServerServiceExt( 1025): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1025): setKeepAlivePacketInterval msec : 60
,D/PostponalbeReceiver( 6276): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/Settings( 1025): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1025): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1025): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/StatusBar.NetworkController( 1465): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1465): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1025): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1025): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1025): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1465): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1465): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming,
V/WiFiOffLoadBroadcast( 6115): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/ConnectivityService( 1025): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService( 1025): Got NetworkAgent Messenger
D/ConnectivityService( 1025): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1025): NetworkAgent connected
D/WiFiOffLoadBroadcast( 6115): MCCMNC not supported: null
E/WifiConfigStore( 1025): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1025): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1025): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1025): doBoolean: SAVE_CONFIG
,D/QRemote ( 6331): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6331): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6331): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/WifiNative-wlan0( 1025): SAVE_CONFIG: returned true
E/WifiConfigStore( 1025): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1025): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1025): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1025): doBoolean: SAVE_CONFIG
I/CloudHub( 2179): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19983
D/UsbSettingsReceiver( 6115): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6115): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6115): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6115): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6115): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 6115): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6115): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6115): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6115): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6115): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6115): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 6115): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6276): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,D/WifiNative-wlan0( 1025): SAVE_CONFIG: returned true
D/CommandListener(  316): Setting iface cfg
V/WiFiOffLoadBroadcast( 6115): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 1025): Start Dhcp Watchdog 1
,E/WifiStateMachine( 1025):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=115852  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/DhcpStateMachine( 1025): StoppedState
D/DhcpStateMachine( 1025): StoppedState{ when=-2ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1025): WaitBeforeStartState
E/WifiStateMachine( 1025):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=115853  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1025):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=115854  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1025):  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1025):  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1025):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1025):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1025):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1025):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiServerServiceExt( 1025): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1025): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1025):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=115859  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1025):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=115859  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1025):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=115860  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1025):  ObtainingIpState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:-1400837905] from screen [on:0 period:-1400837905]
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1400837904]
D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
D/WiFiOffLoadBroadcast( 6115): MCCMNC not supported: null
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1025): updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,E/WifiStateMachine( 1025):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1025):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1025):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1025):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1025):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1025):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/QRemote ( 6331): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6331): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService( 1025): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
I/QRemote ( 6331): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
E/WifiStateMachine( 1025):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
E/WifiStateMachine( 1025):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
D/WifiNative-wlan0( 1025): doBoolean: DRIVER SETSUSPENDMODE 0
D/PostponalbeReceiver( 6276): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6115): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6115): MCCMNC not supported: null
D/QRemote ( 6331): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6331): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6331): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/wpa_supplicant( 6116): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
,D/WifiNative-wlan0( 1025): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1025): doBoolean: SET ps 0
D/WifiNative-wlan0( 1025): SET ps 0: returned true
D/WifiNative-wlan0( 1025): doBoolean: DRIVER BTCOEXMODE 1
,I/wpa_supplicant( 6116): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1025): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1025): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
D/LGWifiP2pService( 1025): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@71c2ba9 target=com.android.internal.util.StateMachine$SmHandler }
V/DhcpStateMachine( 1025): Current State is mWaitBeforeStartState.
D/LGWifiP2pService( 1025): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@71c2ba9 target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper( 1025): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
V/LgDhcpStateMachineHelper( 1025): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700" is not exist.
D/DhcpStateMachine( 1025): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1025): DHCP Start wake lock is acquired.
D/WifiServerServiceExt( 1025): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1025): setSupplicantStateCOMPLETED
D/WifiServerServiceExt( 1025): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1025): setSupplicantStateCOMPLETED
D/DhcpStateMachine( 1025): DHCPV4 request on wlan0
,V/LgDhcpStateMachineHelper( 1025): [bssid] hash key :c0:ff:d4:d3:aa:48
,D/LgDhcpStateMachineHelper( 1025): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
W/dhcpcd  ( 6409): type=1400 audit(0.0:163): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 6409): type=1400 audit(0.0:164): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,I/dhcpcd  ( 6409): version 5.5.6 starting
,E/dhcpcd  ( 6409): get_duid: m
D/dhcpcd  ( 6409): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 6409): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,D/dhcpcd  ( 6409): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 6409): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 6409): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,I/jxcore-log( 6035): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 6035): 
I/dhcpcd  ( 6409): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 6409): wlan0: sending REQUEST (xid 0x44579c59), next in 3.49 seconds
I/jxcore-log( 6035): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 6035): 
,I/jxcore-log( 6035): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
I/jxcore-log( 6035): 
I/jxcore-log( 6035): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 6035): 
E/WifiStateMachine( 1025):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1025):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1025):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1025):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 1025):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1025):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1025): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
I/dhcpcd  ( 6409): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
,I/dhcpcd  ( 6409): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 6409): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 6409): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 6409): wlan0: adding default route via 192.168.1.1
E/WifiStateMachine( 1025):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
D/dhcpcd  ( 6409): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
E/WifiStateMachine( 1025):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1025):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1025):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/dhcpcd  ( 6409): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
E/WifiStateMachine( 1025):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/dhcpcd  ( 6409): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
E/WifiStateMachine( 1025):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/dhcpcd  ( 6409): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
D/ConnectivityService( 1025): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
,W/ProcessCpuTracker( 1025): Skipping unknown process pid 6425
,D/DhcpStateMachine( 1025): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper( 1025): CheckDhcpDirectory [Lease File Count] : 3
,V/LgDhcpStateMachineHelper( 1025): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1025): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1025): Add DhcpResults: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
V/DhcpStateMachine( 1025): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1025): bShouldSendDhcpAction Result: true
D/DhcpStateMachine( 1025): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1025): RunningState
E/WifiStateMachine( 1025):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine( 1025):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/LGWifiP2pService( 1025): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1025): doBoolean: DRIVER BTCOEXMODE 2
D/LGWifiP2pService( 1025): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 6116): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1025): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1025): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 6116): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1025): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1025): doBoolean: SET ps 1
D/WifiNative-wlan0( 1025): SET ps 1: returned true
,D/ConnectivityService( 1025): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
E/WifiStateMachine( 1025):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1025):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1025): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1025): ignoring duplicate network state non-change
W/Settings( 1025): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1025): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1025): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/StatusBar.NetworkController( 1465): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1465): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/StatusBar.NetworkController( 1465): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1465): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService( 1025): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1025): Adding iface wlan0 to network 100
W/Settings( 1025): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1025): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1025): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
E/WifiStateMachine( 1025): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/WifiHS20( 1025): [PASSPOINT] passpointNotification: hs20AP list is checked
D/PostponalbeReceiver( 6276): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WfdStateTracker( 1928): handleWifiStateChangedEvent: 1
I/StatusBar.NetworkController( 1465): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1465): mWifiConnected = true, mWifiLevel = 2
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
,W/Settings( 1025): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1025): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1025): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20( 1025): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings( 1025): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1025): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1025): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
E/ConnectivityService( 1025): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1025): Adding Route [fe80::/64 -> :: wlan0] to network 100
D/ConnectivityService( 1025): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,D/ConnectivityService( 1025): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
D/ConnectivityService( 1025): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1025): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 100
D/ConnectivityService( 1025): Setting Dns servers for network 100 to [/192.168.1.1]
D/Nat464Xlat( 1025): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1025): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1025): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1025): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1025):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1025):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1025):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1025):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1025):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1025): currentScore = 0, newScore = 20
D/ConnectivityService( 1025):    accepting network in place of null
D/ConnectivityService( 1025): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1025): Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1025): DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1025): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1025): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1025): Checking http://clients3.google.com/generate_204 on "NG700"
D/TelephonyNetworkFactory-1( 1839): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1025): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1025):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1839):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
I/StatusBar.NetworkController( 1465): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1465): mWifiConnected = true, mWifiLevel = 2
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
,E/ConnectivityService( 1025): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1025): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
V/WiFiOffLoadBroadcast( 6115): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/ConnectivityService( 1025): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1025): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1025): [e] list.add(nai) empty : false size: 1
D/LocSvc_java( 1025): Sending msg: 4 arg1:1 arg2:1
D/libc-netbsd(  316): res_queryN name = clients3.google.com, class = 1, type = 28
D/LocSvc_java( 1025): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1025): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1025): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java( 1025): Sending msg: 5 arg1:0 arg2:1
D/ConnectivityService( 1025): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/libc-netbsd(  316): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  316): res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
D/libc-netbsd(  316): res_queryN name = 2.android.pool.ntp.org., class = 1, type = 1
D/DSQN    ( 1025): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/ConnectivityService( 1025): validation of new default Network = false
D/ConnectivityService( 1025): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1025): enableDataServiceNotify 
,D/DSQN    ( 1025): start dsqn bin
D/libc-netbsd(  316): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  316): res_queryN name = europe.pool.ntp.org, class = 1, type = 1
D/ConnectivityService( 1025): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1025):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1025):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1025): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1465): CM callback handler got msg 524290
,W/dsqn    ( 6454): type=1400 audit(0.0:165): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 6454): type=1400 audit(0.0:166): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
V/NetworkPolicy( 1025): [LG_RESTRICTED] checkMobilePolicy_type()
D/WiFiOffLoadBroadcast( 6115): MCCMNC not supported: null
E/DSQN    ( 6454): DSQN ssw
,D/libc-netbsd(  316): res_queryN name = clients3.google.com, class = 1, type = 1
,D/TelephonyIcons( 1465): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
D/QRemote ( 6331): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6331): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6331): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6276): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,D/libc-netbsd(  316): res_queryN name = clients3.google.com succeed
,V/WiFiOffLoadBroadcast( 6115): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6115): MCCMNC not supported: null
D/QRemote ( 6331): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6331): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6331): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6276): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 6221): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/libc-netbsd(  316): res_queryN name = europe.pool.ntp.org succeed
D/LGDataListener(  316): argv[0]=dsqncommand
D/LGDataListener(  316): argv[1]=wlan0
D/LGDataListener(  316): argv[2]=1
D/LGDataListener(  316): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1025): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1025): start to monitor internet connection
D/PCSuite ( 6221): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6115): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6115): MCCMNC not supported: null
D/QRemote ( 6331): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6331): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6331): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6331): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6331): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1025): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 04 Feb 2016 13:37:57 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454593077572], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454593077551]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1025): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1025): Validated
D/PostponalbeReceiver( 6276): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/ConnectivityService( 1025): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1025): rematching NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService( 1025):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1025):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1025):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1025): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService( 1025): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1025):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1025):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1025): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1025): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1025): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    ( 1025): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1025):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1839): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1465): CM callback handler got msg 524290
D/TelephonyNetworkFactory-1( 1839):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
I/PCSuite ( 6221): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6221): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6115): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6115): MCCMNC not supported: null
D/QRemote ( 6331): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6331): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6331): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6331): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6331): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,D/TelephonyIcons( 1465): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
D/LocSvc_java( 1025): NTP server : europe.pool.ntp.org
D/LocSvc_java( 1025): NTP server returned: 1454593078038 (Thu Feb 04 14:37:58 GMT+01:00 2016) reference: 118041 certainty: 33 system time offset: 420
D/LocSvc_java( 1025): Sending msg: 10 arg1:0 arg2:1
,D/LocSvc_java( 1025): reportXtraServer 
D/LocSvc_java( 1025):  server1=http://xtra3.gpsOneXTRA.net/xtra2.bin
D/LocSvc_java( 1025):  server2=http://xtra2.gpsOneXTRA.net/xtra2.bin
D/LocSvc_java( 1025):  server3=
D/LocSvc_java( 1025): xtraDownloadRequest
D/LocSvc_java( 1025): Sending msg: 6 arg1:0 arg2:1
,D/libc-netbsd(  316): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  316): res_queryN name = xtra3.gpsOneXTRA.net, class = 1, type = 1
D/UEI.SmartControl( 5915): Internal timer expired: 4
D/UEI.SmartControl( 5915): unbind internal service
,D/serial_port( 5915): close(fd = 24)
I/UEI.SmartControl( 5915): Serial port is closed.
D/libc-netbsd(  316): res_queryN name = xtra3.gpsOneXTRA.net succeed
,D/LocSvc_java( 1025): calling native_inject_xtra_data
,D/LocSvc_java( 1025): Sending msg: 11 arg1:0 arg2:1
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1400834896] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1400834895] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/PowerManagerServiceEx( 1025): acquireWakeLockInternal: lock=1033378170, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1025
,V/QRemote ( 6331): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
D/QRemote ( 6331): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:7380
,D/[Concierge]Service( 2576): onStartCommand(). Type : 9
I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
D/PowerManagerServiceEx( 1025): releaseWakeLockInternal: lock=1033378170 [*alarm*], flags=0x0
,V/WifiInternetCheck( 1025): Single check msg out of sync, ignoring.
,D/ConnectivityService( 1025): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1025): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1025): MasterInitialState.processMessage what=3
D/PostponalbeReceiver( 6276): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
D/libc-netbsd(  316): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  316): res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
W/ContextImpl( 6276): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkMonitor( 5266): type=WIFI subType= reason=null isConnected=true
,D/libc-netbsd(  316): res_queryN name = 2.android.pool.ntp.org succeed
D/AlarmManagerService( 1025): Setting time of day to sec=1454593080
,W/AlarmManagerService( 1025): Unable to set rtc to 1454593080: Invalid argument
I/ActivityManager( 1025): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6493 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/LIA_Informant_Tips_DateChangeManager( 3567): onReceive() : ACTION_TIME_CHANGED
I/art     (  349): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 446us total 25.273ms
,I/LIA_Informant_Tips_LogTracer( 3567): [Log Tracer - Schedule Transition] Time Change Event Received : 2016-02-04 14:38:00...... Request
I/LIA_Informant_Tips_LogTracer( 3567): [Log Tracer - Schedule Transition] UserGuide, DATE_UPDATE : working count : 8, total count : 165, new day : false...... Request
D/LIA_Informant_Tips_DateChangeManager( 3567): DateInfo : SmartTips Total Working Day Count = 165
D/LIA_Informant_Tips_DateChangeManager( 3567): DateInfo : UserGuide Working Duration Count = 8
D/LIA_Informant_Tips_DateChangeManager( 3567): DateInfo : Last Date Check Time = 2016-02-04 14:38:00
I/CalendarProvider2( 4586): onReceive() android.intent.action.TIME_SET
D/CalendarProvider2( 4586): Scheduling check of next Alarm
D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
I/[SystemUI]Clock( 1465): onReceive = android.intent.action.TIME_SET
I/LgeClockWidgetControlView( 1465): time changed, timezoneChanged : false
I/SecureClockService( 1928): Intent.ACTION_TIME_CHANGED 
,W/ActivityManager( 1025): getTasks: caller 10029 is using old GET_TASKS but privileged; allowing
I/[LGHome]LGDateChangeReceiver( 2020): [LGDateChangeReceiver.java:78:updateCalendarShortcut()]date=4 currentDate=-1 dayofweek=5 currentDayOfWeek=-1
,I/[LGHome]LGCalendarIcon( 2020): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Thu date= 4
I/[LGHome]LGCalendarIcon( 2020): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Thu date= 4
I/[LGHome]Launcher( 2020): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/art     (  349): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 407us total 20.102ms
I/art     (  349): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 401us total 17.813ms
,D/[Concierge]Service( 2576): onStartCommand(). Type : 9
,I/ActivityManager( 1025): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=6514 uid=10054 gids={50054, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/AppUp4:AppBoxCP( 6493): onCreate
W/AppUp4:DB( 6493):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 6493):  setFingerPrint start
I/AppUp4:DB( 6493):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 6493):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 6493):  SDK version = 21
I/AppUp4:DB( 6493):  beforefinger == newfinger no write in DB
,I/ActivityManager( 1025): Start proc com.android.gallery3d for service com.android.gallery3d/com.lge.gallery.picasa.PicasaService: pid=6533 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
D/AppUp4:AppBoxApplication( 6493): AppBoxApplication onCreate()
,I/NetworkStateForAutoUpdateMonitor( 6493): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6493): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6493): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6493): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6493): onReceive
,W/ResourcesManager( 6533): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6533): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6533): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 6533): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,D/LgDataFeature( 6493): LgDataFeature() Constructor: none
D/LgDataFeature( 6493): LgDataFeature() Constructor Done, null
D/AppUp4:CustFacade( 6493): Context : android.app.ReceiverRestrictedContext@1a9abb9a
D/AppUp4:CustFacade( 6493): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6493): isPhone : true
D/AppUp4:CustModeStarterReceiver( 6493): begin check event
I/AppUp4:CustModeStarterReceiver( 6493): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6493): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,D/AppUp4:CustModeStarterReceiver( 6493): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6493): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6493): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1025): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=6552 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/LGDMClient( 4006): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4006): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
D/GpsLocationProvider( 1025): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/AppConfig( 6533): Total System Memory = 2995761152
,W/ContextImpl( 4006): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/SystemHelper( 6533): region [EU], country [EU], operator [OPEN], sub-operator []
W/ContextImpl( 4006): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3359): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3359): DownloadService onCreate
I/DownloadManager( 3359): in removeSpuriousFiles
D/LGDMClient( 4006): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/DownloadManager( 3359): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,I/LGDMClient( 4006): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
D/LGDMClient( 4006): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4006): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 3359): created cursor android.database.sqlite.SQLiteCursor@24f856a1 on behalf of 3359
I/DownloadManager( 3359): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3359): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3359): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3359): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3359): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
,I/DownloadManager( 3359): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3359): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3359): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3359): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3359): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3359): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/DownloadManager( 3359): in trimDatabase
V/DownloadManager( 3359): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3359): created cursor android.database.sqlite.SQLiteCursor@9a820c6 on behalf of 3359
I/ActivityManager( 1025): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6578 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,V/DownloadManager( 3359): DownloadService onStartCommand
V/DownloadManager( 3359): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
W/ContextImpl( 4006): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 4006): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4006): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4006): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3359): created cursor android.database.sqlite.SQLiteCursor@36d4a3b4 on behalf of 3359
,V/DownloadManager( 3359): processing inserted download 1
V/DownloadManager( 3359): processing inserted download 4
V/DownloadManager( 3359): processing inserted download 7
V/DownloadManager( 3359): processing inserted download 8
V/DownloadManager( 3359): processing inserted download 9
V/DownloadManager( 3359): processing inserted download 10
V/DownloadManager( 3359): processing inserted download 16
V/DownloadManager( 3359): processing inserted download 17
V/DownloadManager( 3359): processing inserted download 18
V/DownloadManager( 3359): processing inserted download 21
V/DownloadManager( 3359): processing inserted download 22
E/GpsLocationProvider( 1025): No APN found to select.
,V/DownloadManager( 3359): DownloadService onDestroy
,W/ResourcesManager( 6578): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6578): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6578): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6578): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,I/ActivityManager( 1025): Killing 5610:com.google.android.apps.plus/u0a97 (adj 15): empty #17
I/ThermalEngine(  330): Thermal-Server: Thermal received msg from  override
I/Thermal-Lib( 2965): Thermal-Lib-Client: Client request sent
,W/libprocessgroup( 1025): failed to open /acct/uid_10097/pid_5610/cgroup.procs: No such file or directory
,I/LGEmail ( 6578): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,I/ReaderUtils( 6514): PortraitW 1440 LandscapeW 2392 SmallestSize 1340 LargestSize 2392 textZoom 4.4999995 isTablet false Memory 256
D/DelayedSyncController( 6552): Delaying sync.
,D/LGEmail ( 6578): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
I/ActivityManager( 1025): Killing 5894:com.lge.eula/1000 (adj 15): empty #17
,W/ResourceType( 6578): No package identifier when getting value for resource number 0x00000000
,W/libprocessgroup( 1025): failed to open /acct/uid_1000/pid_5894/cgroup.procs: No such file or directory
,W/GAV2    ( 6514): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/LgDataFeature( 6578): LgDataFeature() Constructor: none
,D/LgDataFeature( 6578): LgDataFeature() Constructor Done, null
I/art     ( 2057): Explicit concurrent mark sweep GC freed 18039(1013KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 30MB/62MB, paused 588us total 20.140ms
I/BooksApp( 6514): Created application version: 3.2.35 (30235)
,E/Auth.Api.Credentials( 2303): [CredentialSyncAdapter] Unknown sync event.
W/DriveInitializer( 2303): Background init thread started
,W/DriveInitializer( 2303): Awaiting to be initialized
E/VoldCmdListener(  281): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  281): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.gms/files/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 2303): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.gms/files
,I/BooksSync( 6514): Starting books sync
D/eas_req ( 6578): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/HubEmail( 6578): JNI_OnLoad()
I/HubEmail( 6578): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6578): registerNatives()
I/HubEmail( 6578): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6578): registerNativeMethods()
I/HubEmail( 6578): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6578): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
W/DriveInitializer( 2303): Background init thread ended
,W/Settings( 6578): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/jxcore-log( 6035): Test app app.js loaded
I/jxcore-log( 6035): 
W/Settings( 6578): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/chromium( 6035): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
I/LgeMiscReceiver( 3294): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3294): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 3294): networkInfo.isConnected() = true
D/PhoneState( 3294): setPdpRejectCasuse : false
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6035): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6035): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6035): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6035): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6035): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6035): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6035): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6035): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6035): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6035): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@229cee45 added. We now have 1 listener(s)
I/jxcore-log( 6035): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 6035): 
E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=28.8, 0.0, 0.0  rx=26.5 bcn=0 [on:0 tx:0 rx:0 period:3411] from screen [on:0 period:-1400831476] gl rssi=-60 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=28.8, 0.0, 0.0  rx=26.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1400831475] gl rssi=-60 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
I/ActivityManager( 1025): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6635 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,D/libc-netbsd(  316): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  316): res_queryN name = static-avc.lglime.com, class = 1, type = 1
,D/BooksSync( 6514): started syncMyEbooks
,D/DrmBroadcastReceiver( 6635): Receive CONNECTIVITY_ACTION
D/DrmBroadcastReceiver( 6635): 1  network is available. Sync DRM Time with NTP
V/DrmService( 6635): Service onCreate
D/DrmService( 6635): Received new request = 2
,I/DrmSntpClient( 6635): Start Sync process
D/DrmSntpClient( 6635): Server : 0
D/libc-netbsd(  316): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  316): res_queryN name = pool.ntp.org, class = 1, type = 1
I/ActivityManager( 1025): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=6660 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd(  316): res_queryN name = static-avc.lglime.com succeed
,V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 6660): Almond Protected OAT
V/FormManager( 6164): There are no updated forms. The schedule will be deleted.
V/FormManager( 6164): Alarm would be updated, because LastCheckTime has been updated.
I/GLSUser ( 2057): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2057): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2057): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2057): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/libc-netbsd(  316): res_queryN name = pool.ntp.org succeed
V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/libc-netbsd(  316): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  316): res_queryN name = www.google.com, class = 1, type = 1
I/ActivityManager( 1025): Killing 5435:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
,I/LGDrmClient( 6635): _DRM_ServiceGet() : Bind lgdrm service
,V/ILGDrmService(  326): eDRM_SetDRMTime +++
,I/LGDRM   (  326): [DRM] SET TIME : YR=2016, MON=2, DAY=4
I/LGDRM   (  326): [DRM] SET TIME : HR=13, MIN=38, SEC=2
V/ILGDrmService(  326): eDRM_SetDRMTime ---
I/DrmSntpClient( 6635): Synched
D/DrmService( 6635): Completed !! request = 2
D/DrmService( 6635): Request count = 0
D/libc-netbsd(  316): res_queryN name = www.google.com succeed
D/libc-netbsd(  316): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  316): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  316): res_queryN name = clients3.google.com succeed
,W/libprocessgroup( 1025): failed to open /acct/uid_10005/pid_5435/cgroup.procs: No such file or directory
,V/DrmService( 6635): Service onDestroy
,D/WeatherApplication( 6660): removeAccount
D/WeatherApplication( 6660): Account.length = 0
I/ActivityManager( 1025): Killing 4586:com.android.providers.calendar/u0a14 (adj 15): empty #17
E/WeatherApplication( 6660): OPERATOR:OPEN
D/WeatherAncestor( 6660): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:38:2
V/WifiInternetCheck( 1025): isHttpConnectionAvailable - We got a valid response : 204
D/Weather.Utils( 6660): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6660): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6660): 2 : This is isUpdating : false
D/WeatherAncestor( 6660): connectivity changed - connection : true
D/WeatherService( 6660): 2 : isServiceAlived():false forecastCache:null
,I/art     ( 1025): Explicit concurrent mark sweep GC freed 64175(3MB) AllocSpace objects, 5(120KB) LOS objects, 33% free, 43MB/65MB, paused 4.036ms total 99.352ms
,V/NotificationService( 1025): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/ForecastDataCache( 6660): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 6660): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 6660): 2 : Cache is not up-to-date, count: 0
D/ZenLog  ( 1025): intercepted: 0|com.google.android.gms|1|null|10005,none
V/NotificationService( 1025): pkg=com.google.android.gms canInterrupt=false intercept=true
W/GLSActivity( 2057): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2057): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2057): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2057): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2057): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2057): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2057): 	at android.os.Binder.execTransact(Binder.java:446)
D/Weather_cast( 6660): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 6660): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:38:2
,W/libprocessgroup( 1025): failed to open /acct/uid_10014/pid_4586/cgroup.procs: No such file or directory
I/NotificationServiceEx( 1025): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1025): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1025): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,E/BooksAccountManager( 6514): Authentication error
E/BooksAccountManager( 6514): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6514): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6514): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6514): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6514): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6514): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6514): null auth token
D/libc-netbsd(  316): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  316): res_queryN name = www.googleapis.com, class = 1, type = 1
W/ResourcesManager( 1411): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1465): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1411): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager( 1465): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/LgeQuickCoverNLService( 1411): onNotificationPosted
I/ActivityManager( 1025): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6686 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1025): Killing 2179:com.lge.music/u0a34 (adj 15): empty #17
,D/libc-netbsd(  316): res_queryN name = www.googleapis.com succeed
V/AudioFlinger(  321): 2179 died, releasing its sessions
V/AudioFlinger(  321):  pid 1839 @ 0
V/AudioFlinger(  321):  pid 3294 @ 1
V/AudioFlinger(  321):  pid 3294 @ 2
,W/libprocessgroup( 1025): failed to open /acct/uid_10034/pid_2179/cgroup.procs: No such file or directory
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
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{19c16502 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2057): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 2057): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2057): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2057): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/VoldCmdListener(  281): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  281): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6686): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  281): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  281): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6686): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
V/NotificationService( 1025): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
E/VoldCmdListener(  281): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  281): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6686): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
V/NotificationService( 1025): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1025): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1025): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1025): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2057): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2057): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2057): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2057): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2057): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2057): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2057): 	at android.os.Binder.execTransact(Binder.java:446)
E/VoldCmdListener(  281): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  281): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6686): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
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
D/SyncManager( 1025): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 26822, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager( 1025): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 153335, reason: 10019
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{19c16502 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/DelayedSyncController( 6552): Delaying sync.
,I/WebViewFactory( 6686): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 6686): Loading: webviewchromium
I/LibraryLoader( 6686): Time to load native libraries: 2 ms (timestamps 2396-2398)
I/LibraryLoader( 6686): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6686): Binding Chromium to main looper Looper (main, tid 1) {2d929d6d}
I/LibraryLoader( 6686): Expected native library version number "",actual native library version number ""
I/chromium( 6686): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,W/ApiaryClient( 6514): Error response from books API: {
W/ApiaryClient( 6514):  "error": {
W/ApiaryClient( 6514):   "errors": [
W/ApiaryClient( 6514):    {
W/ApiaryClient( 6514):     "domain": "global",
W/ApiaryClient( 6514):     "reason": "required",
W/ApiaryClient( 6514):     "message": "Login Required",
W/ApiaryClient( 6514):     "locationType": "header",
W/ApiaryClient( 6514):     "location": "Authorization"
W/ApiaryClient( 6514):    }
W/ApiaryClient( 6514):   ],
W/ApiaryClient( 6514):   "code": 401,
W/ApiaryClient( 6514):   "message": "Login Required"
W/ApiaryClient( 6514):  }
W/ApiaryClient( 6514): }
W/ApiaryClient( 6514): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6514): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-5576565517851262965&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6514): Headers:
W/ApiaryClient( 6514): accept-encoding: [gzip]
W/ApiaryClient( 6514): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6514): gdata-version: 2
I/BrowserStartupController( 6686): Initializing chromium process, renderers=0
W/art     ( 6686): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6686): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 6686): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 6686): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
V/AudioPolicyService(  321): registerClient() client 0xb101eca0, uid 10093
W/AudioManagerAndroid( 6686): Requires BLUETOOTH permission
I/Adreno-EGL( 6686): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6686): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6686): Build Date: 12/12/14 금
I/Adreno-EGL( 6686): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6686): Remote Branch: 
I/Adreno-EGL( 6686): Local Patches: 
I/Adreno-EGL( 6686): Reconstruct Branch: 
I/NSApplication( 6686): Starting up...
,I/ActivityManager( 1025): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6744 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1025): Killing 4891:com.android.vending/u0a44 (adj 15): empty #17
W/libprocessgroup( 1025): failed to open /acct/uid_10044/pid_4891/cgroup.procs: No such file or directory
,W/ResourcesManager( 6744): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/libc-netbsd(  316): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  316): res_queryN name = mtalk.google.com, class = 1, type = 1
,I/iu.SyncManager( 2303): SYNC; picasa accounts
,I/GLSActivity( 2057): [ac] getting account id
,I/GLSUser ( 2057): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
D/NetworkLogImpl( 2303): Loaded NetworkSpeedPredictor
I/iu.Environment( 2303): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/iu.UploadsManager( 2303): num queued entries: 0
I/iu.UploadsManager( 2303): num updated entries: 0
,I/iu.SyncManager( 2303): NEXT; no task
D/ChimeraCfgMgr( 2303): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/libc-netbsd(  316): res_queryN name = mtalk.google.com succeed
D/ChimeraCfgMgr( 2303): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PostponalbeReceiver( 6276): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.TIME_SET'.
I/ActivityManager( 1025): Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=6786 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/GLSUser ( 2057): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2057): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2057): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2057): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ALBootInit( 6786): ====action==>android.intent.action.TIME_SET
,D/ALBootInit( 6786): Alarm ALBootInit: TIME_SET
D/Alarms  ( 6786): [setNextAlert] start
V/NotificationService( 1025): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1025): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1025): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1025): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1025): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1411): onNotificationPosted
D/Alarms  ( 6786): [setNextAlert] (1)
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
,D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
W/Kids    ( 2303): [AccountUtils] Account not ready
W/Kids    ( 2303): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2303): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2303): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2303): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2303): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2303): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2303): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2303): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2303): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2303): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2303): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2303): 	at java.lang.Thread.run(Thread.java:818)
E/LgeQuickCoverOverlayWindow( 1411): updateNotificationData: count=3
D/Alarms  ( 6786):  minTime  = 0
D/Alarms  ( 6786):  -- OK multi -- 0
E/jeny.kim( 6786): [setNextAlert] setNextAlert  temp_Alarmlink + 
E/jeny.kim( 6786): [setNextAlert]setNextAlert temp_AlarmLinkText + 
I/CommonUtil( 6786): BUILD Country: EU
,D/Alarms  ( 6786): broadcastToWidgetProvider : false
D/Alarms  ( 6786): Enter formatDayAndTime(final Context context, long timeInMiliSec)
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{19c16502 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
V/SettingsProvider( 1025): call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
,I/DigitalAppWidgetProvider( 6786): onReceive: android.intent.action.TIME_SET
V/DigitalAppWidgetProvider( 6786): cancelAlarmOnQuarterHour android.app.ReceiverRestrictedContext@2c26fccb
V/DigitalAppWidgetProvider( 6786): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@2c26fccb
D/QuickCoverProvider( 6786): onReceiver
I/indal   ( 1411): SmartCoverWidgetContext createApplicationContext
I/indal   ( 1411): SmartCoverWidgetContext createApplicationContext
D/WeatherAncestor( 6660): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 14:38:2
,D/Weather.Utils( 6660): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6660): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6660): 2 : This is isUpdating : false
D/WeatherService( 6660): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3da1aca8
D/ForecastDataCache( 6660): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 6660): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 6660): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 6660): 2 : set auto-update time : 2/4 17:38
D/WeatherAncestor( 6660): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 14:38:2
D/GCM     ( 2057): Connected
I/ActivityManager( 1025): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=6824 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,I/ActivityManager( 1025): Killing 6254:com.lge.settings.easy/1000 (adj 15): empty #17
,W/libprocessgroup( 1025): failed to open /acct/uid_1000/pid_6254/cgroup.procs: No such file or directory
,D/GCM     ( 2057): Message class com.google.f.a.a.p
D/TimeService( 6824): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1454593083075
,D/        ( 6824): TimeServiceNative: User Time to be set is 1454593083075
D/QC-time-services( 6824): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 6824): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 6824): Lib:time_genoff_operation: pargs->ts_val = 1454593083075
D/QC-time-services(  382): Daemon: Connection accepted:time_genoff
D/QC-time-services( 6824): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  382): Daemon:Received base = 2, unit = 1, operation = 0,value = 1454593083075
D/QC-time-services(  382): Daemon:genoff_opr: Base = 2, val = 1454593083075, operation = 0
D/QC-time-services(  382): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS5/14/70 6:50:9
D/QC-time-services(  382): Daemon:Value read from RTC seconds = 14194209000
D/QC-time-services(  382): Daemon:new time 1454593083075 
D/QC-time-services(  382): Daemon: delta 1440398874075 genoff 1440398874075 
D/QC-time-services(  382): Daemon:genoff_persistent_update: Writing genoff = 1440398874075 to memory
D/QC-time-services(  382): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  382): Daemon:time_persistent_memory_opr:Genoff write operation 
D/QC-time-services(  382): Updating the TOD offset
D/QC-time-services(  382): Daemon:genoff_persistent_update: Writing genoff = 1440398874075 to memory
D/QC-time-services(  382): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  382): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services(  382): Daemon:Update to modem bit set
,D/QC-time-services(  382): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  382): Daemon: Base = 2, Value being sent to MODEM = 1124434074075
E/QC-time-services( 6824): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
E/QC-time-services(  382): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
E/QC-time-services(  382): Daemon: Time-services: Waiting to acceptconnection
I/ActivityManager( 1025): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetProvider: pid=6845 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi
I/ActivityManager( 1025): Killing 5940:com.lge.bnr/1000 (adj 15): empty #17
,I/art     (  349): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 437us total 24.519ms
,I/art     (  349): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 419us total 19.271ms
,I/art     (  349): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 415us total 19.162ms
,W/libprocessgroup( 1025): failed to open /acct/uid_1000/pid_5940/cgroup.procs: No such file or directory
,W/ResourcesManager( 6845): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/CalendarApplication( 6845): CalendarApplication.onCreate()
,D/PreferenceKeysParser( 6845): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 6845): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@1c70e48e, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@1588c4af, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@258340bc, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@4040845, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@1a9abb9a, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@2c26fccb, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@3da1aca8, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@3261e3c1, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@2f58f766, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@3269aa7, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@1eb8eb54, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@367fafd, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@3e6d23f2, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@14983a43, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@396368c0, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@3dbe49f9, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@34258d3e, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@20fa379f, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@2b7650ec, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@10908cb5, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@21693f4a, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@854aebb, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@38ed8fd8, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@380a3f31, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@c840616, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@19157b97, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@2797d184, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@2d929d6d, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@2b26da2, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@30ac3a33, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@298281f0, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@1fc8a369, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@366dc1ee, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@9e6468f, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@225cd1c, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@2e3f0d25, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@36780efa, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@150abcab, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@12509f08, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@24f856a1, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@9a820c6, lg_preferences_rece,nt_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@35b6788
D/GeneralPreferenceUtils( 6845): [migratePrefrenceKeys] Exit: Version(44001600) >= 42001300
,D/Config  ( 6845): [init]
I/Config  ( 6845): LGCalendar ver.4.40.16
I/Config  ( 6845): start check model
I/Config  ( 6845): start check native_ca
I/Config  ( 6845): Config Operator=OPEN, Country=EU
D/Config  ( 6845): [setDefaultValuesToPref]
D/Config  ( 6845): [parseProfiles]
D/ProfilesParser( 6845): [debug_displayParseInfos] profile.country = null
,D/ProfilesParser( 6845): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6845): [updateProfiletoCountryInfo]
D/GeneralPreference( 6845): [checkAndMigrateOldPreference]
E/AgendaWidgetManager( 6845): [updateWidgets] 
,I/InitNotificationRingtoneService( 6845): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 6845): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/41
,V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/AlertUtils( 6845): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 6845): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arpeggio.ogg
I/GLSUser ( 2057): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2057): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2057): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2057): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/AlertUtils( 6845): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/AlertUtils( 6845): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 6845): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 6845): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
,I/AlertUtils( 6845): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 6845): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 6845): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 6845): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 6845): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Afternoon_Walk.ogg
I/AlertUtils( 6845): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 6845): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 6845): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
,I/AlertUtils( 6845): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 6845): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6845): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/41
,W/HolidayIntentService( 6845): onHandleIntent
,D/HolidayDataLoader( 6845): readJsonAsset : holiday.json
D/MonthWidgetProvider( 6845): [onReceive]
D/CalendarWidgetProvider( 6845): [onReceive]
D/CalendarWidgetProvider( 6845): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 6845): [onUpdateAndInitCalendarTime]
I/art     ( 1025): Explicit concurrent mark sweep GC freed 23313(1078KB) AllocSpace objects, 3(304KB) LOS objects, 33% free, 44MB/66MB, paused 2.517ms total 148.911ms
,I/AlertUtils( 6845): set default noti to content://media/internal/audio/media/41
,D/WeekWidgetProvider( 6845): [onReceive]
,D/CalendarWidgetProvider( 6845): [onReceive]
D/CalendarWidgetProvider( 6845): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 6845): [onUpdateAndInitCalendarTime]
,E/HolidayIntentService( 6845): onHandleIntent:holiday data empty
,I/InitNotificationRingtoneService( 6845): End InitializeAlertRingtoneService.onHandleIntent
I/ActivityManager( 1025): Killing 6190:com.lge.lifetracker/u0a37 (adj 15): empty #17
,V/NotificationService( 1025): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1025): pkg=com.google.android.gms canInterrupt=false intercept=true
W/GLSActivity( 2057): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2057): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2057): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2057): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2057): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2057): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2057): 	at android.os.Binder.execTransact(Binder.java:446)
I/NotificationServiceEx( 1025): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1025): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
,D/NotificationServiceEx( 1025): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/libprocessgroup( 1025): failed to open /acct/uid_10037/pid_6190/cgroup.procs: No such file or directory
E/BooksAccountManager( 6514): Authentication error
E/BooksAccountManager( 6514): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6514): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6514): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6514): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6514): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6514): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6514): null auth token
D/LgeQuickCoverNLService( 1411): onNotificationPosted
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
,E/LgeQuickCoverOverlayWindow( 1411): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1411): updateNotificationData: count=3
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{19c16502 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,I/DigitalAppWidgetProvider( 6786): onReceive: android.intent.action.ALARM_CHANGED
D/WeatherAncestor( 6660): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 14:38:3
,D/Weather.Utils( 6660): 2 : the weather widgets(using time tick) are gone.
,D/Weather.Utils( 6660): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6660): 2 : This is isUpdating : false
,D/Weather_cast( 6660): 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
D/WeatherAncestor( 6660): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 14:38:3
W/ApiaryClient( 6514): Error response from books API: {
W/ApiaryClient( 6514):  "error": {
W/ApiaryClient( 6514):   "errors": [
W/ApiaryClient( 6514):    {
W/ApiaryClient( 6514):     "domain": "global",
W/ApiaryClient( 6514):     "reason": "required",
W/ApiaryClient( 6514):     "message": "Login Required",
W/ApiaryClient( 6514):     "locationType": "header",
W/ApiaryClient( 6514):     "location": "Authorization"
W/ApiaryClient( 6514):    }
W/ApiaryClient( 6514):   ],
W/ApiaryClient( 6514):   "code": 401,
W/ApiaryClient( 6514):   "message": "Login Required"
W/ApiaryClient( 6514):  }
W/ApiaryClient( 6514): }
W/ApiaryClient( 6514): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6514): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-5576565517851262965&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6514): Headers:
W/ApiaryClient( 6514): accept-encoding: [gzip]
W/ApiaryClient( 6514): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6514): gdata-version: 2
,I/ActivityManager( 1025): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RequestWriter$NetworkStateReceiver: pid=6875 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 6875): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/LgDataFeature( 6875): LgDataFeature() Constructor: none
,D/LgDataFeature( 6875): LgDataFeature() Constructor Done, null
,I/Babel   ( 6875): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 6875): MmsConfig.loadMmsSettings
I/Babel   ( 6875): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
I/Babel   ( 6875): MmsConfig.loadFromDatabase
,E/Babel   ( 6875): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 6875): MmsConfig.loadFromResources
E/Babel   ( 6875): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 6875): MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,W/Settings( 6875): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/AudioCapabilities( 6875): Unsupported mime audio/evrc
,W/AudioCapabilities( 6875): Unsupported mime audio/qcelp
W/VideoCapabilities( 6875): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6875): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 6875): Unsupported mime audio/qcelp
W/AudioCapabilities( 6875): Unsupported mime audio/evrc
W/VideoCapabilities( 6875): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 6875): Unsupported mime video/divx
W/VideoCapabilities( 6875): Unsupported mime video/divx311
W/VideoCapabilities( 6875): Unsupported mime video/divx4
W/VideoCapabilities( 6875): Unsupported mime video/mp4v-esdp
,W/ResourcesManager( 6875): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6875): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/VideoCapabilities( 6875): Unsupported profile 4 for video/mp4v-es
W/AudioCapabilities( 6875): Unsupported mime audio/eac3
W/AudioCapabilities( 6875): Unsupported mime audio/ac3
W/AudioCapabilities( 6875): Unsupported mime audio/g726
,W/AudioCapabilities( 6875): Unsupported mime audio/wma-voice
W/AudioCapabilities( 6875): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6875): Unsupported mime audio/adpcm
W/VideoCapabilities( 6875): Unsupported mime video/theora
W/VideoCapabilities( 6875): Unsupported mime video/mjpg
V/JNIHelp ( 6875): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/System  ( 6875): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/system/app/Hangouts/Hangouts.apk"],nativeLibraryDirectories=[/system/app/Hangouts/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6875): Installed default security provider GmsCore_OpenSSL
I/GLSUser ( 2057): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native
I/GLSUser ( 2057): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2057): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2057): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/Babel   ( 6875): UserRecoverableAuthException.
E/Babel   ( 6875): cfq: BadAuthentication
E/Babel   ( 6875): 	at cfn.a(Unknown Source)
E/Babel   ( 6875): 	at f.a(PG:191)
E/Babel   ( 6875): 	at ava.a(PG:88)
E/Babel   ( 6875): 	at ava.a(PG:128)
E/Babel   ( 6875): 	at bjs.a(PG:255)
E/Babel   ( 6875): 	at bep.a(PG:602)
E/Babel   ( 6875): 	at bep.a(PG:469)
E/Babel   ( 6875): 	at bpo.run(PG:1141)
E/Babel   ( 6875): Error getting auth token
,E/Babel   ( 6875): bxl
E/Babel   ( 6875): 	at f.a(PG:201)
E/Babel   ( 6875): 	at ava.a(PG:88)
E/Babel   ( 6875): 	at ava.a(PG:128)
E/Babel   ( 6875): 	at bjs.a(PG:255)
E/Babel   ( 6875): 	at bep.a(PG:602)
E/Babel   ( 6875): 	at bep.a(PG:469)
E/Babel   ( 6875): 	at bpo.run(PG:1141)
I/Babel_RequestWriter( 6875): error sending REQ[fc:8; creat:1454592405327; type:bev-848513160]; took 152 ms (error code == 100)
E/Babel   ( 6875): Account registration failedRedacted-21
E/Babel   ( 6875): bph: null -- null
E/Babel   ( 6875): 	at ava.a(PG:120)
E/Babel   ( 6875): 	at ava.a(PG:128)
E/Babel   ( 6875): 	at bjs.a(PG:255)
E/Babel   ( 6875): 	at bep.a(PG:602)
E/Babel   ( 6875): 	at bep.a(PG:469)
E/Babel   ( 6875): 	at bpo.run(PG:1141)
I/Babel   ( 6875): Account setup failed with error state:106 account:Redacted-21
I/Babel   ( 6875): Account sign in complete with state 106account: Redacted-21
I/art     ( 6875): Note: end time exceeds epoch: 
I/GLSUser ( 2057): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native
,I/GLSUser ( 2057): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2057): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2057): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 2057): Explicit concurrent mark sweep GC freed 22003(1298KB) AllocSpace objects, 13(1616KB) LOS objects, 51% free, 30MB/62MB, paused 1.576ms total 67.943ms
,V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 2057): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,V/NotificationService( 1025): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1025): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1025): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1025): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1025): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1411): onNotificationPosted
E/Babel   ( 6875): Unexpected exception while authenticating.
E/Babel   ( 6875): cfr: User intervention required. Notification has been pushed.
E/Babel   ( 6875): 	at cfn.b(Unknown Source)
E/Babel   ( 6875): 	at cfn.a(Unknown Source)
E/Babel   ( 6875): 	at f.a(PG:188)
E/Babel   ( 6875): 	,at ava.b(PG:143)
E/Babel   ( 6875): 	at bnr.run(PG:5415)
E/Babel   ( 6875): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 6875): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 6875): 	at java.lang.Thread.run(Thread.java:818)
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
I/GLSUser ( 2057): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2057): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2057): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2057): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{19c16502 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,V/NotificationService( 1025): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1025): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1025): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1025): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1025): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2057): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2057): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2057): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2057): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2057): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2057): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2057): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6514): Authentication error
E/BooksAccountManager( 6514): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6514): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6514): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6514): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6514): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6514): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6514): null auth token
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
,E/LgeQuickCoverOverlayWindow( 1411): updateNotificationData: count=3,
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{19c16502 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6514): Error response from books API: {
W/ApiaryClient( 6514):  "error": {
W/ApiaryClient( 6514):   "errors": [
W/ApiaryClient( 6514):    {
W/ApiaryClient( 6514):     "domain": "global",
W/ApiaryClient( 6514):     "reason": "required",
W/ApiaryClient( 6514):     "message": "Login Required",
W/ApiaryClient( 6514):     "locationType": "header",
W/ApiaryClient( 6514):     "location": "Authorization"
W/ApiaryClient( 6514):    }
W/ApiaryClient( 6514):   ],
W/ApiaryClient( 6514):   "code": 401,
W/ApiaryClient( 6514):   "message": "Login Required"
W/ApiaryClient( 6514):  }
W/ApiaryClient( 6514): }
,W/ApiaryClient( 6514): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6514): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-5576565517851262965&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6514): Headers:
W/ApiaryClient( 6514): accept-encoding: [gzip]
W/ApiaryClient( 6514): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6514): gdata-version: 2
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=17.4, 0.0, 0.0  rx=15.2 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:-1400828466] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=17.4, 0.0, 0.0  rx=15.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1400828463] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,E/BooksSync( 6514): Soft error: 
E/BooksSync( 6514): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6514): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-5576565517851262965&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6514): Headers:
E/BooksSync( 6514): accept-encoding: [gzip]
E/BooksSync( 6514): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6514): gdata-version: 2
E/BooksSync( 6514): 
E/BooksSync( 6514): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6514): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6514): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6514): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6514): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6514): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6514): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6514): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6514): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6514): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6514): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6514): {
E/BooksSync( 6514):  "error": {
E/BooksSync( 6514):   "errors": [
E/BooksSync( 6514):    {
E/BooksSync( 6514):     "domain": "global",
E/BooksSync( 6514):     "reason": "required",
E/BooksSync( 6514):     "message": "Login Required",
E/BooksSync( 6514):     "locationType": "header",
E/BooksSync( 6514):     "location": "Authorization"
E/BooksSync( 6514):    }
E/BooksSync( 6514):   ],
E/BooksSync( 6514):   "code": 401,
E/BooksSync( 6514):   "message": "Login Required"
E/BooksSync( 6514):  }
E/BooksSync( 6514): }
E/BooksSync( 6514): 
E/BooksSync( 6514): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6514): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6514): 	... 8 more
,E/BooksSync( 6514): Sync error
E/BooksSync( 6514): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6514): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-5576565517851262965&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6514): Headers:
E/BooksSync( 6514): accept-encoding: [gzip]
E/BooksSync( 6514): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6514): gdata-version: 2
E/BooksSync( 6514): 
E/BooksSync( 6514): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6514): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6514): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6514): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6514): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6514): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6514): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6514): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6514): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6514): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6514): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6514): {
E/BooksSync( 6514):  "error": {
E/BooksSync( 6514):   "errors": [
E/BooksSync( 6514):    {
E/BooksSync( 6514):     "domain": "global",
E/BooksSync( 6514):     "reason": "required",
E/BooksSync( 6514):     "message": "Login Required",
E/BooksSync( 6514):     "locationType": "header",
E/BooksSync( 6514):     "location": "Authorization"
E/BooksSync( 6514):    }
E/BooksSync( 6514):   ],
E/BooksSync( 6514):   "code": 401,
E/BooksSync( 6514):   "message": "Login Required"
E/BooksSync( 6514):  }
E/BooksSync( 6514): }
E/BooksSync( 6514): 
E/BooksSync( 6514): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6514): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6514): 	... 8 more
I/BooksSync( 6514): Finished books sync
I/ActivityManager( 1025): Killing 5915:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,D/SyncManager( 1025): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 26786, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/QRemote ( 6331): [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
W/System.err( 6331): android.os.DeadObjectException
W/System.err( 6331): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6331): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6331): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 6331): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
W/System.err( 6331): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 6331): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 6331): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6331): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6331): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6331): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 6331): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6331): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6331): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 6331): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 6331): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 6331): android.os.DeadObjectException
W/System.err( 6331): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6331): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6331): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 6331): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
W/System.err( 6331): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 6331): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 6331): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6331): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6331): 	at android.os.Looper.loop(Looper.java:135)
,W/System.err( 6331): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 6331): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6331): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6331): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 6331): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 6331): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/QRemote ( 6331): [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
I/ActivityManager( 1025): Killing 6221:com.lge.sync/1000 (adj 15): empty #18
,W/libprocessgroup( 1025): failed to open /acct/uid_1000/pid_5915/cgroup.procs: No such file or directory
W/ActivityManager( 1025): Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,W/libprocessgroup( 1025): failed to open /acct/uid_1000/pid_6221/cgroup.procs: No such file or directory
D/QRemote ( 6331): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
I/QRemote ( 6331): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
I/ActivityManager( 1025): Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6942 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,V/AlarmManager( 1025): ELAPSED_WAKEUP set : Alarm{b9f8da6 type 2 when 126037 com.android.providers.calendar} when 126037
D/QRemote ( 6331): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,I/ActivityManager( 1025): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=6968 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi
,W/ResourcesManager( 6968): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/UEI.SmartControl( 6942): Quickset Services start...
I/UEI.SmartControl( 6942): Manufacture = LGE
D/UEI.SmartControl( 6942): Id = LGNevo
D/UEI.SmartControl( 6942): File observer start...
E/UEI.SmartControl( 6942): IR Port is disabled: false
D/UEI.SmartControl( 6942): Starting file observer...
D/UEI.SmartControl( 6942): Extracting JNI libs...
D/UEI.SmartControl( 6942): --- this system supports 32-bit or 64-bit only
,D/CalendarProvider2( 6968): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@10d1fb90
,D/CalendarProvider2( 6968): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 6968): Created com.android.providers.calendar.CalendarAlarmManager@4040845(com.android.providers.calendar.CalendarProvider2@10d1fb90)
D/CalendarProviderBroadcastReceiver( 6968): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 6968): [IntentService] WakeLock acquire, start IntentSerivce
D/CalendarProvider2( 6968): CalendarProviderIntentService.onCreate()
,D/CalendarProvider2( 6968): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 6968): [getOrCreateCalendarAlarmManager]
E/SQLiteLog( 6968): (284) automatic index on view_events(_id)
V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/CalendarProvider2( 6968): [IntentService] Release Lock
D/CalendarProvider2( 6968): CalendarProviderIntentService.onDestroy()
I/ActivityManager( 1025): Killing 6115:com.android.settings/1000 (adj 15): empty #17
,D/UEI.SmartControl( 6942): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 6942): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6942): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/GLSUser ( 2057): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 2057): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2057): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2057): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/WifiService( 1025): Client connection lost with reason: 4
,I/UEI.SmartControl( 6942): --- Selecting new region: 6
,I/UEI.SmartControl( 6942): Model = LG-D855
D/UEI.SmartControl( 6942): QS Service created
W/libprocessgroup( 1025): failed to open /acct/uid_1000/pid_6115/cgroup.procs: No such file or directory
,V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/UEI.SmartControl( 6942): Service initServices...
,D/UEI.SmartControl( 6942): QS start get config
V/NotificationService( 1025): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1025): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1025): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1025): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1025): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2057): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2057): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2057): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2057): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2057): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2057): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2057): 	at android.os.Binder.execTransact(Binder.java:446)
,D/ContactsSyncAdapter( 2057): innerSync failed
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
D/SyncManager( 1025): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 153335, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
,D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{19c16502 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/UEI.SmartControl( 6942): Loading JNI Libs...
I/ActivityManager( 1025): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=6997 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager( 1025): RTC_WAKEUP set : Alarm{310aa2a9 type 0 when 1454593086525 com.android.vending} when 1454593086525
,I/UEI.SmartControl( 6942): Supports setup maps: true
,D/UEI.SmartControl( 6942): QS start statue = true Error code = 0
,I/UEI.SmartControl( 6942): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6942): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6942): ### init IR Blaster...
D/serial_port( 6942): Configuring serial port
I/GAV2    ( 6514): Thread[GAThread,5,main]: No campaign data found.
E/UEI.SmartControl( 6942): UEIBLaster setting for 616
I/UEI.SmartControl( 6942): Setting serial record hearder size = 2
I/UEI.SmartControl( 6942): configuring settings for MAXQ616
I/UEI.SmartControl( 6942): Get version...
D/UEI.SmartControl( 6942): serial port data available: 21
,D/Finsky  ( 6997): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/UEI.SmartControl( 6942): MAXQ616 A2-X4 software.
,I/UEI.SmartControl( 6942): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 6942): QS saving settings...
D/UEI.SmartControl( 6942): IR Blaster version: 25672567
D/UEI.SmartControl( 6942): serial port data available: 4
,D/LgDataFeature( 6997): LgDataFeature() Constructor: none
D/LgDataFeature( 6997): LgDataFeature() Constructor Done, null
,I/UEI.SmartControl( 6942): Device manager: loading config....
,W/ContextImpl( 6942): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
D/UEI.SmartControl( 6942): ----------- loading internal config...
E/UEI.SmartControl( 6942): Services init done
D/UEI.SmartControl( 6942): QS Service init finished
D/UEI.SmartControl( 6942): QS Service version name: 2.1.91
D/UEI.SmartControl( 6942): QS Service version code: 201091
D/UEI.SmartControl( 6942): Service requested: Control
D/UEI.SmartControl( 6942): Request IControl service: devices are loaded...
,E/UEI.SmartControl( 6942): Loading SETTINGS...
D/UEI.SmartControl( 6942): -- Open brand translation xml: brands_translations_ko
I/QRemote ( 6331): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 6942): ------ IControl API: 11
I/ActivityManager( 1025): Killing 6331:com.lge.qremote/u0a112 (adj 15): empty #17
I/UEI.SmartControl( 6942): Registering callback...
I/UEI.SmartControl( 6942): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6942): -----service ready thread exits
,W/libprocessgroup( 1025): failed to open /acct/uid_10112/pid_6331/cgroup.procs: No such file or directory
D/UEI.SmartControl( 6942): Internal service binding...
,D/Finsky  ( 6997): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/ActivityManager( 1025): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=7045 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/Settings( 6997): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6997): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 6997): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6997): [1] 2.run: Finished loading 1 libraries.
,W/ResourcesManager( 7045): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7045): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/GAV4    ( 6686): Thread[GAThread,5,main]: No campaign data found.
V/DownloadManager( 3359): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3359): created cursor android.database.sqlite.SQLiteCursor@3b758352 on behalf of 6997
,D/Finsky  ( 6997): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/Finsky  ( 6997): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/MultiDex( 7045): VM with version 2.1.0 has multidex support
,I/MultiDex( 7045): install
I/MultiDex( 7045): VM has multidex support, MultiDex support library is disabled.
V/SIM_STK ( 1025): Menu title from STK is T-Mobile
,V/JNIHelp ( 7045): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 7045): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7045): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@27c89177: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7045): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 2057): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 2057): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GmsCoreStatsServiceLauncher( 2303): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/ActivityManager( 1025): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=7078 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,D/LocationInitializer( 2303): Restart initialization of location
,W/ResourcesManager( 7078): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7078): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/sensors_hal_Time( 1025): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1025): tsOffsetIs: Apps: 127614938443; DSPS: 4322580; Offset : -4313866749
I/art     ( 2303): Explicit concurrent mark sweep GC freed 17812(1252KB) AllocSpace objects, 18(288KB) LOS objects, 49% free, 32MB/64MB, paused 737us total 29.443ms
I/MultiDex( 7078): VM with version 2.1.0 has multidex support
I/MultiDex( 7078): install
,I/MultiDex( 7078): VM has multidex support, MultiDex support library is disabled.
V/JNIHelp ( 7078): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 7078): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7078): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@27c89177: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7078): Installed default security provider GmsCore_OpenSSL
D/WearableService( 7078): callingUid 10005, callindPid: 7078
,V/Finsky  ( 6997): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,E/MDM     ( 1803): [86] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GCM     ( 2057): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AuthorizationBluetoothService( 2057): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 2303): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
I/art     ( 1025): Explicit concurrent mark sweep GC freed 26392(1203KB) AllocSpace objects, 6(608KB) LOS objects, 33% free, 44MB/66MB, paused 3.164ms total 76.349ms
,E/MDM     ( 1803): [87] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/GLSUser ( 2057): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2057): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2057): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2057): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/LocationInitializer( 2303): Restart initialization of location
V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6997): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6997): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6997): [1] 5.onFinished: Scheduling replication attempt 2.
I/ActivityManager( 1025): Killing 6164:com.lge.formmanager/u0a26 (adj 15): empty #17
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=27.7, 0.0, 0.0  rx=25.6 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1400825454] gl rssi=-64 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=27.7, 0.0, 0.0  rx=25.6 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1400825453] gl rssi=-64 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,I/ActivityManager( 1025): Killing 6493:com.lge.appbox.client/u0a11 (adj 15): empty #18
,W/libprocessgroup( 1025): failed to open /acct/uid_10011/pid_6493/cgroup.procs: No such file or directory
,W/libprocessgroup( 1025): failed to open /acct/uid_10026/pid_6164/cgroup.procs: No such file or directory
,V/AlarmManager( 1025): RTC_WAKEUP set : Alarm{2b8406f9 type 0 when 1454593088022 com.android.vending} when 1454593088022
,D/Finsky  ( 6997): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2057): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 2057): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2057): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2057): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 6997): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2057): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 2057): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2057): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2057): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2057): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 2057): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2057): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2057): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 6997): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/SIM_STK ( 1025): Menu title from STK is T-Mobile
,V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2057): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2057): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2057): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2057): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 6997): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 6997): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
D/Finsky  ( 6997): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6997): [1] DailyHygiene.reschedule: Scheduling new run in 31 minutes (failures=2)
D/DeviceConnectionService( 1803): client connected with version: 7571000
,I/ThermalEngine(  330): Thermal-Server: Thermal received msg from  override
,I/Thermal-Lib( 2965): Thermal-Lib-Client: Client request sent
,I/ActivityManager( 1025): Killing 6635:com.lge.drmservice/u0a62 (adj 15): empty #17
,W/libprocessgroup( 1025): failed to open /acct/uid_10062/pid_6635/cgroup.procs: No such file or directory
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=14.8, 0.0, 0.0  rx=12.8 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1400822438] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=14.8, 0.0, 0.0  rx=12.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1400822435] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,D/UEI.SmartControl( 6942): Internal timer expired: 1
,D/UEI.SmartControl( 6942): unbind internal service
D/UEI.SmartControl( 6942): Service.onUnbind: IControl
,D/UEI.SmartControl( 6942): Service.onDestroy
D/UEI.SmartControl( 6942): Lock is in USE false
D/UEI.SmartControl( 6942): unbind internal service
W/System.err( 6942): java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@2f58f766
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
E/UEI.SmartControl( 6942): java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@2f58f766
D/serial_port( 6942): close(fd = 25)
I/UEI.SmartControl( 6942): Serial port is closed.
I/UEI.SmartControl( 6942): Serial port is closed.
D/UEI.SmartControl( 6942): Blaster closed
,D/UEI.SmartControl( 6942): Shut down QS...
D/UEI.SmartControl( 6942): Stopping QS lib
D/UEI.SmartControl( 6942): QS lib stop result = true
D/UEI.SmartControl( 6942): Stopped QS lib
D/UEI.SmartControl( 6942): Stopped file observer...
D/UEI.SmartControl( 6942): QS shutdown complete
I/ActivityManager( 1025): Killing 6533:com.android.gallery3d/u0a27 (adj 15): empty #17
,W/libprocessgroup( 1025): failed to open /acct/uid_10027/pid_6533/cgroup.procs: No such file or directory
,I/ActivityManager( 1025): Killing 6686:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,W/libprocessgroup( 1025): failed to open /acct/uid_10093/pid_6686/cgroup.procs: No such file or directory
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=8.4, 0.0, 0.0  rx=7.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1400819407] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=8.4, 0.0, 0.0  rx=7.4 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1400819398] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=4.2, 0.0, 0.0  rx=3.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1400816376] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=4.2, 0.0, 0.0  rx=3.7 bcn=0 [on:0 tx:0 rx:0 period:14] from screen [on:0 period:-1400816362] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
I/[SystemUI]QPairHandler( 1465): onReceive = android.intent.action.PACKAGE_CHANGED
,D/SplitUIService( 1856): replaced split : contains_com.google.android.talk / true
I/InputReader( 1025): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager( 1025): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7138 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/SplitUIManager( 1856): split_name #11 / not available #0
I/SplitUIService( 1856): split app #11
I/[SystemUI]QSlideListController( 1465): onReceive = android.intent.action.PACKAGE_CHANGED
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1465): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.talk
I/[LGHome]EVENT( 2020): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000010 (has extras) }
D/administrator( 1025): Handling package changes for user 0
,W/ResourcesManager( 2020): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/[LGHome]Launcher( 2020): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/AppUp4:AppBoxCP( 7138): onCreate
,W/AppUp4:DB( 7138):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7138):  setFingerPrint start
I/AppUp4:DB( 7138):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 7138):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7138):  SDK version = 21
I/AppUp4:DB( 7138):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 7138): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 7138): onReceive
,I/NotificationService( 1025): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,D/BackupManagerService( 1025): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000010 (has extras) }
W/ResourcesManager( 1025): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=2.6, 0.0, 0.0  rx=2.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1400813351] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=2.6, 0.0, 0.0  rx=2.4 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:-1400813351] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
D/LgDataFeature( 7138): LgDataFeature() Constructor: none
D/LgDataFeature( 7138): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7138): Context : android.app.ReceiverRestrictedContext@1588c4af
D/AppUp4:CustFacade( 7138): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7138): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7138): begin check event
I/AppUp4:CustModeStarterReceiver( 7138): Event For Nothing, skip.
W/ResourcesManager( 1025): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourceType( 1025): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/ActivityManager( 1025): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7166 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/ActivityManager( 1025): Killing 6552:com.android.chrome/u0a57 (adj 15): empty #17
W/libprocessgroup( 1025): failed to open /acct/uid_10057/pid_6552/cgroup.procs: No such file or directory
,I/[LGHome]EVENT( 2020): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
W/ResourcesManager( 7166): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7166): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7166): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,W/ResourcesManager( 7166): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7166): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/SystemConfig( 7166): BUILD Country: EU
I/SystemConfig( 7166): BUILD Operator: OPEN
,I/ActivityManager( 1025): Killing 6744:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,W/libprocessgroup( 1025): failed to open /acct/uid_10097/pid_6744/cgroup.procs: No such file or directory
,I/SystemConfig( 7166): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7166): existFile = false
I/SystemConfig( 7166): canReadFile = false
I/SystemConfig( 7166): systemFeature RCS result false
D/SystemConfig( 7166): refreshRcsSupport() :false
I/ActivityManager( 1025): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7189 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/ResourcesManager( 7189): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7189): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7189): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 7189): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,I/AppConfig( 7189): Total System Memory = 2995761152
,D/SystemHelper( 7189): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager( 1025): Killing 6578:com.lge.email/u0a23 (adj 15): empty #17
,W/libprocessgroup( 1025): failed to open /acct/uid_10023/pid_6578/cgroup.procs: No such file or directory
,I/UpdateIcingCorporaServi( 4277): Updating corpora: APPS=com.google.android.talk, CONTACTS=MAYBE
I/ActivityManager( 1025): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7213 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,V/SIM_STK ( 1025): Menu title from STK is T-Mobile
,W/ResourcesManager( 4277): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 4277): UpdateCorporaTask done [took 94 ms] updated apps [took 94 ms] 
,I/LockScreenSettings( 7213): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7213): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7213): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7213): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7213): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7213): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
D/LockScreenSettings( 7213): Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,I/ActivityManager( 1025): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7241 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1025): Killing 6276:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,I/art     (  349): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 465us total 39.088ms
,I/art     (  349): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 452us total 20.593ms
,I/art     (  349): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 454us total 20.700ms
,W/libprocessgroup( 1025): failed to open /acct/uid_1000/pid_6276/cgroup.procs: No such file or directory
,W/ResourcesManager( 7241): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/PackageBroadcastService( 2303): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.talk
,I/PeopleContactsSync( 2303): CP2 sync disabled
,I/GLSActivity( 2057): [ac] getting account id
,I/GLSUser ( 2057): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.8, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1400810343] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.8, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1400810340] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1400807314] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1400807310] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,I/ActivityManager( 1025): Killing 6824:com.qualcomm.timeservice/1000 (adj 15): empty #17
,W/libprocessgroup( 1025): failed to open /acct/uid_1000/pid_6824/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1025): tsOffsetIs: Apps: 147617055102; DSPS: 4978009; Offset : -4313857158
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1400804285] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1400804275] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
V/AlarmManager( 1025): RTC_WAKEUP set : Alarm{23a5033b type 0 when 1454593108435 com.android.vending} when 1454593108435
,V/SIM_STK ( 1025): Menu title from STK is T-Mobile
,V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2057): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2057): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2057): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2057): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 2057): Explicit concurrent mark sweep GC freed 23160(1347KB) AllocSpace objects, 9(1296KB) LOS objects, 51% free, 30MB/62MB, paused 1.428ms total 33.415ms
,D/Finsky  ( 6997): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6997): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6997): [1] 5.onFinished: Scheduling replication attempt 3.
,V/AlarmManager( 1025): ELAPSED_WAKEUP set : Alarm{248e4da5 type 2 when 151240 android} when 151240
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1400801255] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1400801246] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:2999] from screen [on:0 period:-1400798227] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1400798226] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1025):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,E/WifiStateMachine( 1025):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1025):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1025):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1025):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1400795214] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1400795210] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1400792187] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1400792184] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1400789159] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1400789156] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1400786133] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1400786130] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1025): tsOffsetIs: Apps: 167619094469; DSPS: 5633436; Offset : -4313862416
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3009] from screen [on:0 period:-1400783097] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:14] from screen [on:0 period:-1400783083] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1400780075] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1400780063] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1400777042] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1400777039] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1400774019] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1400774016] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,V/AlarmManager( 1025): RTC_WAKEUP set : Alarm{1959312b type 0 when 1454593130357 com.android.vending} when 1454593130357
,V/SIM_STK ( 1025): Menu title from STK is T-Mobile
,V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2057): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2057): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2057): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2057): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 1025): Explicit concurrent mark sweep GC freed 39817(1883KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 44MB/66MB, paused 1.652ms total 102.950ms
,D/Finsky  ( 6997): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6997): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6997): [1] 5.onFinished: Scheduling replication attempt 4.
I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
,I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
,D/PowerManagerServiceEx( 1025): acquireWakeLockInternal: lock=1033378170, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1025
,V/AlarmManager( 1025): ELAPSED_WAKEUP set : Alarm{1a66ea15 type 2 when 181261 android} when 181261
D/[Concierge]Service( 2576): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1025): releaseWakeLockInternal: lock=1033378170 [*alarm*], flags=0x0
,I/BooksSync( 6514): Starting books sync
,D/BooksSync( 6514): started syncMyEbooks
,V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2057): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2057): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2057): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2057): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1025): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1025): pkg=com.google.android.gms canInterrupt=false intercept=true
,I/NotificationServiceEx( 1025): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1025): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1025): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/GLSActivity( 2057): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2057): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2057): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2057): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2057): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2057): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2057): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  1
,D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1411): updateNotificationData: count=3
E/BooksAccountManager( 6514): Authentication error
E/BooksAccountManager( 6514): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6514): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6514): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6514): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6514): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6514): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6514): null auth token
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{19c16502 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,I/GLSUser ( 2057): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
,I/GLSUser ( 2057): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2057): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2057): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1025): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1025): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1025): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1025): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1025): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2057): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2057): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2057): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2057): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2057): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2057): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2057): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1411): onNotificationPosted
,W/ApiaryClient( 6514): Error response from books API: {
W/ApiaryClient( 6514):  "error": {
W/ApiaryClient( 6514):   "errors": [
W/ApiaryClient( 6514):    {
W/ApiaryClient( 6514):     "domain": "global",
W/ApiaryClient( 6514):     "reason": "required",
W/ApiaryClient( 6514):     "message": "Login Required",
W/ApiaryClient( 6514):     "locationType": "header",
W/ApiaryClient( 6514):     "location": "Authorization"
W/ApiaryClient( 6514):    }
W/ApiaryClient( 6514):   ],
W/ApiaryClient( 6514):   "code": 401,
W/ApiaryClient( 6514):   "message": "Login Required"
W/ApiaryClient( 6514):  }
W/ApiaryClient( 6514): }
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
W/ApiaryClient( 6514): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6514): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7617293328402823819&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6514): Headers:
W/ApiaryClient( 6514): accept-encoding: [gzip]
W/ApiaryClient( 6514): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/A,piaryClient( 6514): gdata-version: 2
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1411): updateNotificationData: count=3
D/SyncManager( 1025): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 153335, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager( 1025): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 243707, reason: 10019
,D/QuickStatusbarLayout( 1411): Notification difference=198
,D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{19c16502 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1400770988] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1400770985] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2057): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2057): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2057): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2057): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1025): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1025): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1025): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1025): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1025): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
,W/GLSActivity( 2057): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2057): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2057): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2057): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2057): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2057): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2057): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6514): Authentication error
E/BooksAccountManager( 6514): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6514): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6514): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6514): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6514): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6514): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6514): null auth token
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{19c16502 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6514): Error response from books API: {
W/ApiaryClient( 6514):  "error": {
W/ApiaryClient( 6514):   "errors": [
W/ApiaryClient( 6514):    {
W/ApiaryClient( 6514):     "domain": "global",
W/ApiaryClient( 6514):     "reason": "required",
W/ApiaryClient( 6514):     "message": "Login Required",
W/ApiaryClient( 6514):     "locationType": "header",
W/ApiaryClient( 6514):     "location": "Authorization"
W/ApiaryClient( 6514):    }
W/ApiaryClient( 6514):   ],
W/ApiaryClient( 6514):   "code": 401,
W/ApiaryClient( 6514):   "message": "Login Required"
W/ApiaryClient( 6514):  }
W/ApiaryClient( 6514): }
,W/ApiaryClient( 6514): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6514): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7617293328402823819&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6514): Headers:
W/ApiaryClient( 6514): accept-encoding: [gzip]
W/ApiaryClient( 6514): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6514): gdata-version: 2
V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2057): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2057): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2057): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2057): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1025): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1025): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1025): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1025): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1025): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/GLSActivity( 2057): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2057): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2057): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2057): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2057): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2057): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2057): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6514): Authentication error
E/BooksAccountManager( 6514): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6514): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6514): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6514): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6514): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6514): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6514): null auth token
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{19c16502 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6514): Error response from books API: {
W/ApiaryClient( 6514):  "error": {
W/ApiaryClient( 6514):   "errors": [
W/ApiaryClient( 6514):    {
W/ApiaryClient( 6514):     "domain": "global",
W/ApiaryClient( 6514):     "reason": "required",
W/ApiaryClient( 6514):     "message": "Login Required",
W/ApiaryClient( 6514):     "locationType": "header",
W/ApiaryClient( 6514):     "location": "Authorization"
W/ApiaryClient( 6514):    }
W/ApiaryClient( 6514):   ],
W/ApiaryClient( 6514):   "code": 401,
W/ApiaryClient( 6514):   "message": "Login Required"
W/ApiaryClient( 6514):  }
W/ApiaryClient( 6514): }
,W/ApiaryClient( 6514): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6514): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7617293328402823819&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6514): Headers:
W/ApiaryClient( 6514): accept-encoding: [gzip]
W/ApiaryClient( 6514): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6514): gdata-version: 2
,E/BooksSync( 6514): Soft error: 
E/BooksSync( 6514): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6514): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7617293328402823819&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6514): Headers:
E/BooksSync( 6514): accept-encoding: [gzip]
E/BooksSync( 6514): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6514): gdata-version: 2
E/BooksSync( 6514): 
E/BooksSync( 6514): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6514): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6514): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6514): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6514): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6514): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6514): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6514): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6514): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6514): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6514): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6514): {
E/BooksSync( 6514):  "error": {
E/BooksSync( 6514):   "errors": [
E/BooksSync( 6514):    {
E/BooksSync( 6514):     "domain": "global",
E/BooksSync( 6514):     "reason": "required",
E/BooksSync( 6514):     "message": "Login Required",
E/BooksSync( 6514):     "locationType": "header",
E/BooksSync( 6514):     "location": "Authorization"
E/BooksSync( 6514):    }
E/BooksSync( 6514):   ],
E/BooksSync( 6514):   "code": 401,
E/BooksSync( 6514):   "message": "Login Required"
E/BooksSync( 6514):  }
E/BooksSync( 6514): }
E/BooksSync( 6514): 
E/BooksSync( 6514): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6514): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6514): 	... 8 more
,E/BooksSync( 6514): Sync error
E/BooksSync( 6514): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6514): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7617293328402823819&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6514): Headers:
E/BooksSync( 6514): accept-encoding: [gzip]
E/BooksSync( 6514): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6514): gdata-version: 2
E/BooksSync( 6514): 
E/BooksSync( 6514): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6514): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6514): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6514): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6514): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6514): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6514): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6514): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6514): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6514): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6514): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6514): {
E/BooksSync( 6514):  "error": {
E/BooksSync( 6514):   "errors": [
E/BooksSync( 6514):    {
E/BooksSync( 6514):     "domain": "global",
E/BooksSync( 6514):     "reason": "required",
E/BooksSync( 6514):     "message": "Login Required",
E/BooksSync( 6514):     "locationType": "header",
E/BooksSync( 6514):     "location": "Authorization"
E/BooksSync( 6514):    }
E/BooksSync( 6514):   ],
E/BooksSync( 6514):   "code": 401,
E/BooksSync( 6514):   "message": "Login Required"
E/BooksSync( 6514):  }
E/BooksSync( 6514): }
E/BooksSync( 6514): 
E/BooksSync( 6514): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6514): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6514): 	... 8 more
I/BooksSync( 6514): Finished books sync
D/SyncManager( 1025): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 158276, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.7, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1400767965] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.7, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1400767961] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1025): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1025): tsOffsetIs: Apps: 187621761910; DSPS: 6288883; Offset : -4313850187
,I/[SystemUI]LGPowerUI( 1465): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1465): On Skip Timer : true
,D/WifiController( 1025): battery changed pluggedType: 2
,D/LEDHandler( 1928): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1928): Battery Level Remaining: 100%
D/LEDHandler( 1928): Battery Temp: 293, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1465): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 293
I/[SystemUI]LGPowerUI( 1465): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 6089): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1465): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4006): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4006): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/Settings( 1025): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1025): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=3.8, 0.0, 0.0  rx=3.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1400764946] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=3.8, 0.0, 0.0  rx=3.3 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1400764945] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=2.4, 0.0, 0.0  rx=2.2 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1400761925] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=2.4, 0.0, 0.0  rx=2.2 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1400761915] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.7, 0.0, 0.0  rx=1.6 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1400758895] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.7, 0.0, 0.0  rx=1.6 bcn=0 [on:0 tx:0 rx:0 period:15] from screen [on:0 period:-1400758880] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1400755860] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1400755857] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1400752834] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1400752825] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1400749802] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1400749799] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1400746773] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1400746770] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1025): tsOffsetIs: Apps: 207623867475; DSPS: 6944312; Offset : -4313850517
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1400743745] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1400743735] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,V/AlarmManager( 1025): ELAPSED_WAKEUP set : Alarm{299ca765 type 2 when 182169 com.google.android.gms} when 182169
,V/AlarmManager( 1025): RTC_WAKEUP set : Alarm{19b980eb type 0 when 1454593159917 com.android.vending} when 1454593159917
,V/AlarmManager( 1025): ELAPSED_WAKEUP set : Alarm{1a05ae48 type 2 when 209137 android} when 209137
V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/SIM_STK ( 1025): Menu title from STK is T-Mobile
,I/VacuumService( 2057): Vacuum at: now=1454593170494 tag=VacuumService
,V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2057): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2057): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2057): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2057): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6997): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6997): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6997): [1] 5.onFinished: Scheduling replication attempt 5.
V/AlarmManager( 1025): ELAPSED_WAKEUP set : Alarm{ab088d type 2 when 211366 android} when 211366
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1400740715] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1400740706] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1400737686] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1400737685] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1400734672] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1400734669] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1400731643] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1400731640] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1400728616] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1400728607] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1025): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1025): tsOffsetIs: Apps: 227625718665; DSPS: 7599733; Offset : -4313860768
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1400725587] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1400725584] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1400722558] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1400722556] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1400719542] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1400719539] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,V/AlarmManager( 1025): RTC_WAKEUP set : Alarm{616a53 type 0 when 1454593190759 com.android.vending} when 1454593190759
,V/SIM_STK ( 1025): Menu title from STK is T-Mobile
,V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2057): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2057): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2057): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2057): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6997): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6997): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6997): [1] 5.onFinished: Giving up after 6 failures.
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1400716512] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1400716509] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1400713481] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1400713478] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
,I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1400710456] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:14] from screen [on:0 period:-1400710442] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1400707422] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1400707419] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1025): tsOffsetIs: Apps: 247627634074; DSPS: 8255155; Offset : -4313837320
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1400704400] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1400704398] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,D/PowerManagerServiceEx( 1025): acquireWakeLockInternal: lock=1033378170, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1025
,V/AlarmManager( 1025): ELAPSED_WAKEUP set : Alarm{1dbc2efd type 2 when 249770 android} when 249770
D/[Concierge]Service( 2576): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1025): releaseWakeLockInternal: lock=1033378170 [*alarm*], flags=0x0
,I/BooksSync( 6514): Starting books sync
,D/BooksSync( 6514): started syncMyEbooks
,V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2057): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2057): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2057): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2057): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1025): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1025): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1025): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1025): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1025): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/GLSActivity( 2057): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2057): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2057): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2057): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2057): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2057): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2057): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6514): Authentication error
E/BooksAccountManager( 6514): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6514): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6514): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6514): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6514): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6514): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6514): null auth token
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{19c16502 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6514): Error response from books API: {
W/ApiaryClient( 6514):  "error": {
W/ApiaryClient( 6514):   "errors": [
W/ApiaryClient( 6514):    {
W/ApiaryClient( 6514):     "domain": "global",
W/ApiaryClient( 6514):     "reason": "required",
W/ApiaryClient( 6514):     "message": "Login Required",
W/ApiaryClient( 6514):     "locationType": "header",
W/ApiaryClient( 6514):     "location": "Authorization"
W/ApiaryClient( 6514):    }
W/ApiaryClient( 6514):   ],
W/ApiaryClient( 6514):   "code": 401,
W/ApiaryClient( 6514):   "message": "Login Required"
W/ApiaryClient( 6514):  }
W/ApiaryClient( 6514): }
,W/ApiaryClient( 6514): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6514): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=1299066459825391851&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6514): Headers:
W/ApiaryClient( 6514): accept-encoding: [gzip]
W/ApiaryClient( 6514): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6514): gdata-version: 2
,V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2057): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2057): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2057): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2057): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1025): Explicit concurrent mark sweep GC freed 47271(2MB) AllocSpace objects, 6(736KB) LOS objects, 33% free, 44MB/66MB, paused 2.520ms total 147.645ms
,V/NotificationService( 1025): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1025): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1025): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1025): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1025): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
,D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1411): updateNotificationData: count=3
W/GLSActivity( 2057): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2057): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2057): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2057): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2057): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2057): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2057): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6514): Authentication error
E/BooksAccountManager( 6514): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6514): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6514): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6514): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6514): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6514): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6514): null auth token
,D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{19c16502 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6514): Error response from books API: {
W/ApiaryClient( 6514):  "error": {
W/ApiaryClient( 6514):   "errors": [
W/ApiaryClient( 6514):    {
W/ApiaryClient( 6514):     "domain": "global",
W/ApiaryClient( 6514):     "reason": "required",
W/ApiaryClient( 6514):     "message": "Login Required",
W/ApiaryClient( 6514):     "locationType": "header",
W/ApiaryClient( 6514):     "location": "Authorization"
W/ApiaryClient( 6514):    }
W/ApiaryClient( 6514):   ],
W/ApiaryClient( 6514):   "code": 401,
W/ApiaryClient( 6514):   "message": "Login Required"
W/ApiaryClient( 6514):  }
W/ApiaryClient( 6514): }
,W/ApiaryClient( 6514): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6514): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=1299066459825391851&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6514): Headers:
W/ApiaryClient( 6514): accept-encoding: [gzip]
W/ApiaryClient( 6514): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6514): gdata-version: 2
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1400701375] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1400701363] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2057): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2057): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2057): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2057): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1025): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1025): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1025): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1025): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1025): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1411): onNotificationPosted
D/SmartCoverUpdateMonitor( 1411): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1411): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1411): handleNotificationPosted(true)
D/QuickCircle( 1411): onNotificationPosted() : isPosted true
,D/LgeQuickCoverNotificationData( 1411): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
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
E/LgeQuickCoverOverlayWindow( 1411): updateNotificationData: count=3
W/GLSActivity( 2057): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2057): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2057): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2057): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2057): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2057): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2057): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6514): Authentication error
E/BooksAccountManager( 6514): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6514): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6514): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6514): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6514): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6514): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6514): null auth token
,D/QuickStatusbarLayout( 1411): Notification difference=198
,D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{19c16502 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6514): Error response from books API: {
W/ApiaryClient( 6514):  "error": {
W/ApiaryClient( 6514):   "errors": [
W/ApiaryClient( 6514):    {
W/ApiaryClient( 6514):     "domain": "global",
W/ApiaryClient( 6514):     "reason": "required",
W/ApiaryClient( 6514):     "message": "Login Required",
W/ApiaryClient( 6514):     "locationType": "header",
W/ApiaryClient( 6514):     "location": "Authorization"
W/ApiaryClient( 6514):    }
W/ApiaryClient( 6514):   ],
W/ApiaryClient( 6514):   "code": 401,
W/ApiaryClient( 6514):   "message": "Login Required"
W/ApiaryClient( 6514):  }
W/ApiaryClient( 6514): }
,W/ApiaryClient( 6514): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6514): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=1299066459825391851&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6514): Headers:
W/ApiaryClient( 6514): accept-encoding: [gzip]
W/ApiaryClient( 6514): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6514): gdata-version: 2
,E/BooksSync( 6514): Soft error: 
E/BooksSync( 6514): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6514): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=1299066459825391851&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6514): Headers:
E/BooksSync( 6514): accept-encoding: [gzip]
E/BooksSync( 6514): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6514): gdata-version: 2
E/BooksSync( 6514): 
E/BooksSync( 6514): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6514): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6514): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6514): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6514): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6514): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6514): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6514): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6514): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6514): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6514): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6514): {
E/BooksSync( 6514):  "error": {
E/BooksSync( 6514):   "errors": [
E/BooksSync( 6514):    {
E/BooksSync( 6514):     "domain": "global",
E/BooksSync( 6514):     "reason": "required",
E/BooksSync( 6514):     "message": "Login Required",
E/BooksSync( 6514):     "locationType": "header",
E/BooksSync( 6514):     "location": "Authorization"
E/BooksSync( 6514):    }
E/BooksSync( 6514):   ],
E/BooksSync( 6514):   "code": 401,
E/BooksSync( 6514):   "message": "Login Required"
E/BooksSync( 6514):  }
E/BooksSync( 6514): }
E/BooksSync( 6514): 
E/BooksSync( 6514): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6514): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6514): 	... 8 more
,E/BooksSync( 6514): Sync error
E/BooksSync( 6514): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6514): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=1299066459825391851&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6514): Headers:
E/BooksSync( 6514): accept-encoding: [gzip]
E/BooksSync( 6514): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6514): gdata-version: 2
E/BooksSync( 6514): 
E/BooksSync( 6514): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6514): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6514): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6514): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6514): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6514): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6514): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6514): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6514): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6514): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6514): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6514): {
E/BooksSync( 6514):  "error": {
E/BooksSync( 6514):   "errors": [
E/BooksSync( 6514):    {
E/BooksSync( 6514):     "domain": "global",
E/BooksSync( 6514):     "reason": "required",
E/BooksSync( 6514):     "message": "Login Required",
E/BooksSync( 6514):     "locationType": "header",
E/BooksSync( 6514):     "location": "Authorization"
E/BooksSync( 6514):    }
E/BooksSync( 6514):   ],
E/BooksSync( 6514):   "code": 401,
E/BooksSync( 6514):   "message": "Login Required"
E/BooksSync( 6514):  }
E/BooksSync( 6514): }
E/BooksSync( 6514): 
E/BooksSync( 6514): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6514): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6514): 	... 8 more
I/BooksSync( 6514): Finished books sync
D/SyncManager( 1025): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 249770, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=3.7, 0.0, 0.0  rx=2.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1400698341] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=3.7, 0.0, 0.0  rx=2.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1400698338] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=3.4, 0.0, 0.0  rx=2.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1400695315] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=3.4, 0.0, 0.0  rx=2.4 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1400695304] gl rssi=-62 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=2.2, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1400692282] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=2.2, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1400692281] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=4.1, 0.0, 0.0  rx=3.3 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1400689272] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=4.1, 0.0, 0.0  rx=3.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1400689269] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=2.5, 0.0, 0.0  rx=2.2 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1400686245] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=2.5, 0.0, 0.0  rx=2.2 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1400686236] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1025): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1025): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1025): tsOffsetIs: Apps: 267629695993; DSPS: 8910583; Offset : -4313850777
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.3, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1400683215] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.3, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1400683205] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1400680185] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1400680172] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1400677151] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1400677148] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1400674121] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1400674118] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,V/AlarmManager( 1025): ELAPSED_WAKEUP set : Alarm{2098857f type 2 when 279995 android} when 279995
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1400671092] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1400671089] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1400668062] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1400668059] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1025): tsOffsetIs: Apps: 287631926611; DSPS: 9566016; Offset : -4313847735
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1400665033] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1400665030] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1400662005] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1400661995] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1400658973] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1400658970] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1400655942] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1400655939] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
,I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1400652913] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1400652910] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1400649885] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1400649876] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1400646856] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1400646845] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1025): tsOffsetIs: Apps: 307634002228; DSPS: 10221444; Offset : -4313847443
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1400643824] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1400643821] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1400640793] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1400640790] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1400637765] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1400637755] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1400634735] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1400634723] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1400631702] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1400631699] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1400628677] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1400628668] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1025): tsOffsetIs: Apps: 327635868523; DSPS: 10876865; Offset : -4313842642
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1400625646] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1400625637] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1400622616] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1400622605] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1400619583] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1400619580] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1400616556] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1400616546] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1400613525] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1400613514] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1400610494] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1400610490] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1400607463] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1400607460] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,D/PowerManagerServiceEx( 1025): acquireWakeLockInternal: lock=1033378170, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1025
,D/[Concierge]Service( 2576): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1025): releaseWakeLockInternal: lock=1033378170 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1025): tsOffsetIs: Apps: 347637924504; DSPS: 11532293; Offset : -4313861882
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1400604436] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1400604426] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1400601406] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1400601395] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1400598374] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1400598371] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1400595338] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1400595335] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
,I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
,I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1400592312] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1400592309] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1400589287] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1400589278] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.5, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1400586256] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.5, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1400586244] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1025): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1025): tsOffsetIs: Apps: 367640698092; DSPS: 12187744; Offset : -4313865394
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1400583222] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1400583219] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=2.9, 0.0, 0.0  rx=3.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1400580195] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=2.9, 0.0, 0.0  rx=3.3 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1400580185] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1400577163] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1400577160] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1400574133] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1400574130] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1400571105] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1400571096] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
D/PowerManagerServiceEx( 1025): acquireWakeLockInternal: lock=1033378170, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1025
,V/AlarmManager( 1025): ELAPSED_WAKEUP set : Alarm{18d7b94c type 2 when 383134 android} when 383134
D/[Concierge]Service( 2576): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1025): releaseWakeLockInternal: lock=1033378170 [*alarm*], flags=0x0
,I/BooksSync( 6514): Starting books sync
,D/BooksSync( 6514): started syncMyEbooks
,V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2057): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2057): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2057): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2057): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1025): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1025): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1025): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1025): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1025): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/GLSActivity( 2057): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2057): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2057): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2057): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2057): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2057): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2057): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6514): Authentication error
E/BooksAccountManager( 6514): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6514): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6514): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6514): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6514): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6514): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6514): null auth token
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{19c16502 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6514): Error response from books API: {
W/ApiaryClient( 6514):  "error": {
W/ApiaryClient( 6514):   "errors": [
W/ApiaryClient( 6514):    {
W/ApiaryClient( 6514):     "domain": "global",
W/ApiaryClient( 6514):     "reason": "required",
W/ApiaryClient( 6514):     "message": "Login Required",
W/ApiaryClient( 6514):     "locationType": "header",
W/ApiaryClient( 6514):     "location": "Authorization"
W/ApiaryClient( 6514):    }
W/ApiaryClient( 6514):   ],
W/ApiaryClient( 6514):   "code": 401,
W/ApiaryClient( 6514):   "message": "Login Required"
W/ApiaryClient( 6514):  }
W/ApiaryClient( 6514): }
,W/ApiaryClient( 6514): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6514): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=4457480477914762188&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6514): Headers:
W/ApiaryClient( 6514): accept-encoding: [gzip]
W/ApiaryClient( 6514): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6514): gdata-version: 2
,V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2057): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2057): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2057): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2057): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1025): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1025): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1025): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1025): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1025): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
,D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1411): updateNotificationData: count=3
W/GLSActivity( 2057): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2057): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2057): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2057): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2057): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2057): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2057): 	at android.os.Binder.execTransact(Binder.java:446)
,D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{19c16502 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
E/BooksAccountManager( 6514): Authentication error
E/BooksAccountManager( 6514): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6514): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6514): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6514): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6514): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6514): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6514): null auth token
,W/ApiaryClient( 6514): Error response from books API: {
W/ApiaryClient( 6514):  "error": {
W/ApiaryClient( 6514):   "errors": [
W/ApiaryClient( 6514):    {
W/ApiaryClient( 6514):     "domain": "global",
W/ApiaryClient( 6514):     "reason": "required",
W/ApiaryClient( 6514):     "message": "Login Required",
W/ApiaryClient( 6514):     "locationType": "header",
W/ApiaryClient( 6514):     "location": "Authorization"
W/ApiaryClient( 6514):    }
W/ApiaryClient( 6514):   ],
W/ApiaryClient( 6514):   "code": 401,
W/ApiaryClient( 6514):   "message": "Login Required"
W/ApiaryClient( 6514):  }
W/ApiaryClient( 6514): }
,W/ApiaryClient( 6514): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6514): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=4457480477914762188&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6514): Headers:
W/ApiaryClient( 6514): accept-encoding: [gzip]
W/ApiaryClient( 6514): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6514): gdata-version: 2
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1400568074] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1400568071] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2057): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2057): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2057): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2057): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1025): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1025): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1025): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1025): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1025): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2057): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2057): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2057): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2057): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2057): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2057): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2057): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6514): Authentication error
E/BooksAccountManager( 6514): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6514): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6514): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6514): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6514): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6514): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6514): null auth token
W/ResourcesManager( 1411): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1411): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
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
W/ResourcesManager( 1411): Asset path '/system/framework/com.lge.systemui.jar' does not exist or contains no resources.
W/ResourcesManager( 1411): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1411): updateNotificationData: count=3
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{19c16502 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6514): Error response from books API: {
W/ApiaryClient( 6514):  "error": {
W/ApiaryClient( 6514):   "errors": [
W/ApiaryClient( 6514):    {
W/ApiaryClient( 6514):     "domain": "global",
W/ApiaryClient( 6514):     "reason": "required",
W/ApiaryClient( 6514):     "message": "Login Required",
W/ApiaryClient( 6514):     "locationType": "header",
W/ApiaryClient( 6514):     "location": "Authorization"
W/ApiaryClient( 6514):    }
W/ApiaryClient( 6514):   ],
W/ApiaryClient( 6514):   "code": 401,
W/ApiaryClient( 6514):   "message": "Login Required"
W/ApiaryClient( 6514):  }
W/ApiaryClient( 6514): }
,W/ApiaryClient( 6514): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6514): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=4457480477914762188&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6514): Headers:
W/ApiaryClient( 6514): accept-encoding: [gzip]
W/ApiaryClient( 6514): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6514): gdata-version: 2
,E/BooksSync( 6514): Soft error: 
E/BooksSync( 6514): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6514): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=4457480477914762188&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6514): Headers:
E/BooksSync( 6514): accept-encoding: [gzip]
E/BooksSync( 6514): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6514): gdata-version: 2
E/BooksSync( 6514): 
E/BooksSync( 6514): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6514): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6514): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6514): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6514): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6514): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6514): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6514): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6514): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6514): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6514): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6514): {
E/BooksSync( 6514):  "error": {
E/BooksSync( 6514):   "errors": [
E/BooksSync( 6514):    {
E/BooksSync( 6514):     "domain": "global",
E/BooksSync( 6514):     "reason": "required",
E/BooksSync( 6514):     "message": "Login Required",
E/BooksSync( 6514):     "locationType": "header",
E/BooksSync( 6514):     "location": "Authorization"
E/BooksSync( 6514):    }
E/BooksSync( 6514):   ],
E/BooksSync( 6514):   "code": 401,
E/BooksSync( 6514):   "message": "Login Required"
E/BooksSync( 6514):  }
E/BooksSync( 6514): }
E/BooksSync( 6514): 
E/BooksSync( 6514): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6514): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6514): 	... 8 more
,E/BooksSync( 6514): Sync error
E/BooksSync( 6514): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6514): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=4457480477914762188&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6514): Headers:
E/BooksSync( 6514): accept-encoding: [gzip]
E/BooksSync( 6514): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6514): gdata-version: 2
E/BooksSync( 6514): 
E/BooksSync( 6514): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6514): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6514): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6514): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6514): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6514): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6514): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6514): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6514): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6514): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6514): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6514): {
E/BooksSync( 6514):  "error": {
E/BooksSync( 6514):   "errors": [
E/BooksSync( 6514):    {
E/BooksSync( 6514):     "domain": "global",
E/BooksSync( 6514):     "reason": "required",
E/BooksSync( 6514):     "message": "Login Required",
E/BooksSync( 6514):     "locationType": "header",
E/BooksSync( 6514):     "location": "Authorization"
E/BooksSync( 6514):    }
E/BooksSync( 6514):   ],
E/BooksSync( 6514):   "code": 401,
E/BooksSync( 6514):   "message": "Login Required"
E/BooksSync( 6514):  }
E/BooksSync( 6514): }
E/BooksSync( 6514): 
E/BooksSync( 6514): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6514): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6514): 	... 8 more
I/BooksSync( 6514): Finished books sync
D/SyncManager( 1025): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 383134, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1025): tsOffsetIs: Apps: 387642130375; DSPS: 12843150; Offset : -4313836842
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=3.1, 0.0, 0.0  rx=2.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1400565049] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=3.1, 0.0, 0.0  rx=2.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1400565046] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=4.0, 0.0, 0.0  rx=2.6 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1400562025] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=4.0, 0.0, 0.0  rx=2.6 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1400562015] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=2.0, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1400558995] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=2.0, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1400558984] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1400555963] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1400555960] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1400552940] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1400552937] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1400549912] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1400549909] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1400546886] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1400546877] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1025): tsOffsetIs: Apps: 407644092607; DSPS: 13498575; Offset : -4313858383
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1400543860] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1400543857] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1400540830] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1400540827] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,V/AlarmManager( 1025): ELAPSED_WAKEUP set : Alarm{1f959cd6 type 2 when 413348 android} when 413348
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1400537804] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1400537800] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1400534775] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1400534764] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1400531742] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1400531739] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1400528714] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1400528710] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 2057): Explicit concurrent mark sweep GC freed 42022(2MB) AllocSpace objects, 22(3MB) LOS objects, 51% free, 30MB/62MB, paused 2.130ms total 65.083ms
,I/GLSUser ( 2057): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 2057): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2057): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2057): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2057): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1025): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1025): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1025): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1025): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1025): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2057): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2057): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2057): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2057): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2057): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2057): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2057): 	at android.os.Binder.execTransact(Binder.java:446)
E/PlayEventLogger( 6997): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6997): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6997): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 6997): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6997): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 6997): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6997): 	at android.os.Binder.execTransact(Binder.java:446)
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
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{19c16502 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/System  ( 6997): Ignoring header User-Agent because its value was null.
,D/libc-netbsd(  316): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  316): res_queryN name = play.googleapis.com, class = 1, type = 1
D/libc-netbsd(  316): res_queryN name = play.googleapis.com succeed
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1025): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1025): tsOffsetIs: Apps: 427646054631; DSPS: 14153999; Offset : -4313849405
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1400525681] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1400525678] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=5.5, 0.0, 0.0  rx=4.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1400522667] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=5.5, 0.0, 0.0  rx=4.5 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1400522656] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=2.8, 0.0, 0.0  rx=2.3 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1400519635] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=2.8, 0.0, 0.0  rx=2.3 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1400519622] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1400516601] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1400516598] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.7, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1400513575] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.7, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1400513565] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1400510545] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1400510533] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1025):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1400507513] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1025):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1400507510] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1025): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1025): tsOffsetIs: Apps: 447647875039; DSPS: 14809419; Offset : -4313860130
,I/wpa_supplicant( 6116): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/Tethering( 1025): InitialState.processMessage what=4
,D/Tethering( 1025): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiMonitor( 1025): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0]
E/WifiMonitor( 1025): WifiMonitor:wlan0 cnt=25 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
E/WifiStateMachine( 1025):  ConnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1025):  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1025):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1025):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1025):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1025):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiMonitor( 1025): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
D/WifiMonitor( 1025): handleNetworkStateChange: Could not parse disconnect string
E/WifiMonitor( 1025): WifiMonitor notify network disconnect: null reason=0
D/WifiMonitor( 1025): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1025): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,E/WifiStateMachine( 1025):  ConnectedState NETWORK_DISCONNECTION_EVENT nid=0 reason=0 lastbssid=c0:ff:d4:d3:aa:48 freq=2412 rssi=-63 rt=447797
E/WifiStateMachine( 1025):  L2ConnectedState NETWORK_DISCONNECTION_EVENT nid=0 reason=0 lastbssid=c0:ff:d4:d3:aa:48 freq=2412 rssi=-63 rt=447797
E/WifiStateMachine( 1025):  ConnectModeState NETWORK_DISCONNECTION_EVENT nid=0 reason=0 lastbssid=c0:ff:d4:d3:aa:48 freq=2412 rssi=-63 rt=447797
E/WifiConfigStore( 1025): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1025): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1025): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1025): doBoolean: SAVE_CONFIG
,D/WifiNative-wlan0( 1025): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1025): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 6116): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1025): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1025): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1025): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1025): doBoolean: SET ps 1
D/WifiNative-wlan0( 1025): SET ps 1: returned true
D/CommandListener(  316): Clearing all IP addresses on wlan0
,D/DhcpStateMachine( 1025): RunningState{ when=-11ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
V/NativeCrypto( 2057): Read error: ssl=0xaa759600: I/O error during system call, Connection timed out
D/WifiMonitor( 1025): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1025): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,V/NativeCrypto( 2057): SSL shutdown failed: ssl=0xaa759600: I/O error during system call, Broken pipe
I/ActivityManager( 1025): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=7531 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/wpa_supplicant( 6116): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1025): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1025): WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1025): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1025): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/ConnectivityService( 1025): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,D/ConnectivityService( 1025): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/WifiHS20( 1025): hidePasspointNotification off =false
I/StatusBar.NetworkController( 1465): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1465): mWifiConnected = false, mWifiLevel = 0
,V/WfdStateTracker( 1928): handleWifiStateChangedEvent: 0
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1025): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 1025): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1025): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1025): WifiStateMachine: Leaving Connected state
D/WifiHS20( 1025): hidePasspointNotification off =false
W/Settings( 1025): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1025): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1025): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,I/jxcore-log( 6035): Toggling radios to false
I/jxcore-log( 6035): 
I/StatusBar.NetworkController( 1465): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1465): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1025):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=447962  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1025):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=447962  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1025):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=447963  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine( 1025):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=447965  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine( 1025):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiHS20( 1025): hidePasspointNotification off =false
,D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1025):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1025):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1025):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1025):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1025):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
W/Settings( 1025): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1025): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1025): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1025):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1025):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1025):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1025):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
I/StatusBar.NetworkController( 1465): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1465): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService( 1025): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1025): ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1025): DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1025): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1025): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1025): Checking http://clients3.google.com/generate_204 on <unknown ssid>
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1465): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1465): mWifiConnected = false, mWifiLevel = 0
,D/WifiNetworkAgent( 1025): NetworkAgent: NetworkAgent channel lost
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1025): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1025): disableDataServiceNotify
D/libc-netbsd(  316): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1025): stop dsqn bin
W/Settings( 1025): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1025): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1025): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/BluetoothManagerService( 1025): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1025): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@330d0061 mBinding = false
D/DSQN    ( 1025): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1025): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/WifiServerServiceExt( 1025): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1025): setSupplicantStateDISCONNECTED
D/WifiServerServiceExt( 1025): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1025): setSupplicantStateSCANNING
D/ConnectivityService( 1025): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1025):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1025):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService( 1025): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat( 1025): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1025): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1025): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1025): Disconnected - quitting
D/CSLegacyTypeTracker( 1025): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/ConnectivityManager.CallbackHandler( 1465): CM callback handler got msg 524292
D/CSLegacyTypeTracker( 1025): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1025): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1025): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1025): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1025): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1025): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1025): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1839): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1025): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1839):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/WIFI    ( 1025):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkManagementService( 1025): Removing idletimer
W/Settings( 1025): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1025): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
E/ConnectivityService( 1025): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
V/NetworkPolicy( 1025): [LG_RESTRICTED] !!!isConnected  type  :1
D/LocSvc_java( 1025): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1025): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1025): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1025): ignore wifi update if we are not in OPENING or CLOSING
V/NetworkPolicy( 1025): [LG_RESTR,ICTED] !!!isConnected  type  :1
D/LocSvc_java( 1025): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1025): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1025): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1025): ignore wifi update if we are not in OPENING or CLOSING
D/BluetoothManagerService( 1025): Message: 2
,D/BluetoothManagerService( 1025): Sending off request.
D/WifiServiceImplEx( 1025): setWifiEnabled: false pid=6035, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1025): setWifiEnabled: false pid=6035, uid=10311
E/WifiService( 1025): Invoking mWifiStateMachine.setWifiEnabled
D/LocationManagerService( 1025): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1025): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1025): JNI:system_update. Event-4
D/LGBluetoothServiceAdapter( 6089): [BTUI] Precleanup
D/BluetoothAdapterState( 6089): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 6089): Setting state to 13
I/BluetoothAdapterState( 6089): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterProperties( 6089): onBluetoothDisable()
I/BluetoothAdapterState( 6089): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
D/BluetoothAdapterProperties( 6089): Scan Mode:20
D/BluetoothAdapterState( 6089): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
W/bt-l2cap( 6089): L2CAP - L2CA_Deregister() called for PSM: 0x000f
V/BluetoothFtpService:RfcommSocketAcceptThread( 6089): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
W/bt-btif ( 6089): bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
D/btif_config_util( 6089): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
V/BluetoothPbapService( 6089): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/BtOppRfcommListener( 6089): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothSapService( 6089): Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 6089): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 6089): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 6089): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
V/BluetoothMapMasInstance( 6089): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
V/BluetoothMapMasInstance( 6089): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
V/BluetoothMapMasInstance( 6089): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 6089): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 6089): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
W/bt-l2cap( 6089): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 6089): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 6089): L2CAP - L2CA_Deregister() called for PSM: 0x001b
,W/bt-l2cap( 6089): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 6089): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 6089): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 6089): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 6089): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 6089): L2CAP - PSM: 0x001b not found for deregistration
D/BluetoothManagerService( 1025): Message: 60
W/bt-l2cap( 6089): L2CAP - L2CA_Deregister() called for PSM: 0x0011
W/bt-l2cap( 6089): L2CAP - L2CA_Deregister() called for PSM: 0x0013
D/BluetoothManagerService( 1025): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService( 1025): Bluetooth State Change Intent: 12 -> 13
E/bt-btif ( 6089): bta_gattc_deregister Deregister Failedm unknown client cif
D/LGBluetoothAPIService( 1928): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
I/BluetoothMapService( 6089): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 6089): STATE_TURNING_OFF
V/BluetoothMapService( 6089): Handler(): got msg=4
D/BluetoothMapService( 6089): MAP Service closeService in
D/BluetoothMapMasInstance( 6089): MAP Service shutdown
D/LGBluetoothMapAdapter( 6089): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 6089): MAP Service closeService out
V/BtOppService( 6089): Receiver DISABLED_ACTION 
I/BtOppRfcommListener( 6089): stopping Accept Thread
V/BtOppRfcommListener( 6089): close mBtServerSocket
V/BtOppRfcommListener( 6089): waiting for thread to terminate
E/WifiStateMachine( 1025):  DisconnectedState CMD_STOP_SUPPLICANT 0 0
I/jxcore-log( 6035): Radios toggled
I/jxcore-log( 6035): 
I/BtOppRfcommListener( 6089): BluetoothSocket listen thread finished
E/WifiStateMachine( 1025):  ConnectModeState CMD_STOP_SUPPLICANT 0 0
V/BtOppRfcommListener( 6089): done waiting for thread to terminate
E/WifiStateMachine( 1025):  DriverStartedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1025):  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
D/LocationManagerService( 1025): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1025): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1025): JNI:system_update. Event-4
V/BtOppService( 6089): onDestroy
D/LGBluetoothOppAdapter( 6089): [BTUI] LGBluetoothOppAdapter cleanup
,D/LGWifiP2pService( 1025): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1025): P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1025): stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@98905d9
D/LGWifiP2pService( 1025): P2pDisablingState
D/LGWifiP2pService( 1025): P2pDisablingState{ when=-2ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1025): p2p socket connection lost
D/LGWifiP2pService( 1025): P2pDisabledState
E/WifiStateMachine( 1025):  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
D/WifiNative-wlan0( 1025): doBoolean: DRIVER BTCOEXMODE 2
D/LGWifiP2pService( 1025): P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService( 1025): SCAN_AVAILABLE : 1
I/wpa_supplicant( 6116): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/RttService( 1025): SCAN_AVAILABLE : 1
D/WifiNative-wlan0( 1025): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1025): doBoolean: SET ps 1
,D/WifiScanningService( 1025): DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1025): DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1025): SET ps 1: returned true
D/RttService( 1025): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  316): Clearing all IP addresses on wlan0
V/WfdStateTracker( 1928): WfdStateTracker handleDirectStateChangedEvent: 0
D/WfdsService( 1928): WifiP2pState is changed : false
D/WfdsService( 1928): WfdsEnabledState: Receive the WFDS_DISABLE message
D/WfdsService( 1928): Set the WFDS Monitor: false
D/WfdsMonitor( 1928): WFDS Monitor is stopped
D/CtrlSupplicant( 1928): Received on exit socket, terminate
E/CtrlSupplicant( 1928): wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
D/WfdsService( 1928): STATE : WfdsDisabledState - enter
D/WfdsMonitor( 1928): Event [CTRL-EVENT-TERMINATING  - connection closed]
D/WfdsMonitor( 1928): WfdsMonitorThread is received the interrupt - closing
W/WfdsService( 1928): DefaultState - msg [9445378] is not handled
W/WfdsSession:Controller( 1928): DefaultState - msg [9441355] is not handled
D/WifiNative-p2p0( 1025): doBoolean: TERMINATE
D/WifiHS20( 1025): hidePasspointNotification off =false
D/WifiNative-p2p0( 1025): TERMINATE: returned true
E/WifiStateMachine( 1025): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1025): useWiFiOffloading() : false
E/WifiStateMachine( 1025): CONFIG_LGE_WLAN_PATH : true
W/Settings( 1025): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1025): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1025): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20( 1025): hidePasspointNotification off =false
W/Settings( 1025): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1025): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1025): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
V/WfdStateTracker( 1928): WfdStateTracker handleDirectStateChangedEvent: 6
,I/WifiServerServiceExt( 1025): WIFI_STATE_CHANGED_ACTION [0]
D/TelephonyIcons( 1465): null signal icon name: drawable/stat_sys_signal_null
I/GoogleURLConnFactory( 2057): Using platform SSLCertificateSocketFactory
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
,W/ResourcesManager( 7531): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7531): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 7531): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/TelephonyIcons( 1465): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
I/[SystemUI]BluetoothHandler( 1465): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
W/Uploader( 2057): No account for auth token provided
W/ResourcesManager( 7531): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
D/libc-netbsd(  316): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1025): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/Uploader( 2057): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
W/ResourcesManager( 7531): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7531): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/StatusBar.NetworkController( 1465): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1465): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1465): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1465): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
D/DhcpStateMachine( 1025): StoppedState
D/DhcpStateMachine( 1025): StoppedState{ when=-128ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 1025):  SupplicantStoppingState CMD_ON_QUIT 0 0
E/WifiStateMachine( 1025):  DefaultState CMD_ON_QUIT 0 0
,W/ContextImpl( 7531): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,D/UsbSettingsReceiver( 7531): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7531): [AUTORUN] sys.usb.config = ptp_only,adb
,D/UsbSettingsReceiver( 7531): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7531): [AUTORUN] persist.sys.usb.config = ptp_only,adb
V/BluetoothPbapReceiver( 6089): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 6089): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6089): ***********state = 13
D/UsbSettingsReceiver( 7531): [AUTORUN] onReceive() : app userid = 0, current userid = 0
V/BluetoothPbapReceiver( 6089): ***********Calling start service!!!! with action = null
V/BluetoothPbapService( 6089): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 6089): state: 13
V/BluetoothPbapService( 6089): Pbap Service closeService in
I/ActivityManager( 1025): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7577 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
V/BluetoothPbapService( 6089): successfully stopped pbap service
V/BluetoothPbapService( 6089): Pbap Service closeService out
V/BluetoothPbapService( 6089): Pbap Service onDestroy
V/BluetoothPbapService( 6089): Pbap Service closeService in
V/BluetoothPbapService( 6089): Pbap Service closeService out
D/LGBluetoothPbapAdapter( 6089): [BTUI] cleanup
,D/UsbSettingsControl( 7531): [AUTORUN] getUsbConnected() : connected=true
,D/UsbSettingsReceiver( 7531): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 7531): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7531): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7531): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 7531): [AUTORUN] setTetherStatus() : status=false
D/BluetoothManagerService( 1025): Message: 20
D/BluetoothManagerService( 1025): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@422d7e0:true
,I/ActivityManager( 1025): Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=7595 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/BluetoothManagerService( 1025): Message: 30
,D/BluetoothManagerService( 1025): Message: 30
D/LocalBluetoothProfileManager( 7531): Adding local MAP profile
,D/BluetoothMap( 7531): Create BluetoothMap proxy object
D/BluetoothManagerService( 1025): Message: 30
D/BluetoothManagerService( 1025): Message: 30
,D/LocalBluetoothProfileManager( 7531): LocalBluetoothProfileManager construction complete
,D/LGBluetoothFeatureConfig( 7531):  get() - isFeatureLoaded : false
W/ResourcesManager( 7595): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/LGBluetoothUserBindClient( 7531): [BTUI] initUserBindClient
E/ActivityThread( 7577): Failed to find provider info for com.lge.lgaccount.provider
,W/LG Account v2.2( 7577): No ProfileInfo entries
I/LG Account v2.2( 7577): isEnabled: false
I/Feature ( 7577): [Lifetracker]ver: 4.21.112(40211120)
I/Feature ( 7577): [Lifetracker]Country: EU
,I/Feature ( 7577): [Lifetracker]Operator: OPEN
I/Feature ( 7577): [Lifetracker]Ranking support: false
I/Feature ( 7577): [Lifetracker]Comfort support: false
I/Feature ( 7577): [Lifetracker]Accessory: true
I/Feature ( 7577): [Lifetracker]Health device: true
I/Feature ( 7577): [Lifetracker]Extra Pedometer: false
I/Feature ( 7577): [Lifetracker]Blood glucose device: false
W/ContextImpl( 7531): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
I/Feature ( 7577): [Lifetracker]Device Number: 3
I/ActivityManager( 1025): Killing 6845:com.android.calendar/u0a13 (adj 15): empty #17
D/PluginManager( 7595): init()
W/libprocessgroup( 1025): failed to open /acct/uid_10013/pid_6845/cgroup.procs: No such file or directory
,D/DockEventReceiver( 7531): finishStartingService: stopping service
D/BluetoothInputDevice( 7531): Proxy object connected
D/HidProfile( 7531): Bluetooth service connected
D/BluetoothPan( 7531): BluetoothPAN Proxy object connected
D/PanProfile( 7531): Bluetooth service connected
D/BluetoothMap( 7531): Proxy object connected
D/MapProfile( 7531): Bluetooth service connected
,D/BluetoothMap( 7531): getConnectedDevices()
D/BluetoothMap( 7531): Bluetooth is Not enabled
D/LGBluetoothUserBindClient( 7531): [BTUI] onServiceConnected
,D/LGBluetoothAuthorization( 7531): [BTUI] cancel All Notification
D/BluetoothPermissionRequest( 7531): onReceive
D/LGBluetoothAuthorization( 7531): [BTUI] cancel All Notification
,D/LGBluetoothResetSettingReceiver( 7531): return without doing reset settings.
,I/ActivityManager( 1025): Killing 6786:com.lge.clock/u0a10 (adj 15): empty #17
,W/libprocessgroup( 1025): failed to open /acct/uid_10010/pid_6786/cgroup.procs: No such file or directory
,V/BluetoothOppReceiver( 6089): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
D/BluetoothOppNotification( 6089): [BTUI] cancel opp incoming file confirm notification
D/BluetoothOppNotification( 6089): [BTUI] cancel opp active transfer file notification
V/BluetoothFtpReceiver( 6089): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpReceiver( 6089): BluetoothFtpReceiver Start Service
V/BluetoothFtpService( 6089): Ftp Service onStartCommand
V/BluetoothFtpService( 6089): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpService( 6089): Ftp Service closeService
,E/BluetoothFtpService:RfcommSocketAcceptThread( 6089): Shutdown
V/BluetoothFtpService( 6089): successfully stopped ftp service
V/BluetoothFtpService( 6089): Ftp Service onDestroy
V/BluetoothFtpService( 6089): Ftp Service closeService
V/BluetoothSapReceiver( 6089): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 6089): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 6089): SapReceiver onReceive 
V/BluetoothSapReceiver( 6089): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6089):  Bluetooth Adapter state = 13
V/BluetoothSapReceiver( 6089): Calling SAP service start service with action = null
V/BluetoothSapService( 6089): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 6089): state: 13
V/BluetoothSapService( 6089): Stopping SAP server process
V/BluetoothSapService( 6089): Sap Service closeSapService in
V/BluetoothSapService( 6089): Close listen Socket : 
V/BluetoothSapService( 6089): Close rfcomm Socket : 
V/BluetoothSapService( 6089): Close sapd  Socket : 
,I/ActivityManager( 1025): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7624 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,V/BluetoothSapService( 6089): Sap Service closeSapService out
V/BluetoothSapService( 6089): Sap Service onDestroy
V/BluetoothSapService( 6089): Sap Service closeSapService in
V/BluetoothSapService( 6089): Close listen Socket : 
V/BluetoothSapService( 6089): Close rfcomm Socket : 
V/BluetoothSapService( 6089): Close sapd  Socket : 
V/BluetoothSapService( 6089): Sap Service closeSapService out
,W/ResourcesManager( 7624): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/ActivityManager( 1025): Killing 6660:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,W/ExternalStrings( 7595): load override strings
W/ExternalStrings( 7595): java.lang.RuntimeException: Unexpected tag, got eat-comment
W/ExternalStrings( 7595): 	at com.mcafee.plugin.af.a(Unknown Source)
W/ExternalStrings( 7595): 	at com.mcafee.plugin.ac.b(Unknown Source)
W/ExternalStrings( 7595): 	at com.mcafee.plugin.ak.d(Unknown Source)
W/ExternalStrings( 7595): 	at com.mcafee.plugin.ak.a(Unknown Source)
W/ExternalStrings( 7595): 	at com.mcafee.app.s.getClassLoader(Unknown Source)
W/ExternalStrings( 7595): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
W/ExternalStrings( 7595): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
W/ExternalStrings( 7595): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
W/ExternalStrings( 7595): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
W/ExternalStrings( 7595): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
W/ExternalStrings( 7595): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ExternalStrings( 7595): 	at android.os.Looper.loop(Looper.java:135)
W/ExternalStrings( 7595): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/ExternalStrings( 7595): 	at java.lang.reflect.Method.invoke(Native Method)
W/ExternalStrings( 7595): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/ExternalStrings( 7595): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/ExternalStrings( 7595): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
W/libprocessgroup( 1025): failed to open /acct/uid_10085/pid_6660/cgroup.procs: No such file or directory
D/AuthorizationBluetoothService( 2057): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/StatusProvider( 7595): onCreate
E/WifiStateMachine( 1025):  SupplicantStoppingState CMD_RSSI_POLL 1 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1400504486] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1025):  DefaultState CMD_RSSI_POLL 1 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1400504485] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,V/Signer  ( 7595): override build config not found
,D/Signer  ( 7595): value of property debug is false
,D/LGMDMWrapper( 7595): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
,D/LGMDMWrapper( 7595): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
D/LGMDMWrapper( 7595): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
D/LGMDMWrapper( 7595): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
,D/LGMDMWrapper( 7595): Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
,D/LGMDMWrapper( 7595): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
D/LGMDMWrapper( 7595): Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
D/LGMDMWrapper( 7595): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
,D/LGMDMWrapper( 7595): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
D/LGMDMWrapper( 7595): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
D/LGMDMWrapper( 7595): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
D/LGMDMWrapper( 7595): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
,D/LGMDMWrapper( 7595): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
,V/LGMDMManager( 7595): Create singleton instance
D/LGMDMWrapper( 7595): LG MDM library v4.0.0 is available on this device.
,W/bt-btif ( 6089): ag scb idx 1 not allocated
,D/bt_hci_bdroid( 6089): cleanup
,E/bt-btif ( 6089): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 6089): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 6089): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 6089): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 6089): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 6089): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 6089): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 6089): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 6089): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 6089): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 6089): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 6089): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 6089): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 6089): L2CAP - L2CA_Deregister() called for PSM: 0x0019
,W/bt-l2cap( 6089): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 6089): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 6089): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 6089): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 6089): L2CAP - PSM: 0x001b not found for deregistration
E/bt-btif ( 6089): bta_gattc_deregister Deregister Failedm unknown client cif
I/bt_userial_mct( 6089): exiting userial_read_thread
D/bt_userial_mct( 6089): Leaving userial_evt_read_thread()
I/bt_lpm  ( 6089): LPM is already off!!!
D/bt_userial_mct( 6089): userial_close_reader Joined userial reader thread: 0
I/bt_vendor( 6089): hw_epilog_process
,D/bt_hci_bdroid( 6089): cleanup Finalizing cleanup
D/bt_userial_mct( 6089): userial_close
E/bt_userial_mct( 6089): pthread_join() FAILED result:3
I/bt_vendor( 6089): bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
D/PostponalbeReceiver( 7595): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 7595): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,I/ActivityManager( 1025): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7647 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1025): Killing 6875:com.google.android.talk/u0a72 (adj 15): empty #17
,D/bt_hci_bdroid( 6089): set_power 0
,I/bt_vendor( 6089): bt-vendor : BT_VND_OP_POWER_CTRL: Off
I/bt_vendor( 6089): bluetooth satus is on
I/bt_vendor( 6089): bt-vendor : resetting BT status
I/bt_vendor( 6089): Starting hciattach daemon
I/bt_vendor( 6089): try to set false
I/bt_vendor( 6089): Starting hciattach daemon
I/bt_vendor( 6089): try to set false
I/bt_vendor( 6089): cleanup
I/GKI_LINUX( 6089): gki_task task_id=0 [BTU] terminating
W/libprocessgroup( 1025): failed to open /acct/uid_10072/pid_6875/cgroup.procs: No such file or directory
,I/GKI_LINUX( 6089): GKI_exit_task 0 done
,I/GKI_LINUX( 6089): GKI_shutdown(): task [BTU] terminated
D/BluetoothAdapterState( 6089): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/HeadsetService( 6089): Received stop request...Stopping profile...
I/LGBluetoothHfpAdapter( 6089): [BTUI] LGBluetoothHfpAdapter cleanup
W/LGBluetoothHeadsetServiceJni( 6089): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 6089): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c26fccb
,D/HeadsetStateMachine( 6089): Exit Disconnected: -1
D/BluetoothHeadset( 1025): Proxy object disconnected
D/BluetoothHeadset( 1839): Proxy object disconnected
D/BluetoothHeadset( 1839): Proxy object disconnected
D/AudioService( 1025): onServiceDisconnected: Bluetooth profile: 1
D/A2dpService( 6089): Received stop request...Stopping profile...
D/LGBluetoothAvrcpQcomAdapter( 6089): [BTUI] cleanup
D/A2dpStateMachine( 6089): Exit Disconnected: -1
D/BluetoothHeadset( 1839): Proxy object disconnected
D/LGBluetoothA2dpAdapter( 6089): [BTUI] LGBluetoothA2dpAdapter cleanup
W/LGBluetoothA2dpServiceJni( 6089): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 6089): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c26fccb
D/BluetoothA2dp( 1025): Proxy object disconnected
D/AudioService( 1025): onServiceDisconnected: Bluetooth profile: 2
D/HeadsetStateMachine( 6089): Unbinding service...
W/ActivityThread( 7595): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/BluetoothAdapterState( 6089): Stopping profile services that were post enabled
D/HeadsetPhoneState( 6089): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 6089): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetPhoneState( 6089): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 6089): [BTUI] listenForMultiSimPhoneState : start = false
W/BluetoothHeadsetServiceJni( 6089): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 6089): Cleaning up Bluetooth Handsfree callback object
I/LGBluetoothHfpAdapter( 6089): [BTUI] LGBluetoothHfpAdapter cleanup
D/HidService( 6089): Received stop request...Stopping profile...
D/BluetoothAdapterService( 6089): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c26fccb
D/HealthService( 6089): Received stop request...Stopping profile...
D/BluetoothAdapterService( 6089): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c26fccb
D/BluetoothInputDevice( 7531): Proxy object disconnected
D/HidProfile( 7531): Bluetooth service disconnected
D/PanService( 6089): Received stop request...Stopping profile...
D/BluetoothAdapterService( 6089): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c26fccb
D/BtGatt.DebugUtils( 6089): handleDebugAction() action=null
D/BtGatt.GattService( 6089): Received stop request...Stopping profile...
D/BluetoothPan( 7531): BluetoothPAN Proxy object disconnected
D/PanProfile( 7531): Bluetooth service disconnected
D/BtGatt.GattService( 6089): stop()
D/BtGatt.AdvertiseManager( 6089): advertise clients cleared
D/BluetoothAdapterService( 6089): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c26fccb
,I/BluetoothA2dpServiceJni( 6089): cleanupNative
I/GKI_LINUX( 6089): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 6089): GKI_exit_task 2 done
I/GKI_LINUX( 6089): GKI_shutdown(): task [A2DP-MEDIA] terminated
D/BluetoothMapService( 6089): Received stop request...Stopping profile...
D/BluetoothMapService( 6089): stop()
D/BluetoothMapEmailAppObserver( 6089): deinitObservers()
D/BluetoothMapEmailAppObserver( 6089): removeReceiver()
D/BluetoothAdapterService( 6089): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2c26fccb
W/BluetoothHidServiceJni( 6089): Cleaning up Bluetooth HID Interface...
W/BluetoothHidServiceJni( 6089): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 6089): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 6089): Cleaning up Bluetooth Health object
W/LGBluetoothHealthServiceJni( 6089): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 6089): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 6089): Cleaning up Bluetooth PAN callback object
D/BluetoothMap( 7531): Proxy object disconnected
D/MapProfile( 7531): Bluetooth service disconnected
V/BluetoothMapService( 6089): Handler(): got msg=4
D/BluetoothMapService( 6089): MAP Service closeService in
D/LGBluetoothMapAdapter( 6089): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 6089): MAP Service closeService out
D/BluetoothMapService( 6089): cleanup()
D/BluetoothMapService( 6089): MAP Service closeService in
D/LGBluetoothMapAdapter( 6089): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 6089): MAP Service closeService out
D/BluetoothAdapterState( 6089): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 6089): Setting state to 10
I/BluetoothAdapterState( 6089): Bluetooth adapter state changed: 13-> 10
I/BluetoothAdapterState( 6089): Entering OffState
D/BluetoothManagerService( 1025): Message: 60
D/BluetoothManagerService( 1025): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService( 1025): Broadcasting onBluetoothStateChange(false) to 9 receivers.
D/BluetoothHeadset( 1839): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1839): onBluetoothStateChange: up=false
D/BluetoothA2dp( 1025): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1839): onBluetoothStateChange: up=false
D/BluetoothPan( 7531): onBluetoothStateChange on: false
D/BluetoothPbap( 7531): onBluetoothStateChange: up=false
,D/BluetoothMap( 7531): onBluetoothStateChange: up=false
D/BluetoothInputDevice( 7531): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1025): onBluetoothStateChange: up=false
D/BluetoothManagerService( 1025): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService( 1025): Broadcasting onBluetoothServiceDown() to 8 receivers.
D/BluetoothManagerService( 1025): Calling onQBluetoothServiceDown callbacks
D/BluetoothManagerService( 1025): Broadcasting onQBluetoothServiceDown() to 0 receivers.
D/BluetoothManagerService( 1025): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@330d0061 mBinding = false
D/BluetoothManagerService( 1025): Sending unbind request.
D/BluetoothManagerService( 1025): Bluetooth State Change Intent: 13 -> 10
D/LGBluetoothAPIService( 1928): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
I/[SystemUI]BluetoothHandler( 1465): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
D/BluetoothAdapter( 1465): 868837571: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1465): 868837571: getState() :  mService = null. Returning STATE_OFF
D/LGBluetoothAPIService( 1928): Message: 2
,D/LGBluetoothAPIService( 1928): unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@1623665b mBinding = false
D/LGBluetoothAPIService( 1928): Sending unbind request.
D/LGBluetoothFeatureConfig( 7531): isPrivacyLogsEnabled : true
E/LGBluetoothEventManager( 7531): [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
D/LGBluetoothEventManager( 7531): [BTUI] clear device connection state
I/GKI_LINUX( 6089): gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 6089): GKI_exit_task 1 done
I/GKI_LINUX( 6089): GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 6089): cleanupNative: return from cleanup
I/art     ( 6089): --- WEIRD: removing null entry 246
W/art     ( 6089): JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
W/LGBluetoothServiceJni( 6089): Cleaning up Bluetooth Service callback object
D/LGBluetoothSettingsDBObserver( 6089): [BTUI] unregister observer for LG device name DB
W/ContextImpl( 7531): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,I/art     ( 6089): System.exit called, status: 0
I/AndroidRuntime( 6089): VM exiting with result code 0, cleanup skipped.
D/DockEventReceiver( 7531): finishStartingService: stopping service
,V/AudioFlinger(  321): 6089 died, releasing its sessions
V/AudioFlinger(  321):  pid 1839 @ 0
V/AudioFlinger(  321):  pid 3294 @ 1
V/AudioFlinger(  321):  pid 3294 @ 2
D/LGBluetoothUserBindClient( 7531): [BTUI] onServiceDisconnected
I/PCSuite ( 7647): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 7647): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7647): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager( 1025): Process com.android.bluetooth (pid 6089) has died
W/ActivityManager( 1025): Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,V/WiFiOffLoadBroadcast( 7531): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/LgDataFeature( 7531): LgDataFeature() Constructor: none
D/LgDataFeature( 7531): LgDataFeature() Constructor Done, null
,D/WiFiOffLoadBroadcast( 7531): MCCMNC not supported: null
D/BluetoothPermissionRequest( 7531): onReceive
,D/LGBluetoothUtils( 7531): [BTUI] FileNotFound: readProperty
D/BluetoothDiscoverableTimeoutReceiver( 7531): cancelDiscoverableAlarm(): Enter
D/LGBluetoothResetSettingReceiver( 7531): return without doing reset settings.
I/ActivityManager( 1025): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7677 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,I/ActivityManager( 1025): Killing 6942:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,I/art     ( 1025): Explicit concurrent mark sweep GC freed 100784(4MB) AllocSpace objects, 9(912KB) LOS objects, 33% free, 44MB/66MB, paused 2.283ms total 143.789ms
,D/LgDataFeature( 7595): LgDataFeature() Constructor: none
,D/LgDataFeature( 7595): LgDataFeature() Constructor Done, null
,W/libprocessgroup( 1025): failed to open /acct/uid_1000/pid_6942/cgroup.procs: No such file or directory
W/ResourcesManager( 7677): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager( 7677): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7677): Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 7677): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/ActivityManager( 1025): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7695 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,D/BluetoothAdapterApp( 7677): Loading JNI Library
D/BluetoothAdapterApp( 7677): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@10d1fb90 Instance Count = 1
,D/BluetoothAdapterApp( 7677): onCreate
D/ProfileConfigQcom( 7677): [BTUI] HeadsetService is supported
D/ProfileConfigQcom( 7677): Adding HeadsetService
D/ProfileConfigQcom( 7677): [BTUI] A2dpService is supported
D/ProfileConfigQcom( 7677): Adding A2dpService
D/ProfileConfigQcom( 7677): [BTUI] HidService is supported
,D/ProfileConfigQcom( 7677): Adding HidService
D/ProfileConfigQcom( 7677): [BTUI] HealthService is supported
D/ProfileConfigQcom( 7677): Adding HealthService
D/LGBluetoothFeatureConfig( 7677): isSupportPan() :  mTargetOp=OPEN
D/ProfileConfigQcom( 7677): [BTUI] PanService is supported
D/ProfileConfigQcom( 7677): Adding PanService
D/ProfileConfigQcom( 7677): [BTUI] GattService is supported
D/ProfileConfigQcom( 7677): Adding GattService
D/ProfileConfigQcom( 7677): [BTUI] BluetoothMapService is supported
D/ProfileConfigQcom( 7677): Adding BluetoothMapService
D/ProfileConfigQcom( 7677): [BTUI] HeadsetClientService is NOT supported
D/LGBluetoothOppAdapter( 7677): [BTUI] getInstance : create [LGBluetoothOppAdapter]
D/LGBluetoothUserBindClient( 7531): [BTUI] onServiceConnected
W/ResourcesManager( 7695): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
V/LGMDMManagerInternal( 7677): Create singleton instance
D/QRemote ( 7695): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,W/ContextImpl( 7595): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
D/QRemote ( 7695): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,I/QRemote ( 7695): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 7695): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 7695): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 7695): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 7695): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/SiteAdvisor( 7595): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
D/QRemote ( 7695): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7695): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7695): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/SiteAdvisor( 7595): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
D/SiteAdvisor( 7595): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
I/QRemote ( 7695): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/SiteAdvisor( 7595): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
,D/PostponalbeReceiver( 7595): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 7595): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
D/SiteAdvisor( 7595): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
I/SiteAdvisor( 7595): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
,I/PCSuite ( 7647): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7647): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7647): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/SiteAdvisor( 7595): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
D/SiteAdvisor( 7595): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
V/WiFiOffLoadBroadcast( 7531): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/QRemote ( 7695): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
V/BluetoothFtpReceiver( 7677): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 7677): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 7677): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 7677): SapReceiver onReceive 
V/BluetoothSapReceiver( 7677): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 7677):  Bluetooth Adapter state = 10
D/WiFiOffLoadBroadcast( 7531): MCCMNC not supported: null
,D/QRemote ( 7695): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
D/LGBluetoothProfileConnectionReceiver_EasySetting( 7624): [BTUI] STATE_OFF : reset connected device information EasySettings
D/QRemote ( 7695): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7695): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/ActivityManager( 1025): Killing 6968:com.android.providers.calendar/u0a14 (adj 15): empty #17
,D/AuthorizationBluetoothService( 2057): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/libprocessgroup( 1025): failed to open /acct/uid_10014/pid_6968/cgroup.procs: No such file or directory
I/QRemote ( 7695): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 7595): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 7595): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,I/PCSuite ( 7647): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7647): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7647): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7531): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7531): MCCMNC not supported: null
,D/QRemote ( 7695): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7695): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7695): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 7595): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 7595): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
V/WiFiOffLoadBroadcast( 7531): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7531): MCCMNC not supported: null
I/wpa_supplicant( 6116): p2p0: CTRL-EVENT-TERMINATING 
I/wpa_supplicant( 6116): monitor socket send errors count : 1
I/wpa_supplicant( 6116): CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1928-2\x00 that cannot receive messages
,D/QRemote ( 7695): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,W/wpa_supplicant( 6116): USIM:  scard_deinit function
D/WifiMonitor( 1025): Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
D/WifiMonitor( 1025): Dropping event because (p2p0) is stopped
D/WifiMonitor( 1025): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1025): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=
D/QRemote ( 7695): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
E/WifiStateMachine( 1025):  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=449981  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: DISCONNECTED
E/WifiStateMachine( 1025):  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=449982  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: DISCONNECTED
I/QRemote ( 7695): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 7595): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 7647): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
W/ContextImpl( 7595): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,D/PCSuite ( 7647): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7647): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7531): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7531): MCCMNC not supported: null
D/QRemote ( 7695): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7695): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7695): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 7595): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7647): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7647): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7647): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7531): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7531): MCCMNC not supported: null
,I/wpa_supplicant( 6116): wlan0: CTRL-EVENT-TERMINATING 
D/WifiMonitor( 1025): Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
E/WifiMonitor( 1025): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-TERMINATING 
D/WifiMonitor( 1025): Disconnecting from the supplicant, no more events
E/WifiStateMachine( 1025):  SupplicantStoppingState SUP_DISCONNECTION_EVENT 30 0
D/QRemote ( 7695): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7695): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7695): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
I/ActivityManager( 1025): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7729 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,D/WifiOffDelayIfNotUsed( 1025): stopMonitoring
E/WifiStateMachine( 1025): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1025): useWiFiOffloading() : false
E/WifiStateMachine( 1025): CONFIG_LGE_WLAN_PATH : true
D/WfdsService( 1928): Supplicant Connection state is changed : false
,D/WfdsService( 1928): DefaultState - WIFI_SUPPLICANT_DISCONNECTED
D/WfdsService( 1928): Set the WFDS Monitor: false
D/WfdsMonitor( 1928): WFDS Monitor is stopped
,W/Settings( 1803): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/WfdStateTracker( 1928): WfdStateTracker handleDirectStateChangedEvent: 0
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
I/WifiServerServiceExt( 1025): WIFI_STATE_CHANGED_ACTION [1]
I/WifiServerServiceExt( 1025): batteryPsActivateMsgHandler : state:0 event:1
I/WifiServerServiceExt( 1025): batteryPsActivateMsgHandler : this is not treated
,D/PCSuite ( 7647): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7531): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,D/WiFiOffLoadBroadcast( 7531): MCCMNC not supported: null
,W/FormManager( 7729): Network not available. Please check & try again.
,D/PostponalbeReceiver( 7595): WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
D/PowerManagerServiceEx( 1025): acquireWakeLockInternal: lock=1033378170, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1025
V/AlarmManager( 1025): ELAPSED_WAKEUP set : Alarm{19fd8717 type 2 when 450313 com.google.android.gms} when 450313
,V/QRemote ( 7695): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7695): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 7695): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
V/FormManager( 7729): Network unavailable.
D/[Concierge]Service( 2576): onStartCommand(). Type : 9
,V/FormManager( 7729): Network unavailable.
I/ActivityManager( 1025): Killing 7045:com.google.android.gms:car/u0a5 (adj 15): empty #17
,D/LgDataFeature( 7695): LgDataFeature() Constructor: none
D/LgDataFeature( 7695): LgDataFeature() Constructor Done, null
V/SoundPool( 7695): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
,V/SoundPool( 7695): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 7695): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 7695): doLoad: loading sample sampleID=1
I/QRemote ( 7695): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
V/SoundPool( 7695): Start decode
V/MediaPlayer[Native]( 7695): decode(31, 10857164, 17813)
V/MediaPlayerService(  321): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  321): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  321): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  321): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  321): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  321): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  321): player type = 3
V/AwesomePlayer(  321): AwesomePlayer create()
V/AwesomePlayer(  321): reset_l() 
V/AwesomePlayer(  321): cancelPlayerEvents
V/AwesomePlayer(  321): setAudioSink() 
V/AwesomePlayer(  321): reset_l() 
V/AudioCache(  321): notify(0xb14329c0, 8, 0, 0)
V/AudioCache(  321): ignored
V/AwesomePlayer(  321): cancelPlayerEvents
,D/Utils   (  321): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  321): setDataSource_l dataSource
,V/LGParserOSAL(  321): SniffLGParser start
,V/LGParserOSAL(  321): MainType:5, SubType=0
V/LGParserOSAL(  321): #### check Mime : application/ogg
V/LGParserOSAL(  321): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  321): Use LGExtractor :application/ogg 
V/LGParserOSAL(  321): supported mime: application/ogg
V/AwesomePlayer(  321): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  321): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  321): mBitrate = -1 bits/sec
V/AwesomePlayer(  321): AudioTrack Setting
V/AwesomePlayer(  321): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  321): setAudioSource() 
V/MediaPlayerService(  321): prepare
,V/AwesomePlayer(  321): prepareAsync_l() 
V/MediaPlayerService(  321): wait for prepare
V/AwesomePlayer(  321): onPrepareAsyncEvent() 
V/AwesomePlayer(  321): initAudioDecoder() 
W/Utils   (  321): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  321): isOffloadSupported()
V/AudioPolicyManager(  321): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  321): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  321): isAudioPlaybackHookOn() false
V/AwesomePlayer(  321): getUseOffload() = 0 
V/OMXCodec(  321): OMXCodec::Create
V/OMXCodec(  321): findMatchingCodecs()
V/OMXCodec(  321): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  321): matchingCodecs.size()=1
,V/OMXCodec(  321): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
D/OMXCodec(  321): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  321): LG Codec Adapter start
V/OMXCodec(  321): OMXCodec Createtor
V/OMXCodec(  321): setComponentRole
V/OMXCodec(  321): configureCodec protected=0
V/LGCodecAdapter(  321): called getLGCodecSpecificData
V/LGCodecOSAL(  321): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  321): Called LGconfigureCodecMETA
V/LGCodecOSAL(  321): Called LGconfigureCodecMSG
V/LGCodecOSAL(  321): Not support LGCodec
V/OMXCodec(  321): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  321): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  321): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  321): Could not offload audio decode, try pcm offload
,W/Utils   (  321): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  321): isOffloadSupported()
V/AudioPolicyManager(  321): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  321): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  321): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  321): init()
V/OMXCodec(  321): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  321): allocateBuffers
V/OMXCodec(  321): allocateBuffersOnPort portIndex=0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7970 on input port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on input port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on input port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on input port
V/OMXCodec(  321): allocateBuffersOnPort portIndex=1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on output port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on output port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ce0 on output port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d30 on output port
V/OMXCodec(  321): init() mAsyncCompletion wait!!! 
V/OMXCodec(  321): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  321): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  321): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  321): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  321): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  321): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  321): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  321): finishAsyncPrepare_l() 
V/AudioCache(  321): notify(0xb14329c0, 5, 0, 0)
V/AudioCache(  321): ignored
V/AudioCache(  321): notify(0xb14329c0, 1, 0, 0)
V/AudioCache(  321): prepared
V/AudioCache(  321): wait - success
V/MediaPlayerService(  321): start
V/AwesomePlayer(  321): play_l() 
V/AwesomePlayer(  321): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  321): createAudioPlayer_l
V/AwesomePlayer(  321): seekAudioIfNecessary_l() 
V/AwesomePlayer(  321): startAudioPlayer_l() 
D/AudioPlayer(  321): start of Playback, useOffload 0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  321): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  321): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  321): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  321): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  321): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885168
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885328
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885408
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 304188548,8
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  321): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  321): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  321): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  321): allocateBuffersOnPort portIndex=1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ce0 on output port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on output port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on output port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc970 on output port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
,V/OMXCodec(  321): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  321): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  321): notify(0xb14329c0, 6, 0, 0)
V/AudioCache(  321): ignored
V/MediaPlayerService(  321): wait for playback complete
V/AudioCache(  321): write(0xb173f000, 4096)
V/AudioCache(  321): memcpy(0xab700000, 0xb173f000, 4096)
V/AudioCache(  321): write(0xb173f000, 4096)
V/AudioCache(  321): memcpy(0xab701000, 0xb173f000, 4096)
V/AudioCache(  321): write(0xb173f000, 4096)
V/AudioCache(  321): memcpy(0xab702000, 0xb173f000, 4096)
V/AudioCache(  321): write(0xb173f000, 4096)
V/AudioCache(  321): memcpy(0xab703000, 0xb173f000, 4096)
V/AudioCache(  321): write(0xb173f000, 4096)
V/AudioCache(  321): memcpy(0xab704000, 0xb173f000, 4096)
V/AudioCache(  321): write(0xb173f000, 4096)
V/AudioCache(  321): memcpy(0xab705000, 0xb173f000, 4096)
,V/AudioCache(  321): write(0xb173f000, 4096)
V/AudioCache(  321): memcpy(0xab706000, 0xb173f000, 4096)
V/AudioCache(  321): write(0xb173f000, 4096)
V/AudioCache(  321): memcpy(0xab707000, 0xb173f000, 4096)
V/AudioCache(  321): write(0xb173f000, 4096)
V/AudioCache(  321): memcpy(0xab708000, 0xb173f000, 4096)
V/AudioCache(  321): write(0xb173f000, 4096)
V/AudioCache(  321): memcpy(0xab709000, 0xb173f000, 4096)
V/AudioCache(  321): write(0xb173f000, 4096)
V/AudioCache(  321): memcpy(0xab70a000, 0xb173f000, 4096)
,V/AudioCache(  321): write(0xb173f000, 4096)
V/AudioCache(  321): memcpy(0xab70b000, 0xb173f000, 4096)
V/AudioCache(  321): write(0xb173f000, 4096)
V/AudioCache(  321): memcpy(0xab70c000, 0xb173f000, 4096)
V/AudioCache(  321): write(0xb173f000, 4096)
V/AudioCache(  321): memcpy(0xab70d000, 0xb173f000, 4096)
V/AudioCache(  321): write(0xb173f000, 4096)
V/AudioCache(  321): memcpy(0xab70e000, 0xb173f000, 4096)
V/AudioCache(  321): write(0xb173f000, 4096)
V/AudioCache(  321): memcpy(0xab70f000, 0xb173f000, 4096)
V/AudioCache(  321): write(0xb173f000, 4096)
V/AudioCache(  321): memcpy(0xab710000, 0xb173f000, 4096)
V/AudioCache(  321): write(0xb173f000, 4096)
V/AudioCache(  321): memcpy(0xab711000, 0xb173f000, 4096)
V/AudioCache(  321): write(0xb173f000, 4096)
V/AudioCache(  321): memcpy(0xab712000, 0xb173f000, 4096)
V/AudioCache(  321): write(0xb173f000, 4096)
V/AudioCache(  321): memcpy(0xab713000, 0xb173f000, 4096)
V/AudioCache(  321): write(0xb173f000, 4096)
V/AudioCache(  321): memcpy(0xab714000, 0xb173f000, 4096)
V/AudioCache(  321): write(0xb173f000, 4096)
V/AudioCache(  321): memcpy(0xab715000, 0xb173f000, 4096)
V/AudioCache(  321): write(0xb173f000, 4096)
V/AudioCache(  321): memcpy(0xab716000, 0xb173f000, 4096)
V/AudioCache(  321): write(0xb173f000, 4096)
V/AudioCache(  321): memcpy(0xab717000, 0xb173f000, 4096)
V/AudioCache(  321): write(0xb173f000, 4096)
V/AudioCache(  321): memcpy(0xab718000, 0xb173f000, 4096)
V/AudioCache(  321): write(0xb173f000, 4096)
V/AudioCache(  321): memcpy(0xab719000, 0xb173f000, 4096)
,V/AudioCache(  321): write(0xb173f000, 4096)
V/AudioCache(  321): memcpy(0xab71a000, 0xb173f000, 4096)
V/AudioCache(  321): write(0xb173f000, 4096)
V/AudioCache(  321): memcpy(0xab71b000, 0xb173f000, 4096)
V/AudioCache(  321): write(0xb173f000, 4096)
V/AudioCache(  321): memcpy(0xab71c000, 0xb173f000, 4096)
V/AudioCache(  321): write(0xb173f000, 4096)
V/AudioCache(  321): memcpy(0xab71d000, 0xb173f000, 4096)
V/AudioCache(  321): write(0xb173f000, 4096)
V/AudioCache(  321): memcpy(0xab71e000, 0xb173f000, 4096)
V/AudioCache(  321): write(0xb173f000, 4096)
V/AudioCache(  321): memcpy(0xab71f000, 0xb173f000, 4096)
V/AudioCache(  321): write(0xb173f000, 4096)
V/AudioCache(  321): memcpy(0xab720000, 0xb173f000, 4096)
V/AudioCache(  321): write(0xb173f000, 4096)
V/AudioCache(  321): memcpy(0xab721000, 0xb173f000, 4096)
V/AudioCache(  321): write(0xb173f000, 4096)
V/AudioCache(  321): memcpy(0xab722000, 0xb173f000, 4096)
V/AudioCache(  321): write(0xb173f000, 4096)
V/AudioCache(  321): memcpy(0xab723000, 0xb173f000, 4096)
V/AudioCache(  321): write(0xb173f000, 4096)
V/AudioCache(  321): memcpy(0xab724000, 0xb173f000, 4096)
V/AudioCache(  321): write(0xb173f000, 4096)
V/AudioCache(  321): memcpy(0xab725000, 0xb173f000, 4096)
V/AudioCache(  321): write(0xb173f000, 4096)
V/AudioCache(  321): memcpy(0xab726000, 0xb173f000, 4096)
V/AudioCache(  321): write(0xb173f000, 4096)
V/AudioCache(  321): memcpy(0xab727000, 0xb173f000, 4096)
V/AudioCache(  321): write(0xb173f000, 4096)
V/AudioCache(  321): memcpy(0xab728000, 0xb173f000, 4096)
V/AudioCache(  321): write(0xb173f000, 4096)
V/AudioCache(  321): memcpy(0xab729000, 0xb173f000, 4096)
V/AudioCache(  321): write(0xb173f000, 4096)
,V/AudioCache(  321): memcpy(0xab72a000, 0xb173f000, 4096)
I/ActivityManager( 1025): Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7758 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
V/AudioCache(  321): write(0xb173f000, 4096)
V/AudioCache(  321): memcpy(0xab72b000, 0xb173f000, 4096)
W/libprocessgroup( 1025): failed to open /acct/uid_10005/pid_7045/cgroup.procs: No such file or directory
V/AudioCache(  321): write(0xb173f000, 4096)
V/AudioCache(  321): memcpy(0xab72c000, 0xb173f000, 4096)
D/QRemote ( 7695): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
V/AudioCache(  321): write(0xb173f000, 4096)
V/AudioCache(  321): memcpy(0xab72d000, 0xb173f000, 4096)
V/AudioCache(  321): write(0xb173f000, 4096)
V/AudioCache(  321): memcpy(0xab72e000, 0xb173f000, 4096)
V/AudioCache(  321): write(0xb173f000, 4096)
V/AudioCache(  321): memcpy(0xab72f000, 0xb173f000, 4096)
V/AudioCache(  321): write(0xb173f000, 4096)
V/AudioCache(  321): memcpy(0xab730000, 0xb173f000, 4096)
V/AudioCache(  321): write(0xb173f000, 4096)
V/AudioCache(  321): memcpy(0xab731000, 0xb173f000, 4096)
V/OMXCodec(  321): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  321): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
,V/AwesomePlayer(  321): postAudioEOS() 
V/AudioCache(  321): write(0xb173f000, 280)
V/AudioCache(  321): memcpy(0xab732000, 0xb173f000, 280)
E/QRemote ( 7695): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7695): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
V/AwesomePlayer(  321): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  321): onStreamDone
V/AwesomePlayer(  321): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  321): notify(0xb14329c0, 2, 0, 0)
V/AudioCache(  321): playback complete
V/AwesomePlayer(  321): pause_l() 
V/AudioCache(  321): wait - success
V/AudioCache(  321): notify(0xb14329c0, 7, 0, 0)
V/AudioCache(  321): ignored
V/MediaPlayerService(  321): return size 205080, sampleRate=48000, channelCount = 2, format = 1
V/AwesomePlayer(  321): cancelPlayerEvents
D/AudioPlayer(  321): Pause Playback at 1068125
V/AwesomePlayer(  321): reset_l() 
V/AudioCache(  321): notify(0xb14329c0, 8, 0, 0)
V/AudioCache(  321): ignored
V/AwesomePlayer(  321): cancelPlayerEvents
D/AudioPlayer(  321): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  321): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  321): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  321): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  321): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  321): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7970 on port 0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
,V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
,V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc970 on port 1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7bf0 on port 1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c90 on port 1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ce0 on port 1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  321): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  321): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  321): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  321): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  321): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  321): AudioPlayer releasing audio source
D/AudioPlayer(  321): AudioPlayer done releasing audio source
V/AwesomePlayer(  321): reset_l() 
V/AwesomePlayer(  321): cancelPlayerEvents
V/AwesomePlayer(  321): ~AwesomePlayer call
V/AwesomePlayer(  321): reset_l() 
V/AwesomePlayer(  321): cancelPlayerEvents
V/SoundPool( 7695): close(31)
V/SoundPool( 7695): pointer = 0x9fe34000, size = 205080, sampleRate = 48000, numChannels = 2
V/LGMDMManager( 7695): Create singleton instance
,D/UEI.SmartControl( 7758): Quickset Services start...
,I/UEI.SmartControl( 7758): Manufacture = LGE
D/UEI.SmartControl( 7758): Id = LGNevo
D/UEI.SmartControl( 7758): File observer start...
E/UEI.SmartControl( 7758): IR Port is disabled: false
D/UEI.SmartControl( 7758): Starting file observer...
D/UEI.SmartControl( 7758): Extracting JNI libs...
D/UEI.SmartControl( 7758): --- this system supports 32-bit or 64-bit only
D/QRemote ( 7695): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7695): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
D/QRemote ( 7695): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:4240
,D/PostponalbeReceiver( 7595): WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
D/PostponalbeReceiver( 7595): WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
D/PostponalbeReceiver( 7595): WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
D/PostponalbeReceiver( 7595): WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
D/LGDMClient( 4006): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 4006): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4006): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,W/ContextImpl( 4006): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/LGDMClient( 4006): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,D/LGDMClient( 4006): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 4006): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/PCSuite ( 7647): [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
D/PCSuite ( 7647): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7647): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7531): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
W/FormManager( 7729): Network not available. Please check & try again.
,D/WiFiOffLoadBroadcast( 7531): MCCMNC not supported: null
V/FormManager( 7729): Network unavailable.
,V/FormManager( 7729): Network unavailable.
D/PowerManagerServiceEx( 1025): releaseWakeLockInternal: lock=1033378170 [*alarm*], flags=0x0
D/libc-netbsd(  316): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1025): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,D/UEI.SmartControl( 7758): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 7758): --- Checking lib: libqs_armeabi-v7a.zip
,D/UEI.SmartControl( 7758): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 7758): --- Selecting new region: 6
,I/UEI.SmartControl( 7758): Model = LG-D855
,D/UEI.SmartControl( 7758): QS Service created
I/UEI.SmartControl( 7758): Service initServices...
,D/UEI.SmartControl( 7758): QS start get config
,D/UEI.SmartControl( 7758): Loading JNI Libs...
,D/ConnectivityService( 1025): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService( 1025): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1025): MasterInitialState.processMessage what=3
D/Tethering( 1025): MasterInitialState.processMessage what=3
D/GpsLocationProvider( 1025): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/NetworkMonitor( 5266): type=WIFI subType= reason=null isConnected=false
,D/GpsLocationProvider( 1025): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1025): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1025): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PostponalbeReceiver( 7595): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
I/NetworkMonitor( 5266): type=WIFI subType= reason=null isConnected=false
,W/ContextImpl( 7595): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 7138): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7138): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7138): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7138): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7138): onReceive
,D/AppUp4:CustFacade( 7138): Context : android.app.ReceiverRestrictedContext@1588c4af
D/AppUp4:CustFacade( 7138): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7138): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7138): begin check event
I/AppUp4:CustModeStarterReceiver( 7138): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7138): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7138): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7138): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7138): handleAsyncCustNotification do not startCustService
D/LGDMClient( 4006): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4006): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 4006): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4006): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/LGDMClient( 4006): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,D/LGDMClient( 4006): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4006): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,I/ActivityManager( 1025): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7798 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/UEI.SmartControl( 7758): Supports setup maps: true
,W/ResourcesManager( 7798): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7798): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7798): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7798): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
D/UEI.SmartControl( 7758): QS start statue = true Error code = 0
I/UEI.SmartControl( 7758): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 7758): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 7758): ### init IR Blaster...
D/serial_port( 7758): Configuring serial port
E/UEI.SmartControl( 7758): UEIBLaster setting for 616
,I/UEI.SmartControl( 7758): Setting serial record hearder size = 2
I/UEI.SmartControl( 7758): configuring settings for MAXQ616
I/UEI.SmartControl( 7758): Get version...
D/UEI.SmartControl( 7758): serial port data available: 21
,D/UEI.SmartControl( 7758): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 7758): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 7758): QS saving settings...
,I/LGEmail ( 7798): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/UEI.SmartControl( 7758): IR Blaster version: 25672567
D/LGEmail ( 7798): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
D/UEI.SmartControl( 7758): serial port data available: 4
,W/ResourceType( 7798): No package identifier when getting value for resource number 0x00000000
,I/UEI.SmartControl( 7758): Device manager: loading config....
D/UEI.SmartControl( 7758): ----------- loading internal config...
W/ContextImpl( 7758): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
E/UEI.SmartControl( 7758): Services init done
D/UEI.SmartControl( 7758): QS Service init finished
D/LgDataFeature( 7798): LgDataFeature() Constructor: none
D/UEI.SmartControl( 7758): QS Service version name: 2.1.91
D/UEI.SmartControl( 7758): QS Service version code: 201091
D/LgDataFeature( 7798): LgDataFeature() Constructor Done, null
,D/UEI.SmartControl( 7758): Service requested: Control
E/UEI.SmartControl( 7758): Loading SETTINGS...
,D/UEI.SmartControl( 7758): Request IControl service: devices are loaded...
I/QRemote ( 7695): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
D/UEI.SmartControl( 7758): Internal service binding...
I/UEI.SmartControl( 7758): ------ IControl API: 11
I/UEI.SmartControl( 7758): Registering callback...
I/UEI.SmartControl( 7758): ------ IControl API: 19
I/UEI.SmartControl( 7758): Registering Services Ready callback...
D/UEI.SmartControl( 7758): -- Open brand translation xml: brands_translations_ko
,I/UEI.SmartControl( 7758): Notify AllClients services are ready: 0
D/UEI.SmartControl( 7758): -----service ready thread exits
,I/QRemote ( 7695): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
,D/QRemote ( 7695): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 7695): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 7695): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 7695): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 7758): ------ IControl API: 8
D/QRemote ( 7695): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 7695): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 7695): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 7695): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 7695): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7695): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 7695): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
D/QRemote ( 7695): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
I/ActivityManager( 1025): Killing 7189:com.android.gallery3d/u0a27 (adj 15): empty #17
,I/ActivityManager( 1025): Killing 7166:com.android.contacts/u0a19 (adj 15): empty #18
,W/libprocessgroup( 1025): failed to open /acct/uid_10027/pid_7189/cgroup.procs: No such file or directory
,W/libprocessgroup( 1025): failed to open /acct/uid_10019/pid_7166/cgroup.procs: No such file or directory
,D/eas_req ( 7798): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/HubEmail( 7798): JNI_OnLoad()
I/HubEmail( 7798): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7798): registerNatives()
,I/HubEmail( 7798): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7798): registerNativeMethods()
I/HubEmail( 7798): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7798): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,W/FormManager( 7729): Network not available. Please check & try again.
,W/Settings( 7798): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/FormManager( 7729): Network unavailable.
,V/FormManager( 7729): Network unavailable.
I/ActivityManager( 1025): Killing 7213:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,I/LgeMiscReceiver( 3294): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 3294): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3294): networkInfo.isConnected() = false
W/libprocessgroup( 1025): failed to open /acct/uid_10080/pid_7213/cgroup.procs: No such file or directory
,I/ActivityManager( 1025): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7836 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  349): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 522us total 21.208ms
,I/art     (  349): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 453us total 20.661ms
,I/art     (  349): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 421us total 20.610ms
,I/ActivityManager( 1025): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7857 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,I/ActivityManager( 1025): Killing 7078:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
W/libprocessgroup( 1025): failed to open /acct/uid_10005/pid_7078/cgroup.procs: No such file or directory
,I/ActivityManager( 1025): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7874 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1025): Killing 7241:com.google.android.apps.plus/u0a97 (adj 15): empty #17
W/libprocessgroup( 1025): failed to open /acct/uid_10097/pid_7241/cgroup.procs: No such file or directory
,I/art     ( 7874): Almond Protected OAT
,D/WeatherApplication( 7874): removeAccount
,D/WeatherApplication( 7874): Account.length = 0
E/WeatherApplication( 7874): OPERATOR:OPEN
D/WeatherAncestor( 7874): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:43:32
D/Weather.Utils( 7874): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7874): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7874): 2 : This is isUpdating : false
D/WeatherAncestor( 7874): connectivity changed - connection : true
,D/WeatherService( 7874): 2 : isServiceAlived():false forecastCache:null
D/ForecastDataCache( 7874): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7874): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7874): 2 : Cache is not up-to-date, count: 0
,D/Weather_cast( 7874): 2 : isUpdateNeedForAlarm : no city return false
,D/WeatherAncestor( 7874): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:43:32
,I/ActivityManager( 1025): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7895 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1025): Killing 6997:com.android.vending/u0a44 (adj 15): empty #17
,W/libprocessgroup( 1025): failed to open /acct/uid_10044/pid_6997/cgroup.procs: No such file or directory
,E/VoldCmdListener(  281): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  281): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7895): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  281): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  281): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7895): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  281): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  281): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7895): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  281): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  281): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7895): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/WebViewFactory( 7895): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7895): Loading: webviewchromium
I/LibraryLoader( 7895): Time to load native libraries: 5 ms (timestamps 3035-3040)
,I/LibraryLoader( 7895): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7895): Binding Chromium to main looper Looper (main, tid 1) {19157b97}
,I/LibraryLoader( 7895): Expected native library version number "",actual native library version number ""
I/chromium( 7895): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
D/LGWifiP2pService( 1025): P2pDisabledState{ when=-5ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1025): DefaultState{ when=-5ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 1025):  InitialState CMD_STOP_SUPPLICANT_FAILED 1 0
E/WifiStateMachine( 1025):  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
,I/BrowserStartupController( 7895): Initializing chromium process, renderers=0
W/art     ( 7895): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 7895): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7895): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 7895): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
V/AudioPolicyService(  321): registerClient() client 0xb101ec60, uid 10093
,W/AudioManagerAndroid( 7895): Requires BLUETOOTH permission
I/Adreno-EGL( 7895): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7895): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7895): Build Date: 12/12/14 금
I/Adreno-EGL( 7895): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7895): Remote Branch: 
I/Adreno-EGL( 7895): Local Patches: 
I/Adreno-EGL( 7895): Reconstruct Branch: 
,I/NSApplication( 7895): Starting up...
,I/ActivityManager( 1025): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7950 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1025): Killing 6514:com.google.android.apps.books/u0a54 (adj 15): empty #17
,W/libprocessgroup( 1025): failed to open /acct/uid_10054/pid_6514/cgroup.procs: No such file or directory
,W/ResourcesManager( 7950): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/iu.Environment( 2303): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 2303): num queued entries: 0
I/iu.UploadsManager( 2303): num updated entries: 0
I/iu.SyncManager( 2303): NEXT; no task
D/ChimeraCfgMgr( 2303): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/PostponalbeReceiver( 7595): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 7595): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 7138): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7138): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7138): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7138): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 7138): onReceive
D/AppUp4:CustFacade( 7138): Context : android.app.ReceiverRestrictedContext@1588c4af
D/AppUp4:CustFacade( 7138): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7138): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7138): begin check event
I/AppUp4:CustModeStarterReceiver( 7138): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4006): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4006): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4006): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
I/GLSActivity( 2057): [ac] getting account id
W/ContextImpl( 4006): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/LGDMClient( 4006): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,D/eas_req ( 7798): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/GLSUser ( 2057): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
,D/LGDMClient( 4006): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4006): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
W/Settings( 7798): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/LgeMiscReceiver( 3294): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3294): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3294): networkInfo.isConnected() = false
D/WeatherAncestor( 7874): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:43:33
,W/FormManager( 7729): Network not available. Please check & try again.
D/Weather.Utils( 7874): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7874): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7874): 2 : This is isUpdating : false
V/FormManager( 7729): Network unavailable.
D/WeatherAncestor( 7874): connectivity changed - connection : true
D/WeatherService( 7874): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3da1aca8
D/ForecastDataCache( 7874): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7874): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7874): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7874): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7874): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:43:33
V/FormManager( 7729): Network unavailable.
,D/ChimeraCfgMgr( 2303): Loading module com.google.android.gms.kids from APK com.google.android.gms
,V/QRemote ( 7695): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,D/QRemote ( 7695): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 7695): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7695): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 7695): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7695): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 7695): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 7695): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1454593413997]
D/QRemote ( 7695): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,V/QRemote ( 7695): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
E/QRemote ( 7695): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7695): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 7695): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 7695): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
,D/QRemote ( 7695): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
,D/QRemote ( 7695): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 7695): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,I/art     ( 3359): Explicit concurrent mark sweep GC freed 4965(364KB) AllocSpace objects, 0(0B) LOS objects, 36% free, 27MB/43MB, paused 548us total 40.687ms
,V/AlarmManager( 1025): ELAPSED_WAKEUP set : Alarm{24b4973a type 2 when 455338 com.google.android.gms} when 455338
,D/libc-netbsd(  316): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1025): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,D/UEI.SmartControl( 7758): Internal timer expired: 1
,D/UEI.SmartControl( 7758): unbind internal service
,D/serial_port( 7758): close(fd = 25)
,I/UEI.SmartControl( 7758): Serial port is closed.
,I/GAV4    ( 7895): Thread[GAThread,5,main]: No campaign data found.
,I/art     ( 1025): Explicit concurrent mark sweep GC freed 40424(1896KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 6.931ms total 179.692ms
,I/ActivityManager( 1025): Killing 7624:com.lge.settings.easy/1000 (adj 15): empty #17
,W/libprocessgroup( 1025): failed to open /acct/uid_1000/pid_7624/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1025): tsOffsetIs: Apps: 467651519251; DSPS: 15464898; Offset : -4313847667
,D/PowerManagerServiceEx( 1025): acquireWakeLockInternal: lock=1033378170, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1025
,D/[Concierge]Service( 2576): onStartCommand(). Type : 9
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
V/QRemote ( 7695): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
,D/QRemote ( 7695): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:4240
D/PowerManagerServiceEx( 1025): releaseWakeLockInternal: lock=1033378170 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1025): tsOffsetIs: Apps: 487653610337; DSPS: 16120327; Offset : -4313862059
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1025): tsOffsetIs: Apps: 507655656162; DSPS: 16775754; Offset : -4313860886
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1025): tsOffsetIs: Apps: 527657620790; DSPS: 17431178; Offset : -4313849460
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
,D/PowerManagerServiceEx( 1025): acquireWakeLockInternal: lock=1033378170, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1025
,I/ActivityManager( 1025): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=8042 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,D/[Concierge]Service( 2576): onStartCommand(). Type : 9
,I/DigitalAppWidgetProvider( 8042): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 8042): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@1588c4af
D/PowerManagerServiceEx( 1025): releaseWakeLockInternal: lock=1033378170 [*alarm*], flags=0x0
I/ActivityManager( 1025): Killing 7577:com.lge.lifetracker/u0a37 (adj 15): empty #17
W/libprocessgroup( 1025): failed to open /acct/uid_10037/pid_7577/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1025): tsOffsetIs: Apps: 547659461407; DSPS: 18086598; Offset : -4313839925
,I/[SystemUI]LGPowerUI( 1465): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1465): On Skip Timer : true
,D/WifiController( 1025): battery changed pluggedType: 2
,D/LEDHandler( 1928): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1928): Battery Level Remaining: 100%
D/LEDHandler( 1928): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1465): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1465): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1465): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4006): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4006): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,I/[SystemUI]LGPowerUI( 1465): onReceive = com.lge.android.intent.action.BATTERYEX
,I/[SystemUI]LGPowerUI( 1465): On Skip Timer : true
,D/LEDHandler( 1928): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1928): Battery Level Remaining: 100%
D/LEDHandler( 1928): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
,D/KeyguardUpdateMonitor( 1465): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1465): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4006): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/WifiController( 1025): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1465): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4006): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1025): tsOffsetIs: Apps: 567662170463; DSPS: 18742047; Offset : -4313846932
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1025): tsOffsetIs: Apps: 587664206601; DSPS: 19397474; Offset : -4313855290
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1025): tsOffsetIs: Apps: 607665798676; DSPS: 20052886; Offset : -4313850233
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1025): tsOffsetIs: Apps: 627667804033; DSPS: 20708312; Offset : -4313859088
,D/PowerManagerServiceEx( 1025): acquireWakeLockInternal: lock=1033378170, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1025
,V/AlarmManager( 1025): ELAPSED_WAKEUP set : Alarm{14c4ed06 type 2 when 645714 android} when 645714
D/[Concierge]Service( 2576): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1025): releaseWakeLockInternal: lock=1033378170 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1025): tsOffsetIs: Apps: 647669909598; DSPS: 21363741; Offset : -4313859314
,D/PowerManagerServiceEx( 1025): acquireWakeLockInternal: lock=1033378170, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1025
,D/[Concierge]Service( 2576): onStartCommand(). Type : 9
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
D/PowerManagerServiceEx( 1025): releaseWakeLockInternal: lock=1033378170 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1025): tsOffsetIs: Apps: 667672587560; DSPS: 22019188; Offset : -4313836356
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1025): tsOffsetIs: Apps: 687674227501; DSPS: 22674602; Offset : -4313844364
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1025): tsOffsetIs: Apps: 707676303534; DSPS: 23330030; Offset : -4313843474
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
,I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1025): tsOffsetIs: Apps: 727677837537; DSPS: 23985441; Offset : -4313865790
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1025): tsOffsetIs: Apps: 747679808467; DSPS: 24640865; Offset : -4313848141
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1025): tsOffsetIs: Apps: 767682966636; DSPS: 25296329; Offset : -4313863774
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
,I/[SystemUI]DateView( 1465): called onTimeUpdated()
,I/[SystemUI]DateView( 1465): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1025): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0,
D/sensors_hal_Time( 1025): tsOffsetIs: Apps: 787685037097; DSPS: 25951757; Offset : -4313868534
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1025): tsOffsetIs: Apps: 807686978392; DSPS: 26607180; Offset : -4313849586
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1025): tsOffsetIs: Apps: 827689003696; DSPS: 27262606; Offset : -4313838521
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
,I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1025): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1025): tsOffsetIs: Apps: 847690442074; DSPS: 27918014; Offset : -4313865169
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1025): tsOffsetIs: Apps: 867701863578; DSPS: 28573748; Offset : -4313857187
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1025): tsOffsetIs: Apps: 887703589768; DSPS: 29229164; Offset : -4313839825
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
,I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
D/sensors_hal_Time( 1025): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1025): tsOffsetIs: Apps: 907705501323; DSPS: 29884587; Offset : -4313851060
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1025): tsOffsetIs: Apps: 927707360429; DSPS: 30540008; Offset : -4313853448
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1025): tsOffsetIs: Apps: 947709242661; DSPS: 31195430; Offset : -4313863331
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
,I/[SystemUI]DateView( 1465): called onTimeUpdated()
,I/[SystemUI]DateView( 1465): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1025): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1025): tsOffsetIs: Apps: 967711924060; DSPS: 31850878; Offset : -4313867583
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1025): tsOffsetIs: Apps: 987713747125; DSPS: 32506297; Offset : -4313845030
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1025): tsOffsetIs: Apps: 1007715727065; DSPS: 33161722; Offset : -4313848681
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1025): tsOffsetIs: Apps: 1027717684610; DSPS: 33817146; Offset : -4313844183
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1025): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1025): tsOffsetIs: Apps: 1047719686269; DSPS: 34472572; Offset : -4313856709
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1025): tsOffsetIs: Apps: 1067722335585; DSPS: 35128019; Offset : -4313862396
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
,I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
D/sensors_hal_Time( 1025): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1025): tsOffsetIs: Apps: 1087724282660; DSPS: 35783442; Offset : -4313837982
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1025): tsOffsetIs: Apps: 1107726209788; DSPS: 36438866; Offset : -4313863952
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1025): tsOffsetIs: Apps: 1127728249416; DSPS: 37094292; Offset : -4313838589
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
,I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
,I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1465): handleTimeUpdate,
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1025): tsOffsetIs: Apps: 1147731007846; DSPS: 37749743; Offset : -4313857102
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1025): tsOffsetIs: Apps: 1167732886431; DSPS: 38405164; Offset : -4313840167
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1025): tsOffsetIs: Apps: 1187734491528; DSPS: 39060577; Offset : -4313852477
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
,I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1025): tsOffsetIs: Apps: 1207736577197; DSPS: 39716005; Offset : -4313841951
,I/UsageStatsService( 1025): User[0] Flushing usage stats to disk
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1025): tsOffsetIs: Apps: 1227738444376; DSPS: 40371427; Offset : -4313866992
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1025): tsOffsetIs: Apps: 1247740339527; DSPS: 41026849; Offset : -4313863904
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
,I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
,I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
D/sensors_hal_Time( 1025): time_service_sensor1_cb: msg_type 2,
D/sensors_hal_Time( 1025): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1025): tsOffsetIs: Apps: 1267742449258; DSPS: 41682278; Offset : -4313859834
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1025): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1025): tsOffsetIs: Apps: 1287743617272; DSPS: 42337676; Offset : -4313851566
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1025): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1025): tsOffsetIs: Apps: 1307745459712; DSPS: 42993096; Offset : -4313840154
,TIME-OUT KILL (timeout was 1200000ms)
```
