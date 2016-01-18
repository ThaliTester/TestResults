#### Test 56151093b6ab50f_thali06_samsung-SM-A300FU Logs


```
--------- beginning of system
,V/AlarmManager( 1018): waitForAlarm result :4
--------- beginning of main
D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1175): handleTimeUpdate
D/SecKeyguardClockView( 1175): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
D/SecKeyguardClockView( 1175): HomeTimezone(): 1
D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/KeyguardEffectViewController( 1175): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1175): *** don't update sliding image ***
D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/SViewCoverWidget( 1175): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/AndroidRuntime( 6133): 
D/AndroidRuntime( 6133): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6133): CheckJNI is OFF
D/AndroidRuntime( 6133): readGMSProperty: start
D/AndroidRuntime( 6133): readGMSProperty: already setted!!
D/AndroidRuntime( 6133): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6133): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6133): readGMSProperty: end
D/AndroidRuntime( 6133): addProductProperty: start
V/GLSActivity( 1666): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
I/GLSUser ( 1666): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1666): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1666): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1666): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1666): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/Finsky  ( 5386): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 5386): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 5386): [1] 5.onFinished: Scheduling replication attempt 5.
E/AffinityControl( 6133): AffinityControl: registerfunction enter
D/AndroidRuntime( 6133): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1018): inState():  stateMachine is null !!
I/PersonaManagerService( 1018): PersonaId don't exist
I/ActivityManager( 1018): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
W/ActivityManager( 1018): mDVFSHelper.acquire()
D/FocusedStackFrame( 1018): Set to : 0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1018): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1018): *FMB* installDecor flags : 25362712
E/Zygote  ( 6145): MountEmulatedStorage()
E/Zygote  ( 6145): v2
I/libpersona( 6145): KNOX_SDCARD checking this for 10338
I/libpersona( 6145): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6145 uid=10338 gids={50338, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1018): Focused application set to: xxxx
I/SELinux ( 6145): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/InputDispatcher( 1018): Focus left window: 1482
D/AndroidRuntime( 6133): Shutting down VM
I/SELinux ( 6145): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6145): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PhoneWindow( 1018): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1018): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  257): id=12 createSurf (1x1),1 flag=404, uhalitest
D/TimaKeyStoreProvider( 6145): TimaSignature is unavailable
D/ActivityThread( 6145): Added TimaKeyStore provider
D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
V/WindowManager( 1018): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
D/StatusBarManagerService( 1018): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1018): isKioskContainerExistOnDevice
D/WindowOrientationListener( 1018):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
I/SurfaceFlinger(  257): id=9 Removed Mauncher (5/9)
I/SurfaceFlinger(  257): id=9 Removed Mauncher (-2/9)
V/ActivityThread( 1482): updateVisibility : ActivityRecord{1c29ca26 token=android.os.BinderProxy@cf0de63 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1482): onTrimMemory. Level: 20
I/WebViewFactory( 6145): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
I/LibraryLoader( 6145): Time to load native libraries: 1 ms (timestamps 6096-6097)
I/LibraryLoader( 6145): Expected native library version number "",actual native library version number ""
W/art     ( 6133): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,V/WebViewChromiumFactoryProvider( 6145): Binding Chromium to main looper Looper (main, tid 1) {10f17a1c}
,I/LibraryLoader( 6145): Expected native library version number "",actual native library version number ""
,I/chromium( 6145): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6145): Initializing chromium process, singleProcess=true
,W/art     ( 6145): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6145): ApplicationContext is null in ApplicationStatus
,W/chromium( 6145): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6145): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6145): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6145): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6145): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6145): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6145): Local Branch: 
I/Adreno-EGL( 6145): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6145): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6145):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,W/art     ( 6145): Attempt to remove local handle scope entry from IRT, ignoring,
,W/AwContents( 6145): onDetachedFromWindow called when already detached. Ignoring
,D/PhoneWindow( 6145): *FMB* installDecor mIsFloating : false
,D/PhoneWindow( 6145): *FMB* installDecor flags : 8456448
,D/SystemWebViewEngine( 6145): CordovaWebView is running on device made by: samsung
,W/art     ( 6145): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 6145): Attempt to remove local handle scope entry from IRT, ignoring
,E/SMD     (  288): DCD OFF
,W/ActivityManager( 1018): Activity pause timeout for ActivityRecord{3a355684 u0 com.test.thalitest/.MainActivity t20}
,D/OpenGLRenderer( 6145): Render dirty regions requested: true
,D/ActivityManager( 1018): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1018): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1018): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1018): handleActiveUserChange for user 0
D/PersonaManagerService( 1018): getPersonasForUser(): returning null!
,W/chromium( 6145): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,V/ActivityThread( 6145): updateVisibility : ActivityRecord{1d43a311 token=android.os.BinderProxy@1f9bb79b {com.test.thalitest/com.test.thalitest.MainActivity}} show : true,
D/PhoneWindow( 6145): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 6145): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  257): id=13 createSurf (1x1),1 flag=404, NainActivit
,D/InputDispatcher( 1018): Focus entered window: 6145,
,D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
D/SRIB_DCS( 6145): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 6145): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6145): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,D/OpenGLRenderer( 6145): Enabling debug mode 0
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4327, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2636): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,D/InputMethodManagerService( 1018): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,I/StatusBar( 1175): Icon Only,
D/PanelView( 1175): There is/are notification(s) 
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ActivityManager( 1018): Displayed Component not be shown by security: +661ms (total +50s28ms)
,W/ActivityManager( 1018): mDVFSHelper.release()
I/Timeline( 1018): Timeline: Activity_windows_visible id: ActivityRecord{3a355684 u0 com.test.thalitest/.MainActivity t20} time:166614
,I/SurfaceFlinger(  257): id=12 Removed uhalitest (7/9),
I/SurfaceFlinger(  257): id=12 Removed uhalitest (-2/9)
,W/IInputConnectionWrapper( 6145): showStatusIcon on inactive InputConnection
,I/Timeline( 6145): Timeline: Activity_idle id: android.os.BinderProxy@1f9bb79b time:166631
,I/SamsungIME( 1885): getCurrentCandidateView,
,D/SamsungIME( 1885): Dismiss ExpandCandiate
,I/SamsungIME( 1885): getDebugLevel  : 0x4f4c
,W/BindingManager( 6145): Cannot call determinedVisibility() - never saw a connection for the pid: 6145
,I/SamsungIME( 1885): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1885): KeybaordView init() : load resources
,I/SamsungIME( 1885): getCurrentKeyboard
,I/SamsungIME( 1885): getTextKeyboard
,D/SamsungIME( 1885): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/JsMessageQueue( 6145): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6145): JniHelper::setJavaVM(0xb7731448), pthread_self() = -1211588296
,D/JX-Cordova( 6145): jxcore cordova android initializing
,E/Watchdog( 1018): !@Sync 5
,W/jxcore-log( 6145): Initializing JXcore engine
W/jxcore-log( 6145): JXcore engine is ready
,W/jxcore-log( 6145): Starting JXcore engine
,E/audit   ( 1879): type=1400 msg=audit(1453102571.123:205): avc:  denied  { ioctl } for  pid=6145 comm=".test.thalitest" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1879):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1879): type=1300 msg=audit(1453102571.123:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=2 a3=beb5cd58 items=0 ppid=310 ppcomm=main pid=6145 auid=4294967295 uid=10338 gid=10338 euid=10338 suid=10338 fsuid=10338 egid=10338 sgid=10338 fsgid=10338 ses=4294967295 tty=(none) comm=".test.thalitest" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1879): type=1320 msg=audit(1453102571.123:205): 
,W/jxcore-log( 6145): Platform android
W/jxcore-log( 6145): 
W/jxcore-log( 6145): Process ARCH arm
W/jxcore-log( 6145): 
,I/PowerManagerService( 1018): [PWL] Off : 105s ago
,E/SMD     (  288): DCD OFF
,I/jxcore-log( 6145): JXcore Cordova bridge is ready!,
I/jxcore-log( 6145): 
W/jxcore-log( 6145): JXcore engine is started
,I/Choreographer( 6145): Skipped 139 frames!  The application may be doing too much work on its main thread.
,I/chromium( 6145): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6145): Toggling radios to true,
I/jxcore-log( 6145): 
,D/BluetoothAdapter( 6145): enable(),
,D/BluetoothAdapter( 6145): enable(): BT is already enabled..!
,D/SecContentProvider( 1018): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 1018): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 1018): mCursor = null
,D/WifiService( 1018): setWifiEnabled: true pid=6145, uid=10338
W/ActivityManager( 1018): Permission Denial: getCurrentUser() from pid=6145, uid=10338 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 1018): Failed getting userId using ActivityManagerNative
W/WifiService( 1018): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6145, uid=10338 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 1018): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:24603)
W/WifiService( 1018): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2213)
W/WifiService( 1018): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2201)
W/WifiService( 1018): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 1018): 	at android.os.Binder.execTransact(Binder.java:461)
,D/SettingsProvider( 1018): name = wifi_on
,I/WifiService( 1018): disconnect: pid=6145, uid=10338
,I/wpa_supplicant( 1389): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 6145): Radios toggled
I/jxcore-log( 6145): 
,I/jxcore-log( 6145): My device name is: samsung-SM-A300FU
I/jxcore-log( 6145): 
,I/wpa_supplicant( 1389): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1,
I/wpa_supplicant( 1389): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 1389): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
I/wpa_supplicant( 1389): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1389): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/wpa_supplicant( 1389): Cmd 35605 not handled,
E/WifiStateMachine( 1018): WifiStateMachine: Leaving Connected state
,I/wpa_supplicant( 1389): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1389): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1389): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1389): wlan0: State: DISCONNECTED -> SCANNING,
I/wpa_supplicant( 1389): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 1389): First Scan Start
,I/wpa_supplicant( 1389): Scan requested (ret=0) - scan timeout 30 seconds
I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceStatusChanged wlan0, false
D/Tethering( 1018): InitialState.processMessage what=4
,D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceStatusChanged wlan0, false
,E/Tethering( 1018): No numeric data
,D/Tethering( 1018): sendTetherStateChangedBroadcast 0, 0, 0,
D/Tethering( 1018): clearTetheredNotification()
,E/WifiConfigStore( 1018): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
,V/NetworkStats( 1018): performPollLocked(flags=0x1)
D/Tethering( 1018): interfaceStatusChanged wlan0, false
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1018): UpdateStatsForKnox main else ---
,D/HotspotTile( 1175): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1175): updateTetherState():false, false
,V/NetworkStats( 1018): performPollLocked() took 5ms
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,E/WifiNative-wlan0( 1018): do suspend true
,D/WifiP2pService( 1018): InactiveState{ what=143375 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=143375 }
,D/CommandListener(  278): Clearing all IP addresses on wlan0
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
V/NativeCrypto( 1666): Read error: ssl=0xb7c85490: I/O error during system call, Connection timed out
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,V/NativeCrypto( 1666): SSL shutdown failed: ssl=0xb7c85490: I/O error during system call, Broken pipe
,I/rmt_storage(  272): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb7b217c8
I/rmt_storage(  272): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
,I/rmt_storage(  272): wakelock acquired: 1, error no: 42
,I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1213065928),
D/ConnectivityService( 1018): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
I/WifiTrafficPoller( 1018): evaluateTrafficStatsPolling
D/ConnectivityService( 1018): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
E/WifiStateMachine( 1018): Start Disconnecting Watchdog 1
D/ConnectivityService( 1018): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
I/wpa_supplicant( 1389): wlan0: Setting scan request: 0 sec 0 usec
,D/WifiP2pService( 1018): InactiveState{ what=143375 }
E/ConnectivityService( 1018): updateNetworkInfo()
D/WifiP2pService( 1018): P2pEnabledState{ what=143375 }
E/ConnectivityService( 1018): updateNetworkInfo()
E/WifiNative-wlan0( 1018): do suspend true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
I/System.out( 1018): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 1018): Tagging socket 333 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1018, getuid(): 1000
,D/StatusBar.NetworkController( 1175): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/qtaguid ( 1018): Untagging socket 333
,I/System.out( 1018): (HTTPLog)-Static: isSBSettingEnabled false
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/StatusBar.NetworkController( 1175): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false),
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
I/Hs20UtilService( 1725): Starting #8
D/NearbySettings( 1322): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1322): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1322): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/Hs20UtilService( 1725): Message received 5007
,I/NearbySettings( 1322): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1322): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1322): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1322): MountReceiver.mPrefHandler - 7002
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 917504
I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1213065928) wakelock released: 1, error no: 0
I/rmt_storage(  272): 
,I/rmt_storage(  272): rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb7b217c8
,D/EnterpriseController(  278): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0,
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 1000
D/CommandListener(  278): Clearing all IP addresses on wlan0
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
D/ConnectivityService( 1018): setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Validated
D/ConnectivityService( 1018): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1018): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory( 1456): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/CSLegacyTypeTracker( 1018): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/TelephonyNetworkFactory( 1456): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/CSLegacyTypeTracker( 1018): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService( 1018): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/WIFI_P2P( 1018): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,D/EntConnectivity( 1018): Not allowed due to - mEnabled false - primarySimSlot false
D/ConnectivityManager.CallbackHandler( 1175): CM callback handler got msg 524292
D/WifiNetworkAgent( 1018): NetworkAgent: NetworkAgent channel lost
,I/WifiTrafficPoller( 1018): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 1175): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/Tethering( 1018): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/Tethering( 1018): MasterInitialState.processMessage what=3
D/ConnectivityService( 1018): nai.networkMonitor.doQuit()
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): doQuit - quitNow()
,V/NetworkStats( 1018): updateIfacesLocked(),
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
V/NetworkStats( 1018): performPollLocked(flags=0x1)
D/WIFI    ( 1018): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled,
D/SecContentProvider2( 1018): mCursor = null
D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
D/EntConnectivity( 1018): Not allowed due to - mEnabled false - primarySimSlot false
,D/NetworkStatsFactory( 1018): UpdateStatsForKnox main else ---,
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
V/NetworkStats( 1018): performPollLocked() took 4ms
D/StatusBar.NetworkController( 1175): EthernetConnected: false
D/StatusBar.NetworkController( 1175): getUpdateDataNetType(): 0
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1175): getUpdateDataNetType(): mDataTypeBrand = LTE
,D/StatusBar.NetworkController( 1175): updateDataNetType()
V/NetworkStats( 1018): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/StatusBar.NetworkController( 1175): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1175): updateLTEICONDataNetType:0
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1725): Starting #9
,D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1018): mCursor = null
I/Hs20UtilService( 1725): Message received 5007
,D/StatusBar.NetworkController( 1175): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1175): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/NearbySettings( 1322): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1322): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1322): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1322): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1322): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1322): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1322): MountReceiver.mPrefHandler - 7002
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
,D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
,D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
,D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
,D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
,D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
,D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
,D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
,D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
,D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
,D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
,D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
,D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
,D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE,
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
,D/ConnectivityService( 1018): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1018): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy( 1018): updateDataUsageMap
,I/PCWCLIENTTRACE_PushUtil( 5713): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5713): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5713): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5713): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1018): intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=20
I/splitIntent( 1018): base  index=20, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
I/splitIntent( 1018): other index=22, name=com.google.android.gms com.google.android.gms.common.status.StatusServiceLauncherBroadcastReceiver
I/splitIntent( 1018): arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5713): noConnectivity : true
,E/Zygote  ( 6219): MountEmulatedStorage()
E/Zygote  ( 6219): v2
I/libpersona( 6219): KNOX_SDCARD checking this for 10108
I/libpersona( 6219): KNOX_SDCARD not a persona
,I/SELinux ( 6219): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6219): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6219): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6219 uid=10108 gids={50108, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 6219): TimaSignature is unavailable
D/ActivityThread( 6219): Added TimaKeyStore provider
,I/MusicStore( 6219): Database version: 120
,I/wpa_supplicant( 1389): nl80211: Received scan results (4 BSSes),
I/wpa_supplicant( 1389): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1389): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 1389): Trying to associate with  'G700'
I/wpa_supplicant( 1389): Re-associate with C0.AA.48
I/wpa_supplicant( 1389): wlan0: State: SCANNING -> ASSOCIATING
,I/wpa_supplicant( 1389): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,D/WifiMonitor( 1018): didn't find BSSID Trying to associate with SSID 'NG700'
,D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 1018): mCursor = null
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6219): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/wpa_supplicant( 1389): Cmd 35605 not handled
,I/wpa_supplicant( 1389): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 1389): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 1389): Associated with C0.AA.48
,I/wpa_supplicant( 1389): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1389): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1389): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceStatusChanged wlan0, false
D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceStatusChanged wlan0, false
,I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceStatusChanged wlan0, false
I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, true
D/Tethering( 1018): interfaceLinkStateChanged wlan0, true
D/Tethering( 1018): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 1389): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1389): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
E/Tethering( 1018): No numeric data
I/wpa_supplicant( 1389): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 1389): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 1018): sendTetherStateChangedBroadcast 1, 0, 0
D/Tethering( 1018): clearTetheredNotification()
I/wpa_supplicant( 1389): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1389): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1389): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 1389): Blacklist: Clear (temp) 
I/wpa_supplicant( 1389): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
D/SecContentProvider2( 1018): mCursor = null
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6219): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
D/Tethering( 1018): interfaceLinkStateChanged wlan0, true
I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, true
D/Tethering( 1018): interfaceStatusChanged wlan0, true
,V/NetworkStats( 1018): performPollLocked(flags=0x1)
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
D/NetworkStatsFactory( 1018): UpdateStatsForKnox main else ---
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6219): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/HotspotTile( 1175): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1175): updateTetherState():false, false
D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1018): mCursor = null
,V/NetworkStats( 1018): performPollLocked() took 6ms
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/WifiNative-wlan0( 1018): callSECApiVoid - ID [50]
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,E/WifiConfigStore( 1018): setLastSelectedConfiguration -1
,D/StatusBar.NetworkController( 1175): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1018): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,E/WifiConfigStore( 1018): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/ConnectivityService( 1018): hsengiv:checkWhatTypeOfNetwork and the value is false
,E/ConnectivityService( 1018): updateNetworkInfo()
,D/ConnectivityService( 1018): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,E/WifiConfigStore( 1018): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
,D/CommandListener(  278): Setting iface cfg
,E/WifiStateMachine( 1018): Start Dhcp Watchdog 2
,W/ResourcesManager( 6219): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6219): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 1018): mCursor = null
,E/WifiNative-wlan0( 1018): do suspend false
,D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
,D/WifiP2pService( 1018): InactiveState{ what=143375 }
D/SecContentProvider2( 1018): mCursor = null
D/WifiP2pService( 1018): P2pEnabledState{ what=143375 }
,V/JNIHelp ( 6219): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 6219): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 6219): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@28e2e77d: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6219): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6219): GMSCore installation verified,
,I/ConfigStore( 6219): Config Database version: 1,
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 1018): getStreamVolume 3 index 70
,I/MediaRouter( 6219): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6219): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/dhcpcd  ( 6246): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,I/dhcpcd  ( 6246): version 5.5.6 starting
,D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,E/dhcpcd  ( 6246): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6255): MountEmulatedStorage(),
,I/ActivityManager( 1018): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6255 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 6255): v2
I/libpersona( 6255): KNOX_SDCARD checking this for 10001
I/libpersona( 6255): KNOX_SDCARD not a persona
I/dhcpcd  ( 6246): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 6246): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 6246): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 6246): bssid match
,I/dhcpcd  ( 6246): wlan0: rebinding lease of 192.168.1.132,
I/SELinux ( 6255): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6255): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6255): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/GHttpClientFactory( 6219): Using our fixed implementation of GMSCore's GoogleHttpClient
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
D/TimaKeyStoreProvider( 6255): TimaSignature is unavailable
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/ActivityThread( 6255): Added TimaKeyStore provider
,I/GoogleURLConnFactory( 6219): Using platform SSLCertificateSocketFactory
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/ActivityManager( 1018): Killing 5598:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #31
,I/dhcpcd  ( 6246): wlan0: acknowledged 192.168.1.132 from 192.168.1.1
,I/dhcpcd  ( 6246): wlan0: leased 192.168.1.132 for 86400 seconds
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6277): MountEmulatedStorage()
,E/Zygote  ( 6277): v2
I/libpersona( 6277): KNOX_SDCARD checking this for 1000
I/libpersona( 6277): KNOX_SDCARD not a persona
,I/ActivityManager( 1018): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6277 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 4186:com.sec.spp.push/u0a32 (adj 15): empty #31
,I/SELinux ( 6277): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6277): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6277): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6277): TimaSignature is unavailable,
D/ActivityThread( 6277): Added TimaKeyStore provider
,W/libprocessgroup( 1018): failed to open /acct/uid_10139/pid_5598/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_10032/pid_4186/cgroup.procs: No such file or directory,
,I/DIAGMON_AGENT( 6277): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,E/WifiNative-wlan0( 1018): do suspend true
,D/WifiP2pService( 1018): InactiveState{ what=143375 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1175): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/WifiStateMachine( 1018): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
E/WifiStateMachine( 1018): VerifyingLinkState enter
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/WifiNative-wlan0( 1018): callSECApiInt - ID [210]
,E/ConnectivityService( 1018): updateNetworkInfo()
,D/ConnectivityService( 1018): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,D/ConnectivityService( 1018): Adding iface wlan0 to network 503
,D/WifiWatchdogStateMachine( 1018): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger( 1018): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824},
D/WifiWatchdogStateMachine.DnsResolver( 1018): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.SingDnsChecker( 1018): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/ConnectivityService( 1018): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/StatusBar.NetworkController( 1175): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1018): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/ConnectivityService( 1018): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 503
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 1018): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,E/ConnectivityService( 1018): Unexpected mtu value: 0, wlan0
,D/ConnectivityService( 1018): Setting Dns servers for network 503 to [/192.168.1.1]
,D/ConnectivityService( 1018): LTETest block dns file not exists
,D/ConnectivityService( 1018): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,E/WifiStateMachine( 1018): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,I/DIAGMON_AGENT( 6277): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,E/ConnectivityService( 1018): updateNetworkInfo()
,E/ConnectivityService( 1018): updateNetworkInfo()
,I/DIAGMON_AGENT( 6277): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/WifiTrafficPoller( 1018): evaluateTrafficStatsPolling
D/ConnectivityService( 1018): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/ConnectivityService( 1018): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
I/DIAGMON_AGENT( 6277): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1018): rematching NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Checking http://connectivitycheck.android.com/generate_204 on "NG700"
I/DIAGMON_AGENT( 6277): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6277): ./extraInfo: <unknown ssid>
,I/System.out( 1018): (HTTPLog)-Static: isSBSettingEnabled false
W/DIAGMON_AGENT( 6277): [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,D/EnterpriseController(  278): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 503 for uid 1000
,D/ConnectivityService( 1018):    accepting network in place of null
,D/WIFI_P2P( 1018): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/TelephonyNetworkFactory( 1456): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
D/TelephonyNetworkFactory( 1456): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/StatusBar.NetworkController( 1175): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:null
E/CSLegacyTypeTracker( 1018): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1018): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/ConnectivityService( 1018): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/WIFI    ( 1018): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/WifiTrafficPoller( 1018): evaluateTrafficStatsPolling
I/WifiTrafficPoller( 1018): mBoosterFLAG : 0
I/WifiTrafficPoller( 1018): current booster mode : FullMode
D/WifiNative-wlan0( 1018): callSECApiVoid - ID [212]
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6315): MountEmulatedStorage(),
,E/Zygote  ( 6315): v2
I/libpersona( 6315): KNOX_SDCARD checking this for 10008
I/libpersona( 6315): KNOX_SDCARD not a persona
I/SELinux ( 6315): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6315 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 6315): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6315): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Killing 5304:com.google.android.partnersetup/u0a14 (adj 15): empty #31
,D/ConnectivityService( 1018): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/Tethering( 1018): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/ConnectivityService( 1018): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/Tethering( 1018): MasterInitialState.processMessage what=3
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
V/NetworkStats( 1018): updateIfacesLocked()
V/NetworkStats( 1018): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1018): UpdateStatsForKnox main else ---
,D/ConnectivityManager.CallbackHandler( 1175): CM callback handler got msg 524290
V/NetworkStats( 1018): performPollLocked() took 4ms
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
V/NetworkStats( 1018): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1175): EthernetConnected: false
D/StatusBar.NetworkController( 1175): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1175): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1175): updateDataNetType()
D/StatusBar.NetworkController( 1175): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1175): updateLTEICONDataNetType:0
I/art     (  310): Explicit concurrent mark sweep GC freed 8709(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 701us total 24.697ms
,D/StatusBar.NetworkController( 1175): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/TimaKeyStoreProvider( 6315): TimaSignature is unavailable
D/ActivityThread( 6315): Added TimaKeyStore provider
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 658us total 16.784ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 588us total 16.697ms
,I/System.out( 1018): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/ActivityManager( 1018): Killing 5213:com.sec.spp.push:RemoteNotiProcess/u0a32 (adj 15): empty #31
,I/KLMS-2.5.123: ( 3619): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Jan 18 08:36:14 GMT+01:00 2016
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 18 Jan 2016 07:36:14 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453102574263], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453102574241]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Validated
,D/ConnectivityService( 1018): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1018): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1018): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 1018): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1018): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1175): CM callback handler got msg 524290
,I/KLMS-2.5.123: ( 3619): KLMSAbstractReciever(): onReceive().END.
,D/StatusBar.NetworkController( 1175): EthernetConnected: false
D/StatusBar.NetworkController( 1175): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1175): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1175): updateDataNetType()
D/StatusBar.NetworkController( 1175): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1175): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1175): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.123: ( 3619): KLMSIntentService(): onCreate()
,E/Zygote  ( 6331): MountEmulatedStorage()
E/Zygote  ( 6331): v2
,I/libpersona( 6331): KNOX_SDCARD checking this for 10031
I/libpersona( 6331): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6331 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
I/SELinux ( 6331): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/KLMS-2.5.123: ( 3619): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,W/libprocessgroup( 1018): failed to open /acct/uid_10014/pid_5304/cgroup.procs: No such file or directory
I/SELinux ( 6331): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/KLMS-2.5.123: ( 3619): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
E/SELinux ( 6331): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/KLMS-2.5.123: ( 3619): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.123: ( 3619): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.5.123: ( 3619): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,I/KLMS-2.5.123: ( 3619): StateImplV2(): networkChangeListener().START
,I/KLMS-2.5.123: ( 3619): NetworkChangeOperations(): uploadRequestLog().START 
,D/TimaKeyStoreProvider( 6331): TimaSignature is unavailable
,D/ActivityThread( 6331): Added TimaKeyStore provider
,I/KLMS-2.5.123: ( 3619): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.5.123: ( 3619): StateImplV2(): networkChangeListener().END
,I/KLMS-2.5.123: ( 3619): KLMSIntentService(): onDestroy()
,I/SO_AGENT( 6331): [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,I/DBG_POLICYDM( 5760): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,I/SA      ( 5898): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 5898): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,I/SA      ( 5898): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 5898): [SLFUCHKMGR] constructor called
,I/SA      ( 5898): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 5898): [OR] == isSIMCardReady false ==
,I/SA      ( 5898): [SCU] == networkStateCheck == true
,I/DBG_POLICYDM( 5760): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5760): [com.policydm.XDMApplication(429/isNetworkChanged)] a previous network is 0, current network is 2
,E/DBG_POLICYDM( 5760): [com.policydm.XDMApplication(431/isNetworkChanged)] network changed.... 
,I/SA      ( 5898): [DM] getCountryCodeFromCSC : PL
,I/SA      ( 5898): isChinaCountryCode : false
,I/SA      ( 5898): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 5898): [OR] == networkStateCheck true ==
,I/DBG_POLICYDM( 5760): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/SA      ( 5898): [OR] GetMyCountryZoneTask
,I/SA      ( 5898): [OR] onReceive END
W/libprocessgroup( 1018): failed to open /acct/uid_10032/pid_5213/cgroup.procs: No such file or directory
,I/ActivityManager( 1018): Killing 5689:com.samsung.helphub/1000 (adj 15): empty #31
,V/DownloadManager( 1227): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,I/DBG_POLICYDM( 5760): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 5760): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 5760): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 5760): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
I/SA      ( 5898): [SRS] prepareGetMyCountryZone
,I/DBG_POLICYDM( 5760): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,D/accuweather( 1602): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/DBG_POLICYDM( 5760): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 5760): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
I/DBG_POLICYDM( 5760): [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
D/SecContentProvider2( 1018): uri = 15 selection = getAppBlockDownloadState
I/DBG_POLICYDM( 5760): [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
D/SecContentProvider2( 1018): mCursor = null
E/DBG_POLICYDM( 5760): [com.policydm.db.XDBSpdAdp(36/xdbGetSpdDeviceRegister)] Device is Registered
D/daemonapp( 1684): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 7
I/SA      ( 5898): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      ( 5898): [SSP] query invoked
D/accuweather( 1602): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 1602): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1602): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1602): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
I/DBG_POLICYDM( 5760): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
I/DBG_POLICYDM( 5760): [com.policydm.db.XDB(2176/xdbGetWaitWifiFlag)] bWaitWifi : false
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_5689/cgroup.procs: No such file or directory
I/art     ( 1018): Explicit concurrent mark sweep GC freed 65530(3MB) AllocSpace objects, 13(260KB) LOS objects, 33% free, 23MB/35MB, paused 2.591ms total 155.051ms
I/SA      ( 5898): [TPMU] GetMccFromDB : null
I/SA      ( 5898): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 5898): [TPM] isNoProxy(default) : true
D/accuweather( 1602): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
D/accuweather( 1602): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/File    ( 5898): fail readDirectory() errno=2
I/libpersona( 6351): KNOX_SDCARD checking this for 10121
E/Zygote  ( 6351): MountEmulatedStorage()
I/libpersona( 6351): KNOX_SDCARD not a persona
E/Zygote  ( 6351): v2
I/SELinux ( 6351): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 6351): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6351): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6351 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
D/TimaKeyStoreProvider( 6351): TimaSignature is unavailable
D/ActivityThread( 6351): Added TimaKeyStore provider
W/ResourcesManager( 6351): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6351): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6351): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/ConnectivityService( 1018): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/NetworkMonitor( 6219): type=WIFI subType= reason=null isConnected=true
D/GpsLocationProvider( 1018): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/QuickConnect( 6351): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1018): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService( 1018): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1018): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityManager.CallbackHandler( 1175): CM callback handler got msg 524295
D/ConnectivityManager.CallbackHandler( 1175): CM callback handler got msg 524295
I/QuickConnect( 6351): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 6351): PeriphStartReceiver.onReceive - no need to start
D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1018): mCursor = null
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1018): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=6368 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 5728:com.google.android.apps.docs/u0a87 (adj 15): empty #31
E/Zygote  ( 6368): MountEmulatedStorage()
I/libpersona( 6368): KNOX_SDCARD checking this for 10141
E/Zygote  ( 6368): v2
I/libpersona( 6368): KNOX_SDCARD not a persona
I/SELinux ( 6368): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 6368): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6368): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 6368): TimaSignature is unavailable
D/ActivityThread( 6368): Added TimaKeyStore provider
W/ResourcesManager( 6368): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 6368): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6368): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6368): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/RCPManagerService( 1018): exchangeData() failure , invalid userId
D/RCPManagerService( 1018): exchangeData() failure , invalid userId
D/RCPManagerService( 1018): exchangeData() failure , invalid userId
D/RCPManagerService( 1018): exchangeData() failure , invalid userId
D/RCPManagerService( 1018): exchangeData() failure , invalid userId
D/RCPManagerService( 1018): exchangeData() failure , invalid userId
D/BadgeProvider( 5826): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
D/BadgeProvider( 5826): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/Launcher.Model( 1482): reloadBadges entered.
D/BadgeProvider( 5826): sendNotify, [notify] : null
D/BadgeProvider( 5826): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5826): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 5826): update, [UpdateCount] : 1
W/libprocessgroup( 1018): failed to open /acct/uid_10087/pid_5728/cgroup.procs: No such file or directory
D/RCPManagerService( 1018): exchangeData() failure , invalid userId
D/RCPManagerService( 1018): exchangeData() failure , invalid userId
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6391): MountEmulatedStorage()
E/Zygote  ( 6391): v2
I/libpersona( 6391): KNOX_SDCARD checking this for 1000
I/libpersona( 6391): KNOX_SDCARD not a persona
I/SELinux ( 6391): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 6391): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6391): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6391 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 5319:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #31
D/TimaKeyStoreProvider( 6391): TimaSignature is unavailable
D/ActivityThread( 6391): Added TimaKeyStore provider
D/SecurityLogAgent( 6391): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6391): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6391): StateMachine : Current State = 1
D/SecurityLogAgent( 6391): StateMachine : Changed Current State = 1
I/ActivityManager( 1018): Killing 5778:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #31
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
E/SMD     (  288): DCD OFF
V/AlarmManager( 1018): waitForAlarm result :4
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ChimeraCfgMgr( 2066): Loading module com.google.android.gms.kids from APK com.google.android.gms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ConnectivityService( 1018): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
D/ChimeraCfgMgr( 2066): Loading module com.google.android.gms.kids from APK com.google.android.gms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
I/SA      ( 5898): [RC New] Execute method=[GET] start
W/libprocessgroup( 1018): failed to open /acct/uid_10029/pid_5319/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10148/pid_5778/cgroup.procs: No such file or directory
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1018): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=6411 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/System.out( 3977): (HTTPLog)-Static: isSBSettingEnabled false
I/libpersona( 6411): KNOX_SDCARD checking this for 10032
E/Zygote  ( 6411): MountEmulatedStorage()
I/libpersona( 6411): KNOX_SDCARD not a persona
E/Zygote  ( 6411): v2
I/System.out( 3977): (HTTPLog)-Static: isSBSettingEnabled false
I/SELinux ( 6411): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/EnterpriseController(  278): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 503 for uid 10102
I/SELinux ( 6411): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6411): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/SA      ( 5898): [RC New] Security=[true]
I/System.out( 5898): Thread-995(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out( 5898): Thread-995(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 5898): Thread-995(ApacheHTTPLog):isShipBuild true
I/System.out( 5898): Thread-995(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5898): Thread-995(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
D/EnterpriseController(  278): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 503 for uid 10036
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/TimaKeyStoreProvider( 6411): TimaSignature is unavailable
D/ActivityThread( 6411): Added TimaKeyStore provider
I/System.out( 3977): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/GLSUser ( 1666): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1666): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1666): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1666): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1666): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1018): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1175): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1175): Icon Only
E/SPPClientService( 6411): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
E/SPPClientService( 6411): [SystemStateMoniter] Current Time : 172646
,I/StatusBar( 1175): Icon Only
D/PanelView( 1175): There is/are notification(s) 
D/PanelView( 1175): kidsfalse mQsExpansionEnabled:true
,W/Kids    ( 2066): [AccountUtils] Account not ready
W/Kids    ( 2066): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2066): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2066): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2066): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2066): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2066): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2066): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2066): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2066): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2066): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2066): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2066): 	at java.lang.Thread.run(Thread.java:818)
,E/SPPClientService( 6411): ============PushLog. commonIsShipBuild. stop!
D/PersonaManager( 1175): isKioskContainerExistOnDevice
E/SPPClientService( 6411): [SystemStateMoniter] No Connect : true
,I/PhoneStatusBar( 1175): Icon Only
I/StatusBar( 1175): Icon Only
E/SPPClientService( 6411): [PushClientApplication] Push log off : This is Ship build version
D/PanelView( 1175): There is/are notification(s) 
,D/PanelView( 1175): kidsfalse mQsExpansionEnabled:true
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/SPPClientService( 6411): PushLog.txt file is not deleted.
,D/SPPClientService( 6411): PushLog.txt file is not deleted.
D/SPPClientService( 6411): ============PushLog. stop!
,E/Zygote  ( 6432): MountEmulatedStorage(),
I/libpersona( 6432): KNOX_SDCARD checking this for 10110
E/Zygote  ( 6432): v2,
I/libpersona( 6432): KNOX_SDCARD not a persona
I/SELinux ( 6432): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6432 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
I/SELinux ( 6432): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6432): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,E/SPPClientService( 6411): [[SystemStateMonitorService]] No Active Internet
,D/TimaKeyStoreProvider( 6432): TimaSignature is unavailable
,D/ActivityThread( 6432): Added TimaKeyStore provider
,D/PanelView( 1175): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6432): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6432): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6432): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6432): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 6432): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6432):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6432):   adb logcat -s GAv4
,W/GAv4    ( 6432): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6432): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6432): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager( 1018): Killing 5800:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #31
,I/SA      ( 5898): [RC New] [v2liruge] api execute + 661
,I/SA      ( 5898): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 5898): AsyncTask #1 calls detatch()
,I/SA      ( 5898): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 5898): [OCP] update openData : PL
,I/SA      ( 5898): [TPMU] getNetworkMcc : 
,I/SA      ( 5898): [SCU] saveMccToPreferece Start
,I/SA      ( 5898): [SCU] RegionMCC : 260
,I/SA      ( 5898): [SSP] query invoked
,I/SA      ( 5898): [TPMU] GetMccFromDB : null
I/SA      ( 5898): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5898): [SCU] saveMccToPreferece End
,I/SA      ( 5898): [RC New] executeRequest [v2liruge] end. 732
I/SA      ( 5898): [RC New] Execute end
I/SA      ( 5898): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 5898): [OR] GetMyCountryZoneTask Success
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1018): failed to open /acct/uid_10152/pid_5800/cgroup.procs: No such file or directory
,I/WebViewFactory( 6432): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
,I/LibraryLoader( 6432): Time to load native libraries: 1 ms (timestamps 3298-3299)
,I/LibraryLoader( 6432): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6432): Binding Chromium to main looper Looper (main, tid 1) {355f10c8}
,I/LibraryLoader( 6432): Expected native library version number "",actual native library version number ""
,I/chromium( 6432): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6432): Initializing chromium process, singleProcess=true
,W/art     ( 6432): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6432): ApplicationContext is null in ApplicationStatus
,W/chromium( 6432): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6432): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6432): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6432): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6432): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6432): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6432): Local Branch: 
I/Adreno-EGL( 6432): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6432): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6432):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,W/AudioManagerAndroid( 6432): Requires BLUETOOTH permission
,I/NSApplication( 6432): Starting up...
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6488): MountEmulatedStorage(),
I/libpersona( 6488): KNOX_SDCARD checking this for 10077
E/Zygote  ( 6488): v2
I/libpersona( 6488): KNOX_SDCARD not a persona,
I/SELinux ( 6488): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6488): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1018): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6488 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 6488): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Killing 5680:com.android.mms/u0a41 (adj 15): empty #31
,D/TimaKeyStoreProvider( 6488): TimaSignature is unavailable
,D/ActivityThread( 6488): Added TimaKeyStore provider
,D/CountryDetector( 1018): No listener is left
,W/libprocessgroup( 1018): failed to open /acct/uid_10041/pid_5680/cgroup.procs: No such file or directory
,D/SSRM:n  ( 1018): SIOP:: AP = 300
,D/WaitQueueForNetworkActivate( 6032): notifyNetworkActivated
,W/ContextImpl( 6032): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 1018): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/hcjo    ( 6032): AutoUpdateManager:IDLE:execute
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1725): Starting #10
,I/Hs20UtilService( 1725): Message received 5007
,D/NearbySettings( 1322): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1322): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1322): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1322): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1322): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1322): MountReceiver.onReceive - Keep current state
,D/InitializeManagerStateMachine( 6032): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 6032): exit::IDLE
D/InitializeManagerStateMachine( 6032): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 6032): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 6032): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6032): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6032): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6032): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6032): entry::SUCCESS
D/hcjo    ( 6032): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 6032): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 6032): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1725): Starting #11
D/InitializeManagerStateMachine( 6032): exit::SUCCESS
D/InitializeManagerStateMachine( 6032): entry::IDLE
,I/Hs20UtilService( 1725): Message received 5007
,D/NearbySettings( 1322): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1322): MountReceiver.onReceive - Keep current state
,I/ActivityManager( 1018): Killing 5842:com.sec.android.app.myfiles/u0a42 (adj 15): empty #31
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1725): Starting #12
,I/Hs20UtilService( 1725): Message received 5007
,D/NearbySettings( 1322): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1322): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1322): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1322): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1322): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1322): MountReceiver.onReceive - Keep current state
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1725): Starting #13
,I/Hs20UtilService( 1725): Message received 5007
,D/NearbySettings( 1322): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1322): MountReceiver.onReceive - Keep current state
,D/WifiStateMachine( 1018): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,D/SecContentProvider2( 1018): uri = 15 selection = getToastGravityEnabledState
D/SecContentProvider2( 1018): mCursor = null
,D/SecContentProvider2( 1018): uri = 15 selection = getToastGravity
D/SecContentProvider2( 1018): mCursor = null
,D/SecContentProvider2( 1018): uri = 15 selection = getToastGravityXOffset
,D/SecContentProvider2( 1018): mCursor = null
,D/SecContentProvider2( 1018): uri = 15 selection = getToastGravityYOffset
,D/SecContentProvider2( 1018): mCursor = null
,I/jxcore-log( 6145): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 6145): 
,D/SecContentProvider2( 1018): uri = 15 selection = getToastEnabledState
,D/SecContentProvider2( 1018): mCursor = null
,D/SecContentProvider2( 1018): uri = 15 selection = getToastShowPackageNameState
,D/SecContentProvider2( 1018): mCursor = null
,I/PCWCLIENTTRACE_PushUtil( 5713): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5713): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 5713): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5713): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1018): intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=20
I/splitIntent( 1018): base  index=20, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
I/splitIntent( 1018): other index=22, name=com.google.android.gms com.google.android.gms.common.status.StatusServiceLauncherBroadcastReceiver
I/splitIntent( 1018): arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,V/MusicLeanback( 6219): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SurfaceFlinger(  257): id=14 createSurf (1x1),1 flag=4, Uoast
,I/DIAGMON_AGENT( 6277): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 6277): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6277): ./extraInfo: "NG700"
,I/DIAGMON_AGENT( 6277): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/PowerManagerService( 1018): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1018
,D/SRIB_DCS( 1175): log_dcs ThreadedRenderer::initialize entered! 
,I/DBG_POLICYDM( 5760): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5760): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5760): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,I/DBG_POLICYDM( 5760): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5760): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5760): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,I/FOTA_Client( 6315): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,W/FOTA_Client( 6315): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,I/KLMS-2.5.123: ( 3619): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Jan 18 08:36:16 GMT+01:00 2016
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3619): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.5.123: ( 3619): KLMSIntentService(): onCreate()
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,I/KLMS-2.5.123: ( 3619): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,W/libprocessgroup( 1018): failed to open /acct/uid_10042/pid_5842/cgroup.procs: No such file or directory
,I/KLMS-2.5.123: ( 3619): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.123: ( 3619): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.123: ( 3619): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.5.123: ( 3619): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,I/KLMS-2.5.123: ( 3619): StateImplV2(): networkChangeListener().START
,I/KLMS-2.5.123: ( 3619): NetworkChangeOperations(): uploadRequestLog().START 
,I/DBG_POLICYDM( 5760): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,I/KLMS-2.5.123: ( 3619): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.5.123: ( 3619): StateImplV2(): networkChangeListener().END
,I/DBG_POLICYDM( 5760): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/SA      ( 5898): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 5898): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 5898): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,E/DBG_POLICYDM( 5760): [com.policydm.XDMApplication(437/isNetworkChanged)] network not changed.... 
,I/KLMS-2.5.123: ( 3619): KLMSIntentService(): onDestroy()
,I/SA      ( 5898): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 5898): [OR] == isSIMCardReady false ==
,I/SA      ( 5898): [SCU] == networkStateCheck == true
I/SA      ( 5898): [DM] getCountryCodeFromCSC : PL
I/SA      ( 5898): isChinaCountryCode : false
I/SA      ( 5898): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 5898): [OR] == networkStateCheck true ==
I/SA      ( 5898): [OR] GetMyCountryZoneTask
,I/SA      ( 5898): [OR] onReceive END
,I/SA      ( 5898): [SRS] prepareGetMyCountryZone
,V/DownloadManager( 1227): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,D/accuweather( 1602): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/SA      ( 5898): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      ( 5898): [SSP] query invoked
,D/SecContentProvider2( 1018): uri = 15 selection = getAppBlockDownloadState
D/SecContentProvider2( 1018): mCursor = null
,I/SA      ( 5898): [TPMU] GetMccFromDB : null
I/SA      ( 5898): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 5898): [TPM] isNoProxy(default) : true
I/SA      ( 5898): [RC New] Execute method=[GET] start
,D/daemonapp( 1684): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
,D/accuweather( 1602): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1602): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,D/accuweather( 1602): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,D/accuweather( 1602): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1602): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1602): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/QuickConnect( 6351): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 6351): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 6351): PeriphStartReceiver.onReceive - no need to start
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,I/SA      ( 5898): [RC New] Security=[true]
,I/System.out( 5898): Thread-997(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 5898): Thread-997(ApacheHTTPLog):isShipBuild true
I/System.out( 5898): Thread-997(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5898): Thread-997(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/SecurityLogAgent( 6391): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6391): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6391): StateMachine : Current State = 1
,D/SecurityLogAgent( 6391): StateMachine : Changed Current State = 1
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 2066): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 2066): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/SPPClientService( 6411): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 6411): [SystemStateMoniter] Current Time : 174396
,E/SPPClientService( 6411): [SystemStateMoniter] No Connect : false
,I/System.out( 3977): (HTTPLog)-Static: isSBSettingEnabled false
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1666): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1666): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1666): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1666): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1666): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/hcjo    ( 6032): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 6032): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 6032): exit::IDLE
D/InitializeManagerStateMachine( 6032): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 6032): execute::NETWORK_CHECK:NETWORK_STATE_OK
,D/InitializeManagerStateMachine( 6032): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6032): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6032): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6032): exit::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 6032): entry::SUCCESS
D/hcjo    ( 6032): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 6032): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 6032): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 6032): exit::SUCCESS
D/InitializeManagerStateMachine( 6032): entry::IDLE
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,W/Kids    ( 2066): [AccountUtils] Account not ready
W/Kids    ( 2066): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2066): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2066): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2066): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2066): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2066): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2066): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2066): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2066): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2066): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2066): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2066): 	at java.lang.Thread.run(Thread.java:818)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/StatusBar( 1175): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1175): Icon Only
I/StatusBar( 1175): Icon Only
D/PanelView( 1175): There is/are notification(s) 
D/PanelView( 1175): kidsfalse mQsExpansionEnabled:true
D/PersonaManager( 1175): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1175): Icon Only
I/StatusBar( 1175): Icon Only
D/PanelView( 1175): There is/are notification(s) 
D/PanelView( 1175): kidsfalse mQsExpansionEnabled:true
,V/GLSActivity( 1666): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/PanelView( 1175): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,I/art     ( 1666): Explicit concurrent mark sweep GC freed 31326(1844KB) AllocSpace objects, 10(202KB) LOS objects, 39% free, 7MB/12MB, paused 952us total 43.660ms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/VacuumService( 1666): Vacuum at: now=1453102577336 tag=VacuumService
,I/GoogleURLConnFactory( 1666): Using platform SSLCertificateSocketFactory
,W/Uploader( 1666): No account for auth token provided
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 1666): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1666): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1666): (HTTPLog)-Static: isShipBuild true
,I/System.out( 1666): (HTTPLog)-Thread-188-1035581421: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1666): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  278): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 503 for uid 10011
,I/jxcore-log( 6145): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 6145): 
,I/jxcore-log( 6145): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 6145): 
,I/System.out( 1666): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1666): Tagging socket 54 with tag 120100000000{4609,0} for uid -1, pid: 1666, getuid(): 10011
,I/jxcore-log( 6145): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 6145): 
,I/qtaguid ( 1666): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1666, getuid(): 10011
,I/jxcore-log( 6145): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 6145): 
,I/jxcore-log( 6145): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 6145): 
,I/jxcore-log( 6145): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 6145): 
,W/Uploader( 1666): No account for auth token provided
,I/System.out( 1666): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1666): Tagging socket 54 with tag 120100000000{4609,0} for uid -1, pid: 1666, getuid(): 10011
,W/Uploader( 1666): No account for auth token provided
,I/System.out( 1666): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1666): Tagging socket 54 with tag 120100000000{4609,0} for uid -1, pid: 1666, getuid(): 10011
,I/SA      ( 5898): [RC New] [v2liruge] api execute + 795
,I/SA      ( 5898): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
I/System.out( 5898): AsyncTask #2 calls detatch()
,I/SA      ( 5898): [ODM] saveOpenData( GEO_IP, PL )
,W/Uploader( 1666): No account for auth token provided
,I/System.out( 1666): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1666): Tagging socket 54 with tag 120100000000{4609,0} for uid -1, pid: 1666, getuid(): 10011
,I/dhcpcd  ( 6246): wlan0: sending IPv6 Router Solicitation
,W/Uploader( 1666):  no longer exists, so no auth token.,
,I/System.out( 1666): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1666): Tagging socket 54 with tag 120100000000{4609,0} for uid -1, pid: 1666, getuid(): 10011
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 30018(1608KB) AllocSpace objects, 6(104KB) LOS objects, 33% free, 23MB/35MB, paused 2.518ms total 145.323ms
,I/SA      ( 5898): [OCP] update openData : PL
,I/SA      ( 5898): [TPMU] getNetworkMcc : 
,I/SA      ( 5898): [SCU] saveMccToPreferece Start
,I/SA      ( 5898): [SCU] RegionMCC : 260
,I/SA      ( 5898): [SSP] query invoked
,W/Uploader( 1666): No account for auth token provided
,I/System.out( 1666): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1666): Tagging socket 54 with tag 120100000000{4609,0} for uid -1, pid: 1666, getuid(): 10011
,I/SA      ( 5898): [TPMU] GetMccFromDB : null
,I/SA      ( 5898): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 5898): [SCU] saveMccToPreferece End
,I/SA      ( 5898): [RC New] executeRequest [v2liruge] end. 1003
I/SA      ( 5898): [RC New] Execute end
,I/SA      ( 5898): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 5898): [OR] GetMyCountryZoneTask Success
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1666): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1666): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1666): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1666): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1666): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1175): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/Uploader( 1666): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1666): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1666): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1666): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1666): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1666): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1666): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1666): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1666): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1666): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1666): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1666): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1666): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
D/PersonaManager( 1175): isKioskContainerExistOnDevice
D/PersonaManager( 1175): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1175): Icon Only
I/StatusBar( 1175): Icon Only
D/PanelView( 1175): There is/are notification(s) 
D/PanelView( 1175): kidsfalse mQsExpansionEnabled:true
D/PersonaManager( 1175): isKioskContainerExistOnDevice,
I/PhoneStatusBar( 1175): Icon Only
I/StatusBar( 1175): Icon Only
D/PanelView( 1175): There is/are notification(s) 
D/PanelView( 1175): kidsfalse mQsExpansionEnabled:true
I/System.out( 1666): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1666): Tagging socket 54 with tag 120100000000{4609,0} for uid -1, pid: 1666, getuid(): 10011
,E/SMD     (  288): DCD OFF,
,I/jxcore-log( 6145): Test app app.js loaded,
I/jxcore-log( 6145): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6145): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 6145): BLE advertisement is supported
I/jxcore-log( 6145): 
,I/Choreographer( 6145): Skipped 360 frames!  The application may be doing too much work on its main thread.
,I/chromium( 6145): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/PanelView( 1175): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,I/GLSUser ( 1666): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1666): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1666): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1666): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1666): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,E/Uploader( 1666): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1666): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1666): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1666): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1666): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1666): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1666): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1666): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1666): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1666): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1666): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1666): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1666): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/StatusBar( 1175): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1175): Icon Only
I/StatusBar( 1175): Icon Only
D/PanelView( 1175): There is/are notification(s) 
D/PanelView( 1175): kidsfalse mQsExpansionEnabled:true
,I/System.out( 1666): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1666): Tagging socket 54 with tag 120100000000{4609,0} for uid -1, pid: 1666, getuid(): 10011
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1175): Icon Only
I/StatusBar( 1175): Icon Only
D/PanelView( 1175): There is/are notification(s) 
,D/PanelView( 1175): kidsfalse mQsExpansionEnabled:true
,D/PanelView( 1175): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1666): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1666): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1666): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1666): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1666): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1175): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/Uploader( 1666): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1666): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1666): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1666): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1666): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1666): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1666): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1666): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1666): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1666): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1666): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1666): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1666): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
D/PersonaManager( 1175): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1175): Icon Only
I/StatusBar( 1175): Icon Only
D/PanelView( 1175): There is/are notification(s) 
D/PanelView( 1175): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1175): Icon Only
I/StatusBar( 1175): Icon Only
,D/PanelView( 1175): There is/are notification(s) 
D/PanelView( 1175): kidsfalse mQsExpansionEnabled:true
,I/System.out( 1666): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1666): Tagging socket 54 with tag 120100000000{4609,0} for uid -1, pid: 1666, getuid(): 10011
,D/PanelView( 1175): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/SQLiteLog( 1666): (10) POSIX Error : 11 SQLite Error : 3850
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/WearableService( 3455): callingUid 10011, callindPid: 3455
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/MusicLeanback( 6219): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 6219): Stop autocaching.
,E/GmsUtils( 6219): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 6219): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2636): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,V/AlarmManager( 1018): waitForAlarm result :4
,D/EnterpriseController(  278): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 503 for uid 10011
,D/GCM     ( 1666): Connected
,W/ActivityManager( 1018): userId = 0, bbcId = -10000,
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023,
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk,
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/GCM     ( 1666): Message class com.google.f.a.a.p
W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GCM     ( 2066): Message from null null
E/GCM     ( 2066): Dropping message from null
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,I/SurfaceFlinger(  257): id=14 Removed Uoast (8/9),
D/PowerManagerService( 1018): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1018) eventTime = 177568
I/SurfaceFlinger(  257): id=14 Removed Uoast (-2/9)
D/PowerManagerService( 1018): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1018 (0x0)
D/PowerManagerService( 1018): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1018, ws=WorkSource{10049}) (elapsedTime=3476)
,E/SMD     (  288): DCD OFF
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5713): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 5713): [hasSamungAccount] - No Samsung Account
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5713): [GetString-S]
,I/ReactiveServiceManager( 5713): Supported : 1
,D/QSEECOMAPI: ( 1018): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 1018): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1018): Loaded image: APP id = 11
,D/QSEECOMAPI: ( 1018): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 1018): QSEECom_shutdown_app, app_id = 11
E/terrier ( 1018): handleString: Failed to handle string(-4)
,E/terrier ( 1018): Java_com_android_server_ReactiveService_GetString: error code = [-4]
D/PCWCLIENTTRACE_SecurePreferencesJNI( 5713): getString is null
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5713): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 5713): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5713): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5713): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 5713): [ensureRegistration] - No Samsung account
,I/dhcpcd  ( 6246): wlan0: sending IPv6 Router Solicitation
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4
,I/dhcpcd  ( 6246): wlan0: sending IPv6 Router Solicitation
I/dhcpcd  ( 6246): wlan0: no IPv6 Routers available
,I/ServiceManager(  322): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1018): SIOP:: AP = 290
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/PreloadUpdateManagerStateMachine( 6032): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 6032): exit::IDLE
D/PreloadUpdateManagerStateMachine( 6032): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 6032): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 6032): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 6032): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 6032): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 6032): entry::IDLE
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/PreloadUpdateManagerStateMachine( 6032): execute::IDLE:EXECUTE
D/PreloadUpdateManagerStateMachine( 6032): exit::IDLE
D/PreloadUpdateManagerStateMachine( 6032): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 6032): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 6032): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 6032): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 6032): entry::IDLE
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,V/AlarmManager( 1018): waitForAlarm result :4
,V/GLSActivity( 1666): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1666): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1666): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1666): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1666): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1666): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5386): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5386): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 5386): [1] 5.onFinished: Giving up after 6 failures.
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2636): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 290
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1018): !@Sync 6
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 270
,I/PowerManagerService( 1018): [PWL] Off : 140s ago,
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,I/Atfwd_Sendcmd(  322): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  322): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2636): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,V/AlarmManager( 1018): waitForAlarm result :8
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/Watchdog( 1018): !@Sync 7
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2636): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1175): level :100 plugged : 2
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,I/PowerManagerService( 1018): [PWL] Off : 180s ago
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 3,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2636): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,E/Watchdog( 1018): !@Sync 8
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 4
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 1018): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1175): handleTimeUpdate
,D/SecKeyguardClockView( 1175): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1175): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1175): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1175): *** don't update sliding image ***
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1175): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksSync( 6060): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6060): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1666): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1666): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1666): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1666): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1666): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1175): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
D/PersonaManager( 1175): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1175): Icon Only
I/StatusBar( 1175): Icon Only
D/PanelView( 1175): There is/are notification(s) 
D/PanelView( 1175): kidsfalse mQsExpansionEnabled:true
D/PersonaManager( 1175): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1175): Icon Only
I/StatusBar( 1175): Icon Only
D/PanelView( 1175): There is/are notification(s) 
D/PanelView( 1175): kidsfalse mQsExpansionEnabled:true
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,V/AlarmManager( 1018): waitForAlarm result :8
,I/GLSUser ( 1666): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1666): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1666): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1666): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1666): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6060): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6060): Soft error
E/BooksSync( 6060): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6060): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 6060): Sync error
E/BooksSync( 6060): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6060): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6060): Finished books sync
,D/SyncManager( 1018): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 277005, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1175): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1018): mCursor = null
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1018): !@Sync 9
,I/PowerManagerService( 1018): [PWL] Off : 225s ago
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 5,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1175): handleTimeUpdate
,D/SecKeyguardClockView( 1175): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1175): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1175): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1175): *** don't update sliding image ***
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1175): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/TimaService( 1018): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1018): TimaServiceHandler.handleMessage what =1
D/TimaService( 1018): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize( 1018): initializing...
,I/TLC_TIMA_PKM_initialize( 1018): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize( 1018): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1018): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1018): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1018): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1018): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication( 1018): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: ( 1018): QSEECom_get_handle sb_length = 0x80080
D/QSEECOMAPI: ( 1018): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1018): Loaded image: APP id = 12
,I/TZ: qc_tlc_communication( 1018): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize( 1018): Trustlet response is completed
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2636): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,E/Watchdog( 1018): !@Sync 10
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,I/Atfwd_Sendcmd(  322): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  322): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2636): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 1018): waitForAlarm result :4
,I/BooksSync( 6060): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6060): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,V/AlarmManager( 1018): waitForAlarm result :8
,I/GLSUser ( 1666): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1666): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1666): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1666): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1666): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1175): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1175): Icon Only
I/StatusBar( 1175): Icon Only
D/PanelView( 1175): There is/are notification(s) 
D/PanelView( 1175): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1175): Icon Only
I/StatusBar( 1175): Icon Only
,D/PanelView( 1175): There is/are notification(s) 
D/PanelView( 1175): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1666): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1666): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1666): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1666): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1666): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6060): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6060): Soft error
E/BooksSync( 6060): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6060): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 6060): Sync error
E/BooksSync( 6060): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6060): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6060): Finished books sync
,D/SyncManager( 1018): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 309727, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1175): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1018): mCursor = null
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/PowerManagerService( 1018): [PWL] Off : 275s ago
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1018): !@Sync 11
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/jxcore-log( 6145): --= Surplus to requirements =--
I/jxcore-log( 6145): 
,I/jxcore-log( 6145): ****TEST TOOK:  ms ****
I/jxcore-log( 6145): 
I/jxcore-log( 6145): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6145): 
,D/AndroidRuntime( 6635): 
D/AndroidRuntime( 6635): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6635): CheckJNI is OFF
,D/AndroidRuntime( 6635): readGMSProperty: start
D/AndroidRuntime( 6635): readGMSProperty: already setted!!
D/AndroidRuntime( 6635): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6635): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6635): readGMSProperty: end
D/AndroidRuntime( 6635): addProductProperty: start
,E/AffinityControl( 6635): AffinityControl: registerfunction enter,
,D/AndroidRuntime( 6635): Calling main entry com.android.commands.pm.Pm,
,D/PersonaManagerService( 1018): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
D/PackageManager( 1018): START PACKAGE DELETE: observer{248042635}
D/PackageManager( 1018): pkg{<packageName>}
D/PackageManager( 1018): user{0}
D/PackageManager( 1018): caller{2000}
D/PackageManager( 1018): flags{3}
D/PersonaManagerService( 1018): isFromApprovedUnInstaller: isApproved : true,
D/PackageManager( 1018): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService( 1018): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1018): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1018): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 1018): deletePackage- pkg:com.test.thalitest, edmuserId:0,
D/PackageManagerService( 1018): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/PackageManager( 1018): !@killApplicatoin: 10338, uninstall pkg
D/ApplicationPolicy( 1018): getApplicationUninstallationEnabled,
D/ApplicationPolicy( 1018): getApplicationUninstallationEnabled :  enabled true
,I/ActivityManager( 1018): Force stopping com.test.thalitest appid=10338 user=-1: uninstall pkg
,I/ActivityManager( 1018): Killing 6145:com.test.thalitest/u0a338 (adj 0): stop com.test.thalitest cause uninstall pkg
,W/PackageSettings( 1018): Skipping PackageSetting{1abb3e81 com.example.hello/10346} due to missing metadata
,I/ActivityManager( 1018):   Force finishing activity ActivityRecord{3a355684 u0 com.test.thalitest/.MainActivity t20}
,E/JavaBinder( 1018): !!! FAILED BINDER TRANSACTION !!!
,D/InputDispatcher( 1018): Focus left window: 6145
,I/SurfaceFlinger(  257): id=13 Removed NainActivit (6/8)
,I/SurfaceFlinger(  257): id=13 Removed NainActivit (-2/8)
,D/InputDispatcher( 1018): Focused application released
,E/JavaBinder( 1018): !!! FAILED BINDER TRANSACTION !!!
,D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
,I/ActivityManager( 1018): Force stopping com.test.thalitest appid=10338 user=0: pkg removed
,W/ActivityManager( 1018): CustomStartingWindow se packge removed so remove capture also
,I/art     ( 3936): Explicit concurrent mark sweep GC freed 3164(190KB) AllocSpace objects, 1(16KB) LOS objects, 50% free, 3MB/7MB, paused 758us total 27.655ms
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/InputReader( 1018): Reconfiguring input devices.  changes=0x00000010
,I/art     ( 6016): Explicit concurrent mark sweep GC freed 100(15KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 5MB/7MB, paused 734us total 32.813ms
,E/SamsungIME( 1885): mOCRHelper is null
,W/GeofencerStateMachine( 1820): Ignoring removeGeofence because network location is disabled.
,I/KLMS-2.5.123: ( 3619): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Jan 18 08:39:13 GMT+01:00 2016
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3619): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 1018): intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=27
I/splitIntent( 1018): base  index=27, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
I/splitIntent( 1018): other index=30, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
I/splitIntent( 1018): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6648): MountEmulatedStorage()
,E/Zygote  ( 6648): v2,
I/libpersona( 6648): KNOX_SDCARD checking this for 10090
I/ActivityManager( 1018): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6648 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
I/libpersona( 6648): KNOX_SDCARD not a persona,
,I/SELinux ( 6648): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 6648): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6648): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/KLMS-2.5.123: ( 3619): KLMSIntentService(): onCreate()
I/KLMS-2.5.123: ( 3619): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.123: ( 3619): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,D/TimaKeyStoreProvider( 6648): TimaSignature is unavailable
,D/ActivityThread( 6648): Added TimaKeyStore provider
,I/KLMS-2.5.123: ( 3619): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.123: ( 3619): KLMSIntentService(): PACKAGE_REMOVED
,D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1018): mCursor = null
,I/KLMS-2.5.123: ( 3619): KLMSIntentService(): listeningToPackageRemoved().START
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 49081(3MB) AllocSpace objects, 79(1286KB) LOS objects, 33% free, 24MB/36MB, paused 2.833ms total 182.164ms
I/art     ( 1018): WaitForGcToComplete blocked for 123.235ms for cause Explicit
,D/RegisteredServicesCache( 1444): empty dynamic service
,I/KLMS-2.5.123: ( 3619): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,D/elm:15121( 6648): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:15121( 6648): ELMEngine.ELMEngine( context ).
,D/elm:15121( 6648): MDMBridge.setEnterpriseBridge()
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/elm:15121( 6648): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/elm:15121( 6648): ElmAgentService : onCreate()
,D/elm:15121( 6648): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:15121( 6648): MainReceiver.listeningToPackageRemoved()
D/elm:15121( 6648): MDMBridge.getInstance()
D/elm:15121( 6648): MDMBridge.getAllLicenseInfoFromSDK()
,D/RCPManagerService( 1018): PackageReceiver onReceive()
D/elm:15121( 6648): MDMBridge.getAllLicenseInfoFromSDK()
,I/HarmonyEASService( 1018): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 1018): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/EnterpriseDeviceManagerService( 1018): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1018): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1018): no available spell checker services found
,D/elm:15121( 6648): ElmAgentService : onDestroy().
,I/ActivityManager( 1018): Killing 5864:com.wsomacp/u0a23 (adj 15): empty #31
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/KLMS-2.5.123: ( 3619): KLMSIntentService(): listeningToPackageRemoved().END
,I/KLMS-2.5.123: ( 3619): KLMSIntentService(): onDestroy()
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 10845(529KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 24MB/36MB, paused 3.243ms total 185.202ms
I/art     ( 1018): WaitForGcToComplete blocked for 184.467ms for cause Explicit
,W/ResourceType( 1018): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,D/BackupManagerService( 1018): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService( 1018): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1018): uID is 10338
V/EnterpriseBillingPolicy( 1018): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - end - null
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,D/TaskPersister( 1018): removeObsoleteFile: deleting file=20_task.xml
,D/SSRM:aZ ( 1018): MSG_TYPE_APP_REMOVED::
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
,V/EnterpriseBillingPolicy( 1018): uID is 10338
V/EnterpriseBillingPolicy( 1018): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - start - com.test.thalitest
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - end - null
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/PCWCLIENTTRACE_PushUtil( 5713): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5713): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 5713): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5713): [onReceive] - android.intent.action.PACKAGE_REMOVED
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 1018): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1018): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1018): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/PackageManager( 1018): delete codoeFile: 
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/AASA_removePackage( 1018): UID=10338 Target=com.test.thalitest
D/AASAuninstall( 1018): userId = 0, info.removedAppID = -1, info.uid = 10338, packageName = com.test.thalitest
,D/PackageManager( 1018): result of delete: 1{248042635}
,E/Zygote  ( 6666): MountEmulatedStorage()
,E/Zygote  ( 6666): v2
I/libpersona( 6666): KNOX_SDCARD checking this for 10029
I/libpersona( 6666): KNOX_SDCARD not a persona
,I/SELinux ( 6666): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6666): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6666): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=6666 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 6666): TimaSignature is unavailable
,D/ActivityThread( 6666): Added TimaKeyStore provider
,D/AndroidRuntime( 6635): Shutting down VM
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 9080(429KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 24MB/36MB, paused 29.462ms total 189.195ms
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/SA      ( 5898): [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/FeatureConfig( 6666): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
I/SA      ( 5898): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10338 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/ActivityManager( 1018): Killing 5880:com.sec.android.app.soundalive/u0a48 (adj 15): empty #31
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,D/UsbSettingsManager( 1018): clearDefaults: com.test.thalitest
,I/CrashAnrDetector( 1018): onPackageRemoved : com.test.thalitest
,W/libprocessgroup( 1018): failed to open /acct/uid_10023/pid_5864/cgroup.procs: No such file or directory
,I/PackagesMonitor( 5015): PackagesMonitor onReceive :com.test.thalitest
,W/ResourcesManager( 6666): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 6666): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6666): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6666): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 6666): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/ResourcesManager( 6666): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 6666): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6666): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6666): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6666): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6666): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 6666): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6666): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6666): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6666): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6666): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6666): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,E/Zygote  ( 6684): MountEmulatedStorage(),
I/libpersona( 6684): KNOX_SDCARD checking this for 10041
E/Zygote  ( 6684): v2
I/libpersona( 6684): KNOX_SDCARD not a persona
I/SELinux ( 6684): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageStatusReceiver: pid=6684 uid=10041 gids={50041, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
I/SELinux ( 6684): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6684): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,W/ResourcesManager( 6666): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6666): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6666): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6666): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 6666): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6666): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6666): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6666): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6666): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6666): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 6684): TimaSignature is unavailable
,D/ActivityThread( 6684): Added TimaKeyStore provider
,W/ResourcesManager( 6666): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 6666): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6666): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6666): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 6666): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 6666): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6666): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6666): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6684): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 6684): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6684): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6684): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6684): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/ResourcesManager( 6666): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 6666): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6666): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6666): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6666): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/libprocessgroup( 1018): failed to open /acct/uid_10048/pid_5880/cgroup.procs: No such file or directory
,W/ResourcesManager( 6666): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 6666): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
,W/ResourcesManager( 6666): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6666): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6666): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 6666): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 6666): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/GalaxyFinderApplication( 6666): system/finder_cp/cpdata.xml file not found
,D/Mms/MmsApp( 6684): [start]    onCreate() consume time = 0.0
,W/art     ( 6635): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.,
,W/ActivityManager( 1018): userId = 0, bbcId = -10000,
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,W/art     ( 6684): Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 109.810ms
,D/Mms/TelephonyPermission( 6684): start operation mode monitor
,D/Mms/ArtClassLoader( 6684): init before art
,W/ResourcesManager( 6684): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.

```
