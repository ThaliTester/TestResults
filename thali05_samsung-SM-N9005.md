#### Test 61248225a3bd1fe_thali05_samsung-SM-N9005 Logs


```
--------- beginning of system
W/ContextImpl(  751): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
--------- beginning of main
I/ServiceManager(  372): Waiting for service AtCmdFwd...
I/ServiceManager(  372): Waiting for service AtCmdFwd...
I/wpa_supplicant( 1303): nl80211: Received scan results (19 BSSes)
D/WifiP2pService(  751): InactiveState{ what=147461 }
D/WifiP2pService(  751): P2pEnabledState{ what=147461 }
D/WifiP2pService(  751): DefaultState{ what=147461 }
,E/SMD     (  305): DCD ON
D/AndroidRuntime( 7034): 
D/AndroidRuntime( 7034): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7034): CheckJNI is OFF
D/AndroidRuntime( 7034): readGMSProperty: start
D/AndroidRuntime( 7034): readGMSProperty: already setted!!
I/ServiceManager(  372): Waiting for service AtCmdFwd...
D/AndroidRuntime( 7034): readGMSProperty: end
D/AndroidRuntime( 7034): addProductProperty: start
E/AffinityControl( 7034): AffinityControl: registerfunction enter
D/AndroidRuntime( 7034): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  751): inState():  stateMachine is null !!
I/PersonaManagerService(  751): PersonaId don't exist
I/ActivityManager(  751): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy(  751): isApplicationStateBlocked userId 0 pkgname com.example.hello
I/ActivityManager(  751): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  751): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
V/AlarmManager(  751): waitForAlarm result :4
W/ActivityManager(  751): mDVFSHelper.acquire()
D/FocusedStackFrame(  751): Set to : 0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
D/BatteryService(  751): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService(  751): level:100, scale:100, status:5, health:2, present:true, voltage: 4323, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  751): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  751): Sending ACTION_BATTERY_CHANGED.
D/BatteryService(  751): stay LED for fully charged
E/Zygote  ( 7051): MountEmulatedStorage()
E/Zygote  ( 7051): v2
I/libpersona( 7051): KNOX_SDCARD checking this for 10078
I/libpersona( 7051): KNOX_SDCARD not a persona
I/ActivityManager(  751): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=7051 uid=10078 gids={50078, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/SELinux ( 7051): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7051): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
E/SELinux ( 7051): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/AndroidRuntime( 7034): Shutting down VM
D/KeyguardViewMediator( 1191): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
I/MotionRecognitionService(  751): Plugged
I/MotionRecognitionService(  751): setPowerConnected  = true
D/PointerIcon(  751): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  751): setMouseCustomIcon IconType is same.101
D/PointerIcon(  751): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  751): setHoveringSpenCustomIcon IconType is same.1
D/PersonaManager( 1191): isKioskContainerExistOnDevice
D/KeyguardViewMediator( 1191): doKeyguard: not showing because lockscreen is off
D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
D/TimaKeyStoreProvider( 7051): TimaSignature is unavailable
D/ActivityThread( 7051): Added TimaKeyStore provider
V/WindowOrientationListener(  751): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  751): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  751): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  751): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  751): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/ActivityManager(  751): Display changed displayId=0
D/SurfaceWidgetView( 1450): destroyHardwareResources():836600257
D/ConnectivityService(  751): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ResourcesManager( 7051): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
I/SurfaceFlinger(  266): id=8 Removed Mauncher (6/8)
I/SurfaceFlinger(  266): id=8 Removed Mauncher (-2/8)
I/WebViewFactory( 7051): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
D/ResourcesManager( 7051): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1753): [237392/8] Surface widget visibility changed visibility = false on instance = 1
V/ActivityThread( 1450): updateVisibility : ActivityRecord{24d7a2f token=android.os.BinderProxy@16672de8 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1450): onTrimMemory. Level: 20
I/LibraryLoader( 7051): Time to load native libraries: 3 ms (timestamps 3154-3157)
I/LibraryLoader( 7051): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7051): Binding Chromium to main looper Looper (main, tid 1) {33965142}
I/LibraryLoader( 7051): Expected native library version number "",actual native library version number ""
I/chromium( 7051): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7051): Initializing chromium process, singleProcess=true
,W/art     ( 7051): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7051): ApplicationContext is null in ApplicationStatus
,V/AlarmManager(  751): waitForAlarm result :8
,W/chromium( 7051): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,I/chromium( 7051): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
I/chromium( 7051): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,I/Adreno-EGL( 7051): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 7051): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7051): Build Date: 11/19/14 Wed
I/Adreno-EGL( 7051): Local Branch: mybranch5813579
I/Adreno-EGL( 7051): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 7051): Local Patches: NONE
I/Adreno-EGL( 7051): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,D/BluetoothAdapter( 7051): 265847727: getState() :  mService = null. Returning STATE_OFF
,W/chromium( 7051): [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,W/art     ( 7051): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 7051): onDetachedFromWindow called when already detached. Ignoring
,I/PowerManagerService(  751): [PWL] Off : 5s ago
,D/SystemWebViewEngine( 7051): CordovaWebView is running on device made by: samsung
,W/art     ( 7051): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7051): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager(  751): Activity pause timeout for ActivityRecord{2f2e6bdb u0 com.example.hello/.MainActivity t8}
,D/Activity( 7051): performCreate Call secproduct feature valuefalse
D/Activity( 7051): performCreate Call debug elastic valuetrue
,I/ServiceManager(  372): Waiting for service AtCmdFwd...
D/OpenGLRenderer( 7051): Render dirty regions requested: true
D/ActivityManager(  751): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler(  751): postActiveUserChange for user 0
I/KnoxTimeoutHandler(  751): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler(  751): handleActiveUserChange for user 0
D/PersonaManagerService(  751): getPersonasForUser(): returning null!
V/ActivityThread( 7051): updateVisibility : ActivityRecord{23fda83e token=android.os.BinderProxy@33494bc0 {com.example.hello/com.example.hello.MainActivity}} show : true
I/SurfaceFlinger(  266): id=12 createSurf (1x1),1 flag=404, NainActivit
D/StatusBarManagerService(  751): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  751): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon(  751): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  751): setMouseCustomIcon IconType is same.101
D/PointerIcon(  751): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  751): setHoveringSpenCustomIcon IconType is same.1
I/OpenGLRenderer( 7051): Initialized EGL, version 1.4
I/OpenGLRenderer( 7051): HWUI protection enabled for context ,  &this =0xb3c8bd80 ,&mEglDisplay = 1 , &mEglConfig = 8 
D/OpenGLRenderer( 7051): Enabling debug mode 0
D/InputMethodManagerService(  751): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/ContextImpl(  751): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/ActivityManager(  751): mDVFSHelper.release()
I/Timeline(  751): Timeline: Activity_windows_visible id: ActivityRecord{2f2e6bdb u0 com.example.hello/.MainActivity t8} time:83920
I/SamsungIME( 1692): getCurrentCandidateView
W/IInputConnectionWrapper( 7051): showStatusIcon on inactive InputConnection
I/Timeline( 7051): Timeline: Activity_idle id: android.os.BinderProxy@33494bc0 time:83989
W/BindingManager( 7051): Cannot call determinedVisibility() - never saw a connection for the pid: 7051
I/chromium( 7051): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
D/SamsungIME( 1692): Dismiss ExpandCandiate
,D/JsMessageQueue( 7051): Set native->JS mode to OnlineEventsBridgeMode
,E/AndroidProtocolHandler( 7051): Unable to open asset URL: file:///android_asset/www/jxcore.js
,I/SamsungIME( 1692): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1692): getDebugLevel  : 0x4f4c
,D/jxcore_app_log( 7051): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1357552384
,D/JX-Cordova( 7051): jxcore cordova android initializing
,I/SamsungIME( 1692): KeybaordView init() : load resources
,W/jxcore-log( 7051): Initializing JXcore engine
,W/jxcore-log( 7051): JXcore engine is ready
,I/SamsungIME( 1692): getCurrentKeyboard
,I/SamsungIME( 1692): getTextKeyboard
,W/jxcore-log( 7051): Starting JXcore engine
,D/SamsungIME( 1692): [SwiftkeyWrapper] currentLangauge : 1701729619
,I/ServiceManager(  372): Waiting for service AtCmdFwd...
,E/auditd  ( 1797): In denial and Property audit_ondenial is set to 1 
,E/audit   ( 1797): type=1400 msg=audit(1456842852.929:203): avc:  denied  { ioctl } for  pid=7051 comm="m.example.hello" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2886 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
D/SecurityLogAgent:SEDenialService(  751): Got Modify Event and sending Denial Intent foraudit.log
W/ContextImpl(  751): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
E/audit   ( 1797):  SEPF_SM-N9005_5.0-1_0032
E/audit   ( 1797): 
E/audit   ( 1797): type=1300 msg=audit(1456842852.929:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=bee71d58 items=0 ppid=344 ppcomm=main pid=7051 auid=4294967295 uid=10078 gid=10078 euid=10078 suid=10078 fsuid=10078 egid=10078 sgid=10078 fsgid=10078 tty=(none) ses=4294967295 comm="m.example.hello" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1797): type=1320 msg=audit(1456842852.929:203): 
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
D/SecurityLogAgent:SEDenialService(  751): audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,E/Zygote  ( 7125): MountEmulatedStorage()
E/Zygote  ( 7125): v2
I/libpersona( 7125): KNOX_SDCARD checking this for 1000
I/libpersona( 7125): KNOX_SDCARD not a persona
,I/ActivityManager(  751): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=7125 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7125): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7125): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
E/SELinux ( 7125): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/jxcore-log( 7051): Platform android
W/jxcore-log( 7051): 
W/jxcore-log( 7051): Process ARCH arm
W/jxcore-log( 7051): 
,D/TimaKeyStoreProvider( 7125): TimaSignature is unavailable
,D/ActivityThread( 7125): Added TimaKeyStore provider
,D/ResourcesManager( 7125): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/SecurityLogAgent( 7125):  SeDenialReceiver : Intent received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 7125):  SeDenialReceiver : File path = null
,I/ActivityManager(  751): Killing 5962:com.sec.android.app.music:service/u0a49 (adj 15): bgCount ##41
,I/jxcore-log( 7051): JXcore Cordova bridge is ready!
I/jxcore-log( 7051): 
,W/jxcore-log( 7051): JXcore engine is started
,E/jxcore-log( 7051): >> samsung-SM-N9005
E/jxcore-log( 7051): 
,I/jxcore-log( 7051): Total memory 2971471872
I/jxcore-log( 7051): 
I/jxcore-log( 7051): Free memory 339816448
I/jxcore-log( 7051): 
I/jxcore-log( 7051): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 7051): 
I/jxcore-log( 7051): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 7051): 
,I/jxcore-log( 7051): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 7051): 
,I/jxcore-log( 7051): Size 1080 1920
I/jxcore-log( 7051): 
,I/jxcore-log( 7051): Screen Brightness 162
I/jxcore-log( 7051): 
,E/jxcore-log( 7051): Dummy Error Log.
E/jxcore-log( 7051): 
,E/SMD     (  305): DCD ON
,D/SamsungIME( 1692): [SwiftkeyWrapper] currentLangauge : 1701729619
,I/jxcore-log( 7051): getBuffer is called!!!!
I/jxcore-log( 7051): 
,W/ContextImpl(  751): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/Atfwd_Sendcmd(  372): AtCmdFwd service not published, waiting... retryCnt : 5
,V/AlarmManager(  751): waitForAlarm result :4
,D/NtpTrustedTime(  751): forceRefresh() from cache miss
,D/NtpTrustedTime(  751): requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1456842853596 mCachedNtpElapsedRealtime : 86988 mCachedNtpCertainty : 55
,D/NtpTrustedTime(  751): currentTimeMillis() cache hit
,D/AlarmManagerService(  751): Setting time of day to sec=1456842853
,D/AlarmManagerService(  751): Trying to open a file
,D/AlarmManagerService(  751): File Open Success
,D/AlarmManagerService(  751): File Close Success
I/AlarmManagerService(  751): DRM_TIME_PATH CHMOD 666 for resetState done 
,V/AlarmManager(  751): waitForAlarm result :65536
,W/AlarmManagerService(  751): Unable to set rtc to 1456842853: Invalid argument
I/art     (  751): Explicit concurrent mark sweep GC freed 63428(3MB) AllocSpace objects, 22(1898KB) LOS objects, 30% free, 36MB/52MB, paused 1.614ms total 180.780ms
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.TIME_SET
D/WifiStateMachine(  751): android.intent.action.TIME_SET - start updateConfiguredNetworkExpiration()
D/KeyguardUpdateMonitor( 1191): handleTimeUpdate
,I/DowntimeConditions(  751): android.intent.action.TIME_SET ignored because schedule turned off.
D/KeyguardEffectViewController( 1191): onReceive action : android.intent.action.TIME_SET
,D/StatusBar-DoNotDistrub( 1191): Received intent with android.intent.action.TIME_SET action
,D/StatusBar-DoNotDistrub( 1191): Not data shared android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
W/Settings(  751): Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
,D/accuweather( 1753): [Accuweather J]>>> SWW:64 [0:0] =============== BR act = androidintentactionTIME_SET
,D/accuweather( 1753): [Accuweather J]>>> SWW:645 [0:0] renderUpdateAllCondition : [0] = 1
,D/accuweather( 1753): [Accuweather J]>>> WR:452 [0:0] =============== updateAllCondition = 1
,I/DrmEventService(  751):  no response from SecureClock 
,E/Zygote  ( 7172): MountEmulatedStorage()
,E/Zygote  ( 7172): v2
,I/libpersona( 7172): KNOX_SDCARD checking this for 10014
,I/libpersona( 7172): KNOX_SDCARD not a persona
,I/SELinux ( 7172): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7172): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,I/ActivityManager(  751): Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7172 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/StatusBar-DoNotDistrub( 1191): sendBroadcast android.intent.action.DORMANT_MODE_OFF
V/AudioPolicyManager(  311): getOutputsForDevice device 0002 -> 0002
I/AudioService(  751): getStreamVolume 5 index 0
D/StatusBar-DoNotDistrub( 1191): The STREAM NOTIFICATION volume is 0
D/StatusBarManagerService(  751): manageDisableList userId=0 what=0x0 pkg=com.android.systemui
,E/SELinux ( 7172): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/DateView( 1191): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1191): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/TimaKeyStoreProvider( 7172): TimaSignature is unavailable
,D/ActivityThread( 7172): Added TimaKeyStore provider
,D/ResourcesManager( 7172): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/FOTA_Client( 7172): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
,D/Finsky  ( 6310): [1045] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 6310): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,E/Zygote  ( 7192): MountEmulatedStorage()
,E/Zygote  ( 7192): v2
,I/libpersona( 7192): KNOX_SDCARD checking this for 10023
,I/libpersona( 7192): KNOX_SDCARD not a persona
,I/SELinux ( 7192): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7192): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,E/SELinux ( 7192): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  751): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=7192 uid=10023 gids={50023, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  751): Killing 6005:com.sec.android.app.myfiles/u0a56 (adj 15): bgCount ##41
,I/art     (  344): Explicit concurrent mark sweep GC freed 8735(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 955us total 43.290ms
,I/art     (  344): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 508us total 24.202ms
,I/art     (  344): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 516us total 16.681ms
,D/TimaKeyStoreProvider( 7192): TimaSignature is unavailable
,D/ActivityThread( 7192): Added TimaKeyStore provider
,D/ResourcesManager( 7192): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,I/KLMS-2.4.511: ( 7192): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.511: ( 7192): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.TIME_SET , timestamp: 1456842854367
,I/KLMS-2.4.511: ( 7192): MainReciver(): TIME_CHANGED
,I/KLMS-2.4.511: ( 7192): StateImplV2(): dateTimeChanged().START : Tue Mar 01 15:34:14 GMT+01:00 2016
,I/KLMS-2.4.511: ( 7192): StateImplV2(): dateTimeChanged().END
,I/ActivityManager(  751): Killing 6401:flipboard.app/u0a125 (adj 15): bgCount ##41
,W/System.err( 6499): android.provider.Settings$SettingNotFoundException: TIME_DIFFERENCE
,W/System.err( 6499): 	at android.provider.Settings$System.getLongForUser(Settings.java:1679)
,W/System.err( 6499): 	at android.provider.Settings$System.getLong(Settings.java:1669)
,W/System.err( 6499): 	at com.sec.android.sCloudSync.g.d.b(SourceFile:83)
,W/System.err( 6499): 	at com.sec.android.sCloudSync.Receivers.TimeChangedReceiver.onReceive(SourceFile:64)
W/System.err( 6499): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2989)
,W/System.err( 6499): 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
,W/System.err( 6499): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
W/System.err( 6499): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 6499): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 6499): 	at android.app.ActivityThread.main(ActivityThread.java:5938)
W/System.err( 6499): 	at java.lang.reflect.Method.invoke(Native Method)
,W/System.err( 6499): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6499): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
,W/System.err( 6499): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
,E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7215): MountEmulatedStorage()
E/Zygote  ( 7215): v2
,I/libpersona( 7215): KNOX_SDCARD checking this for 10042
,I/libpersona( 7215): KNOX_SDCARD not a persona
,I/ActivityManager(  751): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/com.sec.android.fota.osp.time.ServerTimeReceiver: pid=7215 uid=10042 gids={50042, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 7215): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7215): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,E/SELinux ( 7215): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,V/AlarmManager(  751): waitForAlarm result :8
,W/ProcessCpuTracker(  751): Skipping unknown process pid 7208
,W/ProcessCpuTracker(  751): Skipping unknown process pid 7209
W/ProcessCpuTracker(  751): Skipping unknown process pid 7211
,W/ProcessCpuTracker(  751): Skipping unknown process pid 7212
,D/TimaKeyStoreProvider( 7215): TimaSignature is unavailable
,D/ActivityThread( 7215): Added TimaKeyStore provider
,D/ResourcesManager( 7215): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/SO_AGENT( 7215): [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,I/SA      ( 6541): [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
,V/AlarmManager(  751): waitForAlarm result :8
,E/Zygote  ( 7237): MountEmulatedStorage()
E/Zygote  ( 7237): v2
I/libpersona( 7237): KNOX_SDCARD checking this for 10076
I/libpersona( 7237): KNOX_SDCARD not a persona
,I/SELinux ( 7237): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7237): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,E/SELinux ( 7237): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  751): Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=7237 uid=10076 gids={50076, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  751): Killing 6449:com.google.android.partnersetup/u0a19 (adj 13): bgCount ##41
,D/TimaKeyStoreProvider( 7237): TimaSignature is unavailable
,D/ActivityThread( 7237): Added TimaKeyStore provider
,E/SMD     (  305): DCD ON
,D/ResourcesManager( 7237): creating new AssetManager and set to /system/priv-app/sCloudDataSync/sCloudDataSync.apk
,D/SSRM:n  (  751): SIOP:: AP = 350, PST = 385, CUR = 450
,E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
,I/ Time Manager ( 7237): Time Difference not stored. TIME_DIFFERENCE
,E/Zygote  ( 7257): MountEmulatedStorage()
E/Zygote  ( 7257): v2
I/libpersona( 7257): KNOX_SDCARD checking this for 10106
I/libpersona( 7257): KNOX_SDCARD not a persona
,I/SELinux ( 7257): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7257): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,E/SELinux ( 7257): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  751): Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=7257 uid=10106 gids={50106, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  751): Killing 6467:com.samsung.groupcast/u0a20 (adj 13): bgCount ##41
,D/TimaKeyStoreProvider( 7257): TimaSignature is unavailable
,D/ActivityThread( 7257): Added TimaKeyStore provider
,D/ResourcesManager( 7257): creating new AssetManager and set to /system/app/ClockPackage_Osup/ClockPackage_Osup.apk
,W/ResourcesManager( 7257): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 7257): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7257): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/SettingsProvider(  751): name = next_alarm_formatted
D/SettingsProvider(  751): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  751): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  751): selectionArgs: false
D/SettingsProvider(  751): selectionArgs: 10106
D/SecContentProvider(  751): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  751): ret = -1
,E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  751): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7285 uid=10116 gids={50116, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  751): Killing 5699:com.sec.android.service.health/u0a21 (adj 13): bgCount ##41
,E/Zygote  ( 7285): MountEmulatedStorage()
,E/Zygote  ( 7285): v2
,I/libpersona( 7285): KNOX_SDCARD checking this for 10116
I/libpersona( 7285): KNOX_SDCARD not a persona
,I/SELinux ( 7285): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7285): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
E/SELinux ( 7285): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7285): TimaSignature is unavailable
,D/ActivityThread( 7285): Added TimaKeyStore provider
,D/ResourcesManager( 7285): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,D/elm:14491( 7285): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,D/elm:14491( 7285): ELMEngine.ELMEngine( context ).
,D/elm:14491( 7285): MDMBridge.setEnterpriseBridge()
,D/elm:14491( 7285): ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
,D/elm:14491( 7285): ElmAgentService : onCreate()
,D/elm:14491( 7285): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
,D/elm:14491( 7285): ELMAgentService.listeningToTimeDateChanges( context, intent ).
,D/elm:14491( 7285): ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
,D/elm:14491( 7285): ModuleBase.ModifySetAlarm()
,D/elm:14491( 7285): MDMBridge.getInstance()
,D/elm:14491( 7285): MDMBridge.getAllLicenseInfoFromSDK()
,E/Zygote  ( 7313): MountEmulatedStorage()
,I/libpersona( 7313): KNOX_SDCARD checking this for 10172
E/Zygote  ( 7313): v2
,I/libpersona( 7313): KNOX_SDCARD not a persona
,I/SELinux ( 7313): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7313): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,E/SELinux ( 7313): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  751): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=7313 uid=10172 gids={50172, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,D/elm:14491( 7285): ElmAgentService : onDestroy().
,I/ActivityManager(  751): Killing 6119:sstream.app/u0a25 (adj 13): bgCount ##41
,D/TimaKeyStoreProvider( 7313): TimaSignature is unavailable
,D/ActivityThread( 7313): Added TimaKeyStore provider
,D/ResourcesManager( 7313): creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
,W/ResourcesManager( 7313): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 7313): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7313): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7340): MountEmulatedStorage()
,E/Zygote  ( 7340): v2
I/libpersona( 7340): KNOX_SDCARD checking this for 10051
I/libpersona( 7340): KNOX_SDCARD not a persona
,I/ActivityManager(  751): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=7340 uid=10051 gids={50051, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 7340): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7340): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,E/SELinux ( 7340): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/BluetoothAdapter( 7051): disable()
,E/BluetoothManagerService(  751): Bluetooth is already disabled. DO NOT disable again.
,D/SecurityLogAgent( 7125): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 7125): KnoxConfiguration : Current State Mapping Found 
,I/WifiManager( 7051): packageName : com.example.hello
,D/SecurityLogAgent( 7125): StateMachine : Current State = 1
,D/SecContentProvider(  751): uri = 18 selection = isWifiEnabled
D/SecContentProvider2(  751): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  751): mCursor = null
,D/WifiService(  751): setWifiEnabled: false pid=7051, uid=10078
,D/SettingsProvider(  751): name = wifi_on
,D/ConnectivityService(  751): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  751): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
,E/WifiStateMachine(  751): WifiStateMachine: Leaving Connected state
,I/wpa_supplicant( 1303): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1303): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1303): P2P: Current p2p state = IDLE
I/jxcore-log( 7051): ****TEST TOOK:  3419  ms ****
I/jxcore-log( 7051): 
,I/jxcore-log( 7051): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7051): 
,I/wpa_supplicant( 1303): Scan requested (ret=0) - scan timeout 30 seconds
E/WifiConfigStore(  751): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/TimaKeyStoreProvider( 7340): TimaSignature is unavailable
,D/ActivityThread( 7340): Added TimaKeyStore provider
,E/native  (  751): do suspend true
,D/WifiP2pService(  751): InactiveState{ what=143375 }
D/WifiP2pService(  751): P2pEnabledState{ what=143375 }
,E/Zygote  ( 7360): MountEmulatedStorage()
,E/Zygote  ( 7360): v2
I/libpersona( 7360): KNOX_SDCARD checking this for 1000
I/libpersona( 7360): KNOX_SDCARD not a persona
,I/ActivityManager(  751): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=7360 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7360): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7360): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,E/SELinux ( 7360): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/CommandListener(  299): Clearing all IP addresses on wlan0
,E/ConnectivityService(  751): updateNetworkInfo()
,D/ConnectivityService(  751): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/ConnectivityService(  751): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,D/StatusBar.NetworkController( 1191): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1191): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,E/WifiConfigStore(  751): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/WifiTrafficPoller(  751): evaluateTrafficStatsPolling
,V/NativeCrypto( 1805): Read error: ssl=0x99c60e00: I/O error during system call, Connection timed out
,D/StatusBar.NetworkController( 1191): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1191): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
,E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
D/ConnectivityService(  751): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/NativeCrypto( 1805): SSL shutdown failed: ssl=0x99c60e00: I/O error during system call, Broken pipe
,D/StatusBar.NetworkController( 1191): applyOpen
D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1191): applyOpen
,D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1191): applyOpen
D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1191): applyOpen
,D/TimaKeyStoreProvider( 7360): TimaSignature is unavailable
,D/ActivityThread( 7360): Added TimaKeyStore provider
,E/GCM     ( 1805): Wifi connection closed with errorCode 20
,D/ConnectivityService(  751): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  751): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10015
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  751): ValidatedState{ when=0 what=532488 arg1=10015 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  751): DefaultState{ when=-1ms what=532488 arg1=10015 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  751): Forcing reevaluation
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  751): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  751): Checking http://clients3.google.com/generate_204 on <unknown ssid>
,I/System.out(  751): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid (  751): Tagging socket 287 with tag ffffffff00000000{4294967295,0} uid 10015, pid: 751, getuid(): 1000
,D/ConnectivityService(  751): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  751): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  751): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  751): Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.samsung.myplace.WIFINotificationHandler: pid=7380 uid=10038 gids={50038, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,E/Zygote  ( 7380): MountEmulatedStorage()
,E/Zygote  ( 7380): v2
,I/libpersona( 7380): KNOX_SDCARD checking this for 10038
I/libpersona( 7380): KNOX_SDCARD not a persona
,I/System.out(  751): (HTTPLog)-Static: isSBSettingEnabled false
,D/WifiNetworkAgent(  751): NetworkAgent: NetworkAgent channel lost
,D/WifiP2pService(  751): InactiveState{ what=131204 }
D/WifiP2pService(  751): P2pEnabledState{ what=131204 }
,D/WifiScanningService(  751): SCAN_AVAILABLE : 1
,D/RttService(  751): SCAN_AVAILABLE : 1
,D/WifiScanningService(  751): DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService(  751): EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  751): sending p2p connection changed broadcast: FAILED
,D/WifiP2pService(  751): sending p2p connection changed broadcast: DISCONNECTED
,D/WifiP2pService(  751): P2pDisablingState
,D/WifiP2pService(  751): P2pDisablingState{ what=147458 }
,D/WifiDisplayController(  751): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,D/WifiDisplayAdapter(  751): onP2pDisconnected
D/IpRemoteDisplayController(  751): disconnectWfdBridgeServer
,D/IpRemoteDisplayController(  751): WfdBridgeServer is already null
,D/WifiP2pService(  751): p2p socket connection lost
,D/WifiP2pService(  751): P2pDisabledState
,E/WifiStateMachine(  751): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
E/native  (  751): do suspend true
,D/WifiDisplayController(  751): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
,D/WifiDisplayController(  751): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,D/WifiDisplayController(  751): disconnect
D/WifiDisplayController(  751): updateConnection
D/WifiDisplayController(  751): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayAdapter(  751): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiP2pService(  751): P2pDisabledState{ what=143375 }
D/WifiP2pService(  751): DefaultState{ what=143375 }
,D/ConnectivityService(  751): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  751): calling update connectivity
D/ConnectivityService(  751):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  751): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/ConnectivityService(  751):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  751): Validated
,D/EntConnectivity(  751): Not allowed due to - mEnabled false
D/ConnectivityService(  751): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  751):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  751): sending notification LOST for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,V/Nat464Xlat(  751): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  751): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  751): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  751): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  751): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  751): Disconnected - quitting
,D/CSLegacyTypeTracker(  751): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.104/24,fe80::ea50:8bff:fede:28a3/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker(  751): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService(  751): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/CommandListener(  299): Clearing all IP addresses on wlan0
,D/ConnectivityService(  751): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,E/ConnectivityService(  751): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
E/ConnectivityService(  751): updateNetworkInfo()
E/ConnectivityService(  751): updateNetworkInfo()
D/ConnectivityService(  751): NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  751): ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
,D/Tethering(  751): MasterInitialState.processMessage what=3
E/ConnectivityService(  751): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.104/24,fe80::ea50:8bff:fede:28a3/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
,D/SmartBondingService(  751): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService(  751): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService(  751): getSBEnabled() enabled =false
D/SmartBondingService(  751): getSBEnabled() enabled =false
D/SmartBondingService(  751): getSBEnabled() enabled =false
,V/NetworkStats(  751): updateIfacesLocked()
,D/NtpTrustedTime(  751): currentTimeMillis() cache hit
V/NetworkStats(  751): performPollLocked(flags=0x1)
,D/NetworkStatsFactory(  751): UpdateStatsForKnox
,I/wpa_supplicant( 1303): p2p0: State: DISCONNECTED -> DISCONNECTED
D/ConnectivityService(  751): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/WifiTrafficPoller(  751): evaluateTrafficStatsPolling
,D/SecContentProvider2(  751): uri = 20 selection = getPromptCredentialsEnabled
D/SmartBondingService(  751): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,D/SecContentProvider2(  751): mCursor = null
,V/NetworkStats(  751): performPollLocked() took 10ms
I/SELinux ( 7380): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7380): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
D/NtpTrustedTime(  751): currentTimeMillis() cache hit
E/SELinux ( 7380): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ConnectivityManager.CallbackHandler( 1191): CM callback handler got msg 524292
D/ConnectivityManager.CallbackHandler( 2226): CM callback handler got msg 524292
,D/AllShareCastTile( 1191): action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,D/WifiDisplayAdapter(  751): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/AllShareCastTile( 1191): wifi display status changed! scanstate : 0, ActiveDisplayState : 0
D/SmartBondingService(  751): getNetworkEnabled : wifi : true mobile : true
D/NtpTrustedTime(  751): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1191): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1191): onWifiSignalChanged enabled=true enabledDesc:null
D/NtpTrustedTime(  751): currentTimeMillis() cache hit
D/NtpTrustedTime(  751): currentTimeMillis() cache hit
D/NtpTrustedTime(  751): currentTimeMillis() cache hit
D/NtpTrustedTime(  751): currentTimeMillis() cache hit
D/NtpTrustedTime(  751): currentTimeMillis() cache hit
V/NetworkStats(  751): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/TelephonyNetworkFactory( 1430): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/SmartBondingService(  751): getNetworkEnabled : wifi : false mobile : true
,D/StatusBar.NetworkController( 1191): getUpdateDataNetType(): 0
,D/StatusBar.NetworkController( 1191): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1191): updateDataNetType()
D/StatusBar.NetworkController( 1191): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1191): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1191): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1191): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1191): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1191): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/ResourcesManager( 7360): creating new AssetManager and set to /system/app/TimeService/TimeService.apk
D/STATUSBAR-WifiQuickSettingButton( 1191): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1191): applyOpen
,D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1191): applyOpen
,D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1191): applyOpen
,D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1191): applyOpen
,D/StatusBar.NetworkController( 1191): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1191): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 1191): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1191): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1191): applyOpen
D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1191): applyOpen
D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1191): applyOpen
D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1191): applyOpen
,D/STATUSBAR-WifiQuickSettingButton( 1191): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1191): Wifi onReceive(0)
,D/STATUSBAR-QSTileView( 1191): onStateChanged: Wi-Fi
D/HotspotTile( 1191): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/WifiCredService( 1316): Action received :android.net.wifi.WIFI_STATE_CHANGED
,D/HotspotTile( 1191): onReceive : 0, 0
,I/AudioService(  751): getStreamVolume 3 index 0
,D/ResourcesManager( 7340): creating new AssetManager and set to /system/priv-app/SecCalendarProvider/SecCalendarProvider.apk
,W/ResourcesManager( 7340): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/TimeService( 7360): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1456842857053
,D/        ( 7360): TimeServiceNative: User Time to be set is 1456842857053
D/QC-time-services( 7360): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 7360): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 7360): Lib:time_genoff_operation: pargs->ts_val = 1456842857053
,D/QC-time-services(  374): Daemon: Connection accepted:time_genoff
,D/QC-time-services( 7360): Lib:time_genoff_operation: Send to server  passed!!
D/TimaKeyStoreProvider( 7380): TimaSignature is unavailable
,D/QC-time-services(  374): Daemon:Received base = 2, unit = 1, operation = 0,value = 1456842857053
D/QC-time-services(  374): Daemon:genoff_opr: Base = 2, val = 1456842857053, operation = 0
,D/QC-time-services(  374): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS6/9/70 21:22:47
D/QC-time-services(  374): Daemon:Value read from RTC seconds = 16406567000
D/QC-time-services(  374): Daemon:new time 1456842857053 
D/QC-time-services(  374): Daemon: delta 1440436290053 genoff 1440436290053 
D/QC-time-services(  374): Daemon:genoff_persistent_update: Writing genoff = 1440436290053 to memory
D/QC-time-services(  374): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  374): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/ActivityThread( 7380): Added TimaKeyStore provider
,D/QC-time-services(  374): Updating the TOD offset
D/QC-time-services(  374): Daemon:genoff_persistent_update: Writing genoff = 1440436290053 to memory
D/QC-time-services(  374): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  374): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services(  374): Daemon:Update to modem bit set
D/QC-time-services(  374): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  374): Daemon: Base = 2, Value being sent to MODEM = 1124471490053
,E/QC-time-services( 7360): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,E/QC-time-services(  374): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,E/QC-time-services(  374): Daemon: Time-services: Waiting to acceptconnection
,I/wpa_supplicant( 1303): Blacklist: Clear (all) 
,I/ActivityManager(  751): Killing 6483:com.sec.pcw.device/1000 (adj 13): bgCount ##41
,D/AndroidRuntime( 7359): 
D/AndroidRuntime( 7359): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/comdaemonstockapp( 3596): [Daemon_Stock]>>> Stockclock_DaemonService.java:63 [0:0] onReceive: androidintentactionTIME_SET
D/comdaemonstockapp( 3596): [Daemon_Stock]>>> Stockclock_DaemonService.java:64 [0:0] appServiceStatus: 0
,D/comdaemonstockapp( 3596): [Daemon_Stock]>>> Stockclock_DaemonService.java:65 [0:0] [AR]: 0
D/AndroidRuntime( 7359): CheckJNI is OFF
D/comdaemonstockapp( 3596): [Daemon_Stock]>>> Stockclock_DaemonService.java:66 [0:0] [AR]: Next time = 0
,D/AndroidRuntime( 7359): readGMSProperty: start
D/AndroidRuntime( 7359): readGMSProperty: already setted!!
,D/AndroidRuntime( 7359): readGMSProperty: end
D/AndroidRuntime( 7359): addProductProperty: start
,D/daemonapp( 3596): [MSC_Accu_Daemon]>>> AWDS:70 [0:0] Act : androidintentactionTIME_SET, run:true
D/comsamsunglog( 3596): [MSC_Accu_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 3596): [MSC_Accu_Daemon]>>> daemonapp [Version : 150820735400 ] [ 1 ] 
D/comsamsunglog( 3596): [MSC_Accu_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 3596): [MSC_Accu_Daemon]>>> ====================================================================================================================
,D/daemonapp( 3596): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 3596): [MSC_Accu_Daemon]>>> AWDS:1099 [0:0] PakNme size = 1
D/daemonapp( 3596): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,D/daemonapp( 3596): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,D/daemonapp( 3596): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,D/daemonapp( 3596): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 3596): [MSC_Accu_Daemon]>>> AWDS:113 [0:0] SerStus:true,TmpS:1,AtRfr:3, checkCurrent: 0
,D/daemonapp( 3596): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/FileWriteThread_Telephony( 1430): FileWriteThread : threadType = 3
,D/daemonapp( 3596): [MSC_Accu_Daemon]>>> AWDS:1099 [0:0] PakNme size = 1
,D/daemonapp( 3596): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/packagename
D/FileWriteThread_Telephony( 1430): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1430): FileWriteThread : threadType = 3
,D/daemonapp( 3596): [MSC_Accu_Daemon]>>> AWDS:1099 [0:0] PakNme size = 1
,D/FileWriteThread_Telephony( 1430): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1430): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1430): FileWriteThread : threadType = 3
,D/ResourcesManager( 7380): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,D/FileWriteThread_Telephony( 1430): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1430): FileWriteThread : threadType = 3
,I/wpa_supplicant( 1303): p2p0: CTRL-EVENT-TERMINATING 
W/ResourcesManager( 7380): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
I/wpa_supplicant( 1303): CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
I/wpa_supplicant( 1303): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 1303): CTRL-EVENT-STATE-CHANGE id=1 state=0 BSSID=F4.99.3E SSID=4E47373030
I/wpa_supplicant( 1303): wlan0: State: DISCONNECTED -> DISCONNECTED
,D/FileWriteThread_Telephony( 1430): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1430): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1430): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1430): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1430): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1430): FileWriteThread : threadType = 3
,W/ContextImpl(  751): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/CheckinService( 2226): Checkin interval check for package: unspecified last checkin: 1456600421639 min interval config: 0 actual interval: 242435555
,I/CalendarProvider2( 7340): CalendarProvider2.onCreate() called
,E/AffinityControl( 7359): AffinityControl: registerfunction enter
,I/wpa_supplicant( 1303): Blacklist: Clear (all) 
,D/AndroidRuntime( 7359): Calling main entry com.android.commands.pm.Pm
,D/PackageManager(  751): START PACKAGE DELETE: observer{908970533}
D/PackageManager(  751): pkg{<packageName>}
D/PackageManager(  751): user{0}
D/PackageManager(  751): caller{2000}
D/PackageManager(  751): flags{3}
D/PersonaManagerService(  751): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  751): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  751): isFromApprovedUnInstaller: isApproved before exit: true
,D/PackageManager(  751): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager(  751): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
,D/PackageManager(  751): [MSG] DELETE_PACKAGE_AS_USER
,D/PackageManagerService(  751): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManagerService(  751): deletePackage- pkg:com.example.hello, edmuserId:-1
,D/ApplicationPolicy(  751): getApplicationUninstallationEnabled
D/ApplicationPolicy(  751): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager(  751): !@killApplicatoin: 10078, uninstall pkg
,I/ActivityManager(  751): Force stopping com.example.hello appid=10078 user=-1: uninstall pkg
I/ActivityManager(  751): Killing 7051:com.example.hello/u0a78 (adj 0): stop com.example.hello
,I/WindowState(  751): WIN DEATH: Window{2ce0363e u0 com.example.hello/com.example.hello.MainActivity}
I/SurfaceFlinger(  266): id=12 Removed NainActivit (6/8)
,I/SurfaceFlinger(  266): id=12 Removed NainActivit (-2/8)
,I/SurfaceFlinger(  266): id=12 Removed NainActivit (-2/8)
,D/PointerIcon(  751): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  751): setMouseCustomIcon IconType is same.101
D/PointerIcon(  751): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  751): setHoveringSpenCustomIcon IconType is same.1
,I/wpa_supplicant( 1303): wlan0: CTRL-EVENT-TERMINATING 
D/Tethering(  751): InitialState.processMessage what=4
,E/Tethering(  751): No numeric data
,D/ConnectivityService(  751): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  751):   Force finishing activity ActivityRecord{2f2e6bdb u0 com.example.hello/.MainActivity t8}
D/FocusedStackFrame(  751): Set to : 0
,W/ActivityManager(  751): Spurious death for ProcessRecord{2b487fa 7051:com.example.hello/u0a78}, curProc for 7051: null
I/ActivityManager(  751): Force stopping com.example.hello appid=10078 user=0: pkg removed
,I/ActivityManager(  751):   Force finishing activity ActivityRecord{2f2e6bdb u0 com.example.hello/.MainActivity t8 f}
W/ActivityManager(  751): Duplicate finish request for ActivityRecord{2f2e6bdb u0 com.example.hello/.MainActivity t8 f}
,I/art     ( 6621): Explicit concurrent mark sweep GC freed 328(25KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 15MB/20MB, paused 309us total 17.052ms
,I/art     ( 6745): Explicit concurrent mark sweep GC freed 4973(352KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 16MB/21MB, paused 314us total 22.981ms
,E/WifiStateMachine(  751): skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,D/WifiNative-HAL(  751): callSECApiBoolean - ID [21]
,D/Tethering(  751): sendTetherStateChangedBroadcast 0, 0, 0
,D/ConnectivityService(  751): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager(  751): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
I/art     ( 2226): Explicit concurrent mark sweep GC freed 3686(160KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 22MB/30MB, paused 645us total 56.255ms
,W/SQLiteConnectionPool( 2226): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,D/ResourcesManager(  751): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,W/GeofencerStateMachine( 1805): Ignoring removeGeofence because network location is disabled.
,W/Settings( 6842): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/SamsungIME( 1692): mOCRHelper is null
,D/NetworkChangeNotifierAutoDetect( 1614): Network connectivity changed, type is: 6
,D/NtpTrustedTime(  751): currentTimeMillis() cache hit
V/NetworkStats(  751): performPollLocked(flags=0x1)
,D/ResourcesManager( 1450): creating new AssetManager and set to /system/priv-app/StoryAlbumWidget/StoryAlbumWidget.apk
,I/InputReader(  751): Reconfiguring input devices.  changes=0x00000010
,D/NetworkStatsFactory(  751): UpdateStatsForKnox
,D/ConnectivityService(  751): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ResourcesManager( 1450): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 1450): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
D/ResourcesManager(  751): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,V/NetworkStats(  751): performPollLocked() took 5ms
D/NtpTrustedTime(  751): currentTimeMillis() cache hit
,D/ConnectivityService(  751): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/HotspotTile( 1191): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1191): updateTetherState():false, false
D/StatusBar.NetworkController( 1191): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/ResourcesManager(  751): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,D/STATUSBAR-WifiQuickSettingButton( 1191): onWifiSignalChanged enabled=false enabledDesc:null
D/NtpTrustedTime(  751): currentTimeMillis() cache hit
D/NtpTrustedTime(  751): currentTimeMillis() cache hit
D/STATUSBAR-WifiQuickSettingButton( 1191): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/STATUSBAR-WifiQuickSettingButton( 1191): Wifi onReceive(1)
D/STATUSBAR-QSTileView( 1191): onStateChanged: Wi-Fi
,D/WifiCredService( 1316): Action received :android.net.wifi.WIFI_STATE_CHANGED
D/ResourcesManager( 1450): creating new AssetManager and set to /system/app/AccuweatherPhone2013_H_LMR/AccuweatherPhone2013_H_LMR.apk
,D/HotspotTile( 1191): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/HotspotTile( 1191): onReceive : 1, 0
,D/RegisteredServicesCache( 1424): empty dynamic service
W/ResourcesManager( 1450): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1450): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1450): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
D/ResourcesManager( 1450): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
W/ResourcesManager( 1450): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1450): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
D/ResourcesManager(  751): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,I/art     ( 5943): Explicit concurrent mark sweep GC freed 32320(1796KB) AllocSpace objects, 8(128KB) LOS objects, 40% free, 15MB/26MB, paused 368us total 77.509ms
,D/ResourcesManager(  751): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ConnectivityService(  751): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager(  751): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,W/Settings( 1805): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/ResourcesManager(  751): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager(  751): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager(  751): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager(  751): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,I/VlingoApplication( 7380): VlingoApplication appVersion ='11.2.2.0.37791', ro.csc.sales_code=XEO
,D/ResourcesManager(  751): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager(  751): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,D/ResourcesManager(  751): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/SecContentProvider2(  751): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  751): mCursor = null
,D/ResourcesManager(  751): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
,D/ResourcesManager(  751): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager(  751): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager(  751): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager(  751): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(  751): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  751): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  751): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
E/WifiStateMachine(  751): skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
D/ResourcesManager(  751): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager(  751): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager(  751): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/ActivityManager(  751): Killing 6168:com.samsung.android.app.galaxyfinder/u0a39 (adj 15): bgCount ##41
,D/ResourcesManager(  751): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(  751): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager(  751): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/ResourcesManager(  751): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,V/AlarmManager(  751): waitForAlarm result :8
,D/ResourcesManager(  751): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/RCPManagerService(  751): PackageReceiver onReceive()
,I/HarmonyEASService(  751): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/ResourcesManager(  751): creating new AssetManager and set to /system/app/talkback/talkback.apk
,D/KnoxMUMContainerPolicy(  751): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/BackupManagerService(  751): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,D/JobSchedulerService(  751): Receieved: android.intent.action.PACKAGE_REMOVED
,V/EnterpriseBillingPolicy(  751): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  751): uID is 10078
V/EnterpriseBillingPolicy(  751): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  751): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage(  751): getProfileForApplication - exit null
,V/EnterpriseBillingPolicy(  751): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  751): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  751): getBillingProfileForVpnEngine - start - com.example.hello
,V/EnterpriseBillingPolicyStorage(  751): getBillingProfileForVpnEngine - end - null
,D/TaskPersister(  751): removeObsoleteFile: deleting file=8_task.xml
,D/SSRM:aV (  751): MSG_TYPE_APP_REMOVED::
,D/SmartBondingService(  751): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  751): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  751): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  751): getSBEnabled() enabled =false
D/SmartBondingService(  751): getSBEnabled() enabled =false
D/SmartBondingService(  751): getSBEnabled() enabled =false
D/SmartBondingService(  751): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,V/AlarmManagerEXT(  751): com.example.hello(10078) is removed.
,D/SmartBondingService(  751): getNetworkEnabled : wifi : false mobile : true
D/SmartBondingService(  751): getNetworkEnabled : wifi : false mobile : true
,D/BluetoothAdapter( 7380): 607597053: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 7380): 607597053: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 7380): 607597053: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 7380): 607597053: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 7380): 607597053: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 7380): 607597053: getState() :  mService = null. Returning STATE_OFF
,D/EnterpriseDeviceManagerService(  751): Package has changed for user 0
D/EnterpriseDeviceManagerService(  751): Admin package name: com.google.android.gms
,I/ApplicationPolicy(  751): updateDataUsageMap
,I/art     (  751): Explicit concurrent mark sweep GC freed 56216(3MB) AllocSpace objects, 11(224KB) LOS objects, 30% free, 36MB/52MB, paused 1.689ms total 303.704ms
,D/ResourcesManager(  751): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager(  751): creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
,W/Resources(  751): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  751): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,E/SMD     (  305): DCD ON
,W/Resources(  751): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  751): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(  751): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/PackageManager(  751): delete codoeFile: 
,D/AASAuninstall(  751): userId = 0, info.removedAppID = -1, info.uid = 10078, packageName = com.example.hello
,I/AASA_removePackage(  751): UID=10078 Target=com.example.hello
,D/PackageManager(  751): result of delete: 1{908970533}
D/ResourcesManager(  751): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/AndroidRuntime( 7359): Shutting down VM
,W/Resources(  751): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  751): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager(  751): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,E/BluetoothHeadset( 7380): BTStateChangeCB is registed
,W/Resources(  751): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/BluetoothHeadset( 7380): BluetoothHeadset service is binded
,D/ResourcesManager(  751): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,I/ActivityManager(  751): Killing 4919:com.sec.spp.push/u0a43 (adj 15): bgCount ##41
,D/NearbySettings( 1316): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1316): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  751): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/Resources(  751): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  751): creating new AssetManager and set to /system/priv-app/SamsungLink20/SamsungLink20.apk
,I/NearbySettings( 1316): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  751): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1316): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings( 1316): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1316): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1316): MountReceiver.mPrefHandler - 7002
,D/ConnectivityService(  751): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/Resources(  751): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  751): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  751): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,E/SignOutReceiver( 6745): NETWORK_STATE_CHANGED_ACTION
,D/SettingsProvider(  751): name = driving_mode_on
D/SettingsProvider(  751): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  751): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  751): selectionArgs: false
D/SettingsProvider(  751): selectionArgs: 10038
D/SecContentProvider(  751): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  751): ret = -1
,D/BluetoothManager( 7380): [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.media.ACTION_SCO_AUDIO_STATE_UPDATED
,W/Resources(  751): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  751): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  751): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/NearbySettings( 1316): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,V/NearbySettings( 1316): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  751): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1316): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  751): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1316): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings( 1316): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1316): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1316): MountReceiver.mPrefHandler - 7002
,E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(  751): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(  751): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,W/Resources(  751): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  751): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(  751): creating new AssetManager and set to /system/app/Peel_L/Peel_L.apk
,D/ResourcesManager(  751): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,W/Resources(  751): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  751): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  751): creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
,W/ResourcesManager(  751): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(  751): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  751): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources(  751): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  751): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager(  751): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,D/ResourcesManager(  751): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  751): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources(  751): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  751): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  751): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
,W/Resources(  751): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  751): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  751): creating new AssetManager and set to /system/priv-app/SecMyFiles2/SecMyFiles2.apk
,W/Resources(  751): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  751): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources(  751): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  751): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  751): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/Resources(  751): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  751): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  751): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/Resources(  751): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/Zygote  ( 7435): MountEmulatedStorage()
E/Zygote  ( 7435): v2
I/libpersona( 7435): KNOX_SDCARD checking this for 10088
I/libpersona( 7435): KNOX_SDCARD not a persona
,I/ActivityManager(  751): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7435 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UsbSettingsManager(  751): clearDefaults: com.example.hello
,I/SELinux ( 7435): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7435): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
I/CrashAnrDetector(  751): onPackageRemoved : com.example.hello
,E/SELinux ( 7435): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/GpsLocationProvider(  751): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  751): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/TimaKeyStoreProvider( 7435): TimaSignature is unavailable
,D/ActivityThread( 7435): Added TimaKeyStore provider
,D/ResourcesManager( 7435): creating new AssetManager and set to /system/app/AllshareFileShareServer/AllshareFileShareServer.apk
,D/SurfaceWidgetView( 1450): destroyHardwareResources():836600257
,V/WindowOrientationListener(  751): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  751): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  751): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  751): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  751): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
,D/Launcher( 1450): onRestart, Launcher: 265847727
,D/Launcher( 1450): onStart, Launcher: 265847727
D/Launcher.HomeView( 1450): onStart
,V/ActivityThread( 1450): updateVisibility : ActivityRecord{24d7a2f token=android.os.BinderProxy@16672de8 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/FileShare-Server( 7435): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 1753): [237392/8] Surface widget visibility changed visibility = true on instance = 1
,D/SurfaceWidget.Renderer( 1753): [237392/8] SurfaceWidget drawing first frame
D/accuweather( 1753): [Accuweather J]>>> WR:623 [0:0] onGLDraw : BG texture = 5
,E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
,I/SurfaceFlinger(  266): id=13 createSurf (1080x1920),1 flag=4, Mauncher
,D/StatusBarManagerService(  751): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService(  751): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon(  751): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  751): setMouseCustomIcon IconType is same.101
D/PointerIcon(  751): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  751): setHoveringSpenCustomIcon IconType is same.1
,D/InputMethodManagerService(  751): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService(  751): Got RemoteException sending setActive(false) notification to pid 7051 uid 10078
,W/ContextImpl(  751): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Zygote  ( 7454): MountEmulatedStorage()
E/Zygote  ( 7454): v2
I/libpersona( 7454): KNOX_SDCARD checking this for 10192
I/libpersona( 7454): KNOX_SDCARD not a persona
,I/ActivityManager(  751): Start proc com.samsung.shareshot for broadcast com.samsung.shareshot/.WifiDirectBroadcastReceiver: pid=7454 uid=10192 gids={50192, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  751): Killing 6515:com.samsung.android.sdk.samsunglink/u0a48 (adj 15): bgCount ##41
,I/SELinux ( 7454): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7454): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,E/SELinux ( 7454): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7454): TimaSignature is unavailable
,I/Timeline(  751): Timeline: Activity_windows_visible id: ActivityRecord{108dfe0f u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t7} time:91635
D/ActivityThread( 7454): Added TimaKeyStore provider
,D/ResourcesManager( 7454): creating new AssetManager and set to /system/app/ShareShotService/ShareShotService.apk
,D/WifiDirectBR( 7454): WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,D/WifiDirectBR( 7454): WifiDirectBroadcastReceiver::onReceive(), Action : WifiP2pManager.WIFI_P2P_CONNECTION_CHANGED_ACTION, isConnected() == false
,W/ContextImpl( 7454): Implicit intents with startService are not safe: Intent { act=com.samsung.shareshot.IShareShotService } android.content.ContextWrapper.stopService:538 android.content.ContextWrapper.stopService:538 com.samsung.shareshot.WifiDirectBroadcastReceiver.onReceive:59 
,D/WifiDirectBR( 7454): stopServiceTest : false
,D/WifiDirectBR( 7454): WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.STATE_CHANGED
,I/ActivityManager(  751): Killing 5981:com.sec.android.gallery3d/u0a53 (adj 13): bgCount ##41
,D/NearbySettings( 1316): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1316): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  751): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1316): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,E/SQLiteLog( 7380): (28) failed to open "/data/data/com.vlingo.midas/databases/myPlaceSvoiceDatabase" with flag (131138) and mode_t (0) due to error (30)
D/ConnectivityService(  751): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1316): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings( 1316): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1316): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1316): MountReceiver.mPrefHandler - 7002
,E/SQLiteDatabase( 7380): Failed to open database '/data/data/com.vlingo.midas/databases/myPlaceSvoiceDatabase'.
E/SQLiteDatabase( 7380): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7380): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7380): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 7380): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 7380): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7380): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7380): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7380): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 7380): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 7380): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 7380): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteDatabase( 7380): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 7380): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7380): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 7380): 	at com.samsung.myplace.SVoiceMyPlaceDBProvider.getSelectedMyPlaceDataList(SVoiceMyPlaceDBProvider.java:161)
E/SQLiteDatabase( 7380): 	at com.samsung.myplace.WIFINotificationHandler$2.run(WIFINotificationHandler.java:84)
,E/SQLiteOpenHelper( 7380): Couldn't open myPlaceSvoiceDatabase for writing (will try read-only):
E/SQLiteOpenHelper( 7380): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7380): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7380): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 7380): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 7380): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 7380): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 7380): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 7380): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper( 7380): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper( 7380): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 7380): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteOpenHelper( 7380): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 7380): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 7380): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 7380): 	at com.samsung.myplace.SVoiceMyPlaceDBProvider.getSelectedMyPlaceDataList(SVoiceMyPlaceDBProvider.java:161)
E/SQLiteOpenHelper( 7380): 	at com.samsung.myplace.WIFINotificationHandler$2.run(WIFINotificationHandler.java:84)
D/ConnectivityService(  751): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/SQLiteOpenHelper( 7380): Opened myPlaceSvoiceDatabase in read-only mode
E/SignOutReceiver( 6745): NETWORK_STATE_CHANGED_ACTION
E/SignOutReceiver( 6745): WIFI_STATE_CHANGED_ACTION
D/ConnectivityService(  751): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SecurityLogAgent( 7125): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 7125): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7125): StateMachine : Current State = 1
D/SecurityLogAgent( 7125): StateMachine : Changed Current State = 1
I/KLMS-2.4.511: ( 7192): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/KLMS-2.4.511: ( 7192): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1456842858323
I/KLMS-2.4.511: ( 7192): MainReciver(): PACKAGE_REMOVED
I/KLMS-2.4.511: ( 7192): MainReciver(): REPLACING: false | pkgName: com.example.hello
I/EventHub(  751): Removing device '/dev/input/event6' due to inotify event
,D/elm:14491( 7285): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,I/EventHub(  751): Removing device '/dev/input/event7' due to inotify event
,D/elm:14491( 7285): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/AASAservice-UpdateReceiver( 3669): AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.example.hello, uid = -1
,W/System.err( 3669): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
W/System.err( 3669): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:304)
W/System.err( 3669): 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
W/System.err( 3669): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2989)
W/System.err( 3669): 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
W/System.err( 3669): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
W/System.err( 3669): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3669): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3669): 	at android.app.ActivityThread.main(ActivityThread.java:5938)
W/System.err( 3669): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3669): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3669): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
W/System.err( 3669): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
,E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
,D/elm:14491( 7285): ElmAgentService : onCreate()
,D/elm:14491( 7285): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14491( 7285): MainReceiver.listeningToPackageRemoved()
D/elm:14491( 7285): MDMBridge.getInstance()
D/elm:14491( 7285): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:14491( 7285): MDMBridge.getAllLicenseInfoFromSDK()
,I/EventHub(  751): Removing device '/dev/input/event8' due to inotify event
,I/ActivityManager(  751): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=7475 uid=10021 gids={50021, 9997} abi=armeabi-v7a
,E/Zygote  ( 7475): MountEmulatedStorage()
,E/Zygote  ( 7475): v2
I/libpersona( 7475): KNOX_SDCARD checking this for 10021
,I/libpersona( 7475): KNOX_SDCARD not a persona
,D/elm:14491( 7285): ElmAgentService : onDestroy().
,I/EventHub(  751): Removing device '/dev/input/event9' due to inotify event
,I/art     (  344): Explicit concurrent mark sweep GC freed 8728(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 4.111ms total 20.181ms
,I/art     (  344): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 274us total 9.567ms
,I/SELinux ( 7475): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
E/SELinux ( 7475): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     (  344): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 273us total 11.478ms
,I/EventHub(  751): Removing device '/dev/input/event10' due to inotify event
,D/TimaKeyStoreProvider( 7475): TimaSignature is unavailable
D/ActivityThread( 7475): Added TimaKeyStore provider
,D/ResourcesManager( 7475): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,W/ContextImpl( 7475): Unable to create files subdir /data/data/com.sec.android.service.health/cache
E/ActivityThread( 7475): Unable to setupGraphicsSupport due to missing cache directory
,D/com.sec.android.service.health.upgrade.UninstallReceiver( 7475): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 7475): onReceive called  PACKAGE_REMOVED package:com.example.hello
,D/com.sec.android.service.health.upgrade.UninstallReceiver( 7475): onReceive() : package name is not s health. Return !!!
,E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  751): checkUser: useridlist=null, currentuser=0
,I/EventHub(  751): Removing device '/dev/input/event11' due to inotify event
,E/Zygote  ( 7490): MountEmulatedStorage()
I/libpersona( 7490): KNOX_SDCARD checking this for 10025
E/Zygote  ( 7490): v2
I/libpersona( 7490): KNOX_SDCARD not a persona
,I/ActivityManager(  751): Start proc sstream.app for broadcast sstream.app/.receiver.ApplicationCompatibleReceiver: pid=7490 uid=10025 gids={50025, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  751): Killing 6588:com.sec.android.provider.badge/u0a92 (adj 13): bgCount ##41
,I/EventHub(  751): Removing device '/dev/input/event12' due to inotify event
,I/SELinux ( 7490): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
E/SELinux ( 7490): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7490): TimaSignature is unavailable
,D/ActivityThread( 7490): Added TimaKeyStore provider
,I/EventHub(  751): Removing device '/dev/input/event13' due to inotify event
,D/ResourcesManager( 7490): creating new AssetManager and set to /system/priv-app/MagazineHome/MagazineHome.apk
,W/ResourcesManager( 7490): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ContextImpl( 7490): Unable to create files subdir /data/data/sstream.app/cache
E/ActivityThread( 7490): Unable to setupGraphicsSupport due to missing cache directory
,I/EventHub(  751): Removing device '/dev/input/event14' due to inotify event
,I/CalendarProvider2( 7340): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,I/ActivityManager(  751): Killing 6603:com.sec.android.app.soundalive/u0a64 (adj 13): bgCount ##41
,W/linker  ( 7490): libdmcAlwaysFD.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,D/MVFD_interface( 7490): <<<  caMVFace_FaceInit
,E/SharedPreferencesImpl( 7490): Couldn't create directory for SharedPreferences file /data/data/sstream.app/shared_prefs/uid-prefs.xml
,E/SharedPreferencesImpl( 7490): Couldn't create directory for SharedPreferences file /data/data/sstream.app/shared_prefs/uid-prefs.xml
,E/SharedPreferencesImpl( 7490): Couldn't create directory for SharedPreferences file /data/data/sstream.app/shared_prefs/uid-prefs.xml
,E/SharedPreferencesImpl( 7490): Couldn't create directory for SharedPreferences file /data/data/sstream.app/shared_prefs/uid-prefs.xml
,E/SharedPreferencesImpl( 7490): Couldn't create directory for SharedPreferences file /data/data/sstream.app/shared_prefs/shared_prefs.xml
,E/Vold    (  265): Failed to find mounted volume for /storage/extSdCard/Android/data/sstream.app/cache/
W/Vold    (  265): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7490): Failed to ensure directory: /storage/extSdCard/Android/data/sstream.app/cache
,E/Vold    (  265): Failed to find mounted volume for /storage/extSdCard/Android/data/sstream.app/cache/
W/Vold    (  265): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7490): Failed to ensure directory: /storage/extSdCard/Android/data/sstream.app/cache
W/ContextImpl( 7490): Unable to create files subdir /data/data/sstream.app/cache
,W/ContextImpl( 7490): Unable to create files subdir /data/data/sstream.app/cache
,E/Volley  ( 7490): [1226] DiskBasedCache.initialize: Unable to create cache dir /volley
,W/FileUtils( 7490): Failed to chmod(/data/data/sstream.app/app_usage): android.system.ErrnoException: chmod failed: ENOENT (No such file or directory)
,E/SharedPreferencesImpl( 7490): Couldn't create directory for SharedPreferences file /data/data/sstream.app/shared_prefs/shared_prefs.xml
E/File    ( 7490): fail readDirectory() errno=2
,D/AndroidRuntime( 7490): Shutting down VM
,I/qdhwcomposer(  266): handle_blank_event: dpy:0 panel power state: 0

```
