#### Test 50388019aa1a16d_thali07_samsung-SM-G900F Logs


```
--------- beginning of main
E/LightSensor(  894): Light old sensor_state 8192, new sensor_state : 8704 en : 1
D/SensorManager(  894): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
D/ResourcesManager( 6066): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
--------- beginning of system
D/BatteryService(  894): turn on LED for fully charged
I/CAE     (  894): handleMessage(CaPowerManager.java:182) - AP_SLEEP
I/CAE     (  894): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_SLEEP
I/CAE     (  894): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -46, 0,
D/SensorHubManager(  894): SendSensorHubData: send data = -76, 13, -46, 0
D/Sensorhubs(  292): sendContextData: -76, 13, -46, 0
I/CAE     (  894): sendCmdToSensorHub(SensorHubCommManager.java:144) - -63, 14, 11, 49, 42,
D/SensorHubManager(  894): SendSensorHubData: send data = -63, 14, 11, 49, 42
D/Sensorhubs(  292): sendContextData: -63, 14, 11, 49, 42
W/libprocessgroup(  894): failed to open /acct/uid_1000/pid_5141/cgroup.procs: No such file or directory
D/MotionRecognitionService(  894):   mReceiver.onReceive : ACTION_SCREEN_OFF
E/MotionRecognitionService(  894):  handler : SCREEN_OFF end 
I/WifiNative-HAL(  894): startHal
E/wifi    (  894): getStaticLongField sWifiHalHandle 0x959a27fc
D/wifi    (  894): halHandle = 0x0, mVM = 0xb4e5c280, mCls = 0x501ac2
I/WifiNative-HAL(  894): Could not start hal
D/WifiStateMachine(  894): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  894): handleScreenStateChanged Exit: false
E/WifiStateMachine(  894): setSuspendOptimizations: 4 true
E/WifiStateMachine(  894): mSuspendOptNeedsDisabled 0
D/audio_hw_primary(  285): adev_set_parameters: enter: screen_state=off
V/voice   (  285): voice_set_parameters: enter: screen_state=off
V/voice   (  285): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  285): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  285): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  285): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  285): adev_set_parameters: exit
D/NotificationService(  894): ACTION_SCREEN_OFF
D/LightsService(  894): [api] [SvcLED] setFlashing :: id = 4, color = ffffffff, mode = 12, onMS = 500, offMS = 2000,  (uid: 1000 pid: 894) 
D/LightsService(  894): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x42 | SvcLED(id=4) set On
I/SecExternalDisplayIntents_Java(  894): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
I/ActivityManager(  894): Killing 4894:com.sec.android.provider.badge/u0a78 (adj 15): bgCount ##41
D/VolumePanel( 1168): mCoverBroadcastReceiver: Screen OFF start
D/VolumePanel( 1168): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
D/IpRemoteDisplayController(  894): intent received android.intent.action.SCREEN_OFF
D/IpRemoteDisplayController(  894): Bridge Server is not available
D/VolumePanel( 1168): mCoverBroadcastReceiver: Screen OFF end
D/VolumePanel( 1168): mCoverBroadcastReceiver: onReceive() end : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
D/PersonaManagerService(  894): ACTION_SCREEN_OFF onReceive
D/PersonaManagerServiceHandler(  894): MSG_ACTION_SCREEN_OFF called
D/NfcService( 1464): call the applyRotuiing
D/STATUSBAR-PhoneStatusBar( 1168):      ACTION_SCREEN_OFF is finished!!!! 
E/StatusBar( 1168): onReceive : Intent.ACTION_SCREEN_OFF
D/Recents_AlternateRecentsComponent( 1168): dismissHelpPopup 
W/libprocessgroup(  894): failed to open /acct/uid_10078/pid_4894/cgroup.procs: No such file or directory
,D/accuweather( 2201): [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionSCREEN_OFF
D/accuweather( 2201): [KK AccuPhone]>>> SWW:467 [0:0] stopRefreshIcon : 1
D/accuweather( 2201): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
D/Finsky  ( 6066): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SystemBroadcastReceiver( 5260): [#DCM#] [DCM_Performance] onReceive completed in time  58 microsec. 
I/SystemBroadcastReceiver( 5260): [#DCM#] Calling notifyListeners. 
I/DCMPolicyManager( 5260): [#DCM#] onReceive action = EVENT_SCREEN_OFF
I/DCMController( 5260): [#DCM#] onIntentReceived eventid = EVENT_SCREEN_OFF
W/ActivityManager(  894): getTasks: caller 10086 does not hold GET_TASKS; limiting output
W/ActivityManager(  894): getTasks: caller 10086 does not hold GET_TASKS; limiting output
D/PowerManagerService(  894): [PWL] sb release: PowerManagerService.Broadcasts
D/SSRM:m  (  894): SIOP:: AP = 460, PST = 437, CUR = 300
D/Finsky  ( 6066): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6113): MountEmulatedStorage()
E/Zygote  ( 6113): v2
I/libpersona( 6113): KNOX_SDCARD checking this for 10012
I/libpersona( 6113): KNOX_SDCARD not a persona
I/ActivityManager(  894): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6113 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
I/SELinux ( 6113): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 6113): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 6113): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
W/Settings( 6066): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 6066): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/TimaKeyStoreProvider( 6113): TimaSignature is unavailable
D/ActivityThread( 6113): Added TimaKeyStore provider
D/LightsService(  894): [SvcLED]  onSensorChanged::light value = 39
E/LightSensor(  894): Light old sensor_state 8704, new sensor_state : 8192 en : 0
D/ResourcesManager( 6113): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
D/SensorManager(  894): unregisterListener ::   
D/lights  (  894): led_pattern : 3 +
W/ResourcesManager( 6113): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6113): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/lights  (  894): led_pattern : 3 -
D/LightsService(  894): [SvcLED]  setSvcLedLightLocked :: priority changed! SvcLED(id=3) OUT; SvcLED(id=4) IN
I/MultiDex( 6113): VM with version 2.1.0 has multidex support
I/MultiDex( 6113): install
I/MultiDex( 6113): VM has multidex support, MultiDex support library is disabled.
I/ActivityManager(  894): Killing 5237:com.wsomacp/u0a25 (adj 15): bgCount ##41
D/AndroidRuntime( 6101): 
D/AndroidRuntime( 6101): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/Finsky  ( 6066): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6066): [1] 2.run: Finished loading 1 libraries.
D/AndroidRuntime( 6101): CheckJNI is OFF
D/AndroidRuntime( 6101): setted country_code = Germany
D/AndroidRuntime( 6101): setted countryiso_code = DE
D/AndroidRuntime( 6101): setted sales_code = DBT
D/AndroidRuntime( 6101): readGMSProperty: start
D/AndroidRuntime( 6101): readGMSProperty: already setted!!
D/AndroidRuntime( 6101): readGMSProperty: end
D/AndroidRuntime( 6101): addProductProperty: start
D/ChimeraCfgMgr( 1901): Loading module com.google.android.gms.games from APK com.google.android.gms
D/PackageBroadcastService( 1901): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
V/JNIHelp ( 6113): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
I/ConfigFetchService( 1901): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
I/ConfigFetchService( 1901): launchTask
D/ChimeraCfgMgr( 1901): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/Finsky  ( 6066): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/Vision  ( 1901): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
D/Vision  ( 1901): Failed to find package metadata for com.example.hello
D/Vision  ( 1901): No vision deps
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
D/Finsky  ( 6066): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
E/Zygote  ( 6140): MountEmulatedStorage()
I/libpersona( 6140): KNOX_SDCARD checking this for 10040
E/Zygote  ( 6140): v2
I/libpersona( 6140): KNOX_SDCARD not a persona
D/ResourcesManager( 1901): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
W/ActivityThread( 6113): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6113): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3d1be6c6: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6113): Installed default security provider GmsCore_OpenSSL
I/ActivityManager(  894): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=6140 uid=10040 gids={50040, 9997, 1028, 1015, 3003} abi=armeabi-v7a
V/ConfigFetchTask( 1901): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1Xr9vZgpxMugDW2wL9sxfsvyKmx1cUyMHGv5gTzqsTlmMinuMCqH4V4QRkftsI3JYOBJ7BMK0oZ3zyEku4edmyvkQFsBbDo1KOpR1WnN5kLhkPUb7bB2KK1Tz8_gpmRuhPw6ldYeYGemLC8PM9G5o2LpajzxkN3TJzdP0Lic2r3shgNY7cLnZ-jr1V_9j17LgcLn-cHrpDWSUc9RqBtslEWMXHOHYxLoBgy0W-yibrTakzE2ug
I/SELinux ( 6140): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/PeopleContactsSync( 1901): CP2 sync disabled
I/SELinux ( 6140): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 6140): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
W/libprocessgroup(  894): failed to open /acct/uid_10025/pid_5237/cgroup.procs: No such file or directory
I/GoogleURLConnFactory( 1901): Using platform SSLCertificateSocketFactory
D/TimaKeyStoreProvider( 6140): TimaSignature is unavailable
D/ActivityThread( 6140): Added TimaKeyStore provider
D/ResourcesManager( 6140): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-1/base.apk
I/System.out( 1901): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 1901): (HTTPLog)-Static: isShipBuild true
I/System.out( 1901): (HTTPLog)-Thread-244-1055972115: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
E/AffinityControl( 6101): AffinityControl: registerfunction enter
D/SSRM:a  (  894): DeviceInfo:: 000000000000
D/SSRM:a  (  894): SettingsAirViewInfo:: 000000000
W/ConfigFetchTask( 1901): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
I/ConfigFetchService( 1901): fetch service done; releasing wakelock
I/ConfigFetchService( 1901): stopping self
D/AndroidRuntime( 6101): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  894): inState():  stateMachine is null !!
V/ApplicationPolicy(  894): isApplicationStateBlocked userId 0 pkgname com.example.hello
I/ActivityManager(  894): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  894): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
W/ActivityManager(  894): mDVFSHelper.acquire()
D/FocusedStackFrame(  894): Set to : 0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6171): MountEmulatedStorage()
I/libpersona( 6171): KNOX_SDCARD checking this for 10374
E/Zygote  ( 6171): v2
I/libpersona( 6171): KNOX_SDCARD not a persona
I/ActivityManager(  894): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=6171 uid=10374 gids={50374, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/SELinux ( 6171): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/AndroidRuntime( 6101): Shutting down VM
I/SELinux ( 6171): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 6171): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 6171): TimaSignature is unavailable
D/ActivityThread( 6171): Added TimaKeyStore provider
V/WindowOrientationListener(  894): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  894): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  894): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  894): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  894): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/ActivityManager(  894): Display changed displayId=0
D/ResourcesManager( 6113): creating new AssetManager and set to /system/app/Maps/Maps.apk
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/SurfaceWidgetView( 1477): destroyHardwareResources():251284100
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
I/SurfaceFlinger(  249): id=8 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (6/8)
I/SurfaceFlinger(  249): id=8 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (-2/8)
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ResourcesManager( 6171): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/SHealthUpgrade(SHealthUpgradeUtil)( 4435): isShealthServiceInstalled() : HealthService is Installed.
D/SHealthUpgrade(SHealthUpgradeUtil)( 4435): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 4435): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/Launcher( 1477): onTrimMemory. Level: 20
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2201): [237392/6] Surface widget visibility changed visibility = false on instance = 1
I/ActivityManager(  894): Killing 5342:com.sec.android.cloudagent/u0a2 (adj 15): bgCount ##41
I/SQLiteSecureOpenHelper( 3319): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3319): getDatabaseLocked(b,b,pwd)...
I/WebViewFactory( 6171): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager( 6171): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader( 6171): Loading: webviewchromium
I/LibraryLoader( 6171): Time to load native libraries: 2 ms (timestamps 8365-8367)
I/LibraryLoader( 6171): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6171): Binding Chromium to main looper Looper (main, tid 1) {1ec47ac7}
I/LibraryLoader( 6171): Expected native library version number "",actual native library version number ""
I/chromium( 6171): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6171): Initializing chromium process, renderers=0
W/art     ( 6171): Attempt to remove local handle scope entry from IRT, ignoring
I/ActivityManager(  894): Killing 5388:com.sec.smartcard.manager/u0a172 (adj 15): bgCount ##41
W/libprocessgroup(  894): failed to open /acct/uid_10002/pid_5342/cgroup.procs: No such file or directory
W/chromium( 6171): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
W/chromium( 6171): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6171): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium( 6171): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
D/BluetoothAdapter( 6171): 872093940: getState() :  mService = null. Returning STATE_OFF
D/GCM     ( 1658): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/ResourcesManager( 6113): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
D/ChimeraCfgMgr( 1901): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/Adreno-EGL( 6171): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6171): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6171): Build Date: 03/03/15 Tue
I/Adreno-EGL( 6171): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 6171): Remote Branch: 
I/Adreno-EGL( 6171): Local Patches: 
I/Adreno-EGL( 6171): Reconstruct Branch: 
D/ChimeraCfgMgr( 1901): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/Kids    ( 1901): [KidAccountFixer] No network connection
V/Finsky  ( 6066): [1] GearheadStateMonitor.onReady: sIsProjecting:false
W/chromium( 6171): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/chromium( 6171): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/art     ( 6171): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6171): onDetachedFromWindow called when already detached. Ignoring
W/libprocessgroup(  894): failed to open /acct/uid_10172/pid_5388/cgroup.procs: No such file or directory
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
D/SystemWebViewEngine( 6171): CordovaWebView is running on device made by: samsung
E/Zygote  ( 6215): MountEmulatedStorage()
E/Zygote  ( 6215): v2
I/libpersona( 6215): KNOX_SDCARD checking this for 10036
I/libpersona( 6215): KNOX_SDCARD not a persona
I/ActivityManager(  894): Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.app.profile.SnsStatusStreamBroadcastReceiver: pid=6215 uid=10036 gids={50036, 9997, 1028, 1015, 3003} abi=armeabi-v7a
W/art     ( 6171): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6171): Attempt to remove local handle scope entry from IRT, ignoring
I/ThermalEngine(  304): Sensor:tsens_tz_sensor5:86000 mC
I/ThermalEngine(  304): Sensor:tsens_tz_sensor5:86000 mC
I/ThermalEngine(  304): TM Id 'OPT_CURR_MONITOR-TSENS5' Sensor 'tsens_tz_sensor5' - alarm raised 1 at 86.0 degC
I/ThermalEngine(  304): ACTION: OPT_CURR_REQ 1
I/SELinux ( 6215): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 6215): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 6215): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 6215): TimaSignature is unavailable
D/ActivityThread( 6215): Added TimaKeyStore provider
D/Activity( 6171): performCreate Call secproduct feature valuefalse
D/Activity( 6171): performCreate Call debug elastic valuetrue
D/ResourcesManager( 6215): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
D/OpenGLRenderer( 6171): Render dirty regions requested: true
D/ActivityManager(  894): post active user change for 0
D/KnoxTimeoutHandler(  894): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  894): handleActiveUserChange for user 0
I/SurfaceFlinger(  249): id=13 createSurf (1x1),1 flag=404, com.example.hello/com.example.hello.MainActivity
D/StatusBarManagerService(  894): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/StatusBarManagerService(  894): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
V/AlarmManager(  894): waitForAlarm result :4
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
I/OpenGLRenderer( 6171): Initialized EGL, version 1.4
D/Finsky  ( 6066): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
I/OpenGLRenderer( 6171): HWUI protection enabled for context ,  &this =0xa1753060 ,&mEglDisplay = 1 , &mEglConfig = 8 
D/OpenGLRenderer( 6171): Enabling debug mode 0
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
V/GLSActivity( 1658): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/InputMethodManagerService(  894): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
W/ContextImpl(  894): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
W/ContextImpl(  894): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/ResourcesManager( 6215): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
W/ActivityManager(  894): mDVFSHelper.release()
I/Timeline(  894): Timeline: Activity_windows_visible id: ActivityRecord{2e175322 u0 com.example.hello/.MainActivity t11} time:48768
W/ResourcesManager( 6215): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6215): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
W/ResourcesManager( 6215): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/ResourcesManager( 6215): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
W/ResourcesManager( 6215): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6215): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6215): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/ResourcesManager( 6215): creating new AssetManager and set to /system/app/LegacyInCallUI/LegacyInCallUI.apk
W/ResourcesManager( 6215): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6215): Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
I/art     (  894): Explicit concurrent mark sweep GC freed 32849(2MB) AllocSpace objects, 5(80KB) LOS objects, 30% free, 36MB/52MB, paused 1.409ms total 118.091ms
W/IInputConnectionWrapper( 6171): showStatusIcon on inactive InputConnection
I/Timeline( 6171): Timeline: Activity_idle id: android.os.BinderProxy@367ba3b7 time:48882
I/art     ( 1658): Explicit concurrent mark sweep GC freed 11221(577KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 17MB/29MB, paused 469us total 35.513ms
I/chromium( 6171): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
E/AndroidProtocolHandler( 6171): Unable to open asset URL: file:///android_asset/www/jxcore.js
I/GLSUser ( 1658): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1658): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1658): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1658): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1658): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/JsMessageQueue( 6171): Set native->JS mode to OnlineEventsBridgeMode
V/GLSActivity( 1658): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 1658): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1658): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1658): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1658): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1658): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 6066): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
D/jxcore_app_log( 6171): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1358541824
D/JX-Cordova( 6171): jxcore cordova android initializing
W/jxcore-log( 6171): Initializing JXcore engine
W/jxcore-log( 6171): JXcore engine is ready
W/jxcore-log( 6171): Starting JXcore engine
E/auditd  ( 2016): In denial and Property audit_ondenial is set to 1 
D/SecurityLogAgent:SEDenialService(  894): Got Modify Event and sending Denial Intent foraudit.log
W/ContextImpl(  894): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
D/SecurityLogAgent:SEDenialService(  894): audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
W/jxcore-log( 6171): Platform android
W/jxcore-log( 6171): 
W/jxcore-log( 6171): Process ARCH arm
W/jxcore-log( 6171): 
,E/SPPClientService( 4938): [ForceUpdateAlarmReceiver] Alarm Setting. After one day, it will alram.
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6265): MountEmulatedStorage()
E/Zygote  ( 6265): v2
I/libpersona( 6265): KNOX_SDCARD checking this for 10038
I/libpersona( 6265): KNOX_SDCARD not a persona
,I/jxcore-log( 6171): JXcore Cordova bridge is ready!
I/jxcore-log( 6171): 
,W/jxcore-log( 6171): JXcore engine is started
,I/chromium( 6171): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6171): 
,I/ActivityManager(  894): Start proc com.sec.spp.push:RemoteDlcProcess for broadcast com.sec.spp.push/.dlc.sender.DlcRequestReceiver: pid=6265 uid=10038 gids={50038, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  312): Explicit concurrent mark sweep GC freed 8736(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 295us total 11.019ms
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 250us total 7.572ms
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 251us total 7.748ms
I/SELinux ( 6265): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 6265): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 6265): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,E/jxcore-log( 6171): >> samsung-SM-G900F
E/jxcore-log( 6171): 
,I/jxcore-log( 6171): Total memory 1787449344
I/jxcore-log( 6171): 
,I/jxcore-log( 6171): Free memory 70361088
I/jxcore-log( 6171): 
I/jxcore-log( 6171): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6171): 
I/jxcore-log( 6171): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6171): 
,D/TimaKeyStoreProvider( 6265): TimaSignature is unavailable
,D/ActivityThread( 6265): Added TimaKeyStore provider
,I/jxcore-log( 6171): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 6171): 
,I/jxcore-log( 6171): Size 1080 1920
I/jxcore-log( 6171): 
,I/jxcore-log( 6171): Screen Brightness 134
I/jxcore-log( 6171): 
,E/jxcore-log( 6171): Dummy Error Log.
E/jxcore-log( 6171): 
,D/ResourcesManager( 6265): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,E/SPPClientService( 6265): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 6265): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 6265): PushLog.txt file is not deleted.
,D/SPPClientService( 6265): PushLog.txt file is not deleted.
D/SPPClientService( 6265): ============PushLog. stop!
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6284): MountEmulatedStorage()
I/libpersona( 6284): KNOX_SDCARD checking this for 10038
E/Zygote  ( 6284): v2
I/libpersona( 6284): KNOX_SDCARD not a persona
,I/ActivityManager(  894): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PhoneStatusChangeReceiver: pid=6284 uid=10038 gids={50038, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6284): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6284): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 6284): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6284): TimaSignature is unavailable
,D/ActivityThread( 6284): Added TimaKeyStore provider
,V/GLSActivity( 1658): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 6284): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,E/SMD     (  279): DCD ON
,I/GLSUser ( 1658): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1658): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1658): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1658): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1658): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 6066): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 6066): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 6066): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,E/SPPClientService( 6284): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 6284): [PushClientApplication] Push log off : This is Ship build version
D/Finsky  ( 6066): [1] DailyHygiene.reschedule: Scheduling new run in 889 minutes (failures=5)
,D/SPPClientService( 6284): PushLog.txt file is not deleted.
,D/SPPClientService( 6284): PushLog.txt file is not deleted.
D/SPPClientService( 6284): ============PushLog. stop!
,E/LNoti   ( 6284): [PhoneStatusChangeReceiver] This device doesn't register yet.
,D/DeviceConnectionService( 1706): client connected with version: 7571000
,I/ActivityManager(  894): Killing 5307:com.sec.android.app.music:service/u0a44 (adj 15): bgCount ##41
,I/ActivityManager(  894): Killing 5260:com.samsung.dcm:DCMService/u0a4 (adj 15): bgCount ##42
,I/ActivityManager(  894): Killing 5160:com.google.android.music:main/u0a126 (adj 15): bgCount ##41
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6302): MountEmulatedStorage()
E/Zygote  ( 6302): v2
I/libpersona( 6302): KNOX_SDCARD checking this for 10149
I/libpersona( 6302): KNOX_SDCARD not a persona
,I/ActivityManager(  894): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=6302 uid=10149 gids={50149, 9997} abi=armeabi-v7a
,I/art     ( 1706): Explicit concurrent mark sweep GC freed 24917(1468KB) AllocSpace objects, 6(96KB) LOS objects, 40% free, 18MB/30MB, paused 501us total 39.899ms
,I/SELinux ( 6302): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6302): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6302): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  894): failed to open /acct/uid_10044/pid_5307/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 6302): TimaSignature is unavailable
,D/ActivityThread( 6302): Added TimaKeyStore provider
,D/ResourcesManager( 6302): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
,W/ResourcesManager( 6302): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6302): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6321): MountEmulatedStorage()
E/Zygote  ( 6321): v2
I/libpersona( 6321): KNOX_SDCARD checking this for 10150
I/libpersona( 6321): KNOX_SDCARD not a persona
,I/ActivityManager(  894): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6321 uid=10150 gids={50150, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/ActivityManager(  894): Killing 5447:com.sec.android.widgetapp.digitalclock/u0a94 (adj 15): bgCount ##41
,I/SELinux ( 6321): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
W/libprocessgroup(  894): failed to open /acct/uid_10004/pid_5260/cgroup.procs: No such file or directory
W/libprocessgroup(  894): failed to open /acct/uid_10126/pid_5160/cgroup.procs: No such file or directory
,I/SELinux ( 6321): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6321): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6321): TimaSignature is unavailable
,D/ActivityThread( 6321): Added TimaKeyStore provider
,D/ResourcesManager( 6321): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 6321): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6321): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6321): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/libprocessgroup(  894): failed to open /acct/uid_10094/pid_5447/cgroup.procs: No such file or directory
,I/GAV2    ( 5763): Thread[GAThread,5,main]: No campaign data found.
,D/daemonapp( 1326): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/Babel_RequestWriter( 4235): error sending REQ[fc:103; creat:1447770819797; type:bev-796892003]; took 0 ms (error code == 101)
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6344): MountEmulatedStorage()
E/Zygote  ( 6344): v2
I/libpersona( 6344): KNOX_SDCARD checking this for 10046
I/libpersona( 6344): KNOX_SDCARD not a persona
I/ActivityManager(  894): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6344 uid=10046 gids={50046, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/jxcore-log( 6171): getBuffer is called!!!!
I/jxcore-log( 6171): 
,I/SELinux ( 6344): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6344): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6344): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6344): TimaSignature is unavailable
,D/ActivityThread( 6344): Added TimaKeyStore provider
,D/ResourcesManager( 6344): creating new AssetManager and set to /system/priv-app/SecCalendarProvider/SecCalendarProvider.apk
,W/ResourcesManager( 6344): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CalendarProvider2( 6344): CalendarProvider2.onCreate() called
,W/ContextImpl(  894): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/AcmsKeyStoreHelper( 5976):  getKeyStoreForApplication Enter
,D/GCM     ( 1658): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1658): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,I/AcmsKeyStoreHelper( 5976): Key Store exist
,I/AcmsKeyStoreHelper( 5976): Hence loading the keystore file
,V/GmsCoreStatsServiceLauncher( 1901): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 5021): callingUid 10012, callindPid: 5021
,E/MDM     ( 1706): [168] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1901): Restart initialization of location
,D/AcmsKeyStoreHelper( 5976):  getKeyStoreForApplication Exit
,I/AcmsCertificateMngr( 5976): getKeyStoreForApplication success 
,D/AcmsCore( 5976): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor( 5976): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5976): Decrementing - Counter value: 1
D/AcmsCore( 5976): AcmsCore: ACMS_APP_INSTALLED
,D/AcmsCore( 5976): This is NOT a valid MirrorLink app
D/AcmsCore( 5976): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor( 5976): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5976): Decrementing - Counter value: 0
D/AcmsServiceMonitor( 5976): Counter value is 0: Stopping ACMS service
,D/AcmsServiceMonitor( 5976): getSvcCounter - Counter value: 0
D/AcmsService( 5976): Enter onDestroy
I/AcmsService( 5976): cleanUp(): inside service clean up
D/AcmsCore( 5976): AcmsCore: inside DeInit
D/AcmsCore( 5976): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr( 5976): AcmsCertificateMngr: inside cleanup
D/AcmsRevocationMngr( 5976): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper( 5976): KeyStoreHelper: inside cleanup
D/AcmsAppEntryInterface( 5976): AppEntryInterface: Inside CleanUp
D/AcmsServiceMonitor( 5976): getSvcCounter - Counter value: 0
D/AcmsService( 5976): killing acms process
I/Process ( 5976): Sending signal. PID: 5976 SIG: 9
,I/ActivityManager(  894): Process ACMS.Process (pid 5976)(adj 0) has died(71,592)
,I/ThermalEngine(  304): Sensor:tsens_tz_sensor5:73000 mC
,I/ThermalEngine(  304): Sensor:tsens_tz_sensor5:73000 mC
I/ThermalEngine(  304): TM Id 'OPT_CURR_MONITOR-TSENS5' Sensor 'tsens_tz_sensor5' - alarm cleared 1 at 73.0 degC
,I/ThermalEngine(  304): ACTION: OPT_CURR_REQ 0
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6370): MountEmulatedStorage()
,E/Zygote  ( 6370): v2
I/libpersona( 6370): KNOX_SDCARD checking this for 1000
I/libpersona( 6370): KNOX_SDCARD not a persona
,I/ActivityManager(  894): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=6370 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 6370): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6370): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6370): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6370): TimaSignature is unavailable
,D/ActivityThread( 6370): Added TimaKeyStore provider
,D/ResourcesManager( 6370): creating new AssetManager and set to /system/priv-app/MtpApplication/MtpApplication.apk
,E/MTPRx   ( 6370): In MtpReceiverandroid.hardware.usb.action.USB_STATE
,D/SecContentProvider2(  894): uri = 14 selection = getSealedState
,D/SecContentProvider2(  894): mCursor = null
D/SecContentProvider2(  894): KnoxCustomManagerService offline: service is not available
,D/SecContentProvider2(  894): uri = 14 selection = getSealedUsbMassStorageState
D/SecContentProvider2(  894): mCursor = null
D/SecContentProvider2(  894): KnoxCustomManagerService offline: service is not available
V/MTPRx   ( 6370): sealedState: false
V/MTPRx   ( 6370): sealedUsbMassStorageState: false
,E/MTPRx   ( 6370): check value of boot_completed is1
E/MTPRx   ( 6370): check booting is completed_sys.boot_completed
,E/MTPRx   ( 6370): Sd-Card path/storage/extSdCard
,E/MTPRx   ( 6370): Status for mount/Unmount :removed
E/MTPRx   ( 6370): SDcard is not available
,W/MTPRx   ( 6370): value of connected istrue
,W/MTPRx   ( 6370): value of configured istrue
W/MTPRx   ( 6370): value of mtpEnabled istrue
W/MTPRx   ( 6370): value of ptpEnabled isfalse
,E/MTPRx   ( 6370): Received USB_STATE with sdCardLaunch = 0
E/MTPRx   ( 6370): mFirstTime: false
,D/        ( 6370): MTP: reading debug level property
,E/MTPRx   ( 6370):  String obtained from jar = 0b1e96db05d64ea4
,E/MTPJNIInterface( 6370): Getting CryptionKey from JAVA
E/MTPRx   ( 6370): currentUserId is 0
,E/MTPRx   ( 6370): Start observing USB_STATE_MATCH 
,E/MTPRx   ( 6370): usbMode is 0210
,E/MTPRx   ( 6370): is_Privatemode is NOT 1
,D/SettingsProvider(  894): name = mtp_usb_conditions_met
,D/SecContentProvider(  894): uri = 18 selection = isUsbMediaPlayerAvailable
,E/MTPRx   ( 6370): sending MTP_ICON_ENABLED to stack
,D/SettingsProvider(  894): name = mtp_running_status
,D/SettingsProvider(  894): name = mtp_usb_conditions_met
,E/MTPRx   ( 6370): else part ... so first time!!!
,E/MTPPlaObsrvr( 6370): inside setContext()
E/MTPPlaObsrvr( 6370):  inside createplafiles
,E/MTPPlaObsrvr( 6370): playlist count is0
,E/MTPPlaObsrvr( 6370):  inside try branch createplafiles
,E/MTPPlaObsrvr( 6370):  inside deleteing plas createplafiles
,E/MTPPlaObsrvr( 6370): Inside registerContentObserver
,E/MtpAdbObserver( 6370): inside setContext()
,E/MtpAdbObserver( 6370): Inside registerContentObserver
W/Settings( 6370): Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,D/SettingsProvider(  894): name = mtp_running_status
,D/SettingsProvider(  894): name = mtp_usb_conditions_met
,E/MtpService( 6370): onCreate.
,E/MtpService( 6370): < MTP > Registering BroadCast receiver :::::
,D/MtpService( 1219): updating state; isCurrentUser=true, mMtpLocked=false
,E/MtpService( 6370): < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6387): MountEmulatedStorage()
E/Zygote  ( 6387): v2
I/libpersona( 6387): KNOX_SDCARD checking this for 1000
I/libpersona( 6387): KNOX_SDCARD not a persona
,I/ActivityManager(  894): Start proc com.samsung.android.app.mirrorlink for broadcast com.samsung.android.app.mirrorlink/.TMNetworkReceiver: pid=6387 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/MtpService( 6370): < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
,I/SELinux ( 6387): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
E/MtpService( 6370): onStartCommand.
W/MTPRx   ( 6370): calling native method
E/MTPJNIInterface( 6370): < MTP > Registering BroadCast receiver :::::
E/MtpService( 6370): handleMessage. msg= { when=-1ms what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
I/SELinux ( 6387): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 6387): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/MTPJNIInterface( 6370): < MTP > Registering BroadCast receiver :::::::
,E/MTPJNIInterface( 6370): noti = 10
,E/MtpService( 6370): onStartCommand.
,W/MTPRx   ( 6370): calling native method
E/MTPRx   ( 6370): Checking the driver time out
E/MTPJNIInterface( 6370): noti = 2
D/        ( 6370): deleting sockets before message queue initialization
,D/        ( 6370): event handler thread is created, so set the flag
,E/MtpService( 6370): handleMessage. msg= { when=-3ms what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,E/MTPRx   ( 6370): called native method
E/MTPJNIInterface( 6370): setting Media scanner status0
E/MTPJNIInterface( 6370): After setting Media scanner status0
,W/MTPRx   ( 6370): notification from stack 1
,E/        ( 6370): Unable to get Object Class and clearing cls 2 [int check_media_scanner_status() 594]
E/MTPJNIInterface( 6370): Getting media scanner status0
,E/MTPJNIInterface( 6370): DeviceName is Thali Test (Galaxy S5)
,D/TimaKeyStoreProvider( 6387): TimaSignature is unavailable
,D/ActivityThread( 6387): Added TimaKeyStore provider
,D/ResourcesManager( 6387): creating new AssetManager and set to /system/app/MirrorLink/MirrorLink.apk
,D/TMNetworkReceiver( 6387): TMNetworkReceiver.TMNetworkReceiver() Enter 1 main
,D/TMNetworkReceiver( 6387): TMNetworkReceiver.onReceive() Enter
D/TMNetworkReceiver( 6387): TMNetworkReceiver.onReceive() Action android.hardware.usb.action.USB_STATE
D/TMNetworkReceiver( 6387): TMNetworkReceiver.onReceive(): intent.getExtras() is not null
D/TMNetworkReceiver( 6387): TMNetworkReceiver.onReceive() on USB - connected:true, configured :true, mtp = true, mIsFileUpdated= false
,D/TMNetworkReceiver( 6387): TMNetworkReceiver.onReceive() USB CONNECTED
D/TMNetworkReceiver( 6387): TMNetworkReceiver.onReceive() Exit 
,D/TMSLogRemovalReceiver( 6387): TMLogRemovalReceiver.onReceive() Enter isCalled =false
,D/TMSLogRemovalReceiver( 6387): TMLogRemovalReceiver.onReceive() action android.hardware.usb.action.USB_STATE
D/TMSLogRemovalReceiver( 6387): TMLogRemovalReceiver.onReceive() Exit
,I/ActivityManager(  894): Killing 5463:com.sec.android.widgetapp.dualclockdigital/u0a103 (adj 15): bgCount ##41
,D/MediaScannerReceiver( 1219): action: android.intent.action.MTP_FILE_SCAN
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6405): MountEmulatedStorage()
I/libpersona( 6405): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6405): v2
I/libpersona( 6405): KNOX_SDCARD not a persona
,I/ActivityManager(  894): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/com.diagmondm.XDMBroadcastReceiver: pid=6405 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/TMNetworkReceiver( 6387): TMNetworkReceiver.onReceive() UsbCheck Thread Enter
,I/SELinux ( 6405): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 6405): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 6405): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/CalendarProvider2( 6344): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,D/TimaKeyStoreProvider( 6405): TimaSignature is unavailable
,D/ActivityThread( 6405): Added TimaKeyStore provider
,I/ActivityManager(  894): Killing 5479:com.sec.android.GeoLookout/u0a113 (adj 15): bgCount ##41
,W/libprocessgroup(  894): failed to open /acct/uid_10103/pid_5463/cgroup.procs: No such file or directory
,D/ResourcesManager( 6405): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,D/MediaScannerService( 1219): !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private, /storage/UsbDriveA, /storage/UsbDriveB, /storage/UsbDriveC, /storage/UsbDriveD, /storage/UsbDriveE, /storage/UsbDriveF]
,D/MediaProvider( 1219): savePlaylistTableInBulkDeleter started
,D/MediaProvider( 1219): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
,D/MediaProvider( 1219): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
,D/MediaProvider( 1219): savePlaylistTableInBulkDeleter finished
,D/MediaProvider( 1219): savePlaylistTableInBulkDeleter started
,D/MediaProvider( 1219): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
,W/libprocessgroup(  894): failed to open /acct/uid_10113/pid_5479/cgroup.procs: No such file or directory
,D/MediaProvider( 1219): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
,D/MediaProvider( 1219): savePlaylistTableInBulkDeleter finished
,I/DIAGMON_AGENT( 6405): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,D/MediaScanner( 1219): Prescan. DB items number : 21 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,V/MediaScanner( 1219): processDirectory :  /storage/emulated/0
,I/iu.UploadsManager( 1901): End new media; added: 0, uploading: 0, time: 41 ms
,D/MediaScanner( 1219): Skipping:
D/MediaScanner( 1219): 7klwibgf7fvntblfd7(75ebcf7
,I/DIAGMON_AGENT( 6405): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,D/MediaScanner( 1219): Skipping:
,D/MediaScanner( 1219): 7klwibgf7fvntblfd7(7Budiwrd7dblb7
,V/MediaScanner( 1219): processDirectory :  /storage/extSdCard
,W/MediaScanner( 1219): Error opening directory, reason : Permission denied.
W/MediaScanner( 1219): 7klwibgf7fxlKdCbid7
,E/File    ( 1219): fail readDirectory() errno=2
,V/MediaScanner( 1219): pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@dd3f8fd
,V/MediaScanner( 1219): /pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@dd3f8fd
,V/MediaScanner( 1219):  prescan time: 17ms (DB items: 21)
,V/MediaScanner( 1219):     scan time: 27ms (Caching mode: true), (makeEntry time: 19ms ~70%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1219): postscan time: 13ms (bulkDeleter : 0), (delete DeadThumbnail time : 10ms)
V/MediaScanner( 1219):    total time: 57ms
V/MediaScanner( 1219): checked files: 4  directories : 17  (I: 0, U: 0)
,D/MediaScannerService( 1219): !@done scanning volume external
,E/MTPJNIInterface( 6370): In MTPJNIINterface onReceive:android.intent.action.MEDIA_SCANNER_FINISHED
,I/DIAGMON_AGENT( 6405): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 6405): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 6405): [com.diagmondm.XDMBroadcastReceiver(34/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,I/ActivityManager(  894): Killing 4784:com.sec.android.app.camera/u0a154 (adj 15): bgCount ##41
,I/art     (  894): Explicit concurrent mark sweep GC freed 46913(4MB) AllocSpace objects, 2(32KB) LOS objects, 30% free, 36MB/52MB, paused 1.204ms total 72.444ms
,I/DBG_DM  ( 3469): [com.wssyncmldm.XDMBroadcastReceiver(153/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,W/libprocessgroup(  894): failed to open /acct/uid_10154/pid_4784/cgroup.procs: No such file or directory
,E/SQLiteLog( 6344): (284) automatic index on view_events(_id)
,I/SettingSearch/SearchIntentReceiver( 1300): action : android.settings.FINISH_SEARCHDB_EXTRA_APPS
I/SettingSearch/SearchIntentReceiver( 1300): FINISH_SEARCHDB_EXTRA_APPS call search titleinfo db init!!
,I/SettingSearch/SearchIntentReceiver( 1300): InitTitleDBThread start --> mDoingInitTitleDB : true
,I/SettingSearch/SearchIntentReceiver( 1300): action : android.settings.FINISH_SEARCHDB_EXTRA_APPS
I/SettingSearch/SearchIntentReceiver( 1300): FINISH_SEARCHDB_EXTRA_APPS call search titleinfo db init!!
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6439): MountEmulatedStorage()
,E/Zygote  ( 6439): v2
I/libpersona( 6439): KNOX_SDCARD checking this for 10126
I/libpersona( 6439): KNOX_SDCARD not a persona
,I/ActivityManager(  894): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver: pid=6439 uid=10126 gids={50126, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6439): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6439): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6439): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/CalendarAlarmManager( 6344): sys current time:1448020186383
,D/CalendarAlarmManager( 6344): reminder amount:0
,D/TimaKeyStoreProvider( 6439): TimaSignature is unavailable
,D/ActivityThread( 6439): Added TimaKeyStore provider
,D/ResourcesManager( 6439): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/SettingSearch/SettingsSearchManager( 1300): Infomation -> numtitleinfo : 0 numSearchinfo : 334
,I/art     ( 1219): Explicit concurrent mark sweep GC freed 7545(461KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 14MB/24MB, paused 593us total 17.930ms
,E/MTPJNIInterface( 6370): Status for mount/Unmount :removed
E/MTPJNIInterface( 6370): SDcard is not available
,I/SettingSearch/SettingsSearchManager( 1300):  Infomation -> getItem size : 334
,E/        ( 6370): [mtp_hidden_system_volume 189] Error opening file [error = Read-only file system] 
I/GAV2    ( 5993): Thread[GAThread,5,main]: No campaign data found.
,E/MTPJNIInterface( 6370): Status for mount/Unmount :removed
E/MTPJNIInterface( 6370): SDcard is not available
,E/SQLiteLog( 6370): (21) API call with NULL database connection pointer
E/SQLiteLog( 6370): (21) misuse at line 105654 of [9491ba7d73]
E/SQLiteLog( 6370): (21) API call with NULL database connection pointer
E/SQLiteLog( 6370): (21) misuse at line 100436 of [9491ba7d73]
E/SQLiteLog( 6370): (21) API call with NULL database connection pointer
E/SQLiteLog( 6370): (21) misuse at line 100436 of [9491ba7d73]
,E/SQLiteLog( 6370): (21) API call with NULL database connection pointer
E/SQLiteLog( 6370): (21) misuse at line 105654 of [9491ba7d73]
,W/MTPRx   ( 6370): notification from stack 2
,D/        ( 6370): [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
E/        ( 6370): [mtp_init_device 692]  After open the MTP fd = 32 and line = 692...
D/        ( 6370): [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
,E/        ( 6370):  [sua_support_present:1275] returning false 
D/        ( 6370): *****Starting mtp_io()
,W/MTPRx   ( 6370): notification from stack 3
D/        ( 6370): [mtp_start_io] source_thread Creation 
D/        ( 6370): [mtp_start_io] sink_thread Creation 
D/        ( 6370): [mtp_start_io:368] sink thread created so set th_sink
,D/ResourcesManager( 1300): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,I/MusicStore( 6439): Database version: 104
,D/ResourcesManager( 1300): creating new AssetManager and set to /system/priv-app/TeleService/TeleService.apk
,W/ResourcesManager( 1300): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 1300): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 1300): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 1300): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 1300): creating new AssetManager and set to /system/app/AssistantMenu2/AssistantMenu2.apk
,D/ResourcesManager( 6439): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager( 6439): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6439): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6439): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,V/AlarmManager(  894): waitForAlarm result :4
,W/ActivityThread( 6439): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6439): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@250916d9: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6439): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6439): GMSCore installation verified
,I/ConfigStore( 6439): Config Database version: 1
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6439): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6439): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6439): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/WifiDisplayAdapter(  894): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter(  894): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,V/AudioPolicyManager(  285): getOutputsForDevice device 0002 -> 0002
,I/AudioService(  894): getStreamVolume 3 index 70
,I/MediaRouter( 6439): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,D/WifiDisplayAdapter(  894): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/MusicLeanback( 6439): Stop autocaching.
,I/MusicLeanback( 6439): Stop autocaching.
,D/ResourcesManager( 5676): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,I/MusicLeanback( 6439): Stop autocaching.
W/ResourcesManager( 5676): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
I/MusicLeanback( 6439): Stop autocaching.
,W/ResourcesManager( 5676): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5676): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5676): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5676): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 5676): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 5676): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 5676): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 5676): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 5676): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5676): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5676): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5676): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ResourcesManager( 5676): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/ResourcesManager( 5676): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ResourcesManager( 5676): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ResourcesManager( 5676): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 5676): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5676): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5676): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/GHttpClientFactory( 6439): Using the GMSCore's GoogleHttpClient
,D/ResourcesManager( 5676): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/ResourcesManager( 5676): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5676): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5676): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/SettingSearch/SearchIntentReceiver( 1300): InitTitleDBThread end --> mDoingInitTitleDB : false
I/SettingSearch/SearchIntentReceiver( 1300): LOCALE_CHANGED call search setting db finish!!
,D/ResourcesManager( 5676): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/ResourcesManager( 5676): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5676): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5676): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5676): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 5676): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 5676): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5676): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5676): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 1552): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 5676): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager( 5676): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 5676): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 5676): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,E/Zygote  ( 6484): MountEmulatedStorage()
E/Zygote  ( 6484): v2
I/libpersona( 6484): KNOX_SDCARD checking this for 10075
I/libpersona( 6484): KNOX_SDCARD not a persona
,W/ResourcesManager( 5676): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 5676): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5676): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5676): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5676): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,I/ActivityManager(  894): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6484 uid=10075 gids={50075, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6484): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6484): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6484): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager(  894): Killing 5111:com.sec.android.widgetapp.activeapplicationwidget/u0a158 (adj 15): bgCount ##41
,D/ResourcesManager( 5676): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/ResourcesManager( 5676): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 5676): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5676): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/SettingSearch/SearchIntentReceiver( 1300): InitTitleDBThread start --> mDoingInitTitleDB : true
,D/TimaKeyStoreProvider( 6484): TimaSignature is unavailable
,D/ActivityThread( 6484): Added TimaKeyStore provider
,D/WearableClient( 6439): WearableClientImpl.onPostInitHandler: done
,D/WearableClient( 6439): WearableClientImpl.onPostInitHandler: done
,D/WearableClient( 6439): WearableClientImpl.onPostInitHandler: done
,D/ResourcesManager( 6484): creating new AssetManager and set to /system/app/AllshareFileShareServer/AllshareFileShareServer.apk
,I/SettingSearch/SearchIntentReceiver( 1300): InitTitleDBThread end --> mDoingInitTitleDB : false
,I/SettingSearch/SearchIntentReceiver( 1300): LOCALE_CHANGED call search setting db finish!!
,D/WearableClient( 6439): WearableClientImpl.onPostInitHandler: done
D/ResourcesManager( 5676): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 5676): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 5676): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/MusicLeanback( 6439): Conditions not met for autocaching.
I/MusicLeanback( 6439): Stop autocaching.
W/ResourcesManager( 5676): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 5676): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/GmsUtils( 6439): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 6439): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
D/ResourcesManager( 5676): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,W/ResourcesManager( 5676): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 5676): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,I/ActivityManager(  894): Killing 5625:com.google.android.partnersetup/u0a15 (adj 15): bgCount ##41
,D/ResourcesManager( 5676): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,W/libprocessgroup(  894): failed to open /acct/uid_10158/pid_5111/cgroup.procs: No such file or directory
,E/ActivityThread( 6439): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@1cfd1155 that was originally bound here
E/ActivityThread( 6439): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@1cfd1155 that was originally bound here
E/ActivityThread( 6439): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread( 6439): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread( 6439): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2085)
E/ActivityThread( 6439): 	at android.app.ContextImpl.bindService(ContextImpl.java:2068)
E/ActivityThread( 6439): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 6439): 	at com.google.android.gms.http.GoogleURLConnectionFactory.<init>(Unknown Source)
E/ActivityThread( 6439): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 6439): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 6439): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 6439): 	at com.google.android.music.GoogleHttpClientFactory.createGoogleHttpClient(GoogleHttpClientFactory.java:81)
E/ActivityThread( 6439): 	at com.google.android.music.cloudclient.MusicRequest.createHttpClient(MusicRequest.java:110)
E/ActivityThread( 6439): 	at com.google.android.music.cloudclient.MusicRequest.getSharedHttpClient(MusicRequest.java:100)
E/ActivityThread( 6439): 	at com.google.android.music.download.BaseDownloadQueueManager.<init>(BaseDownloadQueueManager.java:110)
E/ActivityThread( 6439): 	at com.google.android.music.download.TrackDownloadQueueManager.<init>(TrackDownloadQueueManager.java:10)
E/ActivityThread( 6439): 	at com.google.android.music.download.TrackDownloadQueueService.onCreate(TrackDownloadQueueService.java:25)
E/ActivityThread( 6439): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3100)
E/ActivityThread( 6439): 	at android.app.ActivityThread.access$1900(ActivityThread.java:172)
E/ActivityThread( 6439): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1505)
E/ActivityThread( 6439): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6439): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 6439): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
E/ActivityThread( 6439): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6439): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6439): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 6439): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/ResourcesManager( 5676): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,D/FileShare-Server( 6484): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.google.android.gms
W/ResourcesManager( 5676): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 5676): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 5676): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5676): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5676): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 5676): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,I/art     ( 1901): Explicit concurrent mark sweep GC freed 24197(1638KB) AllocSpace objects, 13(208KB) LOS objects, 40% free, 18MB/31MB, paused 839us total 50.700ms
,E/Zygote  ( 6504): MountEmulatedStorage()
E/Zygote  ( 6504): v2
I/libpersona( 6504): KNOX_SDCARD checking this for 1000
I/libpersona( 6504): KNOX_SDCARD not a persona
,D/ResourcesManager( 5676): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/ResourcesManager( 5676): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 5676): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/ActivityManager(  894): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=6504 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  894): Killing 5644:com.samsung.groupcast/u0a16 (adj 15): bgCount ##41
,I/SELinux ( 6504): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6504): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6504): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 1901): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,W/libprocessgroup(  894): failed to open /acct/uid_10015/pid_5625/cgroup.procs: No such file or directory
,W/libprocessgroup(  894): failed to open /acct/uid_10016/pid_5644/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 6504): TimaSignature is unavailable
,D/ActivityThread( 6504): Added TimaKeyStore provider
,D/ResourcesManager( 6504): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager( 6504): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/PowerManagerService(  894): [PWL] Off : 5s ago
I/PowerManagerService(  894): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  894): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  894): [PWL]       PARTIAL_WAKE_LOCK              '*alarm*' (uid=1000, pid=894, ws=WorkSource{10012}) (elapsedTime=28089)
I/PowerManagerService(  894): [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10012, pid=1901, ws=null) (elapsedTime=18818)
I/PowerManagerService(  894): [PWL]       PARTIAL_WAKE_LOCK              'Icing' (uid=10012, pid=1901, ws=WorkSource{10012 com.google.android.gms}) (elapsedTime=2)
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6522): MountEmulatedStorage()
E/Zygote  ( 6522): v2
I/libpersona( 6522): KNOX_SDCARD checking this for 1000
I/libpersona( 6522): KNOX_SDCARD not a persona
,I/ActivityManager(  894): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.shortcut.ShortcutReceiver: pid=6522 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager(  894): Killing 5661:com.sec.pcw.device/1000 (adj 15): bgCount ##41
,I/art     (  312): Explicit concurrent mark sweep GC freed 8772(373KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 276us total 11.098ms
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 250us total 8.114ms
,I/SELinux ( 6522): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6522): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6522): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 385us total 8.387ms
,D/TimaKeyStoreProvider( 6522): TimaSignature is unavailable
,D/ActivityThread( 6522): Added TimaKeyStore provider
,W/libprocessgroup(  894): failed to open /acct/uid_1000/pid_5661/cgroup.procs: No such file or directory
,D/ResourcesManager( 6522): creating new AssetManager and set to /system/app/KnoxSetupWizardClient/KnoxSetupWizardClient.apk
,D/ShortcutReceiver( 6522):  ShortcutReceiver onReceive() intent: android.intent.action.PACKAGE_CHANGED
,I/ActivityManager(  894): Killing 4873:com.policydm/1000 (adj 15): bgCount ##41
,D/PackageBroadcastService( 1901): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,D/ResourcesManager( 1552): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/BootupListener( 1471): ACTION_DRIVELINK
,I/PackageBroadcastService( 1901): Null package name or gms related package.  Ignoreing.
,D/SettingsProvider(  894): name = drivelink_navigation
D/SettingsProvider(  894): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  894): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  894): selectionArgs: false
D/SettingsProvider(  894): selectionArgs: 1001
,D/SecContentProvider(  894): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  894): ret = -1
D/BootupListener( 1471): NAVI : com.google.android.apps.maps
,D/SettingsProvider(  894): name = internet_call_settings_visibility
D/SettingsProvider(  894): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  894): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  894): selectionArgs: false
D/SettingsProvider(  894): selectionArgs: 1001
D/SecContentProvider(  894): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  894): ret = -1
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
I/UpdateIcingCorporaServi( 1552): UpdateCorporaTask done [took 429 ms] updated apps [took 429 ms] 
,E/Zygote  ( 6543): MountEmulatedStorage()
E/Zygote  ( 6543): v2
I/libpersona( 6543): KNOX_SDCARD checking this for 10158
I/libpersona( 6543): KNOX_SDCARD not a persona
,I/ActivityManager(  894): Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=6543 uid=10158 gids={50158, 9997, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6543): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6543): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6543): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/Icing   ( 1901): updateResources: need to parse f{com.google.android.gms}
,E/SMD     (  279): DCD ON
,D/TimaKeyStoreProvider( 6543): TimaSignature is unavailable
,D/ActivityThread( 6543): Added TimaKeyStore provider
,W/libprocessgroup(  894): failed to open /acct/uid_1000/pid_4873/cgroup.procs: No such file or directory
,D/ResourcesManager( 6543): creating new AssetManager and set to /system/app/SamsungWidget_ActiveApplication/SamsungWidget_ActiveApplication.apk
,V/TaskCloserActivity( 6543): TaskCloserActivity enter()
,V/TaskCloserActivity( 6543): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,I/ActivityManager(  894): Killing 5365:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##41
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6560): MountEmulatedStorage()
I/libpersona( 6560): KNOX_SDCARD checking this for 10054
E/Zygote  ( 6560): v2
I/libpersona( 6560): KNOX_SDCARD not a persona
,I/ActivityManager(  894): Start proc com.sec.android.app.videoplayer for broadcast com.sec.android.app.videoplayer/.videowall.TranscodeReceiver: pid=6560 uid=10054 gids={50054, 9997, 3003, 3002, 1028, 1015, 1023} abi=armeabi-v7a
,I/SELinux ( 6560): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 6560): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6560): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6560): TimaSignature is unavailable
,D/ActivityThread( 6560): Added TimaKeyStore provider
,W/libprocessgroup(  894): failed to open /acct/uid_10042/pid_5365/cgroup.procs: No such file or directory
,D/ResourcesManager( 6560): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager( 6560): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 6560): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6560): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6560): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6560): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,E/TranscodeReceiver( 6560): onReceive : android.intent.action.CHECK_SIOP_LEVEL
,D/videowall-Global( 6560): core_num = 4
,W/linker  ( 6560): libsthmb.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
W/linker  ( 6560): libvwengine.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,D/videowall-Global( 6560): density : 3.0 width : 1080 height : 1920 Raw width : 1080 Raw height : 1920
D/videowall-Global( 6560): dsp : 1080, swkey : false, Cores : 4, Clock : 0
,D/TranscodeReceiver( 6560):  SIOP_LEVEL: 0
,I/ActivityManager(  894): Killing 4992:com.osp.app.signin/u0a45 (adj 15): bgCount ##41
,D/daemonapp( 1326): [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
D/daemonapp( 1326): [MSC_Daemon]>>> WU:318 [0:0] cp type is : cp_eng
D/daemonapp( 1326): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1326): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1326): [MSC_Daemon]>>> WDSM:41 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,D/comsamsunglog( 1326): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1326): [MSC_Daemon]>>> daemonapp [Version : 15010801 ] [ 2 ] 
,D/comsamsunglog( 1326): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1326): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1326): [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
,D/daemonapp( 1326): [MSC_Daemon]>>> WDSM:418 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
D/daemonapp( 1326): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1326): [MSC_Daemon]>>> WDSM:421 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 1326): [MSC_Daemon]>>> WDSM:422 [0:0] [ASO][NUT] = 1448041740000
,D/daemonapp( 1326): [MSC_Daemon]>>> WDSM:423 [0:0] [ASO][CT] = 1448020187637
,D/daemonapp( 1326): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1326): [MSC_Daemon]>>> WU:1622 [0:0] PakNme size = 5
,D/daemonapp( 1326): [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,D/daemonapp( 1326): [MSC_Daemon]>>> WU:318 [0:0] cp type is : cp_eng
D/daemonapp( 1326): [MSC_Daemon]>>> WU:1626 [0:0] CP Name cp_eng
,D/daemonapp( 1326): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,E/daemonapp( 1326): [MSC_Daemon]>>> WU:1606 [0:0] [NameNotFoundException] !!
,D/GCM     ( 1658): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1658): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/libprocessgroup(  894): failed to open /acct/uid_10045/pid_4992/cgroup.procs: No such file or directory
,V/GmsCoreStatsServiceLauncher( 1901): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,E/MDM     ( 1706): [180] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1901): Restart initialization of location
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6577): MountEmulatedStorage()
,E/Zygote  ( 6577): v2
I/libpersona( 6577): KNOX_SDCARD checking this for 1000
I/libpersona( 6577): KNOX_SDCARD not a persona
,I/ActivityManager(  894): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=6577 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 6577): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6577): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6577): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6577): TimaSignature is unavailable
,D/ActivityThread( 6577): Added TimaKeyStore provider
,D/ResourcesManager( 6577): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/SecurityLogAgent( 6577):  SeDenialReceiver : Intent Received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 6577):  SeDenialReceiver : File path = null
,I/ActivityManager(  894): Killing 5197:com.android.mms/u0a50 (adj 15): bgCount ##41
,D/Finsky  ( 6066): [1] VerifyInstalledPackagesReceiver.checkPrerequisites: Skipping verification because network inactive
,D/CountryDetector(  894): No listener is left
,E/CscFactoryReceiver( 1471): onReceive android.intent.action.MEDIA_SCANNER_FINISHED
D/CscFactoryReceiver( 1471): Media DB Scanner finished.
D/CscFactoryReceiver( 1471): start service to Set Ringtone
,D/CscFactoryReceiver( 1471): start service to Set Notification
,W/libprocessgroup(  894): failed to open /acct/uid_10050/pid_5197/cgroup.procs: No such file or directory
,D/CscFactoryReceiver( 1471): start service to Set Alarmtone
,D/CscUpdateService( 1471): onStart
E/CscUpdateService( 1471): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 1471): only ringtone update
,D/CscUpdateService( 1471): onStart
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/CscUpdateService( 1471): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 1471): only notification update
,D/CscUpdateService( 1471): onStart
E/CscUpdateService( 1471): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 1471): only alarmtone update
,E/CscParser( 1471): update(): xml file exist
,E/CscParser( 1471): update(): xml file exist
,E/CscParser( 1471): update(): xml file exist
,E/Zygote  ( 6601): MountEmulatedStorage()
I/ActivityManager(  894): Start proc com.samsung.dcm:DCMService for broadcast com.samsung.dcm/.framework.broadcastreceivers.SystemBroadcastReceiver$DCMBroadcastReceiver: pid=6601 uid=10004 gids={50004, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 6601): v2
I/libpersona( 6601): KNOX_SDCARD checking this for 10004
I/libpersona( 6601): KNOX_SDCARD not a persona
,W/CSCSettings( 1471): Setting Ringtones (type) : 2
,W/CSCSettings( 1471): Setting Ringtones (type) : 4
,D/CscParser( 1471): AlarmTone: null
W/CSCSettings( 1471): 1. Tag_Str: null
I/SELinux ( 6601): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 6601): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 6601): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/CscParser( 1471): MessageTone: null
W/CSCSettings( 1471): 1. Tag_Str: null
,W/CSCSettings( 1471): Setting Ringtones (type) : 1
,D/CscParser( 1471): RingTone: null
,W/CSCSettings( 1471): 1. Tag_Str: null
,D/TimaKeyStoreProvider( 6601): TimaSignature is unavailable
,D/ActivityThread( 6601): Added TimaKeyStore provider
,D/ResourcesManager( 6601): creating new AssetManager and set to /system/priv-app/DCMProvider/DCMProvider.apk
,I/ConfigService( 1658): onDestroy
,I/DCMProvider( 6601): [#DCM#] onCreate this Instance = com.sec.dcm.provider.DCMProvider@279ffe3a Provider Ref Count:1
,I/DCMConfig( 6601): [#DCM#] initializeTransport.SystemBroadcastReceiver  1 ms
,I/StorageController( 6601): [#DCM#]  state through storage volume =  mounted
,I/StorageController( 6601): [#DCM#]  storageId =  65537 removable = false path = /storage/emulated/0 state = mounted subsystem = fuse
I/StorageController( 6601): [#DCM#]  state through storage volume =  removed
,I/StorageController( 6601): [#DCM#]  storageId =  131073 removable = true path = /storage/extSdCard state = removed subsystem = sd
I/StorageController( 6601): [#DCM#]  state through storage volume =  unmounted
I/StorageController( 6601): [#DCM#]  storageId =  196609 removable = false path = /storage/Private state = unmounted subsystem = private
I/StorageController( 6601): [#DCM#]  state through storage volume =  removed
,I/StorageController( 6601): [#DCM#]  storageId =  262145 removable = true path = /storage/UsbDriveA state = removed subsystem = usb
I/StorageController( 6601): [#DCM#]  state through storage volume =  removed
,I/StorageController( 6601): [#DCM#]  storageId =  327681 removable = true path = /storage/UsbDriveB state = removed subsystem = usb
I/StorageController( 6601): [#DCM#]  state through storage volume =  removed
I/StorageController( 6601): [#DCM#]  storageId =  393217 removable = true path = /storage/UsbDriveC state = removed subsystem = usb
I/StorageController( 6601): [#DCM#]  state through storage volume =  removed
,I/StorageController( 6601): [#DCM#]  storageId =  458753 removable = true path = /storage/UsbDriveD state = removed subsystem = usb
I/StorageController( 6601): [#DCM#]  state through storage volume =  removed
I/StorageController( 6601): [#DCM#]  storageId =  524289 removable = true path = /storage/UsbDriveE state = removed subsystem = usb
I/StorageController( 6601): [#DCM#]  state through storage volume =  removed
,I/StorageController( 6601): [#DCM#]  storageId =  589825 removable = true path = /storage/UsbDriveF state = removed subsystem = usb
,I/DCMPolicyManager( 6601): [#DCM#] setCriticalStateFromSystem screenOn =  false high siop = false camera running = false
,I/DCMPolicyManager( 6601): [#DCM#] opening file DCMRules.txt 
,I/DCMConfig( 6601): [#DCM#] initializeTransport.DCMPolicyManager  15 ms
,I/DCMConfig( 6601): [#DCM#] initializeTransport.MediaManager  17 ms
,I/DCMConfig( 6601): [#DCM#] initializeTransport.DCMNRTManager  24 ms
,I/DCMConfig( 6601): [#DCM#] No of CPU Core 4
I/DCMConfig( 6601): [#DCM#] initializeTransport took  25 ms
I/DCMProvider( 6601): [#DCM#] onCreate end 
,I/DCMNRTManager( 6601): [#DCM#] intialize 
,I/SystemBroadcastReceiver( 6601): [#DCM#] [DCM_Performance] onReceive completed in time  12 microsec. 
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
I/SystemBroadcastReceiver( 6601): [#DCM#] Calling notifyListeners. 
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,I/StorageController( 6601): [#DCM#]  state through storage volume =  mounted
,I/StorageController( 6601): [#DCM#]  storageId =  65537 removable = false path = /storage/emulated/0 state = mounted subsystem = fuse
I/StorageController( 6601): [#DCM#]  state through storage volume =  removed
,I/StorageController( 6601): [#DCM#]  storageId =  131073 removable = true path = /storage/extSdCard state = removed subsystem = sd
I/StorageController( 6601): [#DCM#]  state through storage volume =  unmounted
,I/StorageController( 6601): [#DCM#]  storageId =  196609 removable = false path = /storage/Private state = unmounted subsystem = private
I/StorageController( 6601): [#DCM#]  state through storage volume =  removed
I/StorageController( 6601): [#DCM#]  storageId =  262145 removable = true path = /storage/UsbDriveA state = removed subsystem = usb
I/StorageController( 6601): [#DCM#]  state through storage volume =  removed
,I/StorageController( 6601): [#DCM#]  storageId =  327681 removable = true path = /storage/UsbDriveB state = removed subsystem = usb
I/StorageController( 6601): [#DCM#]  state through storage volume =  removed
I/StorageController( 6601): [#DCM#]  storageId =  393217 removable = true path = /storage/UsbDriveC state = removed subsystem = usb
I/StorageController( 6601): [#DCM#]  state through storage volume =  removed
,I/StorageController( 6601): [#DCM#]  storageId =  458753 removable = true path = /storage/UsbDriveD state = removed subsystem = usb
I/StorageController( 6601): [#DCM#]  state through storage volume =  removed
I/StorageController( 6601): [#DCM#]  storageId =  524289 removable = true path = /storage/UsbDriveE state = removed subsystem = usb
,I/StorageController( 6601): [#DCM#]  state through storage volume =  removed
I/StorageController( 6601): [#DCM#]  storageId =  589825 removable = true path = /storage/UsbDriveF state = removed subsystem = usb
I/StorageController( 6601): [#DCM#] Bundle =  Bundle[{path=file:///storage/emulated/0, CleanBuffer=false}]
I/StorageController( 6601): [#DCM#] Sending intent for OS Upgrade for Phone contents 
,I/DCMUtilities( 6601): [#DCM#] Scan Completed:Check if lucene upgrade is required for OS upgrade 
,E/Zygote  ( 6629): MountEmulatedStorage()
I/libpersona( 6629): KNOX_SDCARD checking this for 10007
E/Zygote  ( 6629): v2
I/libpersona( 6629): KNOX_SDCARD not a persona
,I/SystemUtils( 6601): [#DCM#] pref_value getOSUpgradeSharedPrefForMedia is = true
,I/SystemUtils( 6601): [#DCM#] setOSUpgradeSharedPrefForMedia set as  true
,I/DCMUtilities( 6601): [#DCM#] OSUpgrade not required 
,I/ActivityManager(  894): Start proc com.samsung.indexservice for broadcast com.samsung.indexservice/com.samsung.index.indexservice.service.DocumentBroadcastReceiver: pid=6629 uid=10007 gids={50007, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  894): Killing 5695:com.sec.android.app.myfiles/u0a51 (adj 15): bgCount ##41
,I/SystemBroadcastReceiver( 6601): [#DCM#] Calling notifyListeners. 
,I/DCMPolicyManager( 6601): [#DCM#] onReceive action = EVENT_SIOP
,I/WriterFactory( 6601): [#DCM#] verifyLuceneDB ++ 
,I/WriterFactory( 6601): [#DCM#] verifyLuceneDB OK breaking 
,I/WriterFactory( 6601): [#DCM#] verifyLuceneDB OK -- 
I/WriterFactory( 6601): [#DCM#] TAXO in mode CREATE_OR_APPEND
,I/SELinux ( 6629): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6629): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6629): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/WriterFactory( 6601): [#DCM#] Before facet 
,I/WriterFactory( 6601): [#DCM#] After facet=!null ? true
,I/DCMUtilities( 6601): [#DCM#] isCommitOk; kKeyOnCommit = true
I/DCMController( 6601): [#DCM#] isCommitOk:  true, isIntentFinished: trueisRebuildDone = true
,I/DCMConfig( 6601): [#DCM#] setSuccessState =  true
,W/libprocessgroup(  894): failed to open /acct/uid_10051/pid_5695/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 6629): TimaSignature is unavailable
,D/ActivityThread( 6629): Added TimaKeyStore provider
,D/ResourcesManager( 6629): creating new AssetManager and set to /system/priv-app/DocumentService/DocumentService.apk
,I/ThumbnailProvider( 6629): ThumbnailProvider onCreate()
,I/DocumentBroadcastReceiver( 6629): DocumentService onReceive android.intent.action.MEDIA_SCANNER_FINISHED
,I/BroadcastProcessorService( 6629): [START] processBroadcastIntent ...
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,I/BroadcastProcessorService( 6629): DocumentService onHandleIntent ACTION_MEDIA_SCANNER_FINISHED
,E/Zygote  ( 6649): MountEmulatedStorage()
I/libpersona( 6649): KNOX_SDCARD checking this for 10044
E/Zygote  ( 6649): v2
I/libpersona( 6649): KNOX_SDCARD not a persona
,I/ActivityManager(  894): Start proc com.sec.android.app.music:service for broadcast com.sec.android.app.music/.appwidget.MusicAppWidgetProvider: pid=6649 uid=10044 gids={50044, 9997, 3003, 3002, 1028, 1015, 1023, 1007} abi=armeabi-v7a
,I/SELinux ( 6649): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6649): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,I/SystemInfo( 6629): [SYSTEM STATUS] Battery and Storage levels are OK:
E/SELinux ( 6649): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/BroadcastProcessorService( 6629): [CURRENT_STATE] DocumentService state: SERVICE_NOT_STARTED
I/BroadcastProcessorService( 6629): [START] DocumentService startDocumentService
,I/DocumentService( 6629): DocumentService onCreate ... service
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6629): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
D/TimaKeyStoreProvider( 6649): TimaSignature is unavailable
,D/ActivityThread( 6649): Added TimaKeyStore provider
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6629): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,D/ResourcesManager( 6649): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/ResourcesManager( 6649): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 6649): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6649): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6649): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6649): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6649): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,E/SystemInfo( 6629): [SIOP LEVEL] : 0
,I/DocumentService( 6629): [BEGIN SYNC] DocumentService beginIndexing :16
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6629): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,D/GalleryCacheReady( 5325): Receive action.ACTION_MEDIA_SCANNER_FINISHED
,D/GalleryCacheReady( 5325): handleMeidaScanFinish()
,D/FaceInterface( 5325): requestFaceScan() is called.
,W/LocalSuggestAlbumData( 5325): query fail: 
I/FaceInterface( 5325): startFaceScan() : waiting 5 sec
,W/LocalSuggestAlbumData( 5325): query fail: 
,D/KeyguardViewMediator( 1168): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,D/PersonaManager( 1168): isKioskContainerExistOnDevice
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/KeyguardViewMediator( 1168): doKeyguard: not showing because lockscreen is off
,I/art     (  894): Explicit concurrent mark sweep GC freed 30010(1948KB) AllocSpace objects, 0(0B) LOS objects, 30% free, 35MB/51MB, paused 1.228ms total 88.906ms
,E/File    ( 6629): fail readDirectory() errno=13
,E/File    ( 6629): fail readDirectory() errno=13
I/DocumentServiceUtils( 6629):  Total PDF: 0 PDF size: 0 OtherFiles Size: 0
E/SystemInfo( 6629): DocumentService [SIOP LEVEL] changed to 0
E/SystemInfo( 6629): DocumentService Resume indexing as [SIOP LEVEL] changed to < 2
,I/SystemInfo( 6629): [SYSTEM STATUS] Battery and Storage levels are OK:
,I/DocumentService( 6629): [STOP DOCUMENTSERVICE] Attempting to stop the Service
E/DocumentService( 6629): [THUMBNAIL AND INDEX] Thumbnail and indexing is Completed Total Time taken for both :107
E/DocumentService( 6629): [THUMBNAIL] Total Time taken for each file :0
E/        ( 6629): [INDEX] Total time taken for each file :0
,I/DocumentService( 6629): DocumentService onDestroy start
,I/DocumentService( 6629): DocumentService onDestroy end
,I/DocumentService( 6629): DocumentService cleanupEverything start
,I/ActivityManager(  894): Killing 5719:com.sec.android.app.soundalive/u0a58 (adj 15): bgCount ##41
,I/IndexParserThreadsManager( 6629): InterruptedException: null
,I/MediaStoreImporter( 6439): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/SystemInfo( 6629): [SYSTEM STATUS] Battery and Storage levels are OK:
I/DocumentService( 6629): DocumentService cleanupEverything end
,I/Process ( 6629): Sending signal. PID: 6629 SIG: 9
,E/lowmemorykiller(  246): Error writing /proc/6629/oom_score_adj; errno=22
I/ActivityManager(  894): Killing 5763:com.google.android.apps.docs/u0a98 (adj 15): bgCount ##41
,I/ActivityManager(  894): Process com.samsung.indexservice (pid 6629)(adj 13) has died(76,606)
,W/libprocessgroup(  894): failed to open /acct/uid_10058/pid_5719/cgroup.procs: No such file or directory
,W/libprocessgroup(  894): failed to open /acct/uid_10098/pid_5763/cgroup.procs: No such file or directory
,D/PackageManager(  894): [MSG] MCS_UNBIND
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,D/BluetoothAdapter( 6171): disable()
,E/BluetoothManagerService(  894): Bluetooth is already disabled. DO NOT disable again.
,D/WifiService(  894): New client listening to asynchronous messages
,I/WifiManager( 6171): packageName : com.example.hello
,D/SecContentProvider(  894): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2(  894): uri = 20 selection = isWifiStateChangeAllowed
,D/SecContentProvider2(  894): mCursor = null
,D/WifiService(  894): setWifiEnabled: false pid=6171, uid=10374
,E/WifiService(  894): Invoking mWifiStateMachine.setWifiEnabled
,D/SettingsProvider(  894): name = wifi_on
I/jxcore-log( 6171): ****TEST TOOK:  5101  ms ****
I/jxcore-log( 6171): 
I/jxcore-log( 6171): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6171): 
,I/CheckinService( 1901): Done disabling old GoogleServicesFramework version
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,D/AndroidRuntime( 6681): 
D/AndroidRuntime( 6681): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6681): CheckJNI is OFF
,D/AndroidRuntime( 6681): setted country_code = Germany
D/AndroidRuntime( 6681): setted countryiso_code = DE
,D/AndroidRuntime( 6681): setted sales_code = DBT
D/AndroidRuntime( 6681): readGMSProperty: start
D/AndroidRuntime( 6681): readGMSProperty: already setted!!
D/AndroidRuntime( 6681): readGMSProperty: end
D/AndroidRuntime( 6681): addProductProperty: start
,I/ActivityManager(  894): Killing 5819:com.vlingo.midas/u0a33 (adj 15): bgCount ##41
,E/AffinityControl( 6681): AffinityControl: registerfunction enter
,D/AndroidRuntime( 6681): Calling main entry com.android.commands.pm.Pm
,W/libprocessgroup(  894): failed to open /acct/uid_10033/pid_5819/cgroup.procs: No such file or directory
,D/PackageManager(  894): START PACKAGE DELETE: observer{895282912}
D/PackageManager(  894): pkg{<packageName>}
D/PackageManager(  894): user{0}
D/PackageManager(  894): caller{2000}
D/PackageManager(  894): flags{3}
,D/PersonaManagerService(  894): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  894): isFromApprovedUnInstaller: isApproved : true
,D/PersonaManagerService(  894): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  894): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
,D/PackageManager(  894): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
,D/PackageManager(  894): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService(  894): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManagerService(  894): deletePackage- pkg:com.example.hello, edmuserId:-1
,D/ApplicationPolicy(  894): getApplicationUninstallationEnabled
D/ApplicationPolicy(  894): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager(  894): !@killApplicatoin: 10374, uninstall pkg
,I/ActivityManager(  894): Force stopping com.example.hello appid=10374 user=-1: uninstall pkg
,I/ActivityManager(  894): Killing 6171:com.example.hello/u0a374 (adj 0): stop com.example.hello
,I/ActivityManager(  894):   Force finishing activity ActivityRecord{2e175322 u0 com.example.hello/.MainActivity t11}
,D/FocusedStackFrame(  894): Set to : 0
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,I/SurfaceFlinger(  249): id=13 Removed com.example.hello/com.example.hello.MainActivity (6/8)
,I/SurfaceFlinger(  249): id=13 Removed com.example.hello/com.example.hello.MainActivity (-2/8)
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/WifiService(  894): Client connection lost with reason: 4
,W/ContextImpl(  894): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  894): Force stopping com.example.hello appid=10374 user=0: pkg removed
,D/ResourcesManager(  894): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,I/art     ( 4295): Explicit concurrent mark sweep GC freed 3400(189KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 14MB/24MB, paused 329us total 23.039ms
,D/ResourcesManager(  894): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  894): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,D/ResourcesManager(  894): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager( 1477): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
,D/ResourcesManager(  894): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,W/GeofencerStateMachine( 1706): Ignoring removeGeofence because network location is disabled.
,I/InputReader(  894): Reconfiguring input devices.  changes=0x00000010
,W/ResourcesManager( 1477): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 1477): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1477): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/ResourcesManager(  894): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager( 1477): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
,E/Zygote  ( 6706): MountEmulatedStorage()
,E/Zygote  ( 6706): v2
I/libpersona( 6706): KNOX_SDCARD checking this for 10019
I/libpersona( 6706): KNOX_SDCARD not a persona
,W/ResourcesManager( 1477): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/ActivityManager(  894): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=6706 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
W/ResourcesManager( 1477): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/ResourcesManager(  894): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,E/SamsungIME( 1835): mOCRHelper is null
,D/ResourcesManager(  894): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager(  894): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,I/SELinux ( 6706): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 6706): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 6706): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(  894): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager(  894): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager(  894): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/TimaKeyStoreProvider( 6706): TimaSignature is unavailable
,D/ActivityThread( 6706): Added TimaKeyStore provider
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/ResourcesManager(  894): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,D/ResourcesManager(  894): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,D/ResourcesManager(  894): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager( 6706): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/SurfaceWidgetView( 1477): destroyHardwareResources():251284100
,V/WindowOrientationListener(  894): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  894): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  894): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  894): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  894): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
,D/ResourcesManager(  894): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager(  894): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager(  894): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager(  894): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
,D/ResourcesManager(  894): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(  894): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/Launcher( 1477): onRestart, Launcher: 1022896409
,D/Launcher( 1477): onStart, Launcher: 1022896409
,D/Launcher.HomeView( 1477): onStart
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 2201): [237392/6] Surface widget visibility changed visibility = true on instance = 1
,D/SurfaceWidget.Renderer( 2201): [237392/6] SurfaceWidget drawing first frame
D/RegisteredServicesCache( 1464): empty dynamic service
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,I/SurfaceFlinger(  249): id=14 createSurf (1080x1920),1 flag=4, com.sec.android.app.launcher/com.android.launcher2.Launcher
,D/SecContentProvider2(  894): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  894): mCursor = null
,D/StatusBarManagerService(  894): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/StatusBarManagerService(  894): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/ResourcesManager(  894): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  894): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,I/KLMS-2.4.503: ( 6706): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,D/ResourcesManager(  894): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,I/KLMS-2.4.503: ( 6706): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1448020190155
,D/ResourcesManager(  894): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,I/KLMS-2.4.503: ( 6706): MainReciver(): PACKAGE_REMOVED
,D/ResourcesManager(  894): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(  894): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,I/KLMS-2.4.503: ( 6706): MainReciver(): REPLACING: false | pkgName: com.example.hello
,D/ResourcesManager(  894): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1168): value : false
,D/ResourcesManager(  894): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/ResourcesManager(  894): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager(  894): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  894): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/RCPManagerService(  894): PackageReceiver onReceive()
,I/HarmonyEASService(  894): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/InputMethodManagerService(  894): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/ResourcesManager(  894): creating new AssetManager and set to /system/app/talkback/talkback.apk
,W/InputMethodManagerService(  894): Got RemoteException sending setActive(false) notification to pid 6171 uid 10374
,D/KnoxMUMContainerPolicy(  894): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
W/ContextImpl(  894): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/BackupManagerService(  894): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,D/JobSchedulerService(  894): Receieved: android.intent.action.PACKAGE_REMOVED
,V/EnterpriseBillingPolicy(  894): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
,V/EnterpriseBillingPolicy(  894): uID is 10374
V/EnterpriseBillingPolicy(  894): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  894): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage(  894): getProfileForApplication - exit null
,V/EnterpriseBillingPolicy(  894): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  894): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  894): getBillingProfileForVpnEngine - start - com.example.hello
,E/Zygote  ( 6735): MountEmulatedStorage()
E/Zygote  ( 6735): v2
I/libpersona( 6735): KNOX_SDCARD checking this for 10104
I/libpersona( 6735): KNOX_SDCARD not a persona
,V/EnterpriseBillingPolicyStorage(  894): getBillingProfileForVpnEngine - end - null
,I/ActivityManager(  894): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6735 uid=10104 gids={50104, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  894): Killing 5794:com.sec.android.automotive.drivelink/u0a99 (adj 15): bgCount ##41
,D/TaskPersister(  894): removeObsoleteFile: deleting file=11_task.xml
,I/art     (  894): Explicit concurrent mark sweep GC freed 20830(1738KB) AllocSpace objects, 4(64KB) LOS objects, 30% free, 36MB/52MB, paused 6.265ms total 219.338ms
,I/SELinux ( 6735): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6735): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6735): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/EnterpriseDeviceManagerService(  894): Package has changed for user 0
,D/EnterpriseDeviceManagerService(  894): Admin package name: com.google.android.gms
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/ResourcesManager(  894): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,D/TimaKeyStoreProvider( 6735): TimaSignature is unavailable
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/ActivityThread( 6735): Added TimaKeyStore provider
,I/Timeline(  894): Timeline: Activity_windows_visible id: ActivityRecord{18db2d2b u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t9} time:55455
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,W/Resources(  894): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  894): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/PackageManager(  894): delete codoeFile: 
,D/PackageManager(  894): result of delete: 1{895282912}
W/Resources(  894): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  894): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager( 6735): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,D/ResourcesManager(  894): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,W/libprocessgroup(  894): failed to open /acct/uid_10099/pid_5794/cgroup.procs: No such file or directory
,D/LockPatternUtilsCache( 1168): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1168): value : false
,D/AndroidRuntime( 6681): Shutting down VM
,D/ResourcesManager(  894): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(  894): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/Resources(  894): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  894): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,W/Resources(  894): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/elm:14451( 6735): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/ResourcesManager(  894): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/elm:14451( 6735): ELMEngine.ELMEngine( context ).
,D/elm:14451( 6735): MDMBridge.setEnterpriseBridge()
,D/ResourcesManager(  894): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/elm:14451( 6735): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,W/Resources(  894): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/elm:14451( 6735): ElmAgentService : onCreate()
,W/Resources(  894): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  894): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
D/elm:14451( 6735): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:14451( 6735): MainReceiver.listeningToPackageRemoved()
D/elm:14451( 6735): MDMBridge.getInstance()
D/elm:14451( 6735): MDMBridge.getAllLicenseInfoFromSDK()
,W/Resources(  894): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  894): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/elm:14451( 6735): MDMBridge.getAllLicenseInfoFromSDK()
,E/Zygote  ( 6754): MountEmulatedStorage()
I/libpersona( 6754): KNOX_SDCARD checking this for 10017
E/Zygote  ( 6754): v2
I/libpersona( 6754): KNOX_SDCARD not a persona
,D/ResourcesManager(  894): creating new AssetManager and set to /system/app/Drive/Drive.apk
,I/ActivityManager(  894): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=6754 uid=10017 gids={50017, 9997} abi=armeabi-v7a
,D/ResourcesManager(  894): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(  894): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,W/Resources(  894): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  894): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(  894): creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
,D/ResourcesManager(  894): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(  894): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(  894): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  894): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources(  894): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  894): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
,D/ResourcesManager(  894): creating new AssetManager and set to /data/app/de.pizza-1/base.apk
,D/ResourcesManager(  894): creating new AssetManager and set to /data/app/de.kaufda.android-1/base.apk
,I/SELinux ( 6754): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/ResourcesManager(  894): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,D/elm:14451( 6735): ElmAgentService : onDestroy().
I/SELinux ( 6754): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6754): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  894): Killing 5854:com.samsung.android.intelligenceservice/u0a3 (adj 15): bgCount ##41
,W/Resources(  894): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  894): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  894): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/Resources(  894): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  894): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager(  894): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/Resources(  894): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  894): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,D/TimaKeyStoreProvider( 6754): TimaSignature is unavailable
,D/ActivityThread( 6754): Added TimaKeyStore provider
,W/Resources(  894): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  894): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  894): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,D/ResourcesManager( 6754): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,W/Resources(  894): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  894): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  894): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/Resources(  894): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager(  894): clearDefaults: com.example.hello
,I/CrashAnrDetector(  894): onPackageRemoved : com.example.hello
,E/SMD     (  279): DCD ON
,W/libprocessgroup(  894): failed to open /acct/uid_10003/pid_5854/cgroup.procs: No such file or directory
,D/com.sec.android.service.health.upgrade.UninstallReceiver( 6754): onReceive()
,I/com.sec.android.service.health.upgrade.UninstallReceiver( 6754): onReceive called  PACKAGE_REMOVED package:com.example.hello
D/com.sec.android.service.health.upgrade.UninstallReceiver( 6754): onReceive() : package name is not s health. Return !!!
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6770): MountEmulatedStorage()
E/Zygote  ( 6770): v2
I/libpersona( 6770): KNOX_SDCARD checking this for 1000
I/libpersona( 6770): KNOX_SDCARD not a persona
,I/ActivityManager(  894): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6770 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  894): Killing 5868:com.sec.android.provider.logsprovider/u0a20 (adj 15): bgCount ##41
,I/SELinux ( 6770): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6770): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6770): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  894): failed to open /acct/uid_10020/pid_5868/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 6770): TimaSignature is unavailable
,D/ActivityThread( 6770): Added TimaKeyStore provider
,D/ResourcesManager( 6770): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,I/PCWCLIENTTRACE_LOG( 6770): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 6770): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 6770): new DMDBOpenHelper instance
,I/PCWCLIENTTRACE_PushUtil( 6770): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6770): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6770): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6770): [onReceive] - android.intent.action.PACKAGE_REMOVED
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6786): MountEmulatedStorage()
E/Zygote  ( 6786): v2
I/libpersona( 6786): KNOX_SDCARD checking this for 10042
I/libpersona( 6786): KNOX_SDCARD not a persona
,I/ActivityManager(  894): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=6786 uid=10042 gids={50042, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
,I/ActivityManager(  894): Killing 5888:com.samsung.android.app.filterinstaller/1000 (adj 15): bgCount ##41
,I/art     (  312): Explicit concurrent mark sweep GC freed 8728(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 587us total 14.904ms
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/SELinux ( 6786): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 331us total 8.718ms
I/SELinux ( 6786): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 6786): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 257us total 8.651ms
,D/TimaKeyStoreProvider( 6786): TimaSignature is unavailable
,D/ActivityThread( 6786): Added TimaKeyStore provider
,W/libprocessgroup(  894): failed to open /acct/uid_1000/pid_5888/cgroup.procs: No such file or directory
,D/ResourcesManager( 6786): creating new AssetManager and set to /system/priv-app/SamsungLinkPlatform/SamsungLinkPlatform.apk
,W/ResourcesManager( 6786): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6786): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,E/SQLiteDatabase( 6786): Failed to open database '/data/data/com.samsung.android.sdk.samsunglink/databases/asp.db'.
E/SQLiteDatabase( 6786): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6786): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6786): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6786): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6786): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6786): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6786): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6786): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:891)
E/SQLiteDatabase( 6786): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:861)
E/SQLiteDatabase( 6786): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 6786): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1450)
E/SQLiteDatabase( 6786): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6786): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6786): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6786): 	at com.mfluent.asp.datamodel.ASPMediaStoreProvider.onCreate(SourceFile:462)
E/SQLiteDatabase( 6786): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
E/SQLiteDatabase( 6786): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
E/SQLiteDatabase( 6786): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5453)
E/SQLiteDatabase( 6786): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5048)
E/SQLiteDatabase( 6786): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4988)
E/SQLiteDatabase( 6786): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 6786): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
E/SQLiteDatabase( 6786): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6786): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6786): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
E/SQLiteDatabase( 6786): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6786): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6786): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 6786): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/AndroidRuntime( 6786): Shutting down VM
,E/AndroidRuntime( 6786): FATAL EXCEPTION: main
E/AndroidRuntime( 6786): Process: com.samsung.android.sdk.samsunglink, PID: 6786
E/AndroidRuntime( 6786): java.lang.RuntimeException: Unable to get provider com.mfluent.asp.datamodel.ASPMediaStoreProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 6786): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5456)
E/AndroidRuntime( 6786): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5048)
E/AndroidRuntime( 6786): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4988)
E/AndroidRuntime( 6786): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 6786): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
E/AndroidRuntime( 6786): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6786): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 6786): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
E/AndroidRuntime( 6786): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 6786): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 6786): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime( 6786): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime( 6786): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 6786): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 6786): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime( 6786): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime( 6786): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 6786): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 6786): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 6786): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:891)
E/AndroidRuntime( 6786): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:861)
E/AndroidRuntime( 6786): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 6786): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1450)
E/AndroidRuntime( 6786): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime( 6786): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 6786): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 6786): 	at com.mfluent.asp.datamodel.ASPMediaStoreProvider.onCreate(SourceFile:462)
E/AndroidRuntime( 6786): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
E/AndroidRuntime( 6786): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
E/AndroidRuntime( 6786): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5453)
E/AndroidRuntime( 6786): 	... 11 more
,V/ApplicationPolicy(  894): isApplicationStateBlocked userId 0 pkgname com.samsung.android.sdk.samsunglink
,F/libc    (  894): Fatal signal 7 (SIGBUS), code 2, fault addr 0x74276568 in tid 1267 (Binder_5)
,E/audit_log( 2016): File locking failed. error= Bad file number
,F/libc    (  894): Failed while talking to debuggerd: Broken pipe
F/libc    (  894): Fatal signal 7 (SIGBUS), code 2, fault addr 0x75904ef2 in tid 6804 (Error dump: sys)
F/libc    (  894): Unable to open connection to debuggerd: Connection refused
E/audit_log( 2016): File locking failed. error= Bad file number
,E/audit_log( 2016): File locking failed. error= Bad file number
,W/AudioFlinger(  285): power manager service died !!!
W/AudioFlinger(  285): power manager service died !!!
,I/SurfaceFlinger(  249): restart the boot-animation @ binderDied
W/Sensors ( 1451): sensorservice died [0xaf0bcc00]
W/Sensors ( 5325): sensorservice died [0xaf0fa540]
I/SurfaceFlinger(  249): id=5 Removed DimLayer (2/8)
,W/Sensors ( 1300): sensorservice died [0x9d621300]
,W/Sensors ( 1168): sensorservice died [0xaf07f100]
W/Sensors ( 2140): sensorservice died [0xaf0bcc40]
,W/Sensors ( 1471): sensorservice died [0xaf0d43c0]
,D/SurfaceFlinger(  249): Set power mode=2, type=0 flinger=0xb6962000
D/qdhwcomposer(  249): hwc_blank: Unblanking display: 0
E/WifiManager( 1168): Channel connection lost
,W/Sensors ( 1706): sensorservice died [0xaf065f00]
,W/Sensors ( 1477): sensorservice died [0xaf067400]
,E/WifiManager( 1471): Channel connection lost
,I/SurfaceFlinger(  249): id=6 Removed DimLayer (2/7)
I/ServiceManager(  247): service 'msapwifi' died
I/ServiceManager(  247): service 'wifiscanner' died
I/ServiceManager(  247): service 'rttmanager' died
I/ServiceManager(  247): service 'connectivity' died
I/ServiceManager(  247): service 'sb_service' died
I/ServiceManager(  247): service 'clinfo' died
I/ServiceManager(  247): service 'servicediscovery' died
I/ServiceManager(  247): service 'textservices' died
I/ServiceManager(  247): service 'network_score' died
I/ServiceManager(  247): service 'netstats' died
I/ServiceManager(  247): service 'netpolicy' died
I/ServiceManager(  247): service 'backup' died
I/ServiceManager(  247): service 'appwidget' died
I/ServiceManager(  247): service 'voiceinteraction' died
I/ServiceManager(  247): service 'SecExternalDisplayService' died
I/ServiceManager(  247): service 'diskstats' died
I/ServiceManager(  247): service 'spengestureservice' died
I/ServiceManager(  247): service 'quickconnect' died
I/ServiceManager(  247): service 'samplingprofiler' died
I/ServiceManager(  247): service 'commontime_management' died
I/ServiceManager(  247): service 'wifi' died
I/ServiceManager(  247): service 'sec_analytics' died
I/ServiceManager(  247): service 'mum_container_policy' died
I/ServiceManager(  247): service 'enterprise_billing_policy' died
I/ServiceManager(  247): service 'knox_timakeystore_policy' died
I/ServiceManager(  247): service 'enterprise_policy' died
I/ServiceManager(  247): service 'statusbar' died
I/ServiceManager(  247): service 'clipboard' died
I/ServiceManager(  247): service 'clipboardEx' died
I/ServiceManager(  247): service 'network_management' died
I/ServiceManager(  247): service 'ABTPersistenceService' died
I/ServiceManager(  247): service 'wifip2p' died
I/ServiceManager(  247): service 'updatelock' died
I/ServiceManager(  247): service 'notification' died
I/ServiceManager(  247): service 'devicestoragemonitor' died
I/ServiceManager(  247): service 'location' died
I/ServiceManager(  247): service 'country_detector' died
I/ServiceManager(  247): service 'sec_location' died
I/ServiceManager(  247): service 'search' died
I/ServiceManager(  247): service 'dropbox' died
I/ServiceManager(  247): service 'wallpaper' died
I/ServiceManager(  247): service 'audio' died
I/ServiceManager(  247): service 'DockObserver' died
I/ServiceManager(  247): service 'usb' died
I/ServiceManager(  247): service 'serial' died
I/ServiceManager(  247): service 'uimode' died
I/ServiceManager(  247): service 'jobscheduler' died
I/ServiceManager(  247): service 'dreams' died
I/ServiceManager(  247): service 'print' died
I/ServiceManager(  247): service 'restrictions' died
I/ServiceManager(  247): service 'media_session' died
I/ServiceManager(  247): service 'media_router' died
I/ServiceManager(  247): service 'trust' died
I/ServiceManager(  247): service 'fingerprint' died
I/ServiceManager(  247): service 'launcherapps' died
I/ServiceManager(  247): service 'voip' died
I/ServiceManager(  247): service 'media_projection' died
I/ServiceManager(  247): service 'imms' died
I/ServiceManager(  247): service 'context_aware' died
I/ServiceManager(  247): service 'scontext' died
I/ServiceManager(  247): service 'barbeam' died
I/ServiceManager(  247): service 'multiwindow_facade' died
I/ServiceManager(  247): service 'window' died
I/ServiceManager(  247): service 'input' died
I/ServiceManager(  247): service 'tactileassist' died
I/ServiceManager(  247): service 'bluetooth_manager' died
I/ServiceManager(  247): service 'bluetooth_secure_mode_manager' died
I/ServiceManager(  247): service 'motion_recognition' died
I/ServiceManager(  247): service 'cover' died
I/ServiceManager(  247): service 'mount' died
I/ServiceManager(  247): service 'lock_settings' died
I/ServiceManager(  247): service 'device_policy' died
I/ServiceManager(  247): service 'harmony_eas_service' died
I/ServiceManager(  247): service 'sdp' died
I/ServiceManager(  247): service 'log_manager_service' died
I/ServiceMan,ager(  247): service 'accessibility' died
I/ServiceManager(  247): service 'rcp' died
I/ServiceManager(  247): service 'cpuinfo' died
I/ServiceManager(  247): service 'dbinfo' died
I/ServiceManager(  247): service 'user' died
I/ServiceManager(  247): service 'procstats' died
I/ServiceManager(  247): service 'package' died
I/ServiceManager(  247): service 'activity' died
I/ServiceManager(  247): service 'gfxinfo' died
I/ServiceManager(  247): service 'telephony.registry' died
I/ServiceManager(  247): service 'batterystats' died
I/ServiceManager(  247): service 'appops' died
I/ServiceManager(  247): service 'power' died
I/ServiceManager(  247): service 'display' died
I/ServiceManager(  247): service 'entropy' died
I/ServiceManager(  247): service 'enterprise_license_policy' died
I/ServiceManager(  247): service 'application_policy' died
I/ServiceManager(  247): service 'wifi_policy' died
I/ServiceManager(  247): service 'phone_restriction_policy' died
I/ServiceManager(  247): service 'remoteinjection' died
I/ServiceManager(  247): service 'SEAMService' died
I/ServiceManager(  247): service 'persona' died
I/ServiceManager(  247): service 'account' died
I/ServiceManager(  247): service 'content' died
I/ServiceManager(  247): service 'DirEncryptService' died
I/ServiceManager(  247): service 'sedenial' died
I/ServiceManager(  247): service 'vibrator' died
I/ServiceManager(  247): service 'tw_toolbox' died
I/ServiceManager(  247): service 'tima' died
I/ServiceManager(  247): service 'cepproxyks' died
I/ServiceManager(  247): service 'input_method' died
I/ServiceManager(  247): service 'CustomFrequencyManagerService' died
I/ServiceManager(  247): service 'samsung.smartfaceservice' died
I/ServiceManager(  247): service 'consumer_ir' died
I/ServiceManager(  247): service 'alarm' died
I/ServiceManager(  247): service 'ReactiveService' died
I/ServiceManager(  247): service 'usagestats' died
I/ServiceManager(  247): service 'battery' died
I/ServiceManager(  247): service 'meminfo' died
I/ServiceManager(  247): service 'hardware' died
I/ServiceManager(  247): service 'scheduling_policy' died
I/ServiceManager(  247): service 'edmnativehelper' died
I/ServiceManager(  247): service 'permission' died
I/ServiceManager(  247): service 'webviewupdate' died
I/ServiceManager(  247): service 'persona_policy' died
E/WifiManager( 1552): Channel connection lost
I/ServiceManager(  247): service 'sensorservice' died
I/ServiceManager(  247): service 'mdm.remotedesktop' died
I/SurfaceFlinger(  249): id=14 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (4/6)
I/SurfaceFlinger(  249): id=7 Removed com.android.systemui.ImageWallpaper (2/5)
I/SurfaceFlinger(  249): id=7 Removed com.android.systemui.ImageWallpaper (-2/5)
I/SurfaceFlinger(  249): id=14 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (-2/5)
I/SurfaceFlinger(  249): id=9 Removed StatusBar (3/4)
I/SurfaceFlinger(  249): id=9 Removed StatusBar (-2/4)
I/SurfaceFlinger(  249): id=12 Removed ColorFade (3/3)
I/SurfaceFlinger(  249): id=12 Removed ColorFade (-2/3)
F/libc    ( 6786): Fatal signal 7 (SIGBUS), code 2, fault addr 0x758b6aa1 in tid 6786 (sdk.samsunglink)
F/libc    ( 6786): Unable to open connection to debuggerd: Connection refused
E/audit_log( 2016): File locking failed. error= Bad file number
E/WifiManager( 1300): Channel connection lost
E/WifiManager( 1706): Channel connection lost
I/SurfaceFlinger(  249): id=2 Removed FocusedStackFrame (2/2)
I/SurfaceFlinger(  249): id=3 Removed DimLayer (0/1)
I/SurfaceFlinger(  249): id=4 Removed DimLayer (0/0)
I/SurfaceFlinger(  249): id=5 Removed DimLayer (-2/0)
I/SurfaceFlinger(  249): id=6 Removed DimLayer (-2/0)
I/SurfaceFlinger(  249): id=2 Removed FocusedStackFrame (-2/0)
I/SurfaceFlinger(  249): id=3 Removed DimLayer (-2/0)
I/SurfaceFlinger(  249): id=4 Removed DimLayer (-2/0)
,I/Zygote  (  312): Process 6786 exited due to signal (7)
,F/libc    ( 6387): Fatal signal 7 (SIGBUS), code 2, fault addr 0x7840ada6 in tid 6399 (HeapTrimmerDaem)
,F/libc    ( 6387): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2016): File locking failed. error= Bad file number
,F/libc    ( 4295): Fatal signal 7 (SIGBUS), code 2, fault addr 0x78057c17 in tid 4341 (AppProvider)
,F/libc    ( 4295): Unable to open connection to debuggerd: Connection refused
E/audit_log( 2016): File locking failed. error= Bad file number
,I/Zygote  (  312): Process 6387 exited due to signal (7)
,I/Zygote  (  312): Process 4295 exited due to signal (7)
,I/qdhwcomposer(  249): handle_blank_event: dpy:0 panel power state: 1
,E/qdexternal(  249): writeHPDOption: file write failed '/sys/devices/virtual/graphics/fb1/hpd'
D/qdhwcomposer(  249): hwc_blank: Done unblanking display: 0
,E/installd(  288): eof
E/installd(  288): failed to read size
I/installd(  288): closing connection
,I/SurfaceFlinger(  249): Disp[0] Orientation 0=>0
,E/qdoverlay(  249): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
,E/qdoverlay(  249): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
E/qdhwcomposer(  249): hwc_set_primary: display commit fail for 0 dpy!
,I/qdhwcomposer(  249): handle_blank_event: dpy:0 panel power state: 0

```
