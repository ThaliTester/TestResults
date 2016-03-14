#### Test 625090944a5472b_thali06_samsung-SM-A300FU Logs


```
--------- beginning of main,
I/ServiceManager(  327): Waiting for service AtCmdFwd...
D/AndroidRuntime( 6354): 
D/AndroidRuntime( 6354): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6354): CheckJNI is OFF
D/AndroidRuntime( 6354): readGMSProperty: start
D/AndroidRuntime( 6354): readGMSProperty: already setted!!
D/AndroidRuntime( 6354): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6354): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6354): readGMSProperty: end
D/AndroidRuntime( 6354): addProductProperty: start
E/AffinityControl( 6354): AffinityControl: registerfunction enter
D/AndroidRuntime( 6354): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1018): inState():  stateMachine is null !!
I/PersonaManagerService( 1018): PersonaId don't exist
I/ActivityManager( 1018): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
W/ActivityManager( 1018): mDVFSHelper.acquire()
D/FocusedStackFrame( 1018): Set to : 0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1018): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1018): *FMB* installDecor flags : -2122120936
E/Zygote  ( 6366): MountEmulatedStorage()
E/Zygote  ( 6366): v2
I/libpersona( 6366): KNOX_SDCARD checking this for 10167
I/libpersona( 6366): KNOX_SDCARD not a persona
I/SELinux ( 6366): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 6366): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1018): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6366 uid=10167 gids={50167, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1018): Focused application set to: xxxx
D/InputDispatcher( 1018): Focus left window: 1498
D/AndroidRuntime( 6354): Shutting down VM
E/SELinux ( 6366): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PhoneWindow( 1018): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1018): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  259): id=12 createSurf (1x1),1 flag=404, uhalitest
D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
D/TimaKeyStoreProvider( 6366): TimaSignature is unavailable
D/ActivityThread( 6366): Added TimaKeyStore provider
V/WindowManager( 1018): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
D/StatusBarManagerService( 1018): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1018): isKioskContainerExistOnDevice
D/WindowOrientationListener( 1018):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
I/SurfaceFlinger(  259): id=9 Removed Mauncher (5/9)
I/SurfaceFlinger(  259): id=9 Removed Mauncher (-2/9)
V/ActivityThread( 1498): updateVisibility : ActivityRecord{2e303372 token=android.os.BinderProxy@2cb80920 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1498): onTrimMemory. Level: 20
I/WebViewFactory( 6366): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
I/LibraryLoader( 6366): Time to load native libraries: 1 ms (timestamps 8138-8139)
I/LibraryLoader( 6366): Expected native library version number "",actual native library version number ""
W/art     ( 6354): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,V/WebViewChromiumFactoryProvider( 6366): Binding Chromium to main looper Looper (main, tid 1) {2b14176b}
I/LibraryLoader( 6366): Expected native library version number "",actual native library version number ""
I/chromium( 6366): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6366): Initializing chromium process, singleProcess=true
W/art     ( 6366): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6366): ApplicationContext is null in ApplicationStatus
W/chromium( 6366): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6366): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6366): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6366): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6366): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6366): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6366): Local Branch: 
I/Adreno-EGL( 6366): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6366): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6366):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
E/Watchdog( 1018): !@Sync 7
W/Atfwd_Sendcmd(  327): AtCmdFwd service not published, waiting... retryCnt : 1
W/art     ( 6366): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6366): onDetachedFromWindow called when already detached. Ignoring
D/PhoneWindow( 6366): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 6366): *FMB* installDecor flags : -2139027200
D/SystemWebViewEngine( 6366): CordovaWebView is running on device made by: samsung
W/art     ( 6366): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6366): Attempt to remove local handle scope entry from IRT, ignoring
W/ActivityManager( 1018): Activity pause timeout for ActivityRecord{3b79fc34 u0 com.test.thalitest/.MainActivity t23}
D/OpenGLRenderer( 6366): Render dirty regions requested: true
D/ActivityManager( 1018): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1018): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1018): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1018): handleActiveUserChange for user 0
D/PersonaManagerService( 1018): getPersonasForUser(): returning null!
W/chromium( 6366): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
V/ActivityThread( 6366): updateVisibility : ActivityRecord{176ef0d3 token=android.os.BinderProxy@286a8b0d {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
D/PhoneWindow( 6366): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 6366): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  259): id=13 createSurf (1x1),1 flag=404, NainActivit
D/InputDispatcher( 1018): Focus entered window: 6366
D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
D/SRIB_DCS( 6366): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 6366): Initialized EGL, version 1.4
D/OpenGLRenderer( 6366): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 6366): Enabling debug mode 0
D/InputMethodManagerService( 1018): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
I/StatusBar( 1178): Icon Only
D/PanelView( 1178): There is/are notification(s) 
W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/ActivityManager( 1018): Displayed Component not be shown by security: +703ms (total +1m51s775ms)
I/Timeline( 1018): Timeline: Activity_windows_visible id: ActivityRecord{3b79fc34 u0 com.test.thalitest/.MainActivity t23} time:228694
W/ActivityManager( 1018): mDVFSHelper.release()
W/IInputConnectionWrapper( 6366): showStatusIcon on inactive InputConnection
I/Timeline( 6366): Timeline: Activity_idle id: android.os.BinderProxy@286a8b0d time:228700
I/SurfaceFlinger(  259): id=12 Removed uhalitest (7/9)
I/SurfaceFlinger(  259): id=12 Removed uhalitest (-2/9)
I/SamsungIME( 1863): getCurrentCandidateView
D/SamsungIME( 1863): Dismiss ExpandCandiate
I/SamsungIME( 1863): getDebugLevel  : 0x4f4c
I/SamsungIME( 1863): getDebugLevel  : 0x4f4c
I/SamsungIME( 1863): KeybaordView init() : load resources
W/BindingManager( 6366): Cannot call determinedVisibility() - never saw a connection for the pid: 6366
I/SamsungIME( 1863): getCurrentKeyboard
I/SamsungIME( 1863): getTextKeyboard
D/SamsungIME( 1863): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/JsMessageQueue( 6366): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6366): JniHelper::setJavaVM(0xb86e1448), pthread_self() = -1195096096
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6366): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6366):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6366):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6366):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6366):     - Handshake required: true
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6366): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1df39140 added. We now have 1 listener(s)
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6366): setBluetoothMacAddress: 08:EC:A9:50:75:41
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6366): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"08:EC:A9:50:75:41"}
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6366): setIdentityString: {"name":"<no peer name>","address":"08:EC:A9:50:75:41"}
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6366): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6366): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6366): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6366):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6366):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6366):     - Bluetooth MAC address: 08:EC:A9:50:75:41
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6366):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6366):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6366):     - Advertise mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6366):     - Advertise TX power level: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6366):     - Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6366):     - Scan report delay in milliseconds: 500
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6366): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f24da1f added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6366): addListener: New listener added - the number of listeners is now 1
,V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6366): isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6366): setDiscoveryMode: Discovery mode BLE is supported
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6366): setAdvertiseMode: 1 -> 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6366): setAdvertiseTxPowerLevel: 2 -> 3
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6366): setScanMode: 1 -> 2
,I/chromium( 6366): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,W/jxcore-log( 6366): Initializing JXcore engine,
W/jxcore-log( 6366): JXcore engine is ready
,I/art     ( 6366): Background sticky concurrent mark sweep GC freed 44551(4MB) AllocSpace objects, 0(0B) LOS objects, 0% free, 20MB/20MB, paused 5.062ms total 41.767ms
,E/audit   ( 1873): type=1400 msg=audit(1457941992.193:205): avc:  denied  { ioctl } for  pid=6417 comm="Thread-1105" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1873):  SEPF_SM-A300FU_5.0.2_0027
,E/audit   ( 1873): type=1300 msg=audit(1457941992.193:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=2 a3=9ecfd8f8 items=0 ppid=314 ppcomm=main pid=6417 auid=4294967295 uid=10167 gid=10167 euid=10167 suid=10167 fsuid=10167 egid=10167 sgid=10167 fsgid=10167 ses=4294967295 tty=(none) comm="Thread-1105" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1873): type=1320 msg=audit(1457941992.193:205): 
,W/jxcore-log( 6366): Starting JXcore engine
,W/jxcore-log( 6366): Platform android
W/jxcore-log( 6366): 
W/jxcore-log( 6366): Process ARCH arm
W/jxcore-log( 6366): 
,I/jxcore-log( 6366): JXcore Cordova bridge is ready!
I/jxcore-log( 6366): 
,W/jxcore-log( 6366): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 6366): execute: REQUEST_ACCESS_COARSE_LOCATION
,I/chromium( 6366): [INFO:CONSOLE(47)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (47)
,E/jxcore  ( 6366): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 6366): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 6366): [INFO:CONSOLE(62)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (62)
,I/chromium( 6366): [INFO:CONSOLE(33)] "****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****", source: file:///android_asset/www/js/thali_main.js (33)
,D/FocusedStackFrame( 1018): Set to : 0
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
D/InputDispatcher( 1018): Focused application set to: xxxx
D/InputDispatcher( 1018): Focus left window: 6366
D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
I/ActivityManager( 1018): Killing 5124:com.android.providers.calendar/u0a37 (adj 15): empty #31
,W/PluginManager( 6366): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 22ms. Plugin should use CordovaInterface.getThreadPool().
,I/SurfaceFlinger(  259): id=13 Removed NainActivit (6/8)
,I/SurfaceFlinger(  259): id=13 Removed NainActivit (-2/8)
,W/ActivityManager( 1018): mDVFSHelper.acquire()
V/WindowManager( 1018): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,D/Launcher( 1498): onRestart, Launcher: 212486790
,D/Launcher( 1498): onStart, Launcher: 212486790
,D/Launcher.HomeView( 1498): onStart
D/Launcher( 1498): onResume, Launcher: 212486790
,D/SettingsProvider( 1018): name = kids_home_mode
,D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
,D/SettingsProvider( 1018): selectionArgs: 10006
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1018): ret = -1
D/Launcher.HomeView( 1498): onResume
,D/Launcher( 1498): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/MenuAppsGridFragment( 1498): onResume
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
,D/ActivityManager( 1018): handle home activity for 0
,I/WallpaperManagerService( 1018): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler( 1018): post home show event for user 0
D/ActivityManager( 1018): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1018): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1018): postActiveUserChange, showWhenLocked: false
,D/Launcher.HomeView( 1498): onPause
D/WallpaperManagerService( 1018):  force update = false; persona id = 0; current user =0; current persona = 0
,D/KnoxTimeoutHandler( 1018): handleHomeShow for 0 and current 0
D/Launcher( 1498): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
D/KnoxTimeoutHandler( 1018): handleActiveUserChange for user 0
D/PersonaManagerService( 1018): getPersonasForUser(): returning null!
,I/splitIntent( 1018): Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=5, mSplitNum[2]=7, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=9
I/splitIntent( 1018): finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
,I/SurfaceFlinger(  259): id=14 createSurf (540x960),1 flag=4, Mauncher
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
,D/StatusBarManagerService( 1018): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 1018): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,D/InputDispatcher( 1018): Focus entered window: 1498
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
,D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 1498): log_dcs ThreadedRenderer::initialize entered! 
,D/Recents_RecreateReceiver( 2540): onReceive by home
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,W/libprocessgroup( 1018): failed to open /acct/uid_10037/pid_5124/cgroup.procs: No such file or directory
,W/ActivityManager( 1018): userId = 0, bbcId = -10000,
V/ActivityThread( 1498): updateVisibility : ActivityRecord{2e303372 token=android.os.BinderProxy@2cb80920 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/Launcher.HomeView( 1498): onStop
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/GalleryCacheReady( 6004): Receive : home resume
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/InputMethodManagerService( 1018): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/IInputConnectionWrapper( 6366): showStatusIcon on inactive InputConnection
W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/SamsungIME( 1863): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
V/TaskCloserActivity( 6135): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,I/StatusBar( 1178): Icon Only
I/libpersona( 6427): KNOX_SDCARD checking this for 10135
D/PanelView( 1178): There is/are notification(s) 
I/libpersona( 6427): KNOX_SDCARD not a persona
E/Zygote  ( 6427): MountEmulatedStorage()
E/Zygote  ( 6427): v2
I/SELinux ( 6427): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6427): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1018): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=6427 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,E/SELinux ( 6427): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
,D/Mms/UIEventReceiver( 5571): ui event
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/BroadcastQueue( 1018): Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1498, uid=10006) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,I/Timeline( 1498): Timeline: Activity_idle id: android.os.BinderProxy@2cb80920 time:231158,
,D/TimaKeyStoreProvider( 6427): TimaSignature is unavailable
,D/ActivityThread( 6427): Added TimaKeyStore provider
,W/ActivityManager( 1018): mDVFSHelper.release()
I/Timeline( 1018): Timeline: Activity_windows_visible id: ActivityRecord{181f435e u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t21} time:231186
,W/ResourcesManager( 6427): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 6427): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6427): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 6427): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 6427): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/splitIntent( 1018): Queue : backgroundsplit_1 intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1018): Killing 5675:com.google.android.talk/u0a102 (adj 15): empty #31
W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,V/TaskCloserActivity( 6135): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,D/AndroidRuntime( 6419): 
D/AndroidRuntime( 6419): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6419): CheckJNI is OFF
,D/AndroidRuntime( 6419): readGMSProperty: start
D/AndroidRuntime( 6419): readGMSProperty: already setted!!
,D/AndroidRuntime( 6419): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6419): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6419): readGMSProperty: end
D/AndroidRuntime( 6419): addProductProperty: start
,D/WindowOrientationListener( 1018):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200,
,D/PersonaManager( 1018): isKioskContainerExistOnDevice
,W/libprocessgroup( 1018): failed to open /acct/uid_10102/pid_5675/cgroup.procs: No such file or directory
,E/AffinityControl( 6419): AffinityControl: registerfunction enter,
,D/AndroidRuntime( 6419): Calling main entry com.android.commands.pm.Pm,
,D/PersonaManagerService( 1018): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1018): START PACKAGE DELETE: observer{840203390}
D/PackageManager( 1018): pkg{<packageName>}
D/PackageManager( 1018): user{0}
D/PackageManager( 1018): caller{2000}
D/PackageManager( 1018): flags{2}
,D/PersonaManagerService( 1018): isFromApprovedUnInstaller: isApproved : true
D/PackageManager( 1018): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService( 1018): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1018): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
D/PackageManager( 1018): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
D/PackageManagerService( 1018): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 1018): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1018): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1018): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 1018): !@killApplicatoin: 10167, uninstall pkg,
,I/ActivityManager( 1018): Force stopping com.test.thalitest appid=10167 user=-1: uninstall pkg
,I/ActivityManager( 1018): Killing 6366:com.test.thalitest/u0a167 (adj 13): stop com.test.thalitest cause uninstall pkg
,W/PackageSettings( 1018): Skipping PackageSetting{22ef8d40 com.example.hello/10346} due to missing metadata,
,W/ActivityManager( 1018): Spurious death for ProcessRecord{181b95df 6366:com.test.thalitest/u0a167}, curProc for 6366: null
,I/ActivityManager( 1018): Force stopping com.test.thalitest appid=10167 user=0: pkg removed
,W/ActivityManager( 1018): CustomStartingWindow se packge removed so remove capture also
,I/InputReader( 1018): Reconfiguring input devices.  changes=0x00000010
,I/art     ( 6023): Explicit concurrent mark sweep GC freed 21816(1139KB) AllocSpace objects, 0(0B) LOS objects, 50% free, 3MB/7MB, paused 772us total 30.661ms
,I/art     ( 6102): Explicit concurrent mark sweep GC freed 344(25KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/8MB, paused 740us total 55.480ms
,E/SamsungIME( 1863): mOCRHelper is null
,V/NetworkStats( 1018): removeUidsLocked() for UIDs [10167]
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
V/NetworkStats( 1018): performPollLocked(flags=0x3)
,D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1018): UpdateStatsForKnox main else ---
,V/NetworkStats( 1018): performPollLocked() took 6ms
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,I/KLMS-2.5.123: ( 3607): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Mar 14 08:53:13 GMT+01:00 2016
,D/RegisteredServicesCache( 1458): empty dynamic service
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 60466(3MB) AllocSpace objects, 50(809KB) LOS objects, 33% free, 24MB/36MB, paused 2.861ms total 194.156ms
,I/art     ( 1018): WaitForGcToComplete blocked for 186.230ms for cause Explicit
,D/RCPManagerService( 1018): PackageReceiver onReceive()
,I/HarmonyEASService( 1018): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 1018): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/BackupManagerService( 1018): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService( 1018): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1018): uID is 10167
V/EnterpriseBillingPolicy( 1018): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - end - null
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1018): uID is 10167
D/TaskPersister( 1018): removeObsoleteFile: deleting file=23_task.xml
V/EnterpriseBillingPolicy( 1018): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - exit null : containerId = 0
D/SSRM:aZ ( 1018): MSG_TYPE_APP_REMOVED::
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - end - null
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 14290(766KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 24MB/36MB, paused 3.565ms total 159.270ms
,I/art     ( 1018): WaitForGcToComplete blocked for 300.480ms for cause Explicit
,D/PackageManager( 1018): delete codoeFile: 
,D/AASAuninstall( 1018): userId = 0, info.removedAppID = 10167, info.uid = 10167, packageName = com.test.thalitest
I/AASA_removePackage( 1018): UID=10167 Target=com.test.thalitest
,D/PackageManager( 1018): result of delete: 1{840203390}
,D/AndroidRuntime( 6419): Shutting down VM
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 3026(176KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.512ms total 137.881ms
D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1018): mCursor = null
W/GeofencerStateMachine( 1812): Ignoring removeGeofence because network location is disabled.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,D/EnterpriseDeviceManagerService( 1018): Package has changed for user 0
W/TextServicesManagerService( 1018): no available spell checker services found
D/EnterpriseDeviceManagerService( 1018): Admin package name: com.google.android.gms
,I/KLMS-2.5.123: ( 3607): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 1018): intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=27
,I/splitIntent( 1018): base  index=27, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
I/splitIntent( 1018): other index=30, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
I/splitIntent( 1018): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.123: ( 3607): KLMSIntentService(): onCreate()
,I/KLMS-2.5.123: ( 3607): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/ActivityManager( 1018): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6453 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,E/Zygote  ( 6453): MountEmulatedStorage()
I/libpersona( 6453): KNOX_SDCARD checking this for 10090
E/Zygote  ( 6453): v2
I/libpersona( 6453): KNOX_SDCARD not a persona
I/KLMS-2.5.123: ( 3607): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/SELinux ( 6453): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/KLMS-2.5.123: ( 3607): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
I/SELinux ( 6453): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/KLMS-2.5.123: ( 3607): KLMSIntentService(): PACKAGE_REMOVED
E/SELinux ( 6453): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/KLMS-2.5.123: ( 3607): KLMSIntentService(): listeningToPackageRemoved().START
,I/KLMS-2.5.123: ( 3607): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,D/TimaKeyStoreProvider( 6453): TimaSignature is unavailable
,D/ActivityThread( 6453): Added TimaKeyStore provider
,I/KLMS-2.5.123: ( 3607): KLMSIntentService(): Notification App List is Null. Remove Notification.
,D/elm:15121( 6453): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:15121( 6453): ELMEngine.ELMEngine( context ).
,D/elm:15121( 6453): MDMBridge.setEnterpriseBridge()
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/elm:15121( 6453): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,I/KLMS-2.5.123: ( 3607): KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,D/elm:15121( 6453): ElmAgentService : onCreate()
,I/KLMS-2.5.123: ( 3607): KLMSIntentService(): listeningToPackageRemoved().END
,D/elm:15121( 6453): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:15121( 6453): MainReceiver.listeningToPackageRemoved()
D/elm:15121( 6453): MDMBridge.getInstance()
D/elm:15121( 6453): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:15121( 6453): MDMBridge.getAllLicenseInfoFromSDK()
,I/KLMS-2.5.123: ( 3607): KLMSIntentService(): onDestroy()
,I/PCWCLIENTTRACE_PushUtil( 5809): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5809): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5809): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5809): [onReceive] - android.intent.action.PACKAGE_REMOVED
,I/SA      ( 5536): [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 5536): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10167 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,D/elm:15121( 6453): ElmAgentService : onDestroy().
,W/ResourceType( 1018): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/art     ( 6419): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 1018): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1018): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1018): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/PackageManager( 1018): [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
D/PackageManager( 1018): userId{-1}
D/PackageManager( 1018): andCode{true}
I/PackagesMonitor( 6004): PackagesMonitor onReceive :com.test.thalitest
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager( 1018): clearDefaults: com.test.thalitest
,I/CrashAnrDetector( 1018): onPackageRemoved : com.test.thalitest
,W/ResourcesManager( 5893): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 5893): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5893): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 5893): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 5893): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/ResourcesManager( 5893): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 5893): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5893): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5893): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5893): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5893): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,W/ResourcesManager( 5893): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5893): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5893): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 5893): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5893): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5893): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/ResourcesManager( 5893): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 5893): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5893): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 5893): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 5893): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5893): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5893): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 5893): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 5893): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5893): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 5893): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 5893): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5893): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5893): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 5893): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.,
W/ResourcesManager( 5893): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5893): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5893): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/Mms/FreeMessageStatusReceiver( 5571): onReceive, action : android.intent.action.PACKAGE_REMOVED
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,I/TactileAssist( 1018): enable value -1
I/TactileAssist( 1018): internal enable value -1
I/TactileAssist( 1018): intensity value -1
I/TactileAssist( 1018): saveAppList value true
D/Mms/FreeMessageReceiverService( 5571): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
D/Mms/FreeMessageReceiverService( 5571): onHandleIntent: ACTION_PACKAGE_REMOVED
I/TactileAssist( 1018): List of disabled apps :
W/ResourcesManager( 5893): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 5893): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5893): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5893): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/Compatibility( 5882): onReceive() it will make start service
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
W/ResourcesManager( 5893): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 5893): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.,
D/Compatibility( 5882): onHandleIntent()
W/ResourcesManager( 5893): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 5893): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 5893): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/Compatibility( 5882): intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10167, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
W/ResourcesManager( 5893): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,E/Zygote  ( 6477): MountEmulatedStorage()
E/Zygote  ( 6477): v2
I/libpersona( 6477): KNOX_SDCARD checking this for 10055
I/libpersona( 6477): KNOX_SDCARD not a persona
D/Compatibility( 5882): found: 2
D/Compatibility( 5882): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5882): skipping ResolveInfo{3e72c2c8 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5882): considering ResolveInfo{3ce60f61 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5882): default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5882): enabling receiver ResolveInfo{caa4a86 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,I/SELinux ( 6477): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=6477 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
I/SELinux ( 6477): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
W/ResourcesManager( 5893): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
D/Compatibility( 5882): enabling receiver ResolveInfo{30dabf47 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,W/ResourcesManager( 5893): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
E/SELinux ( 6477): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/Compatibility( 5882): enabling receiver ResolveInfo{2b554374 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/Compatibility( 5882): enabling receiver ResolveInfo{d93409d com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,D/Compatibility( 5882): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,D/TimaKeyStoreProvider( 6477): TimaSignature is unavailable
,D/ActivityThread( 6477): Added TimaKeyStore provider

```
