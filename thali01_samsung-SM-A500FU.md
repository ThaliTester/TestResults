#### Test 5667282762e056f_thali01_samsung-SM-A500FU Logs


```
--------- beginning of main
I/DBG_POLICYDM( 5864): [com.policydm.adapter.XDMTargetAdapter(264/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
I/DBG_POLICYDM( 5864): [com.policydm.XDMApplication(638/xdmWakeLockRelease)] 
I/DBG_POLICYDM( 5864): [com.policydm.db.XDB(1530/xdbDMffs_Init)] xdbDMffs_Init
I/DBG_POLICYDM( 5864): [com.policydm.XDMApplication(643/xdmWakeLockRelease)] m_WakeLock is release!!
--------- beginning of system
D/CountryDetector( 1016): The first listener is added
E/PhotosPlugin( 5848): Loading PhotosPlugin
D/Mms/MmsApp( 5774): [end]    initCountryIso consume time = 12.200834
D/Mms/MmsConfig( 5774): [start]    MmsConfig.init() consume time = 0.087395
I/DBG_POLICYDM( 5864): [com.policydm.XDMApplication(219/onCreate)] DMApplication Start !
I/DBG_POLICYDM( 5864): [com.policydm.XSPPReceiver(52/onReceive)] ACTION_PACKAGE_ADDED. mPkgName:com.test.thalitest
D/Mms/MmsConfig( 5774): before partial update
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5911): MountEmulatedStorage()
E/Zygote  ( 5911): v2
I/SELinux ( 5911): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5911): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1016): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.receiver.PackageInfoChangeReceiver: pid=5911 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/libpersona( 5911): KNOX_SDCARD checking this for 10035
I/libpersona( 5911): KNOX_SDCARD not a persona
D/Mms/MmsConfig( 5774): Load Resize quality : 80
E/SELinux ( 5911): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
D/EasySignUpManager_1.0.1( 5774): serviceId : 1, features : -1
D/EasySignUpManager_1.0.1( 5774): isAuth is false
D/Mms/MmsConfig( 5774): setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
D/PowerManagerService( 1016): [s] UserActivityState : 2 -> 4
I/PowerManagerService( 1016): Nap time (uid 1000)...
D/PowerManagerService( 1016): handleSandman : startDreaming: false  (canDreamLocked: false  canDozeLocked: false)
I/PowerManagerService( 1016): !@[ps] Screen__Off - 0 :  dream(timeout) (2)
I/PowerManagerService( 1016): Going to sleep due to screen timeout (uid 1000)...
I/SurfaceFlinger(  259): id=12 createSurf (720x1280),-1 flag=20004, DolorFade
V/WindowOrientationListener( 1016): WindowOrientationListener disabled
D/SensorService( 1016): [SO] activate (ident=0xb812c688, enabled=0)
I/Sensors ( 1016): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
D/DisplayPowerController( 1016): getFinalBrightness : Summary is 1 -> 1
D/DisplayPowerController( 1016): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 1016): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService( 1016): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService( 1016): SecHardwareInterface.setBatteryADC : false
D/PowerManagerService( 1016): handleSandman : startDreaming: true  (canDreamLocked: false  canDozeLocked: true)
D/PowerManagerService( 1016): handleSandman : startDream(true)
E/PowerManagerService( 1016): handleSandman : startDreaming, but isDreaming false
I/PowerManagerService( 1016): Sleeping (uid 1000)...
D/PowerManagerService( 1016): [s] UserActivityState : 4 -> 0
I/Adreno-EGL( 1016): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 1016): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 1016): Build Date: 04/06/15 Mon
I/Adreno-EGL( 1016): Local Branch: 
I/Adreno-EGL( 1016): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 1016): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 1016):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
D/SensorManager( 1016): unregisterListener ::   
D/KeyguardViewMediator( 1179): onScreenTurnedOff(3)
I/KeyguardEffectViewController( 1179): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 1179): changeWallpaperByScreenOff()
D/KeyguardViewMediator( 1179): notifyScreenOffLocked
D/TP/MmsSmsProvider( 1459): query,matched:2117, calling pid = 5774
D/TP/MmsSmsProvider( 1459): match 2117:Elapsed time : 1.640 ms
I/DBG_DM  ( 3158): [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] 
W/art     ( 2009): Verification of void com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0(android.content.Context, com.google.android.gms.common.app.BaseApplicationContext) took 104.591ms
D/PowerManagerService( 1016): Excessive delay in ColorFade : createEglContext: 34ms
D/TimaKeyStoreProvider( 5911): TimaSignature is unavailable
D/ActivityThread( 5911): Added TimaKeyStore provider
D/KeyguardViewMediator( 1179): timeout : 5000
D/PermissionCache(  259): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (437 us)
D/PowerManagerService( 1016): Excessive delay in ColorFade : captureScreenshotTextureAndSetViewport: 20ms
I/ServiceManager(  323): Waiting for service AtCmdFwd...
V/ActivityThread( 3158): updateVisibility : ActivityRecord{5aa6983 token=android.os.BinderProxy@15e390d6 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
D/KeyguardViewMediator( 1179): setting alarm to turn off keyguard, seq = 1
D/KeyguardViewMediator( 1179): handleNotifyScreenOff
D/VolumePanel( 1179): onScreenTurnedOff()
D/VolumePanel( 1179): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
D/VolumePanel( 1179): mCoverBroadcastReceiver: Screen OFF end
D/SecKeyguardClockSingleView( 1179): onScreenTurnedOff
E/SmartFaceService( 1016): onReceive: android.intent.action.SCREEN_ON
D/PowerManagerService( 1016): Excessive delay in ColorFade : initGLShaders: 61ms
D/PowerManagerService( 1016): Excessive delay in ColorFade prepare: 136ms
D/DisplayPowerController( 1016): ColorFade: onAnimationStart
D/DisplayPowerController( 1016): getFinalBrightness : Summary is 5 -> 5
D/DisplayPowerController( 1016): performScreenOffTransition : no brightness animation
D/EasySignUpManager_1.0.1( 5774): isAuth is false
D/EasySignUpManager_1.0.1( 5774): getServiceStatus : serviceId (1) is OFF
E/CscParser( 5774): mps_code.dat does not exist
E/CscParser( 5774): customer_path =/system/csc/customer.xml
E/CscParser( 5774): fileName + /system/csc/customer.xml
W/System.err( 1016): java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
W/System.err( 1016): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 1016): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err( 1016): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/SmartFaceService( 1016): fail to set sysfs 1
W/System.err( 1016): 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
W/System.err( 1016): 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
W/System.err( 1016): 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:468)
W/System.err( 1016): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
W/System.err( 1016): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 1016): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 1016): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 1016): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 1016): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 1016): 	at libcore.io.Posix.open(Native Method)
W/System.err( 1016): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 1016): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 1016): 	... 10 more
I/DBG_POLICYDM( 5864): [com.policydm.agent.XDMTask(170/xdmAgentTaskHandler)] XEVENT_DM_INIT
I/DBG_POLICYDM( 5864): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
D/InputMethodManagerService( 1016): [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
I/DBG_POLICYDM( 5864): [com.policydm.XDMApplication(677/xdmGetNotibarState)] get NotibarState : 7
I/DBG_POLICYDM( 5864): [com.policydm.ui.XUINotificationManager(47/xuiSetIndicator)] Indicator id : 7
I/DBG_POLICYDM( 5864): [com.policydm.XDMApplication(669/xdmSetNotibarState)] set NotibarState : 7
D/PanelView( 1179): There is/are notification(s) 
E/CscParser( 5774): mps_code.dat does not exist
E/CscParser( 5774): customer_path =/system/csc/customer.xml
E/CscParser( 5774): fileName + /system/csc/customer.xml
D/MotionRecognitionService( 1016):   mReceiver.onReceive : ACTION_SCREEN_ON
E/MotionRecognitionService( 1016):  handler : SCREEN_ON end
D/CscParser( 5774): getInstance fileName =/system/csc/customer.xml
D/NotificationService( 1016): ACTION_SCREEN_ON
D/LightsService( 1016): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1016) 
D/LightsService( 1016): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 1016): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1016): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
I/DBG_POLICYDM( 5864): [com.policydm.db.XDBAESCrypt(216/xdbGetCryptionkey)] try read dbString
D/Mms/MmsConfig( 5774):  enable multiwindow = true
E/WifiNative-wlan0( 1016): do suspend false
I/wpa_supplicant( 2142): reset timer : RESET_TIMER 1
I/wpa_supplicant( 2142): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 2142): P2P: Current p2p state = IDLE
D/PanelView( 1179): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
I/wpa_supplicant( 2142): Scan requested (ret=0) - scan timeout 30 seconds
D/audio_hw_primary(  284): adev_set_parameters: enter: screen_state=on
V/voice   (  284): voice_set_parameters: enter: screen_state=on
V/voice   (  284): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  284): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  284): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  284): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  284): adev_set_parameters: exit
E/SPPClientService( 5911): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 5911): [PushClientApplication] Push log off : This is Ship build version
I/DBG_POLICYDM( 5864): [com.policydm.db.XDBFumoAdp(427/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.sdk.samsunglink, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
W/art     ( 5774): Verification of boolean com.android.mms.ui.ConversationListFragment.onOptionsItemSelected(android.view.MenuItem) took 104.597ms
E/Mms/MessageUtils( 5774): setCountryDetector : update country detector info 
E/Mms/MessageUtils( 5774): updateCountryIso : update country iso info 
D/SPPClientService( 5911): PushLog.txt file is not deleted.
I/DBG_POLICYDM( 5864): [com.policydm.db.XDBFumoAdp(586/xdbGetFUMOInitiatedType)] Initiated Type: 0
D/SPPClientService( 5911): PushLog.txt file is not deleted.
D/SPPClientService( 5911): ============PushLog. stop!
I/DBG_POLICYDM( 5864): [com.policydm.agent.XDMUITask(190/xdmUIEvent)] XUI_DM_IDLE_STATE :true
I/DBG_POLICYDM( 5864): [com.policydm.polling.XPollingAgent(71/xpollingCheckVersionInfo)] 
E/Zygote  ( 5942): MountEmulatedStorage()
E/Zygote  ( 5942): v2
I/libpersona( 5942): KNOX_SDCARD checking this for 10038
I/DBG_POLICYDM( 5864): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
I/libpersona( 5942): KNOX_SDCARD not a persona
I/SELinux ( 5942): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=5942 uid=10038 gids={50038, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
I/DBG_POLICYDM( 5864): [com.policydm.polling.XPollingAgent(270/xpollingCheckTimer)] 
I/DBG_POLICYDM( 5864): [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
D/Mms/MmsConfig( 5774): [end]    init() consume time = 312.946979
D/Mms/Contact( 5774): [start]    init() consume time = 0.79198
I/DBG_POLICYDM( 5864): [com.policydm.noti.XNOTIAdapter(398/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
I/SELinux ( 5942): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/DBG_POLICYDM( 5864): [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
E/SELinux ( 5942): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/DBG_POLICYDM( 5864): [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
I/DBG_POLICYDM( 5864): [com.policydm.noti.XNOTIAdapter(440/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
I/DBG_POLICYDM( 5864): [com.policydm.noti.XNOTIAdapter(266/xnotiPushAdpClearSessionStatus)] 
I/DBG_POLICYDM( 5864): [com.policydm.ui.XUIAdapter(40/xuiAdpSetUiMode)] nDmUiMode : 0
I/DBG_POLICYDM( 5864): [com.policydm.polling.XPollingAgent(284/xpollingCheckTimer)] savedpollingtime : 2016/02/02/14:24:23
D/IpRemoteDisplayController( 1016): intent received android.intent.action.SCREEN_ON
D/IpRemoteDisplayController( 1016): Bridge Server is not available
I/DBG_POLICYDM( 5864): [com.policydm.db.XDBFumoAdp(438/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
D/GpsLocationProvider( 1016): receive broadcast intent, action: android.intent.action.SCREEN_ON
I/DBG_POLICYDM( 5864): [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] currentTime : 2016/01/26/18:55:53
I/DBG_POLICYDM( 5864): [com.policydm.polling.XPollingAgent(289/xpollingCheckTimer)] Restart Timer..
D/TimaKeyStoreProvider( 5942): TimaSignature is unavailable
D/ActivityThread( 5942): Added TimaKeyStore provider
D/PersonaManagerService( 1016): ACTION_SCREEN_ON onReceive
I/DBG_POLICYDM( 5864): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 0
D/PersonaManagerServiceHandler( 1016): MSG_ACTION_SCREEN_ON called
D/Mms/Contact( 5774): [end]    init consume time = 47.6875
I/DBG_POLICYDM( 5864): [com.policydm.db.XDBFumoAdp(564/xdbSetFUMOInitiatedType)] Initiated Type: 0
D/CoverManagerWhiteLists( 1016): isAllowedToUse : SIGNATURE_MATCH
I/NfcService( 1439): When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
W/ResourcesManager( 5942): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5942): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
D/NfcService( 1439): call the applyRouting
D/StatusBar.NetworkController( 1179): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/TP/MmsSmsProvider( 1459): query,matched:13, calling pid = 5774
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/TP/MmsSmsProvider( 1459): match 13:Elapsed time : 1.562 ms
D/DisplayPowerState( 1016): !@ ColorFade entry
D/DisplayPowerController( 1016): ColorFade: onAnimationEnd
D/accuweather( 1729): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_ON
D/accuweather( 1729): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
D/accuweather( 1729): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
D/lights  ( 1016): lcd : 0 +
D/accuweather( 1729): [KK AccuPhone]>>> UIM:282 [0:0] update clock event, is not screen on!!
D/DisplayPowerController( 1016): getFinalBrightness : Summary is 0 -> 0
D/DisplayPowerController( 1016): performScreenOffTransition : no brightness animation
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
D/Mms/DraftCache( 5774): [start]    rebuildCache consume time = 37.118854
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/lights  ( 1016): lcd : 0 -
D/DisplayPowerController( 1016): getFinalBrightness : Summary is 0 -> 0
D/DisplayPowerController( 1016): performScreenOffTransition : no brightness animation
D/PowerManagerService( 1016): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService( 1016): [PWL] sb release: PowerManagerService.Display
D/MISC PowerHAL( 1016): sysfs_write +: /sys/class/input/event3/device/enabled: 0
D/MISC PowerHAL( 1016): sysfs_write +: /sys/class/input/event1/device/enabled: 0
D/MISC PowerHAL( 1016): sysfs_write -: /sys/class/input/event1/device/enabled: 0
D/ActivityManager( 1016): startService callerProcessName:com.sec.android.widgetapp.ap.hero.accuweather, calleePkgName: com.sec.android.widgetapp.ap.hero.accuweather
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
D/MISC PowerHAL( 1016): sysfs_write -: /sys/class/input/event3/device/enabled: 0
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
I/DBG_POLICYDM( 5864): [com.policydm.db.XDB(1824/xdbSetBackUpServerUrl)] 
I/DBG_POLICYDM( 5864): [com.policydm.polling.XPollingAgent(311/xPollingReportReStartAlarm)] 
D/MISC PowerHAL( 1016): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL( 1016): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
I/QCOM PowerHAL( 1016): Got set_interactive hint
D/DisplayManagerService( 1016): !@display_state: ON -> OFF
I/DisplayManagerService( 1016): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager( 1016): Display changed displayId=0
D/SurfaceFlinger(  259): Set power mode=0, type=0 flinger=0xb8bb1690
D/qdhwcomposer(  259): hwc_setPowerMode: Setting mode 0 on display: 0
E/qdutils (  259): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  259): int qdutils::getHDMINode(): Failed to find HDMI node
I/SamsungIME( 1793): getNextShiftState() cursorCapsMode : 0
D/Mms/MethodReflector( 5774): getSubId is called
D/Mms/TelephonyUtils( 5774): getLongSubId from simSlot 0, return Value = -1
D/StatusBar.NetworkController( 1179): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1179): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1179): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1179): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/TP/MmsSmsProvider( 1459): query,matched:12, calling pid = 5774
D/TP/MmsSmsProvider( 1459): match 12:Elapsed time : 2.935 ms
D/Mms/MethodReflector( 5774): getTelephonyProperty is called
D/Mms/DownloadManager( 5774): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 5774): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5774): auto download without roaming -> true
D/Mms/DownloadManager( 5774): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/MethodReflector( 5774): getSubId is called
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
D/Mms/MethodReflector( 5774): getDefaultSmsSubId is called
E/Mms/TelephonyUtils( 5774): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils( 5774): getLongSubId from simSlot 1, return Value = -1000
D/Mms/MethodReflector( 5774): getTelephonyProperty is called
D/Mms/DownloadManager( 5774): roaming -> false (slotId = 1)
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/Mms/DownloadManager( 5774): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 5774): auto download without roaming -> true
D/Mms/DownloadManager( 5774): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager( 5774): auto download during roaming secondary -> false
D/Mms/DownloadManager( 5774): mAutoDownload ------> true
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/Mms/DraftCache( 5774): [end]    rebuildCache consume time = 80.971875
D/ChimeraCfgMgr( 2009): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2009): Module APK com.google.android.play.games already loaded
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/SSRM:n  ( 1016): SIOP:: AP = 330
I/DBG_POLICYDM( 5864): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 1
D/ComposerPerformance( 5774): 1453830954058 ms / [DONE] Composer constructor
E/CII     ( 5774): CommonIMSInterface: VoLTE CSC feature disabled.
I/Mms/ReservationManager( 5774): ReservationManager()
I/Mms/ReservationManager( 5774): resetAfterConnected()
D/LightsService( 1016): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 10, onMS = 0, offMS = 0,  (uid: 1000 pid: 1016) 
D/LightsService( 1016): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x10 | SvcLED(id=3) set On
D/BatteryService( 1016): turn on LED for charging
E/lights  ( 1016): write_int failed to open -1
D/LightsService( 1016): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1016): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/TP/MmsSmsProvider( 1459): query,matched:7, calling pid = 5774
E/SmartFaceService( 1016): onReceive: android.intent.action.SCREEN_OFF
D/TP/MmsSmsProvider( 1459): match 7:Elapsed time : 3.129 ms
W/System.err( 1016): java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
W/System.err( 1016): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 1016): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err( 1016): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
W/System.err( 1016): 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
W/System.err( 1016): 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
W/System.err( 1016): 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:474)
W/System.err( 1016): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
W/System.err( 1016): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 1016): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 1016): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 1016): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 1016): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
E/SmartFaceService( 1016): fail to set sysfs 0
W/System.err( 1016): 	at libcore.io.Posix.open(Native Method)
W/System.err( 1016): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 1016): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 1016): 	... 10 more
I/DBG_POLICYDM( 5864): [com.policydm.agent.XDMTask(195/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
D/Mms/Conversation( 5774): [start]    init() consume time = 73.339166
D/PanelView( 1179): There is/are notification(s) 
I/Mms/ReservationManager( 5774): getReservedSendMessageCount(): retMessageCount=0
D/MotionRecognitionService( 1016):   mReceiver.onReceive : ACTION_SCREEN_OFF
D/SamsungIME( 1793): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
D/TP/MmsSmsProvider( 1459): deleteConversation threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1459): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1459): updateThread(), thread_id = 9223372036854775807
V/TP/MmsSmsDatabaseHelper( 1459): sUpgradeVersion = 0, db.getVersion() = 81
D/Mms/MmsApp( 5774): [end]    onCreate() consume time = 13.341302
E/MotionRecognitionService( 1016):  handler : SCREEN_OFF end 
D/NotificationService( 1016): ACTION_SCREEN_OFF
D/LightsService( 1016): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1016) 
D/LightsService( 1016): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x10 -> 0x10 | SvcLED(id=4) set Off
D/LightsService( 1016): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/TP/MmsSmsProvider( 1459): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1459): need read changed broadcast:false
D/LightsService( 1016): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/Mms/Conversation( 5774): [end]    init consume time = 10.958542
D/audio_hw_primary(  284): adev_set_parameters: enter: screen_state=off
V/voice   (  284): voice_set_parameters: enter: screen_state=off
V/voice   (  284): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  284): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  284): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  284): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  284): adev_set_parameters: exit
D/Mms/MessagingNotification( 5774): [start]    init() consume time = 3.26526
D/Mms/DownloadManager( 5774): Service state changed: Bundle[mParcelledData.dataSize=744]
D/Mms/DownloadManager( 5774): roaming ------> false, mSimSlot = 0
D/Mms/MethodReflector( 5774): getSubId is called
D/Mms/TelephonyUtils( 5774): getLongSubId from simSlot 0, return Value = -1
D/Mms/MethodReflector( 5774): getTelephonyProperty is called
D/Mms/DownloadManager( 5774): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 5774): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5774): auto download without roaming -> true
D/Mms/DownloadManager( 5774): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager( 5774): mAutoDownload ------> true
D/ChimeraCfgMgr( 2009): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/Mms/MessagingNotification( 5774): [end]    init consume time = 12.70823
I/BackgroundCompactionService( 1016): Schedule Type1 BGCompaction
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
D/Mms/FreeMessageStatusReceiver( 5774): onReceive, action : android.intent.action.PACKAGE_ADDED
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/Mms/SpamFilter( 5774): [start]    SpamFilter fill() begin consume time = 7.298593
D/ActivityManager( 1016): startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
D/Mms/ArtClassLoader( 5774): init [DONE] art
I/BatteryStatsDumper( 1016): In refreshStats isReason Screen ON/OFF: true
D/TP/MmsSmsProvider( 1459): query,matched:0, calling pid = 5774
V/TP/MmsSmsProvider( 1459): getSimpleConversations entered.
D/NetworkStatsFactory( 1016): UpdateStatsForKnox updated
D/TP/MmsSmsProvider( 1459): match 0:Elapsed time : 1.149 ms
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.myfiles, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/TP/MmsSmsProvider( 1459): query,matched:400, calling pid = 5774
D/AsyncTaskServiceImpl( 2009): Submit a task: k
E/Zygote  ( 5973): MountEmulatedStorage()
I/libpersona( 5973): KNOX_SDCARD checking this for 10047
E/Zygote  ( 5973): v2
I/libpersona( 5973): KNOX_SDCARD not a persona
I/SELinux ( 5973): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/NetworkStatsFactory( 1016): UpdateStatsForKnox updated
I/SELinux ( 5973): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5973): [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
D/Mms/Synchronizer( 5774): [start]    doSync consume time = 56.583438
I/ActivityManager( 1016): Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=5973 uid=10047 gids={50047, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/IpRemoteDisplayController( 1016): intent received android.intent.action.SCREEN_OFF
D/IpRemoteDisplayController( 1016): Bridge Server is not available
I/qdhwcomposer(  259): handle_blank_event: dpy:0 panel power state: 0
D/qdhwcomposer(  259): hwc_setPowerMode: Done setting mode 0 on display 0
E/qdutils (  259): int qdutils::getHDMINode(): Failed to open fb node 2
D/SurfaceControl( 1016): Excessive delay in setPowerMode(): 258ms
D/PowerManagerService( 1016): Excessive delay in !@display_state: OFF: 258ms
I/libsuspend( 1016): !@autosuspend_wakeup_count_enable
I/libsuspend( 1016): !@autosuspend_wakeup_count_enable done
E/qdutils (  259): int qdutils::getHDMINode(): Failed to find HDMI node
D/PowerManagerService( 1016): Excessive delay in DisplayManagerInternal.requestDisplayStateInternal(mRequestingState): 269ms
D/Mms/FreeMessageReceiverService( 5774): onHandleIntent, action : android.intent.action.PACKAGE_ADDED
I/PowerManagerService( 1016): [PWL] Off : 0s ago
D/Mms/FreeMessageReceiverService( 5774): onHandleIntent: ACTION_PACKAGE_ADDED
I/PowerManagerService( 1016): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 1016): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 1016): [PWL]       PARTIAL_WAKE_LOCK              '*alarm*' (uid=1000, pid=1016, ws=WorkSource{1000}) (elapsedTime=1463)
I/PowerManagerService( 1016): [PWL]       PARTIAL_WAKE_LOCK              'SmartManager Framework Thread' (uid=1000, pid=1016, ws=null) (elapsedTime=66)
I/PowerManagerService( 1016): [PWL]   PowerManagerService.Broadcasts: ref count=1
I/BatteryStatsDumper( 1016): Screen bin #0: time=30305 power=0.17677916666666665
I/BatteryStatsDumper( 1016): Screen bin #1: time=0 power=0.0
I/BatteryStatsDumper( 1016): Screen bin #2: time=0 power=0.0
I/BatteryStatsDumper( 1016): Screen bin #3: time=0 power=0.0
I/BatteryStatsDumper( 1016): Screen bin #4: time=0 power=0.0
I/BatteryStatsDumper( 1016): Previous Battery Level: 0 Current Level: 100 Delta: -100
D/ActivityManager( 1016): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 5973): TimaSignature is unavailable
D/ActivityThread( 5973): Added TimaKeyStore provider
E/Zygote  ( 5994): MountEmulatedStorage()
E/Zygote  ( 5994): v2
I/libpersona( 5994): KNOX_SDCARD checking this for 10072
I/libpersona( 5994): KNOX_SDCARD not a persona
I/ActivityManager( 1016): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=5994 uid=10072 gids={50072, 9997} abi=armeabi-v7a
D/Mms/SpamFilter( 5774): [end]    SpamFilter fill() finished consume time = 58.466562
I/ActivityManager( 1016): Killing 5349:com.sec.android.diagmonagent/1000 (adj 15): empty #31
W/ActivityManager( 1016): userId = 0, bbcId = -10000
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/TP/MmsSmsProvider( 1459): update, matched:300, calling pid = 5774
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
V/TP/MmsSmsProvider( 1459): syncDBData start
V/TP/MmsSmsProvider( 1459): syncDBData sms end
V/TP/MmsSmsProvider( 1459): syncDBData mms end
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
V/TP/MmsSmsProvider( 1459): syncDBData end
D/Mms/Synchronizer( 5774): [end]    doSync consume time = 29.33349
D/ChimeraCfgMgr( 2009): Loading module com.google.android.gms.gass from APK com.google.android.gms
I/SELinux ( 5994): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5994): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5994): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
W/ResourcesManager( 5973): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5973): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5973): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/TimaKeyStoreProvider( 5994): TimaSignature is unavailable
D/ChimeraCfgMgr( 2009): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/ActivityThread( 5994): Added TimaKeyStore provider
D/k       ( 2009): Processing package: com.test.thalitest
W/BaseAppContext( 2009): Using Auth Proxy for data requests.
W/BaseAppContext( 2009): Using Auth Proxy for data requests.
D/BadgeProvider( 5994): onCreate
D/BadgeProvider( 5994): DatabaseHelper
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/Mms/MessagingNotification( 5774): checkBadgeCount unreadCount=0 badgeCount=0
D/TP/SmsProvider( 1459): query,matched:26, calling pid = 5774
D/TP/SmsProvider( 1459): match 26:Elapsed time : 0.961 ms
D/GpsLocationProvider( 1016): receive broadcast intent, action: android.intent.action.SCREEN_OFF
D/GassUtils( 2009): Found app info for package com.test.thalitest:18. Hash: 82ccbc74df315987b7be206c22ec4eaa3ab0d49235c4895536307c8f71b675fe
D/k       ( 2009): Found info for package com.test.thalitest in db.
V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.SCREEN_OFF
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_5349/cgroup.procs: No such file or directory
V/EmergencyMode( 1415): [EmergencyStateReceiver] binteractive [false] why[3]
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/TP/MmsSmsProvider( 1459): query,matched:6, calling pid = 5774
D/TP/MmsSmsProvider( 1459): match 6:Elapsed time : 1.854 ms
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.process,Name = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1016): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.internal.SharedPreferencesService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/PersonaManagerService( 1016): ACTION_SCREEN_OFF onReceive
D/PersonaManagerServiceHandler( 1016): MSG_ACTION_SCREEN_OFF called
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
D/NfcService( 1439): call the applyRouting
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/accuweather( 1729): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_OFF
D/accuweather( 1729): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
D/ActivityManager( 1016): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6016): MountEmulatedStorage()
I/libpersona( 6016): KNOX_SDCARD checking this for 10025
E/Zygote  ( 6016): v2
I/libpersona( 6016): KNOX_SDCARD not a persona
I/SELinux ( 6016): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=6016 uid=10025 gids={50025, 9997} abi=armeabi-v7a
I/SELinux ( 6016): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6016): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
W/BaseAppContext( 2009): Using Auth Proxy for data requests.
D/accuweather( 1729): [KK AccuPhone]>>> WCS:113 [0:0] onDestroy : End
I/DBG_POLICYDM( 5864): [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
D/TimaKeyStoreProvider( 6016): TimaSignature is unavailable
D/ActivityThread( 6016): Added TimaKeyStore provider
I/DBG_POLICYDM( 5864): [com.policydm.db.XDBNotiAdp(37/xdbNotiExistInfo)] Noti Exist : false
I/ActivityManager( 1016): Killing 5389:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #31
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ResourcesManager( 6016): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/MyFiles ( 5973): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
I/ActivityManager( 1016): Killing 5410:com.android.providers.calendar/u0a42 (adj 15): empty #31
I/SL_DEBUG( 5942): isLoggable:: isProductShip = 1
I/SL_DEBUG( 5942): isLoggable:: SL_DEBUG_EXIST = false
I/ActivityManager( 1016): Killing 5364:com.google.android.talk/u0a104 (adj 15): empty #31
D/SSRM:n  ( 1016): SIOP:: AP = 330
D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.android.defcontainer, action: null
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
I/TactileAssist( 1016): enable value -1
I/TactileAssist( 1016): internal enable value -1
I/TactileAssist( 1016): intensity value -1
I/TactileAssist( 1016): saveAppList value true
E/LibSecureUISvc( 1943): svc_sock_send_message(suisvc): Error sending data, -1 vs 4: Connection refused
E/WifiNative-wlan0( 1016): do suspend true
I/TactileAssist( 1016): List of disabled apps :
E/installd(  288): system dir 0 : /system/app/
E/installd(  288): system dir 1 : /system/priv-app/
E/installd(  288): system dir 2 : /vendor/app/
E/installd(  288): system dir 3 : /oem/app/
I/OMACP   ( 6016): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
D/PowerManagerService( 1016): [PWL] sb release: PowerManagerService.Broadcasts
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/Mms/Omacp( 5774): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
E/SMD     (  292): DCD OFF
I/ServiceManager(  323): Waiting for service AtCmdFwd...
E/Zygote  ( 6037): MountEmulatedStorage()
E/Zygote  ( 6037): v2
I/libpersona( 6037): KNOX_SDCARD checking this for 10053
I/SELinux ( 6037): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 6037): KNOX_SDCARD not a persona
I/ActivityManager( 1016): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=6037 uid=10053 gids={50053, 9997, 3003, 3002} abi=armeabi-v7a
I/OMACP   ( 6016): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
I/SELinux ( 6037): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/OMACP   ( 6016): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
E/SELinux ( 6037): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/OMACP   ( 6016): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
I/OMACP   ( 6016): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
D/PackageManager( 1016): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
I/OMACP   ( 6016): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
I/OMACP   ( 6016): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
I/OMACP   ( 6016): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
I/OMACP   ( 6016): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
I/OMACP   ( 6016): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
I/OMACP   ( 6016): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
D/ActivityManager( 1016): getContentProviderImpl callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
D/TimaKeyStoreProvider( 6037): TimaSignature is unavailable
D/ActivityThread( 5942): Loading provider com.samsung.android.sdk.samsunglink.provider.SLinkMedia: com.mfluent.asp.datamodel.ASPMediaStoreProvider
D/ActivityThread( 6037): Added TimaKeyStore provider
I/OMACP   ( 6016): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
I/OMACP   ( 6016): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
I/OMACP   ( 6016): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
W/ResourcesManager( 6037): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/SSRM:a  ( 1016): DeviceInfo:: 000000000000
D/SSRM:a  ( 1016): SettingsAirViewInfo:: 000000000
D/Compatibility( 6037): onReceive() it will make start service
D/ActivityManager( 1016): startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
D/ActivityManager( 1016): startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
D/Compatibility( 6037): onHandleIntent()
D/Compatibility( 6037): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10155, android.intent.extra.user_handle=0}]
D/Compatibility( 6037): found: 2
E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5942): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
I/UpdateIcingCorporaServi( 5466): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/art     ( 1016): Explicit concurrent mark sweep GC freed 254210(17MB) AllocSpace objects, 12(5MB) LOS objects, 33% free, 28MB/42MB, paused 2.988ms total 297.065ms
W/BaseAppContext( 2009): Using Auth Proxy for data requests.
W/BaseAppContext( 2009): Using Auth Proxy for data requests.
W/BaseAppContext( 2009): Using Auth Proxy for data requests.
I/PeopleDatabaseHelper( 2009): cleanUpNonGplusAccounts done.
D/Compatibility( 6037): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 6037): skipping ResolveInfo{36b6fe42 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 6037): considering ResolveInfo{366e8e53 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 6037): default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 6037): enabling receiver ResolveInfo{3a21390 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 6037): enabling receiver ResolveInfo{1f586489 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
I/BatteryStatsDumper( 1016): Writing to database completed
D/Compatibility( 6037): enabling receiver ResolveInfo{123abc8e com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/AndroidRuntime( 6032): 
D/AndroidRuntime( 6032): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/Compatibility( 6037): enabling receiver ResolveInfo{c49bcaf com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 6037): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
D/AndroidRuntime( 6032): CheckJNI is OFF
D/AndroidRuntime( 6032): readGMSProperty: start
D/AndroidRuntime( 6032): readGMSProperty: already setted!!
D/AndroidRuntime( 6032): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6032): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6032): readGMSProperty: end
D/AndroidRuntime( 6032): addProductProperty: start
D/ActivityManager( 1016): startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
W/libprocessgroup( 1016): failed to open /acct/uid_10042/pid_5410/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10142/pid_5389/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10104/pid_5364/cgroup.procs: No such file or directory
E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5942): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
D/ActivityManager( 1016): startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.mfluent.asp.ContentAggregatorService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
W/BaseAppContext( 2009): Using Auth Proxy for data requests.
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6072): MountEmulatedStorage()
E/Zygote  ( 6072): v2
I/libpersona( 6072): KNOX_SDCARD checking this for 10041
I/libpersona( 6072): KNOX_SDCARD not a persona
I/SELinux ( 6072): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.app.pushmarketing.PushMarketingReceiver: pid=6072 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 6072): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6072): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
D/TimaKeyStoreProvider( 6072): TimaSignature is unavailable
D/ActivityThread( 6072): Added TimaKeyStore provider
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/GAV2    ( 5848): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/SA      ( 6072): [SSP] onCreated
I/SA      ( 6072): [TPM] There is no property file
I/SA      ( 6072): [SCU] isHaveSA() - false
I/SA      ( 6072): [TPM] getModelProperty : null
I/SA      ( 6072): [TPM] getCSCProperty : null
I/SA      ( 6072): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 6072): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 6072): [DM] TFT FEATURE: false
I/SA      ( 6072): [PMR] Received action : android.intent.action.PACKAGE_ADDED
I/SA      ( 6072): [DM] init START
I/SA      ( 6072): [DM] This device is not a Vodafone
I/UpdateIcingCorporaServi( 5466): UpdateCorporaTask done [took 307 ms] updated apps [took 307 ms] 
W/ResourceType( 6072): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
W/ResourceType( 6072): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 6072): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
W/ResourceType( 6072): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 6072): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
W/ResourceType( 6072): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 6072): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
W/ResourceType( 6072): No package identifier when getting value for resource number 0x00000000
W/ResourceType( 6072): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
W/ResourceType( 6072): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
I/ActivityManager( 1016): Killing 5529:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
W/ResourceType( 6072): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
W/ResourceType( 6072): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
W/ResourceType( 6072): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
W/ResourceType( 6072): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
W/ResourceType( 6072): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
W/ResourceType( 6072): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
W/ResourceType( 6072): Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
W/ResourceType( 6072): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
W/ResourceType( 6072): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
W/ResourceType( 6072): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
W/ResourceType( 6072): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 6072): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 6072): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
W/ResourceType( 6072): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
W/ResourceType( 6072): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
I/SA      ( 6072): [SCU] isHaveSA() - false
I/SA      ( 6072): support phone number id : false
I/SA      ( 6072): [DM] Supports Ref Jpn : true
I/SA      ( 6072): [DM] init END
I/SA      ( 6072): [SUR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
I/SA      ( 6072): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10155 extra.user_handle.:0 ]
I/ActivityManager( 1016): Killing 5559:com.sec.knox.foldercontainer/1000 (adj 15): empty #31
W/libprocessgroup( 1016): failed to open /acct/uid_10069/pid_5529/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_5559/cgroup.procs: No such file or directory
E/AffinityControl( 6032): AffinityControl: registerfunction enter
D/AndroidRuntime( 6032): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1016): inState():  stateMachine is null !!
I/PersonaManagerService( 1016): PersonaId don't exist
I/ActivityManager( 1016): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
W/ActivityManager( 1016): mDVFSHelper.acquire()
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1016): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1016): *FMB* installDecor flags : 25362712
I/ActivityManager( 1016): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6108 uid=10155 gids={50155, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1016): Focused application set to: xxxx
D/InputDispatcher( 1016): Focus left window: 3158
E/Zygote  ( 6108): MountEmulatedStorage()
I/libpersona( 6108): KNOX_SDCARD checking this for 10155
E/Zygote  ( 6108): v2
I/libpersona( 6108): KNOX_SDCARD not a persona
I/SELinux ( 6108): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6108): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/AndroidRuntime( 6032): Shutting down VM
E/SELinux ( 6108): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
D/PhoneWindow( 1016): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1016): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  259): id=13 createSurf (1x1),1 flag=404, uhalitest
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
I/art     (  311): Explicit concurrent mark sweep GC freed 8683(369KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 778us total 23.135ms
D/TimaKeyStoreProvider( 6108): TimaSignature is unavailable
D/ActivityThread( 6108): Added TimaKeyStore provider
I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 646us total 16.891ms
I/Icing   ( 2009): Indexing 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28 from com.google.android.gms
I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 609us total 17.790ms
E/Zygote  ( 6123): MountEmulatedStorage()
E/Zygote  ( 6123): v2
I/libpersona( 6123): KNOX_SDCARD checking this for 10100
I/libpersona( 6123): KNOX_SDCARD not a persona
I/SELinux ( 6123): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6123): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6123): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=6123 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 5576:com.google.android.apps.plus/u0a120 (adj 15): empty #31
D/ActivityManager( 1016): startService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.apps.docs
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.apps.docs/com.google.android.apps.docs.sync.syncadapter.ContentSyncService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.apps.docs
W/GAV2    ( 5848): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
V/ActivityManager( 1016): Display changed displayId=0
D/StatusBarManagerService( 1016): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/TimaKeyStoreProvider( 6123): TimaSignature is unavailable
D/ActivityThread( 6123): Added TimaKeyStore provider
D/PersonaManager( 1016): isKioskContainerExistOnDevice
D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
V/GLSActivity( 1846): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PackageIntentReceiver( 6123): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 6123): Not GearManger package! 
W/AccountFeatureHelper( 5848): Write apps_features disabled false
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/SurfaceFlinger(  259): id=10 Removed YUIInstallC (5/9)
I/SurfaceFlinger(  259): id=10 Removed YUIInstallC (-2/9)
I/ActivityManager( 1016): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=6143 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/Zygote  ( 6143): MountEmulatedStorage()
E/Zygote  ( 6143): v2
I/libpersona( 6143): KNOX_SDCARD checking this for 1000
I/libpersona( 6143): KNOX_SDCARD not a persona
I/SELinux ( 6143): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6143): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ServiceManager(  323): Waiting for service AtCmdFwd...
E/SELinux ( 6143): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/libprocessgroup( 1016): failed to open /acct/uid_10120/pid_5576/cgroup.procs: No such file or directory
W/art     ( 6032): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
V/ActivityThread( 3158): updateVisibility : ActivityRecord{5aa6983 token=android.os.BinderProxy@15e390d6 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
W/GAV2    ( 5848): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,I/ActivityManager( 1016): Killing 5221:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
,D/TimaKeyStoreProvider( 6143): TimaSignature is unavailable
,D/ActivityThread( 6143): Added TimaKeyStore provider
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/Icing   ( 2009): Indexing done 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28
,I/WebViewFactory( 6108): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,W/libprocessgroup( 1016): failed to open /acct/uid_10150/pid_5221/cgroup.procs: No such file or directory
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/LibraryLoader( 6108): Time to load native libraries: 2 ms (timestamps 792-794),
I/LibraryLoader( 6108): Expected native library version number "",actual native library version number ""
,E/Zygote  ( 6160): MountEmulatedStorage()
I/ActivityManager( 1016): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=6160 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/Zygote  ( 6160): v2
I/libpersona( 6160): KNOX_SDCARD checking this for 1000
I/libpersona( 6160): KNOX_SDCARD not a persona
I/SELinux ( 6160): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6160): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6160): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Killing 5083:com.sec.android.app.music:service/u0a40 (adj 15): empty #31
,V/WebViewChromiumFactoryProvider( 6108): Binding Chromium to main looper Looper (main, tid 1) {3a21390}
,I/LibraryLoader( 6108): Expected native library version number "",actual native library version number ""
I/chromium( 6108): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,D/TimaKeyStoreProvider( 6160): TimaSignature is unavailable
,D/ActivityThread( 6160): Added TimaKeyStore provider
,I/BrowserStartupController( 6108): Initializing chromium process, singleProcess=true
,W/art     ( 6108): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6108): ApplicationContext is null in ApplicationStatus
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,W/chromium( 6108): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
I/chromium( 6108): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
I/chromium( 6108): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
D/AcmsPackageEventListener( 6160): Received: android.intent.action.PACKAGE_ADDED
,I/Adreno-EGL( 6108): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e),
I/Adreno-EGL( 6108): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6108): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6108): Local Branch: 
I/Adreno-EGL( 6108): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6108): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
,I/Adreno-EGL( 6108):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
W/ContextImpl( 6160): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,E/Zygote  ( 6181): MountEmulatedStorage(),
E/Zygote  ( 6181): v2
,I/libpersona( 6181): KNOX_SDCARD checking this for 10120
I/SELinux ( 6181): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 6181): KNOX_SDCARD not a persona
,I/SELinux ( 6181): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1016): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6181 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 4568:com.google.android.music:main/u0a111 (adj 15): empty #31
,E/SELinux ( 6181): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
,I/wpa_supplicant( 2142): nl80211: Received scan results (3 BSSes)
,D/WifiP2pService( 1016): InactiveState{ what=147461 }
D/WifiP2pService( 1016): P2pEnabledState{ what=147461 }
D/WifiP2pService( 1016): DefaultState{ what=147461 }
,D/AcmsService( 6160): Enter Oncreate
,D/AcmsServiceMonitor( 6160): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsService( 6160): creating AcmsCore
,D/AcmsCore( 6160): AcmsCore.getAcmsCore() - Enter
,D/AcmsCore( 6160): AcmsCore
,D/AcmsCore( 6160): init
D/AcmsCore( 6160): Looper handler is not null
D/AcmsCore( 6160): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 6160): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6160): Incrementing - Counter value: 1
D/AcmsCore( 6160): Incremented Counter Value: postToAcmsCoreHandler =>1
,D/AcmsService( 6160): onStartCommand
D/AcmsService( 6160): Action: android.intent.action.PACKAGE_ADDED
D/AcmsServiceMonitor( 6160): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor( 6160): Incrementing - Counter value: 2
D/AcmsService( 6160): Incremented Counter Value : onStartCommand
,D/TimaKeyStoreProvider( 6181): TimaSignature is unavailable
,D/ActivityManager( 1016): getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
,D/ActivityThread( 6160): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
D/ActivityThread( 6181): Added TimaKeyStore provider
,D/AcmsCertificateMngr( 6160): AcmsCertificateMngr
,D/AcmsRevocationMngr( 6160): AcmsRevocationMngr
,W/ResourcesManager( 6181): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/AcmsService( 6160): Inside handle Intent
D/AcmsService( 6160): App added - package name: com.test.thalitest
D/AcmsCore( 6160): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 6160): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6160): Incrementing - Counter value: 3
D/AcmsCore( 6160): Incremented Counter Value: postToAcmsCoreHandler =>2
D/AcmsService( 6160): Decremented Counter Value : handleStartIntent
D/AcmsServiceMonitor( 6160): Decrementing - Counter value: 2
,I/qtaguid ( 5597): Untagging socket 44
,I/System.out( 5597): Thread-963 calls detatch()
,D/Volley  ( 5597): [963] BasicNetwork.performRequest: HTTP response for request=<[ ] https://android.clients.google.com/fdfe/toc 0xe8d195d1 NORMAL 1> [lifetime=3243], [size=4639], [rc=200], [retryCount=0]
,W/libprocessgroup( 1016): failed to open /acct/uid_10040/pid_5083/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_10111/pid_4568/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 2009): Loading module com.google.android.gms.games from APK com.google.android.play.games
,W/chromium( 6108): [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,D/ChimeraModuleLdr( 2009): Module APK com.google.android.play.games already loaded
,D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1846): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager( 1016): Activity pause timeout for ActivityRecord{3925aeb0 u0 com.test.thalitest/.MainActivity t8}
,I/Mms/MmsApp( 5774):  start initViewCache mms
,D/Mms/ComposeMessageFragment( 5774): [start]    fillCache consume time = 1822.078593
D/Mms/ComposeMessageFragment( 5774): fillCache, easy = false
,I/System.out( 5597): Thread-962(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 5597): Thread-962(ApacheHTTPLog):isShipBuild true
,I/System.out( 5597): Thread-962(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5597): Thread-962(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,W/art     ( 6108): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6108): onDetachedFromWindow called when already detached. Ignoring
,D/PhoneWindow( 6108): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 6108): *FMB* installDecor flags : 8456448
,D/SystemWebViewEngine( 6108): CordovaWebView is running on device made by: samsung
,W/art     ( 6108): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 6108): Attempt to remove local handle scope entry from IRT, ignoring
,D/AbsListView( 5774): Get MotionRecognitionManager
,D/MotionRecognitionService( 1016):  ssp status : false
,D/Mms/ComposeMessageFragment( 5774): [end]    fillCache consume time = 108.026875
,I/Icing   ( 2009): Indexing 675A4012BEFF6588AF9C8DE380F736BA72E6F9BD from com.google.android.googlequicksearchbox
,I/qtaguid ( 5597): Untagging socket 44
,I/qtaguid ( 5597): Failed write_ctrl(u 44) res=-1 errno=22
,D/OpenGLRenderer( 6108): Render dirty regions requested: true
,I/qtaguid ( 5597): Untagging socket 44 failed errno=-22
,D/ActivityManager( 1016): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1016): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1016): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1016): handleActiveUserChange for user 0
D/PersonaManagerService( 1016): getPersonasForUser(): returning null!
,W/NetworkManagementSocketTagger( 5597): untagSocket(44) failed with errno -22
,I/System.out( 5597): Thread-962 calls detatch()
,D/Finsky  ( 5597): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,V/ActivityThread( 6108): updateVisibility : ActivityRecord{24c5e8ec token=android.os.BinderProxy@3c15653e {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/PhoneWindow( 6108): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 6108): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  259): id=14 createSurf (1x1),1 flag=404, NainActivit
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/InputDispatcher( 1016): Focus entered window: 6108
,D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/SRIB_DCS( 6108): log_dcs ThreadedRenderer::initialize entered! 
D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
,I/OpenGLRenderer( 6108): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6108): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 6108): Enabling debug mode 0
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/InputMethodManagerService( 1016): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/PanelView( 1179): There is/are notification(s) 
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ActivityManager( 1016): Displayed Component not be shown by security: +784ms (total +919ms),
,I/Timeline( 1016): Timeline: Activity_windows_visible id: ActivityRecord{3925aeb0 u0 com.test.thalitest/.MainActivity t8} time:81381
W/ActivityManager( 1016): mDVFSHelper.release()
D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator,
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,I/SamsungIME( 1793): getCurrentCandidateView
,V/GLSActivity( 1846): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SurfaceFlinger(  259): id=13 Removed uhalitest (7/9)
W/IInputConnectionWrapper( 6108): showStatusIcon on inactive InputConnection
,I/Timeline( 6108): Timeline: Activity_idle id: android.os.BinderProxy@3c15653e time:81398
,I/SurfaceFlinger(  259): id=13 Removed uhalitest (-2/9)
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6235): MountEmulatedStorage()
,E/Zygote  ( 6235): v2
,I/libpersona( 6235): KNOX_SDCARD checking this for 10012
,I/libpersona( 6235): KNOX_SDCARD not a persona
,I/ActivityManager( 1016): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6235 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a,
,I/splitIntent( 1016): Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/SELinux ( 6235): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6235): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6235): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/Mms/BubbleViewCache( 5774): fillCache bubble = 1
,D/TimaKeyStoreProvider( 6235): TimaSignature is unavailable
,D/ActivityThread( 6235): Added TimaKeyStore provider
,D/daemonapp( 1303): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1303): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1303): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1303): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/System.out( 5597): Thread-963(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 5597): Thread-963(ApacheHTTPLog):isShipBuild true
I/System.out( 5597): Thread-963(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5597): Thread-963(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/Icing   ( 2009): Indexing done 675A4012BEFF6588AF9C8DE380F736BA72E6F9BD
,D/daemonapp( 1303): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1303): [MSC_Daemon]>>> WDSM:54 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,D/comsamsunglog( 1303): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1303): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,D/comsamsunglog( 1303): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1303): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1303): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 1303): [MSC_Daemon]>>> WDSM:441 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/daemonapp( 1303): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,W/BindingManager( 6108): Cannot call determinedVisibility() - never saw a connection for the pid: 6108
,W/ResourcesManager( 6235): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6235): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/daemonapp( 1303): [MSC_Daemon]>>> WDSM:444 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 1303): [MSC_Daemon]>>> WDSM:445 [0:0] [ASO][NUT] = 1453852500000
,D/daemonapp( 1303): [MSC_Daemon]>>> WDSM:446 [0:0] [ASO][CT] = 1453830956538
,D/daemonapp( 1303): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1303): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,D/daemonapp( 1303): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1303): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1303): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,D/daemonapp( 1303): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/SamsungIME( 1793): Dismiss ExpandCandiate
,E/daemonapp( 1303): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,I/MultiDex( 6235): VM with version 2.1.0 has multidex support
I/MultiDex( 6235): install
I/MultiDex( 6235): VM has multidex support, MultiDex support library is disabled.
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/accuweather( 1729): [KK AccuPhone]>>> WCW:32 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,D/daemonapp( 1303): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/accuweather( 1729): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1,
,D/accuweather( 1729): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1729): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1,
D/accuweather( 1729): [KK AccuPhone]>>> UIM:312 [0:0]  action:widgetactionWEATHER_SCREEN_OFF
D/daemonapp( 1303): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,D/daemonapp( 1303): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,V/JNIHelp ( 6235): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/JsMessageQueue( 6108): Set native->JS mode to OnlineEventsBridgeMode
,D/accuweather( 1729): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
,D/accuweather( 1729): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,D/accuweather( 1729): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
D/accuweather( 1729): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/accuweather( 1729): [KK AccuPhone]>>> WC:30 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/accuweather( 1729): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/qtaguid ( 5597): Untagging socket 44,
I/qtaguid ( 5597): Failed write_ctrl(u 44) res=-1 errno=22
I/qtaguid ( 5597): Untagging socket 44 failed errno=-22,
W/NetworkManagementSocketTagger( 5597): untagSocket(44) failed with errno -22
I/System.out( 5597): Thread-963 calls detatch(),
,I/SamsungIME( 1793): getDebugLevel  : 0x4f4c
,W/ActivityThread( 6235): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6235): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1d0af238: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6235): Installed default security provider GmsCore_OpenSSL
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1016): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
I/splitIntent( 1016): base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
I/splitIntent( 1016): other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
I/splitIntent( 1016): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 6235): Reading stored module config
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SamsungIME( 1793): getDebugLevel  : 0x4f4c
,D/WearableService( 1846): callingUid 10012, callindPid: 1846
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/jxcore_app_log( 6108): JniHelper::setJavaVM(0xb796b450), pthread_self() = -1209271120
,E/MDM     ( 1846): [262] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 6235): Loading module com.google.android.gms.car from APK com.google.android.gms
,I/SamsungIME( 1793): KeybaordView init() : load resources
,I/chromium( 6108): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1846): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 2009): Restart initialization of location
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
I/SamsungIME( 1793): getCurrentKeyboard
I/SamsungIME( 1793): getTextKeyboard
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SamsungIME( 1793): [SwiftkeyWrapper] currentLangauge : 1701729619
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1846): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/NativeLibraryUtils( 6235): Install completed successfully. count=14 extracted=0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.crypto.ChannelBindingStateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/art     ( 5597): Suspending all threads took: 5.827ms
,W/GCoreFlp( 1846): No location to return for getLastLocation()
,W/FusedLocationProvider( 1846): location=null
,I/DBG_POLICYDM( 5864): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 5864): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 5864): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 5864): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 5864): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 5864): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 5864): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,D/CAR.SERVICE( 6235): Connecting to CarCallService...
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.car.CarCallService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/art     ( 6235): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 6235): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/CAR.SERVICE( 6235): com.google.android.projection.gearhead isn't installed.
,I/ActivityManager( 1016): Killing 4900:com.sec.android.widgetapp.SPlannerAppWidget/u0a134 (adj 15): empty #31
,D/CAR.TEL.Service( 6235): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 6235): Creating a new PhoneAdapter instance
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: local_bind
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.car.InCallServiceImpl; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 6235): setListener: com.google.android.gms.car.dn@f6abe67
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: local_bind
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.car.InCallServiceImpl; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 6235): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6235): Starting CarCallService with initial phone null
,W/libprocessgroup( 1016): failed to open /acct/uid_10134/pid_4900/cgroup.procs: No such file or directory
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 30212(1567KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 27MB/41MB, paused 2.603ms total 161.337ms
,D/CAR.SERVICE( 6235): Package validated; name: com.android.vending
,V/Finsky  ( 5597): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,D/SamsungIME( 1793): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1846): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,W/jxcore-log( 6108): Initializing JXcore engine
W/jxcore-log( 6108): JXcore engine is ready
,I/System.out( 5597): Thread-962(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 5597): Thread-962(ApacheHTTPLog):isShipBuild true
I/System.out( 5597): Thread-962(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5597): Thread-962(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,E/audit   ( 1903): type=1400 msg=audit(1453830958.357:205): avc:  denied  { ioctl } for  pid=6258 comm="Thread-1070" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1903):  SEPF_SM-A500FU_5.0.2-1_0038
,E/audit   ( 1903): type=1300 msg=audit(1453830958.357:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9e8c08f8 items=0 ppid=311 ppcomm=main pid=6258 auid=4294967295 uid=10155 gid=10155 euid=10155 suid=10155 fsuid=10155 egid=10155 sgid=10155 fsgid=10155 ses=4294967295 tty=(none) comm="Thread-1070" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
,E/audit   ( 1903): type=1320 msg=audit(1453830958.357:205): 
,W/jxcore-log( 6108): Starting JXcore engine
,I/qtaguid ( 5597): Untagging socket 44
,I/qtaguid ( 5597): Failed write_ctrl(u 44) res=-1 errno=22
I/qtaguid ( 5597): Untagging socket 44 failed errno=-22
,W/NetworkManagementSocketTagger( 5597): untagSocket(44) failed with errno -22
I/System.out( 5597): Thread-962 calls detatch()
,W/jxcore-log( 6108): Platform android
W/jxcore-log( 6108): 
W/jxcore-log( 6108): Process ARCH arm
W/jxcore-log( 6108): 
,V/AlarmManager( 1016): waitForAlarm result :4
,D/KeyguardViewMediator( 1179): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,D/KeyguardViewMediator( 1179): doKeyguard: not showing because lockscreen is off
,V/KeyguardEffectViewController( 1179): *** Keyguard wallpaper service already unbounded
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 5
,W/ResourcesManager( 5597): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5597): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 5597): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ActivityManager( 1016): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.wear.WearSupportService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/Finsky  ( 5597): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager( 1016): waitForAlarm result :4
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/Finsky  ( 5597): [984] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5597): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 5597): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,I/art     ( 1846): Explicit concurrent mark sweep GC freed 31268(1987KB) AllocSpace objects, 13(208KB) LOS objects, 39% free, 12MB/21MB, paused 1.204ms total 67.470ms
,E/DataBuffer( 1846): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@ed93aae)
,D/DeviceConnectionService( 1846): client connected with version: 8296000
V/GLSActivity( 1846): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 5597): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 5597): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 5597): (HTTPLog)-Static: isShipBuild true
I/System.out( 5597): (HTTPLog)-Thread-973-881984823: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 5597): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  279): uids 10028
D/EnterpriseController(  279): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 502 for uid 10028
,I/System.out( 5597): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/jxcore-log( 6108): JXcore Cordova bridge is ready!
I/jxcore-log( 6108): 
,W/jxcore-log( 6108): JXcore engine is started
,E/jxcore  ( 6108): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 6108): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 6108): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,D/InputDispatcher( 1016): Focused application set to: xxxx
,I/ActivityManager( 1016): Killing 4385:com.android.calendar/u0a135 (adj 15): empty #31
,I/SurfaceFlinger(  259): id=14 Removed NainActivit (6/8)
,I/SurfaceFlinger(  259): id=14 Removed NainActivit (-2/8)
,D/InputDispatcher( 1016): Focus left window: 6108
,D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
W/ActivityManager( 1016): mDVFSHelper.acquire()
,E/ViewRootImpl( 6108): sendUserActionEvent() mView == null
,I/DBG_DM  ( 3158): [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] 
,I/DBG_DM  ( 3158): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 20
,I/DBG_DM  ( 3158): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,W/libprocessgroup( 1016): failed to open /acct/uid_10135/pid_4385/cgroup.procs: No such file or directory
,I/DBG_DM  ( 3158): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3158): [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 20
,I/DBG_DM  ( 3158): [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,I/DBG_DM  ( 3158): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,I/DBG_DM  ( 3158): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,I/DBG_DM  ( 3158): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,D/ApplicationPolicy( 1016): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,W/NotificationService( 1016): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1179): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
D/PersonaManager( 1179): isKioskContainerExistOnDevice
,D/PanelView( 1179): There is/are notification(s) 
D/PanelView( 1179): kidsfalse mQsExpansionEnabled:true
I/DBG_DM  ( 3158): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 20
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
,D/PanelView( 1179): There is/are notification(s) 
D/PanelView( 1179): kidsfalse mQsExpansionEnabled:true
,I/DBG_DM  ( 3158): [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,I/PowerManagerService( 1016): [PWL] Off : 5s ago
I/PowerManagerService( 1016): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService( 1016): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 1016): [PWL]       PARTIAL_WAKE_LOCK              'wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService' (uid=10028, pid=5597, ws=null) (elapsedTime=358)
,I/DBG_DM  ( 3158): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3158): [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/DBG_DM  ( 3158): [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] 
,I/DBG_DM  ( 3158): [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
,I/ActivityManager( 1016): Killing 5448:com.samsung.aasaservice/1000 (adj 15): empty #31
,I/ActivityManager( 1016): Killing 5236:com.google.android.gm/u0a101 (adj 15): empty #32
,D/ActivityManager( 1016): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1016): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1016): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1016): handleActiveUserChange for user 0
I/DBG_DM  ( 3158): [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] 
D/PersonaManagerService( 1016): getPersonasForUser(): returning null!
,I/SurfaceFlinger(  259): id=15 createSurf (720x1280),1 flag=404, YUIInstallC
,D/StatusBarManagerService( 1016): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 1016): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/InputDispatcher( 1016): Focus entered window: 3158
,D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 3158): log_dcs ThreadedRenderer::initialize entered! 
,V/ActivityThread( 3158): updateVisibility : ActivityRecord{5aa6983 token=android.os.BinderProxy@15e390d6 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,D/InputMethodManagerService( 1016): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/IInputConnectionWrapper( 6108): showStatusIcon on inactive InputConnection
,D/SamsungIME( 1793): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,D/PanelView( 1179): There is/are notification(s) 
,I/Timeline( 3158): Timeline: Activity_idle id: android.os.BinderProxy@15e390d6 time:84277
,D/PanelView( 1179): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,D/PersonaManager( 1016): isKioskContainerExistOnDevice
,W/ActivityManager( 1016): mDVFSHelper.release()
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_5448/cgroup.procs: No such file or directory
I/Timeline( 1016): Timeline: Activity_windows_visible id: ActivityRecord{24d45da7 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t7} time:84308
,W/libprocessgroup( 1016): failed to open /acct/uid_10101/pid_5236/cgroup.procs: No such file or directory
,D/AcmsKeyStoreHelper( 6160):  getKeyStoreForApplication Enter
,I/AcmsKeyStoreHelper( 6160): Key Store exist
I/AcmsKeyStoreHelper( 6160): Hence loading the keystore file
,D/AcmsKeyStoreHelper( 6160):  getKeyStoreForApplication Exit
,I/AcmsCertificateMngr( 6160): getKeyStoreForApplication success 
,D/AcmsCore( 6160): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor( 6160): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
,D/AcmsServiceMonitor( 6160): Decrementing - Counter value: 1
D/AcmsCore( 6160): AcmsCore: ACMS_APP_INSTALLED
,D/AcmsCore( 6160): This is NOT a valid MirrorLink app
,D/AcmsCore( 6160): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor( 6160): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6160): Decrementing - Counter value: 0
,D/AcmsServiceMonitor( 6160): Counter value is 0: Stopping ACMS service
,D/AcmsServiceMonitor( 6160): getSvcCounter - Counter value: 0
,D/AcmsService( 6160): Enter onDestroy
I/AcmsService( 6160): cleanUp(): inside service clean up
,D/AcmsCore( 6160): AcmsCore: inside DeInit
D/AcmsCore( 6160): AcmsCore: mLooperHandler is not null and making it null
,D/AcmsCertificateMngr( 6160): AcmsCertificateMngr: inside cleanup
,D/AcmsRevocationMngr( 6160): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper( 6160): KeyStoreHelper: inside cleanup
D/AcmsAppEntryInterface( 6160): AppEntryInterface: Inside CleanUp
,D/AcmsServiceMonitor( 6160): getSvcCounter - Counter value: 0
,D/AcmsService( 6160): killing acms process
,I/Process ( 6160): Sending signal. PID: 6160 SIG: 9
,I/ActivityManager( 1016): Process ACMS.Process (pid 6160)(adj 0) has died(49,1134)
,V/AlarmManager( 1016): waitForAlarm result :8
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0,
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.gms
,E/SMD     (  292): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/LightsService( 1016): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 1016) 
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
D/LightsService( 1016): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x10 -> 0x40 | SvcLED(id=3) set On
,D/BatteryService( 1016): turn on LED for fully charged
,D/LightsService( 1016): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
,E/lights  ( 1016): write_int failed to open -1
,D/LightsService( 1016): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,D/SecKeyguardStatusUtils( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/SecContentProvider2( 1016): uri = 14 selection = getSealedState
,D/SecContentProvider2( 1016): mCursor = null
,V/HeadsetService( 2635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2635): Disconnected process message: 10
,D/ApplicationPolicy( 1016): isStatusBarNotificationAllowedAsUser: packageName = com.android.systemui,userId = -1
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId -1 pkgname com.android.systemui
,I/ValidateNoPeople( 1016): skipping global notification
,D/WindowManager( 1016): showStatusBarByNotification() mOpenByNotification=false
,D/PowerManagerService( 1016): [api] acquire WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10054 pid=1179
I/PowerManagerService( 1016): !@[ps] Screen__On  - 1 :  wl: PowerUI.Notification (14)
I/PowerManagerService( 1016): Waking up from sleep (uid 10054)...
,D/PowerManagerService( 1016): [PWL] sb acquire: PowerManagerService.Broadcasts
,V/KeyguardServiceDelegate( 1016): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$2@22cda525)
,D/KeyguardViewMediator( 1179): onScreenTurnedOn, seq = 2
D/KeyguardViewMediator( 1179): notifyScreenOnLocked
,D/PowerManagerService( 1016): [s] UserActivityState : 0 -> 1
,I/DisplayPowerController( 1016): Blocking screen on until initial contents have been drawn.
,D/WindowOrientationListener( 1016): sensor enabled
,I/Sensors ( 1016): AccelerometerSensor(0) setDelay : 66000000(ns)
,D/DisplayPowerController( 1016): getFinalBrightness : Summary is 5 -> 5
D/DisplayPowerController( 1016): animation target = 5, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 1016): [PWL] sb acquire: PowerManagerService.Display
D/DisplayPowerController( 1016): getFinalBrightness : Summary is 5 -> 5
D/DisplayPowerController( 1016): animation target = 5, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/libsuspend( 1016): !@autosuspend_wakeup_count_disable
I/libsuspend( 1016): !@autosuspend_wakeup_count_disable done
D/DisplayManagerService( 1016): !@display_state: OFF -> ON
,D/SurfaceFlinger(  259): Set power mode=2, type=0 flinger=0xb8bb1690
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/qdhwcomposer(  259): hwc_setPowerMode: Setting mode 2 on display: 0
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SensorService( 1016): [SO] changed settle time [1]
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SensorService( 1016): [SO] setDelay [66000000]
D/SensorService( 1016): [SO] activate (ident=0xb81a4738, enabled=1)
,D/SensorService( 1016): [SO] AR_init
I/Sensors ( 1016): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
E/qdutils (  259): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  259): int qdutils::getHDMINode(): Failed to find HDMI node
,I/DisplayManagerService( 1016): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state ON, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,D/PersonaManager( 1016): isKioskContainerExistOnDevice
,D/SensorManager( 1016): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
,V/ActivityManager( 1016): Display changed displayId=0
,D/KeyguardViewMediator( 1179): handleNotifyScreenOn
,D/StatusBarKeyguardViewManager( 1179): onScreenTurnedOn()
,D/SecKeyguardClockSingleView( 1179): onScreenTurnedOn
,D/SecKeyguardStatusUtils( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/DBG_DM  ( 3158): [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] 
,D/CoverManagerWhiteLists( 1016): isAllowedToUse : SIGNATURE_MATCH
,I/PalmMotion( 1016): [PALM] 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1
I/PalmMotion( 1016): [PALM] SURFACE_PALM_SWIPE: 1
D/PalmMotion( 1016): [PALM] SETTINGS : [TOUCH: true] [SWEEP: true]
E/MotionRecognitionService( 1016):   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
D/PalmMotion( 1016): [PALM] ACCEPTED : [default] PALM_CNT : 3, M_TOUCH : 1000.0, M_SWEEP : 100.0, E_SWEEP : 2.0, IGNORE_M_SWEEP : false
D/LightsService( 1016): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1016) 
,D/LightsService( 1016): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
,D/LightsService( 1016): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1016): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRM:a  ( 1016): DeviceInfo:: 000000000000
,D/SSRM:a  ( 1016): SettingsAirViewInfo:: 000000000
,D/SamsungIME( 1793): showDlgMsgBox : false true true
,I/DBG_DM  ( 3158): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 20
,D/NfcService( 1439): call the applyRouting
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,I/DBG_DM  ( 3158): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.android.settings
,I/DBG_DM  ( 3158): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3158): [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 20
,D/KnoxNotification( 1179): ----- inflateViews : modified publicViewLocal -----
,D/SensorService( 1016): [SO] currT = 86020076997, prevT = 78530091375, diff = 7489985622, [0.019 0.096 10.075]
,D/SensorService( 1016): [SO] Reset Rotation Old [100], Init [1]
D/LightsService( 1016): [api] [SvcLED] turnOff:: id = 3 (uid: 1000 pid: 1016) 
,D/LightsService( 1016): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x0 | SvcLED(id=3) set Off
D/BatteryService( 1016): turn off LED
D/LightsService( 1016): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
E/lights  ( 1016): write_led_info failed to open -1
E/lights  ( 1016): write_led_info failed to open -1
D/LightsService( 1016): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
E/lights  ( 1016): write_led_info failed to open -1
E/lights  ( 1016): write_led_info failed to open -1
E/lights  ( 1016): write_led_info failed to open -1
E/lights  ( 1016): write_led_info failed to open -1
E/lights  ( 1016): write_led_info failed to open -1
E/lights  ( 1016): write_led_info failed to open -1
E/lights  ( 1016): write_led_info failed to open -1
,I/DBG_DM  ( 3158): [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,V/AlarmManager( 1016): ___SyncScheduler (v3) ACTIVATED___
,I/DBG_DM  ( 3158): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,V/AlarmManagerEXT( 1016): <AppSync3 Whitelist>
V/AlarmManagerEXT( 1016): (AppSync) ### 0 added ###
,D/KnoxNotification( 1179): ----- inflateViews : modified KnoxViewLocal -----
,E/SmartFaceService( 1016): onReceive: android.intent.action.SCREEN_ON
,W/System.err( 1016): java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
,W/System.err( 1016): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 1016): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err( 1016): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
W/System.err( 1016): 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
W/System.err( 1016): 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
W/System.err( 1016): 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:468)
W/System.err( 1016): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
W/System.err( 1016): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 1016): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 1016): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 1016): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/PersonaManager( 1179): PersonaID is invalid or persona doesn't exists. : -1
W/System.err( 1016): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
,W/System.err( 1016): 	at libcore.io.Posix.open(Native Method)
W/System.err( 1016): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/SmartFaceService( 1016): fail to set sysfs 1
W/System.err( 1016): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 1016): 	... 10 more
I/DBG_DM  ( 3158): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
D/PersonaManager( 1179): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1179): Icon Only
I/StatusBar( 1179): Icon Only
,D/PanelView( 1179): There is/are notification(s) 
D/PanelView( 1179): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1179): Icon Only
I/StatusBar( 1179): Icon Only
D/PanelView( 1179): There is/are notification(s) 
D/PanelView( 1179): kidsfalse mQsExpansionEnabled:true
,D/qdhwcomposer(  259): hwc_setPowerMode: Done setting mode 2 on display 0
,I/qdhwcomposer(  259): handle_blank_event: dpy:0 panel power state: 1
D/SurfaceControl( 1016): Excessive delay in setPowerMode(): 109ms
,D/PowerManagerService( 1016): Excessive delay in !@display_state: ON: 110ms
D/MISC PowerHAL( 1016): sysfs_write +: /sys/class/input/event1/device/enabled: 1
I/DBG_DM  ( 3158): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,E/qdutils (  259): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  259): int qdutils::getHDMINode(): Failed to find HDMI node
,D/MISC PowerHAL( 1016): sysfs_write +: /sys/class/input/event3/device/enabled: 1
D/StatusBarKeyguardViewManager( 1179): callback.onShown()
D/StatusBar.NetworkController( 1179): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1179): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1179): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1179): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1179): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1179): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1179): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
V/KeyguardServiceDelegate( 1016): **** SHOWN CALLED ****
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.TIME_TICK
D/PanelView( 1179): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,D/DisplayPowerController( 1016): [api] WindowManagerPolicy.ScreenOnListener : Received onScreenOn().
,I/DisplayPowerController( 1016): Unblocked screen on after 124 ms
,D/DisplayPowerState( 1016): !@ ColorFade exit
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,I/SurfaceFlinger(  259): id=12 Removed DolorFade (8/8)
D/KeyguardUpdateMonitor( 1179): handleTimeUpdate
,I/SurfaceFlinger(  259): id=12 Removed DolorFade (-2/8)
,E/libEGL  ( 1016): call to OpenGL ES API with no current context (logged once per thread)
D/DisplayPowerController( 1016): getFinalBrightness : Summary is 5 -> 5
D/DisplayPowerController( 1016): animation target = 5, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/lights  ( 1016): lcd : 5 +
,V/UserPresentBroadcastReceiver( 1846): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,D/InputMethodManagerService( 1016): [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
,D/ApplicationPolicy( 1016): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,D/lights  ( 1016): lcd : 5 -
D/DisplayPowerController( 1016): getFinalBrightness : Summary is 5 -> 5
D/DisplayPowerController( 1016): animation target = 5, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 1016): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService( 1016): SecHardwareInterface.setBatteryADC : true
,D/SecKeyguardClockView( 1179): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,I/DBG_DM  ( 3158): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 20
,D/SecKeyguardClockView( 1179): HomeTimezone(): 1
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,D/SensorService( 1016): [SO] currT = 86090097674, prevT = 78530091375, diff = 7560006299, [0.019 0.077 10.075]
D/SensorService( 1016): [SO] 0.019 0.077 10.075
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/DBG_DM  ( 3158): [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
D/SensorService( 1016): [SO] [100 -> 255]
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
D/SecKeyguardStatusUtils( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/BatteryMeterView( 1179): onDraw batteryColor : -1
,D/KeyguardEffectViewController( 1179): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1179): *** don't update sliding image ***
I/StatusBar( 1179): Icon Only
,D/PanelView( 1179): There is/are notification(s) 
I/DBG_DM  ( 3158): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3158): [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,W/NotificationService( 1016): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,I/DBG_DM  ( 3158): [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] 
,I/DBG_DM  ( 3158): [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
,D/MotionRecognitionService( 1016):   mReceiver.onReceive : ACTION_SCREEN_ON
,E/MotionRecognitionService( 1016):  handler : SCREEN_ON end
,D/ActivityManager( 1016): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/NotificationService( 1016): ACTION_SCREEN_ON
D/KnoxTimeoutHandler( 1016): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1016): postActiveUserChange, showWhenLocked: false
,D/LightsService( 1016): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1016) 
,D/LightsService( 1016): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 1016): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
,D/LightsService( 1016): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/KnoxTimeoutHandler( 1016): handleActiveUserChange for user 0
D/PersonaManagerService( 1016): getPersonasForUser(): returning null!
D/StatusBar( 1179): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
D/PersonaManager( 1179): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1179): Icon Only
I/StatusBar( 1179): Icon Only
,D/PanelView( 1179): There is/are notification(s) 
D/PanelView( 1179): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1179): Icon Only
I/StatusBar( 1179): Icon Only
D/PanelView( 1179): There is/are notification(s) 
D/PanelView( 1179): kidsfalse mQsExpansionEnabled:true
,I/Timeline( 3158): Timeline: Activity_idle id: android.os.BinderProxy@15e390d6 time:86126
D/PanelView( 1179): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,D/MISC PowerHAL( 1016): sysfs_write -: /sys/class/input/event3/device/enabled: 1
,E/WifiNative-wlan0( 1016): do suspend false
,D/audio_hw_primary(  284): adev_set_parameters: enter: screen_state=on
,V/voice   (  284): voice_set_parameters: enter: screen_state=on
V/voice   (  284): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  284): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  284): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  284): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  284): adev_set_parameters: exit
,D/IpRemoteDisplayController( 1016): intent received android.intent.action.SCREEN_ON
,D/IpRemoteDisplayController( 1016): Bridge Server is not available
,D/GpsLocationProvider( 1016): receive broadcast intent, action: android.intent.action.SCREEN_ON
,D/PersonaManagerService( 1016): ACTION_SCREEN_ON onReceive
,D/PersonaManagerServiceHandler( 1016): MSG_ACTION_SCREEN_ON called
,I/wpa_supplicant( 2142): reset timer : RESET_TIMER 1
I/wpa_supplicant( 2142): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 2142): P2P: Current p2p state = IDLE
,I/wpa_supplicant( 2142): Scan requested (ret=0) - scan timeout 30 seconds
,D/CoverManagerWhiteLists( 1016): isAllowedToUse : SIGNATURE_MATCH
,I/NfcService( 1439): When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
,D/NfcService( 1439): call the applyRouting
,D/accuweather( 1729): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_ON
,D/accuweather( 1729): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
D/accuweather( 1729): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
D/accuweather( 1729): [KK AccuPhone]>>> UIM:289 [0:0] direct update clock
,D/accuweather( 1729): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
,D/accuweather( 1729): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,D/accuweather( 1729): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1729): [KK AccuPhone]>>> UIM:1448 [0:0] mc sy = 2
,D/accuweather( 1729): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
D/accuweather( 1729): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
,E/accuweather( 1729): [KK AccuPhone]>>> UIM:1488 [0:0] bTM 18 56
,D/ActivityManager( 1016): startService callerProcessName:com.sec.android.widgetapp.ap.hero.accuweather, calleePkgName: com.sec.android.widgetapp.ap.hero.accuweather
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,I/SamsungIME( 1793): getNextShiftState() cursorCapsMode : 0
,D/PanelView( 1179): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/MISC PowerHAL( 1016): sysfs_write -: /sys/class/input/event1/device/enabled: 1
,D/MISC PowerHAL( 1016): sysfs_write +: /sys/class/power_supply/battery/lcd: 1
D/MISC PowerHAL( 1016): sysfs_write -: /sys/class/power_supply/battery/lcd: 1
D/PowerManagerService-JNI( 1016): Excessive delay in MISC setInteractive(true) while turning screen on: 171ms
I/QCOM PowerHAL( 1016): Got set_interactive hint
,D/PowerManagerService( 1016): Excessive delay in nativeSetInteractive(true): 172ms
D/lights  ( 1016): button : 1 +
D/PowerManagerService( 1016): Excessive delay in DisplayManagerInternal.requestDisplayStateInternal(mRequestingState): 282ms
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/PowerManagerService( 1016): [PWL] sb release: PowerManagerService.Broadcasts
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/lights  ( 1016): button : 1 -
,D/SSRM:n  ( 1016): SIOP:: AP = 350
,D/daemonapp( 1303): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1303): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1303): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1303): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1303): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1303): [MSC_Daemon]>>> WDSM:54 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,D/comsamsunglog( 1303): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1303): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 1303): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1303): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1303): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 1303): [MSC_Daemon]>>> WDSM:441 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/daemonapp( 1303): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1303): [MSC_Daemon]>>> WDSM:444 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 1303): [MSC_Daemon]>>> WDSM:445 [0:0] [ASO][NUT] = 1453852500000
D/daemonapp( 1303): [MSC_Daemon]>>> WDSM:446 [0:0] [ASO][CT] = 1453830961266
D/daemonapp( 1303): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1303): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,D/daemonapp( 1303): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1303): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1303): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,D/daemonapp( 1303): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename,
,E/daemonapp( 1303): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,D/SecKeyguardStatusUtils( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/StatusBar.NetworkController( 1179): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/SSRM:a  ( 1016): DeviceInfo:: 000000000000
,D/SSRM:a  ( 1016): SettingsAirViewInfo:: 000000000
,D/CAR.SERVICE( 6235): mConnectedToCar = false, abort
,E/ActivityThread( 6235): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@de3306f that was originally bound here
E/ActivityThread( 6235): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@de3306f that was originally bound here
E/ActivityThread( 6235): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 6235): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 6235): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 6235): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 6235): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 6235): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 6235): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 6235): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6235): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6235): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 6235): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 6235): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 6235): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 6235): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3280)
E/ActivityThread( 6235): 	at android.app.ActivityThread.access$1900(ActivityThread.java:181)
E/ActivityThread( 6235): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1565)
E/ActivityThread( 6235): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6235): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 6235): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/ActivityThread( 6235): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6235): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6235): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 6235): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/ActivityThread( 6235): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@28cc5226 that was originally bound here
E/ActivityThread( 6235): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@28cc5226 that was originally bound here
E/ActivityThread( 6235): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 6235): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 6235): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 6235): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 6235): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 6235): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6235): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6235): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 6235): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 6235): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 6235): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 6235): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 6235): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:3312)
E/ActivityThread( 6235): 	at android.app.ActivityThread.access$2000(ActivityThread.java:181)
E/ActivityThread( 6235): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1570)
E/ActivityThread( 6235): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6235): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 6235): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/ActivityThread( 6235): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6235): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6235): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 6235): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,W/ActivityManager( 1016): Unbind failed: could not find connection for android.os.BinderProxy@1576a071
,D/TaskPersister( 1016): removeObsoleteFile: deleting file=7_task.xml
,D/lights  ( 1016): button : 0 +
,D/lights  ( 1016): button : 0 -
,D/StatusBar.NetworkController( 1179): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/SMD     (  292): DCD OFF
,D/StatusBar.NetworkController( 1179): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,V/AlarmManager( 1016): waitForAlarm result :8
,D/SensorService( 1016): [SO] 0.019 0.077 10.036
,I/wpa_supplicant( 2142): nl80211: Received scan results (4 BSSes)
,D/WifiP2pService( 1016): InactiveState{ what=147461 }
,D/WifiP2pService( 1016): P2pEnabledState{ what=147461 }
D/WifiP2pService( 1016): DefaultState{ what=147461 }
,D/PackageManager( 1016): [MSG] MCS_UNBIND
,I/ActivityManager( 1016): Killing 5101:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
,W/libprocessgroup( 1016): failed to open /acct/uid_10044/pid_5101/cgroup.procs: No such file or directory
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/StatusBar.NetworkController( 1179): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/SMD     (  292): DCD OFF
,V/AlarmManager( 1016): waitForAlarm result :8
,D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: android, action: null
,D/ActivityManager( 1016): retrieveServiceLocked(): component = android/com.android.server.os.BackgroundCompactionService; callingUser = 0; userId(target) = 0
,I/BackgroundCompactionService( 1016): onStart. jobID=801
,I/BackgroundCompactionService( 1016): onStart done. jobID=801
,I/ActivityManager( 1016): Waited long enough for: ServiceRecord{3bca5cb5 u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,E/SMD     (  292): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1179): Icon Only
I/StatusBar( 1179): Icon Only
D/PanelView( 1179): There is/are notification(s) 
D/PanelView( 1179): kidsfalse mQsExpansionEnabled:true
,D/PanelView( 1179): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2635): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1016): SIOP:: AP = 320
,D/StatusBar.NetworkController( 1179): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/SMD     (  292): DCD OFF,
,V/AlarmManager( 1016): waitForAlarm result :4
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/Finsky  ( 5597): [975] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5597): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/StatusBar.NetworkController( 1179): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/SensorService( 1016): [SO] -0.019 0.057 10.036
,D/StatusBar.NetworkController( 1179): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/SMD     (  292): DCD OFF
,D/StatusBar.NetworkController( 1179): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1179): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/SMD     (  292): DCD OFF
,D/StatusBar.NetworkController( 1179): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/PowerManagerService( 1016): [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10054 pid=1179 (0x0)
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2635): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1016): SIOP:: AP = 310,
,E/SMD     (  292): DCD OFF,
,E/Watchdog( 1016): !@Sync 3
,D/StatusBar.NetworkController( 1179): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/Atfwd_Sendcmd(  323): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  323): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  292): DCD OFF
,D/PowerManagerService( 1016): [s] UserActivityState : 1 -> 2
D/DisplayPowerController( 1016): getFinalBrightness : Summary is 1 -> 1
D/DisplayPowerController( 1016): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 1016): [s] DisplayPowerCallbacks : onStateChanged()
,D/DisplayPowerController( 1016): getFinalBrightness : Summary is 1 -> 1
,D/lights  ( 1016): lcd : 1 +
,D/DisplayPowerController( 1016): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/lights  ( 1016): lcd : 1 -
,D/DisplayPowerController( 1016): getFinalBrightness : Summary is 1 -> 1
,D/DisplayPowerController( 1016): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/SensorService( 1016): [SO] -0.019 0.057 10.017
,D/StatusBar.NetworkController( 1179): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1179): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,V/AlarmManager( 1016): waitForAlarm result :4
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SMD     (  292): DCD OFF
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.store.VacuumService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1846): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1846): Vacuum at: now=1453830987756 tag=VacuumService
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.uploader.UploaderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PhenotypeConfigurator( 1846): Scheduling Phenotype for one-off execution 503 seconds from now (1453830988145)
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GetConfigurationSnapshotOperation( 1846): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PhenotypeFlagCommitter( 1846): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1846): Using platform SSLCertificateSocketFactory
,D/LocationManagerService( 1016): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 1846): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1846): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1846): (HTTPLog)-Static: isShipBuild true
I/System.out( 1846): (HTTPLog)-Thread-269-358332706: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1846): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  279): uids 10012
D/EnterpriseController(  279): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 502 for uid 10012
,I/System.out( 1846): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1846): Tagging socket 81 with tag 3000120100000000{805310977,0} for uid -1, pid: 1846, getuid(): 10012
,I/qtaguid ( 1846): Tagging socket 87 with tag 3000120100000000{805310977,0} for uid -1, pid: 1846, getuid(): 10012
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,D/LocationManagerService( 1016): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1846): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1846): Tagging socket 81 with tag 3000120100000000{805310977,0} for uid -1, pid: 1846, getuid(): 10012
,D/FactoryTest( 5429): Not factory mode
,D/FactoryTest( 5429): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 5429): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 5429): still no open session command from host, so toast
,W/ContextImpl( 5429): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 5429): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,I/Timeline( 5429): Timeline: Activity_launch_request id:com.android.settings time:113946
E/PersonaManagerService( 1016): inState():  stateMachine is null !!
I/PersonaManagerService( 1016): PersonaId don't exist
I/ActivityManager( 1016): do not start freezing screen for locked container getKeyguardshowstate = false
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.android.settings
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,D/CustomFrequencyManagerService( 1016): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1016  pkgName : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1016): mDVFSHelper.acquire()
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.android.settings
,D/InputDispatcher( 1016): Focused application set to: xxxx
D/InputDispatcher( 1016): Focus left window: 3158
,I/DBG_DM  ( 3158): [com.wssyncmldm.ui.XUIInstallConfirmActivity(366/onUserLeaveHint)] 
,E/MTPRx   ( 5429): started activity for popup
,D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
,I/DBG_DM  ( 3158): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 20
,D/LocationManagerService( 1016): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/DBG_DM  ( 3158): [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,I/System.out( 1846): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1846): Tagging socket 81 with tag 3000120100000000{805310977,0} for uid -1, pid: 1846, getuid(): 10012
,I/DBG_DM  ( 3158): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3158): [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/DBG_DM  ( 3158): [com.wssyncmldm.ui.XUIInstallConfirmActivity(371/onUserLeaveHint)] Home Key!!,
,I/DBG_DM  ( 3158): [com.wssyncmldm.ui.XUIFotaPostponeActivity(337/llIIIIlllllIIllIIllI)] 
,D/StatusBar.NetworkController( 1179): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/DBG_DM  ( 3158): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,I/DBG_DM  ( 3158): [com.wssyncmldm.db.file.XDB(5457/lllIIIIllIlIlllllllI)] Set Download Postpone status : 3
,D/LightsService( 1016): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1016) 
,I/DBG_DM  ( 3158): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 3 / Notification IndicatorState : 3,
,D/LightsService( 1016): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off,
D/PersonaManager( 1179): isKioskContainerExistOnDevice
D/LightsService( 1016): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/PersonaManager( 1179): isKioskContainerExistOnDevice
D/LightsService( 1016): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
I/PhoneStatusBar( 1179): Icon Only
D/LocationManagerService( 1016): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
I/StatusBar( 1179): Icon Only
,D/PanelView( 1179): There is/are notification(s) 
D/PanelView( 1179): kidsfalse mQsExpansionEnabled:true
,D/ApplicationPolicy( 1016): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
,D/WindowManager( 1016): showStatusBarByNotification() mOpenByNotification=false
I/DBG_DM  ( 3158): [com.wssyncmldm.db.file.XDB(3671/llIIIIlllllIIllllllI)] FUMO_Status : 220
W/NotificationService( 1016): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
I/PhoneStatusBar( 1179): Icon Only
I/StatusBar( 1179): Icon Only
D/PanelView( 1179): There is/are notification(s) 
D/PanelView( 1179): kidsfalse mQsExpansionEnabled:true
,I/DBG_DM  ( 3158): [com.wssyncmldm.ui.XUIFotaPostponeActivity(381/llIIIIlllllIIllIIllI)] xdbSetFUMOStatus  to XDL_STATE_POSTPONE_TO_UPDATE
,I/System.out( 1846): (HTTPLog)-Static: isSBSettingEnabled false
I/DBG_DM  ( 3158): [com.wssyncmldm.ui.XUIFotaPostponeActivity(474/llIIIIlllllIIllIIllI)] 
,I/qtaguid ( 1846): Tagging socket 81 with tag 3000120100000000{805310977,0} for uid -1, pid: 1846, getuid(): 10012
,I/DBG_DM  ( 3158): [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] 
,V/ActivityManager( 1016): Display changed displayId=0
,D/Launcher( 1478): onRestart, Launcher: 436171979
,D/KnoxNotification( 1179): ----- inflateViews : modified publicViewLocal -----
,D/Launcher( 1478): onStart, Launcher: 436171979
,D/Launcher.HomeView( 1478): onStart
,V/ActivityThread( 1478): updateVisibility : ActivityRecord{b677911 token=android.os.BinderProxy@4201adf {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,I/SurfaceFlinger(  259): id=16 createSurf (720x1280),1 flag=4, Mauncher
,D/KnoxNotification( 1179): ----- inflateViews : modified KnoxViewLocal -----
,V/WindowOrientationListener( 1016): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1016): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 1016): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,D/PersonaManager( 1179): PersonaID is invalid or persona doesn't exists. : 0
D/StatusBarManagerService( 1016): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
D/PersonaManager( 1179): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1179): Icon Only
,I/StatusBar( 1179): Icon Only
,D/PanelView( 1179): There is/are notification(s) 
D/PanelView( 1179): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1179): Icon Only
I/StatusBar( 1179): Icon Only
D/SRIB_DCS( 1478): log_dcs ThreadedRenderer::initialize entered! 
D/PanelView( 1179): There is/are notification(s) 
D/PanelView( 1179): kidsfalse mQsExpansionEnabled:true
,D/PanelView( 1179): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,W/ResourcesManager( 5429): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 5429): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5429): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5429): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5429): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5429): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/LocationManagerService( 1016): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,E/SettingsReceiverActivity( 5429): PREF_DONT_ASK_AGAIN : true
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1846): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1846): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/FocusedStackFrame( 1016): Set to : 0
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.android.settings
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
,D/InputDispatcher( 1016): Focused application set to: xxxx
,D/InputDispatcher( 1016): Focus entered window: 1478
,D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
E/ActivityManager( 1016): Invalid thumbnail dimensions: 650x650
,W/OpenGLRenderer( 1478): SFEffectCache::get: create texture(0x9fb25724): name, size, mSize = 40, 145188, 467928
,D/PanelView( 1179): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,D/InputMethodManagerService( 1016): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/StatusBar( 1179): Icon Only
,D/PanelView( 1179): There is/are notification(s) 
,D/SamsungIME( 1793): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SettingsReceiverActivity( 5429): dev.kiessupport is : TRUE
,D/PhoneWindow( 5429): *FMB* installDecor mIsFloating : true
D/PhoneWindow( 5429): *FMB* installDecor flags : 8388610
,D/Launcher( 1478): onResume, Launcher: 436171979
,D/SettingsProvider( 1016): name = kids_home_mode
D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 10007
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
,D/Launcher.HomeView( 1478): onResume
,D/PersonaManager( 1016): isKioskContainerExistOnDevice
,I/ActivityManager( 1016): Displayed Component not be shown by security: +18ms
,D/Launcher( 1478): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/MenuAppsGridFragment( 1478): onResume
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
D/WallpaperManager( 1478): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/WallpaperManager( 1478): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/WallpaperManager( 1478): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,I/splitIntent( 1016): Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=6, mSplitNum[2]=8, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=10
I/splitIntent( 1016): finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
,W/ActivityManager( 1016): userId = 0, bbcId = -10000,
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6325): MountEmulatedStorage()
,E/Zygote  ( 6325): v2
I/libpersona( 6325): KNOX_SDCARD checking this for 10044
I/libpersona( 6325): KNOX_SDCARD not a persona
,I/SELinux ( 6325): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/ActivityManager( 1016): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.MediaScannerReceiver: pid=6325 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/SELinux ( 6325): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 6325): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.widgetapp.digitalclock, hostingType: broadcast
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.digitalclock
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6340): MountEmulatedStorage(),
E/Zygote  ( 6340): v2
I/libpersona( 6340): KNOX_SDCARD checking this for 10088
I/libpersona( 6340): KNOX_SDCARD not a persona,
I/SELinux ( 6340): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1016): Start proc com.sec.android.widgetapp.digitalclock for broadcast com.sec.android.widgetapp.digitalclock/.DigitalClockWidgetProvider: pid=6340 uid=10088 gids={50088, 9997} abi=armeabi-v7a,
,I/SELinux ( 6340): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.widgetapp.activeapplicationwidget, hostingType: broadcast
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,E/SELinux ( 6340): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 6325): TimaSignature is unavailable
,D/ActivityThread( 6325): Added TimaKeyStore provider
,E/Zygote  ( 6352): MountEmulatedStorage()
,I/libpersona( 6352): KNOX_SDCARD checking this for 10142
E/Zygote  ( 6352): v2
I/libpersona( 6352): KNOX_SDCARD not a persona
I/SELinux ( 6352): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6352): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1016): Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=6352 uid=10142 gids={50142, 9997, 1028, 1015} abi=armeabi-v7a
D/ActivityManager( 1016): handle home activity for 0
D/PersonaManagerService( 1016): getPersonasForUser(): returning null!
I/WallpaperManagerService( 1016): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler( 1016): post home show event for user 0
D/ActivityManager( 1016): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1016): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1016): postActiveUserChange, showWhenLocked: false
D/WallpaperManagerService( 1016):  force update = false; persona id = 0; current user =0; current persona = 0
D/KnoxTimeoutHandler( 1016): handleHomeShow for 0 and current 0
D/KnoxTimeoutHandler( 1016): handleActiveUserChange for user 0
E/SELinux ( 6352): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/Timeline( 1478): Timeline: Activity_idle id: android.os.BinderProxy@4201adf time:114383
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/BroadcastQueue( 1016): Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1478, uid=10007) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,D/TimaKeyStoreProvider( 6340): TimaSignature is unavailable
,D/TimaKeyStoreProvider( 6352): TimaSignature is unavailable
,D/ActivityThread( 6352): Added TimaKeyStore provider
D/ActivityThread( 6340): Added TimaKeyStore provider
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
,W/ResourcesManager( 6325): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6325): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6325): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6325): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6325): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 6325): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6325): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6325): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/Recents_RecreateReceiver( 2475): onReceive by home
,I/System.out( 1846): (HTTPLog)-Static: isSBSettingEnabled false
,W/ResourcesManager( 6340): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/EnterpriseController(  279): uids 10012
D/EnterpriseController(  279): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 502 for uid 10012
,I/System.out( 1846): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1846): Tagging socket 80 with tag 3000040100000000{805307393,0} for uid 10012, pid: 1846, getuid(): 10012
,V/TaskCloserActivity( 6352): TaskCloserActivity enter()
,V/TaskCloserActivity( 6352): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
,I/ActivityManager( 1016): Killing 4835:com.samsung.android.sm/1000 (adj 15): empty #31
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
,I/qtaguid ( 1846): Tagging socket 90 with tag 3000040100000000{805307393,0} for uid 10012, pid: 1846, getuid(): 10012
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.camera, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6372): MountEmulatedStorage()
,E/Zygote  ( 6372): v2
I/libpersona( 6372): KNOX_SDCARD checking this for 10139,
I/libpersona( 6372): KNOX_SDCARD not a persona
I/SELinux ( 6372): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/ActivityManager( 1016): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=6372 uid=10139 gids={50139, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,I/ActivityManager( 1016): Killing 5765:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31,
,I/SELinux ( 6372): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6372): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6372): TimaSignature is unavailable
,D/ActivityThread( 6372): Added TimaKeyStore provider
,W/ResourcesManager( 6372): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 6372): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6372): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 6372): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 6372): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/ActivityManager( 1016): Killing 5488:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_4835/cgroup.procs: No such file or directory
,D/NearbySource( 6325): Nearby Source Create!
,D/NearbyContext( 6325): Nearby Context Create!
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6325): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,D/SLinkSource( 6325): Samsung link source created
,D/ContactProvider( 6325): getAllContactInfoList Start
,W/libprocessgroup( 1016): failed to open /acct/uid_10152/pid_5765/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_10015/pid_5488/cgroup.procs: No such file or directory
,D/WifiDisplayAdapter( 1016): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 1016): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/GalleryCacheReady( 6325): Receive : home resume
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
,D/CustomFrequencyManagerService( 1016): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1016  tag : ACTIVITY_RESUME_BOOSTER@7,
I/Timeline( 1016): Timeline: Activity_windows_visible id: ActivityRecord{1f1fe9fc u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t6} time:114692
W/ActivityManager( 1016): mDVFSHelper.release()
I/ServiceManager(  323): Waiting for service AtCmdFwd...
,D/Mms/UIEventReceiver( 5774): ui event
,I/SurfaceFlinger(  259): id=15 Removed YUIInstallC (7/8)
,I/splitIntent( 1016): Queue : background intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart  false.
,I/SurfaceFlinger(  259): id=15 Removed YUIInstallC (-2/8)
,I/ActivityManager( 1016): Killing 5206:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,I/ActivityManager( 1016): Killing 5813:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
,I/DBG_DM  ( 3158): [com.wssyncmldm.ui.XUIInstallConfirmActivity(508/onDestroy)] 
,D/CustomFrequencyManagerService( 1016): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1016  pkgName : ACTIVITY_RESUME_BOOSTER@11
,D/WindowOrientationListener( 1016):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,D/SensorService( 1016): [SO] activate (ident=0xb81a4738, enabled=0)
I/Sensors ( 1016): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
D/ContactProvider( 6325): getAllContactInfoList End
,I/syncContacts( 6325): thread: 1083, sync time = 66
,D/SensorManager( 1016): unregisterListener ::   
,I/Sensors ( 1016): AccelerometerSensor(0) setDelay : 200000000(ns)
,D/SensorService( 1016): [SO] changed settle time [0]
D/SensorService( 1016): [SO] setDelay [200000000]
D/SensorService( 1016): [SO] activate (ident=0xb8229348, enabled=1)
D/SensorService( 1016): [SO] AR_init
I/Sensors ( 1016): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,D/SensorManager( 1016): registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
,I/System.out( 1846): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1846): Tagging socket 81 with tag 3000120100000000{805310977,0} for uid -1, pid: 1846, getuid(): 10012
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_5813/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_5206/cgroup.procs: No such file or directory
,D/LocationManagerService( 1016): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1846): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1846): Tagging socket 81 with tag 3000120100000000{805310977,0} for uid -1, pid: 1846, getuid(): 10012
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/SensorService( 1016): [SO] Reset Rotation Old [100], Init [1]
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/CustomFrequencyManagerService( 1016): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1016  tag : ACTIVITY_RESUME_BOOSTER@11
,D/SensorService( 1016): [SO] currT = 115140048757, prevT = 114660072975, diff = 479975782, [-0.019 0.077 10.075]
,D/SensorService( 1016): [SO] -0.019 0.077 10.075
D/SensorService( 1016): [SO] [100 -> 255]
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/PowerManagerService( 1016): [s] UserActivityState : 2 -> 4
,I/PowerManagerService( 1016): Nap time (uid 1000)...
D/PowerManagerService( 1016): handleSandman : startDreaming: false  (canDreamLocked: false  canDozeLocked: false)
I/PowerManagerService( 1016): !@[ps] Screen__Off - 1 :  dream(timeout) (2)
I/PowerManagerService( 1016): Going to sleep due to screen timeout (uid 1000)...,
D/PowerManagerService( 1016): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService( 1016): SecHardwareInterface.setBatteryADC : false
D/PowerManagerService( 1016): handleSandman : startDreaming: true  (canDreamLocked: false  canDozeLocked: true)
,V/WindowOrientationListener( 1016): WindowOrientationListener disabled
D/PowerManagerService( 1016): handleSandman : startDream(true)
E/PowerManagerService( 1016): handleSandman : startDreaming, but isDreaming false
D/SensorService( 1016): [SO] activate (ident=0xb8229348, enabled=0)
I/PowerManagerService( 1016): Sleeping (uid 1000)...
I/SurfaceFlinger(  259): id=17 createSurf (720x1280),-1 flag=20004, DolorFade
D/PowerManagerService( 1016): [s] UserActivityState : 4 -> 0
I/Sensors ( 1016): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,D/SensorManager( 1016): unregisterListener ::   
,D/KeyguardViewMediator( 1179): onScreenTurnedOff(3)
I/KeyguardEffectViewController( 1179): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 1179): changeWallpaperByScreenOff()
D/KeyguardViewMediator( 1179): notifyScreenOffLocked
,D/Launcher.HomeView( 1478): onPause
,D/Launcher( 1478): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,D/KeyguardViewMediator( 1179): timeout : 5000
,V/TaskCloserActivity( 6352): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,D/KeyguardViewMediator( 1179): setting alarm to turn off keyguard, seq = 2
D/KeyguardViewMediator( 1179): handleNotifyScreenOff
D/VolumePanel( 1179): onScreenTurnedOff()
D/VolumePanel( 1179): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,D/VolumePanel( 1179): mCoverBroadcastReceiver: Screen OFF end,
D/SecKeyguardClockSingleView( 1179): onScreenTurnedOff
D/PowerManagerService( 1016): Excessive delay in ColorFade : captureScreenshotTextureAndSetViewport: 30ms
,V/ActivityThread( 1478): updateVisibility : ActivityRecord{b677911 token=android.os.BinderProxy@4201adf {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,D/Launcher.HomeView( 1478): onStop
,E/lights  ( 1016): write_int failed to open -1
D/LightsService( 1016): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 1016) 
D/LightsService( 1016): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
D/BatteryService( 1016): turn on LED for fully charged
D/LightsService( 1016): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1016): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SmartFaceService( 1016): onReceive: android.intent.action.SCREEN_OFF
,W/System.err( 1016): java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
W/System.err( 1016): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 1016): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
,W/System.err( 1016): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
W/System.err( 1016): 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
E/SmartFaceService( 1016): fail to set sysfs 0
W/System.err( 1016): 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
D/PowerManagerService( 1016): Excessive delay in ColorFade : initGLShaders: 14ms,
W/System.err( 1016): 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:474)
D/DisplayPowerController( 1016): ColorFade: onAnimationStart
W/System.err( 1016): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
D/DisplayPowerController( 1016): getFinalBrightness : Summary is 5 -> 5
,W/System.err( 1016): 	at android.os.Handler.handleCallback(Handler.java:739)
D/DisplayPowerController( 1016): performScreenOffTransition : no brightness animation
W/System.err( 1016): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 1016): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 1016): 	at android.os.HandlerThread.run(HandlerThread.java:61),
W/System.err( 1016): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 1016): 	at libcore.io.Posix.open(Native Method)
W/System.err( 1016): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 1016): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 1016): 	,... 10 more
,I/StatusBar( 1179): Icon Only
,D/PanelView( 1179): There is/are notification(s) 
,D/MotionRecognitionService( 1016):   mReceiver.onReceive : ACTION_SCREEN_OFF
,D/SamsungIME( 1793): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,E/MotionRecognitionService( 1016):  handler : SCREEN_OFF end 
,E/WifiNative-wlan0( 1016): do suspend true
,D/NotificationService( 1016): ACTION_SCREEN_OFF
,D/LightsService( 1016): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1016) 
,D/LightsService( 1016): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
,D/LightsService( 1016): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
,D/LightsService( 1016): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/audio_hw_primary(  284): adev_set_parameters: enter: screen_state=off
,V/voice   (  284): voice_set_parameters: enter: screen_state=off
V/voice   (  284): voice_set_parameters: exit with code(-2)
,V/msm8974_platform(  284): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  284): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  284): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  284): adev_set_parameters: exit
,I/BackgroundCompactionService( 1016): Schedule Type1 BGCompaction
,I/BackgroundCompactionService( 1016): onIdleStop
,D/IpRemoteDisplayController( 1016): intent received android.intent.action.SCREEN_OFF
,D/IpRemoteDisplayController( 1016): Bridge Server is not available
,D/PanelView( 1179): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,D/GpsLocationProvider( 1016): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.SCREEN_OFF
,V/EmergencyMode( 1415): [EmergencyStateReceiver] binteractive [false] why[3]
,D/PersonaManagerService( 1016): ACTION_SCREEN_OFF onReceive
D/PersonaManagerServiceHandler( 1016): MSG_ACTION_SCREEN_OFF called
,D/NfcService( 1439): call the applyRouting
,D/accuweather( 1729): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_OFF
,D/accuweather( 1729): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/accuweather( 1729): [KK AccuPhone]>>> WCW:32 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
D/daemonapp( 1303): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
,D/accuweather( 1729): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 1729): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,D/accuweather( 1729): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1729): [KK AccuPhone]>>> UIM:312 [0:0]  action:widgetactionWEATHER_SCREEN_OFF
,D/daemonapp( 1303): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,E/LibSecureUISvc( 1943): svc_sock_send_message(suisvc): Error sending data, -1 vs 4: Connection refused
,D/daemonapp( 1303): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/PowerManagerService( 1016): [PWL] sb release: PowerManagerService.Broadcasts
D/SSRM:n  ( 1016): SIOP:: AP = 300
,D/accuweather( 1729): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
,D/accuweather( 1729): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,D/accuweather( 1729): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1729): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/accuweather( 1729): [KK AccuPhone]>>> WCS:113 [0:0] onDestroy : End
,D/accuweather( 1729): [KK AccuPhone]>>> WC:30 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/accuweather( 1729): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/DisplayPowerState( 1016): !@ ColorFade entry
,D/DisplayPowerController( 1016): ColorFade: onAnimationEnd
,D/DisplayPowerController( 1016): getFinalBrightness : Summary is 0 -> 0
,D/lights  ( 1016): lcd : 0 +
,D/DisplayPowerController( 1016): performScreenOffTransition : no brightness animation
,I/BatteryStatsDumper( 1016): In refreshStats isReason Screen ON/OFF: true
,D/lights  ( 1016): lcd : 0 -
D/DisplayPowerController( 1016): getFinalBrightness : Summary is 0 -> 0
D/DisplayPowerController( 1016): performScreenOffTransition : no brightness animation
,D/MISC PowerHAL( 1016): sysfs_write +: /sys/class/input/event3/device/enabled: 0
D/MISC PowerHAL( 1016): sysfs_write +: /sys/class/input/event1/device/enabled: 0
D/MISC PowerHAL( 1016): sysfs_write -: /sys/class/input/event1/device/enabled: 0
,D/NetworkStatsFactory( 1016): UpdateStatsForKnox updated
D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
D/MISC PowerHAL( 1016): sysfs_write -: /sys/class/input/event3/device/enabled: 0
,D/MISC PowerHAL( 1016): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL( 1016): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
I/QCOM PowerHAL( 1016): Got set_interactive hint
,D/DisplayManagerService( 1016): !@display_state: ON -> OFF
D/SurfaceFlinger(  259): Set power mode=0, type=0 flinger=0xb8bb1690
D/qdhwcomposer(  259): hwc_setPowerMode: Setting mode 0 on display: 0
I/DisplayManagerService( 1016): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager( 1016): Display changed displayId=0
,E/qdutils (  259): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  259): int qdutils::getHDMINode(): Failed to find HDMI node
,D/NetworkStatsFactory( 1016): UpdateStatsForKnox updated
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
D/PowerManagerService( 1016): [s] DisplayPowerCallbacks : onStateChanged()
,D/PowerManagerService( 1016): [PWL] sb release: PowerManagerService.Display
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,D/StatusBar.NetworkController( 1179): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1179): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1179): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1179): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2635): Disconnected process message: 10
,I/BatteryStatsDumper( 1016): Screen bin #0: time=30305 power=0.17677916666666665
I/BatteryStatsDumper( 1016): Screen bin #1: time=0 power=0.0
I/BatteryStatsDumper( 1016): Screen bin #2: time=0 power=0.0
I/BatteryStatsDumper( 1016): Screen bin #3: time=0 power=0.0
I/BatteryStatsDumper( 1016): Screen bin #4: time=0 power=0.0
I/BatteryStatsDumper( 1016): Previous Battery Level: 100 Current Level: 100 Delta: 0
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/rmt_storage(  272): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb808b7c8
I/rmt_storage(  272): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  272): wakelock acquired: 1, error no: 42
I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1207388872)
,I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 917504
I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1207388872) wakelock released: 1, error no: 0
I/rmt_storage(  272): 
,I/rmt_storage(  272): rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb808b7c8
,I/BatteryStatsDumper( 1016): Writing to database completed
,I/qdhwcomposer(  259): handle_blank_event: dpy:0 panel power state: 0
,E/qdutils (  259): int qdutils::getHDMINode(): Failed to open fb node 2
,D/qdhwcomposer(  259): hwc_setPowerMode: Done setting mode 0 on display 0
,E/qdutils (  259): int qdutils::getHDMINode(): Failed to find HDMI node
D/SurfaceControl( 1016): Excessive delay in setPowerMode(): 265ms
D/PowerManagerService( 1016): Excessive delay in !@display_state: OFF: 266ms
I/libsuspend( 1016): !@autosuspend_wakeup_count_enable
I/libsuspend( 1016): !@autosuspend_wakeup_count_enable done
D/PowerManagerService( 1016): Excessive delay in DisplayManagerInternal.requestDisplayStateInternal(mRequestingState): 272ms
,I/PowerManagerService( 1016): [PWL] Off : 0s ago
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,D/TaskPersister( 1016): removeObsoleteFile: deleting file=7_task_thumbnail.png
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  292): DCD OFF
,V/AlarmManager( 1016): waitForAlarm result :4
,D/KeyguardViewMediator( 1179): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/KeyguardViewMediator( 1179): doKeyguard: not showing because lockscreen is off
,V/KeyguardEffectViewController( 1179): *** Keyguard wallpaper service already unbounded
,I/PowerManagerService( 1016): [PWL] Off : 5s ago,
,E/SMD     (  292): DCD OFF,
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,V/AlarmManager( 1016): waitForAlarm result :8
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged,
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2635): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 2
,V/AlarmManager( 1016): waitForAlarm result :8
,E/SMD     (  292): DCD OFF
,I/PowerManagerService( 1016): [PWL] Off : 15s ago,
,E/SMD     (  292): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1016): SIOP:: AP = 270,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2635): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  292): DCD OFF
,E/Watchdog( 1016): !@Sync 4
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF,
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 3
,V/AlarmManager( 1016): waitForAlarm result :8
,E/SMD     (  292): DCD OFF
,V/AlarmManager( 1016): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1179): handleTimeUpdate
,D/SecKeyguardClockView( 1179): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1179): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1179): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1179): *** don't update sliding image ***
D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: android, action: null
D/ActivityManager( 1016): retrieveServiceLocked(): component = android/com.android.server.os.BackgroundCompactionService; callingUser = 0; userId(target) = 0
,I/BackgroundCompactionService( 1016): onStart. jobID=801
,I/BackgroundCompactionService( 1016): onStart done. jobID=801
,I/BackgroundCompactionService( 1016): Execute BGCompaction (type1). (0 times)
I/BackgroundCompactionService( 1016): compact_memory command done
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 1016): [PWL] Off : 30s ago
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2635): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  292): DCD OFF,
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF,
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,I/PowerManagerService( 1016): [PWL] Off : 50s ago,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/Watchdog( 1016): !@Sync 5
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF,
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,I/ServiceManager(  323): Waiting for service AtCmdFwd...,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 2635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2635): Disconnected process message: 10
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  292): DCD OFF
,I/PowerManagerService( 1016): [PWL] Off : 75s ago,
,E/SMD     (  292): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1016): !@Sync 6
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,V/AlarmManager( 1016): waitForAlarm result :8
,E/SMD     (  292): DCD OFF
,I/ClearcutLoggerApiImpl( 1846): disconnect managed GoogleApiClient
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF,
,I/Atfwd_Sendcmd(  323): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  323): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  292): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,I/PowerManagerService( 1016): [PWL] Off : 105s ago
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,I/ServiceManager(  323): Waiting for service AtCmdFwd...,
,E/SMD     (  292): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/Watchdog( 1016): !@Sync 7
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  323): Waiting for service AtCmdFwd...,
,I/ServiceManager(  323): Waiting for service AtCmdFwd...,
,I/ServiceManager(  323): Waiting for service AtCmdFwd...,
,E/SMD     (  292): DCD OFF,
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 1016): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.TIME_TICK,
D/KeyguardUpdateMonitor( 1179): handleTimeUpdate
,D/SecKeyguardClockView( 1179): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1179): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1179): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1179): *** don't update sliding image ***
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,I/ServiceManager(  323): Waiting for service AtCmdFwd...,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 1016): stay LED for fully charged
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2635): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  323): Waiting for service AtCmdFwd...,
,I/ServiceManager(  323): Waiting for service AtCmdFwd...,
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  323): Waiting for service AtCmdFwd...,
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  292): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 1016): [PWL] Off : 140s ago
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  292): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1016): !@Sync 8
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,V/AlarmManager( 1016): waitForAlarm result :8
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF,
,I/ServiceManager(  323): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 4,
,E/SMD     (  292): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1016): !@Sync 9
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  292): DCD OFF
,I/PowerManagerService( 1016): [PWL] Off : 180s ago
,I/ServiceManager(  323): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/TimaService( 1016): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1016): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1016): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize( 1016): initializing...,
I/TLC_TIMA_PKM_initialize( 1016): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize( 1016): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication( 1016): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1016): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1016): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication( 1016): aligned max_recvmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1016): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: ( 1016): QSEECom_get_handle sb_length = 0x80080
D/QSEECOMAPI: ( 1016): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1016): Loaded image: APP id = 11
,I/TZ: qc_tlc_communication( 1016): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize( 1016): Trustlet response is completed
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,I/TLC_TIMA_PKM_measure_kernel( 1016): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1016): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1016): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1016): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1016): !@Sync 10
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,I/Atfwd_Sendcmd(  323): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  323): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,I/PowerManagerService( 1016): [PWL] Off : 225s ago
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/Watchdog( 1016): !@Sync 11,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 2
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,I/ServiceManager(  323): Waiting for service AtCmdFwd...,
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged,
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2635): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/Watchdog( 1016): !@Sync 12
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,I/ServiceManager(  323): Waiting for service AtCmdFwd...,
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  292): DCD OFF
,I/PowerManagerService( 1016): [PWL] Off : 275s ago,
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/Watchdog( 1016): !@Sync 13
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF,
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...,
,I/ServiceManager(  323): Waiting for service AtCmdFwd...,
,E/SMD     (  292): DCD OFF
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 5,
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/Watchdog( 1016): !@Sync 14,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,I/Atfwd_Sendcmd(  323): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  323): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,V/AlarmManager( 1016): waitForAlarm result :8
,V/AlarmManager( 1016): No more alarm at this time.nowELAPSED=445017 batch.start=707019
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1179): handleTimeUpdate,
,D/SecKeyguardClockView( 1179): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1179): HomeTimezone(): 1,
,D/SecKeyguardStatusUtils( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1179): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1179): *** don't update sliding image ***
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  292): DCD OFF,
,I/PowerManagerService( 1016): [PWL] Off : 330s ago,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF,
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF,
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/Watchdog( 1016): !@Sync 15,
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 2
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF,
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...,
,I/bootchecker(  320): bootchecker wake up!!,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF,
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 3
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/Watchdog( 1016): !@Sync 16
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,V/AlarmManager( 1016): waitForAlarm result :8
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF,
,I/PowerManagerService( 1016): [PWL] Off : 390s ago
,I/ServiceManager(  323): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,I/ServiceManager(  323): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 4,
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/Watchdog( 1016): !@Sync 17
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,I/ServiceManager(  323): Waiting for service AtCmdFwd...,
,I/ServiceManager(  323): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF,
,W/Atfwd_Sendcmd(  323): AtCmdFwd service not published, waiting... retryCnt : 5
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1016): Plugged
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
I/MotionRecognitionService( 1016): mGripSensorEnabled= false,
V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2635): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/Watchdog( 1016): !@Sync 18
,I/Atfwd_Sendcmd(  323): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  323): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 1016): [PWL] Off : 455s ago,
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,I/Atfwd_Daemon(  323): Stop the daemon....,
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/Watchdog( 1016): !@Sync 19
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/TimaService( 1016): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1016): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1016): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 1016): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1016): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1016): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1016): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/Watchdog( 1016): !@Sync 20
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  292): DCD OFF
,I/PowerManagerService( 1016): [PWL] Off : 525s ago
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/Watchdog( 1016): !@Sync 21
,E/SMD     (  292): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/Watchdog( 1016): !@Sync 22
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,V/AlarmManager( 1016): waitForAlarm result :4,
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1179): handleTimeUpdate
,D/SecKeyguardClockView( 1179): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1179): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1179): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1179): *** don't update sliding image ***
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/Watchdog( 1016): !@Sync 23
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF
,I/PowerManagerService( 1016): [PWL] Off : 600s ago
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF,
,E/Watchdog( 1016): !@Sync 24,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,V/AlarmManager( 1016): waitForAlarm result :8,
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF
,E/Watchdog( 1016): !@Sync 25,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,I/PowerManagerService( 1016): [PWL] Off : 680s ago
,E/SMD     (  292): DCD OFF
,E/Watchdog( 1016): !@Sync 26
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,V/AlarmManager( 1016): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1179): handleTimeUpdate
,D/SecKeyguardClockView( 1179): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1179): HomeTimezone(): 1
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.EventLogService; callingUser = 0; userId(target) = 0
,D/SecKeyguardStatusUtils( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/KeyguardEffectViewController( 1179): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1179): *** don't update sliding image ***
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/EventLogService( 2009): Aggregate from 1453829417672 (log), 1453829417672 (data)
,D/SecKeyguardStatusUtils( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6685): MountEmulatedStorage()
,I/libpersona( 6685): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6685): v2
I/libpersona( 6685): KNOX_SDCARD not a persona
I/ActivityManager( 1016): Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.common.SmartManagerReceiver: pid=6685 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 6685): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 6685): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6685): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6685): TimaSignature is unavailable
,D/ActivityThread( 6685): Added TimaKeyStore provider
,W/ResourcesManager( 6685): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/ActivityManager( 1016): Killing 5800:com.sec.pcw.device/1000 (adj 15): empty #31
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_5800/cgroup.procs: No such file or directory,
,E/SMD     (  292): DCD OFF
,V/AlarmManager( 1016): waitForAlarm result :8
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  292): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2635): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,E/Watchdog( 1016): !@Sync 27
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2635): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1016): Plugged
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
I/MotionRecognitionService( 1016): mGripSensorEnabled= false,
V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2635): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/Watchdog( 1016): !@Sync 28
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,I/PowerManagerService( 1016): [PWL] Off : 765s ago,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/Watchdog( 1016): !@Sync 29
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,D/TimaService( 1016): TIMA: TimaService scheduler is intialized. 
D/TimaService( 1016): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1016): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 1016): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1016): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1016): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1016): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;,
,E/SMD     (  292): DCD OFF,
,E/Watchdog( 1016): !@Sync 30
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,V/AlarmManager( 1016): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.TIME_TICK,
D/KeyguardUpdateMonitor( 1179): handleTimeUpdate
,D/SecKeyguardClockView( 1179): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1179): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1179): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1179): *** don't update sliding image ***
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/Watchdog( 1016): !@Sync 31,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,I/PowerManagerService( 1016): [PWL] Off : 855s ago,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/Watchdog( 1016): !@Sync 32
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,V/AlarmManager( 1016): waitForAlarm result :8
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/Watchdog( 1016): !@Sync 33
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/Watchdog( 1016): !@Sync 34
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  292): DCD OFF
,I/PowerManagerService( 1016): [PWL] Off : 950s ago
,E/SMD     (  292): DCD OFF,
,E/Watchdog( 1016): !@Sync 35
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,E/Watchdog( 1016): !@Sync 36
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2635): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2635): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,E/Watchdog( 1016): !@Sync 37,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,E/Watchdog( 1016): !@Sync 38
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2635): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  292): DCD OFF,
,I/PowerManagerService( 1016): [PWL] Off : 1050s ago
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/Watchdog( 1016): !@Sync 39
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/TimaService( 1016): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1016): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1016): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService( 1016): User[0] Flushing usage stats to disk
,I/ApplicationUsage( 1016): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage( 1016): Updating Usage Statistics in DB @ 1453832090685
,I/ApplicationPolicy( 1016): updateDataUsageMap
,I/TLC_TIMA_PKM_measure_kernel( 1016): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1016): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1016): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1016): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/NetworkDataUsageDb( 1016): ::getAppControlDB: DB is Created 
,I/NetworkDataUsageDb( 1016): ::isTableExists: Table exists 
,I/ApplicationUsage( 1016): Done Updating Usage Statistics in DB @ 1453832091147
,E/SMD     (  292): DCD OFF,
,E/Watchdog( 1016): !@Sync 40
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/Watchdog( 1016): !@Sync 41
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,I/PowerManagerService( 1016): [PWL] Off : 1155s ago,
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/Watchdog( 1016): !@Sync 42,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,I/art     ( 1016): Background partial concurrent mark sweep GC freed 62533(6MB) AllocSpace objects, 329(5MB) LOS objects, 33% free, 29MB/44MB, paused 2.622ms total 174.968ms
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 6897): 
D/AndroidRuntime( 6897): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6897): CheckJNI is OFF
D/AndroidRuntime( 6897): readGMSProperty: start
D/AndroidRuntime( 6897): readGMSProperty: already setted!!
D/AndroidRuntime( 6897): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6897): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6897): readGMSProperty: end
D/AndroidRuntime( 6897): addProductProperty: start
E/AffinityControl( 6897): AffinityControl: registerfunction enter
D/AndroidRuntime( 6897): Calling main entry com.android.commands.pm.Pm
D/PersonaManagerService( 1016): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1016): START PACKAGE DELETE: observer{117155916}
D/PackageManager( 1016): pkg{<packageName>}
D/PackageManager( 1016): user{0}
D/PackageManager( 1016): caller{2000}
D/PackageManager( 1016): flags{3}
D/PersonaManagerService( 1016): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 1016): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1016): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1016): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1016): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService( 1016): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 1016): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1016): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1016): getApplicationUninstallationEnabled :  enabled true
D/PackageManager( 1016): !@killApplicatoin: 10155, uninstall pkg
I/ActivityManager( 1016): Force stopping com.test.thalitest appid=10155 user=-1: uninstall pkg
I/ActivityManager( 1016): Killing 6108:com.test.thalitest/u0a155 (adj 15): stop com.test.thalitest cause uninstall pkg
W/ActivityManager( 1016): Spurious death for ProcessRecord{1d360095 6108:com.test.thalitest/u0a155}, curProc for 6108: null
I/ActivityManager( 1016): Force stopping com.test.thalitest appid=10155 user=0: pkg removed
W/ActivityManager( 1016): CustomStartingWindow se packge removed so remove capture also
I/art     ( 5683): Explicit concurrent mark sweep GC freed 2026(116KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 909us total 40.972ms
I/InputReader( 1016): Reconfiguring input devices.  changes=0x00000010
I/art     ( 5466): Explicit concurrent mark sweep GC freed 11662(771KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 8MB/11MB, paused 1.032ms total 67.306ms
E/SamsungIME( 1793): mOCRHelper is null
I/art     ( 2009): Explicit concurrent mark sweep GC freed 5121(337KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 14MB/18MB, paused 1.654ms total 105.916ms
W/GeofencerStateMachine( 1846): Ignoring removeGeofence because network location is disabled.
W/SQLiteConnectionPool( 2009): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
I/KLMS-2.5.183: ( 3639): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Jan 26 19:16:06 GMT+01:00 2016
D/ActivityManager( 1016): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
D/RegisteredComponentCache( 1439): Collect Tech packages for Knox
D/PersonaManager( 1439): isKioskContainerExistOnDevice
I/KLMS-2.5.183: ( 3639): KLMSAbstractReciever(): onReceive().END.
I/splitIntent( 1016): Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=21, mSplitNum[2]=34, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=44
I/splitIntent( 1016): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/KLMS-2.5.183: ( 3639): KLMSIntentService(): onCreate()
E/Zygote  ( 6910): MountEmulatedStorage()
E/Zygote  ( 6910): v2
I/libpersona( 6910): KNOX_SDCARD checking this for 10094
I/libpersona( 6910): KNOX_SDCARD not a persona
I/SELinux ( 6910): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6910 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
I/SELinux ( 6910): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/KLMS-2.5.183: ( 3639): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
E/SELinux ( 6910): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/SecContentProvider2( 1016): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1016): mCursor = null
I/art     (  311): Explicit concurrent mark sweep GC freed 8718(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 628us total 21.923ms
I/PackagesMonitor( 6325): PackagesMonitor onReceive :com.test.thalitest
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 629us total 17.176ms
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/RCPManagerService( 1016): PackageReceiver onReceive()
I/HarmonyEASService( 1016): onReceive : android.intent.action.PACKAGE_REMOVED for 0
I/KLMS-2.5.183: ( 3639): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 619us total 17.680ms
D/KnoxMUMContainerPolicy( 1016): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
I/OTPFW   ( 1016): PackageRemovalReceiver::onReceive Enter
D/OTPFW   ( 1016): OtpDbHelper::getInstance New instance created
D/OTPFW   ( 1016): DBIntegrity::getInstance - New instance created
D/TimaKeyStoreProvider( 6910): TimaSignature is unavailable
D/ActivityThread( 6910): Added TimaKeyStore provider
D/OTPFW   ( 1016): PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10155 container id = 0
I/OTPFW   ( 1016): ProvisionData::getAllEntries Enter
E/OTPFW   ( 1016): ProvisionData::getAllEntries Table is empty
E/Zygote  ( 6929): MountEmulatedStorage()
E/Zygote  ( 6929): v2
I/libpersona( 6929): KNOX_SDCARD checking this for 10149
I/libpersona( 6929): KNOX_SDCARD not a persona
I/SELinux ( 6929): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/KLMS-2.5.183: ( 3639): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
I/ActivityManager( 1016): Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=6929 uid=10149 gids={50149, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 6929): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/KLMS-2.5.183: ( 3639): KLMSIntentService(): PACKAGE_REMOVED
E/SELinux ( 6929): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/KLMS-2.5.183: ( 3639): KLMSIntentService(): listeningToPackageRemoved().START
D/PersonaManager( 1439): isKioskContainerExistOnDevice
D/BackupManagerService( 1016): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
D/JobSchedulerService( 1016): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1016): uID is 10155
V/EnterpriseBillingPolicy( 1016): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1016): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1016): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1016): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1016): getBillingProfileForVpnEngine - end - null
I/KLMS-2.5.183: ( 3639): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
D/RegisteredServicesCache( 1439): empty dynamic service
D/TimaKeyStoreProvider( 6929): TimaSignature is unavailable
D/ActivityThread( 6929): Added TimaKeyStore provider
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/Mms/FreeMessageStatusReceiver( 5774): onReceive, action : android.intent.action.PACKAGE_REMOVED
V/AlarmManagerEXT( 1016): com.test.thalitest(10155) is removed.
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1016): uID is 10155
V/EnterpriseBillingPolicy( 1016): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1016): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1016): getProfileForApplication - exit null : containerId = 0
D/SSRM:aZ ( 1016): MSG_TYPE_APP_REMOVED::
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1016): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1016): getBillingProfileForVpnEngine - end - null
D/ActivityManager( 1016): startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
D/TaskPersister( 1016): removeObsoleteFile: deleting file=8_task.xml
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
D/Mms/FreeMessageReceiverService( 5774): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
D/Mms/FreeMessageReceiverService( 5774): onHandleIntent: ACTION_PACKAGE_REMOVED
I/TactileAssist( 1016): enable value -1
I/TactileAssist( 1016): internal enable value -1
I/TactileAssist( 1016): intensity value -1
I/TactileAssist( 1016): saveAppList value true
I/TactileAssist( 1016): List of disabled apps :
I/art     ( 6685): Explicit concurrent mark sweep GC freed 368(32KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 6MB/9MB, paused 979us total 34.489ms
D/elm:15183( 6910): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:15183( 6910): ELMEngine.ELMEngine( context ).
D/elm:15183( 6910): MDMBridge.setEnterpriseBridge()
D/ActivityManager( 1016): startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
D/elm:15183( 6910): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.aasaservice, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/KLMS-2.5.183: ( 3639): KLMSIntentService(): listeningToPackageRemoved().END
D/elm:15183( 6910): ElmAgentService : onCreate()
E/Zygote  ( 6946): MountEmulatedStorage()
I/libpersona( 6946): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6946): v2
I/libpersona( 6946): KNOX_SDCARD not a persona
I/SELinux ( 6946): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/elm:15183( 6910): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:15183( 6910): MainReceiver.listeningToPackageRemoved()
D/elm:15183( 6910): MDMBridge.getInstance()
D/elm:15183( 6910): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:15183( 6910): MDMBridge.getAllLicenseInfoFromSDK()
I/ActivityManager( 1016): Start proc com.samsung.aasaservice for broadcast com.samsung.aasaservice/.AASAUpdateReceiver: pid=6946 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 6946): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6946): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/Compatibility( 6037): onReceive() it will make start service
E/SQLiteLog( 6685): (284) automatic index on crash_info_summary(package_name_touched)
D/ThemeInfoUtil( 6929): getCurrentFestivalName is [null]
D/ThemeInfoUtil( 6929): isCurrentFestival = false
D/ActivityManager( 1016): startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
I/KLMS-2.5.183: ( 3639): KLMSIntentService(): onDestroy()
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 6946): TimaSignature is unavailable
D/ActivityThread( 6946): Added TimaKeyStore provider
D/Compatibility( 6037): onHandleIntent()
E/Zygote  ( 6964): MountEmulatedStorage()
E/Zygote  ( 6964): v2
I/libpersona( 6964): KNOX_SDCARD checking this for 10152
I/libpersona( 6964): KNOX_SDCARD not a persona
I/SELinux ( 6964): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6964): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/Compatibility( 6037): intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10155, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
E/SELinux ( 6964): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/Compatibility( 6037): found: 2
D/Compatibility( 6037): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 6037): skipping ResolveInfo{1f2a139a com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 6037): considering ResolveInfo{19ff74cb com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 6037): default: com.sec.android.app.soundalive.SAControlPanelActivity
I/ActivityManager( 1016): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=6964 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
D/Compatibility( 6037): enabling receiver ResolveInfo{75cc4a8 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/elm:15183( 6910): ElmAgentService : onDestroy().
D/Compatibility( 6037): enabling receiver ResolveInfo{285b1bc1 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/TimaKeyStoreProvider( 6964): TimaSignature is unavailable
D/ActivityThread( 6964): Added TimaKeyStore provider
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
D/BadgeProvider( 5994): sendNotify entered. [uri] : content://com.sec.badge/apps
D/BadgeProvider( 5994): sendNotify, [notify] : null
D/BadgeProvider( 5994): update, [uri] : content://com.sec.badge/apps
D/BadgeProvider( 5994): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 5994): update, [UpdateCount] : 1
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/Compatibility( 6037): enabling receiver ResolveInfo{2985cf66 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
I/art     ( 1016): Explicit concurrent mark sweep GC freed 24997(1889KB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 29MB/44MB, paused 3.488ms total 380.675ms
D/Compatibility( 6037): enabling receiver ResolveInfo{20e92a7 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
E/Zygote  ( 6980): MountEmulatedStorage()
I/libpersona( 6980): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6980): v2
I/libpersona( 6980): KNOX_SDCARD not a persona
I/SELinux ( 6980): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/PackageManager( 1016): delete codoeFile: 
D/AASAservice-UpdateReceiver( 6946): AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
I/ActivityManager( 1016): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=6980 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 6980): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6980): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/AASA_removePackage( 1016): UID=10155 Target=com.test.thalitest
D/AASAuninstall( 1016): userId = 0, info.removedAppID = -1, info.uid = 10155, packageName = com.test.thalitest
D/ActivityManager( 1016): startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
D/PackageManager( 1016): result of delete: 1{117155916}
W/System.err( 6946): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 6946): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
W/System.err( 6946): 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
W/System.err( 6946): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/System.err( 6946): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/System.err( 6946): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/System.err( 6946): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6946): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 6946): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/System.err( 6946): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6946): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6946): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 6946): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
D/Compatibility( 6037): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
D/AndroidRuntime( 6897): Shutting down VM
I/UpdateIcingCorporaServi( 5466): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
D/TimaKeyStoreProvider( 6980): TimaSignature is unavailable
D/ActivityThread( 6980): Added TimaKeyStore provider
I/ActivityManager( 1016): Killing 5831:com.sec.android.widgetapp.tapandpay/u0a156 (adj 15): empty #31
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6996): MountEmulatedStorage()
I/libpersona( 6996): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6996): v2
I/libpersona( 6996): KNOX_SDCARD not a persona
I/SELinux ( 6996): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6996): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6996): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6996 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/SQLiteLog( 6964): (284) automatic index on shooting_modes(title_id)
D/TimaKeyStoreProvider( 6996): TimaSignature is unavailable
D/ActivityThread( 6996): Added TimaKeyStore provider
E/Zygote  ( 7007): MountEmulatedStorage()
E/Zygote  ( 7007): v2
I/libpersona( 7007): KNOX_SDCARD checking this for 10003
I/libpersona( 7007): KNOX_SDCARD not a persona
I/SELinux ( 7007): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 7007): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 7007): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=7007 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
D/ActivityManager( 1016): startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
E/JavaBinder( 1016): !!! FAILED BINDER TRANSACTION !!!
W/BroadcastQueue( 1016): Exception when sending broadcast to ComponentInfo{com.sec.android.widgetapp.tapandpay/com.sec.android.widgetapp.tapandpay.TapandpayAppWidgetProvider}
W/BroadcastQueue( 1016): android.os.TransactionTooLargeException
W/BroadcastQueue( 1016): 	at android.os.BinderProxy.transactNative(Native Method)
W/BroadcastQueue( 1016): 	at android.os.BinderProxy.transact(Binder.java:511)
W/BroadcastQueue( 1016): 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
W/BroadcastQueue( 1016): 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:309)
W/BroadcastQueue( 1016): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1236)
W/BroadcastQueue( 1016): 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20562)
W/BroadcastQueue( 1016): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
W/BroadcastQueue( 1016): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3405)
W/BroadcastQueue( 1016): 	at android.os.Binder.execTransact(Binder.java:461)
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
W/ContextImpl( 6980): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 7007): TimaSignature is unavailable
D/ActivityThread( 7007): Added TimaKeyStore provider
I/PCWCLIENTTRACE_LOG( 6996): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 6996): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 6996): new DMDBOpenHelper instance
E/Zygote  ( 7028): MountEmulatedStorage()
E/Zygote  ( 7028): v2
I/libpersona( 7028): KNOX_SDCARD checking this for 10156
I/libpersona( 7028): KNOX_SDCARD not a persona
I/SELinux ( 7028): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=7028 uid=10156 gids={50156, 9997} abi=armeabi-v7a
D/ActivityManager( 1016): startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
I/SELinux ( 7028): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
E/SELinux ( 7028): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/PCWCLIENTTRACE_PushUtil( 6996): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6996): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6996): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6996): [onReceive] - android.intent.action.PACKAGE_REMOVED
D/TimaKeyStoreProvider( 7028): TimaSignature is unavailable
D/ActivityThread( 7028): Added TimaKeyStore provider
D/Launcher.Model( 1478): reloadBadges entered.
D/RCPManager( 5544):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 1016):  in createShortcut() for packageName: com.test.thalitest userId0
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
D/RCPManagerService( 1016): queryAllProviders():  providerCallBack is not register for 0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/UserAnalysis.PlaceProvider( 7007): PlaceProvider onCreate()
E/Zygote  ( 7044): MountEmulatedStorage()
I/libpersona( 7044): KNOX_SDCARD checking this for 10035
E/Zygote  ( 7044): v2
I/libpersona( 7044): KNOX_SDCARD not a persona
I/SELinux ( 7044): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 7044): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 7044): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
W/art     ( 6897): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
I/ActivityManager( 1016): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=7044 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
D/TimaKeyStoreProvider( 7044): TimaSignature is unavailable
I/ActivityManager( 1016): Killing 5864:com.policydm/1000 (adj 15): empty #31
D/ActivityThread( 7044): Added TimaKeyStore provider
I/TapandpayWidget:TapandpayAppWidgetProvider( 7028): onReceive()
D/TapandpayWidget:TapandpayAppWidgetProvider( 7028): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
D/UserAnalysis.SecureDbManager( 7007): Key for secure DB is newly created
D/UserAnalysis.SecurePlaceDbHelper( 7007): SecurePlaceDbHelper() 
D/UserAnalysis( 7007): Create SecureDbHelper
I/TapandpayWidget:Utils( 7028): Clear T&P info.
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/TapandpayWidget:TapandpayAppWidgetProvider( 7028): Widget is not attached.
D/IntelligenceServiceApplication( 7007): onCreate()
D/UserAnalysis.UserAnalysisBroadcastReceiver( 7007): Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/IntelligenceServiceApplication( 7007): no applications having user consent for prediction
E/Zygote  ( 7064): MountEmulatedStorage()
E/Zygote  ( 7064): v2
I/libpersona( 7064): KNOX_SDCARD checking this for 10160
I/libpersona( 7064): KNOX_SDCARD not a persona
I/SELinux ( 7064): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=7064 uid=10160 gids={50160, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 5880:com.sec.android.app.samsungapps/u0a10 (adj 15): empty #31
I/SELinux ( 7064): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 7064): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Killing 5973:com.sec.android.app.myfiles/u0a47 (adj 15): empty #31
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.android.keychain, hostingType: broadcast
V/PlaceDetection v1.0.19 ( 7007): [PlaceDetection::stopService] Service stopped.
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
V/PlaceDetection v1.0.19 ( 7007): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
D/TimaKeyStoreProvider( 7064): TimaSignature is unavailable
D/ActivityThread( 7064): Added TimaKeyStore provider
E/Zygote  ( 7081): MountEmulatedStorage()
E/Zygote  ( 7081): v2
I/libpersona( 7081): KNOX_SDCARD checking this for 1000
I/libpersona( 7081): KNOX_SDCARD not a persona
I/SELinux ( 7081): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 7081): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 7081): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=7081 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 6016:com.wsomacp/u0a25 (adj 15): empty #31
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
V/PlaceDetection v1.0.19 ( 7007): [PlaceDetection::setDisableDetection] PlaceType PLACE_OTHER disabled.
V/PlaceDetection v1.0.19 ( 7007): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_OTHER set as false.
V/PlaceDetection v1.0.19 ( 7007): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_OTHER_ACTIVITY set as false
V/PlaceDetection v1.0.19 ( 7007): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
V/PlaceDetection v1.0.19 ( 7007): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
V/PlaceDetection v1.0.19 ( 7007): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
E/SQLiteLog( 6685): (10) unixWrite() File Descriptor : 26 gets errno : 9
E/SQLiteLog( 6685): (10) unixWrite() File Descriptor : 26 gets errno : 9
V/PlaceDetection v1.0.19 ( 7007): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
V/PlaceDetection v1.0.19 ( 7007): [PlaceDetection::setDisableDetection] PlaceType PLACE_HOME disabled.
V/PlaceDetection v1.0.19 ( 7007): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_HOME set as false.
V/PlaceDetection v1.0.19 ( 7007): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_HOME set as false
V/PlaceDetection v1.0.19 ( 7007): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
V/PlaceDetection v1.0.19 ( 7007): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
V/PlaceDetection v1.0.19 ( 7007): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
V/PlaceDetection v1.0.19 ( 7007): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
V/PlaceDetection v1.0.19 ( 7007): [PlaceDetection::setDisableDetection] PlaceType PLACE_WORK disabled.
V/PlaceDetection v1.0.19 ( 7007): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_WORK set as false.
V/PlaceDetection v1.0.19 ( 7007): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_WORK set as false
V/PlaceDetection v1.0.19 ( 7007): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
V/PlaceDetection v1.0.19 ( 7007): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
V/PlaceDetection v1.0.19 ( 7007): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
V/PlaceDetection v1.0.19 ( 7007): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
V/PlaceDetection v1.0.19 ( 7007): [PlaceDetection::setDisableDetection] PlaceType MYCAR disabled.
V/PlaceDetection v1.0.19 ( 7007): [PlaceDetectionManager::setChangeDetector] PlaceType MYCAR set as false.
E/SQLiteDatabase( 6685): Error inserting name=status value=successfully initialized
E/SQLiteDatabase( 6685): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
E/SQLiteDatabase( 6685): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 6685): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
E/SQLiteDatabase( 6685): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 6685): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 6685): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
E/SQLiteDatabase( 6685): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
E/SQLiteDatabase( 6685): 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
E/SQLiteDatabase( 6685): 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
E/SQLiteDatabase( 6685): 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:193)
E/SQLiteDatabase( 6685): 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
E/SQLiteDatabase( 6685): 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
E/SQLiteDatabase( 6685): 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
E/SQLiteDatabase( 6685): 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
E/SQLiteDatabase( 6685): 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
E/SQLiteDatabase( 6685): 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
E/SQLiteDatabase( 6685): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 6685): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 6685): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6685): 	at android.os.HandlerThread.run(HandlerThread.java:61)
V/PlaceDetection v1.0.19 ( 7007): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_CAR set as false
D/TimaKeyStoreProvider( 7081): TimaSignature is unavailable
D/ActivityThread( 7081): Added TimaKeyStore provider

```
