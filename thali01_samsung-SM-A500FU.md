#### Test 549702617d40def_thali01_samsung-SM-A500FU Logs


```
--------- beginning of main
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
--------- beginning of system
D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.AppsMonitorIntentService; callingUser = 0; userId(target) = 0
I/DBG_POLICYDM( 5754): [com.policydm.XSPPReceiver(52/onReceive)] ACTION_PACKAGE_ADDED. mPkgName:com.test.thalitest
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/Mms/MmsConfig( 5678): Load Resize quality : 80
D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/EasySignUpManager_1.0.1( 5678): serviceId : 1, features : -1
D/EasySignUpManager_1.0.1( 5678): isAuth is false
D/Mms/MmsConfig( 5678): setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
E/Zygote  ( 5821): MountEmulatedStorage()
E/Zygote  ( 5821): v2
I/SELinux ( 5821): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5821): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5821): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/libpersona( 5821): KNOX_SDCARD checking this for 10035
I/libpersona( 5821): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.receiver.PackageInfoChangeReceiver: pid=5821 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/libprocessgroup( 1018): failed to open /acct/uid_10035/pid_5207/cgroup.procs: No such file or directory
D/TimaKeyStoreProvider( 5821): TimaSignature is unavailable
D/ActivityThread( 5821): Added TimaKeyStore provider
D/TP/MmsSmsProvider( 1466): query,matched:2117, calling pid = 5678
D/TP/MmsSmsProvider( 1466): match 2117:Elapsed time : 0.952 ms
I/DBG_POLICYDM( 5754): [com.policydm.agent.XDMTask(170/xdmAgentTaskHandler)] XEVENT_DM_INIT
I/DBG_POLICYDM( 5754): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
D/EasySignUpManager_1.0.1( 5678): isAuth is false
D/EasySignUpManager_1.0.1( 5678): getServiceStatus : serviceId (1) is OFF
E/CscParser( 5678): mps_code.dat does not exist
E/CscParser( 5678): customer_path =/system/csc/customer.xml
E/CscParser( 5678): fileName + /system/csc/customer.xml
E/CscParser( 5678): mps_code.dat does not exist
I/DBG_POLICYDM( 5754): [com.policydm.XDMApplication(677/xdmGetNotibarState)] get NotibarState : 7
I/DBG_POLICYDM( 5754): [com.policydm.ui.XUINotificationManager(47/xuiSetIndicator)] Indicator id : 7
E/CscParser( 5678): customer_path =/system/csc/customer.xml
,E/CscParser( 5678): fileName + /system/csc/customer.xml
I/DBG_POLICYDM( 5754): [com.policydm.XDMApplication(669/xdmSetNotibarState)] set NotibarState : 7
D/CscParser( 5678): getInstance fileName =/system/csc/customer.xml
D/Mms/MmsConfig( 5678):  enable multiwindow = true
E/Mms/MessageUtils( 5678): setCountryDetector : update country detector info 
E/Mms/MessageUtils( 5678): updateCountryIso : update country iso info 
D/Mms/MmsConfig( 5678): [end]    init() consume time = 169.252812
D/PowerManagerService( 1018): [s] UserActivityState : 2 -> 4
D/Mms/Contact( 5678): [start]    init() consume time = 0.815886
I/PowerManagerService( 1018): Nap time (uid 1000)...
D/PowerManagerService( 1018): handleSandman : startDreaming: false  (canDreamLocked: false  canDozeLocked: false)
I/PowerManagerService( 1018): !@[ps] Screen__Off - 0 :  dream(timeout) (2)
I/PowerManagerService( 1018): Going to sleep due to screen timeout (uid 1000)...
D/DisplayPowerController( 1018): getFinalBrightness : Summary is 1 -> 1
D/DisplayPowerController( 1018): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 1018): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService( 1018): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService( 1018): SecHardwareInterface.setBatteryADC : false
V/WindowOrientationListener( 1018): WindowOrientationListener disabled
D/SensorService( 1018): [SO] activate (ident=0xb88362c8, enabled=0)
I/Sensors ( 1018): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
D/PowerManagerService( 1018): handleSandman : startDreaming: true  (canDreamLocked: false  canDozeLocked: true)
D/PowerManagerService( 1018): handleSandman : startDream(true)
E/PowerManagerService( 1018): handleSandman : startDreaming, but isDreaming false
I/PowerManagerService( 1018): Sleeping (uid 1000)...
D/PowerManagerService( 1018): [s] UserActivityState : 4 -> 0
I/SurfaceFlinger(  257): id=9 createSurf (720x1280),-1 flag=20004, DolorFade
I/DBG_POLICYDM( 5754): [com.policydm.db.XDBAESCrypt(216/xdbGetCryptionkey)] try read dbString
E/SPPClientService( 5821): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 5821): [PushClientApplication] Push log off : This is Ship build version
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.samsung.android.sdk.samsunglink, hostingType: broadcast
D/SensorManager( 1018): unregisterListener ::   
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/PowerManagerService( 1018): Excessive delay in ColorFade : createSurface: 11ms
I/Adreno-EGL( 1018): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 1018): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 1018): Build Date: 04/06/15 Mon
I/Adreno-EGL( 1018): Local Branch: 
I/Adreno-EGL( 1018): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 1018): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 1018):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
D/KeyguardViewMediator( 1176): onScreenTurnedOff(3)
I/KeyguardEffectViewController( 1176): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 1176): changeWallpaperByScreenOff()
D/KeyguardViewMediator( 1176): notifyScreenOffLocked
D/KeyguardViewMediator( 1176): timeout : 5000
D/TP/MmsSmsProvider( 1466): query,matched:13, calling pid = 5678
D/TP/MmsSmsProvider( 1466): match 13:Elapsed time : 2.898 ms
I/ActivityManager( 1018): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=5847 uid=10038 gids={50038, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
E/Zygote  ( 5847): MountEmulatedStorage()
I/libpersona( 5847): KNOX_SDCARD checking this for 10038
E/Zygote  ( 5847): v2
I/libpersona( 5847): KNOX_SDCARD not a persona
I/SELinux ( 5847): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5847): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/DBG_POLICYDM( 5754): [com.policydm.db.XDBFumoAdp(427/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
E/SELinux ( 5847): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
D/KeyguardViewMediator( 1176): setting alarm to turn off keyguard, seq = 1
D/KeyguardViewMediator( 1176): handleNotifyScreenOff
D/VolumePanel( 1176): onScreenTurnedOff()
D/VolumePanel( 1176): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
D/Launcher.HomeView( 1482): onPause
D/VolumePanel( 1176): mCoverBroadcastReceiver: Screen OFF end
D/SecKeyguardClockSingleView( 1176): onScreenTurnedOff
D/Launcher( 1482): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
I/DBG_POLICYDM( 5754): [com.policydm.db.XDBFumoAdp(586/xdbGetFUMOInitiatedType)] Initiated Type: 0
D/PowerManagerService( 1018): Excessive delay in ColorFade : createEglContext: 44ms
I/DBG_POLICYDM( 5754): [com.policydm.polling.XPollingAgent(71/xpollingCheckVersionInfo)] 
I/DBG_POLICYDM( 5754): [com.policydm.polling.XPollingAgent(270/xpollingCheckTimer)] 
D/SPPClientService( 5821): PushLog.txt file is not deleted.
D/SPPClientService( 5821): PushLog.txt file is not deleted.
D/SPPClientService( 5821): ============PushLog. stop!
I/DBG_POLICYDM( 5754): [com.policydm.polling.XPollingAgent(284/xpollingCheckTimer)] savedpollingtime : 2016/01/11/11:32:45
I/DBG_POLICYDM( 5754): [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] currentTime : 2016/01/05/02:20:32
I/DBG_POLICYDM( 5754): [com.policydm.polling.XPollingAgent(289/xpollingCheckTimer)] Restart Timer..
I/DBG_POLICYDM( 5754): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 0
D/PowerManagerService( 1018): Excessive delay in ColorFade : createEglSurface: 10ms
D/TimaKeyStoreProvider( 5847): TimaSignature is unavailable
D/ActivityThread( 5847): Added TimaKeyStore provider
D/PermissionCache(  257): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (236 us)
I/DBG_POLICYDM( 5754): [com.policydm.agent.XDMUITask(190/xdmUIEvent)] XUI_DM_IDLE_STATE :true
D/PowerManagerService( 1018): Excessive delay in ColorFade : captureScreenshotTextureAndSetViewport: 33ms
D/PanelView( 1176): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
I/DBG_POLICYDM( 5754): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
D/Mms/Contact( 5678): [end]    init consume time = 125.465469
D/Mms/DraftCache( 5678): [start]    rebuildCache consume time = 11.273697
I/DBG_POLICYDM( 5754): [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
I/DBG_POLICYDM( 5754): [com.policydm.noti.XNOTIAdapter(398/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
I/DBG_POLICYDM( 5754): [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
I/DBG_POLICYDM( 5754): [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
I/DBG_POLICYDM( 5754): [com.policydm.noti.XNOTIAdapter(440/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
I/DBG_POLICYDM( 5754): [com.policydm.noti.XNOTIAdapter(266/xnotiPushAdpClearSessionStatus)] 
I/DBG_POLICYDM( 5754): [com.policydm.ui.XUIAdapter(40/xuiAdpSetUiMode)] nDmUiMode : 0
I/DBG_POLICYDM( 5754): [com.policydm.db.XDBFumoAdp(438/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
D/TP/MmsSmsProvider( 1466): query,matched:12, calling pid = 5678
D/TP/MmsSmsProvider( 1466): match 12:Elapsed time : 1.635 ms
E/SmartFaceService( 1018): onReceive: android.intent.action.SCREEN_ON
D/StatusBar.NetworkController( 1176): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
W/System.err( 1018): java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/Launcher.HomeView( 1482): onStop
V/ActivityThread( 1482): updateVisibility : ActivityRecord{258c7b54 token=android.os.BinderProxy@17bce9a5 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
W/System.err( 1018): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 1018): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/SmartFaceService( 1018): fail to set sysfs 1
W/System.err( 1018): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
W/System.err( 1018): 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
W/System.err( 1018): 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
W/System.err( 1018): 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:468)
W/System.err( 1018): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
W/System.err( 1018): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 1018): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 1018): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 1018): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 1018): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 1018): 	at libcore.io.Posix.open(Native Method)
W/System.err( 1018): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 1018): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 1018): 	... 10 more
E/PhotosPlugin( 5787): Loading PhotosPlugin
W/ResourcesManager( 5847): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5847): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
I/DBG_POLICYDM( 5754): [com.policydm.db.XDBFumoAdp(564/xdbSetFUMOInitiatedType)] Initiated Type: 0
D/InputMethodManagerService( 1018): [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
I/StatusBar( 1176): Icon Only
D/PanelView( 1176): There is/are notification(s) 
D/Mms/DraftCache( 5678): [end]    rebuildCache consume time = 71.326927
D/MotionRecognitionService( 1018):   mReceiver.onReceive : ACTION_SCREEN_ON
D/Mms/MethodReflector( 5678): getSubId is called
D/Mms/TelephonyUtils( 5678): getLongSubId from simSlot 0, return Value = -1
E/MotionRecognitionService( 1018):  handler : SCREEN_ON end
D/Mms/MethodReflector( 5678): getTelephonyProperty is called
D/Mms/DownloadManager( 5678): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 5678): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5678): auto download without roaming -> true
D/Mms/DownloadManager( 5678): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/MethodReflector( 5678): getSubId is called
D/NotificationService( 1018): ACTION_SCREEN_ON
D/LightsService( 1018): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1018) 
D/LightsService( 1018): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 1018): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1018): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
I/DBG_POLICYDM( 5754): [com.policydm.polling.XPollingAgent(311/xPollingReportReStartAlarm)] 
D/audio_hw_primary(  282): adev_set_parameters: enter: screen_state=on
V/voice   (  282): voice_set_parameters: enter: screen_state=on
D/Mms/MethodReflector( 5678): getDefaultSmsSubId is called
V/voice   (  282): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  282): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  282): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  282): audio_extn_hfp_set_parameters: enter
E/Mms/TelephonyUtils( 5678): subID is null or 0 length, so get DefaultSubId!!
V/audio_hw_primary(  282): adev_set_parameters: exit
D/Mms/TelephonyUtils( 5678): getLongSubId from simSlot 1, return Value = -1000
D/Mms/MethodReflector( 5678): getTelephonyProperty is called
D/Mms/DownloadManager( 5678): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 5678): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 5678): auto download without roaming -> true
D/Mms/DownloadManager( 5678): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager( 5678): auto download during roaming secondary -> false
D/Mms/DownloadManager( 5678): mAutoDownload ------> true
E/WifiNative-wlan0( 1018): do suspend false
I/wpa_supplicant( 2079): reset timer : RESET_TIMER 1
I/wpa_supplicant( 2079): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 2079): P2P: Current p2p state = IDLE
I/wpa_supplicant( 2079): Scan requested (ret=0) - scan timeout 30 seconds
D/PowerManagerService( 1018): Excessive delay in ColorFade : initGLShaders: 124ms
D/IpRemoteDisplayController( 1018): intent received android.intent.action.SCREEN_ON
D/PowerManagerService( 1018): Excessive delay in ColorFade prepare: 244ms
D/IpRemoteDisplayController( 1018): Bridge Server is not available
D/DisplayPowerController( 1018): ColorFade: onAnimationStart
D/DisplayPowerController( 1018): getFinalBrightness : Summary is 5 -> 5
D/GpsLocationProvider( 1018): receive broadcast intent, action: android.intent.action.SCREEN_ON
D/DisplayPowerController( 1018): performScreenOffTransition : no brightness animation
D/PersonaManagerService( 1018): ACTION_SCREEN_ON onReceive
D/PersonaManagerServiceHandler( 1018): MSG_ACTION_SCREEN_ON called
D/CoverManagerWhiteLists( 1018): isAllowedToUse : SIGNATURE_MATCH
I/NfcService( 1447): When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
D/NfcService( 1447): call the applyRouting
D/Mms/ArtClassLoader( 5678): init [DONE] art
D/accuweather( 1728): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_ON
D/accuweather( 1728): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
D/accuweather( 1728): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
D/accuweather( 1728): [KK AccuPhone]>>> UIM:282 [0:0] update clock event, is not screen on!!
D/ActivityManager( 1018): startService callerProcessName:com.sec.android.widgetapp.ap.hero.accuweather, calleePkgName: com.sec.android.widgetapp.ap.hero.accuweather
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
I/DBG_POLICYDM( 5754): [com.policydm.db.XDB(1824/xdbSetBackUpServerUrl)] 
D/ComposerPerformance( 5678): 1451956832904 ms / [DONE] Composer constructor
E/CII     ( 5678): CommonIMSInterface: VoLTE CSC feature disabled.
I/SamsungIME( 1790): getNextShiftState() cursorCapsMode : 0
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
I/Mms/ReservationManager( 5678): ReservationManager()
I/Mms/ReservationManager( 5678): resetAfterConnected()
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/Mms/Conversation( 5678): [start]    init() consume time = 121.784636
D/TP/MmsSmsProvider( 1466): query,matched:7, calling pid = 5678
D/TP/MmsSmsProvider( 1466): match 7:Elapsed time : 6.345 ms
D/TP/MmsSmsProvider( 1466): deleteConversation threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1466): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1466): updateThread(), thread_id = 9223372036854775807
V/TP/MmsSmsDatabaseHelper( 1466): sUpgradeVersion = 0, db.getVersion() = 81
D/TP/MmsSmsProvider( 1466): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1466): need read changed broadcast:false
I/DBG_POLICYDM( 5754): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 1
D/Mms/Conversation( 5678): [end]    init consume time = 28.376667
D/Mms/MessagingNotification( 5678): [start]    init() consume time = 9.009062
I/DBG_POLICYDM( 5754): [com.policydm.agent.XDMTask(195/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
I/Mms/ReservationManager( 5678): getReservedSendMessageCount(): retMessageCount=0
D/Mms/MmsApp( 5678): [end]    onCreate() consume time = 11.952135
D/Mms/MessagingNotification( 5678): [end]    init consume time = 8.25224
D/TP/MmsSmsProvider( 1466): query,matched:0, calling pid = 5678
V/TP/MmsSmsProvider( 1466): getSimpleConversations entered.
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
D/TP/MmsSmsProvider( 1466): match 0:Elapsed time : 6.001 ms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/LightsService( 1018): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 1018) 
E/lights  ( 1018): write_int failed to open -1
D/LightsService( 1018): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
D/BatteryService( 1018): turn on LED for fully charged
D/LightsService( 1018): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1018): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/Mms/DownloadManager( 5678): Service state changed: Bundle[mParcelledData.dataSize=744]
D/SSRM:n  ( 1018): SIOP:: AP = 320
E/SmartFaceService( 1018): onReceive: android.intent.action.SCREEN_OFF
W/System.err( 1018): java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
W/System.err( 1018): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 1018): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err( 1018): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
W/System.err( 1018): 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
W/System.err( 1018): 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
W/System.err( 1018): 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:474)
W/System.err( 1018): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
E/SmartFaceService( 1018): fail to set sysfs 0
W/System.err( 1018): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 1018): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 1018): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 1018): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 1018): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 1018): 	at libcore.io.Posix.open(Native Method)
W/System.err( 1018): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 1018): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 1018): 	... 10 more
D/Mms/Synchronizer( 5678): [start]    doSync consume time = 27.251927
D/Mms/DownloadManager( 5678): roaming ------> false, mSimSlot = 0
D/Mms/MethodReflector( 5678): getSubId is called
D/Mms/TelephonyUtils( 5678): getLongSubId from simSlot 0, return Value = -1
D/Mms/SpamFilter( 5678): [start]    SpamFilter fill() begin consume time = 8.558281
D/TP/MmsSmsProvider( 1466): update, matched:300, calling pid = 5678
V/TP/MmsSmsProvider( 1466): syncDBData start
V/TP/MmsSmsProvider( 1466): syncDBData sms end
V/TP/MmsSmsProvider( 1466): syncDBData mms end
V/TP/MmsSmsProvider( 1466): syncDBData end
D/Mms/MethodReflector( 5678): getTelephonyProperty is called
D/Mms/DownloadManager( 5678): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 5678): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5678): auto download without roaming -> true
D/Mms/DownloadManager( 5678): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager( 5678): mAutoDownload ------> true
D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/Mms/Synchronizer( 5678): [end]    doSync consume time = 16.309792
I/StatusBar( 1176): Icon Only
D/PanelView( 1176): There is/are notification(s) 
D/TP/MmsSmsProvider( 1466): query,matched:400, calling pid = 5678
D/MotionRecognitionService( 1018):   mReceiver.onReceive : ACTION_SCREEN_OFF
D/ActivityManager( 1018): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/ChimeraCfgMgr( 1986): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1986): Module APK com.google.android.play.games already loaded
D/Mms/FreeMessageStatusReceiver( 5678): onReceive, action : android.intent.action.PACKAGE_ADDED
D/SamsungIME( 1790): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
D/DisplayPowerState( 1018): !@ ColorFade entry
D/DisplayPowerController( 1018): ColorFade: onAnimationEnd
D/lights  ( 1018): lcd : 0 +
D/DisplayPowerController( 1018): getFinalBrightness : Summary is 0 -> 0
D/DisplayPowerController( 1018): performScreenOffTransition : no brightness animation
I/BatteryStatsDumper( 1018): In refreshStats isReason Screen ON/OFF: true
D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
E/Zygote  ( 5877): MountEmulatedStorage()
E/Zygote  ( 5877): v2
I/libpersona( 5877): KNOX_SDCARD checking this for 10072
I/libpersona( 5877): KNOX_SDCARD not a persona
I/SELinux ( 5877): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/lights  ( 1018): lcd : 0 -
I/SELinux ( 5877): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5877): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/MISC PowerHAL( 1018): sysfs_write +: /sys/class/input/event1/device/enabled: 0
D/DisplayPowerController( 1018): getFinalBrightness : Summary is 0 -> 0
D/MISC PowerHAL( 1018): sysfs_write -: /sys/class/input/event1/device/enabled: 0
D/DisplayPowerController( 1018): performScreenOffTransition : no brightness animation
D/MISC PowerHAL( 1018): sysfs_write +: /sys/class/input/event3/device/enabled: 0
D/PowerManagerService( 1018): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService( 1018): [PWL] sb release: PowerManagerService.Display
D/MISC PowerHAL( 1018): sysfs_write -: /sys/class/input/event3/device/enabled: 0
D/MISC PowerHAL( 1018): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL( 1018): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
I/QCOM PowerHAL( 1018): Got set_interactive hint
D/DisplayManagerService( 1018): !@display_state: ON -> OFF
D/SurfaceFlinger(  257): Set power mode=0, type=0 flinger=0xb85c1690
D/qdhwcomposer(  257): hwc_setPowerMode: Setting mode 0 on display: 0
E/qdutils (  257): int qdutils::getHDMINode(): Failed to open fb node 2
I/DisplayManagerService( 1018): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
E/qdutils (  257): int qdutils::getHDMINode(): Failed to find HDMI node
D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
D/TimaKeyStoreProvider( 5877): TimaSignature is unavailable
I/ActivityManager( 1018): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=5877 uid=10072 gids={50072, 9997} abi=armeabi-v7a
D/ActivityThread( 5877): Added TimaKeyStore provider
D/ChimeraCfgMgr( 1986): Loading module com.google.android.gms.gass from APK com.google.android.gms
V/ActivityManager( 1018): Display changed displayId=0
D/ActivityManager( 1018): startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/StatusBar.NetworkController( 1176): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1176): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1176): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1176): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
I/BatteryStatsDumper( 1018): Screen bin #0: time=30305 power=0.17677916666666665
I/BatteryStatsDumper( 1018): Screen bin #1: time=0 power=0.0
I/BatteryStatsDumper( 1018): Screen bin #2: time=0 power=0.0
I/BatteryStatsDumper( 1018): Screen bin #3: time=0 power=0.0
I/BatteryStatsDumper( 1018): Screen bin #4: time=0 power=0.0
I/BatteryStatsDumper( 1018): Previous Battery Level: 0 Current Level: 100 Delta: -100
D/AsyncTaskServiceImpl( 1986): Submit a task: k
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/WifiNative-wlan0( 1018): do suspend true
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/NotificationService( 1018): ACTION_SCREEN_OFF
I/ServiceManager(  330): Waiting for service AtCmdFwd...
D/LightsService( 1018): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1018) 
D/LightsService( 1018): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
E/MotionRecognitionService( 1018):  handler : SCREEN_OFF end 
D/LightsService( 1018): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1018): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/Mms/SpamFilter( 5678): [end]    SpamFilter fill() finished consume time = 136.03599
D/Mms/FreeMessageReceiverService( 5678): onHandleIntent, action : android.intent.action.PACKAGE_ADDED
D/Mms/FreeMessageReceiverService( 5678): onHandleIntent: ACTION_PACKAGE_ADDED
D/ChimeraCfgMgr( 1986): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/audio_hw_primary(  282): adev_set_parameters: enter: screen_state=off
V/voice   (  282): voice_set_parameters: enter: screen_state=off
V/voice   (  282): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  282): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  282): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  282): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  282): adev_set_parameters: exit
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.android.app.myfiles, hostingType: broadcast
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/BadgeProvider( 5877): onCreate
D/BadgeProvider( 5877): DatabaseHelper
E/Zygote  ( 5898): MountEmulatedStorage()
E/Zygote  ( 5898): v2
I/libpersona( 5898): KNOX_SDCARD checking this for 10047
I/libpersona( 5898): KNOX_SDCARD not a persona
I/SELinux ( 5898): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5898): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5898): [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=5898 uid=10047 gids={50047, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
D/ChimeraCfgMgr( 1986): Loading module com.google.android.gms.vision from APK com.google.android.gms
I/ActivityManager( 1018): Killing 5271:com.sec.android.diagmonagent/1000 (adj 15): empty #31
I/ActivityManager( 1018): Killing 5228:com.sec.spp.push:RemoteNotiProcess/u0a35 (adj 15): empty #32
I/BackgroundCompactionService( 1018): Schedule Type1 BGCompaction
D/TimaKeyStoreProvider( 5898): TimaSignature is unavailable
D/ActivityThread( 5898): Added TimaKeyStore provider
D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/Mms/MessagingNotification( 5678): checkBadgeCount unreadCount=0 badgeCount=0
I/System.out( 5499): Thread-947(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
D/TP/SmsProvider( 1466): query,matched:26, calling pid = 5678
I/System.out( 5499): Thread-947(ApacheHTTPLog):isSBSettingEnabled false
D/k       ( 1986): Processing package: com.test.thalitest
I/System.out( 5499): Thread-947(ApacheHTTPLog):isShipBuild true
I/System.out( 5499): Thread-947(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5499): Thread-947(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
D/TP/SmsProvider( 1466): match 26:Elapsed time : 8.844 ms
D/IpRemoteDisplayController( 1018): intent received android.intent.action.SCREEN_OFF
D/IpRemoteDisplayController( 1018): Bridge Server is not available
D/GassUtils( 1986): Found app info for package com.test.thalitest:18. Hash: 82ccbc74df315987b7be206c22ec4eaa3ab0d49235c4895536307c8f71b675fe
D/k       ( 1986): Found info for package com.test.thalitest in db.
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1018): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.internal.SharedPreferencesService; callingUser = 0; userId(target) = 0
W/ResourcesManager( 5898): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5898): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5898): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/GpsLocationProvider( 1018): receive broadcast intent, action: android.intent.action.SCREEN_OFF
D/TP/MmsSmsProvider( 1466): query,matched:6, calling pid = 5678
D/TP/MmsSmsProvider( 1466): match 6:Elapsed time : 1.791 ms
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
V/EmergencyMode( 1421): [EmergencyStateReceiver] onReceive : android.intent.action.SCREEN_OFF
W/libprocessgroup( 1018): failed to open /acct/uid_10035/pid_5228/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_5271/cgroup.procs: No such file or directory
V/EmergencyMode( 1421): [EmergencyStateReceiver] binteractive [false] why[3]
D/PersonaManagerService( 1018): ACTION_SCREEN_OFF onReceive
D/PersonaManagerServiceHandler( 1018): MSG_ACTION_SCREEN_OFF called
D/NfcService( 1447): call the applyRouting
D/qdhwcomposer(  257): hwc_setPowerMode: Done setting mode 0 on display 0
D/EnterpriseController(  277): uids 10028
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10028
I/qdhwcomposer(  257): handle_blank_event: dpy:0 panel power state: 0
E/qdutils (  257): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  257): int qdutils::getHDMINode(): Failed to find HDMI node
I/qtaguid ( 5499): Tagging socket 44 with tag e8d195d100000000{3906049489,0} for uid -1, pid: 5499, getuid(): 10028
D/SurfaceControl( 1018): Excessive delay in setPowerMode(): 279ms
D/PowerManagerService( 1018): Excessive delay in !@display_state: OFF: 280ms
I/libsuspend( 1018): !@autosuspend_wakeup_count_enable
D/PowerManagerService( 1018): Excessive delay in DisplayManagerInternal.requestDisplayStateInternal(mRequestingState): 288ms
I/libsuspend( 1018): !@autosuspend_wakeup_count_enable done
I/PowerManagerService( 1018): [PWL] Off : 0s ago
I/PowerManagerService( 1018): [PWL]   PowerManagerService.WakeLocks: ref count=1
D/accuweather( 1728): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_OFF
I/PowerManagerService( 1018): [PWL]     mWakeLockSummary : 0x1
D/accuweather( 1728): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
I/PowerManagerService( 1018): [PWL]       PARTIAL_WAKE_LOCK              '*alarm*' (uid=1000, pid=1018, ws=WorkSource{1000}) (elapsedTime=1250)
D/AndroidRuntime( 5844): 
D/AndroidRuntime( 5844): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
I/PowerManagerService( 1018): [PWL]       PARTIAL_WAKE_LOCK              'SmartManager Framework Thread' (uid=1000, pid=1018, ws=null) (elapsedTime=308)
I/PowerManagerService( 1018): [PWL]       PARTIAL_WAKE_LOCK              'Icing' (uid=10012, pid=1986, ws=WorkSource{10012 com.google.android.gms}) (elapsedTime=132)
I/PowerManagerService( 1018): [PWL]   PowerManagerService.Broadcasts: ref count=1
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
D/AndroidRuntime( 5844): CheckJNI is OFF
D/AndroidRuntime( 5844): readGMSProperty: start
D/AndroidRuntime( 5844): readGMSProperty: already setted!!
D/AndroidRuntime( 5844): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5844): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5844): readGMSProperty: end
D/AndroidRuntime( 5844): addProductProperty: start
D/ActivityManager( 1018): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/accuweather( 1728): [KK AccuPhone]>>> WCS:113 [0:0] onDestroy : End
I/DBG_POLICYDM( 5754): [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
E/Zygote  ( 5925): MountEmulatedStorage()
E/Zygote  ( 5925): v2
I/libpersona( 5925): KNOX_SDCARD checking this for 10025
I/libpersona( 5925): KNOX_SDCARD not a persona
I/SELinux ( 5925): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5925): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5925): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=5925 uid=10025 gids={50025, 9997} abi=armeabi-v7a
W/ActivityManager( 1018): userId = 0, bbcId = -10000
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/DBG_POLICYDM( 5754): [com.policydm.db.XDBNotiAdp(37/xdbNotiExistInfo)] Noti Exist : false
D/TimaKeyStoreProvider( 5925): TimaSignature is unavailable
D/ActivityThread( 5925): Added TimaKeyStore provider
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/ActivityManager( 1018): Killing 5312:com.android.providers.calendar/u0a42 (adj 15): empty #31
W/ResourcesManager( 5925): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/SSRM:n  ( 1018): SIOP:: AP = 310
D/MyFiles ( 5898): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
D/ActivityManager( 1018): bindService callerProcessName:android, calleePkgName: com.android.defcontainer, action: null
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
E/LibSecureUISvc( 1943): svc_sock_send_message(suisvc): Error sending data, -1 vs 4: Connection refused
I/TactileAssist( 1018): enable value -1
I/TactileAssist( 1018): internal enable value -1
I/TactileAssist( 1018): intensity value -1
I/TactileAssist( 1018): saveAppList value true
I/TactileAssist( 1018): List of disabled apps :
E/installd(  283): system dir 0 : /system/app/
E/installd(  283): system dir 1 : /system/priv-app/
E/installd(  283): system dir 2 : /vendor/app/
E/installd(  283): system dir 3 : /oem/app/
D/PowerManagerService( 1018): [PWL] sb release: PowerManagerService.Broadcasts
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/qtaguid ( 5499): Tagging socket 48 with tag e8d195d100000000{3906049489,0} for uid -1, pid: 5499, getuid(): 10028
I/ActivityManager( 1018): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=5941 uid=10053 gids={50053, 9997, 3003, 3002} abi=armeabi-v7a
E/Zygote  ( 5941): MountEmulatedStorage()
E/Zygote  ( 5941): v2
I/libpersona( 5941): KNOX_SDCARD checking this for 10053
I/libpersona( 5941): KNOX_SDCARD not a persona
I/SELinux ( 5941): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
I/SELinux ( 5941): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5941): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/TimaKeyStoreProvider( 5941): TimaSignature is unavailable
D/ActivityThread( 5941): Added TimaKeyStore provider
D/PackageManager( 1018): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/SMD     (  290): DCD OFF
D/Mms/Omacp( 5678): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
W/libprocessgroup( 1018): failed to open /acct/uid_10042/pid_5312/cgroup.procs: No such file or directory
D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ResourcesManager( 5941): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
E/AffinityControl( 5844): AffinityControl: registerfunction enter
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/OMACP   ( 5925): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
I/SL_DEBUG( 5847): isLoggable:: isProductShip = 1
I/SL_DEBUG( 5847): isLoggable:: SL_DEBUG_EXIST = false
D/AndroidRuntime( 5844): Calling main entry com.android.commands.am.Am
I/art     ( 1018): Explicit concurrent mark sweep GC freed 235834(15MB) AllocSpace objects, 12(4MB) LOS objects, 33% free, 27MB/41MB, paused 3.113ms total 265.944ms
E/PersonaManagerService( 1018): inState():  stateMachine is null !!
I/PersonaManagerService( 1018): PersonaId don't exist
I/ActivityManager( 1018): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/Compatibility( 5941): onReceive() it will make start service
D/SSRM:a  ( 1018): DeviceInfo:: 000000000000
D/SSRM:a  ( 1018): SettingsAirViewInfo:: 000000000
I/OMACP   ( 5925): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
I/OMACP   ( 5925): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
I/OMACP   ( 5925): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
I/OMACP   ( 5925): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
I/OMACP   ( 5925): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
I/OMACP   ( 5925): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
I/OMACP   ( 5925): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
I/OMACP   ( 5925): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
W/ActivityManager( 1018): mDVFSHelper.acquire()
I/OMACP   ( 5925): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
I/OMACP   ( 5925): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
I/SurfaceFlinger(  257): id=10 createSurf (16x16),-1 flag=20004, EimLayer(Di
I/OMACP   ( 5925): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
I/SurfaceFlinger(  257): id=11 createSurf (16x16),-1 flag=20004, EimLayer(An
I/OMACP   ( 5925): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
I/OMACP   ( 5925): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
D/FocusedStackFrame( 1018): Set to : 0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1018): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1018): *FMB* installDecor flags : 25362712
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1018): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
E/Zygote  ( 5970): MountEmulatedStorage()
E/Zygote  ( 5970): v2
I/libpersona( 5970): KNOX_SDCARD checking this for 10175
I/libpersona( 5970): KNOX_SDCARD not a persona
I/SELinux ( 5970): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/PhoneWindow( 1018): *FMB* isFloatingMenuEnabled return false
I/SELinux ( 5970): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1018): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5970 uid=10175 gids={50175, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
E/SELinux ( 5970): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/SurfaceFlinger(  257): id=12 createSurf (720x1280),1 flag=404, uhalitest
D/InputDispatcher( 1018): Focused application set to: xxxx
D/ActivityManager( 1018): startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
D/InputDispatcher( 1018): Focus left window: 1482
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
D/AndroidRuntime( 5844): Shutting down VM
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
D/Compatibility( 5941): onHandleIntent()
D/Compatibility( 5941): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10175, android.intent.extra.user_handle=0}]
D/TimaKeyStoreProvider( 5970): TimaSignature is unavailable
D/ActivityThread( 5970): Added TimaKeyStore provider
D/Compatibility( 5941): found: 2
V/WindowManager( 1018): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
D/StatusBarManagerService( 1018): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
W/BaseAppContext( 1986): Using Auth Proxy for data requests.
W/BaseAppContext( 1986): Using Auth Proxy for data requests.
V/ActivityManager( 1018): Display changed displayId=0
D/Compatibility( 5941): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5941): skipping ResolveInfo{31831900 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5941): considering ResolveInfo{1c6fd539 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5941): default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5941): enabling receiver ResolveInfo{11ab577e com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 5941): enabling receiver ResolveInfo{2410d4df com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/PersonaManager( 1018): isKioskContainerExistOnDevice
D/Compatibility( 5941): enabling receiver ResolveInfo{3f80c52c com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/ActivityManager( 1018): startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
D/Compatibility( 5941): enabling receiver ResolveInfo{31ef8bf5 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
D/Compatibility( 5941): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
I/SurfaceFlinger(  257): id=6 Removed Mauncher (5/9)
I/SurfaceFlinger(  257): id=6 Removed Mauncher (-2/9)
I/UpdateIcingCorporaServi( 5365): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
V/ActivityThread( 1482): updateVisibility : ActivityRecord{258c7b54 token=android.os.BinderProxy@17bce9a5 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1482): onTrimMemory. Level: 20
D/WindowOrientationListener( 1018):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
I/PeopleDatabaseHelper( 1986): cleanUpNonGplusAccounts done.
E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5847): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
W/BaseAppContext( 1986): Using Auth Proxy for data requests.
I/qtaguid ( 5499): Untagging socket 44
I/System.out( 5499): Thread-947 calls detatch()
D/ActivityManager( 1018): startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
W/art     ( 5844): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5847): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
W/BaseAppContext( 1986): Using Auth Proxy for data requests.
D/ActivityManager( 1018): startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.mfluent.asp.ContentAggregatorService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
W/BaseAppContext( 1986): Using Auth Proxy for data requests.
W/BaseAppContext( 1986): Using Auth Proxy for data requests.
I/WebViewFactory( 5970): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
W/BaseAppContext( 1986): Using Auth Proxy for data requests.
I/LibraryLoader( 5970): Time to load native libraries: 2 ms (timestamps 147-149)
I/LibraryLoader( 5970): Expected native library version number "",actual native library version number ""
I/UpdateIcingCorporaServi( 5365): UpdateCorporaTask done [took 204 ms] updated apps [took 204 ms] 
V/WebViewChromiumFactoryProvider( 5970): Binding Chromium to main looper Looper (main, tid 1) {11ab577e}
I/ServiceManager(  330): Waiting for service AtCmdFwd...
I/LibraryLoader( 5970): Expected native library version number "",actual native library version number ""
I/chromium( 5970): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/ActivityManager( 1018): Killing 5246:com.google.android.talk/u0a104 (adj 15): empty #31
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5995): MountEmulatedStorage()
E/Zygote  ( 5995): v2
I/libpersona( 5995): KNOX_SDCARD checking this for 10041
I/libpersona( 5995): KNOX_SDCARD not a persona
I/SELinux ( 5995): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1018): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.app.pushmarketing.PushMarketingReceiver: pid=5995 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 5995): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5995): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1018): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
V/GLSActivity( 1808): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/BrowserStartupController( 5970): Initializing chromium process, singleProcess=true
W/art     ( 5970): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5970): ApplicationContext is null in ApplicationStatus
I/System.out( 5499): Thread-948(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 5499): Thread-948(ApacheHTTPLog):isShipBuild true
D/TimaKeyStoreProvider( 5995): TimaSignature is unavailable
D/ActivityThread( 5995): Added TimaKeyStore provider
W/art     ( 5787): Suspending all threads took: 6.020ms
I/System.out( 5499): Thread-948(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5499): Thread-948(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
W/chromium( 5970): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
I/chromium( 5970): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
I/chromium( 5970): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
I/Adreno-EGL( 5970): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 5970): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 5970): Build Date: 04/06/15 Mon
I/Adreno-EGL( 5970): Local Branch: 
I/Adreno-EGL( 5970): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 5970): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 5970):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
I/BatteryStatsDumper( 1018): Writing to database completed
I/SA      ( 5995): [SSP] onCreated
I/ActivityManager( 1018): Killing 5430:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
I/SA      ( 5995): [TPM] There is no property file
I/SA      ( 5995): [SCU] isHaveSA() - false
I/SA      ( 5995): [TPM] getModelProperty : null
I/SA      ( 5995): [TPM] getCSCProperty : null
I/SA      ( 5995): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 5995): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 5995): [DM] TFT FEATURE: false
I/SA      ( 5995): [PMR] Received action : android.intent.action.PACKAGE_ADDED
I/SA      ( 5995): [DM] init START
I/SA      ( 5995): [DM] This device is not a Vodafone
W/ResourceType( 5995): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
W/ResourceType( 5995): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 5995): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
W/ResourceType( 5995): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 5995): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
W/ResourceType( 5995): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 5995): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
W/ResourceType( 5995): No package identifier when getting value for resource number 0x00000000
W/ResourceType( 5995): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
W/ResourceType( 5995): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
W/ResourceType( 5995): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
W/ResourceType( 5995): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
W/ResourceType( 5995): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
W/ResourceType( 5995): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
W/ResourceType( 5995): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
W/ResourceType( 5995): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
W/ResourceType( 5995): Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
W/ResourceType( 5995): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
W/ResourceType( 5995): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
W/ResourceType( 5995): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
W/ResourceType( 5995): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 5995): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 5995): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
W/ResourceType( 5995): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
W/ResourceType( 5995): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
I/SA      ( 5995): [SCU] isHaveSA() - false
I/SA      ( 5995): support phone number id : false
I/SA      ( 5995): [DM] Supports Ref Jpn : true
I/SA      ( 5995): [DM] init END
I/SA      ( 5995): [SUR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
I/SA      ( 5995): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10175 extra.user_handle.:0 ]
W/ActivityManager( 1018): Activity pause timeout for ActivityRecord{2a068cc u0 com.test.thalitest/.MainActivity t2}
I/Icing   ( 1986): Indexing 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28 from com.google.android.gms
W/libprocessgroup( 1018): failed to open /acct/uid_10104/pid_5246/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10069/pid_5430/cgroup.procs: No such file or directory
W/chromium( 5970): [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
W/GAV2    ( 5787): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/qtaguid ( 5499): Untagging socket 44
I/qtaguid ( 5499): Failed write_ctrl(u 44) res=-1 errno=22
I/qtaguid ( 5499): Untagging socket 44 failed errno=-22
W/NetworkManagementSocketTagger( 5499): untagSocket(44) failed with errno -22
I/System.out( 5499): Thread-948 calls detatch()
W/art     ( 5970): Attempt to remove local handle scope entry from IRT, ignoring
D/Finsky  ( 5499): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
I/Icing   ( 1986): Indexing done 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/AwContents( 5970): onDetachedFromWindow called when already detached. Ignoring
D/PhoneWindow( 5970): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 5970): *FMB* installDecor flags : 8456448
D/SystemWebViewEngine( 5970): CordovaWebView is running on device made by: samsung
W/art     ( 5970): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5970): Attempt to remove local handle scope entry from IRT, ignoring
D/ActivityManager( 1018): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
V/GLSActivity( 1808): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6043): MountEmulatedStorage()
E/Zygote  ( 6043): v2
I/libpersona( 6043): KNOX_SDCARD checking this for 10012
I/libpersona( 6043): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6043 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
I/SELinux ( 6043): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6043): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6043): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
D/OpenGLRenderer( 5970): Render dirty regions requested: true
I/System.out( 5499): Thread-947(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 5499): Thread-947(ApacheHTTPLog):isShipBuild true
D/TimaKeyStoreProvider( 6043): TimaSignature is unavailable
I/System.out( 5499): Thread-947(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5499): Thread-947(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
D/ActivityThread( 6043): Added TimaKeyStore provider
D/ActivityManager( 1018): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1018): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1018): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1018): handleActiveUserChange for user 0
D/PersonaManagerService( 1018): getPersonasForUser(): returning null!
I/ActivityManager( 1018): Killing 5461:com.sec.knox.foldercontainer/1000 (adj 15): empty #31
V/ActivityThread( 5970): updateVisibility : ActivityRecord{33b84d3a token=android.os.BinderProxy@14d5d15c {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
D/PhoneWindow( 5970): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 5970): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  257): id=13 createSurf (1x1),1 flag=404, NainActivit
W/ResourcesManager( 6043): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6043): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/InputDispatcher( 1018): Focus entered window: 5970
D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
D/SRIB_DCS( 5970): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 5970): Initialized EGL, version 1.4
D/OpenGLRenderer( 5970): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 5970): Enabling debug mode 0
I/MultiDex( 6043): VM with version 2.1.0 has multidex support
I/MultiDex( 6043): install
I/MultiDex( 6043): VM has multidex support, MultiDex support library is disabled.
D/ActivityManager( 1018): startService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.apps.docs
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.apps.docs/com.google.android.apps.docs.sync.syncadapter.ContentSyncService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.apps.docs
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_5461/cgroup.procs: No such file or directory
V/JNIHelp ( 6043): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/InputMethodManagerService( 1018): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
I/StatusBar( 1176): Icon Only
D/PanelView( 1176): There is/are notification(s) 
W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
E/Zygote  ( 6070): MountEmulatedStorage()
E/Zygote  ( 6070): v2
I/libpersona( 6070): KNOX_SDCARD checking this for 10100
I/libpersona( 6070): KNOX_SDCARD not a persona
I/SELinux ( 6070): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1018): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=6070 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
W/ActivityThread( 6043): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6043): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1fcb7c66: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6043): Installed default security provider GmsCore_OpenSSL
I/SELinux ( 6070): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6070): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/GAV2    ( 5787): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/ActivityManager( 1018): Displayed Component not be shown by security: +934ms (total +1s38ms)
W/ActivityManager( 1018): mDVFSHelper.release()
I/Timeline( 1018): Timeline: Activity_windows_visible id: ActivityRecord{2a068cc u0 com.test.thalitest/.MainActivity t2} time:80871
I/SurfaceFlinger(  257): id=12 Removed uhalitest (7/9)
W/IInputConnectionWrapper( 5970): showStatusIcon on inactive InputConnection
I/Timeline( 5970): Timeline: Activity_idle id: android.os.BinderProxy@14d5d15c time:80887
I/SamsungIME( 1790): getCurrentCandidateView
D/TimaKeyStoreProvider( 6070): TimaSignature is unavailable
D/ActivityThread( 6070): Added TimaKeyStore provider
,D/ChimeraCfgMgr( 6043): Reading stored module config
,W/BindingManager( 5970): Cannot call determinedVisibility() - never saw a connection for the pid: 5970
,D/PackageIntentReceiver( 6070): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 6070): Not GearManger package! 
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6094): MountEmulatedStorage()
E/Zygote  ( 6094): v2
I/libpersona( 6094): KNOX_SDCARD checking this for 1000
I/libpersona( 6094): KNOX_SDCARD not a persona
,I/SELinux ( 6094): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 6094): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1018): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=6094 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/SELinux ( 6094): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/Mms/MmsApp( 5678):  start initViewCache mms
D/Mms/ComposeMessageFragment( 5678): [start]    fillCache consume time = 1805.110103
D/Mms/ComposeMessageFragment( 5678): fillCache, easy = false
,D/ChimeraCfgMgr( 6043): Loading module com.google.android.gms.car from APK com.google.android.gms
,I/qtaguid ( 5499): Untagging socket 44
I/qtaguid ( 5499): Failed write_ctrl(u 44) res=-1 errno=22
I/qtaguid ( 5499): Untagging socket 44 failed errno=-22
W/NetworkManagementSocketTagger( 5499): untagSocket(44) failed with errno -22
I/System.out( 5499): Thread-947 calls detatch()
D/TimaKeyStoreProvider( 6094): TimaSignature is unavailable
D/ActivityThread( 6094): Added TimaKeyStore provider
,I/art     (  313): Explicit concurrent mark sweep GC freed 8701(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 640us total 59.205ms
,I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 618us total 18.353ms
,I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 636us total 18.590ms
,D/SamsungIME( 1790): Dismiss ExpandCandiate
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6114): MountEmulatedStorage(),
E/Zygote  ( 6114): v2,
I/libpersona( 6114): KNOX_SDCARD checking this for 1000,
I/libpersona( 6114): KNOX_SDCARD not a persona
,I/SELinux ( 6114): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 6114): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 6114): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=6114 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1018): Killing 5477:com.google.android.apps.plus/u0a120 (adj 15): empty #31
,D/ActivityManager( 1018): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/AbsListView( 5678): Get MotionRecognitionManager
,D/MotionRecognitionService( 1018):  ssp status : false
,V/GLSActivity( 1808): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Mms/ComposeMessageFragment( 5678): [end]    fillCache consume time = 183.303229
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,W/GAV2    ( 5787): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,I/ActivityManager( 1018): Killing 5114:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
D/JsMessageQueue( 5970): Set native->JS mode to OnlineEventsBridgeMode
,D/TimaKeyStoreProvider( 6114): TimaSignature is unavailable
,D/ActivityThread( 6114): Added TimaKeyStore provider
,W/AccountFeatureHelper( 5787): Write apps_features disabled false
,D/NativeLibraryUtils( 6043): Install completed successfully. count=14 extracted=0
,D/ChimeraCfgMgr( 1986): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1986): Module APK com.google.android.play.games already loaded
,D/CAR.SERVICE( 6043): Connecting to CarCallService...
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.car.CarCallService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/jxcore_app_log( 5970): JniHelper::setJavaVM(0xb8088450), pthread_self() = -1201819256
D/JX-Cordova( 5970): jxcore cordova android initializing
,E/Zygote  ( 6136): MountEmulatedStorage()
E/Zygote  ( 6136): v2
,I/libpersona( 6136): KNOX_SDCARD checking this for 10120
I/libpersona( 6136): KNOX_SDCARD not a persona
I/art     ( 6043): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 6043): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/SELinux ( 6136): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6136): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6136): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6136 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1018): Killing 4961:com.sec.android.app.music:service/u0a40 (adj 15): empty #31
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/CAR.SERVICE( 6043): com.google.android.projection.gearhead isn't installed.
,I/ActivityManager( 1018): Killing 4453:com.google.android.music:main/u0a111 (adj 15): empty #31
,D/TimaKeyStoreProvider( 6136): TimaSignature is unavailable
,D/ActivityThread( 6136): Added TimaKeyStore provider
,D/AcmsPackageEventListener( 6114): Received: android.intent.action.PACKAGE_ADDED
,W/ContextImpl( 6114): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,D/CAR.TEL.Service( 6043): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 6043): Creating a new PhoneAdapter instance
,D/ActivityManager( 1018): startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
,W/libprocessgroup( 1018): failed to open /acct/uid_10120/pid_5477/cgroup.procs: No such file or directory
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: local_bind
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.car.InCallServiceImpl; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 6043): setListener: com.google.android.gms.car.dn@2cae66d
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: local_bind
D/AcmsService( 6114): Enter Oncreate
,D/AcmsServiceMonitor( 6114): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsService( 6114): creating AcmsCore
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.car.InCallServiceImpl; callingUser = 0; userId(target) = 0
D/AcmsCore( 6114): AcmsCore.getAcmsCore() - Enter
D/AcmsCore( 6114): AcmsCore
,W/ActivityManager( 1018): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 6043): Returning an existing PhoneAdapter instance.
,D/CAR.TEL.Service( 6043): Starting CarCallService with initial phone null
,W/libprocessgroup( 1018): failed to open /acct/uid_10150/pid_5114/cgroup.procs: No such file or directory
,W/ResourcesManager( 6136): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/AcmsCore( 6114): init
D/AcmsCore( 6114): Looper handler is not null
D/AcmsCore( 6114): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 6114): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6114): Incrementing - Counter value: 1
D/AcmsCore( 6114): Incremented Counter Value: postToAcmsCoreHandler =>1
,D/AcmsService( 6114): onStartCommand
D/AcmsService( 6114): Action: android.intent.action.PACKAGE_ADDED
D/AcmsServiceMonitor( 6114): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor( 6114): Incrementing - Counter value: 2
D/AcmsService( 6114): Incremented Counter Value : onStartCommand
,D/AcmsCertificateMngr( 6114): AcmsCertificateMngr
,D/ActivityManager( 1018): getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
,D/AcmsRevocationMngr( 6114): AcmsRevocationMngr
D/ActivityThread( 6114): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,W/art     ( 1986): Suspending all threads took: 134.677ms
,D/CAR.SERVICE( 6043): Package validated; name: com.android.vending,
,D/AcmsService( 6114): Inside handle Intent
,D/AcmsService( 6114): App added - package name: com.test.thalitest
,D/AcmsCore( 6114): Post to AcmsCoreHandler
,D/AcmsServiceMonitor( 6114): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
,D/AcmsServiceMonitor( 6114): Incrementing - Counter value: 3
,D/AcmsCore( 6114): Incremented Counter Value: postToAcmsCoreHandler =>2
D/AcmsService( 6114): Decremented Counter Value : handleStartIntent
,D/AcmsServiceMonitor( 6114): Decrementing - Counter value: 2
,V/Finsky  ( 5499): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,D/Mms/BubbleViewCache( 5678): fillCache bubble = 1
,I/SamsungIME( 1790): getDebugLevel  : 0x4f4c
E/libprocessgroup( 1018): failed to kill 1 processes for processgroup 4453
W/libprocessgroup( 1018): failed to open /acct/uid_10040/pid_4961/cgroup.procs: No such file or directory
,I/SamsungIME( 1790): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1790): KeybaordView init() : load resources
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/SamsungIME( 1790): getCurrentKeyboard
I/SamsungIME( 1790): getTextKeyboard
,D/SamsungIME( 1790): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,I/DBG_POLICYDM( 5754): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 5754): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 5754): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/splitIntent( 1018): Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.android.widgetapp.activeapplicationwidget, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/DBG_POLICYDM( 5754): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/property_contexts,
,I/DBG_POLICYDM( 5754): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
E/Zygote  ( 6171): MountEmulatedStorage()
E/Zygote  ( 6171): v2
I/libpersona( 6171): KNOX_SDCARD checking this for 10142
,I/libpersona( 6171): KNOX_SDCARD not a persona
I/SELinux ( 6171): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1018): Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=6171 uid=10142 gids={50142, 9997, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6171): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6171): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/DBG_POLICYDM( 5754): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 5754): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,I/ActivityManager( 1018): Killing 4813:com.sec.android.widgetapp.SPlannerAppWidget/u0a134 (adj 15): empty #31
,D/TimaKeyStoreProvider( 6171): TimaSignature is unavailable
,D/ActivityThread( 6171): Added TimaKeyStore provider
,V/TaskCloserActivity( 6171): TaskCloserActivity enter()
,V/TaskCloserActivity( 6171): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,I/ActivityManager( 1018): Killing 5291:com.android.calendar/u0a135 (adj 15): empty #31
,D/daemonapp( 1325): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1325): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1325): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1325): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1325): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,I/wpa_supplicant( 2079): nl80211: Received scan results (5 BSSes)
,D/WifiP2pService( 1018): InactiveState{ what=147461 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=147461 }
,D/WifiP2pService( 1018): DefaultState{ what=147461 }
,D/daemonapp( 1325): [MSC_Daemon]>>> WDSM:54 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
I/ServiceManager(  330): Waiting for service AtCmdFwd...
,D/comsamsunglog( 1325): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 1325): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,D/comsamsunglog( 1325): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 1325): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1325): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,D/daemonapp( 1325): [MSC_Daemon]>>> WDSM:441 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
D/daemonapp( 1325): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1325): [MSC_Daemon]>>> WDSM:444 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 1325): [MSC_Daemon]>>> WDSM:445 [0:0] [ASO][NUT] = 1451978340000
D/daemonapp( 1325): [MSC_Daemon]>>> WDSM:446 [0:0] [ASO][CT] = 1451956836180
,D/daemonapp( 1325): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1325): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,D/daemonapp( 1325): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1325): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1325): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,D/daemonapp( 1325): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,E/daemonapp( 1325): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,W/libprocessgroup( 1018): failed to open /acct/uid_10135/pid_5291/cgroup.procs: No such file or directory
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,W/libprocessgroup( 1018): failed to open /acct/uid_10134/pid_4813/cgroup.procs: No such file or directory
,D/accuweather( 1728): [KK AccuPhone]>>> WCW:32 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/daemonapp( 1325): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 1
,D/accuweather( 1728): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1728): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,D/accuweather( 1728): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,D/accuweather( 1728): [KK AccuPhone]>>> UIM:312 [0:0]  action:widgetactionWEATHER_SCREEN_OFF
,D/daemonapp( 1325): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1325): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 1728): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
,D/accuweather( 1728): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,D/accuweather( 1728): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1728): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/accuweather( 1728): [KK AccuPhone]>>> WC:30 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/accuweather( 1728): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1018): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
I/splitIntent( 1018): base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
I/splitIntent( 1018): other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
I/splitIntent( 1018): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WearableService( 1808): callingUid 10012, callindPid: 1808
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/MDM     ( 1808): [258] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 1986): Restart initialization of location
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1808): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/GCoreFlp( 1808): No location to return for getLastLocation()
,W/FusedLocationProvider( 1808): location=null
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1808): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.crypto.ChannelBindingStateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SMD     (  290): DCD OFF
,D/SamsungIME( 1790): [SwiftkeyWrapper] currentLangauge : 1701729619
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 38698(2MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 27MB/41MB, paused 2.516ms total 165.750ms
,W/jxcore-log( 5970): Initializing JXcore engine
W/jxcore-log( 5970): JXcore engine is ready
,W/jxcore-log( 5970): Starting JXcore engine
,E/audit   ( 1926): type=1400 msg=audit(1451956836.856:205): avc:  denied  { ioctl } for  pid=5970 comm=".test.thalitest" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,E/audit   ( 1926):  SEPF_SM-A500FU_5.0.2-1_0038
E/audit   ( 1926): type=1300 msg=audit(1451956836.856:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=bef21d58 items=0 ppid=313 ppcomm=main pid=5970 auid=4294967295 uid=10175 gid=10175 euid=10175 suid=10175 fsuid=10175 egid=10175 sgid=10175 fsgid=10175 ses=4294967295 tty=(none) comm=".test.thalitest" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1926): type=1320 msg=audit(1451956836.856:205): 
,W/jxcore-log( 5970): Platform android
W/jxcore-log( 5970): 
,W/jxcore-log( 5970): Process ARCH arm
W/jxcore-log( 5970): 
,D/ActivityManager( 1018): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1808): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/System.out( 5499): Thread-948(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 5499): Thread-948(ApacheHTTPLog):isShipBuild true
I/System.out( 5499): Thread-948(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5499): Thread-948(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 5499): Untagging socket 44
,I/qtaguid ( 5499): Failed write_ctrl(u 44) res=-1 errno=22
,I/qtaguid ( 5499): Untagging socket 44 failed errno=-22
,W/NetworkManagementSocketTagger( 5499): untagSocket(44) failed with errno -22
,I/System.out( 5499): Thread-948 calls detatch()
,W/ResourcesManager( 5499): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5499): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 5499): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,V/AlarmManager( 1018): waitForAlarm result :4
,D/KeyguardViewMediator( 1176): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,D/KeyguardViewMediator( 1176): doKeyguard: not showing because lockscreen is off
,V/KeyguardEffectViewController( 1176): *** Keyguard wallpaper service already unbounded
,D/ActivityManager( 1018): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.wear.WearSupportService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/Finsky  ( 5499): [1] DailyHygiene.access$600: Logging device features
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,V/AlarmManager( 1018): waitForAlarm result :4
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/DeviceConnectionService( 1808): client connected with version: 8296000
,D/Finsky  ( 5499): [969] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/ActivityManager( 1018): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1808): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AcmsKeyStoreHelper( 6114):  getKeyStoreForApplication Enter
,D/Finsky  ( 5499): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 5499): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,I/AcmsKeyStoreHelper( 6114): Key Store exist
I/AcmsKeyStoreHelper( 6114): Hence loading the keystore file
,I/System.out( 5499): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 5499): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 5499): (HTTPLog)-Static: isShipBuild true
I/System.out( 5499): (HTTPLog)-Thread-958-732495464: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 5499): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10028
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10028
,D/AcmsKeyStoreHelper( 6114):  getKeyStoreForApplication Exit
I/jxcore-log( 5970): JXcore Cordova bridge is ready!
I/jxcore-log( 5970): 
I/AcmsCertificateMngr( 6114): getKeyStoreForApplication success 
D/AcmsCore( 6114): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor( 6114): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6114): Decrementing - Counter value: 1
D/AcmsCore( 6114): AcmsCore: ACMS_APP_INSTALLED
W/jxcore-log( 5970): JXcore engine is started
,I/Choreographer( 5970): Skipped 148 frames!  The application may be doing too much work on its main thread.
D/AcmsCore( 6114): This is NOT a valid MirrorLink app
D/AcmsCore( 6114): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor( 6114): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6114): Decrementing - Counter value: 0
D/AcmsServiceMonitor( 6114): Counter value is 0: Stopping ACMS service
,D/AcmsServiceMonitor( 6114): getSvcCounter - Counter value: 0
D/AcmsService( 6114): Enter onDestroy
I/AcmsService( 6114): cleanUp(): inside service clean up
D/AcmsCore( 6114): AcmsCore: inside DeInit
D/AcmsCore( 6114): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr( 6114): AcmsCertificateMngr: inside cleanup
D/AcmsRevocationMngr( 6114): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper( 6114): KeyStoreHelper: inside cleanup
,D/AcmsAppEntryInterface( 6114): AppEntryInterface: Inside CleanUp
,I/chromium( 5970): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/AcmsServiceMonitor( 6114): getSvcCounter - Counter value: 0
D/AcmsService( 6114): killing acms process
I/Process ( 6114): Sending signal. PID: 6114 SIG: 9
,I/System.out( 5499): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/jxcore-log( 5970): Toggling radios to true
I/jxcore-log( 5970): 
,D/BluetoothAdapter( 5970): enable()
,D/BluetoothAdapter( 5970): enable(): BT is already enabled..!
,D/SecContentProvider( 1018): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 1018): uri = 20 selection = isWifiStateChangeAllowed
,D/SecContentProvider2( 1018): mCursor = null
,D/WifiService( 1018): setWifiEnabled: true pid=5970, uid=10175
,W/ActivityManager( 1018): Permission Denial: getCurrentUser() from pid=5970, uid=10175 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 1018): Failed getting userId using ActivityManagerNative
W/WifiService( 1018): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=5970, uid=10175 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 1018): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:24778)
W/WifiService( 1018): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2213)
W/WifiService( 1018): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2201)
W/WifiService( 1018): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 1018): 	at android.os.Binder.execTransact(Binder.java:461)
,D/SettingsProvider( 1018): name = wifi_on
,I/WifiService( 1018): disconnect: pid=5970, uid=10175
,I/wpa_supplicant( 2079): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 5970): Radios toggled
I/jxcore-log( 5970): 
,I/ActivityManager( 1018): Process ACMS.Process (pid 6114)(adj 0) has died(33,1154)
,I/wpa_supplicant( 2079): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 2079): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 2079): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
,I/wpa_supplicant( 2079): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 2079): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/wpa_supplicant( 2079): Cmd 35605 not handled
,E/WifiStateMachine( 1018): WifiStateMachine: Leaving Connected state
,I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 2079): reset timer : RESET_TIMER 0
I/wpa_supplicant( 2079): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 2079): P2P: Current p2p state = IDLE
I/wpa_supplicant( 2079): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 2079): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 2079): First Scan Start
I/wpa_supplicant( 2079): Scan requested (ret=0) - scan timeout 30 seconds
D/Tethering( 1018): InitialState.processMessage what=4
,D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1018): interfaceStatusChanged wlan0, false
,E/WifiConfigStore( 1018): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/Tethering( 1018): No numeric data
D/Tethering( 1018): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering( 1018): clearTetheredNotification()
,I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceStatusChanged wlan0, false
,I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
,V/NetworkStats( 1018): performPollLocked(flags=0x1)
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/HotspotTile( 1176): onReceive : android.net.conn.TETHER_STATE_CHANGED
,D/HotspotTile( 1176): updateTetherState():false, false
,D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1018): UpdateStatsForKnox main else ---
,E/WifiNative-wlan0( 1018): do suspend true
,D/WifiP2pService( 1018): InactiveState{ what=143375 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=143375 }
V/NetworkStats( 1018): performPollLocked() took 9ms
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/CommandListener(  277): Clearing all IP addresses on wlan0
,D/StatusBar.NetworkController( 1176): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
V/NativeCrypto( 1808): Read error: ssl=0xb865fd68: I/O error during system call, Connection timed out
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,V/NativeCrypto( 1808): SSL shutdown failed: ssl=0xb865fd68: I/O error during system call, Broken pipe,
,D/ConnectivityService( 1018): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 1018): updateNetworkInfo()
,D/ConnectivityService( 1018): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,E/ConnectivityService( 1018): updateNetworkInfo()
,D/ConnectivityService( 1018): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
E/WifiStateMachine( 1018): Start Disconnecting Watchdog 1
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,I/wpa_supplicant( 2079): wlan0: Setting scan request: 0 sec 0 usec
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): ValidatedState{ when=0 what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): DefaultState{ when=0 what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Forcing reevaluation
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): EvaluatingState{ when=-1ms what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiTrafficPoller( 1018): evaluateTrafficStatsPolling
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
I/System.out( 1018): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 5499): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 5499): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/qtaguid ( 1018): Tagging socket 358 with tag ffffffff00000000{4294967295,0} for uid 10012, pid: 1018, getuid(): 1000
,I/qtaguid ( 1018): Untagging socket 358
I/System.out( 1018): (HTTPLog)-Static: isSBSettingEnabled false
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.wifi.WifiStateMachine.insertLog:14952 com.android.server.wifi.WifiStateMachine.access$2700:217 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:6951 com.android.internal.util.StateMachine$SmHandler.processMsg:966 
,E/WifiNative-wlan0( 1018): do suspend true
D/ActivityManager( 1018): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
D/StatusBar.NetworkController( 1176): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
D/WifiP2pService( 1018): InactiveState{ what=143375 }
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/WifiP2pService( 1018): P2pEnabledState{ what=143375 }
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3575): Starting #8,
,I/Hs20UtilService( 3575): Message received 5007
,D/CommandListener(  277): Clearing all IP addresses on wlan0
,D/EnterpriseController(  277): uids 1000
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 1000
,D/ConnectivityService( 1018): setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
D/ConnectivityService( 1018): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Validated
D/ConnectivityManager.CallbackHandler( 1176): CM callback handler got msg 524292
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
D/ConnectivityManager.CallbackHandler( 1986): CM callback handler got msg 524292
,V/NearbySettings( 1304): DMSUtil.isNetworkConnected - flag-null, state-null
D/EntConnectivity( 1018): Not allowed due to - mEnabled false - primarySimSlot false
,D/ConnectivityService( 1018): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/StatusBar.NetworkController( 1176): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:null
D/WIFI_P2P( 1018): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/CSLegacyTypeTracker( 1018): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,fe80::7ef9:eff:fe37:96ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/CSLegacyTypeTracker( 1018): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/ConnectivityService( 1018): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/TelephonyNetworkFactory( 1466): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/TelephonyNetworkFactory( 1466): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1304): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1304): MountReceiver.onReceive - Set preference state off
,I/WifiTrafficPoller( 1018): evaluateTrafficStatsPolling
,V/NearbySettings( 1304): MountReceiver.mPrefHandler - 7002
,D/StatusBar.NetworkController( 1176): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/Tethering( 1018): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/ConnectivityService( 1018): nai.networkMonitor.doQuit()
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): doQuit - quitNow()
,D/Tethering( 1018): MasterInitialState.processMessage what=3
,D/WifiNetworkAgent( 1018): NetworkAgent: NetworkAgent channel lost
,V/NetworkStats( 1018): updateIfacesLocked()
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
V/NetworkStats( 1018): performPollLocked(flags=0x1)
,D/EntConnectivity( 1018): Not allowed due to - mEnabled false - primarySimSlot false
,D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
,D/StatusBar.NetworkController( 1176): EthernetConnected: false
D/StatusBar.NetworkController( 1176): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1176): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1176): updateDataNetType()
D/StatusBar.NetworkController( 1176): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1176): updateLTEICONDataNetType:0
,D/NetworkStatsFactory( 1018): UpdateStatsForKnox main else ---
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/WIFI    ( 1018): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1018): mCursor = null
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
V/NetworkStats( 1018): performPollLocked() took 9ms
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
V/NetworkStats( 1018): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/StatusBar.NetworkController( 1176): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1176): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1176): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1176): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/ActivityManager( 1018): Killing 5349:com.samsung.aasaservice/1000 (adj 15): empty #31
,I/ActivityManager( 1018): Killing 5132:com.google.android.gm/u0a101 (adj 15): empty #32
,D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1018): mCursor = null
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6205): MountEmulatedStorage(),
E/Zygote  ( 6205): v2
,I/libpersona( 6205): KNOX_SDCARD checking this for 10104
I/libpersona( 6205): KNOX_SDCARD not a persona
,I/SELinux ( 6205): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1018): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6205 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/SELinux ( 6205): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6205): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 6205): TimaSignature is unavailable,
D/ActivityThread( 6205): Added TimaKeyStore provider
,W/ResourcesManager( 6205): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/PhoneApp( 1466): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1466): FileWriteThread : threadType = 3
,D/PhoneApp( 1466): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1466): FileWriteThread : threadType = 3
,D/PhoneApp( 1466): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1466): FileWriteThread : threadType = 3
,D/PhoneApp( 1466): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1466): FileWriteThread : threadType = 3
,D/PhoneApp( 1466): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1466): FileWriteThread : threadType = 3
,D/PhoneApp( 1466): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1466): FileWriteThread : threadType = 3
,D/PhoneApp( 1466): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1466): FileWriteThread : threadType = 3
,D/PhoneApp( 1466): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1466): FileWriteThread : threadType = 3
,D/PhoneApp( 1466): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_5349/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10101/pid_5132/cgroup.procs: No such file or directory
,D/FileWriteThread_Telephony( 1466): FileWriteThread : threadType = 3
,D/PhoneApp( 1466): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1466): FileWriteThread : threadType = 3,
D/PhoneApp( 1466): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1466): FileWriteThread : threadType = 3
,D/PhoneApp( 1466): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1466): FileWriteThread : threadType = 3
,D/PhoneApp( 1466): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1466): FileWriteThread : threadType = 3
,D/PhoneApp( 1466): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1466): FileWriteThread : threadType = 3
,D/PhoneApp( 1466): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1466): FileWriteThread : threadType = 3
,W/Atfwd_Sendcmd(  330): AtCmdFwd service not published, waiting... retryCnt : 5
,I/Babel   ( 6205): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 6205): MmsConfig.loadMmsSettings
I/Babel   ( 6205): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
I/Babel   ( 6205): MmsConfig.loadFromDatabase
,E/Babel   ( 6205): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 6205): MmsConfig.loadFromResources
,E/Babel   ( 6205): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 6205): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/Settings( 6205): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_StickerModule( 6205): App launched.
,D/ActivityManager( 1018): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3575): Starting #9
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/Hs20UtilService( 3575): Message received 5007
V/NearbySettings( 1304): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1304): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1304): MountReceiver.mPrefHandler - 7002
,I/PowerManagerService( 1018): [PWL] Off : 5s ago
,I/PowerManagerService( 1018): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService( 1018): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService( 1018): [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1018, ws=null) (elapsedTime=382)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/QCamera2Factory(  282): getCameraInfo: E, camera_id = 0
,W/QCamera2Factory(  282): getCameraInfo: X
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/QCamera2Factory(  282): getCameraInfo: E, camera_id = 1
,W/QCamera2Factory(  282): getCameraInfo: X
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
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/VideoCapabilities( 6205): Unrecognized profile 2130706433 for video/avc
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/AudioCapabilities( 6205): Unsupported mime audio/evrc
,W/AudioCapabilities( 6205): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6205): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 6205): Unsupported mime audio/mpeg-L2
,W/AudioCapabilities( 6205): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 6205): Unsupported mime audio/x-ima
,W/AudioCapabilities( 6205): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6205): Unsupported mime audio/evrc
,W/VideoCapabilities( 6205): Unsupported mime video/wvc1
,W/VideoCapabilities( 6205): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 6205): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities( 6205): Unsupported mime video/wvc1
,W/VideoCapabilities( 6205): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 6205): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities( 6205): Unsupported mime video/x-ms-wmv8
,W/VideoCapabilities( 6205): Unsupported mime video/mp43
,W/VideoCapabilities( 6205): Unsupported mime video/sorenson
,D/ConnectivityService( 1018): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,W/VideoCapabilities( 6205): Unsupported mime video/mp4v-esdp
,I/ApplicationPolicy( 1018): updateDataUsageMap
,D/GpsLocationProvider( 1018): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_DM  ( 3072): [com.wssyncmldm.XDMService(936/lIllIlllIIllllIlIlIl)] WiFi network Connected : false
,I/DBG_DM  ( 3072): [com.wssyncmldm.XDMService(952/llIlIllllllllllllllI)] Bluetooth Data Connected : false
,I/PCWCLIENTTRACE_PushUtil( 5701): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5701): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 5701): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5701): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1018): Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=17, mSplitNum[2]=25, mBgSplitQueueNum=3 divideNum= 8 r.nextReceiver= 1 receivers.size=33
,I/splitIntent( 1018): finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.google.android.music, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/VideoCapabilities( 6205): Unsupported profile 4 for video/mp4v-es
,E/Zygote  ( 6246): MountEmulatedStorage(),
I/ActivityManager( 1018): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6246 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 6246): v2
I/libpersona( 6246): KNOX_SDCARD checking this for 10111
I/libpersona( 6246): KNOX_SDCARD not a persona
,I/SELinux ( 6246): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/PCWCLIENTTRACE_SYSTEMReceiver( 5701): noConnectivity : true
,I/SELinux ( 6246): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6246): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6254): MountEmulatedStorage()
,I/libpersona( 6254): KNOX_SDCARD checking this for 10009
E/Zygote  ( 6254): v2
I/libpersona( 6254): KNOX_SDCARD not a persona
I/SELinux ( 6254): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6254): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6254): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6254 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 6246): TimaSignature is unavailable
,D/accuweather( 1728): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
D/ActivityThread( 6246): Added TimaKeyStore provider
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6273): MountEmulatedStorage()
I/libpersona( 6273): KNOX_SDCARD checking this for 10145
E/Zygote  ( 6273): v2
I/libpersona( 6273): KNOX_SDCARD not a persona
I/SELinux ( 6273): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6273): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6273): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=6273 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 6254): TimaSignature is unavailable
,D/ActivityThread( 6254): Added TimaKeyStore provider
,D/daemonapp( 1325): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
,D/accuweather( 1728): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/TimaKeyStoreProvider( 6273): TimaSignature is unavailable
,D/ActivityThread( 6273): Added TimaKeyStore provider
,D/accuweather( 1728): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,D/accuweather( 1728): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,D/accuweather( 1728): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1728): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1728): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 6273): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 6273): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6273): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 6273): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6273): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/ActivityManager( 1018): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6292 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 6292): MountEmulatedStorage()
E/Zygote  ( 6292): v2
,I/libpersona( 6292): KNOX_SDCARD checking this for 10081,
,I/libpersona( 6292): KNOX_SDCARD not a persona
,I/SELinux ( 6292): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 6292): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 6292): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 6292): TimaSignature is unavailable
,D/ActivityThread( 6292): Added TimaKeyStore provider
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/ActivityManager( 1018): Killing 4978:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
,I/ActivityManager( 1018): Killing 5665:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
,I/KLMS-2.5.183: ( 3621): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Jan 05 02:20:38 GMT+01:00 2016
,D/ActivityManager( 1018): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.183: ( 3621): KLMSAbstractReciever(): onReceive().END.
,I/wpa_supplicant( 2079): nl80211: Received scan results (8 BSSes)
,I/wpa_supplicant( 2079): wlan0: Setting scan request: 8 sec 0 usec
,I/wpa_supplicant( 2079): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 2079): Trying to associate with  'G700'
I/wpa_supplicant( 2079): Re-associate with C0.AA.48
I/wpa_supplicant( 2079): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 2079): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
D/WifiMonitor( 1018): didn't find BSSID Trying to associate with SSID 'NG700'
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.183: ( 3621): KLMSIntentService(): onCreate()
,I/KLMS-2.5.183: ( 3621): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.183: ( 3621): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,I/KLMS-2.5.183: ( 3621): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.183: ( 3621): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.5.183: ( 3621): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,I/KLMS-2.5.183: ( 3621): StateImplV2(): networkChangeListener().END
,E/Zygote  ( 6313): MountEmulatedStorage()
,E/Zygote  ( 6313): v2
I/libpersona( 6313): KNOX_SDCARD checking this for 10034
,I/libpersona( 6313): KNOX_SDCARD not a persona
,I/ActivityManager( 1018): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6313 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 6313): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/KLMS-2.5.183: ( 3621): KLMSIntentService(): onDestroy(),
,I/SELinux ( 6313): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,E/SELinux ( 6313): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1018): mCursor = null
,D/TimaKeyStoreProvider( 6313): TimaSignature is unavailable
,D/ActivityThread( 6313): Added TimaKeyStore provider
,I/MusicStore( 6246): Database version: 108,
,I/SO_AGENT( 6313): [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available,
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6338): MountEmulatedStorage()
E/Zygote  ( 6338): v2
I/libpersona( 6338): KNOX_SDCARD checking this for 10113
I/libpersona( 6338): KNOX_SDCARD not a persona
,I/SELinux ( 6338): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1018): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6338 uid=10113 gids={50113, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1018): Killing 5389:com.google.android.partnersetup/u0a15 (adj 15): empty #31,
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/SELinux ( 6338): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6338): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/DBG_POLICYDM( 5754): [com.policydm.XDMApplication(503/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,I/DBG_POLICYDM( 5754): [com.policydm.XDMApplication(513/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,E/DBG_POLICYDM( 5754): [com.policydm.XDMBroadcastReceiver$2(109/run)] network is unserviceable
,E/DBG_POLICYDM( 5754): [com.policydm.XDMApplication(477/isNetworkChanged)] network not changed.... 
,E/SPPClientService( 5821): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,D/TimaKeyStoreProvider( 6338): TimaSignature is unavailable
,I/SA      ( 5995): [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
,I/SA      ( 5995): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      ( 5995): [OR] == ACTION_CONNECTIVITY_CHANGE ==
D/ActivityManager( 1018): startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
D/ActivityThread( 6338): Added TimaKeyStore provider
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,I/SA      ( 5995): [SLFUCHKMGR] constructor called
,W/libprocessgroup( 1018): failed to open /acct/uid_10044/pid_4978/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10152/pid_5665/cgroup.procs: No such file or directory
,E/SPPClientService( 5821): [[SystemStateMonitorService]] No Active Internet
,I/SA      ( 5995): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 5995): [OR] == isSIMCardReady false ==
,I/SA      ( 5995): [SCU] == networkStateCheck == false
,I/SA      ( 5995): [OR] onReceive END
,V/DownloadManager( 1231): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,E/wpa_supplicant( 2079): Cmd 35605 not handled
,I/wpa_supplicant( 2079): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 2079): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 2079): Associated with C0.AA.48
,I/wpa_supplicant( 2079): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 2079): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 2079): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1018): interfaceStatusChanged wlan0, false
,I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1018): interfaceStatusChanged wlan0, false
,D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1018): mCursor = null
,I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
,D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1018): mCursor = null
,D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1018): interfaceStatusChanged wlan0, false
,I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1018): interfaceLinkStateChanged wlan0, true
,D/Tethering( 1018): interfaceStatusChanged wlan0, true
,I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, true
,E/Tethering( 1018): No numeric data
,D/Tethering( 1018): sendTetherStateChangedBroadcast 1, 0, 0
,D/Tethering( 1018): clearTetheredNotification()
,I/wpa_supplicant( 2079): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 2079): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 2079): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 2079): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,D/HotspotTile( 1176): onReceive : android.net.conn.TETHER_STATE_CHANGED
I/wpa_supplicant( 2079): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2079): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2079): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 2079): Blacklist: Clear (temp) 
I/wpa_supplicant( 2079): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 1018): interfaceLinkStateChanged wlan0, true
D/Tethering( 1018): interfaceStatusChanged wlan0, true
I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, true
D/HotspotTile( 1176): updateTetherState():false, false
,V/NetworkStats( 1018): performPollLocked(flags=0x1)
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1018): UpdateStatsForKnox main else ---
,V/NetworkStats( 1018): performPollLocked() took 6ms
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,I/ActivityManager( 1018): Killing 5654:com.samsung.android.sm/1000 (adj 15): empty #31
,D/WifiNative-wlan0( 1018): callSECApiVoid - ID [50]
,E/WifiConfigStore( 1018): setLastSelectedConfiguration -1
,D/StatusBar.NetworkController( 1176): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1018): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService( 1018): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService( 1018): updateNetworkInfo()
D/ConnectivityService( 1018): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,E/WifiConfigStore( 1018): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/BadgeProvider( 5877): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/BadgeProvider( 5877): sendNotify entered. [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 5877): sendNotify, [notify] : null
,D/BadgeProvider( 5877): update, [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 5877): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 5877): update, [UpdateCount] : 1
,D/Launcher.Model( 1482): reloadBadges entered.
,E/WifiConfigStore( 1018): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 6246): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6246): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/Zygote  ( 6362): MountEmulatedStorage(),
I/libpersona( 6362): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6362): v2
I/libpersona( 6362): KNOX_SDCARD not a persona,
I/SELinux ( 6362): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1018): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6362 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 6362): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6362): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/CommandListener(  277): Setting iface cfg,
,E/WifiStateMachine( 1018): Start Dhcp Watchdog 2,
,D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled,
D/SecContentProvider2( 1018): mCursor = null
,I/art     (  313): Explicit concurrent mark sweep GC freed 8705(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 644us total 30.091ms,
,D/TimaKeyStoreProvider( 6362): TimaSignature is unavailable,
D/ActivityThread( 6362): Added TimaKeyStore provider,
,I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 631us total 21.109ms,
,E/WifiNative-wlan0( 1018): do suspend false,
,D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled,
D/SecContentProvider2( 1018): mCursor = null
,D/WifiP2pService( 1018): InactiveState{ what=143375 },
D/WifiP2pService( 1018): P2pEnabledState{ what=143375 },
W/libprocessgroup( 1018): failed to open /acct/uid_10015/pid_5389/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_5654/cgroup.procs: No such file or directory
,I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 623us total 23.899ms,
,V/JNIHelp ( 6246): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/SecurityLogAgent( 6362): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 6362): KnoxConfiguration : Current State Mapping Found 
,D/SecurityLogAgent( 6362): StateMachine : Current State = 1
,D/SecurityLogAgent( 6362): StateMachine : Changed Current State = 1
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6379): MountEmulatedStorage(),
E/Zygote  ( 6379): v2
I/libpersona( 6379): KNOX_SDCARD checking this for 10159
,I/libpersona( 6379): KNOX_SDCARD not a persona
,I/SELinux ( 6379): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 6379): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,I/ActivityManager( 1018): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=6379 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,E/SELinux ( 6379): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL,
I/ActivityManager( 1018): Killing 5717:com.sec.android.widgetapp.tapandpay/u0a156 (adj 15): empty #31
,D/TimaKeyStoreProvider( 6379): TimaSignature is unavailable
,D/ActivityThread( 6379): Added TimaKeyStore provider
,W/ActivityThread( 6246): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6246): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1a19e2f9: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6246): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6246): GMSCore installation verified
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/ConfigStore( 6246): Config Database version: 1
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.gms
,I/iu.Environment( 1986): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/iu.UploadsManager( 1986): num queued entries: 0
,I/iu.UploadsManager( 1986): num updated entries: 0
,I/iu.SyncManager( 1986): NEXT; no task
,W/libprocessgroup( 1018): failed to open /acct/uid_10156/pid_5717/cgroup.procs: No such file or directory
,E/dhcpcd  ( 6398): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 6398): version 5.5.6 starting
,E/dhcpcd  ( 6398): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/,
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6246): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0,
,W/ContextImpl( 6246): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/,
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6246): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music,
W/ActivityManager( 1018): userId = 0, bbcId = -10000,
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.StorageMigrationService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
I/ActivityManager( 1018): Killing 5099:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main,
,I/dhcpcd  ( 6398): wlan0: sending IPv6 Router Solicitation,
E/dhcpcd  ( 6398): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 6398): if(wlan0) info get Success. (MAC : C0.AA.48),
I/dhcpcd  ( 6398): bssid match
I/dhcpcd  ( 6398): wlan0: rebinding lease of 192.168.1.129,
,E/SMD     (  290): DCD OFF,
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.artwork.ArtDownloadService2; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 1018): getStreamVolume 3 index 0
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6338): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
I/MediaRouter( 6246): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6338): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,V/MusicLeanback( 6246): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_5099/cgroup.procs: No such file or directory
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ContextImpl( 6338): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.ArtDownloadQueueService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6338): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.ArtCacheService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/ActivityManager( 1018): Killing 5410:com.samsung.android.app.galaxyfinder/u0a32 (adj 15): empty #31
,D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6416): MountEmulatedStorage()
,I/libpersona( 6416): KNOX_SDCARD checking this for 10002
E/Zygote  ( 6416): v2
I/libpersona( 6416): KNOX_SDCARD not a persona
,I/SELinux ( 6416): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1018): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6416 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6416): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6416): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,D/TimaKeyStoreProvider( 6416): TimaSignature is unavailable
,D/ActivityThread( 6416): Added TimaKeyStore provider
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 6246): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6246): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GHttpClientFactory( 6246): Using the GMSCore's GoogleHttpClient
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/libprocessgroup( 1018): failed to open /acct/uid_10032/pid_5410/cgroup.procs: No such file or directory
,I/ActivityManager( 1018): Killing 5737:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6448): MountEmulatedStorage(),
I/libpersona( 6448): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6448): v2
I/libpersona( 6448): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6448 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 6448): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6448): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6448): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6448): TimaSignature is unavailable
D/ActivityThread( 6448): Added TimaKeyStore provider
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_5737/cgroup.procs: No such file or directory
,I/WebViewFactory( 6338): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,I/LibraryLoader( 6338): Time to load native libraries: 2 ms (timestamps 6027-6029)
I/LibraryLoader( 6338): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6338): Binding Chromium to main looper Looper (main, tid 1) {521cb16}
,I/LibraryLoader( 6338): Expected native library version number "",actual native library version number ""
,I/chromium( 6338): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/DIAGMON_AGENT( 6448): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 242, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 1018): stay LED for fully charged
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1421): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,I/BrowserStartupController( 6338): Initializing chromium process, singleProcess=true
V/EmergencyMode( 1421): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,W/art     ( 6338): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6338): ApplicationContext is null in ApplicationStatus
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/chromium( 6338): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,I/chromium( 6338): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=50556 len=3379
,I/chromium( 6338): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:45 off:7638088 len:1165478
,I/Adreno-EGL( 6338): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6338): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6338): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6338): Local Branch: 
I/Adreno-EGL( 6338): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6338): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6338):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,W/AudioManagerAndroid( 6338): Requires BLUETOOTH permission
,I/DIAGMON_AGENT( 6448): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/NSApplication( 6338): Starting up...
,I/DIAGMON_AGENT( 6448): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 6448): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 6448): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6448): ./extraInfo: <unknown ssid>
,W/DIAGMON_AGENT( 6448): [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,I/ActivityManager( 1018): Killing 5445:com.sec.knox.bridge/1000 (adj 15): empty #31
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6482): MountEmulatedStorage()
,I/libpersona( 6482): KNOX_SDCARD checking this for 10125
E/Zygote  ( 6482): v2
I/libpersona( 6482): KNOX_SDCARD not a persona
I/SELinux ( 6482): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1018): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6482 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 5678:com.android.mms/u0a46 (adj 15): empty #31
,I/SELinux ( 6482): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6482): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/dhcpcd  ( 6398): wlan0: acknowledged 192.168.1.129 from 192.168.1.1
,D/TimaKeyStoreProvider( 6482): TimaSignature is unavailable
,D/ActivityThread( 6482): Added TimaKeyStore provider
,W/ResourcesManager( 6482): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6482): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 6482): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect( 6482): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 6482): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 6482): PeriphStartReceiver.onReceive - no need to start
,I/splitIntent( 1018): Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1018): Killing 5898:com.sec.android.app.myfiles/u0a47 (adj 15): empty #31
,I/dhcpcd  ( 6398): wlan0: leased 192.168.1.129 for 86400 seconds
,D/ActivityManager( 1018): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3575): Starting #10
I/Hs20UtilService( 3575): Message received 5007
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE,
V/NearbySettings( 1304): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - P2P: IDLE,
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1304): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1304): MountReceiver.mPrefHandler - 7002
,D/CountryDetector( 1018): No listener is left,
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_5445/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_10046/pid_5678/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_10047/pid_5898/cgroup.procs: No such file or directory
,E/WifiNative-wlan0( 1018): do suspend true
,D/WifiP2pService( 1018): InactiveState{ what=143375 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1176): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/WifiStateMachine( 1018): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,E/WifiStateMachine( 1018): VerifyingLinkState enter
,D/WifiNative-wlan0( 1018): callSECApiInt - ID [210]
,E/ConnectivityService( 1018): updateNetworkInfo()
,D/ConnectivityService( 1018): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,D/ConnectivityService( 1018): Adding iface wlan0 to network 503
,D/WifiWatchdogStateMachine( 1018): updateDnsLinkProperty: enter,
D/WifiWatchdogStateMachine.DnsPinger( 1018): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.DnsResolver( 1018): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.SingDnsChecker( 1018): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 1018): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/StatusBar.NetworkController( 1176): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/ConnectivityService( 1018): Adding Route [fe80::/64 -> :: wlan0] to network 503
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false),
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/ConnectivityService( 1018): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/ConnectivityService( 1018): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 503
,E/ConnectivityService( 1018): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1018): Setting Dns servers for network 503 to [/192.168.1.1]
D/ConnectivityService( 1018): LTETest block dns file not exists
,D/ConnectivityService( 1018): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,E/WifiStateMachine( 1018): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/ActivityManager( 1018): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,E/ConnectivityService( 1018): updateNetworkInfo()
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3575): Starting #11
,E/ConnectivityService( 1018): updateNetworkInfo()
D/ConnectivityService( 1018): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,I/WifiTrafficPoller( 1018): evaluateTrafficStatsPolling
D/ConnectivityService( 1018): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1018): rematching NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Checking http://connectivitycheck.android.com/generate_204 on "NG700"
I/Hs20UtilService( 3575): Message received 5007
,I/System.out( 1018): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 1000
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/ConnectivityService( 1018):    accepting network in place of null
D/Netd    (  277): getNetworkForDns: using netid 503 for uid 1000
D/WIFI_P2P( 1018): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,D/TelephonyNetworkFactory( 1466): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
E/CSLegacyTypeTracker( 1018): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1018): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
,D/ConnectivityService( 1018): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/TelephonyNetworkFactory( 1466): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/StatusBar.NetworkController( 1176): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:null,
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1018): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/Tethering( 1018): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/ConnectivityService( 1018): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,D/Tethering( 1018): MasterInitialState.processMessage what=3
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
V/NetworkStats( 1018): updateIfacesLocked()
V/NetworkStats( 1018): performPollLocked(flags=0x1)
,D/ConnectivityManager.CallbackHandler( 1176): CM callback handler got msg 524290
,D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1018): UpdateStatsForKnox main else ---
,D/StatusBar.NetworkController( 1176): EthernetConnected: false
,D/StatusBar.NetworkController( 1176): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1176): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1176): updateDataNetType()
D/StatusBar.NetworkController( 1176): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1176): updateLTEICONDataNetType:0
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
V/NetworkStats( 1018): performPollLocked() took 4ms
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1176): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
V/NetworkStats( 1018): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/StatusBar.NetworkController( 1176): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1176): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1176): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityManager.CallbackHandler( 1986): CM callback handler got msg 524290
,I/NearbySettings( 1304): MountReceiver.onReceive - Keep current state
,D/CAR.SERVICE( 6043): mConnectedToCar = false, abort
,D/WIFI    ( 1018): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
I/WifiTrafficPoller( 1018): evaluateTrafficStatsPolling
,I/WifiTrafficPoller( 1018): mBoosterFLAG : 0
I/WifiTrafficPoller( 1018): current booster mode : FullMode
,E/ActivityThread( 6043): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@398cb5b5 that was originally bound here
E/ActivityThread( 6043): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@398cb5b5 that was originally bound here
E/ActivityThread( 6043): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 6043): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 6043): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 6043): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 6043): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 6043): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 6043): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 6043): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6043): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6043): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 6043): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 6043): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 6043): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 6043): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3280)
E/ActivityThread( 6043): 	at android.app.ActivityThread.access$1900(ActivityThread.java:181)
E/ActivityThread( 6043): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1565)
E/ActivityThread( 6043): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6043): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 6043): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/ActivityThread( 6043): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6043): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6043): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 6043): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/WifiNative-wlan0( 1018): callSECApiVoid - ID [212]
,D/StatusBar.NetworkController( 1176): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/ActivityThread( 6043): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@32cf9e84 that was originally bound here
E/ActivityThread( 6043): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@32cf9e84 that was originally bound here
E/ActivityThread( 6043): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 6043): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 6043): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 6043): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 6043): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 6043): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6043): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6043): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 6043): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 6043): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 6043): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 6043): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 6043): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:3312)
E/ActivityThread( 6043): 	at android.app.ActivityThread.access$2000(ActivityThread.java:181)
E/ActivityThread( 6043): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1570)
E/ActivityThread( 6043): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6043): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 6043): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/ActivityThread( 6043): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6043): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6043): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 6043): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/System.out( 1018): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 05 Jan 2016 01:20:40 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1451956840738], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1451956840715]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Don't send network conditions - lacking user consent.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Validated
,D/ConnectivityService( 1018): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1018): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1018): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 1018): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService( 1018): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1176): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1986): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 1176): EthernetConnected: false
,D/StatusBar.NetworkController( 1176): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1176): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1176): updateDataNetType()
D/StatusBar.NetworkController( 1176): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1176): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1176): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1176): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1176): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1176): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 68651(3MB) AllocSpace objects, 4(112KB) LOS objects, 33% free, 27MB/41MB, paused 2.669ms total 154.741ms
W/ActivityManager( 1018): Unbind failed: could not find connection for android.os.BinderProxy@44bea34
,D/ActivityManager( 1018): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3575): Starting #12
,I/Hs20UtilService( 3575): Message received 5007
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1304): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1304): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1304): MountReceiver.onReceive - Keep current state
,D/ActivityManager( 1018): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3575): Starting #13
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1304): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 3575): Message received 5007
,D/WifiStateMachine( 1018): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,D/SecContentProvider2( 1018): uri = 15 selection = getToastGravityEnabledState
,D/SecContentProvider2( 1018): mCursor = null
,D/SecContentProvider2( 1018): uri = 15 selection = getToastGravity
,D/SecContentProvider2( 1018): mCursor = null
,D/SecContentProvider2( 1018): uri = 15 selection = getToastGravityXOffset
,D/SecContentProvider2( 1018): mCursor = null
,D/SecContentProvider2( 1018): uri = 15 selection = getToastGravityYOffset
,D/SecContentProvider2( 1018): mCursor = null
,D/SecContentProvider2( 1018): uri = 15 selection = getToastEnabledState
,D/SecContentProvider2( 1018): mCursor = null
,D/SecContentProvider2( 1018): uri = 15 selection = getToastShowPackageNameState
,D/SecContentProvider2( 1018): mCursor = null
,I/SurfaceFlinger(  257): id=14 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 1018): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1018
,D/SRIB_DCS( 1176): log_dcs ThreadedRenderer::initialize entered! 
,D/ConnectivityService( 1018): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1018): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_DM  ( 3072): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/NetworkMonitor( 6246): type=WIFI subType= reason=null isConnected=true
,I/PCWCLIENTTRACE_PushUtil( 5701): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5701): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5701): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5701): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1018): Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=17, mSplitNum[2]=25, mBgSplitQueueNum=3 divideNum= 8 r.nextReceiver= 1 receivers.size=33
I/splitIntent( 1018): finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,V/MusicLeanback( 6246): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/accuweather( 1728): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 1325): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1018): mCursor = null
,D/accuweather( 1728): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1728): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
I/FOTA_Client( 6254): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
D/accuweather( 1728): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1728): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/SecurityLogAgent( 6362): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6362): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6362): StateMachine : Current State = 1
,D/SecurityLogAgent( 6362): StateMachine : Changed Current State = 1
,D/accuweather( 1728): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1728): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/FOTA_Client( 6254): [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,I/FOTA_Client( 6254): [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,I/DIAGMON_AGENT( 6448): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 6448): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6448): ./extraInfo: "NG700"
,I/DIAGMON_AGENT( 6448): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,W/FOTA_Client( 6254): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,I/KLMS-2.5.183: ( 3621): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Jan 05 02:20:41 GMT+01:00 2016
,D/WaitQueueForNetworkActivate( 5771): notifyNetworkActivated
,D/ActivityManager( 1018): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.183: ( 3621): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.5.183: ( 3621): KLMSIntentService(): onCreate()
,I/KLMS-2.5.183: ( 3621): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.183: ( 3621): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.183: ( 3621): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.183: ( 3621): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,D/ActivityManager( 1018): startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.LocationTagReadyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
I/KLMS-2.5.183: ( 3621): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,I/KLMS-2.5.183: ( 3621): StateImplV2(): networkChangeListener().START
,W/ContextImpl( 5771): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
D/QuickConnect( 6482): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
W/ActivityManager( 1018): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,I/KLMS-2.5.183: ( 3621): NetworkChangeOperations(): uploadRequestLog().START 
,I/QuickConnect( 6482): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 6482): PeriphStartReceiver.onReceive - no need to start
,I/KLMS-2.5.183: ( 3621): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.5.183: ( 3621): StateImplV2(): networkChangeListener().END
,I/KLMS-2.5.183: ( 3621): KLMSIntentService(): onDestroy()
,I/DBG_POLICYDM( 5754): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5754): [com.policydm.XDMApplication(469/isNetworkChanged)] a previous network is 0, current network is 2
,E/SPPClientService( 5821): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      ( 5995): [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
,I/SA      ( 5995): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 5995): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,E/DBG_POLICYDM( 5754): [com.policydm.XDMApplication(471/isNetworkChanged)] network changed.... 
,I/SA      ( 5995): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 5995): [OR] == isSIMCardReady false ==
,I/SA      ( 5995): [SCU] == networkStateCheck == true
,I/SA      ( 5995): [DM] getCountryCodeFromCSC : PL
,I/SA      ( 5995): isChinaCountryCode : false
I/SA      ( 5995): [SCU] is ChinestModel Data Restricted   : false
,I/SA      ( 5995): [OR] == networkStateCheck true ==
,I/SA      ( 5995): [OR] GetMyCountryZoneTask
,I/SA      ( 5995): [OR] onReceive END
,V/DownloadManager( 1231): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,D/ActivityManager( 1018): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,I/SA      ( 5995): [SRS] prepareGetMyCountryZone
,D/SecContentProvider2( 1018): uri = 15 selection = getAppBlockDownloadState
D/SecContentProvider2( 1018): mCursor = null
,I/SA      ( 5995): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 5995): [SSP] query invoked
,I/DBG_POLICYDM( 5754): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 5754): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/SA      ( 5995): [TPMU] GetMccFromDB : null
,I/SA      ( 5995): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 5995): [TPM] isNoProxy(default) : true
,I/DBG_POLICYDM( 5754): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 5754): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 5754): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 5754): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 5754): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,E/File    ( 5995): fail readDirectory() errno=2
,I/DBG_POLICYDM( 5754): [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
,E/DBG_POLICYDM( 5754): [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
,I/DBG_POLICYDM( 5754): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,D/ActivityManager( 1018): startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/hcjo    ( 5771): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 5771): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 5771): exit::IDLE
D/InitializeManagerStateMachine( 5771): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 5771): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5771): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5771): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5771): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5771): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5771): entry::SUCCESS
D/hcjo    ( 5771): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 5771): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 5771): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 5771): exit::SUCCESS
D/InitializeManagerStateMachine( 5771): entry::IDLE
,I/iu.Environment( 1986): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1986): num queued entries: 0
,I/iu.UploadsManager( 1986): num updated entries: 0
I/iu.SyncManager( 1986): NEXT; no task
,I/ActivityManager( 1018): Killing 5925:com.wsomacp/u0a25 (adj 15): empty #31
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1018): Queue : backgroundsplit_2 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 503 for uid 10012
,D/ConnectivityService( 1018): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,W/libprocessgroup( 1018): failed to open /acct/uid_10025/pid_5925/cgroup.procs: No such file or directory
,I/SA      ( 5995): [RC New] Execute method=[GET] start
,I/art     ( 1808): Explicit concurrent mark sweep GC freed 35796(2MB) AllocSpace objects, 14(224KB) LOS objects, 40% free, 12MB/21MB, paused 1.199ms total 64.633ms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,I/SA      ( 5995): [RC New] Security=[true]
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,I/System.out( 5995): Thread-1040(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 5995): Thread-1040(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 5995): Thread-1040(ApacheHTTPLog):isShipBuild true
I/System.out( 5995): Thread-1040(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5995): Thread-1040(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  277): uids 10041
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 503 for uid 10041
,I/SA      ( 5995): [RC New] [v2liruge] api execute + 619
,I/SA      ( 5995): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 5995): AsyncTask #1 calls detatch()
,I/SA      ( 5995): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 5995): [OCP] update openData : PL
,I/SA      ( 5995): [TPMU] getNetworkMcc : 
,I/SA      ( 5995): [SCU] saveMccToPreferece Start
,I/SA      ( 5995): [SCU] RegionMCC : 260
,I/SA      ( 5995): [SSP] query invoked
,I/SA      ( 5995): [TPMU] GetMccFromDB : null
,I/SA      ( 5995): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5995): [SCU] saveMccToPreferece End
,I/SA      ( 5995): [RC New] executeRequest [v2liruge] end. 684
I/SA      ( 5995): [RC New] Execute end
,I/SA      ( 5995): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 5995): [OR] GetMyCountryZoneTask Success
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :8
,D/SSRM:n  ( 1018): SIOP:: AP = 330
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/PackageManager( 1018): [MSG] MCS_UNBIND
,I/ActivityManager( 1018): Killing 5941:com.sec.android.app.soundalive/u0a53 (adj 15): empty #31
,W/libprocessgroup( 1018): failed to open /acct/uid_10053/pid_5941/cgroup.procs: No such file or directory
,I/dhcpcd  ( 6398): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 6398): wlan0: sendmsg: Cannot assign requested address
,D/ActivityManager( 1018): startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push,
,I/SurfaceFlinger(  257): id=14 Removed Uoast (8/9)
I/SurfaceFlinger(  257): id=14 Removed Uoast (-2/9)
,D/PowerManagerService( 1018): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1018) eventTime = 90422
D/PowerManagerService( 1018): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1018 (0x0)
D/PowerManagerService( 1018): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1018, ws=WorkSource{10054}) (elapsedTime=3477)
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.apps.magazines, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,I/GAV4    ( 6338): Thread[GAThread,5,main]: No campaign data found.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.leanback.AutoCacheSchedulingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.TrackDownloadQueueService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.TrackCacheService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.wear.WearMetadataSyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/WearableService( 1808): callingUid 10012, callindPid: 1808
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/MusicLeanback( 6246): Conditions not met for autocaching.
,I/MusicLeanback( 6246): Stop autocaching.
,D/ConnectivityService( 1018): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,fe80::7ef9:eff:fe37:96ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/ConnectivityService( 1018): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService( 1018): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 1986): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 1176): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 1176): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 1986): CM callback handler got msg 524295
,E/GmsUtils( 6246): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,E/GmsUtils( 6246): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5701): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 5701): [hasSamungAccount] - No Samsung Account
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5701): [GetString-S]
,I/ReactiveServiceManager( 5701): Supported : 1
,D/QSEECOMAPI: ( 1018): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 1018): App is not loaded in QSEE
,V/AlarmManager( 1018): waitForAlarm result :8
,D/QSEECOMAPI: ( 1018): Loaded image: APP id = 11
,D/QSEECOMAPI: ( 1018): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 1018): QSEECom_shutdown_app, app_id = 11
,E/terrier ( 1018): handleString: Failed to handle string(-4)
E/terrier ( 1018): Java_com_android_server_ReactiveService_GetString: error code = [-4]
D/PCWCLIENTTRACE_SecurePreferencesJNI( 5701): getString is null
I/PCWCLIENTTRACE_SecurePreferencesJNI( 5701): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 5701): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5701): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5701): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 5701): [ensureRegistration] - No Samsung account
,I/ActivityManager( 1018): Waited long enough for: ServiceRecord{2d8414a4 u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,I/dhcpcd  ( 6398): wlan0: sending IPv6 Router Solicitation
,I/jxcore-log( 5970): Test app app.js loaded
I/jxcore-log( 5970): 
,I/Choreographer( 5970): Skipped 624 frames!  The application may be doing too much work on its main thread.
,I/chromium( 5970): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/PowerManagerService( 1018): [PWL] Off : 15s ago
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4347, temperature: 241, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1421): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1421): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ActivityManager( 1018): startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.preloadupdate.PreloadUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/PreloadUpdateManagerStateMachine( 5771): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 5771): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5771): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 5771): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 5771): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5771): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 5771): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 5771): entry::IDLE,
,V/AlarmManager( 1018): waitForAlarm result :4
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0,
,D/ActivityManager( 1018): bindService callerProcessName:android, calleePkgName: android, action: null
D/ActivityManager( 1018): retrieveServiceLocked(): component = android/com.android.server.os.BackgroundCompactionService; callingUser = 0; userId(target) = 0
,I/BackgroundCompactionService( 1018): onStart. jobID=801
,I/BackgroundCompactionService( 1018): onStart done. jobID=801
,I/BackgroundCompactionService( 1018): Execute BGCompaction (type1). (0 times),
I/BackgroundCompactionService( 1018): compact_memory command done
,E/SMD     (  290): DCD OFF
,I/dhcpcd  ( 6398): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  ( 6398): wlan0: no IPv6 Routers available
,D/Finsky  ( 5499): [960] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5499): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/SSRM:n  ( 1018): SIOP:: AP = 310
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :8
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 241, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1421): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1421): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1018): !@Sync 3
,I/Atfwd_Sendcmd(  330): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  330): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/PowerManagerService( 1018): [PWL] Off : 30s ago,
,V/AlarmManager( 1018): waitForAlarm result :4
,V/AlarmManager( 1018): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManagerEXT( 1018): <AppSync3 Whitelist>
V/AlarmManagerEXT( 1018): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1176): handleTimeUpdate,
,D/SecKeyguardClockView( 1176): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1176): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1176): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1176): *** don't update sliding image ***
,D/SSRM:n  ( 1018): SIOP:: AP = 290
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.store.VacuumService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1808): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1808): Vacuum at: now=1451956867567 tag=VacuumService
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.uploader.UploaderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PhenotypeConfigurator( 1808): Scheduling Phenotype for one-off execution 9051 seconds from now (1451956867961)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GetConfigurationSnapshotOperation( 1808): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PhenotypeFlagCommitter( 1808): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1808): Using platform SSLCertificateSocketFactory
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,D/LocationManagerService( 1018): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 1808): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 503 for uid 10012
,D/FactoryTest( 5330): Not factory mode
,D/FactoryTest( 5330): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 5330): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 5330): still no open session command from host, so toast
,I/Timeline( 5330): Timeline: Activity_launch_request id:com.android.settings time:114295
W/ContextImpl( 5330): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
W/ContextImpl( 5330): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,E/PersonaManagerService( 1018): inState():  stateMachine is null !!
I/PersonaManagerService( 1018): PersonaId don't exist
I/ActivityManager( 1018): do not start freezing screen for locked container getKeyguardshowstate = false
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.android.settings
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,W/ActivityManager( 1018): mDVFSHelper.acquire()
,I/System.out( 1808): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1808): Tagging socket 88 with tag 1000120100000000{268440065,0} for uid -1, pid: 1808, getuid(): 10012
,D/PersonaManager( 1018): isKioskContainerExistOnDevice
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.android.settings
,D/InputDispatcher( 1018): Focused application set to: xxxx
D/InputDispatcher( 1018): Focus left window: 5970
,D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
E/MTPRx   ( 5330): started activity for popup
,I/qtaguid ( 1808): Tagging socket 91 with tag 1000120100000000{268440065,0} for uid -1, pid: 1808, getuid(): 10012
,W/ResourcesManager( 5330): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 5330): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5330): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 5330): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5330): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5330): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 5330): PREF_DONT_ASK_AGAIN : true
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.android.settings
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,D/InputDispatcher( 1018): Focused application set to: xxxx
,D/InputDispatcher( 1018): Focus entered window: 5970
,D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
,D/InputMethodManagerService( 1018): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/InputMethodManagerService( 1018): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@f7b48e1 attribute=null, token = android.os.BinderProxy@8eab0ea
,D/SettingsReceiverActivity( 5330): dev.kiessupport is : TRUE
,D/PhoneWindow( 5330): *FMB* installDecor mIsFloating : true
D/PhoneWindow( 5330): *FMB* installDecor flags : 8388610
,D/ActivityManager( 1018): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1018): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1018): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1018): handleActiveUserChange for user 0
D/PersonaManagerService( 1018): getPersonasForUser(): returning null!
,V/ActivityThread( 5970): updateVisibility : ActivityRecord{33b84d3a token=android.os.BinderProxy@14d5d15c {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,I/Timeline( 5970): Timeline: Activity_idle id: android.os.BinderProxy@14d5d15c time:114468
,D/PersonaManager( 1018): isKioskContainerExistOnDevice
,D/LocationManagerService( 1018): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1808): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1808): Tagging socket 88 with tag 1000120100000000{268440065,0} for uid -1, pid: 1808, getuid(): 10012
,D/LocationManagerService( 1018): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1808): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1808): Tagging socket 88 with tag 1000120100000000{268440065,0} for uid -1, pid: 1808, getuid(): 10012
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  330): Waiting for service AtCmdFwd...,
,W/ActivityManager( 1018): mDVFSHelper.release(),
,I/ServiceManager(  330): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD OFF
,W/Atfwd_Sendcmd(  330): AtCmdFwd service not published, waiting... retryCnt : 1
,D/SSRM:n  ( 1018): SIOP:: AP = 270
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  330): AtCmdFwd service not published, waiting... retryCnt : 2
,I/PowerManagerService( 1018): [PWL] Off : 50s ago,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/Watchdog( 1018): !@Sync 4,
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  330): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 240, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1421): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1421): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 75s ago
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 240, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1421): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1421): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,W/Atfwd_Sendcmd(  330): AtCmdFwd service not published, waiting... retryCnt : 4
,V/AlarmManager( 1018): waitForAlarm result :8
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1018): !@Sync 5
,I/ClearcutLoggerApiImpl( 1808): disconnect managed GoogleApiClient
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/PowerManagerService( 1018): [PWL] Off : 105s ago
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 239, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1421): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
V/EmergencyMode( 1421): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  330): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  330): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1018): !@Sync 6
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,V/AlarmManager( 1018): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1176): handleTimeUpdate
,D/SecKeyguardClockView( 1176): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1176): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1176): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1176): *** don't update sliding image ***
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,I/Atfwd_Sendcmd(  330): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  330): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 140s ago
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,V/AlarmManager( 1018): waitForAlarm result :8
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,E/Watchdog( 1018): !@Sync 7,
,W/Atfwd_Sendcmd(  330): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,W/Atfwd_Sendcmd(  330): AtCmdFwd service not published, waiting... retryCnt : 2
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,W/Atfwd_Sendcmd(  330): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 238, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1421): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1421): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 1018): !@Sync 8
,I/PowerManagerService( 1018): [PWL] Off : 180s ago
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 238, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
V/EmergencyMode( 1421): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1421): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  330): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/Watchdog( 1018): !@Sync 9
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  330): Waiting for service AtCmdFwd...,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,W/Atfwd_Sendcmd(  330): AtCmdFwd service not published, waiting... retryCnt : 5
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 225s ago
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/TimaService( 1018): TIMA: TimaService scheduler is intialized. 
D/TimaService( 1018): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1018): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize( 1018): initializing...
,I/TLC_TIMA_PKM_initialize( 1018): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize( 1018): process = tima_pkm, process_strlen = 8
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
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1018): !@Sync 10
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,I/Atfwd_Sendcmd(  330): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  330): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  290): DCD OFF
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED,
D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 238, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.,
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
V/EmergencyMode( 1421): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1421): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 238, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
V/EmergencyMode( 1421): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1421): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1018): Plugged,
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,W/Atfwd_Sendcmd(  330): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1018): !@Sync 11
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  330): AtCmdFwd service not published, waiting... retryCnt : 2
,I/PowerManagerService( 1018): [PWL] Off : 275s ago
,E/SMD     (  290): DCD OFF
,D/ActivityManager( 1018): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1808): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000,
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1808): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1808): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 5499): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10028
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 503 for uid 10028
,I/System.out( 5499): KnoxVpnUidStorageknoxVpnSupported API value returned is false,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 238, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false,
D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
V/EmergencyMode( 1421): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1421): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/Atfwd_Sendcmd(  330): AtCmdFwd service not published, waiting... retryCnt : 3
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1018): !@Sync 12
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 238, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1421): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
V/EmergencyMode( 1421): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 238, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1421): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1421): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,W/Atfwd_Sendcmd(  330): AtCmdFwd service not published, waiting... retryCnt : 4
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 238, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged,
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1421): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1421): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :8
,V/AlarmManager( 1018): No more alarm at this time.nowELAPSED=406020 batch.start=909617
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1176): handleTimeUpdate,
,D/SecKeyguardClockView( 1176): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false,
,D/SecKeyguardClockView( 1176): HomeTimezone(): 1,
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1176): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1176): *** don't update sliding image ***
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1018): !@Sync 13
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/PowerManagerService( 1018): [PWL] Off : 330s ago
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  330): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1018): SIOP:: AP = 250,
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  330): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 238, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
V/EmergencyMode( 1421): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1421): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 238, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1421): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1421): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1018): !@Sync 14
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/Atfwd_Sendcmd(  330): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  330): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 237, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1421): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1421): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,W/Atfwd_Sendcmd(  330): AtCmdFwd service not published, waiting... retryCnt : 1
,V/AlarmManager( 1018): waitForAlarm result :8,
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1018): !@Sync 15
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  330): Waiting for service AtCmdFwd...,
,I/PowerManagerService( 1018): [PWL] Off : 390s ago,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  330): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/bootchecker(  327): bootchecker wake up!!,
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  330): AtCmdFwd service not published, waiting... retryCnt : 3
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  290): DCD OFF,
,E/Watchdog( 1018): !@Sync 16
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,W/Atfwd_Sendcmd(  330): AtCmdFwd service not published, waiting... retryCnt : 4
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/Watchdog( 1018): !@Sync 17
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  330): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  330): AtCmdFwd service not published, waiting... retryCnt : 5
,I/PowerManagerService( 1018): [PWL] Off : 455s ago
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1018): !@Sync 18
,I/Atfwd_Sendcmd(  330): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  330): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,I/Atfwd_Daemon(  330): Stop the daemon....
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1018): !@Sync 19
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 525s ago
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,D/TimaService( 1018): TIMA: TimaService scheduler is intialized. 
D/TimaService( 1018): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1018): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1018): !@Sync 20
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 250,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 237, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged,
D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
V/EmergencyMode( 1421): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1421): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1018): !@Sync 21,
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 237, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1018): stay LED for fully charged
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate,
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.,
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
V/EmergencyMode( 1421): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1421): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 250,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 236, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1421): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1421): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1018): !@Sync 22
,I/PowerManagerService( 1018): [PWL] Off : 600s ago
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 250,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1018): !@Sync 23
,E/SMD     (  290): DCD OFF
D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1018): SIOP:: AP = 250,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1018): !@Sync 24
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 250,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 681s ago,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 250,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1018): !@Sync 25,
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 250,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1018): SIOP:: AP = 250,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/Watchdog( 1018): !@Sync 26
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 250,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 250,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/Watchdog( 1018): !@Sync 27,
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/SSRM:n  ( 1018): SIOP:: AP = 250,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 236, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
V/EmergencyMode( 1421): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1421): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 236, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,V/EmergencyMode( 1421): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1421): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 766s ago
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/Watchdog( 1018): !@Sync 28
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/Watchdog( 1018): !@Sync 29
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/SSRM:n  ( 1018): SIOP:: AP = 250,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 235, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
V/EmergencyMode( 1421): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1421): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,V/AlarmManager( 1018): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1176): handleTimeUpdate
,D/SecKeyguardClockView( 1176): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1176): HomeTimezone(): 1,
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/KeyguardEffectViewController( 1176): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1176): *** don't update sliding image ***
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.EventLogService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/EventLogService( 1986): Aggregate from 1451955863506 (log), 1451955863506 (data)
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6936): MountEmulatedStorage()
I/ActivityManager( 1018): Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.common.SmartManagerReceiver: pid=6936 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/Zygote  ( 6936): v2
I/libpersona( 6936): KNOX_SDCARD checking this for 1000
I/libpersona( 6936): KNOX_SDCARD not a persona
,I/SELinux ( 6936): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6936): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6936): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6936): TimaSignature is unavailable
,D/ActivityThread( 6936): Added TimaKeyStore provider
,W/ResourcesManager( 6936): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/ActivityManager( 1018): Killing 5365:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
,W/libprocessgroup( 1018): failed to open /acct/uid_10057/pid_5365/cgroup.procs: No such file or directory
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 235, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1421): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1421): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,D/TimaService( 1018): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1018): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1018): TimaServiceHandler.handleMessage what =1
,E/SMD     (  290): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 1018): !@Sync 30,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 236, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1421): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1421): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 235, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
V/EmergencyMode( 1421): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1421): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 1018): [PWL] Off : 856s ago
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :8
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1018): !@Sync 31
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 235, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1421): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1421): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 235, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1421): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1421): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1018): !@Sync 32
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1176): handleTimeUpdate
,D/SecKeyguardClockView( 1176): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1176): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1176): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1176): *** don't update sliding image ***
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :8
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1018): !@Sync 33,
,E/SMD     (  290): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 235, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1421): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1421): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 951s ago
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 235, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate,
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1018): Plugged,
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
V/EmergencyMode( 1421): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1421): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1018): !@Sync 34
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1018): !@Sync 35
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1018): !@Sync 36
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1018): !@Sync 37,
,I/PowerManagerService( 1018): [PWL] Off : 1051s ago
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1018): !@Sync 38
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1018): !@Sync 39
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/TimaService( 1018): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1018): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1018): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService( 1018): User[0] Flushing usage stats to disk
,I/ApplicationUsage( 1018): handleMessage : MSG_UPDATE_USAGE_DB,
I/ApplicationUsage( 1018): Updating Usage Statistics in DB @ 1451957970051
,I/ApplicationPolicy( 1018): updateDataUsageMap
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/NetworkDataUsageDb( 1018): ::getAppControlDB: DB is Created 
,I/NetworkDataUsageDb( 1018): ::isTableExists: Table exists 
,I/ApplicationUsage( 1018): Done Updating Usage Statistics in DB @ 1451957970437
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1018): !@Sync 40,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 235, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1421): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1421): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,I/PowerManagerService( 1018): [PWL] Off : 1156s ago
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 235, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1421): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1421): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1018): !@Sync 41
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/SSRM:n  ( 1018): SIOP:: AP = 250,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1018): !@Sync 42,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 234, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1421): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1421): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1018): !@Sync 43
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1018): !@Sync 44
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,I/PowerManagerService( 1018): [PWL] Off : 1266s ago
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1018): !@Sync 45,
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1018): !@Sync 46,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1018): !@Sync 47
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1018): !@Sync 48
,I/PowerManagerService( 1018): [PWL] Off : 1381s ago
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1018): !@Sync 49
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 234, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
I/MotionRecognitionService( 1018): Plugged,
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
V/EmergencyMode( 1421): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1421): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,D/TimaService( 1018): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1018): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1018): TimaServiceHandler.handleMessage what =1
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 234, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1421): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1421): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1018): !@Sync 50
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF,
,E/Watchdog( 1018): !@Sync 51
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1018): !@Sync 52
,I/PowerManagerService( 1018): [PWL] Off : 1501s ago
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/Watchdog( 1018): !@Sync 53
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 234, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged,
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1421): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
V/EmergencyMode( 1421): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 234, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1421): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1421): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1018): !@Sync 54
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1018): !@Sync 55
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1018): !@Sync 56
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 234, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
V/EmergencyMode( 1421): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1421): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250,
,I/PowerManagerService( 1018): [PWL] Off : 1626s ago
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1018): !@Sync 57
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 234, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1421): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1421): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1018): !@Sync 58
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 234, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1421): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1421): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 234, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1421): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1421): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 234, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1421): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1421): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1018): !@Sync 59
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 234, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1421): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1421): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2620): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,D/TimaService( 1018): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1018): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1018): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1018): !@Sync 60,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,I/PowerManagerService( 1018): [PWL] Off : 1756s ago
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1018): !@Sync 61
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1018): !@Sync 62
,V/AlarmManager( 1018): waitForAlarm result :8
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1176): handleTimeUpdate
,D/SecKeyguardClockView( 1176): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,I/ActivityManager( 1018): Killing 5754:com.policydm/1000 (adj 15): empty for 1800s
I/ActivityManager( 1018): Killing 6482:com.samsung.android.sconnect/u0a125 (adj 15): empty for 1800s
,D/SecKeyguardClockView( 1176): HomeTimezone(): 1
,I/ActivityManager( 1018): Killing 6313:com.sec.android.soagent/u0a34 (adj 15): empty for 1800s
I/ActivityManager( 1018): Killing 6136:com.google.android.apps.plus/u0a120 (adj 15): empty for 1800s
,I/ActivityManager( 1018): Killing 6338:com.google.android.apps.magazines/u0a113 (adj 15): empty for 1800s
I/ActivityManager( 1018): Killing 6292:com.android.chrome/u0a81 (adj 15): empty for 1800s
,I/ActivityManager( 1018): Killing 6448:com.sec.android.diagmonagent/1000 (adj 15): empty for 1800s
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
I/ActivityManager( 1018): Killing 6379:com.samsung.android.service.travel/u0a159 (adj 15): empty for 1800s
,I/ActivityManager( 1018): Killing 6362:com.samsung.android.securitylogagent/1000 (adj 15): empty for 1800s
,I/ActivityManager( 1018): Killing 6416:com.sec.android.cloudagent/u0a2 (adj 15): empty for 1800s
,I/ActivityManager( 1018): Killing 6273:com.android.email/u0a145 (adj 15): empty for 1800s
I/ActivityManager( 1018): Killing 5701:com.sec.pcw.device/1000 (adj 15): empty for 1800s
,I/ActivityManager( 1018): Killing 5877:com.sec.android.provider.badge/u0a72 (adj 15): empty for 1802s
,I/ActivityManager( 1018): Killing 6043:com.google.android.gms:car/u0a12 (adj 15): empty for 1804s
I/ActivityManager( 1018): Killing 6171:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty for 1805s
,I/ActivityManager( 1018): Killing 6094:com.samsung.helphub/1000 (adj 15): empty for 1807s
I/ActivityManager( 1018): Killing 6070:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty for 1807s
I/ActivityManager( 1018): Killing 5787:com.google.android.apps.docs/u0a91 (adj 15): empty for 1807s
,I/ActivityManager( 1018): Killing 5847:com.samsung.android.sdk.samsunglink/u0a38 (adj 15): empty for 1807s
,I/ProcessStatsService( 1018): Prepared write state in 44ms
,D/KeyguardEffectViewController( 1176): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1176): *** don't update sliding image ***
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
V/NetworkStats( 1018): performPollLocked(flags=0x3)
,D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1018): UpdateStatsForKnox main else ---
,V/NetworkStats( 1018): performPollLocked() took 7ms
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,I/BatteryStatsDumper( 1018): In refreshStats isReason Screen ON/OFF: false
,D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
,D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.analytics.CoreAnalyticsIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/BatteryStatsDumper( 1018): Screen bin #0: time=30305 power=0.17677916666666665
I/BatteryStatsDumper( 1018): Screen bin #1: time=0 power=0.0
I/BatteryStatsDumper( 1018): Screen bin #2: time=0 power=0.0
I/BatteryStatsDumper( 1018): Screen bin #3: time=0 power=0.0
I/BatteryStatsDumper( 1018): Screen bin #4: time=0 power=0.0
I/BatteryStatsDumper( 1018): Previous Battery Level: 100 Current Level: 100 Delta: 0
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1808): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1808): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 1808): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 503 for uid 10012
,V/NativeCrypto( 1808): SSL shutdown failed: ssl=0xb85343b0: I/O error during system call, Connection timed out
,I/BatteryStatsDumper( 1018): Writing to database completed
,I/System.out( 1808): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1808): Tagging socket 57 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1808, getuid(): 10012
,I/qtaguid ( 1808): Tagging socket 79 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1808, getuid(): 10012
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ProcessStatsService( 1018): Pruning old procstats: /data/system/procstats/state-2016-01-04-01-54-05.bin
,W/libprocessgroup( 1018): failed to open /acct/uid_10012/pid_6043/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_10002/pid_6416/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10100/pid_6070/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_10038/pid_5847/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10113/pid_6338/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10081/pid_6292/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_6362/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_6448/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_5754/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10072/pid_5877/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10159/pid_6379/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10034/pid_6313/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_6094/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10142/pid_6171/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10120/pid_6136/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10145/pid_6273/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_5701/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10125/pid_6482/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10091/pid_5787/cgroup.procs: No such file or directory
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,TIME-OUT KILL (timeout was 1800000ms),E/SMD     (  290): DCD OFF
D/AndroidRuntime( 7363): 
D/AndroidRuntime( 7363): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7363): CheckJNI is OFF
D/AndroidRuntime( 7363): readGMSProperty: start
D/AndroidRuntime( 7363): readGMSProperty: already setted!!
D/AndroidRuntime( 7363): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 7363): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 7363): readGMSProperty: end
D/AndroidRuntime( 7363): addProductProperty: start
E/AffinityControl( 7363): AffinityControl: registerfunction enter
D/AndroidRuntime( 7363): Calling main entry com.android.commands.pm.Pm
D/PersonaManagerService( 1018): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1018): START PACKAGE DELETE: observer{975481780}
D/PackageManager( 1018): pkg{<packageName>}
D/PackageManager( 1018): user{0}
D/PackageManager( 1018): caller{2000}
D/PackageManager( 1018): flags{3}
D/PersonaManagerService( 1018): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 1018): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1018): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1018): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1018): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService( 1018): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 1018): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1018): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1018): getApplicationUninstallationEnabled :  enabled true
D/PackageManager( 1018): !@killApplicatoin: 10175, uninstall pkg
I/ActivityManager( 1018): Force stopping com.test.thalitest appid=10175 user=-1: uninstall pkg
I/ActivityManager( 1018): Killing 5970:com.test.thalitest/u0a175 (adj 0): stop com.test.thalitest cause uninstall pkg
W/PackageSettings( 1018): Skipping PackageSetting{38fa7a1a com.example.hello/10177} due to missing metadata
I/ActivityManager( 1018):   Force finishing activity ActivityRecord{2a068cc u0 com.test.thalitest/.MainActivity t2}
I/ActivityManager( 1018): Force stopping com.test.thalitest appid=10175 user=0: pkg removed
I/ActivityManager( 1018):   Force finishing activity ActivityRecord{2a068cc u0 com.test.thalitest/.MainActivity t2 f}
W/ActivityManager( 1018): Duplicate finish request for ActivityRecord{2a068cc u0 com.test.thalitest/.MainActivity t2 f}
I/WindowState( 1018): WIN DEATH: Window{cd0cfdb u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger(  257): id=13 Removed NainActivit (6/8)
I/SurfaceFlinger(  257): id=13 Removed NainActivit (-2/8)
W/ActivityManager( 1018): CustomStartingWindow se packge removed so remove capture also
D/InputDispatcher( 1018): Focus left window: 5970
I/SurfaceFlinger(  257): id=13 Removed NainActivit (-2/8)
D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
D/InputDispatcher( 1018): Focused application released
D/FocusedStackFrame( 1018): Set to : 0
W/ActivityManager( 1018): mDVFSHelper.acquire()
V/WindowManager( 1018): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
I/art     ( 4944): Explicit concurrent mark sweep GC freed 2524(147KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 763us total 34.419ms
D/Launcher( 1482): onRestart, Launcher: 192541297
I/InputReader( 1018): Reconfiguring input devices.  changes=0x00000010
E/SamsungIME( 1790): mOCRHelper is null
W/GeofencerStateMachine( 1808): Ignoring removeGeofence because network location is disabled.
I/art     ( 1986): Explicit concurrent mark sweep GC freed 9289(547KB) AllocSpace objects, 3(48KB) LOS objects, 25% free, 14MB/18MB, paused 1.294ms total 99.752ms
D/Launcher( 1482): onStart, Launcher: 192541297
D/Launcher.HomeView( 1482): onStart
D/Launcher( 1482): onResume, Launcher: 192541297
D/SettingsProvider( 1018): name = kids_home_mode
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10007
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
D/Launcher.HomeView( 1482): onResume
D/RegisteredComponentCache( 1447): Collect Tech packages for Knox
D/PersonaManager( 1447): isKioskContainerExistOnDevice
D/Launcher( 1482): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
D/MenuAppsGridFragment( 1482): onResume
I/KLMS-2.5.183: ( 3621): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Jan 05 02:50:47 GMT+01:00 2016
D/ActivityManager( 1018): handle home activity for 0
I/WallpaperManagerService( 1018): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler( 1018): post home show event for user 0
D/ActivityManager( 1018): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1018): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1018): postActiveUserChange, showWhenLocked: false
D/ActivityManager( 1018): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
D/Launcher.HomeView( 1482): onPause
D/Launcher( 1482): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
I/SurfaceFlinger(  257): id=15 createSurf (720x1280),1 flag=4, Mauncher
D/StatusBarManagerService( 1018): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/KLMS-2.5.183: ( 3621): KLMSAbstractReciever(): onReceive().END.
I/splitIntent( 1018): Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=21, mSplitNum[2]=34, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=44
D/StatusBarManagerService( 1018): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/KLMS-2.5.183: ( 3621): KLMSIntentService(): onCreate()
I/splitIntent( 1018): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
D/InputDispatcher( 1018): Focus entered window: 1482
D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
D/SRIB_DCS( 1482): log_dcs ThreadedRenderer::initialize entered! 
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
I/KLMS-2.5.183: ( 3621): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
V/ActivityThread( 1482): updateVisibility : ActivityRecord{258c7b54 token=android.os.BinderProxy@17bce9a5 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/Launcher.HomeView( 1482): onStop
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7378): MountEmulatedStorage()
E/Zygote  ( 7378): v2
I/libpersona( 7378): KNOX_SDCARD checking this for 10094
I/libpersona( 7378): KNOX_SDCARD not a persona
I/SELinux ( 7378): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1018): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7378 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
I/SELinux ( 7378): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 7378): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/KLMS-2.5.183: ( 3621): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
I/KLMS-2.5.183: ( 3621): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
E/Zygote  ( 7393): MountEmulatedStorage()
E/Zygote  ( 7393): v2
I/libpersona( 7393): KNOX_SDCARD checking this for 10044
I/libpersona( 7393): KNOX_SDCARD not a persona
I/SELinux ( 7393): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 7393): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 7393): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=7393 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 7378): TimaSignature is unavailable
D/ActivityThread( 7378): Added TimaKeyStore provider
E/Zygote  ( 7409): MountEmulatedStorage()
E/Zygote  ( 7409): v2
I/libpersona( 7409): KNOX_SDCARD checking this for 10149
I/libpersona( 7409): KNOX_SDCARD not a persona
I/SELinux ( 7409): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 7409): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 7409): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=7409 uid=10149 gids={50149, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/TimaKeyStoreProvider( 7393): TimaSignature is unavailable
D/ActivityThread( 7393): Added TimaKeyStore provider
D/TimaKeyStoreProvider( 7409): TimaSignature is unavailable
D/ActivityThread( 7409): Added TimaKeyStore provider
I/KLMS-2.5.183: ( 3621): KLMSIntentService(): PACKAGE_REMOVED
I/KLMS-2.5.183: ( 3621): KLMSIntentService(): listeningToPackageRemoved().START
I/KLMS-2.5.183: ( 3621): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1018): mCursor = null
D/PersonaManager( 1447): isKioskContainerExistOnDevice
D/RegisteredServicesCache( 1447): empty dynamic service
D/EnterpriseDeviceManagerService( 1018): Package has changed for user 0
D/RCPManagerService( 1018): PackageReceiver onReceive()
I/HarmonyEASService( 1018): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KnoxMUMContainerPolicy( 1018): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
I/OTPFW   ( 1018): PackageRemovalReceiver::onReceive Enter
D/OTPFW   ( 1018): OtpDbHelper::getInstance New instance created
I/art     ( 6936): Explicit concurrent mark sweep GC freed 412(34KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/9MB, paused 902us total 51.796ms
D/OTPFW   ( 1018): DBIntegrity::getInstance - New instance created
D/EnterpriseDeviceManagerService( 1018): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1018): no available spell checker services found
D/OTPFW   ( 1018): PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10175 container id = 0
I/OTPFW   ( 1018): ProvisionData::getAllEntries Enter
E/OTPFW   ( 1018): ProvisionData::getAllEntries Table is empty
D/BackupManagerService( 1018): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1018): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1018): uID is 10175
V/EnterpriseBillingPolicy( 1018): Removed Packageuid is0
W/ResourcesManager( 7393): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - enter
W/ResourcesManager( 7393): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7393): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7393): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7393): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 7393): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7393): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7393): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
E/SQLiteLog( 6936): (284) automatic index on crash_info_summary(package_name_touched)
D/elm:15183( 7378): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - start - com.test.thalitest
D/elm:15183( 7378): ELMEngine.ELMEngine( context ).
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - end - null
D/elm:15183( 7378): MDMBridge.setEnterpriseBridge()
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/ActivityManager( 1018): startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
V/AlarmManagerEXT( 1018): com.test.thalitest(10175) is removed.
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1018): uID is 10175
D/SSRM:aZ ( 1018): MSG_TYPE_APP_REMOVED::
V/EnterpriseBillingPolicy( 1018): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - enter
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - end - null
D/WindowOrientationListener( 1018):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
D/WallpaperManagerService( 1018):  force update = false; persona id = 0; current user =0; current persona = 0
D/KnoxTimeoutHandler( 1018): handleHomeShow for 0 and current 0
D/PersonaManagerService( 1018): getPersonasForUser(): returning null!
D/KnoxTimeoutHandler( 1018): handleActiveUserChange for user 0
D/elm:15183( 7378): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/ActivityManager( 1018): getContentProviderImpl callerProcessName:com.samsung.android.sm, calleePkgName: com.sec.android.provider.badge
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/ThemeInfoUtil( 7409): getCurrentFestivalName is [null]
D/ThemeInfoUtil( 7409): isCurrentFestival = false
D/elm:15183( 7378): ElmAgentService : onCreate()
D/elm:15183( 7378): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:15183( 7378): MainReceiver.listeningToPackageRemoved()
D/elm:15183( 7378): MDMBridge.getInstance()
D/elm:15183( 7378): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:15183( 7378): MDMBridge.getAllLicenseInfoFromSDK()
E/Zygote  ( 7425): MountEmulatedStorage()
I/libpersona( 7425): KNOX_SDCARD checking this for 10072
E/Zygote  ( 7425): v2
I/libpersona( 7425): KNOX_SDCARD not a persona
I/SELinux ( 7425): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1018): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7425 uid=10072 gids={50072, 9997} abi=armeabi-v7a
I/SELinux ( 7425): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 7425): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/TaskPersister( 1018): removeObsoleteFile: deleting file=2_task.xml
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.samsung.aasaservice, hostingType: broadcast
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7435): MountEmulatedStorage()
E/Zygote  ( 7435): v2
I/libpersona( 7435): KNOX_SDCARD checking this for 1000
I/libpersona( 7435): KNOX_SDCARD not a persona
I/SELinux ( 7435): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1018): Start proc com.samsung.aasaservice for broadcast com.samsung.aasaservice/.AASAUpdateReceiver: pid=7435 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/art     ( 1018): Explicit concurrent mark sweep GC freed 50631(3MB) AllocSpace objects, 8(583KB) LOS objects, 33% free, 28MB/42MB, paused 22.565ms total 405.444ms
I/art     ( 1018): WaitForGcToComplete blocked for 333.221ms for cause HeapTrim
I/SELinux ( 7435): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/elm:15183( 7378): ElmAgentService : onDestroy().
E/SELinux ( 7435): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 7425): TimaSignature is unavailable
D/ActivityThread( 7425): Added TimaKeyStore provider
E/Zygote  ( 7454): MountEmulatedStorage()
E/Zygote  ( 7454): v2
I/libpersona( 7454): KNOX_SDCARD checking this for 10152
I/libpersona( 7454): KNOX_SDCARD not a persona
I/SELinux ( 7454): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 7454): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1018): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7454 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
E/SELinux ( 7454): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7435): TimaSignature is unavailable
D/ActivityThread( 7435): Added TimaKeyStore provider
I/ActivityManager( 1018): Killing 6254:com.sec.android.fotaclient/u0a9 (adj 15): empty for 1806s
I/art     (  313): Explicit concurrent mark sweep GC freed 8722(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 626us total 26.643ms
I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 605us total 17.477ms
W/ActivityManager( 1018): mDVFSHelper.release()
D/TimaKeyStoreProvider( 7454): TimaSignature is unavailable
D/ActivityThread( 7454): Added TimaKeyStore provider
I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 625us total 17.014ms
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/KLMS-2.5.183: ( 3621): KLMSIntentService(): listeningToPackageRemoved().END
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/AASAservice-UpdateReceiver( 7435): AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/System.err( 7435): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 7435): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
W/System.err( 7435): 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
W/System.err( 7435): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/System.err( 7435): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/System.err( 7435): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/System.err( 7435): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7435): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 7435): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/System.err( 7435): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7435): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7435): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/PackageManager( 1018): delete codoeFile: 
W/System.err( 7435): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/Zygote  ( 7475): MountEmulatedStorage()
I/ActivityManager( 1018): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=7475 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/Zygote  ( 7475): v2
I/ActivityManager( 1018): Killing 6205:com.google.android.talk/u0a104 (adj 15): empty for 1805s
I/ActivityManager( 1018): Killing 5995:com.osp.app.signin/u0a41 (adj 15): empty for 1806s
I/libpersona( 7475): KNOX_SDCARD checking this for 1000
I/libpersona( 7475): KNOX_SDCARD not a persona
I/SELinux ( 7475): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 7475): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 7475): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/NearbySource( 7393): Nearby Source Create!
D/NearbyContext( 7393): Nearby Context Create!
I/ActivityManager( 1018): Killing 5620:com.android.defcontainer/u0a4 (adj 15): empty for 1804s
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/KLMS-2.5.183: ( 3621): KLMSIntentService(): onDestroy()
D/BadgeProvider( 7425): onCreate
D/BadgeProvider( 7425): DatabaseHelper
E/SQLiteLog( 7454): (284) automatic index on shooting_modes(title_id)
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/TimaKeyStoreProvider( 7475): TimaSignature is unavailable
D/ActivityThread( 7475): Added TimaKeyStore provider
E/Zygote  ( 7489): MountEmulatedStorage()
I/libpersona( 7489): KNOX_SDCARD checking this for 1000
E/Zygote  ( 7489): v2
I/libpersona( 7489): KNOX_SDCARD not a persona
I/SELinux ( 7489): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 7489): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 7489): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/AASAuninstall( 1018): userId = 0, info.removedAppID = -1, info.uid = 10175, packageName = com.test.thalitest
I/AASA_removePackage( 1018): UID=10175 Target=com.test.thalitest
I/ActivityManager( 1018): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7489 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/TimaKeyStoreProvider( 7489): TimaSignature is unavailable
D/ActivityThread( 7489): Added TimaKeyStore provider
D/PackageManager( 1018): result of delete: 1{975481780}
E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7393): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
D/SLinkSource( 7393): Samsung link source created
D/PersonaManager( 1018): isKioskContainerExistOnDevice
D/AndroidRuntime( 7363): Shutting down VM
D/ActivityManager( 1018): startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
D/BadgeProvider( 7425): sendNotify entered. [uri] : content://com.sec.badge/apps
D/BadgeProvider( 7425): sendNotify, [notify] : null
D/BadgeProvider( 7425): update, [uri] : content://com.sec.badge/apps
D/BadgeProvider( 7425): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 7425): update, [UpdateCount] : 1
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1018): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=7506 uid=10156 gids={50156, 9997} abi=armeabi-v7a
E/Zygote  ( 7506): MountEmulatedStorage()
I/libpersona( 7506): KNOX_SDCARD checking this for 10156
E/Zygote  ( 7506): v2
I/libpersona( 7506): KNOX_SDCARD not a persona
I/SELinux ( 7506): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 7506): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
W/ResourceType( 1018): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
E/SELinux ( 7506): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/TimaKeyStoreProvider( 7506): TimaSignature is unavailable
W/ResourcesManager( 1018): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
I/PCWCLIENTTRACE_LOG( 7489): DEFAULT_LOGON : true
W/ResourcesManager( 1018): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/PCWCLIENTTRACE_LOG( 7489): DEFAULT_LOGLEVEL : 3
W/ResourcesManager( 1018): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/ActivityThread( 7506): Added TimaKeyStore provider
W/ContextImpl( 7475): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
I/PCWCLIENTTRACE_DMDBOpenHelper( 7489): new DMDBOpenHelper instance
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ActivityManager( 1018): startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/PCWCLIENTTRACE_PushUtil( 7489): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7489): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7489): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7489): [onReceive] - android.intent.action.PACKAGE_REMOVED
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/Zygote  ( 7524): MountEmulatedStorage()
E/Zygote  ( 7524): v2
I/libpersona( 7524): KNOX_SDCARD checking this for 1000
I/libpersona( 7524): KNOX_SDCARD not a persona
I/SELinux ( 7524): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/SELinux ( 7524): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 7524): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/ActivityManager( 1018): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=7524 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
I/ActivityManager( 1018): Killing 5821:com.sec.spp.push/u0a35 (adj 15): empty for 1803s
I/CrashAnrDetector( 1018): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager( 1018): clearDefaults: com.test.thalitest
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
W/libprocessgroup( 1018): failed to open /acct/uid_10009/pid_6254/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10041/pid_5995/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10004/pid_5620/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10104/pid_6205/cgroup.procs: No such file or directory
D/TimaKeyStoreProvider( 7524): TimaSignature is unavailable
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0

```
