#### Test 57924002a578a80_thali04_samsung-SM-G900F Logs


```
--------- beginning of system
,V/AlarmManager(  908): waitForAlarm result :4
--------- beginning of main
D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1183): handleTimeUpdate
D/KeyguardEffectViewController( 1183): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1183): *** don't update sliding image ***
D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  908): stay LED for fully charged
D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
V/HeadsetService( 3227): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3227): Disconnected process message: 10
D/MotionRecognitionService(  908):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  908): Plugged
I/MotionRecognitionService(  908): setPowerConnected  = true
D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
D/DateView( 1183): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/DateView( 1183): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/AndroidRuntime( 7519): 
D/AndroidRuntime( 7519): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7519): CheckJNI is OFF
D/AndroidRuntime( 7519): setted country_code = Poland
D/AndroidRuntime( 7519): setted countryiso_code = PL
D/AndroidRuntime( 7519): setted sales_code = XEO
D/AndroidRuntime( 7519): readGMSProperty: start
D/AndroidRuntime( 7519): readGMSProperty: already setted!!
D/AndroidRuntime( 7519): readGMSProperty: end
D/AndroidRuntime( 7519): addProductProperty: start
E/SMD     (  292): DCD ON
E/AffinityControl( 7519): AffinityControl: registerfunction enter
D/AndroidRuntime( 7519): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  908): inState():  stateMachine is null !!
V/ApplicationPolicy(  908): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager(  908): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  908): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager(  908): mDVFSHelper.acquire()
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7549): MountEmulatedStorage()
E/Zygote  ( 7549): v2
I/libpersona( 7549): KNOX_SDCARD checking this for 10191
I/libpersona( 7549): KNOX_SDCARD not a persona
I/ActivityManager(  908): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7549 uid=10191 gids={50191, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/AndroidRuntime( 7519): Shutting down VM
I/SELinux ( 7549): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7549): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7549): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/TimaKeyStoreProvider( 7549): TimaSignature is unavailable
D/ActivityThread( 7549): Added TimaKeyStore provider
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
I/SurfaceFlinger(  257): id=13 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (5/8)
I/SurfaceFlinger(  257): id=13 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (-2/8)
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SQLiteSecureOpenHelper( 3513): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3513): getDatabaseLocked(b,b,pwd)...
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/ResourcesManager( 7549): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
,I/WebViewFactory( 7549): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager( 7549): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader( 7549): Loading: webviewchromium
I/LibraryLoader( 7549): Time to load native libraries: 7 ms (timestamps 9271-9278)
I/LibraryLoader( 7549): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7549): Binding Chromium to main looper Looper (main, tid 1) {16ea6cc8}
I/LibraryLoader( 7549): Expected native library version number "",actual native library version number ""
I/chromium( 7549): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7549): Initializing chromium process, renderers=0
W/art     ( 7549): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 7549): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7549): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium( 7549): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
W/ActivityManager(  908): Activity pause timeout for ActivityRecord{10f80644 u0 com.test.thalitest/.MainActivity t11}
I/Adreno-EGL( 7549): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7549): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7549): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7549): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7549): Remote Branch: 
I/Adreno-EGL( 7549): Local Patches: 
I/Adreno-EGL( 7549): Reconstruct Branch: 
W/chromium( 7549): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 7549): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 7549): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 7549): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 7549): CordovaWebView is running on device made by: samsung
W/art     ( 7549): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7549): Attempt to remove local handle scope entry from IRT, ignoring
D/Activity( 7549): performCreate Call secproduct feature valuefalse
D/Activity( 7549): performCreate Call debug elastic valuetrue
D/OpenGLRenderer( 7549): Render dirty regions requested: true
D/ActivityManager(  908): post active user change for 0
D/KnoxTimeoutHandler(  908): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  908): handleActiveUserChange for user 0
I/SurfaceFlinger(  257): id=15 createSurf (1x1),1 flag=404, com.test.thalitest/com.test.thalitest.MainActivity
D/StatusBarManagerService(  908): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/StatusBarManagerService(  908): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
,D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1183): value : false
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1183): value : false
,I/OpenGLRenderer( 7549): Initialized EGL, version 1.4
,I/OpenGLRenderer( 7549): HWUI protection enabled for context ,  &this =0xa1753060 ,&mEglDisplay = 1 , &mEglConfig = 8 
,D/OpenGLRenderer( 7549): Enabling debug mode 0
,D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1183): value : false
,D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1183): value : false
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
,D/InputMethodManagerService(  908): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1183): value : false
,W/ActivityManager(  908): mDVFSHelper.release()
I/Timeline(  908): Timeline: Activity_windows_visible id: ActivityRecord{10f80644 u0 com.test.thalitest/.MainActivity t11} time:209934
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
,W/IInputConnectionWrapper( 7549): showStatusIcon on inactive InputConnection
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
,I/Timeline( 7549): Timeline: Activity_idle id: android.os.BinderProxy@3efa435b time:209938
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1183): value : false
,I/chromium( 7549): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7549): 
,D/JsMessageQueue( 7549): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 7549): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1357563520
,I/chromium( 7549): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/art     ( 7549): Background sticky concurrent mark sweep GC freed 43709(3MB) AllocSpace objects, 12(671KB) LOS objects, 15% free, 19MB/23MB, paused 2.470ms total 156.477ms
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  292): DCD ON
,I/PowerManagerService(  908): [PWL] Off : 140s ago
,W/jxcore-log( 7549): Initializing JXcore engine
W/jxcore-log( 7549): JXcore engine is ready
,E/auditd  ( 2169): In denial and Property audit_ondenial is set to 1 
W/jxcore-log( 7549): Starting JXcore engine
,D/SecurityLogAgent:SEDenialService(  908): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService(  908): audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7634): MountEmulatedStorage()
E/Zygote  ( 7634): v2
I/libpersona( 7634): KNOX_SDCARD checking this for 1000
I/libpersona( 7634): KNOX_SDCARD not a persona
,I/ActivityManager(  908): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=7634 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7634): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7634): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7634): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7634): TimaSignature is unavailable
,D/ActivityThread( 7634): Added TimaKeyStore provider
,D/ResourcesManager( 7634): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,W/jxcore-log( 7549): Platform android
W/jxcore-log( 7549): 
W/jxcore-log( 7549): Process ARCH arm
W/jxcore-log( 7549): 
,D/SecurityLogAgent( 7634):  SeDenialReceiver : Intent Received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 7634):  SeDenialReceiver : File path = null
,I/ActivityManager(  908): Killing 6515:com.sec.knox.bridge/1000 (adj 15): bgCount ##41
,W/libprocessgroup(  908): failed to open /acct/uid_1000/pid_6515/cgroup.procs: No such file or directory
,D/SSRM:m  (  908): SIOP:: AP = 290, PST = 285, CUR = 450
,I/jxcore-log( 7549): JXcore Cordova bridge is ready!
I/jxcore-log( 7549): 
,W/jxcore-log( 7549): JXcore engine is started
,I/jxcore-log( 7549): Toggling radios to true
I/jxcore-log( 7549): 
,D/BluetoothAdapter( 7549): enable()
,D/BluetoothAdapter( 7549): enable(): BT is already enabled..!
,D/WifiService(  908): New client listening to asynchronous messages
,I/WifiManager( 7549): packageName : com.test.thalitest
,D/SecContentProvider(  908): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2(  908): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  908): mCursor = null
D/WifiService(  908): setWifiEnabled: true pid=7549, uid=10191
,E/WifiService(  908): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager(  908): Permission Denial: getCurrentUser() from pid=7549, uid=10191 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService(  908): Failed getting userId using ActivityManagerNative
W/WifiService(  908): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7549, uid=10191 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  908): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:22619)
W/WifiService(  908): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2122)
W/WifiService(  908): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2110)
W/WifiService(  908): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService(  908): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SettingsProvider(  908): name = wifi_on
I/WifiService(  908): disconnect: pid=7549, uid=10191
,I/jxcore-log( 7549): Radios toggled
I/jxcore-log( 7549): 
I/jxcore-log( 7549): My device name is: samsung-SM-G900F
I/jxcore-log( 7549): 
I/wpa_supplicant( 1302): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/wpa_supplicant( 1302): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 1302): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 1302): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1302): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  908): WifiStateMachine: Leaving Connected state
,I/wpa_supplicant( 1302): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1302): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1302): Disconnected - do not scan
I/wpa_supplicant( 1302): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  908): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - exit - invokeExitMethods
E/WifiStateMachine(  908): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  908): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  908): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  908): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine(  908): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  908): do suspend true
,D/WifiP2pService(  908): InactiveState{ what=143375 }
,D/WifiP2pService(  908): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1183): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/CommandListener(  285): Clearing all IP addresses on wlan0
,V/NativeCrypto( 2251): Read error: ssl=0xaf6f5e00: I/O error during system call, Connection timed out
,V/NativeCrypto( 2251): SSL shutdown failed: ssl=0xaf6f5e00: I/O error during system call, Broken pipe
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  908): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  908): DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  908): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  908): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  908): Validated
D/ConnectivityService(  908): Validated NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  908): rematching NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  908):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/ConnectivityService(  908):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  908):   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  908): Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
D/ConnectivityService(  908): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityService(  908): calling update connectivity
I/Atfwd_Sendcmd(  329): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  329): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
D/ConnectivityService(  908):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  908):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  908): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  908):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 1183): CM callback handler got msg 524290
,D/ConnectivityService(  908): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityManager.CallbackHandler( 2490): CM callback handler got msg 524290
,E/WifiStateMachine(  908): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
,E/ConnectivityService(  908): updateNetworkInfo()
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  908): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService(  908): updateNetworkInfo()
D/ConnectivityService(  908): ignoring duplicate network state non-change
D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,E/WifiConfigStore(  908): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/WifiTrafficPoller(  908): evaluateTrafficStatsPolling
,I/CLocInfoService(  908): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1183): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
E/WifiStateMachine(  908): Start Disconnecting Watchdog 1
D/StatusBar.NetworkController( 1183): applyOpen
I/wpa_supplicant( 1302): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1302): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1302): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1302): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1302): First Scan Start
,E/WifiStateMachine(  908): ConnectModeState: Network connection lost 
I/wpa_supplicant( 1302): Scan requested (ret=0) - scan timeout 30 seconds
E/WifiStateMachine(  908): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - processMessage - processMsg
,E/WifiStateMachine(  908): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine(  908): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  908): do suspend true
D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1183): applyOpen
D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1183): applyOpen
,D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1183): applyOpen
,D/WifiP2pService(  908): InactiveState{ what=143375 }
,D/WifiP2pService(  908): P2pEnabledState{ what=143375 }
,I/Hs20UtilService( 1313): Starting #6
,I/Hs20UtilService( 1313): Message received 5007
,D/StatusBar.NetworkController( 1183): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/NearbySettings( 1313): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1313): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1313): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1313): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1313): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1313): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1313): MountReceiver.mPrefHandler - 7002
,D/CommandListener(  285): Clearing all IP addresses on wlan0
,D/ConnectivityService(  908): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  908): calling update connectivity
D/ConnectivityService(  908):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  908):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  908): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
E/WifiStateMachine(  908): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/ConnectivityService(  908):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  908): sending notification LOST for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/Nat464Xlat(  908): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  908): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WifiStateMachine(  908): updateConfiguredNetworkExpiration - currTime: 1454460319673
D/ConnectivityService(  908): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WifiStateMachine(  908): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  908): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityManager.CallbackHandler( 1183): CM callback handler got msg 524292
,E/WifiStateMachine(  908): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  908): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/EntConnectivity(  908): Not allowed due to - mEnabled false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  908): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  908): Disconnected - quitting
,I/WifiTrafficPoller(  908): evaluateTrafficStatsPolling
,D/TelephonyNetworkFactory( 1477): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/CLocInfoService(  908): External Intent Received android.net.wifi.STATE_CHANGE
,D/CSLegacyTypeTracker(  908): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker(  908): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
,E/WifiStateMachine(  908): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  908): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/ConnectivityManager.CallbackHandler( 2490): CM callback handler got msg 524292
,E/WifiStateMachine(  908): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
D/ConnectivityService(  908): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,E/WifiStateMachine(  908): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent(  908): NetworkAgent: NetworkAgent channel lost
,D/StatusBar.NetworkController( 1183): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/WifiStateMachine(  908): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  908): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  908): setDetailed state send new extra info"NG700"
,D/ConnectivityService(  908): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  908): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService(  908): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  908): getSBEnabled() enabled =false
D/SmartBondingService(  908): getSBEnabled() enabled =false
D/SmartBondingService(  908): getSBEnabled() enabled =false
,D/SecContentProvider2(  908): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  908): mCursor = null
V/NetworkStats(  908): updateIfacesLocked()
V/NetworkStats(  908): performPollLocked(flags=0x1)
D/NtpTrustedTime(  908): currentTimeMillis() cache hit
D/SmartBondingService(  908): getNetworkEnabled : wifi : true mobile : true
D/NetworkStatsFactory(  908): UpdateStatsForKnox
D/ConnectivityService(  908): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1183): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1183): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1183): updateDataNetType()
D/StatusBar.NetworkController( 1183): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1183): updateLTEICONDataNetType:0
D/NtpTrustedTime(  908): currentTimeMillis() cache hit
D/NtpTrustedTime(  908): currentTimeMillis() cache hit
D/NtpTrustedTime(  908): currentTimeMillis() cache hit
V/NetworkStats(  908): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  908): currentTimeMillis() cache hit
V/NetworkStats(  908): performPollLocked() took 6ms
D/NtpTrustedTime(  908): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1183): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1183): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1183): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1183): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1183): applyOpen
D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1183): applyOpen
D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1183): applyOpen
D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1183): applyOpen
I/Hs20UtilService( 1313): Starting #7
I/Hs20UtilService( 1313): Message received 5007
D/NtpTrustedTime(  908): currentTimeMillis() cache hit
D/NtpTrustedTime(  908): currentTimeMillis() cache hit
D/SecContentProvider2(  908): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  908): mCursor = null
D/NearbySettings( 1313): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1313): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1313): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/ConnectivityService(  908): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1313): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1313): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1313): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1313): MountReceiver.mPrefHandler - 7002
D/FileWriteThread_Telephony( 1477): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1477): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1477): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1477): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1477): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1477): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1477): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1477): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1477): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1477): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1477): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1477): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1477): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1477): FileWriteThread : threadType = 3
W/ProcessCpuTracker(  908): Skipping unknown process pid 7659
W/ProcessCpuTracker(  908): Skipping unknown process pid 7662
D/ConnectivityService(  908): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ApplicationPolicy(  908): updateDataUsageMap
D/ConnectivityService(  908): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  908): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Tethering(  908): MasterInitialState.processMessage what=3
D/SmartBondingService(  908): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  908): getSBEnabled() enabled =false
D/SmartBondingService(  908): getSBEnabled() enabled =false
D/SmartBondingService(  908): getSBEnabled() enabled =false
I/CLocInfoService(  908): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  908): CLoinfo wifi false
D/SmartBondingService(  908): getNetworkEnabled : wifi : true mobile : true
I/SystemBroadcastReceiver( 6320): [#DCM#] [DCM_Performance] onReceive completed in time  1312 microsec. 
D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/PCWCLIENTTRACE_PushUtil( 7056): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7056): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7056): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7056): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
I/PCWCLIENTTRACE_SYSTEMReceiver( 7056): noConnectivity : true
I/DBG_DM  ( 3732): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
D/ConnectivityService(  908): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/DBG_DM  ( 3732): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
I/NetworkMonitor( 6284): type=WIFI subType= reason=null isConnected=false
W/SLocation(  908): No Active Data Connection
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7690): MountEmulatedStorage()
E/Zygote  ( 7690): v2
I/libpersona( 7690): KNOX_SDCARD checking this for 10002
I/libpersona( 7690): KNOX_SDCARD not a persona
D/accuweather( 2194): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
I/ActivityManager(  908): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7690 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SystemBroadcastReceiver( 6320): [#DCM#] Calling notifyListeners. 
I/DCMController( 6320): [#DCM#] onIntentReceived eventid = EVENT_NETWORK_CHANGED
I/DCMController( 6320): [#DCM#] setIsConnectedForExtractors 
I/SELinux ( 7690): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7690): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7690): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7690): TimaSignature is unavailable
D/ActivityThread( 7690): Added TimaKeyStore provider
D/ResourcesManager( 7690): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
I/ActivityManager(  908): Killing 6562:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): bgCount ##41
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7716): MountEmulatedStorage()
E/Zygote  ( 7716): v2
I/libpersona( 7716): KNOX_SDCARD checking this for 1000
I/libpersona( 7716): KNOX_SDCARD not a persona
I/ActivityManager(  908): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7716 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7716): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7716): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7716): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7716): TimaSignature is unavailable
,D/ActivityThread( 7716): Added TimaKeyStore provider
,D/ResourcesManager( 7716): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,W/libprocessgroup(  908): failed to open /acct/uid_1000/pid_6562/cgroup.procs: No such file or directory
,I/DIAGMON_AGENT( 7716): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,I/DIAGMON_AGENT( 7716): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/DIAGMON_AGENT( 7716): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 7716): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 7716): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7716): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7736): MountEmulatedStorage()
E/Zygote  ( 7736): v2
I/libpersona( 7736): KNOX_SDCARD checking this for 10010
I/libpersona( 7736): KNOX_SDCARD not a persona
,I/ActivityManager(  908): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=7736 uid=10010 gids={50010, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/wpa_supplicant( 1302): nl80211: Received scan results (4 BSSes)
I/wpa_supplicant( 1302): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1302): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 1302): wlan0: State: SCANNING -> ASSOCIATING
,I/wpa_supplicant( 1302): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
E/WifiStateMachine(  908): [1,454,460,320,722 ms] noteScanEnd no scan source
,E/WifiStateMachine(  908): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@3d7040f6 sup_state=SCANNING debouncing=false
,I/SELinux ( 7736): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/CLocInfoService(  908): External Intent Received android.net.wifi.SCAN_RESULTS
E/WifiStateMachine(  908): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  908): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  908): setDetailed state send new extra info0x
D/SecContentProvider2(  908): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  908): mCursor = null
I/SELinux ( 7736): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7736): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7736): TimaSignature is unavailable
,D/ActivityThread( 7736): Added TimaKeyStore provider
,D/ResourcesManager( 7736): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/wpa_supplicant( 1302): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 1302): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 1302): Associated with C0.AA.48
E/WifiStateMachine(  908): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  908): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
D/SecContentProvider2(  908): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  908): mCursor = null
,I/ActivityManager(  908): Killing 5872:com.samsung.android.app.mirrorlink/1000 (adj 15): bgCount ##41
I/wpa_supplicant( 1302): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1302): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
E/WifiStateMachine(  908): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  908): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  908): setDetailed state send new extra info"NG700"
D/SecContentProvider2(  908): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  908): mCursor = null
I/FOTA_Client( 7736): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
I/FOTA_Client( 7736): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
I/wpa_supplicant( 1302): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1302): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 1302): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
E/WifiStateMachine(  908): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  908): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
I/wpa_supplicant( 1302): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1302): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1302): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 1302): Blacklist: Clear (temp) 
I/wpa_supplicant( 1302): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
E/WifiStateMachine(  908): Network connection established
,D/WifiNative-HAL(  908): callSECApiVoid - ID [50]
,E/WifiStateMachine(  908): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/WifiStateMachine(  908): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/CLocInfoService(  908): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1183): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/ConnectivityService(  908): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,E/WifiStateMachine(  908): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
D/ConnectivityService(  908): Got NetworkAgent Messenger
D/ConnectivityService(  908): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService(  908): updateNetworkInfo()
D/ConnectivityService(  908): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  908): NetworkAgent connected
E/WifiStateMachine(  908): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  908): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/FOTA_Client( 7736): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
,E/WifiStateMachine(  908): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  908): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  908): ObtainingIpAddress "NG700" nid=0
,E/WifiConfigStore(  908): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  285): Setting iface cfg
,E/WifiStateMachine(  908): Start Dhcp Watchdog 2
,W/libprocessgroup(  908): failed to open /acct/uid_1000/pid_5872/cgroup.procs: No such file or directory
,D/SecContentProvider2(  908): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  908): mCursor = null
,E/Zygote  ( 7757): MountEmulatedStorage()
,E/Zygote  ( 7757): v2
I/libpersona( 7757): KNOX_SDCARD checking this for 10018
I/libpersona( 7757): KNOX_SDCARD not a persona
,I/ActivityManager(  908): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=7757 uid=10018 gids={50018, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  908): Killing 6100:com.sec.providers.settingsearch/u0a167 (adj 15): bgCount ##41
,E/WifiStateMachine(  908): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  908): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
D/ConnectivityService(  908): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,I/SELinux ( 7757): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7757): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7757): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7757): TimaSignature is unavailable
,D/ActivityThread( 7757): Added TimaKeyStore provider
,D/ResourcesManager( 7757): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,E/WifiStateMachine(  908): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
,E/native  (  908): do suspend false
,I/KLMS-2.4.503: ( 7757): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,D/SecContentProvider2(  908): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  908): mCursor = null
,I/KLMS-2.4.503: ( 7757): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1454460320979
,D/WifiP2pService(  908): InactiveState{ what=143375 }
D/WifiP2pService(  908): P2pEnabledState{ what=143375 }
,I/KLMS-2.4.503: ( 7757): MainReciver(): NETWORK_STATE_CHANGED_ACTION
W/libprocessgroup(  908): failed to open /acct/uid_10167/pid_6100/cgroup.procs: No such file or directory
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7757): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.503: ( 7757): StateImplV2(): networkChangeListener().END
,I/ActivityManager(  908): Killing 6055:com.google.android.gm/u0a113 (adj 15): bgCount ##41
,E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7772): MountEmulatedStorage()
E/Zygote  ( 7772): v2
I/libpersona( 7772): KNOX_SDCARD checking this for 10036
I/libpersona( 7772): KNOX_SDCARD not a persona
,I/ActivityManager(  908): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7772 uid=10036 gids={50036, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 7772): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7772): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7772): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7772): TimaSignature is unavailable
,D/ActivityThread( 7772): Added TimaKeyStore provider
,D/ResourcesManager( 7772): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/SO_AGENT( 7772): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,W/libprocessgroup(  908): failed to open /acct/uid_10113/pid_6055/cgroup.procs: No such file or directory
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 5212): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,I/SA      ( 7096): [OR] onReceive log=[SA = 2.1.0172 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOE5 PSS = 5.219788042639568  ]
,I/SA      ( 7096): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      ( 7096): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 7096): [SLFUCHKMGR] constructor called
,I/SA      ( 7096): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 7096): [OR] == isSIMCardReady false ==
,I/SA      ( 7096): [SCU] == networkStateCheck == false
I/SA      ( 7096): [OR] onReceive END
,E/SPPClientService( 5212): [[SystemStateMonitorService]] No Active Internet
,I/ActivityManager(  908): Killing 6320:com.samsung.dcm:DCMService/u0a4 (adj 15): bgCount ##41
,E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7790): MountEmulatedStorage()
I/libpersona( 7790): KNOX_SDCARD checking this for 10070
E/Zygote  ( 7790): v2
I/libpersona( 7790): KNOX_SDCARD not a persona
,I/ActivityManager(  908): Start proc com.sec.android.widgetapp.ap.hero.accuweather for broadcast com.sec.android.widgetapp.ap.hero.accuweather/.easy.widget.WeatherClock: pid=7790 uid=10070 gids={50070, 9997, 3003, 1028} abi=armeabi-v7a
,I/art     (  318): Explicit concurrent mark sweep GC freed 8723(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 280us total 11.829ms
,I/art     (  318): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 253us total 7.769ms
,I/art     (  318): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 251us total 7.482ms
,I/SELinux ( 7790): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7790): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7790): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/dhcpcd  ( 7796): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 7796): version 5.5.6 starting
,E/dhcpcd  ( 7796): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,D/TimaKeyStoreProvider( 7790): TimaSignature is unavailable
,D/ActivityThread( 7790): Added TimaKeyStore provider
,D/ResourcesManager( 7790): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
,W/ResourcesManager( 7790): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7790): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7790): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,W/libprocessgroup(  908): failed to open /acct/uid_10004/pid_6320/cgroup.procs: No such file or directory
,I/dhcpcd  ( 7796): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 7796): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 7796): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 7796): bssid match
,D/comsamsunglog( 7790): [KK AccuPhone]>>> ==============================================================================================
,I/dhcpcd  ( 7796): wlan0: rebinding lease of 192.168.1.136
D/comsamsunglog( 7790): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
D/comsamsunglog( 7790): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 7790): [KK AccuPhone]>>> ==============================================================================================
,D/comsamsunglog( 7790): [KK AccuPhone]>>> ==============================================================================================
D/comsamsunglog( 7790): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
,D/comsamsunglog( 7790): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 7790): [KK AccuPhone]>>> ==============================================================================================
,D/SettingsProvider(  908): name = aw_daemon_service_key_agree_popup_check
D/SettingsProvider(  908): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  908): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  908): selectionArgs: false
D/SettingsProvider(  908): selectionArgs: 10070
D/SecContentProvider(  908): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  908): ret = -1
,D/daemonapp( 1343): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7790): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7790): [KK AccuPhone]>>> WC:37 [0:0] oR : create UI manager : start
,D/accuweather( 7790): [KK AccuPhone]>>> UIMEM:90 [0:0] getInstance
,D/accuweather( 7790): [KK AccuPhone]>>> UIMEM:78 [0:0] UIManager : create ui manager
,D/accuweather( 7790): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
D/accuweather( 7790): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 1343): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7790): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 1343): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/accuweather( 7790): [KK AccuPhone]>>> DBH:3354 [0:0] gADWI : count = 0
,D/daemonapp( 1343): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7790): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,D/accuweather( 7790): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7814): MountEmulatedStorage()
E/Zygote  ( 7814): v2
I/libpersona( 7814): KNOX_SDCARD checking this for 1000
I/libpersona( 7814): KNOX_SDCARD not a persona
,I/ActivityManager(  908): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=7814 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  908): Killing 6383:com.sec.android.app.music:service/u0a43 (adj 15): bgCount ##41
,I/SELinux ( 7814): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7814): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7814): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7814): TimaSignature is unavailable
,D/ActivityThread( 7814): Added TimaKeyStore provider
,D/ResourcesManager( 7814): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager( 7814): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/libprocessgroup(  908): failed to open /acct/uid_10043/pid_6383/cgroup.procs: No such file or directory
,I/KnoxUsageLogPro( 7814): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7814): premStatus:2
,I/KnoxUsageLogPro( 7814): isEulaShown : false
,I/KnoxUsageLogPro( 7814): KnoxUsageReceiver onReceive : not Processible, just return
,E/SMD     (  292): DCD ON
,E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7829): MountEmulatedStorage()
E/Zygote  ( 7829): v2
I/libpersona( 7829): KNOX_SDCARD checking this for 10087
I/libpersona( 7829): KNOX_SDCARD not a persona
,I/ActivityManager(  908): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7829 uid=10087 gids={50087, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  908): Killing 6814:com.google.android.gms:car/u0a11 (adj 15): bgCount ##41
,I/SELinux ( 7829): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7829): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7829): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7829): TimaSignature is unavailable
,D/ActivityThread( 7829): Added TimaKeyStore provider
,W/libprocessgroup(  908): failed to open /acct/uid_10011/pid_6814/cgroup.procs: No such file or directory
,D/ResourcesManager( 7829): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,I/ActivityManager(  908): Killing 7022:com.google.android.partnersetup/u0a14 (adj 15): bgCount ##41
,D/Headlines( 5443): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5443): getCountryCode(): countryCode = PL
,D/Headlines( 5443): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5443): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5443): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5443): queryCategory.  mRequest is not initialized.
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
,D/HeadlinesCardManager( 5443): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5443): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5443): requestUpdateNewsWelcomeCard !!! no welcome card
,E/Zygote  ( 7855): MountEmulatedStorage()
E/Zygote  ( 7855): v2
I/libpersona( 7855): KNOX_SDCARD checking this for 10127
I/libpersona( 7855): KNOX_SDCARD not a persona
,I/ActivityManager(  908): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7855 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7855): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7855): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7855): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7855): TimaSignature is unavailable
,D/ActivityThread( 7855): Added TimaKeyStore provider
,D/ResourcesManager( 7855): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,W/libprocessgroup(  908): failed to open /acct/uid_10014/pid_7022/cgroup.procs: No such file or directory
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7855): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7855): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7855): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7855): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/WebViewFactory( 7855): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager( 7855): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 7855): Loading: webviewchromium
,I/LibraryLoader( 7855): Time to load native libraries: 4 ms (timestamps 5234-5238)
I/LibraryLoader( 7855): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7855): Binding Chromium to main looper Looper (main, tid 1) {13a746}
,I/LibraryLoader( 7855): Expected native library version number "",actual native library version number ""
,I/chromium( 7855): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7855): Initializing chromium process, renderers=0
,W/art     ( 7855): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7855): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7855): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=42 off=46768 len=2953
,I/chromium( 7855): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:43 off:229524 len:643667
,W/AudioManagerAndroid( 7855): Requires BLUETOOTH permission
,I/Adreno-EGL( 7855): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7855): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7855): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7855): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7855): Remote Branch: 
I/Adreno-EGL( 7855): Local Patches: 
I/Adreno-EGL( 7855): Reconstruct Branch: 
,I/NSApplication( 7855): Starting up...
,E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
,W/art     ( 6577): Suspending all threads took: 6.584ms
,E/Zygote  ( 7917): MountEmulatedStorage()
I/libpersona( 7917): KNOX_SDCARD checking this for 10137
E/Zygote  ( 7917): v2
I/libpersona( 7917): KNOX_SDCARD not a persona
,I/ActivityManager(  908): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7917 uid=10137 gids={50137, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
I/ActivityManager(  908): Killing 7040:com.samsung.groupcast/u0a15 (adj 15): bgCount ##41
,I/SELinux ( 7917): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7917): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7917): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7917): TimaSignature is unavailable
,D/ActivityThread( 7917): Added TimaKeyStore provider
,D/ResourcesManager( 7917): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager( 7917): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7917): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7917): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,W/libprocessgroup(  908): failed to open /acct/uid_10015/pid_7040/cgroup.procs: No such file or directory
,D/QuickConnect( 7917): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7917): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 7917): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7933): MountEmulatedStorage()
,E/Zygote  ( 7933): v2
I/libpersona( 7933): KNOX_SDCARD checking this for 10162
I/libpersona( 7933): KNOX_SDCARD not a persona
,I/ActivityManager(  908): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7933 uid=10162 gids={50162, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager(  908): Killing 6469:com.samsung.android.app.galaxyfinder/u0a33 (adj 15): bgCount ##41
,I/SELinux ( 7933): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7933): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7933): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7933): TimaSignature is unavailable
,D/ActivityThread( 7933): Added TimaKeyStore provider
,D/ResourcesManager( 7933): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/libprocessgroup(  908): failed to open /acct/uid_10033/pid_6469/cgroup.procs: No such file or directory
,W/ResourcesManager( 7933): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 7933): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7933): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 7933): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/RCPManagerService(  908): exchangeData() failure , invalid userId
,D/RCPManagerService(  908): exchangeData() failure , invalid userId
,D/RCPManagerService(  908): exchangeData() failure , invalid userId
,E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService(  908): exchangeData() failure , invalid userId
,E/Zygote  ( 7959): MountEmulatedStorage()
,E/Zygote  ( 7959): v2
I/libpersona( 7959): KNOX_SDCARD checking this for 10077
I/libpersona( 7959): KNOX_SDCARD not a persona
,I/ActivityManager(  908): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7959 uid=10077 gids={50077, 9997} abi=armeabi-v7a
,I/SELinux ( 7959): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7959): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7959): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/RCPManagerService(  908): exchangeData() failure , invalid userId
,D/TimaKeyStoreProvider( 7959): TimaSignature is unavailable
,D/ActivityThread( 7959): Added TimaKeyStore provider
,V/BitmapFactory( 7933): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,D/RCPManagerService(  908): exchangeData() failure , invalid userId
D/ResourcesManager( 7959): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,I/ActivityManager(  908): Killing 4871:com.sec.android.app.shealth/u0a34 (adj 15): bgCount ##41
,V/BitmapFactory( 7933): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,D/BadgeProvider( 7959): onCreate
,D/BadgeProvider( 7959): DatabaseHelper
,V/BitmapFactory( 7933): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 7933): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 7933): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 7933): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 7933): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7634): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 7634): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7634): StateMachine : Current State = 1
,V/BitmapFactory( 7933): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 7933): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 7933): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 7933): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 7933): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 7933): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 7933): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 7933): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 7933): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 7933): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 7933): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 7933): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 7933): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 7933): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 7933): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 7933): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 7933): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 7933): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 7933): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 7933): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 7933): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 7933): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 7933): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 7933): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 7933): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 7933): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 7933): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,V/BitmapFactory( 7933): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_line.pkm
,V/BitmapFactory( 7933): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_icon_undo.pkm
,V/BitmapFactory( 7933): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_calendar_1.pkm
,V/BitmapFactory( 7933): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_attach_icon_etc.pkm
,V/BitmapFactory( 7933): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag.pkm
,V/BitmapFactory( 7933): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate.pkm
,V/BitmapFactory( 7933): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_white.pkm
,V/BitmapFactory( 7933): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_off.pkm
,V/BitmapFactory( 7933): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_on.pkm
,V/BitmapFactory( 7933): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_f.pkm
,V/BitmapFactory( 7933): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate_f.pkm
,V/BitmapFactory( 7933): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_f.pkm
,V/BitmapFactory( 7933): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward.pkm
,V/BitmapFactory( 7933): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward_focus.pkm
,V/BitmapFactory( 7933): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_reply_forward.pkm
,V/BitmapFactory( 7933): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply.pkm
,V/BitmapFactory( 7933): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply_focus.pkm
,V/BitmapFactory( 7933): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_vip.pkm
,V/BitmapFactory( 7933): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_high_priority.pkm
,V/BitmapFactory( 7933): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_low_priority.pkm
,V/BitmapFactory( 7933): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_server_draft.pkm
,V/BitmapFactory( 7933): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_client_draft.pkm
,V/BitmapFactory( 7933): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/permission.pkm
,V/BitmapFactory( 7933): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_voicemail.pkm
,V/BitmapFactory( 7933): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sms.pkm
,V/BitmapFactory( 7933): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sign.pkm
,V/BitmapFactory( 7933): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_encryption.pkm
,W/libprocessgroup(  908): failed to open /acct/uid_10034/pid_4871/cgroup.procs: No such file or directory
,I/art     (  908): Explicit concurrent mark sweep GC freed 77303(4MB) AllocSpace objects, 40(640KB) LOS objects, 30% free, 35MB/51MB, paused 1.380ms total 105.481ms
,D/SecurityLogAgent( 7634): StateMachine : Changed Current State = 1
,I/ActivityManager(  908): Killing 5971:com.samsung.android.sdk.samsunglink/u0a41 (adj 15): bgCount ##41
,V/BitmapFactory( 7933): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_open_01_holo_light.pkm
,V/BitmapFactory( 7933): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_close_01_holo_light.pkm
,D/BadgeProvider( 7959): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
,I/dhcpcd  ( 7796): wlan0: acknowledged 192.168.1.136 from 192.168.1.1
,E/Zygote  ( 7981): MountEmulatedStorage()
E/Zygote  ( 7981): v2
I/libpersona( 7981): KNOX_SDCARD checking this for 10177
I/libpersona( 7981): KNOX_SDCARD not a persona
,I/ActivityManager(  908): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=7981 uid=10177 gids={50177, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/dhcpcd  ( 7796): wlan0: leased 192.168.1.136 for 86400 seconds
,E/WifiStateMachine(  908): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  908): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
D/ConnectivityService(  908): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,I/SELinux ( 7981): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
W/libprocessgroup(  908): failed to open /acct/uid_10041/pid_5971/cgroup.procs: No such file or directory
I/SELinux ( 7981): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7981): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/BadgeProvider( 7959): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7959): sendNotify, [notify] : null
D/BadgeProvider( 7959): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7959): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 7959): update, [UpdateCount] : 1
,D/Launcher.Model( 1499): reloadBadges entered.
,D/TimaKeyStoreProvider( 7981): TimaSignature is unavailable
,D/ActivityThread( 7981): Added TimaKeyStore provider
,W/ActivityManager(  908): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/ResourcesManager( 7981): creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,I/ActivityManager(  908): Killing 5947:com.sec.android.gallery3d/u0a47 (adj 15): bgCount ##41
,I/iu.Environment( 2490): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,V/AlarmManager(  908): waitForAlarm result :4
,I/iu.UploadsManager( 2490): num queued entries: 0
,I/iu.UploadsManager( 2490): num updated entries: 0
,I/iu.SyncManager( 2490): NEXT; no task
,I/Hs20UtilService( 1313): Starting #8
,I/Hs20UtilService( 1313): Message received 5007
,D/NearbySettings( 1313): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1313): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1313): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/ConnectivityService(  908): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1313): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1313): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1313): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1313): MountReceiver.mPrefHandler - 7002
,W/libprocessgroup(  908): failed to open /acct/uid_10047/pid_5947/cgroup.procs: No such file or directory
,E/WifiStateMachine(  908): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine(  908): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  908): do suspend true
,D/WifiP2pService(  908): InactiveState{ what=143375 }
D/WifiP2pService(  908): P2pEnabledState{ what=143375 }
,E/WifiStateMachine(  908): WifiStateMachine DHCP successful
D/ConnectivityService(  908): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  908): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  908): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,E/WifiStateMachine(  908): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,D/WifiStateMachine(  908): Not connected state, yet.
E/WifiStateMachine(  908): VerifyingLinkState enter
,D/StatusBar.NetworkController( 1183): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/WifiStateMachine(  908): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
,D/WifiStateMachine(  908): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine(  908): false / true / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL(  908): callSECApiInt - ID [210]
,E/WifiStateMachine(  908): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
,E/ConnectivityService(  908): updateNetworkInfo()
,D/ConnectivityService(  908): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/ConnectivityService(  908): Adding iface wlan0 to network 503
,I/CLocInfoService(  908): External Intent Received android.net.wifi.STATE_CHANGE
,D/WifiWatchdogStateMachine(  908): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger(  908): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/WifiWatchdogStateMachine.DnsResolver(  908): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.SingDnsChecker(  908): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver(  908): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/StatusBar.NetworkController( 1183): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/Hs20UtilService( 1313): Starting #9
,E/WifiStateMachine(  908): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
D/WifiStateMachine(  908): Now, connected state.
E/WifiStateMachine(  908): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/Hs20UtilService( 1313): Message received 5007
,D/NearbySettings( 1313): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
E/WifiStateMachine(  908): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,I/WifiTrafficPoller(  908): evaluateTrafficStatsPolling
,I/CLocInfoService(  908): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1183): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/WifiTrafficPoller(  908): evaluateTrafficStatsPolling
,I/WifiTrafficPoller(  908): mBoosterFLAG : 0
I/WifiTrafficPoller(  908): current booster mode : FullMode
D/WifiNative-HAL(  908): callSECApiVoid - ID [212]
,I/CLocInfoService(  908): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1183): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
I/NearbySettings( 1313): MountReceiver.onReceive - Keep current state
,E/WifiStateMachine(  908): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/StatusBar.NetworkController( 1183): applyOpen
,D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1183): applyOpen
,D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1183): applyOpen
D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1183): applyOpen
,D/ConnectivityService(  908): Adding Route [fe80::/64 -> :: wlan0] to network 503
,E/WifiStateMachine(  908): ConnectedState Enter  mScreenOn=false scanperiod=20000
D/ConnectivityService(  908): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,I/WifiStateMachine(  908): REQUEST_POWER_SAVE_ON
,D/ConnectivityService(  908): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,E/ConnectivityService(  908): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  908): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  908): updateSourceRoutes : add src route for:192.168.1.136
,V/        (  285): QcRouteController
,V/        (  285): QcRouteController
,I/Hs20UtilService( 1313): Starting #10
,I/Hs20UtilService( 1313): Message received 5007
,D/NearbySettings( 1313): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1313): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1313): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1313): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1313): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1313): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1313): MountReceiver.mPrefHandler - 7002
,I/Hs20UtilService( 1313): Starting #11
,V/        (  285): QcRouteController
,I/Hs20UtilService( 1313): Message received 5007
,D/NearbySettings( 1313): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1313): MountReceiver.onReceive - Keep current state
,I/WifiStateMachine(  908): callSECApi what=220
D/WifiStateMachine(  908): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,V/        (  285): QcRouteController
,V/        (  285): QcRouteController
,V/        (  285): QcRouteController
,V/        (  285): QcRouteController
,I/SurfaceFlinger(  257): id=16 createSurf (1x1),1 flag=4, Toast
,D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1183): value : false
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
,D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
,V/        (  285): QcRouteController
,D/ConnectivityService(  908): Setting Dns servers for network 503 to [/192.168.1.1]
,D/PowerManagerService(  908): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=908
,D/Nat464Xlat(  908): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  908): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService(  908): updateNetworkInfo()
D/ConnectivityService(  908): calling update connectivity
E/ConnectivityService(  908): updateNetworkInfo()
D/ConnectivityService(  908): ignoring duplicate network state non-change
D/ConnectivityService(  908): ignoring duplicate network state non-change
D/ConnectivityService(  908): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  908): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  908): calling update connectivity
D/ConnectivityService(  908): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  908):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  908):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  908):   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  908):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  908): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  908): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  908): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  908): Validated
,D/ConnectivityService(  908): currentScore = 0, newScore = 60
D/ConnectivityService(  908):    accepting network in place of null
D/ConnectivityService(  908): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory( 1477): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/CSLegacyTypeTracker(  908): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  908): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService(  908): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  908): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/SmartBondingService(  908): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/LockPatternUtilsCache( 1183): value : false
D/SmartBondingService(  908): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  908): getSBEnabled() enabled =false
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/SmartBondingService(  908): getSBEnabled() enabled =false
D/LockPatternUtilsCache( 1183): value : false
D/SmartBondingService(  908): getSBEnabled() enabled =false
V/NetworkStats(  908): updateIfacesLocked()
V/NetworkStats(  908): performPollLocked(flags=0x1)
D/NtpTrustedTime(  908): currentTimeMillis() cache hit
D/ConnectivityService(  908): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
D/SmartBondingService(  908): getNetworkEnabled : wifi : true mobile : true
D/NetworkStatsFactory(  908): UpdateStatsForKnox
D/ConnectivityService(  908): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/NtpTrustedTime(  908): currentTimeMillis() cache hit
D/NtpTrustedTime(  908): currentTimeMillis() cache hit
D/NtpTrustedTime(  908): currentTimeMillis() cache hit
D/NtpTrustedTime(  908): currentTimeMillis() cache hit
V/NetworkStats(  908): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/ConnectivityService(  908): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  908): calling update connectivity
D/ConnectivityService(  908):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  908):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  908): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  908):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  908): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  908): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  908): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  908):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityManager.CallbackHandler( 2490): CM callback handler got msg 524290
D/ConnectivityService(  908):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  908):   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  908): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService(  908): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  908): calling update connectivity
D/ConnectivityService(  908):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  908):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  908): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  908):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  908): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  908): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 2490): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler( 1183): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler( 1183): CM callback handler got msg 524290
V/NetworkStats(  908): performPollLocked() took 7ms
D/NtpTrustedTime(  908): currentTimeMillis() cache hit
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/NtpTrustedTime(  908): currentTimeMillis() cache hit
D/NtpTrustedTime(  908): currentTimeMillis() cache hit
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1183): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1183): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1183): updateDataNetType()
D/StatusBar.NetworkController( 1183): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1183): updateLTEICONDataNetType:0
D/StatusBar.NetworkController( 1183): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1183): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1183): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1183): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1183): applyOpen
D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1183): applyOpen
D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1183): applyOpen
D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1183): applyOpen
D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1183): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1183): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1183): updateDataNetType()
D/StatusBar.NetworkController( 1183): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1183): updateLTEICONDataNetType:0
D/StatusBar.NetworkController( 1183): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1183): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1183): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1183): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
,D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
,D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
,D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
,D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
,D/ConnectivityService(  908): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/accuweather( 2194): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/SmartBondingService(  908): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  908): SmartBondingReceiver: wifi is connected
,D/Tethering(  908): MasterInitialState.processMessage what=3
,D/SmartBondingService(  908): SmartBondingReceiver: wifi ap is not changed
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  908): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  908): getSBEnabled() enabled =false
D/SmartBondingService(  908): getSBEnabled() enabled =false
,D/SmartBondingService(  908): getSBEnabled() enabled =false
I/CLocInfoService(  908): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  908): CLocinfo wifi true 
D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  908): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 2225): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.ai.onReceive:-1 
,W/ContextImpl( 2225): Implicit intents with startService are not safe: Intent { act=com.samsung.SMT.UpdateManager.UPDATE_DATA } android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  908): getNetworkEnabled : wifi : true mobile : true
,I/DBG_DM  ( 3732): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/DBG_DM  ( 3732): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,I/NetworkMonitor( 6284): type=WIFI subType= reason=null isConnected=true
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  908): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  908): mCursor = null
,I/PCWCLIENTTRACE_PushUtil( 7056): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7056): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7056): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7056): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7716): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7716): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/FOTA_Client( 7736): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7736): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 7736): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/KLMS-2.4.503: ( 7757): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7757): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1454460323869
,I/KLMS-2.4.503: ( 7757): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7757): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.503: ( 7757): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.503: ( 7757): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.4.503: ( 7757): StateImplV2(): networkChangeListener().END
,I/SO_AGENT( 7772): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/jxcore-log( 7549): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 7549): 
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 5212): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      ( 7096): [OR] onReceive log=[SA = 2.1.0172 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOE5 PSS = 5.219788042639568  ]
,I/SA      ( 7096): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 7096): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 7096): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 7096): [OR] == isSIMCardReady false ==
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SA      ( 7096): [SCU] == networkStateCheck == true
,I/SA      ( 7096): [DM] getCountryCodeFromCSC : PL
I/SA      ( 7096): isChinaCountryCode : false
I/SA      ( 7096): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 7096): [OR] == networkStateCheck true ==
,I/SA      ( 7096): [OR] GetMyCountryZoneTask
,I/SA      ( 7096): [OR] onReceive END
,I/SA      ( 7096): [SRS] prepareGetMyCountryZone
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 7096): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 7096): [SSP] query invoked
,D/accuweather( 7790): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7790): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,I/KnoxUsageLogPro( 7814): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro( 7814): premStatus:2
,I/SA      ( 7096): [TPMU] GetMccFromDB : null
,I/SA      ( 7096): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 7096): [TPM] isNoProxy(default) : true
,I/KnoxUsageLogPro( 7814): isEulaShown : false
I/KnoxUsageLogPro( 7814): KnoxUsageReceiver onReceive : not Processible, just return
,E/File    ( 7096): fail readDirectory() errno=2
,D/Headlines( 5443): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5443): getCountryCode(): countryCode = PL
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Headlines( 5443): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5443): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5443): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5443): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5443): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
,D/HeadlinesCardManager( 5443): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5443): requestUpdateNewsWelcomeCard !!! no welcome card
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/QuickConnect( 7917): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7917): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 7917): PeriphStartReceiver.onReceive - no need to start
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  908): exchangeData() failure , invalid userId
,D/RCPManagerService(  908): exchangeData() failure , invalid userId
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7634): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 7634): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7634): StateMachine : Current State = 1
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SecurityLogAgent( 7634): StateMachine : Changed Current State = 1
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/iu.Environment( 2490): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 2490): num queued entries: 0
,I/iu.UploadsManager( 2490): num updated entries: 0
,I/iu.SyncManager( 2490): NEXT; no task
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WaitQueueForNetworkActivate( 7408): notifyNetworkActivated
,W/ContextImpl( 7408): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager(  908): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/ConnectivityService(  908): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/WifiStateMachine(  908): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  908): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=true
D/ConnectivityService(  908): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/ConnectivityService(  908): identical MTU - not setting
D/ConnectivityService(  908): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  908): updateSourceRoutes : add src route for:fe80::ee1f:72ff:fe63:1186
V/        (  285): QcRouteController
E/WifiStateMachine(  908): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/SmartBondingService(  908): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  908): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  908): getSBEnabled() enabled =false
D/SmartBondingService(  908): getSBEnabled() enabled =false
D/SmartBondingService(  908): getSBEnabled() enabled =false
,V/        (  285): QcRouteController
,W/NetworkManagementService(  908): route cmd failed: 
W/NetworkManagementService(  908): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '72 route replace src v6 wlan0 fe80::ee1f:72ff:fe63:1186 2 ::' failed with '400 72 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService(  908): '
W/NetworkManagementService(  908): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:438)
W/NetworkManagementService(  908): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:371)
W/NetworkManagementService(  908): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:336)
W/NetworkManagementService(  908): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:321)
W/NetworkManagementService(  908): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService(  908): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5478)
W/NetworkManagementService(  908): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5305)
W/NetworkManagementService(  908): 	at com.android.server.ConnectivityService.access$1900(ConnectivityService.java:230)
W/NetworkManagementService(  908): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2324)
W/NetworkManagementService(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  908): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Nat464Xlat(  908): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  908): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  908): calling update connectivity
D/ConnectivityService(  908):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  908):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  908): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  908):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1183): CM callback handler got msg 524295
,D/ConnectivityService(  908): sending notification IP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  908): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService(  908): calling update connectivity
D/ConnectivityManager.CallbackHandler( 2490): CM callback handler got msg 524295
D/ConnectivityService(  908):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  908):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  908): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  908):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1183): CM callback handler got msg 524295
,D/ConnectivityService(  908): sending notification IP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 2490): CM callback handler got msg 524295
,D/hcjo    ( 7408): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 7408): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 7408): exit::IDLE
D/InitializeManagerStateMachine( 7408): entry::NETWORK_CHECK
D/ConnectivityService(  908): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7408): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7408): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7408): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7408): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7408): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7408): entry::SUCCESS
D/hcjo    ( 7408): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 7408): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 7408): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7408): exit::SUCCESS
D/InitializeManagerStateMachine( 7408): entry::IDLE
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  292): DCD ON
,I/SA      ( 7096): [RC New] Execute method=[GET] start
,I/SA      ( 7096): [RC New] Security=[true]
,I/System.out( 7096): Thread-1105(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 7096): Thread-1105(ApacheHTTPLog):isShipBuild true
,I/System.out( 7096): Thread-1105(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/jxcore-log( 7549): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 7549): 
,I/jxcore-log( 7549): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 7549): 
,I/jxcore-log( 7549): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
I/jxcore-log( 7549): 
,I/jxcore-log( 7549): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 7549): 
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  908): stay LED for fully charged
D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  908):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3227): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3227): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/dhcpcd  ( 7796): wlan0: sending IPv6 Router Solicitation
,I/WifiStateMachine(  908): REQUEST_POWER_SAVE_ON
,E/WifiStateMachine(  908): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/SA      ( 7096): [RC New] [v2liruge] api execute + 2036
,I/SA      ( 7096): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
I/System.out( 7096): AsyncTask #1 calls detatch()
,I/SA      ( 7096): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 7096): [OCP] update openData : PL
,I/SA      ( 7096): [TPMU] getNetworkMcc : 
,I/SA      ( 7096): [SCU] saveMccToPreferece Start
I/SA      ( 7096): [SCU] RegionMCC : 260
I/SA      ( 7096): [SSP] query invoked
,I/SA      ( 7096): [TPMU] GetMccFromDB : null
I/SA      ( 7096): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 7096): [SCU] saveMccToPreferece End
,I/SA      ( 7096): [RC New] executeRequest [v2liruge] end. 2084
,I/SA      ( 7096): [RC New] Execute end
I/SA      ( 7096): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 7096): [OR] GetMyCountryZoneTask Success
,I/SurfaceFlinger(  257): id=16 Removed Toast (8/9)
,I/SurfaceFlinger(  257): id=16 Removed Toast (-2/9)
,D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1183): value : false
,D/PowerManagerService(  908): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 908) eventTime = 219826
,D/PowerManagerService(  908): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=908 (0x0)
D/PowerManagerService(  908): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=908, ws=WorkSource{10058}) (elapsedTime=3465)
,D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1183): value : false
,I/GAV4    ( 7855): Thread[GAThread,5,main]: No campaign data found.
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  292): DCD ON
,I/PCWCLIENTTRACE_SYSTEMReceiver( 7056): mConnectivityHandler : connected
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/PCWCLIENTTRACE_AccountUtil( 7056): [hasSamungAccount] - No Samsung Account
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 7056): [GetString-S]
,I/ReactiveServiceManager( 7056): Supported : 1
,D/QSEECOMAPI: (  908): QSEECom_get_handle sb_length = 0x2040
D/QSEECOMAPI: (  908): App is not loaded in QSEE
,D/QSEECOMAPI: (  908): Loaded image: APP id = 3
,D/QSEECOMAPI: (  908): QSEECom_dealloc_memory 
,D/QSEECOMAPI: (  908): QSEECom_shutdown_app, app_id = 3
E/terrier (  908): handleString: Failed to handle string(-4)
E/terrier (  908): Java_com_android_server_ReactiveService_GetString: error code = [-4]
,D/PCWCLIENTTRACE_SecurePreferencesJNI( 7056): getString is null
I/PCWCLIENTTRACE_SecurePreferencesJNI( 7056): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 7056): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7056): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 7056): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 7056): [ensureRegistration] - No Samsung account
,D/SSRM:m  (  908): SIOP:: AP = 330, PST = 288, CUR = 450
,I/jxcore-log( 7549): Test app app.js loaded
I/jxcore-log( 7549): 
,I/chromium( 7549): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7549): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7549): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7549): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7549): 	Bluetooth MAC address: null, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7549): 	Discovery mode: BLE, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7549): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7549): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7549): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7549): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7549): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c756ae0 added. We now have 1 listener(s)
,I/jxcore-log( 7549): BLE advertisement is supported
I/jxcore-log( 7549): 
,I/dhcpcd  ( 7796): wlan0: sending IPv6 Router Solicitation
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD ON
,E/Watchdog(  908): !@Sync 7
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD ON
,I/dhcpcd  ( 7796): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  ( 7796): wlan0: no IPv6 Routers available
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/PreloadUpdateManagerStateMachine( 7408): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7408): exit::IDLE
D/PreloadUpdateManagerStateMachine( 7408): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7408): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 7408): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 7408): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7408): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 7408): entry::IDLE
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 1
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  908):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3227): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3227): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  292): DCD ON
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:m  (  908): SIOP:: AP = 300, PST = 288, CUR = 450
,E/SMD     (  292): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 2
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  908):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3227): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3227): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 290, PST = 288, CUR = 450
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  908):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
,D/BatteryService(  908): stay LED for fully charged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3227): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3227): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService(  908): [PWL] Off : 180s ago
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/SSRM:m  (  908): SIOP:: AP = 290, PST = 288, CUR = 450
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 3
,V/AlarmManager(  908): waitForAlarm result :8
,E/SMD     (  292): DCD ON
,E/Watchdog(  908): !@Sync 8
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 280, PST = 287, CUR = 450
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD ON
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  908):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3227): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3227): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  292): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/SSRM:m  (  908): SIOP:: AP = 270, PST = 285, CUR = 450
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  908):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3227): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3227): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 270, PST = 285, CUR = 450
,E/SMD     (  292): DCD ON
,E/Watchdog(  908): !@Sync 9
,E/SMD     (  292): DCD ON
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  908):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3227): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3227): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  292): DCD ON
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 284, CUR = 450
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/PowerManagerService(  908): [PWL] Off : 225s ago
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  292): DCD ON
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  908):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3227): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3227): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 284, CUR = 450
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  908):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3227): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3227): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  292): DCD ON
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService(  908): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  908): TimaServiceHandler.handleMessage what =1
,D/TimaService(  908): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize(  908): initializing...
,I/TLC_TIMA_PKM_initialize(  908): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  908): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  908): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  908): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  908): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  908): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  908): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  908): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  908): App is not loaded in QSEE
,D/QSEECOMAPI: (  908): Loaded image: APP id = 3
,I/TZ: qc_tlc_communication(  908): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  908): Trustlet response is completed
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 281, CUR = 450
,E/SMD     (  292): DCD ON
,E/Watchdog(  908): !@Sync 10
,I/TLC_TIMA_PKM_measure_kernel(  908): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  908): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  908): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  908): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  292): DCD ON
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  908):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3227): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3227): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,I/Atfwd_Sendcmd(  329): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  329): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 274, CUR = 450
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  292): DCD ON
,V/AlarmManager(  908): waitForAlarm result :4
,E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0,
,E/Zygote  ( 8103): MountEmulatedStorage()
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,E/Zygote  ( 8103): v2
,I/libpersona( 8103): KNOX_SDCARD checking this for 10080
I/libpersona( 8103): KNOX_SDCARD not a persona
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  908): stay LED for fully charged
I/ActivityManager(  908): Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=8103 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  908):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
I/MotionRecognitionService(  908): setPowerConnected  = true
,I/SELinux ( 8103): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8103): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8103): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleTimeUpdate
D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3227): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3227): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardEffectViewController( 1183): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1183): *** don't update sliding image ***
,D/TimaKeyStoreProvider( 8103): TimaSignature is unavailable
,D/ActivityThread( 8103): Added TimaKeyStore provider
,D/ResourcesManager( 8103): creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,D/DateView( 1183): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1183): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/ActivityManager(  908): Killing 5652:com.android.mms/u0a49 (adj 15): bgCount ##41
,D/CountryDetector(  908): No listener is left
,W/libprocessgroup(  908): failed to open /acct/uid_10049/pid_5652/cgroup.procs: No such file or directory
,D/SSRM:m  (  908): SIOP:: AP = 270, PST = 271, CUR = 450
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  908):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3227): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3227): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 1
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 268, CUR = 450
,E/SMD     (  292): DCD ON
,E/Watchdog(  908): !@Sync 11
,E/SMD     (  292): DCD ON
,I/PowerManagerService(  908): [PWL] Off : 275s ago
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD ON
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 2
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 265, CUR = 450
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 263, CUR = 450
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD ON
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  292): DCD ON
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 262, CUR = 450
,V/AlarmManager(  908): waitForAlarm result :8
,E/SMD     (  292): DCD ON
,E/Watchdog(  908): !@Sync 12
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 261, CUR = 450
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  908):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3227): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3227): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  292): DCD ON
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 261, CUR = 450
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,I/PowerManagerService(  908): [PWL] Off : 330s ago
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 261, CUR = 450
,E/Watchdog(  908): !@Sync 13
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD ON
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 5
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 261, CUR = 450
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  908):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3227): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3227): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 261, CUR = 450
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  908): !@Sync 14
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,I/Atfwd_Sendcmd(  329): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  329): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  908):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3227): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3227): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  908):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3227): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3227): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/PowerManagerService(  908): [PWL] Off : 390s ago
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 1
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  908): !@Sync 15
,E/SMD     (  292): DCD ON
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  908):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3227): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3227): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  292): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD ON
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 2
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  908):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3227): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3227): Disconnected process message: 10
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/bootchecker(  325): bootchecker wake up!!
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  908):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3227): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3227): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  292): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD ON
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  292): DCD ON
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  908): !@Sync 16
,E/SMD     (  292): DCD ON
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  908):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3227): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3227): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  292): DCD ON
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  908):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3227): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3227): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,E/Watchdog(  908): !@Sync 17
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  908):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3227): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3227): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  292): DCD ON
,I/PowerManagerService(  908): [PWL] Off : 455s ago
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD ON
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 5
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  908): !@Sync 18
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  292): DCD ON
,I/Atfwd_Sendcmd(  329): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  329): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  908):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3227): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3227): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,I/Atfwd_Daemon(  329): Stop the daemon....,
,E/Watchdog(  908): !@Sync 19
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  908):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3227): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3227): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  292): DCD ON
,I/PowerManagerService(  908): [PWL] Off : 525s ago
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  292): DCD ON
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  908):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3227): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3227): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,D/TimaService(  908): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  908): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  908): TimaServiceHandler.handleMessage what =1
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  908): !@Sync 20
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,I/TLC_TIMA_PKM_measure_kernel(  908): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  908): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  908): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  908): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  292): DCD ON
,I/ActivityManager(  908): Killing 7118:com.sec.android.app.myfiles/u0a50 (adj 15): bgCount ##41
,W/libprocessgroup(  908): failed to open /acct/uid_10050/pid_7118/cgroup.procs: No such file or directory
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,E/Watchdog(  908): !@Sync 21
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  908):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3227): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3227): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON,
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  908):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3227): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3227): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  292): DCD ON
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  908):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
,D/BatteryService(  908): stay LED for fully charged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3227): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3227): Disconnected process message: 10
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,I/PowerManagerService(  908): [PWL] Off : 600s ago
,E/Watchdog(  908): !@Sync 22
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  292): DCD ON
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  908):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3227): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3227): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  292): DCD ON
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  908):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3227): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3227): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,E/Watchdog(  908): !@Sync 23
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,E/Watchdog(  908): !@Sync 24
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,I/PowerManagerService(  908): [PWL] Off : 680s ago
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,E/Watchdog(  908): !@Sync 25
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  292): DCD ON
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  908):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3227): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3227): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  908):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3227): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3227): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,V/AlarmManager(  908): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1183): handleTimeUpdate
,D/KeyguardEffectViewController( 1183): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1183): *** don't update sliding image ***
,D/LightsService(  908): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,E/LightSensor(  908): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/SensorManager(  908): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,E/Watchdog(  908): !@Sync 26
,D/DateView( 1183): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1183): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  292): DCD ON
,E/LightSensor(  908): RED : 0, GREEN : 0, BLUE : 0, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/LightsService(  908): [SvcLED]  onSensorChanged::light value = 0
,E/LightSensor(  908): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager(  908): unregisterListener ::   
,D/LightsService(  908): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  908):   mReceiver.onReceive : ACTION_BATTERY_CHANGED,
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,E/SMD     (  292): DCD ON
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3227): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3227): Disconnected process message: 10
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  292): DCD ON
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  908):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
,D/BatteryService(  908): stay LED for fully charged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3227): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3227): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  908):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
,D/BatteryService(  908): stay LED for fully charged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3227): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3227): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,E/Watchdog(  908): !@Sync 27
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  292): DCD ON
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  908):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3227): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3227): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  292): DCD ON
,I/PowerManagerService(  908): [PWL] Off : 765s ago
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  908):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3227): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3227): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,V/AlarmManager(  908): waitForAlarm result :8
,E/Watchdog(  908): !@Sync 28
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  292): DCD ON
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  908):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3227): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3227): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  292): DCD ON
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  908):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3227): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3227): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,E/Watchdog(  908): !@Sync 29
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  292): DCD ON
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  908):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3227): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3227): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  292): DCD ON
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  908):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3227): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3227): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,D/TimaService(  908): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  908): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  908): TimaServiceHandler.handleMessage what =1
,E/Watchdog(  908): !@Sync 30
,E/SMD     (  292): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  908): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  908): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  908): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  908): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  292): DCD ON
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  908):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3227): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3227): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  292): DCD ON
,I/PowerManagerService(  908): [PWL] Off : 855s ago
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  908):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3227): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3227): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  292): DCD ON
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  908):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3227): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3227): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  292): DCD ON
,E/Watchdog(  908): !@Sync 31
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  292): DCD ON
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  908): stay LED for fully charged
,D/MotionRecognitionService(  908):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3227): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3227): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  292): DCD ON
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  908):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3227): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3227): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  292): DCD ON
,E/Watchdog(  908): !@Sync 32
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  292): DCD ON
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  908):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
,D/BatteryService(  908): stay LED for fully charged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3227): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3227): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  292): DCD ON
,E/Watchdog(  908): !@Sync 33
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  908):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3227): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3227): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  292): DCD ON
,I/PowerManagerService(  908): [PWL] Off : 950s ago
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,E/Watchdog(  908): !@Sync 34
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  292): DCD ON
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  908):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
,D/BatteryService(  908): stay LED for fully charged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3227): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3227): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  908):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
,D/BatteryService(  908): stay LED for fully charged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3227): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3227): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  292): DCD ON
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  908):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3227): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 3227): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  292): DCD ON
,E/Watchdog(  908): !@Sync 35
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  292): DCD ON
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  908):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
,D/BatteryService(  908): stay LED for fully charged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3227): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3227): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  292): DCD ON
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  908):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3227): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3227): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  292): DCD ON
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  908):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
,D/BatteryService(  908): stay LED for fully charged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3227): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3227): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  292): DCD ON
,E/Watchdog(  908): !@Sync 36
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  292): DCD ON
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  908):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3227): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3227): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,V/AlarmManager(  908): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1183): handleTimeUpdate
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  908): stay LED for fully charged
,D/KeyguardEffectViewController( 1183): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1183): *** don't update sliding image ***
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/HeadsetService( 3227): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3227): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/MotionRecognitionService(  908):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
I/MotionRecognitionService(  908): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/DateView( 1183): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1183): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,I/PowerManagerService(  908): [PWL] Off : 1050s ago
,E/Watchdog(  908): !@Sync 37
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  292): DCD ON
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  908):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3227): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3227): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  908):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3227): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3227): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  292): DCD ON
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  908):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3227): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3227): Disconnected process message: 10
,E/SMD     (  292): DCD ON
,V/AlarmManager(  908): waitForAlarm result :8
,E/Watchdog(  908): !@Sync 38
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  292): DCD ON
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  908):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3227): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3227): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  908):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3227): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3227): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  292): DCD ON
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  908):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3227): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3227): Disconnected process message: 10
,E/SMD     (  292): DCD ON
,E/Watchdog(  908): !@Sync 39
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  292): DCD ON
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  908):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3227): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3227): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  908):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3227): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3227): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  292): DCD ON
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  908):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3227): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3227): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  292): DCD ON
,D/TimaService(  908): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  908): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  908): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService(  908): User[0] Flushing usage stats to disk
,I/ApplicationUsage(  908): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage(  908): Updating Usage Statistics in DB @ 1454461318566
,I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
,W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
,W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
,W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
,W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
,W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
,W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
,W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
,W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
,W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
,W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
,W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
,W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
,W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
,W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
,W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
,W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
,W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
,W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
,W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
,W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
,W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
,W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
,W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
,W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
,W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
,W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
,W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
,W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  908): ::getAppControlDB: Exception to create DB
W/System.err(  908): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  908): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  908): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsage(  908): Done Updating Usage Statistics in DB @ 1454461318791
,E/Watchdog(  908): !@Sync 40
,E/SMD     (  292): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  908): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  908): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  908): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  908): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,I/PowerManagerService(  908): [PWL] Off : 1155s ago
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  908):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3227): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3227): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,E/Watchdog(  908): !@Sync 41
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  292): DCD ON
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  908):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
,D/BatteryService(  908): stay LED for fully charged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3227): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3227): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  908):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,E/SMD     (  292): DCD ON
,V/HeadsetService( 3227): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3227): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  292): DCD ON
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  908):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3227): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3227): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  292): DCD ON
,E/Watchdog(  908): !@Sync 42
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  908):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
,D/BatteryService(  908): stay LED for fully charged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3227): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3227): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  292): DCD ON
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  908):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3227): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3227): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  292): DCD ON
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  908):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3227): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3227): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  292): DCD ON
,E/Watchdog(  908): !@Sync 43
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  908):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3227): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3227): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,E/Watchdog(  908): !@Sync 44
,E/SMD     (  292): DCD ON
,I/PowerManagerService(  908): [PWL] Off : 1265s ago
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  292): DCD ON
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  908):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
,D/BatteryService(  908): stay LED for fully charged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3227): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3227): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,E/Watchdog(  908): !@Sync 45
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  292): DCD ON
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  908):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  908): stay LED for fully charged
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3227): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3227): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  292): DCD ON
,E/Watchdog(  908): !@Sync 46
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,D/ConnectivityService(  908): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  292): DCD ON
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  908):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/BatteryService(  908): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3227): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3227): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  292): DCD ON
,E/SMD     (  292): DCD ON
,D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  292): DCD ON
,D/BatteryService(  908): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  908): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  908): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  908):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  908): Plugged
,D/BatteryService(  908): stay LED for fully charged
,I/MotionRecognitionService(  908): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3227): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3227): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  292): DCD ON
,E/Watchdog(  908): !@Sync 47
,TIME-OUT KILL (timeout was 1200000ms),E/SMD     (  292): DCD ON
E/SMD     (  292): DCD ON
D/SSRM:m  (  908): SIOP:: AP = 260, PST = 260, CUR = 450
D/AndroidRuntime( 8213): 
D/AndroidRuntime( 8213): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8213): CheckJNI is OFF
D/AndroidRuntime( 8213): setted country_code = Poland
D/AndroidRuntime( 8213): setted countryiso_code = PL
D/AndroidRuntime( 8213): setted sales_code = XEO
D/AndroidRuntime( 8213): readGMSProperty: start
D/AndroidRuntime( 8213): readGMSProperty: already setted!!
D/AndroidRuntime( 8213): readGMSProperty: end
D/AndroidRuntime( 8213): addProductProperty: start
E/AffinityControl( 8213): AffinityControl: registerfunction enter
D/AndroidRuntime( 8213): Calling main entry com.android.commands.pm.Pm
D/PackageManager(  908): START PACKAGE DELETE: observer{569191885}
D/PackageManager(  908): pkg{<packageName>}
D/PackageManager(  908): user{0}
D/PackageManager(  908): caller{2000}
D/PackageManager(  908): flags{3}
D/PersonaManagerService(  908): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  908): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  908): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  908): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  908): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  908): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService(  908): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  908): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  908): getApplicationUninstallationEnabled
D/ApplicationPolicy(  908): getApplicationUninstallationEnabled :  enabled true
D/PackageManager(  908): !@killApplicatoin: 10191, uninstall pkg
I/ActivityManager(  908): Force stopping com.test.thalitest appid=10191 user=-1: uninstall pkg
I/ActivityManager(  908): Killing 7549:com.test.thalitest/u0a191 (adj 0): stop com.test.thalitest
I/ActivityManager(  908):   Force finishing activity ActivityRecord{10f80644 u0 com.test.thalitest/.MainActivity t11}
W/ActivityManager(  908): mDVFSHelper.acquire()
D/WifiService(  908): Client connection lost with reason: 4
I/WindowState(  908): WIN DEATH: Window{25d1156a u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger(  257): id=15 Removed com.test.thalitest/com.test.thalitest.MainActivity (5/8)
I/SurfaceFlinger(  257): id=15 Removed com.test.thalitest/com.test.thalitest.MainActivity (-2/8)
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
I/SurfaceFlinger(  257): id=15 Removed com.test.thalitest/com.test.thalitest.MainActivity (-2/8)
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
I/SQLiteSecureOpenHelper( 3513): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3513): getDatabaseLocked(b,b,pwd)...
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
I/ActivityManager(  908): Force stopping com.test.thalitest appid=10191 user=0: pkg removed
I/ActivityManager(  908):   Force finishing activity ActivityRecord{10f80644 u0 com.test.thalitest/.MainActivity t11 f}
W/ActivityManager(  908): Duplicate finish request for ActivityRecord{10f80644 u0 com.test.thalitest/.MainActivity t11 f}
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
I/art     ( 6361): Explicit concurrent mark sweep GC freed 28655(1590KB) AllocSpace objects, 8(128KB) LOS objects, 40% free, 14MB/24MB, paused 412us total 30.068ms
I/DBG_DM  ( 3732): [com.wssyncmldm.ui.XUIInstallConfirmActivity(477/onResume)] 
I/art     ( 1716): Explicit concurrent mark sweep GC freed 28730(1800KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 16MB/21MB, paused 485us total 48.817ms
D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/FocusedStackFrame(  908): Set to : 0
I/DBG_DM  ( 3732): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 48
I/art     ( 2490): Explicit concurrent mark sweep GC freed 37407(2MB) AllocSpace objects, 7(112KB) LOS objects, 24% free, 21MB/28MB, paused 678us total 58.741ms
D/ResourcesManager(  908): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
I/DBG_DM  ( 3732): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
D/ResourcesManager(  908): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
I/DBG_DM  ( 3732): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
I/DBG_DM  ( 3732): [com.wssyncmldm.ui.XUIInstallConfirmActivity(487/onResume)] Postpone Count : 48
I/InputReader(  908): Reconfiguring input devices.  changes=0x00000010
I/DBG_DM  ( 3732): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
D/ResourcesManager(  908): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
D/ResourcesManager(  908): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
E/SamsungIME( 1792): mOCRHelper is null
W/GeofencerStateMachine( 2251): Ignoring removeGeofence because network location is disabled.
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
I/DBG_DM  ( 3732): [com.wssyncmldm.ui.llIlIllIIIlIIlllIlII(325/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/KLMS-2.4.503: ( 7757): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/DBG_DM  ( 3732): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
I/KLMS-2.4.503: ( 7757): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1454461535482
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
I/KLMS-2.4.503: ( 7757): MainReciver(): PACKAGE_REMOVED
D/SecContentProvider2(  908): uri = 14 selection = getSealedState
D/SecContentProvider2(  908): mCursor = null
D/SecContentProvider2(  908): KnoxCustomManagerService offline: service is not available
I/KLMS-2.4.503: ( 7757): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
D/ApplicationPolicy(  908): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy(  908): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
D/ResourcesManager(  908): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
D/ResourcesManager(  908): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
I/DBG_DM  ( 3732): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 48
I/DBG_DM  ( 3732): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
I/DBG_DM  ( 3732): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
I/DBG_DM  ( 3732): [com.wssyncmldm.ui.XUIInstallConfirmActivity(573/llIIIIlllllIIllIIllI)] Check Force Install : false
I/DBG_DM  ( 3732): [IIlllIlIIlIllIlllIll(376/llIIllllIIlllIIIIlll)] 
I/DBG_DM  ( 3732): [IIlllIlIIlIllIlllIll(397/llIIllllIIlllIIIIlll)] InternalEncrypted : [false]
D/ActivityManager(  908): post active user change for 0
D/KnoxTimeoutHandler(  908): postActiveUserChange for user 0
I/DBG_DM  ( 3732): [com.wssyncmldm.ui.XUIInstallConfirmActivity(469/onPause)] 
D/SecContentProvider2(  908): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  908): mCursor = null
I/SurfaceFlinger(  257): id=17 createSurf (1080x1920),2 flag=404, com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/StatusBarManagerService(  908): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1183): value : false
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/StatusBarManagerService(  908): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/ResourcesManager(  908): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/ResourcesManager(  908): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
D/ResourcesManager(  908): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
D/ResourcesManager(  908): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
D/RegisteredServicesCache( 1471): empty dynamic service
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/ResourcesManager(  908): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/ResourcesManager(  908): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/Books/Books.apk
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/Drive/Drive.apk
I/Timeline( 3732): Timeline: Activity_idle id: android.os.BinderProxy@345bcec time:1428815
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
W/ActivityManager(  908): mDVFSHelper.release()
I/Timeline(  908): Timeline: Activity_windows_visible id: ActivityRecord{39db2983 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t9} time:1428827
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
D/SurfaceWidgetView( 1499): destroyHardwareResources():238623797
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
V/WindowOrientationListener(  908): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  908): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  908): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  908): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  908): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
I/SurfaceFlinger(  257): id=17 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (4/8)
I/SurfaceFlinger(  257): id=17 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (-2/8)
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
D/Launcher( 1499): onRestart, Launcher: 184214290
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/Videos/Videos.apk
E/Zygote  ( 8245): MountEmulatedStorage()
E/Zygote  ( 8245): v2
I/libpersona( 8245): KNOX_SDCARD checking this for 10103
I/libpersona( 8245): KNOX_SDCARD not a persona
I/ActivityManager(  908): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=8245 uid=10103 gids={50103, 9997, 3003} abi=armeabi-v7a
D/Launcher( 1499): onStart, Launcher: 184214290
D/Launcher.HomeView( 1499): onStart
D/Launcher.HomeView( 1499): onStop
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
I/SELinux ( 8245): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2194): [237392/6] Surface widget visibility changed visibility = true on instance = 1
D/RCPManagerService(  908): PackageReceiver onReceive()
D/SurfaceWidget.Renderer( 2194): [237392/6] SurfaceWidget drawing first frame
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
I/HarmonyEASService(  908): onReceive : android.intent.action.PACKAGE_REMOVED for 0
I/SELinux ( 8245): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8245): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/KnoxMUMContainerPolicy(  908): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  908): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  908): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  908): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  908): uID is 10191
V/EnterpriseBillingPolicy(  908): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  908): getProfileForApplication - enter
I/SurfaceFlinger(  257): id=18 createSurf (1080x1920),1 flag=4, com.sec.android.app.launcher/com.android.launcher2.Launcher
V/EnterpriseBillingPolicyStorage(  908): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  908): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  908): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  908): getBillingProfileForVpnEngine - start - com.test.thalitest
D/StatusBarManagerService(  908): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
V/EnterpriseBillingPolicyStorage(  908): getBillingProfileForVpnEngine - end - null
D/StatusBarManagerService(  908): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/KnoxTimeoutHandler(  908): handleActiveUserChange for user 0
D/TaskPersister(  908): removeObsoleteFile: deleting file=11_task.xml
D/TaskPersister(  908): removeObsoleteFile: deleting file=9_task.xml
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/InputMethodManagerService(  908): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/InputMethodManagerService(  908): Got RemoteException sending setActive(false) notification to pid 7549 uid 10191
D/TimaKeyStoreProvider( 8245): TimaSignature is unavailable
D/StatusBar( 1183): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
D/ActivityThread( 8245): Added TimaKeyStore provider
I/PhoneStatusBar( 1183): Icon Only
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/PanelView( 1183): There is/are notification(s) 
D/PanelView( 1183): There is/are notification(s) 
D/ResourcesManager( 8245): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/elm:14451( 8245): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14451( 8245): ELMEngine.ELMEngine( context ).
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/elm:14451( 8245): MDMBridge.setEnterpriseBridge()
D/elm:14451( 8245): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
I/art     (  908): Explicit concurrent mark sweep GC freed 27719(1958KB) AllocSpace objects, 9(144KB) LOS objects, 30% free, 35MB/51MB, paused 5.564ms total 335.788ms
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
E/Zygote  ( 8264): MountEmulatedStorage()
E/Zygote  ( 8264): v2
I/libpersona( 8264): KNOX_SDCARD checking this for 10016
I/libpersona( 8264): KNOX_SDCARD not a persona
D/elm:14451( 8245): ElmAgentService : onCreate()
D/elm:14451( 8245): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14451( 8245): MainReceiver.listeningToPackageRemoved()
D/elm:14451( 8245): MDMBridge.getInstance()
D/elm:14451( 8245): MDMBridge.getAllLicenseInfoFromSDK()
I/ActivityManager(  908): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=8264 uid=10016 gids={50016, 9997} abi=armeabi-v7a
I/Timeline(  908): Timeline: Activity_windows_visible id: ActivityRecord{34364f14 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t7} time:1428996
D/PackageManager(  908): delete codoeFile: 
D/PackageManager(  908): result of delete: 1{569191885}
I/SELinux ( 8264): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8264): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8264): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/elm:14451( 8245): MDMBridge.getAllLicenseInfoFromSDK()
D/LockPatternUtilsCache( 1183): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1183): value : false
D/elm:14451( 8245): ElmAgentService : onDestroy().
D/TimaKeyStoreProvider( 8264): TimaSignature is unavailable
D/ActivityThread( 8264): Added TimaKeyStore provider
D/AndroidRuntime( 8213): Shutting down VM
I/ActivityManager(  908): Killing 7136:com.sec.android.app.soundalive/u0a57 (adj 15): bgCount ##41
D/ResourcesManager( 8264): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
D/ResourcesManager(  908): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/com.sec.android.service.health.upgrade.UninstallReceiver( 8264): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 8264): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver( 8264): onReceive() : package name is not s health. Return !!!
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
I/PCWCLIENTTRACE_PushUtil( 7056): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7056): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7056): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7056): [onReceive] - android.intent.action.PACKAGE_REMOVED
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  908): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/talkback/talkback.apk
E/Zygote  ( 8281): MountEmulatedStorage()
E/Zygote  ( 8281): v2
I/libpersona( 8281): KNOX_SDCARD checking this for 10033
I/libpersona( 8281): KNOX_SDCARD not a persona
I/ActivityManager(  908): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=8281 uid=10033 gids={50033, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
I/SELinux ( 8281): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8281): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/EnterpriseDeviceManagerService(  908): Package has changed for user 0
D/EnterpriseDeviceManagerService(  908): Admin package name: com.google.android.gms
E/SELinux ( 8281): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager(  908): Killing 6121:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##41
D/ResourcesManager(  908): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
W/Resources(  908): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  908): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
W/libprocessgroup(  908): failed to open /acct/uid_10057/pid_7136/cgroup.procs: No such file or directory
D/TimaKeyStoreProvider( 8281): TimaSignature is unavailable
I/art     (  318): Explicit concurrent mark sweep GC freed 8717(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 287us total 15.288ms
W/Resources(  908): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/Books/Books.apk
D/ActivityThread( 8281): Added TimaKeyStore provider
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/Music2/Music2.apk
I/art     (  318): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 252us total 7.755ms
D/ConnectivityService(  908): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
W/Resources(  908): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
D/ResourcesManager( 8281): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
I/art     (  318): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 254us total 8.028ms
W/Resources(  908): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/Videos/Videos.apk
W/libprocessgroup(  908): failed to open /acct/uid_1000/pid_6121/cgroup.procs: No such file or directory
I/FeatureConfig( 8281): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
D/ResourcesManager(  908): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
W/Resources(  908): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  908): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
W/Resources(  908): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
W/Resources(  908): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
W/ResourcesManager(  908): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  908): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  908): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/Resources(  908): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  908): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
D/ResourcesManager(  908): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
D/ResourcesManager(  908): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk

```
