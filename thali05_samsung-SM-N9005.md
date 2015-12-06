#### Test 502422853393492_thali05_samsung-SM-N9005 Logs


```
--------- beginning of main
D/Finsky  ( 3357): [440] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 3357): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
D/lights  (  748): button : 0 +
--------- beginning of system
D/PowerManagerService(  748): [input device light] handleInputDeviceLightOff
E/SMD     (  293): DCD ON
D/lights  (  748): button : 0 -
,W/ContextImpl(  748): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/AndroidRuntime( 6047): 
D/AndroidRuntime( 6047): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6047): CheckJNI is OFF
D/AndroidRuntime( 6047): readGMSProperty: start
D/AndroidRuntime( 6047): readGMSProperty: already setted!!
D/AndroidRuntime( 6047): readGMSProperty: end
D/AndroidRuntime( 6047): addProductProperty: start
E/AffinityControl( 6047): AffinityControl: registerfunction enter
I/TemperatureHumiditySensor(  748): Accuracy has been changed to 3
D/AndroidRuntime( 6047): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  748): inState():  stateMachine is null !!
I/PersonaManagerService(  748): PersonaId don't exist
I/ActivityManager(  748): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy(  748): isApplicationStateBlocked userId 0 pkgname com.example.hello
I/ActivityManager(  748): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  748): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
D/CustomFrequencyManagerService(  748): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 748  pkgName : ACTIVITY_RESUME_BOOSTER@7
W/ActivityManager(  748): mDVFSHelper.acquire()
I/SurfaceFlinger(  257): id=10 createSurf (16x16),-1 flag=20004, EimLayer
I/SurfaceFlinger(  257): id=11 createSurf (16x16),-1 flag=20004, EimLayer
D/FocusedStackFrame(  748): Set to : 0
D/Launcher.HomeView( 1447): onPause
D/Launcher( 1447): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 40000000
D/AndroidRuntime( 6047): Shutting down VM
V/TaskCloserActivity( 5588): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
D/PointerIcon(  748): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  748): setMouseCustomIcon IconType is same.101
D/PointerIcon(  748): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  748): setHoveringSpenCustomIcon IconType is same.1
E/ActivityManager(  748): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  748): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  748): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  748): checkUser: useridlist=null, currentuser=0
I/SurfaceFlinger(  257): id=12 createSurf (1x1),1 flag=404, iello
E/Zygote  ( 6073): MountEmulatedStorage()
E/Zygote  ( 6073): v2
I/libpersona( 6073): KNOX_SDCARD checking this for 10265
I/libpersona( 6073): KNOX_SDCARD not a persona
I/ActivityManager(  748): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=6073 uid=10265 gids={50265, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/SELinux ( 6073): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6073): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6073): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/StatusBarManagerService(  748): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
V/ActivityThread( 1447): updateVisibility : ActivityRecord{2e40aab2 token=android.os.BinderProxy@680afbe {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
I/MicrophoneInputStream( 1633): mic_close gfk@30b5f9b
V/AudioPolicyManager(  298): stopInput() input 14
V/AudioPolicyManager(  298): releaseInput() 14
V/AudioPolicyManager(  298): closeInput(14)
I/HotwordRecognitionRnr( 1633): Hotword detection finished
I/HotwordRecognitionRnr( 1633): Stopping hotword detection.
V/audio_hw_primary(  298): in_standby: enter
D/TimaKeyStoreProvider( 6073): TimaSignature is unavailable
D/ActivityThread( 6073): Added TimaKeyStore provider
V/WindowOrientationListener(  748): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  748): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  748): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  748): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  748): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/ActivityManager(  748): Display changed displayId=0
D/Launcher.HomeView( 1447): onStop
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1789): [237392/8] Surface widget pause on instance = 1
D/accuweather( 1789): [Accuweather J]>>> SWW:212 [0:0] [SWW] onPause : rI = 1
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1789): [237392/8] Surface widget visibility changed visibility = false on instance = 1
D/accuweather( 1789): [Accuweather J]>>> SWW:222 [0:0] [SWW] onPause : size = 0
V/ActivityThread( 1447): updateVisibility : ActivityRecord{2e40aab2 token=android.os.BinderProxy@680afbe {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/accuweather( 1789): [Accuweather J]>>> SWW:634 [0:0]  unRegisterTTReceiver !! 
D/SurfaceWidgetView( 1447): destroyHardwareResources():402283253
V/audio_hw_primary(  298): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  298): disable_audio_route: enter: usecase(7)
V/audio_hw_primary(  298): disable_audio_route: reset mixer path: audio-record
D/audio_route(  298): ++++ audio_route_update_mixer ==============
D/audio_route(  298): Setting mixer control: MultiMedia1 Mixer SLIM_0_TX
D/audio_route(  298): Setting mixer control: value: 0
D/StatusBarManagerService(  748): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/audio_route(  298): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  298): disable_audio_route: exit
V/audio_hw_primary(  298): disable_snd_device: snd_device(128: vr-main-mic)
D/audio_route(  298): ++++ audio_route_update_mixer ==============
D/audio_route(  298): Setting mixer control: ADC1 Volume
D/audio_route(  298): Setting mixer control: value: 0
D/audio_route(  298): Setting mixer control: DEC6 Volume
D/audio_route(  298): Setting mixer control: value: 0
D/audio_route(  298): Setting mixer control: SLIM TX7 MUX, value: 0
D/audio_route(  298): Setting mixer control: AIF1_CAP Mixer SLIM TX7
D/audio_route(  298): Setting mixer control: value: 0
D/audio_route(  298): Setting mixer control: DEC6 MUX, value: 0
D/audio_route(  298): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  298): stop_input_stream: exit: status(0)
V/audio_hw_primary(  298): in_standby: exit:  status(0)
V/audio_hw_primary(  298): adev_close_input_stream
V/audio_hw_primary(  298): in_standby: enter
V/audio_hw_primary(  298): in_standby: exit:  status(0)
E/audio_hw_primary(  298): adev_close_input_stream, set jack_in to null
V/AudioPolicyManager(  298): releaseInput() exit
D/accuweather( 1789): [Accuweather J]>>> WCD:1431 [0:0] cARH()
D/ConnectivityService(  748): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/accuweather( 1789): [Accuweather J]>>> WCD:549 [0:0]  onPause 
D/accuweather( 1789): [Accuweather J]>>> WR:475 [0:0] onPause : 1
D/accuweather( 1789): [Accuweather J]>>> SWW:540 [0:0] =================== , pause :1
D/ResourcesManager( 6073): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
D/Launcher( 1447): onTrimMemory. Level: 20
D/SurfaceWidgetView( 1447): destroyHardwareResources():402283253
I/WebViewFactory( 6073): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
D/ResourcesManager( 6073): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader( 6073): Loading: webviewchromium
I/LibraryLoader( 6073): Time to load native libraries: 5 ms (timestamps 2049-2054)
I/LibraryLoader( 6073): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6073): Binding Chromium to main looper Looper (main, tid 1) {10c5ce8}
I/LibraryLoader( 6073): Expected native library version number "",actual native library version number ""
I/chromium( 6073): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6073): Initializing chromium process, renderers=0
W/art     ( 6073): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6073): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
W/chromium( 6073): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6073): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46780 len=2953
I/chromium( 6073): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229536 len:643667
D/BluetoothAdapter( 6073): 973238017: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 6073): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 6073): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6073): Build Date: 11/19/14 Wed
I/Adreno-EGL( 6073): Local Branch: mybranch5813579
I/Adreno-EGL( 6073): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 6073): Local Patches: NONE
I/Adreno-EGL( 6073): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
W/chromium( 6073): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 6073): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 6073): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6073): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6073): CordovaWebView is running on device made by: samsung
W/art     ( 6073): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6073): Attempt to remove local handle scope entry from IRT, ignoring
D/Activity( 6073): performCreate Call secproduct feature valuefalse
D/Activity( 6073): performCreate Call debug elastic valuetrue
D/OpenGLRenderer( 6073): Render dirty regions requested: true
D/Atlas   ( 6073): Validating map...
D/ActivityManager(  748): post active user change for 0
D/KnoxTimeoutHandler(  748): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  748): handleActiveUserChange for user 0
I/SurfaceFlinger(  257): id=13 createSurf (1x1),1 flag=404, NainActivit
D/PointerIcon(  748): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
I/OpenGLRenderer( 6073): Initialized EGL, version 1.4
D/PointerIcon(  748): setMouseCustomIcon IconType is same.101
D/PointerIcon(  748): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  748): setHoveringSpenCustomIcon IconType is same.1
I/OpenGLRenderer( 6073): HWUI protection enabled for context ,  &this =0xa1853060 ,&mEglDisplay = 1 , &mEglConfig = 8 
D/OpenGLRenderer( 6073): Enabling debug mode 0
D/InputMethodManagerService(  748): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/ContextImpl(  748): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/ContextImpl(  748): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/SamsungIME( 1735): getCurrentCandidateView
I/ActivityManager(  748): Displayed com.example.hello/.MainActivity: +585ms
I/SurfaceFlinger(  257): id=6 Removed Mauncher (4/10)
I/SurfaceFlinger(  257): id=6 Removed Mauncher (-2/10)
I/Timeline( 6073): Timeline: Activity_idle id: android.os.BinderProxy@2184d018 time:72399
D/SamsungIME( 1735): Dismiss ExpandCandiate
I/chromium( 6073): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
E/AndroidProtocolHandler( 6073): Unable to open asset URL: file:///android_asset/www/jxcore.js
D/JsMessageQueue( 6073): Set native->JS mode to OnlineEventsBridgeMode
I/SamsungIME( 1735): getDebugLevel  : 0x4f4c
I/chromium( 6073): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6073): 
I/SamsungIME( 1735): getDebugLevel  : 0x4f4c
I/SamsungIME( 1735): KeybaordView init() : load resources
I/SamsungIME( 1735): getCurrentKeyboard
I/SamsungIME( 1735): getTextKeyboard
D/SamsungIME( 1735): [SwiftkeyWrapper] currentLangauge : 1701729619
I/SurfaceFlinger(  257): id=12 Removed iello (7/9)
I/SurfaceFlinger(  257): id=12 Removed iello (-2/9)
D/jxcore_app_log( 6073): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1358313728
D/JX-Cordova( 6073): jxcore cordova android initializing
D/CustomFrequencyManagerService(  748): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 748  tag : ACTIVITY_RESUME_BOOSTER@7
D/CustomFrequencyManagerService(  748): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 748  pkgName : ACTIVITY_RESUME_BOOSTER@11
D/CustomFrequencyManagerService(  748): FrequencyrequestList.getNextMaxCPUCoreRequest, index: 0
W/ActivityManager(  748): mDVFSHelper.release()
I/Timeline(  748): Timeline: Activity_windows_visible id: ActivityRecord{23048c u0 com.example.hello/.MainActivity t2} time:72682
W/jxcore-log( 6073): Initializing JXcore engine
W/jxcore-log( 6073): JXcore engine is ready
W/jxcore-log( 6073): Starting JXcore engine
,E/auditd  ( 1865): In denial and Property audit_ondenial is set to 1 
D/SecurityLogAgent:SEDenialService(  748): Got Modify Event and sending Denial Intent foraudit.log
W/ContextImpl(  748): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
E/ActivityManager(  748): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  748): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  748): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  748): checkUser: useridlist=null, currentuser=0
D/SecurityLogAgent:SEDenialService(  748): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
E/Zygote  ( 6131): MountEmulatedStorage()
E/Zygote  ( 6131): v2
I/libpersona( 6131): KNOX_SDCARD checking this for 1000
I/libpersona( 6131): KNOX_SDCARD not a persona
I/ActivityManager(  748): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=6131 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/art     (  343): Explicit concurrent mark sweep GC freed 8756(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 304us total 13.726ms
I/art     (  343): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 272us total 9.870ms
I/art     (  343): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 284us total 9.755ms
W/jxcore-log( 6073): Platform android
W/jxcore-log( 6073): 
W/jxcore-log( 6073): Process ARCH arm
W/jxcore-log( 6073): 
I/SELinux ( 6131): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6131): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6131): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 6131): TimaSignature is unavailable
D/ActivityThread( 6131): Added TimaKeyStore provider
I/jxcore-log( 6073): JXcore Cordova bridge is ready!
I/jxcore-log( 6073): 
W/jxcore-log( 6073): JXcore engine is started
D/ResourcesManager( 6131): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
D/SecurityLogAgent( 6131):  SeDenialReceiver : Intent Received : android.intent.action.DENIAL_NOTIFICATION
D/SecurityLogAgent( 6131):  SeDenialReceiver : File path = null
I/ActivityManager(  748): Killing 5245:com.sec.spp.push:RemoteNotiProcess/u0a43 (adj 15): bgCount ##41
E/jxcore-log( 6073): >> samsung-SM-N9005
E/jxcore-log( 6073): 
I/jxcore-log( 6073): Total memory 2971471872
I/jxcore-log( 6073): 
I/jxcore-log( 6073): Free memory 431091712
I/jxcore-log( 6073): 
I/jxcore-log( 6073): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6073): 
I/jxcore-log( 6073): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6073): 
I/jxcore-log( 6073): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 6073): 
I/jxcore-log( 6073): Size 1080 1920
I/jxcore-log( 6073): 
I/jxcore-log( 6073): Screen Brightness 162
I/jxcore-log( 6073): 
E/jxcore-log( 6073): Dummy Error Log.
E/jxcore-log( 6073): 
D/CustomFrequencyManagerService(  748): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 748  tag : ACTIVITY_RESUME_BOOSTER@11
D/SamsungIME( 1735): [SwiftkeyWrapper] currentLangauge : 1701729619
I/jxcore-log( 6073): getBuffer is called!!!!
I/jxcore-log( 6073): 
,E/SMD     (  293): DCD ON
,V/AlarmManager(  748): waitForAlarm result :8
,E/Watchdog(  748): !@Sync 2
,V/AlarmManager(  748): waitForAlarm result :8
,D/NtpTrustedTime(  748): forceRefresh() from cache miss
,D/NtpTrustedTime(  748): forceRefresh Fail.
,W/ContextImpl(  748): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  293): DCD ON
,D/BluetoothAdapter( 6073): disable()
,E/BluetoothManagerService(  748): Bluetooth is already disabled. DO NOT disable again.
,I/WifiManager( 6073): packageName : com.example.hello
,D/SecContentProvider(  748): uri = 18 selection = isWifiEnabled
D/SecContentProvider2(  748): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  748): mCursor = null
,D/WifiService(  748): setWifiEnabled: false pid=6073, uid=10265,
,D/SettingsProvider(  748): name = wifi_on
,I/jxcore-log( 6073): ****TEST TOOK:  5061  ms ****
I/jxcore-log( 6073): 
,I/jxcore-log( 6073): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6073): 
,D/AndroidRuntime( 6194): 
D/AndroidRuntime( 6194): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6194): CheckJNI is OFF
,D/AndroidRuntime( 6194): readGMSProperty: start
,D/AndroidRuntime( 6194): readGMSProperty: already setted!!
,D/AndroidRuntime( 6194): readGMSProperty: end
,D/AndroidRuntime( 6194): addProductProperty: start
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,E/AffinityControl( 6194): AffinityControl: registerfunction enter
,D/AndroidRuntime( 6194): Calling main entry com.android.commands.pm.Pm
,D/PersonaManagerService(  748): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager(  748): START PACKAGE DELETE: observer{120867014}
D/PackageManager(  748): pkg{<packageName>}
D/PackageManager(  748): user{0}
D/PackageManager(  748): caller{2000}
D/PackageManager(  748): flags{3}
D/PersonaManagerService(  748): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  748): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  748): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager(  748): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
,D/PackageManager(  748): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService(  748): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManagerService(  748): deletePackage- pkg:com.example.hello, edmuserId:-1
D/ApplicationPolicy(  748): getApplicationUninstallationEnabled
,D/ApplicationPolicy(  748): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager(  748): !@killApplicatoin: 10265, uninstall pkg
,I/ActivityManager(  748): Force stopping com.example.hello appid=10265 user=-1: uninstall pkg
I/ActivityManager(  748): Killing 6073:com.example.hello/u0a265 (adj 0): stop com.example.hello
,W/PackageSettings(  748): Skipping PackageSetting{3517d5b4 com.test.thalitest/10264} due to missing metadata
,I/WindowState(  748): WIN DEATH: Window{1385d4b5 u0 com.example.hello/com.example.hello.MainActivity}
,I/SurfaceFlinger(  257): id=13 Removed NainActivit (5/8)
,I/SurfaceFlinger(  257): id=13 Removed NainActivit (-2/8)
I/SurfaceFlinger(  257): id=13 Removed NainActivit (-2/8)
D/PointerIcon(  748): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  748): setMouseCustomIcon IconType is same.101
D/PointerIcon(  748): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  748): setHoveringSpenCustomIcon IconType is same.1
,W/ActivityManager(  748): Force removing ActivityRecord{23048c u0 com.example.hello/.MainActivity t2}: app died, no saved state
,D/FocusedStackFrame(  748): Set to : 0
,D/CustomFrequencyManagerService(  748): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 748  pkgName : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager(  748): mDVFSHelper.acquire()
,V/WindowOrientationListener(  748): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  748): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  748): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  748): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  748): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
,D/SurfaceWidgetView( 1447): destroyHardwareResources():402283253
,D/Launcher( 1447): onRestart, Launcher: 169366066
,I/ActivityManager(  748): Force stopping com.example.hello appid=10265 user=0: pkg removed
,W/ActivityManager(  748): Spurious death for ProcessRecord{e938087 6073:com.example.hello/u0a265}, curProc for 6073: null
,D/ConnectivityService(  748): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager(  748): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  748): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,I/art     ( 5831): Explicit concurrent mark sweep GC freed 3747(195KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 354us total 19.007ms
,W/GeofencerStateMachine( 1473): Ignoring removeGeofence because network location is disabled.
,E/ActivityManager(  748): checkUser: useridlist=null, currentuser=0
E/SamsungIME( 1735): mOCRHelper is null
,E/ActivityManager(  748): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  748): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  748): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(  748): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,I/InputReader(  748): Reconfiguring input devices.  changes=0x00000010
,I/art     ( 4155): Explicit concurrent mark sweep GC freed 32163(1809KB) AllocSpace objects, 9(144KB) LOS objects, 39% free, 15MB/26MB, paused 1.798ms total 31.553ms
,E/Zygote  ( 6224): MountEmulatedStorage()
E/Zygote  ( 6224): v2
I/libpersona( 6224): KNOX_SDCARD checking this for 10023
I/libpersona( 6224): KNOX_SDCARD not a persona
,I/ActivityManager(  748): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=6224 uid=10023 gids={50023, 9997, 3003} abi=armeabi-v7a
,D/Launcher( 1447): onStart, Launcher: 169366066
D/Launcher.HomeView( 1447): onStart
D/Launcher( 1447): onResume, Launcher: 169366066
,I/art     ( 4303): Explicit concurrent mark sweep GC freed 8011(479KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 16MB/21MB, paused 342us total 85.026ms
,D/ResourcesManager(  748): creating new AssetManager and set to /system/app/talkback/talkback.apk
,I/SELinux ( 6224): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6224): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6224): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/SettingsProvider(  748): name = kids_home_mode
D/SettingsProvider(  748): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  748): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  748): selectionArgs: false
D/SettingsProvider(  748): selectionArgs: 10010
D/SecContentProvider(  748): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  748): ret = -1
,D/Launcher.HomeView( 1447): onResume
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 1789): [237392/8] Surface widget resume on instance = 1
,D/accuweather( 1789): [Accuweather J]>>> SWW:179 [0:0] [SWW] onResume : rI = 1
D/Launcher( 1447): setSystemUiTransparency.SettingNotFoundException : set as TRUE
D/accuweather( 1789): [Accuweather J]>>> SWW:184 [0:0] [SWW] onResume : Orientation = 1/1
D/accuweather( 1789): [Accuweather J]>>> WR:456 [0:0] =============== updateTime = 1
D/accuweather( 1789): [Accuweather J]>>> SWW:198 [0:0] [SWW] onResume : size = 1
,D/Launcher( 1447): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 8000
,D/accuweather( 1789): [Accuweather J]>>> DBH:1954 [0:0] gADWI : count = 0
,D/EnterpriseDeviceManagerService(  748): Package has changed for user 0
D/EnterpriseDeviceManagerService(  748): Admin package name: com.google.android.gms
,D/ResourcesManager(  748): creating new AssetManager and set to /system/app/Evernote_H/Evernote_H.apk
,D/accuweather( 1789): [Accuweather J]>>> WCD:423 [0:0]  onFirstUpdate :: fU = false
,D/accuweather( 1789): [Accuweather J]>>> SWW:313 [0:0] hideMsg : mResumeInstnceList[0] = 1
D/accuweather( 1789): [Accuweather J]>>> WR:800 [0:0] hideMsg : -1, isShow = false
D/accuweather( 1789): [Accuweather J]>>> WR:806 [0:0] hideMsg : 0
,D/accuweather( 1789): [Accuweather J]>>> WCD:513 [0:0]  onResume : fU = false, cnt =0
D/accuweather( 1789): [Accuweather J]>>> WCD:523 [0:0]  onResume :: mFAR = false, cC = false, isa = false
D/accuweather( 1789): [Accuweather J]>>> SWW:605 [0:0]  registerTTReceiver ! 
,D/MenuAppsGridFragment( 1447): onResume
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 1789): [237392/8] Surface widget visibility changed visibility = true on instance = 1
,D/SurfaceWidget.Renderer( 1789): [237392/8] SurfaceWidget drawing first frame
D/accuweather( 1789): [Accuweather J]>>> WR:623 [0:0] onGLDraw : BG texture = 5
,D/ActivityManager(  748): handle home activity for 0
,I/WallpaperManagerService(  748): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler(  748): post home show event for user 0
D/ActivityManager(  748): post active user change for 0
D/KnoxTimeoutHandler(  748): postActiveUserChange for user 0
,D/accuweather( 1789): [Accuweather J]>>> WR:497 [0:0] onResume : 1, widgetMode : 1, orientation : 1
,I/SurfaceFlinger(  257): id=14 createSurf (1080x1920),1 flag=4, Mauncher
,D/StatusBarManagerService(  748): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/comsamsunglog( 1789): [Accuweather J]>>> ==============================================================================================
,D/comsamsunglog( 1789): [Accuweather J]>>> widgetappapheroaccuweather [Version : 14121502] [ 1 ] 
D/comsamsunglog( 1789): [Accuweather J]>>> Header set to : ===> "accuweather" <===
D/comsamsunglog( 1789): [Accuweather J]>>> ==============================================================================================
,D/accuweather( 1789): [Accuweather J]>>> SM:1134 [0:0] updateCurrentCityTime : [1]0/1
D/accuweather( 1789): [Accuweather J]>>> SM:1151 [0:0] updateCurrentCityTime , ConditionLayerWidth = 852, mConditionLayerHeight = 532
,D/accuweather( 1789): [Accuweather J]>>> SM:2053 [0:0] drw 1nd Tm dt = Sun, 6 December
,D/accuweather( 1789): [Accuweather J]>>> SM:3422 [0:0] onR : isAni = false
,D/accuweather( 1789): [Accuweather J]>>> SWW:544 [0:0] =================== , resume :1
D/PointerIcon(  748): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  748): setMouseCustomIcon IconType is same.101
D/PointerIcon(  748): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  748): setHoveringSpenCustomIcon IconType is same.1
,D/TimaKeyStoreProvider( 6224): TimaSignature is unavailable
,D/ActivityThread( 6224): Added TimaKeyStore provider
,D/Launcher( 1447): setSystemUiTransparency.SettingNotFoundException : set as TRUE
,D/Launcher( 1447): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 8000
,D/InputMethodManagerService(  748): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService(  748): Got RemoteException sending setActive(false) notification to pid 6073 uid 10265
,W/ContextImpl(  748): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/art     (  748): Explicit concurrent mark sweep GC freed 28491(2MB) AllocSpace objects, 11(176KB) LOS objects, 17% free, 36MB/44MB, paused 2.938ms total 170.681ms
I/art     (  748): WaitForGcToComplete blocked for 170.859ms for cause Explicit
,D/ResourcesManager(  748): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,D/ResourcesManager(  748): creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
,I/MicrophoneInputStream( 1633): mic_starting gfk@1eb6af12
,I/HotwordRecognitionRnr( 1633): Starting hotword detection.
,W/Resources(  748): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  748): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/ResourcesManager(  748): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,V/AudioPolicyManager(  298): getInput() inputSource 1999, samplingRate 16000, format 8, channelMask 1, session 0, flags 0x10
,V/AudioPolicyManager(  298): getDeviceForInputSource()input source 1999, device 80000004
V/audio_hw_primary(  298): adev_open_input_stream: enter
E/audio_hw_primary(  298): adev_open_input_stream : jack_config 0
E/audio_hw_primary(  298): can not make /data/snd/hal_input.pcm 
,E/audio_hw_primary(  298): can not make /data/snd/hal_input_before_ns.pcm 
E/audio_hw_primary(  298): can not make /data/snd/hal_input_after_ns.pcm 
E/audio_hw_primary(  298): adev_open_input_stream input is null, set new input stream
V/audio_hw_primary(  298): adev_open_input_stream: exit
,I/AudioFlinger(  298): AudioFlinger's thread 0xb0566000 ready to run
V/audio_hw_primary(  298): in_standby: enter
V/audio_hw_primary(  298): in_standby: exit:  status(0)
D/ResourcesManager(  748): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,D/ResourcesManager(  748): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,V/audio_hw_primary(  298): in_standby: enter
V/audio_hw_primary(  298): in_standby: exit:  status(0)
,I/EDMNativeHelperService(  748): isMicrophoneEnabled
,D/ResourcesManager( 6224): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,D/ResourcesManager(  748): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/SecContentProvider2(  748): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  748): mCursor = null
,D/WallpaperManager( 1447): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,V/AudioPolicyManager(  298): startInput() input 16
V/AudioPolicyManager(  298): getDeviceForInputSource()input source 1999, device 80000004
V/AudioPolicyManager(  298): getNewInputDevice() selected device 80000004
,V/AudioPolicyManager(  298): DeviceVector::refreshTypes() mDeviceTypes 80000004
V/AudioPolicyManager(  298): DeviceVector::getDevicesFromType() for type 80000004 found 0xb315b3c0
V/audio_hw_primary(  298): in_set_parameters: enter: kvpairs=input_source=6;keyIsHotword=true;routing=-2147483644
V/audio_hw_primary(  298): in_set_parameters: exit: status(11)
V/AudioPolicyManager(  298): setInputDevice() createAudioPatch returned 11 patchHandle 0
V/AudioPolicyManager(  298): AudioPolicyManager::startInput() input source = 1999
,I/MicrophoneInputStream( 1633): mic_started gfk@1eb6af12
,D/WallpaperManager( 1447): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/StatusBarManagerService(  748): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,V/msm8974_platform(  298): platform_update_usecase_from_source: input source :6
V/audio_hw_primary(  298): start_input_stream: enter: usecase(7)
V/voice   (  298): voice_check_and_set_incall_rec_usecase: voice call not active
V/audio_hw_primary(  298): start_input_stream: usecase(7)
D/PreProcess(  298): new SamsungRecord
D/PreProcess(  298): new NS
I/samsungRecord(  298): [samsungrecord] SamsungRecInit 
,I/samsungRecord(  298): [samsungrecordMIC]Use HardCoding Values
E/samsungRecord(  298): miccalib file can't created. (/data/snd/miccalib.txt)
I/samsungRecord(  298): 1
D/SamsungRecord_NS(  298): [SamsungRecord_NS] Init SR 16000
D/SamsungRecord_NS(  298): [SamsungRecord_NS] getLevel inputsource 6, ret_level 3
V/audio_hw_primary(  298): select_devices: ENTER
V/audio_hw_primary(  298): select_devices: usecase(normal)
V/audio_hw_primary(  298): select_devices: usecase(PCM_CAPTURE)
V/msm8974_platform(  298): platform_get_input_snd_device: enter: out_device(0) in_device(0x4)
V/msm8974_platform(  298): get_INPUT_snd_device: check by Input_source(6)
V/msm8974_platform(  298): platform_get_input_snd_device_by_source: enter: out_device(0) in_device(0x4)
V/msm8974_platform(  298): get_INPUT_snd_device: AUDIO_SOURCE_VOICE_RECOGNITION
V/msm8974_platform(  298): platform_get_input_snd_device: exit: in_snd_device(vr-main-mic)
D/audio_hw_primary(  298): select_devices: out_snd_device(0: dummy)
D/audio_hw_primary(  298): select_devices: in_snd_device(128: vr-main-mic)
D/ACDB-LOADER(  298): ACDB -> send_audio_cal, acdb_id = 53, path =  1
D/ACDB-LOADER(  298): ACDB -> send_adm_topology
D/ACDB-LOADER(  298): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TOPOLOGY_ID
D/ACDB-LOADER(  298): ACDB -> send_asm_topology
D/ACDB-LOADER(  298): ACDB -> ACDB_CMD_GET_AUDPROC_STREAM_TOPOLOGY_ID
D/ACDB-LOADER(  298): ACDB -> send_audtable
D/ACDB-LOADER(  298): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TABLE
D/ACDB-LOADER(  298): ACDB -> AUDIO_SET_AUDPROC_CAL
D/ACDB-LOADER(  298): ACDB -> send_audvoltable
D/ACDB-LOADER(  298): ACDB -> ACDB_CMD_GET_AUDPROC_GAIN_DEP_STEP_TABLE
D/        (  298): Failed to fetch the lookup information of the device 00000035 
E/ACDB-LOADER(  298): Error: ACDB AudProc vol returned = -19
D/ACDB-LOADER(  298): ACDB -> AUDIO_SET_AUDPROC_VOL_CAL
D/ACDB-LOADER(  298): ACDB -> AUDIO_SET_AFE_CAL
V/audio_hw_primary(  298): enable_snd_device: snd_device(128: vr-main-mic, vr-main-mic)
D/audio_route(  298): ++++ audio_route_update_mixer ==============
D/audio_route(  298): Setting mixer control: ADC1 Volume
D/audio_route(  298): Setting mixer control: value: 19
,D/ResourcesManager(  748): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/audio_route(  298): Setting mixer control: DEC6 Volume
D/audio_route(  298): Setting mixer control: value: 84
,D/audio_route(  298): Setting mixer control: SLIM TX7 MUX, value: 13
,D/audio_route(  298): Setting mixer control: AIF1_CAP Mixer SLIM TX7
D/audio_route(  298): Setting mixer control: value: 1
,D/audio_route(  298): Setting mixer control: DEC6 MUX, value: 2
,D/audio_route(  298): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  298): enable_audio_route: enter: usecase(7)
V/audio_hw_primary(  298): enable_audio_route: apply mixer path: audio-record
D/audio_route(  298): ++++ audio_route_update_mixer ==============
D/audio_route(  298): Setting mixer control: MultiMedia1 Mixer SLIM_0_TX
D/audio_route(  298): Setting mixer control: value: 1
,D/audio_route(  298): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  298): enable_audio_route: exit
V/audio_hw_primary(  298): start_input_stream: Opening PCM device card_id(0) device_id(0), channels 1
,V/audio_hw_primary(  298): start_input_stream: exit
,I/Timeline( 1447): Timeline: Activity_idle id: android.os.BinderProxy@680afbe time:79065
,D/ResourcesManager(  748): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager(  748): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/RegisteredServicesCache( 1411): empty dynamic service
,I/KLMS-2.4.511: ( 6224): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.511: ( 6224): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1449413995678
,D/ResourcesManager(  748): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,I/KLMS-2.4.511: ( 6224): MainReciver(): PACKAGE_REMOVED
,W/Resources(  748): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  748): creating new AssetManager and set to /system/app/Books/Books.apk
I/KLMS-2.4.511: ( 6224): MainReciver(): REPLACING: false | pkgName: com.example.hello
,D/ResourcesManager(  748): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,D/ResourcesManager(  748): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ResourcesManager(  748): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(  748): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
,D/ResourcesManager(  748): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager(  748): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager(  748): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,I/HotwordWorker( 1633): onReady
,D/ResourcesManager(  748): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  748): creating new AssetManager and set to /system/app/Drive/Drive.apk
,E/ActivityManager(  748): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  748): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  748): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  748): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(  748): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager(  748): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager(  748): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(  748): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(  748): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,E/Zygote  ( 6248): MountEmulatedStorage()
E/Zygote  ( 6248): v2
I/libpersona( 6248): KNOX_SDCARD checking this for 10116
I/libpersona( 6248): KNOX_SDCARD not a persona
,D/ResourcesManager(  748): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,W/Resources(  748): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  748): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager(  748): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,I/ActivityManager(  748): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6248 uid=10116 gids={50116, 9997, 3003} abi=armeabi-v7a
,D/ResourcesManager(  748): creating new AssetManager and set to /system/app/Videos/Videos.apk
,I/ActivityManager(  748): Killing 5287:com.sec.android.diagmonagent/1000 (adj 15): bgCount ##41
,I/SELinux ( 6248): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6248): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6248): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6248): TimaSignature is unavailable
,D/ActivityThread( 6248): Added TimaKeyStore provider
,D/RCPManagerService(  748): PackageReceiver onReceive()
,I/HarmonyEASService(  748): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy(  748): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/ResourcesManager(  748): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/BackupManagerService(  748): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService(  748): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  748): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  748): uID is 10265
V/EnterpriseBillingPolicy(  748): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  748): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage(  748): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  748): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  748): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  748): getBillingProfileForVpnEngine - start - com.example.hello
,V/EnterpriseBillingPolicyStorage(  748): getBillingProfileForVpnEngine - end - null
,D/ResourcesManager( 6248): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,I/art     (  748): Explicit concurrent mark sweep GC freed 8560(402KB) AllocSpace objects, 0(0B) LOS objects, 17% free, 37MB/45MB, paused 4.339ms total 274.907ms
,D/elm:14491( 6248): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14491( 6248): ELMEngine.ELMEngine( context ).
,D/CustomFrequencyManagerService(  748): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 748  tag : ACTIVITY_RESUME_BOOSTER@7
D/TaskPersister(  748): removeObsoleteFile: deleting file=2_task.xml
,D/WallpaperManagerService(  748):  force update = false; persona id = 0; current user =0; current persona = 0
W/ActivityManager(  748): mDVFSHelper.release()
D/KnoxTimeoutHandler(  748): handleHomeShow for 0 and current 0
D/KnoxTimeoutHandler(  748): handleActiveUserChange for user 0
D/CustomFrequencyManagerService(  748): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 748  pkgName : ACTIVITY_RESUME_BOOSTER@11
,D/elm:14491( 6248): MDMBridge.setEnterpriseBridge()
,D/ResourcesManager(  748): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,D/elm:14491( 6248): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,E/ActivityManager(  748): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  748): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  748): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  748): checkUser: useridlist=null, currentuser=0
,W/Resources(  748): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  748): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,E/Zygote  ( 6266): MountEmulatedStorage()
E/Zygote  ( 6266): v2
I/libpersona( 6266): KNOX_SDCARD checking this for 10021
I/libpersona( 6266): KNOX_SDCARD not a persona
,D/elm:14491( 6248): ElmAgentService : onCreate()
D/elm:14491( 6248): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:14491( 6248): MainReceiver.listeningToPackageRemoved()
D/elm:14491( 6248): MDMBridge.getInstance()
D/elm:14491( 6248): MDMBridge.getAllLicenseInfoFromSDK()
,I/ActivityManager(  748): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=6266 uid=10021 gids={50021, 9997} abi=armeabi-v7a
,I/Timeline(  748): Timeline: Activity_windows_visible id: ActivityRecord{2d3bd900 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:79309
,W/Resources(  748): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  748): creating new AssetManager and set to /system/priv-app/SamsungLink20/SamsungLink20.apk
,D/PackageManager(  748): delete codoeFile: 
,W/Resources(  748): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  748): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  748): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,I/AASAUninstall(  748):  com.example.hello not target!
D/PackageManager(  748): result of delete: 1{120867014}
,W/Resources(  748): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  748): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,I/SELinux ( 6266): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,D/elm:14491( 6248): MDMBridge.getAllLicenseInfoFromSDK()
,I/SELinux ( 6266): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6266): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/AndroidRuntime( 6194): Shutting down VM
,D/ResourcesManager(  748): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  748): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(  748): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/TimaKeyStoreProvider( 6266): TimaSignature is unavailable
,D/ActivityThread( 6266): Added TimaKeyStore provider
,W/Resources(  748): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  748): creating new AssetManager and set to /system/app/Maps/Maps.apk
,D/elm:14491( 6248): ElmAgentService : onDestroy().
,I/ActivityManager(  748): Killing 4375:com.android.providers.calendar/u0a51 (adj 15): bgCount ##41
,D/BatteryService(  748): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  748): level:100, scale:100, status:5, health:2, present:true, voltage: 4285, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  748): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  748): Sending ACTION_BATTERY_CHANGED.
,D/ResourcesManager(  748): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,I/MotionRecognitionService(  748): Plugged
I/MotionRecognitionService(  748): setPowerConnected  = true
,D/ResourcesManager( 6266): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,D/ResourcesManager(  748): creating new AssetManager and set to /system/app/Peel_L/Peel_L.apk
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1184):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/ResourcesManager(  748): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,W/Resources(  748): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  748): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  748): creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
,W/ResourcesManager(  748): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(  748): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  748): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources(  748): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  748): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,D/ResourcesManager(  748): creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
,D/ResourcesManager(  748): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  748): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,D/com.sec.android.service.health.upgrade.UninstallReceiver( 6266): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 6266): onReceive called  PACKAGE_REMOVED package:com.example.hello
D/com.sec.android.service.health.upgrade.UninstallReceiver( 6266): onReceive() : package name is not s health. Return !!!
,W/Resources(  748): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  748): creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
,W/Resources(  748): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  748): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
,W/Resources(  748): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  748): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  748): creating new AssetManager and set to /system/priv-app/SecMyFiles2/SecMyFiles2.apk
,I/PCWCLIENTTRACE_PushUtil( 5692): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5692): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5692): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5692): [onReceive] - android.intent.action.PACKAGE_REMOVED
,W/Resources(  748): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  748): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources(  748): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  748): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  748): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/Resources(  748): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  748): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager(  748): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,E/ActivityManager(  748): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  748): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  748): checkUser: useridlist=null, currentuser=0
W/Resources(  748): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/ActivityManager(  748): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6283): MountEmulatedStorage()
,E/Zygote  ( 6283): v2
I/libpersona( 6283): KNOX_SDCARD checking this for 10043
I/libpersona( 6283): KNOX_SDCARD not a persona
,I/ActivityManager(  748): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=6283 uid=10043 gids={50043, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  748): Killing 4723:com.google.android.talk/u0a131 (adj 15): bgCount ##41
,D/UsbSettingsManager(  748): clearDefaults: com.example.hello
I/CrashAnrDetector(  748): onPackageRemoved : com.example.hello
,I/SELinux ( 6283): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6283): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6283): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6283): TimaSignature is unavailable
,D/ActivityThread( 6283): Added TimaKeyStore provider
,D/CustomFrequencyManagerService(  748): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 748  tag : ACTIVITY_RESUME_BOOSTER@11
,D/ResourcesManager( 6283): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,E/SPPClientService( 6283): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 6283): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 6283): PushLog.txt file is not deleted.
D/SPPClientService( 6283): PushLog.txt file is not deleted.
D/SPPClientService( 6283): ============PushLog. stop!
,I/SA      ( 5768): [SUR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOB6 PSS = 5.701607447389803  ]
,I/SA      ( 5768): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10265 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,I/ActivityManager(  748): Killing 5378:com.samsung.android.app.FileShareServer/u0a88 (adj 13): bgCount ##41
,E/SharedPreferencesImpl( 4903): Couldn't rename file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml to backup file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml.bak
,D/Mms/FreeMessageReceiver( 4972): onReceive, action : android.intent.action.PACKAGE_REMOVED
,I/TactileAssist(  748): enable value -1
,I/TactileAssist(  748): internal enable value -1
I/TactileAssist(  748): intensity value -1
I/TactileAssist(  748): saveAppList value true
,D/Mms/FreeMessageReceiverService( 4972): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
,D/Mms/FreeMessageReceiverService( 4972): onHandleIntent: ACTION_PACKAGE_REMOVED
I/TactileAssist(  748): List of disabled apps :
,D/SettingsProvider(  748): name = reading_mode_app_list
,D/Compatibility( 5790): onReceive() it will make start service
,D/Compatibility( 5790): onHandleIntent()
,D/Compatibility( 5790): intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10265, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/Compatibility( 5790): found: 2
D/Compatibility( 5790): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5790): skipping ResolveInfo{2da5fa3d com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5790): considering ResolveInfo{a185232 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5790): default: com.sec.android.app.soundalive.SAControlPanelActivity
,D/Compatibility( 5790): enabling receiver ResolveInfo{3a126b83 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,I/UpdateIcingCorporaServi( 1633): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,D/Compatibility( 5790): enabling receiver ResolveInfo{ebe100 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,W/ContextImpl( 5094): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:2991 
,D/Compatibility( 5790): enabling receiver ResolveInfo{8fcfd39 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/RCPManager( 5402):  in createShortcut() for packageName: com.example.hello userId0
,I/EventHub(  748): Removing device '/dev/input/event6' due to inotify event
,D/Compatibility( 5790): enabling receiver ResolveInfo{3bf55f7e com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,D/RCPManagerService(  748):  in createShortcut() for packageName: com.example.hello userId0
D/RCPManagerService(  748): queryAllProviders():  providerCallBack is not register for 0
,E/SQLiteLog( 5094): (28) failed to open "/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu" with flag (131138) and mode_t (0) due to error (2)
E/SQLiteLog( 5094): (28) failed to open "/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu" with flag (131072) and mode_t (0) due to error (2)
E/SQLiteLog( 5094): (14) cannot open file at line 32503 of [9491ba7d73]
E/SQLiteLog( 5094): (14) os_unix.c:32503: (2) open(/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu) - 
,E/SQLiteDatabase( 5094): Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
E/SQLiteDatabase( 5094): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 5094): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5094): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 5094): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 5094): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5094): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5094): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5094): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 5094): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 5094): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 5094): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteDatabase( 5094): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 5094): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5094): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5094): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
E/SQLiteDatabase( 5094): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:109)
E/SQLiteDatabase( 5094): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5094): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5094): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 5094): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 5094): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
W/System.err( 5094): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 5094): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
W/System.err( 5094): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
W/System.err( 5094): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err( 5094): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err( 5094): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err( 5094): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
W/System.err( 5094): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
W/System.err( 5094): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
W/System.err( 5094): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
W/System.err( 5094): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
W/System.err( 5094): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
W/System.err( 5094): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
W/System.err( 5094): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
W/System.err( 5094): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:109)
W/System.err( 5094): 	at andr,oid.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/System.err( 5094): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5094): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 5094): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SharedPreferencesImpl( 5790): Couldn't create directory for SharedPreferences file /data/data/com.sec.android.app.soundalive/shared_prefs/SoundAlive_Settings.xml
,E/SharedPreferencesImpl( 5790): Couldn't create directory for SharedPreferences file /data/data/com.sec.android.app.soundalive/shared_prefs/SoundAlive_Settings.xml
D/Compatibility( 5790): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,W/ContextImpl( 5831): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:55 android.app.ActivityThread.handleReceiver:2991 
,E/ActivityManager(  748): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  748): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  748): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  748): checkUser: useridlist=null, currentuser=0
,I/EventHub(  748): Removing device '/dev/input/event7' due to inotify event
,E/SQLiteLog( 1633): (10) POSIX Error : 9 SQLite Error : 3850
,E/SQLiteLog( 1633): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,F/libc    ( 1633): Fatal signal 7 (SIGBUS), code 2, fault addr 0xa041e4e1 in tid 6303 (IntentService[U)
,E/Zygote  ( 6306): MountEmulatedStorage()
,E/Zygote  ( 6306): v2
I/libpersona( 6306): KNOX_SDCARD checking this for 10121
I/libpersona( 6306): KNOX_SDCARD not a persona
,I/ActivityManager(  748): Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=6306 uid=10121 gids={50121, 9997, 1023} abi=armeabi-v7a
,I/EventHub(  748): Removing device '/dev/input/event8' due to inotify event
,I/SELinux ( 6306): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0_0002
,E/SELinux ( 6306): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/DEBUG   (  289): failed to create /data/tombstones: Read-only file system
I/DEBUG   (  289): failed to open /data/tombstones: No such file or directory
E/        (  289): !@dumpstate -k -t -z -d -o /data/log/dumpstate_app_native -m 1633
,E/ActivityManager(  748): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  748): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  748): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  748): checkUser: useridlist=null, currentuser=0
,I/dumpstate( 6313): begin
I/dumpstate( 6313): open lockfile failed No such file or directory
E/dumpstate( 6313): Cannot get free space size. So, skip dumpstate.
,I/EventHub(  748): Removing device '/dev/input/event9' due to inotify event
,E/Zygote  ( 6321): MountEmulatedStorage()
E/Zygote  ( 6321): v2
I/libpersona( 6321): KNOX_SDCARD checking this for 1000
I/libpersona( 6321): KNOX_SDCARD not a persona
,I/ActivityManager(  748): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6321 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/audit_log( 1865): File locking failed. error= Bad file number
,I/SELinux ( 6321): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0_0002
,E/SELinux ( 6321): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6306): TimaSignature is unavailable
,D/ActivityThread( 6306): Added TimaKeyStore provider
,I/EventHub(  748): Removing device '/dev/input/event10' due to inotify event
,D/TimaKeyStoreProvider( 6321): TimaSignature is unavailable
,D/ActivityThread( 6321): Added TimaKeyStore provider
,D/ResourcesManager( 6306): creating new AssetManager and set to /system/app/FilterProvider/FilterProvider.apk
,W/ContextImpl( 6306): Unable to create files subdir /data/user/0/com.samsung.android.provider.filterprovider/cache
E/ActivityThread( 6306): Unable to setupGraphicsSupport due to missing cache directory
,I/EventHub(  748): Removing device '/dev/input/event11' due to inotify event
,V/AudioPolicyManager(  298): stopInput() input 16
V/AudioPolicyManager(  298): releaseInput() 16
V/AudioPolicyManager(  298): closeInput(16)
,D/AndroidRuntime( 6306): Shutting down VM
,V/audio_hw_primary(  298): in_standby: enter
,E/AndroidRuntime( 6306): FATAL EXCEPTION: main
E/AndroidRuntime( 6306): Process: com.samsung.android.provider.filterprovider, PID: 6306
E/AndroidRuntime( 6306): java.lang.RuntimeException: Unable to get provider com.samsung.android.provider.filterprovider.FilterProvider: java.lang.ClassNotFoundException: Didn't find class "com.samsung.android.provider.filterprovider.FilterProvider" on path: DexPathList[[zip file "/system/app/FilterProvider/FilterProvider.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
E/AndroidRuntime( 6306): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5560)
E/AndroidRuntime( 6306): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5152)
E/AndroidRuntime( 6306): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5092)
E/AndroidRuntime( 6306): 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
E/AndroidRuntime( 6306): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
E/AndroidRuntime( 6306): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6306): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 6306): 	at android.app.ActivityThread.main(ActivityThread.java:5940)
E/AndroidRuntime( 6306): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 6306): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 6306): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1389)
E/AndroidRuntime( 6306): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1184)
E/AndroidRuntime( 6306): Caused by: java.lang.ClassNotFoundException: Didn't find class "com.samsung.android.provider.filterprovider.FilterProvider" on path: DexPathList[[zip file "/system/app/FilterProvider/FilterProvider.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
E/AndroidRuntime( 6306): 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
E/AndroidRuntime( 6306): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:511)
E/AndroidRuntime( 6306): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:469)
E/AndroidRuntime( 6306): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5545)
E/AndroidRuntime( 6306): 	... 11 more
E/AndroidRuntime( 6306): 	Suppressed: java.io.IOException: Zip archive '/system/app/FilterProvider/FilterProvider.apk' doesn't contain classes.dex (error msg: Entry not found)
E/AndroidRuntime( 6306): 		at dalvik.system.DexFile.openDexFileNative(Native Method)
E/AndroidRuntime( 6306): 		at dalvik.system.DexFile.openDexFile(DexFile.java:295)
E/AndroidRuntime( 6306): 		at dalvik.system.DexFile.<init>(DexFile.java:80)
E/AndroidRuntime( 6306): 		at dalvik.system.DexFile.<init>(DexFile.java:59)
E/AndroidRuntime( 6306): 		at dalvik.system.DexPathList.loadDexFile(DexPathList.java:262)
E/AndroidRuntime( 6306): 		at dalvik.system.DexPathList.makeDexElements(DexPathList.java:231)
E/AndroidRuntime( 6306): 		at dalvik.system.DexPathList.<init>(DexPathList.java:109)
E/AndroidRuntime( 6306): 		at dalvik.system.BaseDexClassLoader.<init>(BaseDexClassLoader.java:48)
E/AndroidRuntime( 6306): 		at dalvik.system.PathClassLoader.<init>(PathClassLoader.java:65)
E/AndroidRuntime( 6306): 		at dalvik.system.PathClassLoader.openArtFile(PathClassLoader.java:74)
E/AndroidRuntime( 6306): 		at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 6306): 		at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 6306): 		at android.app.ApplicationLoaders.openArtFile(ApplicationLoaders.java:63)
E/AndroidRuntime( 6306): 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:119)
E/AndroidRuntime( 6306): 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:46)
E/AndroidRuntime( 6306): 		at android.app.LoadedApk.getClassLoader(LoadedApk.java:415)
E/AndroidRuntime( 6306): 		at android.app.LoadedApk.makeApplication(LoadedApk.java:615)
E/AndroidRuntime( 6306): 		at android.app.ActivityThread.handleBindAppl,ication(ActivityThread.java:5084)
E/AndroidRuntime( 6306): 		... 9 more
E/AndroidRuntime( 6306): 	Caused by: java.io.IOException: Failed to open oat file from dex location '/system/app/FilterProvider/FilterProvider.apk'
E/AndroidRuntime( 6306): 		... 27 more
E/AndroidRuntime( 6306): 	Caused by: java.io.IOException: Failed to open oat file from /system/app/FilterProvider/arm/FilterProvider.odex (error Failed to open oat filename for reading: No such file or directory) (no dalvik_cache availible) and relocation failed.
E/AndroidRuntime( 6306): 		... 27 more
E/AndroidRuntime( 6306): 	Caused by: java.io.IOException: 
E/AndroidRuntime( 6306): 		... 27 more
E/AndroidRuntime( 6306): 	Suppressed: java.lang.ClassNotFoundException: com.samsung.android.provider.filterprovider.FilterProvider
E/AndroidRuntime( 6306): 		at java.lang.Class.classForName(Native Method)
E/AndroidRuntime( 6306): 		at java.lang.BootClassLoader.findClass(ClassLoader.java:781)
E/AndroidRuntime( 6306): 		at java.lang.BootClassLoader.loadClass(ClassLoader.java:841)
E/AndroidRuntime( 6306): 		at java.lang.ClassLoader.loadClass(ClassLoader.java:504)
E/AndroidRuntime( 6306): 		... 13 more
E/AndroidRuntime( 6306): 	Caused by: java.lang.NoClassDefFoundError: Class not found using the boot class loader; no stack available
D/ResourcesManager( 6321): creating new AssetManager and set to /system/app/KeyChain/KeyChain.apk
W/ContextImpl( 6321): Unable to create files subdir /data/data/com.android.keychain/cache
E/ActivityThread( 6321): Unable to setupGraphicsSupport due to missing cache directory
D/AndroidRuntime( 6321): Shutting down VM
E/AndroidRuntime( 6321): FATAL EXCEPTION: main
E/AndroidRuntime( 6321): Process: com.android.keychain, PID: 6321
E/AndroidRuntime( 6321): java.lang.RuntimeException: Unable to instantiate receiver com.android.keychain.KeyChainBroadcastReceiver: java.lang.ClassNotFoundException: Didn't find class "com.android.keychain.KeyChainBroadcastReceiver" on path: DexPathList[[zip file "/system/app/KeyChain/KeyChain.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
E/AndroidRuntime( 6321): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2972)
E/AndroidRuntime( 6321): 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
E/AndroidRuntime( 6321): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
E/AndroidRuntime( 6321): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6321): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 6321): 	at android.app.ActivityThread.main(ActivityThread.java:5940)
E/AndroidRuntime( 6321): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 6321): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 6321): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1389)
E/AndroidRuntime( 6321): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1184)
E/AndroidRuntime( 6321): Caused by: java.lang.ClassNotFoundException: Didn't find class "com.android.keychain.KeyChainBroadcastReceiver" on path: DexPathList[[zip file "/system/app/KeyChain/KeyChain.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
E/AndroidRuntime( 6321): 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
E/AndroidRuntime( 6321): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:511)
E/AndroidRuntime( 6321): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:469)
E/AndroidRuntime( 6321): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2967)
E/AndroidRuntime( 6321): 	... 9 more
E/AndroidRuntime( 6321): 	Suppressed: java.io.IOException: Zip archive '/system/app/KeyChain/KeyChain.apk' doesn't contain classes.dex (error msg: Entry not found)
E/AndroidRuntime( 6321): 		at dalvik.system.DexFile.openDexFileNative(Native Method)
E/AndroidRuntime( 6321): 		at dalvik.system.DexFile.openDexFile(DexFile.java:295)
E/AndroidRuntime( 6321): 		at dalvik.system.DexFile.<init>(DexFile.java:80)
E/AndroidRuntime( 6321): 		at dalvik.system.DexFile.<init>(DexFile.java:59)
E/AndroidRuntime( 6321): 		at dalvik.system.DexPathList.loadDexFile(DexPathList.java:262)
E/AndroidRuntime( 6321): 		at dalvik.system.DexPathList.makeDexElements(DexPathList.java:231)
E/AndroidRuntime( 6321): 		at dalvik.system.DexPathList.<init>(DexPathList.java:109)
E/AndroidRuntime( 6321): 		at dalvik.system.BaseDexClassLoader.<init>(BaseDexClassLoader.java:48)
E/AndroidRuntime( 6321): 		at dalvik.system.PathClassLoader.<init>(PathClassLoader.java:65)
E/AndroidRuntime( 6321): 		at dalvik.system.PathClassLoader.openArtFile(PathClassLoader.java:74)
E/AndroidRuntime( 6321): 		at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 6321): 		at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 6321): 		at android.app.ApplicationLoaders.openArtFile(ApplicationLoaders.java:63)
E/AndroidRuntime( 6321): 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:119)
E/AndroidRuntime( 6321): 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:46)
E/AndroidRuntime( 6321): 		at android.app.LoadedApk.getClassLoader(LoadedApk.java:415)
E/AndroidRuntime( 6321): 		at android.app.LoadedApk.makeApplication(LoadedApk.java:615)
E/AndroidRuntime( 6321): 		at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5084)
E/AndroidRuntime( 6321): 		at android.app.ActivityThread.access$1600(ActivityThread.java:177)
E/AndroidRuntime( 6321): 		at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
E/AndroidRuntime( 6321): 		... 7 more
E/AndroidRuntime( 6321): 	Caused by: java.io.IOException: Failed to open oat file from dex location '/system/app/KeyChain/KeyChain.apk'
E/AndroidRuntime( 6321): 		... 27 more
E/AndroidRuntime( 6321): 	Caused by: java.io.IOException: Failed to open oat file from /system/app/KeyChain/arm/KeyChain.odex (error Failed to open oat filename for reading: No such file or directory) (no dalvik_cache availible) and relocation failed.
E/AndroidRuntime( 6321): 		... 27 more
E/AndroidRuntime( 6321): 	Caused by: java.io.IOException: 
E/AndroidRuntime( 6321): 		... 27 more
E/AndroidRuntime( 6321): 	Suppressed: java.lang.ClassNotFoundException: com.android.keychain.KeyChainBroadcastReceiver
E/AndroidRuntime( 6321): 		at java.lang.Class.classForName(Native Method)
E/AndroidRuntime( 6321): 		at java.lang.BootClassLoader.findClass(ClassLoader.java:781)
E/AndroidRuntime( 6321): 		at java.lang.BootClassLoader.loadClass(ClassLoader.java:841)
E/AndroidRuntime( 6321): 		at java.lang.ClassLoader.loadClass(ClassLoader.java:504)
E/AndroidRuntime( 6321): 		... 11 more
E/AndroidRuntime( 6321): 	Caused by: java.lang.NoClassDefFoundError: Class not found using the boot class loader; no stack available
I/Zygote  (  343): Process 1633 exited due to signal (7)
,V/audio_hw_primary(  298): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  298): disable_audio_route: enter: usecase(7)
V/audio_hw_primary(  298): disable_audio_route: reset mixer path: audio-record
D/audio_route(  298): ++++ audio_route_update_mixer ==============
D/audio_route(  298): Setting mixer control: MultiMedia1 Mixer SLIM_0_TX
D/audio_route(  298): Setting mixer control: value: 0
I/ActivityManager(  748): Process com.google.android.googlequicksearchbox:search (pid 1633)(adj 1) has died(511,1362)
I/EventHub(  748): Removing device '/dev/input/event12' due to inotify event
D/audio_route(  298): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  298): disable_audio_route: exit
V/audio_hw_primary(  298): disable_snd_device: snd_device(128: vr-main-mic)
D/audio_route(  298): ++++ audio_route_update_mixer ==============
D/audio_route(  298): Setting mixer control: ADC1 Volume
D/audio_route(  298): Setting mixer control: value: 0
D/audio_route(  298): Setting mixer control: DEC6 Volume
D/audio_route(  298): Setting mixer control: value: 0
W/ActivityManager(  748): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.hotword.service.HotwordService in 1000ms
D/audio_route(  298): Setting mixer control: SLIM TX7 MUX, value: 0
W/ActivityManager(  748): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 10999ms
W/ActivityManager(  748): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService in 10999ms
D/audio_route(  298): Setting mixer control: AIF1_CAP Mixer SLIM TX7
D/audio_route(  298): Setting mixer control: value: 0
D/audio_route(  298): Setting mixer control: DEC6 MUX, value: 0
D/audio_route(  298): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  298): stop_input_stream: exit: status(0)
V/audio_hw_primary(  298): in_standby: exit:  status(0)
V/audio_hw_primary(  298): adev_close_input_stream
V/audio_hw_primary(  298): in_standby: enter
V/audio_hw_primary(  298): in_standby: exit:  status(0)
E/audio_hw_primary(  298): adev_close_input_stream, set jack_in to null
V/AudioPolicyManager(  298): releaseInput() exit
V/ApplicationPolicy(  748): isApplicationStateBlocked userId 0 pkgname com.samsung.android.provider.filterprovider
V/ApplicationPolicy(  748): isApplicationStateBlocked userId 0 pkgname com.android.keychain
E/AndroidRuntime(  748): *** FATAL EXCEPTION IN SYSTEM PROCESS: Error dump: system_app_crash
E/AndroidRuntime(  748): java.lang.IllegalArgumentException: Invalid path: /data/system/dropbox
E/AndroidRuntime(  748): 	at android.os.StatFs.doStat(StatFs.java:46)
E/AndroidRuntime(  748): 	at android.os.StatFs.restat(StatFs.java:56)
E/AndroidRuntime(  748): 	at com.android.server.DropBoxManagerService.trimToFit(DropBoxManagerService.java:726)
E/AndroidRuntime(  748): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:188)
E/AndroidRuntime(  748): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/AndroidRuntime(  748): 	at com.android.server.am.ActivityManagerService$23.run(ActivityManagerService.java:14833)
E/AndroidRuntime(  748): Caused by: android.system.ErrnoException: statvfs failed: ENOENT (No such file or directory)
E/AndroidRuntime(  748): 	at libcore.io.Posix.statvfs(Native Method)
E/AndroidRuntime(  748): 	at libcore.io.BlockGuardOs.statvfs(BlockGuardOs.java:298)
E/AndroidRuntime(  748): 	at android.system.Os.statvfs(Os.java:473)
E/AndroidRuntime(  748): 	at android.os.StatFs.doStat(StatFs.java:44)
E/AndroidRuntime(  748): 	... 5 more
D/ResourcesManager(  748): creating new AssetManager and set to /system/app/FilterProvider/FilterProvider.apk
I/Process (  748): Sending signal. PID: 748 SIG: 9
,E/SMD     (  293): DCD ON
,E/installd(  301): eof
E/installd(  301): failed to read size
I/installd(  301): closing connection
,W/Sensors ( 1789): sensorservice died [0xaf018640]
,W/Sensors ( 1422): sensorservice died [0xaf0d8240]
I/SurfaceFlinger(  257): restart the boot-animation @ binderDied
,W/AudioFlinger(  298): power manager service died !!!
W/AudioCache(  298): clearPowerManager -mWakeLockCount is 0, failed to releaseWakeLock function
I/SurfaceFlinger(  257): id=2 Removed GocusedStac (4/8)
,W/Sensors ( 1447): sensorservice died [0xaf0fa300]
,W/Sensors ( 1401): sensorservice died [0xaf0aba00]
,W/Sensors ( 1184): sensorservice died [0xaf03a200]
,W/Sensors ( 1473): sensorservice died [0xaf034340]
,E/WifiManager( 1184): Channel connection lost
,E/WifiManager( 1544): Channel connection lost
,E/WifiManager( 1422): Channel connection lost
,I/SurfaceFlinger(  257): id=3 Removed EimLayer (0/7)
,I/SurfaceFlinger(  257): id=4 Removed EimLayer (0/6)
I/SurfaceFlinger(  257): id=10 Removed EimLayer (0/5)
E/WifiManager( 1318): Channel connection lost
I/SurfaceFlinger(  257): id=11 Removed EimLayer (2/4)
I/SurfaceFlinger(  257): id=2 Removed GocusedStac (-2/4)
I/SurfaceFlinger(  257): id=3 Removed EimLayer (-2/4)
,I/SurfaceFlinger(  257): id=4 Removed EimLayer (-2/4)
I/SurfaceFlinger(  257): id=10 Removed EimLayer (-2/4)
I/SurfaceFlinger(  257): id=11 Removed EimLayer (-2/4)
,I/ServiceManager(  255): service 'input_method' died
I/ServiceManager(  255): service 'accessibility' died
I/ServiceManager(  255): service 'motion_recognition' died
I/ServiceManager(  255): service 'connectivity' died
I/ServiceManager(  255): service 'sb_service' died
I/ServiceManager(  255): service 'servicediscovery' died
I/ServiceManager(  255): service 'updatelock' died
I/ServiceManager(  255): service 'notification' died
I/ServiceManager(  255): service 'devicestoragemonitor' died
I/ServiceManager(  255): service 'location' died
I/ServiceManager(  255): service 'country_detector' died
I/ServiceManager(  255): service 'search' died
I/ServiceManager(  255): service 'dropbox' died
I/ServiceManager(  255): service 'wallpaper' died
I/ServiceManager(  255): service 'wifi' died
I/ServiceManager(  255): service 'msapwifi' died
I/ServiceManager(  255): service 'wifiscanner' died
I/ServiceManager(  255): service 'rttmanager' died
I/ServiceManager(  255): service 'wifi_policy' died
I/ServiceManager(  255): service 'phone_restriction_policy' died
I/ServiceManager(  255): service 'remoteinjection' died
I/ServiceManager(  255): service 'mum_container_policy' died
I/ServiceManager(  255): service 'enterprise_billing_policy' died
I/ServiceManager(  255): service 'knox_timakeystore_policy' died
I/ServiceManager(  255): service 'enterprise_policy' died
I/ServiceManager(  255): service 'device_policy' died
I/ServiceManager(  255): service 'harmony_eas_service' died
I/ServiceManager(  255): service 'sdp' died
I/ServiceManager(  255): service 'log_manager_service' died
I/ServiceManager(  255): service 'context_aware' died
I/ServiceManager(  255): service 'scontext' died
I/ServiceManager(  255): service 'barbeam' died
I/ServiceManager(  255): service 'multiwindow_facade' died
I/ServiceManager(  255): service 'window' died
I/ServiceManager(  255): service 'input' died
I/ServiceManager(  255): service 'tactileassist' died
I/ServiceManager(  255): service 'bluetooth_manager' died
I/ServiceManager(  255): service 'bluetooth_secure_mode_manager' died
I/ServiceManager(  255): service 'rcp' died
I/ServiceManager(  255): service 'cover' died
I/ServiceManager(  255): service 'mount' died
I/ServiceManager(  255): service 'lock_settings' died
I/ServiceManager(  255): service 'audio' died
I/ServiceManager(  255): service 'DockObserver' died
I/ServiceManager(  255): service 'usb' died
I/ServiceManager(  255): service 'serial' died
I/ServiceManager(  255): service 'uimode' died
I/ServiceManager(  255): service 'jobscheduler' died
I/ServiceManager(  255): service 'statusbar' died
I/ServiceManager(  255): service 'clipboard' died
I/ServiceManager(  255): service 'clipboardEx' died
I/ServiceManager(  255): service 'network_management' died
I/ServiceManager(  255): service 'ABTPersistenceService' died
I/ServiceManager(  255): service 'textservices' died
I/ServiceManager(  255): service 'network_score' died
I/ServiceManager(  255): service 'netstats' died
I/ServiceManager(  255): service 'netpolicy' died
I/ServiceManager(  255): service 'wifip2p' died
E/ActivityThread( 5831): Failed to find provider info for com.samsung.android.provider.filterprovider
I/ServiceManager(  255): service 'backup' died
I/ServiceManager(  255): service 'appwidget' died
I/ServiceManager(  255): service 'voiceinteraction' died
E/ActivityThread( 5831): Failed to find provider info for com.samsung.android.provider.filterprovider
I/ServiceManager(  255): service 'SecExternalDisplayService' died
I/ServiceManager(  255): service 'diskstats' died
I/ServiceManager(  255): service 'mDNIe' died
I/ServiceManager(  255): service 'spengestureservice' died
I/ServiceManager(  255): service 'quickconnect' died
I/ServiceManager(  255): service 'samplingprofiler' died
I/ServiceManager(  255): service 'commontime_management' died
I/ServiceManager(  255): service 'dreams' died
I/ServiceManager(  255): service 'assetatlas' died
I/ServiceManager(  255): service 'print' died
I/ServiceManager(  255): service 'restrictions' died
I,/ServiceManager(  255): service 'media_session' died
I/ServiceManager(  255): service 'media_router' died
I/ServiceManager(  255): service 'trust' died
I/ServiceManager(  255): service 'fingerprint' died
I/ServiceManager(  255): service 'sec_analytics' died
I/ServiceManager(  255): service 'launcherapps' died
I/ServiceManager(  255): service 'voip' died
I/ServiceManager(  255): service 'media_projection' died
I/ServiceManager(  255): service 'imms' died
I/ServiceManager(  255): service 'webviewupdate' died
I/ServiceManager(  255): service 'procstats' died
I/ServiceManager(  255): service 'SEAMService' died
I/ServiceManager(  255): service 'persona' died
I/ServiceManager(  255): service 'account' died
I/ServiceManager(  255): service 'content' died
I/ServiceManager(  255): service 'DirEncryptService' died
I/ServiceManager(  255): service 'ReactiveService' died
I/ServiceManager(  255): service 'CustomFrequencyManagerService' died
I/ServiceManager(  255): service 'samsung.smartfaceservice' died
I/ServiceManager(  255): service 'consumer_ir' died
I/ServiceManager(  255): service 'alarm' died
I/ServiceManager(  255): service 'sedenial' died
I/ServiceManager(  255): service 'vibrator' died
I/ServiceManager(  255): service 'tima' died
I/ServiceManager(  255): service 'cepproxyks' died
I/ServiceManager(  255): service 'enterprise_license_policy' died
I/ServiceManager(  255): service 'application_policy' died
I/ServiceManager(  255): service 'battery' died
I/ServiceManager(  255): service 'meminfo' died
I/ServiceManager(  255): service 'dbinfo' died
I/ServiceManager(  255): service 'usagestats' died
I/ServiceManager(  255): service 'scheduling_policy' died
I/ServiceManager(  255): service 'telephony.registry' died
I/ServiceManager(  255): service 'entropy' died
I/ServiceManager(  255): service 'package' died
I/ServiceManager(  255): service 'gfxinfo' died
E/AndroidRuntime( 6306): Error reporting crash
E/AndroidRuntime( 6306): android.os.DeadObjectException
E/AndroidRuntime( 6306): 	at android.os.BinderProxy.transactNative(Native Method)
E/AndroidRuntime( 6306): 	at android.os.BinderProxy.transact(Binder.java:496)
E/AndroidRuntime( 6306): 	at android.app.ActivityManagerProxy.handleApplicationCrash(ActivityManagerNative.java:4656)
E/AndroidRuntime( 6306): 	at com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException(RuntimeInit.java:95)
E/AndroidRuntime( 6306): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
E/AndroidRuntime( 6306): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
I/ServiceManager(  255): service 'activity' died
I/ServiceManager(  255): service 'permission' died
I/ServiceManager(  255): service 'hardware' died
I/ServiceManager(  255): service 'edmnativehelper' died
I/Process ( 6306): Sending signal. PID: 6306 SIG: 9
I/ServiceManager(  255): service 'user' died
I/ServiceManager(  255): service 'cpuinfo' died
I/ServiceManager(  255): service 'mdm.remotedesktop' died
I/ServiceManager(  255): service 'sensorservice' died
I/ServiceManager(  255): service 'batterystats' died
I/ServiceManager(  255): service 'appops' died
I/ServiceManager(  255): service 'power' died
I/ServiceManager(  255): service 'display' died
,I/ServiceManager(  255): service 'persona_policy' died
E/AndroidRuntime( 5831): FATAL EXCEPTION: FilterPackageServiceHandler
E/AndroidRuntime( 5831): Process: com.samsung.android.app.filterinstaller, PID: 5831
E/AndroidRuntime( 5831): java.lang.IllegalArgumentException: Unknown URL content://com.samsung.android.provider.filterprovider/packages/com.example.hello
E/AndroidRuntime( 5831): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/AndroidRuntime( 5831): 	at com.samsung.android.app.filterinstaller.FilterUninstaller.removeFromDB(FilterUninstaller.java:52)
E/AndroidRuntime( 5831): 	at com.samsung.android.app.filterinstaller.FilterUninstaller.uninstallFilters(FilterUninstaller.java:43)
E/AndroidRuntime( 5831): 	at com.samsung.android.app.filterinstaller.FilterPackageService$ServiceHandler.handleMessage(FilterPackageService.java:149)
E/AndroidRuntime( 5831): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5831): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 5831): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/SurfaceFlinger(  257): Set power mode=2, type=0 flinger=0xb6a62000
D/SurfaceFlinger(  257): Screen type=0 is already mode=2
,E/WifiManager( 1473): Channel connection lost
W/Sensors ( 1910): sensorservice died [0xaf0d9a40]
W/Sensors ( 4903): sensorservice died [0xaf0cf280]
E/AndroidRuntime( 5831): Error reporting crash
E/AndroidRuntime( 5831): android.os.DeadObjectException
E/AndroidRuntime( 5831): 	at android.os.BinderProxy.transactNative(Native Method)
E/AndroidRuntime( 5831): 	at android.os.BinderProxy.transact(Binder.java:496)
E/AndroidRuntime( 5831): 	at android.app.ActivityManagerProxy.handleApplicationCrash(ActivityManagerNative.java:4656)
E/AndroidRuntime( 5831): 	at com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException(RuntimeInit.java:95)
E/AndroidRuntime( 5831): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
E/AndroidRuntime( 5831): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
,I/Process ( 5831): Sending signal. PID: 5831 SIG: 9
,E/AndroidRuntime( 6321): Error reporting crash
E/AndroidRuntime( 6321): android.os.DeadObjectException
E/AndroidRuntime( 6321): 	at android.os.BinderProxy.transactNative(Native Method)
E/AndroidRuntime( 6321): 	at android.os.BinderProxy.transact(Binder.java:496)
E/AndroidRuntime( 6321): 	at android.app.ActivityManagerProxy.handleApplicationCrash(ActivityManagerNative.java:4656)
E/AndroidRuntime( 6321): 	at com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException(RuntimeInit.java:95)
E/AndroidRuntime( 6321): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
E/AndroidRuntime( 6321): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
,I/Process ( 6321): Sending signal. PID: 6321 SIG: 9
,I/SurfaceFlinger(  257): id=5 Removed JmageWallpa (0/3)
,I/SurfaceFlinger(  257): id=5 Removed JmageWallpa (-2/3)
I/SurfaceFlinger(  257): id=7 Removed TtatusBar (1/2)
I/SurfaceFlinger(  257): id=9 Removed Ieads Up (1/1)
I/SurfaceFlinger(  257): id=14 Removed Mauncher (0/0)
I/SurfaceFlinger(  257): id=7 Removed TtatusBar (-2/0)
I/SurfaceFlinger(  257): id=14 Removed Mauncher (-2/0)
I/SurfaceFlinger(  257): id=9 Removed Ieads Up (-2/0)
,I/SurfaceFlinger(  257): Disp[0] Orientation 0=>0
,E/qdoverlay(  257): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
E/qdoverlay(  257): MdpCtrl close error in unset
,I/ServiceManager(  358): Waiting for service AtCmdFwd...
,I/qdhwcomposer(  257): handle_blank_event: dpy:0 panel power state: 0
,E/qdoverlay(  257): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted,
,E/qdoverlay(  257): MdpCtrl close error in unset
E/qdoverlay(  257): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
,E/qdoverlay(  257): MdpCtrl close error in unset
E/qdoverlay(  257): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
E/qdoverlay(  257): MdpCtrl close error in unset

```
