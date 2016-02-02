#### Test 575312431f256a6_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
I/MusicWidget( 2630): mDelayedStopHandler : unbind
I/MusicBrowser( 2115): [MediaPlaybackService.java:2869:onUnbind()] oooooo 
I/MusicBrowser( 2115): [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2115): [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2115): [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2115): [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2115): [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2115): [MediaPlaybackService.java:2046:onDestroy()] oooooo 
I/MusicBrowser( 2115): [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
I/MediaFocusControl( 1033):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@c2a6338com.lge.music.MediaPlaybackService$5@d977f11
D/MusicBrowser( 2115): [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2115): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2115): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2115): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2115): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@2e7e1587
I/MusicBrowser( 2115): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2115): [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2115): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2115): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2115): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2115): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2115): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2115): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2115): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2115): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2115): [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2115): [MediaPlaybackService.java:6704:release()] oooooo 
I/MusicBrowser( 2115): [MediaPlaybackService.java:6665:stop()] oooooo 
V/MediaPlayer[Native]( 2115): reset
V/MediaPlayer[Native]( 2115): setListener
V/MediaPlayer[Native]( 2115): disconnect
V/MediaPlayer[Native]( 2115): destructor
V/AudioFlinger(  318): releasing 13 from 2115 for -1
V/AudioFlinger(  318):  decremented refcount to 0
V/AudioFlinger(  318): purging stale effects
V/MediaPlayer[Native]( 2115): disconnect
D/MusicBrowser( 2115): [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
I/SmartShareClient( 2115): [SmartShareManagerClient] smartshare client supported version code: 305000
I/SmartShareClient( 2115): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2115): [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
I/MusicBrowser( 2115): [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2115): [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2115): [SmartShareManagerClient] unregisterListener: 173963382
W/SmartShareClient( 2115): [SmartShareManagerClient] unregisterListener invalid listener: 173963382
I/SmartShareClient( 2115): [SmartShareManagerClient] terminate service: 2115/MediaPlaybackService/658297381
E/HomeCloudIF( 2115): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2115): [SmartShareManagerClient] unbindService context:android.app.Application@14316e77
V/CloudHub( 2115): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
V/CloudHub( 2115): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2115): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
D/MusicBrowser( 2115): [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
--------- beginning of system
I/ActivityManager( 1033): Killing 5637:com.android.defcontainer/u0a4 (adj 15): empty #17
I/CloudHub( 2115): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29989
W/libprocessgroup( 1033): failed to open /acct/uid_10004/pid_5637/cgroup.procs: No such file or directory
,D/AndroidRuntime( 5949): 
D/AndroidRuntime( 5949): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5949): CheckJNI is OFF
D/AndroidRuntime( 5949): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1033): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1930): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1033): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1033): setTaskToReturnTo : TaskRecord{24127752 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1033): setTaskToReturnTo : TaskRecord{24127752 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1033): AppWindowTokenEx init.. 
E/GBMv2   (  340): DFP En is all cleared set to be enabled
I/ActivityManager( 1033): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5968 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 5949): Shutting down VM
V/ActivityManager( 1033): Display changed displayId=0
D/DSDPConnection( 1840): Display #0 changed.
D/SplitWindowPolicy( 1930): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1930): topRunningActivity=ActivityInfo{3b08eb40 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1930): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1930): topRunningActivity=ActivityInfo{df9da79 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 5968): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/WebViewFactory( 5968): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 5968): Loading: webviewchromium
,I/LibraryLoader( 5968): Time to load native libraries: 10 ms (timestamps 5801-5811)
I/LibraryLoader( 5968): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5968): Binding Chromium to main looper Looper (main, tid 1) {273cd225}
I/LibraryLoader( 5968): Expected native library version number "",actual native library version number ""
I/chromium( 5968): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5968): Initializing chromium process, renderers=0
W/art     ( 5968): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 5968): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,V/AudioPolicyService(  318): registerClient() client 0xb1427da0, uid 10311
W/chromium( 5968): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 5968): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 5968): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
D/BluetoothManagerService( 1033): Message: 20
D/BluetoothManagerService( 1033): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3f1a094c:true
,D/BluetoothAdapter( 5968): 713748474: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 5968): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5968): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5968): Build Date: 12/12/14 금
I/Adreno-EGL( 5968): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 5968): Remote Branch: 
I/Adreno-EGL( 5968): Local Patches: 
I/Adreno-EGL( 5968): Reconstruct Branch: 
,W/chromium( 5968): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 5968): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 5968): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5968): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 5968): CordovaWebView is running on device made by: LGE
,W/art     ( 5968): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5968): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 5968): Render dirty regions requested: true
I/OpenGLRenderer( 5968): Initialized EGL, version 1.4
D/OpenGLRenderer( 5968): Enabling debug mode 0
D/Atlas   ( 5968): Validating map...
,D/SplitWindow( 1033): check instance of lgWin Window{be72e26 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/LgDataFeature( 5968): LgDataFeature() Constructor: none
D/LgDataFeature( 5968): LgDataFeature() Constructor Done, null
,I/SystemUI[Framework]( 1033): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
,D/PhoneStatusBar( 1463): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
W/PhoneWindowManagerEx( 1033): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1033): setLGSystemUiVisibility(0x0)
,I/[SystemUI]NavigationThemeResource( 1463): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1463):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1463): , Keyguard show=false, IME shown=false, Panel expanded=false
D/StatusBarManagerServiceEx( 1033): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1033): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@22404ac0,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1033): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/ActivityManager( 1033): Displayed com.test.thalitest/.MainActivity: +607ms (total +689ms)
I/Timeline( 5968): Timeline: Activity_idle id: android.os.BinderProxy@37f4baa time:106223
I/Timeline( 1033): Timeline: Activity_windows_visible id: ActivityRecord{17a3fa23 u0 com.test.thalitest/.MainActivity t4} time:106224
,I/chromium( 5968): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 5968): 
,D/JsMessageQueue( 5968): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 5968): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1434991872
,I/chromium( 5968): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 5968): 
,I/chromium( 5968): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/GBMv2   (  340): DFP En is all cleared set to be enabled
E/GBMv2   (  340): Set value is all cleared set the max
I/GBMv2   (  340): DFP Enabled. Ignore VFP set
,I/art     ( 1033): Explicit concurrent mark sweep GC freed 20190(932KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.587ms total 70.904ms
,V/AlarmManager( 1033): RTC_WAKEUP set : Alarm{10a14603 type 0 when 1454434017295 com.android.vending} when 1454434017295
W/ContextImpl( 4159): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,V/SIM_STK ( 1033): Menu title from STK is T-Mobile
,V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2133): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2133): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2133): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2133): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 4855): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 4855): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4855): [1] 5.onFinished: Scheduling replication attempt 1.
W/jxcore-log( 5968): Initializing JXcore engine
W/jxcore-log( 5968): JXcore engine is ready
W/Thread-674( 6021): type=1400 audit(0.0:148): avc: denied { ioctl } for path="socket:[9964]" dev="sockfs" ino=9964 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-674( 6021): type=1400 audit(0.0:149): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-674( 6021): type=1400 audit(0.0:150): avc: denied { ioctl } for path="socket:[10067]" dev="sockfs" ino=10067 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-674( 6021): type=1400 audit(0.0:151): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/Thread-674( 6021): type=1400 audit(0.0:152): avc: denied { ioctl } for path="socket:[27541]" dev="sockfs" ino=27541 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
W/jxcore-log( 5968): Starting JXcore engine
W/jxcore-log( 5968): Platform android
W/jxcore-log( 5968): 
W/jxcore-log( 5968): Process ARCH arm
W/jxcore-log( 5968): 
,I/[SystemUI]TimeTickManager( 1463): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1463): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1463): called onTimeUpdated()
I/[SystemUI]Clock( 1463): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1463): called onTimeUpdated()
I/[SystemUI]DateView( 1463): called onTimeUpdated()
I/[SystemUI]DateView( 1463): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1463): handleTimeUpdate
I/jxcore-log( 5968): JXcore Cordova bridge is ready!
I/jxcore-log( 5968): 
W/jxcore-log( 5968): JXcore engine is started
,I/jxcore-log( 5968): Toggling radios to true
I/jxcore-log( 5968): 
,D/BluetoothManagerService( 1033): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1033): enable():  mBluetooth =null mBinding = false
,D/LocationManagerService( 1033): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1033): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1033): JNI:system_update. Event-4
D/BluetoothManagerService( 1033): Message: 1
D/BluetoothManagerService( 1033): MESSAGE_ENABLE: mBluetooth = null
D/WifiService( 1033): New client listening to asynchronous messages
,I/ActivityManager( 1033): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=6049 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
D/WifiServiceImplEx( 1033): setWifiEnabled: true pid=5968, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1033): setWifiEnabled: true pid=5968, uid=10311
E/WifiService( 1033): Invoking mWifiStateMachine.setWifiEnabled
,I/art     (  344): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 208us total 11.907ms
I/art     (  344): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 284us total 10.618ms
,D/LocationManagerService( 1033): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1033): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1033): JNI:system_update. Event-4
E/WifiStateMachine( 1033):  InitialState CMD_START_SUPPLICANT 0 0
I/LGFTMITEM( 1033): [GET_FTM][id=6], offset=12288
D/WifiServiceImplEx( 1033): disconnect pid=5968, uid=10311, packageName=com.test.thalitest
D/WifiServiceImplEx( 1033): reconnect pid=5968, uid=10311, packageName=com.test.thalitest
I/jxcore-log( 5968): Radios toggled
I/jxcore-log( 5968): 
I/jxcore-log( 5968): My device name is: LGE-LG-D855
I/jxcore-log( 5968): 
E/WifiUtil( 1033): wfc_util_ffile_check_copy(): pid[1033] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
E/WifiUtil( 1033): wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
E/WifiUtil( 1033): wfc_util_ffile_check_copy(): pid[1033] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
E/WifiUtil( 1033): wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
I/WifiUtil( 1033): Intf0MacAddress=C49A027B60AC
E/WifiHW  ( 1033): unknown target_country: EU , set to default
E/WifiHW  ( 1033): [wifi_ensure_config_files] default country1 = GB
E/WifiHW  ( 1033): [wifi_ensure_config_files] default country2 = GB
I/WifiUtil( 1033): gEnableBmps=1
,I/art     (  344): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 195us total 9.882ms
,W/ResourcesManager( 6049): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager( 6049): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6049): Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 6049): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/BluetoothAdapterApp( 6049): Loading JNI Library
,D/SoftapController(  314): Softap fwReload - Ok
,D/CommandListener(  314): Setting iface cfg
D/CommandListener(  314): Trying to bring down wlan0
D/CommandListener(  314): Clearing all IP addresses on wlan0
D/Tethering( 1033): sendTetherStateChangedBroadcast 1, 0, 0
D/Tethering( 1033): InitialState.processMessage what=4
,D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=0
D/BluetoothAdapterApp( 6049): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@18041869 Instance Count = 1
D/DSQN    ( 1033): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/ActivityManager( 1033): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=6079 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/BluetoothAdapterApp( 6049): onCreate
,D/Tethering( 1033): sendTetherStateChangedBroadcast 0, 0, 0
E/WifiHW  ( 1033): Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
W/wpa_supplicant( 6090): type=1400 audit(0.0:153): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,W/wpa_supplicant( 6090): type=1400 audit(0.0:154): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/ProfileConfigQcom( 6049): [BTUI] HeadsetService is supported
D/ProfileConfigQcom( 6049): Adding HeadsetService
D/ProfileConfigQcom( 6049): [BTUI] A2dpService is supported
D/ProfileConfigQcom( 6049): Adding A2dpService
D/ProfileConfigQcom( 6049): [BTUI] HidService is supported
D/ProfileConfigQcom( 6049): Adding HidService
D/ProfileConfigQcom( 6049): [BTUI] HealthService is supported
D/ProfileConfigQcom( 6049): Adding HealthService
D/LGBluetoothFeatureConfig( 6049): isSupportPan() :  mTargetOp=OPEN
D/ProfileConfigQcom( 6049): [BTUI] PanService is supported
D/ProfileConfigQcom( 6049): Adding PanService
D/ProfileConfigQcom( 6049): [BTUI] GattService is supported
D/ProfileConfigQcom( 6049): Adding GattService
D/ProfileConfigQcom( 6049): [BTUI] BluetoothMapService is supported
D/ProfileConfigQcom( 6049): Adding BluetoothMapService
D/ProfileConfigQcom( 6049): [BTUI] HeadsetClientService is NOT supported
I/wpa_supplicant( 6090): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 6090): rfkill: Cannot open RFKILL control device
I/wpa_supplicant( 6090): [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
D/BluetoothManagerService( 1033): Message: 20
D/BluetoothManagerService( 1033): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@387e27c8:true
D/BluetoothAdapterState( 6049): make
,I/LGFMServiceAdapter( 6049): [FM] LGFMServiceAdapter : create
I/BluetoothAdapterState( 6049): Entering OffState
I/bluedroid-qcom( 6049): init
I/bte_conf( 6049): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
I/bte_conf( 6049): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 6049): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 6049): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
D/BTIF_CORE( 6049): [BTUI] lge_load_bluetooth_address
I/bluedroid-qcom( 6049): get_profile_interface socket
I/bluedroid-qcom( 6049): get_profile_interface map_client
I/GKI_LINUX( 6049): gki_task_entry task_id=1 [BTIF] starting
W/bdaddr_loader( 6109): type=1400 audit(0.0:155): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/BluetoothManagerService( 1033): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
W/bdaddr_loader( 6109): type=1400 audit(0.0:156): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,D/BluetoothManagerService( 1033): Message: 40
D/BluetoothManagerService( 1033): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
D/BluetoothAdapterProperties( 6049): Address is:58:3F:54:73:64:C0
I/bluedroid-qcom( 6049): config_hci_snoop_log
D/BluetoothManagerService( 1033): Bluetooth Adapter name changed to G3-1
D/BluetoothManagerService( 1033): Stored Bluetooth name: G3-1
D/BluetoothAdapterProperties( 6049): Name is: G3-1
D/BluetoothManagerService( 1033): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService( 1033): Broadcasting onBluetoothServiceUp() to 7 receivers.
D/lge_bdaddr_loader( 6109): [BTUI] bdaddr_loader ::: START
D/lge_bdaddr_loader( 6109): [BTUI] bluetooth_load_bdaddress
I/LGFTMITEM( 6109): [GET_FTM][id=8], offset=16384
D/lge_bdaddr_loader( 6109): [BTUI] bdaddr to set in property : 58:3F:54:73:64:C0
V/LGMDMManagerInternal( 6049): Create singleton instance
W/ResourcesManager( 6079): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6079): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6079): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
E/lge_bdaddr_loader( 6109): [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:64:C0
D/lge_bdaddr_loader( 6109): [BTUI] bdaddr_loader ::: END
W/ResourcesManager( 6079): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
,W/ResourcesManager( 6079): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6079): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
E/WifiStateMachine( 1033): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1033): useWiFiOffloading() : false
E/WifiStateMachine( 1033): CONFIG_LGE_WLAN_PATH : true
D/WifiMonitor( 1033): startMonitoring(wlan0) with mConnected = false
D/WifiMonitor( 1033): connecting to supplicant
,V/WfdStateTracker( 1930): WfdStateTracker handleDirectStateChangedEvent: 1
I/WifiServerServiceExt( 1033): WIFI_STATE_CHANGED_ACTION [2]
D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
D/BluetoothAdapterState( 6049): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,D/BluetoothAdapterProperties( 6049): Setting state to 11
I/BluetoothAdapterState( 6049): Bluetooth adapter state changed: 10-> 11
D/BluetoothManagerService( 1033): Message: 60
I/LGBluetoothServiceJni( 6049): classInitNative: succeeds
D/BluetoothManagerService( 1033): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService( 1033): Bluetooth State Change Intent: 10 -> 11
D/LGBluetoothAPIService( 1930): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothBondStateMachine( 6049): make
D/BluetoothAdapterService( 6049): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b68e808
D/LGBluetoothServiceAdapter( 6049): [BTUI] check adapter is available - false.
D/BluetoothAdapterService( 6049): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b68e808
D/LGBluetoothServiceAdapter( 6049): [BTUI] check adapter is available - true : set adapter available.
D/LGBluetoothSettingsDBObserver( 6049): [BTUI] register observer for LG device name DB
I/BluetoothBondStateMachine( 6049): StableState(): Entering Off State
I/[SystemUI]BluetoothHandler( 1463): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,I/wpa_supplicant( 6090): rfkill: Cannot open RFKILL control device
E/BluetoothAdapterService( 6049): File transfer profiles supported!!
E/BluetoothAdapterService( 6049): File transfer profiles supported!!
D/BluetoothHeadset( 1033): Proxy object connected
D/BluetoothHeadset( 1840): Proxy object connected
D/HeadsetService( 6049): Received start request. Starting profile...
D/BluetoothHeadset( 1840): Proxy object connected
D/BluetoothHeadset( 1840): Proxy object connected
I/LGBluetoothHeadsetServiceJni( 6049): classInitNative: succeeds
D/LGBluetoothHfpAdapter( 6049): Version 1.6
D/LGBluetoothFeatureConfig( 6049): isPrivacyLogsEnabled : true
I/BluetoothHeadsetServiceJni( 6049): classInitNative: succeeds
,D/HeadsetStateMachine( 6049): make
E/BluetoothAdapterService( 6049): File transfer profiles supported!!
E/BluetoothAdapterService( 6049): File transfer profiles supported!!
E/BluetoothAdapterService( 6049): File transfer profiles supported!!
D/LgDataFeature( 6049): LgDataFeature() Constructor: none
D/LgDataFeature( 6049): LgDataFeature() Constructor Done, null
,D/HeadsetStateMachine( 6049): max_hf_connections = 1
I/bluedroid-qcom( 6049): get_profile_interface handsfree
E/BluetoothAdapterService( 6049): File transfer profiles supported!!
V/ToneGenerator( 6049): ToneGenerator constructor: streamType=8, volume=1.000000
V/AudioPolicyService(  318): registerClient() client 0xb1427f40, uid 1002
V/AudioPolicyManager(  318): getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  318): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  318): getOutput() returns output 2
V/AudioSystem( 6049): getOutputSamplingRate() no output descriptor for output 2 in gOutputs
V/AudioFlinger(  318): registerClient() client 0xb55815c8, pid 6049
V/AudioSystem(  318): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  318): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 3284): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 3284): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1463): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1463): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1840): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1840): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 2115): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1033): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 2115): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1033): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 6049): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  318): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem(  318): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1463): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1463): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1840): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1033): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1840): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1033): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 2115): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 2115): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 3284): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 3284): ioConfigChanged() opening already existing output! 4
V/ToneGenerator( 6049): Create Track: 0xb4928a80
V/AudioTrack( 6049): set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
V/AudioTrack( 6049): set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
V/AudioPolicyManager(  318): getOutputForAttr() usage=3, content=4, tag= flags=00000000
V/AudioSystem( 6049): ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
V/AudioPolicyManager(  318): getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  318): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  318): getOutput() returns output 2
V/AudioSystem( 6049): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 6049): ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
I/AudioFlinger(  318): isAudioPlaybackHookOn() false
E/BluetoothAdapterService( 6049): File transfer profiles supported!!
V/AudioPolicyManager(  318): getOutputForAttr() usage=3, content=4, tag= flags=00000000
V/AudioPolicyManager(  318): getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
V/AudioPolicyManagerEx(  318): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  318): getOutput() returns output 2
V/AudioSystem( 6049): getLatency() output 2, latency 50
V/AudioSystem( 6049): getFrameCount() output 2, frameCount 960
V/AudioTrack( 6049): createTrack_l() output 2 afLatency 50
V/AudioFlinger(  318): [MABL_AudioFlinger] PlaybackThread::s,etMABLEnable(), enable = 0 
V/AudioFlinger(  318): [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
V/AudioFlinger(  318): [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
V/AudioFlinger(  318): [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
V/AudioFlinger(  318): createTrack() lSessionId: 16
V/AudioTrack( 6049): AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
V/AudioFlinger(  318): acquiring 16 from 6049, for 6049
V/AudioFlinger(  318):  added new entry for 16
V/ToneGenerator( 6049): ToneGenerator INIT OK, time: 109083
D/BluetoothAdapterService( 6049): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b68e808
D/HeadsetStateMachine( 6049): Enter Disconnected: -2, size: 0
D/HeadsetPhoneState( 6049): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 6049): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetStateMachine( 6049): [BTUI] change sampling rate to 8000 when device is disconnected
V/AudioFlinger(  318): setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6049
D/BluetoothAdapterService( 6049): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b68e808
D/audio_hw_primary(  318): adev_set_parameters: enter: bt_samplerate=8000
V/voice   (  318): voice_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  318): voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  318): voice_extn_compress_voip_set_parameters: exit
V/voice   (  318): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  318): LGE_platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  318): platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  318): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  318): lge_platform_set_loopback_parameters: enter: 
V/audio_hw_primary(  318): adev_set_parameters: exit with code(0)
E/audio_a2dp_hw(  318): adev_set_parameters: ERROR: set param called even when stream out is null
V/ToneGenerator( 6049): ToneGenerator destructor
V/ToneGenerator( 6049): stopTone
V/ToneGenerator( 6049): Delete Track: 0xb4928a80
D/A2dpService( 6049): Received start request. Starting profile...
D/BluetoothA2dp( 1033): Proxy object connected
I/BluetoothAvrcpServiceJni( 6049): classInitNative: succeeds
V/Avrcp   ( 6049): make
D/Avrcp   ( 6049): [BTUI] Use Native AVRCP : init jni
I/bluedroid-qcom( 6049): get_profile_interface avrcp
V/AudioTrack( 6049): ~AudioTrack, releasing session id from 6049 on behalf of 6049
V/AudioFlinger(  318): releasing 16 from 6049 for 6049
V/AudioFlinger(  318):  decremented refcount to 0
V/AudioFlinger(  318): purging stale effects
V/AudioPolicyService(  318): AudioCommandThread() adding release output 2
V/AudioPolicyService(  318): inserting command: 6 at index 0, num commands 0
V/AudioFlinger(  318): PlaybackThread::Track destructor
V/AudioPolicyService(  318): AudioCommandThread() waking up
V/AudioFlinger(  318): removeClient_l() pid 6049, calling pid 318
V/AudioPolicyService(  318): AudioCommandThread() processing release output 2
V/AudioPolicyManager(  318): releaseOutput() 2
V/AudioPolicyService(  318): AudioCommandThread() going to sleep
V/LGMDMManager( 6049): Create singleton instance
I/BluetoothAdapterState( 6049): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
V/AudioManager( 6049): registerRemoteController: size of Media player list: 0
E/AudioManager( 6049): No RCC entry present to update
E/RemoteController( 6049): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothAvrcpQcomServiceJni( 6049): classInitQcomNative: succeeds
D/LGBluetoothAvrcpQcomAdapter( 6049): [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
I/BluetoothAvrcpQcomServiceJni( 6049): initQcomNative: succeeds
D/UsbSettingsReceiver( 6079): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6079): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6079): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6079): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6079): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/LGBluetoothAvrcpQcomAdapter( 6049): [BTUI] [+] updateMediaPlayerInfo
D/UsbSettingsControl( 6079): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6079): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6079): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6079): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6079): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6079): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 6079): [AUTORUN] setTetherStatus() : status=false
,I/wpa_supplicant( 6090): [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
I/wpa_supplicant( 6090): p2p0: CTRL-EVENT-AVOID-FREQ ranges=
I/wpa_supplicant( 6090): wlan0: CTRL-EVENT-SCAN-STARTED 
,I/ActivityManager( 1033): Killing 5731:com.google.android.partnersetup/u0a8 (adj 15): empty #17
E/WifiStateMachine( 1033):  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
E/WifiStateMachine( 1033):  SupplicantStartingState CMD_START_DRIVER 0 0
E/WifiStateMachine( 1033):  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
E/WifiStateMachine( 1033):  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
E/WifiStateMachine( 1033):  SupplicantStartingState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1033):  DefaultState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1033):  SupplicantStartingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1033):  DefaultState CMD_RECONNECT 0 0
E/WifiStateMachine( 1033):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1033):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1033):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1033):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1033):  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
D/WifiNative-wlan0( 1033): doString: [DRIVER MACADDR]
D/WifiNative-wlan0( 1033):    returned Macaddr = c4:9a:02:7b:60:ac
D/WifiStateMachine( 1033): MAC Addr from driver = c4:9a:02:7b:60:ac
D/WifiOffDelayIfNotUsed( 1033): setPowerSaveActivated(false)
D/WifiMonitor( 1033): Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
D/WifiMonitor( 1033): Dropping event because (p2p0) is stopped
D/WifiMonitor( 1033): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1033): WifiMonitor:wlan0 cnt=0 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1033): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1033): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
V/SIM_STK ( 1033): Menu title from STK is T-Mobile
V/SIM_STK ( 1033): Menu title from STK is T-Mobile
,E/WifiStateMachine( 1033): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1033): useWiFiOffloading() : false
E/WifiStateMachine( 1033): CONFIG_LGE_WLAN_PATH : true
W/ActivityManager( 1033): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
D/WifiNative-wlan0( 1033): doBoolean: SET update_config 1
,W/libprocessgroup( 1033): failed to open /acct/uid_10008/pid_5731/cgroup.procs: No such file or directory
D/WifiNative-wlan0( 1033): SET update_config 1: returned true
D/WifiConfigStore( 1033): Loading config and enabling all networks 
D/WifiNative-wlan0( 1033): doString: [LIST_NETWORKS]
D/WifiNative-wlan0( 1033):    returned network id / ssid / bssid / flags 0	NG700	any	
D/WfdService( 1930): Waiting for WifiP2p enabling
W/Settings( 1033): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1033): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGBluetoothAvrcpQcomAdapter( 6049): [BTUI] installed app name: Music
D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/WifiServerServiceExt( 1033): WIFI_STATE_CHANGED_ACTION [3]
D/LGBluetoothAvrcpQcomAdapter( 6049): [BTUI] installed app name: Google Play Music
I/WifiServerServiceExt( 1033): batteryPsActivateMsgHandler : state:0 event:3
D/LGBluetoothAvrcpQcomAdapter( 6049): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 6049): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 6049): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 6049): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6049): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 6049): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6049): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 6049): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6049): [BTUI] [-] updateMediaPlayerInfo
D/UsbSettingsReceiver( 6079): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
I/BluetoothA2dpServiceJni( 6049): classInitNative
D/UsbSettingsReceiver( 6079): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6079): [AUTORUN] sys.usb.state = ptp_only,adb
,I/BluetoothA2dpServiceJni( 6049): classInitNative: succeeds
D/UsbSettingsReceiver( 6079): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/A2dpStateMachine( 6049): make
I/bluedroid-qcom( 6049): get_profile_interface a2dp
D/UsbSettingsReceiver( 6079): [AUTORUN] onReceive() : app userid = 0, current userid = 0
,I/GKI_LINUX( 6049): gki_task_entry task_id=2 [A2DP-MEDIA] starting
I/LGBluetoothA2dpServiceJni( 6049): classInitNative: succeeds
I/LGBluetoothA2dpAdapter( 6049): [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
D/BluetoothAdapterService( 6049): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b68e808
D/A2dpStateMachine( 6049): Enter Disconnected: -2
I/BluetoothHidServiceJni( 6049): classInitNative: succeeds
D/HidService( 6049): Received start request. Starting profile...
I/bluedroid-qcom( 6049): get_profile_interface hidhost
D/BluetoothAdapterService( 6049): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b68e808
I/BluetoothHealthServiceJni( 6049): classInitNative: succeeds
E/WifiConfigStore( 1033): readNetworkVariablesFromSupplicantFile key=psk
D/UsbSettingsControl( 6079): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6079): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 6079): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6079): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6079): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 6079): [AUTORUN] setTetherStatus() : status=false
D/HealthService( 6049): Received start request. Starting profile...
I/bluedroid-qcom( 6049): get_profile_interface health
I/LGBluetoothHealthServiceJni( 6049): classInitNative: succeeds
D/BluetoothAdapterService( 6049): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b68e808
I/BluetoothPanServiceJni( 6049): classInitNative(L105): succeeds
D/PanService( 6049): Received start request. Starting profile...
D/BluetoothPanServiceJni( 6049): initializeNative(L110): pan
I/bluedroid-qcom( 6049): get_profile_interface pan
,E/WifiConfigStore( 1033): readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
E/WifiConfigStore( 1033): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
I/ActivityManager( 1033): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6125 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,I/LGBluetoothPanAdapter( 6049): [BTUI] getInstance : create [LGBluetoothPanAdapter]
D/BluetoothAdapterService( 6049): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b68e808
I/BtGatt.JNI( 6049): classInitNative(L901): classInitNative: Success!
D/WifiStateMachine( 1033): enableVerboseLogging : level 2
D/WifiNative-wlan0( 1033): doBoolean: SET device_name g3_global_com
D/WifiNative-wlan0( 1033): SET device_name g3_global_com: returned true
D/WifiNative-wlan0( 1033): doBoolean: SET manufacturer LGE
D/WifiNative-wlan0( 1033): SET manufacturer LGE: returned true
D/WifiNative-wlan0( 1033): doBoolean: SET model_name LG-D855
D/WifiNative-wlan0( 1033): SET model_name LG-D855: returned true
D/WifiNative-wlan0( 1033): doBoolean: SET model_number LG-D855
D/WifiNative-wlan0( 1033): SET model_number LG-D855: returned true
D/WifiNative-wlan0( 1033): doBoolean: SET serial_number LGD8553bed2d08
D/WifiNative-wlan0( 1033): SET serial_number LGD8553bed2d08: returned true
D/BtGatt.DebugUtils( 6049): handleDebugAction() action=null
D/WifiNative-wlan0( 1033): doBoolean: SET config_methods physical_display virtual_push_button
D/BtGatt.GattService( 6049): Received start request. Starting profile...
D/BtGatt.GattService( 6049): start()
D/WifiNative-wlan0( 1033): SET config_methods physical_display virtual_push_button: returned true
I/bluedroid-qcom( 6049): get_profile_interface gatt
D/WifiNative-wlan0( 1033): doBoolean: SET device_type 10-0050F204-5
D/BtGatt.AdvertiseManager( 6049): advertise manager created
D/WifiNative-wlan0( 1033): SET device_type 10-0050F204-5: returned true
D/WfdsService( 1930): Supplicant Connection state is changed : true
D/WfdsService( 1930): DefaultState - WIFI_SUPPLICANT_CONNECTED
D/WfdsService( 1930): Set the WFDS Monitor: true
D/WfdsMonitor( 1930): WfdsMonitorThread create
D/WfdsMonitor( 1930): WFDS Monitor is created and started
D/WfdsService( 1930): WiFi: Supplicant connection re-established
E/CtrlSupplicant( 1930): Access OK "@android:wpa_wlan0"
E/CtrlSupplicant( 1930): Succeed to open control connection
E/CtrlSupplicant( 1930): Succeed to open monitor connection
D/WifiStateMachine( 1033): Setting OUI to DA-A1-19
D/WifiNative-wlan0( 1033): doBoolean: SCAN_INTERVAL 120
D/WfdsMonitor( 1930): Supplicant connection established
D/BluetoothAdapterService( 6049): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b68e808
D/WfdsService( 1930): Connected to the supplicant for wfds
D/HeadsetStateMachine( 6049): Proxy object connected
D/WifiNative-wlan0( 1033): SCAN_INTERVAL 120: returned true
,D/WifiNative-HAL( 1033): Setting external_sim to 1
D/WifiNative-wlan0( 1033): doBoolean: SET external_sim 1
D/LGBluetoothHfpAdapter( 6049): [BTUI] queryPhoneState
,D/LGBluetoothHfpAdapter( 6049): Try to query the phonestate on bind
D/WifiNative-wlan0( 1033): SET external_sim 1: returned true
I/WifiNative-HAL( 1033): startHal
E/wifi    ( 1033): getStaticLongField sWifiHalHandle 0x9893a8dc
D/BluetoothPhoneService.BluetoothLTECall( 1840):  call mBluetoothHeadset.phoneStateChanged()
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
E/WifiHAL ( 1033): Could not connect handle
D/wifi    ( 1033): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x401aba
I/WifiNative-HAL( 1033): Could not start hal
D/WifiStateMachine( 1033): Setting OUI to DA-A1-19
I/WifiNative-HAL( 1033): startHal
E/wifi    ( 1033): getStaticLongField sWifiHalHandle 0x9893a85c
E/WifiHAL ( 1033): Could not connect handle
D/wifi    ( 1033): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x501aaa
I/WifiNative-HAL( 1033): Could not start hal
D/WifiNative-wlan0( 1033): doBoolean: STA_AUTOCONNECT 1
D/WifiNative-wlan0( 1033): STA_AUTOCONNECT 1: returned true
D/WifiNative-wlan0( 1033): doBoolean: DRIVER BTCOEXSCAN-STOP
D/BluetoothAdapterService( 6049): Profile still not running:com.android.bluetooth.gatt.GattService
I/wpa_supplicant( 6090): wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
D/HeadsetStateMachine( 6049): Disconnected process message: 10, size: 0
D/BluetoothAdapterService( 6049): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b68e808
I/LGBluetoothMapAdapter( 6049): [BTUI] getInstance : create [LGBluetoothMapAdapter]
V/BluetoothMapService( 6049): BluetoothMapBinder()
D/BluetoothMapService( 6049): Received start request. Starting profile...
D/BluetoothMapService( 6049): start()
D/HeadsetPhoneState( 6049): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 6049): Disconnected process message: 11, size: 0
D/WifiNative-wlan0( 1033): DRIVER BTCOEXSCAN-STOP: returned true
D/BluetoothMapEmailSettingsLoader( 6049): Found 0 applications
D/BluetoothMapEmailAppObserver( 6049): createReceiver()
D/BluetoothMapEmailAppObserver( 6049): initObservers()
D/BluetoothMapEmailAppObserver( 6049): getEnabledAccountItems()
I/StatusBar.NetworkController( 1463): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1463): mWifiConnected = false, mWifiLevel = 0
D/WifiHS20( 1033): hidePasspointNotification off =false
W/Settings( 1033): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1033): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1033): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/Bluetooth,AdapterService( 6049): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b68e808
D/WifiNative-wlan0( 1033): doBoolean: DRIVER RXFILTER-STOP
I/wpa_supplicant( 6090): wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
,V/BluetoothPbapReceiver( 6049): PbapReceiver onReceive 
D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
V/BluetoothPbapReceiver( 6049): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6049): ***********state = 11
D/WifiNative-wlan0( 1033): DRIVER RXFILTER-STOP: returned true
D/WifiNative-wlan0( 1033): doBoolean: DRIVER RXFILTER-REMOVE 3
I/wpa_supplicant( 6090): wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
D/WifiNative-wlan0( 1033): DRIVER RXFILTER-REMOVE 3: returned true
D/WifiNative-wlan0( 1033): doBoolean: DRIVER RXFILTER-START
I/wpa_supplicant( 6090): wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
D/WifiNative-wlan0( 1033): DRIVER RXFILTER-START: returned true
D/WifiNative-wlan0( 1033): doBoolean: DRIVER RXFILTER-STOP
I/wpa_supplicant( 6090): wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
D/WifiNative-wlan0( 1033): DRIVER RXFILTER-STOP: returned true
D/WifiNative-wlan0( 1033): doBoolean: DRIVER RXFILTER-REMOVE 2
I/wpa_supplicant( 6090): android_multicast_filter_startstop : multicast filter set
D/WifiNative-wlan0( 1033): DRIVER RXFILTER-REMOVE 2: returned true
D/WifiNative-wlan0( 1033): doBoolean: DRIVER RXFILTER-START
I/wpa_supplicant( 6090): wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
D/WifiNative-wlan0( 1033): DRIVER RXFILTER-START: returned true
E/WifiNative: ( 1033): [109,360,306 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
D/WifiNative-wlan0( 1033): doBoolean: RECONNECT
D/WifiNative-wlan0( 1033): RECONNECT: returned true
D/BluetoothAdapterService( 6049): Profile still not running:com.android.bluetooth.gatt.GattService
D/WifiNative-wlan0( 1033): doString: [STATUS]
D/WifiMonitor( 1033): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1033): WifiMonitor:wlan0 cnt=1 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiNative-wlan0( 1033):    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
D/WifiNative-wlan0( 1033): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 6090): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1033): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1033): doBoolean: SET ps 1
D/WifiNative-wlan0( 1033): SET ps 1: returned true
D/LGWifiP2pService( 1033): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothAdapterService( 6049): Profile still not running:com.android.bluetooth.gatt.GattService
D/CommandListener(  314): Setting iface cfg
D/CommandListener(  314): Trying to bring up p2p0
D/WifiMonitor( 1033): startMonitoring(p2p0) with mConnected = true
D/LGWifiP2pService( 1033): P2pEnablingState
D/LGWifiP2pService( 1033): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1033): P2p socket connection successful
D/LGWifiP2pService( 1033): P2pEnabledState
,E/WifiStateMachine( 1033):  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
E/WifiStateMachine( 1033):  DisconnectedState CMD_START_DRIVER 0 0
D/BluetoothAdapterService( 6049): Profile still not running:com.android.bluetooth.gatt.GattService
E/WifiStateMachine( 1033):  ConnectModeState CMD_START_DRIVER 0 0
V/PanService( 6049): [BTUI] SIM Extra State :ABSENT
E/WifiStateMachine( 1033):  DriverStartedState CMD_START_DRIVER 0 0
E/WifiStateMachine( 1033):  DisconnectedState what:132106 1 0
E/WifiStateMachine( 1033):  ConnectModeState what:132106 1 0
E/WifiStateMachine( 1033):  DriverStartedState what:132106 1 0
I/WifiServerServiceExt( 1033): setWifiDualbandAPConnection band : 1
E/wpa_supplicant( 6090): nWIFIDualbandAPConnection: 1
D/BluetoothAdapterService( 6049): Profile still not running:com.android.bluetooth.gatt.GattService
E/WifiStateMachine( 1033):  DisconnectedState what:132096 -100 0
E/WifiStateMachine( 1033):  ConnectModeState what:132096 -100 0
D/WifiService( 1033): New client listening to asynchronous messages
E/WifiStateMachine( 1033):  DriverStartedState what:132096 -100 0
I/WifiServerServiceExt( 1033): set CMD_DISCONNECT_RSSI_LVL : -100
E/wpa_supplicant( 6090): disconnect_rssi_lvl: -100
E/WifiStateMachine( 1033):  DisconnectedState CMD_SET_COUNTRY_CODE 1 0 cz
E/WifiStateMachine( 1033):  ConnectModeState CMD_SET_COUNTRY_CODE 1 0 cz
E/WifiStateMachine( 1033):  DriverStartedState CMD_SET_COUNTRY_CODE 1 0 cz
D/BluetoothAdapterService( 6049): Profile still not running:com.android.bluetooth.map.BluetoothMapService
V/BluetoothMapService( 6049): Handler(): got msg=1
D/WifiNative-wlan0( 1033): doBoolean: DRIVER COUNTRY CZ
I/wpa_supplicant( 6090): wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
I/wpa_supplicant( 6090): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
D/WifiMonitor( 1033): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
E/WifiMonitor( 1033): WifiMonitor:wlan0 cnt=2 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1033): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1033): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
D/BluetoothAdapterState( 6049): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/wpa_supplicant( 6090): [LGE_PATCH] driver_cmd() country:CZ
I/bluedroid-qcom( 6049): enable
I/wpa_supplicant( 6090): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
I/GKI_LINUX( 6049): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 6049): btu_task pending for preload complete event
I/bt_hci_bdroid( 6049): init
D/WifiMonitor( 1033): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1033): WifiMonitor:p2p0 cnt=3 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
I/wpa_supplicant( 6090): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1033): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1033): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiMonitor( 1033): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1033): WifiMonitor:p2p0 cnt=4 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1033): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1033): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WfdsMonitor( 1930): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WfdsMonitor( 1930): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WifiNative-wlan0( 1033): DRIVER COUNTRY CZ: returned true
E/WifiStateMachine( 1033):  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine( 1033):  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine( 1033):  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
D/WifiNative-wlan0( 1033): doBoolean: DRIVER SETBAND 0
I/wpa_supplicant( 6090): wpa_driver_nl80211_ext_dri,ver_cmd SETBAND 0 - interface name wlan0
I/wpa_supplicant( 6090): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
D/WifiMonitor( 1033): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
E/WifiMonitor( 1033): WifiMonitor:wlan0 cnt=5 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
E/WifiMonitor( 1033): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
E/WifiMonitor( 1033): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
D/WifiNative-wlan0( 1033): DRIVER SETBAND 0: returned true
D/WifiNative-wlan0( 1033): doBoolean: BSS_FLUSH 0
D/WifiNative-wlan0( 1033): BSS_FLUSH 0: returned true
D/WifiNative-wlan0( 1033): doBoolean: SCAN
D/WifiNative-wlan0( 1033): SCAN: returned false
E/WifiStateMachine( 1033):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=109379  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,I/bt_vendor( 6049): bt-vendor : init
I/bt_vendor( 6049): bt-vendor : get_bt_soc_type
E/bt_vendor( 6049): get_bt_soc_type: Failed to get soc type
I/bt_vendor( 6049): init: Local BD Address : c0:64:73:54:3f:58
D/bt_userial_mct( 6049): userial_init
D/bt_hci_bdroid( 6049): set_power 1
I/bt_vendor( 6049): bt-vendor : BT_VND_OP_POWER_CTRL: On
I/bt_vendor( 6049): Starting hciattach daemon
I/bt_vendor( 6049): try to set true
W/sh      ( 6149): type=1400 audit(0.0:157): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/sh      ( 6149): type=1400 audit(0.0:158): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,I/qcom-bluetooth( 6151): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
I/ActivityManager( 1033): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6150 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
D/LGWifiP2pService( 1033): sending p2p connection changed broadcast
D/WifiNative-p2p0( 1033): doBoolean: SET persistent_reconnect 1
E/WifiStateMachine( 1033):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=109410  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine( 1033):  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
V/WfdStateTracker( 1930): WfdStateTracker handleDirectStateChangedEvent: 2
E/WifiStateMachine( 1033):  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
D/WfdsService( 1930): WifiP2pState is changed : true
E/WifiStateMachine( 1033):  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
D/WfdsService( 1930): Receive the WFDS_ENABLE Method
D/WfdsService( 1930): Set the WFDS Monitor: true
,D/WfdsService( 1930): Connected to the supplicant for wfds
D/WfdsJNI ( 1930): doCommand: WFDS_SET TRUE
I/wpa_supplicant( 6090): WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
E/WifiStateMachine( 1033):  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
D/WfdsJNI ( 1930): doCommand: WFDS_GET_MAC_ADDRESS
E/WifiStateMachine( 1033):  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
I/wpa_supplicant( 6090): WFDS: wfds_supplicant_wfds_cmd: cmd = GET_MAC_ADDRESS
D/WifiNative-p2p0( 1033): SET persistent_reconnect 1: returned true
D/WifiNative-p2p0( 1033): doBoolean: SET device_name G3-1
D/WifiNative-p2p0( 1033): SET device_name G3-1: returned true
D/LGWifiP2pService( 1033): [LGE_P2P] initializeP2pSettings() check postfix
D/LGWifiP2pService( 1033): before postfix = G3-1
D/WifiServerServiceExt( 1033): postfix byte check : 4
D/LGWifiP2pService( 1033): after postfix = G3-1
D/WifiNative-p2p0( 1033): doBoolean: SET p2p_ssid_postfix -G3-1
D/WifiScanningService( 1033): SCAN_AVAILABLE : 3
D/RttService( 1033): SCAN_AVAILABLE : 3
D/WfdsJNI ( 1930): doCommand: IFNAME=wlan0 GET_CAPABILITY channels
D/WfdsService( 1930): selectPreferredScanChannel [36]
D/WfdsService( 1930): STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7b:60:ac
D/WifiNative-p2p0( 1033): SET p2p_ssid_postfix -G3-1: returned true
D/WifiNative-p2p0( 1033): doBoolean: SET device_type 10-0050F204-5
D/WifiNative-p2p0( 1033): SET device_type 10-0050F204-5: returned true
D/WifiNative-p2p0( 1033): doBoolean: SET config_methods virtual_push_button physical_display keypad
D/WifiNative-p2p0( 1033): SET config_methods virtual_push_button physical_display keypad: returned true
D/WifiScanningService( 1033): DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL( 1033): startHal
E/wifi    ( 1033): getStaticLongField sWifiHalHandle 0x94e6c99c
D/WifiNative-p2p0( 1033): doBoolean: P2P_SET conc_pref p2p
E/WifiHAL ( 1033): Could not connect handle
D/wifi    ( 1033): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x2018b6
I/WifiNative-HAL( 1033): Could not start hal
E/WifiScanningService( 1033): could not start HAL
D/WifiNative-p2p0( 1033): P2P_SET conc_pref p2p: returned true
D/WifiNative-HAL( 1033): p2pGetDeviceAddress
D/RttService( 1033): DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-HAL( 1033): p2pGetDeviceAddress returning 02:9a:02:7b:60:ac
D/WfdsService( 1930): WIFI_P2P_CONNECTION_CHANGED_ACTION
W/Settings( 1033): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1033): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1033): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/StatusBar.NetworkController( 1463): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1463): mWifiConnected = false, mWifiLevel = 0
D/WfdsService( 1930): isConnected: false
,D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
D/LGWifiP2pService( 1033): DeviceAddress: 02:9a:02:7b:60:ac
D/WifiNative-p2p0( 1033): doBoolean: P2P_FLUSH
D/WifiNative-p2p0( 1033): P2P_FLUSH: returned true
D/WifiNative-p2p0( 1033): doBoolean: P2P_SERVICE_FLUSH
D/WifiNative-p2p0( 1033): P2P_SERVICE_FLUSH: returned true
D/WifiNative-p2p0( 1033): doString: [LIST_NETWORKS]
D/WifiNative-p2p0( 1033):    returned network id / ssid / bssid / flags
D/WifiNative-p2p0( 1033): doBoolean: SAVE_CONFIG
I/WfdStateTracker( 1930): handleP2pThisDeviceChanged
D/WfdsService( 1930): WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
D/WfdsService( 1930): Update P2p Interface State: 3
D/WifiServerServiceExt( 1033): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1033): setSupplicantStateSCANNING
D/WifiNative-p2p0( 1033): SAVE_CONFIG: returned true
D/LGWifiP2pService( 1033): sending p2p persistent groups changed broadcast
,I/qcom-bluetooth( 6175): /system/etc/init.qcom.bt.sh: Transport : smd 
I/ActivityManager( 1033): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6178 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/qcom-bluetooth( 6179): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
D/LGWifiP2pService( 1033): InactiveState
D/LGWifiP2pService( 1033): InactiveState{ when=-84ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1033): P2pEnabledState{ when=-84ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1033): doBoolean: DRIVER COUNTRY CZ
I/wpa_supplicant( 6090): wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
,I/wpa_supplicant( 6090): p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,D/WifiMonitor( 1033): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
E/WifiMonitor( 1033): WifiMonitor:p2p0 cnt=6 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1033): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1033): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
D/WfdsMonitor( 1930): Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
I/wpa_supplicant( 6090): [LGE_PATCH] driver_cmd() country:CZ
I/wpa_supplicant( 6090): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WfdsMonitor( 1930): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WifiMonitor( 1033): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1033): WifiMonitor:p2p0 cnt=7 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1033): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1033): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
I/wpa_supplicant( 6090): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WfdsMonitor( 1930): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WifiMonitor( 1033): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1033): WifiMonitor:p2p0 cnt=8 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1033): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1033): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiNative-p2p0( 1033): DRIVER COUNTRY CZ: returned true
D/LGWifiP2pService( 1033): InactiveState{ when=-38ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1033): P2pEnabledState{ when=-38ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1033): InactiveState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1033): P2pEnabledState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1033): DefaultState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1033): InactiveState{ when=0 what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1033): P2pEnabledState{ when=0 what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1033): DefaultState{ when=-1ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1033): InactiveState{ when=-2ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1033): P2pEnabledState{ when=-2ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1033): DefaultState{ when=-2ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1033): InactiveState{ when=-2ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1033): P2pEnabledState{ when=-2ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1033): DefaultState{ when=-2ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1033): No p2p device connected
W/WfdsService( 1930): DefaultState - msg [9441285] is not handled
I/qcom-bluetooth( 6197): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,V/FormManager( 6125): Network unavailable.
W/FormManager( 6125): Network not available. Please check & try again.
V/FormManager( 6125): Network unavailable.
I/qcom-bluetooth( 6199): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
I/qcom-bluetooth( 6200): /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/ActivityManager( 1033): Killing 5462:com.lge.appbox.client/u0a11 (adj 15): empty #17
I/qcom-bluetooth( 6201): /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
I/libmdmdetect( 6203): ESOC framework not supported
E/Diag_Lib( 6203):  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,D/PCSuite ( 6178): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/bthci_qcomm_linux( 6203): [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:64:C0)
D/bthci_qcomm_common( 6203): [BTUI] bt_hci_qcomm_init:
D/bthci_qcomm_common( 6203): [BTUI]     BDADDR: 58:3F:54:73:64:C0
D/bthci_qcomm_common( 6203): [BTUI]     BR/EDR: Class 1
D/bthci_qcomm_common( 6203): [BTUI]     LE: Class 2
D/bthci_qcomm_common( 6203): [BTUI]     Ref Clock: 32M
D/btqsocnvmtags( 6203): [BTUI] init_riva_entries: set NORMAL power settings
E/WifiMonitor( 1033): WifiMonitor:wlan0 cnt=9 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1033): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1033): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1033): WifiMonitor:wlan0 cnt=10 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1033): couldn't identify event type - WPS-AP-AVAILABLE 
,E/WifiStateMachine( 1033):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
I/wpa_supplicant( 6090): [LGE_PATCH]scan interval[0] = 2 sec.
E/WifiStateMachine( 1033):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine( 1033):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine( 1033):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
I/WifiNative-HAL( 1033): startHal
E/wifi    ( 1033): getStaticLongField sWifiHalHandle 0x9893a8cc
E/WifiHAL ( 1033): Could not connect handle
D/wifi    ( 1033): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x50182a
I/WifiNative-HAL( 1033): Could not start hal
E/WifiMonitor( 1033): WifiMonitor:p2p0 cnt=11 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
D/WifiNative-wlan0( 1033): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiMonitor( 1033): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1033): Event [IFNAME=p2p0 WPS-AP-AVAILABLE ]
D/LGWifiP2pService( 1033): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiMonitor( 1033): WifiMonitor:p2p0 cnt=12 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1033): couldn't identify event type - WPS-AP-AVAILABLE 
D/LGWifiP2pService( 1033): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1033): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsMonitor( 1930): Event [CTRL-EVENT-SCAN-RESULTS ]
D/WfdsMonitor( 1930): Event [WPS-AP-AVAILABLE ]
W/libprocessgroup( 1033): failed to open /acct/uid_10011/pid_5462/cgroup.procs: No such file or directory
,E/ActivityThread( 6150): Failed to find provider info for com.lge.lgaccount.provider
W/LG Account v2.2( 6150): No ProfileInfo entries
I/LG Account v2.2( 6150): isEnabled: false
I/Feature ( 6150): [Lifetracker]ver: 4.21.112(40211120)
I/Feature ( 6150): [Lifetracker]Country: EU
I/Feature ( 6150): [Lifetracker]Operator: OPEN
I/Feature ( 6150): [Lifetracker]Ranking support: false
I/Feature ( 6150): [Lifetracker]Comfort support: false
I/Feature ( 6150): [Lifetracker]Accessory: true
I/Feature ( 6150): [Lifetracker]Health device: true
I/Feature ( 6150): [Lifetracker]Extra Pedometer: false
I/Feature ( 6150): [Lifetracker]Blood glucose device: false
I/Feature ( 6150): [Lifetracker]Device Number: 3
I/ActivityManager( 1033): Killing 5484:com.android.contacts/u0a19 (adj 15): empty #17
V/WiFiOffLoadBroadcast( 6079): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,D/WifiService( 1033): New client listening to asynchronous messages
D/LgDataFeature( 6079): LgDataFeature() Constructor: none
,D/LgDataFeature( 6079): LgDataFeature() Constructor Done, null
D/WiFiOffLoadUpdatePriority( 6079): remove : truetruetrue
E/WifiStateMachine( 1033):  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1033):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1033):  DisconnectedState CMD_SAVE_CONFIG uid=1000 0 0
E/WifiStateMachine( 1033):  ConnectModeState CMD_SAVE_CONFIG uid=1000 0 0
D/WifiNative-wlan0( 1033): doBoolean: SAVE_CONFIG
,I/rmt_storage(  309): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  309): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  309): wakelock acquired: 1, error no: 42
I/rmt_storage(  309): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236806912)
D/WifiNative-wlan0( 1033): SAVE_CONFIG: returned true
,D/WiFiOffLoadUpdatePriority( 6079): remove1
V/WiFiOffLoadSharedPrefsUtils( 6079): save remove
D/WiFiOffLoadBroadcast( 6079): mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
D/WiFiOffLoadBroadcast( 6079): S: false, R: false
,E/WifiStateMachine( 1033):  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1033):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/WiFiOffLoadUpdatePriority( 6079): saved SSID: "NG700"
D/WiFiOffLoadUpdatePriority( 6079): connected SSID: null
D/WiFiOffLoadUpdatePriority( 6079): private wpa: "NG700" 300
D/WifiServiceImplEx( 1033): addOrUpdateNetwork pid=6079, uid=1000, packageName=android.uid.system:1000
E/addOrUpdateNetwork( 1033):  uid = 1000 SSID "NG700" nid=0
E/WifiStateMachine( 1033):  DisconnectedState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=2
E/WifiStateMachine( 1033):  ConnectModeState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=2
E/WifiConfigStore( 1033):  key="NG700"WPA_PSK netId=0 uid=0/1000
D/WifiServerServiceExt( 1033): addOrUpdateNetwork: mThisIsFirstEnableing = false
D/WifiNative-wlan0( 1033): doBoolean: SET_NETWORK 0 ssid 4e47373030
D/WifiNative-wlan0( 1033): SET_NETWORK 0 ssid 4e47373030: returned true
D/WifiNative-wlan0( 1033): doBoolean: SET_NETWORK 0 key_mgmt WPA-PSK
D/WifiNative-wlan0( 1033): SET_NETWORK 0 key_mgmt WPA-PSK: returned true
D/WifiNative-wlan0( 1033): doBoolean: SET_NETWORK 0 proto WPA RSN
D/WifiNative-wlan0( 1033): SET_NETWORK 0 proto WPA RSN: returned true
D/WifiNative-wlan0( 1033): doBoolean: SET_NETWORK 0 pairwise TKIP CCMP
D/WifiNative-wlan0( 1033): SET_NETWORK 0 pairwise TKIP CCMP: returned true
D/WifiNative-wlan0( 1033): doBoolean: SET_NETWORK 0 group WEP40 WEP104 TKIP CCMP
D/WifiNative-wlan0( 1033): SET_NETWORK 0 group WEP40 WEP104 TKIP CCMP: returned true
D/WifiNative-wlan0( 1033): doBoolean: SET_NETWORK 0 priority 300
,D/WifiNative-wlan0( 1033): SET_NETWORK 0 priority 300: returned true
,E/WifiConfigStore( 1033): will read network variables netId=0
E/WifiConfigStore( 1033): writeIpAndProxyConfigurationsOnChange: "NG700" -> "NG700" path: /data/misc/wifi/ipconfig.txt
E/WifiConfigStore( 1033):  writeKnownNetworkHistory() num networks:1 needWrite=false
W/libprocessgroup( 1033): failed to open /acct/uid_10019/pid_5484/cgroup.procs: No such file or directory
,D/WiFiOffLoadUpdatePriority( 6079):  ssid "NG700" prio 300
D/WiFiOffLoadUpdatePriority( 6079): configuration updated: 0
E/WifiStateMachine( 1033):  DisconnectedState CMD_SAVE_CONFIG uid=1000 0 0
E/WifiStateMachine( 1033):  ConnectModeState CMD_SAVE_CONFIG uid=1000 0 0
D/WifiNative-wlan0( 1033): doBoolean: SAVE_CONFIG
I/rmt_storage(  309): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  309): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  309): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236806912) wakelock released: 1, error no: 0
I/rmt_storage(  309): 
I/rmt_storage(  309): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
E/Diag_Lib(  880): [IMS_FATAL]| 3347 | 904 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
D/WifiNative-wlan0( 1033): SAVE_CONFIG: returned true
D/WiFiOffLoadUpdatePriority( 6079): configuration saved: true
D/BluetoothPermissionRequest( 6079): onReceive
,D/LGBluetoothFeatureConfig( 6079):  get() - isFeatureLoaded : false
D/BluetoothManagerService( 1033): Message: 20
D/BluetoothManagerService( 1033): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3246df96:true
I/ActivityManager( 1033): Killing 5753:com.lge.email/u0a23 (adj 15): empty #17
,D/LGBluetoothResetSettingReceiver( 6079): return without doing reset settings.
W/libprocessgroup( 1033): failed to open /acct/uid_10023/pid_5753/cgroup.procs: No such file or directory
,D/LGBluetoothOppAdapter( 6049): [BTUI] getInstance : create [LGBluetoothOppAdapter]
V/BluetoothFtpReceiver( 6049): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothSapReceiver( 6049): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 6049): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 6049): SapReceiver onReceive 
V/BluetoothSapReceiver( 6049): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6049):  Bluetooth Adapter state = 11
I/ActivityManager( 1033): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6220 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,D/PCSuite ( 6178): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
W/FormManager( 6125): Network not available. Please check & try again.
,V/WiFiOffLoadBroadcast( 6079): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
V/FormManager( 6125): Network unavailable.
V/FormManager( 6125): Network unavailable.
,D/WiFiOffLoadBroadcast( 6079): MCCMNC not supported: null
D/LGDMClient( 3164): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 3164): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 3164): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 3164): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ResourcesManager( 6220): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/PostponalbeReceiver( 5145): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6178): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/AuthorizationBluetoothService( 2133): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/LGDMClient( 3164): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,D/PCSuite ( 6178): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6178): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/LGDMClient( 3164): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 3164): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/WiFiOffLoadBroadcast( 6079): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6079): MCCMNC not supported: null
I/ActivityManager( 1033): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6245 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/ActivityManager( 1033): Killing 5505:com.android.gallery3d/u0a27 (adj 15): empty #17
W/libprocessgroup( 1033): failed to open /acct/uid_10027/pid_5505/cgroup.procs: No such file or directory
,W/ResourcesManager( 6245): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/QRemote ( 6245): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 6245): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,I/QRemote ( 6245): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 6245): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 6245): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 6245): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 6245): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 6245): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6245): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6245): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6245): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,V/[BNRBootReceiver]( 5905): boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/BNRAndroBeam( 5905): [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
D/QRemote ( 6245): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
V/[BNRBootReceiver]( 5905): Boot Receiver Return
D/PostponalbeReceiver( 5145): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/QRemote ( 6245): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
V/WiFiOffLoadBroadcast( 6079): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6079): MCCMNC not supported: null
,D/QRemote ( 6245): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6245): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6245): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/WiFiOffLoadBroadcast( 6079): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,D/WiFiOffLoadBroadcast( 6079): Not supported operator for automatic switch
V/QRemote ( 6245): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6245): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,D/QRemote ( 6245): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
D/LgDataFeature( 6245): LgDataFeature() Constructor: none
,D/LgDataFeature( 6245): LgDataFeature() Constructor Done, null
V/SoundPool( 6245): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 6245): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 6245): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 6245): doLoad: loading sample sampleID=1
V/SoundPool( 6245): Start decode
V/MediaPlayer[Native]( 6245): decode(31, 10857164, 17813)
V/MediaPlayerService(  318): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  318): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  318): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  318): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  318): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  318): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  318): player type = 3
V/AwesomePlayer(  318): AwesomePlayer create()
,V/AwesomePlayer(  318): reset_l() 
V/AwesomePlayer(  318): cancelPlayerEvents
V/AwesomePlayer(  318): setAudioSink() 
V/AwesomePlayer(  318): reset_l() 
V/AudioCache(  318): notify(0xb1163200, 8, 0, 0)
V/AudioCache(  318): ignored
V/AwesomePlayer(  318): cancelPlayerEvents
I/QRemote ( 6245): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
D/Utils   (  318): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  318): setDataSource_l dataSource
V/LGParserOSAL(  318): SniffLGParser start
V/LGParserOSAL(  318): MainType:5, SubType=0
V/LGParserOSAL(  318): #### check Mime : application/ogg
V/LGParserOSAL(  318): Detector mimeType:application/ogg, Confidence=1.000000
,E/MediaExtractor(  318): Use LGExtractor :application/ogg 
D/QRemote ( 6245): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
D/UEI.SmartControl( 5818): QS Service created
,E/QRemote ( 6245): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6245): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
E/QC-QMI  ( 6203): qmi_client [6203] 13: failed to locate client data
E/QC-QMI  (  460): qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
E/QC-QMI  (  460): QMUX qmux_client_id=13 not found in qmux client list, unable to remove
I/UEI.SmartControl( 5818): Service initServices...
D/UEI.SmartControl( 5818): QS start get config
,V/LGParserOSAL(  318): supported mime: application/ogg
V/AwesomePlayer(  318): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  318): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  318): mBitrate = -1 bits/sec
V/AwesomePlayer(  318): AudioTrack Setting
V/AwesomePlayer(  318): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  318): setAudioSource() 
V/MediaPlayerService(  318): prepare
V/AwesomePlayer(  318): prepareAsync_l() 
V/MediaPlayerService(  318): wait for prepare
V/AwesomePlayer(  318): onPrepareAsyncEvent() 
V/AwesomePlayer(  318): initAudioDecoder() 
W/Utils   (  318): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  318): isOffloadSupported()
V/AudioPolicyManager(  318): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  318): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  318): isAudioPlaybackHookOn() false
V/AwesomePlayer(  318): getUseOffload() = 0 
V/OMXCodec(  318): OMXCodec::Create
V/OMXCodec(  318): findMatchingCodecs()
V/OMXCodec(  318): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  318): matchingCodecs.size()=1
V/OMXCodec(  318): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
D/OMXCodec(  318): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  318): LG Codec Adapter start
V/OMXCodec(  318): OMXCodec Createtor
V/OMXCodec(  318): setComponentRole
V/OMXCodec(  318): configureCodec protected=0
V/LGCodecAdapter(  318): called getLGCodecSpecificData
V/LGCodecOSAL(  318): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  318): Called LGconfigureCodecMETA
V/LGCodecOSAL(  318): Called LGconfigureCodecMSG
V/LGCodecOSAL(  318): Not support LGCodec
V/OMXCodec(  318): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  318): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  318): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  318): Could not offload audio decode, try pcm offload
W/Utils   (  318): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  318): isOffloadSupported()
V/AudioPolicyManager(  318): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  318): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  318): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  318): init()
V/OMXCodec(  318): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  318): allocateBuffers
V/OMXCodec(  318): allocateBuffersOnPort portIndex=0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb1434420 on input port
,V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb14344c0 on input port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb1434510 on input port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb1434560 on input port
V/OMXCodec(  318): allocateBuffersOnPort portIndex=1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb1434650 on output port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb14346f0 on output port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb1434740 on output port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb1434790 on output port
V/OMXCodec(  318): init() mAsyncCompletion wait!!! 
V/OMXCodec(  318): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  318): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  318): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  318): init() mAsyncCompletion wait!!! 
V/OMXCodec(  318): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  318): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  318): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  318): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  318): finishAsyncPrepare_l() 
V/AudioCache(  318): notify(0xb1163200, 5, 0, 0)
V/AudioCache(  318): ignored
V/AudioCache(  318): notify(0xb1163200, 1, 0, 0)
V/AudioCache(  318): prepared
V/AudioCache(  318): wait - success
V/MediaPlayerService(  318): start
V/AwesomePlayer(  318): play_l() 
V/AwesomePlayer(  318): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  318): createAudioPlayer_l
V/AwesomePlayer(  318): seekAudioIfNecessary_l() 
V/AwesomePlayer(  318): startAudioPlayer_l() 
D/AudioPlayer(  318): start of Playback, useOffload 0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  318): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  318): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  318): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  318): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  318): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/LGMDMManager( 6245): Create singleton instance
V/OMXCodec(  318): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973976144
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973976304
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973976384
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973976464
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  318): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  318): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  318): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  318): allocateBuffersOnPort portIndex=1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb1434740 on output port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb14346f0 on output port
V/OMXCodec(  318): [OMX.,google.vorbis.decoder] allocated buffer 0xb1434650 on output port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb1434f10 on output port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  318): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  318): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  318): notify(0xb1163200, 6, 0, 0)
V/AudioCache(  318): ignored
V/MediaPlayerService(  318): wait for playback complete
V/AudioCache(  318): write(0xb1249000, 4096)
V/AudioCache(  318): memcpy(0xab406000, 0xb1249000, 4096)
V/AudioCache(  318): write(0xb1249000, 4096)
V/AudioCache(  318): memcpy(0xab407000, 0xb1249000, 4096)
V/AudioCache(  318): write(0xb1249000, 4096)
V/AudioCache(  318): memcpy(0xab408000, 0xb1249000, 4096)
V/AudioCache(  318): write(0xb1249000, 4096)
V/AudioCache(  318): memcpy(0xab409000, 0xb1249000, 4096)
V/AudioCache(  318): write(0xb1249000, 4096)
V/AudioCache(  318): memcpy(0xab40a000, 0xb1249000, 4096)
V/AudioCache(  318): write(0xb1249000, 4096)
V/AudioCache(  318): memcpy(0xab40b000, 0xb1249000, 4096)
V/AudioCache(  318): write(0xb1249000, 4096)
V/AudioCache(  318): memcpy(0xab40c000, 0xb1249000, 4096)
,V/AudioCache(  318): write(0xb1249000, 4096)
V/AudioCache(  318): memcpy(0xab40d000, 0xb1249000, 4096)
V/AudioCache(  318): write(0xb1249000, 4096)
V/AudioCache(  318): memcpy(0xab40e000, 0xb1249000, 4096)
V/AudioCache(  318): write(0xb1249000, 4096)
V/AudioCache(  318): memcpy(0xab40f000, 0xb1249000, 4096)
V/AudioCache(  318): write(0xb1249000, 4096)
V/AudioCache(  318): memcpy(0xab410000, 0xb1249000, 4096)
V/AudioCache(  318): write(0xb1249000, 4096)
V/AudioCache(  318): memcpy(0xab411000, 0xb1249000, 4096)
V/AudioCache(  318): write(0xb1249000, 4096)
V/AudioCache(  318): memcpy(0xab412000, 0xb1249000, 4096)
V/AudioCache(  318): write(0xb1249000, 4096)
V/AudioCache(  318): memcpy(0xab413000, 0xb1249000, 4096)
V/AudioCache(  318): write(0xb1249000, 4096)
V/AudioCache(  318): memcpy(0xab414000, 0xb1249000, 4096)
V/AudioCache(  318): write(0xb1249000, 4096)
V/AudioCache(  318): memcpy(0xab415000, 0xb1249000, 4096)
V/AudioCache(  318): write(0xb1249000, 4096)
V/AudioCache(  318): memcpy(0xab416000, 0xb1249000, 4096)
V/AudioCache(  318): write(0xb1249000, 4096)
V/AudioCache(  318): memcpy(0xab417000, 0xb1249000, 4096)
V/AudioCache(  318): write(0xb1249000, 4096)
V/AudioCache(  318): memcpy(0xab418000, 0xb1249000, 4096)
V/AudioCache(  318): write(0xb1249000, 4096)
V/AudioCache(  318): memcpy(0xab419000, 0xb1249000, 4096)
V/AudioCache(  318): write(0xb1249000, 4096)
V/AudioCache(  318): memcpy(0xab41a000, 0xb1249000, 4096)
V/AudioCache(  318): write(0xb1249000, 4096)
V/AudioCache(  318): memcpy(0xab41b000, 0xb1249000, 4096)
V/AudioCache(  318): write(0xb1249000, 4096)
V/AudioCache(  318): memcpy(0xab41c000, 0xb1249000, 4096)
V/AudioCache(  318): write(0xb1249000, 4096)
V/AudioCache(  318): memcpy(0xab41d000, 0xb1249000, 4096)
V/AudioCache(  318): write(0xb1249000, 4096)
V/AudioCache(  318): memcpy(0xab41e000, 0xb1249000, 4096)
V/AudioCache(  318): write(0xb1249000, 4096)
V/AudioCache(  318): memcpy(0xab41f000, 0xb1249000, 4096)
V/AudioCache(  318): write(0xb1249000, 4096)
V/AudioCache(  318): memcpy(0xab420000, 0xb1249000, 4096)
V/AudioCache(  318): write(0xb1249000, 4096)
V/AudioCache(  318): memcpy(0xab421000, 0xb1249000, 4096)
V/AudioCache(  318): write(0xb1249000, 4096)
V/AudioCache(  318): memcpy(0xab422000, 0xb1249000, 4096)
V/AudioCache(  318): write(0xb1249000, 4096)
V/AudioCache(  318): memcpy(0xab423000, 0xb1249000, 4096)
V/AudioCache(  318): write(0xb1249000, 4096)
V/AudioCache(  318): memcpy(0xab424000, 0xb1249000, 4096)
V/AudioCache(  318): write(0xb1249000, 4096)
V/AudioCache(  318): memcpy(0xab425000, 0xb1249000, 4096)
V/AudioCache(  318): write(0xb1249000, 4096)
V/AudioCache(  318): memcpy(0xab426000, 0xb1249000, 4096)
V/AudioCache(  318): write(0xb1249000, 4096)
V/AudioCache(  318): memcpy(0xab427000, 0xb1249000, 4096)
V/AudioCache(  318): write(0xb1249000, 4096)
V/AudioCache(  318): memcpy(0xab428000, 0xb1249000, 4096)
V/AudioCache(  318): write(0xb1249000, 4096)
V/AudioCache(  318): memcpy(0xab429000, 0xb1249000, 4096)
V/AudioCache(  318): write(0xb1249000, 4096)
V/AudioCache(  318): memcpy(0xab42a000, 0xb1249000, 4096)
V/AudioCache(  318): write(0xb1249000, 4096)
V/AudioCache(  318): memcpy(0xab42b000, 0xb1249000, 4096)
,V/AudioCache(  318): write(0xb1249000, 4096)
V/AudioCache(  318): memcpy(0xab42c000, 0xb1249000, 4096)
V/AudioCache(  318): write(0xb1249000, 4096)
V/AudioCache(  318): memcpy(0xab42d000, 0xb1249000, 4096)
V/AudioCache(  318): write(0xb1249000, 4096)
V/AudioCache(  318): memcpy(0xab42e000, 0xb1249000, 4096)
V/AudioCache(  318): write(0xb1249000, 4096)
V/AudioCache(  318): memcpy(0xab42f000, 0xb1249000, 4096)
V/AudioCache(  318): write(0xb1249000, 4096)
V/AudioCache(  318): memcpy(0xab430000, 0xb1249000, 4096)
V/AudioCache(  318): write(0xb1249000, 4096)
V/AudioCache(  318): memcpy(0xab431000, 0xb1249000, 4096)
V/AudioCache(  318): write(0xb1249000, 4096)
V/AudioCache(  318): memcpy(0xab432000, 0xb1249000, 4096)
V/AudioCache(  318): write(0xb1249000, 4096)
V/AudioCache(  318): memcpy(0xab433000, 0xb1249000, 4096)
V/AudioCache(  318): write(0xb1249000, 4096)
V/AudioCache(  318): memcpy(0xab434000, 0xb1249000, 4096)
V/AudioCache(  318): write(0xb1249000, 4096)
V/AudioCache(  318): memcpy(0xab435000, 0xb1249000, 4096)
V/AudioCache(  318): write(0xb1249000, 4096)
V/AudioCache(  318): memcpy(0xab436000, 0xb1249000, 4096)
V/AudioCache(  318): write(0xb1249000, 4096)
V/AudioCache(  318): memcpy(0xab437000, 0xb1249000, 4096)
V/OMXCodec(  318): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  318): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  318): postAudioEOS() 
V/AudioCache(  318): write(0xb1249000, 280)
V/AudioCache(  318): memcpy(0xab438000, 0xb1249000, 280)
V/AwesomePlayer(  318): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  318): onStreamDone
V/AwesomePlayer(  318): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  318): notify(0xb1163200, 2, 0, 0)
V/AudioCache(  318): playback complete
V/AwesomePlayer(  318): pause_l() 
V/AudioCache(  318): notify(0xb1163200, 7, 0, 0)
V/AudioCache(  318): ignored
V/AwesomePlayer(  318): cancelPlayerEvents
,D/AudioPlayer(  318): Pause Playback at 1068125
V/AudioCache(  318): wait - success
V/MediaPlayerService(  318): return size 205080, sampleRate=48000, channelCount = 2, format = 1
V/AwesomePlayer(  318): reset_l() 
V/AudioCache(  318): notify(0xb1163200, 8, 0, 0)
V/AudioCache(  318): ignored
V/AwesomePlayer(  318): cancelPlayerEvents
D/AudioPlayer(  318): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  318): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  318): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  318): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  318): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  318): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeing buffer 0xb1434560 on port 0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeing buffer 0xb1434510 on port 0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeing buffer 0xb14344c0 on port 0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeing buffer 0xb1434420 on port 0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeing buffer 0xb1434f10 on port 1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeing buffer 0xb1434650 on port 1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeing buffer 0xb14346f0 on port 1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeing buffer 0xb1434740 on port 1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  318): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  318): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  318): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  318): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  318): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  318): AudioPlayer releasing audio source
D/AudioPlayer(  318): AudioPlayer done releasing audio source
V/AwesomePlayer(  318): reset_l() 
V/AwesomePlayer(  318): cancelPlayerEvents
V/AwesomePlayer(  318): ~AwesomePlayer call
V/AwesomePlayer(  318): reset_l() 
V/AwesomePlayer(  318): cancelPlayerEvents
V/SoundPool( 6245): close(31)
V/SoundPool( 6245): pointer = 0x9ff3c000, size = 205080, sampleRate = 48000, numChannels = 2
,I/qcom-bluetooth( 6283): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:64:c0 
D/QRemote ( 6245): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
I/qcom-bluetooth( 6284): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
D/QRemote ( 6245): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,D/QRemote ( 6245): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:1432
I/bt_vendor( 6049): bluetooth satus is on
D/bt_hci_bdroid( 6049): preload
D/bt_userial_mct( 6049): userial_open(port:0)
I/bt_vendor( 6049): bt-vendor : BT_VND_OP_USERIAL_OPEN
I/bt_vendor( 6049): Done intiailizing UART
I/bt_vendor( 6049): Done intiailizing UART
I/bt_userial_mct( 6049): CMD=66, EVT=66, ACL_Out=67, ACL_In=67
,I/bt_vendor( 6049): Bluetooth Firmware and transport layer are initialized
D/bt_userial_mct( 6049): Entering userial_read_thread()
I/bt-btu  ( 6049): btu_task received preload complete event
W/bt-l2cap( 6049): L2CAP - L2CA_Register() called for PSM: 0x0001
,W/bt-l2cap( 6049): L2CAP - L2CA_Register() called for PSM: 0x001f
W/bt-l2cap( 6049): L2CAP - L2CA_Register() called for PSM: 0x0003
I/        ( 6049): BTE_InitTraceLevels -- TRC_HCI
I/        ( 6049): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 6049): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 6049): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 6049): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 6049): BTE_InitTraceLevels -- TRC_A2D
I/        ( 6049): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 6049): BTE_InitTraceLevels -- TRC_BTM
I/        ( 6049): BTE_InitTraceLevels -- TRC_HID_HOST
I/        ( 6049): BTE_InitTraceLevels -- TRC_GAP
I/        ( 6049): BTE_InitTraceLevels -- TRC_PAN
I/        ( 6049): BTE_InitTraceLevels -- TRC_SDP
I/        ( 6049): BTE_InitTraceLevels -- TRC_GATT
I/        ( 6049): BTE_InitTraceLevels -- TRC_SMP
I/        ( 6049): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 6049): BTE_InitTraceLevels -- TRC_BTIF
W/bt-btm  ( 6049): btm_decode_ext_features_page Secure conn Controller support Enabled
E/bt-btm  ( 6049): BTM_SecRegister:p_cb_info->p_le_callback == 0xa01d4061 
E/bt-btm  ( 6049): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01d4061 
,W/bt-l2cap( 6049): L2CAP - L2CA_Register() called for PSM: 0x0019
W/bt-l2cap( 6049): L2CAP - L2CA_Register() called for PSM: 0x0017
W/bt-l2cap( 6049): L2CAP - L2CA_Register() called for PSM: 0x001b
E/bt-btif ( 6049): L2CAP - L2CA_Registe
W/bt-l2cap( 6049): L2CAP - L2CA_Register() called for PSM: 0x0011
W/bt-l2cap( 6049): L2CAP - L2CA_Register() called for PSM: 0x0013
E/bt-btif ( 6049): btif_storage_get_adapter_property service_mask:0x2140040
D/BluetoothAdapterProperties( 6049): Address is:58:3F:54:73:64:C0
D/BluetoothManagerService( 1033): Bluetooth Adapter name changed to G3-1
D/BluetoothManagerService( 1033): Stored Bluetooth name: G3-1
D/BluetoothAdapterProperties( 6049): Name is: G3-1
D/BluetoothAdapterProperties( 6049): Scan Mode:20
D/BluetoothAdapterProperties( 6049): Discoverable Timeout:120
,D/bt_hci_bdroid( 6049): postload
D/bt_hci_bdroid( 6049): Used up Tx Cmd credits
D/bt_hci_bdroid( 6049): Used up Tx Cmd credits
D/bt_hci_bdroid( 6049): Used up Tx Cmd credits
W/bt-l2cap( 6049): L2CAP - L2CA_Register() called for PSM: 0x000f
D/bt_hci_bdroid( 6049): Used up Tx Cmd credits
D/bt_hci_bdroid( 6049): Used up Tx Cmd credits
D/bt_hci_bdroid( 6049): Used up Tx Cmd credits
D/bt_hci_bdroid( 6049): Used up Tx Cmd credits
E/bt_mct  ( 6049): hci lib postload completed
D/bte_conf( 6049): Device ID record 1 : primary
D/bte_conf( 6049):   vendorId            = 00c4
,D/bte_conf( 6049):   vendorIdSource      = 0001
D/bte_conf( 6049):   product             = 13a1
D/bte_conf( 6049):   version             = 1000
D/bte_conf( 6049):   clientExecutableURL = 
D/bte_conf( 6049):   serviceDescription  = 
D/bte_conf( 6049):   documentationURL    = 
D/bte_conf( 6049): bte_load_did_conf no section named DID2.
W/bt-smp  ( 6049): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6049): Plain text(LSB ~ MSB) = 06 5f 7e 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6049): Encrypted text(LSB ~ MSB) = 7f 4e 06 23 f9 76 b7 c1 eb 1f 44 9d 70 8e e9 ff 
W/bt-btm  ( 6049): Stopping oneshot timer
D/BluetoothAdapterState( 6049): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
W/sh      ( 6288): type=1400 audit(0.0:159): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/BluetoothAdapterProperties( 6049): ScanMode =  20
D/BluetoothAdapterProperties( 6049): State =  11
D/BluetoothAdapterProperties( 6049): mDiscoverableTimeout = 120
D/BluetoothPanServiceJni( 6049): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
V/LGBluetoothServiceAdapter( 6049): [BTUI] state:11, scanmode:20, timeout:120
W/sh      ( 6288): type=1400 audit(0.0:160): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/BluetoothAdapterProperties( 6049): Setting state to 12
I/BluetoothAdapterState( 6049): Bluetooth adapter state changed: 11-> 12
D/btif_config_util( 6049): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
D/BluetoothManagerService( 1033): Message: 60
D/BluetoothManagerService( 1033): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService( 1033): Broadcasting onBluetoothStateChange(true) to 5 receivers.
D/BluetoothHeadset( 1033): onBluetoothStateChange: up=true
I/BluetoothAdapterState( 6049): Entering On State
D/BluetoothHeadset( 1840): onBluetoothStateChange: up=true
D/LGBluetoothServiceAdapter( 6049): [BTUI] OnState
D/LGBluetoothServiceAdapter( 6049): [BTUI]         global_name: G3-1
D/LGBluetoothServiceAdapter( 6049): [BTUI]         local_name: G3-1
D/BluetoothA2dp( 1033): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1840): onBluetoothStateChange: up=true
D/BluetoothAdapterService( 6049): [BTUI] autoConnect() : not allowed
D/BluetoothHeadset( 1840): onBluetoothStateChange: up=true
E/BluetoothManagerService( 1033): Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
D/BluetoothManagerService( 1033): Bluetooth State Change Intent: 11 -> 12
D/LGBluetoothAPIService( 1930): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/LGBluetoothAPIService( 1930): Message: 1
D/LGBluetoothAPIService( 1930): MESSAGE_BOOT_COMPLETED
I/[SystemUI]BluetoothHandler( 1463): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
I/LGBluetoothAPIService( 1930): [BTUI] LGBluetoothAPIService Binding Success
D/BluetoothManagerService( 1033): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
I/BluetoothMapService( 6049): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 6049): STATE_ON
W/bt-smp  ( 6049): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6049): Plain text(LSB ~ MSB) = 17 82 46 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6049): Encrypted text(LSB ~ MSB) = 99 6a 7b 2d c8 19 74 4b 40 5b 08 2c 42 55 e0 35 
W/bt-btm  ( 6049): Stopping oneshot timer
D/BluetoothManagerService( 1033): Message: 40
D/BluetoothManagerService( 1033): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,W/ContextImpl( 6079): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
W/bt-smp  ( 6049): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6049): Plain text(LSB ~ MSB) = ea 11 78 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6049): Encrypted text(LSB ~ MSB) = 57 72 8e 99 bb 71 e1 42 5e 80 3f e7 29 70 f6 d3 
W/bt-btm  ( 6049): Stopping oneshot timer
D/LGBluetoothAPIServer( 6049): [BTUI] onCreate()
D/LGBluetoothAPIServer( 6049): [BTUI] onBind()
V/BluetoothMapService( 6049): Handler(): got msg=1
D/LGBluetoothAPIService( 1930): [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
D/BluetoothMapMasInstance( 6049): Map Service startRfcommSocketListener
D/LGBluetoothAPIService( 1930): Message: 100
D/LGBluetoothAPIService( 1930): MESSAGE_BLUETOOTH_SERVICE_CONNECTED
D/BluetoothMapMasInstance( 6049): MAS initSocket()
D/BluetoothMapMasInstance( 6049):   masId = 00
D/BluetoothMapMasInstance( 6049):   msgTypes = 0e
D/BluetoothMapMasInstance( 6049):   masName = SMS/MMS
D/BluetoothMapMasInstance( 6049):   SDP string = 000eSMS/MMS
,D/BluetoothManagerService( 1033): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6049): getBluetoothService() called with no BluetoothManagerCallback
W/bt-smp  ( 6049): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6049): Plain text(LSB ~ MSB) = b0 20 74 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6049): Encrypted text(LSB ~ MSB) = b9 5b ba c0 10 0a 67 8c 89 51 f5 6c 63 42 d5 ff 
W/bt-btm  ( 6049): Stopping oneshot timer
D/LGBluetoothServiceAdapter( 6049): [BTUI] createSocketChannel FD=73 mFd=0
V/BluetoothMapMasInstance( 6049): Succeed to create listening socket 
D/BluetoothMapMasInstance( 6049): Accepting socket connection...
D/BluetoothAdapterService( 6049): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b68e808
V/BluetoothPbapService( 6049): Pbap Service onCreate
V/BluetoothPbapService( 6049): Starting PBAP service
D/LGBluetoothPbapAdapter( 6049): [BTUI] getInstance : create
V/BluetoothPbapService( 6049): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 6049): state: 12
V/BluetoothPbapReceiver( 6049): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 6049): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6049): ***********state = 12
W/bt-smp  ( 6049): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6049): Plain text(LSB ~ MSB) = 8d 47 70 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6049): Encrypted text(LSB ~ MSB) = 5e c6 60 ab e6 91 61 d3 11 f4 08 72 61 c1 27 f6 
W/bt-btm  ( 6049): Stopping oneshot timer
V/BluetoothPbapService( 6049): Handler(): got msg=1
V/BluetoothPbapService( 6049): Pbap Service startRfcommSocketListener
D/LocalBluetoothProfileManager( 6079): Adding local A2DP profile
V/BluetoothPbapService( 6049): Pbap Service initSocket
D/BluetoothManagerService( 1033): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1033): Message: 30
W/BluetoothAdapter( 6049): getBluetoothService() called with no BluetoothManagerCallback
,D/LGBluetoothServiceAdapter( 6049): [BTUI] createSocketChannel FD=75 mFd=73
,V/BluetoothPbapService( 6049): Succeed to create listening socket 
V/BluetoothPbapService( 6049): Accepting socket connection...
D/LocalBluetoothProfileManager( 6079): Adding local HEADSET profile
D/BluetoothManagerService( 1033): Message: 30
D/BluetoothManagerService( 1033): Message: 30
D/LGBluetoothDeviceModeControllManager( 6049): [BTUI] checkDeviceModeAndSet, sinkMode : false
D/BluetoothManagerService( 1033): Message: 30
D/LocalBluetoothProfileManager( 6079): Adding local MAP profile
D/BluetoothMap( 6079): Create BluetoothMap proxy object
I/qcom-bt-wlan-coex( 6296): /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
D/BluetoothManagerService( 1033): Message: 30
,D/BluetoothManagerService( 1033): Message: 30
D/LocalBluetoothProfileManager( 6079): LocalBluetoothProfileManager construction complete
V/BluetoothPbapService( 6049): Pbap Service onBind
D/LGBluetoothUserBindClient( 6079): [BTUI] initUserBindClient
W/ContextImpl( 6079): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
,D/DockEventReceiver( 6079): finishStartingService: stopping service
D/BluetoothA2dp( 6079): Proxy object connected
D/A2dpProfile( 6079): Bluetooth service connected
D/BluetoothHeadset( 6079): Proxy object connected
,D/HeadsetProfile( 6079): Bluetooth service connected
D/BluetoothInputDevice( 6079): Proxy object connected
D/HidProfile( 6079): Bluetooth service connected
D/BluetoothPan( 6079): BluetoothPAN Proxy object connected
D/PanProfile( 6079): Bluetooth service connected
D/BluetoothMap( 6079): Proxy object connected
D/MapProfile( 6079): Bluetooth service connected
D/BluetoothMap( 6079): getConnectedDevices()
V/BluetoothMapService( 6049): getConnectedDevices()
D/BluetoothPbap( 6079): Proxy object connected
D/PbapServerProfile( 6079): Bluetooth service connected
D/LGBluetoothUserBindClient( 6079): [BTUI] onServiceConnected
D/BluetoothAdapterProperties( 6049): Discoverable Timeout:120
D/LGBluetoothDeviceModeControllManager( 6049): adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
D/BluetoothPermissionRequest( 6079): onReceive
D/BluetoothAdapterProperties( 6049): Scan Mode:21
D/LGBluetoothDeviceModeControllManager( 6049): getDeviceMode  deviceMode 0
,D/LGBluetoothFeatureConfig( 6079): isPrivacyLogsEnabled : true
D/LGBluetoothUtils( 6079): [BTUI] FileNotFound: readProperty
D/LGBluetoothResetSettingReceiver( 6079): return without doing reset settings.
V/BluetoothOppReceiver( 6049): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
I/LGBluetoothOppAdapter( 6049): [BTUI] startOppService()
V/BluetoothOppManager( 6049): restoreApplicationData! falsefalsenullnull
,D/LGBluetoothFeatureConfig( 6049): isPrivacyLogsEnabled : true
,V/BtOppService( 6049): onCreate
V/BluetoothOppNotification( 6049): send message
V/BtOppService( 6049): Starting RfcommListener
D/BluetoothOppPreference( 6049): Dumping Names:  
D/BluetoothOppPreference( 6049): {}
D/BluetoothOppPreference( 6049): Dumping Channels:  
D/BluetoothOppPreference( 6049): {}
V/BtOppService( 6049): onStartCommand
V/BluetoothFtpReceiver( 6049): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpReceiver( 6049): BluetoothFtpReceiver Start Service
V/BluetoothOppNotification( 6049): new notify threadi!
V/BtOppService( 6049): Deleted complete outbound shares, number =  0
,V/BluetoothOppNotification( 6049): send delay message
V/BtOppService( 6049): start RfcommListener
V/BluetoothOppProvider( 6049): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
V/BtOppService( 6049): pendingUpdate is true keepUpdateThread is false sListenStarted is true
V/BluetoothOppProvider( 6049): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
V/BtOppService( 6049): RfcommListener started
V/BluetoothOppProvider( 6049): created cursor android.database.sqlite.SQLiteCursor@33844d62 on behalf of 
V/BtOppRfcommListener( 6049): Starting RFCOMM listener....
V/BluetoothOppProvider( 6049): created cursor android.database.sqlite.SQLiteCursor@3ab4fef3 on behalf of 
D/BluetoothManagerService( 1033): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6049): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 6049): [BTUI] createSocketChannel FD=80 mFd=75
V/BtOppRfcommListener( 6049): Started RFCOMM listener....
I/BtOppRfcommListener( 6049): Accept thread started.
V/BtOppRfcommListener( 6049): Accepting connection...
V/BtOppService( 6049): Deleted complete inbound failed shares, number = 0
V/BluetoothOppNotification( 6049): mUpdateCompleteNotification = true
V/BluetoothOppProvider( 6049): starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6049): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 6049): created cursor android.database.sqlite.SQLiteCursor@7b0c7b0 on behalf of 
V/BluetoothOppProvider( 6049): created cursor android.database.sqlite.SQLiteCursor@53cd629 on behalf of 
,V/BtOppService( 6049): pendingUpdate is false keepUpdateThread is false sListenStarted is true
D/BluetoothAdapterService( 6049): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b68e808
V/BluetoothFtpService( 6049): Ftp Service onCreate
I/BluetoothFtpService( 6049): Ftp Service onCreate
V/BluetoothOppNotification( 6049): outbound: succ-0  fail-0
V/BluetoothFtpService( 6049): Ftp Service onStartCommand
V/BluetoothFtpService( 6049): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpService( 6049): Starting Listening on sockets
V/BluetoothSapReceiver( 6049): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 6049): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 6049): SapReceiver onReceive 
V/BluetoothSapReceiver( 6049): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6049):  Bluetooth Adapter state = 12
V/BluetoothSapReceiver( 6049): Calling SAP service start service with action = null
V/BluetoothOppNotification( 6049): outbound notification was removed.
V/BluetoothOppProvider( 6049): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 6049): created cursor android.database.sqlite.SQLiteCursor@2a96974f on behalf of 
V/BtOppService( 6049): ContentObserver received notification
V/BtOppService( 6049): ContentObserver received notification
V/BluetoothFtpService( 6049): Handler(): got msg=1
V/BluetoothOppNotification( 6049): inbound: succ-0  fail-0
V/BluetoothFtpService( 6049): Ftp Service startRfcommSocketListener
V/BluetoothFtpService( 6049): Ftp Service initSocket
V/BtOppService( 6049): pendingUpdate is true keepUpdateThread is false sListenStarted is true
V/BluetoothOppProvider( 6049): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6049): created cursor android.database.sqlite.SQLiteCursor@1a52aedc on behalf of 
V/BluetoothOppNotification( 6049): update too frequent, put in queue
V/BluetoothOppNotification( 6049): inbound notification was removed.
V/BluetoothOppProvider( 6049): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
D/AuthorizationBluetoothService( 2133): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/BluetoothManagerService( 1033): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
V/BluetoothOppProvider( 6049): created cursor android.database.sqlite.SQLiteCursor@a3abe5 on behalf of 
V/BtOppService( 6049): pendingUpdate is false keepUpdateThread is false sListenStarted is true
W/BluetoothAdapter( 6049): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 6049): [BTUI] createSocketChannel FD=82 mFd=80
V/BluetoothFtpService( 6049): Succeed to create listening socket on channel 20
,V/BluetoothFtpService:RfcommSocketAcceptThread( 6049): Run Accept thread
D/BluetoothAdapterService( 6049): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b68e808
V/BluetoothSapService( 6049): Sap Service onCreate
V/BluetoothSapService( 6049): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 6049): state: 12
V/BluetoothSapService( 6049): Starting SAP server process
,V/BluetoothSapService( 6049): SAP Service startRfcommListenerThread
V/BluetoothSapService( 6049): Sap Service initRfcommSocket
D/BluetoothManagerService( 1033): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6049): getBluetoothService() called with no BluetoothManagerCallback
V/BluetoothSapService( 6049): Succeed to create listening socket 
V/BluetoothSapService( 6049): Accepting socket connection...
W/sapd    ( 6311): type=1400 audit(0.0:161): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/sapd    ( 6311): type=1400 audit(0.0:162): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
V/BT_SAP  ( 6311): Event pipe created
V/BT_SAP  ( 6311): create_server_socket qcom.sap.server
V/BT_SAP  ( 6311): created socket fd 6
,I/UEI.SmartControl( 5818): Supports setup maps: true
,D/UEI.SmartControl( 5818): QS start statue = true Error code = 0
I/UEI.SmartControl( 5818): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 5818): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 5818): ### init IR Blaster...
D/serial_port( 5818): Configuring serial port
E/UEI.SmartControl( 5818): UEIBLaster setting for 616
I/UEI.SmartControl( 5818): Setting serial record hearder size = 2
I/UEI.SmartControl( 5818): configuring settings for MAXQ616
I/UEI.SmartControl( 5818): Get version...
D/UEI.SmartControl( 5818): serial port data available: 21
,D/UEI.SmartControl( 5818): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 5818): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 5818): QS saving settings...
,D/UEI.SmartControl( 5818): IR Blaster version: 25672567
,D/UEI.SmartControl( 5818): serial port data available: 4
,I/UEI.SmartControl( 5818): Device manager: loading config....
D/UEI.SmartControl( 5818): ----------- loading internal config...
,W/ContextImpl( 5818): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
E/UEI.SmartControl( 5818): Services init done
D/UEI.SmartControl( 5818): QS Service init finished
D/UEI.SmartControl( 5818): QS Service version name: 2.1.91
D/UEI.SmartControl( 5818): QS Service version code: 201091
D/UEI.SmartControl( 5818): Service requested: Control
E/UEI.SmartControl( 5818): Loading SETTINGS...
D/UEI.SmartControl( 5818): Request IControl service: devices are loaded...
,I/QRemote ( 6245): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 5818): ------ IControl API: 11
D/UEI.SmartControl( 5818): File observer start...
E/UEI.SmartControl( 5818): IR Port is disabled: false
D/UEI.SmartControl( 5818): Internal service binding...
D/UEI.SmartControl( 5818): Starting file observer...
I/UEI.SmartControl( 5818): Registering callback...
I/UEI.SmartControl( 5818): ------ IControl API: 19
I/UEI.SmartControl( 5818): Registering Services Ready callback...
D/UEI.SmartControl( 5818): -- Open brand translation xml: brands_translations_ko
,I/UEI.SmartControl( 5818): Notify AllClients services are ready: 0
D/UEI.SmartControl( 5818): -----service ready thread exits
I/QRemote ( 6245): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 6245): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 6245): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 6245): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
,D/QRemote ( 6245): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 5818): ------ IControl API: 8
D/QRemote ( 6245): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 6245): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 6245): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 6245): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 6245): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6245): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
,D/QRemote ( 6245): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
V/QRemote ( 6245): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6245): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 6245): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6245): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 6245): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6245): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 6245): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
,D/QRemote ( 6245): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1454434022876]
D/QRemote ( 6245): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
I/ActivityManager( 1033): Killing 5795:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,D/QRemote ( 6245): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,W/libprocessgroup( 1033): failed to open /acct/uid_10061/pid_5795/cgroup.procs: No such file or directory
,V/QRemote ( 6245): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
E/QRemote ( 6245): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6245): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 6245): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 6245): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 6245): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 6245): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 6245): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,I/wpa_supplicant( 6090): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1033): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1033): WifiMonitor:wlan0 cnt=13 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1033): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1033): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,V/BluetoothOppNotification( 6049): new notify threadi!
,V/BluetoothOppNotification( 6049): send delay message
V/BluetoothOppProvider( 6049): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,V/BluetoothOppProvider( 6049): created cursor android.database.sqlite.SQLiteCursor@e82161 on behalf of 
V/BluetoothOppNotification( 6049): mUpdateCompleteNotification = true
V/BluetoothOppProvider( 6049): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 6049): created cursor android.database.sqlite.SQLiteCursor@f07f486 on behalf of 
V/BluetoothOppNotification( 6049): outbound: succ-0  fail-0
V/BluetoothOppNotification( 6049): outbound notification was removed.
V/BluetoothOppProvider( 6049): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,V/BluetoothOppProvider( 6049): created cursor android.database.sqlite.SQLiteCursor@38882147 on behalf of 
V/BluetoothOppNotification( 6049): inbound: succ-0  fail-0
V/BluetoothOppNotification( 6049): inbound notification was removed.
V/BluetoothOppProvider( 6049): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6049): created cursor android.database.sqlite.SQLiteCursor@1003fd74 on behalf of 
,I/jxcore-log( 5968): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 5968): 
,E/wpa_supplicant( 6090): USIM:  scard_init function
I/wpa_supplicant( 6090): Trying to associate with SSID 'NG700'
E/WifiMonitor( 1033): WifiMonitor:wlan0 cnt=14 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1033): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1033): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1033): WifiMonitor:wlan0 cnt=15 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1033): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1033): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1033): WifiMonitor:wlan0 cnt=16 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,I/jxcore-log( 5968): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 5968): 
E/WifiStateMachine( 1033):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=2 known=0 got=2 bcn=0
E/WifiStateMachine( 1033):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=2 known=0 got=2 bcn=0
E/WifiStateMachine( 1033):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=2 known=0 got=2 bcn=0
E/WifiStateMachine( 1033):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=2 known=0 got=2 bcn=0
I/WifiNative-HAL( 1033): startHal
E/wifi    ( 1033): getStaticLongField sWifiHalHandle 0x9893a8cc
E/WifiHAL ( 1033): Could not connect handle
D/wifi    ( 1033): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x601c2a
I/WifiNative-HAL( 1033): Could not start hal
D/WifiNative-wlan0( 1033): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1033):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 16 0 rt=113700  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
E/WifiStateMachine( 1033):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 16 0 rt=113701  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
W/Settings( 1033): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1033): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1033): NETWORK_STATE_CHANGED_ACTION [SCANNING]
W/Settings( 1033): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1033): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1033): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/WifiServerServiceExt( 1033): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1033): setSupplicantStateASSOCIATING
I/StatusBar.NetworkController( 1463): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1463): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1463): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1463): mWifiConnected = false, mWifiLevel = 0
D/PostponalbeReceiver( 5145): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WiFiOffLoadBroadcast( 6079): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6079): MCCMNC not supported: null
D/QRemote ( 6245): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6245): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6245): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 5145): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 6079): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6079): MCCMNC not supported: null
D/QRemote ( 6245): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6245): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6245): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/jxcore-log( 5968): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 5968): 
,I/jxcore-log( 5968): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
I/jxcore-log( 5968): 
I/jxcore-log( 5968): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 5968): 
,I/CloudHub( 2115): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19981
,D/WifiMonitor( 1033): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
I/wpa_supplicant( 6090): wlan0: Associated with c0:ff:d4:d3:aa:48
E/WifiMonitor( 1033): WifiMonitor:wlan0 cnt=17 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1033): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1033): WifiMonitor:wlan0 cnt=18 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
E/WifiStateMachine( 1033):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 17 0 rt=114725  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,D/WifiMonitor( 1033): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1033): WifiMonitor:wlan0 cnt=19 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1033):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 17 0 rt=114726  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1033):  DisconnectedState CMD_ASSOCIATED_BSSID 18 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=114727
E/WifiStateMachine( 1033):  ConnectModeState CMD_ASSOCIATED_BSSID 18 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=114727
E/WifiStateMachine( 1033):  DriverStartedState CMD_ASSOCIATED_BSSID 18 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=114727
E/WifiStateMachine( 1033):  SupplicantStartedState CMD_ASSOCIATED_BSSID 18 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=114727
E/WifiStateMachine( 1033):  DefaultState CMD_ASSOCIATED_BSSID 18 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=114727
E/WifiStateMachine( 1033):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=114728  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
D/Tethering( 1033): sendTetherStateChangedBroadcast 1, 0, 0
D/UsbSettingsReceiver( 6079): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6079): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6079): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6079): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=0
I/StatusBar.NetworkController( 1463): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1463): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
,W/Settings( 1033): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1033): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1033): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/DSQN    ( 1033): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/wpa_supplicant( 6090): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 6090): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1033): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1033): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1033): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1033): WifiMonitor:wlan0 cnt=21 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1033): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1033): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1033): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1033): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1033): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1033): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
W/Settings( 1033): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1033): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1033): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
I/StatusBar.NetworkController( 1463): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1463): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1033):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=114750  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
D/WifiServerServiceExt( 1033): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1033): setSupplicantStateASSOCIATED
E/WifiStateMachine( 1033):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1033):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1033):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1033):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1033):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1033):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 20 0 rt=114763  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1033):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 20 0 rt=114764  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1033):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=114764
E/WifiStateMachine( 1033):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=114765
,D/WifiNative-wlan0( 1033): doString: [STATUS]
D/WifiMonitor( 1033): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1033): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1033):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
I/WifiServiceExtension( 1033): setVHTCapabilityType  : false
D/UsbSettingsReceiver( 6079): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 6079): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6079): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6079): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6079): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6079): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6079): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 6079): [AUTORUN] setTetherStatus() : status=false
I/WifiServerServiceExt( 1033): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1033): setKeepAlivePacketInterval msec : 60
,W/Settings( 1033): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1033): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1033): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
W/Settings( 1033): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1033): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1033): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/StatusBar.NetworkController( 1463): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1463): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1463): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1463): mWifiConnected = false, mWifiLevel = 0
D/PostponalbeReceiver( 5145): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WiFiOffLoadBroadcast( 6079): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/ConnectivityService( 1033): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore( 1033): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1033): doBoolean: SET_NETWORK 0 bssid any
D/ConnectivityService( 1033): Got NetworkAgent Messenger
D/WifiNative-wlan0( 1033): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1033): doBoolean: SAVE_CONFIG
D/ConnectivityService( 1033): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1033): NetworkAgent connected
D/WifiNative-wlan0( 1033): SAVE_CONFIG: returned true
E/WifiConfigStore( 1033): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1033): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1033): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1033): doBoolean: SAVE_CONFIG
D/WiFiOffLoadBroadcast( 6079): MCCMNC not supported: null
D/WifiNative-wlan0( 1033): SAVE_CONFIG: returned true
D/CommandListener(  314): Setting iface cfg
,E/WifiStateMachine( 1033): Start Dhcp Watchdog 1
,E/WifiStateMachine( 1033):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=114823  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1033):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=114823  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1033):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=114824  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/DhcpStateMachine( 1033): StoppedState
D/DhcpStateMachine( 1033): StoppedState{ when=-2ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1033): WaitBeforeStartState
D/QRemote ( 6245): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 1033):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=114827  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/QRemote ( 6245): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
E/WifiStateMachine( 1033):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=114827  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1033):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=114827  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
I/QRemote ( 6245): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
E/WifiStateMachine( 1033):  ObtainingIpState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:-1559886800] from screen [on:0 period:-1559886800]
E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:-1559886800]
D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
D/WifiServerServiceExt( 1033): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1033): setSupplicantStateGROUP_HANDSHAKE
D/PostponalbeReceiver( 5145): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
,V/WiFiOffLoadBroadcast( 6079): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6079): MCCMNC not supported: null
D/ConnectivityService( 1033): updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
E/WifiStateMachine( 1033):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1033):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1033):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1033):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1033):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/QRemote ( 6245): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6245): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6245): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
E/WifiStateMachine( 1033):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1033): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
,D/PostponalbeReceiver( 5145): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6079): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 1033):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
,D/WifiServerServiceExt( 1033): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1033): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1033):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1033): doBoolean: DRIVER SETSUSPENDMODE 0
,D/WiFiOffLoadBroadcast( 6079): MCCMNC not supported: null
D/QRemote ( 6245): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6245): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6245): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 5145): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 6079): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6079): MCCMNC not supported: null
D/QRemote ( 6245): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6245): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/wpa_supplicant( 6090): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
,D/WifiNative-wlan0( 1033): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1033): doBoolean: SET ps 0
I/QRemote ( 6245): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/WifiNative-wlan0( 1033): SET ps 0: returned true
D/WifiNative-wlan0( 1033): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 6090): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1033): DRIVER BTCOEXMODE 1: returned true
D/LGWifiP2pService( 1033): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@68c0160 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1033): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@68c0160 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 1033): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
D/DhcpStateMachine( 1033): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
V/DhcpStateMachine( 1033): Current State is mWaitBeforeStartState.
D/DhcpStateMachine( 1033): DHCP Start wake lock is acquired.
V/LgDhcpStateMachineHelper( 1033): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
V/LgDhcpStateMachineHelper( 1033): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700" is not exist.
D/WifiServerServiceExt( 1033): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1033): setSupplicantStateCOMPLETED
D/DhcpStateMachine( 1033): DHCPV4 request on wlan0
,V/LgDhcpStateMachineHelper( 1033): [bssid] hash key :c0:ff:d4:d3:aa:48
,D/LgDhcpStateMachineHelper( 1033): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
W/dhcpcd  ( 6339): type=1400 audit(0.0:163): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 6339): type=1400 audit(0.0:164): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/dhcpcd  ( 6339): version 5.5.6 starting
,E/dhcpcd  ( 6339): get_duid: m
D/dhcpcd  ( 6339): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 6339): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
D/dhcpcd  ( 6339): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 6339): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 6339): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,I/dhcpcd  ( 6339): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 6339): wlan0: sending REQUEST (xid 0x5dfce6c4), next in 4.80 seconds
D/PowerManagerServiceEx( 1033): acquireWakeLockInternal: lock=575145497, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1033
,D/[Concierge]Service( 2612): onStartCommand(). Type : 9
,V/QRemote ( 6245): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
D/QRemote ( 6245): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:1432
,D/PowerManagerServiceEx( 1033): releaseWakeLockInternal: lock=575145497 [*alarm*], flags=0x0
,E/WifiStateMachine( 1033):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1033):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1033):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1033):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1033):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1033):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,D/ConnectivityService( 1033): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
D/UEI.SmartControl( 5818): Internal timer expired: 2
,D/UEI.SmartControl( 5818): unbind internal service
,D/serial_port( 5818): close(fd = 24)
,I/UEI.SmartControl( 5818): Serial port is closed.
I/dhcpcd  ( 6339): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
,I/dhcpcd  ( 6339): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 6339): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 6339): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 6339): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 6339): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 6339): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 6339): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 6339): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,E/WifiStateMachine( 1033):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1033):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1033):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1033):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1033):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1033):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,D/ConnectivityService( 1033): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
,D/DhcpStateMachine( 1033): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper( 1033): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1033): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1033): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1033): Add DhcpResults: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
V/DhcpStateMachine( 1033): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1033): bShouldSendDhcpAction Result: true
D/DhcpStateMachine( 1033): DHCP Start/Renew wake lock is released.
E/WifiStateMachine( 1033):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/DhcpStateMachine( 1033): RunningState
E/WifiStateMachine( 1033):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/LGWifiP2pService( 1033): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1033): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1033): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 6090): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1033): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1033): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 6090): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1033): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1033): doBoolean: SET ps 1
D/WifiNative-wlan0( 1033): SET ps 1: returned true
,E/WifiStateMachine( 1033):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1033):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1033): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1033): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
D/ConnectivityService( 1033): ignoring duplicate network state non-change
I/StatusBar.NetworkController( 1463): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1463): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1033): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1033): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1033): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
W/Settings( 1033): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 1033): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1033): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/ConnectivityService( 1033): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService( 1033): Adding iface wlan0 to network 100
D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/WifiHS20( 1033): [PASSPOINT] passpointNotification: hs20AP list is checked
I/StatusBar.NetworkController( 1463): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1463): mWifiConnected = false, mWifiLevel = 0
E/ConnectivityService( 1033): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1033): Adding Route [fe80::/64 -> :: wlan0] to network 100
,D/ConnectivityService( 1033): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
D/ConnectivityService( 1033): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
D/ConnectivityService( 1033): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1033): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 100
D/ConnectivityService( 1033): Setting Dns servers for network 100 to [/192.168.1.1]
W/Settings( 1033): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1033): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1033): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
E/WifiStateMachine( 1033): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
V/WfdStateTracker( 1930): handleWifiStateChangedEvent: 1
D/WifiHS20( 1033): [PASSPOINT] passpointNotification: hs20AP list is checked
D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1463): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1463): mWifiConnected = true, mWifiLevel = 2
D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1033): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1033): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1033): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/Nat464Xlat( 1033): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1033): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1033): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
D/PostponalbeReceiver( 5145): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/ConnectivityService( 1033): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1033):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1033):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1033):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1033):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1033):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1033): currentScore = 0, newScore = 20
D/ConnectivityService( 1033):    accepting network in place of null
D/ConnectivityService( 1033): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1033): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1033):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1033): DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1033): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1,033): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1033): Checking http://clients3.google.com/generate_204 on "NG700"
,D/libc-netbsd(  314): res_queryN name = clients3.google.com, class = 1, type = 28
D/TelephonyNetworkFactory-1( 1840): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1840):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/ConnectivityService( 1033): Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
E/ConnectivityService( 1033): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1033): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1033): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/LocSvc_java( 1033): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1033): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1033): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1033): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java( 1033): Sending msg: 5 arg1:0 arg2:1
,D/ConnectivityService( 1033): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
D/CSLegacyTypeTracker( 1033): [e] list.add(nai) empty : false size: 1
D/libc-netbsd(  314): res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
D/libc-netbsd(  314): res_queryN name = 2.android.pool.ntp.org., class = 1, type = 1
D/ConnectivityService( 1033): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/DSQN    ( 1033): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/ConnectivityService( 1033): validation of new default Network = false
D/ConnectivityService( 1033): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1033): enableDataServiceNotify 
D/DSQN    ( 1033): start dsqn bin
,D/ConnectivityService( 1033): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1033):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1033):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1033): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1463): CM callback handler got msg 524290
I/StatusBar.NetworkController( 1463): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1463): mWifiConnected = true, mWifiLevel = 2
W/dsqn    ( 6411): type=1400 audit(0.0:165): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 6411): type=1400 audit(0.0:166): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
E/DSQN    ( 6411): DSQN ssw
,V/NetworkPolicy( 1033): [LG_RESTRICTED] checkMobilePolicy_type()
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  314): res_queryN name = europe.pool.ntp.org, class = 1, type = 1
,D/TelephonyIcons( 1463): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WiFiOffLoadBroadcast( 6079): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6079): MCCMNC not supported: null
D/QRemote ( 6245): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6245): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/libc-netbsd(  314): res_queryN name = clients3.google.com, class = 1, type = 1
I/QRemote ( 6245): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 5145): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6079): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6079): MCCMNC not supported: null
D/QRemote ( 6245): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6245): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6245): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 5145): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 6178): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6178): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6079): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/libc-netbsd(  314): res_queryN name = clients3.google.com succeed
,D/WiFiOffLoadBroadcast( 6079): MCCMNC not supported: null
D/QRemote ( 6245): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6245): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6245): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6245): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6245): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 5145): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,D/libc-netbsd(  314): res_queryN name = europe.pool.ntp.org succeed
I/PCSuite ( 6178): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6178): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
D/LGDataListener(  314): argv[0]=dsqncommand
D/LGDataListener(  314): argv[1]=wlan0
D/LGDataListener(  314): argv[2]=1
D/LGDataListener(  314): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1033): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1033): start to monitor internet connection
V/WiFiOffLoadBroadcast( 6079): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6079): MCCMNC not supported: null
D/QRemote ( 6245): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6245): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6245): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6245): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6245): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1033): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 02 Feb 2016 17:27:08 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454434028681], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454434028664]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1033): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1033): Validated
D/ConnectivityService( 1033): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1033): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1033):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1033):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1033):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1033): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService( 1033): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1033):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService( 1033):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1033): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1033): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1463): CM callback handler got msg 524290
D/ConnectivityService( 1033): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    ( 1033): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1033):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1840): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1840):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/TelephonyIcons( 1463): null signal icon name: drawable/stat_sys_signal_null
,D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
D/LocSvc_java( 1033): NTP server : europe.pool.ntp.org
,D/LocSvc_java( 1033): NTP server returned: 1454434028316 (Tue Feb 02 18:27:08 GMT+01:00 2016) reference: 117012 certainty: 33 system time offset: -412
D/LocSvc_java( 1033): Sending msg: 10 arg1:0 arg2:1
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 117832317197; DSPS: 4002480; Offset : -4328167358
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2991] from screen [on:0 period:-1559883792] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:-1559883792] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WifiInternetCheck( 1033): Single check msg out of sync, ignoring.
,D/ConnectivityService( 1033): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1033): MasterInitialState.processMessage what=3
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  314): res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
,D/PostponalbeReceiver( 5145): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 5145): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/NetworkMonitor( 5195): type=WIFI subType= reason=null isConnected=true
,D/libc-netbsd(  314): res_queryN name = 2.android.pool.ntp.org succeed
,D/AlarmManagerService( 1033): Setting time of day to sec=1454434031
,W/AlarmManagerService( 1033): Unable to set rtc to 1454434031: Invalid argument
I/ActivityManager( 1033): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=6456 uid=10054 gids={50054, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     ( 1033): Explicit concurrent mark sweep GC freed 82204(3MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 44MB/66MB, paused 1.477ms total 110.439ms
,I/ActivityManager( 1033): Start proc com.android.gallery3d for service com.android.gallery3d/com.lge.gallery.picasa.PicasaService: pid=6473 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/ActivityManager( 1033): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6490 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/CalendarProvider2( 4536): onReceive() android.intent.action.TIME_SET
D/CalendarProvider2( 4536): Scheduling check of next Alarm
D/LIA_Informant_Tips_DateChangeManager( 2723): onReceive() : ACTION_TIME_CHANGED
I/LIA_Informant_Tips_LogTracer( 2723): [Log Tracer - Schedule Transition] Time Change Event Received : 2016-02-02 18:27:11...... Request
I/LIA_Informant_Tips_LogTracer( 2723): [Log Tracer - Schedule Transition] UserGuide, DATE_UPDATE : working count : 6, total count : 163, new day : false...... Request
D/LIA_Informant_Tips_DateChangeManager( 2723): DateInfo : SmartTips Total Working Day Count = 163
D/LIA_Informant_Tips_DateChangeManager( 2723): DateInfo : UserGuide Working Duration Count = 6
D/LIA_Informant_Tips_DateChangeManager( 2723): DateInfo : Last Date Check Time = 2016-02-02 18:27:11
D/KeyguardUpdateMonitor( 1463): handleTimeUpdate
I/[SystemUI]Clock( 1463): onReceive = android.intent.action.TIME_SET
I/SecureClockService( 1930): Intent.ACTION_TIME_CHANGED 
,I/LgeClockWidgetControlView( 1463): time changed, timezoneChanged : false
W/ActivityManager( 1033): getTasks: caller 10029 is using old GET_TASKS but privileged; allowing
I/[LGHome]LGDateChangeReceiver( 2020): [LGDateChangeReceiver.java:78:updateCalendarShortcut()]date=2 currentDate=-1 dayofweek=3 currentDayOfWeek=-1
,I/[LGHome]LGCalendarIcon( 2020): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Tue date= 2
W/ResourcesManager( 6473): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6473): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6473): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 6473): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/[LGHome]LGCalendarIcon( 2020): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Tue date= 2
I/[LGHome]Launcher( 2020): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,D/[Concierge]Service( 2612): onStartCommand(). Type : 9
I/AppUp4:AppBoxCP( 6490): onCreate
W/AppUp4:DB( 6490):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 6490):  setFingerPrint start
I/AppUp4:DB( 6490):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 6490):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 6490):  SDK version = 21
I/AppUp4:DB( 6490):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6490): AppBoxApplication onCreate()
,I/NetworkStateForAutoUpdateMonitor( 6490): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6490): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6490): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6490): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6490): onReceive
I/AppConfig( 6473): Total System Memory = 2995761152
,D/SystemHelper( 6473): region [EU], country [EU], operator [OPEN], sub-operator []
I/jxcore-log( 5968): Test app app.js loaded
I/jxcore-log( 5968): 
,I/chromium( 5968): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5968): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5968): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5968): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5968): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5968): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5968): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5968): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5968): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5968): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5968): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@118ddfc6 added. We now have 1 listener(s)
I/jxcore-log( 5968): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 5968): 
I/ReaderUtils( 6456): PortraitW 1440 LandscapeW 2392 SmallestSize 1340 LargestSize 2392 textZoom 4.4999995 isTablet false Memory 256
D/LgDataFeature( 6490): LgDataFeature() Constructor: none
D/LgDataFeature( 6490): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 6490): Context : android.app.ReceiverRestrictedContext@7a289ab
D/AppUp4:CustFacade( 6490): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6490): isPhone : true
D/AppUp4:CustModeStarterReceiver( 6490): begin check event
I/AppUp4:CustModeStarterReceiver( 6490): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6490): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6490): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6490): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6490): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1033): Killing 5528:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
I/ThermalEngine(  330): Thermal-Server: Thermal received msg from  override
,I/Thermal-Lib( 3069): Thermal-Lib-Client: Client request sent
,I/art     ( 2133): Explicit concurrent mark sweep GC freed 16845(957KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 30MB/62MB, paused 624us total 20.940ms
,W/libprocessgroup( 1033): failed to open /acct/uid_10080/pid_5528/cgroup.procs: No such file or directory
D/LGDMClient( 3164): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3164): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 3164): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
I/ActivityManager( 1033): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=6519 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/GpsLocationProvider( 1033): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 3164): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,D/GpsLocationProvider( 1033): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
V/DownloadManager( 3319): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3319): DownloadService onCreate
I/DownloadManager( 3319): in removeSpuriousFiles
V/DownloadManager( 3319): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3319): created cursor android.database.sqlite.SQLiteCursor@29c54e81 on behalf of 3319
I/DownloadManager( 3319): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3319): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3319): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3319): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3319): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3319): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3319): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3319): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3319): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3319): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3319): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/DownloadManager( 3319): in trimDatabase
V/DownloadManager( 3319): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,D/LGDMClient( 3164): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3164): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,V/DownloadManager( 3319): created cursor android.database.sqlite.SQLiteCursor@1fb3eb26 on behalf of 3319
D/LGDMClient( 3164): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/LGDMClient( 3164): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager( 1033): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6546 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,V/DownloadManager( 3319): DownloadService onStartCommand
V/DownloadManager( 3319): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
E/GpsLocationProvider( 1033): No APN found to select.
I/art     (  344): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 194us total 9.233ms
V/DownloadManager( 3319): created cursor android.database.sqlite.SQLiteCursor@37751bd on behalf of 3319
W/DriveInitializer( 2390): Background init thread started
W/ContextImpl( 3164): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
,I/art     (  344): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 184us total 9.063ms
V/DownloadManager( 3319): processing inserted download 1
V/DownloadManager( 3319): processing inserted download 4
V/DownloadManager( 3319): processing inserted download 7
V/DownloadManager( 3319): processing inserted download 8
I/art     (  344): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 192us total 8.847ms
V/DownloadManager( 3319): processing inserted download 9
W/GAV2    ( 6456): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.gms/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 2390): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.gms/files
V/DownloadManager( 3319): processing inserted download 10
E/LGDMClient( 3164): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
V/DownloadManager( 3319): processing inserted download 16
V/DownloadManager( 3319): processing inserted download 17
D/LGDMClient( 3164): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 3164): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3319): processing inserted download 18
V/DownloadManager( 3319): processing inserted download 21
I/ActivityManager( 1033): Killing 5547:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,V/DownloadManager( 3319): processing inserted download 22
W/ResourcesManager( 6546): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6546): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6546): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6546): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/libprocessgroup( 1033): failed to open /acct/uid_10097/pid_5547/cgroup.procs: No such file or directory
,V/DownloadManager( 3319): DownloadService onDestroy
I/BooksApp( 6456): Created application version: 3.2.35 (30235)
I/LGEmail ( 6546): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 6546): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,W/DriveInitializer( 2390): Background init thread ended
W/ResourceType( 6546): No package identifier when getting value for resource number 0x00000000
,E/Auth.Api.Credentials( 2390): [CredentialSyncAdapter] Unknown sync event.
,D/LgDataFeature( 6546): LgDataFeature() Constructor: none
D/LgDataFeature( 6546): LgDataFeature() Constructor Done, null
I/BooksSync( 6456): Starting books sync
,D/DelayedSyncController( 6519): Delaying sync.
,I/ActivityManager( 1033): Killing 5881:com.lge.eula/1000 (adj 15): empty #17
W/libprocessgroup( 1033): failed to open /acct/uid_1000/pid_5881/cgroup.procs: No such file or directory
,D/eas_req ( 6546): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,D/BooksSync( 6456): started syncMyEbooks
I/HubEmail( 6546): JNI_OnLoad()
I/HubEmail( 6546): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6546): registerNatives()
I/HubEmail( 6546): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6546): registerNativeMethods()
I/HubEmail( 6546): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/LgeMiscReceiver( 3284): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3284): action = android.net.conn.CONNECTIVITY_CHANGE
W/art     ( 6546): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/LgeMiscReceiver( 3284): networkInfo.isConnected() = true
D/PhoneState( 3284): setPdpRejectCasuse : false
,D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  314): res_queryN name = static-avc.lglime.com, class = 1, type = 1
,I/ActivityManager( 1033): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6602 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
W/Settings( 6546): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 6546): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DrmBroadcastReceiver( 6602): Receive CONNECTIVITY_ACTION
,D/DrmBroadcastReceiver( 6602): 1  network is available. Sync DRM Time with NTP
,I/GLSUser ( 2133): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2133): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2133): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2133): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/DrmService( 6602): Service onCreate
D/DrmService( 6602): Received new request = 2
I/DrmSntpClient( 6602): Start Sync process
D/DrmSntpClient( 6602): Server : 0
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  314): res_queryN name = pool.ntp.org, class = 1, type = 1
,D/libc-netbsd(  314): res_queryN name = static-avc.lglime.com succeed
,I/ActivityManager( 1033): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=6623 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1033): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,D/ZenLog  ( 1033): intercepted: 0|com.google.android.gms|1|null|10005,none
V/NotificationService( 1033): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1033): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1033): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1033): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2133): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2133): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2133): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2133): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2133): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2133): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2133): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6456): Authentication error
E/BooksAccountManager( 6456): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6456): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6456): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6456): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6456): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6456): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6456): null auth token
I/art     ( 6623): Almond Protected OAT
W/ResourcesManager( 1411): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1463): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1411): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager( 1463): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/FormManager( 6125): There are no updated forms. The schedule will be deleted.
D/LgeQuickCoverNLService( 1411): onNotificationPosted
V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
D/LgeQuickCoverOverlayWindow( 1411): [native noti], inex =  1
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
,V/FormManager( 6125): Alarm would be updated, because LastCheckTime has been updated.
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1411): updateNotificationData: count=3
D/libc-netbsd(  314): res_queryN name = pool.ntp.org succeed
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  314): res_queryN name = www.googleapis.com, class = 1, type = 1
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{3ab4fef3 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,I/GLSUser ( 2133): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 2133): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2133): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2133): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager( 1033): Killing 5348:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
,I/LGDrmClient( 6602): _DRM_ServiceGet() : Bind lgdrm service
,V/ILGDrmService(  326): eDRM_SetDRMTime +++
I/LGDRM   (  326): [DRM] SET TIME : YR=2016, MON=2, DAY=2
I/LGDRM   (  326): [DRM] SET TIME : HR=17, MIN=27, SEC=12
V/ILGDrmService(  326): eDRM_SetDRMTime ---
I/DrmSntpClient( 6602): Synched
D/DrmService( 6602): Completed !! request = 2
D/DrmService( 6602): Request count = 0
D/libc-netbsd(  314): res_queryN name = www.googleapis.com succeed
I/art     ( 1033): Explicit concurrent mark sweep GC freed 23876(1085KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 44MB/66MB, paused 1ms total 65.897ms
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=5.5, 0.0, 0.0  rx=4.5 bcn=0 [on:0 tx:0 rx:0 period:2571] from screen [on:0 period:-1559881214] gl rssi=-57 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=5.5, 0.0, 0.0  rx=4.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1559881213] gl rssi=-57 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
W/libprocessgroup( 1033): failed to open /acct/uid_10005/pid_5348/cgroup.procs: No such file or directory
,V/DrmService( 6602): Service onDestroy
D/WeatherApplication( 6623): removeAccount
D/WeatherApplication( 6623): Account.length = 0
I/ActivityManager( 1033): Killing 4536:com.android.providers.calendar/u0a14 (adj 15): empty #17
E/WeatherApplication( 6623): OPERATOR:OPEN
D/WeatherAncestor( 6623): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:27:12
D/Weather.Utils( 6623): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6623): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6623): 2 : This is isUpdating : false
D/WeatherAncestor( 6623): connectivity changed - connection : true
,D/WeatherService( 6623): 2 : isServiceAlived():false forecastCache:null
D/ForecastDataCache( 6623): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 6623): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 6623): 2 : Cache is not up-to-date, count: 0
D/Weather_cast( 6623): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 6623): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:27:12
,I/ActivityManager( 1033): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6643 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1033): Killing 2115:com.lge.music/u0a34 (adj 15): empty #17
,V/AudioFlinger(  318): 2115 died, releasing its sessions
V/AudioFlinger(  318):  pid 1840 @ 0
V/AudioFlinger(  318):  pid 3284 @ 1
V/AudioFlinger(  318):  pid 3284 @ 2
W/libprocessgroup( 1033): failed to open /acct/uid_10014/pid_4536/cgroup.procs: No such file or directory
,W/libprocessgroup( 1033): failed to open /acct/uid_10034/pid_2115/cgroup.procs: No such file or directory
D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
,V/NotificationService( 1033): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1033): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1033): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1033): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1033): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2133): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2133): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2133): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2133): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2133): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2133): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2133): 	at android.os.Binder.execTransact(Binder.java:446)
,D/ContactsSyncAdapter( 2133): innerSync failed
D/ContactsSyncAdapter( 2133): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2133): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2133): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2133): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2133): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2133): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2133): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2133): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2133): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2133): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2133): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2133): 	at android.os.Binder.execTransact(Binder.java:446)
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
D/SyncManager( 1033): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 26480, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager( 1033): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 153455, reason: 10019
,D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{3ab4fef3 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  314): res_queryN name = www.google.com, class = 1, type = 1
,E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6643): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6643): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/ApiaryClient( 6456): Error response from books API: {
W/ApiaryClient( 6456):  "error": {
W/ApiaryClient( 6456):   "errors": [
W/ApiaryClient( 6456):    {
W/ApiaryClient( 6456):     "domain": "global",
W/ApiaryClient( 6456):     "reason": "required",
W/ApiaryClient( 6456):     "message": "Login Required",
W/ApiaryClient( 6456):     "locationType": "header",
W/ApiaryClient( 6456):     "location": "Authorization"
W/ApiaryClient( 6456):    }
W/ApiaryClient( 6456):   ],
W/ApiaryClient( 6456):   "code": 401,
W/ApiaryClient( 6456):   "message": "Login Required"
W/ApiaryClient( 6456):  }
W/ApiaryClient( 6456): }
W/ApiaryClient( 6456): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6456): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4861594032098975377&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6456): Headers:
W/ApiaryClient( 6456): accept-encoding: [gzip]
W/ApiaryClient( 6456): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6456): gdata-version: 2
E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6643): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6643): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
D/DelayedSyncController( 6519): Delaying sync.
,D/libc-netbsd(  314): res_queryN name = www.google.com succeed
,D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  314): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  314): res_queryN name = clients3.google.com succeed
V/WifiInternetCheck( 1033): isHttpConnectionAvailable - We got a valid response : 204
,I/ActivityManager( 1033): Start proc com.google.android.apps.plus for service com.google.android.apps.plus/.service.EsSyncAdapterService: pid=6686 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/WebViewFactory( 6643): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 6643): Loading: webviewchromium
I/LibraryLoader( 6643): Time to load native libraries: 3 ms (timestamps 1142-1145)
I/LibraryLoader( 6643): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6643): Binding Chromium to main looper Looper (main, tid 1) {2b31a602}
I/LibraryLoader( 6643): Expected native library version number "",actual native library version number ""
I/chromium( 6643): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6643): Initializing chromium process, renderers=0
W/ResourcesManager( 6686): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/art     ( 6643): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6643): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 6643): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
V/AudioPolicyService(  318): registerClient() client 0xb1427340, uid 10093
,I/chromium( 6643): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
W/AudioManagerAndroid( 6643): Requires BLUETOOTH permission
I/Adreno-EGL( 6643): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6643): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6643): Build Date: 12/12/14 금
I/Adreno-EGL( 6643): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6643): Remote Branch: 
I/Adreno-EGL( 6643): Local Patches: 
I/Adreno-EGL( 6643): Reconstruct Branch: 
I/NSApplication( 6643): Starting up...
,I/ActivityManager( 1033): Killing 4855:com.android.vending/u0a44 (adj 15): empty #17
W/libprocessgroup( 1033): failed to open /acct/uid_10044/pid_4855/cgroup.procs: No such file or directory
,I/GLSActivity( 2133): [ac] getting account id
,I/GLSUser ( 2133): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  314): res_queryN name = mtalk.google.com, class = 1, type = 1
,I/iu.SyncManager( 2390): SYNC; picasa accounts
,D/NetworkLogImpl( 2390): Loaded NetworkSpeedPredictor
I/iu.Environment( 2390): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 2390): num queued entries: 0
I/iu.UploadsManager( 2390): num updated entries: 0
I/iu.SyncManager( 2390): NEXT; no task
D/libc-netbsd(  314): res_queryN name = mtalk.google.com succeed
D/ChimeraCfgMgr( 2390): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 2390): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/PostponalbeReceiver( 5145): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.TIME_SET'.
,I/ActivityManager( 1033): Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=6743 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/GLSUser ( 2133): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 2133): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2133): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2133): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1033): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1033): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1033): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1033): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1033): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
D/ALBootInit( 6743): ====action==>android.intent.action.TIME_SET
E/LgeQuickCoverOverlayWindow( 1411): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  1
W/Kids    ( 2390): [AccountUtils] Account not ready
W/Kids    ( 2390): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2390): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2390): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2390): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2390): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2390): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2390): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2390): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2390): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2390): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2390): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2390): 	at java.lang.Thread.run(Thread.java:818)
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1411): updateNotificationData: count=3
D/ALBootInit( 6743): Alarm ALBootInit: TIME_SET
D/Alarms  ( 6743): [setNextAlert] start
D/Alarms  ( 6743): [setNextAlert] (1)
,D/Alarms  ( 6743):  minTime  = 0
D/Alarms  ( 6743):  -- OK multi -- 0
E/jeny.kim( 6743): [setNextAlert] setNextAlert  temp_Alarmlink + 
E/jeny.kim( 6743): [setNextAlert]setNextAlert temp_AlarmLinkText + 
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{3ab4fef3 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/CommonUtil( 6743): BUILD Country: EU
,D/Alarms  ( 6743): broadcastToWidgetProvider : false
D/Alarms  ( 6743): Enter formatDayAndTime(final Context context, long timeInMiliSec)
V/SettingsProvider( 1033): call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
I/DigitalAppWidgetProvider( 6743): onReceive: android.intent.action.TIME_SET
V/DigitalAppWidgetProvider( 6743): cancelAlarmOnQuarterHour android.app.ReceiverRestrictedContext@2b68e808
,V/DigitalAppWidgetProvider( 6743): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@2b68e808
D/QuickCoverProvider( 6743): onReceiver
I/indal   ( 1411): SmartCoverWidgetContext createApplicationContext
I/indal   ( 1411): SmartCoverWidgetContext createApplicationContext
D/WeatherAncestor( 6623): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 18:27:12
,D/Weather.Utils( 6623): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6623): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6623): 2 : This is isUpdating : false
D/WeatherService( 6623): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@308d6ba1
D/ForecastDataCache( 6623): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 6623): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 6623): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 6623): 2 : set auto-update time : 2/2 21:27
D/WeatherAncestor( 6623): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 18:27:12
I/ActivityManager( 1033): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=6767 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/ActivityManager( 1033): Killing 5905:com.lge.bnr/1000 (adj 15): empty #17
W/libprocessgroup( 1033): failed to open /acct/uid_1000/pid_5905/cgroup.procs: No such file or directory
,D/GCM     ( 2133): Connected
,D/GCM     ( 2133): Message class com.google.f.a.a.p
,D/TimeService( 6767): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1454434032889
D/        ( 6767): TimeServiceNative: User Time to be set is 1454434032889
D/QC-time-services( 6767): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 6767): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 6767): Lib:time_genoff_operation: pargs->ts_val = 1454434032889
,D/QC-time-services(  414): Daemon: Connection accepted:time_genoff
D/QC-time-services( 6767): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  414): Daemon:Received base = 2, unit = 1, operation = 0,value = 1454434032889
D/QC-time-services(  414): Daemon:genoff_opr: Base = 2, val = 1454434032889, operation = 0
D/QC-time-services(  414): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS5/12/70 10:39:20
D/QC-time-services(  414): Daemon:Value read from RTC seconds = 14035160000
D/QC-time-services(  414): Daemon:new time 1454434032889 
D/QC-time-services(  414): Daemon: delta 1440398872889 genoff 1440398872889 
D/QC-time-services(  414): Daemon:genoff_persistent_update: Writing genoff = 1440398872889 to memory
D/QC-time-services(  414): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  414): Daemon:time_persistent_memory_opr:Genoff write operation 
D/QC-time-services(  414): Updating the TOD offset
D/QC-time-services(  414): Daemon:genoff_persistent_update: Writing genoff = 1440398872889 to memory
D/QC-time-services(  414): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  414): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services(  414): Daemon:Update to modem bit set
D/QC-time-services(  414): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  414): Daemon: Base = 2, Value being sent to MODEM = 1124434072889
E/QC-time-services( 6767): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
E/QC-time-services(  414): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
E/QC-time-services(  414): Daemon: Time-services: Waiting to acceptconnection
I/ActivityManager( 1033): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetProvider: pid=6785 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi
,I/ActivityManager( 1033): Killing 6150:com.lge.lifetracker/u0a37 (adj 15): empty #17
W/libprocessgroup( 1033): failed to open /acct/uid_10037/pid_6150/cgroup.procs: No such file or directory
,W/ResourcesManager( 6785): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/CalendarApplication( 6785): CalendarApplication.onCreate()
,D/PreferenceKeysParser( 6785): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 6785): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@28ab438f, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@f1b861c, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@273cd225, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@2a8aeffa, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@7a289ab, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@2b68e808, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@308d6ba1, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@228811c6, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@2e7e1587, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@23a87cb4, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@2bf420dd, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@20e38452, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@3c9c8323, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@eaab020, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@1916edd9, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@3a11939e, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@1eaa2e7f, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@1ddaae4c, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@31ff8e95, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@37f4baa, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@35bd339b, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@c2a6338, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@d977f11, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@a5e7876, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@14316e77, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@fbe7ae4, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@2de3fb4d, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@2b31a602, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@2c447b13, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@3a5a6150, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@3601ff49, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@1618204e, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@c71b56f, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@348c427c, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@3e24705, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@bd9f35a, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@58e398b, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@3f990a68, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@29c54e81, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@1fb3eb26, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@16a4e367, lg_preferences_recent_,timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@2a286514, 
D/GeneralPreferenceUtils( 6785): [migratePrefrenceKeys] Exit: Version(44001600) >= 42001300
D/Config  ( 6785): [init]
,I/Config  ( 6785): LGCalendar ver.4.40.16
I/Config  ( 6785): start check model
I/Config  ( 6785): start check native_ca
I/Config  ( 6785): Config Operator=OPEN, Country=EU
D/Config  ( 6785): [setDefaultValuesToPref]
D/Config  ( 6785): [parseProfiles]
D/ProfilesParser( 6785): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6785): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6785): [updateProfiletoCountryInfo]
D/GeneralPreference( 6785): [checkAndMigrateOldPreference]
E/AgendaWidgetManager( 6785): [updateWidgets] 
I/InitNotificationRingtoneService( 6785): Start InitializeAlertRingtoneService.onHandleIntent
,I/AlertUtils( 6785): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/41
I/AlertUtils( 6785): [getCalendarNotiSoundURIFromCursor] getCount()= 21
I/AlertUtils( 6785): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arpeggio.ogg
,I/AlertUtils( 6785): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 6785): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 6785): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 6785): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 6785): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
,I/AlertUtils( 6785): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 6785): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 6785): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 6785): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Afternoon_Walk.ogg
I/AlertUtils( 6785): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
,I/AlertUtils( 6785): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 6785): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 6785): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
W/HolidayIntentService( 6785): onHandleIntent
,D/MonthWidgetProvider( 6785): [onReceive]
D/CalendarWidgetProvider( 6785): [onReceive]
D/CalendarWidgetProvider( 6785): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/HolidayDataLoader( 6785): readJsonAsset : holiday.json
D/CalendarTypeController( 6785): [onUpdateAndInitCalendarTime]
,I/art     ( 1033): Explicit concurrent mark sweep GC freed 23192(1048KB) AllocSpace objects, 3(304KB) LOS objects, 33% free, 44MB/66MB, paused 1.432ms total 88.799ms
D/WeekWidgetProvider( 6785): [onReceive]
D/CalendarWidgetProvider( 6785): [onReceive]
D/CalendarWidgetProvider( 6785): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.WeekWidgetProvider }
,D/CalendarTypeController( 6785): [onUpdateAndInitCalendarTime]
I/AlertUtils( 6785): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6785): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/41
I/AlertUtils( 6785): set default noti to content://media/internal/audio/media/41
I/InitNotificationRingtoneService( 6785): End InitializeAlertRingtoneService.onHandleIntent
,E/HolidayIntentService( 6785): onHandleIntent:holiday data empty
I/ActivityManager( 1033): Killing 6220:com.lge.settings.easy/1000 (adj 15): empty #17
W/libprocessgroup( 1033): failed to open /acct/uid_1000/pid_6220/cgroup.procs: No such file or directory
,I/DigitalAppWidgetProvider( 6743): onReceive: android.intent.action.ALARM_CHANGED
,D/WeatherAncestor( 6623): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 18:27:13
D/Weather.Utils( 6623): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6623): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6623): 2 : This is isUpdating : false
D/Weather_cast( 6623): 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
D/WeatherAncestor( 6623): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 18:27:13
I/ActivityManager( 1033): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RequestWriter$NetworkStateReceiver: pid=6812 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2133): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2133): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2133): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2133): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 6812): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/art     ( 2133): Explicit concurrent mark sweep GC freed 17738(1009KB) AllocSpace objects, 11(1328KB) LOS objects, 51% free, 30MB/62MB, paused 1.171ms total 60.602ms
,V/NotificationService( 1033): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1033): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1033): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1033): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1033): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2133): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2133): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2133): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2133): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2133): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2133): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2133): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1411): onNotificationPosted
D/SmartCoverUpdateMonitor( 1411): received broadcast com.lge.intent.action.NLDataPosted
,E/SmartCoverUpdateMonitor( 1411): MSG_NOTIFICATION_POSTED
,D/SmartCoverUpdateMonitor( 1411): handleNotificationPosted(true)
D/QuickCircle( 1411): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1411): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1411): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1411): post do just update job
D/LgeQuickCoverNotificationData( 1411): showAll3
E/BooksAccountManager( 6456): Authentication error
E/BooksAccountManager( 6456): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6456): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6456): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6456): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6456): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6456): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNotificationData( 1411): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/HttpHelper( 6456): null auth token
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
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{3ab4fef3 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/LgDataFeature( 6812): LgDataFeature() Constructor: none
W/ApiaryClient( 6456): Error response from books API: {
W/ApiaryClient( 6456):  "error": {
W/ApiaryClient( 6456):   "errors": [
W/ApiaryClient( 6456):    {
W/ApiaryClient( 6456):     "domain": "global",
W/ApiaryClient( 6456):     "reason": "required",
W/ApiaryClient( 6456):     "message": "Login Required",
W/ApiaryClient( 6456):     "locationType": "header",
W/ApiaryClient( 6456):     "location": "Authorization"
W/ApiaryClient( 6456):    }
W/ApiaryClient( 6456):   ],
W/ApiaryClient( 6456):   "code": 401,
W/ApiaryClient( 6456):   "message": "Login Required"
W/ApiaryClient( 6456):  }
W/ApiaryClient( 6456): }
D/LgDataFeature( 6812): LgDataFeature() Constructor Done, null
,W/ApiaryClient( 6456): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6456): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4861594032098975377&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6456): Headers:
W/ApiaryClient( 6456): accept-encoding: [gzip]
W/ApiaryClient( 6456): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6456): gdata-version: 2
,I/Babel   ( 6812): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 6812): MmsConfig.loadMmsSettings
I/Babel   ( 6812): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
I/Babel   ( 6812): MmsConfig.loadFromDatabase
,E/Babel   ( 6812): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 6812): MmsConfig.loadFromResources
E/Babel   ( 6812): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 6812): MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
W/Settings( 6812): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/AudioCapabilities( 6812): Unsupported mime audio/evrc
W/AudioCapabilities( 6812): Unsupported mime audio/qcelp
W/VideoCapabilities( 6812): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6812): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6812): Unsupported mime audio/qcelp
W/AudioCapabilities( 6812): Unsupported mime audio/evrc
,W/VideoCapabilities( 6812): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 6812): Unsupported mime video/divx
W/VideoCapabilities( 6812): Unsupported mime video/divx311
,W/VideoCapabilities( 6812): Unsupported mime video/divx4
W/ResourcesManager( 6812): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6812): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/VideoCapabilities( 6812): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6812): Unsupported profile 4 for video/mp4v-es
W/AudioCapabilities( 6812): Unsupported mime audio/eac3
W/AudioCapabilities( 6812): Unsupported mime audio/ac3
W/AudioCapabilities( 6812): Unsupported mime audio/g726
,W/AudioCapabilities( 6812): Unsupported mime audio/wma-voice
W/AudioCapabilities( 6812): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6812): Unsupported mime audio/adpcm
W/VideoCapabilities( 6812): Unsupported mime video/theora
W/VideoCapabilities( 6812): Unsupported mime video/mjpg
V/JNIHelp ( 6812): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/System  ( 6812): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/system/app/Hangouts/Hangouts.apk"],nativeLibraryDirectories=[/system/app/Hangouts/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6812): Installed default security provider GmsCore_OpenSSL
I/GLSUser ( 2133): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native
I/GLSUser ( 2133): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2133): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2133): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/Babel   ( 6812): UserRecoverableAuthException.
,E/Babel   ( 6812): cfq: BadAuthentication
E/Babel   ( 6812): 	at cfn.a(Unknown Source)
E/Babel   ( 6812): 	at f.a(PG:191)
E/Babel   ( 6812): 	at ava.a(PG:88)
E/Babel   ( 6812): 	at ava.a(PG:128)
E/Babel   ( 6812): 	at bjs.a(PG:255)
E/Babel   ( 6812): 	at bep.a(PG:602)
E/Babel   ( 6812): 	at bep.a(PG:469)
E/Babel   ( 6812): 	at bpo.run(PG:1141)
,E/Babel   ( 6812): Error getting auth token
E/Babel   ( 6812): bxl
E/Babel   ( 6812): 	at f.a(PG:201)
E/Babel   ( 6812): 	at ava.a(PG:88)
E/Babel   ( 6812): 	at ava.a(PG:128)
E/Babel   ( 6812): 	at bjs.a(PG:255)
E/Babel   ( 6812): 	at bep.a(PG:602)
E/Babel   ( 6812): 	at bep.a(PG:469)
E/Babel   ( 6812): 	at bpo.run(PG:1141)
I/Babel_RequestWriter( 6812): error sending REQ[fc:8; creat:1454431018816; type:bev-134363649]; took 117 ms (error code == 100)
E/Babel   ( 6812): Account registration failedRedacted-21
E/Babel   ( 6812): bph: null -- null
E/Babel   ( 6812): 	at ava.a(PG:120)
E/Babel   ( 6812): 	at ava.a(PG:128)
E/Babel   ( 6812): 	at bjs.a(PG:255)
E/Babel   ( 6812): 	at bep.a(PG:602)
E/Babel   ( 6812): 	at bep.a(PG:469)
E/Babel   ( 6812): 	at bpo.run(PG:1141)
I/Babel   ( 6812): Account setup failed with error state:106 account:Redacted-21
I/Babel   ( 6812): Account sign in complete with state 106account: Redacted-21
I/art     ( 6812): Note: end time exceeds epoch: 
,I/GLSUser ( 2133): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native
I/GLSUser ( 2133): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2133): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2133): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 2133): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,V/NotificationService( 1033): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1033): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1033): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1033): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1033): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
E/Babel   ( 6812): Unexpected exception while authenticating.
E/Babel   ( 6812): cfr: User intervention required. Notification has been pushed.
E/Babel   ( 6812): 	at cfn.b(Unknown Source)
E/Babel   ( 6812): 	at cfn.a(Unknown Source)
E/Babel   ( 6812): 	at f.a(PG:188)
E/Babel   ( 6812): 	at ava.b(PG:143)
E/Babel   ( 6812): 	at bnr.run(PG:5415)
E/Babel   ( 6812): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 6812): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 6812): 	at java.lang.Thread.run(Thread.java:818)
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
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{3ab4fef3 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2133): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2133): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2133): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2133): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1033): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1033): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1033): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1033): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1033): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
,W/GLSActivity( 2133): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2133): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2133): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2133): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2133): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2133): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2133): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6456): Authentication error
E/BooksAccountManager( 6456): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6456): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6456): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6456): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6456): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6456): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6456): null auth token
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{3ab4fef3 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6456): Error response from books API: {
W/ApiaryClient( 6456):  "error": {
W/ApiaryClient( 6456):   "errors": [
W/ApiaryClient( 6456):    {
W/ApiaryClient( 6456):     "domain": "global",
W/ApiaryClient( 6456):     "reason": "required",
W/ApiaryClient( 6456):     "message": "Login Required",
W/ApiaryClient( 6456):     "locationType": "header",
W/ApiaryClient( 6456):     "location": "Authorization"
W/ApiaryClient( 6456):    }
W/ApiaryClient( 6456):   ],
W/ApiaryClient( 6456):   "code": 401,
W/ApiaryClient( 6456):   "message": "Login Required"
W/ApiaryClient( 6456):  }
W/ApiaryClient( 6456): }
,W/ApiaryClient( 6456): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6456): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4861594032098975377&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6456): Headers:
W/ApiaryClient( 6456): accept-encoding: [gzip]
W/ApiaryClient( 6456): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6456): gdata-version: 2
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-53 f=2412 sc=60 link=72 tx=10.8, 0.0, 0.0  rx=8.2 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1559878196] gl rssi=-53 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,I/ThermalEngine(  330): Thermal-Server: Thermal received msg from  override
I/Thermal-Lib( 3069): Thermal-Lib-Client: Client request sent
E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-53 f=2412 sc=60 link=72 tx=10.8, 0.0, 0.0  rx=8.2 bcn=0 [on:0 tx:0 rx:0 period:23] from screen [on:0 period:-1559878173] gl rssi=-53 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
,E/BooksSync( 6456): Soft error: 
E/BooksSync( 6456): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6456): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4861594032098975377&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6456): Headers:
E/BooksSync( 6456): accept-encoding: [gzip]
E/BooksSync( 6456): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6456): gdata-version: 2
E/BooksSync( 6456): 
E/BooksSync( 6456): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6456): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6456): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6456): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6456): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6456): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6456): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6456): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6456): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6456): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6456): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6456): {
E/BooksSync( 6456):  "error": {
E/BooksSync( 6456):   "errors": [
E/BooksSync( 6456):    {
E/BooksSync( 6456):     "domain": "global",
E/BooksSync( 6456):     "reason": "required",
E/BooksSync( 6456):     "message": "Login Required",
E/BooksSync( 6456):     "locationType": "header",
E/BooksSync( 6456):     "location": "Authorization"
E/BooksSync( 6456):    }
E/BooksSync( 6456):   ],
E/BooksSync( 6456):   "code": 401,
E/BooksSync( 6456):   "message": "Login Required"
E/BooksSync( 6456):  }
E/BooksSync( 6456): }
E/BooksSync( 6456): 
E/BooksSync( 6456): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6456): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6456): 	... 8 more
,E/BooksSync( 6456): Sync error
E/BooksSync( 6456): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6456): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4861594032098975377&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6456): Headers:
E/BooksSync( 6456): accept-encoding: [gzip]
E/BooksSync( 6456): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6456): gdata-version: 2
E/BooksSync( 6456): 
E/BooksSync( 6456): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6456): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6456): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6456): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6456): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6456): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6456): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6456): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6456): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6456): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6456): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6456): {
E/BooksSync( 6456):  "error": {
E/BooksSync( 6456):   "errors": [
E/BooksSync( 6456):    {
E/BooksSync( 6456):     "domain": "global",
E/BooksSync( 6456):     "reason": "required",
E/BooksSync( 6456):     "message": "Login Required",
E/BooksSync( 6456):     "locationType": "header",
E/BooksSync( 6456):     "location": "Authorization"
E/BooksSync( 6456):    }
E/BooksSync( 6456):   ],
E/BooksSync( 6456):   "code": 401,
E/BooksSync( 6456):   "message": "Login Required"
E/BooksSync( 6456):  }
E/BooksSync( 6456): }
E/BooksSync( 6456): 
E/BooksSync( 6456): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6456): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6456): 	... 8 more
I/BooksSync( 6456): Finished books sync
I/ActivityManager( 1033): Killing 6178:com.lge.sync/1000 (adj 15): empty #17
,D/SyncManager( 1033): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 26442, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,W/libprocessgroup( 1033): failed to open /acct/uid_1000/pid_6178/cgroup.procs: No such file or directory
,V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2133): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 2133): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2133): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2133): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1033): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1033): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1033): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1033): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1033): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2133): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2133): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2133): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2133): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2133): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2133): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2133): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1411): onNotificationPosted
D/ContactsSyncAdapter( 2133): innerSync failed
D/ContactsSyncAdapter( 2133): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2133): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2133): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2133): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2133): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2133): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2133): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2133): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2133): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2133): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2133): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2133): 	at android.os.Binder.execTransact(Binder.java:446)
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
E/LgeQuickCoverOverlayWindow( 1411): updateNotificationData: count=3
D/SyncManager( 1033): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 153455, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{3ab4fef3 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,V/AlarmManager( 1033): ELAPSED_WAKEUP set : Alarm{36afa448 type 2 when 125052 com.android.providers.calendar} when 125052
,I/ActivityManager( 1033): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=6880 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi
,W/ResourcesManager( 6880): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarProvider2( 6880): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@18041869
,D/CalendarProvider2( 6880): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 6880): Created com.android.providers.calendar.CalendarAlarmManager@2a8aeffa(com.android.providers.calendar.CalendarProvider2@18041869)
D/CalendarProviderBroadcastReceiver( 6880): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 6880): [IntentService] WakeLock acquire, start IntentSerivce
D/CalendarProvider2( 6880): CalendarProviderIntentService.onCreate()
,D/CalendarProvider2( 6880): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
,D/CalendarProvider2( 6880): [getOrCreateCalendarAlarmManager]
E/SQLiteLog( 6880): (284) automatic index on view_events(_id)
I/GAV2    ( 6456): Thread[GAThread,5,main]: No campaign data found.
,D/CalendarProvider2( 6880): [IntentService] Release Lock
D/CalendarProvider2( 6880): CalendarProviderIntentService.onDestroy()
I/ActivityManager( 1033): Killing 5818:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
I/QRemote ( 6245): [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
,W/System.err( 6245): android.os.DeadObjectException
W/System.err( 6245): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6245): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6245): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 6245): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
W/System.err( 6245): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 6245): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 6245): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6245): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6245): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6245): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 6245): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6245): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6245): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 6245): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 6245): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 6245): android.os.DeadObjectException
W/System.err( 6245): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6245): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6245): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 6245): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
W/System.err( 6245): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 6245): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 6245): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6245): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6245): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6245): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 6245): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6245): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6245): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 6245): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 6245): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/QRemote ( 6245): [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
W/libprocessgroup( 1033): failed to open /acct/uid_1000/pid_5818/cgroup.procs: No such file or directory
,W/ActivityManager( 1033): Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,D/QRemote ( 6245): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
I/QRemote ( 6245): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
I/ActivityManager( 1033): Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6919 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/QRemote ( 6245): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,D/UEI.SmartControl( 6919): Quickset Services start...
,I/UEI.SmartControl( 6919): Manufacture = LGE
D/UEI.SmartControl( 6919): Id = LGNevo
D/UEI.SmartControl( 6919): File observer start...
E/UEI.SmartControl( 6919): IR Port is disabled: false
D/UEI.SmartControl( 6919): Starting file observer...
D/UEI.SmartControl( 6919): Extracting JNI libs...
D/UEI.SmartControl( 6919): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 6919): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 6919): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6919): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 6919): --- Selecting new region: 6
,I/UEI.SmartControl( 6919): Model = LG-D855
D/UEI.SmartControl( 6919): QS Service created
I/UEI.SmartControl( 6919): Service initServices...
,D/UEI.SmartControl( 6919): QS start get config
D/UEI.SmartControl( 6919): Loading JNI Libs...
,I/GAV4    ( 6643): Thread[GAThread,5,main]: No campaign data found.
,I/UEI.SmartControl( 6919): Supports setup maps: true
,D/UEI.SmartControl( 6919): QS start statue = true Error code = 0
,I/UEI.SmartControl( 6919): QS version = v2.7.10.1_RC1
,I/UEI.SmartControl( 6919): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6919): ### init IR Blaster...
,D/serial_port( 6919): Configuring serial port
E/UEI.SmartControl( 6919): UEIBLaster setting for 616
I/UEI.SmartControl( 6919): Setting serial record hearder size = 2
I/UEI.SmartControl( 6919): configuring settings for MAXQ616
I/UEI.SmartControl( 6919): Get version...
D/UEI.SmartControl( 6919): serial port data available: 21
,D/UEI.SmartControl( 6919): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 6919): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 6919): QS saving settings...
D/UEI.SmartControl( 6919): IR Blaster version: 25672567
,D/UEI.SmartControl( 6919): serial port data available: 4
,W/ContextImpl( 6919): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,E/UEI.SmartControl( 6919): Services init done
D/UEI.SmartControl( 6919): QS Service init finished
D/UEI.SmartControl( 6919): QS Service version name: 2.1.91
D/UEI.SmartControl( 6919): QS Service version code: 201091
,D/UEI.SmartControl( 6919): Service requested: Control
I/UEI.SmartControl( 6919): Device manager: loading config....
D/UEI.SmartControl( 6919): ----------- loading internal config...
E/UEI.SmartControl( 6919): Loading SETTINGS...
,D/UEI.SmartControl( 6919): Request IControl service: devices are loaded...
I/ActivityManager( 1033): Killing 6079:com.android.settings/1000 (adj 15): empty #17
D/UEI.SmartControl( 6919): -- Open brand translation xml: brands_translations_ko
I/QRemote ( 6245): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 6919): ------ IControl API: 11
I/UEI.SmartControl( 6919): Registering callback...
,I/UEI.SmartControl( 6919): ------ IControl API: 19
I/UEI.SmartControl( 6919): Registering Services Ready callback...
I/UEI.SmartControl( 6919): Notify client services are ready...
I/QRemote ( 6245): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 6245): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 6245): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 6245): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 6245): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6919): ------ IControl API: 8
D/QRemote ( 6245): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 6245): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 6245): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 6245): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
I/UEI.SmartControl( 6919): Notify AllClients services are ready: 0
I/QRemote ( 6245): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/UEI.SmartControl( 6919): -----service ready thread exits
D/QRemote ( 6245): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 6245): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 6245): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6245): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/WifiService( 1033): Client connection lost with reason: 4
,D/UEI.SmartControl( 6919): Internal service binding...
,D/QRemote ( 6245): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,W/libprocessgroup( 1033): failed to open /acct/uid_1000/pid_6079/cgroup.procs: No such file or directory
D/QRemote ( 6245): [RemoteControlManager.java:327:handleMessage()] oooooo 140510:retrieveDevices already complete. Do nothing
V/QRemote ( 6245): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,D/QRemote ( 6245): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 6245): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6245): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 6245): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,D/QRemote ( 6245): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 6245): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 6245): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1454434037604]
I/ActivityManager( 1033): Killing 6490:com.lge.appbox.client/u0a11 (adj 15): empty #17
D/QRemote ( 6245): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,W/libprocessgroup( 1033): failed to open /acct/uid_10011/pid_6490/cgroup.procs: No such file or directory
,V/QRemote ( 6245): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,E/QRemote ( 6245): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,D/QRemote ( 6245): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 6245): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
,D/QRemote ( 6245): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 6245): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 6245): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 6245): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=19.4, 0.0, 0.0  rx=17.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1559875139] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=19.4, 0.0, 0.0  rx=17.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559875136] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,I/ActivityManager( 1033): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=6956 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager( 1033): RTC_WAKEUP set : Alarm{3c1a3eb6 type 0 when 1454434039113 com.android.vending} when 1454434039113
,I/art     (  344): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 428us total 39.404ms
,I/ActivityManager( 1033): Killing 6125:com.lge.formmanager/u0a26 (adj 15): empty #17
,I/art     (  344): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 432us total 43.969ms
,I/art     (  344): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 425us total 21.133ms
,W/libprocessgroup( 1033): failed to open /acct/uid_10026/pid_6125/cgroup.procs: No such file or directory
,D/Finsky  ( 6956): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/LgDataFeature( 6956): LgDataFeature() Constructor: none
D/LgDataFeature( 6956): LgDataFeature() Constructor Done, null
,D/Finsky  ( 6956): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/ActivityManager( 1033): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=7014 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/Settings( 6956): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 6956): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ResourcesManager( 7014): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7014): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Finsky  ( 6956): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6956): [1] 2.run: Finished loading 1 libraries.
V/DownloadManager( 3319): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3319): created cursor android.database.sqlite.SQLiteCursor@3a924f03 on behalf of 6956
D/Finsky  ( 6956): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/MultiDex( 7014): VM with version 2.1.0 has multidex support
I/MultiDex( 7014): install
I/MultiDex( 7014): VM has multidex support, MultiDex support library is disabled.
,D/Finsky  ( 6956): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
V/JNIHelp ( 7014): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,V/SIM_STK ( 1033): Menu title from STK is T-Mobile
,W/ActivityThread( 7014): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7014): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@15b93b44: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7014): Installed default security provider GmsCore_OpenSSL
D/GCM     ( 2133): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AuthorizationBluetoothService( 2133): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 2390): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/ActivityManager( 1033): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=7051 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,D/LocationInitializer( 2390): Restart initialization of location
,W/ResourcesManager( 7051): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7051): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/art     ( 2390): Explicit concurrent mark sweep GC freed 17965(1255KB) AllocSpace objects, 18(288KB) LOS objects, 49% free, 32MB/64MB, paused 1.601ms total 47.901ms
,I/MultiDex( 7051): VM with version 2.1.0 has multidex support
I/MultiDex( 7051): install
I/MultiDex( 7051): VM has multidex support, MultiDex support library is disabled.
,V/Finsky  ( 6956): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,I/art     ( 1033): Explicit concurrent mark sweep GC freed 27430(1283KB) AllocSpace objects, 7(624KB) LOS objects, 33% free, 44MB/66MB, paused 1.167ms total 71.956ms
,V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/JNIHelp ( 7051): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/GLSUser ( 2133): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2133): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2133): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2133): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityThread( 7051): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7051): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@15b93b44: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7051): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 2133): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AuthorizationBluetoothService( 2133): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/Finsky  ( 6956): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6956): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6956): [1] 5.onFinished: Scheduling replication attempt 2.
V/GmsCoreStatsServiceLauncher( 2390): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
D/WearableService( 7051): callingUid 10005, callindPid: 7051
D/LocationInitializer( 2390): Restart initialization of location
,I/ActivityManager( 1033): Killing 6602:com.lge.drmservice/u0a62 (adj 15): empty #17
I/ActivityManager( 1033): Killing 6473:com.android.gallery3d/u0a27 (adj 15): empty #18
,W/libprocessgroup( 1033): failed to open /acct/uid_10062/pid_6602/cgroup.procs: No such file or directory
,W/libprocessgroup( 1033): failed to open /acct/uid_10027/pid_6473/cgroup.procs: No such file or directory
E/MDM     ( 1805): [87] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/MDM     ( 1805): [87] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/Finsky  ( 6956): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/AlarmManager( 1033): RTC_WAKEUP set : Alarm{11c84bee type 0 when 1454434040761 com.android.vending} when 1454434040761
,V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2133): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 2133): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2133): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2133): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 6956): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2133): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 2133): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2133): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2133): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2133): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 2133): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2133): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2133): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 6956): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/SIM_STK ( 1033): Menu title from STK is T-Mobile
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=10.7, 0.0, 0.0  rx=9.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1559872119] gl rssi=-62 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=10.7, 0.0, 0.0  rx=9.1 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1559872117] gl rssi=-62 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2133): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2133): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2133): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2133): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 2133): Explicit concurrent mark sweep GC freed 24323(1458KB) AllocSpace objects, 11(1584KB) LOS objects, 51% free, 30MB/62MB, paused 1.436ms total 50.936ms
,W/Finsky  ( 6956): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 6956): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
D/Finsky  ( 6956): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6956): [1] DailyHygiene.reschedule: Scheduling new run in 844 minutes (failures=5)
,D/DeviceConnectionService( 1805): client connected with version: 7571000
,D/UEI.SmartControl( 6919): Internal timer expired: 1
,D/UEI.SmartControl( 6919): unbind internal service
,D/serial_port( 6919): close(fd = 25)
,I/UEI.SmartControl( 6919): Serial port is closed.
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=6.3, 0.0, 0.0  rx=5.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1559869100] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=6.3, 0.0, 0.0  rx=5.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559869097] gl rssi=-63 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,I/ActivityManager( 1033): Killing 6643:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,W/libprocessgroup( 1033): failed to open /acct/uid_10093/pid_6643/cgroup.procs: No such file or directory
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=3.7, 0.0, 0.0  rx=3.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1559866077] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=3.7, 0.0, 0.0  rx=3.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1559866067] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 137836649430; DSPS: 4657981; Offset : -4328144120
,I/[SystemUI]QPairHandler( 1463): onReceive = android.intent.action.PACKAGE_CHANGED
,D/SplitUIService( 1858): replaced split : contains_com.google.android.talk / true
I/InputReader( 1033): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager( 1033): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7093 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/[SystemUI]QSlideListController( 1463): onReceive = android.intent.action.PACKAGE_CHANGED
,I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1463): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.talk
D/SplitUIManager( 1858): split_name #11 / not available #0
I/SplitUIService( 1858): split app #11
,I/[LGHome]EVENT( 2020): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000010 (has extras) }
D/administrator( 1033): Handling package changes for user 0
,W/ResourcesManager( 2020): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/[LGHome]Launcher( 2020): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/AppUp4:AppBoxCP( 7093): onCreate
,W/AppUp4:DB( 7093):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7093):  setFingerPrint start
I/AppUp4:DB( 7093):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 7093):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
,I/AppUp4:DB( 7093):  SDK version = 21
I/AppUp4:DB( 7093):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7093): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 7093): onReceive
I/NotificationService( 1033): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService( 1033): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000010 (has extras) }
,W/ResourcesManager( 1033): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/LgDataFeature( 7093): LgDataFeature() Constructor: none
,D/LgDataFeature( 7093): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7093): Context : android.app.ReceiverRestrictedContext@f1b861c
D/AppUp4:CustFacade( 7093): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7093): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7093): begin check event
I/AppUp4:CustModeStarterReceiver( 7093): Event For Nothing, skip.
W/ResourcesManager( 1033): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourceType( 1033): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/ActivityManager( 1033): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7129 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/ActivityManager( 1033): Killing 6519:com.android.chrome/u0a57 (adj 15): empty #17
,W/libprocessgroup( 1033): failed to open /acct/uid_10057/pid_6519/cgroup.procs: No such file or directory
,I/[LGHome]EVENT( 2020): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,W/ResourcesManager( 7129): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7129): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7129): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,W/ResourcesManager( 7129): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7129): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/SystemConfig( 7129): BUILD Country: EU
I/SystemConfig( 7129): BUILD Operator: OPEN
,I/ActivityManager( 1033): Killing 6686:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,W/libprocessgroup( 1033): failed to open /acct/uid_10097/pid_6686/cgroup.procs: No such file or directory
,I/ActivityManager( 1033): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7149 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/SystemConfig( 7129): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7129): existFile = false
I/SystemConfig( 7129): canReadFile = false
I/SystemConfig( 7129): systemFeature RCS result false
D/SystemConfig( 7129): refreshRcsSupport() :false
,W/ResourcesManager( 7149): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7149): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 7149): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 7149): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/AppConfig( 7149): Total System Memory = 2995761152
,D/SystemHelper( 7149): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager( 1033): Killing 6546:com.lge.email/u0a23 (adj 15): empty #17
,W/libprocessgroup( 1033): failed to open /acct/uid_10023/pid_6546/cgroup.procs: No such file or directory
,I/UpdateIcingCorporaServi( 4210): Updating corpora: APPS=com.google.android.talk, CONTACTS=MAYBE
,I/ActivityManager( 1033): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7175 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.8, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1559863053] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.8, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1559863052] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
V/SIM_STK ( 1033): Menu title from STK is T-Mobile
,W/ResourcesManager( 4210): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 4210): UpdateCorporaTask done [took 117 ms] updated apps [took 117 ms] 
,I/LockScreenSettings( 7175): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7175): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7175): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7175): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7175): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7175): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
D/LockScreenSettings( 7175): Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,I/ActivityManager( 1033): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7192 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1033): Killing 5145:com.wsandroid.suite.lge/1000 (adj 15): empty #17
W/libprocessgroup( 1033): failed to open /acct/uid_1000/pid_5145/cgroup.procs: No such file or directory
,W/ResourcesManager( 7192): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/PackageBroadcastService( 2390): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.talk
,I/PeopleContactsSync( 2390): CP2 sync disabled
,I/GLSActivity( 2133): [ac] getting account id
,I/GLSUser ( 2133): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1559860037] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1559860027] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/ActivityManager( 1033): Killing 6767:com.qualcomm.timeservice/1000 (adj 15): empty #17
,W/libprocessgroup( 1033): failed to open /acct/uid_1000/pid_6767/cgroup.procs: No such file or directory
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2412 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1559856991] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2412 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:-1559856991] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1559853972] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-55 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559853969] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
,V/AlarmManager( 1033): RTC_WAKEUP set : Alarm{1d8288 type 0 when 1454434061134 com.android.vending} when 1454434061134
,V/AlarmManager( 1033): ELAPSED_WAKEUP set : Alarm{7863421 type 2 when 150238 android} when 150238
,V/SIM_STK ( 1033): Menu title from STK is T-Mobile
,V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2133): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2133): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2133): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2133): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6956): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6956): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6956): [1] 5.onFinished: Scheduling replication attempt 3.
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1559850935] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1559850931] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1559847905] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1559847895] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1033):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,E/WifiStateMachine( 1033):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,E/WifiStateMachine( 1033):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1033):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,E/WifiStateMachine( 1033):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1559844873] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559844870] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 157838763381; DSPS: 5313411; Offset : -4328166321
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1559841831] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559841828] gl rssi=-63 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1559838803] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559838800] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1559835775] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1559835766] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
I/[SystemUI]TimeTickManager( 1463): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1463): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1463): called onTimeUpdated()
I/[SystemUI]Clock( 1463): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1463): called onTimeUpdated()
I/[SystemUI]DateView( 1463): called onTimeUpdated()
I/[SystemUI]DateView( 1463): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1463): handleTimeUpdate
,I/[SystemUI]TimeTickManager( 1463): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1463): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1463): called onTimeUpdated()
,I/[SystemUI]Clock( 1463): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1463): called onTimeUpdated()
,I/[SystemUI]DateView( 1463): called onTimeUpdated()
I/[SystemUI]DateView( 1463): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1463): handleTimeUpdate
E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1559832746] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1559832733] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
D/PowerManagerServiceEx( 1033): acquireWakeLockInternal: lock=575145497, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1033
,V/AlarmManager( 1033): RTC_WAKEUP set : Alarm{67a9db8 type 0 when 1454434081768 com.android.vending} when 1454434081768
,D/[Concierge]Service( 2612): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1033): releaseWakeLockInternal: lock=575145497 [*alarm*], flags=0x0
,V/SIM_STK ( 1033): Menu title from STK is T-Mobile
,V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1559829713] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1559829711] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,I/art     ( 1033): Explicit concurrent mark sweep GC freed 37924(1758KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 2.405ms total 168.408ms
,I/GLSUser ( 2133): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2133): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2133): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2133): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6956): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6956): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6956): [1] 5.onFinished: Scheduling replication attempt 4.
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1559826691] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559826688] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 177840982801; DSPS: 5968843; Offset : -4328144089
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1559823668] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1559823656] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,V/AlarmManager( 1033): ELAPSED_WAKEUP set : Alarm{36daa9da type 2 when 180261 android} when 180261
,I/BooksSync( 6456): Starting books sync
,D/BooksSync( 6456): started syncMyEbooks
,V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2133): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 2133): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2133): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2133): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1033): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1033): pkg=com.google.android.gms canInterrupt=false intercept=true,
I/NotificationServiceEx( 1033): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1033): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1033): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1411): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1411): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1411): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1411): handleNotificationPosted(true)
D/QuickCircle( 1411): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1411): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1411): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1411): post do just update job
,D/LgeQuickCoverNotificationData( 1411): showAll3
W/GLSActivity( 2133): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2133): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2133): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2133): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2133): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2133): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2133): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNotificationData( 1411): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1411): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1411): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1411): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
D/ContactsSyncAdapter( 2133): innerSync failed
D/ContactsSyncAdapter( 2133): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2133): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2133): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2133): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2133): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2133): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2133): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2133): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2133): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2133): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2133): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2133): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  2
,D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1411): updateNotificationData: count=3
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{3ab4fef3 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/SyncManager( 1033): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 153455, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
I/GLSUser ( 2133): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
D/SyncManager( 1033): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 245505, reason: 10019
I/GLSUser ( 2133): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2133): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2133): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1033): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1033): pkg=com.google.android.gms canInterrupt=false intercept=true
,I/NotificationServiceEx( 1033): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1033): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1033): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1411): onNotificationPosted
W/GLSActivity( 2133): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2133): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2133): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2133): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2133): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2133): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2133): 	at android.os.Binder.execTransact(Binder.java:446)
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
E/BooksAccountManager( 6456): Authentication error
E/BooksAccountManager( 6456): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6456): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6456): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6456): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6456): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6456): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6456): null auth token
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1411): updateNotificationData: count=3
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{3ab4fef3 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6456): Error response from books API: {
W/ApiaryClient( 6456):  "error": {
W/ApiaryClient( 6456):   "errors": [
W/ApiaryClient( 6456):    {
W/ApiaryClient( 6456):     "domain": "global",
W/ApiaryClient( 6456):     "reason": "required",
W/ApiaryClient( 6456):     "message": "Login Required",
W/ApiaryClient( 6456):     "locationType": "header",
W/ApiaryClient( 6456):     "location": "Authorization"
W/ApiaryClient( 6456):    }
W/ApiaryClient( 6456):   ],
W/ApiaryClient( 6456):   "code": 401,
W/ApiaryClient( 6456):   "message": "Login Required"
W/ApiaryClient( 6456):  }
W/ApiaryClient( 6456): }
,W/ApiaryClient( 6456): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6456): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=3166412288102034058&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6456): Headers:
W/ApiaryClient( 6456): accept-encoding: [gzip]
W/ApiaryClient( 6456): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6456): gdata-version: 2
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1559820636] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1559820626] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL],
V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2133): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2133): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2133): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2133): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1033): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1033): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1033): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1033): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1033): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/GLSActivity( 2133): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2133): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2133): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2133): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2133): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2133): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2133): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6456): Authentication error
E/BooksAccountManager( 6456): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6456): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6456): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6456): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6456): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6456): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6456): null auth token
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{3ab4fef3 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6456): Error response from books API: {
W/ApiaryClient( 6456):  "error": {
W/ApiaryClient( 6456):   "errors": [
W/ApiaryClient( 6456):    {
W/ApiaryClient( 6456):     "domain": "global",
W/ApiaryClient( 6456):     "reason": "required",
W/ApiaryClient( 6456):     "message": "Login Required",
W/ApiaryClient( 6456):     "locationType": "header",
W/ApiaryClient( 6456):     "location": "Authorization"
W/ApiaryClient( 6456):    }
W/ApiaryClient( 6456):   ],
W/ApiaryClient( 6456):   "code": 401,
W/ApiaryClient( 6456):   "message": "Login Required"
W/ApiaryClient( 6456):  }
W/ApiaryClient( 6456): }
,W/ApiaryClient( 6456): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6456): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=3166412288102034058&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6456): Headers:
W/ApiaryClient( 6456): accept-encoding: [gzip]
W/ApiaryClient( 6456): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6456): gdata-version: 2
,V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2133): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2133): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2133): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2133): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1033): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1033): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1033): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1033): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1033): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
,E/LgeQuickCoverOverlayWindow( 1411): updateNotificationData: count=3
W/GLSActivity( 2133): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2133): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2133): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2133): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2133): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2133): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2133): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6456): Authentication error
E/BooksAccountManager( 6456): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6456): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6456): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6456): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6456): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6456): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6456): null auth token
,D/QuickStatusbarLayout( 1411): Notification difference=198
,D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{3ab4fef3 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6456): Error response from books API: {
W/ApiaryClient( 6456):  "error": {
W/ApiaryClient( 6456):   "errors": [
W/ApiaryClient( 6456):    {
W/ApiaryClient( 6456):     "domain": "global",
W/ApiaryClient( 6456):     "reason": "required",
W/ApiaryClient( 6456):     "message": "Login Required",
W/ApiaryClient( 6456):     "locationType": "header",
W/ApiaryClient( 6456):     "location": "Authorization"
W/ApiaryClient( 6456):    }
W/ApiaryClient( 6456):   ],
W/ApiaryClient( 6456):   "code": 401,
W/ApiaryClient( 6456):   "message": "Login Required"
W/ApiaryClient( 6456):  }
W/ApiaryClient( 6456): }
,W/ApiaryClient( 6456): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6456): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=3166412288102034058&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6456): Headers:
W/ApiaryClient( 6456): accept-encoding: [gzip]
W/ApiaryClient( 6456): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6456): gdata-version: 2
,E/BooksSync( 6456): Soft error: 
E/BooksSync( 6456): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6456): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=3166412288102034058&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6456): Headers:
E/BooksSync( 6456): accept-encoding: [gzip]
E/BooksSync( 6456): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6456): gdata-version: 2
E/BooksSync( 6456): 
E/BooksSync( 6456): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6456): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6456): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6456): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6456): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6456): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6456): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6456): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6456): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6456): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6456): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6456): {
E/BooksSync( 6456):  "error": {
E/BooksSync( 6456):   "errors": [
E/BooksSync( 6456):    {
E/BooksSync( 6456):     "domain": "global",
E/BooksSync(, 6456):     "reason": "required",
E/BooksSync( 6456):     "message": "Login Required",
E/BooksSync( 6456):     "locationType": "header",
E/BooksSync( 6456):     "location": "Authorization"
E/BooksSync( 6456):    }
E/BooksSync( 6456):   ],
E/BooksSync( 6456):   "code": 401,
E/BooksSync( 6456):   "message": "Login Required"
E/BooksSync( 6456):  }
E/BooksSync( 6456): }
E/BooksSync( 6456): 
E/BooksSync( 6456): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6456): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6456): 	... 8 more
,E/BooksSync( 6456): Sync error
E/BooksSync( 6456): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6456): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=3166412288102034058&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6456): Headers:
E/BooksSync( 6456): accept-encoding: [gzip]
E/BooksSync( 6456): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6456): gdata-version: 2
E/BooksSync( 6456): 
E/BooksSync( 6456): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6456): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6456): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6456): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6456): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6456): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6456): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6456): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6456): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6456): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6456): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6456): {
E/BooksSync( 6456):  "error": {
E/BooksSync( 6456):   "errors": [
E/BooksSync( 6456):    {
E/BooksSync( 6456):     "domain": "global",
E/BooksSync( 6456):     "reason": "required",
E/BooksSync( 6456):     "message": "Login Required",
E/BooksSync( 6456):     "locationType": "header",
E/BooksSync( 6456):     "location": "Authorization"
E/BooksSync( 6456):    }
E/BooksSync( 6456):   ],
E/BooksSync( 6456):   "code": 401,
E/BooksSync( 6456):   "message": "Login Required"
E/BooksSync( 6456):  }
E/BooksSync( 6456): }
E/BooksSync( 6456): 
E/BooksSync( 6456): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6456): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6456): 	... 8 more
I/BooksSync( 6456): Finished books sync
D/SyncManager( 1033): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 156519, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1559817603] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559817600] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=3.2, 0.0, 0.0  rx=3.2 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1559814577] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0,
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=3.2, 0.0, 0.0  rx=3.2 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1559814567] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=2.1, 0.0, 0.0  rx=2.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1559811544] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=2.1, 0.0, 0.0  rx=2.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559811541] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1559808514] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559808511] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1559805487] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1559805477] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 197843030606; DSPS: 6624271; Offset : -4328171505
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1559802457] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:8] from screen [on:0 period:-1559802449] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1559799428] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559799425] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1559796401] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559796398] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,V/AlarmManager( 1033): RTC_WAKEUP set : Alarm{3a7809b6 type 0 when 1454434103758 com.android.vending} when 1454434103758
,V/SIM_STK ( 1033): Menu title from STK is T-Mobile
,V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2133): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2133): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2133): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2133): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6956): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6956): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6956): [1] 5.onFinished: Scheduling replication attempt 5.
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1559793371] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559793368] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,V/AlarmManager( 1033): ELAPSED_WAKEUP set : Alarm{490c854 type 2 when 180002 com.google.android.gms} when 180002
,V/AlarmManager( 1033): ELAPSED_WAKEUP set : Alarm{13a713fd type 2 when 209377 android} when 209377
V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 2133): Vacuum at: now=1454434121464 tag=VacuumService
,V/AlarmManager( 1033): ELAPSED_WAKEUP set : Alarm{3479c5b5 type 2 when 210340 android} when 210340
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1559790344] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559790341] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1559787319] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559787316] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1559784289] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559784286] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 217845161378; DSPS: 7279700; Offset : -4328146420
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1559781267] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1559781257] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1559778237] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1559778225] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1559775204] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559775201] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,V/AlarmManager( 1033): RTC_WAKEUP set : Alarm{21470fbb type 0 when 1454434138631 com.android.vending} when 1454434138631
,V/SIM_STK ( 1033): Menu title from STK is T-Mobile
,V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2133): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2133): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2133): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2133): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6956): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6956): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6956): [1] 5.onFinished: Giving up after 6 failures.
I/[SystemUI]TimeTickManager( 1463): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1463): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1463): called onTimeUpdated()
I/[SystemUI]Clock( 1463): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1463): called onTimeUpdated()
I/[SystemUI]DateView( 1463): called onTimeUpdated()
I/[SystemUI]DateView( 1463): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1463): handleTimeUpdate
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1559772175] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1559772166] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1559769145] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1559769141] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1559766113] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559766110] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 237848892777; DSPS: 7935183; Offset : -4328168761
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1559763083] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559763080] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1559760054] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559760051] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1559757025] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1559757016] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1559753995] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1559753983] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
D/PowerManagerServiceEx( 1033): acquireWakeLockInternal: lock=575145497, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1033
,V/AlarmManager( 1033): ELAPSED_WAKEUP set : Alarm{f688625 type 2 when 248147 android} when 248147
D/[Concierge]Service( 2612): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1033): releaseWakeLockInternal: lock=575145497 [*alarm*], flags=0x0
,I/BooksSync( 6456): Starting books sync
,D/BooksSync( 6456): started syncMyEbooks
,V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2133): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2133): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2133): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2133): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1033): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1033): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1033): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1033): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1033): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1411): updateNotificationData: count=3
W/GLSActivity( 2133): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2133): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2133): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2133): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2133): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2133): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2133): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6456): Authentication error
E/BooksAccountManager( 6456): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6456): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6456): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6456): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6456): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6456): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6456): null auth token
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{3ab4fef3 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/art     ( 1033): Explicit concurrent mark sweep GC freed 48626(2MB) AllocSpace objects, 7(752KB) LOS objects, 33% free, 44MB/66MB, paused 2.107ms total 111.608ms
,W/ApiaryClient( 6456): Error response from books API: {
W/ApiaryClient( 6456):  "error": {
W/ApiaryClient( 6456):   "errors": [
W/ApiaryClient( 6456):    {
W/ApiaryClient( 6456):     "domain": "global",
W/ApiaryClient( 6456):     "reason": "required",
W/ApiaryClient( 6456):     "message": "Login Required",
W/ApiaryClient( 6456):     "locationType": "header",
W/ApiaryClient( 6456):     "location": "Authorization"
W/ApiaryClient( 6456):    }
W/ApiaryClient( 6456):   ],
W/ApiaryClient( 6456):   "code": 401,
W/ApiaryClient( 6456):   "message": "Login Required"
W/ApiaryClient( 6456):  }
W/ApiaryClient( 6456): }
,W/ApiaryClient( 6456): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6456): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3020425508833079277&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6456): Headers:
W/ApiaryClient( 6456): accept-encoding: [gzip]
W/ApiaryClient( 6456): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6456): gdata-version: 2
,V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2133): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2133): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2133): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2133): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1033): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1033): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1033): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1033): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1033): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/GLSActivity( 2133): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2133): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2133): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2133): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2133): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2133): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2133): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6456): Authentication error
E/BooksAccountManager( 6456): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6456): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6456): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6456): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6456): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6456): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6456): null auth token
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{3ab4fef3 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6456): Error response from books API: {
W/ApiaryClient( 6456):  "error": {
W/ApiaryClient( 6456):   "errors": [
W/ApiaryClient( 6456):    {
W/ApiaryClient( 6456):     "domain": "global",
W/ApiaryClient( 6456):     "reason": "required",
W/ApiaryClient( 6456):     "message": "Login Required",
W/ApiaryClient( 6456):     "locationType": "header",
W/ApiaryClient( 6456):     "location": "Authorization"
W/ApiaryClient( 6456):    }
W/ApiaryClient( 6456):   ],
W/ApiaryClient( 6456):   "code": 401,
W/ApiaryClient( 6456):   "message": "Login Required"
W/ApiaryClient( 6456):  }
W/ApiaryClient( 6456): }
,W/ApiaryClient( 6456): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6456): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3020425508833079277&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6456): Headers:
W/ApiaryClient( 6456): accept-encoding: [gzip]
W/ApiaryClient( 6456): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6456): gdata-version: 2
,V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2133): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2133): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2133): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2133): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1033): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1033): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1033): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1033): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1033): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/GLSActivity( 2133): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2133): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2133): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2133): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2133): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2133): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2133): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6456): Authentication error
E/BooksAccountManager( 6456): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6456): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6456): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6456): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6456): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6456): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6456): null auth token
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{3ab4fef3 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6456): Error response from books API: {
W/ApiaryClient( 6456):  "error": {
W/ApiaryClient( 6456):   "errors": [
W/ApiaryClient( 6456):    {
W/ApiaryClient( 6456):     "domain": "global",
W/ApiaryClient( 6456):     "reason": "required",
W/ApiaryClient( 6456):     "message": "Login Required",
W/ApiaryClient( 6456):     "locationType": "header",
W/ApiaryClient( 6456):     "location": "Authorization"
W/ApiaryClient( 6456):    }
,W/ApiaryClient( 6456):   ],
W/ApiaryClient( 6456):   "code": 401,
W/ApiaryClient( 6456):   "message": "Login Required"
W/ApiaryClient( 6456):  }
W/ApiaryClient( 6456): }
,W/ApiaryClient( 6456): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6456): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3020425508833079277&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6456): Headers:
W/ApiaryClient( 6456): accept-encoding: [gzip]
W/ApiaryClient( 6456): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6456): gdata-version: 2
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1559750961] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559750958] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,E/BooksSync( 6456): Soft error: 
E/BooksSync( 6456): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6456): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3020425508833079277&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6456): Headers:
E/BooksSync( 6456): accept-encoding: [gzip]
E/BooksSync( 6456): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6456): gdata-version: 2
E/BooksSync( 6456): 
E/BooksSync( 6456): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6456): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6456): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6456): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6456): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6456): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6456): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6456): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6456): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6456): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6456): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6456): {
E/BooksSync( 6456):  "error": {
E/BooksSync( 6456):   "errors": [
E/BooksSync( 6456):    {
E/BooksSync( 6456):     "domain": "global",
E/BooksSync( 6456):     "reason": "required",
E/BooksSync( 6456):     "message": "Login Required",
E/BooksSync( 6456):     "locationType": "header",
E/BooksSync( 6456):     "location": "Authorization"
E/BooksSync( 6456):    }
E/BooksSync( 6456):   ],
E/BooksSync( 6456):   "code": 401,
E/BooksSync( 6456):   "message": "Login Required"
E/BooksSync( 6456):  }
E/BooksSync( 6456): }
E/BooksSync( 6456): 
E/BooksSync( 6456): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6456): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6456): 	... 8 more
,E/BooksSync( 6456): Sync error
E/BooksSync( 6456): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6456): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3020425508833079277&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6456): Headers:
E/BooksSync( 6456): accept-encoding: [gzip]
E/BooksSync( 6456): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6456): gdata-version: 2
E/BooksSync( 6456): 
E/BooksSync( 6456): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6456): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6456): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6456): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6456): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6456): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6456): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6456): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6456): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6456): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6456): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6456): {
E/BooksSync( 6456):  "error": {
E/BooksSync( 6456):   "errors": [
E/BooksSync( 6456):    {
E/BooksSync( 6456):     "domain": "global",
E/BooksSync( 6456):     "reason": "required",
E/BooksSync( 6456):     "message": "Login Required",
E/BooksSync( 6456):     "locationType": "header",
E/BooksSync( 6456):     "location": "Authorization"
E/BooksSync( 6456):    }
E/BooksSync( 6456):   ],
E/BooksSync( 6456):   "code": 401,
E/BooksSync( 6456):   "message": "Login Required"
E/BooksSync( 6456):  }
E/BooksSync( 6456): }
E/BooksSync( 6456): 
E/BooksSync( 6456): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6456): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6456): 	... 8 more
I/BooksSync( 6456): Finished books sync
D/SyncManager( 1033): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 248147, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=3.4, 0.0, 0.0  rx=3.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1559747938] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=3.4, 0.0, 0.0  rx=3.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559747935] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=5.2, 0.0, 0.0  rx=4.7 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1559744909] gl rssi=-64 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=5.2, 0.0, 0.0  rx=4.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559744906] gl rssi=-64 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 257851010010; DSPS: 8590612; Offset : -4328157554
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=2.6, 0.0, 0.0  rx=2.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1559741878] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=2.6, 0.0, 0.0  rx=2.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559741875] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=1.3, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1559738848] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=1.3, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559738845] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1559735817] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1559735806] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1559732784] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559732781] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1559729755] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1559729746] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1559726725] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:14] from screen [on:0 period:-1559726711] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 277852615680; DSPS: 9246024; Offset : -4328138615
,V/AlarmManager( 1033): ELAPSED_WAKEUP set : Alarm{3becf767 type 2 when 278334 android} when 278334
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1559723692] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1559723691] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1559720675] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1559720665] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1559717643] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559717640] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1559714612] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559714609] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1463): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1463): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1463): called onTimeUpdated()
,I/[SystemUI]Clock( 1463): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1463): called onTimeUpdated()
I/[SystemUI]DateView( 1463): called onTimeUpdated()
I/[SystemUI]DateView( 1463): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1463): handleTimeUpdate
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1559711591] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1559711587] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,D/PowerManagerServiceEx( 1033): acquireWakeLockInternal: lock=575145497, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1033
,D/[Concierge]Service( 2612): onStartCommand(). Type : 9
,I/DigitalAppWidgetProvider( 6743): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 6743): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@2b68e808
,D/PowerManagerServiceEx( 1033): releaseWakeLockInternal: lock=575145497 [*alarm*], flags=0x0
E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1559708567] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1559708557] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1559705535] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1559705524] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 297854721974; DSPS: 9901454; Offset : -4328168735
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1559702502] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559702499] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1559699472] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559699469] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1559696442] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559696439] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,I/[SystemUI]LGPowerUI( 1463): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1463): On Skip Timer : true
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3027] from screen [on:0 period:-1559693388] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1559693387] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
D/KeyguardUpdateMonitor( 1463): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
,D/WifiController( 1033): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1463): onReceive = android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1930): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1930): Battery Level Remaining: 100%
D/LEDHandler( 1930): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 6049): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1463): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3164): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3164): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/Settings( 1033): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 1033): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1559690353] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559690350] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1559687325] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1559687316] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1559684295] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1559684285] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 317856797538; DSPS: 10556882; Offset : -4328168183
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1559681265] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1559681261] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1559678236] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1559678227] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1559675207] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1559675195] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1559672172] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559672169] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1559669146] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1559669136] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:2999] from screen [on:0 period:-1559666117] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1559666116] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL],
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 337858927010; DSPS: 11212311; Offset : -4328144451
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1559663098] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559663095] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1559660069] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559660066] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1559657043] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559657040] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1559654016] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1559654007] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
D/PowerManagerServiceEx( 1033): acquireWakeLockInternal: lock=575145497, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1033
,D/[Concierge]Service( 2612): onStartCommand(). Type : 9
,I/[SystemUI]TimeTickManager( 1463): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1463): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1463): called onTimeUpdated()
I/[SystemUI]Clock( 1463): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1463): called onTimeUpdated()
I/[SystemUI]DateView( 1463): called onTimeUpdated()
I/[SystemUI]DateView( 1463): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1463): handleTimeUpdate
D/PowerManagerServiceEx( 1033): releaseWakeLockInternal: lock=575145497 [*alarm*], flags=0x0
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1559650987] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1559650977] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1559647958] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1559647947] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1559644926] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1559644915] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 357861171066; DSPS: 11867745; Offset : -4328158825
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1559641896] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1559641886] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=1.8, 0.0, 0.0  rx=2.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1559638864] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=1.8, 0.0, 0.0  rx=2.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559638861] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=2.4, 0.0, 0.0  rx=3.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1559635828] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=2.4, 0.0, 0.0  rx=3.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559635825] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1559632798] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1559632797] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1559629783] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559629780] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1559626753] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559626750] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 377863105328; DSPS: 12523168; Offset : -4328147041
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1559623723] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559623720] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,V/AlarmManager( 1033): ELAPSED_WAKEUP set : Alarm{37f0e914 type 2 when 379978 android} when 379978
,I/BooksSync( 6456): Starting books sync
,D/BooksSync( 6456): started syncMyEbooks
,V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2133): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2133): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2133): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2133): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 2133): Explicit concurrent mark sweep GC freed 39318(2MB) AllocSpace objects, 15(2MB) LOS objects, 51% free, 30MB/62MB, paused 1.326ms total 37.613ms
,V/NotificationService( 1033): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1033): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1033): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1033): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1033): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2133): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2133): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2133): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2133): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2133): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2133): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2133): 	at android.os.Binder.execTransact(Binder.java:446)
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
E/BooksAccountManager( 6456): Authentication error
E/BooksAccountManager( 6456): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6456): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6456): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6456): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6456): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6456): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6456): null auth token
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{3ab4fef3 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6456): Error response from books API: {
W/ApiaryClient( 6456):  "error": {
W/ApiaryClient( 6456):   "errors": [
W/ApiaryClient( 6456):    {
W/ApiaryClient( 6456):     "domain": "global",
W/ApiaryClient( 6456):     "reason": "required",
W/ApiaryClient( 6456):     "message": "Login Required",
W/ApiaryClient( 6456):     "locationType": "header",
W/ApiaryClient( 6456):     "location": "Authorization"
W/ApiaryClient( 6456):    }
W/ApiaryClient( 6456):   ],
W/ApiaryClient( 6456):   "code": 401,
W/ApiaryClient( 6456):   "message": "Login Required"
W/ApiaryClient( 6456):  }
W/ApiaryClient( 6456): }
,W/ApiaryClient( 6456): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6456): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7983562420229956321&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6456): Headers:
W/ApiaryClient( 6456): accept-encoding: [gzip]
W/ApiaryClient( 6456): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6456): gdata-version: 2
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1559620690] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559620687] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2133): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2133): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2133): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2133): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1033): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1033): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1033): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1033): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1033): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
,D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1411): updateNotificationData: count=3
W/GLSActivity( 2133): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2133): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2133): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2133): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2133): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2133): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2133): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6456): Authentication error
E/BooksAccountManager( 6456): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6456): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6456): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6456): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6456): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6456): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6456): null auth token
,D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{3ab4fef3 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6456): Error response from books API: {
W/ApiaryClient( 6456):  "error": {
W/ApiaryClient( 6456):   "errors": [
W/ApiaryClient( 6456):    {
W/ApiaryClient( 6456):     "domain": "global",
W/ApiaryClient( 6456):     "reason": "required",
W/ApiaryClient( 6456):     "message": "Login Required",
W/ApiaryClient( 6456):     "locationType": "header",
W/ApiaryClient( 6456):     "location": "Authorization"
W/ApiaryClient( 6456):    }
W/ApiaryClient( 6456):   ],
W/ApiaryClient( 6456):   "code": 401,
W/ApiaryClient( 6456):   "message": "Login Required"
W/ApiaryClient( 6456):  }
W/ApiaryClient( 6456): }
W/ApiaryClient( 6456): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6456): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7983562420229956321&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6456): Headers:
W/ApiaryClient( 6456): accept-encoding: [gzip]
W/ApiaryClient( 6456): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6456): gdata-version: 2
,V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2133): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2133): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2133): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2133): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1033): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1033): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1033): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1033): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1033): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2133): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2133): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2133): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2133): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2133): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2133): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2133): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6456): Authentication error
E/BooksAccountManager( 6456): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6456): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6456): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6456): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6456): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6456): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6456): null auth token
W/ResourcesManager( 1411): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 1411): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
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
W/ResourcesManager( 1411): Asset path '/system/framework/com.lge.systemui.jar' does not exist or contains no resources.
,W/ResourcesManager( 1411): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1411): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1411): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1411): updateNotificationData: count=3
D/QuickStatusbarLayout( 1411): Notification difference=198
,D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{3ab4fef3 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6456): Error response from books API: {
W/ApiaryClient( 6456):  "error": {
W/ApiaryClient( 6456):   "errors": [
W/ApiaryClient( 6456):    {
W/ApiaryClient( 6456):     "domain": "global",
W/ApiaryClient( 6456):     "reason": "required",
W/ApiaryClient( 6456):     "message": "Login Required",
W/ApiaryClient( 6456):     "locationType": "header",
W/ApiaryClient( 6456):     "location": "Authorization"
W/ApiaryClient( 6456):    }
W/ApiaryClient( 6456):   ],
W/ApiaryClient( 6456):   "code": 401,
W/ApiaryClient( 6456):   "message": "Login Required"
W/ApiaryClient( 6456):  }
W/ApiaryClient( 6456): }
,W/ApiaryClient( 6456): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6456): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7983562420229956321&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6456): Headers:
W/ApiaryClient( 6456): accept-encoding: [gzip]
W/ApiaryClient( 6456): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6456): gdata-version: 2
,E/BooksSync( 6456): Soft error: 
E/BooksSync( 6456): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6456): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7983562420229956321&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6456): Headers:
E/BooksSync( 6456): accept-encoding: [gzip]
E/BooksSync( 6456): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6456): gdata-version: 2
E/BooksSync( 6456): 
E/BooksSync( 6456): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6456): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6456): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6456): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6456): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6456): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6456): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6456): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6456): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6456): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6456): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6456): {
E/BooksSync( 6456):  "error": {
E/BooksSync( 6456):   "errors": [
E/BooksSync( 6456):    {
E/BooksSync( 6456):     "domain": "global",
E/BooksSync( 6456):     "reason": "required",
E/BooksSync( 6456):     "message": "Login Required",
E/BooksSync( 6456):     "locationType": "header",
E/BooksSync( 6456):     "location": "Authorization"
E/BooksSync( 6456):    }
E/BooksSync( 6456):   ],
E/BooksSync( 6456):   "code": 401,
E/BooksSync( 6456):   "message": "Login Required"
E/BooksSync( 6456):  }
E/BooksSync( 6456): }
E/BooksSync( 6456): 
E/BooksSync( 6456): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6456): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6456): 	... 8 more
,E/BooksSync( 6456): Sync error
E/BooksSync( 6456): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6456): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7983562420229956321&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6456): Headers:
E/BooksSync( 6456): accept-encoding: [gzip]
E/BooksSync( 6456): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6456): gdata-version: 2
E/BooksSync( 6456): 
E/BooksSync( 6456): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6456): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6456): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6456): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6456): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6456): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6456): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6456): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6456): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6456): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6456): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6456): {
E/BooksSync( 6456):  "error": {
E/BooksSync( 6456):   "errors": [
E/BooksSync( 6456):    {
E/BooksSync( 6456):     "domain": "global",
E/BooksSync( 6456):     "reason": "required",
E/BooksSync( 6456):     "message": "Login Required",
E/BooksSync( 6456):     "locationType": "header",
E/BooksSync( 6456):     "location": "Authorization"
E/BooksSync( 6456):    }
E/BooksSync( 6456):   ],
E/BooksSync( 6456):   "code": 401,
E/BooksSync( 6456):   "message": "Login Required"
E/BooksSync( 6456):  }
E/BooksSync( 6456): }
E/BooksSync( 6456): 
E/BooksSync( 6456): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6456): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6456): 	... 8 more
I/BooksSync( 6456): Finished books sync
D/SyncManager( 1033): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 379978, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=1.5, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1559617662] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=1.5, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559617659] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=2.8, 0.0, 0.0  rx=2.6 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1559614631] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=2.8, 0.0, 0.0  rx=2.6 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559614628] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1559611607] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1559611598] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1559608579] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559608576] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1559605550] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559605547] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 397865001102; DSPS: 13178591; Offset : -4328173977
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1559602522] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559602519] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1559599492] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559599489] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1559596463] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559596460] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1559593436] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1559593426] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
I/[SystemUI]TimeTickManager( 1463): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1463): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1463): called onTimeUpdated()
I/[SystemUI]Clock( 1463): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1463): called onTimeUpdated()
,I/[SystemUI]DateView( 1463): called onTimeUpdated()
I/[SystemUI]DateView( 1463): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1463): handleTimeUpdate,
D/PowerManagerServiceEx( 1033): acquireWakeLockInternal: lock=575145497, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1033
,V/AlarmManager( 1033): ELAPSED_WAKEUP set : Alarm{1bb9725e type 2 when 410016 android} when 410016
D/[Concierge]Service( 2612): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1033): releaseWakeLockInternal: lock=575145497 [*alarm*], flags=0x0
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1559590406] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1559590396] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1559587381] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559587378] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1559584358] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559584355] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 417866899532; DSPS: 13834013; Offset : -4328167481
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1559581326] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1559581317] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1559578297] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1559578286] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1559575263] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559575260] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2133): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 2133): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2133): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2133): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1033): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1033): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1033): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1033): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1033): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/GLSActivity( 2133): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2133): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2133): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2133): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2133): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2133): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2133): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 6956): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6956): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6956): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 6956): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6956): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 6956): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6956): 	at android.os.Binder.execTransact(Binder.java:446)
D/QuickStatusbarLayout( 1411): Notification difference=198
D/QuickStatusbarLayout( 1411): child = android.widget.LinearLayout{3ab4fef3 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/System  ( 6956): Ignoring header User-Agent because its value was null.
,D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  314): res_queryN name = play.googleapis.com, class = 1, type = 1
D/libc-netbsd(  314): res_queryN name = play.googleapis.com succeed
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1559572233] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1559572224] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=7.0, 0.0, 0.0  rx=5.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1559569212] gl rssi=-64 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=7.0, 0.0, 0.0  rx=5.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559569209] gl rssi=-64 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=4.0, 0.0, 0.0  rx=3.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1559566184] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=4.0, 0.0, 0.0  rx=3.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559566181] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 437868987024; DSPS: 14489441; Offset : -4328155316
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=4.5, 0.0, 0.0  rx=4.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1559563162] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=4.5, 0.0, 0.0  rx=4.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559563159] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=2.3, 0.0, 0.0  rx=2.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1559560133] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=2.3, 0.0, 0.0  rx=2.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559560130] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1559557104] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559557101] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1559554077] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:8] from screen [on:0 period:-1559554069] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1559551048] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559551045] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1559548021] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559548018] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1559544993] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1559544984] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 457871734152; DSPS: 15144891; Offset : -4328154795
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1559541962] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559541959] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1559538933] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559538930] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1559535905] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1559535901] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1463): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1463): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1463): called onTimeUpdated()
,I/[SystemUI]Clock( 1463): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1463): called onTimeUpdated()
I/[SystemUI]DateView( 1463): called onTimeUpdated()
I/[SystemUI]DateView( 1463): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1463): handleTimeUpdate
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1559532877] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1559532868] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1559529849] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559529846] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1559526822] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559526819] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 477873833571; DSPS: 15800320; Offset : -4328161141
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1559523801] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559523798] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1559520780] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559520777] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1559517751] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559517748] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3007] from screen [on:0 period:-1559514723] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1559514713] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1559511691] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559511688] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1559508663] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559508660] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1559505635] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1559505631] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 497875605908; DSPS: 16455738; Offset : -4328158797
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1559502604] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559502601] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1559499576] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1559499566] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1559496545] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1559496541] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1559493516] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1559493507] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1559490486] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1559490475] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1559487455] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1559487451] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1559484427] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1559484418] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 517877724025; DSPS: 17111167; Offset : -4328146029
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1559481397] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1559481388] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1559478367] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1559478357] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1559475338] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559475335] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
I/[SystemUI]TimeTickManager( 1463): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1463): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1463): called onTimeUpdated()
I/[SystemUI]Clock( 1463): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1463): called onTimeUpdated()
I/[SystemUI]DateView( 1463): called onTimeUpdated()
I/[SystemUI]DateView( 1463): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1463): handleTimeUpdate
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1559472307] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1559472297] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1559469277] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1559469265] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1559466244] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559466241] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 537879858131; DSPS: 17766597; Offset : -4328148544
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1559463216] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1559463207] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1559460187] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1559460176] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1559457156] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1559457145] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL],
E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1559454123] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559454120] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1559451096] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1559451086] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1559448064] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559448061] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1559445037] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1559445028] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 557882518437; DSPS: 18422045; Offset : -4328173732
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1559442007] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:15] from screen [on:0 period:-1559441992] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1559438973] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559438970] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1559435943] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559435940] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1559432913] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559432910] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1559429884] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559429881] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1559426855] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1559426851] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 577884309992; DSPS: 19077463; Offset : -4328152198
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1559423826] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1559423815] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1559420801] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559420798] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1559417774] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559417771] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1559414741] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559414738] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1463): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1463): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1463): called onTimeUpdated()
I/[SystemUI]Clock( 1463): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1463): called onTimeUpdated()
,I/[SystemUI]DateView( 1463): called onTimeUpdated()
I/[SystemUI]DateView( 1463): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1463): handleTimeUpdate
E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1559411713] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559411710] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1559408685] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1559408676] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1559405656] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1559405645] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 597886234672; DSPS: 19732886; Offset : -4328150176
,E/WifiStateMachine( 1033):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1559402623] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1033):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-64 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1559402620] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1033): doString: [SIGNAL_POLL]
,I/wpa_supplicant( 6090): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/WifiMonitor( 1033): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0]
E/WifiMonitor( 1033): WifiMonitor:wlan0 cnt=25 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
E/WifiMonitor( 1033): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
D/WifiMonitor( 1033): handleNetworkStateChange: Could not parse disconnect string
E/WifiMonitor( 1033): WifiMonitor notify network disconnect: null reason=0
D/Tethering( 1033): InitialState.processMessage what=4
,E/WifiStateMachine( 1033):  ConnectedState NETWORK_DISCONNECTION_EVENT nid=0 reason=0 lastbssid=c0:ff:d4:d3:aa:48 freq=2412 rssi=-64 rt=599791
E/WifiStateMachine( 1033):  L2ConnectedState NETWORK_DISCONNECTION_EVENT nid=0 reason=0 lastbssid=c0:ff:d4:d3:aa:48 freq=2412 rssi=-64 rt=599791
E/WifiStateMachine( 1033):  ConnectModeState NETWORK_DISCONNECTION_EVENT nid=0 reason=0 lastbssid=c0:ff:d4:d3:aa:48 freq=2412 rssi=-64 rt=599792
E/WifiConfigStore( 1033): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1033): doBoolean: SET_NETWORK 0 bssid any
D/WifiMonitor( 1033): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1033): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1033): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1033): doBoolean: SAVE_CONFIG
,D/Tethering( 1033): sendTetherStateChangedBroadcast 0, 0, 0
,D/WifiNative-wlan0( 1033): SAVE_CONFIG: returned true
D/LGWifiP2pService( 1033): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1033): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1033): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 6090): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1033): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1033): doBoolean: SET ps 1
D/WifiNative-wlan0( 1033): SET ps 1: returned true
D/DhcpStateMachine( 1033): RunningState{ when=-7ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  314): Clearing all IP addresses on wlan0
,D/WifiMonitor( 1033): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1033): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
I/jxcore-log( 5968): Toggling radios to false
I/jxcore-log( 5968): 
,V/NativeCrypto( 2133): Read error: ssl=0xaf465600: I/O error during system call, Connection timed out
,I/wpa_supplicant( 6090): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1033): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1033): WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1033): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1033): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/ActivityManager( 1033): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=7463 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
V/NativeCrypto( 2133): SSL shutdown failed: ssl=0xaf465600: I/O error during system call, Broken pipe
D/BluetoothManagerService( 1033): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1033): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@2e31a210 mBinding = false
D/ConnectivityService( 1033): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1033): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
E/WifiStateMachine( 1033): WifiStateMachine: Leaving Connected state
D/WifiHS20( 1033): hidePasspointNotification off =false
I/StatusBar.NetworkController( 1463): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1463): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
D/BluetoothManagerService( 1033): Message: 2
D/BluetoothManagerService( 1033): Sending off request.
V/WfdStateTracker( 1930): handleWifiStateChangedEvent: 0
D/LGBluetoothServiceAdapter( 6049): [BTUI] Precleanup
D/BluetoothAdapterState( 6049): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 6049): Setting state to 13
I/BluetoothAdapterState( 6049): Bluetooth adapter state changed: 12-> 13
,D/LocationManagerService( 1033): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1033): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1033): JNI:system_update. Event-4
D/BluetoothAdapterProperties( 6049): onBluetoothDisable()
I/BluetoothAdapterState( 6049): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
D/BluetoothManagerService( 1033): Message: 60
D/BluetoothManagerService( 1033): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService( 1033): Bluetooth State Change Intent: 12 -> 13
W/Settings( 1033): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1033): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1033): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,D/ConnectivityService( 1033): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1033): ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1033): DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1033): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1033): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1033): Checking http://clients3.google.com/generate_204 on <unknown ssid>
E/WifiStateMachine( 1033):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1033):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1033):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1033):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1033):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1033):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=599998  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
D/WifiHS20( 1033): hidePasspointNotification off =false
E/WifiStateMachine( 1033):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=600000  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1033):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=600003  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,D/WifiServiceImplEx( 1033): setWifiEnabled: false pid=5968, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1033): setWifiEnabled: false pid=5968, uid=10311
E/WifiService( 1033): Invoking mWifiStateMachine.setWifiEnabled
D/BluetoothAdapterProperties( 6049): Scan Mode:20
D/BluetoothAdapterState( 6049): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
D/btif_config_util( 6049): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
W/Settings( 1033): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1033): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1033): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
V/BluetoothSapService( 6049): Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 6049): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 6049): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 6049): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
V/BluetoothMapMasInstance( 6049): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
V/BluetoothMapMasInstance( 6049): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
V/BluetoothMapMasInstance( 6049): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 6049): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 6049): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
W/bt-l2cap( 6049): L2CAP - L2CA_Deregister() called for PSM: 0x000f
W/bt-btif ( 6049): bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
W/bt-l2cap( 6049): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 6049): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 6049): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 6049): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 6049): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 6049): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 6049): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 6049): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 6049): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 6049): L2CAP - L2CA_Deregister() called for PSM: 0x0011
W/bt-l2cap( 6049): L2CAP - L2CA_Deregister() called for PSM: 0x0013
E/bt-btif ( 6049): bta_gattc_deregister Deregister Failedm unknown client cif
V/BluetoothPbapService( 6049): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/BtOppRfcommListener( 6049): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
D/LGBluetoothAPIService( 1930): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
I/BluetoothMapService( 6049): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 6049): STATE_TURNING_OFF
V/BtOppService( 6049): Receiver DISABLED_ACTION 
V/BluetoothMapService( 6049): Handler(): got msg=4
D/BluetoothMapService( 6049): MAP Service closeService in
D/BluetoothMapMasInstance( 6049): MAP Service shutdown
D/LGBluetoothMapAdapter( 6049): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 6049): MAP Service closeService out
I/BtOppRfcommListener( 6049): stopping Accept Thread
V/BtOppRfcommListener( 6049): close mBtServerSocket
V/BtOppRfcommListener( 6049): waiting for thread to terminate
I/BtOppRfcommListener( 6049): BluetoothSocket listen thread finished
V/BtOppRfcommListener( 6049): done waiting for thread to terminate
V/BtOppService( 6049): onDestroy
V/BluetoothFtpService:RfcommSocketAcceptThread( 6049): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=0
I/StatusBar.NetworkController( 1463): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1463): mWifiConnected = false, mWifiLevel = 0
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1033): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/ConnectivityService( 1033): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1033): Dns fail occured do internet check.
D/LGBluetoothOppAdapter( 6049): [BTUI] LGBluetoothOppAdapter cleanup
D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
D/DSQN    ( 1033): disableDataServiceNotify
D/DSQN    ( 1033): stop dsqn bin
D/DSQN    ( 1033): EVENT_INTERNET_CHECK_REQUEST received
D/DSQN    ( 1033): try Internet connection check
D/WifiHS20( 1033): hidePasspointNotification off =false
W/Settings( 1033): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1033): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1033): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1033):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=600030  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine( 1033):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1033):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1033):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1033):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
I/[SystemUI]BluetoothHandler( 1463): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
E/WifiStateMachine( 1033):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1033):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1033):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1033):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1033):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1033):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,D/ConnectivityService( 1033): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1033):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1033):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/WifiNetworkAgent( 1033): NetworkAgent: NetworkAgent channel lost
D/ConnectivityService( 1033): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
W/Settings( 1033): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1033): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1033): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/Nat464Xlat( 1033): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1033): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1033): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1033): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1463): CM callback handler got msg 524292
D/CSLegacyTypeTracker( 1033): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1033): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1033): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/WifiServerServiceExt( 1033): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1033): setSupplicantStateSCANNING
D/ConnectivityService( 1033): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1033): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
V/NetworkPolicy( 1033): [LG_RESTRICTED] !!!isConnected  type  :1
D/LocSvc_java( 1033): Sending msg: 4 arg1:0 arg2:1
E/WifiStateMachine( 1033):  DisconnectedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1033):  ConnectModeState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1033):  DriverStartedState CMD_STOP_SUPPLICANT 0 0
D/ConnectivityService( 1033): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1033): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1033): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/NetworkManagementService( 1033): Removing idletimer
W/Settings( 1033): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/WifiStateMachine( 1033):  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
D/ConnectivityService( 1033): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
E/ConnectivityService( 1033): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/TelephonyNetworkFactory-1( 1840): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/jxcore-log( 5968): Radios toggled
I/jxcore-log( 5968): 
D/TelephonyNetworkFactory-1( 1840):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
V/NetworkPolicy( 1033): [LG_RESTRICTED] !!!isConnected  type  :1
,D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1033): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,D/DSQN    ( 1033): ThreadTCPConnectionCheck DNS fail internet is not possible
D/DSQN    ( 1033): ThreadInternetCheck internet check NOK 
D/LocSvc_java( 1033): getAGpsConnectionInfo connType - 4
D/DSQN    ( 1033): L3_DATA_SERVICE_QUALITY STATUS 0 DataEnabled: false
D/LocSvc_java( 1033): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1033): ignore wifi update if we are not in OPENING or CLOSING
W/ContextImpl( 1033): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 com.android.server.DataServiceQualityMonitor.sendDSqualityIntent:1103 com.android.server.DataServiceQualityMonitor.access$200:55 com.android.server.DataServiceQualityMonitor$ThreadInternetCheck.run:921 <bottom of call stack> 
D/LocSvc_java( 1033): Sending msg: 4 arg1:0 arg2:1
D/LocationManagerService( 1033): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1033): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1033): JNI:system_update. Event-4
D/WifiDataContinuityService( 1033): L3_DATA_SERVICE_QUALITY_ACTION, resultStatus : 0
D/WifiServiceExtension( 1930): isInternetCheckAvailable return false
D/LGWifiP2pService( 1033): InactiveState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1033): P2pEnabledState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1033): stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@50901fe
D/LGWifiP2pService( 1033): P2pDisablingState
D/LGWifiP2pService( 1033): P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1033): p2p socket connection lost
D/LGWifiP2pService( 1033): P2pDisabledState
D/LocSvc_java( 1033): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1033): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1033): ignore wifi update if we are not in OPENING or CLOSING
D/WifiScanningService( 1033): SCAN_AVAILABLE : 1
D/RttService( 1033): SCAN_AVAILABLE : 1
V/WfdStateTracker( 1930): WfdStateTracker handleDirectStateChangedEvent: 0
D/WfdsService( 1930): WifiP2pState is changed : false
D/WifiScanningService( 1033): DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService( 1033): EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1930): WfdsEnabledState: Receive the WFDS_DISABLE message
D/WfdsService( 1930): Set the WFDS Monitor: false
D/WfdsMonitor( 1930): WFDS Monitor is stopped
D/WfdsService( 1930): STATE : WfdsDisabledState - enter
D/CtrlSupplicant( 1930): Received on exit socket, terminate
E/CtrlSupplicant( 1930): wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
D/WfdsMonitor( 1930): Event [CTRL-EVENT-TERMINATING  - connection closed]
D/WfdsMonitor( 1930): WfdsMonitorThread is received the interrupt - closing
W/WfdsSession:Controller( 1930): DefaultState - msg [9441355] is not handled
I/StatusBar.NetworkController( 1463): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1463): mWifiConnected = false, mWifiLevel = 0
W/WfdsService( 1930): DefaultState - msg [9445378] is not handled
D/WIFI    ( 1033): new score ,0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1033):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/WifiStateMachine( 1033):  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiNative-wlan0( 1033): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 6090): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1033): P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1033): DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1033): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1033): doBoolean: SET ps 1
I/StatusBar.NetworkController( 1463): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1463): mWifiConnected = false, mWifiLevel = 0
D/WifiNative-wlan0( 1033): SET ps 1: returned true
D/CommandListener(  314): Clearing all IP addresses on wlan0
D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiNative-p2p0( 1033): doBoolean: TERMINATE
D/WifiNative-p2p0( 1033): TERMINATE: returned true
E/WifiStateMachine( 1033): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1033): useWiFiOffloading() : false
E/WifiStateMachine( 1033): CONFIG_LGE_WLAN_PATH : true
D/WifiHS20( 1033): hidePasspointNotification off =false
W/Settings( 1033): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1033): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1033): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20( 1033): hidePasspointNotification off =false
W/Settings( 1033): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1033): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1033): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
V/WfdStateTracker( 1930): WfdStateTracker handleDirectStateChangedEvent: 6
,I/WifiServerServiceExt( 1033): WIFI_STATE_CHANGED_ACTION [0]
D/DhcpStateMachine( 1033): StoppedState
D/DhcpStateMachine( 1033): StoppedState{ when=-14ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 1033):  SupplicantStoppingState CMD_ON_QUIT 0 0
E/WifiStateMachine( 1033):  DefaultState CMD_ON_QUIT 0 0
I/GoogleURLConnFactory( 2133): Using platform SSLCertificateSocketFactory
,W/ResourcesManager( 7463): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7463): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 7463): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7463): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 7463): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7463): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/TelephonyIcons( 1463): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Uploader( 2133): No account for auth token provided
,D/TelephonyIcons( 1463): null signal icon name: drawable/stat_sys_signal_null
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1033): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1463): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1463): mWifiConnected = false, mWifiLevel = 0
D/Uploader( 2133): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/StatusBar.NetworkController( 1463): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1463): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
W/ContextImpl( 7463): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,V/BluetoothPbapReceiver( 6049): PbapReceiver onReceive 
,D/UsbSettingsReceiver( 7463): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7463): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7463): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7463): [AUTORUN] persist.sys.usb.config = ptp_only,adb
V/BluetoothPbapReceiver( 6049): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6049): ***********state = 13
D/UsbSettingsReceiver( 7463): [AUTORUN] onReceive() : app userid = 0, current userid = 0
V/BluetoothPbapReceiver( 6049): ***********Calling start service!!!! with action = null
V/BluetoothPbapService( 6049): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 6049): state: 13
V/BluetoothPbapService( 6049): Pbap Service closeService in
D/UsbSettingsControl( 7463): [AUTORUN] getUsbConnected() : connected=true
,D/UsbSettingsReceiver( 7463): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 7463): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7463): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7463): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 7463): [AUTORUN] setTetherStatus() : status=false
D/BluetoothManagerService( 1033): Message: 20
,D/BluetoothManagerService( 1033): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@157fa328:true
I/ActivityManager( 1033): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7513 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,V/BluetoothPbapService( 6049): successfully stopped pbap service
V/BluetoothPbapService( 6049): Pbap Service closeService out
V/BluetoothPbapService( 6049): Pbap Service onDestroy
V/BluetoothPbapService( 6049): Pbap Service closeService in
V/BluetoothPbapService( 6049): Pbap Service closeService out
D/LGBluetoothPbapAdapter( 6049): [BTUI] cleanup
D/BluetoothManagerService( 1033): Message: 30
I/ActivityManager( 1033): Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=7530 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,D/BluetoothManagerService( 1033): Message: 30
D/LocalBluetoothProfileManager( 7463): Adding local MAP profile
D/BluetoothMap( 7463): Create BluetoothMap proxy object
D/BluetoothManagerService( 1033): Message: 30
,D/BluetoothManagerService( 1033): Message: 30
D/LocalBluetoothProfileManager( 7463): LocalBluetoothProfileManager construction complete
D/LGBluetoothFeatureConfig( 7463):  get() - isFeatureLoaded : false
,D/LGBluetoothUserBindClient( 7463): [BTUI] initUserBindClient
,W/ContextImpl( 7463): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
W/ResourcesManager( 7530): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/DockEventReceiver( 7463): finishStartingService: stopping service
,D/BluetoothInputDevice( 7463): Proxy object connected
,D/HidProfile( 7463): Bluetooth service connected
D/BluetoothPan( 7463): BluetoothPAN Proxy object connected
D/PanProfile( 7463): Bluetooth service connected
D/BluetoothMap( 7463): Proxy object connected
D/MapProfile( 7463): Bluetooth service connected
D/BluetoothMap( 7463): getConnectedDevices()
D/BluetoothMap( 7463): Bluetooth is Not enabled
D/LGBluetoothUserBindClient( 7463): [BTUI] onServiceConnected
I/ActivityManager( 1033): Killing 6785:com.android.calendar/u0a13 (adj 15): empty #17
D/PluginManager( 7530): init()
,W/libprocessgroup( 1033): failed to open /acct/uid_10013/pid_6785/cgroup.procs: No such file or directory
,E/ActivityThread( 7513): Failed to find provider info for com.lge.lgaccount.provider
,W/LG Account v2.2( 7513): No ProfileInfo entries
I/LG Account v2.2( 7513): isEnabled: false
I/Feature ( 7513): [Lifetracker]ver: 4.21.112(40211120)
I/Feature ( 7513): [Lifetracker]Country: EU
I/Feature ( 7513): [Lifetracker]Operator: OPEN
I/Feature ( 7513): [Lifetracker]Ranking support: false
I/Feature ( 7513): [Lifetracker]Comfort support: false
I/Feature ( 7513): [Lifetracker]Accessory: true
I/Feature ( 7513): [Lifetracker]Health device: true
I/Feature ( 7513): [Lifetracker]Extra Pedometer: false
I/Feature ( 7513): [Lifetracker]Blood glucose device: false
I/Feature ( 7513): [Lifetracker]Device Number: 3
,D/LGBluetoothAuthorization( 7463): [BTUI] cancel All Notification
,D/BluetoothPermissionRequest( 7463): onReceive
D/LGBluetoothAuthorization( 7463): [BTUI] cancel All Notification
,D/LGBluetoothResetSettingReceiver( 7463): return without doing reset settings.
I/ActivityManager( 1033): Killing 6623:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,W/libprocessgroup( 1033): failed to open /acct/uid_10085/pid_6623/cgroup.procs: No such file or directory
,V/BluetoothOppReceiver( 6049): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
D/BluetoothOppNotification( 6049): [BTUI] cancel opp incoming file confirm notification
D/BluetoothOppNotification( 6049): [BTUI] cancel opp active transfer file notification
,V/BluetoothFtpReceiver( 6049): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpReceiver( 6049): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 6049): Ftp Service onStartCommand
V/BluetoothFtpService( 6049): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpService( 6049): Ftp Service closeService
,E/BluetoothFtpService:RfcommSocketAcceptThread( 6049): Shutdown
V/BluetoothFtpService( 6049): successfully stopped ftp service
,V/BluetoothSapReceiver( 6049): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 6049): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 6049): SapReceiver onReceive 
V/BluetoothSapReceiver( 6049): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6049):  Bluetooth Adapter state = 13
V/BluetoothSapReceiver( 6049): Calling SAP service start service with action = null
V/BluetoothFtpService( 6049): Ftp Service onDestroy
V/BluetoothFtpService( 6049): Ftp Service closeService
I/ActivityManager( 1033): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7559 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,V/BluetoothSapService( 6049): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 6049): state: 13
V/BluetoothSapService( 6049): Stopping SAP server process
V/BluetoothSapService( 6049): Sap Service closeSapService in
V/BluetoothSapService( 6049): Close listen Socket : 
V/BluetoothSapService( 6049): Close rfcomm Socket : 
V/BluetoothSapService( 6049): Close sapd  Socket : 
V/BluetoothSapService( 6049): Sap Service closeSapService out
V/BluetoothSapService( 6049): Sap Service onDestroy
V/BluetoothSapService( 6049): Sap Service closeSapService in
V/BluetoothSapService( 6049): Close listen Socket : 
V/BluetoothSapService( 6049): Close rfcomm Socket : 
V/BluetoothSapService( 6049): Close sapd  Socket : 
V/BluetoothSapService( 6049): Sap Service closeSapService out
,I/art     (  344): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 433us total 22.669ms
I/art     (  344): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 403us total 18.323ms
,I/art     (  344): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 406us total 20.650ms
,W/ResourcesManager( 7559): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/ActivityManager( 1033): Killing 6812:com.google.android.talk/u0a72 (adj 15): empty #17
,W/ExternalStrings( 7530): load override strings
W/ExternalStrings( 7530): java.lang.RuntimeException: Unexpected tag, got eat-comment
W/ExternalStrings( 7530): 	at com.mcafee.plugin.af.a(Unknown Source)
W/ExternalStrings( 7530): 	at com.mcafee.plugin.ac.b(Unknown Source)
W/ExternalStrings( 7530): 	at com.mcafee.plugin.ak.d(Unknown Source)
W/ExternalStrings( 7530): 	at com.mcafee.plugin.ak.a(Unknown Source)
W/ExternalStrings( 7530): 	at com.mcafee.app.s.getClassLoader(Unknown Source)
W/ExternalStrings( 7530): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
W/ExternalStrings( 7530): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
W/ExternalStrings( 7530): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
W/ExternalStrings( 7530): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
W/ExternalStrings( 7530): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
W/ExternalStrings( 7530): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ExternalStrings( 7530): 	at android.os.Looper.loop(Looper.java:135)
W/ExternalStrings( 7530): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/ExternalStrings( 7530): 	at java.lang.reflect.Method.invoke(Native Method)
W/ExternalStrings( 7530): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/ExternalStrings( 7530): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/ExternalStrings( 7530): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,D/StatusProvider( 7530): onCreate
W/libprocessgroup( 1033): failed to open /acct/uid_10072/pid_6812/cgroup.procs: No such file or directory
D/AuthorizationBluetoothService( 2133): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/bt-btif ( 6049): ag scb idx 1 not allocated
E/bt-btif ( 6049): BTA AG is already disabled, ignoring ...
,W/bt-l2cap( 6049): L2CAP - L2CA_Deregister() called for PSM: 0x0019
,W/bt-l2cap( 6049): L2CAP - PSM: 0x0019 not found for deregistration
D/bt_hci_bdroid( 6049): cleanup
W/bt-l2cap( 6049): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 6049): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 6049): L2CAP - L2CA_Deregister() called for PSM: 0x001b
I/bt_lpm  ( 6049): LPM is already off!!!
W/bt-l2cap( 6049): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 6049): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 6049): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 6049): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 6049): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 6049): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 6049): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 6049): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 6049): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 6049): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 6049): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 6049): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 6049): L2CAP - PSM: 0x001b not found for deregistration
E/bt-btif ( 6049): bta_gattc_deregister Deregister Failedm unknown client cif
I/bt_userial_mct( 6049): exiting userial_read_thread
D/bt_userial_mct( 6049): Leaving userial_evt_read_thread()
D/bt_userial_mct( 6049): userial_close_reader Joined userial reader thread: 0
I/bt_vendor( 6049): hw_epilog_process
D/bt_hci_bdroid( 6049): cleanup Finalizing cleanup
D/bt_userial_mct( 6049): userial_close
E/bt_userial_mct( 6049): pthread_join() FAILED result:3
I/bt_vendor( 6049): bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
V/Signer  ( 7530): override build config not found
D/Signer  ( 7530): value of property debug is false
D/DSQN    ( 1033): EVENT_INTERNET_CHECK_ENABLE received
,D/LGMDMWrapper( 7530): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
,D/LGMDMWrapper( 7530): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
D/LGMDMWrapper( 7530): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
D/LGMDMWrapper( 7530): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
,D/LGMDMWrapper( 7530): Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
D/LGMDMWrapper( 7530): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
D/LGMDMWrapper( 7530): Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
D/LGMDMWrapper( 7530): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
D/LGMDMWrapper( 7530): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
,D/LGMDMWrapper( 7530): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
D/LGMDMWrapper( 7530): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
D/LGMDMWrapper( 7530): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
D/LGMDMWrapper( 7530): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
,V/LGMDMManager( 7530): Create singleton instance
D/bt_hci_bdroid( 6049): set_power 0
I/bt_vendor( 6049): bt-vendor : BT_VND_OP_POWER_CTRL: Off
I/bt_vendor( 6049): bluetooth satus is on
I/bt_vendor( 6049): bt-vendor : resetting BT status
I/bt_vendor( 6049): Starting hciattach daemon
I/bt_vendor( 6049): try to set false
I/bt_vendor( 6049): Starting hciattach daemon
,I/bt_vendor( 6049): try to set false
I/bt_vendor( 6049): cleanup
I/GKI_LINUX( 6049): gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 6049): GKI_exit_task 0 done
I/GKI_LINUX( 6049): GKI_shutdown(): task [BTU] terminated
D/BluetoothAdapterState( 6049): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/HeadsetService( 6049): Received stop request...Stopping profile...
I/LGBluetoothHfpAdapter( 6049): [BTUI] LGBluetoothHfpAdapter cleanup
W/LGBluetoothHeadsetServiceJni( 6049): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 6049): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b68e808
,D/HeadsetStateMachine( 6049): Exit Disconnected: -1
D/BluetoothHeadset( 1033): Proxy object disconnected
D/AudioService( 1033): onServiceDisconnected: Bluetooth profile: 1
D/BluetoothHeadset( 1840): Proxy object disconnected
D/BluetoothHeadset( 1840): Proxy object disconnected
D/BluetoothHeadset( 1840): Proxy object disconnected
D/A2dpService( 6049): Received stop request...Stopping profile...
D/A2dpStateMachine( 6049): Exit Disconnected: -1
D/LGBluetoothAvrcpQcomAdapter( 6049): [BTUI] cleanup
D/LGBluetoothA2dpAdapter( 6049): [BTUI] LGBluetoothA2dpAdapter cleanup
,W/LGBluetoothA2dpServiceJni( 6049): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 6049): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b68e808
D/BluetoothA2dp( 1033): Proxy object disconnected
D/AudioService( 1033): onServiceDisconnected: Bluetooth profile: 2
D/BluetoothAdapterState( 6049): Stopping profile services that were post enabled
D/HeadsetStateMachine( 6049): Unbinding service...
D/HeadsetPhoneState( 6049): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 6049): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetPhoneState( 6049): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 6049): [BTUI] listenForMultiSimPhoneState : start = false
W/BluetoothHeadsetServiceJni( 6049): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 6049): Cleaning up Bluetooth Handsfree callback object
I/LGBluetoothHfpAdapter( 6049): [BTUI] LGBluetoothHfpAdapter cleanup
D/HidService( 6049): Received stop request...Stopping profile...
D/BluetoothAdapterService( 6049): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b68e808
D/HealthService( 6049): Received stop request...Stopping profile...
D/BluetoothAdapterService( 6049): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b68e808
D/BluetoothInputDevice( 7463): Proxy object disconnected
D/PanService( 6049): Received stop request...Stopping profile...
D/HidProfile( 7463): Bluetooth service disconnected
D/BluetoothAdapterService( 6049): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b68e808
D/BluetoothPan( 7463): BluetoothPAN Proxy object disconnected
D/PanProfile( 7463): Bluetooth service disconnected
D/BtGatt.DebugUtils( 6049): handleDebugAction() action=null
D/BtGatt.GattService( 6049): Received stop request...Stopping profile...
D/BtGatt.GattService( 6049): stop()
D/BtGatt.AdvertiseManager( 6049): advertise clients cleared
D/BluetoothAdapterService( 6049): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b68e808
D/BluetoothMapService( 6049): Received stop request...Stopping profile...
D/BluetoothMapService( 6049): stop()
D/BluetoothMapEmailAppObserver( 6049): deinitObservers()
D/BluetoothMapEmailAppObserver( 6049): removeReceiver()
D/BluetoothAdapterService( 6049): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b68e808
D/BluetoothMap( 7463): Proxy object disconnected
D/MapProfile( 7463): Bluetooth service disconnected
,I/BluetoothA2dpServiceJni( 6049): cleanupNative
I/GKI_LINUX( 6049): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 6049): GKI_exit_task 2 done
I/GKI_LINUX( 6049): GKI_shutdown(): task [A2DP-MEDIA] terminated
W/BluetoothHidServiceJni( 6049): Cleaning up Bluetooth HID Interface...
W/BluetoothHidServiceJni( 6049): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 6049): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 6049): Cleaning up Bluetooth Health object
W/LGBluetoothHealthServiceJni( 6049): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 6049): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 6049): Cleaning up Bluetooth PAN callback object
V/BluetoothMapService( 6049): Handler(): got msg=4
D/BluetoothMapService( 6049): MAP Service closeService in
D/LGBluetoothMapAdapter( 6049): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 6049): MAP Service closeService out
D/BluetoothAdapterState( 6049): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 6049): Setting state to 10
I/BluetoothAdapterState( 6049): Bluetooth adapter state changed: 13-> 10
D/BluetoothManagerService( 1033): Message: 60
D/BluetoothManagerService( 1033): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService( 1033): Broadcasting onBluetoothStateChange(false) to 9 receivers.
D/BluetoothHeadset( 1033): onBluetoothStateChange: up=false
I/BluetoothAdapterState( 6049): Entering OffState
D/BluetoothPbap( 7463): onBluetoothStateChange: up=false
D/BluetoothMap( 7463): onBluetoothStateChange: up=false
D/LGMDMWrapper( 7530): LG MDM library v4.0.0 is available on this device.
D/BluetoothMapService( 6049): cleanup()
D/BluetoothMapService( 6049): MAP Service closeService in
D/BluetoothHeadset( 1840): onBluetoothStateChange: up=false
D/LGBluetoothMapAdapter( 6049): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 6049): MAP Service closeService out
D/BluetoothInputDevice( 7463): onBluetoothStateChange: up=false
D/BluetoothA2dp( 1033): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1840): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1840): onBluetoothStateChange: up=false
D/BluetoothPan( 7463): onBluetoothStateChange on: false
D/BluetoothManagerService( 1033): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService( 1033): Broadcasting onBluetoothServiceDown() to 8 receivers.
,D/BluetoothManagerService( 1033): Calling onQBluetoothServiceDown callbacks
D/BluetoothManagerService( 1033): Broadcasting onQBluetoothServiceDown() to 0 receivers.
D/BluetoothManagerService( 1033): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@2e31a210 mBinding = false
D/BluetoothManagerService( 1033): Sending unbind request.
D/BluetoothManagerService( 1033): Bluetooth State Change Intent: 13 -> 10
D/LGBluetoothAPIService( 1930): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/LGBluetoothAPIService( 1930): Message: 2
D/LGBluetoothAPIService( 1930): unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@470e258 mBinding = false
D/LGBluetoothAPIService( 1930): Sending unbind request.
I/[SystemUI]BluetoothHandler( 1463): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
D/LGBluetoothFeatureConfig( 7463): isPrivacyLogsEnabled : true
E/LGBluetoothEventManager( 7463): [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
D/LGBluetoothEventManager( 7463): [BTUI] clear device connection state
W/ContextImpl( 7463): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
D/BluetoothAdapter( 1463): 739032224: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1463): 739032224: getState() :  mService = null. Returning STATE_OFF
I/GKI_LINUX( 6049): gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 6049): GKI_exit_task 1 done
,I/GKI_LINUX( 6049): GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 6049): cleanupNative: return from cleanup
I/art     ( 6049): --- WEIRD: removing null entry 246
W/art     ( 6049): JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
W/LGBluetoothServiceJni( 6049): Cleaning up Bluetooth Service callback object
D/LGBluetoothSettingsDBObserver( 6049): [BTUI] unregister observer for LG device name DB
D/DockEventReceiver( 7463): finishStartingService: stopping service
I/art     ( 6049): System.exit called, status: 0
I/AndroidRuntime( 6049): VM exiting with result code 0, cleanup skipped.
V/AudioFlinger(  318): 6049 died, releasing its sessions
V/AudioFlinger(  318):  pid 1840 @ 0
V/AudioFlinger(  318):  pid 3284 @ 1
V/AudioFlinger(  318):  pid 3284 @ 2
D/LGBluetoothUserBindClient( 7463): [BTUI] onServiceDisconnected
,D/PostponalbeReceiver( 7530): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 7530): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,I/ActivityManager( 1033): Process com.android.bluetooth (pid 6049) has died
W/ActivityManager( 1033): Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,I/ActivityManager( 1033): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7599 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/ActivityManager( 1033): Killing 6880:com.android.providers.calendar/u0a14 (adj 15): empty #17
,W/ActivityThread( 7530): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/art     ( 1033): Explicit concurrent mark sweep GC freed 139770(6MB) AllocSpace objects, 8(896KB) LOS objects, 33% free, 44MB/66MB, paused 1.220ms total 95.999ms
,W/libprocessgroup( 1033): failed to open /acct/uid_10014/pid_6880/cgroup.procs: No such file or directory
D/BluetoothPermissionRequest( 7463): onReceive
D/LGBluetoothUtils( 7463): [BTUI] FileNotFound: readProperty
D/BluetoothDiscoverableTimeoutReceiver( 7463): cancelDiscoverableAlarm(): Enter
,D/LGBluetoothResetSettingReceiver( 7463): return without doing reset settings.
I/ActivityManager( 1033): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7621 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,I/PCSuite ( 7599): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7599): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7599): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7463): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
W/ResourcesManager( 7621): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager( 7621): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7621): Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 7621): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/BluetoothAdapterApp( 7621): Loading JNI Library
,D/LgDataFeature( 7463): LgDataFeature() Constructor: none
D/LgDataFeature( 7463): LgDataFeature() Constructor Done, null
D/WiFiOffLoadBroadcast( 7463): MCCMNC not supported: null
,D/QRemote ( 6245): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6245): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6245): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 7530): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 7530): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,I/PCSuite ( 7599): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7599): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7599): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/BluetoothAdapterApp( 7621): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@18041869 Instance Count = 1
V/WiFiOffLoadBroadcast( 7463): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/BluetoothAdapterApp( 7621): onCreate
D/WiFiOffLoadBroadcast( 7463): MCCMNC not supported: null
D/QRemote ( 6245): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6245): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6245): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/LgDataFeature( 7530): LgDataFeature() Constructor: none
D/LgDataFeature( 7530): LgDataFeature() Constructor Done, null
D/PostponalbeReceiver( 7530): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 7530): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
I/PCSuite ( 7599): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7599): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7599): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7463): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/ProfileConfigQcom( 7621): [BTUI] HeadsetService is supported
D/ProfileConfigQcom( 7621): Adding HeadsetService
D/ProfileConfigQcom( 7621): [BTUI] A2dpService is supported
D/ProfileConfigQcom( 7621): Adding A2dpService
D/ProfileConfigQcom( 7621): [BTUI] HidService is supported
D/ProfileConfigQcom( 7621): Adding HidService
,D/ProfileConfigQcom( 7621): [BTUI] HealthService is supported
D/ProfileConfigQcom( 7621): Adding HealthService
D/LGBluetoothFeatureConfig( 7621): isSupportPan() :  mTargetOp=OPEN
,D/ProfileConfigQcom( 7621): [BTUI] PanService is supported
D/ProfileConfigQcom( 7621): Adding PanService
D/ProfileConfigQcom( 7621): [BTUI] GattService is supported
D/ProfileConfigQcom( 7621): Adding GattService
D/ProfileConfigQcom( 7621): [BTUI] BluetoothMapService is supported
D/ProfileConfigQcom( 7621): Adding BluetoothMapService
D/ProfileConfigQcom( 7621): [BTUI] HeadsetClientService is NOT supported
D/LGBluetoothOppAdapter( 7621): [BTUI] getInstance : create [LGBluetoothOppAdapter]
D/WiFiOffLoadBroadcast( 7463): MCCMNC not supported: null
D/QRemote ( 6245): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/LGBluetoothUserBindClient( 7463): [BTUI] onServiceConnected
D/QRemote ( 6245): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6245): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/LGMDMManagerInternal( 7621): Create singleton instance
D/PostponalbeReceiver( 7530): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 7530): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,V/WiFiOffLoadBroadcast( 7463): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7463): MCCMNC not supported: null
D/QRemote ( 6245): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6245): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6245): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 7530): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,W/ContextImpl( 7530): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
I/PCSuite ( 7599): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7599): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7599): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7463): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7463): MCCMNC not supported: null
D/QRemote ( 6245): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6245): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6245): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 7530): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 7530): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
I/PCSuite ( 7599): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7599): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7599): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7463): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7463): MCCMNC not supported: null
D/QRemote ( 6245): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6245): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6245): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
W/ContextImpl( 7530): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
,I/ActivityManager( 1033): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7648 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
I/ActivityManager( 1033): Killing 7014:com.google.android.gms:car/u0a5 (adj 15): empty #17
,V/BluetoothFtpReceiver( 7621): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothSapReceiver( 7621): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 7621): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 7621): SapReceiver onReceive 
V/BluetoothSapReceiver( 7621): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 7621):  Bluetooth Adapter state = 10
W/libprocessgroup( 1033): failed to open /acct/uid_10005/pid_7014/cgroup.procs: No such file or directory
D/LGBluetoothProfileConnectionReceiver_EasySetting( 7559): [BTUI] STATE_OFF : reset connected device information EasySettings
I/ActivityManager( 1033): Killing 7093:com.lge.appbox.client/u0a11 (adj 15): empty #17
,D/SiteAdvisor( 7530): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
D/SiteAdvisor( 7530): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
D/SiteAdvisor( 7530): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
,D/SiteAdvisor( 7530): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
,D/SiteAdvisor( 7530): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
I/SiteAdvisor( 7530): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
D/SiteAdvisor( 7530): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
D/SiteAdvisor( 7530): com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
,D/AuthorizationBluetoothService( 2133): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
W/libprocessgroup( 1033): failed to open /acct/uid_10011/pid_7093/cgroup.procs: No such file or directory
D/PCSuite ( 7599): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7463): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,D/WiFiOffLoadBroadcast( 7463): MCCMNC not supported: null
D/PostponalbeReceiver( 7530): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
,D/PostponalbeReceiver( 7530): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
W/FormManager( 7648): Network not available. Please check & try again.
D/PostponalbeReceiver( 7530): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
D/PostponalbeReceiver( 7530): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
D/PostponalbeReceiver( 7530): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
D/PostponalbeReceiver( 7530): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
,V/FormManager( 7648): Network unavailable.
,V/FormManager( 7648): Network unavailable.
I/ActivityManager( 1033): Killing 7129:com.android.contacts/u0a19 (adj 15): empty #17
,W/libprocessgroup( 1033): failed to open /acct/uid_10019/pid_7129/cgroup.procs: No such file or directory
,I/wpa_supplicant( 6090): p2p0: CTRL-EVENT-TERMINATING 
,I/wpa_supplicant( 6090): monitor socket send errors count : 1
I/wpa_supplicant( 6090): CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1930-2\x00 that cannot receive messages
,D/WifiMonitor( 1033): Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
D/WifiMonitor( 1033): Dropping event because (p2p0) is stopped
W/wpa_supplicant( 6090): USIM:  scard_deinit function
D/WifiMonitor( 1033): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1033): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1033):  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=602017  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: DISCONNECTED
E/WifiStateMachine( 1033):  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=602019  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: DISCONNECTED
I/wpa_supplicant( 6090): wlan0: CTRL-EVENT-TERMINATING 
D/WifiMonitor( 1033): Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
E/WifiMonitor( 1033): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-TERMINATING 
D/WifiMonitor( 1033): Disconnecting from the supplicant, no more events
E/WifiStateMachine( 1033):  SupplicantStoppingState SUP_DISCONNECTION_EVENT 30 0
,D/WfdsService( 1930): Supplicant Connection state is changed : false
,D/WfdsService( 1930): DefaultState - WIFI_SUPPLICANT_DISCONNECTED
D/WfdsService( 1930): Set the WFDS Monitor: false
D/WfdsMonitor( 1930): WFDS Monitor is stopped
D/WifiOffDelayIfNotUsed( 1033): stopMonitoring
E/WifiStateMachine( 1033): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1033): useWiFiOffloading() : false
E/WifiStateMachine( 1033): CONFIG_LGE_WLAN_PATH : true
D/LGDMClient( 3164): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 3164): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/WifiServerServiceExt( 1033): WIFI_STATE_CHANGED_ACTION [1]
I/WifiServerServiceExt( 1033): batteryPsActivateMsgHandler : state:0 event:1
I/WifiServerServiceExt( 1033): batteryPsActivateMsgHandler : this is not treated
V/WfdStateTracker( 1930): WfdStateTracker handleDirectStateChangedEvent: 0
W/Settings( 1805): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/ContextImpl( 3164): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 3164): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/LGDMClient( 3164): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,I/PCSuite ( 7599): [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
D/PCSuite ( 7599): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7599): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/LGDMClient( 3164): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,D/LGDMClient( 3164): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/WiFiOffLoadBroadcast( 7463): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,D/WiFiOffLoadBroadcast( 7463): MCCMNC not supported: null
W/FormManager( 7648): Network not available. Please check & try again.
,V/FormManager( 7648): Network unavailable.
V/FormManager( 7648): Network unavailable.
,D/PowerManagerServiceEx( 1033): acquireWakeLockInternal: lock=575145497, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1033
,V/AlarmManager( 1033): ELAPSED_WAKEUP set : Alarm{18d7ad1e type 2 when 602275 com.google.android.gms} when 602275
,D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1033): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,D/[Concierge]Service( 2612): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1033): releaseWakeLockInternal: lock=575145497 [*alarm*], flags=0x0
,E/WifiStateMachine( 1033):  InitialState CMD_RSSI_POLL 1 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1559399601] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1033):  DefaultState CMD_RSSI_POLL 1 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1559399599] gl rssi=-64 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/ConnectivityService( 1033): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1033): MasterInitialState.processMessage what=3
,D/GpsLocationProvider( 1033): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService( 1033): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/PostponalbeReceiver( 7530): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,D/Tethering( 1033): MasterInitialState.processMessage what=3
I/NetworkMonitor( 5195): type=WIFI subType= reason=null isConnected=false
,I/NetworkMonitor( 5195): type=WIFI subType= reason=null isConnected=false
,D/GpsLocationProvider( 1033): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1033): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1033): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager( 1033): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7693 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 7530): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/AppUp4:AppBoxCP( 7693): onCreate
,W/AppUp4:DB( 7693):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7693):  setFingerPrint start
I/AppUp4:DB( 7693):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 7693):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7693):  SDK version = 21
I/AppUp4:DB( 7693):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7693): AppBoxApplication onCreate()
,I/NetworkStateForAutoUpdateMonitor( 7693): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7693): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7693): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7693): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7693): onReceive
,D/LgDataFeature( 7693): LgDataFeature() Constructor: none
,D/LgDataFeature( 7693): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7693): Context : android.app.ReceiverRestrictedContext@7a289ab
D/AppUp4:CustFacade( 7693): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7693): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7693): begin check event
I/AppUp4:CustModeStarterReceiver( 7693): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7693): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7693): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7693): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7693): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1033): Killing 7149:com.android.gallery3d/u0a27 (adj 15): empty #17
,W/libprocessgroup( 1033): failed to open /acct/uid_10027/pid_7149/cgroup.procs: No such file or directory
,D/LGDMClient( 3164): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3164): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 3164): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 3164): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,D/LGDMClient( 3164): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/LGDMClient( 3164): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 3164): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,I/ActivityManager( 1033): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7735 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,W/ResourcesManager( 7735): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7735): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7735): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7735): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/LGEmail ( 7735): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7735): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,W/ResourceType( 7735): No package identifier when getting value for resource number 0x00000000
,D/LgDataFeature( 7735): LgDataFeature() Constructor: none
,D/LgDataFeature( 7735): LgDataFeature() Constructor Done, null
,D/eas_req ( 7735): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,V/FormManager( 7648): Network unavailable.
,V/FormManager( 7648): Network unavailable.
W/FormManager( 7648): Network not available. Please check & try again.
I/HubEmail( 7735): JNI_OnLoad()
,I/HubEmail( 7735): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7735): registerNatives()
I/HubEmail( 7735): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7735): registerNativeMethods()
I/HubEmail( 7735): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7735): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
W/Settings( 7735): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager( 1033): Killing 7175:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
I/LgeMiscReceiver( 3284): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3284): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3284): networkInfo.isConnected() = false
W/libprocessgroup( 1033): failed to open /acct/uid_10080/pid_7175/cgroup.procs: No such file or directory
,I/ActivityManager( 1033): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7764 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1033): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7785 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,I/ActivityManager( 1033): Killing 7051:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
,W/libprocessgroup( 1033): failed to open /acct/uid_10005/pid_7051/cgroup.procs: No such file or directory
,I/ActivityManager( 1033): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7802 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1033): Killing 7192:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,W/libprocessgroup( 1033): failed to open /acct/uid_10097/pid_7192/cgroup.procs: No such file or directory
,I/art     ( 7802): Almond Protected OAT
,D/WeatherApplication( 7802): removeAccount
,D/WeatherApplication( 7802): Account.length = 0
,E/WeatherApplication( 7802): OPERATOR:OPEN
D/WeatherAncestor( 7802): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:35:16
,D/Weather.Utils( 7802): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7802): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7802): 2 : This is isUpdating : false
,D/WeatherAncestor( 7802): connectivity changed - connection : true
D/WeatherService( 7802): 2 : isServiceAlived():false forecastCache:null
D/ForecastDataCache( 7802): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7802): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7802): 2 : Cache is not up-to-date, count: 0
,D/Weather_cast( 7802): 2 : isUpdateNeedForAlarm : no city return false
,D/WeatherAncestor( 7802): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:35:16
,I/ActivityManager( 1033): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7825 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1033): Killing 6956:com.android.vending/u0a44 (adj 15): empty #17
,D/LGWifiP2pService( 1033): P2pDisabledState{ when=-2ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1033): DefaultState{ when=-3ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine( 1033):  InitialState CMD_STOP_SUPPLICANT_FAILED 1 0
E/WifiStateMachine( 1033):  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
W/libprocessgroup( 1033): failed to open /acct/uid_10044/pid_6956/cgroup.procs: No such file or directory
,E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7825): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7825): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7825): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7825): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/WebViewFactory( 7825): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7825): Loading: webviewchromium
,I/LibraryLoader( 7825): Time to load native libraries: 11 ms (timestamps 5533-5544)
I/LibraryLoader( 7825): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7825): Binding Chromium to main looper Looper (main, tid 1) {fbe7ae4}
,I/LibraryLoader( 7825): Expected native library version number "",actual native library version number ""
I/chromium( 7825): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7825): Initializing chromium process, renderers=0
W/art     ( 7825): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7825): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7825): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 7825): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
V/AudioPolicyService(  318): registerClient() client 0xb1427580, uid 10093
W/AudioManagerAndroid( 7825): Requires BLUETOOTH permission
,I/Adreno-EGL( 7825): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7825): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7825): Build Date: 12/12/14 금
I/Adreno-EGL( 7825): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7825): Remote Branch: 
I/Adreno-EGL( 7825): Local Patches: 
I/Adreno-EGL( 7825): Reconstruct Branch: 
I/NSApplication( 7825): Starting up...
,I/ActivityManager( 1033): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7887 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1033): Killing 6743:com.lge.clock/u0a10 (adj 15): empty #17
W/libprocessgroup( 1033): failed to open /acct/uid_10010/pid_6743/cgroup.procs: No such file or directory
,W/ResourcesManager( 7887): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/iu.Environment( 2390): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 2390): num queued entries: 0
I/iu.UploadsManager( 2390): num updated entries: 0
I/iu.SyncManager( 2390): NEXT; no task
D/ChimeraCfgMgr( 2390): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PostponalbeReceiver( 7530): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 7530): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/NetworkStateForAutoUpdateMonitor( 7693): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7693): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7693): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7693): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7693): onReceive
,D/AppUp4:CustFacade( 7693): Context : android.app.ReceiverRestrictedContext@7a289ab
D/AppUp4:CustFacade( 7693): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7693): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7693): begin check event
I/AppUp4:CustModeStarterReceiver( 7693): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 3164): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3164): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 3164): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 3164): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/LGDMClient( 3164): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/LGDMClient( 3164): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 3164): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/eas_req ( 7735): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
I/GLSActivity( 2133): [ac] getting account id
,W/Settings( 7735): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/GLSUser ( 2133): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
,I/LgeMiscReceiver( 3284): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3284): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3284): networkInfo.isConnected() = false
W/FormManager( 7648): Network not available. Please check & try again.
D/WeatherAncestor( 7802): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:35:17
,V/FormManager( 7648): Network unavailable.
D/Weather.Utils( 7802): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7802): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7802): 2 : This is isUpdating : false
D/WeatherAncestor( 7802): connectivity changed - connection : true
D/WeatherService( 7802): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@308d6ba1
V/FormManager( 7648): Network unavailable.
D/ForecastDataCache( 7802): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7802): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7802): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7802): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7802): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:35:17
D/ChimeraCfgMgr( 2390): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/art     ( 3319): Explicit concurrent mark sweep GC freed 4639(341KB) AllocSpace objects, 0(0B) LOS objects, 36% free, 27MB/43MB, paused 545us total 40.701ms
,V/AlarmManager( 1033): ELAPSED_WAKEUP set : Alarm{3d174dbf type 2 when 606869 com.google.android.gms} when 606869
,D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1033): DNSproblemNotiEnabled is disabled ignore DNS fail CB,
I/GAV4    ( 7825): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager( 1033): Killing 6456:com.google.android.apps.books/u0a54 (adj 15): empty #17
,W/libprocessgroup( 1033): failed to open /acct/uid_10054/pid_6456/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 617888329508; DSPS: 20388315; Offset : -4328160897
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 637890366219; DSPS: 21043742; Offset : -4328168890
,V/AlarmManager( 1033): ELAPSED_WAKEUP set : Alarm{2bd963ea type 2 when 639803 android} when 639803
,D/PowerManagerServiceEx( 1033): acquireWakeLockInternal: lock=575145497, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1033
,D/[Concierge]Service( 2612): onStartCommand(). Type : 9
,I/[SystemUI]TimeTickManager( 1463): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1463): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1463): called onTimeUpdated()
I/[SystemUI]Clock( 1463): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1463): called onTimeUpdated()
I/[SystemUI]DateView( 1463): called onTimeUpdated()
I/[SystemUI]DateView( 1463): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1463): handleTimeUpdate
D/PowerManagerServiceEx( 1033): releaseWakeLockInternal: lock=575145497 [*alarm*], flags=0x0
,I/ActivityManager( 1033): Killing 7513:com.lge.lifetracker/u0a37 (adj 15): empty #17
,W/libprocessgroup( 1033): failed to open /acct/uid_10037/pid_7513/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 657892535118; DSPS: 21699173; Offset : -4328166635
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 677894221985; DSPS: 22354588; Offset : -4328158261
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 697896376977; DSPS: 23010019; Offset : -4328169939
,I/[SystemUI]TimeTickManager( 1463): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1463): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1463): called onTimeUpdated()
I/[SystemUI]Clock( 1463): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1463): called onTimeUpdated()
,I/[SystemUI]DateView( 1463): called onTimeUpdated()
I/[SystemUI]DateView( 1463): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1463): handleTimeUpdate
D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 717898526917; DSPS: 23665449; Offset : -4328156151
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 737900670296; DSPS: 24320879; Offset : -4328149289
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 757902789140; DSPS: 24976309; Offset : -4328166623
,I/[SystemUI]TimeTickManager( 1463): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1463): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1463): called onTimeUpdated()
,I/[SystemUI]Clock( 1463): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1463): called onTimeUpdated()
I/[SystemUI]DateView( 1463): called onTimeUpdated()
I/[SystemUI]DateView( 1463): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1463): handleTimeUpdate
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 777904672989; DSPS: 25631730; Offset : -4328144347
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 797906531939; DSPS: 26287151; Offset : -4328146969
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 817908605161; DSPS: 26942579; Offset : -4328148917
,I/[SystemUI]TimeTickManager( 1463): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1463): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1463): called onTimeUpdated()
,I/[SystemUI]Clock( 1463): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1463): called onTimeUpdated()
,I/[SystemUI]DateView( 1463): called onTimeUpdated()
I/[SystemUI]DateView( 1463): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1463): handleTimeUpdate
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 837920480362; DSPS: 27598328; Offset : -4328145001
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 857922560510; DSPS: 28253756; Offset : -4328140100
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 877924362117; DSPS: 28909176; Offset : -4328169575
,I/[SystemUI]TimeTickManager( 1463): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1463): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1463): called onTimeUpdated()
I/[SystemUI]Clock( 1463): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1463): called onTimeUpdated()
,I/[SystemUI]DateView( 1463): called onTimeUpdated()
,I/[SystemUI]DateView( 1463): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1463): handleTimeUpdate
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 897926248255; DSPS: 29564597; Offset : -4328145061,
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 917928349028; DSPS: 30220026; Offset : -4328149922
,I/[SystemUI]LGPowerUI( 1463): onReceive = com.lge.android.intent.action.BATTERYEX
,I/[SystemUI]LGPowerUI( 1463): On Skip Timer : true
D/WifiController( 1033): battery changed pluggedType: 2
,D/LEDHandler( 1930): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1930): Battery Level Remaining: 100%
D/LEDHandler( 1930): Battery Temp: 279, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1463): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 279
I/[SystemUI]LGPowerUI( 1463): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1463): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3164): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3164): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 937930542251; DSPS: 30875458; Offset : -4328153939
,I/[SystemUI]TimeTickManager( 1463): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1463): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1463): called onTimeUpdated()
,I/[SystemUI]Clock( 1463): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1463): called onTimeUpdated()
I/[SystemUI]DateView( 1463): called onTimeUpdated()
I/[SystemUI]DateView( 1463): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1463): handleTimeUpdate
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 957932428857; DSPS: 31530880; Offset : -4328159554
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 977934472079; DSPS: 32186307; Offset : -4328160904
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 997936325456; DSPS: 32841728; Offset : -4328169257
,I/[SystemUI]TimeTickManager( 1463): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1463): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1463): called onTimeUpdated()
,I/[SystemUI]Clock( 1463): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1463): called onTimeUpdated()
,I/[SystemUI]DateView( 1463): called onTimeUpdated()
,I/[SystemUI]DateView( 1463): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1463): handleTimeUpdate
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 1017938313157; DSPS: 33497153; Offset : -4328165015
,I/[SystemUI]LGPowerUI( 1463): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1463): On Skip Timer : true
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 1037940232473; DSPS: 34152576; Offset : -4328168334
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 1057942335903; DSPS: 34808005; Offset : -4328170616
,I/[SystemUI]TimeTickManager( 1463): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1463): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1463): called onTimeUpdated()
,I/[SystemUI]Clock( 1463): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1463): called onTimeUpdated()
,I/[SystemUI]DateView( 1463): called onTimeUpdated()
I/[SystemUI]DateView( 1463): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1463): handleTimeUpdate
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 1077944356311; DSPS: 35463431; Offset : -4328164498
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 1097946443491; DSPS: 36118859; Offset : -4328152331
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 1117949271556; DSPS: 36774312; Offset : -4328162557
,I/[SystemUI]TimeTickManager( 1463): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1463): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1463): called onTimeUpdated()
,I/[SystemUI]Clock( 1463): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1463): called onTimeUpdated()
,I/[SystemUI]DateView( 1463): called onTimeUpdated()
I/[SystemUI]DateView( 1463): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1463): handleTimeUpdate
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 1137951457486; DSPS: 37429743; Offset : -4328143297
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 1157953295708; DSPS: 38085164; Offset : -4328166569
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 1177954923617; DSPS: 38740577; Offset : -4328156196
,I/[SystemUI]TimeTickManager( 1463): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1463): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1463): called onTimeUpdated()
I/[SystemUI]Clock( 1463): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1463): called onTimeUpdated()
I/[SystemUI]DateView( 1463): called onTimeUpdated()
I/[SystemUI]DateView( 1463): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1463): handleTimeUpdate
D/PowerManagerServiceEx( 1033): acquireWakeLockInternal: lock=575145497, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1033
,I/ActivityManager( 1033): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=8015 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,D/[Concierge]Service( 2612): onStartCommand(). Type : 9
,I/art     (  344): Explicit concurrent mark sweep GC freed 708(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 439us total 50.247ms
,I/art     (  344): Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 365us total 34.053ms
,I/art     (  344): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 293us total 30.158ms
,I/DigitalAppWidgetProvider( 8015): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 8015): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@f1b861c
D/PowerManagerServiceEx( 1033): releaseWakeLockInternal: lock=575145497 [*alarm*], flags=0x0
I/ActivityManager( 1033): Killing 6919:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
I/QRemote ( 6245): [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
W/System.err( 6245): android.os.DeadObjectException
W/System.err( 6245): 	at android.os.BinderProxy.transactNative(Native Method)
,W/System.err( 6245): 	at android.os.BinderProxy.transact(Binder.java:496)
,W/System.err( 6245): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 6245): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
W/System.err( 6245): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
,W/System.err( 6245): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 6245): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6245): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6245): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6245): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 6245): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6245): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6245): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 6245): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 6245): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 6245): android.os.DeadObjectException
W/System.err( 6245): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6245): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6245): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 6245): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
W/System.err( 6245): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 6245): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 6245): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6245): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6245): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6245): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 6245): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6245): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6245): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 6245): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 6245): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/QRemote ( 6245): [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
W/libprocessgroup( 1033): failed to open /acct/uid_1000/pid_6919/cgroup.procs: No such file or directory
W/ActivityManager( 1033): Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,D/QRemote ( 6245): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
I/QRemote ( 6245): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
I/ActivityManager( 1033): Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=8051 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/QRemote ( 6245): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,D/UEI.SmartControl( 8051): Quickset Services start...
,I/UEI.SmartControl( 8051): Manufacture = LGE
D/UEI.SmartControl( 8051): Id = LGNevo
D/UEI.SmartControl( 8051): File observer start...
E/UEI.SmartControl( 8051): IR Port is disabled: false
D/UEI.SmartControl( 8051): Starting file observer...
D/UEI.SmartControl( 8051): Extracting JNI libs...
D/UEI.SmartControl( 8051): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 8051): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 8051): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 8051): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 8051): --- Selecting new region: 6
,I/UEI.SmartControl( 8051): Model = LG-D855
D/UEI.SmartControl( 8051): QS Service created
,I/art     ( 1033): Explicit concurrent mark sweep GC freed 48083(2MB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 1.532ms total 106.656ms
,I/UEI.SmartControl( 8051): Service initServices...
,D/UEI.SmartControl( 8051): QS start get config
D/UEI.SmartControl( 8051): Loading JNI Libs...
,I/UEI.SmartControl( 8051): Supports setup maps: true
,D/UEI.SmartControl( 8051): QS start statue = true Error code = 0
I/UEI.SmartControl( 8051): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 8051): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 8051): ### init IR Blaster...
D/serial_port( 8051): Configuring serial port
E/UEI.SmartControl( 8051): UEIBLaster setting for 616
I/UEI.SmartControl( 8051): Setting serial record hearder size = 2
I/UEI.SmartControl( 8051): configuring settings for MAXQ616
I/UEI.SmartControl( 8051): Get version...
D/UEI.SmartControl( 8051): serial port data available: 21
,D/UEI.SmartControl( 8051): MAXQ616 A2-X4 software.
,I/UEI.SmartControl( 8051): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 8051): QS saving settings...
D/UEI.SmartControl( 8051): IR Blaster version: 25672567
D/UEI.SmartControl( 8051): serial port data available: 4
,I/UEI.SmartControl( 8051): Device manager: loading config....
,W/ContextImpl( 8051): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
D/UEI.SmartControl( 8051): ----------- loading internal config...
E/UEI.SmartControl( 8051): Services init done
D/UEI.SmartControl( 8051): QS Service init finished
D/UEI.SmartControl( 8051): QS Service version name: 2.1.91
D/UEI.SmartControl( 8051): QS Service version code: 201091
D/UEI.SmartControl( 8051): Service requested: Control
E/UEI.SmartControl( 8051): Loading SETTINGS...
,D/UEI.SmartControl( 8051): Request IControl service: devices are loaded...
I/ActivityManager( 1033): Killing 6245:com.lge.qremote/u0a112 (adj 15): empty #17
D/UEI.SmartControl( 8051): -- Open brand translation xml: brands_translations_ko
,I/UEI.SmartControl( 8051): Notify AllClients services are ready: 0
,D/UEI.SmartControl( 8051): -----service ready thread exits
W/libprocessgroup( 1033): failed to open /acct/uid_10112/pid_6245/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 8051): Internal service binding...
,D/UEI.SmartControl( 8051): Internal timer expired: 1
,D/UEI.SmartControl( 8051): unbind internal service
D/UEI.SmartControl( 8051): Service.onUnbind: IControl
,D/UEI.SmartControl( 8051): Service.onDestroy
D/UEI.SmartControl( 8051): Lock is in USE false
D/UEI.SmartControl( 8051): unbind internal service
W/System.err( 8051): java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@2e7e1587
W/System.err( 8051): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
W/System.err( 8051): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
W/System.err( 8051): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
W/System.err( 8051): 	at com.uei.control.Service.c(Unknown Source)
W/System.err( 8051): 	at com.uei.control.Service.onDestroy(Unknown Source)
W/System.err( 8051): 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
W/System.err( 8051): 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
W/System.err( 8051): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
W/System.err( 8051): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 8051): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 8051): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 8051): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 8051): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 8051): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 8051): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 8051): java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@2e7e1587
D/serial_port( 8051): close(fd = 25)
I/UEI.SmartControl( 8051): Serial port is closed.
I/UEI.SmartControl( 8051): Serial port is closed.
D/UEI.SmartControl( 8051): Blaster closed
D/UEI.SmartControl( 8051): Shut down QS...
D/UEI.SmartControl( 8051): Stopping QS lib
,D/UEI.SmartControl( 8051): QS lib stop result = true
,D/UEI.SmartControl( 8051): Stopped QS lib
,D/UEI.SmartControl( 8051): Stopped file observer...
D/UEI.SmartControl( 8051): QS shutdown complete
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0,
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 1197957086162; DSPS: 39396008; Offset : -4328160348
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 1217959182872; DSPS: 40051437; Offset : -4328169429
,I/UsageStatsService( 1033): User[0] Flushing usage stats to disk
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 1237961524948; DSPS: 40706873; Offset : -4328146583
,I/[SystemUI]TimeTickManager( 1463): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1463): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1463): called onTimeUpdated()
,I/[SystemUI]Clock( 1463): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1463): called onTimeUpdated()
I/[SystemUI]DateView( 1463): called onTimeUpdated()
I/[SystemUI]DateView( 1463): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1463): handleTimeUpdate
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 1257963589264; DSPS: 41362301; Offset : -4328157672
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 1277965566183; DSPS: 42017726; Offset : -4328164160
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 1297967670446; DSPS: 42673155; Offset : -4328165610
,I/[SystemUI]TimeTickManager( 1463): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1463): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1463): called onTimeUpdated()
,I/[SystemUI]Clock( 1463): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1463): called onTimeUpdated()
I/[SystemUI]DateView( 1463): called onTimeUpdated()
I/[SystemUI]DateView( 1463): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1463): handleTimeUpdate
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 1317969763720; DSPS: 43328583; Offset : -4328147584
,TIME-OUT KILL (timeout was 1200000ms),I/[SystemUI]LGPowerUI( 1463): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1463): On Skip Timer : true
D/LEDHandler( 1930): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1930): Battery Level Remaining: 100%
D/LEDHandler( 1930): Battery Temp: 276, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1463): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 276
I/[SystemUI]LGPowerUI( 1463): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController( 1033): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1463): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3164): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 3164): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
D/AndroidRuntime( 8097): 
D/AndroidRuntime( 8097): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8097): CheckJNI is OFF
D/AndroidRuntime( 8097): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1033): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
I/ActivityManager( 1033): Killing 5968:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
I/WindowState( 1033): WIN DEATH: Window{be72e26 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService( 1033): Client connection lost with reason: 4
D/InputDispatcher( 1033): Window went away: Window{be72e26 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings( 1033): Skipping PackageSetting{42bec80 com.example.hello/10319} due to missing metadata
I/ActivityManager( 1033):   Force finishing activity ActivityRecord{17a3fa23 u0 com.test.thalitest/.MainActivity t4}
E/GBMv2   (  340): DFP En is all cleared set to be enabled
W/ActivityManager( 1033): Spurious death for ProcessRecord{32c3348d 5968:com.test.thalitest/u0a311}, curProc for 5968: null
I/ActivityManager( 1033): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
I/ActivityManager( 1033):   Force finishing activity ActivityRecord{17a3fa23 u0 com.test.thalitest/.MainActivity t4 f}
W/ActivityManager( 1033): Duplicate finish request for ActivityRecord{17a3fa23 u0 com.test.thalitest/.MainActivity t4 f}
D/SplitWindowPolicy( 1930): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1930): topRunningActivity=ActivityInfo{31175fb1 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
D/SplitWindowPolicy( 1930): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1930): topRunningActivity=ActivityInfo{3a01dc96 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[LGHome]EVENT( 2020): [Launcher.java:5338:onStart()]onStart
I/[LGHome]EVENT( 2020): [Launcher.java:903:onResume()]onResume
D/KeyguardModel( 1463): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/InputReader( 1033): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1805): Ignoring removeGeofence because network location is disabled.
I/art     ( 4210): Explicit concurrent mark sweep GC freed 22101(1280KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 29MB/45MB, paused 460us total 41.146ms
D/LIA_Service_RemotePackageHandler( 1983): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
D/LIA_MrGDBLogger_PackageInfoDetector( 2723): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
W/System.err( 4159): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 4159): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4159): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4159): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4159): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4159): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4159): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4159): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4159): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4159): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4159): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4159): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
I/[LGHome]EVENT( 2020): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 2020): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/PostponalbeReceiver( 7530): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
D/SplitUIManager( 1858): split_name #11 / not available #0
D/SplitUIService( 1858): removed split : 
I/ActivityManager( 1033): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=8129 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
D/ActionManagerService( 1894): notifyUserLog: 1000003
I/[LGHome]GBoardWebView( 2020): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
D/LIA_Informant_ActionManagerMessageHandler( 2723): handleMessage: what(1000) actionID(0x1000003)
I/[SystemUI]QSlideListController( 1463): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]LGActivityUtil( 2020): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 2020): [Launcher.java:1056:onResume()]onResume end
I/[LGHome]EVENT( 2020): [Launcher.java:1114:onPause()]onPause
D/ActionManagerService( 1894): notifyUserLog: 1000004
I/[LGHome]GBoardWebView( 2020): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
D/LIA_Informant_ActionManagerMessageHandler( 2723): handleMessage: what(1000) actionID(0x1000004)
V/BoardContentProvider( 2723): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
V/SIM_STK ( 1033): Menu title from STK is T-Mobile
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
I/GBoardWebViewUtils( 2020): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1453982949437
I/GBoardWebViewUtils( 2020): , create_time: 1453982950152
I/GBoardWebViewUtils( 2020): , expire_time: 0
I/GBoardWebViewUtils( 2020): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide.html?id=guide_1111111111116_1453982949437&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2020): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2020): , display: false
I/GBoardWebViewUtils( 2020): , animation: false }
I/art     ( 1033): Explicit concurrent mark sweep GC freed 12664(1013KB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 44MB/66MB, paused 1.846ms total 106.519ms
I/art     ( 1033): WaitForGcToComplete blocked for 109.855ms for cause Explicit
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1463): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1463): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
I/SystemUI[Framework]( 1033): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1033): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1033): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1033): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1033): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@22404ac0,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1033): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/WallpaperManager( 2020): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
D/AppUp4:PreloadHelper( 7693): added Exclude : com.test.thalitest
I/[LGHome]EVENT( 2020): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]GBoardWebView( 2020): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
D/SplitUIManager( 1858): split_name #11 / not available #0
I/SplitUIService( 1858): split app #11
D/administrator( 1033): Handling package changes for user 0
I/ActivityManager( 1033): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=8149 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/LockScreenSettings( 8129): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
I/[LGHome]EVENT( 2020): [Launcher.java:5349:onStop()]onStop
D/KeyguardModel( 1463): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1463): createShortcutInfo...
D/KeyguardModel( 1463): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1463): createShortcutInfo...
W/ResourcesManager( 1463): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1463): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1463): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1463): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1463): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1463): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1463): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1463): createShortcutInfo...
V/SIM_STK ( 1033): Menu title from STK is T-Mobile
W/ResourcesManager( 1463): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1463): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1463): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1463): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1463): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1463): createShortcutInfo...
W/ResourcesManager( 1463): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1463): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1463): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1463): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1463): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1463): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1463): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1463): createShortcutInfo...
I/ActivityManager( 1033): Killing 7559:com.lge.settings.easy/1000 (adj 15): empty #17
I/NotificationService( 1033): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1033): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1033): Receieved: android.intent.action.PACKAGE_REMOVED
I/art     ( 1033): Explicit concurrent mark sweep GC freed 4142(219KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 3.086ms total 164.570ms
D/KeyguardModel( 1463): handleShortcutListChanged...
I/[LGHome]Launcher.Model( 2020): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2020): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2020): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2020): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2020): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2020): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
W/libprocessgroup( 1033): failed to open /acct/uid_1000/pid_7559/cgroup.procs: No such file or directory
D/KeyguardModel( 1463): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1463): createShortcutInfo...
D/PhoneStatusBar( 1463): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
I/[SystemUI]NavigationThemeResource( 1463): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1463):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1463): , Keyguard show=false, IME shown=false, Panel expanded=false
D/TaskPersister( 1033): removeObsoleteFile: deleting file=4_task.xml
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
W/ResourcesManager( 8149): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/[LGHome]Launcher.Model( 2020): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2020): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
D/KeyguardModel( 1463): handleShortcutListChanged...
I/Timeline( 1033): Timeline: Activity_windows_visible id: ActivityRecord{230ed45b u0 com.lge.launcher2/.Launcher t3} time:1320583
I/[LGHome]EVENT( 2020): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 2020): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2020): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2020): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2020): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
W/ResourcesManager( 8149): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 8149): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 8149): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 8149): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/[Concierge]WidgetView( 2020): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
D/[Concierge]Service( 2612): onStartCommand(). Type : 8
D/[Concierge]Service( 2612): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/[Concierge]Service( 2612): Update widget ID : 11
D/[Concierge]WidgetView( 2020): change position of spinner
D/AndroidRuntime( 8097): Shutting down VM
I/[Concierge]WidgetView( 2020): initWebView(). Time : 1454435231887
D/[Concierge]Service( 2612): onStartCommand(). Type : 0
I/[Concierge]WebView( 2020): Return exist ConciergeWebView. Reuse : 383618921
D/[Concierge]WidgetView( 2020): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2020): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
I/[LgeWidgetLib]ExtViewHost( 2020): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@8ec1af8
I/[LGHome]EVENT( 2020): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2020): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2020): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2020): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/[Concierge]WidgetView( 2020): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2020): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
W/[Concierge]WidgetView( 2020): Widget kill message received. Destory myself. My : 1454433939706, New one : 1454435231887
D/[Concierge]WidgetView( 2020): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2020): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/[LGHome]Launcher( 2020): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2020): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2020): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2020): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2020): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2020): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2020): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2020): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/SystemConfig( 8149): BUILD Country: EU
I/SystemConfig( 8149): BUILD Operator: OPEN
I/[LgeWidgetLib]LgeAppWidgetHostView( 2020): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
E/[LgeWidgetLib]LgeAppWidgetHostView( 2020): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2020): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 2020): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/ActivityManager( 1033): Killing 7621:com.android.bluetooth/1002 (adj 15): empty #17
I/Timeline( 2020): Timeline: Activity_idle id: android.os.BinderProxy@308d870c time:1320715
D/LGBluetoothUserBindClient( 7463): [BTUI] onServiceDisconnected
W/libprocessgroup( 1033): failed to open /acct/uid_1002/pid_7621/cgroup.procs: No such file or directory
W/ActivityManager( 1033): Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
I/SystemConfig( 8149): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 8149): existFile = false
I/SystemConfig( 8149): canReadFile = false
I/SystemConfig( 8149): systemFeature RCS result false
D/SystemConfig( 8149): refreshRcsSupport() :false
D/VoicemailCleanupService( 2344): Cleaning up data for package: com.test.thalitest
I/PackageChangeReceiver( 7735): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
I/ActivityManager( 1033): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=8172 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
I/chromium( 2020): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
W/ResourcesManager( 8172): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8172): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8172): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 8172): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/GBoardtInterface( 2020): onReloaded()
I/GBoardWebViewClient( 2020): onPageFinished url:file:///android_asset/www/main.html
V/BoardContentProvider( 2723): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
V/BoardContentProvider( 2723): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/ActionManagerService( 1894): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 2723): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 2723): onEvent() : ACTION_BOARD_ENABLED
D/ActionManagerService( 1894): notifyUserLog: 1000001
V/BoardContentProvider( 2723): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/LIA_Informant_ActionManagerMessageHandler( 2723): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 2723): onEvent() : ACTION_BOARD_ENABLED
D/LIA_Informant_Tips_FormEventRepository( 2723): getSize() : size - 0
D/LIA_Informant_Tips_SmartTipsActionManager( 2723): onSettingEvent() : GBoard On - add scheduler - 0
D/GBoardUriUtils( 2020): fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
D/GBoardWebViewUtils( 2020): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
D/GBoardUriUtils( 2020): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
D/GBoardWebViewUtils( 2020): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
D/GBoardUriUtils( 2020): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide2.html?id=guide_1111111111116_1453982949437&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
D/GBoardWebViewUtils( 2020): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide2.html?id=guide_1111111111116_1453982949437&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/AppConfig( 8172): Total System Memory = 2995761152
D/SystemHelper( 8172): region [EU], country [EU], operator [OPEN], sub-operator []
W/ResourcesManager( 1033): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
E/SharedPreferencesImpl( 8172): Couldn't rename file /data/data/com.android.gallery3d/shared_prefs/com.android.gallery3d_preferences.xml to backup file /data/data/com.android.gallery3d/shared_prefs/com.android.gallery3d_preferences.xml.bak
I/ActivityManager( 1033): Killing 7599:com.lge.sync/1000 (adj 15): empty #17
W/ResourceType( 1033): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)

```
