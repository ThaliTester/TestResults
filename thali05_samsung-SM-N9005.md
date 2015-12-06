#### Test 50242285576d0b0_thali05_samsung-SM-N9005 Logs


```
--------- beginning of main
D/Finsky  ( 3377): [450] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 3377): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/AndroidRuntime( 6075): 
D/AndroidRuntime( 6075): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6075): CheckJNI is OFF
D/AndroidRuntime( 6075): readGMSProperty: start
D/AndroidRuntime( 6075): readGMSProperty: already setted!!
D/AndroidRuntime( 6075): readGMSProperty: end
D/AndroidRuntime( 6075): addProductProperty: start
E/AffinityControl( 6075): AffinityControl: registerfunction enter
D/AndroidRuntime( 6075): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  883): inState():  stateMachine is null !!
I/PersonaManagerService(  883): PersonaId don't exist
I/ActivityManager(  883): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.example.hello
--------- beginning of system
I/ActivityManager(  883): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  883): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
D/CustomFrequencyManagerService(  883): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 883  pkgName : ACTIVITY_RESUME_BOOSTER@7
W/ActivityManager(  883): mDVFSHelper.acquire()
I/SurfaceFlinger(  254): id=10 createSurf (16x16),-1 flag=20004, EimLayer
I/SurfaceFlinger(  254): id=11 createSurf (16x16),-1 flag=20004, EimLayer
D/FocusedStackFrame(  883): Set to : 0
D/Launcher.HomeView( 1451): onPause
D/Launcher( 1451): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 40000000
D/AndroidRuntime( 6075): Shutting down VM
V/TaskCloserActivity( 5605): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
I/SurfaceFlinger(  254): id=12 createSurf (1x1),1 flag=404, iello
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
D/PointerIcon(  883): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  883): setMouseCustomIcon IconType is same.101
D/PointerIcon(  883): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  883): setHoveringSpenCustomIcon IconType is same.1
E/Zygote  ( 6102): MountEmulatedStorage()
E/Zygote  ( 6102): v2
I/libpersona( 6102): KNOX_SDCARD checking this for 10265
I/libpersona( 6102): KNOX_SDCARD not a persona
I/ActivityManager(  883): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=6102 uid=10265 gids={50265, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/SELinux ( 6102): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6102): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6102): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/StatusBarManagerService(  883): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
V/ActivityThread( 1451): updateVisibility : ActivityRecord{1e056355 token=android.os.BinderProxy@28a169f7 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
I/MicrophoneInputStream( 1599): mic_close gfk@23af5672
V/AudioPolicyManager(  302): stopInput() input 14
V/AudioPolicyManager(  302): releaseInput() 14
V/AudioPolicyManager(  302): closeInput(14)
I/HotwordRecognitionRnr( 1599): Hotword detection finished
I/HotwordRecognitionRnr( 1599): Stopping hotword detection.
V/audio_hw_primary(  302): in_standby: enter
D/TimaKeyStoreProvider( 6102): TimaSignature is unavailable
D/ActivityThread( 6102): Added TimaKeyStore provider
V/WindowOrientationListener(  883): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  883): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  883): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  883): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  883): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/ActivityManager(  883): Display changed displayId=0
D/Launcher.HomeView( 1451): onStop
V/ActivityThread( 1451): updateVisibility : ActivityRecord{1e056355 token=android.os.BinderProxy@28a169f7 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1754): [237392/8] Surface widget pause on instance = 1
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1754): [237392/8] Surface widget visibility changed visibility = false on instance = 1
D/accuweather( 1754): [Accuweather J]>>> SWW:212 [0:0] [SWW] onPause : rI = 1
D/accuweather( 1754): [Accuweather J]>>> SWW:222 [0:0] [SWW] onPause : size = 0
D/accuweather( 1754): [Accuweather J]>>> SWW:634 [0:0]  unRegisterTTReceiver !! 
D/SurfaceWidgetView( 1451): destroyHardwareResources():679231780
D/StatusBarManagerService(  883): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/ConnectivityService(  883): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
V/audio_hw_primary(  302): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  302): disable_audio_route: enter: usecase(7)
V/audio_hw_primary(  302): disable_audio_route: reset mixer path: audio-record
D/audio_route(  302): ++++ audio_route_update_mixer ==============
D/audio_route(  302): Setting mixer control: MultiMedia1 Mixer SLIM_0_TX
D/audio_route(  302): Setting mixer control: value: 0
D/audio_route(  302): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  302): disable_audio_route: exit
V/audio_hw_primary(  302): disable_snd_device: snd_device(128: vr-main-mic)
D/audio_route(  302): ++++ audio_route_update_mixer ==============
D/audio_route(  302): Setting mixer control: ADC1 Volume
D/audio_route(  302): Setting mixer control: value: 0
D/audio_route(  302): Setting mixer control: DEC6 Volume
D/audio_route(  302): Setting mixer control: value: 0
D/audio_route(  302): Setting mixer control: SLIM TX7 MUX, value: 0
D/audio_route(  302): Setting mixer control: AIF1_CAP Mixer SLIM TX7
D/audio_route(  302): Setting mixer control: value: 0
D/audio_route(  302): Setting mixer control: DEC6 MUX, value: 0
D/audio_route(  302): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  302): stop_input_stream: exit: status(0)
V/audio_hw_primary(  302): in_standby: exit:  status(0)
V/audio_hw_primary(  302): adev_close_input_stream
V/audio_hw_primary(  302): in_standby: enter
V/audio_hw_primary(  302): in_standby: exit:  status(0)
E/audio_hw_primary(  302): adev_close_input_stream, set jack_in to null
V/AudioPolicyManager(  302): releaseInput() exit
D/accuweather( 1754): [Accuweather J]>>> WCD:1431 [0:0] cARH()
D/accuweather( 1754): [Accuweather J]>>> WCD:549 [0:0]  onPause 
D/accuweather( 1754): [Accuweather J]>>> WR:475 [0:0] onPause : 1
D/accuweather( 1754): [Accuweather J]>>> SWW:540 [0:0] =================== , pause :1
D/ResourcesManager( 6102): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
D/Launcher( 1451): onTrimMemory. Level: 20
D/SurfaceWidgetView( 1451): destroyHardwareResources():679231780
,I/WebViewFactory( 6102): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
D/ResourcesManager( 6102): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader( 6102): Loading: webviewchromium
I/LibraryLoader( 6102): Time to load native libraries: 5 ms (timestamps 3219-3224)
I/LibraryLoader( 6102): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6102): Binding Chromium to main looper Looper (main, tid 1) {8d62cde}
I/LibraryLoader( 6102): Expected native library version number "",actual native library version number ""
I/chromium( 6102): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6102): Initializing chromium process, renderers=0
W/art     ( 6102): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6102): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
W/chromium( 6102): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6102): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46780 len=2953
I/chromium( 6102): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229536 len:643667
D/BluetoothAdapter( 6102): 378597055: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 6102): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 6102): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6102): Build Date: 11/19/14 Wed
I/Adreno-EGL( 6102): Local Branch: mybranch5813579
I/Adreno-EGL( 6102): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 6102): Local Patches: NONE
I/Adreno-EGL( 6102): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
W/chromium( 6102): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 6102): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 6102): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6102): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6102): CordovaWebView is running on device made by: samsung
W/art     ( 6102): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6102): Attempt to remove local handle scope entry from IRT, ignoring
D/Activity( 6102): performCreate Call secproduct feature valuefalse
D/Activity( 6102): performCreate Call debug elastic valuetrue
D/OpenGLRenderer( 6102): Render dirty regions requested: true
D/Atlas   ( 6102): Validating map...
D/ActivityManager(  883): post active user change for 0
D/KnoxTimeoutHandler(  883): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  883): handleActiveUserChange for user 0
I/SurfaceFlinger(  254): id=13 createSurf (1x1),1 flag=404, NainActivit
D/PointerIcon(  883): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  883): setMouseCustomIcon IconType is same.101
D/PointerIcon(  883): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  883): setHoveringSpenCustomIcon IconType is same.1
I/OpenGLRenderer( 6102): Initialized EGL, version 1.4
I/OpenGLRenderer( 6102): HWUI protection enabled for context ,  &this =0xaf217b28 ,&mEglDisplay = 1 , &mEglConfig = 8 
D/OpenGLRenderer( 6102): Enabling debug mode 0
D/InputMethodManagerService(  883): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/ContextImpl(  883): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/Timeline( 6102): Timeline: Activity_idle id: android.os.BinderProxy@1cd5898e time:73545
I/ActivityManager(  883): Displayed com.example.hello/.MainActivity: +563ms
W/ContextImpl(  883): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/SamsungIME( 1716): getCurrentCandidateView
I/SurfaceFlinger(  254): id=6 Removed Mauncher (4/10)
I/SurfaceFlinger(  254): id=6 Removed Mauncher (-2/10)
I/chromium( 6102): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
E/AndroidProtocolHandler( 6102): Unable to open asset URL: file:///android_asset/www/jxcore.js
D/SamsungIME( 1716): Dismiss ExpandCandiate
D/JsMessageQueue( 6102): Set native->JS mode to OnlineEventsBridgeMode
I/chromium( 6102): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6102): 
I/SamsungIME( 1716): getDebugLevel  : 0x4f4c
I/SamsungIME( 1716): getDebugLevel  : 0x4f4c
I/SamsungIME( 1716): KeybaordView init() : load resources
D/jxcore_app_log( 6102): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1258378624
D/JX-Cordova( 6102): jxcore cordova android initializing
I/SurfaceFlinger(  254): id=12 Removed iello (7/9)
I/SurfaceFlinger(  254): id=12 Removed iello (-2/9)
I/SamsungIME( 1716): getCurrentKeyboard
I/SamsungIME( 1716): getTextKeyboard
D/SamsungIME( 1716): [SwiftkeyWrapper] currentLangauge : 1701729619
W/jxcore-log( 6102): Initializing JXcore engine
W/jxcore-log( 6102): JXcore engine is ready
W/jxcore-log( 6102): Starting JXcore engine
D/CustomFrequencyManagerService(  883): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 883  tag : ACTIVITY_RESUME_BOOSTER@7
D/CustomFrequencyManagerService(  883): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 883  pkgName : ACTIVITY_RESUME_BOOSTER@11
W/ActivityManager(  883): mDVFSHelper.release()
I/Timeline(  883): Timeline: Activity_windows_visible id: ActivityRecord{36937757 u0 com.example.hello/.MainActivity t2} time:73853
E/auditd  ( 1802): In denial and Property audit_ondenial is set to 1 
D/SecurityLogAgent:SEDenialService(  883): Got Modify Event and sending Denial Intent foraudit.log
W/ContextImpl(  883): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
D/SecurityLogAgent:SEDenialService(  883): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6161): MountEmulatedStorage()
E/Zygote  ( 6161): v2
I/libpersona( 6161): KNOX_SDCARD checking this for 1000
I/libpersona( 6161): KNOX_SDCARD not a persona
I/ActivityManager(  883): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=6161 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/art     (  347): Explicit concurrent mark sweep GC freed 8733(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 308us total 15.086ms
I/art     (  347): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 308us total 9.749ms
I/art     (  347): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 275us total 9.958ms
W/jxcore-log( 6102): Platform android
W/jxcore-log( 6102): 
W/jxcore-log( 6102): Process ARCH arm
W/jxcore-log( 6102): 
I/SELinux ( 6161): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6161): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6161): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 6161): TimaSignature is unavailable
D/ActivityThread( 6161): Added TimaKeyStore provider
I/jxcore-log( 6102): JXcore Cordova bridge is ready!
I/jxcore-log( 6102): 
W/jxcore-log( 6102): JXcore engine is started
D/ResourcesManager( 6161): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
D/SecurityLogAgent( 6161):  SeDenialReceiver : Intent Received : android.intent.action.DENIAL_NOTIFICATION
D/SecurityLogAgent( 6161):  SeDenialReceiver : File path = null
I/ActivityManager(  883): Killing 5306:com.sec.android.diagmonagent/1000 (adj 15): bgCount ##41
E/jxcore-log( 6102): >> samsung-SM-N9005
E/jxcore-log( 6102): 
I/jxcore-log( 6102): Total memory 2971471872
I/jxcore-log( 6102): 
I/jxcore-log( 6102): Free memory 416321536
I/jxcore-log( 6102): 
I/jxcore-log( 6102): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6102): 
I/jxcore-log( 6102): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6102): 
I/jxcore-log( 6102): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 6102): 
I/jxcore-log( 6102): Size 1080 1920
I/jxcore-log( 6102): 
I/jxcore-log( 6102): Screen Brightness 162
I/jxcore-log( 6102): 
E/jxcore-log( 6102): Dummy Error Log.
E/jxcore-log( 6102): 
D/CustomFrequencyManagerService(  883): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 883  tag : ACTIVITY_RESUME_BOOSTER@11
E/SMD     (  291): DCD ON
D/SamsungIME( 1716): [SwiftkeyWrapper] currentLangauge : 1701729619
I/jxcore-log( 6102): getBuffer is called!!!!
I/jxcore-log( 6102): 
,V/AlarmManager(  883): waitForAlarm result :8
,E/Watchdog(  883): !@Sync 2
,V/AlarmManager(  883): waitForAlarm result :8
,D/NtpTrustedTime(  883): forceRefresh() from cache miss
,D/NtpTrustedTime(  883): forceRefresh Fail.
,W/ContextImpl(  883): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD ON
,I/art     ( 1767): Explicit concurrent mark sweep GC freed 38654(2MB) AllocSpace objects, 17(272KB) LOS objects, 39% free, 21MB/35MB, paused 803us total 61.053ms
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,D/BatteryService(  883): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  883): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  883): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  883): Plugged
,I/MotionRecognitionService(  883): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BluetoothAdapter( 6102): disable()
,E/BluetoothManagerService(  883): Bluetooth is already disabled. DO NOT disable again.
,I/WifiManager( 6102): packageName : com.example.hello
,D/SecContentProvider(  883): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2(  883): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  883): mCursor = null
,D/WifiService(  883): setWifiEnabled: false pid=6102, uid=10265
,D/SettingsProvider(  883): name = wifi_on
,I/jxcore-log( 6102): ****TEST TOOK:  5058  ms ****
I/jxcore-log( 6102): 
,I/jxcore-log( 6102): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6102): 
,D/SSRM:n  (  883): SIOP:: AP = 340, PST = 381, CUR = 450
,D/AndroidRuntime( 6215): 
D/AndroidRuntime( 6215): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6215): CheckJNI is OFF
,D/AndroidRuntime( 6215): readGMSProperty: start
,D/AndroidRuntime( 6215): readGMSProperty: already setted!!
,D/AndroidRuntime( 6215): readGMSProperty: end
,D/AndroidRuntime( 6215): addProductProperty: start
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,E/AffinityControl( 6215): AffinityControl: registerfunction enter
,D/AndroidRuntime( 6215): Calling main entry com.android.commands.pm.Pm
,D/PackageManager(  883): START PACKAGE DELETE: observer{1007739456}
D/PackageManager(  883): pkg{<packageName>}
D/PackageManager(  883): user{0}
D/PackageManager(  883): caller{2000}
D/PackageManager(  883): flags{3}
,D/PersonaManagerService(  883): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  883): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  883): isFromApprovedUnInstaller: isApproved before exit: true
,D/PackageManager(  883): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager(  883): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager(  883): [MSG] DELETE_PACKAGE_AS_USER
,D/PackageManagerService(  883): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManagerService(  883): deletePackage- pkg:com.example.hello, edmuserId:-1
D/ApplicationPolicy(  883): getApplicationUninstallationEnabled
,D/ApplicationPolicy(  883): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager(  883): !@killApplicatoin: 10265, uninstall pkg
,I/ActivityManager(  883): Force stopping com.example.hello appid=10265 user=-1: uninstall pkg
I/ActivityManager(  883): Killing 6102:com.example.hello/u0a265 (adj 0): stop com.example.hello
,W/PackageSettings(  883): Skipping PackageSetting{4d09426 com.test.thalitest/10264} due to missing metadata
,I/WindowState(  883): WIN DEATH: Window{a4272a4 u0 com.example.hello/com.example.hello.MainActivity}
,I/SurfaceFlinger(  254): id=13 Removed NainActivit (5/8)
,I/SurfaceFlinger(  254): id=13 Removed NainActivit (-2/8)
,I/SurfaceFlinger(  254): id=13 Removed NainActivit (-2/8)
,D/PointerIcon(  883): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  883): setMouseCustomIcon IconType is same.101
D/PointerIcon(  883): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  883): setHoveringSpenCustomIcon IconType is same.1
,W/ActivityManager(  883): Force removing ActivityRecord{36937757 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,D/FocusedStackFrame(  883): Set to : 0
,D/CustomFrequencyManagerService(  883): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 883  pkgName : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager(  883): mDVFSHelper.acquire()
,V/WindowOrientationListener(  883): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  883): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  883): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  883): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  883): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
,W/ActivityManager(  883): Spurious death for ProcessRecord{35a00579 6102:com.example.hello/u0a265}, curProc for 6102: null
,I/ActivityManager(  883): Force stopping com.example.hello appid=10265 user=0: pkg removed
,D/SurfaceWidgetView( 1451): destroyHardwareResources():679231780
,D/Launcher( 1451): onRestart, Launcher: 653244379
,I/art     ( 4323): Explicit concurrent mark sweep GC freed 8802(513KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 16MB/21MB, paused 386us total 23.015ms
,I/art     ( 5889): Explicit concurrent mark sweep GC freed 3733(195KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 1.291ms total 21.122ms
,D/ResourcesManager(  883): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,D/ConnectivityService(  883): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/InputReader(  883): Reconfiguring input devices.  changes=0x00000010
,I/art     ( 4044): Explicit concurrent mark sweep GC freed 37745(2047KB) AllocSpace objects, 9(144KB) LOS objects, 39% free, 15MB/26MB, paused 398us total 31.500ms
,E/SamsungIME( 1716): mOCRHelper is null
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,W/GeofencerStateMachine( 1483): Ignoring removeGeofence because network location is disabled.
,E/Zygote  ( 6244): MountEmulatedStorage()
E/Zygote  ( 6244): v2
I/libpersona( 6244): KNOX_SDCARD checking this for 10023
I/libpersona( 6244): KNOX_SDCARD not a persona
,I/ActivityManager(  883): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=6244 uid=10023 gids={50023, 9997, 3003} abi=armeabi-v7a
,D/Launcher( 1451): onStart, Launcher: 653244379
D/Launcher.HomeView( 1451): onStart
,D/Launcher( 1451): onResume, Launcher: 653244379
,D/ResourcesManager(  883): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  883): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,D/ResourcesManager(  883): creating new AssetManager and set to /system/app/talkback/talkback.apk
,D/SettingsProvider(  883): name = kids_home_mode
D/SettingsProvider(  883): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  883): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  883): selectionArgs: false
D/SettingsProvider(  883): selectionArgs: 10010
D/SecContentProvider(  883): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  883): ret = -1
I/SELinux ( 6244): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,D/Launcher.HomeView( 1451): onResume
,I/SELinux ( 6244): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6244): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     (  883): Explicit concurrent mark sweep GC freed 26641(2033KB) AllocSpace objects, 11(176KB) LOS objects, 17% free, 36MB/44MB, paused 1.251ms total 116.018ms
D/ResourcesManager(  883): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
D/Launcher( 1451): setSystemUiTransparency.SettingNotFoundException : set as TRUE
I/art     (  883): WaitForGcToComplete blocked for 111.916ms for cause Explicit
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1754): [237392/8] Surface widget resume on instance = 1
D/accuweather( 1754): [Accuweather J]>>> SWW:179 [0:0] [SWW] onResume : rI = 1
D/accuweather( 1754): [Accuweather J]>>> SWW:184 [0:0] [SWW] onResume : Orientation = 1/1
D/accuweather( 1754): [Accuweather J]>>> WR:456 [0:0] =============== updateTime = 1
D/accuweather( 1754): [Accuweather J]>>> SWW:198 [0:0] [SWW] onResume : size = 1
D/Launcher( 1451): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 8000
,D/EnterpriseDeviceManagerService(  883): Package has changed for user 0
,D/EnterpriseDeviceManagerService(  883): Admin package name: com.google.android.gms
D/accuweather( 1754): [Accuweather J]>>> DBH:1954 [0:0] gADWI : count = 0
,D/TimaKeyStoreProvider( 6244): TimaSignature is unavailable
,D/ActivityThread( 6244): Added TimaKeyStore provider
,D/ResourcesManager(  883): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager(  883): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,D/accuweather( 1754): [Accuweather J]>>> WCD:423 [0:0]  onFirstUpdate :: fU = false
,D/accuweather( 1754): [Accuweather J]>>> SWW:313 [0:0] hideMsg : mResumeInstnceList[0] = 1
D/accuweather( 1754): [Accuweather J]>>> WR:800 [0:0] hideMsg : -1, isShow = false
D/accuweather( 1754): [Accuweather J]>>> WR:806 [0:0] hideMsg : 0
,D/accuweather( 1754): [Accuweather J]>>> WCD:513 [0:0]  onResume : fU = false, cnt =0
D/accuweather( 1754): [Accuweather J]>>> WCD:523 [0:0]  onResume :: mFAR = false, cC = false, isa = false
D/accuweather( 1754): [Accuweather J]>>> SWW:605 [0:0]  registerTTReceiver ! 
,D/accuweather( 1754): [Accuweather J]>>> WR:497 [0:0] onResume : 1, widgetMode : 1, orientation : 1
,D/comsamsunglog( 1754): [Accuweather J]>>> ==============================================================================================
,D/comsamsunglog( 1754): [Accuweather J]>>> widgetappapheroaccuweather [Version : 14121502] [ 1 ] 
D/comsamsunglog( 1754): [Accuweather J]>>> Header set to : ===> "accuweather" <===
D/comsamsunglog( 1754): [Accuweather J]>>> ==============================================================================================
,D/ResourcesManager(  883): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/accuweather( 1754): [Accuweather J]>>> SM:3422 [0:0] onR : isAni = false
D/accuweather( 1754): [Accuweather J]>>> SWW:544 [0:0] =================== , resume :1
,E/SMD     (  291): DCD ON
D/MenuAppsGridFragment( 1451): onResume
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 1754): [237392/8] Surface widget visibility changed visibility = true on instance = 1
D/ActivityManager(  883): handle home activity for 0
I/WallpaperManagerService(  883): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler(  883): post home show event for user 0
D/ActivityManager(  883): post active user change for 0
D/KnoxTimeoutHandler(  883): postActiveUserChange for user 0
D/accuweather( 1754): [Accuweather J]>>> SM:1134 [0:0] updateCurrentCityTime : [1]0/1
,D/accuweather( 1754): [Accuweather J]>>> SM:1151 [0:0] updateCurrentCityTime , ConditionLayerWidth = 852, mConditionLayerHeight = 532
,D/accuweather( 1754): [Accuweather J]>>> SM:2053 [0:0] drw 1nd Tm dt = Sun, 6 December
,D/SurfaceWidget.Renderer( 1754): [237392/8] SurfaceWidget drawing first frame
,D/accuweather( 1754): [Accuweather J]>>> WR:623 [0:0] onGLDraw : BG texture = 5
,D/ResourcesManager(  883): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager( 6244): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,D/ResourcesManager(  883): creating new AssetManager and set to /system/app/Evernote_H/Evernote_H.apk
,D/ResourcesManager(  883): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager(  883): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager(  883): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,I/SurfaceFlinger(  254): id=14 createSurf (1080x1920),1 flag=4, Mauncher
,D/StatusBarManagerService(  883): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/SecContentProvider2(  883): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  883): mCursor = null
,D/PointerIcon(  883): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon(  883): setMouseCustomIcon IconType is same.101
D/PointerIcon(  883): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  883): setHoveringSpenCustomIcon IconType is same.1
,D/ResourcesManager(  883): creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
,D/RegisteredServicesCache( 1418): empty dynamic service
,D/ResourcesManager(  883): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager(  883): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,D/Launcher( 1451): setSystemUiTransparency.SettingNotFoundException : set as TRUE
D/Launcher( 1451): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 8000
,W/Resources(  883): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  883): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/InputMethodManagerService(  883): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/ResourcesManager(  883): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,W/InputMethodManagerService(  883): Got RemoteException sending setActive(false) notification to pid 6102 uid 10265
,W/ContextImpl(  883): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ResourcesManager(  883): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
,I/HotwordRecognitionRnr( 1599): Starting hotword detection.
,D/ResourcesManager(  883): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager(  883): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,I/MicrophoneInputStream( 1599): mic_starting gfk@270d9064
,D/ResourcesManager(  883): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,V/AudioPolicyManager(  302): getInput() inputSource 1999, samplingRate 16000, format 8, channelMask 1, session 0, flags 0x10
,V/AudioPolicyManager(  302): getDeviceForInputSource()input source 1999, device 80000004
V/audio_hw_primary(  302): adev_open_input_stream: enter
E/audio_hw_primary(  302): adev_open_input_stream : jack_config 0
E/audio_hw_primary(  302): can not make /data/snd/hal_input.pcm 
,E/audio_hw_primary(  302): can not make /data/snd/hal_input_before_ns.pcm 
E/audio_hw_primary(  302): can not make /data/snd/hal_input_after_ns.pcm 
E/audio_hw_primary(  302): adev_open_input_stream input is null, set new input stream
V/audio_hw_primary(  302): adev_open_input_stream: exit
,I/AudioFlinger(  302): AudioFlinger's thread 0xb0556000 ready to run
V/audio_hw_primary(  302): in_standby: enter
V/audio_hw_primary(  302): in_standby: exit:  status(0)
,D/ResourcesManager(  883): creating new AssetManager and set to /system/app/Books/Books.apk
,V/audio_hw_primary(  302): in_standby: enter
V/audio_hw_primary(  302): in_standby: exit:  status(0)
,I/EDMNativeHelperService(  883): isMicrophoneEnabled
,I/KLMS-2.4.511: ( 6244): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,V/AudioPolicyManager(  302): startInput() input 16
V/AudioPolicyManager(  302): getDeviceForInputSource()input source 1999, device 80000004
V/AudioPolicyManager(  302): getNewInputDevice() selected device 80000004
V/AudioPolicyManager(  302): DeviceVector::refreshTypes() mDeviceTypes 80000004
V/AudioPolicyManager(  302): DeviceVector::getDevicesFromType() for type 80000004 found 0xb325b3c0
,V/audio_hw_primary(  302): in_set_parameters: enter: kvpairs=input_source=6;keyIsHotword=true;routing=-2147483644
V/audio_hw_primary(  302): in_set_parameters: exit: status(11)
,V/AudioPolicyManager(  302): setInputDevice() createAudioPatch returned 11 patchHandle 0
V/AudioPolicyManager(  302): AudioPolicyManager::startInput() input source = 1999
,D/WallpaperManager( 1451): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/WallpaperManager( 1451): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/ResourcesManager(  883): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,I/MicrophoneInputStream( 1599): mic_started gfk@270d9064
,D/ResourcesManager(  883): creating new AssetManager and set to /system/app/Drive/Drive.apk
,I/KLMS-2.4.511: ( 6244): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1449410989845
,D/StatusBarManagerService(  883): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,V/msm8974_platform(  302): platform_update_usecase_from_source: input source :6
V/audio_hw_primary(  302): start_input_stream: enter: usecase(7)
V/voice   (  302): voice_check_and_set_incall_rec_usecase: voice call not active
V/audio_hw_primary(  302): start_input_stream: usecase(7)
D/PreProcess(  302): new SamsungRecord
D/PreProcess(  302): new NS
I/samsungRecord(  302): [samsungrecord] SamsungRecInit 
,I/samsungRecord(  302): [samsungrecordMIC]Use HardCoding Values
E/samsungRecord(  302): miccalib file can't created. (/data/snd/miccalib.txt)
I/samsungRecord(  302): 1
D/SamsungRecord_NS(  302): [SamsungRecord_NS] Init SR 16000
D/SamsungRecord_NS(  302): [SamsungRecord_NS] getLevel inputsource 6, ret_level 3
V/audio_hw_primary(  302): select_devices: ENTER
V/audio_hw_primary(  302): select_devices: usecase(normal)
V/audio_hw_primary(  302): select_devices: usecase(PCM_CAPTURE)
V/msm8974_platform(  302): platform_get_input_snd_device: enter: out_device(0) in_device(0x4)
V/msm8974_platform(  302): get_INPUT_snd_device: check by Input_source(6)
V/msm8974_platform(  302): platform_get_input_snd_device_by_source: enter: out_device(0) in_device(0x4)
V/msm8974_platform(  302): get_INPUT_snd_device: AUDIO_SOURCE_VOICE_RECOGNITION
V/msm8974_platform(  302): platform_get_input_snd_device: exit: in_snd_device(vr-main-mic)
D/audio_hw_primary(  302): select_devices: out_snd_device(0: dummy)
D/audio_hw_primary(  302): select_devices: in_snd_device(128: vr-main-mic)
D/ACDB-LOADER(  302): ACDB -> send_audio_cal, acdb_id = 53, path =  1
D/ACDB-LOADER(  302): ACDB -> send_adm_topology
D/ACDB-LOADER(  302): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TOPOLOGY_ID
D/ACDB-LOADER(  302): ACDB -> send_asm_topology
D/ACDB-LOADER(  302): ACDB -> ACDB_CMD_GET_AUDPROC_STREAM_TOPOLOGY_ID
D/ACDB-LOADER(  302): ACDB -> send_audtable
D/ACDB-LOADER(  302): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TABLE
D/ACDB-LOADER(  302): ACDB -> AUDIO_SET_AUDPROC_CAL
D/ACDB-LOADER(  302): ACDB -> send_audvoltable
D/ACDB-LOADER(  302): ACDB -> ACDB_CMD_GET_AUDPROC_GAIN_DEP_STEP_TABLE
D/        (  302): Failed to fetch the lookup information of the device 00000035 
E/ACDB-LOADER(  302): Error: ACDB AudProc vol returned = -19
D/ACDB-LOADER(  302): ACDB -> AUDIO_SET_AUDPROC_VOL_CAL
D/ACDB-LOADER(  302): ACDB -> AUDIO_SET_AFE_CAL
V/audio_hw_primary(  302): enable_snd_device: snd_device(128: vr-main-mic, vr-main-mic)
D/audio_route(  302): ++++ audio_route_update_mixer ==============
D/audio_route(  302): Setting mixer control: ADC1 Volume
D/audio_route(  302): Setting mixer control: value: 19
I/KLMS-2.4.511: ( 6244): MainReciver(): PACKAGE_REMOVED
,D/audio_route(  302): Setting mixer control: DEC6 Volume
D/audio_route(  302): Setting mixer control: value: 84
,D/audio_route(  302): Setting mixer control: SLIM TX7 MUX, value: 13
,I/KLMS-2.4.511: ( 6244): MainReciver(): REPLACING: false | pkgName: com.example.hello
D/audio_route(  302): Setting mixer control: AIF1_CAP Mixer SLIM TX7
D/audio_route(  302): Setting mixer control: value: 1
,D/audio_route(  302): Setting mixer control: DEC6 MUX, value: 2
,D/audio_route(  302): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  302): enable_audio_route: enter: usecase(7)
V/audio_hw_primary(  302): enable_audio_route: apply mixer path: audio-record
D/audio_route(  302): ++++ audio_route_update_mixer ==============
D/audio_route(  302): Setting mixer control: MultiMedia1 Mixer SLIM_0_TX
D/audio_route(  302): Setting mixer control: value: 1
,D/audio_route(  302): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  302): enable_audio_route: exit
V/audio_hw_primary(  302): start_input_stream: Opening PCM device card_id(0) device_id(0), channels 1
,V/audio_hw_primary(  302): start_input_stream: exit
,D/ResourcesManager(  883): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,I/Timeline( 1451): Timeline: Activity_idle id: android.os.BinderProxy@28a169f7 time:80295
,D/ResourcesManager(  883): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager(  883): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(  883): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(  883): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
W/Resources(  883): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  883): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  883): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager(  883): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/ResourcesManager(  883): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,I/HotwordWorker( 1599): onReady
,D/ResourcesManager(  883): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService(  883): PackageReceiver onReceive()
,I/HarmonyEASService(  883): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy(  883): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/BackupManagerService(  883): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,D/JobSchedulerService(  883): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  883): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  883): uID is 10265
V/EnterpriseBillingPolicy(  883): Removed Packageuid is0
,V/EnterpriseBillingPolicyStorage(  883): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage(  883): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  883): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  883): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  883): getBillingProfileForVpnEngine - start - com.example.hello
,V/EnterpriseBillingPolicyStorage(  883): getBillingProfileForVpnEngine - end - null
W/Resources(  883): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  883): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,W/Resources(  883): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/libpersona( 6269): KNOX_SDCARD checking this for 10116
D/ResourcesManager(  883): creating new AssetManager and set to /system/priv-app/SamsungLink20/SamsungLink20.apk
I/libpersona( 6269): KNOX_SDCARD not a persona
E/Zygote  ( 6269): MountEmulatedStorage()
E/Zygote  ( 6269): v2
,I/art     (  883): Explicit concurrent mark sweep GC freed 8952(510KB) AllocSpace objects, 0(0B) LOS objects, 17% free, 36MB/44MB, paused 2.944ms total 265.095ms
,I/ActivityManager(  883): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6269 uid=10116 gids={50116, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 5128:com.sec.providers.settingsearch/u0a191 (adj 15): bgCount ##41
,D/TaskPersister(  883): removeObsoleteFile: deleting file=2_task.xml
,D/WallpaperManagerService(  883):  force update = false; persona id = 0; current user =0; current persona = 0
,D/KnoxTimeoutHandler(  883): handleHomeShow for 0 and current 0
D/KnoxTimeoutHandler(  883): handleActiveUserChange for user 0
,W/Resources(  883): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  883): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  883): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/Resources(  883): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  883): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  883): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/PackageManager(  883): delete codoeFile: 
,D/ResourcesManager(  883): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
I/SELinux ( 6269): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/AASAUninstall(  883):  com.example.hello not target!
,D/PackageManager(  883): result of delete: 1{1007739456}
I/SELinux ( 6269): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6269): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(  883): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/AndroidRuntime( 6215): Shutting down VM
,W/Resources(  883): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  883): creating new AssetManager and set to /system/app/Maps/Maps.apk
,D/ResourcesManager(  883): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/CustomFrequencyManagerService(  883): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 883  tag : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager(  883): mDVFSHelper.release()
,D/CustomFrequencyManagerService(  883): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 883  pkgName : ACTIVITY_RESUME_BOOSTER@11
,D/TimaKeyStoreProvider( 6269): TimaSignature is unavailable
,D/ActivityThread( 6269): Added TimaKeyStore provider
,D/ResourcesManager(  883): creating new AssetManager and set to /system/app/Peel_L/Peel_L.apk
,D/ResourcesManager(  883): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/ResourcesManager( 6269): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,W/Resources(  883): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  883): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  883): creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
,W/ResourcesManager(  883): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  883): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/elm:14491( 6269): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
W/ResourcesManager(  883): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources(  883): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/elm:14491( 6269): ELMEngine.ELMEngine( context ).
D/ResourcesManager(  883): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager(  883): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/elm:14491( 6269): MDMBridge.setEnterpriseBridge()
,D/elm:14491( 6269): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(  883): creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
,D/elm:14491( 6269): ElmAgentService : onCreate()
,D/elm:14491( 6269): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:14491( 6269): MainReceiver.listeningToPackageRemoved()
D/elm:14491( 6269): MDMBridge.getInstance()
D/elm:14491( 6269): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:14491( 6269): MDMBridge.getAllLicenseInfoFromSDK()
,D/ResourcesManager(  883): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,E/Zygote  ( 6288): MountEmulatedStorage()
I/libpersona( 6288): KNOX_SDCARD checking this for 10021
E/Zygote  ( 6288): v2
I/libpersona( 6288): KNOX_SDCARD not a persona
,D/ResourcesManager(  883): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources(  883): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  883): creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
,W/Resources(  883): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  883): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,I/ActivityManager(  883): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=6288 uid=10021 gids={50021, 9997} abi=armeabi-v7a
,W/Resources(  883): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  883): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  883): creating new AssetManager and set to /system/priv-app/SecMyFiles2/SecMyFiles2.apk
,W/Resources(  883): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  883): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources(  883): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  883): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  883): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/Resources(  883): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  883): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  883): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/Resources(  883): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager(  883): clearDefaults: com.example.hello
,I/CrashAnrDetector(  883): onPackageRemoved : com.example.hello
,I/SELinux ( 6288): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
D/elm:14491( 6269): ElmAgentService : onDestroy().
,I/SELinux ( 6288): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,I/ActivityManager(  883): Killing 4424:com.android.providers.calendar/u0a51 (adj 15): bgCount ##41
,E/SELinux ( 6288): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/Timeline(  883): Timeline: Activity_windows_visible id: ActivityRecord{39ac9763 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:80567
,D/TimaKeyStoreProvider( 6288): TimaSignature is unavailable
,D/ActivityThread( 6288): Added TimaKeyStore provider
,D/ResourcesManager( 6288): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,D/com.sec.android.service.health.upgrade.UninstallReceiver( 6288): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 6288): onReceive called  PACKAGE_REMOVED package:com.example.hello
D/com.sec.android.service.health.upgrade.UninstallReceiver( 6288): onReceive() : package name is not s health. Return !!!
,W/ProcessCpuTracker(  883): Skipping unknown process pid 6215
,I/PCWCLIENTTRACE_PushUtil( 5721): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5721): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5721): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5721): [onReceive] - android.intent.action.PACKAGE_REMOVED
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6305): MountEmulatedStorage()
,E/Zygote  ( 6305): v2
I/libpersona( 6305): KNOX_SDCARD checking this for 10043
I/libpersona( 6305): KNOX_SDCARD not a persona
,I/ActivityManager(  883): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=6305 uid=10043 gids={50043, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 4737:com.google.android.talk/u0a131 (adj 15): bgCount ##41
,D/CustomFrequencyManagerService(  883): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 883  tag : ACTIVITY_RESUME_BOOSTER@11
,I/SELinux ( 6305): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6305): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6305): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6305): TimaSignature is unavailable
,D/ActivityThread( 6305): Added TimaKeyStore provider
,D/ResourcesManager( 6305): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,I/EventHub(  883): Removing device '/dev/input/event6' due to inotify event
,E/SPPClientService( 6305): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 6305): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 6305): PushLog.txt file is not deleted.
,D/SPPClientService( 6305): PushLog.txt file is not deleted.
D/SPPClientService( 6305): ============PushLog. stop!
,E/SQLiteLog( 6305): (28) failed to open "/data/data/com.sec.spp.push/databases/push_noti_db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteLog( 6305): (28) failed to open "/data/data/com.sec.spp.push/databases/push_noti_db" with flag (131072) and mode_t (0) due to error (2)
E/SQLiteLog( 6305): (14) cannot open file at line 32503 of [9491ba7d73]
E/SQLiteLog( 6305): (14) os_unix.c:32503: (2) open(/data/data/com.sec.spp.push/databases/push_noti_db) - 
,E/SQLiteDatabase( 6305): Failed to open database '/data/data/com.sec.spp.push/databases/push_noti_db'.
E/SQLiteDatabase( 6305): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 6305): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6305): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6305): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6305): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6305): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6305): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6305): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 6305): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 6305): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6305): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteDatabase( 6305): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6305): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6305): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6305): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6305): 	at com.sec.spp.push.notisvc.a.b.<init>(Unknown Source)
E/SQLiteDatabase( 6305): 	at com.sec.spp.push.notisvc.a.b.a(Unknown Source)
E/SQLiteDatabase( 6305): 	at com.sec.spp.push.notisvc.registration.l.b(Unknown Source)
E/SQLiteDatabase( 6305): 	at com.sec.spp.push.notisvc.registration.l.a(Unknown Source)
E/SQLiteDatabase( 6305): 	at com.sec.spp.push.notisvc.registration.PackageRemovedReceiver.a(Unknown Source)
E/SQLiteDatabase( 6305): 	at com.sec.spp.push.notisvc.registration.PackageRemovedReceiver.onReceive(Unknown Source)
E/SQLiteDatabase( 6305): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2991)
E/SQLiteDatabase( 6305): 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
E/SQLiteDatabase( 6305): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
E/SQLiteDatabase( 6305): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6305): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6305): 	at android.app.ActivityThread.main(ActivityThread.java:5940)
E/SQLiteDatabase( 6305): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6305): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6305): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1389)
E/SQLiteDatabase( 6305): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1184)
,E/LNoti   ( 6305): [b] open fail. SQLException occured
,I/EventHub(  883): Removing device '/dev/input/event7' due to inotify event
,I/SA      ( 5807): [SUR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOB6 PSS = 5.701607447389803  ]
,I/SA      ( 5807): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10265 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,I/ActivityManager(  883): Killing 5398:com.samsung.android.app.FileShareServer/u0a88 (adj 13): bgCount ##41
,E/SharedPreferencesImpl( 4918): Couldn't create directory for SharedPreferences file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml
,D/Mms/FreeMessageReceiver( 4989): onReceive, action : android.intent.action.PACKAGE_REMOVED
,I/TactileAssist(  883): enable value -1
,I/TactileAssist(  883): internal enable value -1
I/TactileAssist(  883): intensity value -1
I/TactileAssist(  883): saveAppList value true
,I/TactileAssist(  883): List of disabled apps :
,E/SharedPreferencesImpl(  883): Couldn't create directory for SharedPreferences file /data/data/com.android.settings/shared_prefs/com.android.settings_tactileassist.xml
,D/Mms/FreeMessageReceiverService( 4989): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
D/Mms/FreeMessageReceiverService( 4989): onHandleIntent: ACTION_PACKAGE_REMOVED
,I/EventHub(  883): Removing device '/dev/input/event8' due to inotify event
,D/SettingsProvider(  883): name = reading_mode_app_list
,I/EventHub(  883): Removing device '/dev/input/event9' due to inotify event
,D/Compatibility( 5836): onReceive() it will make start service
,D/Compatibility( 5836): onHandleIntent()
,D/Compatibility( 5836): intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10265, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,D/Compatibility( 5836): found: 2
,D/Compatibility( 5836): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5836): skipping ResolveInfo{1e1438ea com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5836): considering ResolveInfo{26efb7db com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
,D/Compatibility( 5836): default: com.sec.android.app.soundalive.SAControlPanelActivity
,I/UpdateIcingCorporaServi( 1599): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,D/Compatibility( 5836): enabling receiver ResolveInfo{2c783278 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,W/ContextImpl( 5147): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:2991 
,D/Compatibility( 5836): enabling receiver ResolveInfo{f5e3d51 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,D/Compatibility( 5836): enabling receiver ResolveInfo{3f74f9b6 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 5836): enabling receiver ResolveInfo{1a7f6b7 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
E/SharedPreferencesImpl( 5836): Couldn't create directory for SharedPreferences file /data/data/com.sec.android.app.soundalive/shared_prefs/SoundAlive_Settings.xml
E/SharedPreferencesImpl( 5836): Couldn't create directory for SharedPreferences file /data/data/com.sec.android.app.soundalive/shared_prefs/SoundAlive_Settings.xml
D/Compatibility( 5836): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
D/RCPManager( 5418):  in createShortcut() for packageName: com.example.hello userId0
,E/SQLiteLog( 5147): (28) failed to open "/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu" with flag (131138) and mode_t (0) due to error (2)
E/SQLiteLog( 5147): (28) failed to open "/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu" with flag (131072) and mode_t (0) due to error (2)
E/SQLiteLog( 5147): (14) cannot open file at line 32503 of [9491ba7d73]
E/SQLiteLog( 5147): (14) os_unix.c:32503: (2) open(/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu) - 
,E/SQLiteDatabase( 5147): Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
E/SQLiteDatabase( 5147): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 5147): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5147): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 5147): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 5147): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5147): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5147): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5147): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 5147): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 5147): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 5147): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteDatabase( 5147): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 5147): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5147): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5147): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
E/SQLiteDatabase( 5147): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:109)
E/SQLiteDatabase( 5147): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5147): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5147): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 5147): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 5147): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
W/System.err( 5147): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 5147): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
W/System.err( 5147): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
W/System.err( 5147): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err( 5147): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err( 5147): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err( 5147): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
W/System.err( 5147): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
W/System.err( 5147): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
W/System.err( 5147): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
W/System.err( 5147): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
W/System.err( 5147): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
W/System.err( 5147): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
W/System.err( 5147): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
W/System.err( 5147): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:109)
W/System.err( 5147): 	at andr,oid.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/System.err( 5147): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5147): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 5147): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/RCPManagerService(  883):  in createShortcut() for packageName: com.example.hello userId0
D/RCPManagerService(  883): queryAllProviders():  providerCallBack is not register for 0
E/SQLiteLog( 1599): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 1599): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/AndroidRuntime( 1599): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 1599): Process: com.google.android.googlequicksearchbox:search, PID: 1599
E/AndroidRuntime( 1599): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1599): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1599): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
E/AndroidRuntime( 1599): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1599): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1599): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
E/AndroidRuntime( 1599): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:421)
E/AndroidRuntime( 1599): 	at csx.d(PG:186)
E/AndroidRuntime( 1599): 	at cun.g(PG:594)
E/AndroidRuntime( 1599): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 1599): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:330)
E/AndroidRuntime( 1599): 	at android.content.ContentResolver.update(ContentResolver.java:1343)
E/AndroidRuntime( 1599): 	at cuw.Tg(PG:368)
E/AndroidRuntime( 1599): 	at cuy.ub(PG:301)
E/AndroidRuntime( 1599): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(PG:268)
E/AndroidRuntime( 1599): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(PG:186)
E/AndroidRuntime( 1599): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1599): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1599): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 1599): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/EventHub(  883): Removing device '/dev/input/event10' due to inotify event
V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.google.android.googlequicksearchbox:search
E/AndroidRuntime(  883): *** FATAL EXCEPTION IN SYSTEM PROCESS: Error dump: system_app_crash
E/AndroidRuntime(  883): java.lang.IllegalArgumentException: Invalid path: /data/system/dropbox
E/AndroidRuntime(  883): 	at android.os.StatFs.doStat(StatFs.java:46)
E/AndroidRuntime(  883): 	at android.os.StatFs.restat(StatFs.java:56)
E/AndroidRuntime(  883): 	at com.android.server.DropBoxManagerService.trimToFit(DropBoxManagerService.java:726)
E/AndroidRuntime(  883): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:188)
E/AndroidRuntime(  883): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/AndroidRuntime(  883): 	at com.android.server.am.ActivityManagerService$23.run(ActivityManagerService.java:14833)
E/AndroidRuntime(  883): Caused by: android.system.ErrnoException: statvfs failed: ENOENT (No such file or directory)
E/AndroidRuntime(  883): 	at libcore.io.Posix.statvfs(Native Method)
E/AndroidRuntime(  883): 	at libcore.io.BlockGuardOs.statvfs(BlockGuardOs.java:298)
E/AndroidRuntime(  883): 	at android.system.Os.statvfs(Os.java:473)
E/AndroidRuntime(  883): 	at android.os.StatFs.doStat(StatFs.java:44)
E/AndroidRuntime(  883): 	... 5 more
,D/StatusBarManagerService(  883): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon(  883): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  883): setMouseCustomIcon IconType is same.101
D/PointerIcon(  883): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  883): setHoveringSpenCustomIcon IconType is same.1
,W/ContextImpl( 5889): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:55 android.app.ActivityThread.handleReceiver:2991 
,F/libc    (  883): Fatal signal 7 (SIGBUS), code 2, fault addr 0xa9766028 in tid 961 (ActivityManager)
,I/EventHub(  883): Removing device '/dev/input/event11' due to inotify event
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6331): MountEmulatedStorage()
E/Zygote  ( 6331): v2
I/libpersona( 6331): KNOX_SDCARD checking this for 1000
I/libpersona( 6331): KNOX_SDCARD not a persona
,I/ActivityManager(  883): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6331 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,I/DEBUG   (  287): failed to change ownership of /data/tombstones: Read-only file system
E/        (  287): !@dumpstate -k -t -z -d -o /data/log/dumpstate_app_native -m 883
,I/SELinux ( 6331): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6331): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6331): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/dumpstate( 6337): begin
,I/dumpstate( 6337): open lockfile failed Read-only file system
,E/Zygote  ( 6339): MountEmulatedStorage()
,E/Zygote  ( 6339): v2
I/libpersona( 6339): KNOX_SDCARD checking this for 10121
I/libpersona( 6339): KNOX_SDCARD not a persona
,I/SELinux ( 6339): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6339): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6339): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/libsuspend(  883): Error reading from /sys/power/wakeup_count: Interrupted system call
E/audit_log( 1802): File locking failed. error= Bad file number
,I/ServiceManager(  252): service 'ABTPersistenceService' died
I/ServiceManager(  252): service 'textservices' died
,E/AndroidRuntime( 1599): Error reporting crash
E/AndroidRuntime( 1599): android.os.DeadObjectException
E/AndroidRuntime( 1599): 	at android.os.BinderProxy.transactNative(Native Method)
E/AndroidRuntime( 1599): 	at android.os.BinderProxy.transact(Binder.java:496)
E/AndroidRuntime( 1599): 	at android.app.ActivityManagerProxy.handleApplicationCrash(ActivityManagerNative.java:4656)
E/AndroidRuntime( 1599): 	at com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException(RuntimeInit.java:95)
E/AndroidRuntime( 1599): 	at gqq.uncaughtException(PG:58)
E/AndroidRuntime( 1599): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
E/AndroidRuntime( 1599): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
I/Process ( 1599): Sending signal. PID: 1599 SIG: 9
W/AudioFlinger(  302): power manager service died !!!
W/AudioCache(  302): clearPowerManager -mWakeLockCount is 0, failed to releaseWakeLock function
W/AudioFlinger(  302): power manager service died !!!
,I/SurfaceFlinger(  254): restart the boot-animation @ binderDied
,I/SurfaceFlinger(  254): id=2 Removed GocusedStac (4/8)
I/SurfaceFlinger(  254): id=3 Removed EimLayer (0/7)
I/SurfaceFlinger(  254): id=4 Removed EimLayer (0/6)
I/SurfaceFlinger(  254): id=10 Removed EimLayer (0/5)
I/SurfaceFlinger(  254): id=11 Removed EimLayer (2/4)
I/SurfaceFlinger(  254): id=2 Removed GocusedStac (-2/4)
I/SurfaceFlinger(  254): id=3 Removed EimLayer (-2/4)
I/SurfaceFlinger(  254): id=4 Removed EimLayer (-2/4)
I/SurfaceFlinger(  254): id=5 Removed JmageWallpa (0/3)
I/SurfaceFlinger(  254): id=5 Removed JmageWallpa (-2/3)
I/SurfaceFlinger(  254): id=10 Removed EimLayer (-2/3)
I/SurfaceFlinger(  254): id=14 Removed Mauncher (0/2)
I/SurfaceFlinger(  254): id=7 Removed TtatusBar (0/1)
I/SurfaceFlinger(  254): id=9 Removed Ieads Up (0/0)
I/SurfaceFlinger(  254): id=11 Removed EimLayer (-2/0)
I/SurfaceFlinger(  254): id=7 Removed TtatusBar (-2/0)
I/SurfaceFlinger(  254): id=14 Removed Mauncher (-2/0)
I/SurfaceFlinger(  254): id=9 Removed Ieads Up (-2/0)
,W/Sensors ( 1754): sensorservice died [0xaf29f680]
,W/Sensors ( 4918): sensorservice died [0xaf2fa240]
W/Sensors ( 1185): sensorservice died [0xaf29d1c0]
,E/WifiManager( 1599): Channel connection lost
W/Sensors ( 1483): sensorservice died [0xaf2f5340]
,D/SurfaceFlinger(  254): Set power mode=2, type=0 flinger=0xb6a62000
D/SurfaceFlinger(  254): Screen type=0 is already mode=2
E/WifiManager( 1313): Channel connection lost
E/WifiManager( 1483): Channel connection lost
,W/Sensors ( 1852): sensorservice died [0xaf2dba40]
,E/WifiManager( 1185): Channel connection lost
,E/WifiManager( 1577): Channel connection lost
,W/Sensors ( 1401): sensorservice died [0xaf2dc9c0]
,W/Sensors ( 1426): sensorservice died [0xaf29b240]
I/ServiceManager(  252): service 'network_score' died
I/ServiceManager(  252): service 'netstats' died
E/ActivityThread( 5889): Failed to find provider info for com.samsung.android.provider.filterprovider
I/ServiceManager(  252): service 'netpolicy' died
I/ServiceManager(  252): service 'wifip2p' died
I/ServiceManager(  252): service 'sec_analytics' died
I/ServiceManager(  252): service 'usb' died
I/ServiceManager(  252): service 'serial' died
E/ActivityThread( 5889): Failed to find provider info for com.samsung.android.provider.filterprovider
I/ServiceManager(  252): service 'uimode' died
I/ServiceManager(  252): service 'jobscheduler' died
I/ServiceManager(  252): service 'connectivity' died
I/ServiceManager(  252): service 'sb_service' died
I/ServiceManager(  252): service 'servicediscovery' died
I/ServiceManager(  252): service 'updatelock' died
I/ServiceManager(  252): service 'notification' died
I/ServiceManager(  252): service 'devicestoragemonitor' died
I/ServiceManager(  252): service 'location' died
I/ServiceManager(  252): service 'country_detector' died
I/ServiceManager(  252): service 'search' died
I/ServiceManager(  252): service 'dropbox' died
I/ServiceManager(  252): service 'wallpaper' died
I/ServiceManager(  252): service 'audio' died
I/ServiceManager(  252): service 'DockObserver' died
I/ServiceManager(  252): service 'wifi' died
I/ServiceManager(  252): service 'msapwifi' died
I/ServiceManager(  252): service 'wifiscanner' died
I/ServiceManager(  252): service 'rttmanager' died
I/ServiceManager(  252): service 'context_aware' died
I/ServiceManager(  252): service 'scontext' died
I/ServiceManager(  252): service 'barbeam' died
I/ServiceManager(  252): service 'multiwindow_facade' died
I/ServiceManager(  252): service 'window' died
I/ServiceManager(  252): service 'input' died
I/ServiceManager(  252): service 'tactileassist' died
I/ServiceManager(  252): service 'bluetooth_manager' died
I/ServiceManager(  252): service 'bluetooth_secure_mode_manager' died
I/ServiceManager(  252): service 'rcp' died
I/ServiceManager(  252): service 'mum_container_policy' died
I/ServiceManager(  252): service 'enterprise_billing_policy' died
I/ServiceManager(  252): service 'knox_timakeystore_policy' died
I/ServiceManager(  252): service 'enterprise_policy' died
I/ServiceManager(  252): service 'statusbar' died
I/ServiceManager(  252): service 'clipboard' died
I/ServiceManager(  252): service 'clipboardEx' died
E/AndroidRuntime( 5889): FATAL EXCEPTION: FilterPackageServiceHandler
E/AndroidRuntime( 5889): Process: com.samsung.android.app.filterinstaller, PID: 5889
E/AndroidRuntime( 5889): java.lang.IllegalArgumentException: Unknown URL content://com.samsung.android.provider.filterprovider/packages/com.example.hello
E/AndroidRuntime( 5889): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/AndroidRuntime( 5889): 	at com.samsung.android.app.filterinstaller.FilterUninstaller.removeFromDB(FilterUninstaller.java:52)
E/AndroidRuntime( 5889): 	at com.samsung.android.app.filterinstaller.FilterUninstaller.uninstallFilters(FilterUninstaller.java:43)
E/AndroidRuntime( 5889): 	at com.samsung.android.app.filterinstaller.FilterPackageService$ServiceHandler.handleMessage(FilterPackageService.java:149)
E/AndroidRuntime( 5889): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5889): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 5889): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ServiceManager(  252): service 'network_management' died
I/ServiceManager(  252): service 'motion_recognition' died
I/ServiceManager(  252): service 'cover' died
I/ServiceManager(  252): service 'mount' died
I/ServiceManager(  252): service 'lock_settings' died
I/ServiceManager(  252): service 'device_policy' died
I/ServiceManager(  252): service 'harmony_eas_service' died
I/ServiceManager(  252): service 'sdp' died
I/ServiceManager(  252): service 'log_manager_service' died
,I/ServiceManager(  252): service 'accessibility' died
I/ServiceManager(  252): service 'backup' died
I/ServiceManager(  252): service 'appwidget' died
I/ServiceManager(  252): service 'voiceinteraction' died
I/ServiceManager(  252): service 'SecExternalDisplayService' died
I/ServiceManager(  252): service 'diskstats' died
I/ServiceManager(  252): service 'mDNIe' died
I/ServiceManager(  252): service 'spengestureservice' died
I/ServiceManager(  252): service 'quickconnect' died
I/ServiceManager(  252): service 'samplingprofiler' died
I/ServiceManager(  252): service 'commontime_management' died
I/ServiceManager(  252): service 'dreams' died
I/ServiceManager(  252): service 'assetatlas' died
I/ServiceManager(  252): service 'print' died
I/ServiceManager(  252): service 'restrictions' died
I/ServiceManager(  252): service 'media_session' died
I/ServiceManager(  252): service 'media_router' died
I/ServiceManager(  252): service 'trust' died
I/ServiceManager(  252): service 'fingerprint' died
I/ServiceManager(  252): service 'launcherapps' died
I/ServiceManager(  252): service 'voip' died
I/ServiceManager(  252): service 'media_projection' died
I/ServiceManager(  252): service 'imms' died
I/ServiceManager(  252): service 'input_method' died
I/ServiceManager(  252): service 'battery' died
I/ServiceManager(  252): service 'telephony.registry' died
I/ServiceManager(  252): service 'sedenial' died
I/ServiceManager(  252): service 'vibrator' died
I/ServiceManager(  252): service 'tima' died
E/AndroidRuntime( 5889): Error reporting crash
E/AndroidRuntime( 5889): android.os.DeadObjectException
E/AndroidRuntime( 5889): 	at android.os.BinderProxy.transactNative(Native Method)
E/AndroidRuntime( 5889): 	at android.os.BinderProxy.transact(Binder.java:496)
E/AndroidRuntime( 5889): 	at android.app.ActivityManagerProxy.handleApplicationCrash(ActivityManagerNative.java:4656)
E/AndroidRuntime( 5889): 	at com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException(RuntimeInit.java:95)
E/AndroidRuntime( 5889): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
E/AndroidRuntime( 5889): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
I/ServiceManager(  252): service 'cepproxyks' died
I/ServiceManager(  252): service 'CustomFrequencyManagerService' died
I/ServiceManager(  252): service 'samsung.smartfaceservice' died
I/Process ( 5889): Sending signal. PID: 5889 SIG: 9
I/ServiceManager(  252): service 'consumer_ir' died
I/ServiceManager(  252): service 'alarm' died
I/ServiceManager(  252): service 'enterprise_license_policy' died
I/ServiceManager(  252): service 'application_policy' died
I/ServiceManager(  252): service 'wifi_policy' died
I/ServiceManager(  252): service 'phone_restriction_policy' died
I/ServiceManager(  252): service 'remoteinjection' died
I/ServiceManager(  252): service 'scheduling_policy' died
I/ServiceManager(  252): service 'hardware' died
I/ServiceManager(  252): service 'webviewupdate' died
I/ServiceManager(  252): service 'usagestats' died
I/ServiceManager(  252): service 'dbinfo' died
I/ServiceManager(  252): service 'cpuinfo' died
I/ServiceManager(  252): service 'activity' died
I/ServiceManager(  252): service 'meminfo' died
I/ServiceManager(  252): service 'edmnativehelper' died
I/ServiceManager(  252): service 'package' died
I/ServiceManager(  252): service 'permission' died
I/ServiceManager(  252): service 'procstats' died
I/ServiceManager(  252): service 'gfxinfo' died
I/ServiceManager(  252): service 'user' died
I/ServiceManager(  252): service 'SEAMService' died
I/ServiceManager(  252): service 'persona' died
I/ServiceManager(  252): service 'account' died
I/ServiceManager(  252): service 'content' died
I/ServiceManager(  252): service 'DirEncryptService' died
I/ServiceManager(  252): service 'ReactiveService' died
I/ServiceManager(  252): service 'entropy' died
I/ServiceManager(  252): service 'mdm.remotedesktop' died
I/ServiceManager(  252): service 'sensorservice' died
I/ServiceManager(  252): service 'batterystats' died
I/ServiceManager(  252): service 'appops' died
I/ServiceManager(  252): service 'power' died
I/ServiceManager(  252): service 'display' died
I/ServiceManager(  252): service 'persona_policy' died
W/Sensors ( 1451): sensorservice died [0xaf29b300]
F/libc    ( 6339): Fatal signal 7 (SIGBUS), code 2, fault addr 0x7428c9c3 in tid 6339 (.filterprovider)
F/libc    ( 6331): Fatal signal 7 (SIGBUS), code 2, fault addr 0x7428c9c3 in tid 6331 (ndroid.keychain)
E/WifiManager( 1426): Channel connection lost
,V/AudioPolicyManager(  302): stopInput() input 16
V/AudioPolicyManager(  302): releaseInput() 16
V/AudioPolicyManager(  302): closeInput(16)
V/audio_hw_primary(  302): in_standby: enter
,V/audio_hw_primary(  302): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  302): disable_audio_route: enter: usecase(7)
V/audio_hw_primary(  302): disable_audio_route: reset mixer path: audio-record
D/audio_route(  302): ++++ audio_route_update_mixer ==============
D/audio_route(  302): Setting mixer control: MultiMedia1 Mixer SLIM_0_TX
D/audio_route(  302): Setting mixer control: value: 0
D/audio_route(  302): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  302): disable_audio_route: exit
V/audio_hw_primary(  302): disable_snd_device: snd_device(128: vr-main-mic)
D/audio_route(  302): ++++ audio_route_update_mixer ==============
D/audio_route(  302): Setting mixer control: ADC1 Volume
D/audio_route(  302): Setting mixer control: value: 0
D/audio_route(  302): Setting mixer control: DEC6 Volume
D/audio_route(  302): Setting mixer control: value: 0
D/audio_route(  302): Setting mixer control: SLIM TX7 MUX, value: 0
D/audio_route(  302): Setting mixer control: AIF1_CAP Mixer SLIM TX7
D/audio_route(  302): Setting mixer control: value: 0
D/audio_route(  302): Setting mixer control: DEC6 MUX, value: 0
D/audio_route(  302): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  302): stop_input_stream: exit: status(0)
,V/audio_hw_primary(  302): in_standby: exit:  status(0)
V/audio_hw_primary(  302): adev_close_input_stream
V/audio_hw_primary(  302): in_standby: enter
V/audio_hw_primary(  302): in_standby: exit:  status(0)
E/audio_hw_primary(  302): adev_close_input_stream, set jack_in to null
V/AudioPolicyManager(  302): releaseInput() exit
,I/DEBUG   (  287): failed to change ownership of /data/tombstones: Read-only file system
E/        (  287): !@dumpstate -k -t -z -d -o /data/log/dumpstate_app_native -m 6339
,E/installd(  306): eof
E/installd(  306): failed to read size
I/installd(  306): closing connection
,I/dumpstate( 6365): begin
,I/dumpstate( 6365): open lockfile failed Read-only file system
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,E/audit_log( 1802): File locking failed. error= Bad file number
,I/SurfaceFlinger(  254): Disp[0] Orientation 0=>0
,I/DEBUG   (  287): failed to change ownership of /data/tombstones: Read-only file system
E/        (  287): !@dumpstate -k -t -z -d -o /data/log/dumpstate_app_native -m 6331
,E/qdoverlay(  254): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
E/qdoverlay(  254): MdpCtrl close error in unset
,I/Zygote  (  347): Process 6339 exited due to signal (7)
,I/dumpstate( 6366): begin
,I/dumpstate( 6366): open lockfile failed Read-only file system
,I/qdhwcomposer(  254): handle_blank_event: dpy:0 panel power state: 0
,E/qdoverlay(  254): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
E/qdoverlay(  254): MdpCtrl close error in unset
E/qdoverlay(  254): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
E/qdoverlay(  254): MdpCtrl close error in unset
E/qdoverlay(  254): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
E/qdoverlay(  254): MdpCtrl close error in unset
,E/qdhwcomposer(  254): hwc_vsync_control: vsync control failed. Dpy=0, enable=1 : Operation not permitted
E/SurfaceFlinger(  254): eventControl(0, 1) failed Operation not permitted
,E/audit_log( 1802): File locking failed. error= Bad file number

```
