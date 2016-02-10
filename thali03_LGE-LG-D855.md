#### Test 58380500a584679_thali03_LGE-LG-D855 Logs


```
--------- beginning of main,
I/MusicWidget( 2700): mDelayedStopHandler : unbind
I/MusicBrowser( 2215): [MediaPlaybackService.java:2869:onUnbind()] oooooo 
I/MusicBrowser( 2215): [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2215): [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2215): [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2215): [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2215): [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2215): [MediaPlaybackService.java:2046:onDestroy()] oooooo 
I/MusicBrowser( 2215): [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
I/MediaFocusControl( 1039):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@3bac8ad3com.lge.music.MediaPlaybackService$5@2cf59610
D/MusicBrowser( 2215): [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2215): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2215): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2215): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2215): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@2911f399
I/MusicBrowser( 2215): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2215): [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2215): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2215): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2215): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2215): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2215): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2215): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2215): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2215): [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2215): [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2215): [MediaPlaybackService.java:6704:release()] oooooo 
I/MusicBrowser( 2215): [MediaPlaybackService.java:6665:stop()] oooooo 
V/MediaPlayer[Native]( 2215): reset
V/MediaPlayer[Native]( 2215): setListener
V/MediaPlayer[Native]( 2215): disconnect
V/MediaPlayer[Native]( 2215): destructor
V/AudioFlinger(  318): releasing 13 from 2215 for -1
V/AudioFlinger(  318):  decremented refcount to 0
V/AudioFlinger(  318): purging stale effects
V/MediaPlayer[Native]( 2215): disconnect
D/MusicBrowser( 2215): [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
I/SmartShareClient( 2215): [SmartShareManagerClient] smartshare client supported version code: 305000
I/SmartShareClient( 2215): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2215): [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
I/MusicBrowser( 2215): [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2215): [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2215): [SmartShareManagerClient] unregisterListener: 413791497
W/SmartShareClient( 2215): [SmartShareManagerClient] unregisterListener invalid listener: 413791497
I/SmartShareClient( 2215): [SmartShareManagerClient] terminate service: 2215/MediaPlaybackService/255867207
E/HomeCloudIF( 2215): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2215): [SmartShareManagerClient] unbindService context:android.app.Application@16fc430e
V/CloudHub( 2215): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
V/CloudHub( 2215): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2215): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
D/MusicBrowser( 2215): [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
--------- beginning of system
I/ActivityManager( 1039): Killing 5410:com.android.providers.calendar/u0a14 (adj 15): empty #17
I/CloudHub( 2215): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29990
W/libprocessgroup( 1039): failed to open /acct/uid_10014/pid_5410/cgroup.procs: No such file or directory
D/AndroidRuntime( 6031): 
D/AndroidRuntime( 6031): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6031): CheckJNI is OFF
D/AndroidRuntime( 6031): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1039): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1958): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1039): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1039): setTaskToReturnTo : TaskRecord{27dfab41 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1039): setTaskToReturnTo : TaskRecord{27dfab41 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1039): AppWindowTokenEx init.. 
E/GBMv2   (  342): DFP En is all cleared set to be enabled
I/ActivityManager( 1039): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6046 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6031): Shutting down VM
V/ActivityManager( 1039): Display changed displayId=0
D/DSDPConnection( 1852): Display #0 changed.
D/SplitWindowPolicy( 1958): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1958): topRunningActivity=ActivityInfo{16402c8a co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1958): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1958): topRunningActivity=ActivityInfo{3a132fb co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 6046): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 6046): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
I/LibraryLoader( 6046): Loading: webviewchromium
I/LibraryLoader( 6046): Time to load native libraries: 3 ms (timestamps 5836-5839)
I/LibraryLoader( 6046): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6046): Binding Chromium to main looper Looper (main, tid 1) {f403947}
I/LibraryLoader( 6046): Expected native library version number "",actual native library version number ""
I/chromium( 6046): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6046): Initializing chromium process, renderers=0
W/art     ( 6046): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6046): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
V/AudioPolicyService(  318): registerClient() client 0xb14fd900, uid 10311
W/chromium( 6046): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6046): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 6046): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
D/BluetoothManagerService( 1039): Message: 20
D/BluetoothManagerService( 1039): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@cbbc5c3:true
D/BluetoothAdapter( 6046): 599143796: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 6046): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6046): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6046): Build Date: 12/12/14 금
I/Adreno-EGL( 6046): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6046): Remote Branch: 
I/Adreno-EGL( 6046): Local Patches: 
I/Adreno-EGL( 6046): Reconstruct Branch: 
W/chromium( 6046): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 6046): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 6046): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6046): onDetachedFromWindow called when already detached. Ignoring
V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{3489a5b3 type 2 when 101596 com.google.android.gms} when 101596
D/SystemWebViewEngine( 6046): CordovaWebView is running on device made by: LGE
D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1039): DNSproblemNotiEnabled is disabled ignore DNS fail CB
W/art     ( 6046): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6046): Attempt to remove local handle scope entry from IRT, ignoring
W/ContextImpl( 4140): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
I/ActivityManager( 1039): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RequestWriter$NetworkStateReceiver: pid=6123 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ActivityManager( 1039): Activity pause timeout for ActivityRecord{15afe8e6 u0 com.test.thalitest/.MainActivity t4}
D/LgDataFeature( 6046): LgDataFeature() Constructor: none
D/LgDataFeature( 6046): LgDataFeature() Constructor Done, null
D/OpenGLRenderer( 6046): Render dirty regions requested: true
I/OpenGLRenderer( 6046): Initialized EGL, version 1.4
D/OpenGLRenderer( 6046): Enabling debug mode 0
D/Atlas   ( 6046): Validating map...
D/SplitWindow( 1039): check instance of lgWin Window{1525a87a u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/ResourcesManager( 6123): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/SystemUI[Framework]( 1039): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
D/PhoneStatusBar( 1444): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1444): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1444):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1444): , Keyguard show=false, IME shown=false, Panel expanded=false
W/PhoneWindowManagerEx( 1039): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1039): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1039): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1039): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@168b094a,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1039): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/ActivityManager( 1039): Displayed com.test.thalitest/.MainActivity: +635ms (total +732ms)
I/Timeline( 1039): Timeline: Activity_windows_visible id: ActivityRecord{15afe8e6 u0 com.test.thalitest/.MainActivity t4} time:106303
I/Timeline( 6046): Timeline: Activity_idle id: android.os.BinderProxy@20be3a4 time:106311
D/LgDataFeature( 6123): LgDataFeature() Constructor: none
D/LgDataFeature( 6123): LgDataFeature() Constructor Done, null
I/chromium( 6046): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6046): 
D/JsMessageQueue( 6046): Set native->JS mode to OnlineEventsBridgeMode
I/Babel   ( 6123): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 6123): MmsConfig.loadMmsSettings
I/Babel   ( 6123): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
I/Babel   ( 6123): MmsConfig.loadFromDatabase
E/Babel   ( 6123): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 6123): MmsConfig.loadFromResources
E/Babel   ( 6123): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 6123): MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
D/jxcore_app_log( 6046): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435016960
W/Settings( 6123): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/chromium( 6046): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 6046): 
W/AudioCapabilities( 6123): Unsupported mime audio/evrc
W/AudioCapabilities( 6123): Unsupported mime audio/qcelp
W/VideoCapabilities( 6123): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6123): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6123): Unsupported mime audio/qcelp
W/AudioCapabilities( 6123): Unsupported mime audio/evrc
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 106581618088; DSPS: 3633226; Offset : -4307789375
I/chromium( 6046): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/ActivityManager( 1039): Killing 5732:com.android.defcontainer/u0a4 (adj 15): empty #17
W/VideoCapabilities( 6123): Unsupported mime video/x-ms-wmv
W/VideoCapabilities( 6123): Unsupported mime video/divx
W/VideoCapabilities( 6123): Unsupported mime video/divx311
W/VideoCapabilities( 6123): Unsupported mime video/divx4
W/VideoCapabilities( 6123): Unsupported mime video/mp4v-esdp
I/VideoCapabilities( 6123): Unsupported profile 4 for video/mp4v-es
W/AudioCapabilities( 6123): Unsupported mime audio/eac3
W/AudioCapabilities( 6123): Unsupported mime audio/ac3
W/AudioCapabilities( 6123): Unsupported mime audio/g726
W/AudioCapabilities( 6123): Unsupported mime audio/wma-voice
W/AudioCapabilities( 6123): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6123): Unsupported mime audio/adpcm
W/VideoCapabilities( 6123): Unsupported mime video/theora
W/VideoCapabilities( 6123): Unsupported mime video/mjpg
W/libprocessgroup( 1039): failed to open /acct/uid_10004/pid_5732/cgroup.procs: No such file or directory
E/GBMv2   (  342): DFP En is all cleared set to be enabled
E/GBMv2   (  342): Set value is all cleared set the max
I/GBMv2   (  342): DFP Enabled. Ignore VFP set
,W/jxcore-log( 6046): Initializing JXcore engine
,W/jxcore-log( 6046): JXcore engine is ready
,W/Thread-703( 6169): type=1400 audit(0.0:146): avc: denied { ioctl } for path="socket:[8459]" dev="sockfs" ino=8459 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-703( 6169): type=1400 audit(0.0:147): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-703( 6169): type=1400 audit(0.0:148): avc: denied { ioctl } for path="socket:[9561]" dev="sockfs" ino=9561 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-703( 6169): type=1400 audit(0.0:149): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/Thread-703( 6169): type=1400 audit(0.0:150): avc: denied { ioctl } for path="socket:[27597]" dev="sockfs" ino=27597 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 6046): Starting JXcore engine
W/jxcore-log( 6046): Platform android
W/jxcore-log( 6046): 
W/jxcore-log( 6046): Process ARCH arm
W/jxcore-log( 6046): 
,I/jxcore-log( 6046): JXcore Cordova bridge is ready!
I/jxcore-log( 6046): 
,W/jxcore-log( 6046): JXcore engine is started
,I/jxcore-log( 6046): Toggling radios to true
I/jxcore-log( 6046): 
,D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1039): enable():  mBluetooth =null mBinding = false
D/LocationManagerService( 1039): getAllProviders()=[passive, gps, network]
,D/BluetoothManagerService( 1039): Message: 1
D/BluetoothManagerService( 1039): MESSAGE_ENABLE: mBluetooth = null
D/WifiService( 1039): New client listening to asynchronous messages
D/Ulp_jni ( 1039): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1039): JNI:system_update. Event-4
I/ActivityManager( 1039): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=6181 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
D/WifiServiceImplEx( 1039): setWifiEnabled: true pid=6046, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: true pid=6046, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
,E/WifiStateMachine( 1039):  InitialState CMD_START_SUPPLICANT 0 0
I/LGFTMITEM( 1039): [GET_FTM][id=6], offset=12288
D/LocationManagerService( 1039): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1039): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1039): JNI:system_update. Event-4
D/WifiServiceImplEx( 1039): disconnect pid=6046, uid=10311, packageName=com.test.thalitest
D/WifiServiceImplEx( 1039): reconnect pid=6046, uid=10311, packageName=com.test.thalitest
,E/WifiUtil( 1039): wfc_util_ffile_check_copy(): pid[1039] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
E/WifiUtil( 1039): wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
E/WifiUtil( 1039): wfc_util_ffile_check_copy(): pid[1039] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
E/WifiUtil( 1039): wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
I/WifiUtil( 1039): Intf0MacAddress=C49A027B60AC
E/WifiHW  ( 1039): unknown target_country: EU , set to default
E/WifiHW  ( 1039): [wifi_ensure_config_files] default country1 = GB
E/WifiHW  ( 1039): [wifi_ensure_config_files] default country2 = GB
I/WifiUtil( 1039): gEnableBmps=1
I/jxcore-log( 6046): Radios toggled
I/jxcore-log( 6046): 
I/jxcore-log( 6046): My device name is: LGE-LG-D855
I/jxcore-log( 6046): 
,W/ResourcesManager( 6181): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager( 6181): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6181): Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 6181): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/BluetoothAdapterApp( 6181): Loading JNI Library
,D/SoftapController(  313): Softap fwReload - Ok
,D/CommandListener(  313): Setting iface cfg
D/CommandListener(  313): Trying to bring down wlan0
D/Tethering( 1039): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering( 1039): InitialState.processMessage what=4
D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1039): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/CommandListener(  313): Clearing all IP addresses on wlan0
D/BluetoothAdapterApp( 6181): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@1035f16b Instance Count = 1
,I/ActivityManager( 1039): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=6218 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/Tethering( 1039): sendTetherStateChangedBroadcast 0, 0, 0
,D/BluetoothAdapterApp( 6181): onCreate
D/ProfileConfigQcom( 6181): [BTUI] HeadsetService is supported
D/ProfileConfigQcom( 6181): Adding HeadsetService
,D/ProfileConfigQcom( 6181): [BTUI] A2dpService is supported
D/ProfileConfigQcom( 6181): Adding A2dpService
D/ProfileConfigQcom( 6181): [BTUI] HidService is supported
D/ProfileConfigQcom( 6181): Adding HidService
D/ProfileConfigQcom( 6181): [BTUI] HealthService is supported
D/ProfileConfigQcom( 6181): Adding HealthService
D/LGBluetoothFeatureConfig( 6181): isSupportPan() :  mTargetOp=OPEN
D/ProfileConfigQcom( 6181): [BTUI] PanService is supported
D/ProfileConfigQcom( 6181): Adding PanService
D/ProfileConfigQcom( 6181): [BTUI] GattService is supported
D/ProfileConfigQcom( 6181): Adding GattService
D/ProfileConfigQcom( 6181): [BTUI] BluetoothMapService is supported
D/ProfileConfigQcom( 6181): Adding BluetoothMapService
D/ProfileConfigQcom( 6181): [BTUI] HeadsetClientService is NOT supported
W/ResourcesManager( 6218): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6218): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6218): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6218): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 6218): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6218): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/BluetoothManagerService( 1039): Message: 20
D/BluetoothManagerService( 1039): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@91e04f7:true
D/BluetoothAdapterState( 6181): make
I/LGFMServiceAdapter( 6181): [FM] LGFMServiceAdapter : create
I/bluedroid-qcom( 6181): init
I/BluetoothAdapterState( 6181): Entering OffState
,E/WifiHW  ( 1039): Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
E/WifiStateMachine( 1039): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1039): useWiFiOffloading() : false
E/WifiStateMachine( 1039): CONFIG_LGE_WLAN_PATH : true
I/bte_conf( 6181): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
D/WifiMonitor( 1039): startMonitoring(wlan0) with mConnected = false
D/WifiMonitor( 1039): connecting to supplicant
I/WifiServerServiceExt( 1039): WIFI_STATE_CHANGED_ACTION [2]
V/WfdStateTracker( 1958): WfdStateTracker handleDirectStateChangedEvent: 1
I/bte_conf( 6181): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 6181): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 6181): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
D/BTIF_CORE( 6181): [BTUI] lge_load_bluetooth_address
D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
I/bluedroid-qcom( 6181): get_profile_interface socket
I/bluedroid-qcom( 6181): get_profile_interface map_client
W/wpa_supplicant( 6239): type=1400 audit(0.0:151): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/wpa_supplicant( 6239): type=1400 audit(0.0:152): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/GKI_LINUX( 6181): gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothManagerService( 1039): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService( 1039): Message: 40
D/BluetoothManagerService( 1039): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
D/BluetoothAdapterProperties( 6181): Address is:58:3F:54:73:64:C0
D/BluetoothAdapterProperties( 6181): Name is: G3-1
D/BluetoothManagerService( 1039): Bluetooth Adapter name changed to G3-1
D/BluetoothManagerService( 1039): Stored Bluetooth name: G3-1
I/bluedroid-qcom( 6181): config_hci_snoop_log
D/BluetoothManagerService( 1039): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService( 1039): Broadcasting onBluetoothServiceUp() to 7 receivers.
W/bdaddr_loader( 6242): type=1400 audit(0.0:153): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,V/LGMDMManagerInternal( 6181): Create singleton instance
D/lge_bdaddr_loader( 6242): [BTUI] bdaddr_loader ::: START
I/wpa_supplicant( 6239): Successfully initialized wpa_supplicant
D/lge_bdaddr_loader( 6242): [BTUI] bluetooth_load_bdaddress
I/LGFTMITEM( 6242): [GET_FTM][id=8], offset=16384
D/lge_bdaddr_loader( 6242): [BTUI] bdaddr to set in property : 58:3F:54:73:64:C0
W/bdaddr_loader( 6242): type=1400 audit(0.0:154): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
E/lge_bdaddr_loader( 6242): [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:64:C0
D/lge_bdaddr_loader( 6242): [BTUI] bdaddr_loader ::: END
I/wpa_supplicant( 6239): rfkill: Cannot open RFKILL control device
,I/wpa_supplicant( 6239): [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
D/UsbSettingsReceiver( 6218): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6218): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6218): [AUTORUN] sys.usb.state = ptp_only,adb
,D/UsbSettingsReceiver( 6218): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6218): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 6218): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6218): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 6218): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6218): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6218): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 6218): [AUTORUN] setTetherStatus() : status=false
D/UsbSettingsReceiver( 6218): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,D/UsbSettingsReceiver( 6218): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6218): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6218): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/BluetoothAdapterState( 6181): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/UsbSettingsReceiver( 6218): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/BluetoothAdapterProperties( 6181): Setting state to 11
I/BluetoothAdapterState( 6181): Bluetooth adapter state changed: 10-> 11
D/UsbSettingsControl( 6218): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6218): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 6218): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6218): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6218): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 6218): [AUTORUN] setTetherStatus() : status=false
D/BluetoothManagerService( 1039): Message: 60
D/BluetoothManagerService( 1039): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService( 1039): Bluetooth State Change Intent: 10 -> 11
I/LGBluetoothServiceJni( 6181): classInitNative: succeeds
,I/ActivityManager( 1039): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6244 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
I/ActivityManager( 1039): Killing 5815:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,I/wpa_supplicant( 6239): rfkill: Cannot open RFKILL control device
,D/BluetoothBondStateMachine( 6181): make
,W/libprocessgroup( 1039): failed to open /acct/uid_10008/pid_5815/cgroup.procs: No such file or directory
D/LGBluetoothAPIService( 1958): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
I/[SystemUI]BluetoothHandler( 1444): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
V/BluetoothPbapReceiver( 6181): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 6181): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6181): ***********state = 11
,D/BluetoothAdapterService( 6181): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1127cb12
D/LGBluetoothServiceAdapter( 6181): [BTUI] check adapter is available - false.
D/BluetoothAdapterService( 6181): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1127cb12
D/LGBluetoothServiceAdapter( 6181): [BTUI] check adapter is available - true : set adapter available.
D/LGBluetoothSettingsDBObserver( 6181): [BTUI] register observer for LG device name DB
I/BluetoothBondStateMachine( 6181): StableState(): Entering Off State
E/BluetoothAdapterService( 6181): File transfer profiles supported!!
I/wpa_supplicant( 6239): [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
I/wpa_supplicant( 6239): p2p0: CTRL-EVENT-AVOID-FREQ ranges=
I/wpa_supplicant( 6239): wlan0: CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine( 1039):  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
E/WifiStateMachine( 1039):  SupplicantStartingState CMD_START_DRIVER 0 0
E/WifiStateMachine( 1039):  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
E/WifiStateMachine( 1039):  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
E/WifiStateMachine( 1039):  SupplicantStartingState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1039):  DefaultState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1039):  SupplicantStartingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1039):  DefaultState CMD_RECONNECT 0 0
E/WifiStateMachine( 1039):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1039):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1039):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1039):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1039):  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
D/WifiNative-wlan0( 1039): doString: [DRIVER MACADDR]
D/WifiNative-wlan0( 1039):    returned Macaddr = c4:9a:02:7b:60:ac
D/WifiStateMachine( 1039): MAC Addr from driver = c4:9a:02:7b:60:ac
D/WifiOffDelayIfNotUsed( 1039): setPowerSaveActivated(false)
D/WifiMonitor( 1039): Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
D/WifiMonitor( 1039): Dropping event because (p2p0) is stopped
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=0 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1039): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1039): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/ActivityManager( 1039): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6263 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
E/WifiStateMachine( 1039): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1039): useWiFiOffloading() : false
E/WifiStateMachine( 1039): CONFIG_LGE_WLAN_PATH : true
E/BluetoothAdapterService( 6181): File transfer profiles supported!!
D/WifiNative-wlan0( 1039): doBoolean: SET update_config 1
D/WifiNative-wlan0( 1039): SET update_config 1: returned true
D/WifiConfigStore( 1039): Loading config and enabling all networks 
D/WifiNative-wlan0( 1039): doString: [LIST_NETWORKS]
D/WifiNative-wlan0( 1039):    returned network id / ssid / bssid / flags 0	NG700	any	
D/BluetoothHeadset( 1852): Proxy object connected
D/BluetoothHeadset( 1852): Proxy object connected
D/BluetoothHeadset( 1852): Proxy object connected
D/BluetoothHeadset( 1039): Proxy object connected
D/WfdService( 1958): Waiting for WifiP2p enabling
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/WifiServerServiceExt( 1039): WIFI_STATE_CHANGED_ACTION [3]
E/BluetoothAdapterService( 6181): File transfer profiles supported!!
D/HeadsetService( 6181): Received start request. Starting profile...
I/LGBluetoothHeadsetServiceJni( 6181): classInitNative: succeeds
D/LGBluetoothHfpAdapter( 6181): Version 1.6
D/LGBluetoothFeatureConfig( 6181): isPrivacyLogsEnabled : true
E/BluetoothAdapterService( 6181): File transfer profiles supported!!
I/BluetoothHeadsetServiceJni( 6181): classInitNative: succeeds
D/HeadsetStateMachine( 6181): make
D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
I/WifiServerServiceExt( 1039): batteryPsActivateMsgHandler : state:0 event:3
E/WifiConfigStore( 1039): readNetworkVariablesFromSupplicantFile key=psk
E/BluetoothAdapterService( 6181): File transfer profiles supported!!
E/WifiConfigStore( 1039): readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
E/WifiConfigStore( 1039): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
D/WifiStateMachine( 1039): enableVerboseLogging : level 2
D/WifiNative-wlan0( 1039): doBoolean: SET device_name g3_global_com
D/WifiNative-wlan0( 1039): SET device_name g3_global_com: returned true
D/WifiNative-wlan0( 1039): doBoolean: SET manufacturer LGE
D/WifiNative-wlan0( 1039): SET manufacturer LGE: returned true
D/WifiNative-wlan0( 1039): doBoolean: SET model_name LG-D855
D/WifiNative-wlan0( 1039): SET model_name LG-D855: returned true
D/WifiNative-wlan0( 1039): doBoolean: SET model_number LG-D855
D/WifiNative-wlan0( 1039): SET model_number LG-D855: returned true
D/WifiNative-wlan0( 1039): doBoolean: SET serial_number LGD8553bed2d08
D/WifiNative-wlan0( 1039): SET serial_number LGD8553bed2d08: returned true
D/WifiNative-wlan0( 1039): doBoolean: SET config_methods physical_display virtual_push_button
D/WifiNative-wlan0( 1039): SET config_methods physical_display virtual_push_button: returned true
D/WifiNative-wlan0( 1039): doBoolean: SET device_type 10-0050F204-5
D/WifiNative-wlan0( 1039): SET device_type 10-0050F204-5: returned true
D/WifiStateMachine( 1039): Setting OUI to DA-A1-19
D/WifiNative-wlan0( 1039): doBoolean: SCAN_INTERVAL 120
D/WifiNative-wlan0( 1039): SCAN_INTERVAL 120: returned true
D/WifiNative-HAL( 1039): Setting external_sim to 1
D/WifiNative-wlan0( 1039): doBoolean: SET external_sim 1
D/WifiNative-wlan0( 1039): SET external_sim 1: returned true
I/WifiNative-HAL( 1039): startHal
E/wifi    ( 1039): getStaticLongField sWifiHalHandle 0x989788dc
E/WifiHAL ( 1039): Could not connect handle
D/wifi    ( 1039): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x40180a
I/WifiNative-HAL( 1039): Could not start hal
D/WifiStateMachine( 1039): Setting OUI to DA-A1-19
I/WifiNative-HAL( 1039): startHal
E/wifi    ( 1039): getStaticLongField sWifiHalHandle 0x9897885c
E/WifiHAL ( 1039): Could not connect handle
D/wifi    ( 1039): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x5017ba
I/WifiNative-HAL( 1039): Could not start hal
D/WifiNative-wlan0( 1039): doBoolean: STA_AUTOCONNECT 1
D/WifiNative-wlan0( 1039): STA_AUTOCONNECT 1: returned true
D/WifiNative-wlan0( 1039): doBoolean: DRIVER BTCOEXSCAN-STOP
I/wpa_supplicant( 6239): wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
D/WifiNative-wlan0( 1039): DRIVER BTCOEXSCAN-STOP: returned true
D/LgDataFeature( 6181): LgDataFeature() Constructor: none
D/LgDataFeature( 6181): LgDataFeature() Constructor Done, null
D/WfdsService( 1958): Supplicant Connection state is changed : true
D/WfdsService( 1958): DefaultState - WIFI_SUPPLICANT_CONNECTED
D/WfdsService( 1958): Set the WFDS Monitor: true
E/BluetoothAdapterService( 6181): File transfer profiles supported!!
D/WfdsMonitor( 1958): WfdsMonitorThread create
D/WfdsMonitor( 1958): WFDS Monitor is created and started
D/WfdsService( 1958): WiFi: Supplicant connection re-established
D/HeadsetStateMachine( 6181): max_hf_connections = 1
I/bluedroid-qcom( 6181): get_profile_interface handsfree
D/WifiHS20( 1039): hidePasspointNotification off =false
V/ToneGenerator( 6181): ToneGenerator constructor: streamType=8, volume=1.000000
V/AudioPolicyService(  318): registerClient() client 0xb14fdee0, uid 1002
V/AudioPolicyManager(  318): getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  318): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  318): getOutput() returns output 2
V/AudioSystem( 6181): getOutputSamplingRate() no output descriptor for output 2 in gOutputs
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiNative-wlan0( 1039): doBoolean: DRIVER RXFILTER-STOP
I/wpa_supplicant( 6239): wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
V/AudioFlinger(  318): registerClient() client 0xb57da130, pid 6181
W/Settings( 6123): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/ToneGenerator( 6181): Create Track: 0xb4927680
V/AudioTrack( 6181): set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
V/AudioTrack( 6181): set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
V/AudioPolicyManager(  318): getOutputForAttr() usage=3, content=4, tag= flags=00000000
V/AudioPolicyManager(  318): getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  318): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  318): getOutput() returns output 2
V/AudioSystem( 6181): getOutputSamplingRate() no output descriptor for output 2 in gOutputs
I/StatusBar.NetworkController( 1444): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1444): mWifiConnected = false, mWifiLevel = 0
I/AudioFlinger(  318): isAudioPlaybackHookOn() false
V/AudioSystem(  318): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem(  318): ioConfigChanged() opening already existing output! 4
D/WifiNative-wlan0( 1039): DRIVER RXFILTER-STOP: returned true
D/WifiNative-wlan0( 1039): doBoolean: DRIVER RXFILTER-REMOVE 3
I/wpa_supplicant( 6239): wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
D/WifiNative-wlan0( 1039): DRIVER RXFILTER-REMOVE 3: returned true
V/AudioPolicyManager(  318): getOutputForAttr() usage=3, content=4, tag= flags=00000000
V/AudioPolicyManager(  318): getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
V/AudioPolicyManagerEx(  318): AudioPolicyManagerEx: getOutputForDevice
D/WifiNative-wlan0( 1039): doBoolean: DRIVER RXFILTER-START
V/AudioPolicyManagerEx(  318): getOutput() returns output 2
I/wpa_supplicant( 6239): wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
D/WifiNative-wlan0( 1039): DRIVER RXFILTER-START: returned true
D/WifiNative-wlan0( 1039): doBoolean: DRIVER RXFILTER-STOP
I/wpa_supplicant( 6239): wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
D/WifiNative-wlan0( 1039): DRIVER RXFILTER-STOP: returned true
D/WifiNative-wlan0( 1039): doBoolean: DRIVER RXFILTER-REMOVE 2
I/wpa_supplicant( 6239): android_multicast_filter_startstop : multicast filter set
D/WifiNative-wlan0( 1039): DRIVER RXFILTER-REMOVE 2: returned true
D/WifiNative-wlan0( 1039): doBoolean: DRIVER RXFILTER-START
I/wpa_supplicant( 6239): wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
D/WifiNative-wlan0( 1039): DRIVER RXFILTER-START: returned true
E/WifiNative: ( 1039): [109,125,976 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
D/WifiNative-wlan0( 1039): doBoolean: RECONNECT
D/WifiNative-wlan0( 1039): RECONNECT: returned true
D/WifiNative-wlan0( 1039): doString: [STATUS]
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=1 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiNative-wlan0( 1039):    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
D/WifiNative-wlan0( 1039): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 6239): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1039): DRIVER SETSUSPENDMODE 1: returned true
V/AudioSystem( 1039): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1039): ioConfigChanged() opening already existing output! 4
D/WifiNative-wlan0( 1039): doBoolean: SET ps 1
V/AudioSystem( 1852): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1852): ioConfigChanged() opening already existing output! 4
D/WifiNative-wlan0( 1039): SET ps 1: returned true
D/LGWifiP2pService( 1039): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
V/AudioSystem( 2215): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 2215): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 3300): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 3300): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 6181): ioConfigChanged() event 0, ioHandle 4
D/CommandListener(  313): Setting iface cfg
D/CommandListener(  313): Trying to bring up p2p0
D/WifiMonitor( 1039): startMonitoring(p2p0) with mConnected = true
D/LGWifiP2pService( 1039): P2pEnablingState
D/LGWifiP2pService( 1039): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2p socket connection successful
D/LGWifiP2pService( 1039): P2pEnabledState
V/AudioSystem( 1444): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1444): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 6181): ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
E/BluetoothAdapterService( 6181): File transfer profiles supported!!
V/AudioSystem(  318): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  318): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1444): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1444): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1039): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1039): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1852): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1852): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 2215): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 2215): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 3300): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 3300): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 6181): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 6181): ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
V/AudioSystem( 6181): getLatency() output 2, latency 50
V/AudioSystem( 6181): getFrameCount() output 2, frameCount 960
V/AudioTrack( 6181): createTrack_l() output 2 afLatency 50
V/AudioFlinger(  318): [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
V/AudioFlinger(  318): [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
V/AudioFlinger(  318): [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
V/AudioFlinger(  318): [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
V/AudioFlinger(  318): createTrack() lSessionId: 16
D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
V/AudioTrack( 6181): AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
V/AudioFlinger(  318): acquiring 16 from 6181, for 6181
V/AudioFlinger(  318):  added new entry for 16
V/ToneGenerator( 6181): ToneGenerator INIT OK, time: 109147
D/BluetoothAdapterService( 6181): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1127cb12
D/HeadsetStateMachine( 6181): Enter Disconnected: -2, size: 0
D/HeadsetPhoneState( 6181): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 6181): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetStateMachine( 6181): [BTUI] change sampling rate to 8000 when device is disconnected
V/AudioFlinger(  318): setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6181
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
V/ToneGenerator( 6181): ToneGenerator destructor
V/ToneGenerator( 6181): stopTone
V/ToneGenerator( 6181): Delete Track: 0xb4927680
V/AudioTrack( 6181): ~AudioTrack, releasing session id from 6181 on behalf of 6181
V/AudioFlinger(  318): releasing 16 from 6181 for 6181
V/AudioFlinger(  318):  decremented refcount to 0
V/AudioFlinger(  318): purging stale effects
V/AudioPolicyService(  318): AudioCommandThread() adding release output 2
V/AudioPolicyService(  318): inserting command: 6 at index 0, num commands 0
V/AudioPolicyService(  318): AudioCommandThread() waking up
V/AudioPolicyService(  318): AudioCommandThread() processing release output 2
V/AudioPolicyManager(  318): releaseOutput() 2
V/AudioPolicyService(  318): AudioCommandThread() going to sleep
V/AudioFlinger(  318): PlaybackThread::Track destructor
V/AudioFlinger(  318): removeClient_l() pid 6181, calling pid 318
E/CtrlSupplicant( 1958): Access OK "@android:wpa_wlan0"
E/CtrlSupplicant( 1958): Succeed to open control connection
E/CtrlSupplicant( 1958): Succeed to open monitor connection
D/WfdsMonitor( 1958): Supplicant connection established
D/WfdsService( 1958): Connected to the supplicant for wfds
W/Process ( 1039): Unable to open /proc/6282/status
D/WifiService( 1039): New client listening to asynchronous messages
I/ActivityManager( 1039): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6285 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/BluetoothAdapterService( 6181): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1127cb12
E/WifiStateMachine( 1039):  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
E/WifiStateMachine( 1039):  DisconnectedState CMD_START_DRIVER 0 0
E/WifiStateMachine( 1039):  ConnectModeState CMD_START_DRIVER 0 0
E/WifiStateMachine( 1039):  DriverStartedState CMD_START_DRIVER 0 0
D/LGWifiP2pService( 1039): sending p2p connection changed broadcast
E/WifiStateMachine( 1039):  DisconnectedState what:132106 1 0
E/WifiStateMachine( 1039):  ConnectModeState what:132106 1 0
E/WifiStateMachine( 1039):  DriverStartedState what:132106 1 0
I/WifiServerServiceExt( 1039): setWifiDualbandAPConnection band : 1
E/wpa_supplicant( 6239): nWIFIDualbandAPConnection: 1
I/art     (  347): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 237us total 11.073ms
E/WifiStateMachine( 1039):  DisconnectedState what:132096 -100 0
E/WifiStateMachine( 1039):  ConnectModeState what:132096 -100 0
D/A2dpService( 6181): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 6181): classInitNative: succeeds
E/WifiStateMachine( 1039):  DriverStartedState what:132096 -100 0
I/WifiServerServiceExt( 1039): set CMD_DISCONNECT_RSSI_LVL : -100
E/wpa_supplicant( 6239): disconnect_rssi_lvl: -100
V/Avrcp   ( 6181): make
D/BluetoothA2dp( 1039): Proxy object connected
D/Avrcp   ( 6181): [BTUI] Use Native AVRCP : init jni
I/bluedroid-qcom( 6181): get_profile_interface avrcp
V/WfdStateTracker( 1958): WfdStateTracker handleDirectStateChangedEvent: 2
D/WifiScanningService( 1039): SCAN_AVAILABLE : 3
D/RttService( 1039): SCAN_AVAILABLE : 3
D/RttService( 1039): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService( 1039): DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL( 1039): startHal
E/wifi    ( 1039): getStaticLongField sWifiHalHandle 0x94e6c99c
E/WifiHAL ( 1039): Could not connect handle
D/wifi    ( 1039): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x5012c2
I/WifiNative-HAL( 1039): Could not start hal
E/WifiScanningService( 1039): could not start HAL
D/WfdsService( 1958): WifiP2pState is changed : true
D/WfdsService( 1958): Receive the WFDS_ENABLE Method
D/WfdsService( 1958): Set the WFDS Monitor: true
D/WfdsService( 1958): Connected to the supplicant for wfds
D/WfdsJNI ( 1958): doCommand: WFDS_SET TRUE
I/wpa_supplicant( 6239): WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
D/WfdsJNI ( 1958): doCommand: WFDS_GET_MAC_ADDRESS
I/wpa_supplicant( 6239): WFDS: wfds_supplicant_wfds_cmd: cmd = GET_MAC_ADDRESS
I/art     (  347): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 195us total 10.420ms
D/WifiNative-p2p0( 1039): doBoolean: SET persistent_reconnect 1
D/WifiNative-p2p0( 1039): SET persistent_reconnect 1: returned true
D/WfdsJNI ( 1958): doCommand: IFNAME=wlan0 GET_CAPABILITY channels
D/WifiNative-p2p0( 1039): doBoolean: SET device_name G3-1
D/WfdsService( 1958): selectPreferredScanChannel [36]
D/WifiNative-p2p0( 1039): SET device_name G3-1: returned true
D/LGWifiP2pService( 1039): [LGE_P2P] initializeP2pSettings() check postfix
D/LGWifiP2pService( 1039): before postfix = G3-1
D/WifiServerServiceExt( 1039): postfix byte check : 4
D/LGWifiP2pService( 1039): after postfix = G3-1
D/WifiNative-p2p0( 1039): doBoolean: SET p2p_ssid_postfix -G3-1
D/WifiNative-p2p0( 1039): SET p2p_ssid_postfix -G3-1: returned true
D/WifiNative-p2p0( 1039): doBoolean: SET device_type 10-0050F204-5
D/WifiNative-p2p0( 1039): SET device_type 10-0050F204-5: returned true
D/WifiNative-p2p0( 1039): doBoolean: SET config_methods virtual_push_button physical_display keypad
D/WifiNative-p2p0( 1039): SET config_methods virtual_push_button physical_display keypad: returned true
D/WifiNative-p2p0( 1039): doBoolean: P2P_SET conc_pref p2p
D/WifiNative-p2p0( 1039): P2P_SET conc_pref p2p: returned true
D/WifiNative-HAL( 1039): p2pGetDeviceAddress
D/WifiNative-HAL( 1039): p2pGetDeviceAddress returning 
D/LGWifiP2pService( 1039): DeviceAddress: 
D/WifiNative-p2p0( 1039): doBoolean: P2P_FLUSH
D/WifiNative-p2p0( 1039): P2P_FLUSH: returned false
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_FLUSH
D/WifiNative-p2p0( 1039): P2P_SERVICE_FLUSH: returned true
D/WifiNative-p2p0( 1039): doString: [LIST_NETWORKS]
D/WfdsService( 1958): STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7b:60:ac
V/AudioManager( 6181): registerRemoteController: size of Media player list: 0
E/AudioManager( 6181): No RCC entry present to update
E/RemoteController( 6181): Cannot set synchronization mode on an unregistered RemoteController
I/art     (  347): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 204us total 9.453ms
D/WfdsService( 1958): WIFI_P2P_CONNECTION_CHANGED_ACTION
D/WfdsService( 1958): isConnected: false
I/BluetoothAvrcpQcomServiceJni( 6181): classInitQcomNative: succeeds
D/WifiNative-p2p0( 1039):    returned OK
D/WifiNative-p2p0( 1039): doBoolean: SAVE_CONFIG
D/WifiNative-p2p0( 1039): SAVE_CONFIG: returned false
D/LGWifiP2pService( 1039): sending p2p persistent groups changed broadcast
I/WfdStateTracker( 1958): handleP2pThisDeviceChanged
D/LGWifiP2pService( 1039): InactiveState
D/WfdsService( 1958): WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
D/LGWifiP2pService( 1039): InactiveState{ when=-9ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
D/LGBluetoothAvrcpQcomAdapter( 6181): [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
D/LGWifiP2pService( 1039): P2pEnabledState{ when=-9ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
I/BluetoothAvrcpQcomServiceJni( 6181): initQcomNative: succeeds
D/WfdsService( 1958): Update P2p Interface State: 3
D/WifiNative-p2p0( 1039): doBoolean: DRIVER COUNTRY CZ
V/LGMDMManager( 6181): Create singleton instance
I/BluetoothAdapterState( 6181): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
D/LGBluetoothAvrcpQcomAdapter( 6181): [BTUI] [+] updateMediaPlayerInfo
D/WifiNative-p2p0( 1039): DRIVER COUNTRY CZ: returned true
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=-1ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): DefaultState{ when=-1ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): InactiveState{ when=-1ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=-1ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): DefaultState{ when=-1ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): InactiveState{ when=-1ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=-1ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): DefaultState{ when=-1ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 6239): wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
I/wpa_supplicant( 6239): p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
I/wpa_supplicant( 6239): [LGE_PATCH] driver_cmd() country:CZ
I/wpa_supplicant( 6239): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiServerServiceExt( 1039): No p2p device connected
I/wpa_supplicant( 6239): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WfdsMonitor( 1958): Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
D/WfdsMonitor( 1958): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WfdsMonitor( 1958): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WifiMonitor( 1039): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
E/WifiMonitor( 1039): WifiMonitor:p2p0 cnt=2 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1039): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1039): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
D/WifiMonitor( 1039): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1039): WifiMonitor:p2p0 cnt=3 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1039): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1039): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiMonitor( 1039): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1039): WifiMonitor:p2p0 cnt=4 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1039): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1039): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiStateMachine( 1039):  DisconnectedState CMD_SET_COUNTRY_CODE 1 0 cz
E/WifiStateMachine( 1039):  ConnectModeState CMD_SET_COUNTRY_CODE 1 0 cz
E/WifiStateMachine( 1039):  DriverStartedState CMD_SET_COUNTRY_CODE 1 0 cz
D/WifiNative-wlan0( 1039): doBoolean: DRIVER COUNTRY CZ
I/wpa_supplicant( 6239): wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
I/wpa_supplicant( 6239): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
D/LGWifiP2pService( 1039): InactiveState{ when=-2ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=-5ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): DefaultState{ when=-5ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 6239): [LGE_PATCH] driver_cmd() country:CZ
I/wpa_supplicant( 6239): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
I/wpa_supplicant( 6239): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
W/WfdsService( 1958): DefaultState - msg [9441285] is not handled
D/WifiNative-wlan0( 1039): DRIVER COUNTRY CZ: returned true
D/WfdsMonitor( 1958): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WfdsMonitor( 1958): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=5 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
E/WifiMonitor( 1039): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
E/WifiMonitor( 1039): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
D/WifiMonitor( 1039): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1039): WifiMonitor:p2p0 cnt=6 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiStateMachine( 1039):  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
E/WifiMonitor( 1039): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1039): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiMonitor( 1039): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1039): WifiMonitor:p2p0 cnt=7 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1039): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1039): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiStateMachine( 1039):  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine( 1039):  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
D/WifiNative-wlan0( 1039): doBoolean: DRIVER SETBAND 0
I/wpa_supplicant( 6239): wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
I/wpa_supplicant( 6239): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=8 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
E/WifiMonitor( 1039): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
E/WifiMonitor( 1039): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
D/WifiNative-wlan0( 1039): DRIVER SETBAND 0: returned true
D/WifiNative-wlan0( 1039): doBoolean: BSS_FLUSH 0
D/WifiNative-wlan0( 1039): BSS_FLUSH 0: returned true
D/WifiNative-wlan0( 1039): doBoolean: SCAN
D/WifiNative-wlan0( 1039): SCAN: returned false
E/WifiStateMachine( 1039):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=109203  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine( 1039):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=109247  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine( 1039):  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1039):  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1039):  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1039):  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1039):  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
V/SIM_STK ( 1039): Menu title from STK is T-Mobile
V/SIM_STK ( 1039): Menu title from STK is T-Mobile
I/art     ( 1039): Explicit concurrent mark sweep GC freed 34438(1764KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 2.244ms total 130.574ms
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WifiServerServiceExt( 1039): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1039): setSupplicantStateSCANNING
E/ActivityThread( 6263): Failed to find provider info for com.lge.lgaccount.provider
W/LG Account v2.2( 6263): No ProfileInfo entries
I/LG Account v2.2( 6263): isEnabled: false
I/Feature ( 6263): [Lifetracker]ver: 4.21.112(40211120)
I/Feature ( 6263): [Lifetracker]Country: EU
I/StatusBar.NetworkController( 1444): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/Feature ( 6263): [Lifetracker]Operator: OPEN
I/Feature ( 6263): [Lifetracker]Ranking support: false
I/Feature ( 6263): [Lifetracker]Comfort support: false
I/StatusBar.NetworkController( 1444): mWifiConnected = false, mWifiLevel = 0
I/Feature ( 6263): [Lifetracker]Accessory: true
I/Feature ( 6263): [Lifetracker]Health device: true
I/Feature ( 6263): [Lifetracker]Extra Pedometer: false
I/Feature ( 6263): [Lifetracker]Blood glucose device: false
I/Feature ( 6263): [Lifetracker]Device Number: 3
D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
D/BluetoothPermissionRequest( 6218): onReceive
D/LGBluetoothFeatureConfig( 6218):  get() - isFeatureLoaded : false
V/FormManager( 6244): Network unavailable.
W/FormManager( 6244): Network not available. Please check & try again.
V/FormManager( 6244): Network unavailable.
I/ActivityManager( 1039): Killing 5458:com.lge.appbox.client/u0a11 (adj 15): empty #17
D/BluetoothManagerService( 1039): Message: 20
D/BluetoothManagerService( 1039): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3f2ef5e2:true
D/PCSuite ( 6285): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
W/ActivityManager( 1039): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
W/libprocessgroup( 1039): failed to open /acct/uid_10011/pid_5458/cgroup.procs: No such file or directory
I/ActivityManager( 1039): Killing 5480:com.android.contacts/u0a19 (adj 15): empty #17
D/LGBluetoothResetSettingReceiver( 6218): return without doing reset settings.
D/LGBluetoothAvrcpQcomAdapter( 6181): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 6181): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6181): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 6181): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 6181): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 6181): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6181): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 6181): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6181): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 6181): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6181): [BTUI] [-] updateMediaPlayerInfo
I/BluetoothA2dpServiceJni( 6181): classInitNative
I/BluetoothA2dpServiceJni( 6181): classInitNative: succeeds
D/A2dpStateMachine( 6181): make
E/wpa_supplicant( 6239): USIM:  scard_init function
I/bluedroid-qcom( 6181): get_profile_interface a2dp
I/GKI_LINUX( 6181): gki_task_entry task_id=2 [A2DP-MEDIA] starting
I/wpa_supplicant( 6239): Trying to associate with SSID 'NG700'
I/LGBluetoothA2dpServiceJni( 6181): classInitNative: succeeds
I/LGBluetoothA2dpAdapter( 6181): [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=9 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1039): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1039): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=10 dispatchEvent: WPS-AP-AVAILABLE 
D/BluetoothAdapterService( 6181): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1127cb12
W/WifiMonitor( 1039): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=11 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
I/BluetoothHidServiceJni( 6181): classInitNative: succeeds
D/A2dpStateMachine( 6181): Enter Disconnected: -2
E/WifiStateMachine( 1039):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
D/HidService( 6181): Received start request. Starting profile...
I/bluedroid-qcom( 6181): get_profile_interface hidhost
D/BluetoothAdapterService( 6181): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1127cb12
E/WifiStateMachine( 1039):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine( 1039):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
E/WifiStateMachine( 1039):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
I/WifiNative-HAL( 1039): startHal
E/wifi    ( 1039): getStaticLongField sWifiHalHandle 0x989788cc
I/BluetoothHealthServiceJni( 6181): classInitNative: succeeds
E/WifiHAL ( 1039): Could not connect handle
D/wifi    ( 1039): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x3022c6
I/WifiNative-HAL( 1039): Could not start hal
D/WifiNative-wlan0( 1039): doString: [BSS RANGE=0- MASK=0x21987]
D/HealthService( 6181): Received start request. Starting profile...
I/bluedroid-qcom( 6181): get_profile_interface health
I/LGBluetoothHealthServiceJni( 6181): classInitNative: succeeds
D/BluetoothAdapterService( 6181): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1127cb12
I/BluetoothPanServiceJni( 6181): classInitNative(L105): succeeds
D/PanService( 6181): Received start request. Starting profile...
D/BluetoothPanServiceJni( 6181): initializeNative(L110): pan
I/bluedroid-qcom( 6181): get_profile_interface pan
W/libprocessgroup( 1039): failed to open /acct/uid_10019/pid_5480/cgroup.procs: No such file or directory
E/WifiStateMachine( 1039):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 11 0 rt=109603  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
I/LGBluetoothPanAdapter( 6181): [BTUI] getInstance : create [LGBluetoothPanAdapter]
D/BluetoothAdapterService( 6181): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1127cb12
D/HeadsetStateMachine( 6181): Proxy object connected
D/LGBluetoothHfpAdapter( 6181): [BTUI] queryPhoneState
D/LGBluetoothHfpAdapter( 6181): Try to query the phonestate on bind
D/BluetoothPhoneService.BluetoothLTECall( 1852):  call mBluetoothHeadset.phoneStateChanged()
E/WifiStateMachine( 1039):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 11 0 rt=109615  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
I/BtGatt.JNI( 6181): classInitNative(L901): classInitNative: Success!
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/BtGatt.DebugUtils( 6181): handleDebugAction() action=null
D/BtGatt.GattService( 6181): Received start request. Starting profile...
D/BtGatt.GattService( 6181): start()
I/bluedroid-qcom( 6181): get_profile_interface gatt
W/BluetoothHeadset( 1852): Proxy not attached to service
D/BtGatt.AdvertiseManager( 6181): advertise manager created
D/BluetoothHeadset( 1852): java.lang.Throwable
D/BluetoothHeadset( 1852): 	at android.bluetooth.BluetoothHeadset.phoneStateChanged(BluetoothHeadset.java:826)
D/BluetoothHeadset( 1852): 	at com.android.phone.BluetoothPhoneService$BluetoothLTECall.handleQueryPhoneState(BluetoothPhoneService.java:1527)
D/BluetoothHeadset( 1852): 	at com.android.phone.BluetoothPhoneService$BluetoothLTECall.access$700(BluetoothPhoneService.java:1360)
D/BluetoothHeadset( 1852): 	at com.android.phone.BluetoothPhoneService$1.handleMessage(BluetoothPhoneService.java:268)
D/BluetoothHeadset( 1852): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BluetoothHeadset( 1852): 	at android.os.Looper.loop(Looper.java:135)
D/BluetoothHeadset( 1852): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
D/BluetoothHeadset( 1852): 	at java.lang.reflect.Method.invoke(Native Method)
D/BluetoothHeadset( 1852): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/BluetoothHeadset( 1852): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
D/BluetoothHeadset( 1852): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/WifiServerServiceExt( 1039): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1039): setSupplicantStateASSOCIATING
I/StatusBar.NetworkController( 1444): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1444): mWifiConnected = false, mWifiLevel = 0
I/ActivityManager( 1039): Killing 5835:com.lge.email/u0a23 (adj 15): empty #17
D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1444): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1444): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
I/wpa_supplicant( 6239): wlan0: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=12 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1039): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=13 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=14 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1039):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 12 0 rt=109636  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1039):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 12 0 rt=109636  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1039):  DisconnectedState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=109637
E/WifiStateMachine( 1039):  ConnectModeState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=109638
E/WifiStateMachine( 1039):  DriverStartedState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=109638
E/WifiStateMachine( 1039):  SupplicantStartedState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=109639
E/WifiStateMachine( 1039):  DefaultState CMD_ASSOCIATED_BSSID 13 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=109639
E/WifiStateMachine( 1039):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 14 0 rt=109640  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
V/WiFiOffLoadBroadcast( 6218): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
D/WifiService( 1039): New client listening to asynchronous messages
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
I/wpa_supplicant( 6239): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=15 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/wpa_supplicant( 6239): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1039): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=16 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1039): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=17 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1039): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=18 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/LgDataFeature( 6218): LgDataFeature() Constructor: none
D/LgDataFeature( 6218): LgDataFeature() Constructor Done, null
D/WiFiOffLoadUpdatePriority( 6218): remove : truetruetrue
D/Tethering( 1039): sendTetherStateChangedBroadcast 1, 0, 0
W/libprocessgroup( 1039): failed to open /acct/uid_10023/pid_5835/cgroup.procs: No such file or directory
D/BluetoothAdapterService( 6181): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1127cb12
D/BluetoothAdapterService( 6181): Profile still not running:com.android.bluetooth.gatt.GattService
I/StatusBar.NetworkController( 1444): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1444): mWifiConnected = false, mWifiLevel = 0
D/BluetoothAdapterService( 6181): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1127cb12
I/LGBluetoothMapAdapter( 6181): [BTUI] getInstance : create [LGBluetoothMapAdapter]
V/BluetoothMapService( 6181): BluetoothMapBinder()
D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
D/BluetoothMapService( 6181): Received start request. Starting profile...
D/BluetoothMapService( 6181): start()
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
E/WifiStateMachine( 1039):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 14 0 rt=109725  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
D/BluetoothMapEmailSettingsLoader( 6181): Found 0 applications
D/BluetoothMapEmailAppObserver( 6181): createReceiver()
I/StatusBar.NetworkController( 1444): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1444): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/BluetoothMapEmailAppObserver( 6181): initObservers()
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/BluetoothMapEmailAppObserver( 6181): getEnabledAccountItems()
D/WifiServerServiceExt( 1039): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1039): setSupplicantStateASSOCIATED
D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
D/BluetoothAdapterService( 6181): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1127cb12
E/WifiStateMachine( 1039):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 15 0 rt=109735  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1039):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 15 0 rt=109735  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1039):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=109736
E/WifiStateMachine( 1039):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=109737
D/BluetoothAdapterService( 6181): Profile still not running:com.android.bluetooth.gatt.GattService
D/HeadsetStateMachine( 6181): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 6181): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 6181): Disconnected process message: 11, size: 0
D/WifiNative-wlan0( 1039): doString: [STATUS]
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=19 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/BluetoothAdapterService( 6181): Profile still not running:com.android.bluetooth.gatt.GattService
D/WifiNative-wlan0( 1039):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
D/BluetoothAdapterService( 6181): Profile still not running:com.android.bluetooth.gatt.GattService
I/WifiServiceExtension( 1039): setVHTCapabilityType  : false
D/BluetoothAdapterService( 6181): Profile still not running:com.android.bluetooth.gatt.GattService
V/PanService( 6181): [BTUI] SIM Extra State :ABSENT
D/LGBluetoothOppAdapter( 6181): [BTUI] getInstance : create [LGBluetoothOppAdapter]
D/BluetoothAdapterService( 6181): Profile still not running:com.android.bluetooth.map.BluetoothMapService
V/BluetoothMapService( 6181): Handler(): got msg=1
D/BluetoothAdapterState( 6181): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid-qcom( 6181): enable
I/GKI_LINUX( 6181): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 6181): btu_task pending for preload complete event
I/WifiServerServiceExt( 1039): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1039): setKeepAlivePacketInterval msec : 60
I/bt_hci_bdroid( 6181): init
V/BluetoothFtpReceiver( 6181): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6181): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 6181): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 6181): SapReceiver onReceive 
V/BluetoothSapReceiver( 6181): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6181):  Bluetooth Adapter state = 11
I/bt_vendor( 6181): bt-vendor : init
I/bt_vendor( 6181): bt-vendor : get_bt_soc_type
E/bt_vendor( 6181): get_bt_soc_type: Failed to get soc type
I/bt_vendor( 6181): init: Local BD Address : c0:64:73:54:3f:58
D/bt_userial_mct( 6181): userial_init
D/bt_hci_bdroid( 6181): set_power 1
I/bt_vendor( 6181): bt-vendor : BT_VND_OP_POWER_CTRL: On
I/bt_vendor( 6181): Starting hciattach daemon
I/bt_vendor( 6181): try to set true
W/sh      ( 6329): type=1400 audit(0.0:155): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/sh      ( 6329): type=1400 audit(0.0:156): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/ConnectivityService( 1039): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService( 1039): Got NetworkAgent Messenger
E/WifiConfigStore( 1039): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1039): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1039): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1039): doBoolean: SAVE_CONFIG
D/ConnectivityService( 1039): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1039): NetworkAgent connected
I/qcom-bluetooth( 6331): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
I/ActivityManager( 1039): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6333 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/WifiNative-wlan0( 1039): SAVE_CONFIG: returned true
E/WifiConfigStore( 1039): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1039): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1039): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1039): doBoolean: SAVE_CONFIG
I/StatusBar.NetworkController( 1444): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1444): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/WifiNative-wlan0( 1039): SAVE_CONFIG: returned true
I/StatusBar.NetworkController( 1444): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1444): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
D/CommandListener(  313): Setting iface cfg
E/WifiStateMachine( 1039): Start Dhcp Watchdog 1
E/WifiStateMachine( 1039):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=109804  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1039):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=109804  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1039):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=109805  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1039):  ObtainingIpState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1039):  L2ConnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1039):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/DhcpStateMachine( 1039): StoppedState
D/DhcpStateMachine( 1039): StoppedState{ when=-4ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1039): WaitBeforeStartState
E/WifiStateMachine( 1039):  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1039):  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1039):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1039):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1039):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1039):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiServerServiceExt( 1039): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1039): setSupplicantStateFOUR_WAY_HANDSHAKE
D/WifiServerServiceExt( 1039): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1039): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1039):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=109813  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1039):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=109813  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1039):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=109814  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1039):  ObtainingIpState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:-926353376] from screen [on:0 period:-926353376]
E/WifiStateMachine( 1039):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-926353373]
I/WifiNative-HAL( 1039): startHal
E/wifi    ( 1039): getStaticLongField sWifiHalHandle 0x989788bc
E/WifiHAL ( 1039): Could not connect handle
D/wifi    ( 1039): halHandle = 0x0, mVM = 0xb487c280, mCls = 0x5021da
I/WifiNative-HAL( 1039): Could not start hal
D/WifiNative-wlan0( 1039): doString: [SIGNAL_POLL]
D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
I/qcom-bluetooth( 6355): /system/etc/init.qcom.bt.sh: Transport : smd 
I/qcom-bluetooth( 6356): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
D/ConnectivityService( 1039): updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
E/WifiStateMachine( 1039):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1039): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
D/WifiServerServiceExt( 1039): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1039): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1039):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
E/WifiStateMachine( 1039):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
D/WifiNative-wlan0( 1039): doBoolean: DRIVER SETSUSPENDMODE 0
W/ResourcesManager( 6333): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
I/qcom-bluetooth( 6358): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
I/ActivityManager( 1039): Killing 5501:com.android.gallery3d/u0a27 (adj 15): empty #17
I/qcom-bluetooth( 6359): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
I/wpa_supplicant( 6239): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1039): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1039): doBoolean: SET ps 0
D/WifiNative-wlan0( 1039): SET ps 0: returned true
D/WifiNative-wlan0( 1039): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 6239): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1039): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1039): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1039): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1039): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
V/LgDhcpStateMachineHelper( 1039): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700" is not exist.
E/WifiStateMachine( 1039):  ObtainingIpState CMD_SAVE_CONFIG uid=1000 0 0
E/WifiStateMachine( 1039):  L2ConnectedState CMD_SAVE_CONFIG uid=1000 0 0
E/WifiStateMachine( 1039):  ConnectModeState CMD_SAVE_CONFIG uid=1000 0 0
D/WifiNative-wlan0( 1039): doBoolean: SAVE_CONFIG
D/LGWifiP2pService( 1039): InactiveState{ when=-3ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3c56cba8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=-3ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3c56cba8 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1039): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1039): DHCP Start wake lock is acquired.
I/qcom-bluetooth( 6360): /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
D/WifiNative-wlan0( 1039): SAVE_CONFIG: returned true
D/WiFiOffLoadUpdatePriority( 6218): remove1
V/WiFiOffLoadSharedPrefsUtils( 6218): save remove
I/qcom-bluetooth( 6361): /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
D/WiFiOffLoadBroadcast( 6218): mLast,ConnectedNetwork from SharedPrefsUtils for wifioffloading : null
D/WiFiOffLoadBroadcast( 6218): S: false, R: false
I/[SystemUI]TimeTickManager( 1444): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1444): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1444): called onTimeUpdated()
I/[SystemUI]Clock( 1444): called onTimeUpdated()
I/LgeClockWidgetControlView( 1444): called onTimeUpdated()
I/[SystemUI]DateView( 1444): called onTimeUpdated()
I/[SystemUI]DateView( 1444): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1444): handleTimeUpdate
I/libmdmdetect( 6363): ESOC framework not supported
E/Diag_Lib( 6363):  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
D/bthci_qcomm_linux( 6363): [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:64:C0)
D/bthci_qcomm_common( 6363): [BTUI] bt_hci_qcomm_init:
D/bthci_qcomm_common( 6363): [BTUI]     BDADDR: 58:3F:54:73:64:C0
D/bthci_qcomm_common( 6363): [BTUI]     BR/EDR: Class 1
D/bthci_qcomm_common( 6363): [BTUI]     LE: Class 2
D/bthci_qcomm_common( 6363): [BTUI]     Ref Clock: 32M
D/btqsocnvmtags( 6363): [BTUI] init_riva_entries: set NORMAL power settings
W/libprocessgroup( 1039): failed to open /acct/uid_10027/pid_5501/cgroup.procs: No such file or directory
D/AuthorizationBluetoothService( 2123): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
E/WifiStateMachine( 1039):  ObtainingIpState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1039):  L2ConnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine( 1039):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
,D/WiFiOffLoadUpdatePriority( 6218): saved SSID: "NG700"
D/WiFiOffLoadUpdatePriority( 6218): connected SSID: null
D/WifiServerServiceExt( 1039): SUPPLICANT_STATE_CHANGED_ACTION
,D/WifiServerServiceExt( 1039): setSupplicantStateCOMPLETED
D/WiFiOffLoadUpdatePriority( 6218): private wpa: "NG700" 300
D/WifiServiceImplEx( 1039): addOrUpdateNetwork pid=6218, uid=1000, packageName=android.uid.system:1000
E/addOrUpdateNetwork( 1039):  uid = 1000 SSID "NG700" nid=0
E/WifiStateMachine( 1039):  ObtainingIpState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=2 any is current
E/WifiStateMachine( 1039):  L2ConnectedState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=2 any is current
E/WifiStateMachine( 1039):  ConnectModeState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=2 any is current
E/WifiConfigStore( 1039):  key="NG700"WPA_PSK netId=0 uid=0/1000
D/WifiServerServiceExt( 1039): addOrUpdateNetwork: mThisIsFirstEnableing = false
D/WifiNative-wlan0( 1039): doBoolean: SET_NETWORK 0 ssid 4e47373030
D/WifiNative-wlan0( 1039): SET_NETWORK 0 ssid 4e47373030: returned true
E/WifiConfigStore( 1039): Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1039): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1039): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1039): doBoolean: SET_NETWORK 0 key_mgmt WPA-PSK
,D/WifiNative-wlan0( 1039): SET_NETWORK 0 key_mgmt WPA-PSK: returned true
D/WifiNative-wlan0( 1039): doBoolean: SET_NETWORK 0 proto WPA RSN
D/WifiNative-wlan0( 1039): SET_NETWORK 0 proto WPA RSN: returned true
D/WifiNative-wlan0( 1039): doBoolean: SET_NETWORK 0 pairwise TKIP CCMP
D/WifiNative-wlan0( 1039): SET_NETWORK 0 pairwise TKIP CCMP: returned true
D/WifiNative-wlan0( 1039): doBoolean: SET_NETWORK 0 group WEP40 WEP104 TKIP CCMP
D/WifiNative-wlan0( 1039): SET_NETWORK 0 group WEP40 WEP104 TKIP CCMP: returned true
D/WifiNative-wlan0( 1039): doBoolean: SET_NETWORK 0 priority 300
D/WifiNative-wlan0( 1039): SET_NETWORK 0 priority 300: returned true
E/WifiConfigStore( 1039): will read network variables netId=0
E/WifiConfigStore( 1039): writeIpAndProxyConfigurationsOnChange: "NG700" -> "NG700" path: /data/misc/wifi/ipconfig.txt
,E/WifiConfigStore( 1039):  writeKnownNetworkHistory() num networks:1 needWrite=false
D/WiFiOffLoadUpdatePriority( 6218):  ssid "NG700" prio 300
D/WiFiOffLoadUpdatePriority( 6218): configuration updated: 0
E/WifiStateMachine( 1039):  ObtainingIpState CMD_SAVE_CONFIG uid=1000 0 0
E/WifiStateMachine( 1039):  L2ConnectedState CMD_SAVE_CONFIG uid=1000 0 0
E/WifiStateMachine( 1039):  ConnectModeState CMD_SAVE_CONFIG uid=1000 0 0
D/WifiNative-wlan0( 1039): doBoolean: SAVE_CONFIG
I/rmt_storage(  310): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  310): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  310): wakelock acquired: 1, error no: 42
I/rmt_storage(  310): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
,D/WifiNative-wlan0( 1039): SAVE_CONFIG: returned true
D/WiFiOffLoadUpdatePriority( 6218): configuration saved: true
D/PCSuite ( 6285): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6218): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
D/WiFiOffLoadBroadcast( 6218): MCCMNC not supported: null
W/FormManager( 6244): Network not available. Please check & try again.
,D/LGDMClient( 3247): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 3247): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 3247): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,W/ContextImpl( 3247): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/FormManager( 6244): Network unavailable.
V/FormManager( 6244): Network unavailable.
D/PostponalbeReceiver( 5124): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/LGDMClient( 3247): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/LGDMClient( 3247): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 3247): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,D/DhcpStateMachine( 1039): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper( 1039): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1039): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
I/PCSuite ( 6285): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6285): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6285): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6218): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6218): MCCMNC not supported: null
I/ActivityManager( 1039): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6372 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,W/dhcpcd  ( 6370): type=1400 audit(0.0:157): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 6370): type=1400 audit(0.0:158): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/rmt_storage(  310): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  310): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
I/rmt_storage(  310): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 22
I/rmt_storage(  310): 
I/rmt_storage(  310): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
E/Diag_Lib(  867): [IMS_FATAL]| 3347 | 888 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
I/dhcpcd  ( 6370): version 5.5.6 starting
,E/dhcpcd  ( 6370): get_duid: m
D/dhcpcd  ( 6370): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 6370): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
W/ResourcesManager( 6372): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/QRemote ( 6372): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,D/dhcpcd  ( 6370): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
,D/dhcpcd  ( 6370): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 6370): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/dhcpcd  ( 6370): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 6370): wlan0: sending REQUEST (xid 0xfb394d94), next in 4.67 seconds
D/QRemote ( 6372): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
I/QRemote ( 6372): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 6372): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 6372): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 6372): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 6372): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 6372): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6372): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6372): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6372): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,V/[BNRBootReceiver]( 5978): boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,D/BNRAndroBeam( 5978): [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
D/QRemote ( 6372): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
V/[BNRBootReceiver]( 5978): Boot Receiver Return
D/PostponalbeReceiver( 5124): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/QRemote ( 6372): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
V/WiFiOffLoadBroadcast( 6218): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6218): MCCMNC not supported: null
D/QRemote ( 6372): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6372): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6372): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/WiFiOffLoadBroadcast( 6218): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
D/WiFiOffLoadBroadcast( 6218): Not supported operator for automatic switch
D/PostponalbeReceiver( 5124): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 6218): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6218): MCCMNC not supported: null
D/QRemote ( 6372): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6372): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6372): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 5124): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6218): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6218): MCCMNC not supported: null
D/QRemote ( 6372): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6372): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6372): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/UsbSettingsReceiver( 6218): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,D/UsbSettingsReceiver( 6218): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6218): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6218): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6218): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 6218): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6218): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6218): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6218): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6218): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6218): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 6218): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 5124): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6218): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6218): MCCMNC not supported: null
,D/QRemote ( 6372): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6372): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6372): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 5124): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 6218): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6218): MCCMNC not supported: null
,D/QRemote ( 6372): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6372): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6372): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 5124): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6218): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6218): MCCMNC not supported: null
D/QRemote ( 6372): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6372): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6372): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 5124): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6218): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6218): MCCMNC not supported: null
D/QRemote ( 6372): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6372): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6372): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
V/QRemote ( 6372): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6372): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 6372): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
D/LgDataFeature( 6372): LgDataFeature() Constructor: none
D/LgDataFeature( 6372): LgDataFeature() Constructor Done, null
,V/SoundPool( 6372): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
,V/SoundPool( 6372): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 6372): create sampleID=1, fd=32, offset=17813 length=10857164
V/SoundPool( 6372): doLoad: loading sample sampleID=1
V/SoundPool( 6372): Start decode
V/MediaPlayer[Native]( 6372): decode(32, 10857164, 17813)
I/QRemote ( 6372): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
V/MediaPlayerService(  318): decode(23, 10857164, 17813)
W/BrunchPlayerTypeImpl(  318): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  318): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  318): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  318): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  318): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  318): player type = 3
V/AwesomePlayer(  318): AwesomePlayer create()
V/AwesomePlayer(  318): reset_l() 
V/AwesomePlayer(  318): cancelPlayerEvents
V/AwesomePlayer(  318): setAudioSink() 
V/AwesomePlayer(  318): reset_l() 
V/AudioCache(  318): notify(0xb5474bc0, 8, 0, 0)
V/AudioCache(  318): ignored
V/AwesomePlayer(  318): cancelPlayerEvents
D/Utils   (  318): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  318): setDataSource_l dataSource
V/LGParserOSAL(  318): SniffLGParser start
V/LGParserOSAL(  318): MainType:5, SubType=0
V/LGParserOSAL(  318): #### check Mime : application/ogg
V/LGParserOSAL(  318): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  318): Use LGExtractor :application/ogg 
D/QRemote ( 6372): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
D/UEI.SmartControl( 5865): QS Service created
,I/UEI.SmartControl( 5865): Service initServices...
D/UEI.SmartControl( 5865): QS start get config
E/QRemote ( 6372): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6372): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
V/LGParserOSAL(  318): supported mime: application/ogg
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
,D/OMXCodec(  318): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
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
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb1434290 on input port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc0b0 on input port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc790 on input port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc7e0 on input port
V/OMXCodec(  318): allocateBuffersOnPort portIndex=1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc830 on output port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc8d0 on output port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc920 on output port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb14fcab0 on output port
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
V/AudioCache(  318): notify(0xb5474bc0, 5, 0, 0)
V/AudioCache(  318): ignored
V/AudioCache(  318): notify(0xb5474bc0, 1, 0, 0)
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
V/OM,XCodec(  318): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  318): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  318): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974795824
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974795984
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974796064
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974796464
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  318): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  318): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  318): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  318): allocateBuffersOnPort portIndex=1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc920 on output port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc8d0 on output port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc830 on output port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb14fcd80 on output port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  318): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  318): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  318): notify(0xb5474bc0, 6, 0, 0)
V/AudioCache(  318): ignored
V/MediaPlayerService(  318): wait for playback complete
V/AudioCache(  318): write(0xb57bd000, 4096)
V/AudioCache(  318): memcpy(0xaf1ff000, 0xb57bd000, 4096)
,V/AudioCache(  318): write(0xb57bd000, 4096)
V/AudioCache(  318): memcpy(0xaf200000, 0xb57bd000, 4096)
V/AudioCache(  318): write(0xb57bd000, 4096)
V/AudioCache(  318): memcpy(0xaf201000, 0xb57bd000, 4096)
V/AudioCache(  318): write(0xb57bd000, 4096)
V/AudioCache(  318): memcpy(0xaf202000, 0xb57bd000, 4096)
V/AudioCache(  318): write(0xb57bd000, 4096)
,V/AudioCache(  318): memcpy(0xaf203000, 0xb57bd000, 4096)
V/AudioCache(  318): write(0xb57bd000, 4096)
V/AudioCache(  318): memcpy(0xaf204000, 0xb57bd000, 4096)
V/AudioCache(  318): write(0xb57bd000, 4096)
V/AudioCache(  318): memcpy(0xaf205000, 0xb57bd000, 4096)
V/AudioCache(  318): write(0xb57bd000, 4096)
V/AudioCache(  318): memcpy(0xaf206000, 0xb57bd000, 4096)
V/AudioCache(  318): write(0xb57bd000, 4096)
V/AudioCache(  318): memcpy(0xaf207000, 0xb57bd000, 4096)
V/AudioCache(  318): write(0xb57bd000, 4096)
V/AudioCache(  318): memcpy(0xaf208000, 0xb57bd000, 4096)
V/AudioCache(  318): write(0xb57bd000, 4096)
V/AudioCache(  318): memcpy(0xaf209000, 0xb57bd000, 4096)
V/AudioCache(  318): write(0xb57bd000, 4096)
V/AudioCache(  318): memcpy(0xaf20a000, 0xb57bd000, 4096)
,V/AudioCache(  318): write(0xb57bd000, 4096)
V/AudioCache(  318): memcpy(0xaf20b000, 0xb57bd000, 4096)
V/AudioCache(  318): write(0xb57bd000, 4096)
V/AudioCache(  318): memcpy(0xaf20c000, 0xb57bd000, 4096)
V/AudioCache(  318): write(0xb57bd000, 4096)
V/AudioCache(  318): memcpy(0xaf20d000, 0xb57bd000, 4096)
V/AudioCache(  318): write(0xb57bd000, 4096)
V/AudioCache(  318): memcpy(0xaf20e000, 0xb57bd000, 4096)
V/AudioCache(  318): write(0xb57bd000, 4096)
V/AudioCache(  318): memcpy(0xaf20f000, 0xb57bd000, 4096)
V/AudioCache(  318): write(0xb57bd000, 4096)
V/AudioCache(  318): memcpy(0xaf210000, 0xb57bd000, 4096)
V/AudioCache(  318): write(0xb57bd000, 4096)
V/AudioCache(  318): memcpy(0xaf211000, 0xb57bd000, 4096)
V/AudioCache(  318): write(0xb57bd000, 4096)
V/AudioCache(  318): memcpy(0xaf212000, 0xb57bd000, 4096)
V/AudioCache(  318): write(0xb57bd000, 4096)
V/AudioCache(  318): memcpy(0xaf213000, 0xb57bd000, 4096)
V/AudioCache(  318): write(0xb57bd000, 4096)
V/AudioCache(  318): memcpy(0xaf214000, 0xb57bd000, 4096)
V/AudioCache(  318): write(0xb57bd000, 4096)
V/AudioCache(  318): memcpy(0xaf215000, 0xb57bd000, 4096)
V/AudioCache(  318): write(0xb57bd000, 4096)
V/AudioCache(  318): memcpy(0xaf216000, 0xb57bd000, 4096)
V/AudioCache(  318): write(0xb57bd000, 4096)
V/AudioCache(  318): memcpy(0xaf217000, 0xb57bd000, 4096)
V/AudioCache(  318): write(0xb57bd000, 4096)
V/AudioCache(  318): memcpy(0xaf218000, 0xb57bd000, 4096)
V/AudioCache(  318): write(0xb57bd000, 4096)
V/AudioCache(  318): memcpy(0xaf219000, 0xb57bd000, 4096)
V/AudioCache(  318): write(0xb57bd000, 4096)
V/AudioCache(  318): memcpy(0xaf21a000, 0xb57bd000, 4096)
V/AudioCache(  318): write(0xb57bd000, 4096)
V/AudioCache(  318): memcpy(0xaf21b000, 0xb57bd000, 4096)
,V/AudioCache(  318): write(0xb57bd000, 4096)
V/AudioCache(  318): memcpy(0xaf21c000, 0xb57bd000, 4096)
V/AudioCache(  318): write(0xb57bd000, 4096)
V/AudioCache(  318): memcpy(0xaf21d000, 0xb57bd000, 4096)
V/AudioCache(  318): write(0xb57bd000, 4096)
V/AudioCache(  318): memcpy(0xaf21e000, 0xb57bd000, 4096)
V/AudioCache(  318): write(0xb57bd000, 4096)
V/AudioCache(  318): memcpy(0xaf21f000, 0xb57bd000, 4096)
V/AudioCache(  318): write(0xb57bd000, 4096)
V/AudioCache(  318): memcpy(0xaf220000, 0xb57bd000, 4096)
V/AudioCache(  318): write(0xb57bd000, 4096)
V/AudioCache(  318): memcpy(0xaf221000, 0xb57bd000, 4096)
V/AudioCache(  318): write(0xb57bd000, 4096)
V/AudioCache(  318): memcpy(0xaf222000, 0xb57bd000, 4096)
V/LGMDMManager( 6372): Create singleton instance
V/AudioCache(  318): write(0xb57bd000, 4096)
V/AudioCache(  318): memcpy(0xaf223000, 0xb57bd000, 4096)
V/AudioCache(  318): write(0xb57bd000, 4096)
V/AudioCache(  318): memcpy(0xaf224000, 0xb57bd000, 4096)
V/AudioCache(  318): write(0xb57bd000, 4096)
V/AudioCache(  318): memcpy(0xaf225000, 0xb57bd000, 4096)
V/AudioCache(  318): write(0xb57bd000, 4096)
V/AudioCache(  318): memcpy(0xaf226000, 0xb57bd000, 4096)
V/AudioCache(  318): write(0xb57bd000, 4096)
V/AudioCache(  318): memcpy(0xaf227000, 0xb57bd000, 4096)
V/AudioCache(  318): write(0xb57bd000, 4096)
V/AudioCache(  318): memcpy(0xaf228000, 0xb57bd000, 4096)
V/AudioCache(  318): write(0xb57bd000, 4096)
V/AudioCache(  318): memcpy(0xaf229000, 0xb57bd000, 4096)
V/AudioCache(  318): write(0xb57bd000, 4096)
V/AudioCache(  318): memcpy(0xaf22a000, 0xb57bd000, 4096)
V/AudioCache(  318): write(0xb57bd000, 4096)
V/AudioCache(  318): memcpy(0xaf22b000, 0xb57bd000, 4096)
V/AudioCache(  318): write(0xb57bd000, 4096)
V/AudioCache(  318): memcpy(0xaf22c000, 0xb57bd000, 4096)
V/AudioCache(  318): write(0xb57bd000, 4096)
V/AudioCache(  318): memcpy(0xaf22d000, 0xb57bd000, 4096)
V/AudioCache(  318): write(0xb57bd000, 4096)
V/AudioCache(  318): memcpy(0xaf22e000, 0xb57bd000, 4096)
V/AudioCache(  318): write(0xb57bd000, 4096)
V/AudioCache(  318): memcpy(0xaf22f000, 0xb57bd000, 4096)
V/AudioCache(  318): write(0xb57bd000, 4096)
V/AudioCache(  318): memcpy(0xaf230000, 0xb57bd000, 4096)
V/OMXCodec(  318): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  318): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  318): postAudioEOS() 
V/AudioCache(  318): write(0xb57bd000, 280)
V/AudioCache(  318): memcpy(0xaf231000, 0xb57bd000, 280)
V/AwesomePlayer(  318): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  318): onStreamDone
V/AwesomePlayer(  318): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  318): notify(0xb5474bc0, 2, 0, 0)
V/AudioCache(  318): playback complete
V/AwesomePlayer(  318): pause_l() 
V/AudioCache(  318): notify(0xb5474bc0, 7, 0, 0)
V/AudioCache(  318): ignored
V/AwesomePlayer(  318): cancelPlayerEvents
D/AudioPlayer(  318): Pause Playback at 1068125
V/AudioCache(  318): wait - success
V/MediaPlayerService(  318): return size 205080, sampleRate=48000, channelCount = 2, format = 1
V/AwesomePlayer(  318): reset_l() 
V/AudioCache(  318): notify(0xb5474bc0, 8, 0, 0)
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
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc7e0 on port 0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  318): [OMX.google.vorbis,.decoder] freeing buffer 0xb14fc790 on port 0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc0b0 on port 0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeing buffer 0xb1434290 on port 0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeing buffer 0xb14fcd80 on port 1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc830 on port 1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc8d0 on port 1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc920 on port 1
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
,V/OMXCodec(  318): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  318): AudioPlayer releasing audio source
D/AudioPlayer(  318): AudioPlayer done releasing audio source
V/AwesomePlayer(  318): reset_l() 
V/AwesomePlayer(  318): cancelPlayerEvents
V/AwesomePlayer(  318): ~AwesomePlayer call
V/AwesomePlayer(  318): reset_l() 
V/AwesomePlayer(  318): cancelPlayerEvents
V/SoundPool( 6372): close(32)
V/SoundPool( 6372): pointer = 0x9ffe6000, size = 205080, sampleRate = 48000, numChannels = 2
D/QRemote ( 6372): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,D/QRemote ( 6372): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,D/QRemote ( 6372): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:8144
E/WifiStateMachine( 1039):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1039): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
,E/QC-QMI  ( 6363): qmi_client [6363] 13: failed to locate client data
,E/QC-QMI  (  469): qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
E/QC-QMI  (  469): QMUX qmux_client_id=13 not found in qmux client list, unable to remove
I/UEI.SmartControl( 5865): Supports setup maps: true
,D/UEI.SmartControl( 5865): QS start statue = true Error code = 0
I/UEI.SmartControl( 5865): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 5865): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 5865): ### init IR Blaster...
D/serial_port( 5865): Configuring serial port
E/UEI.SmartControl( 5865): UEIBLaster setting for 616
I/UEI.SmartControl( 5865): Setting serial record hearder size = 2
I/UEI.SmartControl( 5865): configuring settings for MAXQ616
I/UEI.SmartControl( 5865): Get version...
,D/UEI.SmartControl( 5865): serial port data available: 21
,I/qcom-bluetooth( 6416): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:64:c0 
,D/UEI.SmartControl( 5865): MAXQ616 A2-X4 software.
,I/UEI.SmartControl( 5865): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 5865): QS saving settings...
D/UEI.SmartControl( 5865): IR Blaster version: 25672567
I/qcom-bluetooth( 6417): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,D/UEI.SmartControl( 5865): serial port data available: 4
W/ContextImpl( 5865): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
E/UEI.SmartControl( 5865): Services init done
D/UEI.SmartControl( 5865): QS Service init finished
D/UEI.SmartControl( 5865): QS Service version name: 2.1.91
D/UEI.SmartControl( 5865): QS Service version code: 201091
D/UEI.SmartControl( 5865): Service requested: Control
,I/UEI.SmartControl( 5865): Device manager: loading config....
D/UEI.SmartControl( 5865): ----------- loading internal config...
D/UEI.SmartControl( 5865): Internal service binding...
I/QRemote ( 6372): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 5865): ------ IControl API: 11
D/UEI.SmartControl( 5865): File observer start...
E/UEI.SmartControl( 5865): IR Port is disabled: false
D/UEI.SmartControl( 5865): Starting file observer...
I/UEI.SmartControl( 5865): Registering callback...
I/UEI.SmartControl( 5865): ------ IControl API: 19
I/UEI.SmartControl( 5865): Registering Services Ready callback...
,E/UEI.SmartControl( 5865): Loading SETTINGS...
D/UEI.SmartControl( 5865): -- Open brand translation xml: brands_translations_ko
I/UEI.SmartControl( 5865): Notify AllClients services are ready: 0
,I/bt_vendor( 6181): bluetooth satus is on
D/bt_hci_bdroid( 6181): preload
D/bt_userial_mct( 6181): userial_open(port:0)
I/bt_vendor( 6181): bt-vendor : BT_VND_OP_USERIAL_OPEN
I/bt_vendor( 6181): Done intiailizing UART
W/ProcessCpuTracker( 1039): Skipping unknown process pid 6329
I/bt_vendor( 6181): Done intiailizing UART
I/bt_userial_mct( 6181): CMD=66, EVT=66, ACL_Out=67, ACL_In=67
I/bt_vendor( 6181): Bluetooth Firmware and transport layer are initialized
D/bt_userial_mct( 6181): Entering userial_read_thread()
I/bt-btu  ( 6181): btu_task received preload complete event
D/UEI.SmartControl( 5865): -----service ready thread exits
I/QRemote ( 6372): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
W/bt-l2cap( 6181): L2CAP - L2CA_Register() called for PSM: 0x0001
W/bt-l2cap( 6181): L2CAP - L2CA_Register() called for PSM: 0x001f
W/bt-l2cap( 6181): L2CAP - L2CA_Register() called for PSM: 0x0003
D/QRemote ( 6372): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 6372): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
I/        ( 6181): BTE_InitTraceLevels -- TRC_HCI
I/        ( 6181): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 6181): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 6181): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 6181): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 6181): BTE_InitTraceLevels -- TRC_A2D
I/        ( 6181): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 6181): BTE_InitTraceLevels -- TRC_BTM
I/        ( 6181): BTE_InitTraceLevels -- TRC_HID_HOST
I/        ( 6181): BTE_InitTraceLevels -- TRC_GAP
I/        ( 6181): BTE_InitTraceLevels -- TRC_PAN
I/        ( 6181): BTE_InitTraceLevels -- TRC_SDP
I/        ( 6181): BTE_InitTraceLevels -- TRC_GATT
I/        ( 6181): BTE_InitTraceLevels -- TRC_SMP
I/        ( 6181): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 6181): BTE_InitTraceLevels -- TRC_BTIF
W/ProcessCpuTracker( 1039): Skipping unknown process pid 6422
D/QRemote ( 6372): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 6372): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 5865): ------ IControl API: 8
D/QRemote ( 6372): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0,
D/QRemote ( 6372): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 6372): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 6372): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 6372): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6372): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 6372): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
V/QRemote ( 6372): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6372): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 6372): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6372): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 6372): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,D/QRemote ( 6372): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 6372): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 6372): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1455067561279]
D/QRemote ( 6372): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
I/ActivityManager( 1039): Killing 5524:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
W/bt-btm  ( 6181): btm_decode_ext_features_page Secure conn Controller support Enabled
E/bt-btm  ( 6181): BTM_SecRegister:p_cb_info->p_le_callback == 0xa01f4061 
E/bt-btm  ( 6181): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01f4061 
,E/bt-btif ( 6181): Calling BTA_HhEnable
W/bt-l2cap( 6181): L2CAP - L2CA_Register() called for PSM: 0x0019
W/bt-l2cap( 6181): L2CAP - L2CA_Register() called for PSM: 0x0017
W/bt-l2cap( 6181): L2CAP - L2CA_Register() called for PSM: 0x001b
W/bt-l2cap( 6181): L2CAP - L2CA_Register() called for PSM: 0x0011
W/bt-l2cap( 6181): L2CAP - L2CA_Register() called for PSM: 0x0013
E/bt-btif ( 6181): btif_storage_get_adapter_property service_mask:0x2140040
D/BluetoothAdapterProperties( 6181): Address is:58:3F:54:73:64:C0
W/bt-smp  ( 6181): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 6181): Plain text(LSB ~ MSB) = 28 4d 68 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6181): Encrypted text(LSB ~ MSB) = 39 9c 71 27 db 19 32 2b a9 34 f7 90 36 60 ce a0 
W/bt-btm  ( 6181): Stopping oneshot timer
D/QRemote ( 6372): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,W/libprocessgroup( 1039): failed to open /acct/uid_10080/pid_5524/cgroup.procs: No such file or directory
,D/BluetoothAdapterProperties( 6181): Name is: G3-1
D/BluetoothAdapterProperties( 6181): Scan Mode:20
D/BluetoothAdapterProperties( 6181): Discoverable Timeout:120
,D/bt_hci_bdroid( 6181): postload
W/bt-l2cap( 6181): L2CAP - L2CA_Register() called for PSM: 0x000f
D/bt_hci_bdroid( 6181): Used up Tx Cmd credits
D/BluetoothManagerService( 1039): Bluetooth Adapter name changed to G3-1
D/BluetoothManagerService( 1039): Stored Bluetooth name: G3-1
D/bt_hci_bdroid( 6181): Used up Tx Cmd credits
D/bt_hci_bdroid( 6181): Used up Tx Cmd credits
V/QRemote ( 6372): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
D/bte_conf( 6181): Device ID record 1 : primary
D/bte_conf( 6181):   vendorId            = 00c4
D/bte_conf( 6181):   vendorIdSource      = 0001
D/bte_conf( 6181):   product             = 13a1
D/bte_conf( 6181):   version             = 1000
D/bte_conf( 6181):   clientExecutableURL = 
D/bte_conf( 6181):   serviceDescription  = 
D/bte_conf( 6181):   documentationURL    = 
D/bte_conf( 6181): bte_load_did_conf no section named DID2.
E/QRemote ( 6372): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6372): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 6372): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/bt_hci_bdroid( 6181): Used up Tx Cmd credits
D/QRemote ( 6372): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 6372): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
E/bt_mct  ( 6181): hci lib postload completed
D/BluetoothPanServiceJni( 6181): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/QRemote ( 6372): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/BluetoothAdapterState( 6181): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 6181): ScanMode =  20
D/BluetoothAdapterProperties( 6181): State =  11
D/QRemote ( 6372): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
W/sh      ( 6434): type=1400 audit(0.0:159): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/BluetoothAdapterProperties( 6181): mDiscoverableTimeout = 120
V/LGBluetoothServiceAdapter( 6181): [BTUI] state:11, scanmode:20, timeout:120
D/BluetoothAdapterProperties( 6181): Setting state to 12
I/BluetoothAdapterState( 6181): Bluetooth adapter state changed: 11-> 12
I/BluetoothAdapterState( 6181): Entering On State
D/LGBluetoothServiceAdapter( 6181): [BTUI] OnState
D/LGBluetoothServiceAdapter( 6181): [BTUI]         global_name: G3-1
D/LGBluetoothServiceAdapter( 6181): [BTUI]         local_name: G3-1
D/btif_config_util( 6181): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
D/BluetoothAdapterService( 6181): [BTUI] autoConnect() : not allowed
,W/sh      ( 6434): type=1400 audit(0.0:160): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/BluetoothManagerService( 1039): Message: 60
D/BluetoothManagerService( 1039): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService( 1039): Broadcasting onBluetoothStateChange(true) to 5 receivers.
D/BluetoothHeadset( 1852): onBluetoothStateChange: up=true
D/BluetoothA2dp( 1039): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1852): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1852): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1039): onBluetoothStateChange: up=true
E/BluetoothManagerService( 1039): Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
D/BluetoothManagerService( 1039): Bluetooth State Change Intent: 11 -> 12
D/LGBluetoothAPIService( 1958): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/LGBluetoothAPIService( 1958): Message: 1
D/LGBluetoothAPIService( 1958): MESSAGE_BOOT_COMPLETED
I/[SystemUI]BluetoothHandler( 1444): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,I/LGBluetoothAPIService( 1958): [BTUI] LGBluetoothAPIService Binding Success
D/BluetoothManagerService( 1039): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService( 1039): Message: 40
D/BluetoothManagerService( 1039): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
I/BluetoothMapService( 6181): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 6181): STATE_ON
,D/LGBluetoothAPIServer( 6181): [BTUI] onCreate()
D/LGBluetoothAPIServer( 6181): [BTUI] onBind()
,D/LGBluetoothAPIService( 1958): [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
V/BluetoothMapService( 6181): Handler(): got msg=1
D/LGBluetoothAPIService( 1958): Message: 100
D/BluetoothMapMasInstance( 6181): Map Service startRfcommSocketListener
D/LGBluetoothAPIService( 1958): MESSAGE_BLUETOOTH_SERVICE_CONNECTED
D/LGBluetoothDeviceModeControllManager( 6181): [BTUI] checkDeviceModeAndSet, sinkMode : false
W/ContextImpl( 6218): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
D/BluetoothAdapterService( 6181): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1127cb12
V/BluetoothPbapService( 6181): Pbap Service onCreate
V/BluetoothPbapService( 6181): Starting PBAP service
,I/dhcpcd  ( 6370): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
D/LGBluetoothPbapAdapter( 6181): [BTUI] getInstance : create
V/BluetoothPbapService( 6181): action: android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothPbapService( 6181): state: 12
V/BluetoothPbapReceiver( 6181): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 6181): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6181): ***********state = 12
D/BluetoothMapMasInstance( 6181): MAS initSocket()
D/BluetoothMapMasInstance( 6181):   masId = 00
D/BluetoothMapMasInstance( 6181):   msgTypes = 0e
D/BluetoothMapMasInstance( 6181):   masName = SMS/MMS
D/BluetoothMapMasInstance( 6181):   SDP string = 000eSMS/MMS
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/qcom-bt-wlan-coex( 6442): /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
V/BluetoothPbapService( 6181): Handler(): got msg=1
W/BluetoothAdapter( 6181): getBluetoothService() called with no BluetoothManagerCallback
V/BluetoothPbapService( 6181): Pbap Service startRfcommSocketListener
V/BluetoothPbapService( 6181): Pbap Service initSocket
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/LocalBluetoothProfileManager( 6218): Adding local A2DP profile
D/LGBluetoothServiceAdapter( 6181): [BTUI] createSocketChannel FD=73 mFd=0
V/BluetoothMapMasInstance( 6181): Succeed to create listening socket 
D/BluetoothMapMasInstance( 6181): Accepting socket connection...
,W/BluetoothAdapter( 6181): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothManagerService( 1039): Message: 30
D/LGBluetoothServiceAdapter( 6181): [BTUI] createSocketChannel FD=75 mFd=73
V/BluetoothPbapService( 6181): Succeed to create listening socket 
V/BluetoothPbapService( 6181): Accepting socket connection...
D/LocalBluetoothProfileManager( 6218): Adding local HEADSET profile
D/BluetoothManagerService( 1039): Message: 30
D/BluetoothManagerService( 1039): Message: 30
D/BluetoothManagerService( 1039): Message: 30
,D/LocalBluetoothProfileManager( 6218): Adding local MAP profile
D/BluetoothMap( 6218): Create BluetoothMap proxy object
D/BluetoothManagerService( 1039): Message: 30
D/BluetoothManagerService( 1039): Message: 30
I/dhcpcd  ( 6370): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 6370): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 6370): wlan0: adding route to 192.168.1.0/24
,D/dhcpcd  ( 6370): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 6370): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,E/WifiStateMachine( 1039):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 1039):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
D/LocalBluetoothProfileManager( 6218): LocalBluetoothProfileManager construction complete
V/BluetoothPbapService( 6181): Pbap Service onBind
E/WifiStateMachine( 1039):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1039): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
D/LGBluetoothUserBindClient( 6218): [BTUI] initUserBindClient
W/ContextImpl( 6218): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
D/DockEventReceiver( 6218): finishStartingService: stopping service
,D/BluetoothA2dp( 6218): Proxy object connected
D/A2dpProfile( 6218): Bluetooth service connected
D/BluetoothHeadset( 6218): Proxy object connected
D/HeadsetProfile( 6218): Bluetooth service connected
,D/BluetoothInputDevice( 6218): Proxy object connected
,D/HidProfile( 6218): Bluetooth service connected
D/BluetoothPan( 6218): BluetoothPAN Proxy object connected
D/PanProfile( 6218): Bluetooth service connected
D/BluetoothMap( 6218): Proxy object connected
D/MapProfile( 6218): Bluetooth service connected
D/BluetoothMap( 6218): getConnectedDevices()
V/BluetoothMapService( 6181): getConnectedDevices()
D/BluetoothPbap( 6218): Proxy object connected
D/PbapServerProfile( 6218): Bluetooth service connected
D/LGBluetoothUserBindClient( 6218): [BTUI] onServiceConnected
D/BluetoothPermissionRequest( 6218): onReceive
,D/dhcpcd  ( 6370): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 6370): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 6370): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
D/LGBluetoothFeatureConfig( 6218): isPrivacyLogsEnabled : true
D/LGBluetoothUtils( 6218): [BTUI] FileNotFound: readProperty
D/LGBluetoothResetSettingReceiver( 6218): return without doing reset settings.
V/BluetoothOppReceiver( 6181): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
I/LGBluetoothOppAdapter( 6181): [BTUI] startOppService()
V/BluetoothOppManager( 6181): restoreApplicationData! falsefalsenullnull
,D/LGBluetoothFeatureConfig( 6181): isPrivacyLogsEnabled : true
V/BtOppService( 6181): onCreate
,D/BluetoothAdapterProperties( 6181): Discoverable Timeout:120
D/LGBluetoothDeviceModeControllManager( 6181): adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
D/BluetoothAdapterProperties( 6181): Scan Mode:21
D/LGBluetoothDeviceModeControllManager( 6181): getDeviceMode  deviceMode 0
V/BluetoothOppNotification( 6181): send message
V/BtOppService( 6181): Starting RfcommListener
D/BluetoothOppPreference( 6181): Dumping Names:  
D/BluetoothOppPreference( 6181): {}
D/BluetoothOppPreference( 6181): Dumping Channels:  
D/BluetoothOppPreference( 6181): {}
V/BtOppService( 6181): onStartCommand
,V/BtOppService( 6181): pendingUpdate is true keepUpdateThread is false sListenStarted is true
V/BluetoothFtpReceiver( 6181): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpReceiver( 6181): BluetoothFtpReceiver Start Service
V/BluetoothOppNotification( 6181): new notify threadi!
V/BluetoothOppNotification( 6181): send delay message
V/BtOppService( 6181): start RfcommListener
V/BluetoothOppProvider( 6181): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
V/BtOppService( 6181): Deleted complete outbound shares, number =  0
V/BtOppService( 6181): RfcommListener started
V/BtOppRfcommListener( 6181): Starting RFCOMM listener....
,V/BluetoothOppProvider( 6181): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapterService( 6181): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1127cb12
V/BluetoothFtpService( 6181): Ftp Service onCreate
I/BluetoothFtpService( 6181): Ftp Service onCreate
V/BluetoothFtpService( 6181): Ftp Service onStartCommand
V/BluetoothFtpService( 6181): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpService( 6181): Starting Listening on sockets
V/BtOppService( 6181): Deleted complete inbound failed shares, number = 0
V/BluetoothOppProvider( 6181): starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6181): created cursor android.database.sqlite.SQLiteCursor@3be11da5 on behalf of 
,W/BluetoothAdapter( 6181): getBluetoothService() called with no BluetoothManagerCallback
V/BluetoothSapReceiver( 6181): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 6181): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 6181): SapReceiver onReceive 
V/BluetoothSapReceiver( 6181): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6181):  Bluetooth Adapter state = 12
V/BluetoothSapReceiver( 6181): Calling SAP service start service with action = null
V/BluetoothOppProvider( 6181): created cursor android.database.sqlite.SQLiteCursor@2880157a on behalf of 
V/BtOppService( 6181): ContentObserver received notification
V/BtOppService( 6181): ContentObserver received notification
V/BluetoothFtpService( 6181): Handler(): got msg=1
D/LGBluetoothServiceAdapter( 6181): [BTUI] createSocketChannel FD=79 mFd=75
V/BtOppRfcommListener( 6181): Started RFCOMM listener....
I/BtOppRfcommListener( 6181): Accept thread started.
V/BtOppRfcommListener( 6181): Accepting connection...
V/BluetoothFtpService( 6181): Ftp Service startRfcommSocketListener
V/BluetoothFtpService( 6181): Ftp Service initSocket
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6181): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 6181): [BTUI] createSocketChannel FD=81 mFd=79
V/BluetoothFtpService( 6181): Succeed to create listening socket on channel 20
V/BluetoothFtpService:RfcommSocketAcceptThread( 6181): Run Accept thread
D/AuthorizationBluetoothService( 2123): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,V/BtOppService( 6181): pendingUpdate is true keepUpdateThread is false sListenStarted is true
V/BluetoothOppProvider( 6181): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
D/BluetoothAdapterService( 6181): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1127cb12
V/BluetoothSapService( 6181): Sap Service onCreate
V/BluetoothOppProvider( 6181): created cursor android.database.sqlite.SQLiteCursor@1b70812b on behalf of 
,V/BluetoothOppNotification( 6181): mUpdateCompleteNotification = true
V/BluetoothOppProvider( 6181): created cursor android.database.sqlite.SQLiteCursor@3e6a0f46 on behalf of 
V/BluetoothSapService( 6181): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 6181): state: 12
V/BluetoothOppNotification( 6181): update too frequent, put in queue
V/BluetoothSapService( 6181): Starting SAP server process
V/BluetoothOppProvider( 6181): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 6181): created cursor android.database.sqlite.SQLiteCursor@30d87634 on behalf of 
V/BtOppService( 6181): pendingUpdate is false keepUpdateThread is false sListenStarted is true
V/BluetoothOppNotification( 6181): outbound: succ-0  fail-0
V/BluetoothSapService( 6181): SAP Service startRfcommListenerThread
V/BluetoothOppNotification( 6181): outbound notification was removed.
V/BluetoothOppProvider( 6181): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BluetoothSapService( 6181): Sap Service initRfcommSocket
W/sapd    ( 6469): type=1400 audit(0.0:161): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/sapd    ( 6469): type=1400 audit(0.0:162): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/BluetoothAdapter( 6181): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 6181): [BTUI] createSocketChannel FD=82 mFd=81
V/BluetoothOppProvider( 6181): created cursor android.database.sqlite.SQLiteCursor@20665c5d on behalf of 
V/BluetoothSapService( 6181): Succeed to create listening socket 
V/BluetoothSapService( 6181): Accepting socket connection...
V/BT_SAP  ( 6469): Event pipe created
V/BT_SAP  ( 6469): create_server_socket qcom.sap.server
V/BT_SAP  ( 6469): created socket fd 6
,V/BluetoothOppNotification( 6181): inbound: succ-0  fail-0
V/BluetoothOppNotification( 6181): inbound notification was removed.
V/BluetoothOppProvider( 6181): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6181): created cursor android.database.sqlite.SQLiteCursor@8a7d9d2 on behalf of 
D/DhcpStateMachine( 1039): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper( 1039): CheckDhcpDirectory [Lease File Count] : 3
,V/LgDhcpStateMachineHelper( 1039): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1039): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1039): Add DhcpResults: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
V/DhcpStateMachine( 1039): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1039): bShouldSendDhcpAction Result: true
E/WifiStateMachine( 1039):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine( 1039):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/WifiNative-wlan0( 1039): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 6239): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1039): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1039): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1039): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 6239): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1039): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1039): doBoolean: SET ps 1
D/DhcpStateMachine( 1039): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1039): RunningState
D/WifiNative-wlan0( 1039): SET ps 1: returned true
D/ConnectivityService( 1039): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
E/WifiStateMachine( 1039):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1039):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1039): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,D/ConnectivityService( 1039): ignoring duplicate network state non-change
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,I/StatusBar.NetworkController( 1444): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1444): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1039): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService( 1039): Adding iface wlan0 to network 100
,D/PostponalbeReceiver( 5124): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/WifiStateMachine( 1039): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
I/StatusBar.NetworkController( 1444): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1444): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/WifiHS20( 1039): [PASSPOINT] passpointNotification: hs20AP list is checked
I/StatusBar.NetworkController( 1444): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/StatusBar.NetworkController( 1444): mWifiConnected = true, mWifiLevel = 2
D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WfdStateTracker( 1958): handleWifiStateChangedEvent: 1
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20( 1039): [PASSPOINT] passpointNotification: hs20AP list is checked
E/ConnectivityService( 1039): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1039): Adding Route [fe80::/64 -> :: wlan0] to network 100
D/ConnectivityService( 1039): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/ConnectivityService( 1039): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
D/ConnectivityService( 1039): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1039): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 100
D/ConnectivityService( 1039): Setting Dns servers for network 100 to [/192.168.1.1]
D/Nat464Xlat( 1039): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1039): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1039): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1039): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1039):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1039):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1039):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1039):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1039):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1039): currentScore = 0, newScore = 20
D/ConnectivityService( 1039):    accepting network in place of null
D/ConnectivityService( 1039): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
I/StatusBar.NetworkController( 1444): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): Checking http://clients3.google.com/generate_204 on "NG700"
I/StatusBar.NetworkController( 1444): mWifiConnected = true, mWifiLevel = 2
D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WiFiOffLoadBroadcast( 6218): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WIFI    ( 1039): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1039):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/libc-netbsd(  313): res_queryN name = clients3.google.com, class = 1, type = 28
D/ConnectivityService( 1039): Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
D/TelephonyNetworkFactory-1( 1852): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1852):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,E/ConnectivityService( 1039): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/WiFiOffLoadBroadcast( 6218): MCCMNC not supported: null
D/CSLegacyTypeTracker( 1039): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1039): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/LocSvc_java( 1039): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1039): getAGpsConnectionInfo connType - 4
D/ConnectivityService( 1039): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/LocSvc_java( 1039): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1039): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java( 1039): Sending msg: 5 arg1:0 arg2:1
D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  313): res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
D/CSLegacyTypeTracker( 1039): [e] list.add(nai) empty : false size: 1
D/libc-netbsd(  313): res_queryN name = 2.android.pool.ntp.org., class = 1, type = 1
D/DSQN    ( 1039): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/QRemote ( 6372): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6372): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=1
,D/ConnectivityService( 1039): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/libc-netbsd(  313): res_queryN name = europe.pool.ntp.org, class = 1, type = 1
D/ConnectivityService( 1039): validation of new default Network = false
D/ConnectivityService( 1039): Default network via Wi-Fi connected. start DSQN
D/libc-netbsd(  313): res_queryN name = europe.pool.ntp.org., class = 1, type = 1
D/DSQN    ( 1039): enableDataServiceNotify 
D/DSQN    ( 1039): start dsqn bin
D/DSQN    ( 1039): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/LocSvc_java( 1039): requestTime failed
D/LocSvc_java( 1039): Sending msg: 10 arg1:0 arg2:1
I/QRemote ( 6372): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 5124): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/ConnectivityService( 1039): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1039):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1039):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1039): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1444): CM callback handler got msg 524290
,W/dsqn    ( 6487): type=1400 audit(0.0:163): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,W/dsqn    ( 6487): type=1400 audit(0.0:164): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
V/WiFiOffLoadBroadcast( 6218): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
V/NetworkPolicy( 1039): [LG_RESTRICTED] checkMobilePolicy_type()
D/WiFiOffLoadBroadcast( 6218): MCCMNC not supported: null
D/QRemote ( 6372): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6372): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6372): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
E/DSQN    ( 6487): DSQN ssw
D/libc-netbsd(  313): res_queryN name = clients3.google.com, class = 1, type = 1
D/PostponalbeReceiver( 5124): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6285): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/TelephonyIcons( 1444): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PCSuite ( 6285): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6218): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6218): MCCMNC not supported: null
D/QRemote ( 6372): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6372): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6372): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6372): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6372): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 5124): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/libc-netbsd(  313): res_queryN name = clients3.google.com succeed
,I/PCSuite ( 6285): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6285): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6218): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6218): MCCMNC not supported: null
D/QRemote ( 6372): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6372): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6372): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6372): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6372): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/LGDataListener(  313): argv[0]=dsqncommand
D/LGDataListener(  313): argv[1]=wlan0
D/LGDataListener(  313): argv[2]=1
D/LGDataListener(  313): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1039): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1039): start to monitor internet connection
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 10 Feb 2016 01:26:02 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1455067562025], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1455067562005]}
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): Validated
D/ConnectivityService( 1039): Validated NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService( 1039): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1039):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1039):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1039):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1039): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService( 1039): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1039):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1039):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1039): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1039): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1039): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory-1( 1852): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1039): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1039):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1852):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/ConnectivityManager.CallbackHandler( 1444): CM callback handler got msg 524290
D/TelephonyIcons( 1444): null signal icon name: drawable/stat_sys_signal_null
,D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
V/BluetoothOppNotification( 6181): new notify threadi!
V/BluetoothOppNotification( 6181): send delay message
,V/BluetoothOppProvider( 6181): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6181): created cursor android.database.sqlite.SQLiteCursor@1e41eaa3 on behalf of 
V/BluetoothOppNotification( 6181): mUpdateCompleteNotification = true
,V/BluetoothOppProvider( 6181): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,V/BluetoothOppProvider( 6181): created cursor android.database.sqlite.SQLiteCursor@14a0c1a0 on behalf of 
V/BluetoothOppNotification( 6181): outbound: succ-0  fail-0
,V/BluetoothOppNotification( 6181): outbound notification was removed.
V/BluetoothOppProvider( 6181): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 6181): created cursor android.database.sqlite.SQLiteCursor@25316159 on behalf of 
V/BluetoothOppNotification( 6181): inbound: succ-0  fail-0
V/BluetoothOppNotification( 6181): inbound notification was removed.
V/BluetoothOppProvider( 6181): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 6181): created cursor android.database.sqlite.SQLiteCursor@585c11e on behalf of 
,E/WifiStateMachine( 1039):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-926350358] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1039):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-926350355] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1039): doString: [SIGNAL_POLL]
,D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
I/jxcore-log( 6046): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 6046): 
,V/WifiInternetCheck( 1039): Single check msg out of sync, ignoring.
,I/jxcore-log( 6046): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 6046): 
D/ConnectivityService( 1039): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1039): MasterInitialState.processMessage what=3
,D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  313): res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
,D/GpsLocationProvider( 1039): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/PostponalbeReceiver( 5124): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 5124): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkMonitor( 5263): type=WIFI subType= reason=null isConnected=true
,I/jxcore-log( 6046): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 6046): 
I/jxcore-log( 6046): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 6046): 
,D/libc-netbsd(  313): res_queryN name = 2.android.pool.ntp.org succeed
,I/ActivityManager( 1039): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6530 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/AlarmManagerService( 1039): Setting time of day to sec=1455067565
W/AlarmManagerService( 1039): Unable to set rtc to 1455067565: Invalid argument
I/ActivityManager( 1039): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=6549 uid=10054 gids={50054, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/PowerManagerServiceEx( 1039): acquireWakeLockInternal: lock=545313920, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1039
V/AlarmManager( 1039): RTC_WAKEUP set : Alarm{a8665f type 0 when 1455067561541 com.android.vending} when 1455067561541
D/KeyguardUpdateMonitor( 1444): handleTimeUpdate
,W/ActivityManager( 1039): getTasks: caller 10029 is using old GET_TASKS but privileged; allowing
D/LIA_Informant_Tips_DateChangeManager( 3589): onReceive() : ACTION_TIME_CHANGED
I/[SystemUI]Clock( 1444): onReceive = android.intent.action.TIME_SET
I/LIA_Informant_Tips_LogTracer( 3589): [Log Tracer - Schedule Transition] Time Change Event Received : 2016-02-10 02:26:05...... Request
I/LIA_Informant_Tips_LogTracer( 3589): [Log Tracer - Schedule Transition] UserGuide, DATE_UPDATE : working count : 7, total count : 171, new day : false...... Request
D/LIA_Informant_Tips_DateChangeManager( 3589): DateInfo : SmartTips Total Working Day Count = 171
D/LIA_Informant_Tips_DateChangeManager( 3589): DateInfo : UserGuide Working Duration Count = 7
D/LIA_Informant_Tips_DateChangeManager( 3589): DateInfo : Last Date Check Time = 2016-02-10 02:26:05
I/LgeClockWidgetControlView( 1444): time changed, timezoneChanged : false
I/SecureClockService( 1958): Intent.ACTION_TIME_CHANGED 
I/[LGHome]LGDateChangeReceiver( 2068): [LGDateChangeReceiver.java:78:updateCalendarShortcut()]date=10 currentDate=-1 dayofweek=4 currentDayOfWeek=-1
I/[LGHome]LGCalendarIcon( 2068): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Wed date= 10
I/[LGHome]LGCalendarIcon( 2068): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Wed date= 10
I/[LGHome]Launcher( 2068): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/jxcore-log( 6046): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 6046): 
,I/AppUp4:AppBoxCP( 6530): onCreate
W/AppUp4:DB( 6530):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 6530):  setFingerPrint start
I/AppUp4:DB( 6530):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/ActivityManager( 1039): Start proc com.android.gallery3d for service com.android.gallery3d/com.lge.gallery.picasa.PicasaService: pid=6567 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
I/jxcore-log( 6046): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log( 6046): 
,V/SIM_STK ( 1039): Menu title from STK is T-Mobile
D/[Concierge]Service( 2616): onStartCommand(). Type : 9
D/[Concierge]Service( 2616): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1039): releaseWakeLockInternal: lock=545313920 [*alarm*], flags=0x0
I/AppUp4:DB( 6530):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
,I/AppUp4:DB( 6530):  SDK version = 21
I/AppUp4:DB( 6530):  beforefinger == newfinger no write in DB
I/CloudHub( 2215): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19984
D/AppUp4:AppBoxApplication( 6530): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6530): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6530): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6530): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6530): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6530): onReceive
,W/ResourcesManager( 6567): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6567): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6567): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 6567): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
D/LgDataFeature( 6530): LgDataFeature() Constructor: none
D/LgDataFeature( 6530): LgDataFeature() Constructor Done, null
D/AppUp4:CustFacade( 6530): Context : android.app.ReceiverRestrictedContext@4964a9d
D/AppUp4:CustFacade( 6530): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6530): isPhone : true
D/AppUp4:CustModeStarterReceiver( 6530): begin check event
I/AppUp4:CustModeStarterReceiver( 6530): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6530): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,D/AppUp4:CustModeStarterReceiver( 6530): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6530): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6530): handleAsyncCustNotification do not startCustService
D/LGDMClient( 3247): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3247): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 3247): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 3247): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,V/DownloadManager( 3368): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3368): DownloadService onCreate
,D/LGDMClient( 3247): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/LGDMClient( 3247): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
D/LGDMClient( 3247): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 3247): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/DownloadManager( 3368): in removeSpuriousFiles
V/DownloadManager( 3368): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3368): created cursor android.database.sqlite.SQLiteCursor@15bd3279 on behalf of 3368
I/DownloadManager( 3368): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3368): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3368): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3368): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3368): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
,I/DownloadManager( 3368): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3368): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3368): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3368): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3368): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3368): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/DownloadManager( 3368): in trimDatabase
V/DownloadManager( 3368): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3368): created cursor android.database.sqlite.SQLiteCursor@29858bbe on behalf of 3368
I/ActivityManager( 1039): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6593 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/AppConfig( 6567): Total System Memory = 2995761152
W/ContextImpl( 3247): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
D/SystemHelper( 6567): region [EU], country [EU], operator [OPEN], sub-operator []
,V/DownloadManager( 3368): DownloadService onStartCommand
V/DownloadManager( 3368): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3368): created cursor android.database.sqlite.SQLiteCursor@1beeb36c on behalf of 3368
V/DownloadManager( 3368): processing inserted download 1
V/DownloadManager( 3368): processing inserted download 4
V/DownloadManager( 3368): processing inserted download 7
E/LGDMClient( 3247): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 3247): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 3247): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3368): processing inserted download 8
V/DownloadManager( 3368): processing inserted download 9
V/DownloadManager( 3368): processing inserted download 10
,V/DownloadManager( 3368): processing inserted download 16
V/DownloadManager( 3368): processing inserted download 17
V/DownloadManager( 3368): processing inserted download 18
V/DownloadManager( 3368): processing inserted download 21
V/DownloadManager( 3368): processing inserted download 22
V/DownloadManager( 3368): DownloadService onDestroy
W/ResourcesManager( 6593): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6593): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 6593): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6593): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/ActivityManager( 1039): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=6610 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ThermalEngine(  335): Thermal-Server: Thermal received msg from  override
I/Thermal-Lib( 2932): Thermal-Lib-Client: Client request sent
D/GpsLocationProvider( 1039): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ReaderUtils( 6549): PortraitW 1440 LandscapeW 2392 SmallestSize 1340 LargestSize 2392 textZoom 4.4999995 isTablet false Memory 256
E/GpsLocationProvider( 1039): No APN found to select.
,I/LGEmail ( 6593): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6593): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,I/ActivityManager( 1039): Killing 5893:com.google.android.apps.docs/u0a61 (adj 15): empty #17
W/ResourceType( 6593): No package identifier when getting value for resource number 0x00000000
,W/libprocessgroup( 1039): failed to open /acct/uid_10061/pid_5893/cgroup.procs: No such file or directory
,V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/DriveInitializer( 2323): Background init thread started
,W/GAV2    ( 6549): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.gms/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 2323): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.gms/files
D/LgDataFeature( 6593): LgDataFeature() Constructor: none
D/LgDataFeature( 6593): LgDataFeature() Constructor Done, null
,I/art     ( 1039): Explicit concurrent mark sweep GC freed 72825(3MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 1.334ms total 84.151ms
,I/BooksApp( 6549): Created application version: 3.2.35 (30235)
W/DriveInitializer( 2323): Background init thread ended
E/Auth.Api.Credentials( 2323): [CredentialSyncAdapter] Unknown sync event.
I/GLSUser ( 2123): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2123): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2123): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2123): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DelayedSyncController( 6610): Delaying sync.
,D/Finsky  ( 5581): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 5581): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 5581): [1] 5.onFinished: Scheduling replication attempt 2.
I/ActivityManager( 1039): Killing 5551:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,W/libprocessgroup( 1039): failed to open /acct/uid_10097/pid_5551/cgroup.procs: No such file or directory
,I/BooksSync( 6549): Starting books sync
,D/eas_req ( 6593): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager( 1039): Killing 5950:com.lge.eula/1000 (adj 15): empty #17
E/WifiStateMachine( 1039):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-54 f=2412 sc=60 link=72 tx=4.8, 0.0, 0.0  rx=3.0 bcn=0 [on:0 tx:0 rx:0 period:3458] from screen [on:0 period:-926346884] gl rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1039):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-54 f=2412 sc=60 link=72 tx=4.8, 0.0, 0.0  rx=3.0 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:-926346884] gl rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1039): doString: [SIGNAL_POLL]
,W/libprocessgroup( 1039): failed to open /acct/uid_1000/pid_5950/cgroup.procs: No such file or directory
I/HubEmail( 6593): JNI_OnLoad()
I/HubEmail( 6593): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6593): registerNatives()
I/HubEmail( 6593): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6593): registerNativeMethods()
I/HubEmail( 6593): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,I/LgeMiscReceiver( 3300): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3300): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3300): networkInfo.isConnected() = true
,D/PhoneState( 3300): setPdpRejectCasuse : false
W/art     ( 6593): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  313): res_queryN name = static-avc.lglime.com, class = 1, type = 1
,I/ActivityManager( 1039): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6670 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
W/Settings( 6593): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 6593): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  313): res_queryN name = www.google.com, class = 1, type = 1
D/DrmBroadcastReceiver( 6670): Receive CONNECTIVITY_ACTION
D/DrmBroadcastReceiver( 6670): 1  network is available. Sync DRM Time with NTP
,V/DrmService( 6670): Service onCreate
D/DrmService( 6670): Received new request = 2
I/DrmSntpClient( 6670): Start Sync process
D/DrmSntpClient( 6670): Server : 0
D/libc-netbsd(  313): res_queryN name = www.google.com succeed
D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  313): res_queryN name = pool.ntp.org, class = 1, type = 1
D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  313): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  313): res_queryN name = clients3.google.com succeed
,D/libc-netbsd(  313): res_queryN name = static-avc.lglime.com succeed
I/ActivityManager( 1039): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=6693 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     ( 6693): Almond Protected OAT
V/WifiInternetCheck( 1039): isHttpConnectionAvailable - We got a valid response : 204
,D/BooksSync( 6549): started syncMyEbooks
,D/WeatherApplication( 6693): removeAccount
D/WeatherApplication( 6693): Account.length = 0
E/WeatherApplication( 6693): OPERATOR:OPEN
,D/libc-netbsd(  313): res_queryN name = pool.ntp.org succeed
D/WeatherAncestor( 6693): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 2:26:6
D/Weather.Utils( 6693): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6693): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6693): 2 : This is isUpdating : false
V/FormManager( 6244): There are no updated forms. The schedule will be deleted.
D/WeatherAncestor( 6693): connectivity changed - connection : true
V/FormManager( 6244): Alarm would be updated, because LastCheckTime has been updated.
D/WeatherService( 6693): 2 : isServiceAlived():false forecastCache:null
,D/ForecastDataCache( 6693): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 6693): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 6693): 2 : Cache is not up-to-date, count: 0
V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/LGDrmClient( 6670): _DRM_ServiceGet() : Bind lgdrm service
D/UEI.SmartControl( 5865): Internal timer expired: 2
D/UEI.SmartControl( 5865): unbind internal service
,V/ILGDrmService(  328): eDRM_SetDRMTime +++
,I/LGDRM   (  328): [DRM] SET TIME : YR=2016, MON=2, DAY=10
I/LGDRM   (  328): [DRM] SET TIME : HR=1, MIN=26, SEC=5
I/ActivityManager( 1039): Killing 5371:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
V/ILGDrmService(  328): eDRM_SetDRMTime ---
I/DrmSntpClient( 6670): Synched
D/DrmService( 6670): Completed !! request = 2
D/DrmService( 6670): Request count = 0
D/Weather_cast( 6693): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 6693): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 2:26:6
D/serial_port( 5865): close(fd = 24)
,I/UEI.SmartControl( 5865): Serial port is closed.
I/ActivityManager( 1039): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6717 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1039): Killing 2215:com.lge.music/u0a34 (adj 15): empty #17
,V/AudioFlinger(  318): 2215 died, releasing its sessions
,V/AudioFlinger(  318):  pid 1852 @ 0
V/AudioFlinger(  318):  pid 3300 @ 1
V/AudioFlinger(  318):  pid 3300 @ 2
,W/libprocessgroup( 1039): failed to open /acct/uid_10005/pid_5371/cgroup.procs: No such file or directory
,V/DrmService( 6670): Service onDestroy
W/libprocessgroup( 1039): failed to open /acct/uid_10034/pid_2215/cgroup.procs: No such file or directory
,I/ActivityManager( 1039): Killing 6123:com.google.android.talk/u0a72 (adj 15): empty #17
W/libprocessgroup( 1039): failed to open /acct/uid_10072/pid_6123/cgroup.procs: No such file or directory
,I/GLSUser ( 2123): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2123): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2123): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2123): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,D/ZenLog  ( 1039): intercepted: 0|com.google.android.gms|1|null|10005,none
V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/ResourcesManager( 1396): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1396): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/GLSActivity( 2123): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2123): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2123): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2123): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2123): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2123): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2123): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1396): onNotificationPosted
W/ResourcesManager( 1444): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1444): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do add job
D/LgeQuickCoverNotificationData( 1396): add : 2
D/LgeQuickCoverNotificationData( 1396): do add job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/BooksAccountManager( 6549): Authentication error
E/BooksAccountManager( 6549): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6549): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6549): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6549): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6549): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6549): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6549): null auth token
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
,E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  313): res_queryN name = www.googleapis.com, class = 1, type = 1
E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{3be11da5 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ContextImpl( 6717): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6717): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
D/libc-netbsd(  313): res_queryN name = www.googleapis.com succeed
W/ContextImpl( 6717): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6717): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 2123): Explicit concurrent mark sweep GC freed 10545(572KB) AllocSpace objects, 3(432KB) LOS objects, 51% free, 30MB/62MB, paused 734us total 38.057ms
,I/GLSUser ( 2123): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 2123): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2123): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2123): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
W/GLSActivity( 2123): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2123): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2123): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2123): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2123): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2123): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2123): 	at android.os.Binder.execTransact(Binder.java:446)
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,D/ContactsSyncAdapter( 2123): innerSync failed
D/ContactsSyncAdapter( 2123): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2123): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2123): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2123): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2123): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2123): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2123): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2123): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2123): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2123): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2123): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2123): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1396): onNotificationPosted
D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
D/SyncManager( 1039): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 26878, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager( 1039): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 149546, reason: 10019
I/WebViewFactory( 6717): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
D/QuickStatusbarLayout( 1396): Notification difference=198
,D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{3be11da5 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/LibraryLoader( 6717): Loading: webviewchromium
I/LibraryLoader( 6717): Time to load native libraries: 2 ms (timestamps 6734-6736)
I/LibraryLoader( 6717): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6717): Binding Chromium to main looper Looper (main, tid 1) {c86033c}
,I/LibraryLoader( 6717): Expected native library version number "",actual native library version number ""
I/chromium( 6717): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6717): Initializing chromium process, renderers=0
W/art     ( 6717): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 6717): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 6717): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 6717): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
V/AudioPolicyService(  318): registerClient() client 0xb1427fe0, uid 10093
W/AudioManagerAndroid( 6717): Requires BLUETOOTH permission
I/Adreno-EGL( 6717): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6717): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6717): Build Date: 12/12/14 금
I/Adreno-EGL( 6717): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6717): Remote Branch: 
I/Adreno-EGL( 6717): Local Patches: 
I/Adreno-EGL( 6717): Reconstruct Branch: 
,D/DelayedSyncController( 6610): Delaying sync.
,I/NSApplication( 6717): Starting up...
,I/ActivityManager( 1039): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6788 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1039): Killing 5978:com.lge.bnr/1000 (adj 15): empty #17
I/art     (  347): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 447us total 25.809ms
,I/art     (  347): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 393us total 19.068ms
,I/art     (  347): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 347us total 18.144ms
,W/libprocessgroup( 1039): failed to open /acct/uid_1000/pid_5978/cgroup.procs: No such file or directory
,W/ResourcesManager( 6788): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ApiaryClient( 6549): Error response from books API: {
W/ApiaryClient( 6549):  "error": {
W/ApiaryClient( 6549):   "errors": [
W/ApiaryClient( 6549):    {
W/ApiaryClient( 6549):     "domain": "global",
W/ApiaryClient( 6549):     "reason": "required",
W/ApiaryClient( 6549):     "message": "Login Required",
W/ApiaryClient( 6549):     "locationType": "header",
W/ApiaryClient( 6549):     "location": "Authorization"
W/ApiaryClient( 6549):    }
W/ApiaryClient( 6549):   ],
W/ApiaryClient( 6549):   "code": 401,
W/ApiaryClient( 6549):   "message": "Login Required"
W/ApiaryClient( 6549):  }
W/ApiaryClient( 6549): }
,W/ApiaryClient( 6549): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6549): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5335455908363876655&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6549): Headers:
W/ApiaryClient( 6549): accept-encoding: [gzip]
W/ApiaryClient( 6549): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6549): gdata-version: 2
,D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  313): res_queryN name = mtalk.google.com, class = 1, type = 1
,I/GLSActivity( 2123): [ac] getting account id
I/iu.SyncManager( 2323): SYNC; picasa accounts
D/libc-netbsd(  313): res_queryN name = mtalk.google.com succeed
,I/art     ( 1039): Explicit concurrent mark sweep GC freed 30768(1366KB) AllocSpace objects, 4(192KB) LOS objects, 33% free, 44MB/66MB, paused 1.868ms total 99.729ms
,I/GLSUser ( 2123): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
,D/NetworkLogImpl( 2323): Loaded NetworkSpeedPredictor
,I/iu.Environment( 2323): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/iu.UploadsManager( 2323): num queued entries: 0
I/iu.UploadsManager( 2323): num updated entries: 0
I/iu.SyncManager( 2323): NEXT; no task
D/ChimeraCfgMgr( 2323): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 2323): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
D/PostponalbeReceiver( 5124): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.TIME_SET'.
,I/ActivityManager( 1039): Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=6828 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,D/ALBootInit( 6828): ====action==>android.intent.action.TIME_SET
,D/ALBootInit( 6828): Alarm ALBootInit: TIME_SET
D/Alarms  ( 6828): [setNextAlert] start
D/Alarms  ( 6828): [setNextAlert] (1)
,D/Alarms  ( 6828):  minTime  = 0
D/Alarms  ( 6828):  -- OK multi -- 0
E/jeny.kim( 6828): [setNextAlert] setNextAlert  temp_Alarmlink + 
E/jeny.kim( 6828): [setNextAlert]setNextAlert temp_AlarmLinkText + 
I/CommonUtil( 6828): BUILD Country: EU
D/Alarms  ( 6828): broadcastToWidgetProvider : false
,D/Alarms  ( 6828): Enter formatDayAndTime(final Context context, long timeInMiliSec)
,V/SettingsProvider( 1039): call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
,I/DigitalAppWidgetProvider( 6828): onReceive: android.intent.action.TIME_SET
V/DigitalAppWidgetProvider( 6828): cancelAlarmOnQuarterHour android.app.ReceiverRestrictedContext@1127cb12
V/DigitalAppWidgetProvider( 6828): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@1127cb12
D/QuickCoverProvider( 6828): onReceiver
I/indal   ( 1396): SmartCoverWidgetContext createApplicationContext
,I/indal   ( 1396): SmartCoverWidgetContext createApplicationContext
D/WeatherAncestor( 6693): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 2:26:8
,D/Weather.Utils( 6693): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6693): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6693): 2 : This is isUpdating : false
D/WeatherService( 6693): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@fbd22e3
D/ForecastDataCache( 6693): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 6693): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 6693): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 6693): 2 : set auto-update time : 2/10 5:26
D/WeatherAncestor( 6693): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 2:26:8
,I/ActivityManager( 1039): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=6852 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/ActivityManager( 1039): Killing 6263:com.lge.lifetracker/u0a37 (adj 15): empty #17
,D/GCM     ( 2123): Connected
,W/libprocessgroup( 1039): failed to open /acct/uid_10037/pid_6263/cgroup.procs: No such file or directory
,D/GCM     ( 2123): Message class com.google.f.a.a.p
D/TimeService( 6852): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1455067568457
D/        ( 6852): TimeServiceNative: User Time to be set is 1455067568457
D/QC-time-services( 6852): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 6852): Lib:time_genoff_operation: pargs->operation = 0
,D/QC-time-services( 6852): Lib:time_genoff_operation: pargs->ts_val = 1455067568457
D/QC-time-services( 6852): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  366): Daemon: Connection accepted:time_genoff
D/QC-time-services(  366): Daemon:Received base = 2, unit = 1, operation = 0,value = 1455067568457
D/QC-time-services(  366): Daemon:genoff_opr: Base = 2, val = 1455067568457, operation = 0
D/QC-time-services(  366): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS5/19/70 18:38:10
D/QC-time-services(  366): Daemon:Value read from RTC seconds = 14668690000
D/QC-time-services(  366): Daemon:new time 1455067568457 
D/QC-time-services(  366): Daemon: delta 1440398878457 genoff 1440398878457 
D/QC-time-services(  366): Daemon:genoff_persistent_update: Writing genoff = 1440398878457 to memory
D/QC-time-services(  366): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  366): Daemon:time_persistent_memory_opr:Genoff write operation 
D/QC-time-services(  366): Updating the TOD offset
D/QC-time-services(  366): Daemon:genoff_persistent_update: Writing genoff = 1440398878457 to memory
D/QC-time-services(  366): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  366): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services(  366): Daemon:Update to modem bit set
D/QC-time-services(  366): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  366): Daemon: Base = 2, Value being sent to MODEM = 1124434078457
E/QC-time-services( 6852): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
E/QC-time-services(  366): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
E/QC-time-services(  366): Daemon: Time-services: Waiting to acceptconnection
I/ActivityManager( 1039): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetProvider: pid=6870 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi
,I/ActivityManager( 1039): Killing 6333:com.lge.settings.easy/1000 (adj 15): empty #17
W/libprocessgroup( 1039): failed to open /acct/uid_1000/pid_6333/cgroup.procs: No such file or directory
,W/ResourcesManager( 6870): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/CalendarApplication( 6870): CalendarApplication.onCreate()
,D/PreferenceKeysParser( 6870): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 6870): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@8ec7961, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@1bb16c86, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@f403947, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@23b63574, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@4964a9d, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@1127cb12, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@fbd22e3, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@32bb34e0, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@2911f399, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@3633865e, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@11950a3f, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@114ebf0c, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@2c053055, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@9adaa6a, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@da0b5b, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@2faebff8, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@3db57cd1, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@2cf40336, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@2ea40237, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@20be3a4, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@3344150d, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@27751cc2, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@3bac8ad3, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@2cf59610, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@18a9f509, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@16fc430e, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@10ab012f, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@c86033c, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@2673d8c5, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@18bd821a, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@70814b, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@24e1728, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@173e3c41, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@3721a5e6, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@2fc3e727, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@36017dd4, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@18f15b7d, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@28523a72, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@1efdcec3, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@34e2a340, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@15bd3279, lg_preferences_recent_,timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@29858bbe, 
,D/GeneralPreferenceUtils( 6870): [migratePrefrenceKeys] Exit: Version(44001600) >= 42001300
V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Config  ( 6870): [init]
,I/Config  ( 6870): LGCalendar ver.4.40.16
I/Config  ( 6870): start check model
I/Config  ( 6870): start check native_ca
I/Config  ( 6870): Config Operator=OPEN, Country=EU
D/Config  ( 6870): [setDefaultValuesToPref]
D/Config  ( 6870): [parseProfiles]
I/GLSUser ( 2123): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2123): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2123): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2123): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ProfilesParser( 6870): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6870): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6870): [updateProfiletoCountryInfo]
D/GeneralPreference( 6870): [checkAndMigrateOldPreference]
E/AgendaWidgetManager( 6870): [updateWidgets] 
,V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,D/LgeQuickCoverNLService( 1396): onNotificationPosted
D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
W/GLSActivity( 2123): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2123): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2123): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2123): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2123): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2123): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2123): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/BooksAccountManager( 6549): Authentication error
E/BooksAccountManager( 6549): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6549): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6549): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6549): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6549): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6549): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6549): null auth token
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
,D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{3be11da5 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/InitNotificationRingtoneService( 6870): Start InitializeAlertRingtoneService.onHandleIntent
,I/AlertUtils( 6870): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/41
W/HolidayIntentService( 6870): onHandleIntent
D/MonthWidgetProvider( 6870): [onReceive]
D/CalendarWidgetProvider( 6870): [onReceive]
D/CalendarWidgetProvider( 6870): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/HolidayDataLoader( 6870): readJsonAsset : holiday.json
D/CalendarTypeController( 6870): [onUpdateAndInitCalendarTime]
D/WeekWidgetProvider( 6870): [onReceive]
D/CalendarWidgetProvider( 6870): [onReceive]
D/CalendarWidgetProvider( 6870): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 6870): [onUpdateAndInitCalendarTime]
,I/AlertUtils( 6870): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 6870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arpeggio.ogg
I/AlertUtils( 6870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
,I/AlertUtils( 6870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 6870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 6870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 6870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
,E/HolidayIntentService( 6870): onHandleIntent:holiday data empty
I/AlertUtils( 6870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 6870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/DigitalAppWidgetProvider( 6828): onReceive: android.intent.action.ALARM_CHANGED
I/AlertUtils( 6870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
,D/WeatherAncestor( 6693): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 2:26:9
D/Weather.Utils( 6693): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6693): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6693): 2 : This is isUpdating : false
I/AlertUtils( 6870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Afternoon_Walk.ogg
D/Weather_cast( 6693): 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
D/WeatherAncestor( 6693): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 2:26:9
I/AlertUtils( 6870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 6870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
,I/AlertUtils( 6870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 6870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 6870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
,I/AlertUtils( 6870): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/41
I/ActivityManager( 1039): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RequestWriter$NetworkStateReceiver: pid=6901 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/AlertUtils( 6870): set default noti to content://media/internal/audio/media/41
I/InitNotificationRingtoneService( 6870): End InitializeAlertRingtoneService.onHandleIntent
I/ActivityManager( 1039): Killing 6285:com.lge.sync/1000 (adj 15): empty #17
,W/libprocessgroup( 1039): failed to open /acct/uid_1000/pid_6285/cgroup.procs: No such file or directory
,W/ResourcesManager( 6901): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ApiaryClient( 6549): Error response from books API: {
W/ApiaryClient( 6549):  "error": {
W/ApiaryClient( 6549):   "errors": [
W/ApiaryClient( 6549):    {
W/ApiaryClient( 6549):     "domain": "global",
W/ApiaryClient( 6549):     "reason": "required",
W/ApiaryClient( 6549):     "message": "Login Required",
W/ApiaryClient( 6549):     "locationType": "header",
W/ApiaryClient( 6549):     "location": "Authorization"
W/ApiaryClient( 6549):    }
W/ApiaryClient( 6549):   ],
W/ApiaryClient( 6549):   "code": 401,
W/ApiaryClient( 6549):   "message": "Login Required"
W/ApiaryClient( 6549):  }
W/ApiaryClient( 6549): }
W/ApiaryClient( 6549): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6549): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5335455908363876655&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6549): Headers:
W/ApiaryClient( 6549): accept-encoding: [gzip]
W/ApiaryClient( 6549): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6549): gdata-version: 2
D/LgDataFeature( 6901): LgDataFeature() Constructor: none
,D/LgDataFeature( 6901): LgDataFeature() Constructor Done, null
E/WifiStateMachine( 1039):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=4.4, 0.0, 0.0  rx=3.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-926343874] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1039):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-51 f=2412 sc=60 link=72 tx=4.4, 0.0, 0.0  rx=3.0 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:-926343874] gl rssi=-51 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1039): doString: [SIGNAL_POLL]
D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/Babel   ( 6901): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 6901): MmsConfig.loadMmsSettings
,I/Babel   ( 6901): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
I/Babel   ( 6901): MmsConfig.loadFromDatabase
,E/Babel   ( 6901): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 6901): MmsConfig.loadFromResources
W/AudioCapabilities( 6901): Unsupported mime audio/evrc
E/Babel   ( 6901): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 6901): MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,W/AudioCapabilities( 6901): Unsupported mime audio/qcelp
W/VideoCapabilities( 6901): Unrecognized profile 2130706433 for video/avc
W/Settings( 6901): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/AudioCapabilities( 6901): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 6901): Unsupported mime audio/qcelp
W/AudioCapabilities( 6901): Unsupported mime audio/evrc
W/VideoCapabilities( 6901): Unsupported mime video/x-ms-wmv
W/VideoCapabilities( 6901): Unsupported mime video/divx
,W/VideoCapabilities( 6901): Unsupported mime video/divx311
W/VideoCapabilities( 6901): Unsupported mime video/divx4
,W/VideoCapabilities( 6901): Unsupported mime video/mp4v-esdp
I/VideoCapabilities( 6901): Unsupported profile 4 for video/mp4v-es
,W/AudioCapabilities( 6901): Unsupported mime audio/eac3
W/AudioCapabilities( 6901): Unsupported mime audio/ac3
W/AudioCapabilities( 6901): Unsupported mime audio/g726
W/AudioCapabilities( 6901): Unsupported mime audio/wma-voice
W/AudioCapabilities( 6901): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6901): Unsupported mime audio/adpcm
W/VideoCapabilities( 6901): Unsupported mime video/theora
W/VideoCapabilities( 6901): Unsupported mime video/mjpg
W/ResourcesManager( 6901): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6901): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/JNIHelp ( 6901): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/System  ( 6901): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/system/app/Hangouts/Hangouts.apk"],nativeLibraryDirectories=[/system/app/Hangouts/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6901): Installed default security provider GmsCore_OpenSSL
,I/GLSUser ( 2123): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native
I/GLSUser ( 2123): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2123): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2123): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/Babel   ( 6901): UserRecoverableAuthException.
,E/Babel   ( 6901): cfq: BadAuthentication
E/Babel   ( 6901): 	at cfn.a(Unknown Source)
E/Babel   ( 6901): 	at f.a(PG:191)
E/Babel   ( 6901): 	at ava.a(PG:88)
E/Babel   ( 6901): 	at ava.a(PG:128)
E/Babel   ( 6901): 	at bjs.a(PG:255)
E/Babel   ( 6901): 	at bep.a(PG:602)
E/Babel   ( 6901): 	at bep.a(PG:469)
E/Babel   ( 6901): 	at bpo.run(PG:1141)
E/Babel   ( 6901): Error getting auth token
E/Babel   ( 6901): bxl
E/Babel   ( 6901): 	at f.a(PG:201)
E/Babel   ( 6901): 	at ava.a(PG:88)
E/Babel   ( 6901): 	at ava.a(PG:128)
E/Babel   ( 6901): 	at bjs.a(PG:255)
E/Babel   ( 6901): 	at bep.a(PG:602)
E/Babel   ( 6901): 	at bep.a(PG:469)
E/Babel   ( 6901): 	at bpo.run(PG:1141)
I/Babel_RequestWriter( 6901): error sending REQ[fc:8; creat:1455059518417; type:bev-148037187]; took 108 ms (error code == 100)
E/Babel   ( 6901): Account registration failedRedacted-21
E/Babel   ( 6901): bph: null -- null
E/Babel   ( 6901): 	at ava.a(PG:120)
E/Babel   ( 6901): 	at ava.a(PG:128)
E/Babel   ( 6901): 	at bjs.a(PG:255)
E/Babel   ( 6901): 	at bep.a(PG:602)
E/Babel   ( 6901): 	at bep.a(PG:469)
E/Babel   ( 6901): 	at bpo.run(PG:1141)
I/Babel   ( 6901): Account setup failed with error state:106 account:Redacted-21
I/Babel   ( 6901): Account sign in complete with state 106account: Redacted-21
I/art     ( 6901): Note: end time exceeds epoch: 
,I/GLSUser ( 2123): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native
I/GLSUser ( 2123): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2123): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2123): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 2123): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
,I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
E/Babel   ( 6901): Unexpected exception while authenticating.
D/LgeQuickCoverNLService( 1396): onNotificationPosted
E/Babel   ( 6901): cfr: User intervention required. Notification has been pushed.
E/Babel   ( 6901): 	at cfn.b(Unknown Source)
E/Babel   ( 6901): 	at cfn.a(Unknown Source)
E/Babel   ( 6901): 	at f.a(PG:188)
E/Babel   ( 6901): 	at ava.b(PG:143)
E/Babel   ( 6901): 	at bnr.run(PG:5415)
E/Babel   ( 6901): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 6901): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 6901): 	at java.lang.Thread.run(Thread.java:818)
D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{3be11da5 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2123): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2123): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2123): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2123): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1396): onNotificationPosted
D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
,D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
W/GLSActivity( 2123): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2123): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2123): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2123): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2123): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2123): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2123): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6549): Authentication error
E/BooksAccountManager( 6549): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6549): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6549): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6549): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6549): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6549): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6549): null auth token
D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{3be11da5 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6549): Error response from books API: {
W/ApiaryClient( 6549):  "error": {
W/ApiaryClient( 6549):   "errors": [
W/ApiaryClient( 6549):    {
W/ApiaryClient( 6549):     "domain": "global",
W/ApiaryClient( 6549):     "reason": "required",
W/ApiaryClient( 6549):     "message": "Login Required",
W/ApiaryClient( 6549):     "locationType": "header",
W/ApiaryClient( 6549):     "location": "Authorization"
W/ApiaryClient( 6549):    }
W/ApiaryClient( 6549):   ],
W/ApiaryClient( 6549):   "code": 401,
W/ApiaryClient( 6549):   "message": "Login Required"
W/ApiaryClient( 6549):  }
W/ApiaryClient( 6549): }
W/ApiaryClient( 6549): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6549): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5335455908363876655&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6549): Headers:
W/ApiaryClient( 6549): accept-encoding: [gzip]
W/ApiaryClient( 6549): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6549): gdata-version: 2
,I/GAV2    ( 6549): Thread[GAThread,5,main]: No campaign data found.
,I/ThermalEngine(  335): Thermal-Server: Thermal received msg from  override
,I/Thermal-Lib( 2932): Thermal-Lib-Client: Client request sent
,I/jxcore-log( 6046): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 6046): 
E/BooksSync( 6549): Soft error: 
E/BooksSync( 6549): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6549): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5335455908363876655&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6549): Headers:
E/BooksSync( 6549): accept-encoding: [gzip]
E/BooksSync( 6549): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6549): gdata-version: 2
E/BooksSync( 6549): 
E/BooksSync( 6549): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6549): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6549): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6549): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6549): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6549): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6549): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6549): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6549): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6549): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6549): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6549): {
E/BooksSync( 6549):  "error": {
E/BooksSync( 6549):   "errors": [
E/BooksSync( 6549):    {
E/BooksSync( 6549):     "domain": "global",
E/BooksSync( 6549):     "reason": "required",
E/BooksSync( 6549):     "message": "Login Required",
E/BooksSync( 6549):     "locationType": "header",
E/BooksSync( 6549):     "location": "Authorization"
E/BooksSync( 6549):    }
E/BooksSync( 6549):   ],
E/BooksSync( 6549):   "code": 401,
E/BooksSync( 6549):   "message": "Login Required"
E/BooksSync( 6549):  }
E/BooksSync( 6549): }
E/BooksSync( 6549): 
E/BooksSync( 6549): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6549): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6549): 	... 8 more
E/BooksSync( 6549): Sync error
E/BooksSync( 6549): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6549): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5335455908363876655&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6549): Headers:
E/BooksSync( 6549): accept-encoding: [gzip]
E/BooksSync( 6549): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6549): gdata-version: 2
E/BooksSync( 6549): 
E/BooksSync( 6549): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6549): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6549): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6549): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6549): 	at com.googl,e.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6549): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6549): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6549): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6549): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6549): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6549): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6549): {
E/BooksSync( 6549):  "error": {
E/BooksSync( 6549):   "errors": [
E/BooksSync( 6549):    {
E/BooksSync( 6549):     "domain": "global",
E/BooksSync( 6549):     "reason": "required",
E/BooksSync( 6549):     "message": "Login Required",
E/BooksSync( 6549):     "locationType": "header",
E/BooksSync( 6549):     "location": "Authorization"
E/BooksSync( 6549):    }
E/BooksSync( 6549):   ],
E/BooksSync( 6549):   "code": 401,
E/BooksSync( 6549):   "message": "Login Required"
E/BooksSync( 6549):  }
E/BooksSync( 6549): }
E/BooksSync( 6549): 
E/BooksSync( 6549): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6549): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6549): 	... 8 more
I/BooksSync( 6549): Finished books sync
,D/SyncManager( 1039): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 26831, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager( 1039): Killing 5865:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
I/QRemote ( 6372): [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
,W/System.err( 6372): android.os.DeadObjectException
W/System.err( 6372): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6372): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6372): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
,W/System.err( 6372): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
W/System.err( 6372): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 6372): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 6372): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6372): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6372): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6372): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 6372): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6372): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6372): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 6372): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 6372): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 6372): android.os.DeadObjectException
W/System.err( 6372): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6372): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6372): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 6372): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
W/System.err( 6372): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 6372): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 6372): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6372): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6372): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6372): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 6372): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6372): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6372): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 6372): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 6372): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/QRemote ( 6372): [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,W/libprocessgroup( 1039): failed to open /acct/uid_1000/pid_5865/cgroup.procs: No such file or directory
,W/ActivityManager( 1039): Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
D/QRemote ( 6372): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
I/QRemote ( 6372): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
I/ActivityManager( 1039): Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6996 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,D/QRemote ( 6372): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,I/art     ( 1039): Explicit concurrent mark sweep GC freed 18649(865KB) AllocSpace objects, 4(448KB) LOS objects, 33% free, 44MB/66MB, paused 1.727ms total 124.168ms
,I/GAV4    ( 6717): Thread[GAThread,5,main]: No campaign data found.
V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/UEI.SmartControl( 6996): Quickset Services start...
I/UEI.SmartControl( 6996): Manufacture = LGE
D/UEI.SmartControl( 6996): Id = LGNevo
D/UEI.SmartControl( 6996): File observer start...
E/UEI.SmartControl( 6996): IR Port is disabled: false
D/UEI.SmartControl( 6996): Starting file observer...
D/UEI.SmartControl( 6996): Extracting JNI libs...
D/UEI.SmartControl( 6996): --- this system supports 32-bit or 64-bit only
I/GLSUser ( 2123): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
,I/GLSUser ( 2123): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2123): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2123): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1396): onNotificationPosted
W/GLSActivity( 2123): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2123): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2123): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2123): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2123): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2123): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2123): 	at android.os.Binder.execTransact(Binder.java:446)
D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/ContactsSyncAdapter( 2123): innerSync failed
D/ContactsSyncAdapter( 2123): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2123): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2123): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2123): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2123): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2123): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2123): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2123): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2123): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2123): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2123): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2123): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindo,w( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
,E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
D/SyncManager( 1039): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 149546, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{3be11da5 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/UEI.SmartControl( 6996): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 6996): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6996): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/jxcore-log( 6046): Test app app.js loaded
I/jxcore-log( 6046): 
,I/chromium( 6046): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dd4bb00 added. We now have 1 listener(s)
,I/jxcore-log( 6046): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 6046): 
I/UEI.SmartControl( 6996): --- Selecting new region: 6
I/UEI.SmartControl( 6996): Model = LG-D855
,D/UEI.SmartControl( 6996): QS Service created
I/UEI.SmartControl( 6996): Service initServices...
,D/UEI.SmartControl( 6996): QS start get config
,D/UEI.SmartControl( 6996): Loading JNI Libs...
,E/WifiStateMachine( 1039):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=22.7, 0.0, 0.0  rx=18.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-926340862] gl rssi=-59 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1039):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=22.7, 0.0, 0.0  rx=18.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-926340861] gl rssi=-59 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1039): doString: [SIGNAL_POLL]
I/UEI.SmartControl( 6996): Supports setup maps: true
,D/UEI.SmartControl( 6996): QS start statue = true Error code = 0
,I/UEI.SmartControl( 6996): QS version = v2.7.10.1_RC1
,I/UEI.SmartControl( 6996): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6996): ### init IR Blaster...
,I/ActivityManager( 1039): Killing 6218:com.android.settings/1000 (adj 15): empty #17
D/serial_port( 6996): Configuring serial port
D/WifiService( 1039): Client connection lost with reason: 4
,E/UEI.SmartControl( 6996): UEIBLaster setting for 616
I/UEI.SmartControl( 6996): Setting serial record hearder size = 2
I/UEI.SmartControl( 6996): configuring settings for MAXQ616
I/UEI.SmartControl( 6996): Get version...
D/UEI.SmartControl( 6996): serial port data available: 21
,W/libprocessgroup( 1039): failed to open /acct/uid_1000/pid_6218/cgroup.procs: No such file or directory
D/UEI.SmartControl( 6996): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 6996): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 6996): QS saving settings...
,D/UEI.SmartControl( 6996): IR Blaster version: 25672567
,D/UEI.SmartControl( 6996): serial port data available: 4
,I/UEI.SmartControl( 6996): Device manager: loading config....
D/UEI.SmartControl( 6996): ----------- loading internal config...
,W/ContextImpl( 6996): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
E/UEI.SmartControl( 6996): Services init done
D/UEI.SmartControl( 6996): QS Service init finished
D/UEI.SmartControl( 6996): QS Service version name: 2.1.91
D/UEI.SmartControl( 6996): QS Service version code: 201091
,D/UEI.SmartControl( 6996): Service requested: Control
D/UEI.SmartControl( 6996): Request IControl service: devices are loaded...
I/ActivityManager( 1039): Killing 6372:com.lge.qremote/u0a112 (adj 15): empty #17
E/UEI.SmartControl( 6996): Loading SETTINGS...
,D/UEI.SmartControl( 6996): -- Open brand translation xml: brands_translations_ko
,I/UEI.SmartControl( 6996): Notify AllClients services are ready: 0
,D/UEI.SmartControl( 6996): -----service ready thread exits
D/UEI.SmartControl( 6996): Internal service binding...
W/libprocessgroup( 1039): failed to open /acct/uid_10112/pid_6372/cgroup.procs: No such file or directory
,I/[SystemUI]LGPowerUI( 1444): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1444): On Skip Timer : true
,D/WifiController( 1039): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1444): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 291
I/[SystemUI]LGPowerUI( 1444): onReceive = android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1958): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1958): Battery Level Remaining: 100%
D/LEDHandler( 1958): Battery Temp: 291, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1444): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 6181): Disconnected process message: 10, size: 0
,D/LGDMClient( 3247): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
,D/LGDMClient( 3247): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,I/ActivityManager( 1039): Killing 5581:com.android.vending/u0a44 (adj 15): empty #17
,W/libprocessgroup( 1039): failed to open /acct/uid_10044/pid_5581/cgroup.procs: No such file or directory
,E/WifiStateMachine( 1039):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=13.3, 0.0, 0.0  rx=10.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-926337851] gl rssi=-59 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1039):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=13.3, 0.0, 0.0  rx=10.5 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-926337842] gl rssi=-59 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,D/WifiNative-wlan0( 1039): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 126583145215; DSPS: 4288636; Offset : -4307890733
,D/serial_port( 6996): close(fd = 25)
,D/UEI.SmartControl( 6996): Internal timer expired: 1
D/UEI.SmartControl( 6996): unbind internal service
D/UEI.SmartControl( 6996): Service.onUnbind: IControl
,D/UEI.SmartControl( 6996): Service.onDestroy
D/UEI.SmartControl( 6996): Lock is in USE false
D/UEI.SmartControl( 6996): unbind internal service
W/System.err( 6996): java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@2911f399
W/System.err( 6996): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
W/System.err( 6996): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
W/System.err( 6996): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
W/System.err( 6996): 	at com.uei.control.Service.c(Unknown Source)
W/System.err( 6996): 	at com.uei.control.Service.onDestroy(Unknown Source)
W/System.err( 6996): 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
W/System.err( 6996): 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
W/System.err( 6996): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
W/System.err( 6996): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6996): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6996): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 6996): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6996): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6996): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 6996): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 6996): java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@2911f399
I/UEI.SmartControl( 6996): Serial port is closed.
I/UEI.SmartControl( 6996): Serial port is closed.
I/UEI.SmartControl( 6996): Serial port is closed.
D/UEI.SmartControl( 6996): Blaster closed
D/UEI.SmartControl( 6996): Shut down QS...
D/UEI.SmartControl( 6996): Stopping QS lib
D/UEI.SmartControl( 6996): QS lib stop result = true
D/UEI.SmartControl( 6996): Stopped QS lib
,D/UEI.SmartControl( 6996): Stopped file observer...
,D/UEI.SmartControl( 6996): QS shutdown complete
,E/WifiStateMachine( 1039):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=7.7, 0.0, 0.0  rx=6.2 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-926334821] gl rssi=-59 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1039):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=7.7, 0.0, 0.0  rx=6.2 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-926334809] gl rssi=-59 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,D/WifiNative-wlan0( 1039): doString: [SIGNAL_POLL]
I/[SystemUI]LGPowerUI( 1444): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1444): On Skip Timer : true
,E/WifiStateMachine( 1039):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=3.8, 0.0, 0.0  rx=3.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-926331789] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1039):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=3.8, 0.0, 0.0  rx=3.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-926331786] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1039): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1039):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=2.4, 0.0, 0.0  rx=2.1 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-926328760] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1039):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=2.4, 0.0, 0.0  rx=2.1 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-926328750] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1039): doString: [SIGNAL_POLL]
I/[SystemUI]QPairHandler( 1444): onReceive = android.intent.action.PACKAGE_CHANGED
,D/SplitUIService( 1869): replaced split : contains_com.google.android.talk / true
,I/InputReader( 1039): Reconfiguring input devices.  changes=0x00000010
,I/[SystemUI]QSlideListController( 1444): onReceive = android.intent.action.PACKAGE_CHANGED
,I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1444): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.talk
D/SplitUIManager( 1869): split_name #11 / not available #0
I/SplitUIService( 1869): split app #11
,D/administrator( 1039): Handling package changes for user 0
,I/AppUp4:CustModeStarterReceiver( 6530): onReceive
,I/[LGHome]EVENT( 2068): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000010 (has extras) }
,D/AppUp4:CustFacade( 6530): Context : android.app.ReceiverRestrictedContext@4964a9d
D/AppUp4:CustFacade( 6530): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6530): isPhone : true
D/AppUp4:CustModeStarterReceiver( 6530): begin check event
I/AppUp4:CustModeStarterReceiver( 6530): Event For Nothing, skip.
W/ResourcesManager( 2068): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/[LGHome]Launcher( 2068): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/ActivityManager( 1039): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7055 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/NotificationService( 1039): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService( 1039): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000010 (has extras) }
,W/ResourcesManager( 1039): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 7055): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7055): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7055): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7055): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7055): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,W/ResourcesManager( 1039): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourceType( 1039): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/[LGHome]EVENT( 2068): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/SystemConfig( 7055): BUILD Country: EU
I/SystemConfig( 7055): BUILD Operator: OPEN
,I/ActivityManager( 1039): Killing 6244:com.lge.formmanager/u0a26 (adj 15): empty #17
,W/libprocessgroup( 1039): failed to open /acct/uid_10026/pid_6244/cgroup.procs: No such file or directory
,I/SystemConfig( 7055): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7055): existFile = false
,I/SystemConfig( 7055): canReadFile = false
I/SystemConfig( 7055): systemFeature RCS result false
D/SystemConfig( 7055): refreshRcsSupport() :false
,I/UpdateIcingCorporaServi( 4183): Updating corpora: APPS=com.google.android.talk, CONTACTS=MAYBE
,V/SIM_STK ( 1039): Menu title from STK is T-Mobile
,I/ActivityManager( 1039): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7080 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
W/ResourcesManager( 4183): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 4183): UpdateCorporaTask done [took 77 ms] updated apps [took 77 ms] 
,I/LockScreenSettings( 7080): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7080): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,D/LockScreenSettings( 7080): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7080): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7080): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7080): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
D/LockScreenSettings( 7080): Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,I/ActivityManager( 1039): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7101 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1039): Killing 6670:com.lge.drmservice/u0a62 (adj 15): empty #17
,W/libprocessgroup( 1039): failed to open /acct/uid_10062/pid_6670/cgroup.procs: No such file or directory
,D/Finsky  ( 7101): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/LgDataFeature( 7101): LgDataFeature() Constructor: none
D/LgDataFeature( 7101): LgDataFeature() Constructor Done, null
,D/Finsky  ( 7101): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/ActivityManager( 1039): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=7140 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/Settings( 7101): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7101): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ResourcesManager( 7140): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7140): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/DownloadManager( 3368): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3368): created cursor android.database.sqlite.SQLiteCursor@30aa5ca on behalf of 7101
,I/MultiDex( 7140): VM with version 2.1.0 has multidex support
,I/MultiDex( 7140): install
I/MultiDex( 7140): VM has multidex support, MultiDex support library is disabled.
D/Finsky  ( 7101): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7101): [1] 2.run: Finished loading 1 libraries.
D/Finsky  ( 7101): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/PackageBroadcastService( 2323): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.talk
,V/JNIHelp ( 7140): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
D/Finsky  ( 7101): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager( 1039): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=7176 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/ActivityManager( 1039): Killing 6717:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
I/PeopleContactsSync( 2323): CP2 sync disabled
,W/ActivityThread( 7140): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7140): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@150a606e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7140): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup( 1039): failed to open /acct/uid_10093/pid_6717/cgroup.procs: No such file or directory
,D/GCM     ( 2123): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 2123): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GmsCoreStatsServiceLauncher( 2323): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,W/ResourcesManager( 7176): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7176): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/LocationInitializer( 2323): Restart initialization of location
,I/MultiDex( 7176): VM with version 2.1.0 has multidex support
I/MultiDex( 7176): install
I/MultiDex( 7176): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 7176): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 7176): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7176): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@150a606e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7176): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 7176): callingUid 10005, callindPid: 7176
,W/NativeLibraryUtils( 7176): Install did not work
W/NativeLibraryUtils( 7176): java.io.IOException: fcntl failed: EAGAIN (Try again)
W/NativeLibraryUtils( 7176): 	at java.nio.FileChannelImpl.basicLock(FileChannelImpl.java:123)
W/NativeLibraryUtils( 7176): 	at java.nio.FileChannelImpl.tryLock(FileChannelImpl.java:181)
W/NativeLibraryUtils( 7176): 	at java.nio.channels.FileChannel.tryLock(FileChannel.java:584)
W/NativeLibraryUtils( 7176): 	at com.google.android.gms.common.util.ax.a(SourceFile:314)
W/NativeLibraryUtils( 7176): 	at com.google.android.gms.common.app.a.run(SourceFile:136)
W/NativeLibraryUtils( 7176): Caused by: android.system.ErrnoException: fcntl failed: EAGAIN (Try again)
W/NativeLibraryUtils( 7176): 	at libcore.io.Posix.fcntlFlock(Native Method)
W/NativeLibraryUtils( 7176): 	at libcore.io.ForwardingOs.fcntlFlock(ForwardingOs.java:70)
W/NativeLibraryUtils( 7176): 	at java.nio.FileChannelImpl.basicLock(FileChannelImpl.java:121)
W/NativeLibraryUtils( 7176): 	... 4 more
,I/ActivityManager( 1039): Killing 6610:com.android.chrome/u0a57 (adj 15): empty #17
W/libprocessgroup( 1039): failed to open /acct/uid_10057/pid_6610/cgroup.procs: No such file or directory
,D/GCM     ( 2123): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
E/MDM     ( 1817): [87] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
D/AuthorizationBluetoothService( 2123): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/Finsky  ( 7101): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,V/GmsCoreStatsServiceLauncher( 2323): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
E/MDM     ( 1817): [88] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 2323): Restart initialization of location
,E/WifiStateMachine( 1039):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=1.7, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-926325716] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1039):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=1.7, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-926325713] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1039): doString: [SIGNAL_POLL]
,V/AlarmManager( 1039): RTC_WAKEUP set : Alarm{243d78cc type 0 when 1455067586145 com.android.vending} when 1455067586145
,V/AlarmManager( 1039): RTC_WAKEUP set : Alarm{34d55a2a type 0 when 1455067587299 com.android.vending} when 1455067587299
D/Finsky  ( 7101): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,I/ActivityManager( 1039): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7219 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/art     (  347): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 437us total 48.948ms
,I/art     (  347): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 410us total 30.523ms
V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  347): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 517us total 19.079ms
,I/GLSUser ( 2123): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2123): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2123): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2123): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/SIM_STK ( 1039): Menu title from STK is T-Mobile
,W/ResourcesManager( 7219): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
I/art     ( 2123): Explicit concurrent mark sweep GC freed 29588(1704KB) AllocSpace objects, 15(1904KB) LOS objects, 51% free, 30MB/62MB, paused 980us total 49.704ms
,D/QRemote ( 7219): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,W/Finsky  ( 7101): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2123): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 2123): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2123): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2123): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/QRemote ( 7219): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
I/QRemote ( 7219): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 7219): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 7219): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 7219): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 7219): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 7219): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
,V/QRemote ( 7219): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
D/QRemote ( 7219): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:8144
D/QRemote ( 7219): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
D/QRemote ( 7219): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
V/QRemote ( 7219): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7219): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 7219): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,D/LgDataFeature( 7219): LgDataFeature() Constructor: none
D/LgDataFeature( 7219): LgDataFeature() Constructor Done, null
,V/SoundPool( 7219): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 7219): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 7219): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 7219): doLoad: loading sample sampleID=1
I/QRemote ( 7219): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
V/SoundPool( 7219): Start decode
V/MediaPlayer[Native]( 7219): decode(31, 10857164, 17813)
D/QRemote ( 7219): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
D/UEI.SmartControl( 6996): QS Service created
V/MediaPlayerService(  318): decode(23, 10857164, 17813)
W/BrunchPlayerTypeImpl(  318): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  318): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  318): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  318): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  318): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  318): player type = 3
V/AwesomePlayer(  318): AwesomePlayer create()
V/AwesomePlayer(  318): reset_l() 
V/AwesomePlayer(  318): cancelPlayerEvents
V/AwesomePlayer(  318): setAudioSink() 
V/AwesomePlayer(  318): reset_l() 
V/AudioCache(  318): notify(0xb5474bc0, 8, 0, 0)
V/AudioCache(  318): ignored
V/AwesomePlayer(  318): cancelPlayerEvents
D/Utils   (  318): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  318): setDataSource_l dataSource
V/LGParserOSAL(  318): SniffLGParser start
V/LGParserOSAL(  318): MainType:5, SubType=0
V/LGParserOSAL(  318): #### check Mime : application/ogg
V/LGParserOSAL(  318): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  318): Use LGExtractor :application/ogg 
E/QRemote ( 7219): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7219): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,I/UEI.SmartControl( 6996): Service initServices...
D/UEI.SmartControl( 6996): QS start get config
V/LGParserOSAL(  318): supported mime: application/ogg
V/AwesomePlayer(  318): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  318): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  318): mBitrate = -1 bits/sec
V/AwesomePlayer(  318): AudioTrack Setting
V/AwesomePlayer(  318): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  318): setAudioSource() 
V/MediaPlayerService(  318): prepare
,V/AwesomePlayer(  318): prepareAsync_l() 
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
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb1434290 on input port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc0b0 on input port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc790 on input port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc7e0 on input port
V/OMXCodec(  318): allocateBuffersOnPort portIndex=1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc830 on output port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc8d0 on output port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc920 on output port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb14fcb00 on output port
V/OMXCodec(  318): init() mAsyncCompletion wait!!! 
V/OMXCodec(  318): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  318): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  318): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  318): init() mAsyncCompletion wait!!! 
V/OMXCodec(  318): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  318): [OMX.google,.vorbis.decoder] Now Executing.
V/OMXCodec(  318): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  318): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  318): finishAsyncPrepare_l() 
V/AudioCache(  318): notify(0xb5474bc0, 5, 0, 0)
V/AudioCache(  318): ignored
V/AudioCache(  318): notify(0xb5474bc0, 1, 0, 0)
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
V/LGMDMManager( 7219): Create singleton instance
V/OMXCodec(  318): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  318): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  318): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  318): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974795824
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974795984
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974796064
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974796544
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  318): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  318): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  318): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  318): allocateBuffersOnPort portIndex=1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc920 on output port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc8d0 on output port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc830 on output port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  318): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  318): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  318): notify(0xb5474bc0, 6, 0, 0)
V/AudioCache(  318): ignored
V/MediaPlayerService(  318): wait for playback complete
,V/AudioCache(  318): write(0xb57c5000, 4096)
V/AudioCache(  318): memcpy(0xaf1ff000, 0xb57c5000, 4096)
V/AudioCache(  318): write(0xb57c5000, 4096)
V/AudioCache(  318): memcpy(0xaf200000, 0xb57c5000, 4096)
V/AudioCache(  318): write(0xb57c5000, 4096),
V/AudioCache(  318): memcpy(0xaf201000, 0xb57c5000, 4096)
V/AudioCache(  318): write(0xb57c5000, 4096)
V/AudioCache(  318): memcpy(0xaf202000, 0xb57c5000, 4096)
V/AudioCache(  318): write(0xb57c5000, 4096)
V/AudioCache(  318): memcpy(0xaf203000, 0xb57c5000, 4096)
V/AudioCache(  318): write(0xb57c5000, 4096)
V/AudioCache(  318): memcpy(0xaf204000, 0xb57c5000, 4096)
V/AudioCache(  318): write(0xb57c5000, 4096)
V/AudioCache(  318): memcpy(0xaf205000, 0xb57c5000, 4096)
V/AudioCache(  318): write(0xb57c5000, 4096)
V/AudioCache(  318): memcpy(0xaf206000, 0xb57c5000, 4096)
V/AudioCache(  318): write(0xb57c5000, 4096)
V/AudioCache(  318): memcpy(0xaf207000, 0xb57c5000, 4096)
V/AudioCache(  318): write(0xb57c5000, 4096)
V/AudioCache(  318): memcpy(0xaf208000, 0xb57c5000, 4096)
V/AudioCache(  318): write(0xb57c5000, 4096)
V/AudioCache(  318): memcpy(0xaf209000, 0xb57c5000, 4096)
V/AudioCache(  318): write(0xb57c5000, 4096)
,V/AudioCache(  318): memcpy(0xaf20a000, 0xb57c5000, 4096)
V/AudioCache(  318): write(0xb57c5000, 4096)
V/AudioCache(  318): memcpy(0xaf20b000, 0xb57c5000, 4096)
V/AudioCache(  318): write(0xb57c5000, 4096)
V/AudioCache(  318): memcpy(0xaf20c000, 0xb57c5000, 4096)
,V/AudioCache(  318): write(0xb57c5000, 4096)
V/AudioCache(  318): memcpy(0xaf20d000, 0xb57c5000, 4096)
V/AudioCache(  318): write(0xb57c5000, 4096)
V/AudioCache(  318): memcpy(0xaf20e000, 0xb57c5000, 4096)
V/AudioCache(  318): write(0xb57c5000, 4096)
V/AudioCache(  318): memcpy(0xaf20f000, 0xb57c5000, 4096)
V/AudioCache(  318): write(0xb57c5000, 4096)
V/AudioCache(  318): memcpy(0xaf210000, 0xb57c5000, 4096)
V/AudioCache(  318): write(0xb57c5000, 4096)
V/AudioCache(  318): memcpy(0xaf211000, 0xb57c5000, 4096)
V/AudioCache(  318): write(0xb57c5000, 4096)
V/AudioCache(  318): memcpy(0xaf212000, 0xb57c5000, 4096)
V/AudioCache(  318): write(0xb57c5000, 4096)
V/AudioCache(  318): memcpy(0xaf213000, 0xb57c5000, 4096)
V/AudioCache(  318): write(0xb57c5000, 4096)
V/AudioCache(  318): memcpy(0xaf214000, 0xb57c5000, 4096)
V/AudioCache(  318): write(0xb57c5000, 4096)
V/AudioCache(  318): memcpy(0xaf215000, 0xb57c5000, 4096)
V/AudioCache(  318): write(0xb57c5000, 4096)
V/AudioCache(  318): memcpy(0xaf216000, 0xb57c5000, 4096)
V/AudioCache(  318): write(0xb57c5000, 4096)
V/AudioCache(  318): memcpy(0xaf217000, 0xb57c5000, 4096)
V/AudioCache(  318): write(0xb57c5000, 4096)
V/AudioCache(  318): memcpy(0xaf218000, 0xb57c5000, 4096)
V/AudioCache(  318): write(0xb57c5000, 4096)
V/AudioCache(  318): memcpy(0xaf219000, 0xb57c5000, 4096)
V/AudioCache(  318): write(0xb57c5000, 4096)
V/AudioCache(  318): memcpy(0xaf21a000, 0xb57c5000, 4096)
V/AudioCache(  318): write(0xb57c5000, 4096)
V/AudioCache(  318): memcpy(0xaf21b000, 0xb57c5000, 4096)
,V/AudioCache(  318): write(0xb57c5000, 4096)
V/AudioCache(  318): memcpy(0xaf21c000, 0xb57c5000, 4096)
V/AudioCache(  318): write(0xb57c5000, 4096)
V/AudioCache(  318): memcpy(0xaf21d000, 0xb57c5000, 4096)
V/AudioCache(  318): write(0xb57c5000, 4096)
V/AudioCache(  318): memcpy(0xaf21e000, 0xb57c5000, 4096)
V/AudioCache(  318): write(0xb57c5000, 4096)
V/AudioCache(  318): memcpy(0xaf21f000, 0xb57c5000, 4096)
V/AudioCache(  318): write(0xb57c5000, 4096)
V/AudioCache(  318): memcpy(0xaf220000, 0xb57c5000, 4096)
V/AudioCache(  318): write(0xb57c5000, 4096)
V/AudioCache(  318): memcpy(0xaf221000, 0xb57c5000, 4096)
V/AudioCache(  318): write(0xb57c5000, 4096)
V/AudioCache(  318): memcpy(0xaf222000, 0xb57c5000, 4096)
V/AudioCache(  318): write(0xb57c5000, 4096)
V/AudioCache(  318): memcpy(0xaf223000, 0xb57c5000, 4096)
V/AudioCache(  318): write(0xb57c5000, 4096)
V/AudioCache(  318): memcpy(0xaf224000, 0xb57c5000, 4096)
V/AudioCache(  318): write(0xb57c5000, 4096)
V/AudioCache(  318): memcpy(0xaf225000, 0xb57c5000, 4096)
V/AudioCache(  318): write(0xb57c5000, 4096)
V/AudioCache(  318): memcpy(0xaf226000, 0xb57c5000, 4096)
V/AudioCache(  318): write(0xb57c5000, 4096)
V/AudioCache(  318): memcpy(0xaf227000, 0xb57c5000, 4096)
V/AudioCache(  318): write(0xb57c5000, 4096)
V/AudioCache(  318): memcpy(0xaf228000, 0xb57c5000, 4096)
V/AudioCache(  318): write(0xb57c5000, 4096)
V/AudioCache(  318): memcpy(0xaf229000, 0xb57c5000, 4096)
V/AudioCache(  318): write(0xb57c5000, 4096)
V/AudioCache(  318): memcpy(0xaf22a000, 0xb57c5000, 4096)
,V/AudioCache(  318): write(0xb57c5000, 4096)
V/AudioCache(  318): memcpy(0xaf22b000, 0xb57c5000, 4096)
V/AudioCache(  318): write(0xb57c5000, 4096)
V/AudioCache(  318): memcpy(0xaf22c000, 0xb57c5000, 4096)
V/AudioCache(  318): write(0xb57c5000, 4096)
V/AudioCache(  318): memcpy(0xaf22d000, 0xb57c5000, 4096)
V/AudioCache(  318): write(0xb57c5000, 4096)
V/AudioCache(  318): memcpy(0xaf22e000, 0xb57c5000, 4096)
V/AudioCache(  318): write(0xb57c5000, 4096)
V/AudioCache(  318): memcpy(0xaf22f000, 0xb57c5000, 4096)
V/AudioCache(  318): write(0xb57c5000, 4096)
V/AudioCache(  318): memcpy(0xaf230000, 0xb57c5000, 4096)
V/OMXCodec(  318): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  318): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  318): postAudioEOS() 
V/AudioCache(  318): write(0xb57c5000, 280)
V/AudioCache(  318): memcpy(0xaf231000, 0xb57c5000, 280)
V/AwesomePlayer(  318): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  318): onStreamDone
V/AwesomePlayer(  318): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  318): notify(0xb5474bc0, 2, 0, 0)
V/AudioCache(  318): playback complete
V/AwesomePlayer(  318): pause_l() 
V/AudioCache(  318): notify(0xb5474bc0, 7, 0, 0)
V/AudioCache(  318): ignored
V/AwesomePlayer(  318): cancelPlayerEvents
V/AudioCache(  318): wait - success
V/MediaPlayerService(  318): return size 205080, sampleRate=48000, channelCount = 2, format = 1
D/AudioPlayer(  318): Pause Playback at 1068125
V/AwesomePlayer(  318): reset_l() 
V/AudioCache(  318): notify(0xb5474bc0, 8, 0, 0)
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
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc7e0 on port 0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc790 on port 0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc0b0 on port 0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeing buffer 0xb1434290 on port 0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc830 on port 1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc8d0 on port 1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc920 on port 1
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
,D/AudioPlayer(  318): AudioPlayer releasing audio source
D/AudioPlayer(  318): AudioPlayer done releasing audio source
V/AwesomePlayer(  318): reset_l() 
V/AwesomePlayer(  318): cancelPlayerEvents
V/AwesomePlayer(  318): ~AwesomePlayer call
V/AwesomePlayer(  318): reset_l() 
V/AwesomePlayer(  318): cancelPlayerEvents
V/SoundPool( 7219): close(31)
V/SoundPool( 7219): pointer = 0x9ffe6000, size = 205080, sampleRate = 48000, numChannels = 2
D/QRemote ( 7219): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7219): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
D/QRemote ( 7219): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:5189
,V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2123): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2123): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2123): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2123): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7101): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 7101): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7101): [1] 5.onFinished: Scheduling replication attempt 3.
I/GLSUser ( 2123): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2123): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2123): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2123): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 7101): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/UEI.SmartControl( 6996): Supports setup maps: true
,D/UEI.SmartControl( 6996): QS start statue = true Error code = 0
,I/UEI.SmartControl( 6996): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6996): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6996): ### init IR Blaster...
D/serial_port( 6996): Configuring serial port
E/UEI.SmartControl( 6996): UEIBLaster setting for 616
I/UEI.SmartControl( 6996): Setting serial record hearder size = 2
I/UEI.SmartControl( 6996): configuring settings for MAXQ616
I/UEI.SmartControl( 6996): Get version...
V/SIM_STK ( 1039): Menu title from STK is T-Mobile
D/UEI.SmartControl( 6996): serial port data available: 21
,D/UEI.SmartControl( 6996): MAXQ616 A2-X4 software.
,I/UEI.SmartControl( 6996): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 6996): QS saving settings...
D/UEI.SmartControl( 6996): IR Blaster version: 25672567
D/UEI.SmartControl( 6996): serial port data available: 4
,I/UEI.SmartControl( 6996): Device manager: loading config....
,W/ContextImpl( 6996): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,D/UEI.SmartControl( 6996): ----------- loading internal config...
E/UEI.SmartControl( 6996): Services init done
D/UEI.SmartControl( 6996): QS Service init finished
D/UEI.SmartControl( 6996): QS Service version name: 2.1.91
D/UEI.SmartControl( 6996): QS Service version code: 201091
D/UEI.SmartControl( 6996): Service requested: Control
D/UEI.SmartControl( 6996): Request IControl service: devices are loaded...
E/UEI.SmartControl( 6996): Loading SETTINGS...
D/UEI.SmartControl( 6996): Internal service binding...
I/QRemote ( 7219): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
,I/UEI.SmartControl( 6996): ------ IControl API: 11
D/UEI.SmartControl( 6996): File observer start...
E/UEI.SmartControl( 6996): IR Port is disabled: false
D/UEI.SmartControl( 6996): Starting file observer...
I/UEI.SmartControl( 6996): Registering callback...
I/UEI.SmartControl( 6996): ------ IControl API: 19
D/UEI.SmartControl( 6996): -- Open brand translation xml: brands_translations_ko
I/UEI.SmartControl( 6996): Registering Services Ready callback...
I/UEI.SmartControl( 6996): Notify AllClients services are ready: 0
,D/UEI.SmartControl( 6996): -----service ready thread exits
I/QRemote ( 7219): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 7219): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 7219): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 7219): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 7219): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6996): ------ IControl API: 8
D/QRemote ( 7219): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 7219): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 7219): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 7219): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 7219): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7219): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 7219): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
V/QRemote ( 7219): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7219): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,E/QRemote ( 7219): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7219): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 7219): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7219): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 7219): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 7219): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1455067588945]
D/QRemote ( 7219): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
D/QRemote ( 7219): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,V/QRemote ( 7219): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
E/QRemote ( 7219): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7219): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 7219): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 7219): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 7219): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 7219): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
,D/QRemote ( 7219): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1039): Explicit concurrent mark sweep GC freed 35127(1644KB) AllocSpace objects, 3(176KB) LOS objects, 33% free, 44MB/66MB, paused 2.755ms total 187.723ms
,I/GLSUser ( 2123): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2123): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2123): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2123): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 7101): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 7101): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
D/Finsky  ( 7101): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7101): [1] DailyHygiene.reschedule: Scheduling new run in 29 minutes (failures=2)
,D/DeviceConnectionService( 1817): client connected with version: 7571000
I/ActivityManager( 1039): Killing 6593:com.lge.email/u0a23 (adj 15): empty #17
,W/libprocessgroup( 1039): failed to open /acct/uid_10023/pid_6593/cgroup.procs: No such file or directory
,E/WifiStateMachine( 1039):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=1.9, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-926322687] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1039):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=1.9, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-926322686] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1039): doString: [SIGNAL_POLL]
,I/ActivityManager( 1039): Killing 5124:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,W/libprocessgroup( 1039): failed to open /acct/uid_1000/pid_5124/cgroup.procs: No such file or directory
,E/WifiStateMachine( 1039):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-926319665] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1039):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=1.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-926319662] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1039): doString: [SIGNAL_POLL]
,D/serial_port( 6996): close(fd = 24)
,I/UEI.SmartControl( 6996): Serial port is closed.
,D/UEI.SmartControl( 6996): Internal timer expired: 2
,D/UEI.SmartControl( 6996): unbind internal service
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{d8d7a78 type 2 when 145206 android} when 145206
,V/QRemote ( 7219): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
D/QRemote ( 7219): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:5189
,E/WifiStateMachine( 1039):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-926316639] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1039):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-926316635] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1039): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 146584700885; DSPS: 4944047; Offset : -4307891407
,E/WifiStateMachine( 1039):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-926313609] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1039):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-926313605] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1039): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1039):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,E/WifiStateMachine( 1039):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,E/WifiStateMachine( 1039):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,E/WifiStateMachine( 1039):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,E/WifiStateMachine( 1039):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1039):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,E/WifiStateMachine( 1039):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-926310564] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1039):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-926310561] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0,
D/WifiNative-wlan0( 1039): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1039):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-926307536] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1039):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-926307533] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1039): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1039):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-926304510] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1039):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-926304500] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1039): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1039):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-926301478] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1039):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-926301475] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1039): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1039):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-926298452] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1039):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-926298442] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1039): doString: [SIGNAL_POLL]
V/AlarmManager( 1039): RTC_WAKEUP set : Alarm{2e7f81b6 type 0 when 1455067608702 com.android.vending} when 1455067608702
,V/SIM_STK ( 1039): Menu title from STK is T-Mobile
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 166586068221; DSPS: 5599452; Offset : -4307897467
,V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2123): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 2123): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2123): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2123): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7101): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7101): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 7101): [1] 5.onFinished: Scheduling replication attempt 4.
,E/WifiStateMachine( 1039):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-926295406] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1039):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-926295403] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1039): doString: [SIGNAL_POLL]
,I/[SystemUI]TimeTickManager( 1444): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1444): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1444): called onTimeUpdated()
,I/[SystemUI]Clock( 1444): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1444): called onTimeUpdated()
I/[SystemUI]DateView( 1444): called onTimeUpdated()
I/[SystemUI]DateView( 1444): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1444): handleTimeUpdate
E/WifiStateMachine( 1039):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-926292377] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1039):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-926292374] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1039): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1039):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-926289353] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1039):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-926289350] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1039): doString: [SIGNAL_POLL]
,D/PowerManagerServiceEx( 1039): acquireWakeLockInternal: lock=545313920, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1039
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{349071a8 type 2 when 175250 android} when 175250
D/[Concierge]Service( 2616): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1039): releaseWakeLockInternal: lock=545313920 [*alarm*], flags=0x0
,I/BooksSync( 6549): Starting books sync
,D/BooksSync( 6549): started syncMyEbooks
,V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2123): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
,I/GLSUser ( 2123): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2123): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2123): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
,I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1396): onNotificationPosted
D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
W/GLSActivity( 2123): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2123): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2123): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2123): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2123): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2123): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2123): 	at android.os.Binder.execTransact(Binder.java:446)
,D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
D/ContactsSyncAdapter( 2123): innerSync failed
D/ContactsSyncAdapter( 2123): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2123): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2123): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2123): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2123): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2123): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2123): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2123): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2123): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2123): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2123): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2123): 	at android.os.Binder.execTransact(Binder.java:446)
D/QuickStatusbarLayout( 1396): Notification difference=198
,D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{3be11da5 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/SyncManager( 1039): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 149546, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager( 1039): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 241381, reason: 10019
I/GLSUser ( 2123): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2123): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2123): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2123): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2123): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2123): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2123): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2123): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2123): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2123): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2123): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1396): onNotificationPosted
D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
E/BooksAccountManager( 6549): Authentication error
E/BooksAccountManager( 6549): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6549): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6549): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6549): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6549): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6549): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
E/HttpHelper( 6549): null auth token
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{3be11da5 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6549): Error response from books API: {
W/ApiaryClient( 6549):  "error": {
W/ApiaryClient( 6549):   "errors": [
W/ApiaryClient( 6549):    {
W/ApiaryClient( 6549):     "domain": "global",
W/ApiaryClient( 6549):     "reason": "required",
W/ApiaryClient( 6549):     "message": "Login Required",
W/ApiaryClient( 6549):     "locationType": "header",
W/ApiaryClient( 6549):     "location": "Authorization"
W/ApiaryClient( 6549):    }
W/ApiaryClient( 6549):   ],
W/ApiaryClient( 6549):   "code": 401,
W/ApiaryClient( 6549):   "message": "Login Required"
W/ApiaryClient( 6549):  }
W/ApiaryClient( 6549): }
W/ApiaryClient( 6549): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6549): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4442064757349851474&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6549): Headers:
W/ApiaryClient( 6549): accept-encoding: [gzip]
W/ApiaryClient( 6549): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6549): gdata-version: 2
,E/WifiStateMachine( 1039):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-926286325] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1039):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-926286322] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1039): doString: [SIGNAL_POLL]
,V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2123): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2123): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2123): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2123): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1396): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
W/GLSActivity( 2123): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2123): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2123): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2123): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2123): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2123): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2123): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6549): Authentication error
E/BooksAccountManager( 6549): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6549): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6549): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6549): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6549): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6549): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6549): null auth token
D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{3be11da5 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6549): Error response from books API: {
W/ApiaryClient( 6549):  "error": {
W/ApiaryClient( 6549):   "errors": [
W/ApiaryClient( 6549):    {
W/ApiaryClient( 6549):     "domain": "global",
W/ApiaryClient( 6549):     "reason": "required",
W/ApiaryClient( 6549):     "message": "Login Required",
W/ApiaryClient( 6549):     "locationType": "header",
W/ApiaryClient( 6549):     "location": "Authorization"
W/ApiaryClient( 6549):    }
W/ApiaryClient( 6549):   ],
W/ApiaryClient( 6549):   "code": 401,
W/ApiaryClient( 6549):   "message": "Login Required"
W/ApiaryClient( 6549):  }
W/ApiaryClient( 6549): }
,W/ApiaryClient( 6549): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6549): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4442064757349851474&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6549): Headers:
W/ApiaryClient( 6549): accept-encoding: [gzip]
W/ApiaryClient( 6549): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6549): gdata-version: 2
,V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2123): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2123): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2123): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2123): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1396): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
,W/GLSActivity( 2123): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2123): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2123): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2123): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2123): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2123): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2123): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6549): Authentication error
E/BooksAccountManager( 6549): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6549): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6549): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6549): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6549): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6549): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6549): null auth token
D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{3be11da5 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6549): Error response from books API: {
W/ApiaryClient( 6549):  "error": {
W/ApiaryClient( 6549):   "errors": [
W/ApiaryClient( 6549):    {
W/ApiaryClient( 6549):     "domain": "global",
W/ApiaryClient( 6549):     "reason": "required",
W/ApiaryClient( 6549):     "message": "Login Required",
W/ApiaryClient( 6549):     "locationType": "header",
W/ApiaryClient( 6549):     "location": "Authorization"
W/ApiaryClient( 6549):    }
W/ApiaryClient( 6549):   ],
W/ApiaryClient( 6549):   "code": 401,
W/ApiaryClient( 6549):   "message": "Login Required"
W/ApiaryClient( 6549):  }
W/ApiaryClient( 6549): }
,W/ApiaryClient( 6549): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6549): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4442064757349851474&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6549): Headers:
W/ApiaryClient( 6549): accept-encoding: [gzip]
W/ApiaryClient( 6549): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6549): gdata-version: 2
,E/BooksSync( 6549): Soft error: 
E/BooksSync( 6549): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6549): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4442064757349851474&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6549): Headers:
E/BooksSync( 6549): accept-encoding: [gzip]
E/BooksSync( 6549): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6549): gdata-version: 2
E/BooksSync( 6549): 
E/BooksSync( 6549): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6549): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6549): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6549): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6549): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6549): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6549): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6549): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6549): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6549): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6549): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6549): {
E/BooksSync( 6549):  "error": {
E/BooksSync( 6549):   "errors": [
E/BooksSync( 6549):    {
E/BooksSync( 6549):     "domain": "global",
E/BooksSync( 6549):     "reason": "required",
E/BooksSync( 6549):     "message": "Login Required",
E/BooksSync( 6549):     "locationType": "header",
E/BooksSync( 6549):     "location": "Authorization"
E/BooksSync( 6549):    }
E/BooksSync( 6549):   ],
E/BooksSync( 6549):   "code": 401,
E/BooksSync( 6549):   "message": "Login Required"
E/BooksSync( 6549):  }
E/BooksSync( 6549): }
E/BooksSync( 6549): 
E/BooksSync( 6549): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6549): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6549): 	... 8 more
,E/BooksSync( 6549): Sync error
E/BooksSync( 6549): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6549): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4442064757349851474&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6549): Headers:
E/BooksSync( 6549): accept-encoding: [gzip]
E/BooksSync( 6549): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6549): gdata-version: 2
E/BooksSync( 6549): 
E/BooksSync( 6549): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6549): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6549): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6549): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6549): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6549): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6549): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6549): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6549): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6549): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6549): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6549): {
E/BooksSync( 6549):  "error": {
E/BooksSync( 6549):   "errors": [
E/BooksSync( 6549):    {
E/BooksSync( 6549):     "domain": "global",
E/BooksSync( 6549):     "reason": "required",
E/BooksSync( 6549):     "message": "Login Required",
E/BooksSync( 6549):     "locationType": "header",
E/BooksSync( 6549):     "location": "Authorization"
E/BooksSync( 6549):    }
E/BooksSync( 6549):   ],
E/BooksSync( 6549):   "code": 401,
E/BooksSync( 6549):   "message": "Login Required"
E/BooksSync( 6549):  }
E/BooksSync( 6549): }
E/BooksSync( 6549): 
E/BooksSync( 6549): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6549): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6549): 	... 8 more
I/BooksSync( 6549): Finished books sync
D/SyncManager( 1039): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 153127, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/WifiStateMachine( 1039):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=2.2, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-926283303] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1039):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=2.2, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-926283300] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1039): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1039):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=4.6, 0.0, 0.0  rx=3.3 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-926280276] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1039):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=4.6, 0.0, 0.0  rx=3.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-926280273] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1039): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1039):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=2.3, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-926277249] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1039):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=2.3, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-926277245] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1039): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 186587799411; DSPS: 6254868; Offset : -4307875130
,E/WifiStateMachine( 1039):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=1.6, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:2999] from screen [on:0 period:-926274222] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1039):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=1.6, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-926274219] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1039): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1039):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-926271195] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1039):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-926271192] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1039): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1039):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-926268168] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1039):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-926268165] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1039): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1039):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-926265140] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1039):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-926265130] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1039): doString: [SIGNAL_POLL]
V/AlarmManager( 1039): RTC_WAKEUP set : Alarm{30d636e4 type 0 when 1455067637303 com.android.vending} when 1455067637303
,V/SIM_STK ( 1039): Menu title from STK is T-Mobile
,V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2123): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2123): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2123): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2123): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7101): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 7101): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 7101): [1] 5.onFinished: Scheduling replication attempt 5.
,E/WifiStateMachine( 1039):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-926262108] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1039):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-926262105] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1039): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1039):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-926259084] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1039):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-926259081] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1039): doString: [SIGNAL_POLL]
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{228d4726 type 2 when 205490 android} when 205490
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 206589579507; DSPS: 6910287; Offset : -4307895572
,E/WifiStateMachine( 1039):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-926256055] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1039):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-926256052] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1039): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1039):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-926253025] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1039):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-926253022] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1039): doString: [SIGNAL_POLL]
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{2f390f67 type 2 when 182018 com.google.android.gms} when 182018
V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{ea72114 type 2 when 210597 android} when 210597
,V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 2123): Vacuum at: now=1455067662108 tag=VacuumService
,I/GoogleURLConnFactory( 2123): Using platform SSLCertificateSocketFactory
,W/Uploader( 2123): No account for auth token provided
D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  313): res_queryN name = play.googleapis.com, class = 1, type = 1
D/libc-netbsd(  313): res_queryN name = play.googleapis.com succeed
,W/Uploader( 2123): No account for auth token provided
,W/Uploader( 2123):  no longer exists, so no auth token.
,W/Uploader( 2123): No account for auth token provided
,W/Uploader( 2123): No account for auth token provided
,E/WifiStateMachine( 1039):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-926250002] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1039):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-926249999] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1039): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1039):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=9.9, 0.0, 0.0  rx=6.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-926246964] gl rssi=-59 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1039):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=9.9, 0.0, 0.0  rx=6.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-926246961] gl rssi=-59 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,D/WifiNative-wlan0( 1039): doString: [SIGNAL_POLL]
,V/AlarmManager( 1039): RTC_WAKEUP set : Alarm{149e25f1 type 0 when 1455067668813 com.android.vending} when 1455067668813
,V/SIM_STK ( 1039): Menu title from STK is T-Mobile
,V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2123): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2123): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2123): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2123): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7101): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 7101): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 7101): [1] 5.onFinished: Giving up after 6 failures.
,E/WifiStateMachine( 1039):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=5.5, 0.0, 0.0  rx=3.7 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-926243940] gl rssi=-59 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1039):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=5.5, 0.0, 0.0  rx=3.7 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-926243930] gl rssi=-59 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,D/WifiNative-wlan0( 1039): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1039):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=2.7, 0.0, 0.0  rx=1.9 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-926240908] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1039):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=2.7, 0.0, 0.0  rx=1.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-926240905] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1039): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1039):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=1.9, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-926237882] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1039):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=1.9, 0.0, 0.0  rx=1.4 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-926237873] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1039): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 226603198510; DSPS: 7566093; Offset : -4307887408
,E/WifiStateMachine( 1039):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-926234851] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1039):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=1.4, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-926234842] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1039): doString: [SIGNAL_POLL]
D/PowerManagerServiceEx( 1039): acquireWakeLockInternal: lock=545313920, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1039
,D/[Concierge]Service( 2616): onStartCommand(). Type : 9
,I/[SystemUI]TimeTickManager( 1444): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1444): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1444): called onTimeUpdated()
I/[SystemUI]Clock( 1444): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1444): called onTimeUpdated()
I/[SystemUI]DateView( 1444): called onTimeUpdated()
I/[SystemUI]DateView( 1444): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1444): handleTimeUpdate
D/PowerManagerServiceEx( 1039): releaseWakeLockInternal: lock=545313920 [*alarm*], flags=0x0
,E/WifiStateMachine( 1039):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-926231821] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1039):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-926231811] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1039): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1039):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-926228789] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1039):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-926228785] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1039): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1039):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-926225760] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1039):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-926225750] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1039): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1039):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-926222726] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1039):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-926222722] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1039): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1039):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-926219702] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1039):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-926219699] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1039): doString: [SIGNAL_POLL]
V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{23dec56b type 2 when 243587 android} when 243587
,I/art     ( 1039): Explicit concurrent mark sweep GC freed 61175(2MB) AllocSpace objects, 6(608KB) LOS objects, 33% free, 44MB/66MB, paused 3.427ms total 172.906ms
,I/BooksSync( 6549): Starting books sync
,D/BooksSync( 6549): started syncMyEbooks
,V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2123): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2123): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2123): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2123): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1396): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
W/GLSActivity( 2123): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2123): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2123): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2123): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2123): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2123): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2123): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
,D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
E/BooksAccountManager( 6549): Authentication error
E/BooksAccountManager( 6549): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6549): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6549): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6549): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6549): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6549): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6549): null auth token
D/QuickStatusbarLayout( 1396): Notification difference=198
,D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{3be11da5 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6549): Error response from books API: {
W/ApiaryClient( 6549):  "error": {
W/ApiaryClient( 6549):   "errors": [
W/ApiaryClient( 6549):    {
W/ApiaryClient( 6549):     "domain": "global",
W/ApiaryClient( 6549):     "reason": "required",
W/ApiaryClient( 6549):     "message": "Login Required",
W/ApiaryClient( 6549):     "locationType": "header",
W/ApiaryClient( 6549):     "location": "Authorization"
W/ApiaryClient( 6549):    }
W/ApiaryClient( 6549):   ],
W/ApiaryClient( 6549):   "code": 401,
W/ApiaryClient( 6549):   "message": "Login Required"
W/ApiaryClient( 6549):  }
W/ApiaryClient( 6549): }
,W/ApiaryClient( 6549): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6549): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=8898640654022906453&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6549): Headers:
W/ApiaryClient( 6549): accept-encoding: [gzip]
W/ApiaryClient( 6549): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6549): gdata-version: 2
,V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 2123): Explicit concurrent mark sweep GC freed 49561(2MB) AllocSpace objects, 14(1783KB) LOS objects, 51% free, 30MB/62MB, paused 2.442ms total 69.955ms
,I/GLSUser ( 2123): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2123): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2123): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2123): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1396): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
,D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{3be11da5 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/GLSActivity( 2123): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2123): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2123): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2123): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2123): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2123): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2123): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6549): Authentication error
E/BooksAccountManager( 6549): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6549): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6549): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6549): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6549): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6549): 	at android.os.Binder.execTransact(Binder.java:446)
,E/HttpHelper( 6549): null auth token
W/ApiaryClient( 6549): Error response from books API: {
W/ApiaryClient( 6549):  "error": {
W/ApiaryClient( 6549):   "errors": [
W/ApiaryClient( 6549):    {
W/ApiaryClient( 6549):     "domain": "global",
W/ApiaryClient( 6549):     "reason": "required",
W/ApiaryClient( 6549):     "message": "Login Required",
W/ApiaryClient( 6549):     "locationType": "header",
W/ApiaryClient( 6549):     "location": "Authorization"
W/ApiaryClient( 6549):    }
W/ApiaryClient( 6549):   ],
W/ApiaryClient( 6549):   "code": 401,
W/ApiaryClient( 6549):   "message": "Login Required"
W/ApiaryClient( 6549):  }
W/ApiaryClient( 6549): }
,W/ApiaryClient( 6549): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6549): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=8898640654022906453&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6549): Headers:
W/ApiaryClient( 6549): accept-encoding: [gzip]
W/ApiaryClient( 6549): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6549): gdata-version: 2
,E/WifiStateMachine( 1039):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-926216672] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1039):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-926216663] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1039): doString: [SIGNAL_POLL]
,V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2123): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2123): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2123): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2123): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 246608986263; DSPS: 8221643; Offset : -4307898152
V/GLSActivity( 2123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1396): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1396): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1396): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1396): handleNotificationPosted(true)
D/QuickCircle( 1396): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1396): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): post do just update job
D/LgeQuickCoverNotificationData( 1396): showAll3
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1396): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1396): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1396): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1396): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1396): updateNotificationData: count=3
W/GLSActivity( 2123): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2123): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2123): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2123): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2123): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2123): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2123): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6549): Authentication error
E/BooksAccountManager( 6549): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6549): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6549): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6549): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6549): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6549): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6549): null auth token
D/QuickStatusbarLayout( 1396): Notification difference=198
D/QuickStatusbarLayout( 1396): child = android.widget.LinearLayout{3be11da5 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6549): Error response from books API: {
W/ApiaryClient( 6549):  "error": {
W/ApiaryClient( 6549):   "errors": [
W/ApiaryClient( 6549):    {
W/ApiaryClient( 6549):     "domain": "global",
W/ApiaryClient( 6549):     "reason": "required",
W/ApiaryClient( 6549):     "message": "Login Required",
W/ApiaryClient( 6549):     "locationType": "header",
W/ApiaryClient( 6549):     "location": "Authorization"
W/ApiaryClient( 6549):    }
W/ApiaryClient( 6549):   ],
W/ApiaryClient( 6549):   "code": 401,
W/ApiaryClient( 6549):   "message": "Login Required"
W/ApiaryClient( 6549):  }
W/ApiaryClient( 6549): }
,W/ApiaryClient( 6549): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6549): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=8898640654022906453&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6549): Headers:
W/ApiaryClient( 6549): accept-encoding: [gzip]
W/ApiaryClient( 6549): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6549): gdata-version: 2
,E/BooksSync( 6549): Soft error: 
E/BooksSync( 6549): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6549): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=8898640654022906453&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6549): Headers:
E/BooksSync( 6549): accept-encoding: [gzip]
E/BooksSync( 6549): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6549): gdata-version: 2
E/BooksSync( 6549): 
E/BooksSync( 6549): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6549): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6549): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6549): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6549): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6549): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6549): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6549): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6549): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6549): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6549): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6549): {
E/BooksSync( 6549):  "error": {
E/BooksSync( 6549):   "errors": [
E/BooksSync( 6549):    {
E/BooksSync( 6549):     "domain": "global",
E/BooksSync( 6549):     "reason": "required",
E/BooksSync( 6549):     "message": "Login Required",
E/BooksSync( 6549):     "locationType": "header",
E/BooksSync( 6549):     "location": "Authorization"
E/BooksSync( 6549):    }
E/BooksSync( 6549):   ],
E/BooksSync( 6549):   "code": 401,
E/BooksSync( 6549):   "message": "Login Required"
E/BooksSync( 6549):  }
E/BooksSync( 6549): }
E/BooksSync( 6549): 
E/BooksSync( 6549): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6549): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6549): 	... 8 more
,E/BooksSync( 6549): Sync error
E/BooksSync( 6549): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6549): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=8898640654022906453&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6549): Headers:
E/BooksSync( 6549): accept-encoding: [gzip]
E/BooksSync( 6549): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6549): gdata-version: 2
E/BooksSync( 6549): 
E/BooksSync( 6549): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6549): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6549): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6549): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6549): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6549): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6549): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6549): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6549): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6549): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6549): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6549): {
E/BooksSync( 6549):  "error": {
E/BooksSync( 6549):   "errors": [
E/BooksSync( 6549):    {
E/BooksSync( 6549):     "domain": "global",
E/BooksSync( 6549):     "reason": "required",
E/BooksSync( 6549):     "message": "Login Required",
E/BooksSync( 6549):     "locationType": "header",
E/BooksSync( 6549):     "location": "Authorization"
E/BooksSync( 6549):    }
E/BooksSync( 6549):   ],
E/BooksSync( 6549):   "code": 401,
E/BooksSync( 6549):   "message": "Login Required"
E/BooksSync( 6549):  }
E/BooksSync( 6549): }
E/BooksSync( 6549): 
E/BooksSync( 6549): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6549): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6549): 	... 8 more
I/BooksSync( 6549): Finished books sync
D/SyncManager( 1039): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 243587, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/WifiStateMachine( 1039):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=3.7, 0.0, 0.0  rx=2.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-926213641] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1039):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=3.7, 0.0, 0.0  rx=2.7 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-926213631] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1039): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1039):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=3.4, 0.0, 0.0  rx=2.4 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-926210607] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1039):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=3.4, 0.0, 0.0  rx=2.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-926210604] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1039): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1039):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=2.2, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-926207578] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1039):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=2.2, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-926207575] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1039): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1039):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=1.6, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-926204550] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1039):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=1.6, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-926204540] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1039): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1039):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-926201520] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1039):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.8, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-926201507] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1039): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1039):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-926198485] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1039):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-926198482] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1039): doString: [SIGNAL_POLL]
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 266611247766; DSPS: 8877077; Offset : -4307894897
,E/WifiStateMachine( 1039):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-926195455] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1039):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-926195452] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1039): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1039):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-926192430] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1039):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-926192420] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,D/WifiNative-wlan0( 1039): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1039):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-926189399] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1039):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.9, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-926189395] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1039): doString: [SIGNAL_POLL]
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{2d5d8f7d type 2 when 273612 android} when 273612
,I/jxcore-log( 6046): TAP version 13
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # setup
I/jxcore-log( 6046): 
I/jxcore-log( 6046): # multiplex can send data
I/jxcore-log( 6046): 
I/jxcore-log( 6046): # teardown
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): ok 1 String should be length:200
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # setup
I/jxcore-log( 6046): 
I/jxcore-log( 6046): # enqueue and run in order
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # teardown
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): ok 2 firstPromise setTimeout
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): ok 3 firstPromise result
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): ok 4 firstPromise testValue
I/jxcore-log( 6046): 
I/jxcore-log( 6046): ok 5 secondPromise setTimeout
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): ok 6 secondPromise result
I/jxcore-log( 6046): 
I/jxcore-log( 6046): ok 7 secondPromise testValue
I/jxcore-log( 6046): 
I/jxcore-log( 6046): ok 8 thirdPromise in promise
I/jxcore-log( 6046): 
I/jxcore-log( 6046): ok 9 thirdPromise result
I/jxcore-log( 6046): 
I/jxcore-log( 6046): ok 10 thirdPromise testValue
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # setup
I/jxcore-log( 6046): 
I/jxcore-log( 6046): # basic
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # teardown
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): ok 11 sane
I/jxcore-log( 6046): 
I/jxcore-log( 6046): # setup
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # another
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # teardown
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): ok 12 sane
I/jxcore-log( 6046): 
I/jxcore-log( 6046): # setup
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 6046): 
,E/WifiStateMachine( 1039):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-926186369] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine( 1039):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-926186365] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1039): doString: [SIGNAL_POLL]
I/jxcore-log( 6046): # teardown
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): ok 13 should be equal
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): ok 14 null
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): ok 15 (unnamed assert)
I/jxcore-log( 6046): 
I/jxcore-log( 6046): ok 16 should be equal
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): ok 17 should not throw
I/jxcore-log( 6046): 
I/jxcore-log( 6046): # setup
I/jxcore-log( 6046): 
I/jxcore-log( 6046): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # teardown
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): ok 18 (unnamed assert)
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): ok 19 (unnamed assert)
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): ok 20 should not throw
I/jxcore-log( 6046): 
I/jxcore-log( 6046): ok 21 should be equal
I/jxcore-log( 6046): 
I/jxcore-log( 6046): ok 22 should be equal
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # setup
I/jxcore-log( 6046): 
I/jxcore-log( 6046): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # teardown
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): ok 23 should be equal
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # setup
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # failed to get mobile documents path
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # teardown
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): ok 24 should be equal
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # setup
I/jxcore-log( 6046): 
I/jxcore-log( 6046): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # teardown
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): ok 25 should be equal
I/jxcore-log( 6046): 
I/jxcore-log( 6046): ok 26 should be equal
I/jxcore-log( 6046): 
I/jxcore-log( 6046): ok 27 should be equal
I/jxcore-log( 6046): 
I/jxcore-log( 6046): # setup
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # #init should register the networkChanged event
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # teardown
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): ok 28 should be equal
I/jxcore-log( 6046): 
I/jxcore-log( 6046): # setup
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # #startBroadcasting should throw on null device name
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # teardown
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): ok 29 should throw
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # setup
I/jxcore-log( 6046): 
I/jxcore-log( 6046): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # teardown
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): ok 30 should throw
I/jxcore-log( 6046): 
I/jxcore-log( 6046): # setup
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # #startBroadcasting should throw on non-number port
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # teardown
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): ok 31 should throw
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # setup
I/jxcore-log( 6046): 
I/jxcore-log( 6046): # #startBroadcasting should throw on NaN port
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # teardown
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): ok 32 should throw
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # setup
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # #startBroadcasting should throw on negative port
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # teardown
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): ok 33 should throw
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # setup
I/jxcore-log( 6046): 
I/jxcore-log( 6046): # #startBroadcasting should throw on too large port
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # teardown
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): ok 34 should throw
I/jxcore-log( 6046): 
I/jxcore-log( 6046): # setup
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # teardown
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): ok 35 should be equal
I/jxcore-log( 6046): 
I/jxcore-log( 6046): ok 36 should be equal
I/jxcore-log( 6046): 
I/jxcore-log( 6046): ok 37 should be equal
I/jxcore-log( 6046): 
I/jxcore-log( 6046): # setup
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # teardown
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): ok 38 should be equal
I/jxcore-log( 6046): 
I/jxcore-log( 6046): ok 39 should be equal
I/jxcore-log( 6046): 
I/jxcore-log( 6046): ok 40 should be equal
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # setup
I/jxcore-log( 6046): 
I/jxcore-log( 6046): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # teardown
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): ok 41 should be equal
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): ok 42 should be equal
I/jxcore-log( 6046): 
I/jxcore-log( 6046): # setup
I/jxcore-log( 6046): 
I/jxcore-log( 6046): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # teardown
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): ok 43 should be equal
I/jxcore-log( 6046): 
I/jxcore-log( 6046): ok 44 should be equal
I/jxcore-log( 6046): 
I/jxcore-log( 6046): # setup
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # teardown
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): ok 45 should be equal
I/jxcore-log( 6046): 
I/jxcore-log( 6046): ok 46 should be equal
I/jxcore-log( 6046): 
I/jxcore-log( 6046): ok 47 should be equal
I/jxcore-log( 6046): 
I/jxcore-log( 6046): # setup
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # teardown
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): ok 48 should be equal
I/jxcore-log( 6046): 
I/jxcore-log( 6046): ok 49 should be equal
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # setup
I/jxcore-log( 6046): 
I/jxcore-log( 6046): # should call Mobile("Disconnect") without an error
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # teardown
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): ok 50 should be equal
I/jxcore-log( 6046): 
I/jxcore-log( 6046): ok 51 should be equal
I/jxcore-log( 6046): 
I/jxcore-log( 6046): # setup
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # teardown
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): ok 52 should be equal
I/jxcore-log( 6046): 
I/jxcore-log( 6046): ok 53 should be equal
I/jxcore-log( 6046): 
I/jxcore-log( 6046): # setup
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # #start should fail if called twice in a row
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # teardown
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): ok 54 specific error should be received
I/jxcore-log( 6046): 
I/jxcore-log( 6046): # setup
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # #startListeningForAdvertisements should fail if start not called
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # teardown
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): ok 55 specific error should be returned
I/jxcore-log( 6046): 
I/jxcore-log( 6046): # setup
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # should be able to call #stopListeningForAdvertisements many times
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # teardown
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): ok 56 error should be null
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): ok 57 error should be null
I/jxcore-log( 6046): 
I/jxcore-log( 6046): # setup
I/jxcore-log( 6046): 
I/jxcore-log( 6046): # should be able to call #startListeningForAdvertisements many times
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # teardown
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): ok 58 error should be null
I/jxcore-log( 6046): 
I/jxcore-log( 6046): ok 59 error should be null
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # setup
I/jxcore-log( 6046): 
I/jxcore-log( 6046): # should be able to call #startUpdateAdvertisingAndListening many times
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # teardown
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): ok 60 error should be null
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): ok 61 error should be null
I/jxcore-log( 6046): 
I/jxcore-log( 6046): # setup
I/jxcore-log( 6046): 
,E/WifiStateMachine( 1039):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=17.7, 0.0, 0.0  rx=17.7 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-926183354] gl rssi=-59 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1039):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=17.7, 0.0, 0.0  rx=17.7 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-926183353] gl rssi=-59 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1039): doString: [SIGNAL_POLL]
,I/jxcore-log( 6046): # #startUpdateAdvertisingAndListening should fail if start not called
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # teardown
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): ok 62 specific error should be returned
I/jxcore-log( 6046): 
I/jxcore-log( 6046): # setup
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # teardown
I/jxcore-log( 6046): 
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6046): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6046): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6046): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6046): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68dcf39 added. We now have 2 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): setDiscoveryMode: WIFI -> BLE_AND_WIFI
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6046): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1455067730133.6046
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6046): bind: Binding a new listener
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6046): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6046): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1455067730133.6046","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6046): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6046): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6046): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6046): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6046): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6046): start: OK
I/io.jxcore.node.ConnectionHelper( 6046): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1455067730133.6046, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6046): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6046): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6046): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1455067730133.6046","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6046): start: {"pi":"58:3F:54:73:64:C0","pn":"1455067730133.6046","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6046): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1455067730133.6046","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
,W/BluetoothAdapter( 6046): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 6181): [BTUI] createSocketChannel FD=84 mFd=82
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6046): Waiting for incoming connections...
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@5a9cabcc target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@5a9cabcc target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState add service
D/LGWifiP2pService( 1039): add a new client
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435353036373733303133332e36303436222c227261223a2235383a33463a35343a37333a36343a4330227dc027
,D/WifiNative-p2p0( 1039): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435353036373733303133332e36303436222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353036373733303133331f36303436222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1039): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353036373733303133331f36303436222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): start: Starting P2P device discovery...
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1039): doBoolean: P2P_FIND 120
I/wpa_supplicant( 6239): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1958): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1039): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1039): WifiMonitor:p2p0 cnt=20 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1039): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1039): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1039): P2P_FIND 120: returned true
D/LGWifiP2pService( 1039): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6046): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1455067730133.6046, mode: WIFI
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6046): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6046): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 6046): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 6046): start: OK
I/jxcore-log( 6046): ok 63 Should be able to call startBroadcasting without error
I/jxcore-log( 6046): 
I/io.jxcore.node.ConnectionHelper( 6046): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6046): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6046): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6046): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6046): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6046): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6046): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6046): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6046): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6046): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 6046): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6046): stop: Stopping services
D/LGWifiP2pService( 1039): InactiveState{ when=-1ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=-1ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState clear service
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/WifiNative-p2p0( 1039): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353036373733303133331f36303436222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/WifiNative-p2p0( 1039): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353036373733303133331f36303436222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1039): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6046): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): stop: Stopping P2P device discovery...
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1039): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 6239): P2P-FIND-STOPPED 
,D/WfdsMonitor( 1958): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1039): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1039): WifiMonitor:p2p0 cnt=21 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1039): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): P2P device discovery stopped successfully
D/LGWifiP2pService( 1039): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): setState: NOT_INITIALIZED
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6046): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6046): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6046): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6046): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6046): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 6046): ok 64 Should be able to call stopBroadcasting without error
I/jxcore-log( 6046): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6046): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6046): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6046): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6046): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38f325f5 added. We now have 3 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): setDiscoveryMode: WIFI -> BLE_AND_WIFI
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6046): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1455067730259.6046
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6046): bind: Binding a new listener
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6046): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6046): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1455067730259.6046","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6046): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6046): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6046): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6046): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6046): start: OK
I/io.jxcore.node.ConnectionHelper( 6046): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/io.jxcore.node.ConnectionHelper( 6046): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1455067730259.6046, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6046): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6046): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
W/BluetoothAdapter( 6046): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6046): Waiting for incoming connections...
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6046): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1455067730259.6046","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6046): start: {"pi":"58:3F:54:73:64:C0","pn":"1455067730259.6046","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6046): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1455067730259.6046","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@6edc0fa target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@6edc0fa target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState add service
D/LGWifiP2pService( 1039): add a new client
,D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435353036373733303235392e36303436222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1039): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435353036373733303235392e36303436222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353036373733303235391f36303436222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1039): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353036373733303235391f36303436222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onIsWifiPeerDiscoveryStartedChanged: true
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6046): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): startWifiPeerDiscovery: Wi-Fi Direct OK
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1039): doBoolean: P2P_FIND 120
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): start: OK
I/wpa_supplicant( 6239): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1958): Event [P2P: Reject scan trigger since one is already pending]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1455067730259.6046, mode: WIFI
D/WifiMonitor( 1039): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
,E/WifiMonitor( 1039): WifiMonitor:p2p0 cnt=22 dispatchEvent: P2P: Reject scan trigger since one is already pending
,D/WifiNative-p2p0( 1039): P2P_FIND 120: returned true
D/LGWifiP2pService( 1039): discovery change broadcast true
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/io.jxcore.node.ConnectionHelper( 6046): start: OK
I/jxcore-log( 6046): ok 65 Should be able to call startBroadcasting without error
I/jxcore-log( 6046): 
I/io.jxcore.node.ConnectionHelper( 6046): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6046): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6046): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6046): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6046): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6046): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6046): setState: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6046): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6046): onServerStopped
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6046): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6046): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 6046): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 6046): onConnectionManagerStateChanged: NOT_STARTED
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1039): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 6239): P2P-FIND-STOPPED 
D/WifiMonitor( 1039): Event [P2P-FIND-STOPPED ]
D/WfdsMonitor( 1958): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1039): WifiMonitor:p2p0 cnt=23 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1039): P2P_STOP_FIND: returned true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 6046): stopProvideBluetoothMacAddressMode
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6046): stop: Stopping services
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): discovery change broadcast false
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): P2P device discovery stopped successfully
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1039): P2pEnabledState clear service
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): stop: Stopping P2P device discovery...
D/WifiNative-p2p0( 1039): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353036373733303235391f36303436222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
,D/WifiNative-p2p0( 1039): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353036373733303235391f36303436222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
,D/LGWifiP2pService( 1039): remove client information from framework
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1039): doBoolean: P2P_STOP_FIND
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6046): Local services cleared successfully
D/WifiNative-p2p0( 1039): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6046): release: No more listeners, de-initializing...
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState clear service request
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6046): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6046): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6046): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6046): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 6046): ok 66 Should be able to call stopBroadcasting without error
I/jxcore-log( 6046): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6046): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6046): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6046): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6046): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@281d2c71 added. We now have 4 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): setDiscoveryMode: WIFI -> BLE_AND_WIFI
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
,D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6046): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1455067730336.6046
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6046): bind: Binding a new listener
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6046): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6046): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1455067730336.6046","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6046): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6046): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6046): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6046): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6046): start: OK
I/io.jxcore.node.ConnectionHelper( 6046): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 6046): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6046): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6046): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1455067730336.6046, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6046): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6046): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6046): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1455067730336.6046","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6046): start: {"pi":"58:3F:54:73:64:C0","pn":"1455067730336.6046","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6046): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1455067730336.6046","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@aa347c02 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@aa347c02 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState add service
D/LGWifiP2pService( 1039): add a new client
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435353036373733303333362e36303436222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6046): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): start: OK
I/io.jxcore.node.ConnectionHelper( 6046): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1455067730336.6046, mode: WIFI
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 6046): ok 67 Should be able to call startBroadcasting without error
I/jxcore-log( 6046): 
I/io.jxcore.node.ConnectionHelper( 6046): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6046): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6046): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6046): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6046): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6046): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6046): setState: NOT_STARTED
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6046): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): start: OK
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 6046): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 6046): onConnectionManagerStateChanged: NOT_STARTED
D/WifiNative-p2p0( 1039): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435353036373733303333362e36303436222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353036373733303333361f36303436222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1039): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353036373733303333361f36303436222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6046): Local service added successfully
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=-1ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1039): doBoolean: P2P_FIND 120
I/wpa_supplicant( 6239): p2p0: P2P: Reject scan trigger since one is already pending
D/WifiMonitor( 1039): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1039): WifiMonitor:p2p0 cnt=24 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1958): Event [P2P: Reject scan trigger since one is already pending]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6046): Exiting thread
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 6046): stopProvideBluetoothMacAddressMode
D/WifiNative-p2p0( 1039): P2P_FIND 120: returned true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6046): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6046): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): P2P device discovery started successfully
D/LGWifiP2pService( 1039): discovery change broadcast true
D/LGWifiP2pService( 1039): InactiveState{ when=-3ms what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1039): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 6239): P2P-FIND-STOPPED 
D/WifiMonitor( 1039): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1039): WifiMonitor:p2p0 cnt=25 dispatchEvent: P2P-FIND-STOPPED 
D/WfdsMonitor( 1958): Event [P2P-FIND-STOPPED ]
D/WifiNative-p2p0( 1039): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler, }
D/LGWifiP2pService( 1039): discovery change broadcast false
D/LGWifiP2pService( 1039): InactiveState{ when=-1ms what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): stop: Stopping P2P device discovery...
D/LGWifiP2pService( 1039): P2pEnabledState{ when=-1ms what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState clear service
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/WifiNative-p2p0( 1039): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353036373733303333361f36303436222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): setState: NOT_INITIALIZED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): stopWifiPeerDiscovery: Stopped
D/WifiNative-p2p0( 1039): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353036373733303333361f36303436222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1039): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6046): release: No more listeners, de-initializing...
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1039): doBoolean: P2P_STOP_FIND
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6046): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6046): release: No more listeners, de-initializing...
D/WifiNative-p2p0( 1039): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1039): InactiveState{ when=-1ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1039): P2pEnabledState{ when=-1ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6046): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6046): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6046): Service requests cleared successfully
,I/jxcore-log( 6046): ok 68 Should be able to call stopBroadcasting without error
I/jxcore-log( 6046): 
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6046): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6046): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6046): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6046): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12071ead added. We now have 5 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): setDiscoveryMode: WIFI -> BLE_AND_WIFI
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6046): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1455067730405.6046
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6046): bind: Binding a new listener
,D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6046): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6046): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1455067730405.6046","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6046): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6046): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6046): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6046): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6046): start: OK
I/io.jxcore.node.ConnectionHelper( 6046): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 6046): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6046): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6046): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1455067730405.6046, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6046): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6046): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6046): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1455067730405.6046","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6046): start: {"pi":"58:3F:54:73:64:C0","pn":"1455067730405.6046","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6046): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1455067730405.6046","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@5014d7c8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@5014d7c8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState add service
D/LGWifiP2pService( 1039): add a new client
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435353036373733303430352e36303436222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1039): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435353036373733303430352e36303436222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353036373733303430351f36303436222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6046): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): startWifiPeerDiscovery: Wi-Fi Direct OK
D/WifiNative-p2p0( 1039): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353036373733303430351f36303436222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1455067730405.6046, mode: WIFI
,D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-p2p0( 1039): doBoolean: P2P_FIND 120
I/io.jxcore.node.ConnectionHelper( 6046): start: OK
I/wpa_supplicant( 6239): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1958): Event [P2P: Reject scan trigger since one is already pending]
D/WifiNative-p2p0( 1039): P2P_FIND 120: returned true
D/WifiMonitor( 1039): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1039): WifiMonitor:p2p0 cnt=26 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/LGWifiP2pService( 1039): discovery change broadcast true
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 6046): ok 69 Should be able to call startBroadcasting without error
I/jxcore-log( 6046): 
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6046): start: Already running, call stopListening() first to restart
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): start: OK
I/io.jxcore.node.ConnectionHelper( 6046): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6046): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/io.jxcore.node.ConnectionHelper( 6046): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6046): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6046): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6046): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6046): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6046): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6046): Exiting thread
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6046): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6046): onServerStopped
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/io.jxcore.node.ConnectionHelper( 6046): onConnectionManagerStateChanged: NOT_STARTED
D/WifiNative-p2p0( 1039): doBoolean: P2P_STOP_FIND
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): stop: Stopping peer discovery...
I/wpa_supplicant( 6239): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 6046): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6046): stop: Stopping services
,D/WfdsMonitor( 1958): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1039): Event [P2P-FIND-STOPPED ]
D/WifiNative-p2p0( 1039): P2P_STOP_FIND: returned true
E/WifiMonitor( 1039): WifiMonitor:p2p0 cnt=27 dispatchEvent: P2P-FIND-STOPPED 
D/LGWifiP2pService( 1039): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): P2P device discovery stopped successfully
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState clear service
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01,
D/WifiNative-p2p0( 1039): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353036373733303430351f36303436222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/WifiNative-p2p0( 1039): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353036373733303430351f36303436222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1039): remove client information from framework
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): setState: NOT_INITIALIZED
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1039): doBoolean: P2P_STOP_FIND
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): restart: Cannot restart, because not initialized
D/WifiNative-p2p0( 1039): P2P_STOP_FIND: returned true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6046): Local services cleared successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): P2P device discovery stopped successfully
,D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onIsWifiPeerDiscoveryStartedChanged: false
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): stopWifiPeerDiscovery: Stopped
D/LGWifiP2pService( 1039): P2pEnabledState clear service request
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6046): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6046): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6046): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6046): clear
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6046): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 6046): ok 70 Should be able to call stopBroadcasting without error
I/jxcore-log( 6046): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6046): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6046): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6046): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6046): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f23f8a9 added. We now have 6 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): setDiscoveryMode: WIFI -> BLE_AND_WIFI
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6046): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1455067730466.6046
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6046): bind: Binding a new listener
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6046): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6046): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1455067730466.6046","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6046): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6046): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6046): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6046): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6046): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6046): start: OK
I/io.jxcore.node.ConnectionHelper( 6046): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1455067730466.6046, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6046): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6046): bind: Binding a new listener
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6046): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6046): Waiting for incoming connections...
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6046): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1455067730466.6046","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6046): start: {"pi":"58:3F:54:73:64:C0","pn":"1455067730466.6046","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6046): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1455067730466.6046","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@313acb7a target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@313acb7a target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState add service
D/LGWifiP2pService( 1039): add a new client
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435353036373733303436362e36303436222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1039): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435353036373733303436362e36303436222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353036373733303436361f36303436222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1039): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353036373733303436361f36303436222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): start: Starting P2P device discovery...
,D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1039): doBoolean: P2P_FIND 120
I/wpa_supplicant( 6239): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1958): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1039): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1039): WifiMonitor:p2p0 cnt=28 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WifiNative-p2p0( 1039): P2P_FIND 120: returned true
D/LGWifiP2pService( 1039): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6046): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1455067730466.6046, mode: WIFI
I/io.jxcore.node.ConnectionHelper( 6046): start: OK
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6046): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6046): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 6046): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1039): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 6239): P2P-FIND-STOPPED 
D/WfdsMonitor( 1958): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1039): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1039): WifiMonitor:p2p0 cnt=29 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1039): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1039): discovery change broadcast false
I/jxcore-log( 6046): ok 71 Should be able to call startBroadcasting without error,
I/jxcore-log( 6046): 
I/io.jxcore.node.ConnectionHelper( 6046): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6046): stop: Stopping Bluetooth...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6046): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6046): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6046): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6046): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6046): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6046): Exiting thread
I/io.jxcore.node.ConnectionHelper( 6046): onConnectionManagerStateChanged: NOT_STARTED
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): stopForRestart
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6046): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 6046): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6046): stop: Stopping services
,D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState clear service
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): setState: NOT_INITIALIZED
D/WifiNative-p2p0( 1039): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): stopWifiPeerDiscovery: Stopped
,D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353036373733303436361f36303436222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6046): release: No more listeners, de-initializing...
D/WifiNative-p2p0( 1039): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353036373733303436361f36303436222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
,D/LGWifiP2pService( 1039): remove client information from framework
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1039): doBoolean: P2P_STOP_FIND
D/WifiNative-p2p0( 1039): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1039): P2pEnabledState clear service request
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6046): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6046): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6046): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6046): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): setState: NOT_STARTED
I/jxcore-log( 6046): ok 72 Should be able to call stopBroadcasting without error
I/jxcore-log( 6046): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6046): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6046): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6046): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6046): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@321a7665 added. We now have 7 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): setDiscoveryMode: WIFI -> BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 6046): onDiscoveryManagerStateChanged: NOT_STARTED
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6046): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1455067730532.6046
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6046): bind: Binding a new listener
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6046): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6046): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1455067730532.6046","ra":"58:3F:54:73:64:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6046): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6046): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6046): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6046): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6046): start: OK
I/io.jxcore.node.ConnectionHelper( 6046): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 6046): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6046): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1455067730532.6046, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6046): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6046): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6046): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6046): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1455067730532.6046","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6046): start: {"pi":"58:3F:54:73:64:C0","pn":"1455067730532.6046","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6046): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1455067730532.6046","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
,D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@3d164b86 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@3d164b86 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState add service
,D/LGWifiP2pService( 1039): add a new client
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435353036373733303533322e36303436222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1039): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435353036373733303533322e36303436222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353036373733303533321f36303436222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
,D/WifiNative-p2p0( 1039): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353036373733303533321f36303436222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): start: Starting P2P device discovery...
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6046): start: Already running, call stopListening() first to restart
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): startWifiPeerDiscovery: Wi-Fi Direct OK
D/WifiNative-p2p0( 1039): doBoolean: P2P_FIND 120
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): start: OK
I/wpa_supplicant( 6239): p2p0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1455067730532.6046, mode: WIFI
D/WfdsMonitor( 1958): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1039): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1039): WifiMonitor:p2p0 cnt=30 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WifiNative-p2p0( 1039): P2P_FIND 120: returned true
D/LGWifiP2pService( 1039): discovery change broadcast true
I/io.jxcore.node.ConnectionHelper( 6046): start: OK
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6046): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6046): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 6046): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1039): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 6239): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
I/wpa_supplicant( 6239): P2P-FIND-STOPPED 
I/jxcore-log( 6046): ok 73 Should be able to call startBroadcasting without error
I/jxcore-log( 6046): 
D/WfdsMonitor( 1958): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1039): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1039): WifiMonitor:p2p0 cnt=31 dispatchEvent: P2P-FIND-STOPPED 
I/io.jxcore.node.ConnectionHelper( 6046): stop
I/org.tha,liproject.p2p.btconnectorlib.ConnectionManager( 6046): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6046): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6046): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6046): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6046): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6046): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6046): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6046): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6046): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 6046): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6046): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6046): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6046): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6046): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6046): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 6046): ok 74 Should be able to call stopBroadcasting without error
I/jxcore-log( 6046): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6046): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6046): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6046): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6046): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@374113e1 added. We now have 8 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): setDiscoveryMode: WIFI -> BLE_AND_WIFI
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/WifiNative-p2p0( 1039): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1039): InactiveState{ when=-20ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=-20ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): P2P device discovery stopped successfully
D/LGWifiP2pService( 1039): discovery change broadcast false
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=-1ms what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState clear service
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/WifiNative-p2p0( 1039): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353036373733303533321f36303436222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/WifiNative-p2p0( 1039): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353036373733303533321f36303436222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1039): remove client information from framework
D/LGWifiP2pService( 1039): InactiveState{ when=-2ms what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1039): doBoolean: P2P_STOP_FIND
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6046): Local services cleared successfully
D/WifiNative-p2p0( 1039): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1039): InactiveState{ when=-3ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1039): P2pEnabledState{ when=-3ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): P2P device discovery stopped successfully
D/LGWifiP2pService( 1039): P2pEnabledState clear service request
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6046): Service requests cleared successfully
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6046): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1455067730600.6046
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6046): bind: Binding a new listener
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6046): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6046): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1455067730600.6046","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6046): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6046): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6046): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6046): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6046): start: OK
I/io.jxcore.node.ConnectionHelper( 6046): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 6046): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6046): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1455067730600.6046, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6046): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6046): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6046): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6046): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1455067730600.6046","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6046): start: {"pi":"58:3F:54:73:64:C0","pn":"1455067730600.6046","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6046): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1455067730600.6046","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@5a4a5e0e target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@5a4a5e0e target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState add service
D/LGWifiP2pService( 1039): add a new client
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435353036373733303630302e36303436222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1039): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435353036373733303630302e36303436222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353036373733303630301f36303436222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1039): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353036373733303630301f36303436222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onIsWifiPeerDiscoveryStartedChanged: true
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6046): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): startWifiPeerDiscovery: Wi-Fi Direct OK
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): setState: RUNNING_WIFI
D/WifiNative-p2p0( 1039): doBoolean: P2P_FIND 120
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): start: OK
I/io.jxcore.node.ConnectionHelper( 6046): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1455067730600.6046, mode: WIFI
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/wpa_supplicant( 6239): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1958): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1039): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1039): WifiMonitor:p2p0 cnt=32 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
I/jxcore-log( 6046): ok 75 Should be able to call startBroadcasting without error
I/jxcore-log( 6046): 
D/WifiNative-p2p0( 1039): P2P_FIND 120: returned true
E/WifiMonitor( 1039): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1039): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/LGWifiP2pService( 1039): discovery change broadcast true
I/io.jxcore.node.ConnectionHelper( 6046): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6046): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6046): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6046): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6046): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6046): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6046): onServerStopped
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.Wif,iPeerDiscoverer( 6046): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6046): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 6046): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6046): release: 1 listener(s) left
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1039): doBoolean: P2P_STOP_FIND
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6046): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6046): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): stop: Stopping peer discovery...
I/wpa_supplicant( 6239): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 6046): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6046): stop: Stopping services
D/WfdsMonitor( 1958): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1039): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1039): WifiMonitor:p2p0 cnt=33 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1039): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): P2P device discovery stopped successfully
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState clear service
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6046): release: No more listeners, de-initializing...
D/WifiNative-p2p0( 1039): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353036373733303630301f36303436222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/WifiNative-p2p0( 1039): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353036373733303630301f36303436222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1039): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6046): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6046): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6046): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): setState: NOT_STARTED
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1039): doBoolean: P2P_STOP_FIND
I/io.jxcore.node.ConnectionHelper( 6046): onDiscoveryManagerStateChanged: NOT_STARTED
D/WifiNative-p2p0( 1039): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): P2P device discovery stopped successfully
D/LGWifiP2pService( 1039): InactiveState{ when=-4ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=-4ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState clear service request
I/jxcore-log( 6046): ok 76 Should be able to call stopBroadcasting without error
I/jxcore-log( 6046): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6046): Service requests cleared successfully
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6046): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6046): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6046): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6046): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046),: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fda0d1d added. We now have 9 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): setDiscoveryMode: WIFI -> BLE_AND_WIFI
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
,D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6046): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1455067730667.6046
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6046): bind: Binding a new listener
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6046): initialize: My bluetooth address is 58:3F:54:73:64:C0
,D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6046): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1455067730667.6046","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6046): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6046): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6046): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6046): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6046): start: OK
I/io.jxcore.node.ConnectionHelper( 6046): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 6046): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6046): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1455067730667.6046, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6046): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6046): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6046): Waiting for incoming connections...
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6046): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1455067730667.6046","ra":"58:3F:54:73:64:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6046): start: {"pi":"58:3F:54:73:64:C0","pn":"1455067730667.6046","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6046): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1455067730667.6046","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@6f7a0934 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@6f7a0934 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState add service
D/LGWifiP2pService( 1039): add a new client
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435353036373733303636372e36303436222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1039): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435353036373733303636372e36303436222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353036373733303636371f36303436222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): start: Starting P2P device discovery...
D/WifiNative-p2p0( 1039): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353036373733303636371f36303436222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6046): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): setState: RUNNING_WIFI
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): start: OK
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/io.jxcore.node.ConnectionHelper( 6046): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1455067730667.6046, mode: WIFI
D/WifiNative-p2p0( 1039): doBoolean: P2P_FIND 120
I/wpa_supplicant( 6239): p2p0: P2P: Reject scan trigger since one is already pending
D/WifiMonitor( 1039): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
E/WifiMonitor( 1039): WifiMonitor:p2p0 cnt=34 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1958): Event [P2P: Reject scan trigger since one is already pending]
I/jxcore-log( 6046): ok 77 Should be able to call startBroadcasting without error
I/jxcore-log( 6046): 
I/io.jxcore.node.ConnectionHelper( 6046): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6046): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6046): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.,BluetoothConnector( 6046): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6046): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6046): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6046): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6046): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6046): setState: NOT_STARTED
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6046): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 6046): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6046): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6046): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 6046): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 6046): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): stop: Stopping P2P device discovery...
D/WifiNative-p2p0( 1039): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6046): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): setState: STARTED
D/LGWifiP2pService( 1039): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6046): release: No more listeners, de-initializing...
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6046): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): setState: NOT_STARTED
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState clear service
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
I/io.jxcore.node.ConnectionHelper( 6046): onDiscoveryManagerStateChanged: NOT_STARTED
D/WifiNative-p2p0( 1039): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353036373733303636371f36303436222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
,D/WifiNative-p2p0( 1039): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353036373733303636371f36303436222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1039): remove client information from framework
I/jxcore-log( 6046): ok 78 Should be able to call stopBroadcasting without error
I/jxcore-log( 6046): 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6046): Local services cleared successfully
D/LGWifiP2pService( 1039): InactiveState{ when=-2ms what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1039): doBoolean: P2P_STOP_FIND
,I/wpa_supplicant( 6239): P2P-FIND-STOPPED 
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6046): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6046): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6046): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6046): 	Maximum number of connection attempt retries: 0
D/WfdsMonitor( 1958): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1039): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1039): WifiMonitor:p2p0 cnt=35 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1039): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): P2P device discovery stopped successfully
D/LGWifiP2pService( 1039): InactiveState{ when=-4ms what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1039): doBoolean: P2P_STOP_FIND
D/WifiNative-p2p0( 1039): P2P_STOP_FIND: returned true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@350f5e19 added. We now have 10 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): P2P device discovery stopped successfully
D/LGWifiP2pService( 1039): InactiveState{ when=-5ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=-5ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6046): Service requests cleared successfully
D/LGWifiP2pService( 1039): InactiveState{ when=-3ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=-3ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): discovery change broadcast false
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true,
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6046): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1455067730742.6046
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6046): bind: Binding a new listener
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6046): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6046): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1455067730742.6046","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6046): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6046): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6046): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6046): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6046): start: OK
I/io.jxcore.node.ConnectionHelper( 6046): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 6046): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6046): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1455067730742.6046, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6046): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6046): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6046): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6046): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1455067730742.6046","ra":"58:3F:54:73:64:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6046): start: {"pi":"58:3F:54:73:64:C0","pn":"1455067730742.6046","ra":"58:3F:54:73:64:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6046): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1455067730742.6046","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@16831c0 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@16831c0 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState add service
D/LGWifiP2pService( 1039): add a new client
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435353036373733303734322e36303436222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1039): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435353036373733303734322e36303436222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353036373733303734321f36303436222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6046): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): setState: RUNNING_WIFI
D/WifiNative-p2p0( 1039): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353036373733303734321f36303436222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): start: OK
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1039): doBoolean: P2P_FIND 120
I/wpa_supplicant( 6239): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1958): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1039): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1039): WifiMonitor:p2p0 cnt=36 dispatchEvent: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1455067730742.6046, mode: WIFI
I/io.jxcore.node.ConnectionHelper( 6046): start: OK
D/WifiNative-p2p0( 1039): P2P_FIND 120: returned true
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/LGWifiP2pService( 1039): discovery change broadcast true
I/jxcore-log( 6046): ok 79 Should be able to call startBroadcasting without error
I/jxcore-log( 6046): 
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6046): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): start: OK
I/io.jxcore.node.ConnectionHelper( 6046): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6046): stop: Stopping Bluetooth...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6046): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6046): stopListeningForIncomingConnections: Stopping...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6046): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6046): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6046): onServerStopped
I/io.jxcore.node.ConnectionHelper( 6046): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6046): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6046): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6046): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): stop: Stopping peer discovery...
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 6046): stopProvideBluetoothMacAddressMode
D/WifiNative-p2p0( 1039): doBoolean: P2P_STOP_FIND
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6046): stop: Stopping services
I/wpa_supplicant( 6239): P2P-FIND-STOPPED 
I/io.jxcore.node.ConnectionHelper( 6046): onConnectionManagerStateChanged: NOT_STARTED
D/WfdsMonitor( 1958): Event [P2P-FIND-STOPPED ]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): stop: Stopping P2P device discovery...
D/WifiMonitor( 1039): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1039): WifiMonitor:p2p0 cnt=37 dispatchEvent: P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6046): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6046): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6046): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): setState: NOT_STAR,TED
D/WifiNative-p2p0( 1039): P2P_STOP_FIND: returned true
I/io.jxcore.node.ConnectionHelper( 6046): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): P2P device discovery stopped successfully
D/LGWifiP2pService( 1039): InactiveState{ when=-3ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=-3ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): discovery change broadcast false
D/LGWifiP2pService( 1039): InactiveState{ when=-1ms what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=-1ms what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState clear service
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
I/jxcore-log( 6046): ok 80 Should be able to call stopBroadcasting without error
I/jxcore-log( 6046): 
D/WifiNative-p2p0( 1039): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353036373733303734321f36303436222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6046): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6046): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6046): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6046): 	Maximum number of connection attempt retries: 0
D/WifiNative-p2p0( 1039): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353036373733303734321f36303436222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1039): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6046): Local services cleared successfully
D/LGWifiP2pService( 1039): InactiveState{ when=-3ms what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1039): doBoolean: P2P_STOP_FIND
,D/WifiNative-p2p0( 1039): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): P2P device discovery stopped successfully
D/LGWifiP2pService( 1039): InactiveState{ when=-5ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=-5ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6046): Service requests cleared successfully
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2eaec2d5 added. We now have 11 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): setDiscoveryMode: WIFI -> BLE_AND_WIFI
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6046): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1455067730815.6046
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6046): bind: Binding a new listener
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6046): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6046): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1455067730815.6046","ra":"58:3F:54:73:64:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6046): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6046): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6046): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6046): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6046): start: OK
I/io.jxcore.node.ConnectionHelper( 6046): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 6046): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6046): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6046): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1455067730815.6046, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6046): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6046): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6046): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1455067730815.6046","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6046): start: {"pi":"58:3F:54:73:64:C0","pn":"1455067730815.6046","ra":"58:3F:54:73:64:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6046): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1455067730815.6046","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@c9f9b27e target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@c9f9b27e target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState add service
D/LGWifiP2pService( 1039): add a new client
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435353036373733303831352e36303436222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1039): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435353036373733303831352e36303436222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353036373733303831351f36303436222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1039): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353036373733303831351f36303436222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6046): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): setState: RUNNING_WIFI
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): start: OK
D/WifiNative-p2p0( 1039): doBoolean: P2P_FIND 120
I/io.jxcore.node.ConnectionHelper( 6046): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1455067730815.6046, mode: WIFI
I/wpa_supplicant( 6239): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1958): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1039): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1039): WifiMonitor:p2p0 cnt=38 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WifiNative-p2p0( 1039): P2P_FIND 120: returned true
D/LGWifiP2pService( 1039): discovery change broadcast true
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 6046): ok 81 Should be able to call startBroadcasting without error
I/jxcore-log( 6046): 
I/io.jxcore.node.ConnectionHelper( 6046): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6046): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6046): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6046): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6046): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6046): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6046): Exiting thread
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6046): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6046): onServerStopped
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6046): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 6046): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6046): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6046): Local service added successfully
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState clear service
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
I/io.jxcore.node.ConnectionHelper( 6046): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): P2P device discovery started successfully
D/WifiNative-p2p0( 1039): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353036373733303831351f36303436222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/WifiNative-p2p0( 1039): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353036373733303831351f36303436222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1039): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): stop: Stopping P2P device discovery...
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): setState: NOT_INITIALIZED
D/WifiNative-p2p0( 1039): doBoolean: P2P_STOP_FIND
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): setState: STARTED
I/wpa_supplicant( 6239): P2P-FIND-STOPPED 
I/io.jxcore.node.ConnectionHelper( 6046): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6046): Local services cleared successfully
D/WfdsMonitor( 1958): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1039): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1039): WifiMonitor:p2p0 cnt=39 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1039): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): P2P device discovery stopped successfully
D/LGWifiP2pService( 1039): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): discovery change broadcast false
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6046): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onIsWi,fiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): stopWifiPeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6046): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6046): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6046): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 6046): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 6046): ok 82 Should be able to call stopBroadcasting without error
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # setup
I/jxcore-log( 6046): 
E/WifiStateMachine( 1039):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=88.9, 0.0, 0.0  rx=87.4 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-926180343] gl rssi=-59 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1039):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=88.9, 0.0, 0.0  rx=87.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-926180340] gl rssi=-59 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1039): doString: [SIGNAL_POLL]
,I/jxcore-log( 6046): # ThaliEmitter calls startBroadcasting twice with error
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # teardown
I/jxcore-log( 6046): 
,E/WifiStateMachine( 1039):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=51.4, 0.0, 0.0  rx=50.2 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-926177306] gl rssi=-59 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1039):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=51.4, 0.0, 0.0  rx=50.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-926177303] gl rssi=-59 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,D/WifiNative-wlan0( 1039): doString: [SIGNAL_POLL]
,D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 286621348800; DSPS: 9532768; Offset : -4307895077
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6046): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6046): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6046): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6046): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39a5b751 added. We now have 12 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): setDiscoveryMode: WIFI -> BLE_AND_WIFI
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6046): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1455067737977.6046
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6046): bind: Binding a new listener
,D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6046): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6046): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1455067737977.6046","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6046): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6046): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6046): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6046): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6046): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6046): start: OK
I/io.jxcore.node.ConnectionHelper( 6046): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1455067737977.6046, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6046): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6046): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6046): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6046): Waiting for incoming connections...
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6046): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1455067737977.6046","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6046): start: {"pi":"58:3F:54:73:64:C0","pn":"1455067737977.6046","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6046): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1455067737977.6046","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@32e09cde target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@32e09cde target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState add service
D/LGWifiP2pService( 1039): add a new client
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435353036373733373937372e36303436222c227261223a2235383a33463a35343a37333a36343a4330227dc027
,D/WifiNative-p2p0( 1039): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435353036373733373937372e36303436222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353036373733373937371f36303436222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1039): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353036373733373937371f36303436222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): start: Starting P2P device discovery...
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1039): doBoolean: P2P_FIND 120
I/wpa_supplicant( 6239): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1958): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1039): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1039): WifiMonitor:p2p0 cnt=40 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1039): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1039): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1039): P2P_FIND 120: returned true
D/LGWifiP2pService( 1039): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6046): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1455067737977.6046, mode: WIFI
,D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6046): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6046): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 6046): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1039): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 6239): P2P-FIND-STOPPED 
D/WfdsMonitor( 1958): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1039): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1039): WifiMonitor:p2p0 cnt=41 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1039): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): P2P device discovery stopped successfully
D/LGWifiP2pService( 1039): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): setState: RESTARTING
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1039): doBoolean: P2P_STOP_FIND
D/WifiNative-p2p0( 1039): P2P_STOP_FIND: returned true
I/io.jxcore.node.ConnectionHelper( 6046): start: OK
I/jxcore-log( 6046): ok 83 Should be able to call startBroadcasting without error
I/jxcore-log( 6046): 
I/jxcore-log( 6046): ok 84 Cannot call startBroadcasting twice
I/jxcore-log( 6046): 
I/io.jxcore.node.ConnectionHelper( 6046): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6046): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6046): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6046): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6046): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6046): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6046): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6046): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6046): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6046): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 6046): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6046): stop: Stopping services
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState clear service
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/WifiNative-p2p0( 1039): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353036373733373937371f36303436222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/WifiNative-p2p0( 1039): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353036373733373937371f36303436222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1039): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6046): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): stop: Stopping P2P device discovery...
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139268 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1039): doBoolean: P2P_STOP_FIND
D/WifiNative-p2p0( 1039): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): setState: NOT_INITIALIZED
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6046): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6046): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6046): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6046): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6046): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 6046): ok 85 Should be able to call stopBroadcasting without error
I/jxcore-log( 6046): 
I/jxcore-log( 6046): # setup
I/jxcore-log( 6046): 
I/jxcore-log( 6046): # ThaliEmitter throws on connection to bad peer
I/jxcore-log( 6046): 
,E/WifiStateMachine( 1039):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-50 f=2412 sc=60 link=72 tx=29.7, 0.0, 0.0  rx=29.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-926174267] gl rssi=-50 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1039):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-50 f=2412 sc=60 link=72 tx=29.7, 0.0, 0.0  rx=29.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-926174264] gl rssi=-50 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,D/WifiNative-wlan0( 1039): doString: [SIGNAL_POLL]
,D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/[SystemUI]TimeTickManager( 1444): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1444): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1444): called onTimeUpdated()
I/[SystemUI]Clock( 1444): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1444): called onTimeUpdated()
,I/[SystemUI]DateView( 1444): called onTimeUpdated()
I/[SystemUI]DateView( 1444): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1444): handleTimeUpdate
,E/WifiStateMachine( 1039):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=19.4, 0.0, 0.0  rx=19.5 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-926171223] gl rssi=-59 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1039):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=19.4, 0.0, 0.0  rx=19.5 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-926171219] gl rssi=-59 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,D/WifiNative-wlan0( 1039): doString: [SIGNAL_POLL]
,I/jxcore-log( 6046): # teardown
I/jxcore-log( 6046): 
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6046): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6046): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6046): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6046): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a3d778d added. We now have 13 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): setDiscoveryMode: WIFI -> BLE_AND_WIFI
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6046): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1455067742918.6046
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6046): bind: Binding a new listener
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6046): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6046): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1455067742918.6046","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6046): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6046): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6046): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6046): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 6046): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6046): start: OK
I/io.jxcore.node.ConnectionHelper( 6046): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1455067742918.6046, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6046): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6046): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6046): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6046): Waiting for incoming connections...
,D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6046): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1455067742918.6046","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6046): start: {"pi":"58:3F:54:73:64:C0","pn":"1455067742918.6046","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6046): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1455067742918.6046","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@e455f930 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@e455f930 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState add service
D/LGWifiP2pService( 1039): add a new client
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435353036373734323931382e36303436222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1039): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435353036373734323931382e36303436222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353036373734323931381f36303436222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
,D/WifiNative-p2p0( 1039): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353036373734323931381f36303436222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): start: Starting P2P device discovery...
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1039): doBoolean: P2P_FIND 120
I/wpa_supplicant( 6239): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1958): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1039): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1039): WifiMonitor:p2p0 cnt=42 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1039): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1039): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1039): P2P_FIND 120: returned true
D/LGWifiP2pService( 1039): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6046): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1455067742918.6046, mode: WIFI
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6046): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6046): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 6046): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1039): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 6239): P2P-FIND-STOPPED 
D/WfdsMonitor( 1958): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1039): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1039): WifiMonitor:p2p0 cnt=43 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1039): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): P2P device discovery stopped successfully
D/LGWifiP2pService( 1039): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): setState: RESTARTING
,D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1039): doBoolean: P2P_STOP_FIND
D/WifiNative-p2p0( 1039): P2P_STOP_FIND: returned true
I/io.jxcore.node.ConnectionHelper( 6046): start: OK
I/jxcore-log( 6046): ok 86 Should be able to call startBroadcasting without error
I/jxcore-log( 6046): 
I/io.jxcore.node.ConnectionHelper( 6046): connect: Trying to connect to peer with ID foobar
W/io.jxcore.node.ConnectionHelper( 6046): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
E/io.jxcore.node.ConnectionHelper( 6046): connect: Invalid Bluetooth address: foobar
I/jxcore-log( 6046): ok 87 Should not connect to a bad peer
I/jxcore-log( 6046): 
I/io.jxcore.node.ConnectionHelper( 6046): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6046): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6046): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6046): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6046): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6046): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6046): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6046): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6046): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6046): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 6046): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6046): stop: Stopping services
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState clear service
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/WifiNative-p2p0( 1039): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353036373734323931381f36303436222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/WifiNative-p2p0( 1039): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353036373734323931381f36303436222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1039): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6046): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): stop: Stopping P2P device discovery...
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139268 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1039): doBoolean: P2P_STOP_FIND
D/WifiNative-p2p0( 1039): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): setState: NOT_INITIALIZED
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6046): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6046): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6046): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6046): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6046): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 6046): ok 88 Should be able to call stopBroadcasting without error
I/jxcore-log( 6046): 
I/jxcore-log( 6046): # setup
I/jxcore-log( 6046): 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): Start timer timeout, starting now...
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): start: Cannot start, because not initialized
,I/jxcore-log( 6046): # ThaliEmitter throws on disconnect to bad peer
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # teardown
I/jxcore-log( 6046): 
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6046): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6046): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6046): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6046): 	Maximum number of connection attempt retries: 0
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Bluetooth MAC address: 58:3F:54:73:64:C0, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1616ff89 added. We now have 14 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): setDiscoveryMode: WIFI -> BLE_AND_WIFI
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6046): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6046): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1455067744209.6046
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6046): bind: Binding a new listener
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6046): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6046): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1455067744209.6046","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6046): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6046): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6046): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6046): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6046): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6046): start: OK
I/io.jxcore.node.ConnectionHelper( 6046): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1455067744209.6046, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6046): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6046): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6046): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6046): Waiting for incoming connections...
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6046): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1455067744209.6046","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6046): start: {"pi":"58:3F:54:73:64:C0","pn":"1455067744209.6046","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6046): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1455067744209.6046","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
,D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@7f68be7a target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@7f68be7a target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState add service
D/LGWifiP2pService( 1039): add a new client
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435353036373734343230392e36303436222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1039): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435353036373734343230392e36303436222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353036373734343230391f36303436222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1039): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353036373734343230391f36303436222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): start: Starting P2P device discovery...
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1039): doBoolean: P2P_FIND 120
I/wpa_supplicant( 6239): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1958): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1039): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1039): WifiMonitor:p2p0 cnt=44 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1039): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1039): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1039): P2P_FIND 120: returned true
D/LGWifiP2pService( 1039): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6046): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): start: OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1455067744209.6046, mode: WIFI
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6046): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6046): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 6046): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1039): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 6239): P2P-FIND-STOPPED 
D/WfdsMonitor( 1958): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1039): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1039): WifiMonitor:p2p0 cnt=45 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1039): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): P2P device discovery stopped successfully
,D/LGWifiP2pService( 1039): InactiveState{ when=-3ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=-3ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): setState: RESTARTING
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1039): doBoolean: P2P_STOP_FIND
D/WifiNative-p2p0( 1039): P2P_STOP_FIND: returned true
I/io.jxcore.node.ConnectionHelper( 6046): start: OK
I/jxcore-log( 6046): ok 89 Should be able to call startBroadcasting without error
I/jxcore-log( 6046): 
D/io.jxcore.node.ConnectionHelper( 6046): disconnectOutgoingConnection: Trying to close connection to peer with ID foobar
E/io.jxcore.node.PeerAndConnectionModel( 6046): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID foobar
D/io.jxcore.node.PeerAndConnectionModel( 6046): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 6046): disconnectOutgoingConnection: Failed to disconnect (peer ID: foobar), either no such connection or failed to close the connection
I/jxcore-log( 6046): ok 90 Disconnect should fail to a non-existant peer 
I/jxcore-log( 6046): 
I/io.jxcore.node.ConnectionHelper( 6046): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6046): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6046): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6046): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6046): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6046): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6046): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6046): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6046): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6046): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 6046): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6046): stop: Stopping services
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=-1ms what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState clear service
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/WifiNative-p2p0( 1039): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1039): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353036373734343230391f36303436222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/WifiNative-p2p0( 1039): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435353036373734343230391f36303436222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1039): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6046): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): stop: Stopping P2P device discovery...
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139268 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1039): doBoolean: P2P_STOP_FIND
D/WifiNative-p2p0( 1039): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): setState: NOT_INITIALIZED
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState clear service request
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6046): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6046): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6046): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6046): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6046): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6046): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 6046): ok 91 Should be able to call stopBroadcasting without error
I/jxcore-log( 6046): 
I/jxcore-log( 6046): # setup
I/jxcore-log( 6046): 
I/jxcore-log( 6046): # #generatePreambleAndBeacons null ECDH for local device
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # teardown
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): ok 92 ecdhForLocalDevice cannot be null
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # setup
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # #generatePreambleAndBeacons expiration out of range lower
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # teardown
I/jxcore-log( 6046): 
,E/WifiStateMachine( 1039):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=9.7, 0.0, 0.0  rx=9.8 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-926168188] gl rssi=-59 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1039):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=9.7, 0.0, 0.0  rx=9.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-926168185] gl rssi=-59 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,D/WifiNative-wlan0( 1039): doString: [SIGNAL_POLL]
,I/jxcore-log( 6046): ok 93 secondsUntilExpiration out of range.
I/jxcore-log( 6046): 
I/jxcore-log( 6046): # setup
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # #generatePreambleAndBeacons expiration out of range upper
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # teardown
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): ok 94 secondsUntilExpiration out of range.
I/jxcore-log( 6046): 
I/jxcore-log( 6046): # setup
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # #generatePreambleAndBeacons empty keys to notify
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # teardown
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): ok 95 should be equal
I/jxcore-log( 6046): 
I/jxcore-log( 6046): # setup
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # #generatePreambleAndBeacons multiple keys to notify
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # teardown
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): ok 96 should be equal
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): ok 97 should be equal
I/jxcore-log( 6046): 
I/jxcore-log( 6046): ok 98 should be equal
I/jxcore-log( 6046): 
I/jxcore-log( 6046): ok 99 should be equal
I/jxcore-log( 6046): 
I/jxcore-log( 6046): # setup
I/jxcore-log( 6046): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): Start timer timeout, starting now...
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): start: Cannot start, because not initialized
,E/WifiStateMachine( 1039):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=17.8, 0.0, 0.0  rx=16.9 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-926165166] gl rssi=-59 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1039):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=17.8, 0.0, 0.0  rx=16.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-926165163] gl rssi=-59 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1039): doString: [SIGNAL_POLL]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): Start timer timeout, starting now...
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6046): start: Cannot start, because not initialized
,I/jxcore-log( 6046): # #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # teardown
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): ok 100 should throw
I/jxcore-log( 6046): 
I/jxcore-log( 6046): # setup
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # #parseBeacons invalid expiration in beaconStreamWithPreAmble
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # teardown
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): ok 101 Preamble expiration must be a 64 bit integer
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # setup
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # #parseBeacons expiration out of range lower
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # teardown
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): ok 102 Expiration out of range
I/jxcore-log( 6046): 
I/jxcore-log( 6046): # setup
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # #parseBeacons no beacons returns null
I/jxcore-log( 6046): 
,E/WifiStateMachine( 1039):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=19.4, 0.0, 0.0  rx=20.4 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-926162137] gl rssi=-59 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine( 1039):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=19.4, 0.0, 0.0  rx=20.4 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-926162136] gl rssi=-59 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1039): doString: [SIGNAL_POLL]
,I/jxcore-log( 6046): # teardown
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): ok 103 should be equal
I/jxcore-log( 6046): 
I/jxcore-log( 6046): # setup
I/jxcore-log( 6046): 
,E/WifiStateMachine( 1039):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=21.7, 0.0, 0.0  rx=23.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-926159125] gl rssi=-59 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1039):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=21.7, 0.0, 0.0  rx=23.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-926159122] gl rssi=-59 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1039): doString: [SIGNAL_POLL]
,I/jxcore-log( 6046): # #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # teardown
I/jxcore-log( 6046): 
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 306623196188; DSPS: 10188188; Offset : -4307878848
,E/WifiStateMachine( 1039):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=12.9, 0.0, 0.0  rx=13.9 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-926156095] gl rssi=-59 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1039):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=12.9, 0.0, 0.0  rx=13.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-926156092] gl rssi=-59 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1039): doString: [SIGNAL_POLL]
,E/WifiStateMachine( 1039):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=10.9, 0.0, 0.0  rx=10.9 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-926153068] gl rssi=-59 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1039):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=10.9, 0.0, 0.0  rx=10.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-926153065] gl rssi=-59 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,D/WifiNative-wlan0( 1039): doString: [SIGNAL_POLL]
,I/jxcore-log( 6046): ok 104 Malformed encrypted beacon key ID
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # setup
I/jxcore-log( 6046): 
I/jxcore-log( 6046): # #parseBeacons addressBookCallback fails decrypt
I/jxcore-log( 6046): 
,E/WifiStateMachine( 1039):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=5.5, 0.0, 0.0  rx=5.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-926150037] gl rssi=-58 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1039):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=5.5, 0.0, 0.0  rx=5.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-926150034] gl rssi=-58 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,D/WifiNative-wlan0( 1039): doString: [SIGNAL_POLL]
,I/jxcore-log( 6046): # teardown
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): ok 105 should be equal
I/jxcore-log( 6046): 
I/jxcore-log( 6046): # setup
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # #parseBeacons addressBookCallback returns no matches
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # teardown
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): ok 106 should be equal
I/jxcore-log( 6046): 
I/jxcore-log( 6046): ok 107 should be equal
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # setup
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # #parseBeacons addressBookCallback returns public key
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # teardown
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): ok 108 should be equal
I/jxcore-log( 6046): 
I/jxcore-log( 6046): ok 109 (unnamed assert)
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # setup
I/jxcore-log( 6046): 
I/jxcore-log( 6046): # #parseBeacons with beacons both for and not for the user
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # teardown
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): ok 110 (unnamed assert)
I/jxcore-log( 6046): 
I/jxcore-log( 6046): # setup
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted
I/jxcore-log( 6046): 
,E/WifiStateMachine( 1039):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=5.7, 0.0, 0.0  rx=6.2 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-926147010] gl rssi=-58 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1039):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=5.7, 0.0, 0.0  rx=6.2 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-926147000] gl rssi=-58 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1039): doString: [SIGNAL_POLL]
I/jxcore-log( 6046): # teardown
I/jxcore-log( 6046): 
,E/WifiStateMachine( 1039):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=15.9, 0.0, 0.0  rx=16.6 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-926143980] gl rssi=-58 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1039):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=15.9, 0.0, 0.0  rx=16.6 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-926143970] gl rssi=-58 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,D/WifiNative-wlan0( 1039): doString: [SIGNAL_POLL]
E/WifiStateMachine( 1039):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=9.9, 0.0, 0.0  rx=11.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-926140950] gl rssi=-58 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1039):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=9.9, 0.0, 0.0  rx=11.3 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-926140937] gl rssi=-58 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiNative-wlan0( 1039): doString: [SIGNAL_POLL]
I/jxcore-log( 6046): ok 111 peer identifier should match
I/jxcore-log( 6046): 
I/jxcore-log( 6046): ok 112 host address should match
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): ok 113 port should match
I/jxcore-log( 6046): 
I/jxcore-log( 6046): ok 114 peer should be available
I/jxcore-log( 6046): 
I/jxcore-log( 6046): ok 115 peer should be unavailable
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # setup
I/jxcore-log( 6046): 
I/jxcore-log( 6046): # #startUpdateAdvertisingAndListening should use different USN after every invocation
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # teardown
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): ok 116 USN should have changed from the first one
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): ok 117 when receiving the second byebye, the first USN should be already set
I/jxcore-log( 6046): 
I/jxcore-log( 6046): # setup
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # messages with invalid location or USN should be ignored
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # teardown
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): WARN thaliWifiInfrastructure Failed to parse a valid port number from location: http://foo.bar:90000
I/jxcore-log( 6046): 
I/jxcore-log( 6046): ok 118 should not have emitted with invalid port
I/jxcore-log( 6046): 
I/jxcore-log( 6046): WARN thaliWifiInfrastructure Received an invalid USN value: 
I/jxcore-log( 6046): 
I/jxcore-log( 6046): ok 119 should not have emitted with invalid USN
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # setup
I/jxcore-log( 6046): 
I/jxcore-log( 6046): # verify that Thali-specific messages are filtered correctly
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # teardown
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): ok 120 irrelevant messages should be ignored
I/jxcore-log( 6046): 
I/jxcore-log( 6046): ok 121 relevant messages should not be ignored
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): ok 122 messages from this device should be ignored
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # setup
I/jxcore-log( 6046): 
I/jxcore-log( 6046): # #startUpdateAdvertisingAndListening should fail invalid router has been passed
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # teardown
I/jxcore-log( 6046): 
,E/jxcore-log( 6046): ERROR thaliWifiInfrastructure Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
E/jxcore-log( 6046): 
I/jxcore-log( 6046): ok 123 specific error should be received
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # setup
I/jxcore-log( 6046): 
I/jxcore-log( 6046): # #startUpdateAdvertisingAndListening should fail if router server starting fails
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # teardown
I/jxcore-log( 6046): 
,E/jxcore-log( 6046): ERROR thaliWifiInfrastructure Router server emitted an error: Error: listen EADDRINUSE
E/jxcore-log( 6046): 
,I/jxcore-log( 6046): ok 124 specific error expected
I/jxcore-log( 6046): 
I/jxcore-log( 6046): # setup
I/jxcore-log( 6046): 
I/jxcore-log( 6046): # #startUpdateAdvertisingAndListening should start hosting given router object
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # teardown
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): ok 125 server should respond with code 200
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # setup
I/jxcore-log( 6046): 
I/jxcore-log( 6046): # #stop can be called multiple times in a row
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # teardown
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): ok 126 should be in stopped state
I/jxcore-log( 6046): 
I/jxcore-log( 6046): ok 127 should still be in stopped state
I/jxcore-log( 6046): 
I/jxcore-log( 6046): # setup
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # #startListeningForAdvertisements can be called multiple times in a row
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # teardown
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): ok 128 should be in listening state
I/jxcore-log( 6046): 
I/jxcore-log( 6046): ok 129 should still be in listening state
I/jxcore-log( 6046): 
I/jxcore-log( 6046): # setup
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # #stopListeningForAdvertisements can be called multiple times in a row
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # teardown
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): ok 130 should not be in listening state
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): ok 131 should still not be in listening state
I/jxcore-log( 6046): 
I/jxcore-log( 6046): # setup
I/jxcore-log( 6046): 
I/jxcore-log( 6046): # #stopAdvertisingAndListening can be called multiple times in a row
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # teardown
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): ok 132 should not be in advertising state
I/jxcore-log( 6046): 
I/jxcore-log( 6046): ok 133 should still not be in advertising state
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # setup
I/jxcore-log( 6046): 
E/WifiStateMachine( 1039):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=5.0, 0.0, 0.0  rx=5.7 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-926137915] gl rssi=-58 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine( 1039):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=5.0, 0.0, 0.0  rx=5.7 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-926137914] gl rssi=-58 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1039): doString: [SIGNAL_POLL]
,I/jxcore-log( 6046): # functions are run from a queue in the right order
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): # teardown
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): ok 134 call order must match
I/jxcore-log( 6046): 
,I/jxcore-log( 6046): Tests Complete
I/jxcore-log( 6046): 
I/jxcore-log( 6046): Total: 0	Passed: 0	Failed: 0
I/jxcore-log( 6046): 
I/jxcore-log( 6046): Toggling radios to false
I/jxcore-log( 6046): 
,I/chromium( 6046): [INFO:CONSOLE(63)] "logCallback ------ Final results ---- ", source: file:///android_asset/www/js/thali_main.js (63)
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@3bcc00c0 mBinding = false
I/chromium( 6046): [INFO:CONSOLE(63)] "logCallback Total: 0, Passed: 0, Failed: 0", source: file:///android_asset/www/js/thali_main.js (63)
,D/LocationManagerService( 1039): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1039): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1039): JNI:system_update. Event-4
D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
D/LGBluetoothServiceAdapter( 6181): [BTUI] Precleanup
D/BluetoothAdapterState( 6181): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 6181): Setting state to 13
I/BluetoothAdapterState( 6181): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterProperties( 6181): onBluetoothDisable()
I/BluetoothAdapterState( 6181): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
D/BluetoothAdapterProperties( 6181): Scan Mode:20
,D/BluetoothAdapterState( 6181): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
V/BluetoothMapMasInstance( 6181): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 6181): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 6181): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
V/BluetoothMapMasInstance( 6181): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
V/BluetoothMapMasInstance( 6181): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
V/BluetoothMapMasInstance( 6181): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 6181): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 6181): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
V/BluetoothPbapService( 6181): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/BtOppRfcommListener( 6181): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothFtpService:RfcommSocketAcceptThread( 6181): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothSapService( 6181): Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
D/btif_config_util( 6181): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
W/bt-l2cap( 6181): L2CAP - L2CA_Deregister() called for PSM: 0x000f
,W/bt-btif ( 6181): bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
W/bt-l2cap( 6181): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 6181): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 6181): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 6181): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 6181): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 6181): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 6181): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 6181): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 6181): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 6181): L2CAP - L2CA_Deregister() called for PSM: 0x0011
W/bt-l2cap( 6181): L2CAP - L2CA_Deregister() called for PSM: 0x0013
E/bt-btif ( 6181): bta_gattc_deregister Deregister Failedm unknown client cif
D/BluetoothManagerService( 1039): Message: 60
D/BluetoothManagerService( 1039): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService( 1039): Bluetooth State Change Intent: 12 -> 13
I/ActivityManager( 1039): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7470 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=6046, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: false pid=6046, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
D/LGBluetoothAPIService( 1958): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,I/[SystemUI]BluetoothHandler( 1444): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,I/BluetoothMapService( 6181): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 6181): STATE_TURNING_OFF
V/BluetoothMapService( 6181): Handler(): got msg=4
D/BluetoothMapService( 6181): MAP Service closeService in
D/BluetoothMapMasInstance( 6181): MAP Service shutdown
D/LGBluetoothMapAdapter( 6181): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 6181): MAP Service closeService out
V/BtOppService( 6181): Receiver DISABLED_ACTION 
I/BtOppRfcommListener( 6181): stopping Accept Thread
V/BtOppRfcommListener( 6181): close mBtServerSocket
I/BtOppRfcommListener( 6181): BluetoothSocket listen thread finished
V/BtOppRfcommListener( 6181): waiting for thread to terminate
V/BtOppRfcommListener( 6181): done waiting for thread to terminate
,D/LocationManagerService( 1039): getAllProviders()=[passive, gps, network]
E/WifiStateMachine( 1039):  ConnectedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1039):  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1039):  ConnectModeState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1039):  DriverStartedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1039):  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1039): WifiStateMachine: Leaving Connected state
E/WifiConfigStore( 1039): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1039): doBoolean: SET_NETWORK 0 bssid any
D/Ulp_jni ( 1039): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1039): JNI:system_update. Event-4
D/WifiNative-wlan0( 1039): SET_NETWORK 0 bssid any: returned true
I/ActivityManager( 1039): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=7499 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/WifiNative-wlan0( 1039): doBoolean: SAVE_CONFIG
I/jxcore-log( 6046): Radios toggled
I/jxcore-log( 6046): 
I/jxcore-log( 6046): ****TEST TOOK:  ms ****
I/jxcore-log( 6046): 
I/jxcore-log( 6046): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6046): 
V/BtOppService( 6181): onDestroy
D/LGBluetoothOppAdapter( 6181): [BTUI] LGBluetoothOppAdapter cleanup
D/WifiNative-wlan0( 1039): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1039): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 6239): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1039): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1039): doBoolean: SET ps 1
D/WifiNative-wlan0( 1039): SET ps 1: returned true
D/CommandListener(  313): Clearing all IP addresses on wlan0
I/jxcore-log( 6046): Toggling radios to false
I/jxcore-log( 6046): 
,D/DhcpStateMachine( 1039): RunningState{ when=-15ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@3bcc00c0 mBinding = false
D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
,V/NativeCrypto( 2123): Read error: ssl=0xaa6f3e00: I/O error during system call, Connection timed out
D/LGBluetoothServiceAdapter( 6181): [BTUI] Precleanup
E/WifiStateMachine( 1039):  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1039): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1039): ignoring duplicate network state non-change
D/ConnectivityService( 1039): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/BluetoothAdapterService( 6181): disable() : BT State is not STATE_ON. Can't disable BT
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
V/NativeCrypto( 2123): SSL shutdown failed: ssl=0xaa6f3e00: I/O error during system call, Broken pipe
D/WifiHS20( 1039): hidePasspointNotification off =false
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20( 1039): hidePasspointNotification off =false
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiScanningService( 1039): SCAN_AVAILABLE : 1
D/RttService( 1039): SCAN_AVAILABLE : 1
D/WifiScanningService( 1039): DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): InactiveState{ when=-10ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=-10ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1039): stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@21d21b58
D/LGWifiP2pService( 1039): P2pDisablingState
D/LGWifiP2pService( 1039): P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): p2p socket connection lost
D/LGWifiP2pService( 1039): P2pDisabledState
V/WfdStateTracker( 1958): handleWifiStateChangedEvent: 0
D/WifiNetworkAgent( 1039): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine( 1039):  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
D/WifiNative-wlan0( 1039): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 6239): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1039): P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService( 1039): EnabledState got{ when=-4ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1039): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1039): doBoolean: SET ps 1
D/WifiNative-wlan0( 1039): SET ps 1: returned true
,D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=6046, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: false pid=6046, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
V/WfdStateTracker( 1958): WfdStateTracker handleDirectStateChangedEvent: 0
D/WfdsService( 1958): WifiP2pState is changed : false
D/WfdsService( 1958): WfdsEnabledState: Receive the WFDS_DISABLE message
D/WfdsService( 1958): Set the WFDS Monitor: false
D/WfdsMonitor( 1958): WFDS Monitor is stopped
D/WfdsService( 1958): STATE : WfdsDisabledState - enter
D/CtrlSupplicant( 1958): Received on exit socket, terminate
E/CtrlSupplicant( 1958): wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
D/WfdsMonitor( 1958): Event [CTRL-EVENT-TERMINATING  - connection closed]
D/WfdsMonitor( 1958): WfdsMonitorThread is received the interrupt - closing
W/WfdsSession:Controller( 1958): DefaultState - msg [9441355] is not handled
D/ConnectivityService( 1039): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): ValidatedState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): Checking http://clients3.google.com/generate_204 on <unknown ssid>
I/StatusBar.NetworkController( 1444): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1444): mWifiConnected = false, mWifiLevel = 0
W/WfdsService( 1958): DefaultState - msg [9445378] is not handled
I/jxcore-log( 6046): Radios toggled
I/jxcore-log( 6046): 
,D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1444): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1444): mWifiConnected = false, mWifiLevel = 0
,D/CommandListener(  313): Clearing all IP addresses on wlan0
D/ConnectivityService( 1039): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1039): disableDataServiceNotify
D/DSQN    ( 1039): stop dsqn bin
D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=0
,D/WifiNative-p2p0( 1039): doBoolean: TERMINATE
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/DSQN    ( 1039): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiHS20( 1039): hidePasspointNotification off =false
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiNative-p2p0( 1039): TERMINATE: returned true
E/WifiStateMachine( 1039): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1039): useWiFiOffloading() : false
E/WifiStateMachine( 1039): CONFIG_LGE_WLAN_PATH : true
I/StatusBar.NetworkController( 1444): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1444): mWifiConnected = false, mWifiLevel = 0
,I/WifiServerServiceExt( 1039): WIFI_STATE_CHANGED_ACTION [0]
D/WifiServerServiceExt( 1039): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1039): setSupplicantStateDISCONNECTED
V/WfdStateTracker( 1958): WfdStateTracker handleDirectStateChangedEvent: 6
D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1039): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1039):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1039):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1039): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat( 1039): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/CSLegacyTypeTracker( 1039): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1039): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1039): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1039): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1039): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
V/NetworkPolicy( 1039): [LG_RESTRICTED] !!!isConnected  type  :1
D/LocSvc_java( 1039): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1039): getAGpsConnectionInfo connType - 4
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): EvaluatingState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/LocSvc_java( 1039): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/LocSvc_java( 1039): ignore wifi update if we are not in OPENING or CLOSING
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1444): CM callback handler got msg 524292
,D/ConnectivityService( 1039): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1039): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1039): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1039): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1039):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1852): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1852):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/NetworkManagementService( 1039): Removing idletimer
W/ResourcesManager( 7499): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7499): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/Settings( 1039): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1039): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
W/ResourcesManager( 7499): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7499): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
V/NetworkPolicy( 1039): [LG_RESTRICTED] !!!isConnected  type  :1
W/ResourcesManager( 7499): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7499): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/LocSvc_java( 1039): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1039): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1039): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1039): ignore wifi update if we are not in OPENING or CLOSING
,D/TelephonyIcons( 1444): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/TelephonyIcons( 1444): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
I/wpa_supplicant( 6239): p2p0: CTRL-EVENT-TERMINATING 
I/wpa_supplicant( 6239): monitor socket send errors count : 1
I/wpa_supplicant( 6239): CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1958-2\x00 that cannot receive messages
D/WifiMonitor( 1039): Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
D/WifiMonitor( 1039): Dropping event because (p2p0) is stopped
D/AndroidRuntime( 7527): 
D/AndroidRuntime( 7527): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/DhcpStateMachine( 1039): StoppedState
D/DhcpStateMachine( 1039): StoppedState{ when=-172ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 1039):  SupplicantStoppingState CMD_ON_QUIT 0 0
E/WifiStateMachine( 1039):  DefaultState CMD_ON_QUIT 0 0
D/AndroidRuntime( 7527): CheckJNI is OFF
W/ContextImpl( 7499): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
V/BluetoothPbapReceiver( 6181): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 6181): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6181): ***********state = 13
V/BluetoothPbapReceiver( 6181): ***********Calling start service!!!! with action = null
,D/BluetoothManagerService( 1039): Message: 20
D/BluetoothManagerService( 1039): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7d068ec:true
V/BluetoothPbapService( 6181): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 6181): state: 13
V/BluetoothPbapService( 6181): Pbap Service closeService in
V/BluetoothPbapService( 6181): successfully stopped pbap service
V/BluetoothPbapService( 6181): Pbap Service closeService out
V/BluetoothPbapService( 6181): Pbap Service onDestroy
V/BluetoothPbapService( 6181): Pbap Service closeService in
V/BluetoothPbapService( 6181): Pbap Service closeService out
D/LGBluetoothPbapAdapter( 6181): [BTUI] cleanup
D/BluetoothManagerService( 1039): Message: 30
,E/ActivityThread( 7470): Failed to find provider info for com.lge.lgaccount.provider
W/LG Account v2.2( 7470): No ProfileInfo entries
I/LG Account v2.2( 7470): isEnabled: false
,I/Feature ( 7470): [Lifetracker]ver: 4.21.112(40211120)
I/Feature ( 7470): [Lifetracker]Country: EU
I/Feature ( 7470): [Lifetracker]Operator: OPEN
I/Feature ( 7470): [Lifetracker]Ranking support: false
I/Feature ( 7470): [Lifetracker]Comfort support: false
I/Feature ( 7470): [Lifetracker]Accessory: true
I/Feature ( 7470): [Lifetracker]Health device: true
I/Feature ( 7470): [Lifetracker]Extra Pedometer: false
I/Feature ( 7470): [Lifetracker]Blood glucose device: false
I/Feature ( 7470): [Lifetracker]Device Number: 3
D/BluetoothManagerService( 1039): Message: 30
I/wpa_supplicant( 6239): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
W/wpa_supplicant( 6239): USIM:  scard_deinit function
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1039): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1039): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/Tethering( 1039): InitialState.processMessage what=4
E/WifiStateMachine( 1039):  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=325614
E/WifiStateMachine( 1039):  DefaultState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=325614
E/WifiStateMachine( 1039):  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=325615  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1039):  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=325615  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
I/ActivityManager( 1039): Killing 6852:com.qualcomm.timeservice/1000 (adj 15): empty #17
D/AndroidRuntime( 7527): Calling main entry com.android.commands.pm.Pm
,W/libprocessgroup( 1039): failed to open /acct/uid_1000/pid_6852/cgroup.procs: No such file or directory
,D/LocalBluetoothProfileManager( 7499): Adding local MAP profile
D/BluetoothMap( 7499): Create BluetoothMap proxy object
I/ActivityManager( 1039): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
I/ActivityManager( 1039): Killing 6046:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
I/wpa_supplicant( 6239): wlan0: CTRL-EVENT-TERMINATING 
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-TERMINATING 
D/WifiMonitor( 1039): Disconnecting from the supplicant, no more events
E/WifiStateMachine( 1039):  SupplicantStoppingState SUP_DISCONNECTION_EVENT 48 0
,W/PackageSettings( 1039): Skipping PackageSetting{112a63ca com.example.hello/10319} due to missing metadata
,I/WindowState( 1039): WIN DEATH: Window{1525a87a u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService( 1039): Client connection lost with reason: 4
,D/InputDispatcher( 1039): Window went away: Window{1525a87a u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/ActivityManager( 1039):   Force finishing activity ActivityRecord{15afe8e6 u0 com.test.thalitest/.MainActivity t4}
,E/GBMv2   (  342): DFP En is all cleared set to be enabled
,D/Tethering( 1039): sendTetherStateChangedBroadcast 0, 0, 0
D/BluetoothManagerService( 1039): Message: 30
,I/ActivityManager( 1039): Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=7556 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,W/ActivityManager( 1039): Spurious death for ProcessRecord{34119f0 6046:com.test.thalitest/u0a311}, curProc for 6046: null
I/[LGHome]EVENT( 2068): [Launcher.java:5338:onStart()]onStart
I/[LGHome]EVENT( 2068): [Launcher.java:903:onResume()]onResume
D/WifiOffDelayIfNotUsed( 1039): stopMonitoring
E/WifiStateMachine( 1039): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1039): useWiFiOffloading() : false
E/WifiStateMachine( 1039): CONFIG_LGE_WLAN_PATH : true
,D/BluetoothManagerService( 1039): Message: 30
D/SplitWindowPolicy( 1958): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1958): topRunningActivity=ActivityInfo{1b51c2e2 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
D/SplitWindowPolicy( 1958): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1958): topRunningActivity=ActivityInfo{27fd0673 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[LGHome]EVENT( 2068): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 2068): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
,D/ActionManagerService( 1910): notifyUserLog: 1000003
D/LIA_Informant_ActionManagerMessageHandler( 3589): handleMessage: what(1000) actionID(0x1000003)
I/[LGHome]GBoardWebView( 2068): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
I/[LGHome]LGActivityUtil( 2068): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 2068): [Launcher.java:1056:onResume()]onResume end
,I/[LGHome]EVENT( 2068): [Launcher.java:1114:onPause()]onPause
D/WfdsService( 1958): Supplicant Connection state is changed : false
D/WfdsService( 1958): DefaultState - WIFI_SUPPLICANT_DISCONNECTED
D/WfdsService( 1958): Set the WFDS Monitor: false
D/WfdsMonitor( 1958): WFDS Monitor is stopped
D/StatusBar.NetworkController( 1444): refreshViews: Data not connected!! Set no data type icon / Roaming
,V/WfdStateTracker( 1958): WfdStateTracker handleDirectStateChangedEvent: 0
,W/Settings( 1817): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/WifiServerServiceExt( 1039): WIFI_STATE_CHANGED_ACTION [1]
I/WifiServerServiceExt( 1039): batteryPsActivateMsgHandler : state:0 event:1
I/WifiServerServiceExt( 1039): batteryPsActivateMsgHandler : this is not treated
D/ActionManagerService( 1910): notifyUserLog: 1000004
D/LIA_Informant_ActionManagerMessageHandler( 3589): handleMessage: what(1000) actionID(0x1000004)
D/LocalBluetoothProfileManager( 7499): LocalBluetoothProfileManager construction complete
D/LGBluetoothFeatureConfig( 7499):  get() - isFeatureLoaded : false
,I/[LGHome]GBoardWebView( 2068): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
V/BoardContentProvider( 3589): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
I/GBoardWebViewUtils( 2068): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2068): , create_time: 1430558575574
I/GBoardWebViewUtils( 2068): , expire_time: 0
I/GBoardWebViewUtils( 2068): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2068): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2068): , display: false
I/GBoardWebViewUtils( 2068): , animation: false }
I/GBoardWebViewUtils( 2068): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2068): , create_time: 1430558575600
I/GBoardWebViewUtils( 2068): , expire_time: 0
I/GBoardWebViewUtils( 2068): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2068): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2068): , display: false
I/GBoardWebViewUtils( 2068): , animation: false }
I/GBoardWebViewUtils( 2068): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1454599632914
I/GBoardWebViewUtils( 2068): , create_time: 1454599633839
I/GBoardWebViewUtils( 2068): , expire_time: 0
I/GBoardWebViewUtils( 2068): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide.html?id=guide_1111111111116_1454599632914&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2068): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2068): , display: false
I/GBoardWebViewUtils( 2068): , animation: false }
W/Settings( 6901): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WallpaperManager( 2068): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
I/ActivityManager( 1039): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
,D/bt_hci_bdroid( 6181): cleanup
I/bt_lpm  ( 6181): LPM is already off!!!
W/bt-btif ( 6181): ag scb idx 1 not allocated
E/bt-btif ( 6181): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 6181): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 6181): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 6181): L2CAP - L2CA_Deregister() called for PSM: 0x0017
I/SystemUI[Framework]( 1039): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
W/bt-l2cap( 6181): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 6181): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 6181): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 6181): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 6181): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 6181): L2CAP - L2CA_Deregister() called for PSM: 0x0017
I/bt_userial_mct( 6181): exiting userial_read_thread
D/bt_userial_mct( 6181): Leaving userial_evt_read_thread()
W/bt-l2cap( 6181): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 6181): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 6181): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 6181): L2CAP - L2CA_Deregister() called for PSM: 0x0019
D/bt_userial_mct( 6181): userial_close_reader Joined userial reader thread: 0
W/bt-l2cap( 6181): L2CAP - PSM: 0x0019 not found for deregistration
I/bt_vendor( 6181): hw_epilog_process
W/bt-l2cap( 6181): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 6181): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 6181): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 6181): L2CAP - PSM: 0x001b not found for deregistration
E/bt-btif ( 6181): bta_gattc_deregister Deregister Failedm unknown client cif
D/bt_hci_bdroid( 6181): cleanup Finalizing cleanup
D/bt_userial_mct( 6181): userial_close
E/bt_userial_mct( 6181): pthread_join() FAILED result:3
I/bt_vendor( 6181): bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
D/PhoneStatusBar( 1444): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
W/PhoneWindowManagerEx( 1039): Call!!!getLGSystemUiVisibility. =0x0
,D/StatusBarManagerServiceEx( 1039): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1039): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1039): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@168b094a,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1039): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1444): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1444):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1444): , Keyguard show=false, IME shown=false, Panel expanded=false
,I/[LGHome]GBoardWebView( 2068): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
,D/LGBluetoothUserBindClient( 7499): [BTUI] initUserBindClient
W/ContextImpl( 7499): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
D/KeyguardModel( 1444): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
D/LIA_MrGDBLogger_PackageInfoDetector( 3589): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
E/LGBluetoothAvrcpQcomAdapter( 6181): [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
D/LGBluetoothAvrcpQcomAdapter( 6181): [BTUI] [+] updateMediaPlayerInfo
D/LIA_Service_RemotePackageHandler( 2032): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
I/InputReader( 1039): Reconfiguring input devices.  changes=0x00000010
I/art     ( 4183): Explicit concurrent mark sweep GC freed 22050(1275KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 29MB/45MB, paused 2.453ms total 56.988ms
,E/WifiStateMachine( 1039):  InitialState CMD_TETHER_STATE_CHANGE 0 0
,E/WifiStateMachine( 1039):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,D/DockEventReceiver( 7499): finishStartingService: stopping service
,D/BluetoothInputDevice( 7499): Proxy object connected
D/HidProfile( 7499): Bluetooth service connected
W/GeofencerStateMachine( 1817): Ignoring removeGeofence because network location is disabled.
W/System.err( 4140): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 4140): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4140): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4140): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4140): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4140): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4140): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4140): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4140): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4140): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4140): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4140): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
V/SIM_STK ( 1039): Menu title from STK is T-Mobile
D/KeyguardModel( 1444): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1444): createShortcutInfo...
D/KeyguardModel( 1444): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1444): createShortcutInfo...
,W/ResourcesManager( 1444): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1444): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1444): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1444): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1444): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1444): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/BluetoothPan( 7499): BluetoothPAN Proxy object connected
D/PanProfile( 7499): Bluetooth service connected
D/BluetoothMap( 7499): Proxy object connected
D/MapProfile( 7499): Bluetooth service connected
D/BluetoothMap( 7499): getConnectedDevices()
D/BluetoothMap( 7499): Bluetooth is Not enabled
D/LGBluetoothUserBindClient( 7499): [BTUI] onServiceConnected
I/[SystemUI]QSlideListController( 1444): onReceive = android.intent.action.PACKAGE_REMOVED
,D/LGBluetoothAuthorization( 7499): [BTUI] cancel All Notification
I/art     ( 2068): Background partial concurrent mark sweep GC freed 6684(303KB) AllocSpace objects, 7(19MB) LOS objects, 34% free, 59MB/91MB, paused 19.268ms total 61.865ms
D/KeyguardModel( 1444): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1444): createShortcutInfo...
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1444): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1444): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,W/ResourcesManager( 1444): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1444): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1444): No package identifier when getting value for resource number 0x00000000
,W/PackageManager( 1444): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1444): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1444): createShortcutInfo...
D/BluetoothPermissionRequest( 7499): onReceive
W/ResourcesManager( 1444): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1444): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1444): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1444): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
D/bt_hci_bdroid( 6181): set_power 0
I/bt_vendor( 6181): bt-vendor : BT_VND_OP_POWER_CTRL: Off
I/bt_vendor( 6181): bluetooth satus is on
I/bt_vendor( 6181): bt-vendor : resetting BT status
I/bt_vendor( 6181): Starting hciattach daemon
I/bt_vendor( 6181): try to set false
,I/bt_vendor( 6181): Starting hciattach daemon
I/bt_vendor( 6181): try to set false
I/bt_vendor( 6181): cleanup
I/GKI_LINUX( 6181): gki_task task_id=0 [BTU] terminating
W/ResourcesManager( 7556): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/GKI_LINUX( 6181): GKI_exit_task 0 done
I/GKI_LINUX( 6181): GKI_shutdown(): task [BTU] terminated
D/BluetoothAdapterState( 6181): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
W/ResourceType( 1444): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1444): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1444): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1444): createShortcutInfo...
D/SplitUIManager( 1869): split_name #11 / not available #0
D/SplitUIService( 1869): removed split : 
D/LGBluetoothAuthorization( 7499): [BTUI] cancel All Notification
I/art     ( 1039): Explicit concurrent mark sweep GC freed 76566(4MB) AllocSpace objects, 6(480KB) LOS objects, 33% free, 44MB/66MB, paused 2.221ms total 170.574ms
D/BluetoothAdapterState( 6181): Stopping profile services that were post enabled
,I/art     ( 1039): WaitForGcToComplete blocked for 167.753ms for cause Explicit
D/KeyguardModel( 1444): handleShortcutListChanged...
D/LGBluetoothResetSettingReceiver( 7499): return without doing reset settings.
,V/SIM_STK ( 1039): Menu title from STK is T-Mobile
V/SIM_STK ( 1039): Menu title from STK is T-Mobile
D/PluginManager( 7556): init()
D/KeyguardModel( 1444): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1444): createShortcutInfo...
,I/[LGHome]EVENT( 2068): [Launcher.java:5349:onStop()]onStop
I/[LGHome]Launcher.Model( 2068): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
D/KeyguardModel( 1444): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1444): createShortcutInfo...
I/[LGHome]Launcher( 2068): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2068): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2068): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2068): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2068): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
W/ResourceType( 1444): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1444): Failure retrieving resources for com.android.mms: Resource ID #0x0
,D/SplitUIManager( 1869): split_name #11 / not available #0
I/SplitUIService( 1869): split app #11
W/ActivityManager( 1039): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
D/KeyguardModel( 1444): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1444): createShortcutInfo...
D/LGBluetoothAvrcpQcomAdapter( 6181): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 6181): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6181): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 6181): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 6181): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 6181): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6181): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 6181): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 6181): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 6181): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 6181): [BTUI] [-] updateMediaPlayerInfo
D/HeadsetService( 6181): Received stop request...Stopping profile...
I/LGBluetoothHfpAdapter( 6181): [BTUI] LGBluetoothHfpAdapter cleanup
W/LGBluetoothHeadsetServiceJni( 6181): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 6181): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1127cb12
W/ResourceType( 1444): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1444): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/HeadsetStateMachine( 6181): Exit Disconnected: -1
D/A2dpService( 6181): Received stop request...Stopping profile...
D/A2dpStateMachine( 6181): Exit Disconnected: -1
D/BluetoothHeadset( 1852): Proxy object disconnected
D/BluetoothHeadset( 1852): Proxy object disconnected
D/BluetoothHeadset( 1852): Proxy object disconnected
D/LGBluetoothAvrcpQcomAdapter( 6181): [BTUI] cleanup
I/[LGHome]EVENT( 2068): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/KeyguardModel( 1444): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1444): createShortcutInfo...
W/ResourceType( 1444): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1444): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1444): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1444): createShortcutInfo...
,I/[LGHome]Launcher.Model( 2068): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/Timeline( 1039): Timeline: Activity_windows_visible id: ActivityRecord{3a7f4671 u0 com.lge.launcher2/.Launcher t3} time:326534
I/[LGHome]Launcher( 2068): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
D/LGBluetoothA2dpAdapter( 6181): [BTUI] LGBluetoothA2dpAdapter cleanup
W/LGBluetoothA2dpServiceJni( 6181): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 6181): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1127cb12
D/HidService( 6181): Received stop request...Stopping profile...
D/BluetoothAdapterService( 6181): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1127cb12
D/HealthService( 6181): Received stop request...Stopping profile...
D/BluetoothAdapterService( 6181): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1127cb12
D/PanService( 6181): Received stop request...Stopping profile...
D/BluetoothAdapterService( 6181): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1127cb12
D/BluetoothInputDevice( 7499): Proxy object disconnected
D/HidProfile( 7499): Bluetooth service disconnected
D/BtGatt.DebugUtils( 6181): handleDebugAction() action=null
D/BtGatt.GattService( 6181): Received stop request...Stopping profile...
D/BtGatt.GattService( 6181): stop()
D/BtGatt.AdvertiseManager( 6181): advertise clients cleared
I/ActivityManager( 1039): Killing 6870:com.android.calendar/u0a13 (adj 15): empty #17
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2068): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2068): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
D/administrator( 1039): Handling package changes for user 0
I/ThermalEngine(  335): Thermal-Server: Thermal received msg from  override
I/Thermal-Lib( 2932): Thermal-Lib-Client: Client request sent
D/BluetoothPan( 7499): BluetoothPAN Proxy object disconnected
D/PanProfile( 7499): Bluetooth service disconnected
I/[LGHome]EVENT( 2068): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 2068): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2068): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,V/SIM_STK ( 1039): Menu title from STK is T-Mobile
I/[Concierge]WidgetView( 2068): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 326624369879; DSPS: 10843587; Offset : -4307894066
,I/NotificationService( 1039): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1039): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1039): Receieved: android.intent.action.PACKAGE_REMOVED
D/KeyguardModel( 1444): handleShortcutListChanged...
D/BluetoothAdapterService( 6181): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1127cb12
,W/libprocessgroup( 1039): failed to open /acct/uid_10013/pid_6870/cgroup.procs: No such file or directory
,D/[Concierge]Service( 2616): onStartCommand(). Type : 8
D/[Concierge]Service( 2616): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/[Concierge]WidgetView( 2068): change position of spinner
D/[Concierge]Service( 2616): Update widget ID : 11
D/BluetoothMapService( 6181): Received stop request...Stopping profile...
D/BluetoothMapService( 6181): stop()
D/BluetoothHeadset( 1039): Proxy object disconnected
D/AudioService( 1039): onServiceDisconnected: Bluetooth profile: 1
D/BluetoothA2dp( 1039): Proxy object disconnected
D/AudioService( 1039): onServiceDisconnected: Bluetooth profile: 2
D/BluetoothMapEmailAppObserver( 6181): deinitObservers()
D/BluetoothMapEmailAppObserver( 6181): removeReceiver()
D/BluetoothAdapterService( 6181): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1127cb12
D/BluetoothMap( 7499): Proxy object disconnected
D/MapProfile( 7499): Bluetooth service disconnected
V/BluetoothOppReceiver( 6181): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
D/BluetoothOppNotification( 6181): [BTUI] cancel opp incoming file confirm notification
D/BluetoothOppNotification( 6181): [BTUI] cancel opp active transfer file notification
D/HeadsetStateMachine( 6181): Unbinding service...
D/HeadsetPhoneState( 6181): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 6181): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetPhoneState( 6181): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 6181): [BTUI] listenForMultiSimPhoneState : start = false
W/BluetoothHeadsetServiceJni( 6181): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 6181): Cleaning up Bluetooth Handsfree callback object
I/LGBluetoothHfpAdapter( 6181): [BTUI] LGBluetoothHfpAdapter cleanup
I/BluetoothA2dpServiceJni( 6181): cleanupNative
I/GKI_LINUX( 6181): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 6181): GKI_exit_task 2 done
I/GKI_LINUX( 6181): GKI_shutdown(): task [A2DP-MEDIA] terminated
W/BluetoothHidServiceJni( 6181): Cleaning up Bluetooth HID Interface...
W/BluetoothHidServiceJni( 6181): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 6181): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 6181): Cleaning up Bluetooth Health object
W/LGBluetoothHealthServiceJni( 6181): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 6181): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 6181): Cleaning up Bluetooth PAN callback object
V/BluetoothMapService( 6181): Handler(): got msg=4
D/BluetoothMapService( 6181): MAP Service closeService in
D/LGBluetoothMapAdapter( 6181): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 6181): MAP Service closeService out
D/BluetoothMapService( 6181): cleanup()
D/BluetoothMapService( 6181): MAP Service closeService in
D/LGBluetoothMapAdapter( 6181): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 6181): MAP Service closeService out
D/BluetoothAdapterState( 6181): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 6181): Setting state to 10
I/BluetoothAdapterState( 6181): Bluetooth adapter state changed: 13-> 10
D/BluetoothManagerService( 1039): Message: 60
D/BluetoothManagerService( 1039): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService( 1039): Broadcasting onBluetoothStateChange(false) to 9 receivers.
I/BluetoothAdapterState( 6181): Entering OffState
D/BluetoothPan( 7499): onBluetoothStateChange on: false
I/[Concierge]WidgetView( 2068): initWebView(). Time : 1455067777248
D/[Concierge]Service( 2616): onStartCommand(). Type : 0
,D/TaskPersister( 1039): removeObsoleteFile: deleting file=4_task.xml
V/BluetoothFtpReceiver( 6181): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpReceiver( 6181): BluetoothFtpReceiver Start Service
V/BluetoothFtpService( 6181): Ftp Service onStartCommand
V/BluetoothFtpService( 6181): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpService( 6181): Ftp Service closeService
E/BluetoothFtpService:RfcommSocketAcceptThread( 6181): Shutdown
D/BluetoothHeadset( 1852): onBluetoothStateChange: up=false
V/BluetoothFtpService( 6181): successfully stopped ftp service
D/BluetoothA2dp( 1039): onBluetoothStateChange: up=false
V/BluetoothSapReceiver( 6181): [BTUI] checkServiceStart
D/BluetoothHeadset( 1852): onBluetoothStateChange: up=false
V/BluetoothSapReceiver( 6181): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 6181): SapReceiver onReceive 
V/BluetoothSapReceiver( 6181): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6181):  Bluetooth Adapter state = 13
V/BluetoothSapReceiver( 6181): Calling SAP service start service with action = null
V/BluetoothFtpService( 6181): Ftp Service onDestroy
V/BluetoothFtpService( 6181): Ftp Service closeService
D/BluetoothHeadset( 1852): onBluetoothStateChange: up=false
I/art     ( 1039): Explicit concurrent mark sweep GC freed 10404(595KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 2.218ms total 208.279ms
I/ActivityManager( 1039): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7606 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,V/BluetoothSapService( 6181): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 6181): state: 13
V/BluetoothSapService( 6181): Stopping SAP server process
V/BluetoothSapService( 6181): Sap Service closeSapService in
V/BluetoothSapService( 6181): Close listen Socket : 
V/BluetoothSapService( 6181): Close rfcomm Socket : 
V/BluetoothSapService( 6181): Close sapd  Socket : 
D/BluetoothInputDevice( 7499): onBluetoothStateChange: up=false
V/BluetoothSapService( 6181): Sap Service closeSapService out
V/BluetoothSapService( 6181): Sap Service onDestroy
V/BluetoothSapService( 6181): Sap Service closeSapService in
V/BluetoothSapService( 6181): Close listen Socket : 
V/BluetoothSapService( 6181): Close rfcomm Socket : 
D/BluetoothMap( 7499): onBluetoothStateChange: up=false
V/BluetoothSapService( 6181): Close sapd  Socket : 
V/BluetoothSapService( 6181): Sap Service closeSapService out
D/BluetoothPbap( 7499): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1039): onBluetoothStateChange: up=false
D/BluetoothManagerService( 1039): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService( 1039): Broadcasting onBluetoothServiceDown() to 7 receivers.
D/BluetoothManagerService( 1039): Calling onQBluetoothServiceDown callbacks
D/BluetoothManagerService( 1039): Broadcasting onQBluetoothServiceDown() to 0 receivers.
D/BluetoothManagerService( 1039): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@3bcc00c0 mBinding = false
D/BluetoothManagerService( 1039): Sending unbind request.
D/BluetoothManagerService( 1039): Bluetooth State Change Intent: 13 -> 10
D/LGBluetoothFeatureConfig( 7499): isPrivacyLogsEnabled : true
D/LGBluetoothAPIService( 1958): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/LGBluetoothAPIService( 1958): Message: 2
E/LGBluetoothEventManager( 7499): [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
D/LGBluetoothEventManager( 7499): [BTUI] clear device connection state
D/LGBluetoothAPIService( 1958): unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@ea4f930 mBinding = false
D/LGBluetoothAPIService( 1958): Sending unbind request.
I/[SystemUI]BluetoothHandler( 1444): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
D/BluetoothAdapter( 1444): 75338636: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1444): 75338636: getState() :  mService = null. Returning STATE_OFF
I/[Concierge]WebView( 2068): Return exist ConciergeWebView. Reuse : 413543065
D/[Concierge]WidgetView( 2068): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2068): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
I/[LgeWidgetLib]ExtViewHost( 2068): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@b17eefc
I/[LGHome]EVENT( 2068): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2068): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2068): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/[LGHome]EVENT( 2068): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
,D/[Concierge]WidgetView( 2068): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2068): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
W/ResourcesManager( 7606): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/[Concierge]WidgetView( 2068): Widget kill message received. Destory myself. My : 1455067478489, New one : 1455067777248
D/[Concierge]WidgetView( 2068): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2068): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,I/[LGHome]Launcher( 2068): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2068): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2068): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2068): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2068): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/ActivityManager( 1039): Killing 6828:com.lge.clock/u0a10 (adj 15): empty #17
I/[LGHome]EVENT( 2068): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/GKI_LINUX( 6181): gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 6181): GKI_exit_task 1 done
I/GKI_LINUX( 6181): GKI_shutdown(): task [BTIF] terminated
,I/BluetoothServiceJni( 6181): cleanupNative: return from cleanup
I/art     ( 6181): --- WEIRD: removing null entry 246
W/art     ( 6181): JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
I/[LGHome]Launcher( 2068): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
W/LGBluetoothServiceJni( 6181): Cleaning up Bluetooth Service callback object
I/[LGHome]Launcher( 2068): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
D/AndroidRuntime( 7527): Shutting down VM
I/[LgeWidgetLib]LgeAppWidgetHostView( 2068): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,W/ResourcesManager( 1039): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourceType( 1039): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
E/[LgeWidgetLib]LgeAppWidgetHostView( 2068): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2068): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 2068): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/Timeline( 2068): Timeline: Activity_idle id: android.os.BinderProxy@3f7ad5f6 time:326835
,D/AuthorizationBluetoothService( 2123): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/LGBluetoothSettingsDBObserver( 6181): [BTUI] unregister observer for LG device name DB
W/ExternalStrings( 7556): load override strings
W/ExternalStrings( 7556): java.lang.RuntimeException: Unexpected tag, got eat-comment
W/ExternalStrings( 7556): 	at com.mcafee.plugin.af.a(Unknown Source)
W/ExternalStrings( 7556): 	at com.mcafee.plugin.ac.b(Unknown Source)
W/ExternalStrings( 7556): 	at com.mcafee.plugin.ak.d(Unknown Source)
W/ExternalStrings( 7556): 	at com.mcafee.plugin.ak.a(Unknown Source)
W/ExternalStrings( 7556): 	at com.mcafee.app.s.getClassLoader(Unknown Source)
W/ExternalStrings( 7556): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
W/ExternalStrings( 7556): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
W/ExternalStrings( 7556): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
W/ExternalStrings( 7556): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
W/ExternalStrings( 7556): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
W/ExternalStrings( 7556): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ExternalStrings( 7556): 	at android.os.Looper.loop(Looper.java:135)
W/ExternalStrings( 7556): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/ExternalStrings( 7556): 	at java.lang.reflect.Method.invoke(Native Method)
W/ExternalStrings( 7556): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/ExternalStrings( 7556): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/ExternalStrings( 7556): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,I/art     ( 6181): System.exit called, status: 0
I/AndroidRuntime( 6181): VM exiting with result code 0, cleanup skipped.
D/StatusProvider( 7556): onCreate
W/ContextImpl( 7499): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
W/libprocessgroup( 1039): failed to open /acct/uid_10010/pid_6828/cgroup.procs: No such file or directory
I/[LGHome]EVENT( 2068): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
D/DockEventReceiver( 7499): finishStartingService: stopping service
V/AudioFlinger(  318): 6181 died, releasing its sessions
V/AudioFlinger(  318):  pid 1852 @ 0
V/AudioFlinger(  318):  pid 3300 @ 1
V/AudioFlinger(  318):  pid 3300 @ 2
,D/LGBluetoothUserBindClient( 7499): [BTUI] onServiceDisconnected
,V/Signer  ( 7556): override build config not found
D/Signer  ( 7556): value of property debug is false
,D/LGMDMWrapper( 7556): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
D/LGMDMWrapper( 7556): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
D/LGMDMWrapper( 7556): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
D/LGMDMWrapper( 7556): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
,D/LGMDMWrapper( 7556): Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
D/LGMDMWrapper( 7556): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
D/LGMDMWrapper( 7556): Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
D/LGMDMWrapper( 7556): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
D/LGMDMWrapper( 7556): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
D/LGMDMWrapper( 7556): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
D/LGMDMWrapper( 7556): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
D/LGMDMWrapper( 7556): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
D/LGMDMWrapper( 7556): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
V/LGMDMManager( 7556): Create singleton instance
I/chromium( 2068): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,D/LGMDMWrapper( 7556): LG MDM library v4.0.0 is available on this device.
I/ActivityManager( 1039): Process com.android.bluetooth (pid 6181) has died
W/ActivityManager( 1039): Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,D/BluetoothPermissionRequest( 7499): onReceive
D/LGBluetoothUtils( 7499): [BTUI] FileNotFound: readProperty
D/BluetoothDiscoverableTimeoutReceiver( 7499): cancelDiscoverableAlarm(): Enter
D/LGBluetoothResetSettingReceiver( 7499): return without doing reset settings.
I/GBoardtInterface( 2068): onReloaded()
I/GBoardWebViewClient( 2068): onPageFinished url:file:///android_asset/www/main.html
,I/ActivityManager( 1039): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7628 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
V/BoardContentProvider( 3589): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/PostponalbeReceiver( 7556): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/ContextImpl( 7556): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
V/BoardContentProvider( 3589): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,I/ActivityManager( 1039): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7648 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1039): Killing 6693:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
W/ActivityThread( 7556): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/libprocessgroup( 1039): failed to open /acct/uid_10085/pid_6693/cgroup.procs: No such file or directory
,W/ResourcesManager( 7628): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager( 7628): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7628): Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
,W/ResourcesManager( 7628): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
E/SQLiteDatabase( 7556): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 7556): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7556): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7556): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7556): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.mcafee.wsstorage.ConfigManager.c(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.mcafee.wsstorage.ConfigManager.ab(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.mcafee.fw.ws.WSLicenseService.a(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.mcafee.g.b.a(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.mcafee.applock.AppLockComponent.a_(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.mcafee.applock.AppLockComponent.a(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7556): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7556): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7556): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7556): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7556): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7556): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7556): 	at com.mcafee.d.c.run(Unknown Source)
D/ActionManagerService( 1910): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 3589): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3589): onEvent() : ACTION_BOARD_ENABLED
D/ActionManagerService( 1910): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 3589): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3589): onEvent() : ACTION_BOARD_ENABLED
D/LIA_Informant_Tips_FormEventRepository( 3589): getSize() : size - 0
D/LIA_Informant_Tips_SmartTipsActionManager( 3589): onSettingEvent() : GBoard On - add scheduler - 0
V/BoardContentProvider( 3589): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/GBoardUriUtils( 2068): fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
D/GBoardWebViewUtils( 2068): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
,D/GBoardUriUtils( 2068): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
D/GBoardWebViewUtils( 2068): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
D/BluetoothAdapterApp( 7628): Loading JNI Library
D/GBoardUriUtils( 2068): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide2.html?id=guide_1111111111116_1454599632914&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
D/GBoardWebViewUtils( 2068): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide2.html?id=guide_1111111111116_1454599632914&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/PCSuite ( 7648): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 7648): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7648): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/BluetoothAdapterApp( 7628): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@1035f16b Instance Count = 1
E/SQLiteDatabase( 7648): Failed to open database '/data/data/com.lge.sync/databases/lgds.db'.
E/SQLiteDatabase( 7648): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7648): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7648): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7648): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7648): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7648): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7648): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7648): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7648): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7648): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7648): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7648): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7648): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7648): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7648): 	at com.lge.ds.agent.db.providers.DatabaseAdapter.open(DatabaseAdapter.java:104)
E/SQLiteDatabase( 7648): 	at com.lge.ds.agent.db.providers.ProfileInterface.getTotalCount(ProfileInterface.java:716)
E/SQLiteDatabase( 7648): 	at com.lge.ds.ServersInfo$InsertProfiles.run(ServersInfo.java:208)
E/SQLiteDatabase( 7556): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/lockedapplications'.
E/SQLiteDatabase( 7556): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7556): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7556): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 7556): 	at com.mcafee.applock.a.a(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.mcafee.applock.d.d(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.mcafee.appl,ock.d.<init>(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.mcafee.applock.d.a(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.mcafee.modes.adapt.a.<init>(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.mcafee.modes.adapt.a.a(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.mcafee.modes.adapt.ModesLockHelper.a(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.mcafee.applock.h.<init>(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.mcafee.applock.f.<init>(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.mcafee.applock.f.a(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.mcafee.applock.AppLockComponent.d(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.mcafee.applock.AppLockComponent.a_(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.mcafee.applock.AppLockComponent.a(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7556): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7556): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7556): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7556): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7556): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7556): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7556): 	at com.mcafee.d.c.run(Unknown Source)
E/SQLiteOpenHelper( 7556): Couldn't open lockedapplications for writing (will try read-only):
E/SQLiteOpenHelper( 7556): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7556): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7556): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 7556): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 7556): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 7556): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 7556): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 7556): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteOpenHelper( 7556): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteOpenHelper( 7556): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteOpenHelper( 7556): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteOpenHelper( 7556): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 7556): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 7556): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 7556): 	at com.mcafee.applock.a.a(Unknown Source)
E/SQLiteOpenHelper( 7556): 	at com.mcafee.applock.d.d(Unknown Source)
E/SQLiteOpenHelper( 7556): 	at com.mcafee.applock.d.<init>(Unknown Source)
E/SQLiteOpenHelper( 7556): 	at com.mcafee.applock.d.a(Unknown Source)
E/SQLiteOpenHelper( 7556): 	at com.mcafee.modes.adapt.a.<init>(Unknown Source)
E/SQLiteOpenHelper( 7556): 	at com.mcafee.modes.adapt.a.a(Unknown Source)
E/SQLiteOpenHelper( 7556): 	at com.mcafee.modes.adapt.ModesLockHelper.a(Unknown Source)
E/SQLiteOpenHelper( 7556): 	at com.mcafee.applock.h.<init>(Unknown Source)
E/SQLiteOpenHelper( 7556): 	at com.mcafee.applock.f.<init>(Unknown Source)
E/SQLiteOpenHelper( 7556): 	at com.mcafee.applock.f.a(Unknown Source)
E/SQLiteOpenHelper( 7556): 	at com.mcafee.applock.AppLockCompon,ent.d(Unknown Source)
E/SQLiteOpenHelper( 7556): 	at com.mcafee.applock.AppLockComponent.a_(Unknown Source)
E/SQLiteOpenHelper( 7556): 	at com.mcafee.applock.AppLockComponent.a(Unknown Source)
E/SQLiteOpenHelper( 7556): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteOpenHelper( 7556): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteOpenHelper( 7556): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteOpenHelper( 7556): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteOpenHelper( 7556): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteOpenHelper( 7556): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteOpenHelper( 7556): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 7556): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 7556): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteOpenHelper( 7556): 	at com.mcafee.d.c.run(Unknown Source)
D/BluetoothAdapterApp( 7628): onCreate
W/SQLiteOpenHelper( 7556): Opened lockedapplications in read-only mode
V/WiFiOffLoadBroadcast( 7499): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
E/LGSync  ( 7648): [DatabaseAdapter] com.lge.ds.agent.db.providers.DatabaseAdapter.open(): 108: Exception:
E/LGSync  ( 7648): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/LGSync  ( 7648): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/LGSync  ( 7648): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/LGSync  ( 7648): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/LGSync  ( 7648): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/LGSync  ( 7648): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/LGSync  ( 7648): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/LGSync  ( 7648): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/LGSync  ( 7648): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/LGSync  ( 7648): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/LGSync  ( 7648): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/LGSync  ( 7648): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/LGSync  ( 7648): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/LGSync  ( 7648): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/LGSync  ( 7648): 	at com.lge.ds.agent.db.providers.DatabaseAdapter.open(DatabaseAdapter.java:104)
E/LGSync  ( 7648): 	at com.lge.ds.agent.db.providers.ProfileInterface.getTotalCount(ProfileInterface.java:716)
E/LGSync  ( 7648): 	at com.lge.ds.ServersInfo$InsertProfiles.run(ServersInfo.java:208)
E/LGSync  ( 7648): [DatabaseAdapter] com.lge.ds.agent.db.providers.DatabaseAdapter.query(): 238: Pre-condition is failed!
E/LGSync  ( 7648): [ProfileInterface] com.lge.ds.agent.db.providers.ProfileInterface.getTotalCount(): 727: crCountProfile is null
D/ProfileConfigQcom( 7628): [BTUI] HeadsetService is supported
D/ProfileConfigQcom( 7628): Adding HeadsetService
D/ProfileConfigQcom( 7628): [BTUI] A2dpService is supported
D/ProfileConfigQcom( 7628): Adding A2dpService
D/ProfileConfigQcom( 7628): [BTUI] HidService is supported
D/ProfileConfigQcom( 7628): Adding HidService
D/ProfileConfigQcom( 7628): [BTUI] HealthService is supported
D/ProfileConfigQcom( 7628): Adding HealthService
D/LGBluetoothFeatureConfig( 7628): isSupportPan() :  mTargetOp=OPEN
E/SQLiteDatabase( 7648): Failed to open database '/data/data/com.lge.sync/databases/lgds.db'.
E/SQLiteDatabase( 7648): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7648): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7648): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7648): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7648): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7648): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7648): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7648): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7648): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7648): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7648): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7648): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7648): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7648): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7648): 	at com.lge.ds.agent.db.providers.DatabaseAdapter.open(DatabaseAdapter.java:104)
E/SQLiteDatabase( 7648): 	at com.lge.ds.agent.db.providers.ProfileInterface.updateInactivationAllRecord(ProfileInterface.java:502)
E/SQLiteDatabase( 7648): 	at com.lge.ds.agent.db.providers.ProfileInterface.doPreprocess(ProfileInterface.java:483)
E/SQLiteDatabase( 7648): 	at com.lge.ds.agent.db.providers.ProfileInterface.insertProfile(ProfileInterface.java:546)
E/SQLiteDatabase( 7648): 	at com.lge.ds.ServersInfo$InsertProfiles.run(ServersInfo.java:227)
E/LGSync  ( 7648): [DatabaseAdapter] com.lge.ds.agent.db.providers.DatabaseAdapter.open(): 108: Exception:
E/LGSync  ( 7648): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/LGSync  ( 7648): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/LGSync  ( 7648): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/LGSync  ( 7648): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/LGSync  ( 7648): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/LGSync  ( 7648): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/LGSync  ( 7648): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/LGSync  ( 7648): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/LGSync  ( 7648): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/LGSync  ( 7648): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/LGSync  ( 7648): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/LGSync  ( 7648): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/LGSync  ( 7648): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/LGSync  ( 7648): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/LGSync  ( 7648): 	at com.lge.ds.agent.db.providers.DatabaseAdapter.open(DatabaseAdapter.java:104)
E/LGSync  ( 7648): 	at com.lge.ds.agent.db.providers.ProfileInterface.updateInactivationAllRecord(ProfileInterface.java:502)
E/LGSync  ( 7648): 	at com.lge.ds.agent.db.providers.ProfileInterface.doPreprocess(ProfileInterface.java:483)
E/LGSync  ( 7648): 	at com.lge.ds.agent.db.providers.ProfileInterface.insertProfile(ProfileInterface.java:546)
E/LGSync  ( 7648): 	at com.lge.ds.ServersInfo$InsertProfiles.run(ServersInfo.java:227)
E/LGSync  ( 7648): [DatabaseAdapter] com.lge.ds.agent.db.providers.DatabaseAdapter.update(): 216: Pre-condition is failed!
E/SQLiteDatabase( 7648): Failed to open database '/data/data/com.lge.sync/databases/lgds.db'.
E/SQLiteDatabase( 7648): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7648): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7648): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7648): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7648): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7648): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7648): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7648): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7648): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7648): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7648): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7648): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7648): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7648): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7648): 	at com.lge.ds.agent.db.providers.DatabaseAdapter.open(DatabaseAdapter.java:104)
E/SQLiteDatabase( 7648): 	at com.lge.ds.agent.db.providers.ProfileInterface.insertProfile(ProfileInterface.java:554)
E/SQLiteDatabase( 7648): 	at com.lge.ds.ServersInfo$InsertProfiles.run(ServersInfo.java:227)
E/LGSync  ( 7648): [DatabaseAdapter] com.lge.ds.agent.db.providers.DatabaseAdapter.open(): 108: Exception:
E/LGSync  ( 7648): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/LGSync  ( 7648): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/LGSync  ( 7648): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/LGSync  ( 7648): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/LGSync  ( 7648): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/LGSync  ( 7648): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/LGSync  ( 7648): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/LGSync  ( 7648): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/LGSync  ( 7648): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/LGSync  ( 7648): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/LGSync  ( 7648): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/LGSync  ( 7648): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/LGSync  ( 7648): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/LGSync  ( 7648): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/LGSync  ( 7648): 	at com.lge.ds.agent.db.providers.DatabaseAdapter.open(DatabaseAdapter.java:104)
E/LGSync  ( 7648): 	at com.lge.ds.agent.db.providers.ProfileInterface.insertProfile(ProfileInterface.java:554)
E/LGSync  ( 7648): 	at com.lge.ds.ServersInfo$InsertProfiles.run(ServersInfo.java:227)
E/LGSync  ( 7648): [DatabaseAdapter] com.lge.ds.agent.db.providers.DatabaseAdapter.insert(): 205: Pre-condition is failed!
E/LGSync  ( 7648): [ProfileInterface] com.lge.ds.agent.db.providers.ProfileInterface.insertProfile(): 558: Failed! - Failure to call insert()
E/LGSync  ( 7648): [ServersInfo] com.lge.ds.ServersInfo$InsertProfiles.run(): 229: Failure to call ProfileInterface.insertProfile()
E/SQLiteDatabase( 7556): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 7556): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7556): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7556): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7556): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.mcafee.wsstorage.ConfigManager.b(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.mcafee.notificationtray.e.<init>(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.mcafee.notificationtray.e.a(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.mcafee.notificationtray.NotificationComponent.a(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7556): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7556): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7556): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7556): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7556): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7556): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7556): 	at com.mcafee.d.c.run(Unknown Source)
E/SQLiteDatabase( 7556): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 7556): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7556): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7556): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7556): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.mcafee.wsstorage.ConfigManager.a(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.wavesecure.utils.CommonPhoneUtils.o(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.wavesecure.utils.y.v(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7556): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7556): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7556): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7556): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7556): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7556): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7556): 	at com.mcafee.d.c.run(Unknown Source)
,E/SQLiteDatabase( 7556): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 7556): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7556): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7556): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7556): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.mcafee.wsstorage.ConfigManager.d(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.wavesecure.utils.CommonPhoneUtils.o(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.wavesecure.utils.y.v(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7556): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7556): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7556): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7556): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7556): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7556): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7556): 	at com.mcafee.d.c.run(Unknown Source)
D/LgDataFeature( 7499): LgDataFeature() Constructor: none
D/LgDataFeature( 7499): LgDataFeature() Constructor Done, null
E/SQLiteDatabase( 7556): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 7556): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7556): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7556): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7556): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.mcafee.wsstorage.ConfigManager.c(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.mcafee.wsstorage.ConfigManager.m(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7556): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7556): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7556): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7556): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7556): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7556): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7556): 	at com.mcafee.d.c.run(Unknown Source)
D/WiFiOffLoadBroadcast( 7499): MCCMNC not supported: null
D/QRemote ( 7219): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
E/SQLiteDatabase( 7556): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 7556): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7556): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7556): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7556): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.mcafee.wsstorage.ConfigManager.c(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.wavesecure.c2dm.a.d(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.wavesecure.c2dm.a.c(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.wavesecure.notification.g.a(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7556): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7556): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7556): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7556): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7556): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7556): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7556): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7556): 	at com.mcafee.d.c.run(Unknown Source)

```
