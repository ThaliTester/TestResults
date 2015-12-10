#### Test 50650278c0f6ec2_thali05_samsung-SM-N9005 Logs


```
--------- beginning of main
E/SMD     (  290): DCD ON
I/ServiceManager(  338): Waiting for service AtCmdFwd...
,D/AndroidRuntime( 6591): 
D/AndroidRuntime( 6591): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6591): CheckJNI is OFF
D/AndroidRuntime( 6591): readGMSProperty: start
D/AndroidRuntime( 6591): readGMSProperty: already setted!!
D/AndroidRuntime( 6591): readGMSProperty: end
D/AndroidRuntime( 6591): addProductProperty: start
E/AffinityControl( 6591): AffinityControl: registerfunction enter
--------- beginning of system
V/AlarmManager(  872): waitForAlarm result :8
D/AndroidRuntime( 6591): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  872): inState():  stateMachine is null !!
I/PersonaManagerService(  872): PersonaId don't exist
I/ActivityManager(  872): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy(  872): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager(  872): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  872): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager(  872): mDVFSHelper.acquire()
D/FocusedStackFrame(  872): Set to : 0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  872): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6606 uid=10279 gids={50279, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/PointerIcon(  872): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  872): setMouseCustomIcon IconType is same.101
D/PointerIcon(  872): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  872): setHoveringSpenCustomIcon IconType is same.1
E/Zygote  ( 6606): MountEmulatedStorage()
E/Zygote  ( 6606): v2
I/libpersona( 6606): KNOX_SDCARD checking this for 10279
I/libpersona( 6606): KNOX_SDCARD not a persona
D/AndroidRuntime( 6591): Shutting down VM
I/SELinux ( 6606): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6606): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6606): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 6606): TimaSignature is unavailable
D/ActivityThread( 6606): Added TimaKeyStore provider
V/WindowOrientationListener(  872): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  872): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  872): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  872): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  872): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/ActivityManager(  872): Display changed displayId=0
D/SurfaceWidgetView( 1462): destroyHardwareResources():447025947
D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ResourcesManager( 6606): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
I/SurfaceFlinger(  254): id=6 Removed Mauncher (6/8)
I/SurfaceFlinger(  254): id=6 Removed Mauncher (-2/8)
V/ActivityThread( 1462): updateVisibility : ActivityRecord{1a838320 token=android.os.BinderProxy@1c21d26a {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1806): [237392/8] Surface widget visibility changed visibility = false on instance = 1
D/Launcher( 1462): onTrimMemory. Level: 20
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/WebViewFactory( 6606): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,D/ResourcesManager( 6606): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 6606): Loading: webviewchromium
,I/LibraryLoader( 6606): Time to load native libraries: 6 ms (timestamps 9643-9649)
I/LibraryLoader( 6606): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6606): Binding Chromium to main looper Looper (main, tid 1) {24375d5d}
,I/LibraryLoader( 6606): Expected native library version number "",actual native library version number ""
I/chromium( 6606): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6606): Initializing chromium process, renderers=0
,W/art     ( 6606): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 6606): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,W/chromium( 6606): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 6606): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46780 len=2953
,I/chromium( 6606): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229536 len:643667
,D/BluetoothAdapter( 6606): 485705426: getState() :  mService = null. Returning STATE_OFF
,I/Adreno-EGL( 6606): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 6606): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6606): Build Date: 11/19/14 Wed
I/Adreno-EGL( 6606): Local Branch: mybranch5813579
I/Adreno-EGL( 6606): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 6606): Local Patches: NONE
I/Adreno-EGL( 6606): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,W/chromium( 6606): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 6606): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/ActivityManager(  872): Activity pause timeout for ActivityRecord{8c81ead u0 com.test.thalitest/.MainActivity t3}
,I/PowerManagerService(  872): [PWL] Off : 50s ago
,W/art     ( 6606): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6606): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6606): CordovaWebView is running on device made by: samsung
,W/art     ( 6606): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6606): Attempt to remove local handle scope entry from IRT, ignoring
,D/Activity( 6606): performCreate Call secproduct feature valuefalse
D/Activity( 6606): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer( 6606): Render dirty regions requested: true
,D/Atlas   ( 6606): Validating map...
,D/ActivityManager(  872): post active user change for 0
,D/KnoxTimeoutHandler(  872): postActiveUserChange for user 0
,D/KnoxTimeoutHandler(  872): handleActiveUserChange for user 0
,V/ActivityThread( 6606): updateVisibility : ActivityRecord{d526b93 token=android.os.BinderProxy@5af57cd {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,I/SurfaceFlinger(  254): id=13 createSurf (1x1),1 flag=404, NainActivit
,D/StatusBarManagerService(  872): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService(  872): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon(  872): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,I/OpenGLRenderer( 6606): Initialized EGL, version 1.4
D/PointerIcon(  872): setMouseCustomIcon IconType is same.101
,D/PointerIcon(  872): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  872): setHoveringSpenCustomIcon IconType is same.1
,I/OpenGLRenderer( 6606): HWUI protection enabled for context ,  &this =0xb3a67b28 ,&mEglDisplay = 1 , &mEglConfig = 8 
,D/OpenGLRenderer( 6606): Enabling debug mode 0
,D/InputMethodManagerService(  872): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl(  872): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ActivityManager(  872): mDVFSHelper.release()
,I/Timeline(  872): Timeline: Activity_windows_visible id: ActivityRecord{8c81ead u0 com.test.thalitest/.MainActivity t3} time:160192
,I/SamsungIME( 1708): getCurrentCandidateView
,W/IInputConnectionWrapper( 6606): showStatusIcon on inactive InputConnection
,I/Timeline( 6606): Timeline: Activity_idle id: android.os.BinderProxy@5af57cd time:160202
,W/ContextImpl(  872): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SamsungIME( 1708): Dismiss ExpandCandiate
,I/chromium( 6606): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6606): 
,I/SamsungIME( 1708): getDebugLevel  : 0x4f4c
,D/JsMessageQueue( 6606): Set native->JS mode to OnlineEventsBridgeMode
,I/SamsungIME( 1708): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1708): KeybaordView init() : load resources
,D/SSRM:n  (  872): SIOP:: AP = 320, PST = 333, CUR = 450
,I/SamsungIME( 1708): getCurrentKeyboard
I/SamsungIME( 1708): getTextKeyboard
,D/SamsungIME( 1708): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/jxcore_app_log( 6606): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1357254272
D/JX-Cordova( 6606): jxcore cordova android initializing
V/AlarmManager(  872): waitForAlarm result :4
,D/NtpTrustedTime(  872): forceRefresh() from cache miss
,D/NtpTrustedTime(  872): forceRefresh Fail.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1187): handleTimeUpdate
,D/KeyguardEffectViewController( 1187): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1187): *** don't update sliding image ***
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/DateView( 1187): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1187): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,D/SamsungIME( 1708): [SwiftkeyWrapper] currentLangauge : 1701729619
,E/SMD     (  290): DCD ON
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,W/jxcore-log( 6606): Initializing JXcore engine
W/jxcore-log( 6606): JXcore engine is ready
,W/jxcore-log( 6606): Starting JXcore engine
,E/auditd  ( 1856): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  872): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl(  872): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
,D/SecurityLogAgent:SEDenialService(  872): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,E/Zygote  ( 6699): MountEmulatedStorage()
I/ActivityManager(  872): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=6699 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/Zygote  ( 6699): v2
I/libpersona( 6699): KNOX_SDCARD checking this for 1000
I/libpersona( 6699): KNOX_SDCARD not a persona
,I/SELinux ( 6699): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6699): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6699): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6699): TimaSignature is unavailable
,D/ActivityThread( 6699): Added TimaKeyStore provider
,W/jxcore-log( 6606): Platform android
W/jxcore-log( 6606): 
,W/jxcore-log( 6606): Process ARCH arm
W/jxcore-log( 6606): 
,D/ResourcesManager( 6699): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/SecurityLogAgent( 6699):  SeDenialReceiver : Intent Received : android.intent.action.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 6699):  SeDenialReceiver : File path = null
,I/ActivityManager(  872): Killing 4997:com.google.android.talk/u0a131 (adj 15): bgCount ##41
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/jxcore-log( 6606): JXcore Cordova bridge is ready!
I/jxcore-log( 6606): 
,W/jxcore-log( 6606): JXcore engine is started
,I/jxcore-log( 6606): Toggling radios to true
I/jxcore-log( 6606): 
,D/BluetoothAdapter( 6606): enable()
,W/ActivityManager(  872): Permission Denial: getCurrentUser() from pid=6606, uid=10279 requires android.permission.INTERACT_ACROSS_USERS
W/BluetoothManagerService(  872): Failed getting userId using ActivityManagerNative
W/BluetoothManagerService(  872): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6606, uid=10279 requires android.permission.INTERACT_ACROSS_USERS
W/BluetoothManagerService(  872): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23057)
W/BluetoothManagerService(  872): 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2141)
W/BluetoothManagerService(  872): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:671)
W/BluetoothManagerService(  872): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
W/BluetoothManagerService(  872): 	at android.os.Binder.execTransact(Binder.java:446)
E/DevicePolicyManagerService(  872): getAllowBluetoothMode - value retunrs : 2
,E/DevicePolicyManagerService(  872): getAllowBluetoothMode - value retunrs : 2
D/SettingsProvider(  872): name = bluetooth_on
,E/DevicePolicyManagerService(  872): getAllowBluetoothMode - value retunrs : 2
E/DevicePolicyManagerService(  872): getAllowBluetoothMode - value retunrs : 2
,E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
,I/WifiManager( 6606): packageName : com.test.thalitest
D/SecContentProvider(  872): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2(  872): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  872): mCursor = null
,D/WifiService(  872): setWifiEnabled: true pid=6606, uid=10279
W/ActivityManager(  872): Permission Denial: getCurrentUser() from pid=6606, uid=10279 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  872): Failed getting userId using ActivityManagerNative
W/WifiService(  872): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6606, uid=10279 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  872): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23057)
W/WifiService(  872): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2181)
W/WifiService(  872): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2169)
W/WifiService(  872): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService(  872): 	at android.os.Binder.execTransact(Binder.java:446)
D/SettingsProvider(  872): name = wifi_on
,I/WifiService(  872): disconnect: pid=6606, uid=10279
,E/WifiHW  (  872): ##################### set firmware type 0 #####################
,I/jxcore-log( 6606): Radios toggled
I/jxcore-log( 6606): 
,I/WifiHW  (  284): wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
I/WifiHW  (  284): module is semco
E/WifiHW  (  284): ==========[WIFI] SEMCO MODULE ===========
I/WifiHW  (  284): wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt
E/WifiHW  (  284): TEMP_FAILURE_RETRY complete
D/SoftapController(  284): Softap fwReload - Ok
,D/CommandListener(  284): Setting iface cfg
D/CommandListener(  284): Trying to bring down wlan0
,D/CommandListener(  284): Clearing all IP addresses on wlan0
I/libpersona( 6717): KNOX_SDCARD checking this for 1002
E/Zygote  ( 6717): MountEmulatedStorage()
I/libpersona( 6717): KNOX_SDCARD not a persona
E/Zygote  ( 6717): v2
,E/WifiHW  (  872): supplicant_name : p2p_supplicant
,I/ActivityManager(  872): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=6717 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,D/SmartBondingService(  872): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,D/WifiMonitor(  872): startMonitoring(wlan0) with mConnected = false
,E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
,I/SELinux ( 6717): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6717): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6717): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/SmartBondingService(  872): getNetworkEnabled : wifi : false mobile : true
,D/StatusBar.NetworkController( 1187): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1187): onWifiSignalChanged enabled=false enabledDesc:null
,D/STATUSBAR-WifiQuickSettingButton( 1187): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1187): Wifi onReceive(2)
,D/STATUSBAR-QSTileView( 1187): onStateChanged: Wi-Fi
I/wpa_supplicant( 6718): [wpa_supplicant_init]: use SECRIL
I/wpa_supplicant( 6718): Successfully initialized wpa_supplicant
,I/SecureStorage( 6718): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 6718): [INFO]: SPID(0x00000000)This device supports Secure Storage
,E/Zygote  ( 6733): MountEmulatedStorage()
E/Zygote  ( 6733): v2
I/libpersona( 6733): KNOX_SDCARD checking this for 10152
I/libpersona( 6733): KNOX_SDCARD not a persona
,I/ActivityManager(  872): Start proc tv.peel.samsung.app for broadcast tv.peel.samsung.app/com.peel.receiver.ConnectivityActionReceiver: pid=6733 uid=10152 gids={50152, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/SecureStorage(  394): [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6718
I/SecureStorage(  394): [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
I/SecureStorage( 6718): [INFO]: SPID(0x00000000)SS Daemon is running
I/wpa_supplicant( 6718): ssSupport state is = 1
,I/wpa_supplicant( 6718): >>>>> GET KEY, IV <<<<<
,I/SecureStorage( 6718): [INFO]: SPID(0x00000000)Processing data
,I/SecureStorage(  394): [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6718
D/WifiCredService( 1303): Action received :android.net.wifi.WIFI_STATE_CHANGED
I/SecureStorage(  394): [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,I/SELinux ( 6733): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
D/HotspotTile( 1187): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/HotspotTile( 1187): onReceive : 2, 0
,I/SELinux ( 6733): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
D/TimaKeyStoreProvider( 6717): TimaSignature is unavailable
,D/ActivityThread( 6717): Added TimaKeyStore provider
E/SELinux ( 6733): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 6717): creating new AssetManager and set to /system/app/Bluetooth/Bluetooth.apk
,W/ResourcesManager( 6717): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,W/ResourcesManager( 6717): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 6733): TimaSignature is unavailable
D/ActivityThread( 6733): Added TimaKeyStore provider
I/BluetoothA2dpSinkServiceJni( 6717): register_com_android_bluetooth_a2dp_sink
,D/ResourcesManager( 6733): creating new AssetManager and set to /system/app/Peel_L/Peel_L.apk
,D/BtSettings.ProfileConfig( 6717): Adding GattService
,D/BtSettings.ProfileConfig( 6717): Adding HeadsetService
,D/BtSettings.ProfileConfig( 6717): Adding A2dpService
D/BtSettings.ProfileConfig( 6717): Adding HidService
,D/BtSettings.ProfileConfig( 6717): Adding HealthService
,D/BtSettings.ProfileConfig( 6717): Adding PanService
D/BtSettings.ProfileConfig( 6717): Adding BluetoothMapService
,D/BtSettings.ProfileConfig( 6717): Adding SapService
D/BtSettings.ProfileConfig( 6717): Adding HeadsetClientService
D/BtSettings.ProfileConfig( 6717): Adding A2dpSinkService
D/BtSettings.ProfileConfig( 6717): Adding SapClientService
D/BtSettings.ProfileConfig( 6717): Adding HidDevService
I/BtSettings.ProfileConfig( 6717): *********Initializing Bluetooth Profile Settings*******
D/SettingsProvider(  872): name = bt_svcst_com.android.bluetooth.gatt.GattService
D/SettingsProvider(  872): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  872): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  872): selectionArgs: false
D/SettingsProvider(  872): selectionArgs: 1002
D/SecContentProvider(  872): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  872): ret = -1
,W/BackupManagerService(  872): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  872): name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
,D/SettingsProvider(  872): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  872): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  872): selectionArgs: false
D/SettingsProvider(  872): selectionArgs: 1002
D/SecContentProvider(  872): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider(  872): ret = -1
,W/BackupManagerService(  872): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  872): name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
,D/SettingsProvider(  872): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  872): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  872): selectionArgs: false
D/SettingsProvider(  872): selectionArgs: 1002
,D/SecContentProvider(  872): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  872): ret = -1
,W/BackupManagerService(  872): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  872): name = bt_svcst_com.android.bluetooth.hid.HidService
D/SettingsProvider(  872): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  872): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  872): selectionArgs: false
D/SettingsProvider(  872): selectionArgs: 1002
D/SecContentProvider(  872): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  872): ret = -1
,W/BackupManagerService(  872): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  872): name = bt_svcst_com.android.bluetooth.hdp.HealthService
,D/SettingsProvider(  872): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  872): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  872): selectionArgs: false
D/SettingsProvider(  872): selectionArgs: 1002
,D/SecContentProvider(  872): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  872): ret = -1
,W/BackupManagerService(  872): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  872): name = bt_svcst_com.android.bluetooth.pan.PanService
D/SettingsProvider(  872): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  872): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  872): selectionArgs: false
D/SettingsProvider(  872): selectionArgs: 1002
D/SecContentProvider(  872): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  872): ret = -1
,W/BackupManagerService(  872): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  872): name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
D/SettingsProvider(  872): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  872): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  872): selectionArgs: false
D/SettingsProvider(  872): selectionArgs: 1002
D/SecContentProvider(  872): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  872): ret = -1
,W/BackupManagerService(  872): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  872): name = bt_svcst_com.broadcom.bt.service.sap.SapService
D/SettingsProvider(  872): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  872): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  872): selectionArgs: false
D/SettingsProvider(  872): selectionArgs: 1002
D/SecContentProvider(  872): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  872): ret = -1
,W/BackupManagerService(  872): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  872): name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
D/SettingsProvider(  872): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  872): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  872): selectionArgs: false
D/SettingsProvider(  872): selectionArgs: 1002
D/SecContentProvider(  872): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  872): ret = -1
,W/BackupManagerService(  872): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  872): name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
D/SettingsProvider(  872): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  872): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  872): selectionArgs: false
D/SettingsProvider(  872): selectionArgs: 1002
D/SecContentProvider(  872): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  872): ret = -1
,W/BackupManagerService(  872): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  872): name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
D/SettingsProvider(  872): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  872): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  872): selectionArgs: false
D/SettingsProvider(  872): selectionArgs: 1002
D/SecContentProvider(  872): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  872): ret = -1
,W/BackupManagerService(  872): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  872): name = bt_svcst_com.android.bluetooth.hid.HidDevService
D/SettingsProvider(  872): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  872): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  872): selectionArgs: false
D/SettingsProvider(  872): selectionArgs: 1002
D/SecContentProvider(  872): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  872): ret = -1
,W/BackupManagerService(  872): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/BluetoothAdapterState( 6717): make
,I/bluedroid( 6717): init
,I/BluetoothAdapterState( 6717): Entering OffState
,I/bte_conf( 6717): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 6717): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 6717): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 6717): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,E/bt-btif ( 6717): btif_fetch_local_ble_random_bdaddr
,I/bluedroid( 6717): get_profile_interface socket
I/bluedroid( 6717): get_profile_interface map_client
I/GKI_LINUX( 6717): gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothAdapterService( 6717): checkAddrForIOP: Loading from conf
,D/BluetoothAdapterProperties( 6717): Address is:E0:DB:10:1F:C9:5E
E/BluetoothServiceJni( 6717): populateRssiValuesNative
I/bluedroid( 6717): getModelRssiValues
E/BluetoothServiceJni( 6717): model_rssi_values_callback: low = -70, mid = -60, high = 127
D/BluetoothAdapterProperties( 6717): modelRssiValuesCallback, low, mid, high = -70,-60,127
,D/BluetoothAdapterProperties( 6717): Name is: Note3-1
,D/SettingsProvider(  872): name = bluetooth_name
,I/bluedroid( 6717): config_hci_snoop_log
,D/BluetoothManagerService(  872): Broadcasting onBluetoothServiceUp() to 10 receivers.
,E/DevicePolicyManagerService(  872): getAllowBluetoothMode - value retunrs : 2
,E/DevicePolicyManagerService(  872): getAllowBluetoothMode - value retunrs : 2
,D/SecContentProvider(  872): uri = 3 selection = isBluetoothEnabled
,D/BluetoothAdapterState( 6717): CURRENT_STATE=OFF, MSG = USER_TURN_ON
D/BluetoothAdapterProperties( 6717): Setting state to 11
,I/BluetoothAdapterState( 6717): Bluetooth adapter state changed: 10-> 11
D/BluetoothAdapterService( 6717): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 6717): updateAdapterState state is 11
D/BluetoothAdapterService( 6717): Autoconnection is available 
,D/BluetoothAdapterService( 6717): updateAdapterState prevState = 10newState = 11
,W/InputMethodManagerService(  872): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,I/InputMethodManagerService(  872): [BT Setting State] State =11
D/BluetoothSecureManager( 6717): getInstant: null
,D/BluetoothSecureManager( 6717): calling getMethod for getService
D/BluetoothSecureManager( 6717): calling getService
,I/SamsungIME( 1708): STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,D/BluetoothSecureManager( 6717): getService return binder: android.os.BinderProxy@1fef941b
D/BluetoothTile( 1187):  onBluetoothPairedDevicesChanged:
D/BluetoothTile( 1187): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothSecureManagerService(  872): isSecureModeEnabled
D/BluetoothSecureManagerService(  872): getSecureModeSetting, name: secure_mode_enable
D/BtConfig.SecureMode( 6717): isSecureModeOn:false
D/BtSettings.ProfileConfig( 6717): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,W/BluetoothAdapterService( 6717): isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 6717): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,W/BluetoothAdapterService( 6717): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
,D/StatusBarManagerService(  872): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020319 level=0 visible=true num=0 )
D/BtSettings.ProfileConfig( 6717): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,D/STATUSBAR-QSTileView( 1187): onStateChanged: Bluetooth
,W/BluetoothAdapterService( 6717): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
D/StatusBarManagerService(  872): setIconVisibility slot=bluetooth visible=false
,D/BtSettings.ProfileConfig( 6717): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,D/PhoneStatusBar( 1187): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020319 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020319 level=0 visible=false num=0 )
,W/BluetoothAdapterService( 6717): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 6717): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 6717): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 6717): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService( 6717): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 6717): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 6717): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 6717): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 6717): isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
,D/BtSettings.ProfileConfig( 6717): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 6717): processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig( 6717): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,W/BluetoothAdapterService( 6717): processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 6717): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,W/BluetoothAdapterService( 6717): processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
,D/BtSettings.ProfileConfig( 6717): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
W/BluetoothAdapterService( 6717): processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,D/BluetoothBondStateMachine( 6717): make
,I/BluetoothBondStateMachine( 6717): StableState(): Entering Off State
,W/BluetoothAdapterService( 6717): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 6717): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 6717): Not skipping com.android.bluetooth.gatt.GattService
,I/BtGatt.JNI( 6717): classInitNative(L890): classInitNative: Success!
,W/BluetoothAdapterService( 6717): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 6717): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
W/BluetoothAdapterService( 6717): Not skipping com.android.bluetooth.hfp.HeadsetService
,W/BluetoothAdapterService( 6717): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 6717): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 6717): Not skipping com.android.bluetooth.a2dp.A2dpService
,D/BtGatt.DebugUtils( 6717): handleDebugAction() action=null
,D/BtGatt.GattService( 6717): Received start request. Starting profile...
D/BtGatt.GattService( 6717): start()
I/bluedroid( 6717): get_profile_interface gatt
,D/BluetoothAdapterService( 6717): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cf346d2
D/BtGatt.AdvertiseManager( 6717): advertise manager created
,W/BluetoothAdapterService( 6717): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 6717): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 6717): Not skipping com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 6717): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 6717): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 6717): Not skipping com.android.bluetooth.hdp.HealthService
,I/SecureStorage(  394): [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,W/BluetoothAdapterService( 6717): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 6717): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 6717): Not skipping com.android.bluetooth.pan.PanService
,D/BluetoothAdapterService( 6717): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cf346d2
,I/WebViewFactory( 6733): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,D/ResourcesManager( 6733): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,D/HeadsetService( 6717): Received start request. Starting profile...
,W/BluetoothAdapterService( 6717): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 6717): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 6717): Not skipping com.android.bluetooth.map.BluetoothMapService
,I/BluetoothHeadsetServiceJni( 6717): classInitNative: succeeds
,D/HeadsetStateMachine( 6717): make
,W/BluetoothAdapterService( 6717): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,D/BtSettings.ProfileConfig( 6717): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 6717): Not skipping com.broadcom.bt.service.sap.SapService
,E/HeadsetStateMachine( 6717): # of Max HF connection is 2
,I/LibraryLoader( 6733): Loading: webviewchromium
,W/BluetoothAdapterService( 6717): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig( 6717): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 6717): Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 6717): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 6717): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 6717): Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 6717): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 6717): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 6717): Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 6717): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
D/BtSettings.ProfileConfig( 6717): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
W/BluetoothAdapterService( 6717): Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
I/BluetoothAdapterState( 6717): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,I/LibraryLoader( 6733): Time to load native libraries: 5 ms (timestamps 3372-3377)
,I/LibraryLoader( 6733): Expected native library version number "",actual native library version number ""
,I/bluedroid( 6717): get_profile_interface handsfree
,I/DualScoManager( 6717): Instantiating Dual Sco Manager
I/DualScoManager( 6717): Set HeadsetServiceHelper
,D/BluetoothAtMessage( 6717): createCMTIContentObservers
,D/SettingsProvider(  872): name = bluetooth_hfp_allowed_bvra
,D/SettingsProvider(  872): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  872): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  872): selectionArgs: false
D/SettingsProvider(  872): selectionArgs: 1002
D/SecContentProvider(  872): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider(  872): ret = -1
,W/BackupManagerService(  872): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/HeadsetStateMachine( 6717): Enter Disconnected: -2
,D/BluetoothAdapterService( 6717): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cf346d2
,E/HeadsetStateMachine( 6717): set to mRemoteBrsf = 0
,D/A2dpService( 6717): Received start request. Starting profile...
,D/BluetoothA2dp(  872): Proxy object connected
,I/BluetoothAvrcpServiceJni( 6717): classInitNative: succeeds
V/Avrcp   ( 6717): make
,V/Avrcp   ( 6717): Avrcp
I/bluedroid( 6717): get_profile_interface avrcp
,D/HeadsetStateMachine( 6717): map size, before remove : 0
,V/Avrcp   ( 6717): start
D/HeadsetStateMachine( 6717): map size, after remove: 0
D/HeadsetStateMachine( 6717): mNextConnectingDevice : null
,D/BluetoothA2dp( 2947): Proxy object connected
,E/RemoteController( 6717): Cannot set synchronization mode on an unregistered RemoteController
,V/Avrcp   ( 6717): ++registerMediaPlayers++
,I/Avrcp   ( 6717): No of Audio players :: 2
I/Avrcp   ( 6717): App Package name is com.google.android.music
,D/ResourcesManager( 6717): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/Avrcp   ( 6717): App pkg name is Google Play Music
,I/Avrcp   ( 6717): Name::Google Play Music
V/Avrcp   ( 6717): MediaPlayerInfo: mPlayerId=1
I/Avrcp   ( 6717): App Package name is com.sec.android.app.music
,D/ResourcesManager( 6717): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,I/Avrcp   ( 6717): App pkg name is Music
,I/Avrcp   ( 6717): Name::Music
V/Avrcp   ( 6717): MediaPlayerInfo: mPlayerId=2
I/Avrcp   ( 6717):  set player publishabilty with player id::2 toBePublished ::true
,V/WebViewChromiumFactoryProvider( 6733): Binding Chromium to main looper Looper (main, tid 1) {b9553a3}
I/Avrcp   ( 6717): No of Video players :: 1
I/Avrcp   ( 6717): Video App Package name is com.sec.android.app.videoplayer
,D/ResourcesManager( 6717): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,I/LibraryLoader( 6733): Expected native library version number "",actual native library version number ""
,I/chromium( 6733): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/Avrcp   ( 6717): Video App pkg name is Video Player
I/Avrcp   ( 6717): Name::Video Player
V/Avrcp   ( 6717): MediaPlayerInfo: mPlayerId=3
I/Avrcp   ( 6717): Add tempPlayer
V/Avrcp   ( 6717): MediaPlayerInfo: mPlayerId=4
I/Avrcp   ( 6717): Total no of players: 4
V/Avrcp   ( 6717): swapping the samsung player with 1st player
I/Avrcp   ( 6717):  Updating now playing list upon AVRCP Start
V/Avrcp   ( 6717): handleMessage, msg=207
,D/BluetoothMediaBrowser( 6717):  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,I/BluetoothA2dpServiceJni( 6717): classInitNative: succeeds
D/A2dpStateMachine( 6717): make
,I/bluedroid( 6717): get_profile_interface a2dp
,I/GKI_LINUX( 6717): gki_task_entry task_id=2 [A2DP-MEDIA] starting
E/bt-btif ( 6717): warning : media task started media_task_refcnt 1 
,D/BluetoothAdapterService( 6717): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cf346d2
,I/BluetoothHidServiceJni( 6717): classInitNative: succeeds
,D/A2dpStateMachine( 6717): Enter Disconnected: -2
,I/BrowserStartupController( 6733): Initializing chromium process, renderers=0
D/HidService( 6717): Received start request. Starting profile...
I/bluedroid( 6717): get_profile_interface hidhost
D/HidService( 6717): setHidService(): set to: null
D/BluetoothAdapterService( 6717): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cf346d2
,D/BluetoothMediaBrowser( 6717): no now playing list
D/BluetoothMediaBrowser( 6717):  getNowPlayingId now playing id : -1
D/Avrcp   ( 6717):  checkNowPlayingList start
I/BluetoothHealthServiceJni( 6717): classInitNative: succeeds
,D/HealthService( 6717): Received start request. Starting profile...
,W/art     ( 6733): Attempt to remove local handle scope entry from IRT, ignoring
,I/bluedroid( 6717): get_profile_interface health
D/BluetoothAdapterService( 6717): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cf346d2
E/BluetoothAdapterService(485705426)( 6717): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,I/BluetoothPanServiceJni( 6717): classInitNative(L105): succeeds
,D/BluetoothPan(  872): BluetoothPAN Proxy object connected
,D/PanService( 6717): Received start request. Starting profile...
D/BluetoothPanServiceJni( 6717): initializeNative(L110): pan
I/bluedroid( 6717): get_profile_interface pan
,D/BluetoothAdapterService( 6717): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cf346d2
,D/BluetoothMapService( 6717): Received start request. Starting profile...
,E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
,W/chromium( 6733): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,W/chromium( 6733): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,I/chromium( 6733): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=36 off=46780 len=2953
I/chromium( 6733): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:37 off:229536 len:643667
,E/Zygote  ( 6788): MountEmulatedStorage()
,E/Zygote  ( 6788): v2
I/libpersona( 6788): KNOX_SDCARD checking this for 10186
I/libpersona( 6788): KNOX_SDCARD not a persona
,I/Adreno-EGL( 6733): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 6733): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6733): Build Date: 11/19/14 Wed
I/Adreno-EGL( 6733): Local Branch: mybranch5813579
I/Adreno-EGL( 6733): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 6733): Local Patches: NONE
I/Adreno-EGL( 6733): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,I/ActivityManager(  872): Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=6788 uid=10186 gids={50186, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/SELinux ( 6788): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6788): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6788): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6788): TimaSignature is unavailable
,D/ActivityThread( 6788): Added TimaKeyStore provider
,W/Atfwd_Sendcmd(  338): AtCmdFwd service not published, waiting... retryCnt : 4
,D/ResourcesManager( 6788): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 6788): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 6788): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6788): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6788): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6788): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/SecureStorage( 6718): [INFO]: SPID(0x00000000)Processing data has been completed
,W/chromium( 6733): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 6733): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,I/SecureStorage( 6718): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 6718): [INFO]: SPID(0x00000000)This device supports Secure Storage
,I/SecureStorage(  394): [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6718
I/SecureStorage(  394): [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
I/SecureStorage( 6718): [INFO]: SPID(0x00000000)SS Daemon is running
I/wpa_supplicant( 6718): ssSupport state is = 1
I/wpa_supplicant( 6718): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,E/wpa_supplicant( 6718): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 6718): SIM READ ERROR
I/wpa_supplicant( 6718): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 6718): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 6718): SIM READ ERROR
I/wpa_supplicant( 6718): Blacklist: Clear (all) 
,I/wpa_supplicant( 6718): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 6718): getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
I/wpa_supplicant( 6718): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 6718): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,I/wpa_supplicant( 6718): rfkill: Cannot open RFKILL control device
,D/RCPManagerService(  872): exchangeData() failure , invalid userId
,W/art     ( 6733): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6733): onDetachedFromWindow called when already detached. Ignoring
,D/RCPManagerService(  872): exchangeData() failure , invalid userId
,D/RCPManagerService(  872): exchangeData() failure , invalid userId
,D/BluetoothAdapterService( 6717): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cf346d2
,I/BluetoothSAPServiceJni( 6717): classInitNative(L204): succeeds
,D/SapService( 6717): Received start request. Starting profile...
D/BluetoothSAPServiceJni( 6717): initializeNative(L209): sap
I/bluedroid( 6717): get_profile_interface sap
D/BluetoothAdapterService( 6717): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cf346d2
,D/HeadsetStateMachine( 6717): Try to query the phonestate on bind
,I/Telecom ( 1417): BluetoothPhoneService: queryPhoneState
,I/Telecom ( 1417): BluetoothPhoneService: updateHeadsetWithCallState
,I/Telecom ( 1417): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,W/BluetoothHeadset( 1417): Proxy not attached to service
,D/HeadsetStateMachine( 6717): Proxy object connected
,D/HeadsetPhoneState( 6717): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
D/HeadsetPhoneState( 6717): sendDeviceDataStateChanged
D/HeadsetStateMachine( 6717): Disconnected process message: 11
D/HeadsetPhoneState( 6717): Signal level : previous=0 curr=0
E/BluetoothAdapterService(485705426)( 6717): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
,V/HeadsetService( 6717): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/BluetoothA2dp( 6717): Proxy object connected
D/BluetoothAdapterService( 6717): Bluetooth A2dp source service connected
E/BluetoothAdapterService(485705426)( 6717): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
E/BluetoothAdapterService(485705426)( 6717): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
D/HeadsetStateMachine( 6717): Disconnected process message: 18
D/HeadsetStateMachine( 6717): Disconnected process message: 10
D/RCPManagerService(  872): exchangeData() failure , invalid userId
D/HeadsetPhoneState( 6717): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 6717): Disconnected process message: 11
,E/BluetoothAdapterService(485705426)( 6717): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
E/BluetoothAdapterService(485705426)( 6717): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,D/BadgeProvider( 6069): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,I/ActivityManager(  872): Killing 5784:com.google.android.gms:car/u0a15 (adj 15): bgCount ##41
,E/BluetoothAdapterService(485705426)( 6717): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
E/BluetoothAdapterService(485705426)( 6717): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,D/BluetoothAdapterState( 6717): CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 6717): enable
,I/GKI_LINUX( 6717): gki_task_entry task_id=0 [BTU] starting
,I/bt_hci_bdroid( 6717): init
,I/bt_vendor( 6717): init
I/bt_vnd_conf( 6717): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 6717): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial( 6717): userial_init
D/bt_vendor( 6717): op for 5
,D/bt_vendor( 6717): op for 0
,D/bt_upio ( 6717): upio_set_bluetooth_power(on: 0)
D/bt_upio ( 6717): is_emulator_context : 0
D/bt_upio ( 6717): is_rfkill_disabled ? [0]
D/bt_upio ( 6717): is_rfkill_disabled ? [0]
,D/BadgeProvider( 6069): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 6069): sendNotify, [notify] : null
D/Launcher.Model( 1462): reloadBadges entered.
D/BadgeProvider( 6069): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 6069): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 6069): update, [UpdateCount] : 1
D/bt_vendor( 6717): op for 0
D/bt_upio ( 6717): upio_set_bluetooth_power(on: 1)
D/bt_upio ( 6717): is_emulator_context : 0
D/bt_upio ( 6717): is_rfkill_disabled ? [0]
,D/bt_vendor( 6717): op for 3
I/bt_userial_vendor( 6717): userial vendor open: opening /dev/ttyHS0
,I/bt_userial_vendor( 6717): userial_vendor_open():UART is setup
I/bt_userial_vendor( 6717): device fd = 65 open
,D/bt_vendor( 6717): op for 1
D/bt_userial( 6717): Entering userial_read_thread()
E/bt_hwcfg( 6717): Start CFG HW, HCI reset
,E/bt_hwcfg( 6717): Read Local Name after HCI reset
,E/SignOutReceiver( 6233): WIFI_STATE_CHANGED_ACTION
,I/art     (  872): Explicit concurrent mark sweep GC freed 71375(4MB) AllocSpace objects, 34(544KB) LOS objects, 17% free, 37MB/45MB, paused 1.437ms total 98.169ms
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 6699): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 6699): KnoxConfiguration : Current State Mapping Found 
,D/SecurityLogAgent( 6699): StateMachine : Current State = 1
,D/SecurityLogAgent( 6699): StateMachine : Changed Current State = 1
,I/ActivityManager(  872): Killing 5836:com.android.defcontainer/u0a7 (adj 15): bgCount ##41
,D/BluetoothNotiBroadcastReceiver( 1303): onReceive
,D/AuthorizationBluetoothService( 1397): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/ActivityManager(  872): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,E/SMD     (  290): DCD ON
,E/Tethering(  872): No numeric data
,D/Tethering(  872): sendTetherStateChangedBroadcast 1, 0, 0
D/NtpTrustedTime(  872): forceRefresh() from cache miss
,D/HotspotTile( 1187): onReceive : android.net.conn.TETHER_STATE_CHANGED
,D/HotspotTile( 1187): updateTetherState():false, false
,D/NtpTrustedTime(  872): forceRefresh Fail.
,V/NetworkStats(  872): performPollLocked(flags=0x1)
,D/NetworkStatsFactory(  872): UpdateStatsForKnox
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/NetworkStats(  872): performPollLocked() took 4ms
,D/NtpTrustedTime(  872): forceRefresh() from cache miss
,D/NtpTrustedTime(  872): forceRefresh Fail.
,I/wpa_supplicant( 6718): wlan0: Setting scan request: 0 sec 100000 usec
,I/wpa_supplicant( 6718): wlan0: State: DISCONNECTED -> DISCONNECTED
,I/SecureStorage( 6718): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 6718): [INFO]: SPID(0x00000000)This device supports Secure Storage
,I/SecureStorage(  394): [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6718
I/SecureStorage(  394): [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
,I/SecureStorage( 6718): [INFO]: SPID(0x00000000)SS Daemon is running
I/wpa_supplicant( 6718): ssSupport state is = 1
,I/SecureStorage( 6718): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 6718): [INFO]: SPID(0x00000000)This device supports Secure Storage
,I/SecureStorage(  394): [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6718
I/SecureStorage(  394): [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
I/SecureStorage( 6718): [INFO]: SPID(0x00000000)SS Daemon is running
I/wpa_supplicant( 6718): ssSupport state is = 1
I/wpa_supplicant( 6718): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 6718): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 6718): SIM READ ERROR
I/wpa_supplicant( 6718): rfkill: Cannot open RFKILL control device
,I/wpa_supplicant( 6718): p2p0: State: DISCONNECTED -> INACTIVE
I/wpa_supplicant( 6718): CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 6718): p2p0: State: INACTIVE -> DISCONNECTED
I/wpa_supplicant( 6718): CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
I/wpa_supplicant( 6718): Skip scan - bUseNetwork false
,E/WifiStateMachine(  872): skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,D/WifiNative-HAL(  872): callSECApiBoolean - ID [21]
,I/wpa_supplicant( 6718): HOTSPOT20_ENABLE called
I/wpa_supplicant( 6718): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 6718): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 6718): SIM READ ERROR
I/wpa_supplicant( 6718): Blacklist: Clear (all) 
,I/wpa_supplicant( 6718): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 6718): Skip scan - bUseNetwork false
,D/WifiNative-HAL(  872): callSECApiInt - ID [210]
,D/StatusBar.NetworkController( 1187): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1187): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1187): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1187): applyOpen
D/StatusBar.NetworkController( 1187): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1187): applyOpen
D/HotspotTile( 1187): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/StatusBar.NetworkController( 1187): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-QSTileView( 1187): onStateChanged: Wi-Fi
D/StatusBar.NetworkController( 1187): applyOpen
D/StatusBar.NetworkController( 1187): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1187): applyOpen
D/STATUSBAR-WifiQuickSettingButton( 1187): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/SmartBondingService(  872): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1187): Wifi onReceive(3)
,D/WifiCredService( 1303): Action received :android.net.wifi.WIFI_STATE_CHANGED
,D/WifiConfigStore(  872): Loading config and enabling all networks 
,D/HotspotTile( 1187): onReceive : 3, 0
,D/SmartBondingService(  872): getNetworkEnabled : wifi : true mobile : true
,E/SignOutReceiver( 6233): WIFI_STATE_CHANGED_ACTION
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/WifiConfigStore(  872): Not a HS20
D/SecurityLogAgent( 6699): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6699): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6699): StateMachine : Current State = 1
D/SecurityLogAgent( 6699): StateMachine : Changed Current State = 1
,E/WifiConfigStore(  872): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/WifiNative-HAL(  872): callSECApiInt - ID [65]
,D/WifiNative-HAL(  872): callSECApiBoolean - ID [13]
I/wpa_supplicant( 6718): USE_NETWORK : USE_NETWORK ON
I/wpa_supplicant( 6718): wlan0: Setting scan request: 8 sec 0 usec
,I/wpa_supplicant( 6718): reset timer : RESET_TIMER 0
I/wpa_supplicant( 6718): P2P: Current p2p state = IDLE
I/wpa_supplicant( 6718): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 6718): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 6718): First Scan Start
,I/wpa_supplicant( 6718): Scan requested (ret=0) - scan timeout 30 seconds
,D/WifiNative-HAL(  872): Setting external_sim to 1
,D/WifiStateMachine(  872): Setting OUI to DA-A1-19
I/WifiNative-HAL(  872): startHal
E/wifi    (  872): getStaticLongField sWifiHalHandle 0x9bcff86c
D/wifi    (  872): halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0x502202
I/WifiNative-HAL(  872): Could not start hal
,E/native  (  872): do suspend true
,E/WifiStateMachine(  872): skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
D/WifiP2pService(  872): P2pDisabledState{ what=131203 }
,D/WifiScanningService(  872): SCAN_AVAILABLE : 3
D/RttService(  872): SCAN_AVAILABLE : 3
D/RttService(  872): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  284): Setting iface cfg
D/CommandListener(  284): Trying to bring up p2p0
D/WifiScanningService(  872): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  872): startHal
E/wifi    (  872): getStaticLongField sWifiHalHandle 0x9984f99c
D/wifi    (  872): halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0x4021fe
I/WifiNative-HAL(  872): Could not start hal
E/WifiScanningService(  872): could not start HAL
D/WifiMonitor(  872): startMonitoring(p2p0) with mConnected = true
,D/WifiP2pService(  872): P2pEnablingState
D/WifiP2pService(  872): P2pEnablingState{ what=147457 }
D/WifiP2pService(  872): P2p socket connection successful
D/WifiP2pService(  872): P2pEnabledState
,E/WifiStateMachine(  872): DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
D/WifiNative-HAL(  872): callSECStringApiVoid - ID [215]
D/WifiP2pService(  872): sending p2p connection changed broadcast: IDLE
E/WifiStateMachine(  872): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
E/WifiNative-HAL(  872): invaild command id : 215
,D/WifiDisplayController(  872): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
,D/WifiDisplayController(  872): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController(  872): disconnect
D/WifiDisplayController(  872): updateConnection
D/WifiDisplayController(  872): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayAdapter(  872): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6837): MountEmulatedStorage()
E/Zygote  ( 6837): v2
I/libpersona( 6837): KNOX_SDCARD checking this for 10192
I/libpersona( 6837): KNOX_SDCARD not a persona
,I/wpa_supplicant( 6718): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,I/ActivityManager(  872): Start proc com.samsung.shareshot for broadcast com.samsung.shareshot/.WifiDirectBroadcastReceiver: pid=6837 uid=10192 gids={50192, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/WifiP2pService(  872): create mNetworkAgent
D/WifiDisplayController(  872): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService(  872): Got NetworkAgent Messenger
D/ConnectivityService(  872): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService(  872): updateNetworkInfo()
D/ConnectivityService(  872): NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from null to UNKNOWN, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  872): NetworkAgent connected
E/CSLegacyTypeTracker(  872): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} } for legacy network type 13
,I/SELinux ( 6837): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,D/AllShareCastTile( 1187): action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,D/WifiDisplayAdapter(  872): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/SELinux ( 6837): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
D/AllShareCastTile( 1187): wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,E/SELinux ( 6837): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/wpa_supplicant( 6718): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,D/SecContentProvider2(  872): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  872): mCursor = null
,D/SecContentProvider2(  872): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  872): mCursor = null
,D/WifiNative-HAL(  872): p2pGetDeviceAddress
,D/WifiNative-HAL(  872): p2pGetDeviceAddress returning ea:50:8b:de:28:a3
D/WifiP2pService(  872): DeviceAddress: ea:28:a3
,D/WifiDisplayController(  872): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Note3-1
D/WifiDisplayController(  872):  deviceAddress: ea:50:8b:de:28:a3
D/WifiDisplayController(  872):  primary type: 10-0050F204-5
D/WifiDisplayController(  872):  secondary type: null
D/WifiDisplayController(  872):  wps: 0
D/WifiDisplayController(  872):  grpcapab: 0
D/WifiDisplayController(  872):  devcapab: 0
D/WifiDisplayController(  872):  status: 3
D/WifiDisplayController(  872):  wfdInfo: null
D/WifiDisplayController(  872):  groupownerAddress: null
D/WifiDisplayController(  872):  GOdeviceName: null
D/WifiDisplayController(  872):  interfaceAddress: 
D/WifiDisplayController(  872):  SConnectInfo : null
,D/TimaKeyStoreProvider( 6837): TimaSignature is unavailable
,D/ActivityThread( 6837): Added TimaKeyStore provider
,D/WifiP2pService(  872): sending p2p persistent groups changed broadcast
,D/WifiP2pService(  872): InactiveState
,D/WifiP2pService(  872): InactiveState{ what=143376 }
D/WifiP2pService(  872): P2pEnabledState{ what=143376 }
,I/wpa_supplicant( 6718): p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,E/ConnectivityService(  872): updateNetworkInfo()
D/ConnectivityService(  872): ignoring duplicate network state non-change. WIFI_P2P, state = UNKNOWN
,D/WifiP2pService(  872): InactiveState{ what=143376 }
D/WifiP2pService(  872): P2pEnabledState{ what=143376 }
,D/ResourcesManager( 6837): creating new AssetManager and set to /system/app/ShareShotService/ShareShotService.apk
,D/WifiDirectBR( 6837): WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.STATE_CHANGED
,I/ActivityManager(  872): Killing 5896:com.google.android.partnersetup/u0a19 (adj 15): bgCount ##41
,D/NearbySettings( 1303): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,V/NearbySettings( 1303): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1303): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/ConnectivityService(  872): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1303): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1303): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1303): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1303): MountReceiver.mPrefHandler - 7002
,D/FileShare-Server( 6428): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,D/WifiDirectBR( 6837): WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,D/WifiDirectBR( 6837): WifiDirectBroadcastReceiver::onReceive(), Action : WifiP2pManager.WIFI_P2P_CONNECTION_CHANGED_ACTION, isConnected() == false
,W/ContextImpl( 6837): Implicit intents with startService are not safe: Intent { act=com.samsung.shareshot.IShareShotService } android.content.ContextWrapper.stopService:538 android.content.ContextWrapper.stopService:538 com.samsung.shareshot.WifiDirectBroadcastReceiver.onReceive:59 
,D/WifiDirectBR( 6837): stopServiceTest : false
,I/wpa_supplicant( 6718): nl80211: Received scan results (6 BSSes)
,I/wpa_supplicant( 6718): wlan0: Setting scan request: 8 sec 0 usec
,I/wpa_supplicant( 6718): Trying to associate with C0.AA.4A (SSID='4E473730303567' freq=5220 MHz)
,I/wpa_supplicant( 6718): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 6718): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E473730303567
,D/SecContentProvider2(  872): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  872): mCursor = null
,I/wpa_supplicant( 6718): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 6718): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E473730303567
I/wpa_supplicant( 6718): Associated with C0.AA.4A
,D/SecContentProvider2(  872): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  872): mCursor = null
,I/wpa_supplicant( 6718): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 6718): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.4A SSID=4E473730303567
,D/SecContentProvider2(  872): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  872): mCursor = null
,I/wpa_supplicant( 6718): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 6718): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 6718): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.4A SSID=4E473730303567
,I/wpa_supplicant( 6718): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 6718): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 6718): CTRL-EVENT-CONNECTED - Connection to C0.AA.4A completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 6718): Blacklist: Clear (temp) 
I/wpa_supplicant( 6718): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.4A SSID=4E473730303567
,D/WifiNative-HAL(  872): callSECApiVoid - ID [50]
,D/ConnectivityService(  872): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService(  872): Got NetworkAgent Messenger
D/ConnectivityService(  872): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService(  872): updateNetworkInfo()
E/WifiConfigStore(  872): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  872): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  872): NetworkAgent connected
,D/StatusBar.NetworkController( 1187): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1187): onWifiSignalChanged enabled=true enabledDesc:null
,E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
,E/WifiConfigStore(  872): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  284): Setting iface cfg
,E/Zygote  ( 6855): MountEmulatedStorage()
E/Zygote  ( 6855): v2
I/libpersona( 6855): KNOX_SDCARD checking this for 10038
I/libpersona( 6855): KNOX_SDCARD not a persona
,I/ActivityManager(  872): Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.samsung.myplace.WIFINotificationHandler: pid=6855 uid=10038 gids={50038, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,E/WifiStateMachine(  872): Start Dhcp Watchdog 1
,D/SecContentProvider2(  872): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  872): mCursor = null
,D/ConnectivityService(  872): Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=false
,D/SecContentProvider2(  872): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  872): mCursor = null
,I/art     (  330): Explicit concurrent mark sweep GC freed 8776(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 305us total 13.364ms
,I/art     (  330): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 271us total 9.876ms
,I/SELinux ( 6855): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,D/StatusBar.NetworkController( 1187): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1187): onWifiSignalChanged enabled=true enabledDesc:null
,I/SELinux ( 6855): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6855): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/art     (  330): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 275us total 10.266ms
,D/TimaKeyStoreProvider( 6855): TimaSignature is unavailable
,D/ActivityThread( 6855): Added TimaKeyStore provider
,D/ResourcesManager( 6855): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,W/ResourcesManager( 6855): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,E/native  (  872): do suspend false
,D/WifiP2pService(  872): InactiveState{ what=143375 }
,D/WifiP2pService(  872): P2pEnabledState{ what=143375 }
,I/VlingoApplication( 6855): VlingoApplication appVersion ='11.2.2.0.37649', ro.csc.sales_code=XEO
,E/Watchdog(  872): !@Sync 5
,E/BluetoothHeadset( 6855): BTStateChangeCB is registed
,E/BluetoothHeadset( 6855): BluetoothHeadset service is binded
,I/ActivityManager(  872): Killing 5915:com.samsung.groupcast/u0a20 (adj 15): bgCount ##41
,I/Hs20UtilService( 1303): Starting #2,
,E/dhcpcd  ( 6876): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/Hs20UtilService( 1303): Message received 5007
,I/dhcpcd  ( 6876): version 5.5.6 starting
D/NearbySettings( 1303): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1303): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1303): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/ConnectivityService(  872): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1303): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1303): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1303): MountReceiver.onReceive - Set preference state off
E/dhcpcd  ( 6876): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,V/NearbySettings( 1303): MountReceiver.mPrefHandler - 7002
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6233): NETWORK_STATE_CHANGED_ACTION
,D/SettingsProvider(  872): name = driving_mode_on
,D/SettingsProvider(  872): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  872): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  872): selectionArgs: false
,D/SettingsProvider(  872): selectionArgs: 10038
D/SecContentProvider(  872): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider(  872): ret = -1
,D/BluetoothManager( 6855): [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.media.ACTION_SCO_AUDIO_STATE_UPDATED
,I/dhcpcd  ( 6876): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 6876): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 6876): if(wlan0) info get Success. (MAC : C0.AA.4A)
,I/dhcpcd  ( 6876): bssid match
,I/dhcpcd  ( 6876): wlan0: rebinding lease of 192.168.1.128
,I/dhcpcd  ( 6876): wlan0: acknowledged 192.168.1.128 from 192.168.1.1
,I/dhcpcd  ( 6876): wlan0: leased 192.168.1.128 for 86400 seconds
,D/ConnectivityService(  872): Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=false
,E/SMD     (  290): DCD ON
,E/native  (  872): do suspend true
,D/WifiP2pService(  872): InactiveState{ what=143375 }
,D/WifiP2pService(  872): P2pEnabledState{ what=143375 }
,D/ConnectivityService(  872): Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=false
,D/StatusBar.NetworkController( 1187): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1187): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine(  872): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG7005g"WPA_PSK
E/WifiStateMachine(  872): VerifyingLinkState enter
,D/WifiNative-HAL(  872): callSECApiInt - ID [210]
,E/ConnectivityService(  872): updateNetworkInfo()
,D/WifiWatchdogStateMachine(  872): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger(  872): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.DnsResolver(  872): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.SingDnsChecker(  872): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver(  872): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService(  872): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService(  872): Adding iface wlan0 to network 502
,D/StatusBar.NetworkController( 1187): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1187): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine(  872): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
I/WifiTrafficPoller(  872): evaluateTrafficStatsPolling
D/StatusBar.NetworkController( 1187): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1187): onWifiSignalChanged enabled=true enabledDesc:null
,I/Hs20UtilService( 1303): Starting #3
,I/Hs20UtilService( 1303): Message received 5007
,I/WifiTrafficPoller(  872): evaluateTrafficStatsPolling
I/WifiTrafficPoller(  872): mBoosterFLAG : 0
I/WifiTrafficPoller(  872): current booster mode : FullMode
D/WifiNative-HAL(  872): callSECApiVoid - ID [212]
,D/StatusBar.NetworkController( 1187): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG7005g"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG7005g"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014a/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1187): onWifiSignalChanged enabled=true enabledDesc:"NG7005g"
D/StatusBar.NetworkController( 1187): refreshSignalCluster - setNWBoosterIndicators(false)
,D/NearbySettings( 1303): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1303): MountReceiver.onReceive - Keep current state
,D/StatusBar.NetworkController( 1187): applyOpen
,D/StatusBar.NetworkController( 1187): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1187): applyOpen
D/StatusBar.NetworkController( 1187): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1187): applyOpen
,D/StatusBar.NetworkController( 1187): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1187): applyOpen
E/WifiStateMachine(  872): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/ConnectivityService(  872): Adding Route [fe80::/64 -> :: wlan0] to network 502
,D/ConnectivityService(  872): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 502
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 502
,E/ConnectivityService(  872): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  872): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  872): updateSourceRoutes : add src route for:192.168.1.128
,V/        (  284): QcRouteController
,E/SignOutReceiver( 6233): NETWORK_STATE_CHANGED_ACTION
,V/        (  284): QcRouteController
,I/Hs20UtilService( 1303): Starting #4
,I/Hs20UtilService( 1303): Message received 5007
,D/NearbySettings( 1303): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1303): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1303): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1303): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1303): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1303): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1303): MountReceiver.mPrefHandler - 7002
,V/        (  284): QcRouteController
,V/        (  284): QcRouteController
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6233): NETWORK_STATE_CHANGED_ACTION
,V/        (  284): QcRouteController
,I/Hs20UtilService( 1303): Starting #5
,I/Hs20UtilService( 1303): Message received 5007
,D/NearbySettings( 1303): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1303): MountReceiver.onReceive - Keep current state
,D/WifiStateMachine(  872): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,V/        (  284): QcRouteController
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6233): NETWORK_STATE_CHANGED_ACTION
,V/        (  284): QcRouteController
,V/        (  284): QcRouteController
,I/SurfaceFlinger(  254): id=14 createSurf (1x1),1 flag=4, Uoast
,V/        (  284): QcRouteController
,D/PowerManagerService(  872): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=872
,D/ConnectivityService(  872): Setting Dns servers for network 502 to [/192.168.1.1]
,D/ConnectivityService(  872): LTETest block dns file not exists
,V/Nat464Xlat(  872): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  872): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  872): calling update connectivity
,D/ConnectivityService(  872): ignoring duplicate network state non-change. WIFI, state = CONNECTING
D/EntConnectivity(  872): Not allowed due to - mEnabled false
,E/ConnectivityService(  872): updateNetworkInfo()
,D/ConnectivityService(  872): ignoring duplicate network state non-change. WIFI, state = CONNECTING
E/ConnectivityService(  872): updateNetworkInfo()
D/ConnectivityService(  872): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  872): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityService(  872): calling update connectivity
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  872): DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  872): Connected
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  872): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  872): rematching NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  872):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  872): Checking http://clients3.google.com/generate_204 on "NG7005g"
D/ConnectivityService(  872):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  872):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  872): currentScore = 0, newScore = 60
,D/ConnectivityService(  872):    accepting network in place of null
D/ConnectivityService(  872): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/System.out(  872): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out(  872): (HTTPLog)-Static: isShipBuild true
I/System.out(  872): (HTTPLog)-Thread-180-262660443: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out(  872): (HTTPLog)-Static: isSBSettingEnabled false
,D/TelephonyNetworkFactory( 1440): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  872): Setting tx/rx TCP buffers to 524288,1048576,4525824,524288,1048576,4525824
,E/CSLegacyTypeTracker(  872): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  872): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=true
,D/ConnectivityService(  872): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,V/NetworkStats(  872): updateIfacesLocked()
V/NetworkStats(  872): performPollLocked(flags=0x1)
,D/NetworkStatsFactory(  872): UpdateStatsForKnox
D/NtpTrustedTime(  872): forceRefresh() from cache miss
,D/Tethering(  872): MasterInitialState.processMessage what=3
D/SmartBondingService(  872): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService(  872): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  872): getSBEnabled() enabled =false
D/SmartBondingService(  872): getSBEnabled() enabled =false
D/SmartBondingService(  872): getSBEnabled() enabled =false
,D/ConnectivityService(  872): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  872): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/NtpTrustedTime(  872): forceRefresh Fail.
D/ConnectivityService(  872): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,V/NetworkStats(  872): performPollLocked() took 5ms
D/SmartBondingService(  872): getNetworkEnabled : wifi : true mobile : true
,D/NtpTrustedTime(  872): forceRefresh() from cache miss
,D/NtpTrustedTime(  872): forceRefresh Fail.
V/NetworkStats(  872): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/EntConnectivity(  872): Not allowed due to - mEnabled false
D/ConnectivityService(  872): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  872): calling update connectivity
D/ConnectivityService(  872):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  872):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  872): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1187): CM callback handler got msg 524290
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1187): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1187): updateDataNetType()
D/StatusBar.NetworkController( 1187): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1187): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1187): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1187): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1187): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1187): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG7005g"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG7005g"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014a/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1187): onWifiSignalChanged enabled=true enabledDesc:"NG7005g"
,D/StatusBar.NetworkController( 1187): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1187): applyOpen
D/StatusBar.NetworkController( 1187): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1187): applyOpen
D/StatusBar.NetworkController( 1187): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1187): applyOpen
D/StatusBar.NetworkController( 1187): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1187): applyOpen
,I/System.out(  872): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  872): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 10 Dec 2015 11:58:08 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449748688668], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449748688651]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  872): Don't send network conditions - lacking user consent.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  872): Validated
D/ConnectivityService(  872): Validated NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  872): rematching NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  872):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  872):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  872): Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
D/ConnectivityService(  872): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  872): calling update connectivity
,D/ConnectivityService(  872):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  872):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  872): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  872): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1187): CM callback handler got msg 524290
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1187): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1187): updateDataNetType()
D/StatusBar.NetworkController( 1187): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1187): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1187): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1187): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1187): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1187): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG7005g"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG7005g"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014a/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1187): onWifiSignalChanged enabled=true enabledDesc:"NG7005g"
,D/ConnectivityService(  872): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  872): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  872): SmartBondingReceiver: wifi is connected
D/SmartBondingService(  872): SmartBondingReceiver: wifi ap is changed, init speed ratio
D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  872): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  872): getSBEnabled() enabled =false
D/SmartBondingService(  872): getSBEnabled() enabled =false
D/SmartBondingService(  872): getSBEnabled() enabled =false
D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/NtpTrustedTime(  872): forceRefresh() from cache miss
D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/NtpTrustedTime(  872): forceRefresh Fail.
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1886): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.ai.onReceive:-1 
W/ContextImpl( 1886): Implicit intents with startService are not safe: Intent { act=com.samsung.SMT.UpdateManager.UPDATE_DATA } android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  872): getNetworkEnabled : wifi : true mobile : true
I/DBG_DM  ( 3161): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 3161): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 5126): type=WIFI subType= reason=null isConnected=true
,I/DBG_DM  ( 3161): [com.wssyncmldm.llllIIIllIlIIIIllllI(263/onReceive)] ----------- XEVENT_DM_INIT WIFI ok
,I/PCWCLIENTTRACE_PushUtil( 5933): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5933): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5933): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5933): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3161): [llIlIIIIlllIlllllIll(224/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 3161): [IIllIIllIIIlllIlIIll(403/llllllIllIlIlllIIlIl)] Check completed.
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3161): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/DBG_DM  ( 3161): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,E/Zygote  ( 6955): MountEmulatedStorage()
E/Zygote  ( 6955): v2
I/libpersona( 6955): KNOX_SDCARD checking this for 10004
I/libpersona( 6955): KNOX_SDCARD not a persona
,I/ActivityManager(  872): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6955 uid=10004 gids={50004, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/DBG_DM  ( 3161): [com.wssyncmldm.XDMService(809/llIlIIIIlIIIIIlIlIII)] TopActivity : com.test.thalitest.MainActivity
,I/DBG_DM  ( 3161): [IIIlllIlIIlllIIIIllI(73/llllIIIllIlIIIIllllI)] 
,I/SELinux ( 6955): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6955): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6955): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6955): TimaSignature is unavailable
,D/ActivityThread( 6955): Added TimaKeyStore provider
,I/DBG_DM  ( 3161): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,I/DBG_DM  ( 3161): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 8
,D/ResourcesManager( 6955): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/DBG_DM  ( 3161): [com.wssyncmldm.db.file.XDB(6055/IIIlIllIlIIIIIlIIIll)] Initiated Type: 2
,I/DBG_DM  ( 3161): [IIllIIllIIIlllIlIIll(102/lllIlIlIIIllIIlIllIl)] nStatus [220]
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3161): [IIllIIllIIIlllIlIIll(177/lllIlIlIIIllIIlIllIl)] nDownloadPostpone is [8]
,E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
,D/ConnectivityService(  872): Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=true
,D/ConnectivityService(  872): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,fe80::ea50:8bff:fede:28a3/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService(  872): identical MTU - not setting
D/ConnectivityService(  872): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  872): updateSourceRoutes : add src route for:fe80::ea50:8bff:fede:28a3
,V/        (  284): QcRouteController
,E/Zygote  ( 6978): MountEmulatedStorage()
E/Zygote  ( 6978): v2
I/libpersona( 6978): KNOX_SDCARD checking this for 10104
I/libpersona( 6978): KNOX_SDCARD not a persona
,V/        (  284): QcRouteController
,W/NetworkManagementService(  872): route cmd failed: 
W/NetworkManagementService(  872): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '54 route replace src v6 wlan0 fe80::ea50:8bff:fede:28a3 2 ::' failed with '400 54 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService(  872): '
W/NetworkManagementService(  872): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:444)
W/NetworkManagementService(  872): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:377)
W/NetworkManagementService(  872): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:342)
W/NetworkManagementService(  872): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:327)
W/NetworkManagementService(  872): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService(  872): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5625)
W/NetworkManagementService(  872): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5437)
W/NetworkManagementService(  872): 	at com.android.server.ConnectivityService.access$2300(ConnectivityService.java:229)
W/NetworkManagementService(  872): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2382)
W/NetworkManagementService(  872): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  872): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService(  872): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/Nat464Xlat(  872): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  872): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  872): calling update connectivity
D/ConnectivityService(  872):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  872):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  872): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  872): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  872): calling update connectivity
D/ConnectivityService(  872):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  872):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  872): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
I/ActivityManager(  872): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=6978 uid=10104 gids={50104, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/SmartBondingService(  872): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  872): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  872): getSBEnabled() enabled =false
D/SmartBondingService(  872): getSBEnabled() enabled =false
D/SmartBondingService(  872): getSBEnabled() enabled =false
D/ConnectivityManager.CallbackHandler( 1187): CM callback handler got msg 524295
I/SELinux ( 6978): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
D/ConnectivityManager.CallbackHandler( 1187): CM callback handler got msg 524295
I/SELinux ( 6978): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6978): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
V/GLSActivity( 1397): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GpsLocationProvider(  872): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/DBG_DM  ( 3161): [com.wssyncmldm.db.file.XDB(5276/IIIIIlIlIlIllIlIIllI)] Set Download Postpone status : 0
I/DBG_DM  ( 3161): [IIllIlIIlIlllIIllIII(741/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_START
I/DBG_DM  ( 3161): [com.wssyncmldm.IIIIllIlIIlIIIIlllIl(1273/handleMessage)] event ->220
I/VacuumService( 1397): Vacuum at: now=1449748689376 tag=VacuumService
I/DBG_DM  ( 3161): [llIlIIIIlllIlllllIll(280/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT : Initialized
I/DBG_DM  ( 3161): [llIlIIIIlllIlllllIll(1907/lllIlIlIIIllIIlIllIl)] 
I/DBG_DM  ( 3161): [com.wssyncmldm.XDMService(809/llIlIIIIlIIIIIlIlIII)] TopActivity : com.test.thalitest.MainActivity
I/DBG_DM  ( 3161): [com.wssyncmldm.XDMService(876/IIIIllIlIIlIIIIlllIl)] 
D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/DBG_DM  ( 3161): [com.wssyncmldm.db.file.XDB(4994/IIIlllIlIIlllIIIIllI)] Get Autoinstall status : false
D/TimaKeyStoreProvider( 6978): TimaSignature is unavailable
D/ActivityThread( 6978): Added TimaKeyStore provider
I/DBG_DM  ( 3161): [com.wssyncmldm.XDMBroadcastReceiver(332/llIIIIlllllIIllIIllI)] m_IsSavedNfcMode : false
D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/DBG_DM  ( 3161): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(501/lllIlIlIIIllIIlIllIl)] Get bUpdateReport = false
I/DBG_DM  ( 3161): [IIllIlIIlIlllIIllIII(695/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_CONFIRM
I/DBG_DM  ( 3161): [com.wssyncmldm.XDMService(638/llllIIIllIlIIIIllllI)] 
D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/DBG_DM  ( 3161): [com.wssyncmldm.XDMService(646/llllIIIllIlIIIIllllI)] didn't register
E/DBG_DM  ( 3161): [com.wssyncmldm.XDMService(647/llllIIIllIlIIIIllllI)] java.lang.IllegalArgumentException: Receiver not registered: com.wssyncmldm.llIIIIlllllIIllIIllI@733d348
,D/ResourcesManager( 6978): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
I/DBG_DM  ( 3161): [com.wssyncmldm.XDMService(819/IllIlIIIIlIIlIIIllIl)] Idle Screen : false
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/Zygote  ( 7001): MountEmulatedStorage()
E/Zygote  ( 7001): v2
I/libpersona( 7001): KNOX_SDCARD checking this for 1000
I/libpersona( 7001): KNOX_SDCARD not a persona
,I/ActivityManager(  872): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7001 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/ActivityThread( 1748): Failed to find provider info for com.android.contacts.metadata
,I/SELinux ( 7001): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7001): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7001): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/DBG_DM  ( 3161): [com.wssyncmldm.ui.llIlIllIIIlIIlllIlII(325/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,E/GpsLocationProvider(  872): No APN found to select.
,D/TimaKeyStoreProvider( 7001): TimaSignature is unavailable
,D/ActivityThread( 7001): Added TimaKeyStore provider
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3161): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 7001): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,D/SyncManager(  872): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 19859, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager(  872): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 199364, reason: UserStart
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  872): uri = 14 selection = getSealedState
,D/SecContentProvider2(  872): mCursor = null
,V/GLSActivity( 1397): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ApplicationPolicy(  872): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,V/ApplicationPolicy(  872): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,D/WindowManager(  872): showStatusBarByNotification() mOpenByNotification=false
,I/DBG_DM  ( 3161): [com.wssyncmldm.ui.XUIFotaPostponeActivity(329/lllIlIlIIIllIIlIllIl)] 
,D/ResourcesManager( 1187): creating new AssetManager and set to /system/priv-app/SyncmlDM/SyncmlDM.apk
,I/DIAGMON_AGENT( 7001): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,I/DBG_DM  ( 3161): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,D/KnoxNotification( 1187): ----- inflateViews : modified publicViewLocal -----
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  872): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  872): mCursor = null
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/KnoxNotification( 1187): ----- inflateViews : modified KnoxViewLocal -----
,E/Auth.Api.Credentials( 1748): [CredentialSyncAdapter] Unknown sync event.
,I/DIAGMON_AGENT( 7001): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,D/PersonaManager( 1187): PersonaID is invalid or persona doesn't exists. : 0
,D/PhoneStatusBar( 1187): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@3cb291a3
D/PersonaManager( 1187): isKioskContainerExistOnDevice
D/PersonaManager( 1187): isKioskContainerExistOnDevice
,D/PanelView( 1187): There is/are notification(s) 
,D/PanelView( 1187): There is/are notification(s) 
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3161): [com.wssyncmldm.db.file.XDB(5276/IIIIIlIlIlIllIlIIllI)] Set Download Postpone status : 8
,I/DBG_DM  ( 3161): [com.wssyncmldm.ui.XUIFotaPostponeActivity(378/lllIlIlIIIllIIlIllIl)] No idle Postpone
,I/DBG_DM  ( 3161): [com.wssyncmldm.ui.XUIFotaPostponeActivity(466/llIIIIlllllIIllIIllI)] 
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/DelayedSyncController( 6978): Delaying sync.
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  872): Killing 4175:com.sec.android.app.shealth/u0a40 (adj 15): bgCount ##41
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DIAGMON_AGENT( 7001): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 7001): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 7001): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7001): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7028): MountEmulatedStorage()
,E/Zygote  ( 7028): v2
I/libpersona( 7028): KNOX_SDCARD checking this for 10014
I/libpersona( 7028): KNOX_SDCARD not a persona
,I/ActivityManager(  872): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=7028 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7028): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,D/ConnectivityService(  872): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  872): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
D/ConnectivityService(  872): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  872): apparently satisfied.  currentScore=60
,D/ConnectivityService(  872): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/SELinux ( 7028): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7028): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/ConnectivityManager.CallbackHandler( 1748): CM callback handler got msg 524290
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/TimaKeyStoreProvider( 7028): TimaSignature is unavailable
,D/ActivityThread( 7028): Added TimaKeyStore provider
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PicasaService( 5217): start picasa sync
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PicasaService( 5217): end picasa sync
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 7028): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PackageManager(  872): [MSG] WRITE_PACKAGE_RESTRICTIONS
,I/PhenotypeConfigurator( 1397): Scheduling Phenotype for one-off execution 6651 seconds from now (1449748690101)
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/DelayedSyncController( 6978): Delaying sync.
,D/GetConfigurationSnapshotOperation( 1397): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/FOTA_Client( 7028): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7028): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/PhenotypeFlagCommitter( 1397): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1397): Using platform SSLCertificateSocketFactory
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/FOTA_Client( 7028): [lIIIIlIlIlIlllllllll(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7056): MountEmulatedStorage()
I/libpersona( 7056): KNOX_SDCARD checking this for 10023
E/Zygote  ( 7056): v2
I/libpersona( 7056): KNOX_SDCARD not a persona
,I/ActivityManager(  872): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=7056 uid=10023 gids={50023, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 7056): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7056): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7056): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/DriveInitializer( 1748): Awaiting to be initialized
,W/DriveInitializer( 1748): Background init thread started
,D/TimaKeyStoreProvider( 7056): TimaSignature is unavailable
,D/ActivityThread( 7056): Added TimaKeyStore provider
,D/ResourcesManager( 7056): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 1748): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.511: ( 7056): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.511: ( 7056): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1449748690337
,I/KLMS-2.4.511: ( 7056): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  872): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.511: ( 7056): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.511: ( 7056): StateImplV2(): networkChangeListener().START
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.511: ( 7056): NetworkChangeOperations(): uploadRequestLog().START 
,W/DriveInitializer( 1748): Background init thread ended
,I/ActivityManager(  872): Killing 5967:com.policydm/1000 (adj 15): bgCount ##41
,I/KLMS-2.4.511: ( 7056): StateImplV2(): networkChangeListener().END
,E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7086): MountEmulatedStorage()
E/Zygote  ( 7086): v2
I/libpersona( 7086): KNOX_SDCARD checking this for 10036
I/libpersona( 7086): KNOX_SDCARD not a persona
,I/ActivityManager(  872): Start proc com.samsung.android.app.pinboard:tagService for broadcast com.samsung.android.app.pinboard/.service.TagReadyReceiver: pid=7086 uid=10036 gids={50036, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  872): Killing 4703:com.sec.spp.push/u0a43 (adj 15): bgCount ##41
,I/SELinux ( 7086): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7086): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7086): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/LocationManagerService(  872): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/TimaKeyStoreProvider( 7086): TimaSignature is unavailable
,D/ActivityThread( 7086): Added TimaKeyStore provider
,E/bt-btif ( 6717): ...preload_wait_timeout (retried:0/max-retry:1)...
,D/bt_userial( 6717): RX termination
W/bt_userial( 6717): select_read return size <=0:-1, exiting userial_read_thread
D/bt_userial( 6717): Leaving userial_read_thread()
D/bt_vendor( 6717): op for 4
I/bt_userial_vendor( 6717): device fd = 65 close
,D/ResourcesManager( 7086): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,W/ResourcesManager( 7086): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7086): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  872): Killing 5992:com.samsung.android.sdk.samsunglink/u0a48 (adj 15): bgCount ##41
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Minikin ( 7086): addFont failed to create font /system/fonts/SamsungSans-light.ttf
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/bt_vendor( 6717): op for 0
,D/bt_upio ( 6717): upio_set_bluetooth_power(on: 0)
D/bt_upio ( 6717): is_emulator_context : 0
,D/bt_upio ( 6717): is_rfkill_disabled ? [0]
,I/ActivityManager(  872): Killing 6024:com.osp.app.signin/u0a50 (adj 15): bgCount ##41
,D/bt_vendor( 6717): cleanup
,E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7102): MountEmulatedStorage()
,E/Zygote  ( 7102): v2
I/libpersona( 7102): KNOX_SDCARD checking this for 10042
I/libpersona( 7102): KNOX_SDCARD not a persona
,I/ActivityManager(  872): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7102 uid=10042 gids={50042, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 7102): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7102): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7102): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/TimaKeyStoreProvider( 7102): TimaSignature is unavailable
,D/ActivityThread( 7102): Added TimaKeyStore provider
,I/bt_hci_bdroid( 6717): init
,I/bt_vendor( 6717): init
,I/bt_vnd_conf( 6717): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 6717): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial( 6717): userial_init
D/bt_vendor( 6717): op for 5
,D/bt_vendor( 6717): op for 0
,D/bt_upio ( 6717): upio_set_bluetooth_power(on: 0)
D/bt_upio ( 6717): is_emulator_context : 0
D/bt_upio ( 6717): is_rfkill_disabled ? [0]
D/bt_upio ( 6717): is_rfkill_disabled ? [0]
D/bt_vendor( 6717): op for 0
,D/bt_upio ( 6717): upio_set_bluetooth_power(on: 1)
D/bt_upio ( 6717): is_emulator_context : 0
D/bt_upio ( 6717): is_rfkill_disabled ? [0]
,D/bt_vendor( 6717): op for 3
,I/bt_userial_vendor( 6717): userial vendor open: opening /dev/ttyHS0
,I/bt_userial_vendor( 6717): userial_vendor_open():UART is setup
,I/bt_userial_vendor( 6717): device fd = 65 open
D/bt_vendor( 6717): op for 1
D/bt_userial( 6717): Entering userial_read_thread()
E/bt_hwcfg( 6717): Start CFG HW, HCI reset
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out( 1397): (HTTPLog)-Static: isSBSettingEnabled false
,D/ResourcesManager( 7102): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  872): Killing 6083:com.sec.android.app.soundalive/u0a64 (adj 15): bgCount ##41
,I/SO_AGENT( 7102): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,E/bt_hwcfg( 6717): Read Local Name after HCI reset
,E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
,I/System.out( 1397): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1397): Tagging socket 74 with tag 1000120100000000{268440065,0} uid -1, pid: 1397, getuid(): 10015
,D/bt_hwcfg( 6717): Chipset BCM4335C0
D/bt_hwcfg( 6717): Target name = [BCM4335C0]
,I/bt_hwcfg( 6717): module_type[semco].
I/bt_hwcfg( 6717): not ZERO...
I/bt_hwcfg( 6717): module_type[semco] is invalid.
,E/bt_hwcfg( 6717): patchram path ORG . BCM4335C0
E/bt_hwcfg( 6717): patchram path ORG .. BCM4335C0
E/bt_hwcfg( 6717): patchram path ORG bcm2079xB4_firmware.ncd BCM4335C0
E/bt_hwcfg( 6717): patchram path ORG bcm2079xB4_pre_firmware.ncd BCM4335C0
E/bt_hwcfg( 6717): patchram path ORG bcm2079xB5_firmware.ncd BCM4335C0
E/bt_hwcfg( 6717): patchram path ORG bcm2079xB5_pre_firmware.ncd BCM4335C0
E/bt_hwcfg( 6717): patchram path ORG bcm4335_V0093.0399.hcd BCM4335C0
E/bt_hwcfg( 6717): patchram path ORG bcm4335_V0093.0399_wisol.hcd BCM4335C0
E/bt_hwcfg( 6717): fw ver (org)0.0
E/bt_hwcfg( 6717): vendor lib preload failed to locate firmware patch file
E/bt_hwcfg( 6717): Remove module rev, try again BCM4335
D/bt_hwcfg( 6717): Target name = [BCM4335]
I/bt_hwcfg( 6717): module_type[semco].
I/bt_hwcfg( 6717): not ZERO...
I/bt_hwcfg( 6717): module_type[semco] is invalid.
E/bt_hwcfg( 6717): patchram path ORG . BCM4335
E/bt_hwcfg( 6717): patchram path ORG .. BCM4335
E/bt_hwcfg( 6717): patchram path ORG bcm2079xB4_firmware.ncd BCM4335
E/bt_hwcfg( 6717): patchram path ORG bcm2079xB4_pre_firmware.ncd BCM4335
E/bt_hwcfg( 6717): patchram path ORG bcm2079xB5_firmware.ncd BCM4335
E/bt_hwcfg( 6717): patchram path ORG bcm2079xB5_pre_firmware.ncd BCM4335
E/bt_hwcfg( 6717): patchram path ORG bcm4335_V0093.0399.hcd BCM4335
I/bt_hwcfg( 6717): patch(org) : bcm4335_V0093.0399.hcd
I/bt_hwcfg( 6717): Found patchfile: /vendor/firmware/bcm4335_V0093.0399.hcd
E/bt_hwcfg( 6717): ORG patchram base 0093
E/bt_hwcfg( 6717): ORG patchram minor 0399
E/bt_hwcfg( 6717): fw ver (org)93.399
E/bt_hwcfg( 6717): Final Patchram is /vendor/firmware/bcm4335_V0093.0399.hcd
,I/bt_hwcfg( 6717): Axi patch failure or not include AXI patching
,I/bt_hwcfg( 6717): bt vendor lib: set UART baud 3000000
,E/Zygote  ( 7125): MountEmulatedStorage()
E/Zygote  ( 7125): v2
I/libpersona( 7125): KNOX_SDCARD checking this for 1000
I/libpersona( 7125): KNOX_SDCARD not a persona
,I/qtaguid ( 1397): Tagging socket 78 with tag 1000120100000000{268440065,0} uid -1, pid: 1397, getuid(): 10015
,I/ActivityManager(  872): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=7125 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  872): Killing 4982:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##41
,I/jxcore-log( 6606): Test app app.js loaded
I/jxcore-log( 6606): 
,I/SELinux ( 7125): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7125): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7125): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/chromium( 6606): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/TimaKeyStoreProvider( 7125): TimaSignature is unavailable
,D/ActivityThread( 7125): Added TimaKeyStore provider
,I/chromium( 6606): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/ResourcesManager( 7125): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7145): MountEmulatedStorage()
E/Zygote  ( 7145): v2
I/libpersona( 7145): KNOX_SDCARD checking this for 10043
I/libpersona( 7145): KNOX_SDCARD not a persona
,E/SMD     (  290): DCD ON
,I/ActivityManager(  872): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7145 uid=10043 gids={50043, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  872): Killing 6131:com.wsomacp/u0a29 (adj 15): bgCount ##41
,I/SELinux ( 7145): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7145): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7145): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/dhcpcd  ( 6876): wlan0: sending IPv6 Router Solicitation
,D/LocationManagerService(  872): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/TimaKeyStoreProvider( 7145): TimaSignature is unavailable
,D/ActivityThread( 7145): Added TimaKeyStore provider
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 7145): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out( 1397): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 1397): Tagging socket 74 with tag 1000120100000000{268440065,0} uid -1, pid: 1397, getuid(): 10015
,E/SPPClientService( 7145): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 7145): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 7145): PushLog.txt file is not deleted.
,D/SPPClientService( 7145): PushLog.txt file is not deleted.
D/SPPClientService( 7145): ============PushLog. stop!
,E/SPPClientService( 7145): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
,D/LocationManagerService(  872): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,E/Zygote  ( 7163): MountEmulatedStorage()
I/libpersona( 7163): KNOX_SDCARD checking this for 10050
E/Zygote  ( 7163): v2
I/libpersona( 7163): KNOX_SDCARD not a persona
,I/ActivityManager(  872): Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7163 uid=10050 gids={50050, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  872): Killing 6115:com.google.android.apps.docs/u0a112 (adj 15): bgCount ##41
,D/SSRM:n  (  872): SIOP:: AP = 390, PST = 333, CUR = 450
,I/SELinux ( 7163): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SELinux ( 7163): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7163): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/art     (  872): Explicit concurrent mark sweep GC freed 104105(5MB) AllocSpace objects, 9(144KB) LOS objects, 17% free, 37MB/45MB, paused 1.804ms total 131.655ms
,D/TimaKeyStoreProvider( 7163): TimaSignature is unavailable
,D/ActivityThread( 7163): Added TimaKeyStore provider
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out( 1397): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1397): Tagging socket 74 with tag 1000120100000000{268440065,0} uid -1, pid: 1397, getuid(): 10015
,D/ResourcesManager( 7163): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,I/SA      ( 7163): [SSP] onCreated
I/bt_hwcfg( 6717): bt vendor lib: set UART baud 115200
,I/bt_hwcfg( 6717): FW Download delta = 527038
D/bt_hwcfg( 6717): Settlement delay -- 100 ms
I/bt_hwcfg( 6717): Setting fw settlement delay to 100 
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4287, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
D/BatteryService(  872): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  872): Plugged
I/MotionRecognitionService(  872): setPowerConnected  = true
,V/HeadsetService( 6717): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 6717): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/SA      ( 7163): [TPM] There is no property file
,I/SA      ( 7163): [SCU] isHaveSA() - false
,I/SA      ( 7163): [TPM] getModelProperty : null
I/SA      ( 7163): [TPM] getCSCProperty : null
,I/SA      ( 7163): [DM] init START
,I/SA      ( 7163): [DM] This device is not a Vodafone
,I/SA      ( 7163): checkReactivationActive for LOLLIPOP
,I/SA      ( 7163): checkReactivationActive for reactiveActive
I/SA      ( 7163): setSupportRL : true
,I/SA      ( 7163): [SCU] isHaveSA() - false
,I/SA      ( 7163): support phone number id : false
,I/SA      ( 7163): [DM] init END
I/SA      ( 7163): [OR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOB6 PSS = 5.701607447389803  ]
,I/SA      ( 7163): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
,I/SA      ( 7163): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 7163): [SLFUCHKMGR] constructor called
,I/SA      ( 7163): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 7163): [OR] == isSIMCardReady false ==
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 7163): [SCU] == networkStateCheck == true
,I/SA      ( 7163): [DM] getCountryCodeFromCSC : PL
I/SA      ( 7163): isChinaCountryCode : false
I/SA      ( 7163): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 7163): [OR] == networkStateCheck true ==
,I/SA      ( 7163): [OR] GetMyCountryZoneTask
,I/SA      ( 7163): [OR] onReceive END
,I/ActivityManager(  872): Killing 6175:com.samsung.android.app.filterinstaller/1000 (adj 15): bgCount ##41
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 7163): [SRS] prepareGetMyCountryZone
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 7163): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
,I/SA      ( 7163): [SSP] query invoked
,I/SA      ( 7163): [TPMU] GetMccFromDB : null
,I/SA      ( 7163): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 7163): [TPM] isNoProxy(default) : true
,E/File    ( 7163): fail readDirectory() errno=2
,E/Zygote  ( 7186): MountEmulatedStorage()
E/Zygote  ( 7186): v2
I/libpersona( 7186): KNOX_SDCARD checking this for 10074
I/libpersona( 7186): KNOX_SDCARD not a persona
,I/bt_hwcfg( 6717): bt vendor lib: set UART baud 3000000
,I/ActivityManager(  872): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=7186 uid=10074 gids={50074, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 7186): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7186): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7186): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     (  330): Explicit concurrent mark sweep GC freed 8722(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 311us total 16.215ms
,I/bt_hwcfg( 6717): vendor lib fwcfg completed
,I/        ( 6717): BTE_InitTraceLevels -- TRC_HCI
I/        ( 6717): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 6717): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 6717): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 6717): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 6717): BTE_InitTraceLevels -- TRC_A2D
I/        ( 6717): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 6717): BTE_InitTraceLevels -- TRC_BTM
I/        ( 6717): BTE_InitTraceLevels -- TRC_GAP
I/        ( 6717): BTE_InitTraceLevels -- TRC_PAN
I/        ( 6717): BTE_InitTraceLevels -- TRC_SAP
I/        ( 6717): BTE_InitTraceLevels -- TRC_SDP
I/        ( 6717): BTE_InitTraceLevels -- TRC_GATT
I/        ( 6717): BTE_InitTraceLevels -- TRC_SMP
I/        ( 6717): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 6717): BTE_InitTraceLevels -- TRC_BTIF
I/        ( 6717): BTE_InitTraceLevels -- TRC_PROTOCOL
,I/art     (  330): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 271us total 9.901ms
,I/art     (  330): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 362us total 10.105ms
,D/TimaKeyStoreProvider( 7186): TimaSignature is unavailable
,D/ActivityThread( 7186): Added TimaKeyStore provider
,D/ResourcesManager( 7186): creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
,I/sCloudBackupApp( 7186): sCloudBackupApp Version Info : 3.13.7.KK_APP
,I/SCloudBackupReceiver( 7186): Other Intent
,I/KnoxUsageLogPro( 6444): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 6444): premStatus:2
,I/KnoxUsageLogPro( 6444): isEulaShown : false
I/KnoxUsageLogPro( 6444): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7202): MountEmulatedStorage()
,E/Zygote  ( 7202): v2
I/libpersona( 7202): KNOX_SDCARD checking this for 10146
I/libpersona( 7202): KNOX_SDCARD not a persona
,I/SELinux ( 7202): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/ActivityManager(  872): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7202 uid=10146 gids={50146, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  872): Killing 6200:com.samsung.android.app.watchmanagerstub/u0a126 (adj 15): bgCount ##41
,I/SELinux ( 7202): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7202): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7202): TimaSignature is unavailable
,D/ActivityThread( 7202): Added TimaKeyStore provider
,D/ResourcesManager( 7202): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,W/bt-l2cap( 6717): l2c_link_processs_ble_num_bufs 15
,E/bt-btm  ( 6717): BTM_SecRegister:p_cb_info->p_le_callback == 0xaf918b05 
E/bt-btm  ( 6717): BTM_SecRegister: btm_cb.api.p_le_callback = 0xaf918b05 
,E/WifiStateMachine(  872): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7202): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7202): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7202): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7202): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BluetoothAdapterProperties( 6717): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 0 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 0 mIsActivityAndEnergyReporting = false
E/bt-btif ( 6717): Calling BTA_HhEnable
E/bt-btif ( 6717): BTA got event 0x518
D/BluetoothAdapterProperties( 6717): Address is:E0:DB:10:1F:C9:5E
E/BluetoothServiceJni( 6717): populateRssiValuesNative
I/bluedroid( 6717): getModelRssiValues
E/BluetoothServiceJni( 6717): model_rssi_values_callback: low = -70, mid = -60, high = 127
D/BluetoothAdapterProperties( 6717): modelRssiValuesCallback, low, mid, high = -70,-60,127
D/BluetoothAdapterProperties( 6717): Name is: Note3-1
D/SettingsProvider(  872): name = bluetooth_name
D/BluetoothAdapterProperties( 6717): Scan Mode:20
D/BluetoothAdapterProperties( 6717): Discoverable Timeout:120
D/BluetoothAdapterProperties( 6717): LE Address is:E0:B7:20:3E:93:BC
E/bt-btif ( 6717): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
D/bt_vendor( 6717): op for 2
E/bt-btif ( 6717): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
D/bt_vendor( 6717): op for 6
E/bt-btif ( 6717): btif_sock_init: !radio_req && !rfc_init
E/bt-btif ( 6717): btif_sock_init: !vhci_init
D/bt_vendor( 6717): op for 7
D/IOP_DB_BT( 6717): db_open: file /etc/bluetooth/iop_bt.db
D/bt_upio ( 6717): proc btwrite assertion
,D/bt_vendor( 6717): op for 7
D/bt_upio ( 6717): BT_WAKE is asserted already
,D/bt_vendor( 6717): op for 7
D/bt_upio ( 6717): BT_WAKE is asserted already
,D/IOP_DB_BT( 6717): db_open: db_open : handle 3013783568l, read 14063 bytes onto local cache
D/IOP_DB_BT( 6717): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
D/IOP_DB_BT( 6717): db_query: result 1
I/        ( 6717): iop_db_open: iop_db_open status 0
,D/bte_conf( 6717): Device ID record 1 : primary
D/bte_conf( 6717):   vendorId            = 0075
D/bte_conf( 6717):   vendorIdSource      = 0001
D/bte_conf( 6717):   product             = 0100
D/bte_conf( 6717):   version             = 0200
D/bte_conf( 6717):   clientExecutableURL = 
D/bte_conf( 6717):   serviceDescription  = 
D/bte_conf( 6717):   documentationURL    = 
D/bte_conf( 6717): bte_load_did_conf no section named DID2.
D/BluetoothAdapterState( 6717): CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothPanServiceJni( 6717): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothAdapterProperties( 6717): ScanMode =  20
D/BluetoothAdapterProperties( 6717): State =  11
,D/SecContentProvider(  872): uri = 3 selection = isDiscoverableEnabled
D/BluetoothAdapterProperties( 6717): Setting state to 12
I/BluetoothAdapterState( 6717): Bluetooth adapter state changed: 11-> 12
,I/WebViewFactory( 7202): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
D/BluetoothAdapterProperties( 6717): Scan Mode:21
D/BluetoothAdapterProperties( 6717): Discoverable Timeout:120
,D/SettingsProvider(  872): name = bluetooth_a2dp_sink_mode
D/SettingsProvider(  872): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  872): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  872): selectionArgs: false
D/SettingsProvider(  872): selectionArgs: 1002
D/SecContentProvider(  872): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  872): ret = -1
D/ResourcesManager( 7202): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,W/BackupManagerService(  872): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/BluetoothAdapterService( 6717): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 6717): updateAdapterState state is 12
,D/BluetoothA2dp( 2947): onBluetoothStateChange: up=true
,D/BluetoothA2dp( 6717): onBluetoothStateChange: up=true
D/BluetoothA2dp(  872): onBluetoothStateChange: up=true
,W/InputMethodManagerService(  872): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothHeadset( 1417): registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@4631139, true
,I/InputMethodManagerService(  872): [BT Setting State] State =12
D/BluetoothHeadset( 1417): registerMessageListener
I/InputMethodManagerService(  872): [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,D/BluetoothAdapterService( 6717): Autoconnection is available 
D/BluetoothAdapterService( 6717): updateAdapterState prevState = 11newState = 12
D/BluetoothAdapterService( 6717): starting service from this receiver
,D/BluetoothTile( 1187):  onBluetoothStateChange:
,I/SamsungIME( 1708): STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,D/bt_vendor( 6717): op for 7
D/bt_upio ( 6717): BT_WAKE is asserted already
,E/bt_h4   ( 6717): vendor lib postload completed
,D/bt_vendor( 6717): op for 7
D/bt_upio ( 6717): BT_WAKE is asserted already
I/LibraryLoader( 7202): Loading: webviewchromium
,D/BluetoothTile( 1187):  onBluetoothPairedDevicesChanged:
D/BluetoothTile( 1187): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,D/bt_vendor( 6717): op for 7
D/bt_upio ( 6717): BT_WAKE is asserted already
I/BluetoothPbapService( 6717): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,D/HeadsetService( 6717): registerMessageListener
,D/HeadsetService( 6717): registerMessageListener
D/bt_vendor( 6717): op for 7
D/bt_upio ( 6717): BT_WAKE is asserted already
D/HeadsetStateMachine( 6717): Disconnected process message: 70
D/HeadsetStateMachine( 6717): processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@a38c0ad
,I/Telecom ( 1417): BluetoothPhoneService: updateHeadsetWithCallState
I/BluetoothAdapterState( 6717): Entering On State from state = 11
I/BluetoothPbapService( 6717): Handler(): got msg=1
,D/BluetoothManagerService(  872): Broadcasting onBluetoothServiceUp() to 0 receivers.
D/bt_vendor( 6717): op for 7
D/bt_upio ( 6717): BT_WAKE is asserted already
D/StatusBarManagerService(  872): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020319 level=0 visible=true num=0 )
D/BluetoothManager( 6855): [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
I/Telecom ( 1417): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,D/SecContentProvider(  872): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,D/bt_vendor( 6717): op for 7
D/bt_upio ( 6717): BT_WAKE is asserted already
,D/StatusBarManagerService(  872): setIconVisibility slot=bluetooth visible=true
,D/PhoneStatusBar( 1187): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020319 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020319 level=0 visible=true num=0 )
,D/bt_vendor( 6717): op for 7
D/bt_upio ( 6717): BT_WAKE is asserted already
,D/bt_vendor( 6717): op for 7
D/bt_upio ( 6717): BT_WAKE is asserted already
,D/bt_vendor( 6717): op for 7
D/bt_upio ( 6717): BT_WAKE is asserted already
,D/HeadsetStateMachine( 6717): Disconnected process message: 9
V/BluetoothPbapService( 6717): PBAP Service initSocket try: 0
D/HeadsetStateMachine( 6717): mNumActive: 0 mNumHeld: 0 mCallState: 6
,D/bt_vendor( 6717): op for 7
D/bt_upio ( 6717): BT_WAKE is asserted already
,D/bt_vendor( 6717): op for 7
D/bt_upio ( 6717): BT_WAKE is asserted already
,D/BluetoothTile( 1187):  handleUpdatestate:false name:null
D/STATUSBAR-QSTileView( 1187): onStateChanged: Bluetooth
,D/bt_vendor( 6717): op for 7
D/bt_upio ( 6717): BT_WAKE is asserted already
,D/bt_vendor( 6717): op for 7
D/bt_upio ( 6717): BT_WAKE is asserted already
,I/LibraryLoader( 7202): Time to load native libraries: 18 ms (timestamps 1137-1155)
I/LibraryLoader( 7202): Expected native library version number "",actual native library version number ""
,D/bt_vendor( 6717): op for 7
D/bt_upio ( 6717): BT_WAKE is asserted already
D/audio_hw_primary(  298): adev_set_parameters: enter: A2dpSuspended=false
V/voice   (  298): voice_set_parameters: enter: A2dpSuspended=false
V/voice   (  298): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  298): platform_set_parameters: enter: A2dpSuspended=false
V/msm8974_platform(  298): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  298): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  298): adev_set_parameters: exit
E/HeadsetStateMachine( 6717): terminateScoUsingVirtualVoiceCall:No present call to terminate
,D/bt_vendor( 6717): op for 7
D/bt_upio ( 6717): BT_WAKE is asserted already
,D/bt_vendor( 6717): op for 7
D/bt_upio ( 6717): BT_WAKE is asserted already
,W/BluetoothAdapter( 6717): getBluetoothService() called with no BluetoothManagerCallback
,D/bt_vendor( 6717): op for 7
D/bt_upio ( 6717): BT_WAKE is asserted already
,D/BluetoothSocket( 6717): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[72]}
D/BluetoothSocket( 6717): bindListen(), new LocalSocket 
D/BluetoothSocket( 6717): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 6717): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3b123d5c
D/BluetoothSocket( 6717): channel: 19
D/BluetoothPbapService( 6717): PBAP Socket is BluetoothServerSocket
,D/bt_vendor( 6717): op for 7
D/bt_upio ( 6717): BT_WAKE is asserted already
,D/BluetoothMapMasInstance( 6717): set MAP SDP message type : 1
,V/WebViewChromiumFactoryProvider( 7202): Binding Chromium to main looper Looper (main, tid 1) {68a0301}
,D/bt_vendor( 6717): op for 7
D/bt_upio ( 6717): BT_WAKE is asserted already
,I/LibraryLoader( 7202): Expected native library version number "",actual native library version number ""
,D/bt_vendor( 6717): op for 7
D/bt_upio ( 6717): BT_WAKE is asserted already
,I/chromium( 7202): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,W/BluetoothAdapter( 6717): getBluetoothService() called with no BluetoothManagerCallback
D/bt_vendor( 6717): op for 7
D/bt_upio ( 6717): BT_WAKE is asserted already
,D/BluetoothSocket( 6717): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
D/BluetoothSocket( 6717): bindListen(), new LocalSocket 
D/BluetoothSocket( 6717): bindListen(), new LocalSocket.getInputStream() 
D/bt_vendor( 6717): op for 7
D/bt_upio ( 6717): BT_WAKE is asserted already
D/BluetoothSocket( 6717): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@69e5865
D/BluetoothSocket( 6717): channel: 5
,D/bt_vendor( 6717): op for 7
D/bt_upio ( 6717): BT_WAKE is asserted already
,D/bt_vendor( 6717): op for 7
D/bt_upio ( 6717): BT_WAKE is asserted already
,D/bt_vendor( 6717): op for 7
D/bt_upio ( 6717): BT_WAKE is asserted already
,D/bt_vendor( 6717): op for 7
D/bt_upio ( 6717): BT_WAKE is asserted already
,D/bt_vendor( 6717): op for 7
D/bt_upio ( 6717): BT_WAKE is asserted already
,I/SurfaceFlinger(  254): id=14 Removed Uoast (8/9)
,I/SurfaceFlinger(  254): id=14 Removed Uoast (-2/9)
,D/PowerManagerService(  872): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 872) eventTime = 171182
,D/OpenGLRenderer( 3161): Render dirty regions requested: true
D/PowerManagerService(  872): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=872 (0x0)
D/PowerManagerService(  872): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=872, ws=WorkSource{10067}) (elapsedTime=3474)
,I/BrowserStartupController( 7202): Initializing chromium process, renderers=0
,W/art     ( 7202): Attempt to remove local handle scope entry from IRT, ignoring
,D/Atlas   ( 3161): Validating map...
,W/chromium( 7202): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7202): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46780 len=2953
,I/chromium( 7202): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229536 len:643667
,W/AudioManagerAndroid( 7202): Requires BLUETOOTH permission
,I/SurfaceFlinger(  254): id=15 createSurf (1x1),1 flag=4, Uoast
,I/Adreno-EGL( 7202): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 7202): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7202): Build Date: 11/19/14 Wed
I/Adreno-EGL( 7202): Local Branch: mybranch5813579
I/Adreno-EGL( 7202): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 7202): Local Patches: NONE
I/Adreno-EGL( 7202): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,D/PowerManagerService(  872): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=872
,I/Adreno-EGL( 3161): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 3161): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 3161): Build Date: 11/19/14 Wed
I/Adreno-EGL( 3161): Local Branch: mybranch5813579
I/Adreno-EGL( 3161): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 3161): Local Patches: NONE
I/Adreno-EGL( 3161): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,I/OpenGLRenderer( 3161): Initialized EGL, version 1.4
,I/OpenGLRenderer( 3161): HWUI protection enabled for context ,  &this =0xaf022088 ,&mEglDisplay = 1 , &mEglConfig = 8 
,D/OpenGLRenderer( 3161): Enabling debug mode 0
,I/NSApplication( 7202): Starting up...
,I/SA      ( 7163): [RC New] Execute method=[GET] start
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl(  872): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
,I/SA      ( 7163): [RC New] Security=[true]
,I/System.out( 7163): Thread-1160(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 7163): Thread-1160(ApacheHTTPLog):isShipBuild true
,I/System.out( 7163): Thread-1160(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,E/Zygote  ( 7267): MountEmulatedStorage()
I/libpersona( 7267): KNOX_SDCARD checking this for 10158
E/Zygote  ( 7267): v2
I/libpersona( 7267): KNOX_SDCARD not a persona
,I/ActivityManager(  872): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7267 uid=10158 gids={50158, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  872): Killing 6215:com.samsung.helphub/1000 (adj 15): bgCount ##41
,I/SELinux ( 7267): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7267): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7267): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7267): TimaSignature is unavailable
,D/ActivityThread( 7267): Added TimaKeyStore provider
,D/ResourcesManager( 7267): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager( 7267): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7267): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7267): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect( 7267): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7267): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 7267): PeriphStartReceiver.onReceive - no need to start
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  872): exchangeData() failure , invalid userId
,D/RCPManagerService(  872): exchangeData() failure , invalid userId
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SecurityLogAgent( 6699): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 6699): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6699): StateMachine : Current State = 1
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SecurityLogAgent( 6699): StateMachine : Changed Current State = 1
,I/ActivityManager(  872): Killing 6250:com.samsung.android.snote:provider/u0a168 (adj 15): bgCount ##41
,E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Zygote  ( 7283): MountEmulatedStorage()
E/Zygote  ( 7283): v2
I/libpersona( 7283): KNOX_SDCARD checking this for 10200
I/libpersona( 7283): KNOX_SDCARD not a persona
,I/ActivityManager(  872): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=7283 uid=10200 gids={50200, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7283): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7283): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7283): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7283): TimaSignature is unavailable
,D/ActivityThread( 7283): Added TimaKeyStore provider
,D/ResourcesManager( 7283): creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,I/iu.SyncManager( 1748): SYNC; picasa accounts
,D/NetworkLogImpl( 1748): Loaded NetworkSpeedPredictor
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/iu.Environment( 1748): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/iu.UploadsManager( 1748): num queued entries: 0
,I/iu.UploadsManager( 1748): num updated entries: 0
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/iu.SyncManager( 1748): NEXT; no task
,I/ActivityManager(  872): Killing 6270:com.sec.kidsplat.installer/u0a189 (adj 15): bgCount ##41
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WaitQueueForNetworkActivate( 6301): notifyNetworkActivated
,W/ContextImpl( 6301): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager(  872): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/hcjo    ( 6301): AutoUpdateManager:IDLE:execute
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 1397): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
D/InitializeManagerStateMachine( 6301): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 6301): exit::IDLE
D/InitializeManagerStateMachine( 6301): entry::NETWORK_CHECK
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 6301): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 6301): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6301): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6301): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6301): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6301): entry::SUCCESS
D/hcjo    ( 6301): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 6301): AutoUpdateTriggerManager:IDLE:setInterval:345600000
,I/GCM     ( 1397): GCM config loaded
,D/hcjo    ( 6301): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 6301): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 6301): exit::SUCCESS
D/InitializeManagerStateMachine( 6301): entry::IDLE
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1303): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/LocalBluetoothProfileManager( 1303): Adding local A2DP profile
,D/LocalBluetoothProfileManager( 1303): Adding local HEADSET profile
,E/BluetoothHeadset( 1303): BTStateChangeCB is registed
,E/BluetoothHeadset( 1303): BluetoothHeadset service is binded
,W/ContextImpl( 1303): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2124 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
,D/Bluetoothsap( 1303): bindService called to Bluetooth SAP Service
,D/LocalBluetoothProfileManager( 1303): PANU : true
D/LocalBluetoothProfileManager( 1303): Adding local MAP profile
,D/BluetoothMap( 1303): Create BluetoothMap proxy object
,W/LocalBluetoothProfileManager( 1303): Warning: SAP profile was previously added.
D/LocalBluetoothProfileManager( 1303): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 1303): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 1303): onReceive
,D/BluetoothA2dp( 1303): Proxy object connected
,D/A2dpProfile( 1303): Bluetooth service connected
D/BluetoothAdapterService( 6717): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cf346d2
D/BtConfig.SecureMode( 6717): isSecureModeOn:false
,D/HeadsetProfile( 1303): Bluetooth service connected
,D/Bluetoothsap( 1303): BluetoothSAP Proxy object connected
,D/AuthorizationBluetoothService( 1397): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/SapProfile( 1303): Bluetooth service connected
D/Bluetoothsap( 1303): getConnectedDevices()
,D/BluetoothInputDevice( 1303): Proxy object connected
,D/HidProfile( 1303): Bluetooth service connected
,D/BluetoothPan( 1303): BluetoothPAN Proxy object connected
,D/PanProfile( 1303): Bluetooth service connected
,D/BluetoothMap( 1303): Proxy object connected
,D/MapProfile( 1303): Bluetooth service connected
D/BluetoothPbap( 1303): Proxy object connected
D/PbapServerProfile( 1303): Bluetooth service connected
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider(  872): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/BluetoothAdapter( 6717): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 6717): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[78]}
D/BluetoothSocket( 6717): bindListen(), new LocalSocket 
D/BluetoothSocket( 6717): bindListen(), new LocalSocket.getInputStream() 
D/bt_vendor( 6717): op for 7
D/bt_upio ( 6717): BT_WAKE is asserted already
D/BluetoothSocket( 6717): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@37f969c7
D/BluetoothSocket( 6717): channel: 12
I/BtOppRfcommListener( 6717): Accept thread started.
,I/SA      ( 7163): [RC New] [v2liruge] api execute + 632
I/SA      ( 7163): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 7163): AsyncTask #1 calls detatch()
,I/SA      ( 7163): [TPMU] getNetworkMcc : 
,I/SA      ( 7163): [SCU] saveMccToPreferece Start
I/SA      ( 7163): [SCU] RegionMCC : 260
I/SA      ( 7163): [SSP] query invoked
,I/SA      ( 7163): [TPMU] GetMccFromDB : null
I/SA      ( 7163): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 7163): [SCU] saveMccToPreferece End
,I/SA      ( 7163): [RC New] executeRequest [v2liruge] end. 688
I/SA      ( 7163): [RC New] Execute end
I/SA      ( 7163): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 7163): [OR] GetMyCountryZoneTask Success
,D/bt_upio ( 6717): ..proc_btwrite_timeout..
E/SMD     (  290): DCD ON
I/PCWCLIENTTRACE_SYSTEMReceiver( 5933): mConnectivityHandler : connected
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/PCWCLIENTTRACE_AccountUtil( 5933): [hasSamungAccount] - No Samsung Account
,I/CSTORAGE( 5933): ================================================
,I/CSTORAGE( 5933):  CSTORAGE_SKM_LIB v1.0.6
I/CSTORAGE( 5933): ================================================
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5933): [GetString-S]
,E/art     ( 5933): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 5933): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5933): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 5933): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5933): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5933): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 5933): [ensureRegistration] - No Samsung account
,D/bt_vendor( 6717): op for 7
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/dhcpcd  ( 6876): wlan0: sending IPv6 Router Solicitation
,I/SurfaceFlinger(  254): id=15 Removed Uoast (8/9)
,I/SurfaceFlinger(  254): id=15 Removed Uoast (-2/9)
,D/PowerManagerService(  872): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 872) eventTime = 174724
,D/PowerManagerService(  872): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=872 (0x0)
,D/PowerManagerService(  872): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=872, ws=WorkSource{1000}) (elapsedTime=3496)
,I/GAV4    ( 7202): Thread[GAThread,5,main]: No campaign data found.
,E/SMD     (  290): DCD ON
,E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7335): MountEmulatedStorage()
,E/Zygote  ( 7335): v2
,I/libpersona( 7335): KNOX_SDCARD checking this for 10051
I/libpersona( 7335): KNOX_SDCARD not a persona
,D/btif_config_util( 6717): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/ActivityManager(  872): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=7335 uid=10051 gids={50051, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7335): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7335): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7335): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7335): TimaSignature is unavailable
,D/ActivityThread( 7335): Added TimaKeyStore provider
,D/ResourcesManager( 7335): creating new AssetManager and set to /system/priv-app/SecCalendarProvider/SecCalendarProvider.apk
,W/ResourcesManager( 7335): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CalendarProvider2( 7335): CalendarProvider2.onCreate() called
,I/dhcpcd  ( 6876): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  ( 6876): wlan0: no IPv6 Routers available
,I/CalendarProvider2( 7335): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  872): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=7376 uid=10171 gids={50171, 9997} abi=armeabi-v7a
,I/ActivityManager(  872): Killing 6376:com.sec.enterprise.knox.cloudmdm.smdms/u0a201 (adj 15): bgCount ##41
,E/Zygote  ( 7376): MountEmulatedStorage()
,E/Zygote  ( 7376): v2
,I/libpersona( 7376): KNOX_SDCARD checking this for 10171
I/libpersona( 7376): KNOX_SDCARD not a persona
,I/SELinux ( 7376): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7376): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7376): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7376): TimaSignature is unavailable
D/ActivityThread( 7376): Added TimaKeyStore provider
,D/ResourcesManager( 7376): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
,W/ResourcesManager( 7376): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7376): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7407): MountEmulatedStorage()
E/Zygote  ( 7407): v2
I/libpersona( 7407): KNOX_SDCARD checking this for 10172
I/libpersona( 7407): KNOX_SDCARD not a persona
,I/SELinux ( 7407): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7407): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7407): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  872): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=7407 uid=10172 gids={50172, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/ActivityManager(  872): Killing 5339:sstream.app/u0a25 (adj 15): bgCount ##41
,D/TimaKeyStoreProvider( 7407): TimaSignature is unavailable
,D/ActivityThread( 7407): Added TimaKeyStore provider
,D/ResourcesManager( 7407): creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
,W/ResourcesManager( 7407): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 7407): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7407): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/art     (  872): Explicit concurrent mark sweep GC freed 23593(1514KB) AllocSpace objects, 4(64KB) LOS objects, 17% free, 37MB/45MB, paused 1.505ms total 129.376ms
,I/ActivityManager(  872): Killing 5379:com.samsung.android.app.galaxyfinder/u0a39 (adj 15): bgCount ##41
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 340, PST = 332, CUR = 450
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  872): Plugged
I/MotionRecognitionService(  872): setPowerConnected  = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  872): stay LED for fully charged
,V/HeadsetService( 6717): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6717): Disconnected process message: 10
,D/PreloadUpdateManagerStateMachine( 6301): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 6301): exit::IDLE
D/PreloadUpdateManagerStateMachine( 6301): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 6301): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 6301): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 6301): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 6301): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 6301): entry::IDLE
,E/SMD     (  290): DCD ON
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/PowerManagerService(  872): [PWL] Off : 75s ago
,E/SMD     (  290): DCD ON
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD ON
,W/Atfwd_Sendcmd(  338): AtCmdFwd service not published, waiting... retryCnt : 5
,D/SSRM:n  (  872): SIOP:: AP = 320, PST = 331, CUR = 450
,E/SMD     (  290): DCD ON
,W/ContextImpl(  872): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD ON
,E/Watchdog(  872): !@Sync 6
,E/SMD     (  290): DCD ON
,V/AlarmManager(  872): waitForAlarm result :4
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  872): stay LED for fully charged
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  872): Plugged
I/MotionRecognitionService(  872): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6717): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6717): Disconnected process message: 10
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager(  872): waitForAlarm result :4
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 320, PST = 329, CUR = 450,
,I/ClearcutLoggerApiImpl( 1397): disconnect managed GoogleApiClient
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 310, PST = 326, CUR = 450
,W/ContextImpl(  872): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD ON
,I/Atfwd_Sendcmd(  338): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  338): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/PowerManagerService(  872): [PWL] Off : 105s ago
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,V/AlarmManager(  872): waitForAlarm result :8
,D/SSRM:n  (  872): SIOP:: AP = 310, PST = 325, CUR = 450
,E/SMD     (  290): DCD ON
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD ON
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,E/Watchdog(  872): !@Sync 7
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD ON
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,V/AlarmManager(  872): waitForAlarm result :4
,W/Atfwd_Sendcmd(  338): AtCmdFwd service not published, waiting... retryCnt : 1
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1187): handleTimeUpdate
,D/KeyguardEffectViewController( 1187): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1187): *** don't update sliding image ***
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/DateView( 1187): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1187): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityThread( 1748): Failed to find provider info for com.android.contacts.metadata
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  872): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, SERVER, currentRunTime 199364, reason: ServiceChanged, SyncResult: databaseError: true stats []
,D/SyncManager(  872): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, SERVER, currentRunTime 290275, reason: ServiceChanged
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  872): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  872): mCursor = null
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 310, PST = 324, CUR = 450
,W/ContextImpl(  872): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD ON
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD ON
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  338): AtCmdFwd service not published, waiting... retryCnt : 2
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 310, PST = 324, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/PowerManagerService(  872): [PWL] Off : 140s ago
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,D/SSRM:n  (  872): SIOP:: AP = 310, PST = 324, CUR = 450
,E/SMD     (  290): DCD ON
,W/ContextImpl(  872): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  338): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  290): DCD ON
,E/Watchdog(  872): !@Sync 8
,E/SMD     (  290): DCD ON
,V/AlarmManager(  872): waitForAlarm result :4
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 300, PST = 322, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  872): stay LED for fully charged
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  872): Plugged
I/MotionRecognitionService(  872): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6717): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6717): Disconnected process message: 10
,E/SMD     (  290): DCD ON
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,D/SSRM:n  (  872): SIOP:: AP = 300, PST = 313, CUR = 450
,W/ContextImpl(  872): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD ON
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  338): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,V/AlarmManager(  872): waitForAlarm result :8
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  872): SIOP:: AP = 300, PST = 309, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/Watchdog(  872): !@Sync 9
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  872): Plugged
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  872): stay LED for fully charged
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6717): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6717): Disconnected process message: 10
,I/PowerManagerService(  872): [PWL] Off : 180s ago
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 300, PST = 307, CUR = 450
,W/ContextImpl(  872): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD ON
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD ON
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  338): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  872): Plugged
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
I/MotionRecognitionService(  872): setPowerConnected  = true
,D/BatteryService(  872): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6717): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6717): Disconnected process message: 10
,D/SSRM:n  (  872): SIOP:: AP = 300, PST = 305, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  872): Plugged
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/BatteryService(  872): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6717): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6717): Disconnected process message: 10
,D/SSRM:n  (  872): SIOP:: AP = 300, PST = 304, CUR = 450
,E/SMD     (  290): DCD ON
,W/ContextImpl(  872): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService(  872): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  872): TimaServiceHandler.handleMessage what =1
,D/TimaService(  872): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize(  872): initializing...
,I/TLC_TIMA_PKM_initialize(  872): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  872): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication(  872): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication(  872): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication(  872): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  872): aligned max_recvmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication(  872): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: (  872): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  872): App is not loaded in QSEE
,D/QSEECOMAPI: (  872): Loaded image: APP id = 2
,I/TZ: qc_tlc_communication(  872): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  872): Trustlet response is completed
,E/SMD     (  290): DCD ON
,E/Watchdog(  872): !@Sync 10
,I/TLC_TIMA_PKM_measure_kernel(  872): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  872): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  872): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  872): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  872): Plugged
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/BatteryService(  872): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6717): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6717): Disconnected process message: 10
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 300, PST = 303, CUR = 450
,E/SMD     (  290): DCD ON
,I/Atfwd_Sendcmd(  338): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  338): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 300, PST = 302, CUR = 450
,W/ContextImpl(  872): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  872): waitForAlarm result :4
,E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  872): stay LED for fully charged
,I/ActivityManager(  872): Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=7478 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,E/Zygote  ( 7478): MountEmulatedStorage()
,I/MotionRecognitionService(  872): Plugged
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
E/Zygote  ( 7478): v2
I/libpersona( 7478): KNOX_SDCARD checking this for 10096
I/libpersona( 7478): KNOX_SDCARD not a persona
,D/KeyguardUpdateMonitor( 1187): handleTimeUpdate
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  872): setPowerConnected  = true
,I/SELinux ( 7478): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,V/HeadsetService( 6717): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6717): Disconnected process message: 10
,I/SELinux ( 7478): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,E/SELinux ( 7478): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardEffectViewController( 1187): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1187): *** don't update sliding image ***
,D/DateView( 1187): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1187): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/TimaKeyStoreProvider( 7478): TimaSignature is unavailable
,D/ActivityThread( 7478): Added TimaKeyStore provider
,D/ResourcesManager( 7478): creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,I/ActivityManager(  872): Killing 5464:com.sec.android.app.controlpanel/u0a134 (adj 13): bgCount ##41
,E/SMD     (  290): DCD ON,
,V/AlarmManager(  872): waitForAlarm result :4
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PowerManagerService(  872): [PWL] Off : 225s ago
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,V/AlarmManager(  872): waitForAlarm result :8
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 300, PST = 301, CUR = 450
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  338): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  290): DCD ON
,E/Watchdog(  872): !@Sync 11
,V/GLSActivity( 1397): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1397): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1397): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 5514): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 5514): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,E/SMD     (  290): DCD ON
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD ON
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,W/ContextImpl(  872): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  872): SIOP:: AP = 300, PST = 300, CUR = 450
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD ON
,W/Atfwd_Sendcmd(  338): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  290): DCD ON
,I/wpa_supplicant( 6718): wlan0: State: COMPLETED -> GROUP_HANDSHAKE
,I/wpa_supplicant( 6718): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.4A SSID=4E473730303567,
,I/wpa_supplicant( 6718): wlan0: WPA: Group rekeying completed with c0:ff:d4:d3:aa:4a [GTK=CCMP]
,I/wpa_supplicant( 6718): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 6718): Blacklist: Clear (temp) 
,I/wpa_supplicant( 6718): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.4A SSID=4E473730303567
,D/SecContentProvider2(  872): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  872): mCursor = null
,D/SecContentProvider2(  872): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  872): mCursor = null
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 300, PST = 300, CUR = 450
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD ON
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD ON
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD ON
,W/Atfwd_Sendcmd(  338): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  290): DCD ON
,W/ContextImpl(  872): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  872): SIOP:: AP = 300, PST = 300, CUR = 450
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD ON
,E/Watchdog(  872): !@Sync 12
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 300, PST = 300, CUR = 450
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD ON
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/PowerManagerService(  872): [PWL] Off : 275s ago
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD ON
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  338): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  290): DCD ON
,W/ContextImpl(  872): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  872): SIOP:: AP = 300, PST = 300, CUR = 450
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  872): Plugged
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 6717): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6717): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/BatteryService(  872): stay LED for fully charged
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,I/jxcore-log( 6606): Toggling radios to false
I/jxcore-log( 6606): 
,D/BluetoothAdapter( 6606): disable()
,D/SettingsProvider(  872): name = bluetooth_on
,D/BluetoothAdapterState( 6717): CURRENT_STATE=ON, MSG = USER_TURN_OFF
,D/BluetoothAdapterProperties( 6717): Setting state to 13
I/BluetoothAdapterState( 6717): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterService( 6717): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 6717): updateAdapterState state is 13
,I/BluetoothPbapService( 6717): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,D/BluetoothAdapterService( 6717): Autoconnection is available 
,D/BluetoothAdapterService( 6717): updateAdapterState prevState = 12newState = 13
D/BluetoothAdapterService( 6717): terminating service from this receiver
,D/BluetoothSocket( 6717): close() in, this: android.bluetooth.BluetoothSocket@2a56dbf4, channel: 19, state: LISTENING
,D/BluetoothSocket( 6717): close() this: android.bluetooth.BluetoothSocket@2a56dbf4, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3b123d5c, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@10b82f1dmSocket: android.net.LocalSocket@a351592 impl:android.net.LocalSocketImpl@618db63 fd:FileDescriptor[72]
D/BluetoothSocket( 6717): Closing mSocket: android.net.LocalSocket@a351592 impl:android.net.LocalSocketImpl@618db63 fd:FileDescriptor[72]
,D/BluetoothAdapterProperties( 6717): onBluetoothDisable()
,D/SecContentProvider(  872): uri = 3 selection = isDiscoverableEnabled
I/BluetoothAdapterState( 6717): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,D/BluetoothAdapterProperties( 6717): Scan Mode:20
,D/BluetoothAdapterState( 6717): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,E/bt-btif ( 6717): btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,E/bt-btif ( 6717): btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,E/bt-btif ( 6717): cmd socket is not created
D/bt_vendor( 6717): op for 7
,E/BtOppRfcommListener( 6717): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,D/btif_config_util( 6717): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/bt_upio ( 6717): proc btwrite assertion
,E/bt-btm  ( 6717): btm_ble_start_auto_conn start : 0, 0
,W/bt-btif ( 6717): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,W/bt-l2cap( 6717): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 6717): L2CAP - PSM: 0x0017 not found for deregistration
,W/bt-l2cap( 6717): L2CAP - PSM: 0x001b not found for deregistration
D/bt_vendor( 6717): op for 7
,D/bt_upio ( 6717): BT_WAKE is asserted already
,D/bt_vendor( 6717): op for 7
,D/bt_upio ( 6717): BT_WAKE is asserted already
,D/bt_vendor( 6717): op for 7
D/bt_upio ( 6717): BT_WAKE is asserted already
,D/bt_vendor( 6717): op for 7
,D/bt_upio ( 6717): BT_WAKE is asserted already
,D/bt_vendor( 6717): op for 7
,D/bt_upio ( 6717): BT_WAKE is asserted already
,D/bt_vendor( 6717): op for 7
,D/bt_upio ( 6717): BT_WAKE is asserted already
,D/bt_vendor( 6717): op for 7
,D/bt_upio ( 6717): BT_WAKE is asserted already
,W/InputMethodManagerService(  872): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,I/InputMethodManagerService(  872): [BT Setting State] State =13
,D/bt_vendor( 6717): op for 7
D/bt_upio ( 6717): BT_WAKE is asserted already
,D/bt_vendor( 6717): op for 7
,D/bt_upio ( 6717): BT_WAKE is asserted already
,D/BluetoothTile( 1187):  onBluetoothStateChange:
,D/bt_vendor( 6717): op for 7
,D/bt_upio ( 6717): BT_WAKE is asserted already
,D/bt_vendor( 6717): op for 7
,D/bt_upio ( 6717): BT_WAKE is asserted already
,D/bt_vendor( 6717): op for 7
D/bt_upio ( 6717): BT_WAKE is asserted already
D/BluetoothTile( 1187):  onBluetoothPairedDevicesChanged:
D/BluetoothTile( 1187): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,D/bt_vendor( 6717): op for 7
D/bt_upio ( 6717): BT_WAKE is asserted already
,D/bt_vendor( 6717): op for 7
,D/bt_upio ( 6717): BT_WAKE is asserted already
,D/BluetoothSocket( 6717): close() in, this: android.bluetooth.BluetoothSocket@22ada019, channel: 5, state: LISTENING
,D/BluetoothSocket( 6717): close() this: android.bluetooth.BluetoothSocket@22ada019, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@69e5865, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@170af8demSocket: android.net.LocalSocket@133cabf impl:android.net.LocalSocketImpl@198db58c fd:FileDescriptor[74]
D/BluetoothSocket( 6717): Closing mSocket: android.net.LocalSocket@133cabf impl:android.net.LocalSocketImpl@198db58c fd:FileDescriptor[74]
,D/BluetoothTile( 1187):  handleUpdatestate:false name:null
,D/BluetoothTile( 1187):  handleUpdatestate:false name:null
,D/STATUSBAR-QSTileView( 1187): onStateChanged: Bluetooth
,I/BtOppRfcommListener( 6717): stopping Accept Thread
,D/BluetoothSocket( 6717): close() in, this: android.bluetooth.BluetoothSocket@4ef24d5, channel: 12, state: LISTENING
D/BluetoothSocket( 6717): close() this: android.bluetooth.BluetoothSocket@4ef24d5, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@37f969c7, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@8c9c4eamSocket: android.net.LocalSocket@2ee453db impl:android.net.LocalSocketImpl@3f269e78 fd:FileDescriptor[78]
,D/BluetoothSocket( 6717): Closing mSocket: android.net.LocalSocket@2ee453db impl:android.net.LocalSocketImpl@3f269e78 fd:FileDescriptor[78]
I/BtOppRfcommListener( 6717): BluetoothSocket listen thread finished
,D/StatusBarManagerService(  872): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020319 level=0 visible=true num=0 )
,D/StatusBarManagerService(  872): setIconVisibility slot=bluetooth visible=false
,D/PhoneStatusBar( 1187): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020319 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020319 level=0 visible=false num=0 )
,I/WifiManager( 6606): packageName : com.test.thalitest
,D/BluetoothManager( 6855): [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
,I/SamsungIME( 1708): STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
D/SecContentProvider(  872): uri = 18 selection = isWifiEnabled
D/SecContentProvider2(  872): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  872): mCursor = null
D/BluetoothPbap( 1303): Proxy object disconnected
D/PbapServerProfile( 1303): Bluetooth service disconnected
V/BluetoothEventManager( 1303): Received android.bluetooth.adapter.action.STATE_CHANGED
,D/WifiService(  872): setWifiEnabled: false pid=6606, uid=10279
,D/SettingsProvider(  872): name = wifi_on
,W/ContextImpl( 1303): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,I/jxcore-log( 6606): Radios toggled
I/jxcore-log( 6606): 
,E/WifiStateMachine(  872): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 6718): reset timer : RESET_TIMER 0
I/wpa_supplicant( 6718): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 6718): P2P: Current p2p state = IDLE
,E/WifiConfigStore(  872): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,I/wpa_supplicant( 6718): Scan requested (ret=0) - scan timeout 30 seconds
,D/DockEventReceiver( 1303): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 1303): onReceive
,E/native  (  872): do suspend true
,D/WifiP2pService(  872): InactiveState{ what=143375 }
,D/WifiP2pService(  872): P2pEnabledState{ what=143375 }
,D/AuthorizationBluetoothService( 1397): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/CommandListener(  284): Clearing all IP addresses on wlan0
,D/StatusBar.NetworkController( 1187): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG7005g"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG7005g"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014a/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1187): onWifiSignalChanged enabled=true enabledDesc:"NG7005g"
,V/NativeCrypto( 1397): Read error: ssl=0xb3b7f200: I/O error during system call, Connection timed out
,V/NativeCrypto( 1397): SSL shutdown failed: ssl=0xb3b7f200: I/O error during system call, Broken pipe
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10015
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  872): ValidatedState{ when=0 what=532488 arg1=10015 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  872): DefaultState{ when=-1ms what=532488 arg1=10015 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  872): Forcing reevaluation
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  872): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  872): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ConnectivityService(  872): updateNetworkInfo()
E/ConnectivityService(  872): updateNetworkInfo()
D/ConnectivityService(  872): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetUtils(  872): android_net_utils_resetConnections in env=0x9d161e40 clazz=0x9baf798c iface=wlan0 mask=0x3
D/ConnectivityService(  872): ignoring duplicate network state non-change. WIFI, state = DISCONNECTED
D/ConnectivityService(  872): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,E/WifiConfigStore(  872): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,I/System.out(  872): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid (  872): Tagging socket 417 with tag ffffffff00000000{4294967295,0} uid 10015, pid: 872, getuid(): 1000
,I/System.out(  872): (HTTPLog)-Static: isSBSettingEnabled false
D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/WifiTrafficPoller(  872): evaluateTrafficStatsPolling
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1187): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1187): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1187): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1187): applyOpen
D/StatusBar.NetworkController( 1187): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1187): applyOpen
D/StatusBar.NetworkController( 1187): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1187): applyOpen
D/StatusBar.NetworkController( 1187): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1187): applyOpen
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  872): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  872): Validated
,D/bt_vendor( 6717): op for 6
D/bt_vendor( 6717): op for 7
D/bt_upio ( 6717): BT_WAKE is asserted already
D/bt_userial( 6717): RX termination
W/bt_userial( 6717): select_read return size <=0:-1, exiting userial_read_thread
D/bt_userial( 6717): Leaving userial_read_thread()
D/bt_userial( 6717): userial_close_reader Joined userial reader thread: 0
W/bt-l2cap( 6717): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 6717): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 6717): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 6717): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 6717): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 6717): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 6717): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 6717): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 6717): L2CAP - PSM: 0x001b not found for deregistration
W/bt-btif ( 6717): ag scb idx 1 not allocated
W/bt-btif ( 6717): ag scb idx 2 not allocated
E/bt-btif ( 6717): BTA AG is already disabled, ignoring ...
D/bt_vendor( 6717): op for 9
D/bt_hwcfg( 6717): hw_epilog_process
D/bt_vendor( 6717): op for 4
I/bt_userial_vendor( 6717): device fd = 65 close
,D/bt_vendor( 6717): op for 0
,D/bt_upio ( 6717): upio_set_bluetooth_power(on: 0)
D/bt_upio ( 6717): is_emulator_context : 0
D/bt_upio ( 6717): is_rfkill_disabled ? [0]
,D/WifiP2pService(  872): InactiveState{ what=131204 }
D/WifiScanningService(  872): SCAN_AVAILABLE : 1
D/RttService(  872): SCAN_AVAILABLE : 1
D/bt_vendor( 6717): cleanup
D/WifiScanningService(  872): DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService(  872): EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  872): P2pEnabledState{ what=131204 }
I/GKI_LINUX( 6717): gki_task task_id=0 [BTU] terminating
,I/GKI_LINUX( 6717): GKI_exit_task 0 done
,I/GKI_LINUX( 6717): GKI_shutdown(): task [BTU] terminated
,D/BluetoothAdapterState( 6717): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BtConfig.SecureMode( 6717): isSecureModeOn:false
D/BluetoothAdapterService( 6717): mProfilesStarted : true supportedProfileServices.length : 12
W/BluetoothAdapterService( 6717): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 6717): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,W/BluetoothAdapterService( 6717): Not skipping com.android.bluetooth.gatt.GattService
,W/BluetoothAdapterService( 6717): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 6717): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,D/BtGatt.DebugUtils( 6717): handleDebugAction() action=null
W/BluetoothAdapterService( 6717): Not skipping com.android.bluetooth.hfp.HeadsetService
D/BtGatt.GattService( 6717): Received stop request...Stopping profile...
D/BtGatt.GattService( 6717): stop()
,D/BtGatt.AdvertiseManager( 6717): advertise clients cleared
,W/BluetoothAdapterService( 6717): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 6717): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
D/BluetoothAdapterService( 6717): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cf346d2
D/WifiP2pService(  872): sending p2p connection changed broadcast: FAILED
W/BluetoothAdapterService( 6717): Not skipping com.android.bluetooth.a2dp.A2dpService
,D/WifiNetworkAgent(  872): NetworkAgent: NetworkAgent channel lost
,W/BluetoothAdapterService( 6717): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 6717): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 6717): Not skipping com.android.bluetooth.hid.HidService
,D/WifiDisplayController(  872): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/WifiDisplayAdapter(  872): onP2pDisconnected
I/Hs20UtilService( 1303): Starting #6
D/IpRemoteDisplayController(  872): disconnectWfdBridgeServer
D/IpRemoteDisplayController(  872): WfdBridgeServer is already null
,D/WifiP2pService(  872): sending p2p connection changed broadcast: DISCONNECTED
,W/BluetoothAdapterService( 6717): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 6717): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 6717): Not skipping com.android.bluetooth.hdp.HealthService
,E/WifiStateMachine(  872): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,D/WifiDisplayController(  872): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
D/WifiDisplayController(  872): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController(  872): disconnect
D/WifiDisplayController(  872): updateConnection
D/WifiDisplayController(  872): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayAdapter(  872): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiP2pService(  872): P2pDisablingState
,D/WifiP2pService(  872): P2pDisablingState{ what=147458 }
W/BluetoothAdapterService( 6717): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/WifiP2pService(  872): p2p socket connection lost
D/BtSettings.ProfileConfig( 6717): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,D/WifiP2pService(  872): P2pDisabledState
W/BluetoothAdapterService( 6717): Not skipping com.android.bluetooth.pan.PanService
E/native  (  872): do suspend true
D/WifiDisplayController(  872): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
D/WifiDisplayAdapter(  872): onP2pDisconnected
I/Hs20UtilService( 1303): Message received 5007
D/IpRemoteDisplayController(  872): disconnectWfdBridgeServer
D/IpRemoteDisplayController(  872): WfdBridgeServer is already null
,D/AllShareCastTile( 1187): action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,D/WifiDisplayAdapter(  872): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/AllShareCastTile( 1187): wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,W/BluetoothAdapterService( 6717): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 6717): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/NearbySettings( 1303): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1303): DMSUtil.isNetworkConnected - flag-null, state-null
W/BluetoothAdapterService( 6717): Not skipping com.android.bluetooth.map.BluetoothMapService
D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1303): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,W/BluetoothAdapterService( 6717): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 6717): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1303): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1303): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1303): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1303): MountReceiver.mPrefHandler - 7002
D/WifiP2pService(  872): P2pDisabledState{ what=143375 }
D/WifiP2pService(  872): DefaultState{ what=143375 }
,W/BluetoothAdapterService( 6717): Not skipping com.broadcom.bt.service.sap.SapService
,W/BluetoothAdapterService( 6717): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,D/BtSettings.ProfileConfig( 6717): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 6717): Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,W/BluetoothAdapterService( 6717): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 6717): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 6717): Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
,W/BluetoothAdapterService( 6717): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 6717): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 6717): Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
,W/BluetoothAdapterService( 6717): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
,D/BtSettings.ProfileConfig( 6717): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
D/CommandListener(  284): Clearing all IP addresses on wlan0
W/BluetoothAdapterService( 6717): Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
,D/BluetoothAdapterState( 6717): Stopping profile services that were post enabled
E/BluetoothAdapterService(485705426)( 6717): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
D/StatusBar.NetworkController( 1187): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1187): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 1187): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1187): onWifiSignalChanged enabled=true enabledDesc:null
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/WifiTrafficPoller(  872): evaluateTrafficStatsPolling
,I/wpa_supplicant( 6718): p2p0: State: DISCONNECTED -> DISCONNECTED
D/HeadsetService( 6717): Received stop request...Stopping profile...
,E/SignOutReceiver( 6233): NETWORK_STATE_CHANGED_ACTION
,D/BluetoothAdapterService( 6717): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cf346d2
,D/AudioService(  872): onServiceDisconnected: Bluetooth profile: 1
,D/HeadsetProfile( 1303): Bluetooth service disconnected
,D/SmartBondingService(  872): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
D/A2dpService( 6717): Received stop request...Stopping profile...
V/Avrcp   ( 6717): doQuit
D/StatusBar.NetworkController( 1187): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1187): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1187): refreshSignalCluster - setNWBoosterIndicators(false)
D/A2dpStateMachine( 6717): Exit Disconnected: -1
D/StatusBar.NetworkController( 1187): applyOpen
D/StatusBar.NetworkController( 1187): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1187): applyOpen
D/StatusBar.NetworkController( 1187): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1187): applyOpen
D/StatusBar.NetworkController( 1187): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1187): applyOpen
D/Avrcp   ( 6717): Unregistering previous receiver
D/STATUSBAR-WifiQuickSettingButton( 1187): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1187): Wifi onReceive(0)
D/SecContentProvider2(  872): uri = 20 selection = getPromptCredentialsEnabled
D/STATUSBAR-QSTileView( 1187): onStateChanged: Wi-Fi
D/SecContentProvider2(  872): mCursor = null
,D/HotspotTile( 1187): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/HotspotTile( 1187): onReceive : 0, 0
,D/ConnectivityService(  872): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/BluetoothHeadset( 6855): Proxy not attached to service
,D/SmartBondingService(  872): getNetworkEnabled : wifi : false mobile : true
D/WifiCredService( 1303): Action received :android.net.wifi.WIFI_STATE_CHANGED
,D/BluetoothAdapterService( 6717): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cf346d2
D/BluetoothA2dp(  872): Proxy object disconnected
,D/BluetoothA2dp( 1303): Proxy object disconnected
D/A2dpProfile( 1303): Bluetooth service disconnected
D/AudioService(  872): onServiceDisconnected: Bluetooth profile: 2
,D/HidService( 6717): Received stop request...Stopping profile...
D/HidService( 6717): Stopping Bluetooth HidService
,W/BluetoothHidServiceJni( 6717): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 6717): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 6717): Cleaning up Bluetooth GID callback object
D/BluetoothAdapterService( 6717): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cf346d2
,D/BluetoothInputDevice( 1303): Proxy object disconnected
D/HidProfile( 1303): Bluetooth service disconnected
D/HealthService( 6717): Received stop request...Stopping profile...
D/BluetoothAdapterService( 6717): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cf346d2
,D/PanService( 6717): Received stop request...Stopping profile...
D/BluetoothAdapterService( 6717): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cf346d2
,D/BluetoothPan(  872): BluetoothPAN Proxy object disconnected
,D/BluetoothMapService( 6717): Received stop request...Stopping profile...
,D/BluetoothA2dp( 2947): Proxy object disconnected
,D/BluetoothPan( 1303): BluetoothPAN Proxy object disconnected
D/PanProfile( 1303): Bluetooth service disconnected
,D/BluetoothAdapterService( 6717): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cf346d2
,D/NearbySettings( 1303): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
V/NearbySettings( 1303): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1303): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/SapService( 6717): Received stop request...Stopping profile...
D/SapService( 6717): Stopping Bluetooth SapService
D/BluetoothAdapterService( 6717): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cf346d2
,E/BluetoothAdapterService(485705426)( 6717): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 6717): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 6717): Profile still running: com.android.bluetooth.hid.HidService
D/ConnectivityService(  872): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1303): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1303): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
W/BluetoothHeadsetServiceJni( 6717): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 6717): Cleaning up Bluetooth Handsfree callback object
E/BluetoothAdapterService(485705426)( 6717): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 6717): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 6717): Profile still running: com.android.bluetooth.hid.HidService
D/BluetoothA2dp( 6717): Proxy object disconnected
D/BluetoothAdapterService( 6717): Bluetooth A2dp source service disconnected
,I/GKI_LINUX( 6717): gki_task task_id=2 [A2DP-MEDIA] terminating
I/NearbySettings( 1303): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1303): MountReceiver.mPrefHandler - 7002
I/GKI_LINUX( 6717): GKI_exit_task 2 done
I/GKI_LINUX( 6717): GKI_shutdown(): task [A2DP-MEDIA] terminated
V/Avrcp   ( 6717): cleanup
D/BluetoothMap( 1303): Proxy object disconnected
D/MapProfile( 1303): Bluetooth service disconnected
D/Bluetoothsap( 1303): BluetoothSAP Proxy object disconnected
E/BluetoothAdapterService(485705426)( 6717): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 6717): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 6717): Profile still running: com.android.bluetooth.map.BluetoothMapService
,D/SapProfile( 1303): Bluetooth service disconnected
E/BluetoothAdapterService(485705426)( 6717): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 6717): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 6717): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothHealthServiceJni( 6717): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 6717): Cleaning up Bluetooth Health object
,E/BluetoothAdapterService(485705426)( 6717): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 6717): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 6717): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothPanServiceJni( 6717): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 6717): Cleaning up Bluetooth PAN callback object
,E/BluetoothAdapterService(485705426)( 6717): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 6717): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 6717): Profile still running: com.broadcom.bt.service.sap.SapService
,E/BluetoothAdapterService(485705426)( 6717): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
W/BluetoothSAPServiceJni( 6717): ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
D/FileShare-Server( 6428): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
W/BluetoothSAPServiceJni( 6717): ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,D/BluetoothAdapterState( 6717): CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 6717): Setting state to 10
I/BluetoothAdapterState( 6717): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 6717): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 6717): updateAdapterState state is 10
D/BluetoothAdapterService( 6717): Autoconnection is available 
D/BluetoothAdapterService( 6717): updateAdapterState prevState = 13newState = 10
I/BluetoothAdapterState( 6717): Entering OffState
,D/WifiDirectBR( 6837): WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,D/WifiDirectBR( 6837): WifiDirectBroadcastReceiver::onReceive(), Action : WifiP2pManager.WIFI_P2P_CONNECTION_CHANGED_ACTION, isConnected() == false
,W/ContextImpl( 6837): Implicit intents with startService are not safe: Intent { act=com.samsung.shareshot.IShareShotService } android.content.ContextWrapper.stopService:538 android.content.ContextWrapper.stopService:538 com.samsung.shareshot.WifiDirectBroadcastReceiver.onReceive:59 
D/BluetoothInputDevice( 1303): onBluetoothStateChange: up=false
,D/WifiDirectBR( 6837): stopServiceTest : false
,D/BluetoothA2dp( 2947): onBluetoothStateChange: up=false
,D/WifiDirectBR( 6837): WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.STATE_CHANGED
,D/BluetoothA2dp( 6717): onBluetoothStateChange: up=false
,D/BluetoothA2dp(  872): onBluetoothStateChange: up=false
,D/BluetoothPbap( 1303): onBluetoothStateChange: up=false
,I/Hs20UtilService( 1303): Starting #7
D/Bluetoothsap( 1303): onBluetoothStateChange: up=false
D/Bluetoothsap( 1303): Unbinding service...
,I/Hs20UtilService( 1303): Message received 5007
,D/NearbySettings( 1303): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1303): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1303): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1303): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1303): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1303): MountReceiver.onReceive - Set preference state off
,I/wpa_supplicant( 6718): Blacklist: Clear (all) 
V/NearbySettings( 1303): MountReceiver.mPrefHandler - 7002
D/BluetoothMap( 1303): onBluetoothStateChange: up=false
,D/BluetoothA2dp( 1303): onBluetoothStateChange: up=false
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BluetoothManagerService(  872): Broadcasting onBluetoothServiceDown() to 12 receivers.
,D/BluetoothManagerService(  872): Broadcasting onBluetoothServiceUp() to 0 receivers.
,E/SignOutReceiver( 6233): NETWORK_STATE_CHANGED_ACTION
,W/InputMethodManagerService(  872): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService(  872): [BT Setting State] State =10
I/InputMethodManagerService(  872): [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,D/BluetoothAdapter( 1187): 275806819: getState() :  mService = null. Returning STATE_OFF
D/BluetoothTile( 1187): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothTile( 1187):  onBluetoothPairedDevicesChanged:
D/BluetoothAdapter( 1187): 275806819: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1187): 275806819: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 1187): 275806819: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1187): 275806819: getState() :  mService = null. Returning STATE_OFF
I/GKI_LINUX( 6717): gki_task task_id=1 [BTIF] terminating
D/STATUSBAR-QSTileView( 1187): onStateChanged: Bluetooth
,D/BluetoothManager( 6855): [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothEventManager( 1303): Received android.bluetooth.adapter.action.STATE_CHANGED
D/StatusBarManagerService(  872): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020319 level=0 visible=true num=0 )
I/SamsungIME( 1708): STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,I/GKI_LINUX( 6717): GKI_exit_task 1 done
I/GKI_LINUX( 6717): GKI_shutdown(): task [BTIF] terminated
,D/StatusBarManagerService(  872): setIconVisibility slot=bluetooth visible=false
I/BluetoothServiceJni( 6717): cleanupNative: return from cleanup
D/PhoneStatusBar( 1187): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020319 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020319 level=0 visible=false num=0 )
,D/BluetoothAdapter( 1397): 1027207889: getState() :  mService = null. Returning STATE_OFF
,I/wpa_supplicant( 6718): p2p0: CTRL-EVENT-TERMINATING 
,D/BluetoothAdapter( 1397): 1027207889: getState() :  mService = null. Returning STATE_OFF
,I/art     ( 6717): System.exit called, status: 0
,I/wpa_supplicant( 6718): CTRL-EVENT-DISCONNECTED bssid=C0.AA.4A reason=3 locally_generated=1
I/wpa_supplicant( 6718): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 6718): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.4A SSID=4E473730303567
I/wpa_supplicant( 6718): wlan0: State: DISCONNECTED -> DISCONNECTED
,I/AndroidRuntime( 6717): VM exiting with result code 0, cleanup skipped.
,D/ConnectivityService(  872): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  872): calling update connectivity
D/ConnectivityService(  872):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  872):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/EntConnectivity(  872): Not allowed due to - mEnabled false
D/ConnectivityService(  872): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  872):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 1187): CM callback handler got msg 524292
,D/ConnectivityService(  872): sending notification LOST for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/SignOutReceiver( 6233): WIFI_STATE_CHANGED_ACTION
,V/Nat464Xlat(  872): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  872): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  872): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  872): Disconnected - quitting
D/ConnectivityService(  872): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  872): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1440): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/CSLegacyTypeTracker(  872): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,fe80::ea50:8bff:fede:28a3/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
,D/CSLegacyTypeTracker(  872): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
,D/ConnectivityService(  872): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityManager.CallbackHandler( 1748): CM callback handler got msg 524292
,D/ConnectivityService(  872): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  872): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/Tethering(  872): MasterInitialState.processMessage what=3
D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/NtpTrustedTime(  872): forceRefresh() from cache miss
D/SecurityLogAgent( 6699): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6699): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6699): StateMachine : Current State = 1
D/SecurityLogAgent( 6699): StateMachine : Changed Current State = 1
,V/NetworkStats(  872): updateIfacesLocked()
V/NetworkStats(  872): performPollLocked(flags=0x1)
E/ConnectivityService(  872): updateNetworkInfo()
E/ConnectivityService(  872): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,fe80::ea50:8bff:fede:28a3/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/ConnectivityService(  872): NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/SmartBondingService(  872): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  872): getSBEnabled() enabled =false
D/SmartBondingService(  872): getSBEnabled() enabled =false
D/SmartBondingService(  872): getSBEnabled() enabled =false
,D/NetworkStatsFactory(  872): UpdateStatsForKnox
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/ConnectivityService(  872): updateNetworkInfo()
,D/StatusBar.NetworkController( 1187): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1187): updateDataNetType()
D/StatusBar.NetworkController( 1187): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1187): updateLTEICONDataNetType:0
,D/NtpTrustedTime(  872): forceRefresh Fail.
V/NetworkStats(  872): performPollLocked() took 4ms
,D/SmartBondingService(  872): getNetworkEnabled : wifi : false mobile : true
,D/ConnectivityService(  872): ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
,D/StatusBar.NetworkController( 1187): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1187): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1187): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/NtpTrustedTime(  872): forceRefresh() from cache miss
,D/NtpTrustedTime(  872): forceRefresh Fail.
V/NetworkStats(  872): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/StatusBar.NetworkController( 1187): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1187): onWifiSignalChanged enabled=false enabledDesc:null
,D/StatusBar.NetworkController( 1187): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1187): applyOpen
D/StatusBar.NetworkController( 1187): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1187): applyOpen
,D/StatusBar.NetworkController( 1187): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1187): applyOpen
D/StatusBar.NetworkController( 1187): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1187): applyOpen
,W/ContextImpl( 1303): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,I/wpa_supplicant( 6718): Blacklist: Clear (all) 
,D/DockEventReceiver( 1303): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 1303): onReceive
,I/ActivityManager(  872): Process com.android.bluetooth (pid 6717)(adj 0) has died(262,1474)
,D/AuthorizationBluetoothService( 1397): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/FileWriteThread_Telephony( 1440): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1440): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1440): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1440): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1440): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1440): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1440): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1440): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1440): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1440): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1440): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1440): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1440): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1440): FileWriteThread : threadType = 3
,D/Tethering(  872): InitialState.processMessage what=4
,E/Tethering(  872): No numeric data
,I/wpa_supplicant( 6718): wlan0: CTRL-EVENT-TERMINATING 
,D/NtpTrustedTime(  872): forceRefresh() from cache miss
,D/Tethering(  872): sendTetherStateChangedBroadcast 0, 0, 0
,D/NtpTrustedTime(  872): forceRefresh Fail.
,D/HotspotTile( 1187): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1187): updateTetherState():false, false
,V/NetworkStats(  872): performPollLocked(flags=0x1)
,D/NetworkStatsFactory(  872): UpdateStatsForKnox
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/NetworkStats(  872): performPollLocked() took 12ms
,D/NtpTrustedTime(  872): forceRefresh() from cache miss
,D/NtpTrustedTime(  872): forceRefresh Fail.
,E/WifiStateMachine(  872): skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
D/WifiNative-HAL(  872): callSECApiBoolean - ID [21]
,D/SmartBondingService(  872): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,D/StatusBar.NetworkController( 1187): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1187): onWifiSignalChanged enabled=false enabledDesc:null
,D/STATUSBAR-WifiQuickSettingButton( 1187): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1187): Wifi onReceive(1)
,D/HotspotTile( 1187): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/STATUSBAR-QSTileView( 1187): onStateChanged: Wi-Fi
D/SmartBondingService(  872): getNetworkEnabled : wifi : false mobile : true
,D/WifiCredService( 1303): Action received :android.net.wifi.WIFI_STATE_CHANGED
,D/HotspotTile( 1187): onReceive : 1, 0
W/Settings( 1397): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/SignOutReceiver( 6233): WIFI_STATE_CHANGED_ACTION
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 6699): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6699): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6699): StateMachine : Current State = 1
D/SecurityLogAgent( 6699): StateMachine : Changed Current State = 1
,E/WifiStateMachine(  872): skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,D/ConnectivityService(  872): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  872): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider(  872): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  872): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  872): getSBEnabled() enabled =false
D/SmartBondingService(  872): getSBEnabled() enabled =false
D/SmartBondingService(  872): getSBEnabled() enabled =false
,I/ApplicationPolicy(  872): updateDataUsageMap
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NetworkMonitor( 5126): type=WIFI subType= reason=null isConnected=false
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3161): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  872): getNetworkEnabled : wifi : false mobile : true
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3161): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,I/PCWCLIENTTRACE_PushUtil( 5933): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5933): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5933): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5933): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
I/PCWCLIENTTRACE_SYSTEMReceiver( 5933): noConnectivity : true
,I/DIAGMON_AGENT( 7001): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7001): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/FOTA_Client( 7028): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7028): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 7028): [lIIIIlIlIlIlllllllll(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/KLMS-2.4.511: ( 7056): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.511: ( 7056): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1449748918492
,I/KLMS-2.4.511: ( 7056): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.511: ( 7056): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.511: ( 7056): StateImplV2(): networkChangeListener().END
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SO_AGENT( 7102): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 7145): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,I/SA      ( 7163): [OR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOB6 PSS = 5.701607447389803  ]
,I/SA      ( 7163): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,I/SA      ( 7163): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 7163): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 7163): [OR] == isSIMCardReady false ==
,I/SA      ( 7163): [SCU] == networkStateCheck == false
I/SA      ( 7163): [OR] onReceive END
,I/SCloudBackupReceiver( 7186): Other Intent
,I/KnoxUsageLogPro( 6444): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 6444): premStatus:2
,I/KnoxUsageLogPro( 6444): isEulaShown : false
,I/KnoxUsageLogPro( 6444): KnoxUsageReceiver onReceive : not Processible, just return
,E/SPPClientService( 7145): [[SystemStateMonitorService]] No Active Internet
,D/QuickConnect( 7267): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7267): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 7267): PeriphStartReceiver.onReceive - no need to start
,D/RCPManagerService(  872): exchangeData() failure , invalid userId
,D/RCPManagerService(  872): exchangeData() failure , invalid userId
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 6699): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 6699): KnoxConfiguration : Current State Mapping Found 
,D/SecurityLogAgent( 6699): StateMachine : Current State = 1
D/SecurityLogAgent( 6699): StateMachine : Changed Current State = 1
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/iu.Environment( 1748): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1748): num queued entries: 0
,I/iu.UploadsManager( 1748): num updated entries: 0
,I/iu.SyncManager( 1748): NEXT; no task
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 300, PST = 300, CUR = 450
,V/AlarmManager(  872): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1187): handleTimeUpdate
,D/KeyguardEffectViewController( 1187): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1187): *** don't update sliding image ***
,D/DateView( 1187): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1187): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD ON
,E/Watchdog(  872): !@Sync 13
,E/SMD     (  290): DCD ON
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD ON
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,W/ContextImpl(  872): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  872): SIOP:: AP = 300, PST = 300, CUR = 450
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  872): stay LED for fully charged
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
I/MotionRecognitionService(  872): Plugged
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD ON
,W/Atfwd_Sendcmd(  338): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 300, PST = 300, CUR = 450
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,W/ContextImpl(  872): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  872): SIOP:: AP = 290, PST = 299, CUR = 450
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD ON
,E/Watchdog(  872): !@Sync 14
,E/SMD     (  290): DCD ON
,I/Atfwd_Sendcmd(  338): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  338): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/PowerManagerService(  872): [PWL] Off : 330s ago
,I/PowerManagerService(  872): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  872): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  872): [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=872, ws=null) (elapsedTime=43053)
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 290, PST = 298, CUR = 450
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,W/ContextImpl(  872): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  872): SIOP:: AP = 290, PST = 297, CUR = 450
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD ON
,D/ConnectivityService(  872): Failed to find a new network - expiring NetTransition Wakelock
,E/SMD     (  290): DCD ON
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,V/AlarmManager(  872): waitForAlarm result :8
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD ON
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,D/SSRM:n  (  872): SIOP:: AP = 290, PST = 296, CUR = 450
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  872): Plugged
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
I/MotionRecognitionService(  872): setPowerConnected  = true
,D/BatteryService(  872): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  338): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  290): DCD ON
,E/Watchdog(  872): !@Sync 15
,E/SMD     (  290): DCD ON
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD ON
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,W/ContextImpl(  872): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,D/SSRM:n  (  872): SIOP:: AP = 290, PST = 295, CUR = 450
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD ON
,W/Atfwd_Sendcmd(  338): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 290, PST = 294, CUR = 450
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  872): Plugged
I/MotionRecognitionService(  872): setPowerConnected  = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  872): stay LED for fully charged
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/bootchecker(  333): bootchecker wake up!!
,E/SMD     (  290): DCD ON
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD ON
,W/Atfwd_Sendcmd(  338): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  290): DCD ON
,W/ContextImpl(  872): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  872): SIOP:: AP = 290, PST = 293, CUR = 450
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  872): Plugged
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  872): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,E/SMD     (  290): DCD ON
,E/Watchdog(  872): !@Sync 16
,E/SMD     (  290): DCD ON
,I/PowerManagerService(  872): [PWL] Off : 390s ago
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 290, PST = 292, CUR = 450
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  872): stay LED for fully charged
D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  872): Plugged
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
I/MotionRecognitionService(  872): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD ON
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  338): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  290): DCD ON
,W/ContextImpl(  872): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  872): SIOP:: AP = 290, PST = 291, CUR = 450
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD ON
,E/Watchdog(  872): !@Sync 17
,E/SMD     (  290): DCD ON
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD ON
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,W/ContextImpl(  872): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,D/SSRM:n  (  872): SIOP:: AP = 290, PST = 290, CUR = 450
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  872): stay LED for fully charged
D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  872): Plugged
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,E/SMD     (  290): DCD ON
,W/Atfwd_Sendcmd(  338): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  872): stay LED for fully charged
D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  872): Plugged
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,W/ContextImpl(  872): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  872): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  872): stay LED for fully charged
D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  872): Plugged
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,E/Watchdog(  872): !@Sync 18
,E/SMD     (  290): DCD ON
,I/Atfwd_Sendcmd(  338): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  338): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  872): stay LED for fully charged
D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  872): Plugged
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,I/PowerManagerService(  872): [PWL] Off : 455s ago
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,W/ContextImpl(  872): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  872): stay LED for fully charged
D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  872): Plugged
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  872): stay LED for fully charged
D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  872): Plugged
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/Atfwd_Daemon(  338): Stop the daemon....
,E/SMD     (  290): DCD ON
,E/Watchdog(  872): !@Sync 19
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,W/ContextImpl(  872): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  872): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  872): Plugged
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  872): stay LED for fully charged
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,W/ContextImpl(  872): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  872): SIOP:: AP = 290, PST = 290, CUR = 450
,D/TimaService(  872): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  872): TimaServiceHandler.handleMessage what =1
,D/TimaService(  872): TIMA: checkEvent, operation: 50000 subject: 10000
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD ON
,E/Watchdog(  872): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel(  872): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  872): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  872): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  872): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  872): stay LED for fully charged
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  872): Plugged
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,W/ContextImpl(  872): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  872): stay LED for fully charged
D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  872): Plugged
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService(  872): [PWL] Off : 525s ago
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  872): Plugged
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/BatteryService(  872): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,E/Watchdog(  872): !@Sync 21
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  872): Plugged
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
I/MotionRecognitionService(  872): setPowerConnected  = true
,D/BatteryService(  872): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  872): Plugged
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/BatteryService(  872): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  872): Plugged
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  872): stay LED for fully charged
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,E/Watchdog(  872): !@Sync 22
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  872): stay LED for fully charged
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
I/MotionRecognitionService(  872): Plugged
I/MotionRecognitionService(  872): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,E/Watchdog(  872): !@Sync 23
,E/SMD     (  290): DCD ON
,I/PowerManagerService(  872): [PWL] Off : 600s ago
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
I/MotionRecognitionService(  872): Plugged
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/BatteryService(  872): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
I/MotionRecognitionService(  872): Plugged
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  872): stay LED for fully charged
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  872): stay LED for fully charged
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  872): Plugged
I/MotionRecognitionService(  872): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,E/Watchdog(  872): !@Sync 24
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  872): stay LED for fully charged
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  872): Plugged
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  872): stay LED for fully charged
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  872): Plugged
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
I/MotionRecognitionService(  872): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  872): !@Sync 25
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  872): stay LED for fully charged
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  872): Plugged
I/MotionRecognitionService(  872): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  872): stay LED for fully charged
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  872): Plugged
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
I/MotionRecognitionService(  872): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,I/PowerManagerService(  872): [PWL] Off : 680s ago
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  872): stay LED for fully charged
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  872): Plugged
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
I/MotionRecognitionService(  872): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  872): !@Sync 26
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,V/AlarmManager(  872): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1187): handleTimeUpdate
,D/KeyguardEffectViewController( 1187): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1187): *** don't update sliding image ***
,D/LightsService(  872): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,E/LightSensor(  872): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/SensorManager(  872): registerListener :: 6, MAX88921 RGB Sensor, 200000, 0,  
,D/DateView( 1187): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1187): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/LightsService(  872): [SvcLED]  onSensorChanged::light value = 54
,E/LightSensor(  872): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager(  872): unregisterListener ::   
,D/LightsService(  872): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  872): Plugged
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/BatteryService(  872): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  872): Plugged
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  872): stay LED for fully charged
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,V/AlarmManager(  872): waitForAlarm result :8
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  872): Plugged
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  872): stay LED for fully charged
,E/Watchdog(  872): !@Sync 27
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  872): Plugged
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  872): stay LED for fully charged
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  872): stay LED for fully charged
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
I/MotionRecognitionService(  872): Plugged
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  872): stay LED for fully charged
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  872): Plugged
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  872): !@Sync 28
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  872): stay LED for fully charged
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
I/MotionRecognitionService(  872): Plugged
I/MotionRecognitionService(  872): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 290, PST = 290, CUR = 450
,I/PowerManagerService(  872): [PWL] Off : 765s ago
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  872): stay LED for fully charged
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  872): Plugged
I/MotionRecognitionService(  872): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 289, CUR = 450
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  872): stay LED for fully charged
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  872): Plugged
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  872): !@Sync 29
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 288, CUR = 450
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  872): stay LED for fully charged
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  872): Plugged
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 287, CUR = 450
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  872): stay LED for fully charged
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  872): Plugged
I/MotionRecognitionService(  872): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/TimaService(  872): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  872): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  872): TimaServiceHandler.handleMessage what =1,
,D/SSRM:n  (  872): SIOP:: AP = 290, PST = 287, CUR = 450
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  872): stay LED for fully charged
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  872): Plugged
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
I/MotionRecognitionService(  872): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/TLC_TIMA_PKM_measure_kernel(  872): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  872): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,E/Watchdog(  872): !@Sync 30
,D/TimaService(  872): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  872): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 290, PST = 287, CUR = 450
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 290, PST = 287, CUR = 450
,E/SMD     (  290): DCD ON
,V/AlarmManager(  872): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1187): handleTimeUpdate
,D/KeyguardEffectViewController( 1187): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1187): *** don't update sliding image ***
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/DateView( 1187): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1187): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  290): DCD ON
,V/AlarmManager(  872): waitForAlarm result :8
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 290, PST = 287, CUR = 450
,E/SMD     (  290): DCD ON
,E/Watchdog(  872): !@Sync 31
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 286, CUR = 450
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  872): Plugged
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/BatteryService(  872): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 285, CUR = 450
,I/PowerManagerService(  872): [PWL] Off : 855s ago
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  872): Plugged
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/BatteryService(  872): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 284, CUR = 450
,E/Watchdog(  872): !@Sync 32
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  872): Plugged
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/BatteryService(  872): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 284, CUR = 450
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 284, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  872): Plugged
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/BatteryService(  872): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 284, CUR = 450
,E/Watchdog(  872): !@Sync 33
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  872): Plugged
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/BatteryService(  872): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 283, CUR = 450
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 282, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  872): Plugged
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/BatteryService(  872): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 281, CUR = 450
,E/Watchdog(  872): !@Sync 34
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  872): Plugged
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/BatteryService(  872): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  872): Plugged
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/BatteryService(  872): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService(  872): [PWL] Off : 950s ago
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  872): !@Sync 35
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  872): Plugged
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/BatteryService(  872): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  872): Plugged
I/MotionRecognitionService(  872): setPowerConnected  = true
,D/BatteryService(  872): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  872): Plugged
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  872): stay LED for fully charged
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  872): !@Sync 36
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  872): !@Sync 37
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  872): Plugged
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/BatteryService(  872): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  872): !@Sync 38
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  872): Plugged
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
I/MotionRecognitionService(  872): setPowerConnected  = true
,D/BatteryService(  872): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService(  872): [PWL] Off : 1050s ago
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  872): Plugged
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/BatteryService(  872): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  872): !@Sync 39
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  872): Plugged
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  872): stay LED for fully charged
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  872): Plugged
I/MotionRecognitionService(  872): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  872): stay LED for fully charged
,E/SMD     (  290): DCD ON
,D/TimaService(  872): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  872): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  872): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService(  872): User[0] Flushing usage stats to disk
,I/ApplicationUsage(  872): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage(  872): Updating Usage Statistics in DB @ 1449749734510
,I/ApplicationUsageDb(  872): ::getAppControlDB: Exception to create DB
W/System.err(  872): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  872): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  872): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  872): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  872): ::getAppControlDB: Exception to create DB
W/System.err(  872): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  872): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  872): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  872): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  872): ::getAppControlDB: Exception to create DB
,W/System.err(  872): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
,W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  872): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  872): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  872): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  872): ::getAppControlDB: Exception to create DB
W/System.err(  872): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  872): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  872): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  872): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  872): ::getAppControlDB: Exception to create DB
W/System.err(  872): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  872): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  872): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  872): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  872): ::getAppControlDB: Exception to create DB
,W/System.err(  872): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  872): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  872): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  872): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  872): ::getAppControlDB: Exception to create DB
,W/System.err(  872): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  872): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  872): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  872): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  872): ::getAppControlDB: Exception to create DB
W/System.err(  872): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  872): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  872): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  872): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  872): ::getAppControlDB: Exception to create DB
,W/System.err(  872): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  872): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  872): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  872): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  872): ::getAppControlDB: Exception to create DB
W/System.err(  872): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  872): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  872): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  872): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  872): ::getAppControlDB: Exception to create DB
W/System.err(  872): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  872): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  872): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  872): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  872): ::getAppControlDB: Exception to create DB
,W/System.err(  872): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  872): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  872): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  872): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  872): ::getAppControlDB: Exception to create DB
W/System.err(  872): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
,W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  872): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  872): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  872): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  872): ::getAppControlDB: Exception to create DB
,W/System.err(  872): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  872): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  872): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  872): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  872): ::getAppControlDB: Exception to create DB
W/System.err(  872): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  872): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  872): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  872): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  872): ::getAppControlDB: Exception to create DB
W/System.err(  872): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  872): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  872): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  872): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  872): ::getAppControlDB: Exception to create DB
W/System.err(  872): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  872): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  872): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  872): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  872): ::getAppControlDB: Exception to create DB
,W/System.err(  872): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  872): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  872): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  872): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  872): ::getAppControlDB: Exception to create DB
,W/System.err(  872): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  872): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  872): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  872): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  872): ::getAppControlDB: Exception to create DB
W/System.err(  872): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  872): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  872): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  872): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  872): ::getAppControlDB: Exception to create DB
,W/System.err(  872): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  872): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  872): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  872): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  872): ::getAppControlDB: Exception to create DB
W/System.err(  872): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  872): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  872): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  872): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  872): ::getAppControlDB: Exception to create DB
,W/System.err(  872): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  872): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  872): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  872): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  872): ::getAppControlDB: Exception to create DB
,W/System.err(  872): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  872): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  872): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  872): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  872): ::getAppControlDB: Exception to create DB
,W/System.err(  872): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  872): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  872): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  872): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  872): ::getAppControlDB: Exception to create DB
W/System.err(  872): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  872): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  872): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  872): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  872): ::getAppControlDB: Exception to create DB
W/System.err(  872): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  872): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  872): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  872): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  872): ::getAppControlDB: Exception to create DB
,W/System.err(  872): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  872): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  872): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  872): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  872): ::getAppControlDB: Exception to create DB
W/System.err(  872): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  872): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  872): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  872): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  872): ::getAppControlDB: Exception to create DB
,W/System.err(  872): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  872): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  872): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  872): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  872): ::getAppControlDB: Exception to create DB
W/System.err(  872): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  872): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  872): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  872): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  872): ::getAppControlDB: Exception to create DB
W/System.err(  872): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  872): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  872): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  872): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  872): ::getAppControlDB: Exception to create DB
W/System.err(  872): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  872): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  872): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  872): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  872): ::getAppControlDB: Exception to create DB
W/System.err(  872): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  872): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  872): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  872): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  872): ::getAppControlDB: Exception to create DB
W/System.err(  872): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  872): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  872): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  872): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  872): ::getAppControlDB: Exception to create DB
W/System.err(  872): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  872): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  872): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  872): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  872): ::getAppControlDB: Exception to create DB
W/System.err(  872): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  872): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  872): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  872): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  872): ::getAppControlDB: Exception to create DB
W/System.err(  872): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  872): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  872): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  872): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  872): ::getAppControlDB: Exception to create DB
W/System.err(  872): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  872): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  872): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  872): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  872): ::getAppControlDB: Exception to create DB
W/System.err(  872): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  872): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  872): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  872): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  872): ::getAppControlDB: Exception to create DB
W/System.err(  872): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  872): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  872): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  872): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  872): ::getAppControlDB: Exception to create DB
W/System.err(  872): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  872): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  872): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  872): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  872): ::getAppControlDB: Exception to create DB
W/System.err(  872): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  872): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  872): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  872): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  872): ::getAppControlDB: Exception to create DB
W/System.err(  872): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  872): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  872): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  872): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  872): ::getAppControlDB: Exception to create DB
,W/System.err(  872): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  872): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  872): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  872): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  872): ::getAppControlDB: Exception to create DB
W/System.err(  872): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  872): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  872): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  872): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  872): ::getAppControlDB: Exception to create DB
W/System.err(  872): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  872): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  872): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  872): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  872): ::getAppControlDB: Exception to create DB
W/System.err(  872): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  872): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  872): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  872): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  872): ::getAppControlDB: Exception to create DB
W/System.err(  872): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  872): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  872): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  872): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  872): ::getAppControlDB: Exception to create DB
W/System.err(  872): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  872): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  872): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  872): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  872): ::getAppControlDB: Exception to create DB
W/System.err(  872): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  872): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  872): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  872): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  872): ::getAppControlDB: Exception to create DB
W/System.err(  872): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  872): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  872): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  872): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  872): ::getAppControlDB: Exception to create DB
W/System.err(  872): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  872): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  872): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  872): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  872): ::getAppControlDB: Exception to create DB
W/System.err(  872): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  872): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  872): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  872): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  872): ::getAppControlDB: Exception to create DB
W/System.err(  872): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  872): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  872): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  872): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  872): ::getAppControlDB: Exception to create DB
W/System.err(  872): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  872): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  872): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  872): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  872): ::getAppControlDB: Exception to create DB
W/System.err(  872): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  872): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  872): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  872): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  872): ::getApp,ControlDB: Exception to create DB
W/System.err(  872): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  872): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  872): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  872): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  872): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsage(  872): Done Updating Usage Statistics in DB @ 1449749734699
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 290, PST = 281, CUR = 450
,I/TLC_TIMA_PKM_measure_kernel(  872): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  872): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  872): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  872): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  872): !@Sync 40
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  872): Plugged
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/BatteryService(  872): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,V/AlarmManager(  872): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1187): handleTimeUpdate
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/KeyguardEffectViewController( 1187): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1187): *** don't update sliding image ***
,V/AlarmManager(  872): OOI=Alarm{350650e5 type 2 when 1234842 com.google.android.gms}
,D/DateView( 1187): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1187): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 290, PST = 282, CUR = 450
,E/SMD     (  290): DCD ON
,V/AlarmManager(  872): waitForAlarm result :8
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  872): Plugged
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  872): stay LED for fully charged
D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 282, CUR = 450
,E/Watchdog(  872): !@Sync 41
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 282, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,I/PowerManagerService(  872): [PWL] Off : 1155s ago
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  872): stay LED for fully charged
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
I/MotionRecognitionService(  872): Plugged
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 282, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  872): Plugged
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/BatteryService(  872): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  872): !@Sync 42
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 282, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 282, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  872): Plugged
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  872): stay LED for fully charged
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 282, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  872): Plugged
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/BatteryService(  872): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  872): !@Sync 43
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 282, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  872): Plugged
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/BatteryService(  872): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  872): Plugged
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/BatteryService(  872): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  872): !@Sync 44
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  872): Plugged
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
I/MotionRecognitionService(  872): setPowerConnected  = true
,D/BatteryService(  872): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  872): Plugged
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/BatteryService(  872): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  872): !@Sync 45
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,I/PowerManagerService(  872): [PWL] Off : 1265s ago
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  872): Plugged
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/BatteryService(  872): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  872): Plugged
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/BatteryService(  872): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  872): !@Sync 46
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 280, CUR = 450
,V/AlarmManager(  872): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1187): handleTimeUpdate
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  872): stay LED for fully charged
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService(  872): Plugged
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/KeyguardEffectViewController( 1187): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1187): *** don't update sliding image ***
,D/DateView( 1187): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1187): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/Procstats( 1748): User is not opted-in to Usage & Diagnostics.
,V/AlarmManager(  872): waitForAlarm result :8
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,V/AlarmManager(  872): waitForAlarm result :8
,D/LightsService(  872): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,E/LightSensor(  872): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/SensorManager(  872): registerListener :: 6, MAX88921 RGB Sensor, 200000, 0,  
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1187): handleTimeUpdate
,D/KeyguardEffectViewController( 1187): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1187): *** don't update sliding image ***
,D/DateView( 1187): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1187): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/LightsService(  872): [SvcLED]  onSensorChanged::light value = 64
,E/LightSensor(  872): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager(  872): unregisterListener ::   
,D/LightsService(  872): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/Watchdog(  872): !@Sync 47
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
I/MotionRecognitionService(  872): Plugged
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  872): stay LED for fully charged
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  872): Plugged
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/BatteryService(  872): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/Watchdog(  872): !@Sync 48
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,V/AlarmManager(  872): waitForAlarm result :8
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  872): Plugged
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/BatteryService(  872): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/Watchdog(  872): !@Sync 49
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService(  872): [PWL] Off : 1380s ago
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  872): Plugged
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/BatteryService(  872): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD ON
,D/TimaService(  872): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  872): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  872): TimaServiceHandler.handleMessage what =1
,E/SMD     (  290): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  872): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  872): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  872): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  872): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  872): !@Sync 50
,D/SSRM:n  (  872): SIOP:: AP = 290, PST = 281, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,V/AlarmManager(  872): waitForAlarm result :4
,V/AlarmManager(  872): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  872): <AppSync3 Whitelist>
V/AlarmManager(  872): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1187): handleTimeUpdate
,D/KeyguardEffectViewController( 1187): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1187): *** don't update sliding image ***
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/DateView( 1187): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1187): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/art     ( 1748): Explicit concurrent mark sweep GC freed 19709(1370KB) AllocSpace objects, 26(416KB) LOS objects, 24% free, 22MB/30MB, paused 655us total 47.433ms
,I/EventLogService( 1748): Aggregate from 1449748145273 (log), 1449748145273 (data)
,E/SMD     (  290): DCD ON,
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  872): Plugged
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  872): setPowerConnected  = true,
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  872): stay LED for fully charged
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  290): DCD ON
,V/AlarmManager(  872): waitForAlarm result :8
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  872): Plugged
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/BatteryService(  872): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,E/Watchdog(  872): !@Sync 51
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  872): Plugged
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/BatteryService(  872): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  872): Plugged
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  872): setPowerConnected  = true
D/BatteryService(  872): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,E/Watchdog(  872): !@Sync 52
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  872): Plugged
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/BatteryService(  872): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  872): Plugged
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  872): stay LED for fully charged
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
I/MotionRecognitionService(  872): Plugged
I/MotionRecognitionService(  872): setPowerConnected  = true
,D/BatteryService(  872): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,E/Watchdog(  872): !@Sync 53
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  290): DCD ON
,I/PowerManagerService(  872): [PWL] Off : 1500s ago
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  872): Plugged
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/BatteryService(  872): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,E/Watchdog(  872): !@Sync 54
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  872): Plugged
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/BatteryService(  872): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  872): Plugged
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/BatteryService(  872): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  872): Plugged
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/BatteryService(  872): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,E/Watchdog(  872): !@Sync 55
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  872): Plugged
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/BatteryService(  872): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
I/MotionRecognitionService(  872): Plugged
I/MotionRecognitionService(  872): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  872): stay LED for fully charged
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD ON
,E/Watchdog(  872): !@Sync 56
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
I/MotionRecognitionService(  872): Plugged
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  872): stay LED for fully charged
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  872): Plugged
I/MotionRecognitionService(  872): setPowerConnected  = true
,D/BatteryService(  872): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD ON
,E/Watchdog(  872): !@Sync 57
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService(  872): [PWL] Off : 1625s ago
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  872): Plugged
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/BatteryService(  872): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,E/Watchdog(  872): !@Sync 58
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  872): Plugged
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/BatteryService(  872): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  872): Plugged
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/BatteryService(  872): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  872): Plugged
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  872): stay LED for fully charged
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,E/Watchdog(  872): !@Sync 59
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,D/NetworkStatsFactory(  872): UpdateStatsForKnox
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  872): Plugged
I/MotionRecognitionService(  872): setPowerConnected  = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
D/BatteryService(  872): stay LED for fully charged
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/TimaService(  872): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  872): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  872): TimaServiceHandler.handleMessage what =1
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  872): stay LED for fully charged
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  872): Plugged
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  872): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  872): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  872): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  872): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  872): !@Sync 60
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,V/AlarmManager(  872): waitForAlarm result :8
,D/NtpTrustedTime(  872): forceRefresh() from cache miss
,D/NtpTrustedTime(  872): forceRefresh Fail.
,V/NetworkStats(  872): performPollLocked(flags=0x3)
,D/NetworkStatsFactory(  872): UpdateStatsForKnox
,D/ConnectivityService(  872): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.TIME_TICK
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/KeyguardUpdateMonitor( 1187): handleTimeUpdate
,D/KeyguardEffectViewController( 1187): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1187): *** don't update sliding image ***
,V/NetworkStats(  872): performPollLocked() took 42ms
,I/ProcessStatsService(  872): Prepared write state in 13ms
,I/ProcessStatsService(  872): Prepared write state in 10ms
,D/NtpTrustedTime(  872): forceRefresh() from cache miss
,D/NtpTrustedTime(  872): forceRefresh Fail.
,D/DateView( 1187): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1187): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/GLSActivity( 1397): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1397): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 1397): (HTTPLog)-Static: isSBSettingEnabled false
,E/Auth    ( 1397): [GoogleAccountDataServiceImpl] getToken() failed. Status NETWORK_ERROR, Account: <ELLIDED:1197869880>, App: com.google.android.gms, Service: oauth2: email
,I/ProcessStatsService(  872): Pruning old procstats: /data/system/procstats/state-2015-12-09-18-11-15.bin
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 280, CUR = 450
,V/AlarmManager(  872): waitForAlarm result :8
,E/SMD     (  290): DCD ON,
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
I/MotionRecognitionService(  872): Plugged
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  872): stay LED for fully charged
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  872): !@Sync 61
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  872): Plugged
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/BatteryService(  872): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,I/PowerManagerService(  872): [PWL] Off : 1755s ago
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  872): Plugged
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/BatteryService(  872): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  872): Plugged
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/BatteryService(  872): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  872): !@Sync 62
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  872): Plugged
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/BatteryService(  872): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  872): !@Sync 63
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  872): Plugged
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/BatteryService(  872): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  872): Plugged
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  872): stay LED for fully charged
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  872): !@Sync 64
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  872): Plugged
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/BatteryService(  872): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  872): Plugged
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,D/BatteryService(  872): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  872): Plugged
,D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
,I/MotionRecognitionService(  872): setPowerConnected  = true
,D/BatteryService(  872): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  872): !@Sync 65
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD ON
,D/SSRM:n  (  872): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 7776): 
D/AndroidRuntime( 7776): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7776): CheckJNI is OFF
D/AndroidRuntime( 7776): readGMSProperty: start
D/AndroidRuntime( 7776): readGMSProperty: already setted!!
D/AndroidRuntime( 7776): readGMSProperty: end
D/AndroidRuntime( 7776): addProductProperty: start
E/AffinityControl( 7776): AffinityControl: registerfunction enter
D/AndroidRuntime( 7776): Calling main entry com.android.commands.pm.Pm
D/PersonaManagerService(  872): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager(  872): START PACKAGE DELETE: observer{297468867}
D/PackageManager(  872): pkg{<packageName>}
D/PackageManager(  872): user{0}
D/PackageManager(  872): caller{2000}
D/PackageManager(  872): flags{3}
D/PersonaManagerService(  872): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  872): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  872): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  872): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  872): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService(  872): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  872): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  872): getApplicationUninstallationEnabled
D/ApplicationPolicy(  872): getApplicationUninstallationEnabled :  enabled true
D/PackageManager(  872): !@killApplicatoin: 10279, uninstall pkg
I/ActivityManager(  872): Force stopping com.test.thalitest appid=10279 user=-1: uninstall pkg
I/ActivityManager(  872): Killing 6606:com.test.thalitest/u0a279 (adj 0): stop com.test.thalitest
W/PackageSettings(  872): Skipping PackageSetting{2cc1b190 com.example.hello/10268} due to missing metadata
I/WindowState(  872): WIN DEATH: Window{1f1121db u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger(  254): id=13 Removed NainActivit (6/8)
I/SurfaceFlinger(  254): id=13 Removed NainActivit (-2/8)
I/SurfaceFlinger(  254): id=13 Removed NainActivit (-2/8)
D/PointerIcon(  872): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  872): setMouseCustomIcon IconType is same.101
D/PointerIcon(  872): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  872): setHoveringSpenCustomIcon IconType is same.1
I/ActivityManager(  872): Killing 7407:com.android.calendar/u0a172 (adj 13): empty for 1805s
I/ActivityManager(  872): Killing 7376:com.sec.android.widgetapp.SPlannerAppWidget/u0a171 (adj 13): empty for 1805s
I/ActivityManager(  872): Killing 7335:com.android.providers.calendar/u0a51 (adj 13): empty for 1806s
I/ActivityManager(  872): Killing 5217:com.sec.android.gallery3d/u0a53 (adj 13): empty for 1814s
I/ActivityManager(  872): Killing 6069:com.sec.android.provider.badge/u0a92 (adj 13): empty for 1820s
I/ActivityManager(  872): Killing 5687:com.sec.android.widgetapp.activeapplicationwidget/u0a182 (adj 13): empty for 1874s
I/ActivityManager(  872): Killing 6342:com.sec.android.widgetapp.dualclockdigital/u0a115 (adj 15): empty for 1878s
I/ActivityManager(  872): Killing 6324:com.sec.android.widgetapp.digitalclock/u0a109 (adj 15): empty for 1878s
I/ActivityManager(  872): Killing 6044:com.android.mms/u0a55 (adj 15): empty for 1878s
D/CountryDetector(  872): No listener is left
I/ActivityManager(  872): Killing 5514:com.android.vending/u0a33 (adj 15): empty for 1883s
I/ActivityManager(  872): Killing 6459:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): empty for 1884s
I/ActivityManager(  872):   Force finishing activity ActivityRecord{8c81ead u0 com.test.thalitest/.MainActivity t3}
D/FocusedStackFrame(  872): Set to : 0
W/ActivityManager(  872): Spurious death for ProcessRecord{33983440 6606:com.test.thalitest/u0a279}, curProc for 6606: null
W/libprocessgroup(  872): failed to open /acct/uid_10172/pid_7407/cgroup.procs: No such file or directory
W/libprocessgroup(  872): failed to open /acct/uid_10171/pid_7376/cgroup.procs: No such file or directory
W/libprocessgroup(  872): failed to open /acct/uid_10051/pid_7335/cgroup.procs: No such file or directory
W/libprocessgroup(  872): failed to open /acct/uid_10053/pid_5217/cgroup.procs: No such file or directory
W/libprocessgroup(  872): failed to open /acct/uid_10092/pid_6069/cgroup.procs: No such file or directory
W/libprocessgroup(  872): failed to open /acct/uid_10182/pid_5687/cgroup.procs: No such file or directory
W/libprocessgroup(  872): failed to open /acct/uid_10115/pid_6342/cgroup.procs: No such file or directory
W/libprocessgroup(  872): failed to open /acct/uid_10109/pid_6324/cgroup.procs: No such file or directory
W/libprocessgroup(  872): failed to open /acct/uid_10055/pid_6044/cgroup.procs: No such file or directory
W/libprocessgroup(  872): failed to open /acct/uid_10033/pid_5514/cgroup.procs: No such file or directory
W/libprocessgroup(  872): failed to open /acct/uid_1000/pid_6459/cgroup.procs: No such file or directory
D/ConnectivityService(  872): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ActivityManager(  872): Force stopping com.test.thalitest appid=10279 user=0: pkg removed
I/art     ( 1646): Explicit concurrent mark sweep GC freed 440(29KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 18MB/31MB, paused 876us total 42.284ms
D/ResourcesManager(  872): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
E/SamsungIME( 1708): mOCRHelper is null
W/GeofencerStateMachine( 1397): Ignoring removeGeofence because network location is disabled.
I/InputReader(  872): Reconfiguring input devices.  changes=0x00000010
I/KLMS-2.4.511: ( 7056): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/art     ( 5180): Explicit concurrent mark sweep GC freed 34328(1908KB) AllocSpace objects, 8(128KB) LOS objects, 39% free, 15MB/26MB, paused 8.345ms total 78.022ms
I/KLMS-2.4.511: ( 7056): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1449750505806
I/KLMS-2.4.511: ( 7056): MainReciver(): PACKAGE_REMOVED
I/KLMS-2.4.511: ( 7056): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
D/SecContentProvider2(  872): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  872): mCursor = null
I/art     ( 6233): Explicit concurrent mark sweep GC freed 9217(537KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 16MB/21MB, paused 360us total 150.210ms
I/art     (  872): Explicit concurrent mark sweep GC freed 20873(1949KB) AllocSpace objects, 25(400KB) LOS objects, 17% free, 37MB/45MB, paused 1.811ms total 162.402ms
I/art     (  872): WaitForGcToComplete blocked for 43.200ms for cause Explicit
D/ResourcesManager(  872): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
I/art     ( 1748): Explicit concurrent mark sweep GC freed 3538(176KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 22MB/30MB, paused 46.158ms total 217.488ms
W/SQLiteConnectionPool( 1748): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
D/RegisteredServicesCache( 1429): empty dynamic service
D/ResourcesManager(  872): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
D/ResourcesManager(  872): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
D/ResourcesManager(  872): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
D/ResourcesManager(  872): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager(  872): creating new AssetManager and set to /system/app/Evernote_H/Evernote_H.apk
D/ResourcesManager(  872): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/ResourcesManager(  872): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/ResourcesManager(  872): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/ResourcesManager(  872): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
D/ResourcesManager(  872): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
D/ResourcesManager(  872): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
D/ResourcesManager(  872): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
D/ResourcesManager(  872): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
D/ResourcesManager(  872): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(  872): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(  872): creating new AssetManager and set to /system/app/Books/Books.apk
D/ResourcesManager(  872): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager(  872): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager(  872): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
D/ResourcesManager(  872): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
D/ResourcesManager(  872): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/ResourcesManager(  872): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/ResourcesManager(  872): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
I/ActivityManager(  872): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7814 uid=10116 gids={50116, 9997, 3003} abi=armeabi-v7a
E/Zygote  ( 7814): MountEmulatedStorage()
I/libpersona( 7814): KNOX_SDCARD checking this for 10116
E/Zygote  ( 7814): v2
I/libpersona( 7814): KNOX_SDCARD not a persona
D/ResourcesManager(  872): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
D/ResourcesManager(  872): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
D/ResourcesManager(  872): creating new AssetManager and set to /system/app/Videos/Videos.apk
I/SELinux ( 7814): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7814): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7814): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/RCPManagerService(  872): PackageReceiver onReceive()
I/HarmonyEASService(  872): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KnoxMUMContainerPolicy(  872): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  872): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  872): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  872): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  872): uID is 10279
V/EnterpriseBillingPolicy(  872): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  872): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage(  872): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  872): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  872): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  872): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage(  872): getBillingProfileForVpnEngine - end - null
D/TaskPersister(  872): removeObsoleteFile: deleting file=3_task.xml
D/TimaKeyStoreProvider( 7814): TimaSignature is unavailable
D/ActivityThread( 7814): Added TimaKeyStore provider
I/art     (  872): Explicit concurrent mark sweep GC freed 10470(471KB) AllocSpace objects, 0(0B) LOS objects, 17% free, 37MB/45MB, paused 5.297ms total 195.898ms
D/ResourcesManager(  872): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/ResourcesManager( 7814): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
D/SurfaceWidgetView( 1462): destroyHardwareResources():447025947
V/WindowOrientationListener(  872): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  872): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  872): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  872): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  872): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
D/Launcher( 1462): onRestart, Launcher: 396033566
D/Launcher( 1462): onStart, Launcher: 396033566
D/Launcher.HomeView( 1462): onStart
V/ActivityThread( 1462): updateVisibility : ActivityRecord{1a838320 token=android.os.BinderProxy@1c21d26a {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1806): [237392/8] Surface widget visibility changed visibility = true on instance = 1
D/SurfaceWidget.Renderer( 1806): [237392/8] SurfaceWidget drawing first frame
D/accuweather( 1806): [Accuweather J]>>> WR:623 [0:0] onGLDraw : BG texture = 5
D/ResourcesManager(  872): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
D/elm:14491( 7814): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14491( 7814): ELMEngine.ELMEngine( context ).
I/SurfaceFlinger(  254): id=16 createSurf (1080x1920),1 flag=4, Mauncher
D/elm:14491( 7814): MDMBridge.setEnterpriseBridge()
D/StatusBarManagerService(  872): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/elm:14491( 7814): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/StatusBarManagerService(  872): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
D/PointerIcon(  872): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  872): setMouseCustomIcon IconType is same.101
D/PointerIcon(  872): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  872): setHoveringSpenCustomIcon IconType is same.1
D/elm:14491( 7814): ElmAgentService : onCreate()
D/elm:14491( 7814): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14491( 7814): MainReceiver.listeningToPackageRemoved()
D/elm:14491( 7814): MDMBridge.getInstance()
D/elm:14491( 7814): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14491( 7814): MDMBridge.getAllLicenseInfoFromSDK()
D/InputMethodManagerService(  872): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
D/ResourcesManager(  872): creating new AssetManager and set to /system/app/talkback/talkback.apk
W/InputMethodManagerService(  872): Got RemoteException sending setActive(false) notification to pid 6606 uid 10279
W/ContextImpl(  872): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
E/Zygote  ( 7834): MountEmulatedStorage()
E/Zygote  ( 7834): v2
I/libpersona( 7834): KNOX_SDCARD checking this for 10021
I/libpersona( 7834): KNOX_SDCARD not a persona
I/ActivityManager(  872): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=7834 uid=10021 gids={50021, 9997} abi=armeabi-v7a
I/SELinux ( 7834): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
D/elm:14491( 7814): ElmAgentService : onDestroy().
I/SELinux ( 7834): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7834): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/EnterpriseDeviceManagerService(  872): Package has changed for user 0
D/EnterpriseDeviceManagerService(  872): Admin package name: com.google.android.gms
D/ResourcesManager(  872): creating new AssetManager and set to /system/app/Evernote_H/Evernote_H.apk
D/ResourcesManager(  872): creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
W/Resources(  872): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  872): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
D/TimaKeyStoreProvider( 7834): TimaSignature is unavailable
D/ActivityThread( 7834): Added TimaKeyStore provider
W/Resources(  872): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  872): creating new AssetManager and set to /system/app/Books/Books.apk
D/PackageManager(  872): delete codoeFile: 
D/ResourcesManager(  872): creating new AssetManager and set to /system/app/Music2/Music2.apk
I/AASAUninstall(  872):  com.test.thalitest not target!
D/PackageManager(  872): result of delete: 1{297468867}
D/AndroidRuntime( 7776): Shutting down VM
I/Timeline(  872): Timeline: Activity_windows_visible id: ActivityRecord{42316a5 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:1985435
D/ResourcesManager( 7834): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
D/ResourcesManager(  872): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
W/Resources(  872): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  872): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/com.sec.android.service.health.upgrade.UninstallReceiver( 7834): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 7834): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver( 7834): onReceive() : package name is not s health. Return !!!
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  872): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(  872): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
D/ResourcesManager(  872): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
W/Resources(  872): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  872): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
W/Resources(  872): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  872): creating new AssetManager and set to /system/priv-app/SamsungLink20/SamsungLink20.apk
W/Resources(  872): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  872): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  872): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
W/Resources(  872): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  872): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
E/Zygote  ( 7851): MountEmulatedStorage()
E/Zygote  ( 7851): v2
I/libpersona( 7851): KNOX_SDCARD checking this for 10025
I/libpersona( 7851): KNOX_SDCARD not a persona
D/ResourcesManager(  872): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager(  872): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager(  872): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
I/ActivityManager(  872): Start proc sstream.app for broadcast sstream.app/.receiver.ApplicationCompatibleReceiver: pid=7851 uid=10025 gids={50025, 9997, 1028, 1015, 3003} abi=armeabi-v7a
W/Resources(  872): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  872): creating new AssetManager and set to /system/app/Maps/Maps.apk
D/ResourcesManager(  872): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/ResourcesManager(  872): creating new AssetManager and set to /system/app/Peel_L/Peel_L.apk
D/ResourcesManager(  872): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
I/SELinux ( 7851): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
W/Resources(  872): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  872): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  872): creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
I/SELinux ( 7851): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7851): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ResourcesManager(  872): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  872): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  872): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/Resources(  872): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  872): creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
D/ResourcesManager(  872): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
W/Resources(  872): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  872): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  872): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
D/TimaKeyStoreProvider( 7851): TimaSignature is unavailable
D/ActivityThread( 7851): Added TimaKeyStore provider
W/Resources(  872): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  872): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  872): creating new AssetManager and set to /system/priv-app/SecMyFiles2/SecMyFiles2.apk
W/Resources(  872): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  872): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
W/Resources(  872): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  872): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  872): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
W/Resources(  872): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  872): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  872): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
W/Resources(  872): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 7851): creating new AssetManager and set to /system/priv-app/MagazineHome/MagazineHome.apk
D/UsbSettingsManager(  872): clearDefaults: com.test.thalitest
I/CrashAnrDetector(  872): onPackageRemoved : com.test.thalitest
W/ResourcesManager( 7851): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/linker  ( 7851): libdmcAlwaysFD.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
D/MVFD_interface( 7851): <<<  caMVFace_FaceInit
E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/sstream.app/cache/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7851): Failed to ensure directory: /storage/extSdCard/Android/data/sstream.app/cache
E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/sstream.app/cache/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7851): Failed to ensure directory: /storage/extSdCard/Android/data/sstream.app/cache
D/HockeyApp( 7851): Current handler class = sstream.app.util.Log$1
E/SMD     (  290): DCD ON
D/BatteryService(  872): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService(  872): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  872): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  872): stay LED for fully charged
D/BatteryService(  872): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1187): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1187): handleBatteryUpdate
I/MotionRecognitionService(  872): Plugged
I/MotionRecognitionService(  872): setPowerConnected  = true
D/STATUSBAR-PhoneStatusBar( 1187):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1187): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/EventHub(  872): Removing device '/dev/input/event6' due to inotify event
D/ResourcesManager( 7851): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
W/ResourcesManager( 7851): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
E/SQLiteLog( 7851): (28) failed to open "/data/data/sstream.app/databases/sstream.db" with flag (131138) and mode_t (0) due to error (2)
E/SQLiteLog( 7851): (28) failed to open "/data/data/sstream.app/databases/sstream.db" with flag (131072) and mode_t (0) due to error (2)
E/SQLiteLog( 7851): (14) cannot open file at line 32503 of [9491ba7d73]
E/SQLiteLog( 7851): (14) os_unix.c:32503: (2) open(/data/data/sstream.app/databases/sstream.db) - 
E/SQLiteDatabase( 7851): Failed to open database '/data/data/sstream.app/databases/sstream.db'.
E/SQLiteDatabase( 7851): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 7851): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7851): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 7851): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 7851): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7851): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7851): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7851): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 7851): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 7851): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 7851): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteDatabase( 7851): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 7851): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7851): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7851): 	at sstream.app.provider.StoryProvider.query(StoryProvider.java:386)
E/SQLiteDatabase( 7851): 	at android.content.ContentProvider.query(ContentProvider.java:980)
E/SQLiteDatabase( 7851): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/SQLiteDatabase( 7851): 	at android.content.ContentResolver.query(ContentResolver.java:484)
E/SQLiteDatabase( 7851): 	at android.content.ContentResolver.query(ContentResolver.java:428)
E/SQLiteDatabase( 7851): 	at sstream.app.provider.DatabaseUtil.queryConfigSetting(DatabaseUtil.java:685)
E/SQLiteDatabase( 7851): 	at sstream.app.receiver.ApplicationCompatibleReceiver.addCompatibleAppsToDB(ApplicationCompatibleReceiver.java:418)
E/SQLiteDatabase( 7851): 	at sstream.app.receiver.ApplicationCompatibleReceiver.getCompatibleApps(ApplicationCompatibleReceiver.java:155)
E/SQLiteDatabase( 7851): 	at sstream.app.StreamManager$1.run(StreamManager.java:177)
E/SQLiteLog( 7851): (28) failed to open "/data/data/sstream.app/databases/sstream.db" with flag (131138) and mode_t (0) due to error (2)
E/SQLiteLog( 7851): (28) failed to open "/data/data/sstream.app/databases/sstream.db" with flag (131072) and mode_t (0) due to error (2)
E/SQLiteLog( 7851): (14) cannot open file at line 32503 of [9491ba7d73]
E/SQLiteLog( 7851): (14) os_unix.c:32503: (2) open(/data/data/sstream.app/databases/sstream.db) - 
E/SQLiteDatabase( 7851): Failed to open database '/data/data/sstream.app/databases/sstream.db'.
E/SQLiteDatabase( 7851): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 7851): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7851): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 7851): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 7851): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7851): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7851): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7851): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 7851): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 7851): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 7851): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteDatabase( 7851): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 7851): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7851): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7851): 	at sstream.app.provider.StoryProvider.delete(StoryProvider.java:90)
E/SQLiteDatabase( 7851): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:314)
E/SQLiteDatabase( 7851): 	at android.content.ContentResolver.delete(ContentResolver.java:1309)
E/SQLiteDatabase( 7851): 	at sstream.app.provider.DatabaseUtil.deleteConfigSettingForApp(DatabaseUtil.java:985)
E/SQLiteDatabase( 7851): 	at sstream.app.receiver.ApplicationCompatibleReceiver.onReceive(ApplicationCompatibleReceiver.java:216)
E/SQLiteDatabase( 7851): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2991)
E/SQLiteDatabase( 7851): 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
E/SQLiteDatabase( 7851): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
E/SQLiteDatabase( 7851): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7851): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 7851): 	at android.app.ActivityThread.main(ActivityThread.java:5940)
E/SQLiteDatabase( 7851): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 7851): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 7851): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1389)
E/SQLiteDatabase( 7851): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1184)

```
