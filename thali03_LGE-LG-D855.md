#### Test 5838050069f842e_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
I/MusicWidget( 2676): mDelayedStopHandler : unbind
I/MusicBrowser( 2231): [MediaPlaybackService.java:2869:onUnbind()] oooooo 
I/MusicBrowser( 2231): [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2231): [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2231): [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2231): [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2231): [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2231): [MediaPlaybackService.java:2046:onDestroy()] oooooo 
I/MusicBrowser( 2231): [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
I/MediaFocusControl( 1026):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@354e0080com.lge.music.MediaPlaybackService$5@195d66b9
D/MusicBrowser( 2231): [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2231): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2231): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2231): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2231): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@57adf6f
I/MusicBrowser( 2231): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2231): [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2231): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2231): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2231): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2231): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2231): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2231): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2231): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2231): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2231): [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2231): [MediaPlaybackService.java:6704:release()] oooooo 
I/MusicBrowser( 2231): [MediaPlaybackService.java:6665:stop()] oooooo 
V/MediaPlayer[Native]( 2231): reset
V/MediaPlayer[Native]( 2231): setListener
V/MediaPlayer[Native]( 2231): disconnect
V/MediaPlayer[Native]( 2231): destructor
V/AudioFlinger(  331): releasing 13 from 2231 for -1
V/AudioFlinger(  331):  decremented refcount to 0
V/AudioFlinger(  331): purging stale effects
V/MediaPlayer[Native]( 2231): disconnect
D/MusicBrowser( 2231): [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
I/SmartShareClient( 2231): [SmartShareManagerClient] smartshare client supported version code: 305000
I/SmartShareClient( 2231): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2231): [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
I/MusicBrowser( 2231): [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2231): [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2231): [SmartShareManagerClient] unregisterListener: 774327038
W/SmartShareClient( 2231): [SmartShareManagerClient] unregisterListener invalid listener: 774327038
I/SmartShareClient( 2231): [SmartShareManagerClient] terminate service: 2231/MediaPlaybackService/436532557
E/HomeCloudIF( 2231): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2231): [SmartShareManagerClient] unbindService context:android.app.Application@1e08825f
V/CloudHub( 2231): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
V/CloudHub( 2231): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2231): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
D/MusicBrowser( 2231): [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
--------- beginning of system
I/ActivityManager( 1026): Killing 5657:com.android.defcontainer/u0a4 (adj 15): empty #17
I/CloudHub( 2231): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29989
W/libprocessgroup( 1026): failed to open /acct/uid_10004/pid_5657/cgroup.procs: No such file or directory
,D/AndroidRuntime( 5982): 
D/AndroidRuntime( 5982): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5982): CheckJNI is OFF
D/AndroidRuntime( 5982): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1026): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1960): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1026): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1026): setTaskToReturnTo : TaskRecord{9720214 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1026): setTaskToReturnTo : TaskRecord{9720214 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1026): AppWindowTokenEx init.. 
E/GBMv2   (  348): DFP En is all cleared set to be enabled
I/ActivityManager( 1026): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5997 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 5982): Shutting down VM
V/ActivityManager( 1026): Display changed displayId=0
D/DSDPConnection( 1865): Display #0 changed.
D/SplitWindowPolicy( 1960): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1960): topRunningActivity=ActivityInfo{16079388 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1960): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1960): topRunningActivity=ActivityInfo{135d7121 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 5997): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/WebViewFactory( 5997): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 5997): Loading: webviewchromium
I/LibraryLoader( 5997): Time to load native libraries: 3 ms (timestamps 5572-5575)
I/LibraryLoader( 5997): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5997): Binding Chromium to main looper Looper (main, tid 1) {1a04f54d}
,I/LibraryLoader( 5997): Expected native library version number "",actual native library version number ""
I/chromium( 5997): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5997): Initializing chromium process, renderers=0
W/art     ( 5997): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 5997): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,W/chromium( 5997): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,V/AudioPolicyService(  331): registerClient() client 0xb54f4260, uid 10311
I/chromium( 5997): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 5997): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
D/BluetoothManagerService( 1026): Message: 20
D/BluetoothManagerService( 1026): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@35e7edfe:true
D/BluetoothAdapter( 5997): 493361154: getState() :  mService = null. Returning STATE_OFF
,I/Adreno-EGL( 5997): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5997): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5997): Build Date: 12/12/14 금
I/Adreno-EGL( 5997): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 5997): Remote Branch: 
I/Adreno-EGL( 5997): Local Patches: 
I/Adreno-EGL( 5997): Reconstruct Branch: 
,W/chromium( 5997): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 5997): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 5997): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5997): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 5997): CordovaWebView is running on device made by: LGE
,W/art     ( 5997): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5997): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager( 1026): Activity pause timeout for ActivityRecord{31a52abd u0 com.test.thalitest/.MainActivity t4}
,D/LgDataFeature( 5997): LgDataFeature() Constructor: none
D/LgDataFeature( 5997): LgDataFeature() Constructor Done, null
I/art     ( 1026): Explicit concurrent mark sweep GC freed 23768(1157KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.746ms total 88.164ms
,D/OpenGLRenderer( 5997): Render dirty regions requested: true
I/OpenGLRenderer( 5997): Initialized EGL, version 1.4
D/OpenGLRenderer( 5997): Enabling debug mode 0
D/Atlas   ( 5997): Validating map...
,D/SplitWindow( 1026): check instance of lgWin Window{27ae29c8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/SystemUI[Framework]( 1026): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
,D/PhoneStatusBar( 1465): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1465): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1465):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1465): , Keyguard show=false, IME shown=false, Panel expanded=false
W/PhoneWindowManagerEx( 1026): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1026): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1026): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1026): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@26b07e38,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1026): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/Timeline( 5997): Timeline: Activity_idle id: android.os.BinderProxy@179a85b2 time:106053
,I/ActivityManager( 1026): Displayed com.test.thalitest/.MainActivity: +661ms (total +741ms)
I/Timeline( 1026): Timeline: Activity_windows_visible id: ActivityRecord{31a52abd u0 com.test.thalitest/.MainActivity t4} time:106078
,I/chromium( 5997): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 5997): 
,D/JsMessageQueue( 5997): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 5997): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435086592
,I/chromium( 5997): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 5997): 
,I/chromium( 5997): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,V/AlarmManager( 1026): RTC_WAKEUP set : Alarm{1cb2cb9d type 0 when 1454701192262 com.android.vending} when 1454701192262
,E/GBMv2   (  348): DFP En is all cleared set to be enabled
E/GBMv2   (  348): Set value is all cleared set the max
I/GBMv2   (  348): DFP Enabled. Ignore VFP set
W/ContextImpl( 4221): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,V/SIM_STK ( 1026): Menu title from STK is T-Mobile
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 4901): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4901): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4901): [1] 5.onFinished: Scheduling replication attempt 1.
W/jxcore-log( 5997): Initializing JXcore engine
W/jxcore-log( 5997): JXcore engine is ready
,W/Thread-684( 6071): type=1400 audit(0.0:148): avc: denied { ioctl } for path="socket:[8577]" dev="sockfs" ino=8577 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-684( 6071): type=1400 audit(0.0:149): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-684( 6071): type=1400 audit(0.0:150): avc: denied { ioctl } for path="socket:[7706]" dev="sockfs" ino=7706 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/Thread-684( 6071): type=1400 audit(0.0:151): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/Thread-684( 6071): type=1400 audit(0.0:152): avc: denied { ioctl } for path="socket:[28656]" dev="sockfs" ino=28656 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
W/jxcore-log( 5997): Starting JXcore engine
,W/jxcore-log( 5997): Platform android
W/jxcore-log( 5997): 
W/jxcore-log( 5997): Process ARCH arm
W/jxcore-log( 5997): 
,I/jxcore-log( 5997): JXcore Cordova bridge is ready!
I/jxcore-log( 5997): 
W/jxcore-log( 5997): JXcore engine is started
,I/jxcore-log( 5997): Toggling radios to true
I/jxcore-log( 5997): 
,D/BluetoothManagerService( 1026): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1026): enable():  mBluetooth =null mBinding = false
,D/LocationManagerService( 1026): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1026): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1026): JNI:system_update. Event-4
D/BluetoothManagerService( 1026): Message: 1
D/BluetoothManagerService( 1026): MESSAGE_ENABLE: mBluetooth = null
D/WifiService( 1026): New client listening to asynchronous messages
,I/ActivityManager( 1026): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=6098 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,D/WifiServiceImplEx( 1026): setWifiEnabled: true pid=5997, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1026): setWifiEnabled: true pid=5997, uid=10311
E/WifiService( 1026): Invoking mWifiStateMachine.setWifiEnabled
,D/LocationManagerService( 1026): getAllProviders()=[passive, gps, network]
D/WifiServiceImplEx( 1026): disconnect pid=5997, uid=10311, packageName=com.test.thalitest
D/Ulp_jni ( 1026): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1026): JNI:system_update. Event-4
E/WifiStateMachine( 1026):  InitialState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1026):  DefaultState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1026):  InitialState CMD_START_SUPPLICANT 0 0
I/LGFTMITEM( 1026): [GET_FTM][id=6], offset=12288
D/WifiServiceImplEx( 1026): reconnect pid=5997, uid=10311, packageName=com.test.thalitest
I/jxcore-log( 5997): Radios toggled
I/jxcore-log( 5997): 
E/WifiUtil( 1026): wfc_util_ffile_check_copy(): pid[1026] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
E/WifiUtil( 1026): wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
E/WifiUtil( 1026): wfc_util_ffile_check_copy(): pid[1026] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
E/WifiUtil( 1026): wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
I/WifiUtil( 1026): Intf0MacAddress=C49A027B60AC
E/WifiHW  ( 1026): unknown target_country: EU , set to default
E/WifiHW  ( 1026): [wifi_ensure_config_files] default country1 = GB
E/WifiHW  ( 1026): [wifi_ensure_config_files] default country2 = GB
I/WifiUtil( 1026): gEnableBmps=1
,I/jxcore-log( 5997): My device name is: LGE-LG-D855
I/jxcore-log( 5997): 
W/ResourcesManager( 6098): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager( 6098): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6098): Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 6098): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/BluetoothAdapterApp( 6098): Loading JNI Library
,D/BluetoothAdapterApp( 6098): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@33bcd911 Instance Count = 1
,D/BluetoothAdapterApp( 6098): onCreate
,D/Tethering( 1026): sendTetherStateChangedBroadcast 1, 0, 0
,D/libc-netbsd(  327): default dns: query_ipv6=0, query_ipv4=0
,D/Tethering( 1026): InitialState.processMessage what=4
D/SoftapController(  327): Softap fwReload - Ok
,D/DSQN    ( 1026): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/CommandListener(  327): Setting iface cfg
D/CommandListener(  327): Trying to bring down wlan0
D/CommandListener(  327): Clearing all IP addresses on wlan0
,I/ActivityManager( 1026): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=6136 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,D/Tethering( 1026): sendTetherStateChangedBroadcast 0, 0, 0
E/WifiHW  ( 1026): Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,D/ProfileConfigQcom( 6098): [BTUI] HeadsetService is supported
D/ProfileConfigQcom( 6098): Adding HeadsetService
D/ProfileConfigQcom( 6098): [BTUI] A2dpService is supported
E/WifiStateMachine( 1026): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1026): useWiFiOffloading() : false
E/WifiStateMachine( 1026): CONFIG_LGE_WLAN_PATH : true
D/ProfileConfigQcom( 6098): Adding A2dpService
D/ProfileConfigQcom( 6098): [BTUI] HidService is supported
D/ProfileConfigQcom( 6098): Adding HidService
D/ProfileConfigQcom( 6098): [BTUI] HealthService is supported
D/ProfileConfigQcom( 6098): Adding HealthService
D/WifiMonitor( 1026): startMonitoring(wlan0) with mConnected = false
D/LGBluetoothFeatureConfig( 6098): isSupportPan() :  mTargetOp=OPEN
D/WifiMonitor( 1026): connecting to supplicant
I/WifiServerServiceExt( 1026): WIFI_STATE_CHANGED_ACTION [2]
V/WfdStateTracker( 1960): WfdStateTracker handleDirectStateChangedEvent: 1
D/ProfileConfigQcom( 6098): [BTUI] PanService is supported
D/ProfileConfigQcom( 6098): Adding PanService
D/ProfileConfigQcom( 6098): [BTUI] GattService is supported
D/ProfileConfigQcom( 6098): Adding GattService
D/ProfileConfigQcom( 6098): [BTUI] BluetoothMapService is supported
D/ProfileConfigQcom( 6098): Adding BluetoothMapService
D/ProfileConfigQcom( 6098): [BTUI] HeadsetClientService is NOT supported
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
W/wpa_supplicant( 6154): type=1400 audit(0.0:153): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/wpa_supplicant( 6154): type=1400 audit(0.0:154): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/wpa_supplicant( 6154): Successfully initialized wpa_supplicant
,D/BluetoothManagerService( 1026): Message: 20
D/BluetoothManagerService( 1026): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@25bc4f1a:true
D/BluetoothAdapterState( 6098): make
I/LGFMServiceAdapter( 6098): [FM] LGFMServiceAdapter : create
I/bluedroid-qcom( 6098): init
I/BluetoothAdapterState( 6098): Entering OffState
I/bte_conf( 6098): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
I/bte_conf( 6098): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 6098): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 6098): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
D/BTIF_CORE( 6098): [BTUI] lge_load_bluetooth_address
,I/bluedroid-qcom( 6098): get_profile_interface socket
I/bluedroid-qcom( 6098): get_profile_interface map_client
I/GKI_LINUX( 6098): gki_task_entry task_id=1 [BTIF] starting
D/BluetoothAdapterProperties( 6098): Address is:58:3F:54:73:64:C0
D/BluetoothAdapterProperties( 6098): Name is: G3-1
D/BluetoothManagerService( 1026): Bluetooth Adapter name changed to G3-1
D/BluetoothManagerService( 1026): Stored Bluetooth name: G3-1
D/BluetoothManagerService( 1026): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService( 1026): Message: 40
D/BluetoothManagerService( 1026): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
I/bluedroid-qcom( 6098): config_hci_snoop_log
D/BluetoothManagerService( 1026): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService( 1026): Broadcasting onBluetoothServiceUp() to 7 receivers.
W/bdaddr_loader( 6159): type=1400 audit(0.0:155): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/bdaddr_loader( 6159): type=1400 audit(0.0:156): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/wpa_supplicant( 6154): rfkill: Cannot open RFKILL control device
,I/wpa_supplicant( 6154): [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
V/LGMDMManagerInternal( 6098): Create singleton instance
D/lge_bdaddr_loader( 6159): [BTUI] bdaddr_loader ::: START
,D/lge_bdaddr_loader( 6159): [BTUI] bluetooth_load_bdaddress
I/LGFTMITEM( 6159): [GET_FTM][id=8], offset=16384
D/lge_bdaddr_loader( 6159): [BTUI] bdaddr to set in property : 58:3F:54:73:64:C0
E/lge_bdaddr_loader( 6159): [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:64:C0
D/lge_bdaddr_loader( 6159): [BTUI] bdaddr_loader ::: END
W/ResourcesManager( 6136): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6136): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6136): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6136): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 6136): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6136): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/BluetoothAdapterState( 6098): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 6098): Setting state to 11
I/BluetoothAdapterState( 6098): Bluetooth adapter state changed: 10-> 11
D/BluetoothManagerService( 1026): Message: 60
D/BluetoothManagerService( 1026): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService( 1026): Bluetooth State Change Intent: 10 -> 11
,D/LGBluetoothAPIService( 1960): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
I/[SystemUI]BluetoothHandler( 1465): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
I/LGBluetoothServiceJni( 6098): classInitNative: succeeds
D/BluetoothBondStateMachine( 6098): make
D/BluetoothAdapterService( 6098): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37432350
D/LGBluetoothServiceAdapter( 6098): [BTUI] check adapter is available - false.
D/BluetoothAdapterService( 6098): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37432350
D/LGBluetoothServiceAdapter( 6098): [BTUI] check adapter is available - true : set adapter available.
D/LGBluetoothSettingsDBObserver( 6098): [BTUI] register observer for LG device name DB
,I/BluetoothBondStateMachine( 6098): StableState(): Entering Off State
E/BluetoothAdapterService( 6098): File transfer profiles supported!!
,E/BluetoothAdapterService( 6098): File transfer profiles supported!!
,D/BluetoothHeadset( 1026): Proxy object connected
D/BluetoothHeadset( 1865): Proxy object connected
D/BluetoothHeadset( 1865): Proxy object connected
D/HeadsetService( 6098): Received start request. Starting profile...
I/LGBluetoothHeadsetServiceJni( 6098): classInitNative: succeeds
D/LGBluetoothHfpAdapter( 6098): Version 1.6
D/LGBluetoothFeatureConfig( 6098): isPrivacyLogsEnabled : true
I/BluetoothHeadsetServiceJni( 6098): classInitNative: succeeds
D/HeadsetStateMachine( 6098): make
D/BluetoothHeadset( 1865): Proxy object connected
I/wpa_supplicant( 6154): rfkill: Cannot open RFKILL control device
E/BluetoothAdapterService( 6098): File transfer profiles supported!!
D/UsbSettingsReceiver( 6136): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6136): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6136): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6136): [AUTORUN] persist.sys.usb.config = ptp_only,adb
,E/BluetoothAdapterService( 6098): File transfer profiles supported!!
E/BluetoothAdapterService( 6098): File transfer profiles supported!!
D/UsbSettingsReceiver( 6136): [AUTORUN] onReceive() : app userid = 0, current userid = 0
E/BluetoothAdapterService( 6098): File transfer profiles supported!!
E/BluetoothAdapterService( 6098): File transfer profiles supported!!
D/LgDataFeature( 6098): LgDataFeature() Constructor: none
D/LgDataFeature( 6098): LgDataFeature() Constructor Done, null
,D/HeadsetStateMachine( 6098): max_hf_connections = 1
I/bluedroid-qcom( 6098): get_profile_interface handsfree
V/ToneGenerator( 6098): ToneGenerator constructor: streamType=8, volume=1.000000
V/AudioPolicyService(  331): registerClient() client 0xb100fc60, uid 1002
V/AudioPolicyManager(  331): getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  331): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  331): getOutput() returns output 2
,V/AudioSystem( 6098): getOutputSamplingRate() no output descriptor for output 2 in gOutputs
V/AudioFlinger(  331): registerClient() client 0xb5581688, pid 6098
V/AudioSystem(  331): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  331): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 3243): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 3243): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1465): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1465): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1865): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 6098): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1865): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 2231): ioConfigChanged() event 0, ioHandle 2
,V/AudioSystem( 2231): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1026): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1026): ioConfigChanged() opening already existing output! 2
V/AudioSystem(  331): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem(  331): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1465): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1465): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1865): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1865): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1026): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1026): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 2231): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 2231): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 3243): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 3243): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 6098): ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
V/AudioSystem( 6098): ioConfigChanged() event 0, ioHandle 4
V/ToneGenerator( 6098): Create Track: 0xb4928a80
V/AudioTrack( 6098): set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
V/AudioSystem( 6098): ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
V/AudioTrack( 6098): set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
V/AudioPolicyManager(  331): getOutputForAttr() usage=3, content=4, tag= flags=00000000
V/AudioPolicyManager(  331): getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  331): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  331): getOutput() returns output 2
I/AudioFlinger(  331): isAudioPlaybackHookOn() false
V/AudioPolicyManager(  331): getOutputForAttr() usage=3, content=4, tag= flags=00000000
V/AudioPolicyManager(  331): getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
V/AudioPolicyManagerEx(  331): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  331): getOutput() returns output 2
V/AudioSystem( 6098): getLatency() output 2, latency 50
V/AudioSystem( 6098): getFrameCount() output 2, frameCount 960
V/AudioTrack( 6098): createTrack_l() output 2 afLatency 50
V/AudioFlinger(  331): [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
V/AudioFlinger(  331): [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
V/AudioFlinger(  331): [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
V/AudioFlinger(  331): [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
V/AudioFlinger(  331): createTrack() lSessionId: 16
V/AudioTrack( 6098): AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
V/AudioFlinger(  331): acquiring 16 from 6098, for 6098
V/AudioFlinger(  331):  added new entry for 16
V/ToneGenerator( 6098): ToneGenerator INIT OK, time: 108799
D/BluetoothAdapterService( 6098): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37432350
D/HeadsetStateMachine( 6098): Enter Disconnected: -2, size: 0
D/HeadsetPhoneState( 6098): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 6098): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetStateMachine( 6098): [BTUI] change sampling rate to 8000 when device is disconnected
D/BluetoothAdapterService( 6098): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37432350
V/AudioFlinger(  331): setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6098
D/audio_hw_primary(  331): adev_set_parameters: enter: bt_samplerate=8000
V/voice   (  331): voice_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  331): voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
V/compr,ess_voip(  331): voice_extn_compress_voip_set_parameters: exit
V/voice   (  331): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  331): LGE_platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  331): platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  331): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  331): lge_platform_set_loopback_parameters: enter: 
V/audio_hw_primary(  331): adev_set_parameters: exit with code(0)
E/audio_a2dp_hw(  331): adev_set_parameters: ERROR: set param called even when stream out is null
V/ToneGenerator( 6098): ToneGenerator destructor
V/ToneGenerator( 6098): stopTone
V/ToneGenerator( 6098): Delete Track: 0xb4928a80
D/BluetoothA2dp( 1026): Proxy object connected
D/A2dpService( 6098): Received start request. Starting profile...
V/AudioTrack( 6098): ~AudioTrack, releasing session id from 6098 on behalf of 6098
V/AudioPolicyService(  331): AudioCommandThread() adding release output 2
I/BluetoothAvrcpServiceJni( 6098): classInitNative: succeeds
V/AudioPolicyService(  331): inserting command: 6 at index 0, num commands 0
V/AudioFlinger(  331): releasing 16 from 6098 for 6098
V/AudioFlinger(  331):  decremented refcount to 0
V/AudioFlinger(  331): purging stale effects
V/AudioPolicyService(  331): AudioCommandThread() waking up
V/AudioPolicyService(  331): AudioCommandThread() processing release output 2
V/AudioPolicyManager(  331): releaseOutput() 2
V/AudioPolicyService(  331): AudioCommandThread() going to sleep
V/AudioFlinger(  331): PlaybackThread::Track destructor
V/AudioFlinger(  331): removeClient_l() pid 6098, calling pid 331
V/Avrcp   ( 6098): make
D/Avrcp   ( 6098): [BTUI] Use Native AVRCP : init jni
I/bluedroid-qcom( 6098): get_profile_interface avrcp
W/Process ( 1026): Unable to open /proc/6162/status
V/LGMDMManager( 6098): Create singleton instance
V/AudioManager( 6098): registerRemoteController: size of Media player list: 0
D/UsbSettingsControl( 6136): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6136): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6136): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6136): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6136): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6136): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 6136): [AUTORUN] setTetherStatus() : status=false
I/BluetoothAdapterState( 6098): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
I/ActivityManager( 1026): Killing 5768:com.google.android.partnersetup/u0a8 (adj 15): empty #17
E/AudioManager( 6098): No RCC entry present to update
E/RemoteController( 6098): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothAvrcpQcomServiceJni( 6098): classInitQcomNative: succeeds
D/LGBluetoothAvrcpQcomAdapter( 6098): [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
I/BluetoothAvrcpQcomServiceJni( 6098): initQcomNative: succeeds
,I/wpa_supplicant( 6154): [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
I/wpa_supplicant( 6154): p2p0: CTRL-EVENT-AVOID-FREQ ranges=
,I/wpa_supplicant( 6154): wlan0: CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine( 1026):  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
E/WifiStateMachine( 1026):  SupplicantStartingState CMD_START_DRIVER 0 0
D/WifiMonitor( 1026): Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
D/WifiMonitor( 1026): Dropping event because (p2p0) is stopped
D/WifiMonitor( 1026): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiStateMachine( 1026):  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
E/WifiMonitor( 1026): WifiMonitor:wlan0 cnt=0 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine( 1026):  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
E/WifiMonitor( 1026): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1026): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine( 1026):  SupplicantStartingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1026):  DefaultState CMD_RECONNECT 0 0
E/WifiStateMachine( 1026):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1026):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1026):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1026):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1026):  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
D/WifiNative-wlan0( 1026): doString: [DRIVER MACADDR]
D/WifiNative-wlan0( 1026):    returned Macaddr = c4:9a:02:7b:60:ac
D/WifiStateMachine( 1026): MAC Addr from driver = c4:9a:02:7b:60:ac
D/WifiOffDelayIfNotUsed( 1026): setPowerSaveActivated(false)
W/libprocessgroup( 1026): failed to open /acct/uid_10008/pid_5768/cgroup.procs: No such file or directory
,D/LGBluetoothAvrcpQcomAdapter( 6098): [BTUI] [+] updateMediaPlayerInfo
E/WifiStateMachine( 1026): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1026): useWiFiOffloading() : false
E/WifiStateMachine( 1026): CONFIG_LGE_WLAN_PATH : true
D/WifiNative-wlan0( 1026): doBoolean: SET update_config 1
,D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1026): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1026): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiNative-wlan0( 1026): SET update_config 1: returned true
D/WfdService( 1960): Waiting for WifiP2p enabling
D/WifiConfigStore( 1026): Loading config and enabling all networks 
D/WifiNative-wlan0( 1026): doString: [LIST_NETWORKS]
D/WifiNative-wlan0( 1026):    returned network id / ssid / bssid / flags 0	NG700	any	
I/WifiServerServiceExt( 1026): WIFI_STATE_CHANGED_ACTION [3]
I/WifiServerServiceExt( 1026): batteryPsActivateMsgHandler : state:0 event:3
D/UsbSettingsReceiver( 6136): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6136): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6136): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6136): [AUTORUN] persist.sys.usb.config = ptp_only,adb
E/WifiConfigStore( 1026): readNetworkVariablesFromSupplicantFile key=psk
D/UsbSettingsReceiver( 6136): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 6136): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6136): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 6136): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6136): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6136): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 6136): [AUTORUN] setTetherStatus() : status=false
,E/WifiConfigStore( 1026): readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
E/WifiConfigStore( 1026): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
I/ActivityManager( 1026): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6168 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,D/WifiStateMachine( 1026): enableVerboseLogging : level 2
D/WifiNative-wlan0( 1026): doBoolean: SET device_name g3_global_com
D/WifiNative-wlan0( 1026): SET device_name g3_global_com: returned true
D/WifiNative-wlan0( 1026): doBoolean: SET manufacturer LGE
D/WifiNative-wlan0( 1026): SET manufacturer LGE: returned true
D/WifiNative-wlan0( 1026): doBoolean: SET model_name LG-D855
D/WifiNative-wlan0( 1026): SET model_name LG-D855: returned true
D/WifiNative-wlan0( 1026): doBoolean: SET model_number LG-D855
D/WifiNative-wlan0( 1026): SET model_number LG-D855: returned true
D/WifiNative-wlan0( 1026): doBoolean: SET serial_number LGD8553bed2d08
D/WifiNative-wlan0( 1026): SET serial_number LGD8553bed2d08: returned true
D/WifiNative-wlan0( 1026): doBoolean: SET config_methods physical_display virtual_push_button
V/SIM_STK ( 1026): Menu title from STK is T-Mobile
D/WifiNative-wlan0( 1026): SET config_methods physical_display virtual_push_button: returned true
V/SIM_STK ( 1026): Menu title from STK is T-Mobile
D/WifiNative-wlan0( 1026): doBoolean: SET device_type 10-0050F204-5
D/WifiNative-wlan0( 1026): SET device_type 10-0050F204-5: returned true
D/WfdsService( 1960): Supplicant Connection state is changed : true
D/WfdsService( 1960): DefaultState - WIFI_SUPPLICANT_CONNECTED
D/WfdsService( 1960): Set the WFDS Monitor: true
D/WifiStateMachine( 1026): Setting OUI to DA-A1-19
D/WifiNative-wlan0( 1026): doBoolean: SCAN_INTERVAL 120
D/WifiNative-wlan0( 1026): SCAN_INTERVAL 120: returned true
D/WifiNative-HAL( 1026): Setting external_sim to 1
D/WifiNative-wlan0( 1026): doBoolean: SET external_sim 1
D/WifiNative-wlan0( 1026): SET external_sim 1: returned true
I/WifiNative-HAL( 1026): startHal
E/wifi    ( 1026): getStaticLongField sWifiHalHandle 0x989658dc
E/WifiHAL ( 1026): Could not connect handle
D/wifi    ( 1026): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x3021aa
I/WifiNative-HAL( 1026): Could not start hal
D/WifiStateMachine( 1026): Setting OUI to DA-A1-19
D/WfdsMonitor( 1960): WfdsMonitorThread create
I/WifiNative-HAL( 1026): startHal
E/wifi    ( 1026): getStaticLongField sWifiHalHandle 0x9896585c
E/WifiHAL ( 1026): Could not connect handle
D/wifi    ( 1026): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x501a5a
I/WifiNative-HAL( 1026): Could not start hal
D/WfdsMonitor( 1960): WFDS Monitor is created and started
D/WfdsService( 1960): WiFi: Supplicant connection re-established
D/WifiNative-wlan0( 1026): doBoolean: STA_AUTOCONNECT 1
D/WifiNative-wlan0( 1026): STA_AUTOCONNECT 1: returned true
D/WifiNative-wlan0( 1026): doBoolean: DRIVER BTCOEXSCAN-STOP
I/wpa_supplicant( 6154): wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
D/WifiNative-wlan0( 1026): DRIVER BTCOEXSCAN-STOP: returned true
E/CtrlSupplicant( 1960): Access OK "@android:wpa_wlan0"
E/CtrlSupplicant( 1960): Succeed to open control connection
E/CtrlSupplicant( 1960): Succeed to open monitor connection
D/WfdsMonitor( 1960): Supplicant connection established
D/WfdsService( 1960): Connected to the supplicant for wfds
I/StatusBar.NetworkController( 1465): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1465): mWifiConnected = false, mWifiLevel = 0
D/WifiHS20( 1026): hidePasspointNotification off =false
,D/WifiNative-wlan0( 1026): doBoolean: DRIVER RXFILTER-STOP
,D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
I/wpa_supplicant( 6154): wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
D/WifiNative-wlan0( 1026): DRIVER RXFILTER-STOP: returned true
D/WifiNative-wlan0( 1026): doBoolean: DRIVER RXFILTER-REMOVE 3
I/wpa_supplicant( 6154): wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
W/Settings( 1026): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1026): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed( 1026): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiNative-wlan0( 1026): DRIVER RXFILTER-REMOVE 3: returned true
D/WifiNative-wlan0( 1026): doBoolean: DRIVER RXFILTER-START
I/wpa_supplicant( 6154): wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
D/WifiNative-wlan0( 1026): DRIVER RXFILTER-START: returned true
D/WifiNative-wlan0( 1026): doBoolean: DRIVER RXFILTER-STOP
I/wpa_supplicant( 6154): wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
D/WifiNative-wlan0( 1026): DRIVER RXFILTER-STOP: returned true
D/WifiNative-wlan0( 1026): doBoolean: DRIVER RXFILTER-REMOVE 2
I/wpa_supplicant( 6154): android_multicast_filter_startstop : multicast filter set
D/WifiNative-wlan0( 1026): DRIVER RXFILTER-REMOVE 2: returned true
D/WifiNative-wlan0( 1026): doBoolean: DRIVER RXFILTER-START
I/wpa_supplicant( 6154): wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
D/WifiNative-wlan0( 1026): DRIVER RXFILTER-START: returned true
E/WifiNative: ( 1026): [109,027,556 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
D/WifiNative-wlan0( 1026): doBoolean: RECONNECT
D/WifiNative-wlan0( 1026): RECONNECT: returned true
D/WifiNative-wlan0( 1026): doString: [STATUS]
D/WifiMonitor( 1026): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1026): WifiMonitor:wlan0 cnt=1 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiNative-wlan0( 1026):    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
D/WifiNative-wlan0( 1026): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 6154): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1026): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1026): doBoolean: SET ps 1
D/WifiNative-wlan0( 1026): SET ps 1: returned true
D/LGWifiP2pService( 1026): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService( 1026): SCAN_AVAILABLE : 3
D/RttService( 1026): SCAN_AVAILABLE : 3
D/WifiScanningService( 1026): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL( 1026): startHal
E/wifi    ( 1026): getStaticLongField sWifiHalHandle 0x94f6b99c
E/WifiHAL ( 1026): Could not connect handle
D/wifi    ( 1026): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x701a3e
I/WifiNative-HAL( 1026): Could not start hal
E/WifiScanningService( 1026): could not start HAL
D/RttService( 1026): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  327): Setting iface cfg
D/CommandListener(  327): Trying to bring up p2p0
D/WifiMonitor( 1026): startMonitoring(p2p0) with mConnected = true
E/WifiStateMachine( 1026):  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
D/LGWifiP2pService( 1026): P2pEnablingState
D/LGWifiP2pService( 1026): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1026): P2p socket connection successful
E/WifiStateMachine( 1026):  DisconnectedState CMD_START_DRIVER 0 0
D/LGWifiP2pService( 1026): P2pEnabledState
E/WifiStateMachine( 1026):  ConnectModeState CMD_START_DRIVER 0 0
D/LGWifiP2pService( 1026): sending p2p connection changed broadcast
V/WfdStateTracker( 1960): WfdStateTracker handleDirectStateChangedEvent: 2
D/WifiNative-p2p0( 1026): doBoolean: SET persistent_reconnect 1
D/WfdsService( 1960): WifiP2pState is changed : true
D/WfdsService( 1960): Receive the WFDS_ENABLE Method
D/WfdsService( 1960): Set the WFDS Monitor: true
D/WfdsService( 1960): Connected to the supplicant for wfds
D/WfdsJNI ( 1960): doCommand: WFDS_SET TRUE
I/wpa_supplicant( 6154): WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
D/WifiNative-p2p0( 1026): SET persistent_reconnect 1: returned true
D/WifiNative-p2p0( 1026): doBoolean: SET device_name G3-1
D/WfdsJNI ( 1960): doCommand: WFDS_GET_MAC_ADDRESS
I/,wpa_supplicant( 6154): WFDS: wfds_supplicant_wfds_cmd: cmd = GET_MAC_ADDRESS
D/WfdsJNI ( 1960): doCommand: IFNAME=wlan0 GET_CAPABILITY channels
D/WfdsService( 1960): selectPreferredScanChannel [36]
D/WfdsService( 1960): STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7b:60:ac
D/WifiNative-p2p0( 1026): SET device_name G3-1: returned true
D/LGWifiP2pService( 1026): [LGE_P2P] initializeP2pSettings() check postfix
D/LGWifiP2pService( 1026): before postfix = G3-1
D/WifiServerServiceExt( 1026): postfix byte check : 4
D/LGWifiP2pService( 1026): after postfix = G3-1
D/WifiNative-p2p0( 1026): doBoolean: SET p2p_ssid_postfix -G3-1
D/WifiNative-p2p0( 1026): SET p2p_ssid_postfix -G3-1: returned true
D/WifiNative-p2p0( 1026): doBoolean: SET device_type 10-0050F204-5
D/WifiNative-p2p0( 1026): SET device_type 10-0050F204-5: returned true
D/WifiNative-p2p0( 1026): doBoolean: SET config_methods virtual_push_button physical_display keypad
D/WifiNative-p2p0( 1026): SET config_methods virtual_push_button physical_display keypad: returned true
D/WifiNative-p2p0( 1026): doBoolean: P2P_SET conc_pref p2p
D/WifiNative-p2p0( 1026): P2P_SET conc_pref p2p: returned true
D/WifiNative-HAL( 1026): p2pGetDeviceAddress
D/WfdsService( 1960): WIFI_P2P_CONNECTION_CHANGED_ACTION
D/WifiNative-HAL( 1026): p2pGetDeviceAddress returning 02:9a:02:7b:60:ac
D/WfdsService( 1960): isConnected: false
E/WifiStateMachine( 1026):  DriverStartedState CMD_START_DRIVER 0 0
E/WifiStateMachine( 1026):  DisconnectedState what:132106 1 0
E/WifiStateMachine( 1026):  ConnectModeState what:132106 1 0
E/WifiStateMachine( 1026):  DriverStartedState what:132106 1 0
I/WifiServerServiceExt( 1026): setWifiDualbandAPConnection band : 1
E/wpa_supplicant( 6154): nWIFIDualbandAPConnection: 1
D/LGWifiP2pService( 1026): DeviceAddress: 02:9a:02:7b:60:ac
D/WifiNative-p2p0( 1026): doBoolean: P2P_FLUSH
D/WifiNative-p2p0( 1026): P2P_FLUSH: returned true
D/WifiNative-p2p0( 1026): doBoolean: P2P_SERVICE_FLUSH
D/WifiNative-p2p0( 1026): P2P_SERVICE_FLUSH: returned true
D/WifiNative-p2p0( 1026): doString: [LIST_NETWORKS]
D/WifiNative-p2p0( 1026):    returned network id / ssid / bssid / flags
D/WifiNative-p2p0( 1026): doBoolean: SAVE_CONFIG
I/WfdStateTracker( 1960): handleP2pThisDeviceChanged
D/WfdsService( 1960): WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
D/WfdsService( 1960): Update P2p Interface State: 3
E/WifiStateMachine( 1026):  DisconnectedState what:132096 -100 0
E/WifiStateMachine( 1026):  ConnectModeState what:132096 -100 0
E/WifiStateMachine( 1026):  DriverStartedState what:132096 -100 0
I/WifiServerServiceExt( 1026): set CMD_DISCONNECT_RSSI_LVL : -100
E/wpa_supplicant( 6154): disconnect_rssi_lvl: -100
D/WifiNative-p2p0( 1026): SAVE_CONFIG: returned true
D/LGWifiP2pService( 1026): sending p2p persistent groups changed broadcast
E/WifiStateMachine( 1026):  DisconnectedState CMD_SET_COUNTRY_CODE 1 0 cz
E/WifiStateMachine( 1026):  ConnectModeState CMD_SET_COUNTRY_CODE 1 0 cz
E/WifiStateMachine( 1026):  DriverStartedState CMD_SET_COUNTRY_CODE 1 0 cz
D/WifiNative-wlan0( 1026): doBoolean: DRIVER COUNTRY CZ
I/wpa_supplicant( 6154): wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
I/wpa_supplicant( 6154): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
I/wpa_supplicant( 6154): [LGE_PATCH] driver_cmd() country:CZ
I/wpa_supplicant( 6154): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WfdsMonitor( 1960): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
I/wpa_supplicant( 6154): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiNative-wlan0( 1026): DRIVER COUNTRY CZ: returned true
D/WifiMonitor( 1026): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
D/WfdsMonitor( 1960): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1026): WifiMonitor:wlan0 cnt=2 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiStateMachine( 1026):  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
E/WifiMonitor( 1026): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1026): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
D/WifiMonitor( 1026): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiStateMachine( 1026):  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
E/WifiMonitor( 1026): WifiMonitor:p2p0 cnt=3 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1026): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1026): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiMonitor( 1026): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiStateMachine( 1026):  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
E/WifiMonitor( 1026): WifiMonitor:p2p0 cnt=4 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
W/ActivityManager( 1026): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
E/WifiMonitor( 1026): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1026): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/LGWifiP2pService( 1026): InactiveState
D/LGWifiP2pService( 1026): InactiveState{ when=-14ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1026): P2pEnabledState{ when=-14ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1026): doBoolean: DRIVER COUNTRY CZ
I/wpa_supplicant( 6154): wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
I/wpa_supplicant( 6154): p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
D/WifiMonitor( 1026): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
E/WifiMonitor( 1026): WifiMonitor:p2p0 cnt=5 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1026): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1026): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
I/wpa_supplicant( 6154): [LGE_PATCH] driver_cmd() country:CZ
I/wpa_supplicant( 6154): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiMonitor( 1026): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1026): WifiMonitor:p2p0 cnt=6 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1026): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1026): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
I/wpa_supplicant( 6154): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiMonitor( 1026): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1026): WifiMonitor:p2p0 cnt=7 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1026): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1026): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiService( 1026): New client listening to asynchronous messages
D/WfdsMonitor( 1960): Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
D/WfdsMonitor( 1960): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WfdsMonitor( 1960): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WifiNative-p2p0( 1026): DRIVER COUNTRY CZ: returned true
D/LGWifiP2pService( 1026): InactiveState{ when=-4ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1026): P2pEnabledState{ when=-4ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1026): InactiveState{ when=-3ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1026): P2pEnabledState{ when=-3ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1026): DefaultState{ when=-3ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1026): InactiveState{ when=-3ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1026): P2pEnabledState{ when=-3ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1026): DefaultState{ when=-3ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1026): InactiveState{ when=-4ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1026): P2pEnabledState{ when=-4ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1026): DefaultState{ when=-4ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1026): InactiveState{ when=-4ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1026): P2pEnabledState{ when=-4ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1026): DefaultState{ when=-4ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
W/WfdsService( 1960): DefaultState - msg [9441285] is not handled
E/WifiServerServiceExt( 1026): No p2p device connected
D/LGBluetoothAvrcpQcomAdapter( 6098): [BTUI] installed app name: Music
D/WifiNative-wlan0( 1026): doBoolean: DRIVER SETBAND 0
I/wpa_supplicant( 6154): wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
I/wpa_supplicant( 6154): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
D/WifiMonitor( 1026): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
E/WifiMonitor( 1026): WifiMonitor:wlan0 cnt=8 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
E/WifiMonitor( 1026): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
E/WifiMonitor( 1026): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
D/WifiNative-wlan0( 1026): DRIVER SETBAND 0: returned true
D/WifiNative-wlan0( 1026): doBoolean: BSS_FLUSH 0
D/WifiNative-wlan0( 1026): BSS_FLUSH 0: returned true
D/WifiNative-wlan0( 1026): doBoolean: SCAN
D/WifiNative-wlan0( 1026): SCAN: returned false
E/WifiStateMachine( 1026):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=109069  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine( 1026):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=109070  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/LGBluetoothAvrcpQcomAdapter( 6098): [BTUI] installed app name: Google Play Music
E/WifiStateMachine( 1026):  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1026):  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
D/LGBluetoothAvrcpQcomAdapter( 6098): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 6098): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 6098): [BTUI]          packageName: com.lge.music
E/WifiStateMachine( 1026):  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
D/LGBluetoothAvrcpQcomAdapter( 6098): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6098): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 6098): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6098): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 6098): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6098): [BTUI] [-] updateMediaPlayerInfo
E/WifiStateMachine( 1026):  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
I/BluetoothA2dpServiceJni( 6098): classInitNative
I/BluetoothA2dpServiceJni( 6098): classInitNative: succeeds
E/WifiStateMachine( 1026):  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
D/A2dpStateMachine( 6098): make
I/StatusBar.NetworkController( 1465): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1465): mWifiConnected = false, mWifiLevel = 0
I/bluedroid-qcom( 6098): get_profile_interface a2dp
I/GKI_LINUX( 6098): gki_task_entry task_id=2 [A2DP-MEDIA] starting
W/Settings( 1026): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1026): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1026): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WifiServerServiceExt( 1026): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1026): setSupplicantStateSCANNING
I/LGBluetoothA2dpServiceJni( 6098): classInitNative: succeeds
I/LGBluetoothA2dpAdapter( 6098): [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
D/BluetoothAdapterService( 6098): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37432350
I/BluetoothHidServiceJni( 6098): classInitNative: succeeds
D/A2dpStateMachine( 6098): Enter Disconnected: -2
D/HidService( 6098): Received start request. Starting profile...
I/bluedroid-qcom( 6098): get_profile_interface hidhost
D/BluetoothAdapterService( 6098): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37432350
I/BluetoothHealthServiceJni( 6098): classInitNative: succeeds
D/HealthService( 6098): Received start request. Starting profile...
I/bluedroid-qcom( 6098): get_profile_interface health
I/LGBluetoothHealthServiceJni( 6098): classInitNative: succeeds
D/BluetoothAdapterService( 6098): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37432350
,I/BluetoothPanServiceJni( 6098): classInitNative(L105): succeeds
D/PanService( 6098): Received start request. Starting profile...
D/BluetoothPanServiceJni( 6098): initializeNative(L110): pan
I/bluedroid-qcom( 6098): get_profile_interface pan
I/LGBluetoothPanAdapter( 6098): [BTUI] getInstance : create [LGBluetoothPanAdapter]
D/BluetoothAdapterService( 6098): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37432350
I/BtGatt.JNI( 6098): classInitNative(L901): classInitNative: Success!
D/BtGatt.DebugUtils( 6098): handleDebugAction() action=null
D/BtGatt.GattService( 6098): Received start request. Starting profile...
D/BtGatt.GattService( 6098): start()
I/bluedroid-qcom( 6098): get_profile_interface gatt
D/BtGatt.AdvertiseManager( 6098): advertise manager created
I/ActivityManager( 1026): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6197 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
W/FormManager( 6168): Network not available. Please check & try again.
D/BluetoothAdapterService( 6098): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37432350
D/BluetoothAdapterService( 6098): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37432350
I/LGBluetoothMapAdapter( 6098): [BTUI] getInstance : create [LGBluetoothMapAdapter]
V/BluetoothMapService( 6098): BluetoothMapBinder()
D/BluetoothMapService( 6098): Received start request. Starting profile...
D/BluetoothMapService( 6098): start()
D/BluetoothMapEmailSettingsLoader( 6098): Found 0 applications
D/BluetoothMapEmailAppObserver( 6098): createReceiver()
D/BluetoothMapEmailAppObserver( 6098): initObservers()
,D/BluetoothMapEmailAppObserver( 6098): getEnabledAccountItems()
D/BluetoothAdapterService( 6098): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37432350
D/HeadsetStateMachine( 6098): Proxy object connected
D/LGBluetoothHfpAdapter( 6098): [BTUI] queryPhoneState
D/LGBluetoothHfpAdapter( 6098): Try to query the phonestate on bind
D/BluetoothPhoneService.BluetoothLTECall( 1865):  call mBluetoothHeadset.phoneStateChanged()
W/BluetoothHeadset( 1865): Proxy not attached to service
D/BluetoothHeadset( 1865): java.lang.Throwable
D/BluetoothHeadset( 1865): 	at android.bluetooth.BluetoothHeadset.phoneStateChanged(BluetoothHeadset.java:826)
D/BluetoothHeadset( 1865): 	at com.android.phone.BluetoothPhoneService$BluetoothLTECall.handleQueryPhoneState(BluetoothPhoneService.java:1527)
D/BluetoothHeadset( 1865): 	at com.android.phone.BluetoothPhoneService$BluetoothLTECall.access$700(BluetoothPhoneService.java:1360)
D/BluetoothHeadset( 1865): 	at com.android.phone.BluetoothPhoneService$1.handleMessage(BluetoothPhoneService.java:268)
D/BluetoothHeadset( 1865): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BluetoothHeadset( 1865): 	at android.os.Looper.loop(Looper.java:135)
D/BluetoothHeadset( 1865): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
D/BluetoothHeadset( 1865): 	at java.lang.reflect.Method.invoke(Native Method)
D/BluetoothHeadset( 1865): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/BluetoothHeadset( 1865): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
D/BluetoothHeadset( 1865): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
V/FormManager( 6168): Network unavailable.
D/BluetoothAdapterService( 6098): Profile still not running:com.android.bluetooth.gatt.GattService
V/BluetoothPbapReceiver( 6098): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 6098): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6098): ***********state = 11
D/HeadsetStateMachine( 6098): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 6098): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 6098): Disconnected process message: 11, size: 0
D/BluetoothAdapterService( 6098): Profile still not running:com.android.bluetooth.gatt.GattService
,D/BluetoothAdapterService( 6098): Profile still not running:com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 6098): Profile still not running:com.android.bluetooth.gatt.GattService
V/PanService( 6098): [BTUI] SIM Extra State :ABSENT
D/BluetoothAdapterService( 6098): Profile still not running:com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 6098): Profile still not running:com.android.bluetooth.map.BluetoothMapService
V/BluetoothMapService( 6098): Handler(): got msg=1
D/BluetoothAdapterState( 6098): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid-qcom( 6098): enable
I/GKI_LINUX( 6098): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 6098): btu_task pending for preload complete event
I/bt_hci_bdroid( 6098): init
I/bt_vendor( 6098): bt-vendor : init
I/bt_vendor( 6098): bt-vendor : get_bt_soc_type
E/bt_vendor( 6098): get_bt_soc_type: Failed to get soc type
I/bt_vendor( 6098): init: Local BD Address : c0:64:73:54:3f:58
D/bt_userial_mct( 6098): userial_init
,D/bt_hci_bdroid( 6098): set_power 1
I/bt_vendor( 6098): bt-vendor : BT_VND_OP_POWER_CTRL: On
I/bt_vendor( 6098): Starting hciattach daemon
I/bt_vendor( 6098): try to set true
W/sh      ( 6220): type=1400 audit(0.0:157): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/sh      ( 6220): type=1400 audit(0.0:158): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/qcom-bluetooth( 6221): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,I/ActivityManager( 1026): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6223 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,V/FormManager( 6168): Network unavailable.
,I/qcom-bluetooth( 6243): /system/etc/init.qcom.bt.sh: Transport : smd 
I/qcom-bluetooth( 6245): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
I/ActivityManager( 1026): Killing 5519:com.lge.appbox.client/u0a11 (adj 15): empty #17
,I/qcom-bluetooth( 6247): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
I/qcom-bluetooth( 6248): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
D/PCSuite ( 6197): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,I/qcom-bluetooth( 6251): /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
I/qcom-bluetooth( 6252): /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,I/libmdmdetect( 6254): ESOC framework not supported
E/Diag_Lib( 6254):  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,D/bthci_qcomm_linux( 6254): [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:64:C0)
D/bthci_qcomm_common( 6254): [BTUI] bt_hci_qcomm_init:
D/bthci_qcomm_common( 6254): [BTUI]     BDADDR: 58:3F:54:73:64:C0
,D/bthci_qcomm_common( 6254): [BTUI]     BR/EDR: Class 1
D/bthci_qcomm_common( 6254): [BTUI]     LE: Class 2
D/bthci_qcomm_common( 6254): [BTUI]     Ref Clock: 32M
D/btqsocnvmtags( 6254): [BTUI] init_riva_entries: set NORMAL power settings
E/WifiMonitor( 1026): WifiMonitor:wlan0 cnt=9 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1026): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1026): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1026): WifiMonitor:wlan0 cnt=10 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1026): couldn't identify event type - WPS-AP-AVAILABLE 
E/wpa_supplicant( 6154): USIM:  scard_init function
E/WifiStateMachine( 1026):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
I/wpa_supplicant( 6154): Trying to associate with SSID 'NG700'
E/WifiStateMachine( 1026):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine( 1026):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
,E/WifiStateMachine( 1026):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
I/WifiNative-HAL( 1026): startHal
E/wifi    ( 1026): getStaticLongField sWifiHalHandle 0x989658cc
E/WifiHAL ( 1026): Could not connect handle
D/wifi    ( 1026): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x8017c2
I/WifiNative-HAL( 1026): Could not start hal
D/WifiNative-wlan0( 1026): doString: [BSS RANGE=0- MASK=0x21987]
W/libprocessgroup( 1026): failed to open /acct/uid_10011/pid_5519/cgroup.procs: No such file or directory
D/WifiMonitor( 1026): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1026): WifiMonitor:wlan0 cnt=11 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1026):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 11 0 rt=109300  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
I/StatusBar.NetworkController( 1465): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1465): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1026): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1026): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1026): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1026):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 11 0 rt=109303  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
I/StatusBar.NetworkController( 1465): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1465): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1026): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1026): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1026): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiServerServiceExt( 1026): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1026): setSupplicantStateASSOCIATING
E/ActivityThread( 6223): Failed to find provider info for com.lge.lgaccount.provider
W/LG Account v2.2( 6223): No ProfileInfo entries
,I/LG Account v2.2( 6223): isEnabled: false
I/Feature ( 6223): [Lifetracker]ver: 4.21.112(40211120)
I/Feature ( 6223): [Lifetracker]Country: EU
I/Feature ( 6223): [Lifetracker]Operator: OPEN
I/Feature ( 6223): [Lifetracker]Ranking support: false
I/Feature ( 6223): [Lifetracker]Comfort support: false
I/Feature ( 6223): [Lifetracker]Accessory: true
I/Feature ( 6223): [Lifetracker]Health device: true
I/Feature ( 6223): [Lifetracker]Extra Pedometer: false
I/Feature ( 6223): [Lifetracker]Blood glucose device: false
I/Feature ( 6223): [Lifetracker]Device Number: 3
V/WiFiOffLoadBroadcast( 6136): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
D/WifiService( 1026): New client listening to asynchronous messages
I/ActivityManager( 1026): Killing 5542:com.android.contacts/u0a19 (adj 15): empty #17
D/LgDataFeature( 6136): LgDataFeature() Constructor: none
D/LgDataFeature( 6136): LgDataFeature() Constructor Done, null
,D/WiFiOffLoadUpdatePriority( 6136): remove : truetruetrue
,E/WifiStateMachine( 1026):  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1026):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1026):  DisconnectedState CMD_SAVE_CONFIG uid=1000 0 0
E/WifiStateMachine( 1026):  ConnectModeState CMD_SAVE_CONFIG uid=1000 0 0
D/WifiNative-wlan0( 1026): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1026): SAVE_CONFIG: returned true
D/WiFiOffLoadUpdatePriority( 6136): remove1
V/WiFiOffLoadSharedPrefsUtils( 6136): save remove
,I/rmt_storage(  325): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  325): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  325): wakelock acquired: 1, error no: 42
I/rmt_storage(  325): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
,D/WiFiOffLoadBroadcast( 6136): mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
D/WiFiOffLoadBroadcast( 6136): S: false, R: false
E/WifiStateMachine( 1026):  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1026):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/WiFiOffLoadUpdatePriority( 6136): saved SSID: "NG700"
D/WiFiOffLoadUpdatePriority( 6136): connected SSID: null
D/WiFiOffLoadUpdatePriority( 6136): private wpa: "NG700" 300
D/WifiServiceImplEx( 1026): addOrUpdateNetwork pid=6136, uid=1000, packageName=android.uid.system:1000
E/addOrUpdateNetwork( 1026):  uid = 1000 SSID "NG700" nid=0
,E/WifiStateMachine( 1026):  DisconnectedState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=2
E/WifiStateMachine( 1026):  ConnectModeState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=2
E/WifiConfigStore( 1026):  key="NG700"WPA_PSK netId=0 uid=0/1000
D/WifiServerServiceExt( 1026): addOrUpdateNetwork: mThisIsFirstEnableing = false
D/WifiNative-wlan0( 1026): doBoolean: SET_NETWORK 0 ssid 4e47373030
I/wpa_supplicant( 6154): wlan0: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1026): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1026): WifiMonitor:wlan0 cnt=12 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1026): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1026): WifiMonitor:wlan0 cnt=13 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1026): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1026): WifiMonitor:wlan0 cnt=14 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1026): SET_NETWORK 0 ssid 4e47373030: returned true
D/WifiNative-wlan0( 1026): doBoolean: SET_NETWORK 0 key_mgmt WPA-PSK
D/WifiNative-wlan0( 1026): SET_NETWORK 0 key_mgmt WPA-PSK: returned true
D/WifiNative-wlan0( 1026): doBoolean: SET_NETWORK 0 proto WPA RSN
,D/WifiNative-wlan0( 1026): SET_NETWORK 0 proto WPA RSN: returned true
D/WifiNative-wlan0( 1026): doBoolean: SET_NETWORK 0 pairwise TKIP CCMP
D/WifiNative-wlan0( 1026): SET_NETWORK 0 pairwise TKIP CCMP: returned true
D/WifiNative-wlan0( 1026): doBoolean: SET_NETWORK 0 group WEP40 WEP104 TKIP CCMP
D/WifiNative-wlan0( 1026): SET_NETWORK 0 group WEP40 WEP104 TKIP CCMP: returned true
D/WifiNative-wlan0( 1026): doBoolean: SET_NETWORK 0 priority 300
D/WifiNative-wlan0( 1026): SET_NETWORK 0 priority 300: returned true
E/WifiConfigStore( 1026): will read network variables netId=0
W/libprocessgroup( 1026): failed to open /acct/uid_10019/pid_5542/cgroup.procs: No such file or directory
D/Tethering( 1026): sendTetherStateChangedBroadcast 1, 0, 0
I/wpa_supplicant( 6154): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 6154): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1026): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1026): WifiMonitor:wlan0 cnt=15 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1026): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1026): WifiMonitor:wlan0 cnt=16 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1026): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1026): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1026): WifiMonitor:wlan0 cnt=17 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1026): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1026): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1026): WifiMonitor:wlan0 cnt=18 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiConfigStore( 1026): writeIpAndProxyConfigurationsOnChange: "NG700" -> "NG700" path: /data/misc/wifi/ipconfig.txt
E/WifiConfigStore( 1026):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine( 1026):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 12 0 rt=109427  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
D/WiFiOffLoadUpdatePriority( 6136):  ssid "NG700" prio 300
D/WiFiOffLoadUpdatePriority( 6136): configuration updated: 0
E/WifiStateMachine( 1026):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 12 0 rt=109428  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1026):  DisconnectedState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=109428
E/WifiStateMachine( 1026):  ConnectModeState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=109428
E/WifiStateMachine( 1026):  DriverStartedState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=109429
E/WifiStateMachine( 1026):  SupplicantStartedState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=109429
E/WifiStateMachine( 1026):  DefaultState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=109429
E/WifiStateMachine( 1026):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 14 0 rt=109429  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
I/StatusBar.NetworkController( 1465): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1465): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1026): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returni,ng read-only value.
W/Settings( 1026): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1026): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/StatusBar.NetworkController( 1465): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1465): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1026): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1026): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1026): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
E/WifiStateMachine( 1026):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 14 0 rt=109434  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine( 1026):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1026):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1026):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1026):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1026):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1026):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 15 0 rt=109435  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1026):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 15 0 rt=109436  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1026):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=109436
E/WifiStateMachine( 1026):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=109436
D/WifiNative-wlan0( 1026): doString: [STATUS]
D/WifiMonitor( 1026): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1026): WifiMonitor:wlan0 cnt=19 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1026):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
I/WifiServiceExtension( 1026): setVHTCapabilityType  : false
I/rmt_storage(  325): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  325): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
I/rmt_storage(  325): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 22
I/rmt_storage(  325): 
,I/rmt_storage(  325): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
E/Diag_Lib(  901): [IMS_FATAL]| 3347 | 911 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
I/WifiServerServiceExt( 1026): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1026): setKeepAlivePacketInterval msec : 60
,I/StatusBar.NetworkController( 1465): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1465): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1026): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1026): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1026): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/StatusBar.NetworkController( 1465): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1465): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1026): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1026): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1026): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/ConnectivityService( 1026): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService( 1026): Got NetworkAgent Messenger
D/ConnectivityService( 1026): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1026): NetworkAgent connected
E/WifiConfigStore( 1026): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1026): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1026): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1026): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1026): SAVE_CONFIG: returned true
E/WifiConfigStore( 1026): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1026): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1026): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1026): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1026): SAVE_CONFIG: returned true
D/CommandListener(  327): Setting iface cfg
E/WifiStateMachine( 1026): Start Dhcp Watchdog 1
D/DhcpStateMachine( 1026): StoppedState
D/DhcpStateMachine( 1026): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1026): WaitBeforeStartState
E/WifiStateMachine( 1026):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=109560  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1026):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=109560  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1026):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=109560  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1026):  ObtainingIpState CMD_SAVE_CONFIG uid=1000 0 0
E/WifiStateMachine( 1026):  L2ConnectedState CMD_SAVE_CONFIG uid=1000 0 0
E/WifiStateMachine( 1026):  ConnectModeState CMD_SAVE_CONFIG uid=1000 0 0
D/WifiNative-wlan0( 1026): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1026): SAVE_CONFIG: returned true
D/WiFiOffLoadUpdatePriority( 6136): configuration saved: true
D/WifiServerServiceExt( 1026): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1026): setSupplicantStateASSOCIATED
D/WifiServerServiceExt( 1026): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1026): setSupplicantStateFOUR_WAY_HANDSHAKE
D/WifiServerServiceExt( 1026): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1026): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1026):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=109571  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1026):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=109571  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1026):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=109571  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1026):  ObtainingIpState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:-1292715392] from screen [on:0 period:-1292715392]
D/BluetoothPermissionRequest( 6136): onReceive
D/LGBluetoothFeatureConfig( 6136):  get() - isFeatureLoaded : false
E/WifiStateMachine( 1026):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1292715391]
I/WifiNative-HAL( 1026): startHal
E/wifi    ( 1026): getStaticLongField sWifiHalHandle 0x989658bc
E/WifiHAL ( 1026): Could not connect handle
D/wifi    ( 1026): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x901c8e
I/WifiNative-HAL( 1026): Could not start hal
D/WifiNative-wlan0( 1026): doString: [SIGNAL_POLL]
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1026): updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
E/WifiStateMachine( 1026):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1026):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1026):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1026):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1026):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1026):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1026): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
E/WifiStateMachine( 1026):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
E/WifiStateMachine( 1026):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
D/WifiNative-wlan0( 1026): doBoolean: DRIVER SETSUSPENDMODE 0
D/BluetoothManagerService( 1026): Message: 20
D/BluetoothManagerService( 1026): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f50b12c:true
I/ActivityManager( 1026): Killing 5789:com.lge.email/u0a23 (adj 15): empty #17
D/LGBluetoothResetSettingReceiver( 6136): return without doing reset settings.
I/wpa_supplicant( 6154): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1026): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1026): doBoolean: SET ps 0
D/WifiNative-wlan0( 1026): SET ps 0: returned true
D/WifiNative-wlan0( 1026): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 6154): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1026): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1026): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
D/LGWifiP2pService( 1026): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@f5f07f5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1026): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@f5f07f5 target=com.android.internal.util.StateMachine$SmHandler }
V/DhcpStateMachine( 1026): Current State is mWaitBeforeStartState.
D/DhcpStateMachine( 1026): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper( 1026): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
V/LgDhcpStateMachineHelper( 1026): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700" is not exist.
D/DhcpStateMachine( 1026): DHCP Start wake lock is acquired.
W/libprocessgroup( 1026): failed to open /acct/uid_10023/pid_5789/cgroup.procs: No such file or directory
D/LGBluetoothOppAdapter( 6098): [BTUI] getInstance : create [LGBluetoothOppAdapter]
D/WifiServerServiceExt( 1026): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1026): setSupplicantStateCOMPLETED
V/BluetoothFtpReceiver( 6098): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6098): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 6098): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 6098): SapReceiver onReceive 
V/BluetoothSapReceiver( 6098): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6098):  Bluetooth Adapter state = 11
I/ActivityManager( 1026): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6265 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/PCSuite ( 6197): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6136): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
W/FormManager( 6168): Network not available. Please check & try again.
V/FormManager( 6168): Network unavailable.
V/FormManager( 6168): Network unavailable.
D/WiFiOffLoadBroadcast( 6136): MCCMNC not supported: null
D/DhcpStateMachine( 1026): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper( 1026): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1026): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
W/dhcpcd  ( 6285): type=1400 audit(0.0:159): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 6285): type=1400 audit(0.0:160): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/LGDMClient( 3990): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 3990): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 3990): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
I/dhcpcd  ( 6285): version 5.5.6 starting
W/ContextImpl( 3990): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
E/dhcpcd  ( 6285): get_duid: m
D/dhcpcd  ( 6285): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 6285): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
W/ResourcesManager( 6265): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/PostponalbeReceiver( 5205): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/AuthorizationBluetoothService( 2135): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
I/PCSuite ( 6197): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/LGDMClient( 3990): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/PCSuite ( 6197): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6197): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/LGDMClient( 3990): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
V/WiFiOffLoadBroadcast( 6136): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/LGDMClient( 3990): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/WiFiOffLoadBroadcast( 6136): MCCMNC not supported: null
D/dhcpcd  ( 6285): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 6285): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 6285): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/dhcpcd  ( 6285): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 6285): wlan0: sending REQUEST (xid 0xea09697a), next in 4.13 seconds
I/ActivityManager( 1026): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6295 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
I/ActivityManager( 1026): Killing 5562:com.android.gallery3d/u0a27 (adj 15): empty #17
W/libprocessgroup( 1026): failed to open /acct/uid_10027/pid_5562/cgroup.procs: No such file or directory
W/ResourcesManager( 6295): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/QRemote ( 6295): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
D/QRemote ( 6295): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
I/QRemote ( 6295): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 6295): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 6295): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 6295): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 6295): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 6295): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6295): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6295): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6295): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/[BNRBootReceiver]( 5921): boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/BNRAndroBeam( 5921): [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
D/QRemote ( 6295): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
D/QRemote ( 6295): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
V/[BNRBootReceiver]( 5921): Boot Receiver Return
D/PostponalbeReceiver( 5205): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6136): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6136): MCCMNC not supported: null
D/QRemote ( 6295): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6295): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6295): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/WiFiOffLoadBroadcast( 6136): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
D/WiFiOffLoadBroadcast( 6136): Not supported operator for automatic switch
D/PostponalbeReceiver( 5205): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6136): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6136): MCCMNC not supported: null
D/QRemote ( 6295): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6295): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6295): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 5205): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6136): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6136): MCCMNC not supported: null
D/QRemote ( 6295): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6295): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6295): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/UsbSettingsReceiver( 6136): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6136): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6136): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6136): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6136): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 6136): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6136): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6136): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6136): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6136): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6136): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 6136): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 5205): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6136): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6136): MCCMNC not supported: null
D/QRemote ( 6295): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6295): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6295): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
E/QC-QMI  ( 6254): qmi_client [6254] 13: failed to locate client data
E/QC-QMI  (  464): qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
E/QC-QMI  (  464): QMUX qmux_client_id=13 not found in qmux client list, unable to remove
D/PostponalbeReceiver( 5205): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6136): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6136): MCCMNC not supported: null
D/QRemote ( 6295): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6295): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6295): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 5205): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6136): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6136): MCCMNC not supported: null
I/qcom-bluetooth( 6319): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:64:c0 
D/QRemote ( 6295): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6295): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6295): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/qcom-bluetooth( 6320): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
D/PostponalbeReceiver( 5205): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6136): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/bt_vendor( 6098): bluetooth satus is on
D/bt_hci_bdroid( 6098): preload
D/bt_userial_mct( 6098): userial_open(port:0)
I/bt_vendor( 6098): bt-vendor : BT_VND_OP_USERIAL_OPEN
I/bt_vendor( 6098): Done intiailizing UART
I/bt_vendor( 6098): Done intiailizing UART
I/bt_userial_mct( 6098): CMD=66, EVT=66, ACL_Out=67, ACL_In=67
I/bt_vendor( 6098): Bluetooth Firmware and transport layer are initialized
D/bt_userial_mct( 6098): Entering userial_read_thread()
I/bt-btu  ( 6098): btu_task received preload complete event
W/bt-l2cap( 6098): L2CAP - L2CA_Register() called for PSM: 0x0001
W/bt-l2cap( 6098): L2CAP - L2CA_Register() called for PSM: 0x001f
W/bt-l2cap( 6098): L2CAP - L2CA_Register() called for PSM: 0x0003
I/        ( 6098): BTE_InitTraceLevels -- TRC_HCI
I/        ( 6098): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 6098): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 6098): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 6098): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 6098): BTE_InitTraceLevels -- TRC_A2D
I/        ( 6098): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 6098): BTE_InitTraceLevels -- TRC_BTM
I/        ( 6098): BTE_InitTraceLevels -- TRC_HID_HOST
I/        ( 6098): BTE_InitTraceLevels -- TRC_GAP
I/        ( 6098): BTE_InitTraceLevels -- TRC_PAN
I/        ( 6098): BTE_InitTraceLevels -- TRC_SDP
I/        ( 6098): BTE_InitTraceLevels -- TRC_GATT
I/        ( 6098): BTE_InitTraceLevels -- TRC_SMP
I/        ( 6098): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 6098): BTE_InitTraceLevels -- TRC_BTIF
D/WiFiOffLoadBroadcast( 6136): MCCMNC not supported: null
D/QRemote ( 6295): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6295): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6295): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
V/QRemote ( 6295): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6295): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 6295): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
W/bt-btm  ( 6098): btm_decode_ext_features_page Secure conn Controller support Enabled
E/bt-btm  ( 6098): BTM_SecRegister:p_cb_info->p_le_callback == 0xa01e3061 
E/bt-btm  ( 6098): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01e3061 
E/bt-btif ( 6098): Calling BTA_HhEnable
E/bt-btif ( 6098): btif_storage_get_adapter_property service_mask:0x2140040
D/BluetoothAdapterProperties( 6098): Address is:58:3F:54:73:64:C0
W/bt-l2cap( 6098): L2CAP - L2CA_Register() called for PSM: 0x0019
W/bt-l2cap( 6098): L2CAP - L2CA_Register() called for PSM: 0x0017
W/bt-l2cap( 6098): L2CAP - L2CA_Register() called for PSM: 0x001b
W/bt-l2cap( 6098): L2CAP - L2CA_Register() called for PSM: 0x0011
W/bt-l2cap( 6098): L2CAP - L2CA_Register() called for PSM: 0x0013
D/BluetoothManagerService( 1026): Bluetooth Adapter name changed to G3-1
D/BluetoothAdapterProperties( 6098): Name is: G3-1
D/BluetoothAdapterProperties( 6098): Scan Mode:20
D/BluetoothAdapterProperties( 6098): Discoverable Timeout:120
D/bt_hci_bdroid( 6098): postload
D/bt_hci_bdroid( 6098): Used up Tx Cmd credits
W/bt-l2cap( 6098): L2CAP - L2CA_Register() called for PSM: 0x000f
D/BluetoothManagerService( 1026): Stored Bluetooth name: G3-1
W/bt-smp  ( 6098): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6098): Plain text(LSB ~ MSB) = 00 cb 68 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6098): Encrypted text(LSB ~ MSB) = bc b1 b3 de 57 ce 47 90 62 84 7e 87 b9 64 ab 7f 
D/bt_hci_bdroid( 6098): Used up Tx Cmd credits
W/bt-btm  ( 6098): Stopping oneshot timer
D/bt_hci_bdroid( 6098): Used up Tx Cmd credits
D/bt_hci_bdroid( 6098): Used up Tx Cmd credits
D/bt_hci_bdroid( 6098): Used up Tx Cmd credits
E/bt_mct  ( 6098): hci lib postload completed
D/bte_conf( 6098): Device ID record 1 : primary
D/bte_conf( 6098):   vendorId            = 00c4
D/bte_conf( 6098):   vendorIdSource      = 0001
D/bte_conf( 6098):   product             = 13a1
D/bte_conf( 6098):   version             = 1000
D/bte_conf( 6098):   clientExecutableURL = 
D/bte_conf( 6098):   serviceDescription  = 
D/bte_conf( 6098):   documentationURL    = 
D/bte_conf( 6098): bte_load_did_conf no section named DID2.
D/BluetoothPanServiceJni( 6098): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothAdapterState( 6098): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 6098): ScanMode =  20
D/BluetoothAdapterProperties( 6098): State =  11
D/BluetoothAdapterProperties( 6098): mDiscoverableTimeout = 120
V/LGBluetoothServiceAdapter( 6098): [BTUI] state:11, scanmode:20, timeout:120
D/BluetoothAdapterProperties( 6098): Setting state to 12
I/BluetoothAdapterState( 6098): Bluetooth adapter state changed: 11-> 12
W/sh      ( 6324): type=1400 audit(0.0:161): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/sh      ( 6324): type=1400 audit(0.0:162): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/btif_config_util( 6098): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
D/BluetoothManagerService( 1026): Message: 60
I/BluetoothAdapterState( 6098): Entering On State
W/bt-smp  ( 6098): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6098): Plain text(LSB ~ MSB) = 34 fc 4e 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6098): Encrypted text(LSB ~ MSB) = 0c 06 20 35 b2 37 0c df df 12 93 b1 17 fb d6 b2 
W/bt-btm  ( 6098): Stopping oneshot timer
D/LGBluetoothServiceAdapter( 6098): [BTUI] OnState
D/LGBluetoothServiceAdapter( 6098): [BTUI]         global_name: G3-1
D/LGBluetoothServiceAdapter( 6098): [BTUI]         local_name: G3-1
D/BluetoothAdapterService( 6098): [BTUI] autoConnect() : not allowed
D/BluetoothManagerService( 1026): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService( 1026): Broadcasting onBluetoothStateChange(true) to 5 receivers.
D/BluetoothA2dp( 1026): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1865): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1026): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1865): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1865): onBluetoothStateChange: up=true
E/BluetoothManagerService( 1026): Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
D/BluetoothManagerService( 1026): Bluetooth State Change Intent: 11 -> 12
W/bt-smp  ( 6098): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6098): Plain text(LSB ~ MSB) = 57 bd 72 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6098): Encrypted text(LSB ~ MSB) = 87 d3 db 9b 37 eb 7d da 35 9b 55 e8 d4 e1 89 3e 
W/bt-btm  ( 6098): Stopping oneshot timer
D/BluetoothManagerService( 1026): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/LGBluetoothAPIService( 1960): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/LGBluetoothAPIService( 1960): Message: 1
D/LGBluetoothAPIService( 1960): MESSAGE_BOOT_COMPLETED
,D/BluetoothManagerService( 1026): Message: 40
D/BluetoothManagerService( 1026): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
D/LgDataFeature( 6295): LgDataFeature() Constructor: none
D/LgDataFeature( 6295): LgDataFeature() Constructor Done, null
W/bt-smp  ( 6098): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6098): Plain text(LSB ~ MSB) = 5c 63 77 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6098): Encrypted text(LSB ~ MSB) = 07 cf 6f 1c 45 bf 41 db e0 f6 cf a4 f8 f4 83 12 
W/bt-btm  ( 6098): Stopping oneshot timer
I/[SystemUI]BluetoothHandler( 1465): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,I/LGBluetoothAPIService( 1960): [BTUI] LGBluetoothAPIService Binding Success
I/BluetoothMapService( 6098): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 6098): STATE_ON
,W/bt-smp  ( 6098): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6098): Plain text(LSB ~ MSB) = 07 a2 5b 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6098): Encrypted text(LSB ~ MSB) = 5c 42 58 a6 78 7d c9 64 d9 96 e0 2d 0a d5 ba be 
W/bt-btm  ( 6098): Stopping oneshot timer
V/SoundPool( 6295): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 6295): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 6295): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 6295): doLoad: loading sample sampleID=1
,D/LGBluetoothDeviceModeControllManager( 6098): [BTUI] checkDeviceModeAndSet, sinkMode : false
I/QRemote ( 6295): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
W/ContextImpl( 6136): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
V/SoundPool( 6295): Start decode
V/MediaPlayer[Native]( 6295): decode(31, 10857164, 17813)
D/UEI.SmartControl( 5866): QS Service created
I/qcom-bt-wlan-coex( 6337): /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
D/LGBluetoothAPIServer( 6098): [BTUI] onCreate()
,D/LGBluetoothAPIServer( 6098): [BTUI] onBind()
D/LGBluetoothAPIService( 1960): [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
D/LGBluetoothAPIService( 1960): Message: 100
V/MediaPlayerService(  331): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  331): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  331): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  331): [FindUsePlayer] type = [application/ogg]
D/LGBluetoothAPIService( 1960): MESSAGE_BLUETOOTH_SERVICE_CONNECTED
W/BrunchPlayerTypeImpl(  331): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  331): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  331): player type = 3
V/AwesomePlayer(  331): AwesomePlayer create()
V/AwesomePlayer(  331): reset_l() 
V/AwesomePlayer(  331): cancelPlayerEvents
V/AwesomePlayer(  331): setAudioSink() 
V/AwesomePlayer(  331): reset_l() 
V/AudioCache(  331): notify(0xb54749c0, 8, 0, 0)
V/AudioCache(  331): ignored
V/AwesomePlayer(  331): cancelPlayerEvents
D/Utils   (  331): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  331): setDataSource_l dataSource
,V/LGParserOSAL(  331): SniffLGParser start
V/LGParserOSAL(  331): MainType:5, SubType=0
V/LGParserOSAL(  331): #### check Mime : application/ogg
V/LGParserOSAL(  331): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  331): Use LGExtractor :application/ogg 
D/QRemote ( 6295): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
I/UEI.SmartControl( 5866): Service initServices...
D/UEI.SmartControl( 5866): QS start get config
V/BluetoothMapService( 6098): Handler(): got msg=1
D/BluetoothMapMasInstance( 6098): Map Service startRfcommSocketListener
D/BluetoothMapMasInstance( 6098): MAS initSocket()
D/BluetoothMapMasInstance( 6098):   masId = 00
D/BluetoothMapMasInstance( 6098):   msgTypes = 0e
D/BluetoothMapMasInstance( 6098):   masName = SMS/MMS
D/BluetoothMapMasInstance( 6098):   SDP string = 000eSMS/MMS
D/BluetoothManagerService( 1026): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6098): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 6098): [BTUI] createSocketChannel FD=73 mFd=0
V/BluetoothMapMasInstance( 6098): Succeed to create listening socket 
D/BluetoothMapMasInstance( 6098): Accepting socket connection...
D/BluetoothAdapterService( 6098): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37432350
V/BluetoothPbapService( 6098): Pbap Service onCreate
V/BluetoothPbapService( 6098): Starting PBAP service
D/LGBluetoothPbapAdapter( 6098): [BTUI] getInstance : create
V/BluetoothPbapService( 6098): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 6098): state: 12
E/QRemote ( 6295): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
V/BluetoothPbapReceiver( 6098): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 6098): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6098): ***********state = 12
D/QRemote ( 6295): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
V/BluetoothPbapService( 6098): Handler(): got msg=1
V/BluetoothPbapService( 6098): Pbap Service startRfcommSocketListener
V/BluetoothPbapService( 6098): Pbap Service initSocket
,D/BluetoothManagerService( 1026): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6098): getBluetoothService() called with no BluetoothManagerCallback
D/LocalBluetoothProfileManager( 6136): Adding local A2DP profile
D/BluetoothManagerService( 1026): Message: 30
D/LGBluetoothServiceAdapter( 6098): [BTUI] createSocketChannel FD=75 mFd=73
V/BluetoothPbapService( 6098): Succeed to create listening socket 
V/BluetoothPbapService( 6098): Accepting socket connection...
D/LocalBluetoothProfileManager( 6136): Adding local HEADSET profile
,D/BluetoothManagerService( 1026): Message: 30
D/BluetoothManagerService( 1026): Message: 30
V/LGMDMManager( 6295): Create singleton instance
,D/BluetoothManagerService( 1026): Message: 30
D/LocalBluetoothProfileManager( 6136): Adding local MAP profile
D/BluetoothMap( 6136): Create BluetoothMap proxy object
D/BluetoothManagerService( 1026): Message: 30
D/BluetoothManagerService( 1026): Message: 30
V/BluetoothPbapService( 6098): Pbap Service onBind
D/LocalBluetoothProfileManager( 6136): LocalBluetoothProfileManager construction complete
V/LGParserOSAL(  331): supported mime: application/ogg
V/AwesomePlayer(  331): setDataSource_l() extractor countTracks=1
D/LGBluetoothUserBindClient( 6136): [BTUI] initUserBindClient
V/AwesomePlayer(  331): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  331): mBitrate = -1 bits/sec
V/AwesomePlayer(  331): AudioTrack Setting
V/AwesomePlayer(  331): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  331): setAudioSource() 
V/MediaPlayerService(  331): prepare
V/AwesomePlayer(  331): prepareAsync_l() 
V/MediaPlayerService(  331): wait for prepare
V/AwesomePlayer(  331): onPrepareAsyncEvent() 
V/AwesomePlayer(  331): initAudioDecoder() 
W/Utils   (  331): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  331): isOffloadSupported()
V/AudioPolicyManager(  331): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  331): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  331): isAudioPlaybackHookOn() false
V/AwesomePlayer(  331): getUseOffload() = 0 
V/OMXCodec(  331): OMXCodec::Create
V/OMXCodec(  331): findMatchingCodecs()
V/OMXCodec(  331): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  331): matchingCodecs.size()=1
V/OMXCodec(  331): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
D/OMXCodec(  331): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  331): LG Codec Adapter start
V/OMXCodec(  331): OMXCodec Createtor
V/OMXCodec(  331): setComponentRole
V/OMXCodec(  331): configureCodec protected=0
V/LGCodecAdapter(  331): called getLGCodecSpecificData
V/LGCodecOSAL(  331): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  331): Called LGconfigureCodecMETA
V/LGCodecOSAL(  331): Called LGconfigureCodecMSG
V/LGCodecOSAL(  331): Not support LGCodec
V/OMXCodec(  331): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  331): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  331): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  331): Could not offload audio decode, try pcm offload
W/Utils   (  331): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  331): isOffloadSupported()
V/AudioPolicyManager(  331): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  331): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  331): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  331): init()
V/OMXCodec(  331): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  331): allocateBuffers
V/OMXCodec(  331): allocateBuffersOnPort portIndex=0
,W/ContextImpl( 6136): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
V/OMXCodec(  331): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  331): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d30 on input port
V/OMXCodec(  331): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d80 on input port
V/OMXCodec(  331): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7dd0 on input port
V/OMXCodec(  331): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e20 on input port
V/OMXCodec(  331): allocateBuffersOnPort portIndex=1
V/OMXCodec(  331): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  331): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ec0 on output port
V/OMXCodec(  331): [OMX.google.vorbis.decoder] allocated buffer 0xb57c3240 on output port
V/OMXCodec(  331): [OMX.google.vorbis.decoder] allocated buffer 0xb57c3290 on output port
V/OMXCodec(  331): [OMX.google.vorbis.decoder] allocated buffer 0xb57c33d0 on output port
V/OMXCodec(  331): init() mAsyncCompletion wait!!! 
V/OMXCodec(  331): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  331): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  331): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  331): init() mAsyncCompletion wait!!! 
V/OMXCodec(  331): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  331): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  331): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  331): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  331): finishAsyncPrepare_l() 
V/AudioCache(  331): notify(0xb54749c0, 5, 0, 0)
V/AudioCache(  331): ignored
V/AudioCache(  331): notify(0xb54749c0, 1, 0, 0)
V/AudioCache(  331): prepared
D/BluetoothAdapterProperties( 6098): Discoverable Timeout:120
D/LGBluetoothDeviceModeControllManager( 6098): adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
D/BluetoothAdapterProperties( 6098): Scan Mode:21
D/LGBluetoothDeviceModeControllManager( 6098): getDeviceMode  deviceMode 0
V/AudioCache(  331): wait - success
V/MediaPlayerService(  331): start
V/AwesomePlayer(  331): play_l() 
V/AwesomePlayer(  331): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  331): createAudioPlayer_l
V/AwesomePlayer(  331): seekAudioIfNecessary_l() 
V/AwesomePlayer(  331): startAudioPlayer_l() 
D/AudioPlayer(  331): start of Playback, useOffload 0
V/OMXCodec(  331): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  331): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
D/DockEventReceiver( 6136): finishStartingService: stopping service
V/OMXCodec(  331): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  331): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  331): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  331): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  331): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  331): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  331): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885888
V/OMXCodec(  331): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  331): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044815424
V/OMXCodec(  331): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  331): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044815504
V/OMXCodec(  331): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec( , 331): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044815824
V/OMXCodec(  331): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  331): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  331): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  331): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  331): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  331): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  331): allocateBuffersOnPort portIndex=1
V/OMXCodec(  331): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  331): [OMX.google.vorbis.decoder] allocated buffer 0xb57c3290 on output port
V/OMXCodec(  331): [OMX.google.vorbis.decoder] allocated buffer 0xb57c3240 on output port
V/OMXCodec(  331): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ec0 on output port
V/OMXCodec(  331): [OMX.google.vorbis.decoder] allocated buffer 0xb57c36a0 on output port
V/OMXCodec(  331): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  331): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  331): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  331): notify(0xb54749c0, 6, 0, 0)
V/AudioCache(  331): ignored
,V/MediaPlayerService(  331): wait for playback complete
V/AudioCache(  331): write(0xb1741000, 4096)
V/AudioCache(  331): memcpy(0xab602000, 0xb1741000, 4096)
V/AudioCache(  331): write(0xb1741000, 4096)
V/AudioCache(  331): memcpy(0xab603000, 0xb1741000, 4096)
V/AudioCache(  331): write(0xb1741000, 4096)
V/AudioCache(  331): memcpy(0xab604000, 0xb1741000, 4096)
V/AudioCache(  331): write(0xb1741000, 4096)
V/AudioCache(  331): memcpy(0xab605000, 0xb1741000, 4096)
V/AudioCache(  331): write(0xb1741000, 4096)
V/AudioCache(  331): memcpy(0xab606000, 0xb1741000, 4096)
V/AudioCache(  331): write(0xb1741000, 4096)
V/AudioCache(  331): memcpy(0xab607000, 0xb1741000, 4096)
V/AudioCache(  331): write(0xb1741000, 4096)
V/AudioCache(  331): memcpy(0xab608000, 0xb1741000, 4096)
V/AudioCache(  331): write(0xb1741000, 4096)
V/AudioCache(  331): memcpy(0xab609000, 0xb1741000, 4096)
V/AudioCache(  331): write(0xb1741000, 4096)
V/AudioCache(  331): memcpy(0xab60a000, 0xb1741000, 4096)
V/AudioCache(  331): write(0xb1741000, 4096)
V/AudioCache(  331): memcpy(0xab60b000, 0xb1741000, 4096)
V/AudioCache(  331): write(0xb1741000, 4096)
V/AudioCache(  331): memcpy(0xab60c000, 0xb1741000, 4096)
D/BluetoothA2dp( 6136): Proxy object connected
V/AudioCache(  331): write(0xb1741000, 4096)
V/AudioCache(  331): memcpy(0xab60d000, 0xb1741000, 4096)
D/A2dpProfile( 6136): Bluetooth service connected
V/AudioCache(  331): write(0xb1741000, 4096)
V/AudioCache(  331): memcpy(0xab60e000, 0xb1741000, 4096)
V/AudioCache(  331): write(0xb1741000, 4096)
V/AudioCache(  331): memcpy(0xab60f000, 0xb1741000, 4096)
V/AudioCache(  331): write(0xb1741000, 4096)
V/AudioCache(  331): memcpy(0xab610000, 0xb1741000, 4096)
V/AudioCache(  331): write(0xb1741000, 4096)
V/AudioCache(  331): memcpy(0xab611000, 0xb1741000, 4096)
V/AudioCache(  331): write(0xb1741000, 4096)
V/AudioCache(  331): memcpy(0xab612000, 0xb1741000, 4096)
V/AudioCache(  331): write(0xb1741000, 4096)
V/AudioCache(  331): memcpy(0xab613000, 0xb1741000, 4096)
V/AudioCache(  331): write(0xb1741000, 4096)
V/AudioCache(  331): memcpy(0xab614000, 0xb1741000, 4096)
D/BluetoothHeadset( 6136): Proxy object connected
V/AudioCache(  331): write(0xb1741000, 4096)
V/AudioCache(  331): memcpy(0xab615000, 0xb1741000, 4096)
V/AudioCache(  331): write(0xb1741000, 4096)
V/AudioCache(  331): memcpy(0xab616000, 0xb1741000, 4096)
D/HeadsetProfile( 6136): Bluetooth service connected
V/AudioCache(  331): write(0xb1741000, 4096)
V/AudioCache(  331): memcpy(0xab617000, 0xb1741000, 4096)
V/AudioCache(  331): write(0xb1741000, 4096)
V/AudioCache(  331): memcpy(0xab618000, 0xb1741000, 4096)
D/BluetoothInputDevice( 6136): Proxy object connected
D/HidProfile( 6136): Bluetooth service connected
V/AudioCache(  331): write(0xb1741000, 4096)
V/AudioCache(  331): memcpy(0xab619000, 0xb1741000, 4096)
V/AudioCache(  331): write(0xb1741000, 4096)
V/AudioCache(  331): memcpy(0xab61a000, 0xb1741000, 4096)
D/BluetoothPan( 6136): BluetoothPAN Proxy object connected
V/AudioCache(  331): write(0xb1741000, 4096)
V/AudioCache(  331): memcpy(0xab61b000, 0xb1741000, 4096)
D/PanProfile( 6136): Bluetooth service connected
V/AudioCache(  331): write(0xb1741000, 4096)
V/AudioCache(  331): memcpy(0xab61c000, 0xb1741000, 4096)
V/AudioCache(  331): write(0xb1741000, 4096)
V/AudioCache(  331): memcpy(0xab61d000, 0xb1741000, 4096)
D/BluetoothMap( 6136): Proxy object connected
V/AudioCache(  331): write(0xb1741000, 4096)
V/AudioCache(  331): memcpy(0xab61e000, 0xb1741000, 4096)
D/MapProfile( 6136): Bluetooth service connected
D/BluetoothMap( 6136): getConnectedDevices()
V/AudioCache(  331): write(0xb1741000, 4096)
V/AudioCache(  331): memcpy(0xab61f000, 0xb1741000, 4096)
,V/AudioCache(  331): write(0xb1741000, 4096)
V/AudioCache(  331): memcpy(0xab620000, 0xb1741000, 4096)
V/AudioCache(  331): write(0xb1741000, 4096)
V/AudioCache(  331): memcpy(0xab621000, 0xb1741000, 4096)
V/AudioCache(  331): write(0xb1741000, 4096)
V/AudioCache(  331): memcpy(0xab622000, 0xb1741000, 4096)
V/AudioCache(  331): write(0xb1741000, 4096)
V/AudioCache(  331): memcpy(0xab623000, 0xb1741000, 4096)
V/AudioCache(  331): write(0xb1741000, 4096)
V/AudioCache(  331): memcpy(0xab624000, 0xb1741000, 4096)
V/AudioCache(  331): write(0xb1741000, 4096)
V/AudioCache(  331): memcpy(0xab625000, 0xb1741000, 4096)
V/AudioCache(  331): write(0xb1741000, 4096)
V/AudioCache(  331): memcpy(0xab626000, 0xb1741000, 4096)
V/AudioCache(  331): write(0xb1741000, 4096)
V/AudioCache(  331): memcpy(0xab627000, 0xb1741000, 4096)
V/AudioCache(  331): write(0xb1741000, 4096)
V/AudioCache(  331): memcpy(0xab628000, 0xb1741000, 4096)
V/AudioCache(  331): write(0xb1741000, 4096)
V/AudioCache(  331): memcpy(0xab629000, 0xb1741000, 4096)
V/AudioCache(  331): write(0xb1741000, 4096)
V/AudioCache(  331): memcpy(0xab62a000, 0xb1741000, 4096)
V/AudioCache(  331): write(0xb1741000, 4096)
V/AudioCache(  331): memcpy(0xab62b000, 0xb1741000, 4096)
V/AudioCache(  331): write(0xb1741000, 4096)
V/AudioCache(  331): memcpy(0xab62c000, 0xb1741000, 4096)
V/AudioCache(  331): write(0xb1741000, 4096)
V/AudioCache(  331): memcpy(0xab62d000, 0xb1741000, 4096)
V/AudioCache(  331): write(0xb1741000, 4096)
V/AudioCache(  331): memcpy(0xab62e000, 0xb1741000, 4096)
V/AudioCache(  331): write(0xb1741000, 4096)
V/AudioCache(  331): memcpy(0xab62f000, 0xb1741000, 4096)
V/AudioCache(  331): write(0xb1741000, 4096)
V/AudioCache(  331): memcpy(0xab630000, 0xb1741000, 4096)
V/OMXCodec(  331): [OMX.google.vorbis.decoder] No more output data.
V/AudioCache(  331): write(0xb1741000, 4096)
V/AudioCache(  331): memcpy(0xab631000, 0xb1741000, 4096)
V/OMXCodec(  331): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AudioCache(  331): write(0xb1741000, 4096)
V/AudioCache(  331): memcpy(0xab632000, 0xb1741000, 4096)
V/OMXCodec(  331): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AudioCache(  331): write(0xb1741000, 4096)
V/AudioCache(  331): memcpy(0xab633000, 0xb1741000, 4096)
V/OMXCodec(  331): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/OMXCodec(  331): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  331): postAudioEOS() 
V/AudioCache(  331): write(0xb1741000, 280)
V/AudioCache(  331): memcpy(0xab634000, 0xb1741000, 280)
V/AwesomePlayer(  331): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  331): onStreamDone
V/AwesomePlayer(  331): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  331): notify(0xb54749c0, 2, 0, 0)
V/AudioCache(  331): playback complete
V/AwesomePlayer(  331): pause_l() 
V/AudioCache(  331): wait - success
V/AudioCache(  331): notify(0xb54749c0, 7, 0, 0)
V/AudioCache(  331): ignored
V/MediaPlayerService(  331): return size 205080, sampleRate=48000, channelCount = 2, format = 1
V/AwesomePlayer(  331): cancelPlayerEvents
D/AudioPlayer(  331): Pause Playback at 1068125
,V/AwesomePlayer(  331): reset_l() 
V/AudioCache(  331): notify(0xb54749c0, 8, 0, 0)
V/AudioCache(  331): ignored
V/AwesomePlayer(  331): cancelPlayerEvents
D/AudioPlayer(  331): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  331): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  331): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  331): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  331): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  331): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  331): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  331): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  331): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7e20 on port 0
V/OMXCodec(  331): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  331): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7dd0 on port 0
V/OMXCodec(  331): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  331): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7d80 on port 0
V/OMXCodec(  331): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  331): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7d30 on port 0
V/OMXCodec(  331): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  331): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  331): [OMX.google.vorbis.decoder] freeing buffer 0xb57c36a0 on port 1
V/OMXCodec(  331): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  331): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ec0 on port 1
V/OMXCodec(  331): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  331): [OMX.google.vorbis.decoder] freeing buffer 0xb57c3240 on port 1
V/OMXCodec(  331): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  331): [OMX.google.vorbis.decoder] freeing buffer 0xb57c3290 on port 1
V/OMXCodec(  331): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  331): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  331): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  331): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  331): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  331): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  331): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  331): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  331): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  331): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
V/OMXCodec(  331): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  331): AudioPlayer releasing audio source
D/AudioPlayer(  331): AudioPlayer done releasing audio source
V/AwesomePlayer(  331): reset_l() 
V/AwesomePlayer(  331): cancelPlayerEvents
V/AwesomePlayer(  331): ~AwesomePlayer call
V/AwesomePlayer(  331): reset_l() 
V/AwesomePlayer(  331): cancelPlayerEvents
V/SoundPool( 6295): close(31)
V/SoundPool( 6295): pointer = 0x9ffd5000, size = 205080, sampleRate = 48000, numChannels = 2
V/BluetoothMapService( 6098): getConnectedDevices()
D/BluetoothPbap( 6136): Proxy object connected
D/PbapServerProfile( 6136): Bluetooth service connected
D/LGBluetoothUserBindClient( 6136): [BTUI] onServiceConnected
D/QRemote ( 6295): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/BluetoothPermissionRequest( 6136): onReceive
,D/QRemote ( 6295): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
D/LGBluetoothFeatureConfig( 6136): isPrivacyLogsEnabled : true
D/LGBluetoothUtils( 6136): [BTUI] FileNotFound: readProperty
D/LGBluetoothResetSettingReceiver( 6136): return without doing reset settings.
D/QRemote ( 6295): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:9987
V/BluetoothOppReceiver( 6098): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
I/LGBluetoothOppAdapter( 6098): [BTUI] startOppService()
V/BluetoothOppManager( 6098): restoreApplicationData! falsefalsenullnull
,D/LGBluetoothFeatureConfig( 6098): isPrivacyLogsEnabled : true
,V/BtOppService( 6098): onCreate
V/BluetoothOppNotification( 6098): send message
,V/BtOppService( 6098): Starting RfcommListener
D/BluetoothOppPreference( 6098): Dumping Names:  
D/BluetoothOppPreference( 6098): {}
D/BluetoothOppPreference( 6098): Dumping Channels:  
D/BluetoothOppPreference( 6098): {}
V/BtOppService( 6098): onStartCommand
V/BluetoothFtpReceiver( 6098): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpReceiver( 6098): BluetoothFtpReceiver Start Service
V/BtOppService( 6098): pendingUpdate is true keepUpdateThread is false sListenStarted is true
V/BtOppService( 6098): Deleted complete outbound shares, number =  0
V/BluetoothOppNotification( 6098): new notify threadi!
V/BtOppService( 6098): Deleted complete inbound failed shares, number = 0
,V/BluetoothOppNotification( 6098): send delay message
V/BluetoothOppProvider( 6098): starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6098): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
V/BtOppService( 6098): start RfcommListener
V/BluetoothOppProvider( 6098): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
V/BtOppService( 6098): RfcommListener started
V/BtOppRfcommListener( 6098): Starting RFCOMM listener....
V/BluetoothOppProvider( 6098): created cursor android.database.sqlite.SQLiteCursor@27a1e46a on behalf of 
D/BluetoothManagerService( 1026): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapterService( 6098): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37432350
,V/BluetoothFtpService( 6098): Ftp Service onCreate
I/BluetoothFtpService( 6098): Ftp Service onCreate
V/BtOppService( 6098): ContentObserver received notification
V/BluetoothFtpService( 6098): Ftp Service onStartCommand
V/BluetoothFtpService( 6098): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpService( 6098): Starting Listening on sockets
V/BluetoothSapReceiver( 6098): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 6098): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 6098): SapReceiver onReceive 
V/BluetoothSapReceiver( 6098): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothOppProvider( 6098): created cursor android.database.sqlite.SQLiteCursor@17be89f8 on behalf of 
V/BluetoothSapReceiver( 6098):  Bluetooth Adapter state = 12
V/BluetoothSapReceiver( 6098): Calling SAP service start service with action = null
V/BtOppService( 6098): ContentObserver received notification
V/BluetoothFtpService( 6098): Handler(): got msg=1
V/BluetoothOppProvider( 6098): created cursor android.database.sqlite.SQLiteCursor@17fa7ed1 on behalf of 
V/BluetoothFtpService( 6098): Ftp Service startRfcommSocketListener
V/BluetoothFtpService( 6098): Ftp Service initSocket
W/BluetoothAdapter( 6098): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothManagerService( 1026): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
V/BluetoothOppNotification( 6098): mUpdateCompleteNotification = true
W/BluetoothAdapter( 6098): getBluetoothService() called with no BluetoothManagerCallback
V/BtOppService( 6098): pendingUpdate is true keepUpdateThread is false sListenStarted is true
V/BluetoothOppProvider( 6098): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6098): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 6098): created cursor android.database.sqlite.SQLiteCursor@2ef1dd36 on behalf of 
D/AuthorizationBluetoothService( 2135): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
V/BluetoothOppNotification( 6098): update too frequent, put in queue
D/LGBluetoothServiceAdapter( 6098): [BTUI] createSocketChannel FD=79 mFd=75
V/BluetoothFtpService( 6098): Succeed to create listening socket on channel 20
V/BluetoothFtpService:RfcommSocketAcceptThread( 6098): Run Accept thread
D/LGBluetoothServiceAdapter( 6098): [BTUI] createSocketChannel FD=81 mFd=79
V/BtOppService( 6098): pendingUpdate is false keepUpdateThread is false sListenStarted is true
V/BluetoothOppProvider( 6098): created cursor android.database.sqlite.SQLiteCursor@3c25d437 on behalf of 
V/BluetoothOppNotification( 6098): outbound: succ-0  fail-0
V/BluetoothOppNotification( 6098): outbound notification was removed.
V/BluetoothOppProvider( 6098): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 6098): created cursor android.database.sqlite.SQLiteCursor@3c4e4da4 on behalf of 
V/BluetoothOppNotification( 6098): inbound: succ-0  fail-0
V/BluetoothOppNotification( 6098): inbound notification was removed.
V/BluetoothOppProvider( 6098): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6098): created cursor android.database.sqlite.SQLiteCursor@39d7370d on behalf of 
D/BluetoothAdapterService( 6098): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@,37432350
V/BluetoothSapService( 6098): Sap Service onCreate
V/BtOppRfcommListener( 6098): Started RFCOMM listener....
I/BtOppRfcommListener( 6098): Accept thread started.
V/BtOppRfcommListener( 6098): Accepting connection...
V/BluetoothSapService( 6098): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 6098): state: 12
V/BluetoothSapService( 6098): Starting SAP server process
,V/BluetoothSapService( 6098): SAP Service startRfcommListenerThread
V/BluetoothSapService( 6098): Sap Service initRfcommSocket
D/BluetoothManagerService( 1026): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6098): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 6098): [BTUI] createSocketChannel FD=82 mFd=81
V/BluetoothSapService( 6098): Succeed to create listening socket 
V/BluetoothSapService( 6098): Accepting socket connection...
W/sapd    ( 6357): type=1400 audit(0.0:163): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/sapd    ( 6357): type=1400 audit(0.0:164): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
V/BT_SAP  ( 6357): Event pipe created
V/BT_SAP  ( 6357): create_server_socket qcom.sap.server
V/BT_SAP  ( 6357): created socket fd 6
I/UEI.SmartControl( 5866): Supports setup maps: true
,D/UEI.SmartControl( 5866): QS start statue = true Error code = 0
,I/UEI.SmartControl( 5866): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 5866): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 5866): ### init IR Blaster...
D/serial_port( 5866): Configuring serial port
E/UEI.SmartControl( 5866): UEIBLaster setting for 616
I/UEI.SmartControl( 5866): Setting serial record hearder size = 2
I/UEI.SmartControl( 5866): configuring settings for MAXQ616
I/UEI.SmartControl( 5866): Get version...
D/UEI.SmartControl( 5866): serial port data available: 21
,D/UEI.SmartControl( 5866): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 5866): IR Blaster version: 256702256704300002
,I/UEI.SmartControl( 5866): QS saving settings...
D/UEI.SmartControl( 5866): IR Blaster version: 25672567
D/UEI.SmartControl( 5866): serial port data available: 4
,I/UEI.SmartControl( 5866): Device manager: loading config....
,D/UEI.SmartControl( 5866): ----------- loading internal config...
W/ContextImpl( 5866): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
E/UEI.SmartControl( 5866): Services init done
D/UEI.SmartControl( 5866): QS Service init finished
D/UEI.SmartControl( 5866): QS Service version name: 2.1.91
D/UEI.SmartControl( 5866): QS Service version code: 201091
D/UEI.SmartControl( 5866): Service requested: Control
E/UEI.SmartControl( 5866): Loading SETTINGS...
D/UEI.SmartControl( 5866): Request IControl service: devices are loaded...
I/QRemote ( 6295): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
D/UEI.SmartControl( 5866): Internal service binding...
,I/UEI.SmartControl( 5866): ------ IControl API: 11
D/UEI.SmartControl( 5866): File observer start...
E/UEI.SmartControl( 5866): IR Port is disabled: false
D/UEI.SmartControl( 5866): Starting file observer...
I/UEI.SmartControl( 5866): Registering callback...
D/UEI.SmartControl( 5866): -- Open brand translation xml: brands_translations_ko
I/UEI.SmartControl( 5866): ------ IControl API: 19
I/UEI.SmartControl( 5866): Registering Services Ready callback...
E/WifiStateMachine( 1026):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1026):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1026):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1026):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 1026):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
I/UEI.SmartControl( 5866): Notify AllClients services are ready: 0
E/WifiStateMachine( 1026):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,D/ConnectivityService( 1026): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
D/UEI.SmartControl( 5866): -----service ready thread exits
I/QRemote ( 6295): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 6295): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 6295): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 6295): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 6295): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 5866): ------ IControl API: 8
D/QRemote ( 6295): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 6295): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 6295): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 6295): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
,D/QRemote ( 6295): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
,D/QRemote ( 6295): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 6295): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
V/QRemote ( 6295): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6295): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 6295): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6295): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 6295): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6295): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 6295): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
,D/QRemote ( 6295): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1454701199348]
,D/QRemote ( 6295): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
I/ActivityManager( 1026): Killing 5582:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
D/QRemote ( 6295): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,I/dhcpcd  ( 6285): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
,W/libprocessgroup( 1026): failed to open /acct/uid_10080/pid_5582/cgroup.procs: No such file or directory
,V/QRemote ( 6295): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
E/QRemote ( 6295): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6295): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 6295): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 6295): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 6295): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 6295): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
I/dhcpcd  ( 6285): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 6285): wlan0: adding IP address 192.168.1.141/24
,D/dhcpcd  ( 6285): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 6285): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 6285): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 6285): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 6285): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 6285): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
E/WifiStateMachine( 1026):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1026):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
D/QRemote ( 6295): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
E/WifiStateMachine( 1026):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1026):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1026):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1026):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1026): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
D/DhcpStateMachine( 1026): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper( 1026): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1026): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1026): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1026): Add DhcpResults: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
V/DhcpStateMachine( 1026): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1026): bShouldSendDhcpAction Result: true
D/DhcpStateMachine( 1026): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1026): RunningState
E/WifiStateMachine( 1026):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine( 1026):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/LGWifiP2pService( 1026): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1026): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1026): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 6154): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1026): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1026): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 6154): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1026): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1026): doBoolean: SET ps 1
D/WifiNative-wlan0( 1026): SET ps 1: returned true
D/ConnectivityService( 1026): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
E/WifiStateMachine( 1026):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
,E/WifiStateMachine( 1026):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1026): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1026): ignoring duplicate network state non-change
,W/Settings( 1026): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1026): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1026): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/StatusBar.NetworkController( 1465): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1465): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService( 1026): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService( 1026): Adding iface wlan0 to network 100
,D/PostponalbeReceiver( 5205): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1026): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
I/StatusBar.NetworkController( 1465): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/Settings( 1026): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1026): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1026): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/WifiHS20( 1026): [PASSPOINT] passpointNotification: hs20AP list is checked
I/StatusBar.NetworkController( 1465): mWifiConnected = false, mWifiLevel = 0
V/WfdStateTracker( 1960): handleWifiStateChangedEvent: 1
W/Settings( 1026): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1026): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1026): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20( 1026): [PASSPOINT] passpointNotification: hs20AP list is checked
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
,W/Settings( 1026): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1026): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1026): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/StatusBar.NetworkController( 1465): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1465): mWifiConnected = true, mWifiLevel = 2
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
,E/ConnectivityService( 1026): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1026): Adding Route [fe80::/64 -> :: wlan0] to network 100
I/StatusBar.NetworkController( 1465): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1465): mWifiConnected = true, mWifiLevel = 2
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1026): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
D/ConnectivityService( 1026): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
D/ConnectivityService( 1026): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1026): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 100
D/ConnectivityService( 1026): Setting Dns servers for network 100 to [/192.168.1.1]
D/Nat464Xlat( 1026): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1026): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1026): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1026): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1026): rematching NetworkAgentInfo [WIFI () - 100]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1026): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1026): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1026):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1026): Checking http://clients3.google.com/generate_204 on "NG700"
,D/ConnectivityService( 1026):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1026):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1026):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1026):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1026): currentScore = 0, newScore = 20
D/ConnectivityService( 1026):    accepting network in place of null
D/ConnectivityService( 1026): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1026): Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
D/TelephonyNetworkFactory-1( 1865): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1865):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/WIFI    ( 1026): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1026):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/libc-netbsd(  327): res_queryN name = clients3.google.com, class = 1, type = 28
E/ConnectivityService( 1026): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1026): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1026): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1026): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1026): [e] list.add(nai) empty : false size: 1
D/ConnectivityService( 1026): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/LocSvc_java( 1026): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1026): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1026): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1026): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java( 1026): Sending msg: 5 arg1:0 arg2:1
D/libc-netbsd(  327): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  327): res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
D/libc-netbsd(  327): res_queryN name = 2.android.pool.ntp.org., class = 1, type = 1
D/DSQN    ( 1026): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/libc-netbsd(  327): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  327): res_queryN name = europe.pool.ntp.org, class = 1, type = 1
D/libc-netbsd(  327): res_queryN name = europe.pool.ntp.org., class = 1, type = 1
D/LocSvc_java( 1026): requestTime failed
D/LocSvc_java( 1026): Sending msg: 10 arg1:0 arg2:1
D/DSQN    ( 1026): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/ConnectivityService( 1026): validation of new default Network = false
D/ConnectivityService( 1026): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1026): enableDataServiceNotify 
D/DSQN    ( 1026): start dsqn bin
,V/WiFiOffLoadBroadcast( 6136): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
V/NetworkPolicy( 1026): [LG_RESTRICTED] checkMobilePolicy_type()
D/ConnectivityService( 1026): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1026):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1026):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1026): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
W/dsqn    ( 6403): type=1400 audit(0.0:165): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 6403): type=1400 audit(0.0:166): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/ConnectivityManager.CallbackHandler( 1465): CM callback handler got msg 524290
,D/WiFiOffLoadBroadcast( 6136): MCCMNC not supported: null
,E/DSQN    ( 6403): DSQN ssw
,D/TelephonyIcons( 1465): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
D/QRemote ( 6295): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6295): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/libc-netbsd(  327): res_queryN name = clients3.google.com, class = 1, type = 1
I/QRemote ( 6295): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 5205): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 6136): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6136): MCCMNC not supported: null
D/QRemote ( 6295): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6295): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6295): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 5205): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6197): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6197): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6136): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/libc-netbsd(  327): res_queryN name = clients3.google.com succeed
,D/WiFiOffLoadBroadcast( 6136): MCCMNC not supported: null
D/QRemote ( 6295): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6295): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6295): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6295): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6295): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,D/PostponalbeReceiver( 5205): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,D/LGDataListener(  327): argv[0]=dsqncommand
D/LGDataListener(  327): argv[1]=wlan0
D/LGDataListener(  327): argv[2]=1
D/LGDataListener(  327): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1026): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1026): start to monitor internet connection
,I/PCSuite ( 6197): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6197): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6136): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6136): MCCMNC not supported: null
D/QRemote ( 6295): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6295): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6295): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6295): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6295): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1026): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 05 Feb 2016 19:40:00 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454701200039], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454701200014]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1026): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1026): Validated
D/ConnectivityService( 1026): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1026): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1026):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1026):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1026):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1026): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService( 1026): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1026):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1026):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1026): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1026): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1465): CM callback handler got msg 524290
D/WIFI    ( 1026): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1026): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    ( 1026):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1865): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1865):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,D/TelephonyIcons( 1465): null signal icon name: drawable/stat_sys_signal_null
,D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
V/BluetoothOppNotification( 6098): new notify threadi!
,V/BluetoothOppNotification( 6098): send delay message
V/BluetoothOppProvider( 6098): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6098): created cursor android.database.sqlite.SQLiteCursor@124d3709 on behalf of 
,V/BluetoothOppNotification( 6098): mUpdateCompleteNotification = true
V/BluetoothOppProvider( 6098): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 6098): created cursor android.database.sqlite.SQLiteCursor@2b9b5d0e on behalf of ,
V/BluetoothOppNotification( 6098): outbound: succ-0  fail-0
V/BluetoothOppNotification( 6098): outbound notification was removed.
,V/BluetoothOppProvider( 6098): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,I/art     ( 1026): Explicit concurrent mark sweep GC freed 78103(3MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 44MB/66MB, paused 2.092ms total 120.305ms
,V/BluetoothOppProvider( 6098): created cursor android.database.sqlite.SQLiteCursor@2e55132f on behalf of 
,V/BluetoothOppNotification( 6098): inbound: succ-0  fail-0
,V/BluetoothOppNotification( 6098): inbound notification was removed.
,V/BluetoothOppProvider( 6098): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6098): created cursor android.database.sqlite.SQLiteCursor@2b6bad3c on behalf of 
E/WifiStateMachine( 1026):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1292712385] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1026):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1292712382] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1026): doString: [SIGNAL_POLL]
,D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
I/jxcore-log( 5997): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 5997): 
,I/jxcore-log( 5997): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 5997): 
,I/jxcore-log( 5997): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 5997): 
I/jxcore-log( 5997): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 5997): 
,I/jxcore-log( 5997): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 5997): 
,I/jxcore-log( 5997): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 5997): 
,I/jxcore-log( 5997): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
I/jxcore-log( 5997): 
,V/WifiInternetCheck( 1026): Single check msg out of sync, ignoring.
,I/jxcore-log( 5997): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 5997): 
,I/jxcore-log( 5997): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 5997): 
,D/ConnectivityService( 1026): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1026): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1026): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/libc-netbsd(  327): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  327): res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
D/Tethering( 1026): MasterInitialState.processMessage what=3
D/PostponalbeReceiver( 5205): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 5205): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,D/libc-netbsd(  327): res_queryN name = 2.android.pool.ntp.org succeed
,I/NetworkMonitor( 5256): type=WIFI subType= reason=null isConnected=true
D/AlarmManagerService( 1026): Setting time of day to sec=1454701203
,W/AlarmManagerService( 1026): Unable to set rtc to 1454701203: Invalid argument
,I/ActivityManager( 1026): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6433 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/SecureClockService( 1960): Intent.ACTION_TIME_CHANGED 
D/LIA_Informant_Tips_DateChangeManager( 2695): onReceive() : ACTION_TIME_CHANGED
W/ActivityManager( 1026): getTasks: caller 10029 is using old GET_TASKS but privileged; allowing
D/PowerManagerServiceEx( 1026): acquireWakeLockInternal: lock=631714865, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1026
I/LIA_Informant_Tips_LogTracer( 2695): [Log Tracer - Schedule Transition] Time Change Event Received : 2016-02-05 20:40:03...... Request
,I/LIA_Informant_Tips_LogTracer( 2695): [Log Tracer - Schedule Transition] UserGuide, DATE_UPDATE : working count : 2, total count : 166, new day : false...... Request
D/LIA_Informant_Tips_DateChangeManager( 2695): DateInfo : SmartTips Total Working Day Count = 166
E/GpsLocationProvider( 1026): No APN found to select.
D/LIA_Informant_Tips_DateChangeManager( 2695): DateInfo : UserGuide Working Duration Count = 2
I/[LGHome]LGDateChangeReceiver( 2082): [LGDateChangeReceiver.java:78:updateCalendarShortcut()]date=5 currentDate=-1 dayofweek=6 currentDayOfWeek=-1
D/LIA_Informant_Tips_DateChangeManager( 2695): DateInfo : Last Date Check Time = 2016-02-05 20:40:03
I/GoogleURLConnFactory( 2135): Using platform SSLCertificateSocketFactory
,I/[LGHome]LGCalendarIcon( 2082): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Fri date= 5
I/[SystemUI]Clock( 1465): onReceive = android.intent.action.TIME_SET
I/LgeClockWidgetControlView( 1465): time changed, timezoneChanged : false
I/CalendarProvider2( 4606): onReceive() android.intent.action.TIME_SET
D/CalendarProvider2( 4606): Scheduling check of next Alarm
D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
,I/[LGHome]LGCalendarIcon( 2082): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Fri date= 5
I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/CloudHub( 2231): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19983
,D/[Concierge]Service( 2588): onStartCommand(). Type : 9
D/[Concierge]Service( 2588): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1026): releaseWakeLockInternal: lock=631714865 [*alarm*], flags=0x0
,I/AppUp4:AppBoxCP( 6433): onCreate
W/AppUp4:DB( 6433):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 6433):  setFingerPrint start
I/AppUp4:DB( 6433):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/ActivityManager( 1026): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=6454 uid=10054 gids={50054, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/AppUp4:DB( 6433):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 6433):  SDK version = 21
I/AppUp4:DB( 6433):  beforefinger == newfinger no write in DB
I/ActivityManager( 1026): Start proc com.android.gallery3d for service com.android.gallery3d/com.lge.gallery.picasa.PicasaService: pid=6471 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
D/AppUp4:AppBoxApplication( 6433): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6433): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6433): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6433): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6433): [onReceive] request level :IDLE....
,I/art     (  352): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 236us total 12.324ms
I/art     (  352): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 197us total 10.384ms
,I/AppUp4:CustModeStarterReceiver( 6433): onReceive
I/art     (  352): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 194us total 10.858ms
,W/ResourcesManager( 6471): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6471): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6471): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 6471): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
D/LgDataFeature( 6433): LgDataFeature() Constructor: none
D/LgDataFeature( 6433): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 6433): Context : android.app.ReceiverRestrictedContext@102f0513
D/AppUp4:CustFacade( 6433): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6433): isPhone : true
D/AppUp4:CustModeStarterReceiver( 6433): begin check event
I/AppUp4:CustModeStarterReceiver( 6433): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6433): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6433): call method handleAsyncCustNotification.
,D/AppUp4:CustModeStarterReceiver( 6433): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6433): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1026): Killing 5824:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,W/libprocessgroup( 1026): failed to open /acct/uid_10061/pid_5824/cgroup.procs: No such file or directory
,D/LGDMClient( 3990): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3990): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 3990): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
I/ActivityManager( 1026): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=6494 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/AppConfig( 6471): Total System Memory = 2995761152
I/ReaderUtils( 6454): PortraitW 1440 LandscapeW 2392 SmallestSize 1340 LargestSize 2392 textZoom 4.4999995 isTablet false Memory 256
W/ContextImpl( 3990): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,D/SystemHelper( 6471): region [EU], country [EU], operator [OPEN], sub-operator []
I/VacuumService( 2135): Vacuum at: now=1454701203872 tag=VacuumService
V/DownloadManager( 3297): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3297): DownloadService onCreate
I/DownloadManager( 3297): in removeSpuriousFiles
,V/DownloadManager( 3297): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3297): created cursor android.database.sqlite.SQLiteCursor@36c87029 on behalf of 3297
I/DownloadManager( 3297): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3297): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3297): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3297): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3297): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3297): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3297): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3297): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3297): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3297): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3297): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/DownloadManager( 3297): in trimDatabase
V/DownloadManager( 3297): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3297): created cursor android.database.sqlite.SQLiteCursor@e3a6fae on behalf of 3297
D/LGDMClient( 3990): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/LGDMClient( 3990): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3990): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/LGDMClient( 3990): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/ActivityManager( 1026): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6522 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
W/ContextImpl( 3990): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
,I/ActivityManager( 1026): Killing 5601:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,V/DownloadManager( 3297): DownloadService onStartCommand
,V/DownloadManager( 3297): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3297): created cursor android.database.sqlite.SQLiteCursor@284ee5e5 on behalf of 3297
V/DownloadManager( 3297): processing inserted download 1
V/DownloadManager( 3297): processing inserted download 4
V/DownloadManager( 3297): processing inserted download 7
V/DownloadManager( 3297): processing inserted download 8
V/DownloadManager( 3297): processing inserted download 9
V/DownloadManager( 3297): processing inserted download 10
V/DownloadManager( 3297): processing inserted download 16
V/DownloadManager( 3297): processing inserted download 17
V/DownloadManager( 3297): processing inserted download 18
V/DownloadManager( 3297): processing inserted download 21
V/DownloadManager( 3297): processing inserted download 22
I/art     ( 2135): Explicit concurrent mark sweep GC freed 25465(1476KB) AllocSpace objects, 2(32KB) LOS objects, 51% free, 30MB/62MB, paused 1.796ms total 47.574ms
,E/LGDMClient( 3990): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
,D/LGDMClient( 3990): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
,D/LGDMClient( 3990): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
W/libprocessgroup( 1026): failed to open /acct/uid_10097/pid_5601/cgroup.procs: No such file or directory
V/DownloadManager( 3297): DownloadService onDestroy
,W/GAV2    ( 6454): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
W/ResourcesManager( 6522): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6522): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 6522): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6522): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/BooksApp( 6454): Created application version: 3.2.35 (30235)
,W/DriveInitializer( 2361): Background init thread started
,E/Auth.Api.Credentials( 2361): [CredentialSyncAdapter] Unknown sync event.
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.gms/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
D/DelayedSyncController( 6494): Delaying sync.
W/ContextImpl( 2361): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.gms/files
I/ActivityManager( 1026): Killing 5896:com.lge.eula/1000 (adj 15): empty #17
,W/DriveInitializer( 2361): Awaiting to be initialized
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/BooksSync( 6454): Starting books sync
W/libprocessgroup( 1026): failed to open /acct/uid_1000/pid_5896/cgroup.procs: No such file or directory
,I/LGEmail ( 6522): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 6522): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,E/WifiStateMachine( 1026):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=4.8, 0.0, 0.0  rx=3.5 bcn=0 [on:0 tx:0 rx:0 period:3359] from screen [on:0 period:-1292709005] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1026):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=4.8, 0.0, 0.0  rx=3.5 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:-1292709005] gl rssi=-57 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1026): doString: [SIGNAL_POLL]
,W/DriveInitializer( 2361): Background init thread ended
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/ads_measurement
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/ads_measurement without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Ads     ( 2361): [JAMS] Failed to get OAuth token: com.google.android.gms.auth.ad: BadAuthentication
,W/ResourceType( 6522): No package identifier when getting value for resource number 0x00000000
D/LgDataFeature( 6522): LgDataFeature() Constructor: none
D/LgDataFeature( 6522): LgDataFeature() Constructor Done, null
,D/libc-netbsd(  327): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  327): res_queryN name = www.google.com, class = 1, type = 1
,D/libc-netbsd(  327): res_queryN name = www.google.com succeed
,D/libc-netbsd(  327): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  327): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  327): res_queryN name = clients3.google.com succeed
,D/BooksSync( 6454): started syncMyEbooks
,D/eas_req ( 6522): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,V/WifiInternetCheck( 1026): isHttpConnectionAvailable - We got a valid response : 204
I/LgeMiscReceiver( 3243): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3243): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 3243): networkInfo.isConnected() = true
D/PhoneState( 3243): setPdpRejectCasuse : false
I/HubEmail( 6522): JNI_OnLoad()
I/HubEmail( 6522): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6522): registerNatives()
I/HubEmail( 6522): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6522): registerNativeMethods()
I/HubEmail( 6522): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6522): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
W/Settings( 6522): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/libc-netbsd(  327): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  327): res_queryN name = static-avc.lglime.com, class = 1, type = 1
,I/ActivityManager( 1026): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6583 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
W/Settings( 6522): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/UEI.SmartControl( 5866): Internal timer expired: 4
D/UEI.SmartControl( 5866): unbind internal service
,I/art     ( 1026): Explicit concurrent mark sweep GC freed 32423(1441KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 44MB/66MB, paused 1.389ms total 70.599ms
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/serial_port( 5866): close(fd = 24)
I/UEI.SmartControl( 5866): Serial port is closed.
V/NotificationService( 1026): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,D/ZenLog  ( 1026): intercepted: 0|com.google.android.gms|1|null|10005,none
,V/NotificationService( 1026): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1026): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1026): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1026): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2135): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2135): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2135): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2135): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6454): Authentication error
E/BooksAccountManager( 6454): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6454): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6454): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6454): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6454): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6454): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6454): null auth token
W/ResourcesManager( 1465): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1465): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager( 1411): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1411): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/LgeQuickCoverNLService( 1411): onNotificationPosted
D/libc-netbsd(  327): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  327): res_queryN name = www.googleapis.com, class = 1, type = 1
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
,D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1411): updateNotificationData: count=3
D/DrmBroadcastReceiver( 6583): Receive CONNECTIVITY_ACTION
D/DrmBroadcastReceiver( 6583): 1  network is available. Sync DRM Time with NTP
,D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{782bd5b V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
V/DrmService( 6583): Service onCreate
D/DrmService( 6583): Received new request = 2
I/DrmSntpClient( 6583): Start Sync process
,D/DrmSntpClient( 6583): Server : 0
D/libc-netbsd(  327): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  327): res_queryN name = pool.ntp.org, class = 1, type = 1
D/libc-netbsd(  327): res_queryN name = www.googleapis.com succeed
D/libc-netbsd(  327): res_queryN name = static-avc.lglime.com succeed
,D/libc-netbsd(  327): res_queryN name = pool.ntp.org succeed
,I/ActivityManager( 1026): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=6606 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/FormManager( 6168): There are no updated forms. The schedule will be deleted.
V/FormManager( 6168): Alarm would be updated, because LastCheckTime has been updated.
I/LGDrmClient( 6583): _DRM_ServiceGet() : Bind lgdrm service
V/ILGDrmService(  336): eDRM_SetDRMTime +++
I/LGDRM   (  336): [DRM] SET TIME : YR=2016, MON=2, DAY=5
I/LGDRM   (  336): [DRM] SET TIME : HR=19, MIN=40, SEC=3
,V/ILGDrmService(  336): eDRM_SetDRMTime ---
I/DrmSntpClient( 6583): Synched
D/DrmService( 6583): Completed !! request = 2
I/ActivityManager( 1026): Killing 5412:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
D/DrmService( 6583): Request count = 0
,W/libprocessgroup( 1026): failed to open /acct/uid_10005/pid_5412/cgroup.procs: No such file or directory
V/DrmService( 6583): Service onDestroy
I/ActivityManager( 1026): Killing 4606:com.android.providers.calendar/u0a14 (adj 15): empty #17
,W/ApiaryClient( 6454): Error response from books API: {
W/ApiaryClient( 6454):  "error": {
W/ApiaryClient( 6454):   "errors": [
W/ApiaryClient( 6454):    {
W/ApiaryClient( 6454):     "domain": "global",
W/ApiaryClient( 6454):     "reason": "required",
W/ApiaryClient( 6454):     "message": "Login Required",
W/ApiaryClient( 6454):     "locationType": "header",
W/ApiaryClient( 6454):     "location": "Authorization"
W/ApiaryClient( 6454):    }
W/ApiaryClient( 6454):   ],
W/ApiaryClient( 6454):   "code": 401,
W/ApiaryClient( 6454):   "message": "Login Required"
W/ApiaryClient( 6454):  }
W/ApiaryClient( 6454): }
,W/ApiaryClient( 6454): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6454): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7942475560706659353&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6454): Headers:
W/ApiaryClient( 6454): accept-encoding: [gzip]
W/ApiaryClient( 6454): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6454): gdata-version: 2
I/art     ( 6606): Almond Protected OAT
W/libprocessgroup( 1026): failed to open /acct/uid_10014/pid_4606/cgroup.procs: No such file or directory
,D/WeatherApplication( 6606): removeAccount
,D/WeatherApplication( 6606): Account.length = 0
E/WeatherApplication( 6606): OPERATOR:OPEN
D/WeatherAncestor( 6606): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 20:40:5
D/Weather.Utils( 6606): 2 : the weather widgets(using time tick) are gone.
,D/Weather.Utils( 6606): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6606): 2 : This is isUpdating : false
D/WeatherAncestor( 6606): connectivity changed - connection : true
D/WeatherService( 6606): 2 : isServiceAlived():false forecastCache:null
,D/ForecastDataCache( 6606): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 6606): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 6606): 2 : Cache is not up-to-date, count: 0
D/Weather_cast( 6606): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 6606): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 20:40:5
,I/ActivityManager( 1026): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6625 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1026): Killing 2231:com.lge.music/u0a34 (adj 15): empty #17
V/AudioFlinger(  331): 2231 died, releasing its sessions
V/AudioFlinger(  331):  pid 1865 @ 0
V/AudioFlinger(  331):  pid 3243 @ 1
V/AudioFlinger(  331):  pid 3243 @ 2
,W/libprocessgroup( 1026): failed to open /acct/uid_10034/pid_2231/cgroup.procs: No such file or directory
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6625): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6625): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6625): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6625): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
,I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1026): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1026): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1026): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1026): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1026): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2135): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2135): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2135): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2135): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1411): onNotificationPosted
D/ContactsSyncAdapter( 2135): innerSync failed
D/ContactsSyncAdapter( 2135): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2135): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2135): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2135): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2135): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2135): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2135): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2135): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2135): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2135): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2135): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2135): 	at android.os.Binder.execTransact(Binder.java:446)
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
D/LgeQuickCoverOverlayWindo,w( 1411): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1411): updateNotificationData: count=3
D/SyncManager( 1026): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 26988, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager( 1026): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 149359, reason: 10019
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{782bd5b V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/ActivityManager( 1026): Start proc com.google.android.apps.plus for service com.google.android.apps.plus/.service.EsSyncAdapterService: pid=6651 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 6651): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/WebViewFactory( 6625): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 6625): Loading: webviewchromium
,I/LibraryLoader( 6625): Time to load native libraries: 4 ms (timestamps 6987-6991)
I/LibraryLoader( 6625): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6625): Binding Chromium to main looper Looper (main, tid 1) {b29190a}
I/LibraryLoader( 6625): Expected native library version number "",actual native library version number ""
I/chromium( 6625): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6625): Initializing chromium process, renderers=0
W/art     ( 6625): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 6625): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 6625): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 6625): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
V/AudioPolicyService(  331): registerClient() client 0xb100fe80, uid 10093
I/Adreno-EGL( 6625): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6625): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6625): Build Date: 12/12/14 금
I/Adreno-EGL( 6625): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6625): Remote Branch: 
I/Adreno-EGL( 6625): Local Patches: 
I/Adreno-EGL( 6625): Reconstruct Branch: 
,W/AudioManagerAndroid( 6625): Requires BLUETOOTH permission
I/NSApplication( 6625): Starting up...
,I/ActivityManager( 1026): Killing 4901:com.android.vending/u0a44 (adj 15): empty #17
,I/GLSActivity( 2135): [ac] getting account id
W/libprocessgroup( 1026): failed to open /acct/uid_10044/pid_4901/cgroup.procs: No such file or directory
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2135): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1026): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1026): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1026): LED remove() : mLights=0|com.google.android.gms|1|null|10005
W/GLSActivity( 2135): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2135): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2135): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2135): 	at android.os.Binder.execTransact(Binder.java:446)
D/NotificationServiceEx( 1026): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1026): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1411): onNotificationPosted
D/DelayedSyncController( 6494): Delaying sync.
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
E/BooksAccountManager( 6454): Authentication error
E/BooksAccountManager( 6454): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6454): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6454): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6454): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6454): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6454): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6454): null auth token
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1411): updateNotificationData: count=3
I/art     ( 2135): Explicit concurrent mark sweep GC freed 15381(888KB) AllocSpace objects, 8(1152KB) LOS objects, 51% free, 30MB/62MB, paused 1.379ms total 64.332ms
,D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{782bd5b V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  327): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  327): res_queryN name = mtalk.google.com, class = 1, type = 1
,I/iu.SyncManager( 2361): SYNC; picasa accounts
,I/GoogleURLConnFactory( 2361): Using platform SSLCertificateSocketFactory
D/NetworkLogImpl( 2361): Loaded NetworkSpeedPredictor
I/iu.Environment( 2361): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/gcm
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/gcm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/iu.UploadsManager( 2361): num queued entries: 0
I/iu.UploadsManager( 2361): num updated entries: 0
W/ApiaryClient( 6454): Error response from books API: {
W/ApiaryClient( 6454):  "error": {
W/ApiaryClient( 6454):   "errors": [
W/ApiaryClient( 6454):    {
W/ApiaryClient( 6454):     "domain": "global",
W/ApiaryClient( 6454):     "reason": "required",
W/ApiaryClient( 6454):     "message": "Login Required",
W/ApiaryClient( 6454):     "locationType": "header",
W/ApiaryClient( 6454):     "location": "Authorization"
W/ApiaryClient( 6454):    }
W/ApiaryClient( 6454):   ],
W/ApiaryClient( 6454):   "code": 401,
W/ApiaryClient( 6454):   "message": "Login Required"
W/ApiaryClient( 6454):  }
W/ApiaryClient( 6454): }
I/iu.SyncManager( 2361): NEXT; no task
,W/ApiaryClient( 6454): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6454): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7942475560706659353&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6454): Headers:
W/ApiaryClient( 6454): accept-encoding: [gzip]
W/ApiaryClient( 6454): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6454): gdata-version: 2
D/libc-netbsd(  327): res_queryN name = mtalk.google.com succeed
D/ChimeraCfgMgr( 2361): Loading module com.google.android.gms.kids from APK com.google.android.gms
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GcmGroups( 2361): Failed to subscribe to group.
I/GcmGroups( 2361): com.google.android.gms.auth.ad: BadAuthentication
I/GcmGroups( 2361): 	at com.google.android.gms.auth.p.b(SourceFile:442)
I/GcmGroups( 2361): 	at com.google.android.gms.auth.p.a(SourceFile:365)
I/GcmGroups( 2361): 	at com.google.android.gms.auth.p.a(SourceFile:318)
I/GcmGroups( 2361): 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:443)
I/GcmGroups( 2361): 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:333)
I/GcmGroups( 2361): 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:240)
I/GcmGroups( 2361): 	at com.google.android.gms.gcm.gmsproc.GcmReceiverService.onHandleIntent(SourceFile:50)
I/GcmGroups( 2361): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
I/GcmGroups( 2361): 	at android.os.Handler.dispatchMessage(Handler.java:102)
I/GcmGroups( 2361): 	at android.os.Looper.loop(Looper.java:135)
I/GcmGroups( 2361): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/art     ( 2361): Explicit concurrent mark sweep GC freed 17380(1259KB) AllocSpace objects, 20(320KB) LOS objects, 49% free, 32MB/64MB, paused 903us total 37.769ms
D/ChimeraCfgMgr( 2361): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/art     ( 1026): Explicit concurrent mark sweep GC freed 24520(1044KB) AllocSpace objects, 3(304KB) LOS objects, 33% free, 44MB/66MB, paused 1.225ms total 88.522ms
,I/GcmGroups( 2361): Groups upload failed, retrying in 24000:00:00
,D/PostponalbeReceiver( 5205): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.TIME_SET'.
,I/ActivityManager( 1026): Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=6724 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: mail
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> mail without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1026): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1026): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1026): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1026): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1026): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1026): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1026): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1026): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1026): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
,D/NotificationServiceEx( 1026): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2135): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2135): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2135): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2135): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1411): onNotificationPosted
W/SubscribedFeeds( 2361): Hard error
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
D/LgeQuickCoverNLService( 1411): onNotificationPosted
,W/Kids    ( 2361): [AccountUtils] Account not ready
W/Kids    ( 2361): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2361): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2361): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2361): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2361): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2361): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2361): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2361): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2361): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2361): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2361): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2361): 	at java.lang.Thread.run(Thread.java:818)
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1411): updateNotificationData: count=3
D/SyncManager( 1026): failed sync operation thalitester@gmail.com u0 (com.google), subscribedfeeds, PERIODIC, currentRunTime 39728, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager( 1026): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), subscribedfeeds, PERIODIC, currentRunTime 148479, reason: Periodic
,D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{782bd5b V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
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
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{782bd5b V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,I/ActivityManager( 1026): Start proc com.google.android.syncadapters.calendar for service com.google.android.syncadapters.calendar/.CalendarSyncAdapterService: pid=6741 uid=10069 gids={50069, 9997, 3003} abi=armeabi-v7a
,D/ALBootInit( 6724): ====action==>android.intent.action.TIME_SET
D/ALBootInit( 6724): Alarm ALBootInit: TIME_SET
D/Alarms  ( 6724): [setNextAlert] start
,D/Alarms  ( 6724): [setNextAlert] (1)
D/Alarms  ( 6724):  minTime  = 0
D/Alarms  ( 6724):  -- OK multi -- 0
E/jeny.kim( 6724): [setNextAlert] setNextAlert  temp_Alarmlink + 
E/jeny.kim( 6724): [setNextAlert]setNextAlert temp_AlarmLinkText + 
I/CommonUtil( 6724): BUILD Country: EU
,D/Alarms  ( 6724): broadcastToWidgetProvider : false
D/Alarms  ( 6724): Enter formatDayAndTime(final Context context, long timeInMiliSec)
V/SettingsProvider( 1026): call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
,I/DigitalAppWidgetProvider( 6724): onReceive: android.intent.action.TIME_SET
V/DigitalAppWidgetProvider( 6724): cancelAlarmOnQuarterHour android.app.ReceiverRestrictedContext@37432350
V/DigitalAppWidgetProvider( 6724): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@37432350
D/QuickCoverProvider( 6724): onReceiver
I/indal   ( 1411): SmartCoverWidgetContext createApplicationContext
,I/indal   ( 1411): SmartCoverWidgetContext createApplicationContext
D/WeatherAncestor( 6606): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 20:40:6
D/Weather.Utils( 6606): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6606): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6606): 2 : This is isUpdating : false
D/WeatherService( 6606): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1c389949
D/ForecastDataCache( 6606): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 6606): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 6606): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 6606): 2 : set auto-update time : 2/5 23:40
D/WeatherAncestor( 6606): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 20:40:6
,D/GCM     ( 2135): Connected
,I/ActivityManager( 1026): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=6765 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1026): Killing 5921:com.lge.bnr/1000 (adj 15): empty #17
,W/AbstractGoogleClient( 6741): Application name is not set. Call Builder#setApplicationName.
,W/libprocessgroup( 1026): failed to open /acct/uid_1000/pid_5921/cgroup.procs: No such file or directory
,D/GCM     ( 2135): Message class com.google.f.a.a.p
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1026): tsOffsetIs: Apps: 118052380740; DSPS: 4009735; Offset : -4330564183
D/TimeService( 6765): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1454701206779
D/        ( 6765): TimeServiceNative: User Time to be set is 1454701206779
D/QC-time-services( 6765): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 6765): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 6765): Lib:time_genoff_operation: pargs->ts_val = 1454701206779
D/QC-time-services( 6765): Lib:time_genoff_operation: Send to server  passed!!
,D/QC-time-services(  370): Daemon: Connection accepted:time_genoff
D/QC-time-services(  370): Daemon:Received base = 2, unit = 1, operation = 0,value = 1454701206779
D/QC-time-services(  370): Daemon:genoff_opr: Base = 2, val = 1454701206779, operation = 0
D/QC-time-services(  370): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS5/15/70 12:52:11
D/QC-time-services(  370): Daemon:Value read from RTC seconds = 14302331000
D/QC-time-services(  370): Daemon:new time 1454701206779 
D/QC-time-services(  370): Daemon: delta 1440398875779 genoff 1440398875779 
D/QC-time-services(  370): Daemon:genoff_persistent_update: Writing genoff = 1440398875779 to memory
D/QC-time-services(  370): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  370): Daemon:time_persistent_memory_opr:Genoff write operation 
D/QC-time-services(  370): Updating the TOD offset
D/QC-time-services(  370): Daemon:genoff_persistent_update: Writing genoff = 1440398875779 to memory
D/QC-time-services(  370): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  370): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services(  370): Daemon:Update to modem bit set
D/QC-time-services(  370): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  370): Daemon: Base = 2, Value being sent to MODEM = 1124434075779
E/QC-time-services( 6765): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
E/QC-time-services(  370): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
E/QC-time-services(  370): Daemon: Time-services: Waiting to acceptconnection
I/ActivityManager( 1026): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6785 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi
,I/ActivityManager( 1026): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetProvider: pid=6802 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi
I/ActivityManager( 1026): Killing 6223:com.lge.lifetracker/u0a37 (adj 15): empty #17
I/art     (  352): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 361us total 20.620ms
,I/art     (  352): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 348us total 16.234ms
,I/art     (  352): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 328us total 14.889ms
,W/libprocessgroup( 1026): failed to open /acct/uid_10037/pid_6223/cgroup.procs: No such file or directory
,W/ResourcesManager( 6785): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/GoogleURLConnFactory( 2135): Using platform SSLCertificateSocketFactory
,W/ResourcesManager( 6802): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/CalendarProvider2( 6785): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@33bcd911
W/Uploader( 2135): No account for auth token provided
D/libc-netbsd(  327): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  327): res_queryN name = play.googleapis.com, class = 1, type = 1
D/CalendarProvider2( 6785): [getOrCreateCalendarAlarmManager]
I/CalendarProvider2( 6785): Created com.android.providers.calendar.CalendarAlarmManager@1d681802(com.android.providers.calendar.CalendarProvider2@33bcd911)
D/CalendarApplication( 6802): CalendarApplication.onCreate()
,D/PreferenceKeysParser( 6802): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 6802): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@25a75877, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@283f1ce4, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@1a04f54d, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@1d681802, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@102f0513, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@37432350, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@1c389949, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@1a43b24e, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@57adf6f, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@43f247c, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@3fe88105, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@1c2ca55a, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@1700038b, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@14980c68, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@18f52881, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@277fbd26, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@2e694d67, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@1d158714, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@3ecacbbd, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@179a85b2, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@3b335903, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@354e0080, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@195d66b9, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@2e274afe, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@1e08825f, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@15d2a4ac, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@1e4b575, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@b29190a, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@2ddce57b, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@d1b5f98, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@335833f1, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@19c7bbd6, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@32ca5e57, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@1732dd44, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@6ab1e2d, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@3ddbbf62, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@32ac88f3, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@42289b0, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@36c87029, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@e3a6fae, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@2b7cc14f, lg_preferences_rec,ent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@191e90
,D/GeneralPreferenceUtils( 6802): [migratePrefrenceKeys] Exit: Version(44001600) >= 42001300
D/Config  ( 6802): [init]
,D/libc-netbsd(  327): res_queryN name = play.googleapis.com succeed
I/Config  ( 6802): LGCalendar ver.4.40.16
I/Config  ( 6802): start check model
I/Config  ( 6802): start check native_ca
I/Config  ( 6802): Config Operator=OPEN, Country=EU
D/Config  ( 6802): [setDefaultValuesToPref]
D/Config  ( 6802): [parseProfiles]
D/ProfilesParser( 6802): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6802): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6802): [updateProfiletoCountryInfo]
D/GeneralPreference( 6802): [checkAndMigrateOldPreference]
E/AgendaWidgetManager( 6802): [updateWidgets] 
,I/InitNotificationRingtoneService( 6802): Start InitializeAlertRingtoneService.onHandleIntent
,I/AlertUtils( 6802): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/41
I/AlertUtils( 6802): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 6802): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arpeggio.ogg
,I/AlertUtils( 6802): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 6802): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
,I/AlertUtils( 6802): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 6802): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 6802): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 6802): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 6802): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
,I/AlertUtils( 6802): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 6802): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Afternoon_Walk.ogg
I/AlertUtils( 6802): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 6802): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 6802): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 6802): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
,I/AlertUtils( 6802): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/AlertUtils( 6802): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/41
I/AlertUtils( 6802): set default noti to content://media/internal/audio/media/41
I/InitNotificationRingtoneService( 6802): End InitializeAlertRingtoneService.onHandleIntent
I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/HolidayIntentService( 6802): onHandleIntent
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/HolidayDataLoader( 6802): readJsonAsset : holiday.json
D/MonthWidgetProvider( 6802): [onReceive]
D/CalendarWidgetProvider( 6802): [onReceive]
D/CalendarWidgetProvider( 6802): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 6802): [onUpdateAndInitCalendarTime]
D/WeekWidgetProvider( 6802): [onReceive]
D/CalendarWidgetProvider( 6802): [onReceive]
D/CalendarWidgetProvider( 6802): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 6802): [onUpdateAndInitCalendarTime]
,V/NotificationService( 1026): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2135): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2135): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2135): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2135): 	at android.os.Binder.execTransact(Binder.java:446)
V/NotificationService( 1026): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1026): LED remove() : mLights=0|com.google.android.gms|1|null|10005
E/BooksAccountManager( 6454): Authentication error
E/BooksAccountManager( 6454): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6454): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6454): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6454): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6454): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6454): 	at android.os.Binder.execTransact(Binder.java:446)
D/NotificationServiceEx( 1026): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
E/HttpHelper( 6454): null auth token
D/NotificationServiceEx( 1026): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.calendar, service: oauth2:https://www.googleapis.com/auth/calendar
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/calendar without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{782bd5b V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
E/HolidayIntentService( 6802): onHandleIntent:holiday data empty
I/ActivityManager( 1026): Killing 6265:com.lge.settings.easy/1000 (adj 15): empty #17
W/ApiaryClient( 6454): Error response from books API: {
W/ApiaryClient( 6454):  "error": {
W/ApiaryClient( 6454):   "errors": [
W/ApiaryClient( 6454):    {
W/ApiaryClient( 6454):     "domain": "global",
W/ApiaryClient( 6454):     "reason": "required",
W/ApiaryClient( 6454):     "message": "Login Required",
W/ApiaryClient( 6454):     "locationType": "header",
W/ApiaryClient( 6454):     "location": "Authorization"
W/ApiaryClient( 6454):    }
W/ApiaryClient( 6454):   ],
W/ApiaryClient( 6454):   "code": 401,
W/ApiaryClient( 6454):   "message": "Login Required"
W/ApiaryClient( 6454):  }
W/ApiaryClient( 6454): }
W/ApiaryClient( 6454): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6454): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7942475560706659353&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6454): Headers:
W/ApiaryClient( 6454): accept-encoding: [gzip]
W/ApiaryClient( 6454): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6454): gdata-version: 2
,E/WifiStateMachine( 1026):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-54 f=2412 sc=60 link=72 tx=4.4, 0.0, 0.0  rx=3.2 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1292705996] gl rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1026):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-54 f=2412 sc=60 link=72 tx=4.4, 0.0, 0.0  rx=3.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1292705993] gl rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1026): doString: [SIGNAL_POLL]
W/libprocessgroup( 1026): failed to open /acct/uid_1000/pid_6265/cgroup.procs: No such file or directory
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
D/GCM     ( 2135): GcmService start Intent { act=com.google.android.gcm.intent.SEND flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.gcm.intent.SEND
,I/DigitalAppWidgetProvider( 6724): onReceive: android.intent.action.ALARM_CHANGED
D/WeatherAncestor( 6606): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 20:40:7
D/Weather.Utils( 6606): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6606): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6606): 2 : This is isUpdating : false
D/Weather_cast( 6606): 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
D/WeatherAncestor( 6606): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 20:40:7
,I/ActivityManager( 1026): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RequestWriter$NetworkStateReceiver: pid=6833 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/Uploader( 2135): No account for auth token provided
W/ResourcesManager( 6833): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
V/NotificationService( 1026): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1026): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1026): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1026): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1026): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,D/LgeQuickCoverNLService( 1411): onNotificationPosted
D/SmartCoverUpdateMonitor( 1411): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1411): MSG_NOTIFICATION_POSTED
,D/SmartCoverUpdateMonitor( 1411): handleNotificationPosted(true)
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
E/CalendarSyncAdapter( 6741): Exception in onPerformLoggedSync 
E/CalendarSyncAdapter( 6741): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/CalendarSyncAdapter( 6741): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(GoogleRequestInitializer.java:152)
E/CalendarSyncAdapter( 6741): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(GoogleRequestInitializer.java:89)
E/CalendarSyncAdapter( 6741): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:858)
E/CalendarSyncAdapter( 6741): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(AbstractGoogleClientRequest.java:410)
E/CalendarSyncAdapter( 6741): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(AbstractGoogleClientRequest.java:343)
E/CalendarSyncAdapter( 6741): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(AbstractGoogleClientRequest.java:460)
E/CalendarSyncAdapter( 6741): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.processAccountCalendars(CalendarSyncAdapterApiary.java:1510)
E/CalendarSyncAdapter( 6741): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.updateCalendarsFromServerFeed(CalendarSyncAdapterApiary.java:1024)
E/CalendarSyncAdapter( 6741): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.getServerDiffs(CalendarSyncAdapterApiary.java:906)
E/CalendarSyncAdapter( 6741): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.performSync(CalendarSyncAdapterApiary.java:430)
E/CalendarSyncAdapter( 6741): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.onPerformLoggedSync(CalendarSyncAdapterApiary.java:335)
E/CalendarSyncAdapter( 6741): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
E/CalendarSyncAdapter( 6741): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/CalendarSyncAdapter( 6741): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/CalendarSyncAdapter( 6741): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/CalendarSyncAdapter( 6741): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/CalendarSyncAdapter( 6741): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(GoogleRequestInitializer.java:140)
E/CalendarSyncAdapter( 6741): 	... 12 more
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1411): updateNotificationData: count=3
,I/ActivityManager( 1026): Killing 6197:com.lge.sync/1000 (adj 15): empty #17
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{782bd5b V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/SyncManager( 1026): failed sync operation thalitester@gmail.com u0 (com.google), com.android.calendar, PERIODIC, currentRunTime 39830, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,I/ActivityManager( 1026): Killing 5866:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,D/SyncManager( 1026): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.calendar, PERIODIC, currentRunTime 150002, reason: Periodic
,W/Uploader( 2135): No account for auth token provided
I/QRemote ( 6295): [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
W/System.err( 6295): android.os.DeadObjectException
W/System.err( 6295): 	at android.os.BinderProxy.transactNative(Native Method)
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
,W/System.err( 6295): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 6295): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/QRemote ( 6295): [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
E/libprocessgroup( 1026): failed to kill 1 processes for processgroup 5866
,W/libprocessgroup( 1026): failed to open /acct/uid_1000/pid_6197/cgroup.procs: No such file or directory
D/LgDataFeature( 6833): LgDataFeature() Constructor: none
D/LgDataFeature( 6833): LgDataFeature() Constructor Done, null
,W/ActivityManager( 1026): Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
D/QRemote ( 6295): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
I/QRemote ( 6295): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,W/Uploader( 2135):  no longer exists, so no auth token.
,I/ActivityManager( 1026): Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6852 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,D/QRemote ( 6295): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,W/Uploader( 2135): No account for auth token provided
,I/Babel   ( 6833): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 6833): MmsConfig.loadMmsSettings
I/art     ( 1026): Explicit concurrent mark sweep GC freed 24088(1101KB) AllocSpace objects, 5(592KB) LOS objects, 33% free, 44MB/66MB, paused 1.493ms total 103.121ms
,I/Babel   ( 6833): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
I/Babel   ( 6833): MmsConfig.loadFromDatabase
W/Uploader( 2135): No account for auth token provided
W/Settings( 6833): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Babel   ( 6833): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 6833): MmsConfig.loadFromResources
,E/Babel   ( 6833): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 6833): MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
W/AudioCapabilities( 6833): Unsupported mime audio/evrc
W/AudioCapabilities( 6833): Unsupported mime audio/qcelp
W/VideoCapabilities( 6833): Unrecognized profile 2130706433 for video/avc
,D/UEI.SmartControl( 6852): Quickset Services start...
I/UEI.SmartControl( 6852): Manufacture = LGE
D/UEI.SmartControl( 6852): Id = LGNevo
D/UEI.SmartControl( 6852): File observer start...
,E/UEI.SmartControl( 6852): IR Port is disabled: false
D/UEI.SmartControl( 6852): Starting file observer...
D/UEI.SmartControl( 6852): Extracting JNI libs...
D/UEI.SmartControl( 6852): --- this system supports 32-bit or 64-bit only
W/AudioCapabilities( 6833): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 6833): Unsupported mime audio/qcelp
W/AudioCapabilities( 6833): Unsupported mime audio/evrc
W/VideoCapabilities( 6833): Unsupported mime video/x-ms-wmv
W/VideoCapabilities( 6833): Unsupported mime video/divx
,W/VideoCapabilities( 6833): Unsupported mime video/divx311
W/VideoCapabilities( 6833): Unsupported mime video/divx4
W/VideoCapabilities( 6833): Unsupported mime video/mp4v-esdp
W/ResourcesManager( 6833): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6833): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GCoreUlr( 1830): Uploading GCM registration ID for account#2#
D/UEI.SmartControl( 6852): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 6852): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6852): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/VideoCapabilities( 6833): Unsupported profile 4 for video/mp4v-es
V/JNIHelp ( 6833): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
W/AudioCapabilities( 6833): Unsupported mime audio/eac3
W/AudioCapabilities( 6833): Unsupported mime audio/ac3
W/AudioCapabilities( 6833): Unsupported mime audio/g726
W/AudioCapabilities( 6833): Unsupported mime audio/wma-voice
W/AudioCapabilities( 6833): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6833): Unsupported mime audio/adpcm
,W/VideoCapabilities( 6833): Unsupported mime video/theora
I/UEI.SmartControl( 6852): --- Selecting new region: 6
W/VideoCapabilities( 6833): Unsupported mime video/mjpg
I/UEI.SmartControl( 6852): Model = LG-D855
D/UEI.SmartControl( 6852): QS Service created
I/UEI.SmartControl( 6852): Service initServices...
,D/UEI.SmartControl( 6852): QS start get config
E/BooksSync( 6454): Soft error: 
E/BooksSync( 6454): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6454): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7942475560706659353&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6454): Headers:
E/BooksSync( 6454): accept-encoding: [gzip]
E/BooksSync( 6454): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6454): gdata-version: 2
E/BooksSync( 6454): 
E/BooksSync( 6454): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6454): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6454): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6454): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6454): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6454): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6454): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6454): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6454): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6454): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6454): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6454): {
E/BooksSync( 6454):  "error": {
E/BooksSync( 6454):   "errors": [
E/BooksSync( 6454):    {
E/BooksSync( 6454):     "domain": "global",
E/BooksSync( 6454):     "reason": "required",
E/BooksSync( 6454):     "message": "Login Required",
E/BooksSync( 6454):     "locationType": "header",
E/BooksSync( 6454):     "location": "Authorization"
E/BooksSync( 6454):    }
E/BooksSync( 6454):   ],
E/BooksSync( 6454):   "code": 401,
E/BooksSync( 6454):   "message": "Login Required"
E/BooksSync( 6454):  }
E/BooksSync( 6454): }
E/BooksSync( 6454): 
E/BooksSync( 6454): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6454): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6454): 	... 8 more
E/BooksSync( 6454): Sync error
E/BooksSync( 6454): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6454): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7942475560706659353&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6454): Headers:
E/BooksSync( 6454): accept-encoding: [gzip]
E/BooksSync( 6454): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6454): gdata-version: 2
E/BooksSync( 6454): 
E/BooksSync( 6454): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6454): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6454): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6454): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6454): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6454): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6454): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6454): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6454): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6454): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6454): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6454): {
E/BooksSync( 6454):  "error": {
E/BooksSync( 6454):   "errors": [
E/BooksSync( 6454):    {
E/BooksSync( 6454):     "domain": "global",
E/BooksSync( 6454):     "reason": "required",
E/BooksSync( 6454):     "message": "Login Required",
E/BooksSync( 6454):     "locationType": "header",
E/BooksSync( 6454):     "location": "Authorization"
E/BooksSync( 6454):    }
E/BooksSync( 6454):   ],
E/BooksSync( 6454):   "code": 401,
E/BooksSync( 6454):   "message": "Login Required"
E/BooksSync( 6454):  }
E/BooksSync( 6454): }
E/BooksSync( 6454): 
E/BooksSync( 6454): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6454): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6454): 	... 8 more
I/BooksSync( 6454): Finished books sync
W/System  ( 6833): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/system/app/Hangouts/Hangouts.apk"],nativeLibraryDirectories=[/system/app/Hangouts/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6833): Installed default security provider GmsCore_OpenSSL
,D/UEI.SmartControl( 6852): Loading JNI Libs...
I/ThermalEngine(  342): Thermal-Server: Thermal received msg from  override
I/Thermal-Lib( 3099): Thermal-Lib-Client: Client request sent
,D/SyncManager( 1026): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 26944, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
I/ActivityManager( 1026): Killing 6136:com.android.settings/1000 (adj 15): empty #17
D/WifiService( 1026): Client connection lost with reason: 4
,W/libprocessgroup( 1026): failed to open /acct/uid_1000/pid_6136/cgroup.procs: No such file or directory
W/BaseAppContext( 1830): Using Auth Proxy for data requests.
,V/AlarmManager( 1026): ELAPSED_WAKEUP set : Alarm{2daf44d9 type 2 when 119735 com.android.providers.calendar} when 119735
,D/CalendarProviderBroadcastReceiver( 6785): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 6785): [IntentService] WakeLock acquire, start IntentSerivce
V/QRemote ( 6295): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
D/QRemote ( 6295): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:9987
,D/CalendarProvider2( 6785): CalendarProviderIntentService.onCreate()
D/CalendarProvider2( 6785): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 6785): [getOrCreateCalendarAlarmManager]
E/SQLiteLog( 6785): (284) automatic index on view_events(_id)
D/CalendarProvider2( 6785): [IntentService] Release Lock
,D/CalendarProvider2( 6785): CalendarProviderIntentService.onDestroy()
I/GLSUser ( 1830): [ChannelManager] Attempting to channel bind connection HttpClient.
I/GLSUser ( 1830): [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/UEI.SmartControl( 6852): Supports setup maps: true
,D/UEI.SmartControl( 6852): QS start statue = true Error code = 0
I/UEI.SmartControl( 6852): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6852): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
,I/UEI.SmartControl( 6852): ### init IR Blaster...
D/serial_port( 6852): Configuring serial port
E/UEI.SmartControl( 6852): UEIBLaster setting for 616
I/UEI.SmartControl( 6852): Setting serial record hearder size = 2
I/UEI.SmartControl( 6852): configuring settings for MAXQ616
I/UEI.SmartControl( 6852): Get version...
D/UEI.SmartControl( 6852): serial port data available: 21
,I/ActivityManager( 1026): Start proc com.google.android.gm for service com.google.android.gm/.provider.MailSyncAdapterService: pid=6896 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/Babel   ( 6833): UserRecoverableAuthException.
E/Babel   ( 6833): cfq: BadAuthentication
E/Babel   ( 6833): 	at cfn.a(Unknown Source)
E/Babel   ( 6833): 	at f.a(PG:191)
E/Babel   ( 6833): 	at ava.a(PG:88)
E/Babel   ( 6833): 	at ava.a(PG:128)
E/Babel   ( 6833): 	at bjs.a(PG:255)
E/Babel   ( 6833): 	at bep.a(PG:602)
E/Babel   ( 6833): 	at bep.a(PG:469)
E/Babel   ( 6833): 	at bpo.run(PG:1141)
E/Babel   ( 6833): Error getting auth token
E/Babel   ( 6833): bxl
E/Babel   ( 6833): 	at f.a(PG:201)
E/Babel   ( 6833): 	at ava.a(PG:88)
E/Babel   ( 6833): 	at ava.a(PG:128)
E/Babel   ( 6833): 	at bjs.a(PG:255)
E/Babel   ( 6833): 	at bep.a(PG:602)
E/Babel   ( 6833): 	at bep.a(PG:469)
E/Babel   ( 6833): 	at bpo.run(PG:1141)
I/Babel_RequestWriter( 6833): error sending REQ[fc:8; creat:1454683021463; type:bev-986262441]; took 255 ms (error code == 100)
E/Babel   ( 6833): Account registration failedRedacted-21
,E/Babel   ( 6833): bph: null -- null
E/Babel   ( 6833): 	at ava.a(PG:120)
E/Babel   ( 6833): 	at ava.a(PG:128)
E/Babel   ( 6833): 	at bjs.a(PG:255)
E/Babel   ( 6833): 	at bep.a(PG:602)
E/Babel   ( 6833): 	at bep.a(PG:469)
E/Babel   ( 6833): 	at bpo.run(PG:1141)
I/Babel   ( 6833): Account setup failed with error state:106 account:Redacted-21
I/Babel   ( 6833): Account sign in complete with state 106account: Redacted-21
D/UEI.SmartControl( 6852): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 6852): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 6852): QS saving settings...
D/UEI.SmartControl( 6852): IR Blaster version: 25672567
,D/UEI.SmartControl( 6852): serial port data available: 4
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/userlocation.reporting
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/userlocation.reporting without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 6833): Note: end time exceeds epoch: 
W/ResourcesManager( 2135): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ContextImpl( 6852): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
E/UEI.SmartControl( 6852): Services init done
D/UEI.SmartControl( 6852): QS Service init finished
D/UEI.SmartControl( 6852): QS Service version name: 2.1.91
D/UEI.SmartControl( 6852): QS Service version code: 201091
D/UEI.SmartControl( 6852): Service requested: Control
I/UEI.SmartControl( 6852): Device manager: loading config....
D/UEI.SmartControl( 6852): ----------- loading internal config...
E/GCoreUlr( 1830): 
E/GCoreUlr( 1830): com.google.android.gms.auth.ad: BadAuthentication
E/GCoreUlr( 1830): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/GCoreUlr( 1830): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/GCoreUlr( 1830): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/GCoreUlr( 1830): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/GCoreUlr( 1830): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/GCoreUlr( 1830): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/GCoreUlr( 1830): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/GCoreUlr( 1830): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/GCoreUlr( 1830): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/GCoreUlr( 1830): 	at com.google.android.location.reporting.c.c.a(SourceFile:166)
E/GCoreUlr( 1830): 	at com.google.android.location.reporting.c.g.a(SourceFile:111)
E/GCoreUlr( 1830): 	at com.google.android.location.reporting.service.t.b(SourceFile:220)
E/GCoreUlr( 1830): 	at com.google.android.location.reporting.service.t.a(SourceFile:173)
E/GCoreUlr( 1830): 	at com.google.android.location.reporting.service.s.onPerformSync(SourceFile:149)
E/GCoreUlr( 1830): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
V/NotificationService( 1026): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1026): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1026): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1026): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
,D/NotificationServiceEx( 1026): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1411): onNotificationPosted
D/SmartCoverUpdateMonitor( 1411): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1411): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1411): handleNotificationPosted(true)
D/QuickCircle( 1411): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1411): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1411): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1411): post do just update job
D/LgeQuickCoverNotificationData( 1411): showAll3
E/Babel   ( 6833): Unexpected exception while authenticating.
D/LgeQuickCoverNotificationData( 1411): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1411): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1411): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1411): showNotificationWithSetupData: display=false
E/Babel   ( 6833): cfr: User intervention required. Notification has been pushed.
E/Babel   ( 6833): 	at cfn.b(Unknown Source)
E/Babel   ( 6833): 	at cfn.a(Unknown Source)
E/Babel   ( 6833): 	at f.a(PG:188)
E/Babel   ( 6833): 	at ava.b(PG:143)
E/Babel   ( 6833): 	at bnr.run(PG:5415)
E/Babel   ( 6833): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 6833): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 6833): 	at java.lang.Thread.run(Thread.java:818)
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
E/UEI.SmartControl( 6852): Loading SETTINGS...
E/LgeQuickCoverOverlayWindow( 1411): updateNotificationData: count=3
D/UEI.SmartControl( 6852): Request IControl service: devices are loaded...
I/ActivityManager( 1026): Killing 6433:com.lge.appbox.client/u0a11 (adj 15): empty #17
I/QRemote ( 6295): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
,I/UEI.SmartControl( 6852): ------ IControl API: 11
I/UEI.SmartControl( 6852): Registering callback...
D/UEI.SmartControl( 6852): -- Open brand translation xml: brands_translations_ko
I/UEI.SmartControl( 6852): ------ IControl API: 19
I/UEI.SmartControl( 6852): Registering Services Ready callback...
I/UEI.SmartControl( 6852): Notify client services are ready...
I/QRemote ( 6295): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 6295): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 6295): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 6295): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 6295): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{782bd5b V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/UEI.SmartControl( 6852): ------ IControl API: 8
D/QRemote ( 6295): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 6295): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 6295): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 6295): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
,D/QRemote ( 6295): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6295): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
,I/UEI.SmartControl( 6852): Notify AllClients services are ready: 0
,D/UEI.SmartControl( 6852): -----service ready thread exits
I/QRemote ( 6295): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 6295): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 6295): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
W/libprocessgroup( 1026): failed to open /acct/uid_10011/pid_6433/cgroup.procs: No such file or directory
D/UEI.SmartControl( 6852): Internal service binding...
,D/QRemote ( 6295): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
W/ActivityManager( 1026): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/QRemote ( 6295): [RemoteControlManager.java:327:handleMessage()] oooooo 140510:retrieveDevices already complete. Do nothing
D/SyncManager( 1026): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.location.reporting, PERIODIC, currentRunTime 39838, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
V/QRemote ( 6295): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6295): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 6295): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/SyncManager( 1026): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.location.reporting, PERIODIC, currentRunTime 153095, reason: Periodic
D/QRemote ( 6295): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 6295): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6295): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 6295): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 6295): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1454701208853]
,D/QRemote ( 6295): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
W/ActivityManager( 1026): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,W/ActivityManager( 1026): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Gmail   ( 6896): getAccountsCursor
I/Gmail   ( 6896): Observing account changes for notifications
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/jxcore-log( 5997): Test app app.js loaded
I/jxcore-log( 5997): 
W/GAV2    ( 6896): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/chromium( 5997): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5997): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5997): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5997): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5997): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5997): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5997): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5997): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5997): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5997): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5997): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c7e5170 added. We now have 1 listener(s)
I/jxcore-log( 5997): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 5997): 
I/jxcore-log( 5997): TAP version 13
I/jxcore-log( 5997): 
I/jxcore-log( 5997): # setup
I/jxcore-log( 5997): 
,I/jxcore-log( 5997): # #generatePreambleAndBeacons empty keys to notify
I/jxcore-log( 5997): 
W/ActivityManager( 1026): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
V/QRemote ( 6295): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
W/Gmail   ( 6896): Sync started for account: account:61035162
,E/QRemote ( 6295): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6295): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 6295): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 6295): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 6295): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
,D/QRemote ( 6295): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 6295): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
I/Gmail   ( 6896): getAccountsCursor
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/Gmail   ( 6896): Error finding the version of the Email provider.....
E/Gmail   ( 6896): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6896): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 6896): 	at com.google.android.gm.EmailMigrationService.aU(SourceFile:1235)
E/Gmail   ( 6896): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:187)
E/Gmail   ( 6896): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6896): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 6896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 6896): We do not support migrating this version of the Email provider.
,I/jxcore-log( 5997): ok 1 should be equal
I/jxcore-log( 5997): 
I/jxcore-log( 5997): ok 2 should be equal
I/jxcore-log( 5997): 
I/jxcore-log( 5997): ok 3 should be equal
I/jxcore-log( 5997): 
I/jxcore-log( 5997): ok 4 should be equal
I/jxcore-log( 5997): 
I/jxcore-log( 5997): # teardown
I/jxcore-log( 5997): 
I/jxcore-log( 5997): # setup
I/jxcore-log( 5997): 
I/jxcore-log( 5997): # #generatePreambleAndBeacons multiple keys to notify
I/jxcore-log( 5997): 
I/art     ( 2135): Explicit concurrent mark sweep GC freed 42604(2MB) AllocSpace objects, 19(2MB) LOS objects, 50% free, 30MB/62MB, paused 775us total 43.522ms
I/art     ( 2135): WaitForGcToComplete blocked for 6.130ms for cause HeapTrim
,E/SQLiteLog( 6896): (283) recovered 1504 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
I/GAV2    ( 6454): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 5997): ok 5 should be equal
I/jxcore-log( 5997): 
I/jxcore-log( 5997): ok 6 should be equal
I/jxcore-log( 5997): 
I/jxcore-log( 5997): ok 7 should be equal
I/jxcore-log( 5997): 
I/jxcore-log( 5997): ok 8 should be equal
I/jxcore-log( 5997): 
I/jxcore-log( 5997): # teardown
I/jxcore-log( 5997): 
I/jxcore-log( 5997): # setup
I/jxcore-log( 5997): 
I/jxcore-log( 5997): # #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
I/jxcore-log( 5997): 
I/jxcore-log( 5997): ok 9 should throw
I/jxcore-log( 5997): 
,I/jxcore-log( 5997): # teardown
I/jxcore-log( 5997): 
I/jxcore-log( 5997): # setup
I/jxcore-log( 5997): 
I/jxcore-log( 5997): # #parseBeacons invalid expiration in beaconStreamWithPreAmble
I/jxcore-log( 5997): 
I/jxcore-log( 5997): ok 10 should throw
I/jxcore-log( 5997): 
,I/jxcore-log( 5997): # teardown
I/jxcore-log( 5997): 
I/jxcore-log( 5997): # setup
I/jxcore-log( 5997): 
I/jxcore-log( 5997): # #parseBeacons no beacons returns null
I/jxcore-log( 5997): 
I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/reminders
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/reminders without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 6896): notifyAccountChanged
I/Gmail   ( 6896): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 6896): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
E/ReminderSync( 2361): AuthError [T SyncAdapterThread-1:id=271:priority=5:group=main]
I/jxcore-log( 5997): ok 11 should be equal
I/jxcore-log( 5997): 
I/jxcore-log( 5997): # teardown
I/jxcore-log( 5997): 
I/Gmail   ( 6896): notifyAccountChanged
I/jxcore-log( 5997): # setup
I/jxcore-log( 5997): 
I/jxcore-log( 5997): # #parseBeacons invalid size for encryptedBeaconKeyId in beaconStreamWithPreAmble
I/jxcore-log( 5997): 
I/Gmail   ( 6896): calculateUnknownSyncRationalesAndPurgeInBackground: running
,D/SyncManager( 1026): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.gms.reminders, PERIODIC, currentRunTime 40002, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
I/Gmail   ( 6896): calculateUnknownSyncRationalesAndPurgeInBackground: running
D/SyncManager( 1026): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.gms.reminders, PERIODIC, currentRunTime 152334, reason: Periodic
I/jxcore-log( 5997): ok 12 should throw
I/jxcore-log( 5997): 
I/jxcore-log( 5997): # teardown
I/jxcore-log( 5997): 
I/jxcore-log( 5997): # setup
I/jxcore-log( 5997): 
I/jxcore-log( 5997): # #parseBeacons addressBookCallback fails decrypt
I/jxcore-log( 5997): 
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 6896): getAccountsCursor
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager( 1026): Start proc com.google.android.apps.docs for service com.google.android.apps.docs/.sync.syncadapter.DocsSyncAdapterService: pid=6949 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Gmail   ( 6896): getAccountsCursor
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 5997): ok 13 should be equal
I/jxcore-log( 5997): 
,I/jxcore-log( 5997): # teardown
I/jxcore-log( 5997): 
I/jxcore-log( 5997): # setup
I/jxcore-log( 5997): 
I/jxcore-log( 5997): # #parseBeacons addressBookCallback returns null for all
I/jxcore-log( 5997): 
I/art     ( 1026): Explicit concurrent mark sweep GC freed 21502(949KB) AllocSpace objects, 4(192KB) LOS objects, 33% free, 44MB/66MB, paused 1.195ms total 66.638ms
,I/Gmail   ( 6896): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 5310, normalSync: true
D/DocsApplication( 6949): Installing DEX configuration.
,D/DexInstaller( 6949): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
I/PackageInfoHelper( 6949): Provided clientMode=RELEASE, packageInfo=PackageInfo{33bcd911 com.google.android.apps.docs}
D/TAG     ( 6949): onCreate()
D/CrossAppStateProvider( 6949): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,W/ResourcesManager( 6896): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6896): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/JNIHelp ( 6896): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/jxcore-log( 5997): ok 14 (unnamed assert)
I/jxcore-log( 5997): 
I/jxcore-log( 5997): ok 15 should be equal
I/jxcore-log( 5997): 
I/jxcore-log( 5997): # teardown
I/jxcore-log( 5997): 
I/jxcore-log( 5997): # setup
I/jxcore-log( 5997): 
I/jxcore-log( 5997): # #parseBeacons addressBookCallback returns public key
I/jxcore-log( 5997): 
W/System  ( 6896): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[directory "."],nativeLibraryDirectories=[/vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6896): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gm, service: mail
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> mail without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1026): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1026): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1026): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1026): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1026): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,W/GLSActivity( 2135): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2135): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2135): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2135): 	at android.os.Binder.execTransact(Binder.java:446)
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
I/jxcore-log( 5997): ok 16 (unnamed assert)
I/jxcore-log( 5997): 
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 5997): ok 17 (unnamed assert)
I/jxcore-log( 5997): 
I/jxcore-log( 5997): # teardown
I/jxcore-log( 5997): 
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{782bd5b V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gm, service: mail
,I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> mail without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1026): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1026): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1026): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1026): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1026): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2135): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2135): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2135): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2135): 	at android.os.Binder.execTransact(Binder.java:446)
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
I/Gmail   ( 6896): notifyAccountChanged
I/Gmail   ( 6896): getAccountsCursor
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 6896): notifyAccountChanged
W/Gmail   ( 6896): Sync complete for account: account:61035162
I/Gmail   ( 6896): getAccountsCursor
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{782bd5b V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/SyncManager( 1026): failed sync operation thalitester@gmail.com u0 (com.google), gmail-ls, PERIODIC, currentRunTime 39899, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager( 1026): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), gmail-ls, PERIODIC, currentRunTime 151713, reason: Periodic
I/SyncAdapterService( 6625): Ignoring sync request for non-current account
,I/ActivityManager( 1026): Killing 6168:com.lge.formmanager/u0a26 (adj 15): empty #17
,W/BaseAppContext( 2361): Using Auth Proxy for data requests.
W/BaseAppContext( 2361): Using Auth Proxy for data requests.
W/libprocessgroup( 1026): failed to open /acct/uid_10026/pid_6168/cgroup.procs: No such file or directory
,W/BaseAppContext( 2361): Using Auth Proxy for data requests.
,W/BaseAppContext( 2361): Using Auth Proxy for data requests.
,W/BaseAppContext( 2361): Using Auth Proxy for data requests.
W/BaseAppContext( 2361): Using Auth Proxy for data requests.
,W/BaseAppContext( 2361): Using Auth Proxy for data requests.
,I/GoogleHttpClient( 5256): Falling back to old http client 0 java.lang.NoSuchMethodException: <init> [class android.content.Context, class java.lang.String, boolean, boolean]
,I/art     ( 2135): Explicit concurrent mark sweep GC freed 13561(705KB) AllocSpace objects, 5(720KB) LOS objects, 51% free, 30MB/62MB, paused 589us total 20.921ms
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.music, service: sj
,I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> sj without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1026): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1026): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1026): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1026): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1026): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,D/LgeQuickCoverNLService( 1411): onNotificationPosted
,W/GLSActivity( 2135): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2135): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2135): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2135): 	at android.os.Binder.execTransact(Binder.java:446)
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
W/MusicSyncAdapter( 5256): Sync failed due to an authentication issue.
D/SyncManager( 1026): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.music.MusicContent, PERIODIC, currentRunTime 40071, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager( 1026): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.music.MusicContent, PERIODIC, currentRunTime 153198, reason: Periodic
,D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{782bd5b V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/ActivityManager( 1026): Start proc com.google.android.videos for service com.google.android.videos/.store.SyncService: pid=6978 uid=10103 gids={50103, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5256): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5256): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5256): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5256): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,I/ActivityManager( 1026): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=7005 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
W/ResourcesManager( 6978): Asset path '/system/framework/com.google.widevine.software.drm.jar' does not exist or contains no resources.
,I/MusicLeanback( 5256): Conditions not met for autocaching.
I/MusicLeanback( 5256): Stop autocaching.
W/ResourcesManager( 7005): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7005): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 7005): VM with version 2.1.0 has multidex support
,I/MultiDex( 7005): install
I/MultiDex( 7005): VM has multidex support, MultiDex support library is disabled.
V/JNIHelp ( 7005): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 7005): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7005): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1315e90c: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7005): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 2135): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 2135): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 2361): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5256): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5256): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/cache
D/WearableService( 7005): callingUid 10005, callindPid: 7005
D/LocationInitializer( 2361): Restart initialization of location
,D/LgDataFeature( 6949): LgDataFeature() Constructor: none
D/LgDataFeature( 6949): LgDataFeature() Constructor Done, null
E/MDM     ( 1830): [85] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
D/WearableClient( 5256): WearableClientImpl.onPostInitHandler: done
D/WearableClient( 5256): WearableClientImpl.onPostInitHandler: done
E/GmsUtils( 5256): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,W/ArtDownloadService( 5256): Setting cache size 0
W/ArtDownloadService( 5256): Setting cache size 0
D/LgDataFeature( 6978): LgDataFeature() Constructor: none
D/LgDataFeature( 6978): LgDataFeature() Constructor Done, null
,W/GAV2    ( 6949): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/WifiStateMachine( 1026):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=27.7, 0.0, 0.0  rx=22.6 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1292702980] gl rssi=-60 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1026):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=27.7, 0.0, 0.0  rx=22.6 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1292702979] gl rssi=-60 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1026): doString: [SIGNAL_POLL]
,D/WifiService( 1026): acquireWifiLockLocked: WifiLock{SyncManager type=1 binder=android.os.BinderProxy@228a3d1d}
,D/libc-netbsd(  327): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  327): res_queryN name = ssl.gstatic.com, class = 1, type = 1
,D/libc-netbsd(  327): res_queryN name = ssl.gstatic.com succeed
,I/GAV4    ( 6625): Thread[GAThread,5,main]: No campaign data found.
,D/PlayMovies( 6978): PersistentCache.cleanup:103 Cache is below limit, no need to shrink: [size=0, limit=5242880]
,D/PlayMovies( 6978): TransferService.onCreate:52 creating transfer service
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.videos/files/Movies/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/AudioCapabilities( 6978): Unsupported mime audio/evrc
W/AudioCapabilities( 6978): Unsupported mime audio/qcelp
W/ContextImpl( 6978): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.videos/files/Movies
W/VideoCapabilities( 6978): Unrecognized profile 2130706433 for video/avc
,W/ResourcesManager( 2361): Asset path '/system/framework/com.google.widevine.software.drm.jar' does not exist or contains no resources.
,W/AudioCapabilities( 6978): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6978): Unsupported mime audio/qcelp
W/AudioCapabilities( 6978): Unsupported mime audio/evrc
I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.videos, service: oauth2:https://www.googleapis.com/auth/android_video https://www.googleapis.com/auth/youtube https://www.googleapis.com/auth/pos
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/android_video https://www.googleapis.com/auth/youtube https://www.googleapis.com/auth/pos without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/VideoCapabilities( 6978): Unsupported mime video/x-ms-wmv
W/VideoCapabilities( 6978): Unsupported mime video/divx
W/VideoCapabilities( 6978): Unsupported mime video/divx311
W/VideoCapabilities( 6978): Unsupported mime video/divx4
W/VideoCapabilities( 6978): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6978): Unsupported profile 4 for video/mp4v-es
,W/AudioCapabilities( 6978): Unsupported mime audio/eac3
W/AudioCapabilities( 6978): Unsupported mime audio/ac3
W/AudioCapabilities( 6978): Unsupported mime audio/g726
W/AudioCapabilities( 6978): Unsupported mime audio/wma-voice
W/AudioCapabilities( 6978): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6978): Unsupported mime audio/adpcm
W/VideoCapabilities( 6978): Unsupported mime video/theora
W/VideoCapabilities( 6978): Unsupported mime video/mjpg
,I/art     ( 1026): Explicit concurrent mark sweep GC freed 24132(1132KB) AllocSpace objects, 6(480KB) LOS objects, 33% free, 44MB/66MB, paused 1.337ms total 72.395ms
,V/NotificationService( 1026): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1026): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1026): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1026): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1026): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
E/PlayMovies( 6978): GmsAccountManagerWrapper.blockingGetAuthTokenInternal:100 Cannot get user auth
E/PlayMovies( 6978): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/PlayMovies( 6978): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/PlayMovies( 6978): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/PlayMovies( 6978): 	at com.google.android.videos.accounts.GmsAccountManagerWrapper.blockingGetAuthTokenInternal(GmsAccountManagerWrapper.java:85)
E/PlayMovies( 6978): 	at com.google.android.videos.accounts.AccountManagerWrapper.blockingGetAuthToken(AccountManagerWrapper.java:186)
E/PlayMovies( 6978): 	at com.google.android.videos.accounts.AccountManagerWrapper.blockingAuthenticate(AccountManagerWrapper.java:162)
E/PlayMovies( 6978): 	at com.google.android.videos.store.SyncService$SyncAdapter.onPerformSync(SyncService.java:225)
E/PlayMovies( 6978): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/LgeQuickCoverNLService( 1411): onNotificationPosted
D/SmartCoverUpdateMonitor( 1411): received broadcast com.lge.intent.action.NLDataPosted
,I/ActivityManager( 1026): Killing 6471:com.android.gallery3d/u0a27 (adj 15): empty #17
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
D/SyncManager( 1026): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.videos.sync, PERIODIC, currentRunTime 40083, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager( 1026): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.videos.sync, PERIODIC, currentRunTime 154769, reason: Periodic
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
,W/libprocessgroup( 1026): failed to open /acct/uid_10027/pid_6471/cgroup.procs: No such file or directory
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1411): updateNotificationData: count=3
D/QuickStatusbarLayout( 1411): Notification difference=198
I/ActivityManager( 1026): Killing 6583:com.lge.drmservice/u0a62 (adj 15): empty #17
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{782bd5b V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.docs, service: oauth2: https://www.googleapis.com/auth/drive
,I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/libprocessgroup( 1026): failed to open /acct/uid_10062/pid_6583/cgroup.procs: No such file or directory
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1026): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1026): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1026): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1026): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1026): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
,D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1411): updateNotificationData: count=3
E/Auth.Api.Credentials( 2361): [CredentialSyncAdapter] Unknown sync event.
W/GLSActivity( 2135): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2135): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2135): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2135): 	at android.os.Binder.execTransact(Binder.java:446)
,D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{782bd5b V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/PsynchoHelperImpl( 6949): Error fetching or saving configuration
W/PsynchoHelperImpl( 6949): java.io.IOException: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
W/PsynchoHelperImpl( 6949): 	at Op.a(ApiaryPsynchoConfigurationAccessor.java:145)
W/PsynchoHelperImpl( 6949): 	at Op.a(ApiaryPsynchoConfigurationAccessor.java:215)
W/PsynchoHelperImpl( 6949): 	at OQ.a(PsynchoHelperImpl.java:60)
W/PsynchoHelperImpl( 6949): 	at agr.a(DriveSpecificSyncManager.java:27)
W/PsynchoHelperImpl( 6949): 	at agO.a(LegacySyncManager.java:678)
W/PsynchoHelperImpl( 6949): 	at agO.b(LegacySyncManager.java:582)
W/PsynchoHelperImpl( 6949): 	at agO.a(LegacySyncManager.java:467)
W/PsynchoHelperImpl( 6949): 	at agO.a(LegacySyncManager.java:97)
W/PsynchoHelperImpl( 6949): 	at agQ.run(LegacySyncManager.java:419)
W/PsynchoHelperImpl( 6949): 	at ami.a(NetworkUtilitiesImpl.java:31)
W/PsynchoHelperImpl( 6949): 	at agP.run(LegacySyncManager.java:416)
W/PsynchoHelperImpl( 6949): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
W/PsynchoHelperImpl( 6949): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
W/PsynchoHelperImpl( 6949): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
W/PsynchoHelperImpl( 6949): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
W/PsynchoHelperImpl( 6949): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
W/PsynchoHelperImpl( 6949): 	at android.os.Binder.execTransact(Binder.java:446)
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.docs, service: writely
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> writely without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1026): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1026): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1026): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1026): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
,D/NotificationServiceEx( 1026): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2135): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2135): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2135): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2135): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1411): onNotificationPosted
E/HttpIssuerBase( 6949): Attempt to consume entity of HttpIssuer when no request is executing.
E/HttpIssuerBase( 6949): Attempt to close HttpIssuer when no request is executing.
E/HttpIssuerBase( 6949): java.io.IOException
E/HttpIssuerBase( 6949): 	at TG.b(HttpIssuerBase.java:188)
E/HttpIssuerBase( 6949): 	at Tj.b(DefaultAuthenticatedHttpIssuer.java:151)
E/HttpIssuerBase( 6949): 	at afE.a(AccountMetadataUpdater.java:227)
E/HttpIssuerBase( 6949): 	at afE.a(AccountMetadataUpdater.java:140)
E/HttpIssuerBase( 6949): 	at agO.a(LegacySyncManager.java:828)
E/HttpIssuerBase( 6949): 	at agO.b(LegacySyncManager.java:588)
E/HttpIssuerBase( 6949): 	at agO.a(LegacySyncManager.java:467)
E/HttpIssuerBase( 6949): 	at agO.a(LegacySyncManager.java:97)
E/HttpIssuerBase( 6949): 	at agQ.run(LegacySyncManager.java:419)
E/HttpIssuerBase( 6949): 	at ami.a(NetworkUtilitiesImpl.java:31)
E/HttpIssuerBase( 6949): 	at agP.run(LegacySyncManager.java:416)
D/SmartCoverUpdateMonitor( 1411): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1411): MSG_NOTIFICATION_POSTED
,D/SmartCoverUpdateMonitor( 1411): handleNotificationPosted(true)
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
E/SyncManager( 6949): AuthenticatorException
E/SyncManager( 6949): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/SyncManager( 6949): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/SyncManager( 6949): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/SyncManager( 6949): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/SyncManager( 6949): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/SyncManager( 6949): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  2
W/GAV2    ( 6949): SyncManager-thalitester@gmail.com: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
D/WifiService( 1026): releaseWifiLockLocked: WifiLock{SyncManager type=1 binder=android.os.BinderProxy@228a3d1d}
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1411): updateNotificationData: count=3
,D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{782bd5b V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/SyncManager( 1026): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.docs, PERIODIC, currentRunTime 40020, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
I/ActivityManager( 1026): Killing 6494:com.android.chrome/u0a57 (adj 15): empty #17
D/SyncManager( 1026): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.apps.docs, PERIODIC, currentRunTime 153415, reason: Periodic
I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/libprocessgroup( 1026): failed to open /acct/uid_10057/pid_6494/cgroup.procs: No such file or directory
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1026): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1026): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1026): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1026): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1026): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2135): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2135): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2135): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2135): 	at android.os.Binder.execTransact(Binder.java:446)
D/ContactsSyncAdapter( 2135): innerSync failed
D/ContactsSyncAdapter( 2135): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2135): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2135): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2135): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2135): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2135): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2135): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2135): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2135): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2135): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2135): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2135): 	at android.os.Binder.execTransact(Binder.java:446)
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
D/SyncManager( 1026): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 149359, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1411): updateNotificationData: count=3
,D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{782bd5b V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/ThermalEngine(  342): Thermal-Server: Thermal received msg from  override
,I/Thermal-Lib( 3099): Thermal-Lib-Client: Client request sent
,E/WifiStateMachine( 1026):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=23.3, 0.0, 0.0  rx=17.8 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:-1292699963] gl rssi=-61 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1026):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=23.3, 0.0, 0.0  rx=17.8 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1292699950] gl rssi=-61 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1026): doString: [SIGNAL_POLL]
D/serial_port( 6852): close(fd = 25)
,D/UEI.SmartControl( 6852): Internal timer expired: 1
D/UEI.SmartControl( 6852): unbind internal service
,I/UEI.SmartControl( 6852): Serial port is closed.
,I/ActivityManager( 1026): Killing 6522:com.lge.email/u0a23 (adj 15): empty #17
W/libprocessgroup( 1026): failed to open /acct/uid_10023/pid_6522/cgroup.procs: No such file or directory
,I/GAV2    ( 6896): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager( 1026): Killing 5205:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,W/libprocessgroup( 1026): failed to open /acct/uid_1000/pid_5205/cgroup.procs: No such file or directory
,I/GAV2    ( 6949): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager( 1026): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=7093 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager( 1026): RTC_WAKEUP set : Alarm{8e621aa type 0 when 1454701215592 com.android.vending} when 1454701215592
,D/Finsky  ( 7093): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/LgDataFeature( 7093): LgDataFeature() Constructor: none
D/LgDataFeature( 7093): LgDataFeature() Constructor Done, null
,D/Finsky  ( 7093): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/ActivityManager( 1026): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=7143 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/Settings( 7093): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7093): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ResourcesManager( 7143): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7143): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
E/WifiStateMachine( 1026):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=21.2, 0.0, 0.0  rx=16.9 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1292696935] gl rssi=-61 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1026):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=21.2, 0.0, 0.0  rx=16.9 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1292696934] gl rssi=-61 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1026): doString: [SIGNAL_POLL]
D/Finsky  ( 7093): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
V/DownloadManager( 3297): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
D/Finsky  ( 7093): [1] 2.run: Finished loading 1 libraries.
,V/DownloadManager( 3297): created cursor android.database.sqlite.SQLiteCursor@176e236b on behalf of 7093
D/Finsky  ( 7093): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/MultiDex( 7143): VM with version 2.1.0 has multidex support
I/MultiDex( 7143): install
I/MultiDex( 7143): VM has multidex support, MultiDex support library is disabled.
,D/Finsky  ( 7093): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
V/JNIHelp ( 7143): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,V/SIM_STK ( 1026): Menu title from STK is T-Mobile
W/ActivityThread( 7143): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7143): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1315e90c: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7143): Installed default security provider GmsCore_OpenSSL
D/GCM     ( 2135): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AuthorizationBluetoothService( 2135): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 2361): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
D/WearableService( 7005): callingUid 10005, callindPid: 7005
,E/MDM     ( 1830): [86] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
D/LocationInitializer( 2361): Restart initialization of location
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 2135): Explicit concurrent mark sweep GC freed 18073(1052KB) AllocSpace objects, 14(2016KB) LOS objects, 50% free, 30MB/62MB, paused 1.646ms total 57.229ms
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/Finsky  ( 7093): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7093): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7093): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 7093): [1] 5.onFinished: Scheduling replication attempt 2.
I/ActivityManager( 1026): Killing 6765:com.qualcomm.timeservice/1000 (adj 15): empty #17
,W/libprocessgroup( 1026): failed to open /acct/uid_1000/pid_6765/cgroup.procs: No such file or directory
,D/Finsky  ( 7093): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/AlarmManager( 1026): RTC_WAKEUP set : Alarm{23edcf3 type 0 when 1454701217194 com.android.vending} when 1454701217194
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 7093): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 7093): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/SIM_STK ( 1026): Menu title from STK is T-Mobile
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1026): Explicit concurrent mark sweep GC freed 33299(1472KB) AllocSpace objects, 8(640KB) LOS objects, 33% free, 44MB/66MB, paused 2.403ms total 160.666ms
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 7093): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 7093): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
D/Finsky  ( 7093): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7093): [1] DailyHygiene.reschedule: Scheduling new run in 28 minutes (failures=2)
,D/DeviceConnectionService( 1830): client connected with version: 7571000
,I/[SystemUI]LGPowerUI( 1465): onReceive = com.lge.android.intent.action.BATTERYEX
,I/[SystemUI]LGPowerUI( 1465): On Skip Timer : true
,D/LEDHandler( 1960): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1960): Battery Level Remaining: 100%
D/LEDHandler( 1960): Battery Temp: 292, mChargingStatus=5, mChargingStop=false
,D/KeyguardUpdateMonitor( 1465): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 292
I/[SystemUI]LGPowerUI( 1465): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController( 1026): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1465): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3990): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3990): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,D/HeadsetStateMachine( 6098): Disconnected process message: 10, size: 0
,W/Settings( 1026): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 1026): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/WifiStateMachine( 1026):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=10.6, 0.0, 0.0  rx=8.5 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1292693918] gl rssi=-61 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1026):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=10.6, 0.0, 0.0  rx=8.5 bcn=0 [on:0 tx:0 rx:0 period:14] from screen [on:0 period:-1292693904] gl rssi=-61 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1026): doString: [SIGNAL_POLL]
I/InputReader( 1026): Reconfiguring input devices.  changes=0x00000010
,I/[SystemUI]QPairHandler( 1465): onReceive = android.intent.action.PACKAGE_CHANGED
D/SplitUIService( 1882): replaced split : contains_com.google.android.talk / true
,I/ActivityManager( 1026): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7219 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/[LGHome]EVENT( 2082): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000010 (has extras) }
,I/[SystemUI]QSlideListController( 1465): onReceive = android.intent.action.PACKAGE_CHANGED
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1465): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.talk
D/SplitUIManager( 1882): split_name #11 / not available #0
I/SplitUIService( 1882): split app #11
D/administrator( 1026): Handling package changes for user 0
,W/ResourcesManager( 2082): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/InputReader( 1026): Reconfiguring input devices.  changes=0x00000010
,I/[SystemUI]QPairHandler( 1465): onReceive = android.intent.action.PACKAGE_CHANGED
I/[SystemUI]QSlideListController( 1465): onReceive = android.intent.action.PACKAGE_CHANGED
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1465): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.videos
,I/[LGHome]EVENT( 2082): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.videos flg=0x4000010 (has extras) }
I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/AppUp4:AppBoxCP( 7219): onCreate
W/AppUp4:DB( 7219):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7219):  setFingerPrint start
I/AppUp4:DB( 7219):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/AppUp4:DB( 7219):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7219):  SDK version = 21
I/AppUp4:DB( 7219):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 7219): AppBoxApplication onCreate()
I/NotificationService( 1026): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService( 1026): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000010 (has extras) }
I/AppUp4:CustModeStarterReceiver( 7219): onReceive
W/ResourcesManager( 1026): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/administrator( 1026): Handling package changes for user 0
,I/NotificationService( 1026): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService( 1026): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.videos flg=0x4000010 (has extras) }
D/LgDataFeature( 7219): LgDataFeature() Constructor: none
,D/LgDataFeature( 7219): LgDataFeature() Constructor Done, null
D/AppUp4:CustFacade( 7219): Context : android.app.ReceiverRestrictedContext@283f1ce4
D/AppUp4:CustFacade( 7219): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7219): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7219): begin check event
I/AppUp4:CustModeStarterReceiver( 7219): Event For Nothing, skip.
W/ResourcesManager( 1026): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourceType( 1026): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/ActivityManager( 1026): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7254 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/ActivityManager( 1026): Killing 6802:com.android.calendar/u0a13 (adj 15): empty #17
W/libprocessgroup( 1026): failed to open /acct/uid_10013/pid_6802/cgroup.procs: No such file or directory
,I/[LGHome]EVENT( 2082): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
W/ResourceType( 1026): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/[LGHome]EVENT( 2082): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
W/ResourcesManager( 7254): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7254): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7254): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,W/ResourcesManager( 7254): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7254): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 7254): BUILD Country: EU
,I/SystemConfig( 7254): BUILD Operator: OPEN
,I/ActivityManager( 1026): Killing 6724:com.lge.clock/u0a10 (adj 15): empty #17
,W/libprocessgroup( 1026): failed to open /acct/uid_10010/pid_6724/cgroup.procs: No such file or directory
,I/SystemConfig( 7254): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7254): existFile = false
I/SystemConfig( 7254): canReadFile = false
,I/SystemConfig( 7254): systemFeature RCS result false
,D/SystemConfig( 7254): refreshRcsSupport() :false
,I/ActivityManager( 1026): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7281 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/art     (  352): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 455us total 25.012ms
,I/art     (  352): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 418us total 21.586ms
,I/art     (  352): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 584us total 18.205ms
,W/ResourcesManager( 7281): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7281): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7281): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 7281): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/AppConfig( 7281): Total System Memory = 2995761152
,D/SystemHelper( 7281): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager( 1026): Killing 6606:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,W/libprocessgroup( 1026): failed to open /acct/uid_10085/pid_6606/cgroup.procs: No such file or directory
,I/ActivityManager( 1026): Killing 6741:com.google.android.syncadapters.calendar/u0a69 (adj 15): empty #17
,I/UpdateIcingCorporaServi( 4264): Updating corpora: APPS=com.google.android.talk, CONTACTS=MAYBE
V/SIM_STK ( 1026): Menu title from STK is T-Mobile
,W/libprocessgroup( 1026): failed to open /acct/uid_10069/pid_6741/cgroup.procs: No such file or directory
,W/ResourcesManager( 4264): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/UpdateIcingCorporaServi( 4264): UpdateCorporaTask done [took 81 ms] updated apps [took 81 ms] 
,I/ActivityManager( 1026): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7319 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,I/LockScreenSettings( 7319): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7319): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,D/LockScreenSettings( 7319): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7319): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7319): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7319): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
D/LockScreenSettings( 7319): Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,I/ActivityManager( 1026): Killing 6833:com.google.android.talk/u0a72 (adj 15): empty #17
,W/libprocessgroup( 1026): failed to open /acct/uid_10072/pid_6833/cgroup.procs: No such file or directory
,D/PackageBroadcastService( 2361): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.talk
I/AppUp4:CustModeStarterReceiver( 7219): onReceive
,I/PeopleContactsSync( 2361): CP2 sync disabled
D/AppUp4:CustFacade( 7219): Context : android.app.ReceiverRestrictedContext@283f1ce4
D/AppUp4:CustFacade( 7219): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7219): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7219): begin check event
I/AppUp4:CustModeStarterReceiver( 7219): Event For Nothing, skip.
I/UpdateIcingCorporaServi( 4264): Updating corpora: APPS=com.google.android.videos, CONTACTS=MAYBE
,D/LockScreenSettings( 7319): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7319): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7319): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7319): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7319): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
D/LockScreenSettings( 7319): Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,D/PackageBroadcastService( 2361): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.videos
,V/SIM_STK ( 1026): Menu title from STK is T-Mobile
,I/PeopleContactsSync( 2361): CP2 sync disabled
,I/UpdateIcingCorporaServi( 4264): UpdateCorporaTask done [took 104 ms] updated apps [took 104 ms] 
,E/WifiStateMachine( 1026):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=5.8, 0.0, 0.0  rx=4.7 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:-1292690881] gl rssi=-60 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1026):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=5.8, 0.0, 0.0  rx=4.7 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1292690877] gl rssi=-60 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1026): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1026):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=3.4, 0.0, 0.0  rx=2.9 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1292687864] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1026):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=3.4, 0.0, 0.0  rx=2.9 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1292687853] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1026): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1026): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1026): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1026): tsOffsetIs: Apps: 138054499743; DSPS: 4665164; Offset : -4330549876
,E/WifiStateMachine( 1026):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=1.7, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1292684833] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1026):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=1.7, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1292684830] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1026): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1026):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=1.3, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1292681807] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1026):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=1.3, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1292681797] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1026): doString: [SIGNAL_POLL]
,V/AlarmManager( 1026): ELAPSED_WAKEUP set : Alarm{2f622e8d type 2 when 145108 android} when 145108
,E/WifiStateMachine( 1026):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1292678777] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1026):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1292678774] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1026): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1026):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1292675758] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1026):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1292675747] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1026): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1026):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1026):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,E/WifiStateMachine( 1026):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1026):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1026):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1026):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1026):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1292672737] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1026):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1292672735] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1026): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1026):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1292669713] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1026):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1292669710] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1026): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1026):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1292666688] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1026):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1292666678] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1026): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1026): tsOffsetIs: Apps: 158056557808; DSPS: 5320592; Offset : -4330569117
,E/WifiStateMachine( 1026):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1292663655] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1026):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1292663652] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1026): doString: [SIGNAL_POLL]
,V/AlarmManager( 1026): RTC_WAKEUP set : Alarm{1478a966 type 0 when 1454701237427 com.android.vending} when 1454701237427
,V/SIM_STK ( 1026): Menu title from STK is T-Mobile
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7093): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 7093): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7093): [1] 5.onFinished: Scheduling replication attempt 3.
E/WifiStateMachine( 1026):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1292660625] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1026):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1292660624] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1026): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1026):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1292657613] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1026):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1292657601] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1026): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1026):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1292654581] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1026):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1292654578] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1026): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
,I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
,E/WifiStateMachine( 1026):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1292651556] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1026):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1292651553] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1026): doString: [SIGNAL_POLL]
,D/PowerManagerServiceEx( 1026): acquireWakeLockInternal: lock=631714865, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1026
,V/AlarmManager( 1026): ELAPSED_WAKEUP set : Alarm{2221f1d8 type 2 when 175840 android} when 175840
D/[Concierge]Service( 2588): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1026): releaseWakeLockInternal: lock=631714865 [*alarm*], flags=0x0
,E/WifiStateMachine( 1026):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:2999] from screen [on:0 period:-1292648530] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1026):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:-1292648530] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1026): doString: [SIGNAL_POLL]
,I/BooksSync( 6454): Starting books sync
,D/BooksSync( 6454): started syncMyEbooks
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
,I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1026): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1026): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1026): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1026): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1026): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2135): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2135): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2135): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2135): 	at android.os.Binder.execTransact(Binder.java:446)
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
,D/ContactsSyncAdapter( 2135): innerSync failed
D/ContactsSyncAdapter( 2135): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2135): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2135): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2135): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2135): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2135): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2135): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2135): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2135): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2135): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2135): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2135): 	at android.os.Binder.execTransact(Binder.java:446)
,D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
W/ResourcesManager( 1411): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1411): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
,E/LgeQuickCoverOverlayWindow( 1411): updateNotificationData: count=3
I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{782bd5b V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SyncManager( 1026): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 149359, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager( 1026): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 241422, reason: 10019
V/NotificationService( 1026): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1026): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1026): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1026): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1026): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,W/GLSActivity( 2135): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2135): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2135): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2135): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1411): onNotificationPosted
E/BooksAccountManager( 6454): Authentication error
E/BooksAccountManager( 6454): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6454): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6454): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6454): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6454): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6454): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6454): null auth token
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
,D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1411): updateNotificationData: count=3
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{782bd5b V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6454): Error response from books API: {
W/ApiaryClient( 6454):  "error": {
W/ApiaryClient( 6454):   "errors": [
W/ApiaryClient( 6454):    {
W/ApiaryClient( 6454):     "domain": "global",
W/ApiaryClient( 6454):     "reason": "required",
W/ApiaryClient( 6454):     "message": "Login Required",
W/ApiaryClient( 6454):     "locationType": "header",
W/ApiaryClient( 6454):     "location": "Authorization"
W/ApiaryClient( 6454):    }
W/ApiaryClient( 6454):   ],
W/ApiaryClient( 6454):   "code": 401,
W/ApiaryClient( 6454):   "message": "Login Required"
W/ApiaryClient( 6454):  }
W/ApiaryClient( 6454): }
W/ApiaryClient( 6454): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6454): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=300911201684242798&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6454): Headers:
W/ApiaryClient( 6454): accept-encoding: [gzip]
W/ApiaryClient( 6454): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6454): gdata-version: 2
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1026): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1026): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1026): LED remove() : mLights=0|com.google.android.gms|1|null|10005
,D/NotificationServiceEx( 1026): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1026): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/GLSActivity( 2135): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2135): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2135): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2135): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6454): Authentication error
E/BooksAccountManager( 6454): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6454): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6454): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6454): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6454): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6454): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6454): null auth token
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{782bd5b V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6454): Error response from books API: {
W/ApiaryClient( 6454):  "error": {
W/ApiaryClient( 6454):   "errors": [
W/ApiaryClient( 6454):    {
W/ApiaryClient( 6454):     "domain": "global",
W/ApiaryClient( 6454):     "reason": "required",
W/ApiaryClient( 6454):     "message": "Login Required",
W/ApiaryClient( 6454):     "locationType": "header",
W/ApiaryClient( 6454):     "location": "Authorization"
W/ApiaryClient( 6454):    }
W/ApiaryClient( 6454):   ],
W/ApiaryClient( 6454):   "code": 401,
W/ApiaryClient( 6454):   "message": "Login Required"
W/ApiaryClient( 6454):  }
W/ApiaryClient( 6454): }
,W/ApiaryClient( 6454): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6454): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=300911201684242798&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6454): Headers:
W/ApiaryClient( 6454): accept-encoding: [gzip]
W/ApiaryClient( 6454): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6454): gdata-version: 2
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1026): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1026): tsOffsetIs: Apps: 178058319102; DSPS: 5976009; Offset : -4330547324
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1026): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1026): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1026): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1026): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1026): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/GLSActivity( 2135): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2135): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2135): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2135): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6454): Authentication error
E/BooksAccountManager( 6454): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6454): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6454): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6454): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6454): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6454): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6454): null auth token
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{782bd5b V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6454): Error response from books API: {
W/ApiaryClient( 6454):  "error": {
W/ApiaryClient( 6454):   "errors": [
W/ApiaryClient( 6454):    {
W/ApiaryClient( 6454):     "domain": "global",
W/ApiaryClient( 6454):     "reason": "required",
W/ApiaryClient( 6454):     "message": "Login Required",
W/ApiaryClient( 6454):     "locationType": "header",
W/ApiaryClient( 6454):     "location": "Authorization"
W/ApiaryClient( 6454):    }
W/ApiaryClient( 6454):   ],
W/ApiaryClient( 6454):   "code": 401,
W/ApiaryClient( 6454):   "message": "Login Required"
W/ApiaryClient( 6454):  }
W/ApiaryClient( 6454): }
,W/ApiaryClient( 6454): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6454): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=300911201684242798&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6454): Headers:
W/ApiaryClient( 6454): accept-encoding: [gzip]
W/ApiaryClient( 6454): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6454): gdata-version: 2
,E/WifiStateMachine( 1026):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1292645514] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1026):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1292645511] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1026): doString: [SIGNAL_POLL]
,E/BooksSync( 6454): Soft error: 
E/BooksSync( 6454): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6454): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=300911201684242798&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6454): Headers:
E/BooksSync( 6454): accept-encoding: [gzip]
E/BooksSync( 6454): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6454): gdata-version: 2
E/BooksSync( 6454): 
E/BooksSync( 6454): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6454): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6454): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6454): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6454): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6454): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6454): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6454): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6454): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6454): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6454): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6454): {
E/BooksSync( 6454):  "error": {
E/BooksSync( 6454):   "errors": [
E/BooksSync( 6454):    {
E/BooksSync( 6454):     "domain": "global",
E/BooksSync( 6454):     "reason": "required",
E/BooksSync( 6454):     "message": "Login Required",
E/BooksSync( 6454):     "locationType": "header",
E/BooksSync( 6454):     "location": "Authorization"
E/BooksSync( 6454):    }
E/BooksSync( 6454):   ],
E/BooksSync( 6454):   "code": 401,
E/BooksSync( 6454):   "message": "Login Required"
E/BooksSync( 6454):  }
E/BooksSync( 6454): }
E/BooksSync( 6454): 
E/BooksSync( 6454): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6454): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6454): 	... 8 more
,E/BooksSync( 6454): Sync error
E/BooksSync( 6454): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6454): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=300911201684242798&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6454): Headers:
E/BooksSync( 6454): accept-encoding: [gzip]
E/BooksSync( 6454): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6454): gdata-version: 2
E/BooksSync( 6454): 
E/BooksSync( 6454): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6454): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6454): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6454): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6454): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6454): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6454): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6454): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6454): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6454): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6454): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6454): {
E/BooksSync( 6454):  "error": {
E/BooksSync( 6454):   "errors": [
E/BooksSync( 6454):    {
E/BooksSync( 6454):     "domain": "global",
E/BooksSync( 6454):     "reason": "required",
E/BooksSync( 6454):     "message": "Login Required",
E/BooksSync( 6454):     "locationType": "header",
E/BooksSync( 6454):     "location": "Authorization"
E/BooksSync( 6454):    }
E/BooksSync( 6454):   ],
E/BooksSync( 6454):   "code": 401,
E/BooksSync( 6454):   "message": "Login Required"
E/BooksSync( 6454):  }
E/BooksSync( 6454): }
E/BooksSync( 6454): 
E/BooksSync( 6454): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6454): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6454): 	... 8 more
I/BooksSync( 6454): Finished books sync
D/SyncManager( 1026): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 151605, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/WifiStateMachine( 1026):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=5.3, 0.0, 0.0  rx=3.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1292642491] gl rssi=-61 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1026):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=5.3, 0.0, 0.0  rx=3.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1292642488] gl rssi=-61 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1026): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1026):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=2.7, 0.0, 0.0  rx=1.9 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1292639465] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1026):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=2.7, 0.0, 0.0  rx=1.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1292639462] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1026): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1026):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=1.8, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1292636437] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1026):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=1.8, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1292636428] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1026): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1026):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1292633409] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1026):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1292633397] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1026): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1026):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1292630373] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1026):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1292630370] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1026): doString: [SIGNAL_POLL]
,V/AlarmManager( 1026): RTC_WAKEUP set : Alarm{21d3f780 type 0 when 1454701270445 com.android.vending} when 1454701270445
,V/SIM_STK ( 1026): Menu title from STK is T-Mobile
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1026): Explicit concurrent mark sweep GC freed 53596(2MB) AllocSpace objects, 5(592KB) LOS objects, 33% free, 44MB/66MB, paused 2.182ms total 100.002ms
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7093): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7093): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7093): [1] 5.onFinished: Scheduling replication attempt 4.
,E/WifiStateMachine( 1026):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1292627354] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1026):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1292627351] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1026): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1026): tsOffsetIs: Apps: 198061225866; DSPS: 6631465; Offset : -4330570222
,E/WifiStateMachine( 1026):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1292624326] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1026):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1292624323] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1026): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1026):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1292621299] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1026):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1292621290] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1026): doString: [SIGNAL_POLL]
,V/AlarmManager( 1026): ELAPSED_WAKEUP set : Alarm{1ac2de62 type 2 when 206113 android} when 206113
,E/WifiStateMachine( 1026):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1292618268] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1026):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1292618257] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1026): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1026):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1292615235] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1026):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:20] from screen [on:0 period:-1292615215] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1026): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1026):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1292612204] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1026):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1292612201] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1026): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1026):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1292609174] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1026):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1292609171] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1026): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1026): tsOffsetIs: Apps: 218062868983; DSPS: 7286878; Offset : -4330544615
,E/WifiStateMachine( 1026):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1292606145] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1026):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1292606142] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1026): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1026):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1292603117] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1026):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1292603107] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1026): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1026):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1292600088] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1026):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1292600087] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1026): doString: [SIGNAL_POLL]
,V/AlarmManager( 1026): ELAPSED_WAKEUP set : Alarm{2686bbf3 type 2 when 208362 android} when 208362
,V/AlarmManager( 1026): RTC_WAKEUP set : Alarm{3f55b29 type 0 when 1454701305387 com.android.vending} when 1454701305387
,V/SIM_STK ( 1026): Menu title from STK is T-Mobile
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7093): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7093): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 7093): [1] 5.onFinished: Scheduling replication attempt 5.
E/WifiStateMachine( 1026):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:-1292597073] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1026):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1292597070] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1026): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1026):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1292594051] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1026):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1292594048] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1026): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
,E/WifiStateMachine( 1026):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1292591024] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1026):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1292591021] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1026): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1026):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1292587996] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1026):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1292587993] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1026): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1026): tsOffsetIs: Apps: 238064897934; DSPS: 7942305; Offset : -4330560263
,E/WifiStateMachine( 1026):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1292584970] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1026):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1292584968] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1026): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1026):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1292581953] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1026):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1292581950] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1026): doString: [SIGNAL_POLL]
,D/PowerManagerServiceEx( 1026): acquireWakeLockInternal: lock=631714865, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1026
,V/AlarmManager( 1026): ELAPSED_WAKEUP set : Alarm{2fd687e3 type 2 when 243856 android} when 243856
D/[Concierge]Service( 2588): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1026): releaseWakeLockInternal: lock=631714865 [*alarm*], flags=0x0
,I/BooksSync( 6454): Starting books sync
,D/BooksSync( 6454): started syncMyEbooks
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1026): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1026): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1026): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1026): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1026): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
,W/GLSActivity( 2135): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2135): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2135): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2135): 	at android.os.Binder.execTransact(Binder.java:446)
,D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{782bd5b V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
E/BooksAccountManager( 6454): Authentication error
E/BooksAccountManager( 6454): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6454): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6454): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6454): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6454): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6454): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6454): null auth token
W/ApiaryClient( 6454): Error response from books API: {
W/ApiaryClient( 6454):  "error": {
W/ApiaryClient( 6454):   "errors": [
W/ApiaryClient( 6454):    {
W/ApiaryClient( 6454):     "domain": "global",
W/ApiaryClient( 6454):     "reason": "required",
W/ApiaryClient( 6454):     "message": "Login Required",
W/ApiaryClient( 6454):     "locationType": "header",
W/ApiaryClient( 6454):     "location": "Authorization"
W/ApiaryClient( 6454):    }
W/ApiaryClient( 6454):   ],
W/ApiaryClient( 6454):   "code": 401,
W/ApiaryClient( 6454):   "message": "Login Required"
W/ApiaryClient( 6454):  }
W/ApiaryClient( 6454): }
,W/ApiaryClient( 6454): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6454): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2113905949709680237&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6454): Headers:
W/ApiaryClient( 6454): accept-encoding: [gzip]
W/ApiaryClient( 6454): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6454): gdata-version: 2
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1026): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1026): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1026): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1026): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1026): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
,D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1411): updateNotificationData: count=3
W/GLSActivity( 2135): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2135): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2135): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2135): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6454): Authentication error
E/BooksAccountManager( 6454): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6454): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6454): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6454): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6454): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6454): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6454): null auth token
,D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{782bd5b V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6454): Error response from books API: {
W/ApiaryClient( 6454):  "error": {
W/ApiaryClient( 6454):   "errors": [
W/ApiaryClient( 6454):    {
W/ApiaryClient( 6454):     "domain": "global",
W/ApiaryClient( 6454):     "reason": "required",
W/ApiaryClient( 6454):     "message": "Login Required",
W/ApiaryClient( 6454):     "locationType": "header",
W/ApiaryClient( 6454):     "location": "Authorization"
W/ApiaryClient( 6454):    }
W/ApiaryClient( 6454):   ],
W/ApiaryClient( 6454):   "code": 401,
W/ApiaryClient( 6454):   "message": "Login Required"
W/ApiaryClient( 6454):  }
W/ApiaryClient( 6454): }
W/ApiaryClient( 6454): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6454): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2113905949709680237&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6454): Headers:
W/ApiaryClient( 6454): accept-encoding: [gzip]
W/ApiaryClient( 6454): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6454): gdata-version: 2
,E/WifiStateMachine( 1026):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1292578924] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1026):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1292578923] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1026): doString: [SIGNAL_POLL]
,I/jxcore-log( 5997): # setup
I/jxcore-log( 5997): 
,I/jxcore-log( 5997): # multiplex can send data
I/jxcore-log( 5997): 
,I/jxcore-log( 5997): ok 18 String should be length:200
I/jxcore-log( 5997): 
,I/jxcore-log( 5997): # teardown
I/jxcore-log( 5997): 
I/jxcore-log( 5997): # setup
I/jxcore-log( 5997): 
,I/jxcore-log( 5997): # enqueue and run in order
I/jxcore-log( 5997): 
,I/jxcore-log( 5997): ok 19 firstPromise setTimeout
I/jxcore-log( 5997): 
,I/jxcore-log( 5997): ok 20 firstPromise result
I/jxcore-log( 5997): 
,I/jxcore-log( 5997): ok 21 firstPromise testValue
I/jxcore-log( 5997): 
I/jxcore-log( 5997): ok 22 secondPromise setTimeout
I/jxcore-log( 5997): 
,I/jxcore-log( 5997): ok 23 secondPromise result
I/jxcore-log( 5997): 
I/jxcore-log( 5997): ok 24 secondPromise testValue
I/jxcore-log( 5997): 
I/jxcore-log( 5997): ok 25 thirdPromise in promise
I/jxcore-log( 5997): 
I/jxcore-log( 5997): ok 26 thirdPromise result
I/jxcore-log( 5997): 
I/jxcore-log( 5997): ok 27 thirdPromise testValue
I/jxcore-log( 5997): 
I/jxcore-log( 5997): # teardown
I/jxcore-log( 5997): 
,I/jxcore-log( 5997): # setup
I/jxcore-log( 5997): 
,I/jxcore-log( 5997): # basic
I/jxcore-log( 5997): 
,I/jxcore-log( 5997): ok 28 sane
I/jxcore-log( 5997): 
,I/jxcore-log( 5997): # teardown
I/jxcore-log( 5997): 
I/jxcore-log( 5997): # setup
I/jxcore-log( 5997): 
,I/jxcore-log( 5997): # another
I/jxcore-log( 5997): 
,I/jxcore-log( 5997): ok 29 sane
I/jxcore-log( 5997): 
,I/jxcore-log( 5997): # teardown
I/jxcore-log( 5997): 
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 5997): # setup
I/jxcore-log( 5997): 
,I/jxcore-log( 5997): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 5997): 
,I/art     ( 2135): Explicit concurrent mark sweep GC freed 34022(2MB) AllocSpace objects, 14(2016KB) LOS objects, 50% free, 30MB/62MB, paused 8.485ms total 111.926ms
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/jxcore-log( 5997): ok 30 should be equal
I/jxcore-log( 5997): 
,I/jxcore-log( 5997): ok 31 null
I/jxcore-log( 5997): 
,V/NotificationService( 1026): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1026): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1026): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1026): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1026): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/GLSActivity( 2135): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2135): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2135): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2135): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6454): Authentication error
E/BooksAccountManager( 6454): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6454): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6454): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6454): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6454): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6454): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6454): null auth token
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1411): updateNotificationData: count=3
,I/jxcore-log( 5997): ok 32 (unnamed assert)
I/jxcore-log( 5997): 
I/jxcore-log( 5997): ok 33 should be equal
I/jxcore-log( 5997): 
I/jxcore-log( 5997): ok 34 should not throw
I/jxcore-log( 5997): 
,I/jxcore-log( 5997): # teardown
I/jxcore-log( 5997): 
,D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{782bd5b V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/jxcore-log( 5997): # setup
I/jxcore-log( 5997): 
,W/ApiaryClient( 6454): Error response from books API: {
W/ApiaryClient( 6454):  "error": {
W/ApiaryClient( 6454):   "errors": [
W/ApiaryClient( 6454):    {
W/ApiaryClient( 6454):     "domain": "global",
W/ApiaryClient( 6454):     "reason": "required",
W/ApiaryClient( 6454):     "message": "Login Required",
W/ApiaryClient( 6454):     "locationType": "header",
W/ApiaryClient( 6454):     "location": "Authorization"
W/ApiaryClient( 6454):    }
W/ApiaryClient( 6454):   ],
W/ApiaryClient( 6454):   "code": 401,
W/ApiaryClient( 6454):   "message": "Login Required"
W/ApiaryClient( 6454):  }
W/ApiaryClient( 6454): }
,W/ApiaryClient( 6454): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6454): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2113905949709680237&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6454): Headers:
W/ApiaryClient( 6454): accept-encoding: [gzip]
W/ApiaryClient( 6454): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6454): gdata-version: 2
,I/jxcore-log( 5997): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 5997): 
,I/jxcore-log( 5997): ok 35 (unnamed assert)
I/jxcore-log( 5997): 
,I/jxcore-log( 5997): ok 36 (unnamed assert)
I/jxcore-log( 5997): 
,I/jxcore-log( 5997): ok 37 should not throw
I/jxcore-log( 5997): 
,I/jxcore-log( 5997): ok 38 should be equal
I/jxcore-log( 5997): 
,I/jxcore-log( 5997): ok 39 should be equal
I/jxcore-log( 5997): 
,I/jxcore-log( 5997): # teardown
I/jxcore-log( 5997): 
I/jxcore-log( 5997): # setup
I/jxcore-log( 5997): 
,I/jxcore-log( 5997): # failed to extract public key because of corrupt pkcs12 file,
I/jxcore-log( 5997): 
,I/jxcore-log( 5997): ok 40 should be equal
I/jxcore-log( 5997): 
,I/jxcore-log( 5997): # teardown
I/jxcore-log( 5997): 
I/jxcore-log( 5997): # setup
I/jxcore-log( 5997): 
,E/BooksSync( 6454): Soft error: 
E/BooksSync( 6454): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6454): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2113905949709680237&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6454): Headers:
E/BooksSync( 6454): accept-encoding: [gzip]
E/BooksSync( 6454): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6454): gdata-version: 2
E/BooksSync( 6454): 
E/BooksSync( 6454): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6454): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6454): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6454): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6454): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6454): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6454): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6454): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6454): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6454): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6454): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6454): {
E/BooksSync( 6454):  "error": {
E/BooksSync( 6454):   "errors": [
E/BooksSync( 6454):    {
E/BooksSync( 6454):     "domain": "global",
E/BooksSync( 6454):     "reason": "required",
E/BooksSync( 6454):     "message": "Login Required",
E/BooksSync( 6454):     "locationType": "header",
E/BooksSync( 6454):     "location": "Authorization"
E/BooksSync( 6454):    }
E/BooksSync( 6454):   ],
E/BooksSync( 6454):   "code": 401,
E/BooksSync( 6454):   "message": "Login Required"
E/BooksSync( 6454):  }
E/BooksSync( 6454): }
E/BooksSync( 6454): 
E/BooksSync( 6454): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6454): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6454): 	... 8 more
,E/BooksSync( 6454): Sync error
E/BooksSync( 6454): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6454): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2113905949709680237&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6454): Headers:
E/BooksSync( 6454): accept-encoding: [gzip]
E/BooksSync( 6454): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6454): gdata-version: 2
E/BooksSync( 6454): 
E/BooksSync( 6454): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6454): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6454): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6454): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6454): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6454): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6454): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6454): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6454): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6454): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6454): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6454): {
E/BooksSync( 6454):  "error": {
E/BooksSync( 6454):   "errors": [
E/BooksSync( 6454):    {
E/BooksSync( 6454):     "domain": "global",
E/BooksSync( 6454):     "reason": "required",
E/BooksSync( 6454):     "message": "Login Required",
E/BooksSync( 6454):     "locationType": "header",
E/BooksSync( 6454):     "location": "Authorization"
E/BooksSync( 6454):    }
E/BooksSync( 6454):   ],
E/BooksSync( 6454):   "code": 401,
E/BooksSync( 6454):   "message": "Login Required"
E/BooksSync( 6454):  }
E/BooksSync( 6454): }
E/BooksSync( 6454): 
E/BooksSync( 6454): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6454): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6454): 	... 8 more
I/BooksSync( 6454): Finished books sync
D/SyncManager( 1026): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 243856, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/WifiStateMachine( 1026):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=7.2, 0.0, 0.0  rx=5.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1292575912] gl rssi=-60 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1026):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=7.2, 0.0, 0.0  rx=5.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1292575909] gl rssi=-60 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1026): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1026):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=20.6, 0.0, 0.0  rx=18.9 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1292572889] gl rssi=-61 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1026):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=20.6, 0.0, 0.0  rx=18.9 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1292572877] gl rssi=-61 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1026): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1026):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=10.3, 0.0, 0.0  rx=9.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1292569855] gl rssi=-61 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1026):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=10.3, 0.0, 0.0  rx=9.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1292569852] gl rssi=-61 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1026): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1026):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=5.2, 0.0, 0.0  rx=4.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1292566827] gl rssi=-61 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1026):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=5.2, 0.0, 0.0  rx=4.7 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1292566817] gl rssi=-61 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,D/WifiNative-wlan0( 1026): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1026): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1026): tsOffsetIs: Apps: 258066309541; DSPS: 8597711; Offset : -4330552361
,V/AlarmManager( 1026): RTC_WAKEUP set : Alarm{3cb91eca type 0 when 1454701336099 com.android.vending} when 1454701336099
,V/SIM_STK ( 1026): Menu title from STK is T-Mobile
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7093): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7093): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 7093): [1] 5.onFinished: Giving up after 6 failures.
,E/WifiStateMachine( 1026):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=2.6, 0.0, 0.0  rx=2.4 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1292563794] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1026):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=2.6, 0.0, 0.0  rx=2.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1292563791] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1026): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1026):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=1.3, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1292560767] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1026):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=1.3, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:8] from screen [on:0 period:-1292560759] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1026): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1026):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1292557738] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1026):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1292557725] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1026): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1026):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1292554705] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1026):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1292554701] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1026): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1026):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1292551680] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1026):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1292551677] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1026): doString: [SIGNAL_POLL]
,V/AlarmManager( 1026): ELAPSED_WAKEUP set : Alarm{613a09c type 2 when 274069 android} when 274069
,E/WifiStateMachine( 1026):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1292548655] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1026):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1292548652] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1026): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1026): tsOffsetIs: Apps: 278068244273; DSPS: 9253134; Offset : -4330540366
,E/WifiStateMachine( 1026):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1292545624] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1026):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1292545621] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1026): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1026):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1292542597] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1026):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1292542593] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1026): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1026):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1292539567] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1026):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1292539558] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1026): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1026):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1292536536] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1026):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1292536533] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1026): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1026):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1292533511] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1026):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1292533508] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1026): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
,I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
E/WifiStateMachine( 1026):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1292530482] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1026):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1292530479] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1026): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1026):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1292527456] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1026):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1292527453] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1026): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1026): tsOffsetIs: Apps: 298071311506; DSPS: 9908595; Offset : -4330555330
,E/WifiStateMachine( 1026):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1292524428] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1026):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:8] from screen [on:0 period:-1292524420] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1026): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1026):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1292521400] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1026):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1292521397] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1026): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1026):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1292518372] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1026):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1292518369] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1026): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1026):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1292515343] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1026):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1292515340] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1026): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1026):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1292512318] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1026):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1292512309] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1026): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1026):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1292509289] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1026):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1292509279] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1026): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1026): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1026): tsOffsetIs: Apps: 318073171393; DSPS: 10564016; Offset : -4330556911
,E/WifiStateMachine( 1026):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1292506258] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1026):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1292506249] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1026): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1026):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1292503227] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1026):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1292503214] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1026): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1026):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1292500194] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1026):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1292500191] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1026): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1026):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1292497164] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1026):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1292497161] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1026): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1026):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1292494136] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1026):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1292494133] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1026): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1026):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1292491109] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1026):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1292491100] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1026): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1026):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1292488083] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1026):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1292488080] gl rssi=-61 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1026): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1026): tsOffsetIs: Apps: 338075117948; DSPS: 11219440; Offset : -4330563585
,I/wpa_supplicant( 6154): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/WifiMonitor( 1026): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0]
E/WifiMonitor( 1026): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
E/WifiMonitor( 1026): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
D/WifiMonitor( 1026): handleNetworkStateChange: Could not parse disconnect string
E/WifiMonitor( 1026): WifiMonitor notify network disconnect: null reason=0
D/Tethering( 1026): InitialState.processMessage what=4
,D/Tethering( 1026): sendTetherStateChangedBroadcast 0, 0, 0
,E/WifiStateMachine( 1026):  ConnectedState NETWORK_DISCONNECTION_EVENT nid=0 reason=0 lastbssid=c0:ff:d4:d3:aa:48 freq=2412 rssi=-60 rt=339385
E/WifiStateMachine( 1026):  L2ConnectedState NETWORK_DISCONNECTION_EVENT nid=0 reason=0 lastbssid=c0:ff:d4:d3:aa:48 freq=2412 rssi=-60 rt=339385
E/WifiStateMachine( 1026):  ConnectModeState NETWORK_DISCONNECTION_EVENT nid=0 reason=0 lastbssid=c0:ff:d4:d3:aa:48 freq=2412 rssi=-60 rt=339386
E/WifiConfigStore( 1026): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1026): doBoolean: SET_NETWORK 0 bssid any
,D/WifiNative-wlan0( 1026): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1026): doBoolean: SAVE_CONFIG
D/WifiMonitor( 1026): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1026): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1026): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1026): doBoolean: DRIVER BTCOEXMODE 2
D/LGWifiP2pService( 1026): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1026): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 6154): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1026): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1026): doBoolean: SET ps 1
D/WifiNative-wlan0( 1026): SET ps 1: returned true
D/CommandListener(  327): Clearing all IP addresses on wlan0
,D/DhcpStateMachine( 1026): RunningState{ when=-10ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1026): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1026): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,I/jxcore-log( 5997): Toggling radios to false
I/jxcore-log( 5997): 
,I/wpa_supplicant( 6154): wlan0: CTRL-EVENT-SCAN-STARTED 
,I/ActivityManager( 1026): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=7501 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
V/NativeCrypto( 2135): Read error: ssl=0xaf4d5600: I/O error during system call, Connection timed out
D/WifiMonitor( 1026): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1026): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1026): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1026): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/BluetoothManagerService( 1026): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1026): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@25f31aa5 mBinding = false
V/NativeCrypto( 2135): SSL shutdown failed: ssl=0xaf4d5600: I/O error during system call, Broken pipe
,D/ConnectivityService( 1026): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1026): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
E/WifiStateMachine( 1026): WifiStateMachine: Leaving Connected state
,D/WifiHS20( 1026): hidePasspointNotification off =false
I/StatusBar.NetworkController( 1465): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1465): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
D/LocationManagerService( 1026): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1026): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1026): JNI:system_update. Event-4
D/BluetoothManagerService( 1026): Message: 2
V/WfdStateTracker( 1960): handleWifiStateChangedEvent: 0
D/BluetoothManagerService( 1026): Sending off request.
D/LGBluetoothServiceAdapter( 6098): [BTUI] Precleanup
D/BluetoothAdapterState( 6098): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 6098): Setting state to 13
I/BluetoothAdapterState( 6098): Bluetooth adapter state changed: 12-> 13
W/Settings( 1026): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1026): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1026): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/BluetoothAdapterProperties( 6098): onBluetoothDisable()
I/BluetoothAdapterState( 6098): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
D/WifiHS20( 1026): hidePasspointNotification off =false
E/WifiStateMachine( 1026):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1026):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1026):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1026):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1026):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1026):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=339560  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1026):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=339561  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1026):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=339561  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,D/BluetoothManagerService( 1026): Message: 60
D/BluetoothManagerService( 1026): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService( 1026): Bluetooth State Change Intent: 12 -> 13
D/ConnectivityService( 1026): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1026): ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1026): DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1026): Forcing reevaluation
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1026): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1026): Checking http://clients3.google.com/generate_204 on <unknown ssid>
I/StatusBar.NetworkController( 1465): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1465): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1026): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1026): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1026): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/BluetoothAdapterProperties( 6098): Scan Mode:20
D/WifiServiceImplEx( 1026): setWifiEnabled: false pid=5997, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1026): setWifiEnabled: false pid=5997, uid=10311
E/WifiService( 1026): Invoking mWifiStateMachine.setWifiEnabled
D/LGBluetoothAPIService( 1960): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
I/[SystemUI]BluetoothHandler( 1465): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
D/BluetoothAdapterState( 6098): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
V/BluetoothPbapService( 6098): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
D/btif_config_util( 6098): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
V/BluetoothFtpService:RfcommSocketAcceptThread( 6098): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 6098): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 6098): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 6098): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
V/BluetoothMapMasInstance( 6098): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
V/BluetoothMapMasInstance( 6098): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
V/BluetoothMapMasInstance( 6098): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 6098): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 6098): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,W/bt-l2cap( 6098): L2CAP - L2CA_Deregister() called for PSM: 0x000f
W/bt-btif ( 6098): bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
W/bt-l2cap( 6098): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 6098): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 6098): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 6098): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 6098): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 6098): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 6098): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 6098): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 6098): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 6098): L2CAP - L2CA_Deregister() called for PSM: 0x0011
W/bt-l2cap( 6098): L2CAP - L2CA_Deregister() called for PSM: 0x0013
E/bt-btif ( 6098): bta_gattc_deregister Deregister Failedm unknown client cif
E/BtOppRfcommListener( 6098): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothSapService( 6098): Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
D/libc-netbsd(  327): default dns: query_ipv6=0, query_ipv4=0
E/WifiStateMachine( 1026):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=339599  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/ConnectivityService( 1026): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1026): disableDataServiceNotify
E/WifiStateMachine( 1026):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
D/DSQN    ( 1026): stop dsqn bin
E/WifiStateMachine( 1026):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
D/DSQN    ( 1026): DNSproblemNotiEnabled is disabled ignore DNS fail CB
E/WifiStateMachine( 1026):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1026):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1026):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1026):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1026):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1026):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1026):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1026):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiNetworkAgent( 1026): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine( 1026):  DisconnectedState CMD_RSSI_POLL 1 0 0x 00:00:00:00:00:00 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3050] from screen [on:0 period:-1292485007] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/ConnectivityService( 1026): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1026):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1026):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1026): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat( 1026): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityManager.CallbackHandler( 1465): CM callback handler got msg 524292
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1026): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1026): EvaluatingState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1026): DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1026): Disconnected - quitting
I/BluetoothMapService( 6098): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 6098): STATE_TURNING_OFF
V/BluetoothMapService( 6098): Handler(): got msg=4
D/BluetoothMapService( 6098): MAP Service closeService in
D/BluetoothMapMasInstance( 6098): MAP Service shutdown
D/LGBluetoothMapAdapter( 6098): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 6098): MAP Service closeService out
V/BtOppService( 6098): Receiver DISABLED_ACTION 
I/BtOppRfcommListener( 6098): stopping Accept Thread
V/BtOppRfcommListener( 6098): close mBtServerSocket
V/BtOppRfcommListener( 6098): waiting for thread to terminate
D/CSLegacyTypeTracker( 1026): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1026): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1026): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/BtOppRfcommListener( 6098): BluetoothSocket listen thread finished
I/jxcore-log( 5997): Radios toggled
I/jxcore-log( 5997): 
V/BtOppRfcommListener( 6098): done waiting for thread to terminate
D/WifiHS20( 1026): hidePasspointNotification off =false
W/Settings( 1026): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1026): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1026): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/LocationManagerService( 1026): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1026): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1026): JNI:system_update. Event-4
W/Settings( 1026): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global,, returning read-only value.
W/Settings( 1026): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1026): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/ConnectivityService( 1026): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1026): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
E/WifiStateMachine( 1026):  ConnectModeState CMD_RSSI_POLL 1 0 0x 00:00:00:00:00:00 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1292484996] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1026):  DriverStartedState CMD_RSSI_POLL 1 0 0x 00:00:00:00:00:00 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1292484986] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1026):  SupplicantStartedState CMD_RSSI_POLL 1 0 0x 00:00:00:00:00:00 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1292484985] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1026):  DefaultState CMD_RSSI_POLL 1 0 0x 00:00:00:00:00:00 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:-1292484985] gl rssi=-60 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
V/BtOppService( 6098): onDestroy
D/ConnectivityService( 1026): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1026): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1026): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService( 1026): Removing idletimer
W/Settings( 1026): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1026): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
E/ConnectivityService( 1026): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/TelephonyNetworkFactory-1( 1865): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1865):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
I/StatusBar.NetworkController( 1465): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/StatusBar.NetworkController( 1465): mWifiConnected = false, mWifiLevel = 0
D/LGBluetoothOppAdapter( 6098): [BTUI] LGBluetoothOppAdapter cleanup
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
V/NetworkPolicy( 1026): [LG_RESTRICTED] !!!isConnected  type  :1
I/StatusBar.NetworkController( 1465): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1465): mWifiConnected = false, mWifiLevel = 0
D/LocSvc_java( 1026): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1026): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1026): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1026): ignore wifi update if we are not in OPENING or CLOSING
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
V/NetworkPolicy( 1026): [LG_RESTRICTED] !!!isConnected  type  :1
D/LocSvc_java( 1026): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1026): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1026): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1026): ignore wifi update if we are not in OPENING or CLOSING
D/WifiServerServiceExt( 1026): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1026): setSupplicantStateDISCONNECTED
E/WifiStateMachine( 1026):  DisconnectedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1026):  ConnectModeState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1026):  DriverStartedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1026):  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
D/WifiServerServiceExt( 1026): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1026): setSupplicantStateSCANNING
,D/TelephonyIcons( 1465): null signal icon name: drawable/stat_sys_signal_null
W/ResourcesManager( 7501): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7501): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 7501): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
W/ResourcesManager( 7501): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiScanningService( 1026): SCAN_AVAILABLE : 1
D/RttService( 1026): SCAN_AVAILABLE : 1
D/WIFI    ( 1026): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WifiScanningService( 1026): DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1026): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WIFI    ( 1026):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/LGWifiP2pService( 1026): P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService( 1026): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1026): stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@d2eef86
D/LGWifiP2pService( 1026): P2pDisablingState
D/LGWifiP2pService( 1026): P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1026): p2p socket connection lost
D/LGWifiP2pService( 1026): P2pDisabledState
W/ResourcesManager( 7501): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
V/WfdStateTracker( 1960): WfdStateTracker handleDirectStateChangedEvent: 0
D/WfdsService( 1960): WifiP2pState is changed : false
D/WfdsService( 1960): WfdsEnabledState: Receive the WFDS_DISABLE message
D/WfdsService( 1960): Set the WFDS Monitor: false
W/ResourcesManager( 7501): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/WfdsMonitor( 1960): WFDS Monitor is stopped
D/CtrlSupplicant( 1960): Received on exit socket, terminate
D/WfdsService( 1960): STATE : WfdsDisabledState - enter
E/CtrlSupplicant( 1960): wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
E/WifiStateMachine( 1026):  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
D/WfdsMonitor( 1960): Event [CTRL-EVENT-TERMINATING  - connection closed]
D/WfdsMonitor( 1960): WfdsMonitorThread is received the interrupt - closing
D/WifiNative-wlan0( 1026): doBoolean: DRIVER BTCOEXMODE 2
W/WfdsService( 1960): DefaultState - msg [9445378] is not handled
I/wpa_supplicant( 6154): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1026): P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1026): DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/WfdsSession:Controller( 1960): DefaultState - msg [9441355] is not handled
,D/WifiNative-wlan0( 1026): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1026): doBoolean: SET ps 1
D/WifiNative-wlan0( 1026): SET ps 1: returned true
D/CommandListener(  327): Clearing all IP addresses on wlan0
D/WifiHS20( 1026): hidePasspointNotification off =false
W/Settings( 1026): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1026): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1026): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiNative-p2p0( 1026): doBoolean: TERMINATE
D/WifiNative-p2p0( 1026): TERMINATE: returned true
E/WifiStateMachine( 1026): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1026): useWiFiOffloading() : false
E/WifiStateMachine( 1026): CONFIG_LGE_WLAN_PATH : true
D/WifiHS20( 1026): hidePasspointNotification off =false
W/Settings( 1026): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1026): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1026): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
V/WfdStateTracker( 1960): WfdStateTracker handleDirectStateChangedEvent: 6
I/WifiServerServiceExt( 1026): WIFI_STATE_CHANGED_ACTION [0]
,D/TelephonyIcons( 1465): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1465): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1465): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1465): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1465): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
D/DhcpStateMachine( 1026): StoppedState
D/DhcpStateMachine( 1026): StoppedState{ when=-46ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 1026):  SupplicantStoppingState CMD_ON_QUIT 0 0
,E/WifiStateMachine( 1026):  DefaultState CMD_ON_QUIT 0 0
W/ContextImpl( 7501): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,V/BluetoothPbapReceiver( 6098): PbapReceiver onReceive 
,V/BluetoothPbapReceiver( 6098): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6098): ***********state = 13
D/UsbSettingsReceiver( 7501): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7501): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7501): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7501): [AUTORUN] persist.sys.usb.config = ptp_only,adb
V/BluetoothPbapReceiver( 6098): ***********Calling start service!!!! with action = null
D/UsbSettingsReceiver( 7501): [AUTORUN] onReceive() : app userid = 0, current userid = 0
V/BluetoothPbapService( 6098): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 6098): state: 13
V/BluetoothPbapService( 6098): Pbap Service closeService in
I/ActivityManager( 1026): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7544 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,V/BluetoothPbapService( 6098): successfully stopped pbap service
V/BluetoothPbapService( 6098): Pbap Service closeService out
V/BluetoothPbapService( 6098): Pbap Service onDestroy
V/BluetoothPbapService( 6098): Pbap Service closeService in
V/BluetoothPbapService( 6098): Pbap Service closeService out
D/LGBluetoothPbapAdapter( 6098): [BTUI] cleanup
D/UsbSettingsControl( 7501): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7501): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 7501): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7501): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7501): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 7501): [AUTORUN] setTetherStatus() : status=false
,D/BluetoothManagerService( 1026): Message: 20
D/BluetoothManagerService( 1026): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3b9fbc21:true
,I/ActivityManager( 1026): Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=7562 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,D/BluetoothManagerService( 1026): Message: 30
,D/BluetoothManagerService( 1026): Message: 30
,D/LocalBluetoothProfileManager( 7501): Adding local MAP profile
D/BluetoothMap( 7501): Create BluetoothMap proxy object
D/BluetoothManagerService( 1026): Message: 30
D/BluetoothManagerService( 1026): Message: 30
,D/LocalBluetoothProfileManager( 7501): LocalBluetoothProfileManager construction complete
D/LGBluetoothFeatureConfig( 7501):  get() - isFeatureLoaded : false
,D/LGBluetoothUserBindClient( 7501): [BTUI] initUserBindClient
,W/ContextImpl( 7501): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
E/ActivityThread( 7544): Failed to find provider info for com.lge.lgaccount.provider
W/LG Account v2.2( 7544): No ProfileInfo entries
I/LG Account v2.2( 7544): isEnabled: false
I/Feature ( 7544): [Lifetracker]ver: 4.21.112(40211120)
,I/Feature ( 7544): [Lifetracker]Country: EU
I/Feature ( 7544): [Lifetracker]Operator: OPEN
I/Feature ( 7544): [Lifetracker]Ranking support: false
I/Feature ( 7544): [Lifetracker]Comfort support: false
I/Feature ( 7544): [Lifetracker]Accessory: true
I/Feature ( 7544): [Lifetracker]Health device: true
I/Feature ( 7544): [Lifetracker]Extra Pedometer: false
I/Feature ( 7544): [Lifetracker]Blood glucose device: false
I/Feature ( 7544): [Lifetracker]Device Number: 3
W/ResourcesManager( 7562): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
I/ActivityManager( 1026): Killing 6785:com.android.providers.calendar/u0a14 (adj 15): empty #17
D/PluginManager( 7562): init()
,W/libprocessgroup( 1026): failed to open /acct/uid_10014/pid_6785/cgroup.procs: No such file or directory
,D/DockEventReceiver( 7501): finishStartingService: stopping service
D/BluetoothInputDevice( 7501): Proxy object connected
D/HidProfile( 7501): Bluetooth service connected
D/BluetoothPan( 7501): BluetoothPAN Proxy object connected
D/PanProfile( 7501): Bluetooth service connected
,D/BluetoothMap( 7501): Proxy object connected
,D/MapProfile( 7501): Bluetooth service connected
D/BluetoothMap( 7501): getConnectedDevices()
D/BluetoothMap( 7501): Bluetooth is Not enabled
D/LGBluetoothUserBindClient( 7501): [BTUI] onServiceConnected
D/LGBluetoothAuthorization( 7501): [BTUI] cancel All Notification
,D/BluetoothPermissionRequest( 7501): onReceive
,D/LGBluetoothAuthorization( 7501): [BTUI] cancel All Notification
,D/LGBluetoothResetSettingReceiver( 7501): return without doing reset settings.
,I/ActivityManager( 1026): Killing 6852:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,I/QRemote ( 6295): [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
W/System.err( 6295): android.os.DeadObjectException
W/System.err( 6295): 	at android.os.BinderProxy.transactNative(Native Method)
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
,W/System.err( 6295): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
W/System.err( 6295): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 6295): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 6295): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6295): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6295): 	at android.os.Looper.loop(Looper.java:135)
,W/System.err( 6295): ,	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 6295): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6295): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6295): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909),
W/System.err( 6295): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704),
E/UEI.SmartControl( 6295): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/QRemote ( 6295): [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,V/BluetoothOppReceiver( 6098): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
D/BluetoothOppNotification( 6098): [BTUI] cancel opp incoming file confirm notification
W/libprocessgroup( 1026): failed to open /acct/uid_1000/pid_6852/cgroup.procs: No such file or directory
W/ActivityManager( 1026): Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,D/BluetoothOppNotification( 6098): [BTUI] cancel opp active transfer file notification
V/BluetoothFtpReceiver( 6098): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpReceiver( 6098): BluetoothFtpReceiver Start Service
V/BluetoothFtpService( 6098): Ftp Service onStartCommand
V/BluetoothFtpService( 6098): action: android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothFtpService( 6098): Ftp Service closeService
E/BluetoothFtpService:RfcommSocketAcceptThread( 6098): Shutdown
V/BluetoothFtpService( 6098): successfully stopped ftp service
V/BluetoothSapReceiver( 6098): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 6098): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 6098): SapReceiver onReceive 
,V/BluetoothSapReceiver( 6098): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6098):  Bluetooth Adapter state = 13
V/BluetoothSapReceiver( 6098): Calling SAP service start service with action = null
V/BluetoothFtpService( 6098): Ftp Service onDestroy
V/BluetoothFtpService( 6098): Ftp Service closeService
D/QRemote ( 6295): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
,I/QRemote ( 6295): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
I/ActivityManager( 1026): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7603 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,V/BluetoothSapService( 6098): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 6098): state: 13
V/BluetoothSapService( 6098): Stopping SAP server process
V/BluetoothSapService( 6098): Sap Service closeSapService in
V/BluetoothSapService( 6098): Close listen Socket : 
V/BluetoothSapService( 6098): Close rfcomm Socket : 
V/BluetoothSapService( 6098): Close sapd  Socket : 
I/ActivityManager( 1026): Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7620 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,V/BluetoothSapService( 6098): Sap Service closeSapService out
V/BluetoothSapService( 6098): Sap Service onDestroy
V/BluetoothSapService( 6098): Sap Service closeSapService in
V/BluetoothSapService( 6098): Close listen Socket : 
V/BluetoothSapService( 6098): Close rfcomm Socket : 
V/BluetoothSapService( 6098): Close sapd  Socket : 
V/BluetoothSapService( 6098): Sap Service closeSapService out
D/QRemote ( 6295): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,W/ResourcesManager( 7603): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/ActivityManager( 1026): Killing 6295:com.lge.qremote/u0a112 (adj 15): empty #17
D/bt_hci_bdroid( 6098): cleanup
,I/bt_lpm  ( 6098): LPM is already off!!!
I/bt_userial_mct( 6098): exiting userial_read_thread
D/bt_userial_mct( 6098): Leaving userial_evt_read_thread()
D/bt_userial_mct( 6098): userial_close_reader Joined userial reader thread: 0
W/bt-btif ( 6098): ag scb idx 1 not allocated
E/bt-btif ( 6098): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 6098): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 6098): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 6098): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 6098): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 6098): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 6098): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 6098): L2CAP - L2CA_Deregister() called for PSM: 0x0019
,W/bt-l2cap( 6098): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 6098): L2CAP - L2CA_Deregister() called for PSM: 0x0017
,W/bt-l2cap( 6098): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 6098): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 6098): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 6098): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 6098): L2CAP - PSM: 0x0019 not found for deregistration,
W/bt-l2cap( 6098): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 6098): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 6098): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 6098): L2CAP - PSM: 0x001b not found for deregistration
,E/bt-btif ( 6098): bta_gattc_deregister Deregister Failedm unknown client cif
I/bt_vendor( 6098): hw_epilog_process
D/bt_hci_bdroid( 6098): cleanup Finalizing cleanup
D/bt_userial_mct( 6098): userial_close
E/bt_userial_mct( 6098): pthread_join() FAILED result:3
,I/bt_vendor( 6098): bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
W/ExternalStrings( 7562): load override strings
W/ExternalStrings( 7562): java.lang.RuntimeException: Unexpected tag, got eat-comment
W/ExternalStrings( 7562): 	at com.mcafee.plugin.af.a(Unknown Source)
W/ExternalStrings( 7562): 	at com.mcafee.plugin.ac.b(Unknown Source)
W/ExternalStrings( 7562): ,	at com.mcafee.plugin.ak.d(Unknown Source)
W/ExternalStrings( 7562): 	at com.mcafee.plugin.ak.a(Unknown Source)
W/ExternalStrings( 7562): 	at com.mcafee.app.s.getClassLoader(Unknown Source)
W/ExternalStrings( 7562): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
W/ExternalStrings( 7562): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
W/ExternalStrings( 7562): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
W/ExternalStrings( 7562): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
W/ExternalStrings( 7562): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
W/ExternalStrings( 7562): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ExternalStrings( 7562): 	at android.os.Looper.loop(Looper.java:135)
W/ExternalStrings( 7562): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/ExternalStrings( 7562): 	at java.lang.reflect.Method.invoke(Native Method)
W/ExternalStrings( 7562): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/ExternalStrings( 7562): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/ExternalStrings( 7562): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,D/StatusProvider( 7562): onCreate
,D/AuthorizationBluetoothService( 2135): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/libprocessgroup( 1026): failed to open /acct/uid_10112/pid_6295/cgroup.procs: No such file or directory
,D/bt_hci_bdroid( 6098): set_power 0
I/bt_vendor( 6098): bt-vendor : BT_VND_OP_POWER_CTRL: Off
I/bt_vendor( 6098): bluetooth satus is on
I/bt_vendor( 6098): bt-vendor : resetting BT status
I/bt_vendor( 6098): Starting hciattach daemon
I/bt_vendor( 6098): try to set false
I/bt_vendor( 6098): Starting hciattach daemon
I/bt_vendor( 6098): try to set false
I/bt_vendor( 6098): cleanup
I/GKI_LINUX( 6098): gki_task task_id=0 [BTU] terminating
,D/UEI.SmartControl( 7620): Quickset Services start...
I/UEI.SmartControl( 7620): Manufacture = LGE
D/UEI.SmartControl( 7620): Id = LGNevo
I/GKI_LINUX( 6098): GKI_exit_task 0 done
I/GKI_LINUX( 6098): GKI_shutdown(): task [BTU] terminated
D/UEI.SmartControl( 7620): File observer start...
D/BluetoothAdapterState( 6098): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/HeadsetService( 6098): Received stop request...Stopping profile...
E/UEI.SmartControl( 7620): IR Port is disabled: false
I/LGBluetoothHfpAdapter( 6098): [BTUI] LGBluetoothHfpAdapter cleanup
W/LGBluetoothHeadsetServiceJni( 6098): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 6098): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37432350
D/HeadsetStateMachine( 6098): Exit Disconnected: -1
D/UEI.SmartControl( 7620): Starting file observer...
D/UEI.SmartControl( 7620): Extracting JNI libs...
D/UEI.SmartControl( 7620): --- this system supports 32-bit or 64-bit only
D/BluetoothHeadset( 1026): Proxy object disconnected
D/AudioService( 1026): onServiceDisconnected: Bluetooth profile: 1
D/BluetoothHeadset( 1865): Proxy object disconnected
D/BluetoothHeadset( 1865): Proxy object disconnected
D/BluetoothHeadset( 1865): Proxy object disconnected
,D/A2dpService( 6098): Received stop request...Stopping profile...
D/A2dpStateMachine( 6098): Exit Disconnected: -1
D/LGBluetoothAvrcpQcomAdapter( 6098): [BTUI] cleanup
D/BluetoothAdapterState( 6098): Stopping profile services that were post enabled
D/LGBluetoothA2dpAdapter( 6098): [BTUI] LGBluetoothA2dpAdapter cleanup
W/LGBluetoothA2dpServiceJni( 6098): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 6098): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37432350
D/BluetoothA2dp( 1026): Proxy object disconnected
D/AudioService( 1026): onServiceDisconnected: Bluetooth profile: 2
D/HidService( 6098): Received stop request...Stopping profile...
D/BluetoothAdapterService( 6098): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37432350
D/BluetoothInputDevice( 7501): Proxy object disconnected
D/HealthService( 6098): Received stop request...Stopping profile...
D/HidProfile( 7501): Bluetooth service disconnected
D/BluetoothAdapterService( 6098): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37432350
D/HeadsetStateMachine( 6098): Unbinding service...
D/HeadsetPhoneState( 6098): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 6098): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetPhoneState( 6098): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 6098): [BTUI] listenForMultiSimPhoneState : start = false
W/BluetoothHeadsetServiceJni( 6098): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 6098): Cleaning up Bluetooth Handsfree callback object
I/LGBluetoothHfpAdapter( 6098): [BTUI] LGBluetoothHfpAdapter cleanup
D/PanService( 6098): Received stop request...Stopping profile...
D/BluetoothAdapterService( 6098): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37432350
,D/BtGatt.DebugUtils( 6098): handleDebugAction() action=null
D/BtGatt.GattService( 6098): Received stop request...Stopping profile...
D/BtGatt.GattService( 6098): stop()
D/BtGatt.AdvertiseManager( 6098): advertise clients cleared
D/BluetoothAdapterService( 6098): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37432350
D/BluetoothMapService( 6098): Received stop request...Stopping profile...
D/BluetoothMapService( 6098): stop()
D/BluetoothMapEmailAppObserver( 6098): deinitObservers()
D/BluetoothMapEmailAppObserver( 6098): removeReceiver()
D/BluetoothAdapterService( 6098): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37432350
D/BluetoothPan( 7501): BluetoothPAN Proxy object disconnected
D/PanProfile( 7501): Bluetooth service disconnected
D/BluetoothMap( 7501): Proxy object disconnected
D/MapProfile( 7501): Bluetooth service disconnected
I/BluetoothA2dpServiceJni( 6098): cleanupNative
I/GKI_LINUX( 6098): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 6098): GKI_exit_task 2 done
I/GKI_LINUX( 6098): GKI_shutdown(): task [A2DP-MEDIA] terminated
W/BluetoothHidServiceJni( 6098): Cleaning up Bluetooth HID Interface...
W/BluetoothHidServiceJni( 6098): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 6098): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 6098): Cleaning up Bluetooth Health object
W/LGBluetoothHealthServiceJni( 6098): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 6098): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 6098): Cleaning up Bluetooth PAN callback object
V/BluetoothMapService( 6098): Handler(): got msg=4
D/BluetoothMapService( 6098): MAP Service closeService in
D/LGBluetoothMapAdapter( 6098): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 6098): MAP Service closeService out
D/BluetoothAdapterState( 6098): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 6098): Setting state to 10
I/BluetoothAdapterState( 6098): Bluetooth adapter state changed: 13-> 10
D/BluetoothManagerService( 1026): Message: 60
D/BluetoothManagerService( 1026): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService( 1026): Broadcasting onBluetoothStateChange(false) to 9 receivers.
I/BluetoothAdapterState( 6098): Entering OffState
D/BluetoothMap( 7501): onBluetoothStateChange: up=false
D/BluetoothMapService( 6098): cleanup()
D/BluetoothMapService( 6098): MAP Service closeService in
D/LGBluetoothMapAdapter( 6098): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 6098): MAP Service closeService out
D/BluetoothA2dp( 1026): onBluetoothStateChange: up=false
D/BluetoothPbap( 7501): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1865): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1026): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1865): onBluetoothStateChange: up=false
D/BluetoothInputDevice( 7501): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1865): onBluetoothStateChange: up=false
,D/BluetoothPan( 7501): onBluetoothStateChange on: false
D/BluetoothManagerService( 1026): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService( 1026): Broadcasting onBluetoothServiceDown() to 8 receivers.
D/BluetoothManagerService( 1026): Calling onQBluetoothServiceDown callbacks
D/BluetoothManagerService( 1026): Broadcasting onQBluetoothServiceDown() to 0 receivers.
D/BluetoothManagerService( 1026): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@25f31aa5 mBinding = false
D/BluetoothManagerService( 1026): Sending unbind request.
D/BluetoothManagerService( 1026): Bluetooth State Change Intent: 13 -> 10
D/LGBluetoothAPIService( 1960): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/LGBluetoothAPIService( 1960): Message: 2
D/LGBluetoothAPIService( 1960): unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@df45b1e mBinding = false
D/LGBluetoothAPIService( 1960): Sending unbind request.
I/[SystemUI]BluetoothHandler( 1465): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
D/LGBluetoothFeatureConfig( 7501): isPrivacyLogsEnabled : true
E/LGBluetoothEventManager( 7501): [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
D/LGBluetoothEventManager( 7501): [BTUI] clear device connection state
D/BluetoothAdapter( 1465): 567373274: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1465): 567373274: getState() :  mService = null. Returning STATE_OFF
,I/GKI_LINUX( 6098): gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 6098): GKI_exit_task 1 done
I/GKI_LINUX( 6098): GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 6098): cleanupNative: return from cleanup
I/art     ( 6098): --- WEIRD: removing null entry 246
W/art     ( 6098): JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
W/LGBluetoothServiceJni( 6098): Cleaning up Bluetooth Service callback object
D/LGBluetoothSettingsDBObserver( 6098): [BTUI] unregister observer for LG device name DB
W/ContextImpl( 7501): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
I/art     ( 6098): System.exit called, status: 0
I/AndroidRuntime( 6098): VM exiting with result code 0, cleanup skipped.
D/DockEventReceiver( 7501): finishStartingService: stopping service
,V/AudioFlinger(  331): 6098 died, releasing its sessions
V/AudioFlinger(  331):  pid 1865 @ 0
V/AudioFlinger(  331):  pid 3243 @ 1
V/AudioFlinger(  331):  pid 3243 @ 2
D/LGBluetoothUserBindClient( 7501): [BTUI] onServiceDisconnected
V/Signer  ( 7562): override build config not found
D/Signer  ( 7562): value of property debug is false
,D/UEI.SmartControl( 7620): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 7620): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7620): --- Extracting JNI libs: libqs_armeabi-v7a.zip
D/LGMDMWrapper( 7562): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
,D/LGMDMWrapper( 7562): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
D/LGMDMWrapper( 7562): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
D/LGMDMWrapper( 7562): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
D/LGMDMWrapper( 7562): Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
D/LGMDMWrapper( 7562): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
D/LGMDMWrapper( 7562): Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
D/LGMDMWrapper( 7562): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
D/LGMDMWrapper( 7562): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
D/LGMDMWrapper( 7562): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
D/LGMDMWrapper( 7562): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
D/LGMDMWrapper( 7562): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
D/LGMDMWrapper( 7562): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
I/UEI.SmartControl( 7620): --- Selecting new region: 6
,V/LGMDMManager( 7562): Create singleton instance
I/UEI.SmartControl( 7620): Model = LG-D855
D/UEI.SmartControl( 7620): QS Service created
I/ActivityManager( 1026): Process com.android.bluetooth (pid 6098) has died
W/ActivityManager( 1026): Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
I/UEI.SmartControl( 7620): Service initServices...
,D/UEI.SmartControl( 7620): QS start get config
D/BluetoothPermissionRequest( 7501): onReceive
D/LGBluetoothUtils( 7501): [BTUI] FileNotFound: readProperty
D/BluetoothDiscoverableTimeoutReceiver( 7501): cancelDiscoverableAlarm(): Enter
D/LGBluetoothResetSettingReceiver( 7501): return without doing reset settings.
,D/LGMDMWrapper( 7562): LG MDM library v4.0.0 is available on this device.
,I/ActivityManager( 1026): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7653 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
D/UEI.SmartControl( 7620): Loading JNI Libs...
,D/PostponalbeReceiver( 7562): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,W/ContextImpl( 7562): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
I/ActivityManager( 1026): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7675 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/ActivityManager( 1026): Killing 6896:com.google.android.gm/u0a64 (adj 15): empty #17
,W/ActivityThread( 7562): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/ResourcesManager( 7653): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager( 7653): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7653): Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 7653): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
W/libprocessgroup( 1026): failed to open /acct/uid_10064/pid_6896/cgroup.procs: No such file or directory
D/BluetoothAdapterApp( 7653): Loading JNI Library
,D/BluetoothAdapterApp( 7653): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@33bcd911 Instance Count = 1
D/BluetoothAdapterApp( 7653): onCreate
I/PCSuite ( 7675): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/ProfileConfigQcom( 7653): [BTUI] HeadsetService is supported
,D/ProfileConfigQcom( 7653): Adding HeadsetService
D/ProfileConfigQcom( 7653): [BTUI] A2dpService is supported
D/ProfileConfigQcom( 7653): Adding A2dpService
D/ProfileConfigQcom( 7653): [BTUI] HidService is supported
D/ProfileConfigQcom( 7653): Adding HidService
D/ProfileConfigQcom( 7653): [BTUI] HealthService is supported
D/ProfileConfigQcom( 7653): Adding HealthService
D/LGBluetoothFeatureConfig( 7653): isSupportPan() :  mTargetOp=OPEN
D/ProfileConfigQcom( 7653): [BTUI] PanService is supported
D/ProfileConfigQcom( 7653): Adding PanService
D/ProfileConfigQcom( 7653): [BTUI] GattService is supported
D/ProfileConfigQcom( 7653): Adding GattService
D/ProfileConfigQcom( 7653): [BTUI] BluetoothMapService is supported
D/ProfileConfigQcom( 7653): Adding BluetoothMapService
D/ProfileConfigQcom( 7653): [BTUI] HeadsetClientService is NOT supported
D/PCSuite ( 7675): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7675): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/LGBluetoothOppAdapter( 7653): [BTUI] getInstance : create [LGBluetoothOppAdapter]
V/LGMDMManagerInternal( 7653): Create singleton instance
,V/WiFiOffLoadBroadcast( 7501): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/UEI.SmartControl( 7620): Supports setup maps: true
V/BluetoothFtpReceiver( 7653): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
D/LgDataFeature( 7501): LgDataFeature() Constructor: none
D/LgDataFeature( 7501): LgDataFeature() Constructor Done, null
V/BluetoothSapReceiver( 7653): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 7653): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 7653): SapReceiver onReceive 
,D/UEI.SmartControl( 7620): QS start statue = true Error code = 0
I/UEI.SmartControl( 7620): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 7620): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 7620): ### init IR Blaster...
V/BluetoothSapReceiver( 7653): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 7653):  Bluetooth Adapter state = 10
D/LGBluetoothProfileConnectionReceiver_EasySetting( 7603): [BTUI] STATE_OFF : reset connected device information EasySettings
D/WiFiOffLoadBroadcast( 7501): MCCMNC not supported: null
D/LGBluetoothUserBindClient( 7501): [BTUI] onServiceConnected
D/AuthorizationBluetoothService( 2135): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/serial_port( 7620): Configuring serial port
E/UEI.SmartControl( 7620): UEIBLaster setting for 616
I/UEI.SmartControl( 7620): Setting serial record hearder size = 2
I/UEI.SmartControl( 7620): configuring settings for MAXQ616
I/UEI.SmartControl( 7620): Get version...
,D/LgDataFeature( 7562): LgDataFeature() Constructor: none
D/LgDataFeature( 7562): LgDataFeature() Constructor Done, null
,D/UEI.SmartControl( 7620): serial port data available: 21
I/ActivityManager( 1026): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7707 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/ActivityManager( 1026): Killing 6978:com.google.android.videos/u0a103 (adj 15): empty #17
D/UEI.SmartControl( 7620): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 7620): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 7620): QS saving settings...
D/UEI.SmartControl( 7620): IR Blaster version: 25672567
D/UEI.SmartControl( 7620): serial port data available: 4
,W/ContextImpl( 7562): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
,I/UEI.SmartControl( 7620): Device manager: loading config....
D/UEI.SmartControl( 7620): ----------- loading internal config...
W/ContextImpl( 7620): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
I/ActivityManager( 1026): Killing 6625:com.google.android.apps.magazines/u0a93 (adj 15): empty #18
,E/UEI.SmartControl( 7620): Loading SETTINGS...
,D/UEI.SmartControl( 7620): -- Open brand translation xml: brands_translations_ko
I/UEI.SmartControl( 7620): Notify AllClients services are ready: 0
D/UEI.SmartControl( 7620): -----service ready thread exits
,W/libprocessgroup( 1026): failed to open /acct/uid_10103/pid_6978/cgroup.procs: No such file or directory
,W/libprocessgroup( 1026): failed to open /acct/uid_10093/pid_6625/cgroup.procs: No such file or directory
,E/UEI.SmartControl( 7620): Services init done
D/UEI.SmartControl( 7620): QS Service init finished
D/UEI.SmartControl( 7620): QS Service version name: 2.1.91
D/UEI.SmartControl( 7620): QS Service version code: 201091
D/UEI.SmartControl( 7620): Service requested: Control
D/UEI.SmartControl( 7620): Service.onUnbind: IControl
D/UEI.SmartControl( 7620): unbind internal service
D/UEI.SmartControl( 7620): Service.onDestroy
D/UEI.SmartControl( 7620): Lock is in USE false
D/UEI.SmartControl( 7620): unbind internal service
D/serial_port( 7620): close(fd = 25)
I/UEI.SmartControl( 7620): Serial port is closed.
,I/UEI.SmartControl( 7620): Serial port is closed.
D/UEI.SmartControl( 7620): Blaster closed
D/UEI.SmartControl( 7620): Shut down QS...
D/UEI.SmartControl( 7620): Stopping QS lib
D/UEI.SmartControl( 7620): QS lib stop result = true
D/UEI.SmartControl( 7620): Stopped QS lib
D/UEI.SmartControl( 7620): Stopped file observer...
D/UEI.SmartControl( 7620): QS shutdown complete
D/UEI.SmartControl( 7620): QS Service created
W/ResourcesManager( 7707): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/SiteAdvisor( 7562): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
,D/SiteAdvisor( 7562): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
D/SiteAdvisor( 7562): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
D/SiteAdvisor( 7562): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
D/SiteAdvisor( 7562): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
I/SiteAdvisor( 7562): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
,D/SiteAdvisor( 7562): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
D/SiteAdvisor( 7562): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
I/UEI.SmartControl( 7620): Service initServices...
D/UEI.SmartControl( 7620): QS start get config
D/QRemote ( 7707): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 7707): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
I/QRemote ( 7707): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 7707): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 7707): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 7707): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 7707): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 7707): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
I/wpa_supplicant( 6154): p2p0: CTRL-EVENT-TERMINATING 
I/wpa_supplicant( 6154): monitor socket send errors count : 1
I/wpa_supplicant( 6154): CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1960-2\x00 that cannot receive messages
,D/WifiMonitor( 1026): Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
,D/WifiMonitor( 1026): Dropping event because (p2p0) is stopped
W/wpa_supplicant( 6154): USIM:  scard_deinit function
D/WifiMonitor( 1026): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1026): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1026):  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=341531  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: DISCONNECTED
E/WifiStateMachine( 1026):  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=341532  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: DISCONNECTED
I/art     ( 1026): Explicit concurrent mark sweep GC freed 90522(4MB) AllocSpace objects, 5(464KB) LOS objects, 33% free, 44MB/66MB, paused 1.391ms total 139.135ms
,D/QRemote ( 7707): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7707): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7707): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 7562): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 7562): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
D/QRemote ( 7707): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
,I/wpa_supplicant( 6154): wlan0: CTRL-EVENT-TERMINATING 
I/PCSuite ( 7675): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/QRemote ( 7707): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
D/PCSuite ( 7675): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7675): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7501): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WifiMonitor( 1026): Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
E/WifiMonitor( 1026): WifiMonitor:wlan0 cnt=25 dispatchEvent: CTRL-EVENT-TERMINATING 
D/WifiMonitor( 1026): Disconnecting from the supplicant, no more events
E/WifiStateMachine( 1026):  SupplicantStoppingState SUP_DISCONNECTION_EVENT 25 0
D/WfdsService( 1960): Supplicant Connection state is changed : false
,D/WfdsService( 1960): DefaultState - WIFI_SUPPLICANT_DISCONNECTED
D/WfdsService( 1960): Set the WFDS Monitor: false
D/WfdsMonitor( 1960): WFDS Monitor is stopped
D/WifiOffDelayIfNotUsed( 1026): stopMonitoring
E/WifiStateMachine( 1026): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1026): useWiFiOffloading() : false
E/WifiStateMachine( 1026): CONFIG_LGE_WLAN_PATH : true
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WfdStateTracker( 1960): WfdStateTracker handleDirectStateChangedEvent: 0
I/WifiServerServiceExt( 1026): WIFI_STATE_CHANGED_ACTION [1]
I/WifiServerServiceExt( 1026): batteryPsActivateMsgHandler : state:0 event:1
I/WifiServerServiceExt( 1026): batteryPsActivateMsgHandler : this is not treated
W/Settings( 1830): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WiFiOffLoadBroadcast( 7501): MCCMNC not supported: null
D/QRemote ( 7707): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7707): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7707): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PowerManagerServiceEx( 1026): acquireWakeLockInternal: lock=631714865, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1026
V/AlarmManager( 1026): ELAPSED_WAKEUP set : Alarm{1f4a9056 type 2 when 341715 com.google.android.gms} when 341715
,D/PostponalbeReceiver( 7562): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/[Concierge]Service( 2588): onStartCommand(). Type : 9
,I/PCSuite ( 7675): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7675): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7675): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7501): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7501): MCCMNC not supported: null
,D/QRemote ( 7707): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7707): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7707): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 7562): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 7501): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7501): MCCMNC not supported: null
,D/QRemote ( 7707): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7707): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7707): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 7562): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7675): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 7675): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7675): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7501): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7501): MCCMNC not supported: null
D/QRemote ( 7707): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7707): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7707): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 7562): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7675): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7675): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7675): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7501): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7501): MCCMNC not supported: null
D/QRemote ( 7707): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7707): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7707): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
I/UEI.SmartControl( 7620): Supports setup maps: true
,D/UEI.SmartControl( 7620): QS start statue = true Error code = 0
I/UEI.SmartControl( 7620): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 7620): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 7620): ### init IR Blaster...
D/serial_port( 7620): Configuring serial port
,E/UEI.SmartControl( 7620): UEIBLaster setting for 616
I/UEI.SmartControl( 7620): Setting serial record hearder size = 2
I/UEI.SmartControl( 7620): configuring settings for MAXQ616
I/UEI.SmartControl( 7620): Get version...
,D/UEI.SmartControl( 7620): serial port data available: 21
,I/ActivityManager( 1026): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7738 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
D/UEI.SmartControl( 7620): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 7620): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 7620): QS saving settings...
D/UEI.SmartControl( 7620): IR Blaster version: 25672567
,D/UEI.SmartControl( 7620): serial port data available: 4
,I/UEI.SmartControl( 7620): Device manager: loading config....
D/UEI.SmartControl( 7620): ----------- loading internal config...
E/UEI.SmartControl( 7620): Loading SETTINGS...
W/ContextImpl( 7620): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,E/UEI.SmartControl( 7620): Services init done
D/UEI.SmartControl( 7620): QS Service init finished
D/UEI.SmartControl( 7620): QS Service version name: 2.1.91
D/UEI.SmartControl( 7620): QS Service version code: 201091
D/UEI.SmartControl( 7620): Service requested: Control
,D/UEI.SmartControl( 7620): -- Open brand translation xml: brands_translations_ko
I/ActivityManager( 1026): Killing 7143:com.google.android.gms:car/u0a5 (adj 15): empty #17
,I/UEI.SmartControl( 7620): Notify AllClients services are ready: 0
,D/UEI.SmartControl( 7620): -----service ready thread exits
,W/libprocessgroup( 1026): failed to open /acct/uid_10005/pid_7143/cgroup.procs: No such file or directory
,E/ActivityThread( 7620): Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@57adf6f that was originally bound here
E/ActivityThread( 7620): android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@57adf6f that was originally bound here
E/ActivityThread( 7620): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1167)
E/ActivityThread( 7620): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1061)
E/ActivityThread( 7620): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1839)
E/ActivityThread( 7620): 	at android.app.ContextImpl.bindService(ContextImpl.java:1822)
E/ActivityThread( 7620): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 7620): 	at com.uei.control.Service.b(Unknown Source)
E/ActivityThread( 7620): 	at com.uei.control.Service.a(Unknown Source)
E/ActivityThread( 7620): 	at com.uei.control.Service.onCreate(Unknown Source)
E/ActivityThread( 7620): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
E/ActivityThread( 7620): 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
E/ActivityThread( 7620): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
E/ActivityThread( 7620): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 7620): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 7620): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
E/ActivityThread( 7620): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 7620): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 7620): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
E/ActivityThread( 7620): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,D/UEI.SmartControl( 7620): Internal service binding...
D/PCSuite ( 7675): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7501): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,D/WiFiOffLoadBroadcast( 7501): MCCMNC not supported: null
,W/FormManager( 7738): Network not available. Please check & try again.
,D/PostponalbeReceiver( 7562): WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
V/QRemote ( 7707): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,D/QRemote ( 7707): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 7707): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
V/FormManager( 7738): Network unavailable.
V/FormManager( 7738): Network unavailable.
I/ActivityManager( 1026): Killing 7219:com.lge.appbox.client/u0a11 (adj 15): empty #17
,D/LgDataFeature( 7707): LgDataFeature() Constructor: none
,D/LgDataFeature( 7707): LgDataFeature() Constructor Done, null
,V/SoundPool( 7707): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
,V/SoundPool( 7707): load: fd=30, offset=10857164, length=17813, priority=1
,V/SoundPool( 7707): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 7707): doLoad: loading sample sampleID=1
I/QRemote ( 7707): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
V/SoundPool( 7707): Start decode
V/MediaPlayer[Native]( 7707): decode(31, 10857164, 17813)
V/MediaPlayerService(  331): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  331): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  331): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  331): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  331): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  331): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  331): player type = 3
V/AwesomePlayer(  331): AwesomePlayer create()
V/AwesomePlayer(  331): reset_l() 
V/AwesomePlayer(  331): cancelPlayerEvents
V/AwesomePlayer(  331): setAudioSink() 
V/AwesomePlayer(  331): reset_l() 
V/AudioCache(  331): notify(0xb5474740, 8, 0, 0)
V/AudioCache(  331): ignored
V/AwesomePlayer(  331): cancelPlayerEvents
D/Utils   (  331): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  331): setDataSource_l dataSource
V/LGParserOSAL(  331): SniffLGParser start
V/LGParserOSAL(  331): MainType:5, SubType=0
V/LGParserOSAL(  331): #### check Mime : application/ogg
V/LGParserOSAL(  331): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  331): Use LGExtractor :application/ogg 
,V/LGParserOSAL(  331): supported mime: application/ogg
,V/AwesomePlayer(  331): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  331): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  331): mBitrate = -1 bits/sec
V/AwesomePlayer(  331): AudioTrack Setting
V/AwesomePlayer(  331): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  331): setAudioSource() 
V/MediaPlayerService(  331): prepare
V/AwesomePlayer(  331): prepareAsync_l() 
V/MediaPlayerService(  331): wait for prepare
V/AwesomePlayer(  331): onPrepareAsyncEvent() 
V/AwesomePlayer(  331): initAudioDecoder() 
W/Utils   (  331): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  331): isOffloadSupported()
V/AudioPolicyManager(  331): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  331): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  331): isAudioPlaybackHookOn() false
V/AwesomePlayer(  331): getUseOffload() = 0 
V/OMXCodec(  331): OMXCodec::Create
V/OMXCodec(  331): findMatchingCodecs()
V/OMXCodec(  331): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  331): matchingCodecs.size()=1
V/OMXCodec(  331): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
W/libprocessgroup( 1026): failed to open /acct/uid_10011/pid_7219/cgroup.procs: No such file or directory
D/OMXCodec(  331): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  331): LG Codec Adapter start
V/OMXCodec(  331): OMXCodec Createtor
V/OMXCodec(  331): setComponentRole
V/OMXCodec(  331): configureCodec protected=0
V/LGCodecAdapter(  331): called getLGCodecSpecificData
V/LGCodecOSAL(  331): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  331): Called LGconfigureCodecMETA
V/LGCodecOSAL(  331): Called LGconfigureCodecMSG
V/LGCodecOSAL(  331): Not support LGCodec
V/OMXCodec(  331): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  331): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  331): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  331): Could not offload audio decode, try pcm offload
W/Utils   (  331): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  331): isOffloadSupported()
V/AudioPolicyManager(  331): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  331): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  331): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  331): init()
V/OMXCodec(  331): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  331): allocateBuffers
V/OMXCodec(  331): allocateBuffersOnPort portIndex=0
V/OMXCodec(  331): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  331): [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on input port
V/OMXCodec(  331): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on input port
V/OMXCodec(  331): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on input port
V/OMXCodec(  331): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on input port
V/OMXCodec(  331): allocateBuffersOnPort portIndex=1
V/OMXCodec(  331): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  331): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d30 on output port
V/OMXCodec(  331): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7dd0 on output port
V/OMXCodec(  331): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e20 on output port
V/OMX,Codec(  331): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ec0 on output port
V/OMXCodec(  331): init() mAsyncCompletion wait!!! 
V/OMXCodec(  331): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  331): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  331): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  331): init() mAsyncCompletion wait!!! 
D/QRemote ( 7707): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
V/OMXCodec(  331): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  331): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  331): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  331): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  331): finishAsyncPrepare_l() 
V/AudioCache(  331): notify(0xb5474740, 5, 0, 0)
V/AudioCache(  331): ignored
V/AudioCache(  331): notify(0xb5474740, 1, 0, 0)
V/AudioCache(  331): prepared
V/AudioCache(  331): wait - success
V/MediaPlayerService(  331): start
V/AwesomePlayer(  331): play_l() 
V/AwesomePlayer(  331): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  331): createAudioPlayer_l
V/AwesomePlayer(  331): seekAudioIfNecessary_l() 
V/AwesomePlayer(  331): startAudioPlayer_l() 
D/AudioPlayer(  331): start of Playback, useOffload 0
V/OMXCodec(  331): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  331): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
E/QRemote ( 7707): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7707): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
V/OMXCodec(  331): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  331): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  331): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  331): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  331): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  331): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  331): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885488
V/OMXCodec(  331): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  331): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885648
V/OMXCodec(  331): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  331): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885728
V/OMXCodec(  331): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  331): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885888
V/OMXCodec(  331): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  331): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  331): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  331): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  331): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  331): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  331): allocateBuffersOnPort portIndex=1
V/OMXCodec(  331): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  331): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e20 on output port
V/OMXCodec(  331): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7dd0 on output port
V/OMXCodec(  331): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d30 on output port
V/OMXCodec(  331): [OMX.google.vorbis.decoder] allocated buffer 0xb57c35b0 on output port
V/OMXCodec(  331): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  331): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  331): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  331): notify(0xb5474740, 6, 0, 0)
V/AudioCache(  331): ignored
V/MediaPlayerService(  331): wait for playback complete
V/AudioCache(  331): write(0xb16ac000, 4096)
V/AudioCache(  331): memcpy(0xab602000, 0xb16ac000, 4096)
V/AudioCache(  331): write(0xb16ac000, 4096)
V/AudioCache(  331): memcpy(0xab603000, 0xb16ac000, 4096)
V/AudioCache(  331): write(0xb16ac000, 4096)
V/AudioCache(  331): memcpy(0xab604000, 0xb16ac000, 4096)
V/AudioCache(  331): write(0xb16ac000, 4096)
V/AudioCache(  331): memcpy(0xab605000, 0xb16ac000, 4096)
V/AudioCache(  331): write(0xb16ac000, 4096)
V/AudioCache(  331): memcpy(0xab606000, 0xb16ac000, 4096)
V/AudioCache(  331): write(0xb16ac000, 4096)
V/AudioCache(  331): memcpy(0xab607000, 0xb16ac000, 4096)
V/AudioCache(  331): write(0xb16ac000, 4096)
V/AudioCache(  331): memcpy(0xab608000, 0xb16ac000, 4096)
V/LGMDMManager( 7707): Create singleton instance
V/AudioCache(  331): write(0xb16ac000, 4096)
V/AudioCache(  331): memcpy(0xab609000, 0xb16ac000, 4096)
V/AudioCache(  331): write(0xb16ac000, 4096)
V/AudioCache(  331): memcpy(0xab60a000, 0xb16ac000, 4096)
V/AudioCache(  331): write(0xb16ac000, 4096)
V/AudioCache(  331): memcpy(0xab60b000, 0xb16ac000, 4096)
V/AudioCache(  331): write(0xb16ac000, 4096)
V/AudioCache(  331): memcpy(0xab60c000, 0xb16ac000, 4096)
V/AudioCache(  331): write(0xb16ac000, 4096)
V/AudioCache(  331): memcpy(0xab60d000, 0xb16ac000, 4096)
V/AudioCache(  331): write(0xb16ac000, 4096)
V/AudioCache(  331): memcpy(0xab60e000, 0xb16ac000, 4096)
V/AudioCache(  331): write(0xb16ac000, 4096)
V/AudioCache(  331): memcpy(0xab60f000, 0xb16ac000, 4096)
V/AudioCache(  331): write(0xb16ac000, 4096)
V/AudioCache(  331): memcpy(0xab610000, 0xb16ac000, 4096)
,V/AudioCache(  331): write(0xb16ac000, 4096)
V/AudioCache(  331): memcpy(0xab611000, 0xb16ac000, 4096)
V/AudioCache(  331): write(0xb16ac000, 4096)
V/AudioCache(  331): memcpy(0xab612000, 0xb16ac000, 4096)
V/AudioCache(  331): write(0xb16ac000, 4096)
V/AudioCache(  331): memcpy(0xab613000, 0xb16ac000, 4096)
V/AudioCache(  331): write(0xb16ac000, 4096)
V/AudioCache(  331): memcpy(0xab614000, 0xb16ac000, 4096)
V/AudioCache(  331): write(0xb16ac000, 4096)
V/AudioCache(  331): memcpy(0xab615000, 0xb16ac000, 4096)
V/AudioCache(  331): write(0xb16ac000, 4096)
V/AudioCache(  331): memcpy(0xab616000, 0xb16ac000, 4096)
V/AudioCache(  331): write(0xb16ac000, 4096)
V/AudioCache(  331): memcpy(0xab617000, 0xb16ac000, 4096)
V/AudioCache(  331): write(0xb16ac000, 4096)
V/AudioCache(  331): memcpy(0xab618000, 0xb16ac000, 4096)
V/AudioCache(  331): write(0xb16ac000, 4096)
V/AudioCache(  331): memcpy(0xab619000, 0xb16ac000, 4096)
V/AudioCache(  331): write(0xb16ac000, 4096)
V/AudioCache(  331): memcpy(0xab61a000, 0xb16ac000, 4096)
V/AudioCache(  331): write(0xb16ac000, 4096)
V/AudioCache(  331): memcpy(0xab61b000, 0xb16ac000, 4096)
V/AudioCache(  331): write(0xb16ac000, 4096)
V/AudioCache(  331): memcpy(0xab61c000, 0xb16ac000, 4096)
V/AudioCache(  331): write(0xb16ac000, 4096)
V/AudioCache(  331): memcpy(0xab61d000, 0xb16ac000, 4096)
V/AudioCache(  331): write(0xb16ac000, 4096)
V/AudioCache(  331): memcpy(0xab61e000, 0xb16ac000, 4096)
V/AudioCache(  331): write(0xb16ac000, 4096)
V/AudioCache(  331): memcpy(0xab61f000, 0xb16ac000, 4096)
V/AudioCache(  331): write(0xb16ac000, 4096)
V/AudioCache(  331): memcpy(0xab620000, 0xb16ac000, 4096)
V/AudioCache(  331): write(0xb16ac000, 4096)
V/AudioCache(  331): memcpy(0xab621000, 0xb16ac000, 4096)
V/AudioCache(  331): write(0xb16ac000, 4096)
V/AudioCache(  331): memcpy(0xab622000, 0xb16ac000, 4096)
V/AudioCache(  331): write(0xb16ac000, 4096)
V/AudioCache(  331): memcpy(0xab623000, 0xb16ac000, 4096)
V/AudioCache(  331): write(0xb16ac000, 4096)
V/AudioCache(  331): memcpy(0xab624000, 0xb16ac000, 4096)
V/AudioCache(  331): write(0xb16ac000, 4096)
V/AudioCache(  331): memcpy(0xab625000, 0xb16ac000, 4096)
V/AudioCache(  331): write(0xb16ac000, 4096)
V/AudioCache(  331): memcpy(0xab626000, 0xb16ac000, 4096)
V/AudioCache(  331): write(0xb16ac000, 4096)
V/AudioCache(  331): memcpy(0xab627000, 0xb16ac000, 4096)
V/AudioCache(  331): write(0xb16ac000, 4096)
V/AudioCache(  331): memcpy(0xab628000, 0xb16ac000, 4096)
V/AudioCache(  331): write(0xb16ac000, 4096)
V/AudioCache(  331): memcpy(0xab629000, 0xb16ac000, 4096)
V/AudioCache(  331): write(0xb16ac000, 4096)
V/AudioCache(  331): memcpy(0xab62a000, 0xb16ac000, 4096)
V/AudioCache(  331): write(0xb16ac000, 4096)
V/AudioCache(  331): memcpy(0xab62b000, 0xb16ac000, 4096)
V/AudioCache(  331): write(0xb16ac000, 4096)
V/AudioCache(  331): memcpy(0xab62c000, 0xb16ac000, 4096)
V/AudioCache(  331): write(0xb16ac000, 4096)
V/AudioCache(  331): memcpy(0xab62d000, 0xb16ac000, 4096)
V/AudioCache(  331): write(0xb16ac000, 4096)
V/AudioCache(  331): memcpy(0xab62e000, 0xb16ac000, 4096)
V/AudioCache(  331): write(0xb16ac000, 4096)
V/AudioCache(  331): memcpy(0xab62f000, 0xb16ac000, 4096)
V/AudioCache(  331): write(0xb16ac000, 4096)
V/AudioCache(  331): memcpy(0xab630000, 0xb16ac000, 4096)
,V/AudioCache(  331): write(0xb16ac000, 4096)
V/AudioCache(  331): memcpy(0xab631000, 0xb16ac000, 4096)
V/AudioCache(  331): write(0xb16ac000, 4096)
V/AudioCache(  331): memcpy(0xab632000, 0xb16ac000, 4096)
V/AudioCache(  331): write(0xb16ac000, 4096)
V/AudioCache(  331): memcpy(0xab633000, 0xb16ac000, 4096)
V/OMXCodec(  331): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  331): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  331): postAudioEOS() 
V/AudioCache(  331): write(0xb16ac000, 280)
V/AudioCache(  331): memcpy(0xab634000, 0xb16ac000, 280)
V/AwesomePlayer(  331): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  331): onStreamDone
V/AwesomePlayer(  331): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  331): notify(0xb5474740, 2, 0, 0)
V/AudioCache(  331): playback complete
V/AwesomePlayer(  331): pause_l() 
V/AudioCache(  331): notify(0xb5474740, 7, 0, 0)
V/AudioCache(  331): ignored
V/AwesomePlayer(  331): cancelPlayerEvents
D/AudioPlayer(  331): Pause Playback at 1068125
V/AudioCache(  331): wait - success
V/MediaPlayerService(  331): return size 205080, sampleRate=48000, channelCount = 2, format = 1
V/AwesomePlayer(  331): reset_l() 
V/AudioCache(  331): notify(0xb5474740, 8, 0, 0)
V/AudioCache(  331): ignored
V/AwesomePlayer(  331): cancelPlayerEvents
D/AudioPlayer(  331): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  331): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  331): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  331): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  331): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  331): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  331): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  331): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  331): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7bf0 on port 0
V/OMXCodec(  331): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  331): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 0
V/OMXCodec(  331): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  331): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 0
V/OMXCodec(  331): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  331): [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 0
V/OMXCodec(  331): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  331): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  331): [OMX.google.vorbis.decoder] freeing buffer 0xb57c35b0 on port 1
V/OMXCodec(  331): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  331): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7d30 on port 1
V/OMXCodec(  331): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  331): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7dd0 on port 1
V/OMXCodec(  331): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  331): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7e20 on port 1
V/OMXCodec(  331): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  331): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  331): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  331): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  331): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  331): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  331): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  331): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  331): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  331): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
V/OMXCodec(  331): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPla,yer(  331): AudioPlayer releasing audio source
D/AudioPlayer(  331): AudioPlayer done releasing audio source
V/AwesomePlayer(  331): reset_l() 
V/AwesomePlayer(  331): cancelPlayerEvents
V/AwesomePlayer(  331): ~AwesomePlayer call
V/AwesomePlayer(  331): reset_l() 
V/AwesomePlayer(  331): cancelPlayerEvents
V/SoundPool( 7707): close(31)
V/SoundPool( 7707): pointer = 0x9ffd5000, size = 205080, sampleRate = 48000, numChannels = 2
D/QRemote ( 7707): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7707): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
D/QRemote ( 7707): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:4298
,D/PostponalbeReceiver( 7562): WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
I/QRemote ( 7707): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 7620): ------ IControl API: 11
D/UEI.SmartControl( 7620): File observer start...
E/UEI.SmartControl( 7620): IR Port is disabled: false
D/UEI.SmartControl( 7620): Starting file observer...
I/UEI.SmartControl( 7620): Registering callback...
D/LGDMClient( 3990): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
I/UEI.SmartControl( 7620): ------ IControl API: 19
D/LGDMClient( 3990): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
I/UEI.SmartControl( 7620): Registering Services Ready callback...
I/UEI.SmartControl( 7620): Notify client services are ready...
I/QRemote ( 7707): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 7707): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 7707): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
W/ContextImpl( 3990): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,D/QRemote ( 7707): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 7707): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 7620): ------ IControl API: 8
D/QRemote ( 7707): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
W/ContextImpl( 3990): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/QRemote ( 7707): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 7707): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 7707): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 7707): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7707): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/LGDMClient( 3990): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/QRemote ( 7707): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,D/LGDMClient( 3990): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 3990): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/PCSuite ( 7675): [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
D/PCSuite ( 7675): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7675): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/QRemote ( 7707): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
V/WiFiOffLoadBroadcast( 7501): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,W/FormManager( 7738): Network not available. Please check & try again.
,V/FormManager( 7738): Network unavailable.
V/FormManager( 7738): Network unavailable.
D/WiFiOffLoadBroadcast( 7501): MCCMNC not supported: null
I/ActivityManager( 1026): Killing 7254:com.android.contacts/u0a19 (adj 15): empty #17
,W/libprocessgroup( 1026): failed to open /acct/uid_10019/pid_7254/cgroup.procs: No such file or directory
,D/PowerManagerServiceEx( 1026): releaseWakeLockInternal: lock=631714865 [*alarm*], flags=0x0
,V/QRemote ( 7707): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/libc-netbsd(  327): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1026): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/QRemote ( 7707): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 7707): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,D/QRemote ( 7707): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 7707): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7707): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 7707): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
,D/QRemote ( 7707): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1454701431317]
D/ConnectivityService( 1026): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1026): MasterInitialState.processMessage what=3
D/GpsLocationProvider( 1026): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1026): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/PostponalbeReceiver( 7562): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,D/Tethering( 1026): MasterInitialState.processMessage what=3
I/NetworkMonitor( 5256): type=WIFI subType= reason=null isConnected=false
,W/ContextImpl( 7562): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,D/GpsLocationProvider( 1026): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1026): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1026): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NetworkMonitor( 5256): type=WIFI subType= reason=null isConnected=false
,D/QRemote ( 7707): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
I/ActivityManager( 1026): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7784 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/art     (  352): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 474us total 22.737ms
,I/art     (  352): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 445us total 20.602ms
I/art     (  352): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 441us total 20.622ms
,I/AppUp4:AppBoxCP( 7784): onCreate
,W/AppUp4:DB( 7784):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7784):  setFingerPrint start
,I/AppUp4:DB( 7784):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 7784):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7784):  SDK version = 21
I/AppUp4:DB( 7784):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7784): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7784): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7784): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 7784): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7784): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7784): onReceive
D/LgDataFeature( 7784): LgDataFeature() Constructor: none
D/LgDataFeature( 7784): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7784): Context : android.app.ReceiverRestrictedContext@102f0513
D/AppUp4:CustFacade( 7784): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 7784): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7784): begin check event
I/AppUp4:CustModeStarterReceiver( 7784): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7784): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7784): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7784): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7784): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1026): Killing 7281:com.android.gallery3d/u0a27 (adj 15): empty #17
W/libprocessgroup( 1026): failed to open /acct/uid_10027/pid_7281/cgroup.procs: No such file or directory
,D/LGDMClient( 3990): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3990): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 3990): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 3990): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/LGDMClient( 3990): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,D/LGDMClient( 3990): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3990): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/ActivityManager( 1026): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7805 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,W/ResourcesManager( 7805): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7805): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7805): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,W/ResourcesManager( 7805): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/LGEmail ( 7805): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7805): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,W/ResourceType( 7805): No package identifier when getting value for resource number 0x00000000
,D/LgDataFeature( 7805): LgDataFeature() Constructor: none
,D/LgDataFeature( 7805): LgDataFeature() Constructor Done, null
,D/eas_req ( 7805): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,W/FormManager( 7738): Network not available. Please check & try again.
,I/HubEmail( 7805): JNI_OnLoad()
V/FormManager( 7738): Network unavailable.
I/HubEmail( 7805): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7805): registerNatives()
I/HubEmail( 7805): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7805): registerNativeMethods()
I/HubEmail( 7805): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7805): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
V/FormManager( 7738): Network unavailable.
W/Settings( 7805): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager( 1026): Killing 7319:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,I/LgeMiscReceiver( 3243): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3243): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3243): networkInfo.isConnected() = false
W/libprocessgroup( 1026): failed to open /acct/uid_10080/pid_7319/cgroup.procs: No such file or directory
,I/ActivityManager( 1026): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7838 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1026): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7860 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,I/ActivityManager( 1026): Killing 6651:com.google.android.apps.plus/u0a97 (adj 15): empty #17
W/libprocessgroup( 1026): failed to open /acct/uid_10097/pid_6651/cgroup.procs: No such file or directory
,I/ActivityManager( 1026): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7877 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1026): Killing 7005:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
,W/libprocessgroup( 1026): failed to open /acct/uid_10005/pid_7005/cgroup.procs: No such file or directory
,I/art     ( 7877): Almond Protected OAT
,D/WeatherApplication( 7877): removeAccount
,D/WeatherApplication( 7877): Account.length = 0
E/WeatherApplication( 7877): OPERATOR:OPEN
,D/WeatherAncestor( 7877): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 20:43:53
D/Weather.Utils( 7877): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7877): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7877): 2 : This is isUpdating : false
,D/WeatherAncestor( 7877): connectivity changed - connection : true
,D/WeatherService( 7877): 2 : isServiceAlived():false forecastCache:null
D/ForecastDataCache( 7877): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7877): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7877): 2 : Cache is not up-to-date, count: 0
,D/Weather_cast( 7877): 2 : isUpdateNeedForAlarm : no city return false
,D/WeatherAncestor( 7877): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 20:43:53
,I/ActivityManager( 1026): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7900 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1026): Killing 6949:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,W/libprocessgroup( 1026): failed to open /acct/uid_10061/pid_6949/cgroup.procs: No such file or directory
,D/LGWifiP2pService( 1026): P2pDisabledState{ when=-5ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1026): DefaultState{ when=-5ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 1026):  InitialState CMD_STOP_SUPPLICANT_FAILED 1 0
E/WifiStateMachine( 1026):  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7900): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7900): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7900): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7900): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/WebViewFactory( 7900): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7900): Loading: webviewchromium
,I/LibraryLoader( 7900): Time to load native libraries: 7 ms (timestamps 5020-5027)
I/LibraryLoader( 7900): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7900): Binding Chromium to main looper Looper (main, tid 1) {15d2a4ac}
,I/LibraryLoader( 7900): Expected native library version number "",actual native library version number ""
I/chromium( 7900): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7900): Initializing chromium process, renderers=0
,W/art     ( 7900): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 7900): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7900): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
,I/chromium( 7900): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
V/AudioPolicyService(  331): registerClient() client 0xb54f40c0, uid 10093
W/AudioManagerAndroid( 7900): Requires BLUETOOTH permission
I/Adreno-EGL( 7900): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7900): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7900): Build Date: 12/12/14 금
I/Adreno-EGL( 7900): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7900): Remote Branch: 
I/Adreno-EGL( 7900): Local Patches: 
I/Adreno-EGL( 7900): Reconstruct Branch: 
,I/NSApplication( 7900): Starting up...
,I/ActivityManager( 1026): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7956 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1026): Killing 6454:com.google.android.apps.books/u0a54 (adj 15): empty #17
W/libprocessgroup( 1026): failed to open /acct/uid_10054/pid_6454/cgroup.procs: No such file or directory
,W/ResourcesManager( 7956): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,E/UEI.SmartControl( 7620): file observer is disposed!
,I/iu.Environment( 2361): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 2361): num queued entries: 0
I/iu.UploadsManager( 2361): num updated entries: 0
I/iu.SyncManager( 2361): NEXT; no task
D/ChimeraCfgMgr( 2361): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/PostponalbeReceiver( 7562): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 7562): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/NetworkStateForAutoUpdateMonitor( 7784): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7784): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7784): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7784): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7784): onReceive
,I/GLSActivity( 2135): [ac] getting account id
,D/AppUp4:CustFacade( 7784): Context : android.app.ReceiverRestrictedContext@102f0513
D/AppUp4:CustFacade( 7784): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7784): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7784): begin check event
I/AppUp4:CustModeStarterReceiver( 7784): Event For GoodConnectivity, noConnectivity : false, but skip! 
,D/LGDMClient( 3990): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 3990): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 3990): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
I/GLSUser ( 2135): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
W/ContextImpl( 3990): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,D/LGDMClient( 3990): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/eas_req ( 7805): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
D/LGDMClient( 3990): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3990): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,W/Settings( 7805): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/LgeMiscReceiver( 3243): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3243): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 3243): networkInfo.isConnected() = false
W/FormManager( 7738): Network not available. Please check & try again.
,D/WeatherAncestor( 7877): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 20:43:54
V/FormManager( 7738): Network unavailable.
D/Weather.Utils( 7877): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7877): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7877): 2 : This is isUpdating : false
D/WeatherAncestor( 7877): connectivity changed - connection : true
D/WeatherService( 7877): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1c389949
V/FormManager( 7738): Network unavailable.
D/ForecastDataCache( 7877): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7877): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7877): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7877): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7877): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 20:43:54
,D/ChimeraCfgMgr( 2361): Loading module com.google.android.gms.kids from APK com.google.android.gms
,V/QRemote ( 7707): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,E/QRemote ( 7707): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,D/QRemote ( 7707): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 7707): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 7707): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 7707): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 7707): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 7707): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,V/AlarmManager( 1026): ELAPSED_WAKEUP set : Alarm{475b21c type 2 when 346872 com.google.android.gms} when 346872
,D/libc-netbsd(  327): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1026): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/serial_port( 7620): close(fd = 24)
,I/UEI.SmartControl( 7620): Serial port is closed.
,D/UEI.SmartControl( 7620): Internal timer expired: 2
D/UEI.SmartControl( 7620): unbind internal service
I/GAV4    ( 7900): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager( 1026): Killing 7093:com.android.vending/u0a44 (adj 15): empty #17
,W/libprocessgroup( 1026): failed to open /acct/uid_10044/pid_7093/cgroup.procs: No such file or directory
,I/ActivityManager( 1026): Killing 7603:com.lge.settings.easy/1000 (adj 15): empty #17
,W/libprocessgroup( 1026): failed to open /acct/uid_1000/pid_7603/cgroup.procs: No such file or directory
,D/PowerManagerServiceEx( 1026): acquireWakeLockInternal: lock=631714865, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1026
,D/[Concierge]Service( 2588): onStartCommand(). Type : 9
,V/QRemote ( 7707): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
D/QRemote ( 7707): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:4298
D/PowerManagerServiceEx( 1026): releaseWakeLockInternal: lock=631714865 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1026): tsOffsetIs: Apps: 358077344451; DSPS: 11874873; Offset : -4330564839
,V/AlarmManager( 1026): ELAPSED_WAKEUP set : Alarm{34b3a5ab type 2 when 375882 android} when 375882
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1026): tsOffsetIs: Apps: 378079428714; DSPS: 12530301; Offset : -4330555850
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1026): tsOffsetIs: Apps: 398082165529; DSPS: 13185751; Offset : -4330565643
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
,I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
,D/PowerManagerServiceEx( 1026): acquireWakeLockInternal: lock=631714865, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1026
,I/ActivityManager( 1026): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=8033 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,D/[Concierge]Service( 2588): onStartCommand(). Type : 9
,I/art     ( 1026): Explicit concurrent mark sweep GC freed 42954(1970KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 1.744ms total 80.113ms
,I/DigitalAppWidgetProvider( 8033): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 8033): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@283f1ce4
D/PowerManagerServiceEx( 1026): releaseWakeLockInternal: lock=631714865 [*alarm*], flags=0x0
,I/ActivityManager( 1026): Killing 7544:com.lge.lifetracker/u0a37 (adj 15): empty #17
W/libprocessgroup( 1026): failed to open /acct/uid_10037/pid_7544/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1026): tsOffsetIs: Apps: 418083898230; DSPS: 13841167; Offset : -4330541822
,I/[SystemUI]LGPowerUI( 1465): onReceive = com.lge.android.intent.action.BATTERYEX
,I/[SystemUI]LGPowerUI( 1465): On Skip Timer : true
,D/LEDHandler( 1960): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1960): Battery Level Remaining: 100%
D/LEDHandler( 1960): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
,D/KeyguardUpdateMonitor( 1465): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
,D/WifiController( 1026): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1465): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1465): onReceive = android.intent.action.BATTERY_CHANGED
,D/LGDMClient( 3990): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3990): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: msg_type 2,
D/sensors_hal_Time( 1026): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1026): tsOffsetIs: Apps: 438085997337; DSPS: 14496596; Offset : -4330548558
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1026): tsOffsetIs: Apps: 458088100193; DSPS: 15152025; Offset : -4330551441
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
,I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1026): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1026): tsOffsetIs: Apps: 478089978103; DSPS: 15807447; Offset : -4330565595
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1026): tsOffsetIs: Apps: 498092050283; DSPS: 16462874; Offset : -4330538015
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1026): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1026): tsOffsetIs: Apps: 518093299442; DSPS: 17118276; Offset : -4330570803
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
,I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1026): tsOffsetIs: Apps: 538094996101; DSPS: 17773691; Offset : -4330552429
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1026): tsOffsetIs: Apps: 558096609687; DSPS: 18429104; Offset : -4330556377
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1026): tsOffsetIs: Apps: 578098703117; DSPS: 19084533; Offset : -4330568531
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
,I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
,I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
D/sensors_hal_Time( 1026): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1026): tsOffsetIs: Apps: 598101200505; DSPS: 19739974; Offset : -4330543067
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1026): tsOffsetIs: Apps: 618103283466; DSPS: 20395403; Offset : -4330565974
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1026): tsOffsetIs: Apps: 638105367625; DSPS: 21050831; Offset : -4330556906
,D/PowerManagerServiceEx( 1026): acquireWakeLockInternal: lock=631714865, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1026
,D/[Concierge]Service( 2588): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1026): releaseWakeLockInternal: lock=631714865 [*alarm*], flags=0x0
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
,I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1026): tsOffsetIs: Apps: 658107472669; DSPS: 21706260; Offset : -4330557549
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1026): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1026): tsOffsetIs: Apps: 678121585527; DSPS: 22362083; Offset : -4330574461
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1026): tsOffsetIs: Apps: 698123497759; DSPS: 23017505; Offset : -4330554110
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
,I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
,I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
D/sensors_hal_Time( 1026): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1026): tsOffsetIs: Apps: 718125603011; DSPS: 23672934; Offset : -4330554623,
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1026): tsOffsetIs: Apps: 738127641441; DSPS: 24328361; Offset : -4330560871
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1026): tsOffsetIs: Apps: 758129484402; DSPS: 24983781; Offset : -4330549042
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
,I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1026): tsOffsetIs: Apps: 778132283926; DSPS: 25639233; Offset : -4330557005
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1026): tsOffsetIs: Apps: 798134250116; DSPS: 26294657; Offset : -4330543966
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1026): tsOffsetIs: Apps: 818136272921; DSPS: 26950084; Offset : -4330566022
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
,I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
,I/[SystemUI]DateView( 1465): called onTimeUpdated()
,I/[SystemUI]DateView( 1465): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1026): tsOffsetIs: Apps: 838138443226; DSPS: 27605515; Offset : -4330562257
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1026): tsOffsetIs: Apps: 858140953062; DSPS: 28260957; Offset : -4330555018
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1026): tsOffsetIs: Apps: 878143061023; DSPS: 28916386; Offset : -4330552743
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
,I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
,I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
D/sensors_hal_Time( 1026): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1026): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1026): tsOffsetIs: Apps: 898150365339; DSPS: 29571985; Offset : -4330542025
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1026): tsOffsetIs: Apps: 918152443144; DSPS: 30227414; Offset : -4330569984
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1026): tsOffsetIs: Apps: 938154506469; DSPS: 30882841; Offset : -4330551311
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
,I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1026): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1026): tsOffsetIs: Apps: 958156484899; DSPS: 31538266; Offset : -4330556524
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1026): tsOffsetIs: Apps: 978158321974; DSPS: 32193686; Offset : -4330550425
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1026): tsOffsetIs: Apps: 998160939988; DSPS: 32849132; Offset : -4330557028
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated(),
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
,I/[SystemUI]DateView( 1465): called onTimeUpdated()
,I/[SystemUI]DateView( 1465): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1026): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0,
D/sensors_hal_Time( 1026): tsOffsetIs: Apps: 1018162584043; DSPS: 33504546; Offset : -4330560895
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1026): tsOffsetIs: Apps: 1038164621327; DSPS: 34159972; Offset : -4330537798
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1026): tsOffsetIs: Apps: 1058166273246; DSPS: 34815387; Offset : -4330564345
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
,I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
,I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
D/sensors_hal_Time( 1026): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1026): tsOffsetIs: Apps: 1078168185426; DSPS: 35470809; Offset : -4330544203
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1026): tsOffsetIs: Apps: 1098170912762; DSPS: 36126259; Offset : -4330563397
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1026): tsOffsetIs: Apps: 1118172793692; DSPS: 36781680; Offset : -4330544169
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
,I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
D/sensors_hal_Time( 1026): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1026): tsOffsetIs: Apps: 1138174898059; DSPS: 37437109; Offset : -4330545464
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1026): tsOffsetIs: Apps: 1158176894301; DSPS: 38092535; Offset : -4330563563
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1026): tsOffsetIs: Apps: 1178178784242; DSPS: 38747957; Offset : -4330565608
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
,I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: msg_type 2,
D/sensors_hal_Time( 1026): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1026): tsOffsetIs: Apps: 1198180363089; DSPS: 39403369; Offset : -4330573702
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1026): tsOffsetIs: Apps: 1218182033186; DSPS: 40058783; Offset : -4330551397
,I/UsageStatsService( 1026): User[0] Flushing usage stats to disk
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1026): tsOffsetIs: Apps: 1238184109428; DSPS: 40714211; Offset : -4330550351
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
,I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
,I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
D/sensors_hal_Time( 1026): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1026): tsOffsetIs: Apps: 1258186207232; DSPS: 41369640; Offset : -4330558338
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1026): tsOffsetIs: Apps: 1278188031339; DSPS: 42025060; Offset : -4330565129
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1026): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1026): tsOffsetIs: Apps: 1298191642894; DSPS: 42680538; Offset : -4330554753
,I/[SystemUI]TimeTickManager( 1465): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1465): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1465): called onTimeUpdated()
,I/[SystemUI]Clock( 1465): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1465): called onTimeUpdated()
,I/[SystemUI]DateView( 1465): called onTimeUpdated()
I/[SystemUI]DateView( 1465): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1465): handleTimeUpdate
,D/PowerManagerServiceEx( 1026): acquireWakeLockInternal: lock=631714865, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1026
,D/[Concierge]Service( 2588): onStartCommand(). Type : 9
,I/DigitalAppWidgetProvider( 8033): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 8033): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@283f1ce4
,D/PowerManagerServiceEx( 1026): releaseWakeLockInternal: lock=631714865 [*alarm*], flags=0x0
D/sensors_hal_Time( 1026): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1026): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1026): tsOffsetIs: Apps: 1318195196793; DSPS: 43336015; Offset : -4330571619
,TIME-OUT KILL (timeout was 1200000ms)
```
